#### Test 81418577c146d2e_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 08:18:08.841  3870  3982 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 08:18:08.843  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-16 08:18:08.849  6736  6736 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 08:18:10.572  6847  6847 D AndroidRuntime: 
08-16 08:18:10.572  6847  6847 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 08:18:10.576  6847  6847 D AndroidRuntime: CheckJNI is OFF
08-16 08:18:10.783  6847  6847 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 08:18:10.794  1036  2053 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 08:18:10.808  1943  1961 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 08:18:10.815  1036  2053 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 08:18:10.816  1036  2053 D ActivityManager: setTaskToReturnTo : TaskRecord{2dd62bca #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 08:18:10.817  1036  2053 D ActivityManager: setTaskToReturnTo : TaskRecord{2dd62bca #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 08:18:10.818  1036  2053 D WindowStateEx: AppWindowTokenEx init.. 
08-16 08:18:10.819   342   354 E GBMv2   : DFP En is all cleared set to be enabled
08-16 08:18:10.849  1036  2053 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6862 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 08:18:10.852  6847  6847 D AndroidRuntime: Shutting down VM
08-16 08:18:10.909  1943  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 08:18:10.910  1943  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16b51a86 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 08:18:10.912  1943  3968 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 08:18:10.912  1943  3968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{22d54f47 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 08:18:10.986  6862  6862 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-16 08:18:11.075  6862  6862 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 08:18:11.084  6862  6862 I LibraryLoader: Loading: webviewchromium
08-16 08:18:11.087  6862  6862 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 641-645)
,08-16 08:18:11.087  6862  6862 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 08:18:11.105  6862  6862 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d862024}
,08-16 08:18:11.106  6862  6862 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 08:18:11.106  6862  6862 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 08:18:11.116  6862  6862 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 08:18:11.117  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 08:18:11.127  6862  6862 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 08:18:11.128  6862  6862 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 08:18:11.128  6862  6862 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 08:18:11.133   322  2144 V AudioPolicyService: registerClient() client 0xb558ad60, uid 10118
,08-16 08:18:11.137  1036  1118 D BluetoothManagerService: Message: 20
08-16 08:18:11.137  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fe95a04:true
08-16 08:18:11.147  6862  6862 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:11.147  6862  6862 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:11.147  6862  6862 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:11.147  6862  6862 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:11.147  6862  6862 I Adreno-EGL: Remote Branch: 
08-16 08:18:11.147  6862  6862 I Adreno-EGL: Local Patches: 
08-16 08:18:11.147  6862  6862 I Adreno-EGL: Reconstruct Branch: 
,08-16 08:18:11.228  6862  6897 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-16 08:18:11.229  6862  6862 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-16 08:18:11.252  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 08:18:11.257  6862  6862 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 08:18:11.260  6862  6862 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 08:18:11.263  6862  6862 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 08:18:11.263  6862  6862 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 08:18:11.276  6862  6862 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 08:18:11.283  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 08:18:11.283  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 08:18:11.305  6862  6909 D OpenGLRenderer: Render dirty regions requested: true
08-16 08:18:11.305  6862  6909 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 08:18:11.315  6862  6909 D OpenGLRenderer: Enabling debug mode 0
,08-16 08:18:11.326  6862  6862 D Atlas   : Validating map...
08-16 08:18:11.330  1036  1051 D SplitWindow: check instance of lgWin Window{b0fe71e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 08:18:11.391  6862  6907 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:11.391  6862  6907 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:11.443  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +540ms (total +623ms)
08-16 08:18:11.444  6862  6862 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3cd73543 time:191003
08-16 08:18:11.445  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2dc4613b u0 com.test.thalitest/.MainActivity t6} time:191003
,08-16 08:18:11.544  6862  6862 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 08:18:11.574  6862  6862 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 08:18:11.574  6862  6862 I chromium: 
,08-16 08:18:11.696  6862  6920 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435164160
,08-16 08:18:11.714  6862  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 08:18:11.714  6862  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 08:18:11.714  6862  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 08:18:11.714  6862  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 08:18:11.714  6862  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 08:18:11.715  6862  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d338697 added. We now have 1 listener(s)
08-16 08:18:11.729  1036  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:11.735  6862  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-16 08:18:11.737  6862  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:11.738  6862  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:11.739  6862  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 08:18:11.746  6862  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b0434a2 added. We now have 1 listener(s)
08-16 08:18:11.747  6862  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:18:11.753  1036  1506 D WifiService: New client listening to asynchronous messages
08-16 08:18:11.756  6862  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:18:11.756  6862  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 08:18:11.757  6862  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 08:18:11.757  6862  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 08:18:11.757  6862  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 08:18:11.761  6862  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:18:11.764  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:11.765  6862  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 08:18:11.773  6862  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:11.774  6862  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:11.774  6862  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 08:18:11.774  6862  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:11.775  6862  6920 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 08:18:11.776  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:11.778  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:11.814  6862  6907 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 08:18:11.814  6862  6907 I chromium: 
,08-16 08:18:11.884  6862  6862 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 08:18:12.374   342   356 E GBMv2   : DFP En is all cleared set to be enabled
08-16 08:18:12.374   342   356 E GBMv2   : Set value is all cleared set the max
08-16 08:18:12.374   342   356 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 08:18:12.687  6862  6923 W jxcore-log: Initializing JXcore engine
08-16 08:18:12.688  6862  6923 W jxcore-log: JXcore engine is ready
,08-16 08:18:12.771  6923  6923 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6104]" dev="sockfs" ino=6104 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-16 08:18:12.771  6923  6923 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 08:18:12.771  6923  6923 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10348]" dev="sockfs" ino=10348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 08:18:12.771  6923  6923 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 08:18:12.771  6923  6923 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33175]" dev="sockfs" ino=33175 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-16 08:18:12.808  6862  6923 W jxcore-log: Starting JXcore engine
,08-16 08:18:12.931  6862  6923 W jxcore-log: Platform android
08-16 08:18:12.931  6862  6923 W jxcore-log: 
08-16 08:18:12.931  6862  6923 W jxcore-log: Process ARCH arm
08-16 08:18:12.931  6862  6923 W jxcore-log: 
,08-16 08:18:13.111  6862  6923 I jxcore-log: JXcore Cordova bridge is ready!
08-16 08:18:13.111  6862  6923 I jxcore-log: 
08-16 08:18:13.112  6862  6923 W jxcore-log: JXcore engine is started
,08-16 08:18:13.117  6862  6920 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 08:18:13.120  6862  6862 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 08:18:24.372  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 08:18:24.372  6862  6923 I jxcore-log: 
,08-16 08:18:24.374  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 08:18:24.374  6862  6923 I jxcore-log: 
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:24.379  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:24.381  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.383  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 08:18:24.383  6862  6923 I jxcore-log: 
08-16 08:18:24.385  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 08:18:24.385  6862  6923 I jxcore-log: 
,08-16 08:18:24.706  6862  6923 D ExecuteNativeTests: Running unit tests
,08-16 08:18:24.787  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-16 08:18:24.788  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 added. We now have 2 listener(s)
08-16 08:18:24.788  1036  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 08:18:24.790  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:24.790  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:24.790  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 08:18:24.790  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:24.790  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a added. We now have 2 listener(s)
08-16 08:18:24.790  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:18:24.791  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:18:24.794  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:24.798  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:24.799  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.799  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:24.800  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:24.801  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:24.805  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 08:18:24.805  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 08:18:24.805  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 08:18:24.806  6862  6923 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 08:18:24.810  6862  6923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 08:18:24.810  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 08:18:24.811  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:18:24.812  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:18:24.814  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.816  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.817  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 08:18:24.824  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.824  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.824  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:24.824  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:24.825  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 removed from the list
08-16 08:18:24.825  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.825  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a removed from the list
08-16 08:18:24.825  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.825  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.825  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.825  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.826  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.826  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.826  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.826  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.827  6862  6923 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 08:18:24.828  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.828  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.828  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.828  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.828  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.828  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.828  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.828  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.828  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.828  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.828  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.828  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08,-16 08:18:24.828  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.828  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:18:24.829  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.829  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.829  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.829  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 08:18:24.833  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 08:18:24.834  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 08:18:24.834  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.834  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.834  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.835  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.835  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.835  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.835  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.835  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.835  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.835  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.835  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.835  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.835  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.835  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.836  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.836  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.836  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.836  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.836  6862  6923 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 08:18:24.838  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:24,.840  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:24.840  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:24.840  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:24.840  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:24.840  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:24.840  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.840  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:24.840  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:18:24.843  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.843  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:24.844  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:24.844  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:24.845  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:18:24.845  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:18:24.845  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:24.845  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:18:24.846  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:24.848  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:18:24.849  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:24.854  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 08:18:24.861  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 08:18:24.863  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 08:18:24.863  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:18:24.864  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:24.865  6862  6923 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 08:18:24.865  6862  6923 I io.jxcore.node.ConnectionHelper: start: OK
08-16 08:18:24.867  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.867  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.867  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 08:18:24.869  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.869  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.869  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:24.869  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.869  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.869  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.869  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.869  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.869  6862  6923 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 08:18:24.870  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:24.872  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:24.873  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.873  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:24.873  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:24.874  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:18:24.874  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:18:24.874  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:24.874  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:18:24.875  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:24.876  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:24.877  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:18:24.878  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:24.879  6862  6923 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 08:18:24.879  6862  6,923 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 08:18:24.881  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.881  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.881  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.882  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.882  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.882  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:24.882  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.882  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.882  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.882  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.882  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.882  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.882  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.883  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.883  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.885  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.885  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.885  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.885  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.886  6862  6923 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 08:18:24.887  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:24.889  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:24.891  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:24.891  6862  6923 D io.jxcore.node.ConnectivityM,onitor: start: OK
08-16 08:18:24.892  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:24.892  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:18:24.892  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:18:24.892  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:24.892  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:18:24.894  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:24.895  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:24.896  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:18:24.897  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:24.897  6862  6923 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 08:18:24.898  6862  6923 I io.jxcore.node.ConnectionHelper: start: OK
08-16 08:18:24.898  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.898  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.898  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.898  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.898  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.898  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.899  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.899  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.899  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:24.899  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.899  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.899  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.899  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.899  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.899  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.899  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.900  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.900  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.900  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.900  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.900  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.900  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.901  6862  6923 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 08:18:24.901  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.901  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.901  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.901  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.901  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.901  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.901  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.901  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.901  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.901  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.901  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.901  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.901  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.901  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.902  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.902  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.903  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.903  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.903  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.903  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.905  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 08:18:24.905  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.905  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.906  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.906  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.906  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.906  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.906  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.906  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.906  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.906  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.906  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.906  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.906  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.906  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.906  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.906  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.907  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.907  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.907  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.907  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.907  6862  6923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 08:18:24.907  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.907  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.907  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.908  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.908  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.908  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.908  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.908  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.908  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.908  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.908  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.908  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.908  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.908  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.908  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.908  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.909  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.909  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.909  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.909  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.909  6862  6923 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 08:18:24.909  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.909  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.909  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.910  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.910  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.910  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.910  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.910  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.910  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.910  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.910  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.910  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.910  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.910  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.910  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.910  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.911  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.911  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.911  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.911  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.911  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 08:18:24.911  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 08:18:24.911  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 08:18:24.911  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:18:24.911  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 08:18:24.911  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 08:18:24.911  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.911  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.911  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.912  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.912  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.912  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.912  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.912  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.912  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.912  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.912  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.912  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.912  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.912  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.913  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.913  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.914  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.914  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.914  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.914  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.914  6862  6923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:18:24.915  6862  6923 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 08:18:24.915  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 08:18:24.916  6862  6923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:18:24.916  6862  6923 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 08:18:24.916  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 08:18:24.916  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 08:18:24.917  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 08:18:24.917  6862  6923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 08:18:24.917  6862  6923 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 08:18:24.917  6862  6923 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 08:18:24.918  6862  6923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:18:24.918  6862  6923 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 08:18:24.918  6862  6923 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 08:18:24.918  6862  6923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:18:24.918  6862  6923 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 08:18:24.918  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 08:18:24.921  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 08:18:24.926  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 08:18:24.926  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 08:18:24.928  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 08:18:24.928  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-16 08:18:24.931  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 08:18:24.931  6862  6923 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 08:18:24.931  6862  6923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:18:24.931  6862  6923 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 08:18:24.932  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.932  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.932  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.932  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.932  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.933  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.933  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 08:18:24.934  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.934  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.934  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.935  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.936  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.936  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.936  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.936  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.937  6862  6942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-16 08:18:24.937  6862  6942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-16 08:18:24.937  6862  6942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
08-16 08:18:24.937  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.937  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.938  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.938  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.938  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.938  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.938  6862  6923 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 08:18:24.939  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.939  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.939  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.939  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.939  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.939  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.939  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.939  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.939  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.939  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.939  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.939  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.939  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.939  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.940  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.940  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.941  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.941  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.941  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.941  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.942  6862  6923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 08:18:24.942  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.942  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.942  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.943  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.943  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.943  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.943  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.943  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.943  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.943  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.943  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.943  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.943  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.943  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.946  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.946  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.948  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.948  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.948  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.948  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.950  6862  6923 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 08:18:24.950  6862  6923 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 08:18:24.950  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 08:18:24.951  6862  6923 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 08:18:24.951  6862  6923 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 08:18:24.951  6862  6923 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 08:18:24.951  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 08:18:24.951  6862  6923 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 08:18:24.951  6862  6923 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 08:18:24.951  6862  6923 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 08:18:24.951  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 08:18:24.951  6862  6923 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 08:18:24.951  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.951  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.951  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.952  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.952  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.952  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.952  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.952  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.952  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.952  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.952  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.952  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.952  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.952  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.953  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.954  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.954  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.954  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.954  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.954  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.955  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.955  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.955  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.955  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.955  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.955  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.955  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.955  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.955  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.956  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.956  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.956  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.956  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.956  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.956  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.956  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.956  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.956  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired, outcome of this operation, skipping...
08-16 08:18:24.956  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.956  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.956  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.956  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.956  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.956  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.956  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.956  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.956  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.956  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.956  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.957  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.957  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.957  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.957  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.957  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.957  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.958  6862  6923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 08:18:24.958  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:18:24.959  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 08:18:24.959  6862  6923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 08:18:24.959  6862  6923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 08:18:24.959  6862  6862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 08:18:24.960  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 08:18:24.960  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 08:18:24.960  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.960  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 08:18:24.960  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 08:18:24.960  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 08:18:24.961  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.961  6862  6923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 08:18:24.971  6862  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 08:18:24.971  6862  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 08:18:24.971  6862  6862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 08:18:24.971  6862  6862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 08:18:24.972  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.972  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.972  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 08:18:24.972  6862  6923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 08:18:24.972  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 08:18:24.973  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 08:18:24.973  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:24.973  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:24.973  6862  6923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 08:18:24.974  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.974  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.974  6862  6923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:18:24.975  6862  6862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:18:24.975  6862  6862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:18:24.975  6862  6862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:18:24.975  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.975  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.975  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.975  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.975  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.975  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.976  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.976  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.976  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.976  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.976  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.976  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.976  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.976  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.976  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.976  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.976  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.976  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.977  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.977  6862  6923 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 08:18:24.978  6862  6923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 08:18:24.978  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 08:18:24.979  6862  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:18:24.979  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.979  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.979  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.980  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.980  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.980  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.980  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.980  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.980  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.980  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.980  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.980  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.980  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.980  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.981  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.981  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.981  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.981  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.987  6862  6941 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 08:18:24.988  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-16 08:18:24.989  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:24.989  1036  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:24.990  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:24.990  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.990  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.990  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.990  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.990  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.990  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.991  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.991  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.991  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.991  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.991  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.991  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.991  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.991  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.992  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.992  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.992  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.992  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.992  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:24.992  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:24.992  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:24.992  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:24.992  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.992  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.992  6862  6923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b07a45 not in the list
08-16 08:18:24.992  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.992  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.992  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:24.992  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.992  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.992  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:24.992  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:24.993  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:24.993  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:24.993  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:24.993  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3459a not in the list
08-16 08:18:24.995  6862  6923 I io.jxcor,e.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 08:18:24.995  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 08:18:24.995  6862  6923 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 08:18:24.995  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 08:18:24.995  6862  6923 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 08:18:24.995  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 08:18:24.996  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 08:18:24.996  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 08:18:24.997  6862  6923 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 08:18:24.997  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 08:18:24.997  6862  6923 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 08:18:24.997  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 08:18:24.997  6862  6923 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 08:18:24.997  6862  6923 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 08:18:24.998  6862  6923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 08:18:24.998  6862  6923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 08:18:24.998  6862  6923 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 08:18:24.998  6862  6923 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 08:18:24.998  6862  6923 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 08:18:24.998  6862  6923 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 08:18:24.999  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:24.999  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cbd3c43 added. We now have 2 listener(s)
08-16 08:18:24.999  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:25.000  6862  6923 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 08:18:25.001  1036  1595 D WifiServiceImplEx: setWifiEnabled: true pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 08:18:25.001  1036  1595 D WifiService: setWifiEnabled: true pid=6862, uid=10118
08-16 08:18:25.001  1036  1595 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 08:18:25.002  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:25.002  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23c142c0 added. We now have 3 listener(s)
08-16 08:18:25.002  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:25.005  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:25.005  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c201bf9 added. We now have 4 listener(s)
,08-16 08:18:25.005  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:25.006  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:25.006  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3dc7f73e added. We now have 5 listener(s)
08-16 08:18:25.006  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:18:25.007  1036  1595 D WifiServiceImplEx: setWifiEnabled: false pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 08:18:25.007  1036  1595 D WifiService: setWifiEnabled: false pid=6862, uid=10118
08-16 08:18:25.008  1036  1595 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 08:18:25.016  1036  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:25.016  1036  2053 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@16607e39 mBinding = false
08-16 08:18:25.017  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 08:18:25.017  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 08:18:25.017  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-16 08:18:25.019  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:25.019  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:25.020  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:25.020  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:25.021  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:25.021  1036  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 08:18:25.021  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:18:25.021  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 08:18:25.021  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 08:18:25.021  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 08:18:25.026  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 08:18:25.026  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 08:18:25.026  2715  2715 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 08:18:25.026  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 08:18:25.026  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 08:18:25.026  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.026  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.026  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:25.027   317   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 08:18:25.031  1036  2865 D DhcpStateMachine: RunningState{ when=-5ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:25.033  1036  1118 D BluetoothManagerService: Message: 2
08-16 08:18:25.035  1036  1118 D BluetoothManagerService: Sending off request.
08-16 08:18:25.035  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 08:18:25.035  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 08:18:25.035  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 08:18:25.037  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:25.037  3870  4185 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:25.038  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:25.039  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:25.039  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:25.040  3870  3946 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 08:18:25.040  3870  3946 D BluetoothAdapterProperties: Setting state to 13
08-16 08:18:25.040  3870  3946 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 08:18:25.041  3870  3946 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 08:18:25.041  3870  3946 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 08:18:25.041  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:25.041  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 08:18:25.041  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 08:18:25.043  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:25.043  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:25.044  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will r,eturn stored value
08-16 08:18:25.044  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:18:25.046  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:25.047  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 08:18:25.047  3870  3870 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:25.048  3870  3870 D BluetoothMapService: STATE_TURNING_OFF
08-16 08:18:25.048  3870  3870 V BtOppService: Receiver DISABLED_ACTION 
08-16 08:18:25.051  3870  3870 V BluetoothMapService: Handler(): got msg=4
08-16 08:18:25.051  3870  3870 D BluetoothMapService: MAP Service closeService in
08-16 08:18:25.051  3870  3870 D BluetoothMapMasInstance: MAP Service shutdown
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 08:18:25.052  3870  4194 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 08:18:25.052  3870  3870 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 08:18:25.052  3870  3870 V BluetoothMapService: MAP Service closeService out
08-16 08:18:25.052  3870  3870 I BtOppRfcommListener: stopping Accept Thread
08-16 08:18:25.052  3870  3870 V BtOppRfcommListener: close mBtServerSocket
08-16 08:18:25.052  3870  3870 V BtOppRfcommListener: waiting for thread to terminate
08-16 08:18:25.054  3870  4230 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:25.054  3870  4230 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 08:18:25.054  3870  3870 V BtOppRfcommListener: done waiting for thread to terminate
,08-16 08:18:25.063  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 08:18:25.063  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 08:18:25.065  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:25.065  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:25.070  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.070  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:25.072  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:25.072  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:18:25.073  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.073  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:25.074  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:25.074  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:25.081  1036  1114 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6953 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 08:18:25.082  3870  3870 V BtOppService: onDestroy
08-16 08:18:25.083  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.083  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.084  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.084  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.084  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.084  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.085  1036  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 08:18:25.085  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.085  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.085  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:25.086  1036  1391 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.086  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.086  1036  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@26ebd162
08-16 08:18:25.086  1036  1391 D LGWifiP2pService: P2pDisablingState
08-16 08:18:25.086  1036  1391 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.086  1036  1391 D LGWifiP2pService: p2p socket connection lost
08-16 08:18:25.086  1036  1391 D LGWifiP2pService: P2pDisabledState
,08-16 08:18:25.087  3870  3870 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 08:18:25.089  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 08:18:25.090  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 08:18:25.091  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:25.091  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:25.091  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:25.091  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 08:18:25.092  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 08:18:25.092  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.092  1036  1391 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.092  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 08:18:25.092  2715  2715 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 08:18:25.094  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:25.094  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:25.094  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:25.095  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 08:18:25.095  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-16 08:18:25.095  1036  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.097  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 08:18:25.097  1943  1943 D WfdsService: WifiP2pState is changed : false
08-16 08:18:25.097  1943  2385 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 08:18:25.097  1943  2385 D WfdsService: Set the WFDS Monitor: false
08-16 08:18:25.098  1943  2385 D WfdsMonitor: WFDS Monitor is stopped
,08-16 08:18:25.098  1943  2385 D WfdsService: STATE : WfdsDisabledState - enter
08-16 08:18:25.098  1943  2771 D CtrlSupplicant: Received on exit socket, terminate
,08-16 08:18:25.098  1943  2771 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 08:18:25.098  1943  2771 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 08:18:25.098  1943  2771 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 08:18:25.099  1943  2385 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 08:18:25.099  1943  2386 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 08:18:25.100  1036  1558 D WifiScanningService: DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.111  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 08:18:25.111  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 08:18:25.111  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:25.114  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:25.114  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:25.115  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.116  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:25.122  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:25.122  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:25.125  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.139   317   894 D CommandListener: Clearing all IP addresses on wlan0
,08-16 08:18:25.140  1036  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 08:18:25.140  1036  1527 D DSQN    : disableDataServiceNotify
08-16 08:18:25.140  1036  1527 D DSQN    : stop dsqn bin
08-16 08:18:25.145  1036  1973 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6976 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 08:18:25.146  1036  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 08:18:25.146  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:25.146  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:25.146  1036  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:25.147  1036  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 08:18:25.147  1036  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.147  1036  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:25.147  1036  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 08:18:25.148  1604  1836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 08:18:25.148  1036  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 08:18:25.148  1036  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 08:18:25.148  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 08:18:25.148  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 08:18:25.148  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:25.148  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:25.148  1036  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:25.148  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:25.149  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 08:18:25.149  1036  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:25.149  1036  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:25.149 , 1036  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:25.149  1036  1527 D NetworkManagementService: Removing idletimer
08-16 08:18:25.149  1036  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:25.150  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:25.150  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 08:18:25.151  1036  1440 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 08:18:25.151  1036  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 08:18:25.151  1036  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 08:18:25.151  1036  1440 D WifiNative-p2p0: TERMINATE: returned true
08-16 08:18:25.151  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 08:18:25.151  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:25.151  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:25.151  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 08:18:25.152  1036  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:25.152  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:25.152  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 08:18:25.154  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 08:18:25.154  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 08:18:25.156  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.157  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:25.157  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:25.158  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.158  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:25.161  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:25.161  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:25.168  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:18:25.168  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:25.178  6953  6953 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 08:18:25.178  6953  6953 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 08:18:25.178  6953  6953 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:25.178  6953  6953 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 08:18:25.179  6953  6953 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 08:18:25.179  6953  6953 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 08:18:25.188  1036  1938 I art     : Explicit concurrent mark sweep GC freed 35917(1737KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.335ms total 146.470ms
08-16 08:18:25.189  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 08:18:25.190  1036  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 08:18:25.195  3870  3951 D BluetoothAdapterProperties: Scan Mode:20
,08-16 08:18:25.196  3870  3946 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 08:18:25.196  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 08:18:25.196  3870  4026 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 08:18:25.196  3870  3946 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 08:18:25.197  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 08:18:25.197  3870  4026 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 08:18:25.197  3870  4195 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:25.197  3870  4235 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:25.198  3870  4237 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:25.198  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 08:18:25.198  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:25.198  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 08:18:25.198  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 08:18:25.198  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 08:18:25.198  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 08:18:25.198  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 08:18:25.198  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 08:18:25.198  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 08:18:25.203  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16, 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:25.203  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:25.206  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:25.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:18:25.220  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 08:18:25.221  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.221  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:25.234  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 08:18:25.234  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.235  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.235  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.247  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 08:18:25.250  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:25.250  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:25.251  1036  1997 I ActivityManager: Killing 6288:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 08:18:25.253  2715  2715 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 08:18:25.253  2715  2715 I wpa_supplicant: monitor socket send errors count : 1
08-16 08:18:25.253  2715  2715 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-16 08:18:25.254  1036  2769 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 08:18:25.254  1036  2769 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 08:18:25.263  1036  2865 D DhcpStateMachine: StoppedState
08-16 08:18:25.263  1036  2865 D DhcpStateMachine: StoppedState{ when=-151ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:25.273  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 08:18:25.273  1036  2053 W libprocessgroup: failed to open /acct/uid_10014/pid_6288/cgroup.procs: No such file or directory
08-16 08:18:25.273  1036  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-16 08:18:25.291  2715  2715 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 08:18:25.292  2715  2715 W wpa_supplicant: USIM:  scard_deinit function
,08-16 08:18:25.292  1036  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 08:18:25.292  1036  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 08:18:25.292  1036  2769 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 08:18:25.292  1036  2769 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 08:18:25.293  1036  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:25.293  1036  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:25.293  1036  1118 D Tethering: InitialState.processMessage what=4
08-16 08:18:25.294  1036  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=204839
08-16 08:18:25.294  1036  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=204839
08-16 08:18:25.294  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 08:18:25.294  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=204840  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 08:18:25.295  1036  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=204840  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 08:18:25.295  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:25.295  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:25.330  6953  6953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 08:18:25.338  3870  3870 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 08:18:25.338  3870  3870 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:18:25.338  3870  3870 V BluetoothPbapReceiver: ***********state = 13
08-16 08:18:25.341  3870  3870 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 08:18:25.342  3870  3870 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:25.342  3870  3870 V BluetoothPbapService: state: 13
08-16 08:18:25.343  3870  3870 V BluetoothPbapService: Pbap Service closeService in
08-16 08:18:25.343  3870  3870 V BluetoothPbapService: successfully stopped pbap service
08-16 08:18:25.343  3870  3870 V BluetoothPbapService: Pbap Service closeService out
08-16 08:18:25.343  3870  3870 V BluetoothPbapService: Pbap Service onDestroy
,08-16 08:18:25.344  3870  3870 V BluetoothPbapService: Pbap Service closeService in
08-16 08:18:25.344  3870  3870 V BluetoothPbapService: Pbap Service closeService out
08-16 08:18:25.344  3870  3870 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 08:18:25.346  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 08:18:25.359  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:25.396  1036  1051 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7003 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 08:18:25.400  6953  6953 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:25.400  6953  6953 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 08:18:25.402  2715  2715 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 08:18:25.405  1036  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 08:18:25.405  1036  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 08:18:25.405  1036  2769 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 08:18:25.406  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-16 08:18:25.416  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:25.430  1036  1118 D BluetoothManagerService: Message: 20
08-16 08:18:25.430  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4db40fb:true
,08-16 08:18:25.444  1036  1118 D BluetoothManagerService: Message: 30
,08-16 08:18:25.449  1036  1118 D BluetoothManagerService: Message: 30
08-16 08:18:25.451  6953  6953 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 08:18:25.453  6953  6953 D BluetoothMap: Create BluetoothMap proxy object
08-16 08:18:25.454  1036  1118 D BluetoothManagerService: Message: 30
,08-16 08:18:25.461  1036  1118 D BluetoothManagerService: Message: 30
08-16 08:18:25.463  6953  6953 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 08:18:25.464  6953  6953 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 08:18:25.476  6862  6862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 08:18:25.482  6953  6953 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 08:18:25.486  6953  6953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 08:18:25.499  6953  6953 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:18:25.508  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-16 08:18:25.508  1943  2385 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-16 08:18:25.508  1943  2385 D WfdsService: Set the WFDS Monitor: false
08-16 08:18:25.508  1943  2385 D WfdsMonitor: WFDS Monitor is stopped
08-16 08:18:25.508  1036  1440 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 08:18:25.508  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:25.508  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:25.508  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 08:18:25.510  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 08:18:25.511  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:25.516  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 08:18:25.516  1036  1473 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 08:18:25.516  1036  1473 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 08:18:25.517  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:18:25.520  6953  6953 D BluetoothInputDevice: Proxy object connected
08-16 08:18:25.521  6953  6953 D HidProfile: Bluetooth service connected
08-16 08:18:25.522  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:25.523  6953  6953 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 08:18:25.523  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:25.524  6953  6953 D PanProfile: Bluetooth service connected
08-16 08:18:25.525  6953  6953 D BluetoothMap: Proxy object connected
08-16 08:18:25.525  6953  6953 D MapProfile: Bluetooth service connected
08-16 08:18:25.525  6953  6953 D BluetoothMap: getConnectedDevices()
08-16 08:18:25.526  6953  6953 D BluetoothMap: Bluetooth is Not enabled
08-16 08:18:25.527  6953  6953 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 08:18:25.567  1036  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7027 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 08:18:25.570  1036  1051 I ActivityManager: Killing 6398:com.android.defcontainer/u0a4 (adj 15): empty #17
08-16 08:18:25.591   364   364 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 20.374ms
,08-16 08:18:25.611   364   364 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 19.835ms
,08-16 08:18:25.643   364   364 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 629us total 29.347ms
,08-16 08:18:25.705  1036  2034 W libprocessgroup: failed to open /acct/uid_10004/pid_6398/cgroup.procs: No such file or directory
,08-16 08:18:25.725  7003  7003 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 08:18:25.727  7003  7003 W LG Account v2.2: No ProfileInfo entries
08-16 08:18:25.727  7003  7003 I LG Account v2.2: isEnabled: false
08-16 08:18:25.727  7003  7003 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 08:18:25.728  7003  7003 I Feature : [Lifetracker]Country: EU
08-16 08:18:25.728  7003  7003 I Feature : [Lifetracker]Operator: OPEN
08-16 08:18:25.728  7003  7003 I Feature : [Lifetracker]Ranking support: false
08-16 08:18:25.728  7003  7003 I Feature : [Lifetracker]Comfort support: false
08-16 08:18:25.728  7003  7003 I Feature : [Lifetracker]Accessory: true
08-16 08:18:25.729  7003  7003 I Feature : [Lifetracker]Health device: true
08-16 08:18:25.729  7003  7003 I Feature : [Lifetracker]Extra Pedometer: false
08-16 08:18:25.729  7003  7003 I Feature : [Lifetracker]Blood glucose device: false
08-16 08:18:25.729  7003  7003 I Feature : [Lifetracker]Device Number: 3
08-16 08:18:25.746  6953  6953 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 08:18:25.746  7027  7027 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 08:18:25.752  6953  6953 D BluetoothPermissionRequest: onReceive,
08-16 08:18:25.757  6953  6953 D LGBluetoothAuthorization: [BTUI] cancel All Notification,
,08-16 08:18:25.770  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:25.772  1036  1938 I ActivityManager: Killing 6562:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-16 08:18:25.866  3870  3870 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 08:18:25.867  3870  3870 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 08:18:25.867  1036  1997 W libprocessgroup: failed to open /acct/uid_10008/pid_6562/cgroup.procs: No such file or directory
08-16 08:18:25.870  3870  3870 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 08:18:25.880  7027  7027 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 08:18:25.884  3870  3870 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:25.884  3870  3870 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 08:18:25.892  3870  3870 V BluetoothFtpService: Ftp Service onStartCommand
,08-16 08:18:25.892  3870  3870 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:25.893  3870  3870 V BluetoothFtpService: Ftp Service closeService
08-16 08:18:25.893  3870  3870 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 08:18:25.894  3870  3870 V BluetoothFtpService: successfully stopped ftp service
08-16 08:18:25.895  3870  3870 V BluetoothFtpService: Ftp Service onDestroy
08-16 08:18:25.895  3870  3870 V BluetoothFtpService: Ftp Service closeService
08-16 08:18:25.902  3870  3870 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-16 08:18:25.903  3870  3870 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:25.903  3870  3870 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:25.903  3870  3870 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:25.903  3870  3870 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 08:18:25.903  3870  3870 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 08:18:25.906  3870  3870 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:25.906  3870  3870 V BluetoothSapService: state: 13
08-16 08:18:25.906  3870  3870 V BluetoothSapService: Stopping SAP server process
,08-16 08:18:25.909  3870  3870 V BluetoothSapService: Sap Service closeSapService in
08-16 08:18:25.910  3870  3870 V BluetoothSapService: Close listen Socket : 
08-16 08:18:25.910  3870  3870 V BluetoothSapService: Close rfcomm Socket : 
08-16 08:18:25.910  3870  3870 V BluetoothSapService: Close sapd  Socket : 
08-16 08:18:25.928  7027  7027 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 08:18:25.928  7027  7027 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-16 08:18:25.929  7027  7027 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 08:18:25.929  7027  7027 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 08:18:25.929  7027  7027 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 08:18:25.932  7027  7027 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 08:18:25.938  7027  7027 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 08:18:25.960  1036  1938 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7046 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 08:18:25.961  3870  3870 V BluetoothSapService: Sap Service closeSapService out
08-16 08:18:25.962  3870  3870 V BluetoothSapService: Sap Service onDestroy
08-16 08:18:25.962  3870  3870 V BluetoothSapService: Sap Service closeSapService in
08-16 08:18:25.962  3870  3870 V BluetoothSapService: Close listen Socket : 
08-16 08:18:25.962  3870  3870 V BluetoothSapService: Close rfcomm Socket : 
08-16 08:18:25.962  3870  3870 V BluetoothSapService: Close sapd  Socket : 
08-16 08:18:25.963  3870  3870 V BluetoothSapService: Sap Service closeSapService out
,08-16 08:18:25.969  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:25.971  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:25.991  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 08:18:25.994  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:25.995  7027  7027 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 08:18:25.997  7027  7027 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 08:18:26.000  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 08:18:26.000  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:26.000  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:26.005  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:26.012  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:26.019  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 08:18:26.019  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 08:18:26.021  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 08:18:26.025  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:26.030  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 08:18:26.030  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:26.030  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 08:18:26.034  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:26.045  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:26.054  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:26.054  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:26.056  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 08:18:26.061  7046  7046 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:26.110  1036  1051 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7066 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 08:18:26.113  1036  1051 I ActivityManager: Killing 6084:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 08:18:26.153  1036  1738 W libprocessgroup: failed to open /acct/uid_10011/pid_6084/cgroup.procs: No such file or directory
,08-16 08:18:26.199  3870  4026 W bt-btif : ag scb idx 1 not allocated
08-16 08:18:26.199  3870  3951 D bt_hci_bdroid: cleanup
08-16 08:18:26.199  3870  4032 I bt_lpm  : LPM is already off!!!
08-16 08:18:26.199  3870  4026 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 08:18:26.199  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:26.199  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:26.200  3870  4146 I bt_userial_mct: exiting userial_read_thread
08-16 08:18:26.200  3870  4146 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 08:18:26.200  3870  3951 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 08:18:26.200  3870  4032 I bt_vendor: hw_epilog_process
,08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:26.201  3870  3951 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:26.201  3870  3951 D bt_userial_mct: userial_close
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:26.201  3870  3951 E bt_userial_mct: pthread_join() FAILED result:3
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:26.201  3870  3951 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:26.201  3870  4026 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:26.201  3870  4026 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 08:18:26.215  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 08:18:26.220  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 08:18:26.226  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:26.256  7066  7086 W FormManager: Network not available. Please check & try again.
,08-16 08:18:26.260  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 08:18:26.261  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 08:18:26.261  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 08:18:26.262  6953  6953 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 08:18:26.266  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 08:18:26.273  7066  7087 V FormManager: Network unavailable.
,08-16 08:18:26.275  7066  7087 V FormManager: Network unavailable.
08-16 08:18:26.280  3870  3951 D bt_hci_bdroid: set_power 0
08-16 08:18:26.280  3870  3951 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 08:18:26.280  3870  3951 I bt_vendor: bluetooth satus is on
08-16 08:18:26.280  3870  3951 I bt_vendor: bt-vendor : resetting BT status
08-16 08:18:26.280  3870  3951 I bt_vendor: Starting hciattach daemon
08-16 08:18:26.280  3870  3951 I bt_vendor: try to set false
08-16 08:18:26.282  3870  3951 I bt_vendor: Starting hciattach daemon
08-16 08:18:26.282  3870  3951 I bt_vendor: try to set false
08-16 08:18:26.283  3870  3951 I bt_vendor: cleanup
08-16 08:18:26.284  3870  4026 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 08:18:26.284  3870  3951 I GKI_LINUX: GKI_exit_task 0 done
08-16 08:18:26.284  3870  3951 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 08:18:26.285  6953  6953 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 08:18:26.285  3870  3946 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 08:18:26.285  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 08:18:26.285  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 08:18:26.286  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 08:18:26.286  6953  6953 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 08:18:26.287  6953  6953 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 08:18:26.288  3870  3870 D HeadsetService: Received stop request...Stopping profile...
,08-16 08:18:26.290  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:26.291  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:26.292  3870  3870 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 08:18:26.292  3870  3982 D HeadsetStateMachine: Exit Disconnected: -1
08-16 08:18:26.292  3870  3870 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 08:18:26.292  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fbed78d
08-16 08:18:26.293  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:26.293  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 08:18:26.294  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:26.294  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:26.295  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:26.295  1036  1953 I ActivityManager: Killing 6104:com.android.contacts/u0a19 (adj 15): empty #17
08-16 08:18:26.295  3870  3870 D A2dpService: Received stop request...Stopping profile...
08-16 08:18:26.297  3870  3870 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 08:18:26.297  3870  4016 D A2dpStateMachine: Exit Disconnected: -1
08-16 08:18:26.299  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 08:18:26.327  1036  2036 W libprocessgroup: failed to open /acct/uid_10019/pid_6104/cgroup.procs: No such file or directory
,08-16 08:18:26.327  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:26.331  3870  3946 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 08:18:26.332  3870  3870 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 08:18:26.332  3870  3870 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 08:18:26.332  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fbed78d
08-16 08:18:26.334  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-16 08:18:26.334  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 08:18:26.334  3870  3870 D HidService: Received stop request...Stopping profile...
08-16 08:18:26.334  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fbed78d
08-16 08:18:26.336  3870  3870 D HealthService: Received stop request...Stopping profile...
08-16 08:18:26.336  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fbed78d
08-16 08:18:26.338  4349  7093 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 08:18:26.340  6953  6953 D BluetoothInputDevice: Proxy object disconnected
08-16 08:18:26.340  6953  6953 D HidProfile: Bluetooth service disconnected
08-16 08:18:26.340  4349  7094 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:26.341  4349  7094 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 08:18:26.342  3870  3870 D PanService: Received stop request...Stopping profile...
,08-16 08:18:26.342  6976  6976 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 08:18:26.342  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:26.342  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:26.343  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fbed78d
08-16 08:18:26.346  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 08:18:26.348  3870  3870 D HeadsetStateMachine: Unbinding service...
08-16 08:18:26.349  3870  3870 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 08:18:26.349  3870  3870 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 08:18:26.349  3870  3870 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 08:18:26.349  3870  3870 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 08:18:26.349  3870  3870 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 08:18:26.349  3870  3870 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 08:18:26.349  3870  3870 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 08:18:26.350  3870  3870 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 08:18:26.351  3870  3870 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 08:18:26.351  3870  3870 D BtGatt.GattService: stop()
08-16 08:18:26.351  3870  3870 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 08:18:26.354  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fbed78d
,08-16 08:18:26.357  3870  3870 D BluetoothMapService: Received stop request...Stopping profile...
08-16 08:18:26.357  3870  3870 D BluetoothMapService: stop()
08-16 08:18:26.357  3870  3870 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 08:18:26.357  3870  3870 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 08:18:26.358  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fbed78d
08-16 08:18:26.359  7066  7096 W FormManager: Network not available. Please check & try again.
08-16 08:18:26.360  3870  3870 I BluetoothA2dpServiceJni: cleanupNative
08-16 08:18:26.360  3870  4017 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 08:18:26.360  3870  3870 I GKI_LINUX: GKI_exit_task 2 done
08-16 08:18:26.360  3870  3870 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 08:18:26.361  3870  3870 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 08:18:26.361  3870  3870 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 08:18:26.361  3870  3870 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 08:18:26.362  3870  3870 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 08:18:26.362  3870  3870 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 08:18:26.362  3870  3870 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 08:18:26.362  3870  3870 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 08:18:26.363  3870  3870 V BluetoothMapService: Handler(): got msg=4
08-16 08:18:26.363  3870  3870 D BluetoothMapService: MAP Service closeService in
08-16 08:18:26.363  3870  3870 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 08:18:26.363  3870  3870 V BluetoothMapService: MAP Service closeService out
08-16 08:18:26.363  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:26.363  3870  3946 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 08:18:26.363  3870  3946 D BluetoothAdapterProperties: Setting state to 10
08-16 08:18:26.363  3870  3946 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 08:18:26.364  3870  3870 D BluetoothMapService: cleanup()
08-16 08:18:26.364  3870  3870 D BluetoothMapService: MAP Service closeService in
08-16 08:18:26.364  3870  3870 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 08:18:26.364  3870  3870 V BluetoothMapService: MAP Service closeService out
08-16 08:18:26.365  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:26.365  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 08:18:26.365  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 08:18:26.365  3870  3946 I BluetoothAdapterState: Entering OffState
08-16 08:18:26.365  6953  6981 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 08:18:26.366  6953  6953 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 08:18:26.366  6953  6953 D PanProfile: Bluetooth service disconnected
08-16 08:18:26.366  6953  6953 D BluetoothMap: Proxy object disconnected
08-16 08:18:26.366  6953  6953 D MapProfile: Bluetooth service disconnected
,08-16 08:18:26.368  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:26.369  6953  6974 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 08:18:26.370  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:26.370  7066  7097 V FormManager: Network unavailable.
08-16 08:18:26.372  1855  3981 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:26.372  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:26.373  6953  7098 D BluetoothMap: onBluetoothStateChange: up=false
08-16 08:18:26.374  7066  7097 V FormManager: Network unavailable.
08-16 08:18:26.374  6953  6981 D BluetoothPan: onBluetoothStateChange on: false
08-16 08:18:26.375  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 08:18:26.375  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 08:18:26.376  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-16 08:18:26.378  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 08:18:26.378  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 08:18:26.379  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@16607e39 mBinding = false
08-16 08:18:26.379  1036  1118 D BluetoothManagerService: Sending unbind request.
,08-16 08:18:26.383  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 08:18:26.386  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:26.387  1943  2173 D LGBluetoothAPIService: Message: 2
08-16 08:18:26.387  1943  2173 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2ae49374 mBinding = false
08-16 08:18:26.387  1943  2173 D LGBluetoothAPIService: Sending unbind request.
08-16 08:18:26.388  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 08:18:26.390  6953  6953 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 08:18:26.390  6953  6953 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 08:18:26.390  6953  6953 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 08:18:26.391  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:26.392  3870  3951 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 08:18:26.393  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:26.393  3870  3870 I GKI_LINUX: GKI_exit_task 1 done
08-16 08:18:26.393  3870  3870 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 08:18:26.394  3870  3870 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 08:18:26.394  3870  3870 I art     : --- WEIRD: removing null entry 246
08-16 08:18:26.394  3870  3870 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 08:18:26.394  3870  3870 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 08:18:26.395  6953  6953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 08:18:26.396  3870  3870 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 08:18:26.398  7027  7027 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 08:18:26.399  1604  1604 D BluetoothAdapter: 990594108: getState() :  mService = null. Returning STATE_OFF
08-16 08:18:26.399  1604  1604 D BluetoothAdapter: 990594108: getState() :  mService = null. Returning STATE_OFF
08-16 08:18:26.400  3870  3870 I art     : System.exit called, status: 0
08-16 08:18:26.400  3870  3870 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 08:18:26.403  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-16 08:18:26.404  7027  7027 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 08:18:26.404  6953  6953 D DockEventReceiver: finishStartingService: stopping service
08-16 08:18:26.419   322  2145 V AudioFlinger: 3870 died, releasing its sessions
08-16 08:18:26.419   322  2145 V AudioFlinger:  pid 1855 @ 0
08-16 08:18:26.419   322  2145 V AudioFlinger:  pid 3422 @ 1
08-16 08:18:26.419   322  2145 V AudioFlinger:  pid 3422 @ 2
,08-16 08:18:26.421  6953  6953 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-16 08:18:26.456  7027  7027 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:26.457  7027  7027 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:26.468  7027  7027 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 08:18:26.470  7027  7027 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 08:18:26.470  7027  7027 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
,08-16 08:18:26.470  7027  7027 V SoundPool: doLoad: loading sample sampleID=1
08-16 08:18:26.471  7027  7027 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 08:18:26.473  7027  7107 V SoundPool: Start decode
08-16 08:18:26.473  7027  7107 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 08:18:26.474   322  1397 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 08:18:26.474   322  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 08:18:26.474   322  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 08:18:26.474   322  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 08:18:26.474   322  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 08:18:26.474   322  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 08:18:26.474   322  1397 V MediaPlayerService: player type = 3
08-16 08:18:26.474   322  1397 V AwesomePlayer: AwesomePlayer create()
08-16 08:18:26.475   322  1397 V AwesomePlayer: reset_l() 
08-16 08:18:26.475   322  1397 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:26.475   322  1397 V AwesomePlayer: setAudioSink() 
08-16 08:18:26.475   322  1397 V AwesomePlayer: reset_l() 
08-16 08:18:26.475   322  1397 V AudioCache: notify(0xb1432f80, 8, 0, 0)
08-16 08:18:26.475   322  1397 V AudioCache: ignored
08-16 08:18:26.475   322  1397 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:26.475  1036  2007 I ActivityManager: Process com.android.bluetooth (pid 3870) has died
08-16 08:18:26.475   322  1397 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 08:18:26.475   322  1397 V AwesomePlayer: setDataSource_l dataSource
08-16 08:18:26.475   322  1397 V LGParserOSAL: SniffLGParser start
08-16 08:18:26.475   322  1397 V LGParserOSAL: MainType:5, SubType=0
08-16 08:18:26.475   322  1397 V LGParserOSAL: #### check Mime : application/ogg
08-16 08:18:26.475   322  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 08:18:26.475   322  1397 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 08:18:26.475  1036  2007 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-16 08:18:26.485  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:18:26.488  6764  6764 D UEI.SmartControl: QS Service created
08-16 08:18:26.492  7027  7027 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 08:18:26.496  7027  7027 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 08:18:26.497  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 08:18:26.506  6953  6953 D BluetoothPermissionRequest: onReceive
08-16 08:18:26.506  6764  6764 I UEI.SmartControl: Service initServices...
,08-16 08:18:26.506  6764  6764 D UEI.SmartControl: QS start get config
08-16 08:18:26.508  6953  6953 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 08:18:26.509  6953  6953 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 08:18:26.514  7027  7027 V LGMDMManager: Create singleton instance
08-16 08:18:26.523  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:26.537   322  1397 V LGParserOSAL: supported mime: application/ogg
08-16 08:18:26.537   322  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 08:18:26.537   322  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 08:18:26.537   322  1397 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 08:18:26.537   322  1397 V AwesomePlayer: AudioTrack Setting
08-16 08:18:26.537   322  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 08:18:26.537   322  1397 V AwesomePlayer: setAudioSource() 
08-16 08:18:26.537   322  1397 V MediaPlayerService: prepare
08-16 08:18:26.537   322  1397 V AwesomePlayer: prepareAsync_l() 
,08-16 08:18:26.537   322  1397 V MediaPlayerService: wait for prepare
08-16 08:18:26.537   322  7109 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 08:18:26.537   322  7109 V AwesomePlayer: initAudioDecoder() 
08-16 08:18:26.537   322  7109 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 08:18:26.537   322  7109 V AudioSystem: isOffloadSupported()
08-16 08:18:26.537   322  7109 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 08:18:26.537   322  7109 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 08:18:26.537   322  7109 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 08:18:26.537   322  7109 V AwesomePlayer: getUseOffload() = 0 
08-16 08:18:26.537   322  7109 V OMXCodec: OMXCodec::Create
08-16 08:18:26.537   322  7109 V OMXCodec: findMatchingCodecs()
08-16 08:18:26.537   322  7109 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 08:18:26.538   322  7109 V OMXCodec: matchingCodecs.size()=1
08-16 08:18:26.538   322  7109 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 08:18:26.539   322  7109 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 08:18:26.539   322  7109 V LGCodecAdapter: LG Codec Adapter start
08-16 08:18:26.539   322  7109 V OMXCodec: OMXCodec Createtor
08-16 08:18:26.539   322  7109 V OMXCodec: setComponentRole
08-16 08:18:26.539   322  7109 V OMXCodec: configureCodec protected=0
08-16 08:18:26.539   322  7109 V LGCodecAdapter: called getLGCodecSpecificData
08-16 08:18:26.539   322  7109 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 08:18:26.539   322  7109 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 08:18:26.539   322  7109 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 08:18:26.539   322  7109 V LGCodecOSAL: Not support LGCodec
08-16 08:18:26.539   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 08:18:26.539   322  7109 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 08:18:26.540   322  7109 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 08:18:26.540   322  7109 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 08:18:26.540   322  7109 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 08:18:26.540   322  7109 V AudioSystem: isOffloadSupported()
08-16 08:18:26.540   322  7109 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 08:18:26.540   322  7109 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 08:18:26.540   322  7109 V OMXCodec: init()
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 08:18:26.540   322  7109 V OMXCodec: allocateBuffers
08-16 08:18:26.540   322  7109 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.deco,der] allocated buffer 0xb54f7b00 on input port
08-16 08:18:26.540   322  7109 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-16 08:18:26.540   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-16 08:18:26.541   322  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-16 08:18:26.541   322  7109 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 08:18:26.541   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 08:18:26.541   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 08:18:26.541   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 08:18:26.542   322  7109 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 08:18:26.542   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 08:18:26.542   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 08:18:26.542   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 08:18:26.542   322  7109 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 08:18:26.542   322  7109 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 08:18:26.542   322  7109 V AudioCache: notify(0xb1432f80, 5, 0, 0)
08-16 08:18:26.542   322  7109 V AudioCache: ignored
08-16 08:18:26.542   322  7109 V AudioCache: notify(0xb1432f80, 1, 0, 0)
08-16 08:18:26.542   322  7109 V AudioCache: prepared
08-16 08:18:26.542   322  1397 V AudioCache: wait - success
08-16 08:18:26.542   322  1397 V MediaPlayerService: start
08-16 08:18:26.542   322  1397 V AwesomePlayer: play_l() 
08-16 08:18:26.542   322  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 08:18:26.542   322  1397 V AwesomePlayer: createAudioPlayer_l
08-16 08:18:26.542   322  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 08:18:26.542   322  1397 V AwesomePlayer: startAudioPlayer_l() 
08-16 08:18:26.542   322  1397 D AudioPlayer: start of Playback, useOffload 0
08-16 08:18:26.542   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 08:18:26.542   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-16 08:18:26.545   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 08:18:26.545   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 08:18:26.545   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 08:18:26.545   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 08:18:26.545   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008,
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-16 08:18:26.546   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 08:18:26.547   322  7111 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 08:18:26.547   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 08:18:26.547   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-16 08:18:26.547   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
,08-16 08:18:26.547   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 08:18:26.547   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1740 on output port
08-16 08:18:26.547   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 08:18:26.547   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 08:18:26.549   322  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 08:18:26.550   322  1397 V AudioCache: notify(0xb1432f80, 6, 0, 0)
08-16 08:18:26.550   322  1397 V AudioCache: ignored
,08-16 08:18:26.550   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.550   322  7112 V AudioCache: memcpy(0xaf006000, 0xb14b4000, 4096)
08-16 08:18:26.550   322  1397 V MediaPlayerService: wait for playback complete
08-16 08:18:26.552   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.552   322  7112 V AudioCache: memcpy(0xaf007000, 0xb14b4000, 4096)
08-16 08:18:26.552   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.552   322  7112 V AudioCache: memcpy(0xaf008000, 0xb14b4000, 4096)
,08-16 08:18:26.553   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.553   322  7112 V AudioCache: memcpy(0xaf009000, 0xb14b4000, 4096)
08-16 08:18:26.554   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.554   322  7112 V AudioCache: memcpy(0xaf00a000, 0xb14b4000, 4096)
08-16 08:18:26.555   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.555   322  7112 V AudioCache: memcpy(0xaf00b000, 0xb14b4000, 4096)
08-16 08:18:26.556   322  7112 V AudioCache: write(0xb14b4000, 4096)
,08-16 08:18:26.556   322  7112 V AudioCache: memcpy(0xaf00c000, 0xb14b4000, 4096)
,08-16 08:18:26.556   322  7112 V AudioCache: write(0xb14b4000, 4096)
,08-16 08:18:26.556   322  7112 V AudioCache: memcpy(0xaf00d000, 0xb14b4000, 4096)
08-16 08:18:26.557   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.557   322  7112 V AudioCache: memcpy(0xaf00e000, 0xb14b4000, 4096)
08-16 08:18:26.558   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.558   322  7112 V AudioCache: memcpy(0xaf00f000, 0xb14b4000, 4096)
08-16 08:18:26.558   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.558   322  7112 V AudioCache: memcpy(0xaf010000, 0xb14b4000, 4096)
08-16 08:18:26.559   322  7112 V AudioCache: write(0xb14b4000, 4096)
,08-16 08:18:26.559   322  7112 V AudioCache: memcpy(0xaf011000, 0xb14b4000, 4096)
08-16 08:18:26.560   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.560   322  7112 V AudioCache: memcpy(0xaf012000, 0xb14b4000, 4096)
08-16 08:18:26.561   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.561   322  7112 V AudioCache: memcpy(0xaf013000, 0xb14b4000, 4096)
08-16 08:18:26.561   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.561   322  7112 V AudioCache: memcpy(0xaf014000, 0xb14b4000, 4096)
08-16 08:18:26.572   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.572   322  7112 V AudioCache: memcpy(0xaf015000, 0xb14b4000, 4096)
08-16 08:18:26.572   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.572   322  7112 V AudioCache: memcpy(0xaf016000, 0xb14b4000, 4096)
08-16 08:18:26.573   322  7112 V AudioCache: write(0xb14b4000, 4096)
,08-16 08:18:26.573   322  7112 V AudioCache: memcpy(0xaf017000, 0xb14b4000, 4096)
08-16 08:18:26.574   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.574   322  7112 V AudioCache: memcpy(0xaf018000, 0xb14b4000, 4096)
08-16 08:18:26.574   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.574   322  7112 V AudioCache: memcpy(0xaf019000, 0xb14b4000, 4096)
08-16 08:18:26.575   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.575   322  7112 V AudioCache: memcpy(0xaf01a000, 0xb14b4000, 4096)
,08-16 08:18:26.576   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.576   322  7112 V AudioCache: memcpy(0xaf01b000, 0xb14b4000, 4096)
08-16 08:18:26.576   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.576   322  7112 V AudioCache: memcpy(0xaf01c000, 0xb14b4000, 4096)
08-16 08:18:26.577   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.577   322  7112 V AudioCache: memcpy(0xaf01d000, 0xb14b4000, 4096)
08-16 08:18:26.577   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.577   322  7112 V AudioCache: memcpy(0xaf01e000, 0xb14b4000, 4096)
,08-16 08:18:26.578   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.578   322  7112 V AudioCache: memcpy(0xaf01f000, 0xb14b4000, 4096)
08-16 08:18:26.578   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.578   322  7112 V AudioCache: memcpy(0xaf020000, 0xb14b4000, 4096)
08-16 08:18:26.579   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.579   322  7112 V AudioCache: memcpy(0xaf021000, 0xb14b4000, 4096)
08-16 08:18:26.579   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.579   322  7112 V AudioCache: memcpy(0xaf022000, 0xb14b4000, 4096)
08-16 08:18:26.580   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.580   322  7112 V AudioCache: memcpy(0xaf023000, 0xb14b4000, 4096)
08-16 08:18:26.581   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.581   322  7112 V AudioCache: memcpy(0xaf024000, 0xb14b4000, 4096)
08-16 08:18:26.581   322  7112 V AudioCache: write(0xb14b4000, 4096)
,08-16 08:18:26.581   322  7112 V AudioCache: memcpy(0xaf025000, 0xb14b4000, 4096)
08-16 08:18:26.582   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.582   322  7112 V AudioCache: memcpy(0xaf026000, 0xb14b4000, 4096)
08-16 08:18:26.583   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.583   322  7112 V AudioCache: memcpy(0xaf027000, 0xb14b4000, 4096)
08-16 08:18:26.583   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.583   322  7112 V AudioCache: memcpy(0xaf028000, 0xb14b4000, 4096)
08-16 08:18:26.584   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.584   322  7112 V AudioCache: memcpy(0xaf029000, 0xb14b4000, 4096)
08-16 08:18:26.584   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.584   322  7112 V AudioCache: memcpy(0xaf02a000, 0xb14b4000, 4096)
08-16 08:18:26.585   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.585   322  7112 V AudioCache: memcpy(0xaf02b000, 0xb14b4000, 4096)
08-16 08:18:26.586   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.586   322  7112 V AudioCache: memcpy(0xaf02c000, 0xb14b4000, 4096)
08-16 08:18:26.586   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.586   322  7112 V AudioCache: memcpy(0xaf02d000, 0xb14b4000, 4096)
08-16 08:18:26.587   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.587   322  7112 V AudioCache: memcpy(0xaf02e000, 0xb14b4000, 4096)
,08-16 08:18:26.587   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.587   322  7112 V AudioCache: memcpy(0xaf02f000, 0xb14b4000, 4096)
08-16 08:18:26.588   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.588   322  7112 V AudioCache: memcpy(0xaf030000, 0xb14b4000, 4096)
08-16 08:18:26.588  1036  1953 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7113 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 08:18:26.588   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.588   322  7112 V AudioCache: memcpy(0xaf031000, 0xb14b4000, 4096)
08-16 08:18:26.589   322  7112 V AudioCache: write(0xb14b4000, 4096)
,08-16 08:18:26.589   322  7112 V AudioCache: memcpy(0xaf032000, 0xb14b4000, 4096)
08-16 08:18:26.589   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.589   322  7112 V AudioCache: memcpy(0xaf033000, 0xb14b4000, 4096)
08-16 08:18:26.590   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.590   322  7112 V AudioCache: memcpy(0xaf034000, 0xb14b4000, 4096)
08-16 08:18:26.590   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.590   322  7112 V AudioCache: memcpy(0xaf035000, 0xb14b4000, 4096)
08-16 08:18:26.591   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.591   322  7112 V AudioCache: memcpy(0xaf036000, 0xb14b4000, 4096)
08-16 08:18:26.591   322  7112 V AudioCache: write(0xb14b4000, 4096)
08-16 08:18:26.591   322  7112 V AudioCache: memcpy(0xaf037000, 0xb14b4000, 4096)
08-16 08:18:26.592   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 08:18:26.592   322  7112 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 08:18:26.592   322  7112 V AwesomePlayer: postAudioEOS() 
08-16 08:18:26.592   322  7112 V AudioCache: write(0xb14b4000, 280)
08-16 08:18:26.592   322  7112 V AudioCache: memcpy(0xaf038000, 0xb14b4000, 280)
08-16 08:18:26.593   322  7109 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 08:18:26.593   322  7109 V AwesomePlayer: onStreamDone
08-16 08:18:26.593   322  7109 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 08:18:26.593   322  7109 V AudioCache: notify(0xb1432f80, 2, 0, 0)
08-16 08:18:26.593   322  7109 V AudioCache: playback complete
08-16 08:18:26.593   322  7109 V AwesomePlayer: pause_l() 
08-16 08:18:26.593   322  7109 V AudioCache: notify(0xb1432f80, 7, 0, 0)
08-16 08:18:26.593   322  7109 V AudioCache: ignored
08-16 08:18:26.593   322  7109 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:26.593   322  7109 D AudioPlayer: Pause Playback at 1068125
08-16 08:18:26.594   322  1397 V AudioCache: wait - success
08-16 08:18:26.594   322  1397 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 08:18:26.594   322  1397 V AwesomePlayer: reset_l() 
08-16 08:18:26.594   322  1397 V AudioCache: notify(0xb1432f80, 8, 0, 0)
08-16 08:18:26.594   322  1397 V AudioCache: ignored
08-16 08:18:26.594   322  1397 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:26.594   322  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 08:18:26.594   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 08:18:26.594   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 08:18:26.594   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 08:18:26.594   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vor,bis.decoder] freeBuffersOnPort portIndex=1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1740 on port 1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 08:18:26.595   322  7111 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 08:18:26.595   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 08:18:26.595   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 08:18:26.595   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 08:18:26.596   322  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 08:18:26.596   322  1397 D AudioPlayer: AudioPlayer releasing audio source
08-16 08:18:26.596   322  1397 D AudioPlayer: AudioPlayer done releasing audio source
08-16 08:18:26.596   322  1397 V AwesomePlayer: reset_l() 
08-16 08:18:26.596   322  1397 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:26.596   322  1397 V AwesomePlayer: ~AwesomePlayer call
08-16 08:18:26.596   322  1397 V AwesomePlayer: reset_l() 
08-16 08:18:26.596   322  1397 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:26.597  7027  7107 V SoundPool: close(31)
08-16 08:18:26.597  7027  7107 V SoundPool: pointer = 0xa004a000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 08:18:26.615  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 08:18:26.618  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-16 08:18:26.621  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9811
08-16 08:18:26.627  7113  7113 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 08:18:26.628  7113  7113 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:26.628  7113  7113 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 08:18:26.628  7113  7113 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 08:18:26.639  7113  7113 D BluetoothAdapterApp: Loading JNI Library
,08-16 08:18:26.656  7113  7113 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f7deaea Instance Count = 1
,08-16 08:18:26.659  7113  7113 D BluetoothAdapterApp: onCreate
08-16 08:18:26.672  7113  7113 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-16 08:18:26.673  7113  7113 D ProfileConfigQcom: Adding HeadsetService
08-16 08:18:26.673  7113  7113 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 08:18:26.673  7113  7113 D ProfileConfigQcom: Adding A2dpService
08-16 08:18:26.674  7113  7113 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 08:18:26.674  7113  7113 D ProfileConfigQcom: Adding HidService
08-16 08:18:26.674  7113  7113 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 08:18:26.675  7113  7113 D ProfileConfigQcom: Adding HealthService
08-16 08:18:26.675  7113  7113 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 08:18:26.675  7113  7113 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 08:18:26.675  7113  7113 D ProfileConfigQcom: Adding PanService
08-16 08:18:26.676  7113  7113 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 08:18:26.676  7113  7113 D ProfileConfigQcom: Adding GattService
08-16 08:18:26.676  7113  7113 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 08:18:26.676  7113  7113 D ProfileConfigQcom: Adding BluetoothMapService
08-16 08:18:26.676  7113  7113 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 08:18:26.678  7113  7113 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 08:18:26.682  6953  6953 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 08:18:26.685  7113  7113 V LGMDMManagerInternal: Create singleton instance
08-16 08:18:26.768  7113  7113 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:18:26.771  7113  7113 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 08:18:26.771  7113  7113 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:26.771  7113  7113 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:26.772  7113  7113 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:26.772  7113  7113 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 08:18:26.780  7046  7046 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 08:18:26.811  6764  6764 I UEI.SmartControl: Supports setup maps: true
,08-16 08:18:26.813  6764  6764 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 08:18:26.813  6764  6764 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 08:18:26.813  6764  6764 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 08:18:26.813  6764  6764 I UEI.SmartControl: ### init IR Blaster...
08-16 08:18:26.817  6764  6764 D serial_port: Configuring serial port
08-16 08:18:26.817  6764  6764 E UEI.SmartControl: UEIBLaster setting for 616
08-16 08:18:26.817  6764  6764 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 08:18:26.817  6764  6764 I UEI.SmartControl: configuring settings for MAXQ616
08-16 08:18:26.817  6764  6764 I UEI.SmartControl: Get version...
08-16 08:18:26.833  6764  7133 D UEI.SmartControl: serial port data available: 21
,08-16 08:18:26.860  6764  6764 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 08:18:26.860  6764  6764 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 08:18:26.860  6764  6764 I UEI.SmartControl: QS saving settings...
08-16 08:18:26.862  6764  6764 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 08:18:26.879  6764  7133 D UEI.SmartControl: serial port data available: 4
,08-16 08:18:26.912  6764  7139 I UEI.SmartControl: Device manager: loading config....
,08-16 08:18:26.918  6764  7139 D UEI.SmartControl: ----------- loading internal config...
,08-16 08:18:26.919  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 08:18:26.923  6764  6764 E UEI.SmartControl: Services init done
08-16 08:18:26.923  6764  6764 D UEI.SmartControl: QS Service init finished
08-16 08:18:26.925  6764  6764 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 08:18:26.925  6764  6764 D UEI.SmartControl: QS Service version code: 201091
08-16 08:18:26.925  6764  6764 D UEI.SmartControl: Service requested: Control
08-16 08:18:26.931  6764  7139 E UEI.SmartControl: Loading SETTINGS...
08-16 08:18:26.931  6764  6764 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 08:18:26.939  6764  6764 D UEI.SmartControl: Internal service binding...
08-16 08:18:26.940  7027  7027 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 08:18:26.943  6764  6780 I UEI.SmartControl: ------ IControl API: 11
08-16 08:18:26.943  6764  6780 D UEI.SmartControl: File observer start...
08-16 08:18:26.944  6764  6780 E UEI.SmartControl: IR Port is disabled: false
08-16 08:18:26.944  6764  6780 D UEI.SmartControl: Starting file observer...
08-16 08:18:26.944  6764  6780 I UEI.SmartControl: Registering callback...
08-16 08:18:26.945  6764  6779 I UEI.SmartControl: ------ IControl API: 19
08-16 08:18:26.946  6764  6779 I UEI.SmartControl: Registering Services Ready callback...
08-16 08:18:26.950  6764  7139 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 08:18:26.969  6764  7138 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 08:18:26.970  6764  7138 D UEI.SmartControl: -----service ready thread exits
08-16 08:18:26.971  7027  7042 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 08:18:26.972  7027  7105 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 08:18:26.972  7027  7105 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-16 08:18:26.973  7027  7027 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 08:18:26.973  7027  7027 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 08:18:26.973  6764  6780 I UEI.SmartControl: ------ IControl API: 8
,08-16 08:18:26.975  7027  7027 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 08:18:26.975  7027  7027 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 08:18:26.976  7027  7027 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 08:18:26.976  7027  7027 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 08:18:26.977  7027  7027 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 08:18:26.977  7027  7027 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 08:18:26.978  7027  7027 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 08:18:26.985  7027  7027 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 08:18:26.987  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 08:18:26.988  7027  7027 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 08:18:26.989  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 08:18:26.991  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 08:18:26.993  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 08:18:26.993  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 08:18:26.994  7027  7027 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471328306994]
08-16 08:18:26.996  7027  7027 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 08:18:27.003  1036  1956 I ActivityManager: Killing 6133:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 08:18:27.036  7027  7141 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 08:18:27.051  1036  1956 I ActivityManager: Killing 6599:com.lge.email/u0a23 (adj 15): empty #18
,08-16 08:18:27.135  1036  1953 W libprocessgroup: failed to open /acct/uid_10027/pid_6133/cgroup.procs: No such file or directory
,08-16 08:18:27.154  1036  1973 W libprocessgroup: failed to open /acct/uid_10023/pid_6599/cgroup.procs: No such file or directory
,08-16 08:18:27.155  7027  7027 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 08:18:27.157  7027  7027 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 08:18:27.158  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 08:18:27.159  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-16 08:18:27.160  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 08:18:27.162  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 08:18:27.163  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 08:18:27.193  7027  7027 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 08:18:28.045  1036  2036 D WifiServiceImplEx: setWifiEnabled: true pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 08:18:28.046  1036  2036 D WifiService: setWifiEnabled: true pid=6862, uid=10118
08-16 08:18:28.047  1036  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 08:18:28.073  1036  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=429638175, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-16 08:18:28.077  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{28838853 type 2 when 207618 com.google.android.gms} when 207618
08-16 08:18:28.086  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 08:18:28.086  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 08:18:28.086  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-16 08:18:28.092  1036  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 08:18:28.092  1036  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 08:18:28.094  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 08:18:28.094  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 08:18:28.095  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 08:18:28.095  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 08:18:28.095  1036  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 08:18:28.095  1036  1440 E WifiHW  : unknown target_country: EU , set to default
08-16 08:18:28.095  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 08:18:28.095  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 08:18:28.095  1036  1440 I WifiUtil: gEnableBmps=1
08-16 08:18:28.099   317  7150 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 08:18:28.107  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 08:18:28.119  2630  2630 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 08:18:28.151  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:28.156  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-16 08:18:28.162  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:28.165  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:28.167  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:28.173  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-16 08:18:28.183  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:28.184  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:28.198  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 08:18:28.202  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:28.203  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:28.204  5823  5823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 08:18:28.204  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:28.204  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:28.207  6518  6965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 08:18:28.212  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=429638175 [*alarm*], flags=0x0
,08-16 08:18:28.220  5823  5823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 08:18:28.234  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:28.305  1036  1649 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7167 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 08:18:28.401  7167  7167 I AppUp4:AppBoxCP: onCreate
,08-16 08:18:28.402  7167  7167 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 08:18:28.413  7167  7167 I AppUp4:DB:  setFingerPrint start
08-16 08:18:28.413  7167  7167 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-16 08:18:28.423  7167  7167 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-16 08:18:28.423  7167  7167 I AppUp4:DB:  SDK version = 21
08-16 08:18:28.423  7167  7167 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 08:18:28.425  7167  7167 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 08:18:28.426  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 08:18:28.426  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:28.430  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 08:18:28.430  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 08:18:28.438  7167  7167 I AppUp4:CustModeStarterReceiver: onReceive
08-16 08:18:28.493  7167  7167 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:28.494  7167  7167 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:28.517  7167  7167 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d862024
08-16 08:18:28.517  7167  7167 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 08:18:28.518  7167  7167 D AppUp4:CustFacade: isPhone : true
08-16 08:18:28.519  7167  7167 D AppUp4:CustModeStarterReceiver: begin check event
08-16 08:18:28.520  7167  7167 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 08:18:28.521  7167  7167 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 08:18:28.523  7167  7185 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 08:18:28.523  7167  7185 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 08:18:28.524  7167  7185 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-16 08:18:28.533  1036  1649 I ActivityManager: Killing 6201:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 08:18:28.627  1036  1953 W libprocessgroup: failed to open /acct/uid_10080/pid_6201/cgroup.procs: No such file or directory
,08-16 08:18:28.648  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:28.648  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:28.650  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 08:18:28.656  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:28.712  1036  1938 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7203 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 08:18:28.764  4349  7202 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 08:18:28.769  4349  7219 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:28.769  4349  7219 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 08:18:28.805  7203  7203 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:28.806  7203  7203 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:28.808  7203  7203 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 08:18:28.808  7203  7203 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 08:18:28.816  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 08:18:28.823   317   894 D SoftapController: Softap fwReload - Ok
08-16 08:18:28.823  1036  1118 D Tethering: InitialState.processMessage what=4
,08-16 08:18:28.826  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 08:18:28.828  1036  1440 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (719ms)
08-16 08:18:28.832   317   894 D CommandListener: Setting iface cfg
08-16 08:18:28.833   317   894 D CommandListener: Trying to bring down wlan0
08-16 08:18:28.833   317   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 08:18:28.835  1036  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 08:18:28.821  7233  7233 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 08:18:28.821  7233  7233 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:28.865  7233  7233 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 08:18:28.897  7233  7233 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 08:18:28.897  7233  7233 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 08:18:28.926  7203  7203 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 08:18:28.936  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:28.936  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:28.936  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 08:18:28.936  1036  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 08:18:28.936  1036  1440 D WifiMonitor: connecting to supplicant
08-16 08:18:28.938  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:28.938  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 08:18:28.939  7203  7203 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 08:18:28.941  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:28.942  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:28.943  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 08:18:28.974  7203  7203 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 08:18:28.994  7233  7233 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 08:18:28.997  7203  7203 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:28.997  7203  7203 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:29.048  7233  7233 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 08:18:29.056  7233  7233 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 08:18:29.056  7233  7233 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 08:18:29.059  1036  7244 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 08:18:29.059  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 08:18:29.059  1036  7244 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 08:18:29.059  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 08:18:29.059  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 08:18:29.059  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 08:18:29.059  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-16 08:18:29.060  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 08:18:29.061  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-16 08:18:29.063  1036  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 08:18:29.064  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:29.065  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:29.066  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:29.067  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:29.068  1036  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 08:18:29.068  1036  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 08:18:29.069  1036  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 08:18:29.069  1036  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 08:18:29.069  7203  7203 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 08:18:29.069  1036  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-16 08:18:29.070  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:29.070  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:29.070  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 08:18:29.070  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.070  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.070  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.070  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.071  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:29.072  1036  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 08:18:29.072  1036  1440 D WifiNative-wlan0: SET update_config 1: returned true
08-16 08:18:29.072  1036  1440 D WifiConfigStore: Loading config and enabling all networks 
08-16 08:18:29.072  1036  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 08:18:29.073  1036  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 08:18:29.077  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:29.079  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-16 08:18:29.079  1036  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 08:18:29.080  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 08:18:29.080  1036  1473 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 08:18:29.080  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:29.080  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:29.080  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:29.081  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:29.085  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE m,ultiple advertisement supported: NOT_SUPPORTED
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:29.085  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:29.085  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:29.085  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:29.088  1036  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 08:18:29.088  1036  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 08:18:29.089  1036  1440 D WifiStateMachine: enableVerboseLogging : level 2
08-16 08:18:29.089  1036  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 08:18:29.089  1036  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 08:18:29.089  1036  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 08:18:29.089  1036  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 08:18:29.089  1036  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 08:18:29.090  1036  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 08:18:29.090  1036  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 08:18:29.090  1036  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
,08-16 08:18:29.090  1036  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 08:18:29.090  1036  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 08:18:29.090  1036  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 08:18:29.091  1036  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 08:18:29.091  1036  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 08:18:29.092  1036  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 08:18:29.092  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 08:18:29.092  1036  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 08:18:29.093  1036  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 08:18:29.093  1036  1440 D WifiNative-HAL: Setting external_sim to 1
08-16 08:18:29.093  1036  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 08:18:29.093  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-16 08:18:29.093  1943  2385 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 08:18:29.093  1943  2385 D WfdsService: Set the WFDS Monitor: true
08-16 08:18:29.093  1943  2385 D WfdsMonitor: WfdsMonitorThread create
08-16 08:18:29.093  1943  2385 D WfdsMonitor: WFDS Monitor is created and started
08-16 08:18:29.093  1943  2385 D WfdsService: WiFi: Supplicant connection re-established
08-16 08:18:29.093  1036  1440 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 08:18:29.093  1036  1440 I WifiNative-HAL: startHal
08-16 08:18:29.093  1036  1440 D wifi    : setting scan oui 0xaf7a8ec0
08-16 08:18:29.094  1943  7246 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 08:18:29.094  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 08:18:29.094  1036  1440 I WifiNative-HAL: startHal
08-16 08:18:29.094  1036  1440 D wifi    : setting scan oui 0xaf7a8ec0
08-16 08:18:29.094  1943  7246 E CtrlSupplicant: Succeed to open control connection
08-16 08:18:29.094  1943  7246 E CtrlSupplicant: Succeed to open monitor connection
08-16 08:18:29.094  1036  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 08:18:29.094  1943  7246 D WfdsMonitor: Supplicant connection established
08-16 08:18:29.094  1943  2385 D WfdsService: Connected to the supplicant for wfds
08-16 08:18:29.094  1036  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 08:18:29.095  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 08:18:29.095  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 08:18:29.095  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 08:18:29.095  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 08:18:29.095  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 08:18:29.095  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 08:18:29.095  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 08:18:29.096  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 08:18:29.096  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 08:18:29.096  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 08:18:29.096  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 08:18:29.096  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 08:18:29.096  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 08:18:29.096  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 08:18:29.096  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 08:18:29.097  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 08:18:29.097  7233  7233 I wpa_supplicant: android_multicast_filter_startstop : multicast filter ,set
08-16 08:18:29.097  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 08:18:29.097  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 08:18:29.097  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 08:18:29.097  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 08:18:29.098  1036  1440 E WifiNative: : [208,643,046 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 08:18:29.098  1036  1440 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 08:18:29.098  1036  1440 D WifiNative-wlan0: RECONNECT: returned true
08-16 08:18:29.098  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-16 08:18:29.099  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 08:18:29.099  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 08:18:29.099  1036  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 08:18:29.099  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 08:18:29.099  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:29.100  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.101   317   894 D CommandListener: Setting iface cfg
08-16 08:18:29.102   317   894 D CommandListener: Trying to bring up p2p0
08-16 08:18:29.102  1036  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 08:18:29.102  1036  1391 D LGWifiP2pService: P2pEnablingState
08-16 08:18:29.102  1036  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.102  1036  1391 D LGWifiP2pService: P2p socket connection successful
08-16 08:18:29.102  1036  1391 D LGWifiP2pService: P2pEnabledState
08-16 08:18:29.102  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 08:18:29.103  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-16 08:18:29.103  1036  1391 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 08:18:29.103  1036  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 08:18:29.103  1036  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.103  1036  1558 I WifiNative-HAL: startHal
08-16 08:18:29.103  1036  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:29.105  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 08:18:29.105  1943  1943 D WfdsService: WifiP2pState is changed : true
08-16 08:18:29.105  1943  2385 D WfdsService: Receive the WFDS_ENABLE Method
08-16 08:18:29.106  1943  2385 D WfdsService: Set the WFDS Monitor: true
08-16 08:18:29.106  1943  2385 D WfdsService: Connected to the supplicant for wfds
08-16 08:18:29.106  1943  2385 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 08:18:29.106  7233  7233 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 08:18:29.106  1943  2385 D WfdsService: selectPreferredScanChannel [36]
08-16 08:18:29.106  1943  2385 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 08:18:29.106  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 08:18:29.107  1943  1943 D WfdsService: isConnected: false
08-16 08:18:29.107  1036  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 08:18:29.107  1036  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 08:18:29.108  1036  1391 D WifiNative-p2p0: SET device_name G3: returned true
08-16 08:18:29.108  1036  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 08:18:29.108  1036  1391 D LGWifiP2pService: before postfix = G3
08-16 08:18:29.108  1036  1391 D WifiServerServiceExt: postfix byte check : 2
08-16 08:18:29.108  1036  1391 D LGWifiP2pService: after postfix = G3
08-16 08:18:29.108  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf7a8ec0
08-16 08:18:29.108  1036  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 08:18:29.108  1036  1558 D wifi    : failed to get capabilities : -3
08-16 08:18:29.108  1036  1558 E WifiScanningService: could not get scan capabilities
08-16 08:18:29.108  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 08:18:29.109  1036  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 08:18:29.109  1036  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 08:18:29.109  1036  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 08:18:29.109  1036  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 08:18:29.109  1036  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 08:18:29.110  1036  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 08:18:29.110  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 08:18:29.110  1036  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 08:18:29.110  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress
08-16 08:18:29.110  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 08:18:29.111  1036  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 08:18:29.111  1036  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 08:18:29.111  1036  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 08:18:29.111  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 08:18:29.111  1036  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 08:18:29.111  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 08:18:29.112  1036  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 08:18:29.112  1036  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 08:18:29.112  1036  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 08:18:29.113  1036  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 08:18:29.113  1036  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 08:18:29.113  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 08:18:29.113  1943  1943 D WfdsService: Update P2p Interface State: 3
08-16 08:18:29.113  1036  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 08:18:29.116  3422 , 3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 08:18:29.116  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:29.116  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 08:18:29.117  1036  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 08:18:29.117  1036  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 08:18:29.118  1036  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 08:18:29.121  7203  7203 I HubEmail: JNI_OnLoad()
08-16 08:18:29.121  7203  7203 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 08:18:29.121  7203  7203 I HubEmail: registerNatives()
08-16 08:18:29.121  7203  7203 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 08:18:29.121  7203  7203 I HubEmail: registerNativeMethods()
08-16 08:18:29.121  7203  7203 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 08:18:29.121  7203  7203 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 08:18:29.123  7233  7233 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 08:18:29.124  1036  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 08:18:29.124  1036  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 08:18:29.124  1036  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 08:18:29.124  1036  1440 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 08:18:29.125  1036  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 08:18:29.125  1036  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 08:18:29.125  7233  7233 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 08:18:29.125  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 08:18:29.125  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 08:18:29.126  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 08:18:29.126  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 08:18:29.126  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-16 08:18:29.127  7233  7233 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.127  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 08:18:29.127  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.127  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.127  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.127  7233  7233 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 08:18:29.127  7233  7233 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1943  7246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.128  1036  7244 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.128  1036  7244 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1036  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 08:18:29.128  7233  7233 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 08:18:29.128  1943  7246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.128  1036  7244 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.128  1036  7244 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.128  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 08:18:29.129  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 08:18:29.129  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 08:18:29.129  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 08:18:29.129  7233  7233 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:29.129  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 08:18:29.129  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:29.129  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:29.129  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:29.129  1036  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 08:18:29.129  1036  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 08:18:29.129  1036  1440 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 08:18:29.129  1036  1440 D WifiNative-wlan0: doBoolean: SCAN
08-16 08:18:29.130  1036  1440 D WifiNative-wlan0: SCAN: returned false
08-16 08:18:29.130  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=208675  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 08:18:29.161  1036  1997 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7252 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-16 08:18:29.163  1036  1391 D LGWifiP2pS,ervice: InactiveState
08-16 08:18:29.163  1036  1391 D LGWifiP2pService: InactiveState{ when=-51ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.163  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-51ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.163  1036  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-16 08:18:29.165  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 08:18:29.167  7233  7233 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.168  1036  7244 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 08:18:29.169  1036  7244 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.169  1943  7246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 08:18:29.169  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.169  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:29.169  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=208714  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 08:18:29.169  7233  7233 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 08:18:29.169  7233  7233 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.169  1036  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 08:18:29.169  1036  1391 D LGWifiP2pService: InactiveState{ when=-42ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.170  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-42ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.170  1036  1391 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:29.170  1036  7244 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.170  1036  7244 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.170  1036  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:29.170  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.170  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 08:18:29.170  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.170  1036  1391 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.170  1943  7246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.171  1036  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:29.172  7233  7233 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.173  1036  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-16 08:18:29.174  1036  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:29.174  1943  7246 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.175  1036  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:29.175  1036  7244 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:29.175  1036  7244 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.175  1036  7244 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 08:18:29.175  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:29.175  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:29.175  1036  7244 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:29.176  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.176  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.176  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-16 08:18:29.176  1036  1391 D LGWifiP2pService: InactiveState{ when=-13ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1036  1391 D LGWifiP2pService: DefaultState{ when=-13ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1036  1391 D LGWifiP2pService: InactiveState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1036  1391 D LGWifiP2pService: DefaultState{ when=-13ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1036  1391 D LGWifiP2pService: InactiveState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:29.177  1036  1391 D LGWifiP2pService: DefaultState{ when=-14ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:29.177  1943  2385 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 08:18:29.177  1036  1036 E WifiServerServiceExt: No p2p device connected
,08-16 08:18:29.178  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:29.178  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:29.178  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 08:18:29.180  7066  7248 W FormManager: Network not available. Please check & try again.
08-16 08:18:29.185  7203  7251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.186  7066  7249 V FormManager: Network unavailable.
08-16 08:18:29.189  7066  7249 V FormManager: Network unavailable.
,08-16 08:18:29.196  1036  1052 I ActivityManager: Killing 6647:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-16 08:18:29.226  1036  1956 W libprocessgroup: failed to open /acct/uid_10061/pid_6647/cgroup.procs: No such file or directory
,08-16 08:18:29.315  7252  7252 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:29.315  7252  7252 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:29.319  7252  7252 D PhoneMonitor: Register our PhoneStateListener
,08-16 08:18:29.348  7252  7252 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 08:18:29.353  7252  7252 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 08:18:29.382  7252  7252 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 08:18:29.391  7252  7252 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 08:18:29.393  7252  7252 D TelephonyAutoProfiling: [parse] Load xml
08-16 08:18:29.400  7252  7252 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-16 08:18:29.400  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 08:18:29.400  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 08:18:29.400  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 08:18:29.400  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 08:18:29.400  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 08:18:29.400  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 08:18:29.400  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 08:18:29.401  7252  7252 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 08:18:29.402  7252  7252 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-16 08:18:29.415  7252  7252 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-16 08:18:29.425  1036  1956 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7272 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 08:18:29.426  1036  1956 I ActivityManager: Killing 6230:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-16 08:18:29.473  1036  2034 W libprocessgroup: failed to open /acct/uid_10097/pid_6230/cgroup.procs: No such file or directory
,08-16 08:18:29.701  1036  1956 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7293 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 08:18:29.709  1036  1956 I ActivityManager: Killing 6717:com.lge.eula/1000 (adj 15): empty #17
08-16 08:18:29.744  7233  7233 E wpa_supplicant: USIM:  scard_init function
08-16 08:18:29.744  7233  7233 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 08:18:29.749  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 08:18:29.749  1036  7244 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 08:18:29.749  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 08:18:29.750  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-16 08:18:29.750  1036  7244 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 08:18:29.750  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 08:18:29.750  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 08:18:29.751  1036  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 08:18:29.752  1036  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 08:18:29.752  1036  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 08:18:29.752  1036  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 08:18:29.752  1036  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 08:18:29.772  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6717/cgroup.procs: No such file or directory
,08-16 08:18:29.785  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=209330  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 08:18:29.786  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=209331  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 08:18:29.789  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:29.789  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:29.790  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.790  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.790  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 08:18:29.790  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.790  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.790  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 08:18:29.792  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:29.794  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:29.795  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 08:18:29.798  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:29.798  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:29.800  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:29.856  7233  7233 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 08:18:29.858  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 08:18:29.859  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 08:18:29.860  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 08:18:29.860  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 08:18:29.860  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:29.860  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:29.863  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=209406  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 08:18:29.864  7233  7233 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 08:18:29.864  7233  7233 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 08:18:29.864  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=209409  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 08:18:29.866  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:29.866  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:29.866  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 08:18:29.866  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 08:18:29.866  1036  7244 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 08:18:29.866  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 08:18:29.866  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-16 08:18:29.866  1036  7244 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 08:18:29.867  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:29.867  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:29.868  1036  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209414
08-16 08:18:29.870  1036  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209415
08-16 08:18:29.871  1036  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209416
08-16 08:18:29.872  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209418
08-16 08:18:29.873  1036  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=209418
,08-16 08:18:29.874  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=209419  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 08:18:29.894  1036  1595 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7324 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 08:18:29.896  1036  1595 I ActivityManager: Killing 6736:com.lge.bnr/1000 (adj 15): empty #17
08-16 08:18:29.933  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 08:18:29.935  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 08:18:29.936  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:29.937  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:29.940  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.940  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.940  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 08:18:29.948  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6736/cgroup.procs: No such file or directory
,08-16 08:18:29.953  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=209498  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 08:18:29.955  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.955  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.955  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 08:18:29.955  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:29.955  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 08:18:29.955  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=209501  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 08:18:29.956  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=209501  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 08:18:29.957  1036  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=209502
08-16 08:18:29.957  1036  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=209503
08-16 08:18:29.958  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-16 08:18:29.959  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:29.959  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:29.959  1036  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 08:18:29.959  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:29.959  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:29.960  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:29.962  1036  1440 I WifiServiceExtension: setVHTCapabilityType  : false
,08-16 08:18:29.969  1036  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-16 08:18:29.969  1036  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 08:18:29.973  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.973  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.973  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 08:18:29.976  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.976  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:29.976  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 08:18:29.977  7324  7324 I art     : Almond Protected OAT
08-16 08:18:29.981  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:29.981  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:29.982  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:29.984  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:29.984  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:29.986  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:29.989  1036  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 08:18:29.990  1036  1527 D ConnectivityService: Got NetworkAgent Messenger
08-16 08:18:29.990  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:18:29.990  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 08:18:29.990  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 08:18:29.990  1036  1527 D ConnectivityService: NetworkAgent connected
08-16 08:18:29.990  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 08:18:29.990  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 08:18:29.995  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 08:18:29.996  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:18:29.996  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 08:18:29.996  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 08:18:29.996  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 08:18:30.001  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 08:18:30.004   317   894 D CommandListener: Setting iface cfg
08-16 08:18:30.006  1036  1440 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 08:18:30.006  1036  7343 D DhcpStateMachine: StoppedState
08-16 08:18:30.007  1036  7343 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.007  1036  7343 D DhcpStateMachine: WaitBeforeStartState
,08-16 08:18:30.007  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=209552  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:30.008  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=209553  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:30.008  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=209553  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:30.009  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:30.009  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:30.009  1036  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:30.010  1036  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:30.010  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:30.011  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:30.011  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-16 08:18:30.011  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 08:18:30.012  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:30.012  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 08:18:30.012  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=209557  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:30.013  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=209558  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:30.013  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=209558  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:30.014  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:163338] from screen [on:0 period:-1845472514] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 08:18:30.015  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1845472513] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 08:18:30.015  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 08:18:30.019  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:30.021  1036  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 08:18:30.021  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.022  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.022  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.022  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.023  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.023  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.023  1036  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 08:18:30.024  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
08-16 08:18:30.024  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
08-16 08:18:30.024  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 08:18:30.025  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 08:18:30.025  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 08:18:30.025  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 08:18:30.025  1036  1440 D WifiNative-wlan0: SET ps 0: returned true
08-16 08:18:30.026  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 08:18:30.026  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 08:18:30.026  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 08:18:30.026  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2362cc49 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.026  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2362cc49 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.027  1036  7343 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.027  1036  7343 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 08:18:30.027  1036  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 08:18:30.027  1036  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 08:18:30.027  1036  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 08:18:30.028   317   894 D CommandListener: Setting iface cfg
08-16 08:18:30.028   317   894 D CommandListener: Trying to bring up wlan0
08-16 08:18:30.029  1036  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 08:18:30.029  7324  7324 D WeatherApplication: removeAccount
08-16 08:18:30.031  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:30.031  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 08:18:30.032  7324  7324 D WeatherApplication: Account.length = 0
08-16 08:18:30.032  7324  7324 E WeatherApplication: OPERATOR:OPEN
08-16 08:18:30.032  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.033  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:30.033  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.033  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 08:18:30.033  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.034  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.034  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.034  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:30.035  1036  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 08:18:30.035  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 08:18:30.036  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 08:18:30.036  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 08:18:30.036  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.036  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.036  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 08:18:30.036  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 08:18:30.036  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 08:18:30.036  7324  7324 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:30
08-16 08:18:30.037  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 08:18:30.037  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 08:18:30.037  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 08:18:30.039  7324  7324 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 08:18:30.039  7324  7324 D Weather.Utils: 2 : All the weather widget is gone.
08-16 08:18:30.042  7324  7324 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 08:18:30.044  7324  7324 D WeatherAncestor: connectivity changed - connection : true
08-16 08:18:30.045  7324  7324 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 08:18:30.052  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:30.053  1036  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 08:18:30.053  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 08:18:30.054  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 08:18:30.054  1036  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 08:18:30.054  1036  1527 D ConnectivityService: ignoring duplicate network state non-change
,08-16 08:18:30.057  7324  7324 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 08:18:30.058  7324  7324 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 08:18:30.058  7324  7324 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 08:18:30.060  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:30.060  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:30.060  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:30.061  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:30.061  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 08:18:30.063  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:30.063  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 08:18:30.064  1036  1527 D ConnectivityService: Adding iface wlan0 to network 101
08-16 08:18:30.066  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:30.066  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:30.067  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 08:18:30.072  1036  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 08:18:30.073  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:30.073  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:30.077  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:30.078  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 08:18:30.078  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:30.078  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:30.078  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 08:18:30.078  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 08:18:30.079  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 08:18:30.084  7324  7324 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 08:18:30.084  7324  7324 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:30
08-16 08:18:30.084  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:30.084  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:18:30.085  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 08:18:30.087  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.087  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.087  1036  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.092  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:30.092  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 08:18:30.092  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:30.093  1036  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 08:18:30.093  1036  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 08:18:30.094  1036  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 08:18:30.094   317   894 E Netd    : netlink response contains error (File exists)
08-16 08:18:30.095  1036  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 08:18:30.095  1036  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 08:18:30.095  1036  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 08:18:30.095  1036  1527 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 08:18:30.097  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 08:18:30.097  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 08:18:30.097  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:30.116  1036  1938 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7347 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 08:18:30.116  1036  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 08:18:30.116  1036  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 08:18:30.116  1036  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 08:18:30.116  1036  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 08:18:30.116  1036  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:30.117  1036  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:30.117  1036  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 08:18:30.117  1036  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.117  1036  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 08:18:30.117  1036  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-16 08:18:30.117  1036  1527 D ConnectivityService:    accepting network in place of null
08-16 08:18:30.117  1036  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.117  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.117  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.117  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 08:18:30.117  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:30.118  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 08:18:30.118  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 08:18:30.118  1036  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 08:18:30.118  1036  1527 D CSLegacyTypeTracker: Sending connected broadcast ,for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 08:18:30.118  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 08:18:30.118  1036  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.119  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 08:18:30.120  1036  1938 I ActivityManager: Killing 2125:com.lge.music/u0a34 (adj 15): empty #17
08-16 08:18:30.122   317  7358 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 08:18:30.122  1036  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:30.122  1036  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 08:18:30.123  1036  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 08:18:30.124  1036  1527 D ConnectivityService: validation of new default Network = false
08-16 08:18:30.125  1036  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 08:18:30.125  1036  1527 D DSQN    : enableDataServiceNotify 
08-16 08:18:30.125  1036  1527 D DSQN    : start dsqn bin
08-16 08:18:30.131  1036  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 08:18:30.131  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 08:18:30.131  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 08:18:30.132  1036  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:30.133  1604  1836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 08:18:30.121  7366  7366 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:30.121  7366  7366 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:30.140   322  1398 V AudioFlinger: 2125 died, releasing its sessions
08-16 08:18:30.140   322  1398 V AudioFlinger:  pid 1855 @ 0
08-16 08:18:30.140   322  1398 V AudioFlinger:  pid 3422 @ 1
08-16 08:18:30.140   322  1398 V AudioFlinger:  pid 3422 @ 2
08-16 08:18:30.147  7366  7366 E DSQN    : DSQN ssw
,08-16 08:18:30.152  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 08:18:30.153  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 08:18:30.153  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 08:18:30.154  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 08:18:30.154  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 08:18:30.154  1036  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 08:18:30.163  1036  1114 W ActivityManager: Failed to clear dns cache for: com.lge.music
,08-16 08:18:30.164  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-16 08:18:30.164  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 08:18:30.164  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 08:18:30.164  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 08:18:30.171  1036  1956 W libprocessgroup: failed to open /acct/uid_10034/pid_2125/cgroup.procs: No such file or directory
08-16 08:18:30.184   317  7358 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 08:18:30.193  1036  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 08:18:30.202  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 08:18:30.203  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:30.204  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:30.217   317  7358 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 08:18:30.228  1819  7371 I CheckinService: active receiver: enabled
08-16 08:18:30.229  1036  7343 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 08:18:30.229  1036  7343 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 08:18:30.229  1036  7343 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 08:18:30.221  7372  7372 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:30.221  7372  7372 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:30.242  7372  7372 I dhcpcd  : version 5.5.6 starting
,08-16 08:18:30.244  7372  7372 E dhcpcd  : get_duid: m
08-16 08:18:30.244  7372  7372 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 08:18:30.244  7372  7372 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 08:18:30.249   317   893 D LGDataListener: argv[0]=dsqncommand
08-16 08:18:30.249   317   893 D LGDataListener: argv[1]=wlan0
08-16 08:18:30.249   317   893 D LGDataListener: argv[2]=1
08-16 08:18:30.249   317   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 08:18:30.249  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 08:18:30.249  1036  1116 D DSQN    : start to monitor internet connection
08-16 08:18:30.252  1819  7371 I CheckinService: Preparing to send checkin request
08-16 08:18:30.252  1819  7371 I EventLogService: Accumulating logs since 1471328157788
08-16 08:18:30.281  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 06:18:30 GMT], X-Android-Received-Millis=[1471328310281], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471328310248]}
08-16 08:18:30.281  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 08:18:30.281  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 08:18:30.282  1036  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 08:18:30.282  1036  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 08:18:30.282  1036  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:30.282  1036  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:30.282  1036  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 08:18:30.282  1036  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 08:18:30.282  1036  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 08:18:30.282  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.282  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:30.282  1036  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:30.282  1036  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.282  1036  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.282  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 08:18:30.283  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 08:18:30.283  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:30.283  1604  1836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 08:18:30.283  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 08:18:30.284  1819  7371 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 08:18:30.287  7372  7372 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 08:18:30.287  7372  7372 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 08:18:30.287  7372  7372 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 08:18:30.288  7372  7372 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 08:18:30.288  7372  7372 D dhcpcd  : wlan0: sending REQUEST (xid 0xa0afd202), next in 3.68 seconds
08-16 08:18:30.293   281   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 08:18:30.293   281   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 08:18:30.293   281   349 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 08:18:30.294  7347  7383 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 08:18:30.295   281   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 08:18:30.295   281   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 08:18:30.295   281   349 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 08:18:30.296  7347  7383 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 08:18:30.301  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 08:18:30.302  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:30.303  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:30.308   281   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 08:18:30.309   281   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 08:18:30.309   281   349 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 08:18:30.309  7347  7385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 08:18:30.310   281   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 08:18:30.310   281   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 08:18:30.310   281   349 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 08:18:30.311  7347  7385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-16 08:18:30.394  1036  1997 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7389 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 08:18:30.420   364   364 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 26.662ms
,08-16 08:18:30.442   364   364 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 20.720ms
,08-16 08:18:30.448  7389  7389 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 08:18:30.448  7389  7389 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 08:18:30.460   364   364 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 17.559ms
08-16 08:18:30.474  7389  7389 I MultiDex: VM with version 2.1.0 has multidex support
08-16 08:18:30.475  7389  7389 I MultiDex: install
08-16 08:18:30.475  7389  7389 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 08:18:30.487  7389  7389 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 08:18:30.526  7347  7347 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 08:18:30.534  7347  7347 I LibraryLoader: Loading: webviewchromium
08-16 08:18:30.538  7347  7347 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 92-96)
,08-16 08:18:30.538  7347  7347 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 08:18:30.546  7347  7347 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2dade29f}
,08-16 08:18:30.549  7347  7347 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 08:18:30.549  7347  7347 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 08:18:30.562  7347  7347 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 08:18:30.563  7347  7347 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 08:18:30.580  7347  7347 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 08:18:30.586  7347  7347 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-16 08:18:30.587  7347  7347 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 08:18:30.589   322  2144 V AudioPolicyService: registerClient() client 0xb558aa20, uid 10093
08-16 08:18:30.590  7347  7426 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 08:18:30.621  7347  7347 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:30.621  7347  7347 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:30.621  7347  7347 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:30.621  7347  7347 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:30.621  7347  7347 I Adreno-EGL: Remote Branch: 
08-16 08:18:30.621  7347  7347 I Adreno-EGL: Local Patches: 
08-16 08:18:30.621  7347  7347 I Adreno-EGL: Reconstruct Branch: 
,08-16 08:18:30.714  7347  7347 I NSApplication: Starting up...
,08-16 08:18:30.768  1036  1924 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7439 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 08:18:30.769  1036  1924 I ActivityManager: Killing 6154:com.android.vending/u0a44 (adj 15): empty #17
,08-16 08:18:30.773  7389  7405 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 08:18:30.773  7389  7405 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 08:18:30.876  1036  2053 W libprocessgroup: failed to open /acct/uid_10044/pid_6154/cgroup.procs: No such file or directory
,08-16 08:18:30.928  7439  7439 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 08:18:31.028  7459  7459 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-16 08:18:31.090  7459  7459 I dex2oat : dex2oat took 61.936ms (threads: 4)
,08-16 08:18:31.095  1036  2053 D WifiServiceImplEx: setWifiEnabled: false pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 08:18:31.095  1036  2053 D WifiService: setWifiEnabled: false pid=6862, uid=10118
08-16 08:18:31.095  1036  2053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 08:18:31.102  7389  7405 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:31.102  7389  7405 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:31.102  7389  7405 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:31.102  7389  7405 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:31.102  7389  7405 I Adreno-EGL: Remote Branch: 
08-16 08:18:31.102  7389  7405 I Adreno-EGL: Local Patches: 
08-16 08:18:31.102  7389  7405 I Adreno-EGL: Reconstruct Branch: 
08-16 08:18:31.105  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 08:18:31.105  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:31.105  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 08:18:31.105  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 08:18:31.106  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-16 08:18:31.106  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:31.106  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:31.107  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 08:18:31.107  1036  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 08:18:31.107  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:18:31.107  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 08:18:31.108  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 08:18:31.108  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 08:18:31.113  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 08:18:31.113  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 08:18:31.113  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.113  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.113  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 08:18:31.114  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 08:18:31.114  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 08:18:31.114  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:31.114   317   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 08:18:31.133  1036  1527 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 08:18:31.136  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 08:18:31.136  1036  1527 D ConnectivityService: ignoring duplicate network state non-change
08-16 08:18:31.136  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-16 08:18:31.138  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 08:18:31.139  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:31.139  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:31.140  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 08:18:31.140  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:31.140  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:31.140  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:31.143  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:31.143  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:31.144  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:31.144  1036  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 08:18:31.144  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.144  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.144  1036  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@26ebd162
08-16 08:18:31.144  1036  1391 D LGWifiP2pService: P2pDisablingState
08-16 08:18:31.144  1036  1391 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.144  1036  1391 D LGWifiP2pService: p2p socket connection lost
08-16 08:18:31.144  1036  1391 D LGWifiP2pService: P2pDisabledState
08-16 08:18:31.145  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:31.149  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 08:18:31.152  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:31.152  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:31.152  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:31.153  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 08:18:31.153  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-16 08:18:31.153  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:31.154  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 08:18:31.154  1943  1943 D WfdsService: WifiP2pState is changed : false
08-16 08:18:31.154  1943  2385 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 08:18:31.154  1943  2385 D WfdsService: Set the WFDS Monitor: false
08-16 08:18:31.154  1036  1559 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.155  1943  2385 D WfdsMonitor: WFDS Monitor is stopped
08-16 08:18:31.155  1943  2385 D WfdsService: STATE : WfdsDisabledState - enter
08-16 08:18:31.155  1943  2386 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 08:18:31.155  1943  7246 D CtrlSupplicant: Received on exit socket, terminate
08-16 08:18:31.155  1943  7246 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 08:18:31.155  1943  7246 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 08:18:31.155  1943  7246 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 08:18:31.157  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 08:18:31.157  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.158  1036  1391 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.158  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 08:18:31.158  7233  7233 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 08:18:31.158  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 08:18:31.158  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 08:18:31.159  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:31.161  1943  2385 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 08:18:31.167  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:31.167  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:31.195  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:31.195   317   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 08:18:31.196  1036  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 08:18:31.196  1036  1527 D DSQN    : disableDataServiceNotify
08-16 08:18:31.196  1036  1527 D DSQN    : stop dsqn bin
08-16 08:18:31.197  1036  1440 D WifiNative-p2p0: doBoolean: TERMINATE
,08-16 08:18:31.200  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 08:18:31.200  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:31.200  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:31.200  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:31.202  1036  1440 D WifiNative-p2p0: TERMINATE: returned true
08-16 08:18:31.202  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:31.202  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:31.202  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 08:18:31.204  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 08:18:31.206  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 08:18:31.206  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:31.206  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:31.206  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:31.206  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:31.206  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:31.206  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 08:18:31.207  1036  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 08:18:31.207  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:31.207  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:31.208  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:31.208  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:31.208  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:31.208  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:31.208  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:31.208  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:31.208  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:31.208  6862  6862 V io.jxco,re.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:31.208  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:31.208  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:31.208  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:31.209  1036  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:31.209  1036  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 08:18:31.209  1036  1905 I art     : Explicit concurrent mark sweep GC freed 100769(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.214ms total 181.846ms
08-16 08:18:31.209  1036  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 08:18:31.209  1036  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 08:18:31.209  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 08:18:31.210  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.210  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:31.210  1036  7342 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 08:18:31.210  1036  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:31.210  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 08:18:31.211  1604  1836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-16 08:18:31.212  1036  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:31.212  1036  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:31.213  1036  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:31.213  1036  1527 D NetworkManagementService: Removing idletimer
08-16 08:18:31.213  1036  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:31.213  1036  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:31.213  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:31.213  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:31.214  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 08:18:31.214  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 08:18:31.214  1036  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 08:18:31.214  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 08:18:31.214  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 08:18:31.214  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 08:18:31.214  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 08:18:31.214  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 08:18:31.216  1036  1390 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 08:18:31.217  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 08:18:31.218  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 08:18:31.220  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 08:18:31.220  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:31.228  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:31.229  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:31.255  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 08:18:31.256  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:31.257  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:31.272  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 08:18:31.272  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:31.273  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:31.312  7233  7233 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 08:18:31.312  7233  7233 I wpa_supplicant: monitor socket send errors count : 1
08-16 08:18:31.312  7233  7233 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-16 08:18:31.314  1036  7244 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 08:18:31.314  1036  7244 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 08:18:31.353  7233  7233 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 08:18:31.354  1036  1118 D Tethering: InitialState.processMessage what=4
08-16 08:18:31.354  7233  7233 W wpa_supplicant: USIM:  scard_deinit function
08-16 08:18:31.355  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 08:18:31.355  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 08:18:31.355  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 08:18:31.355  1036  7244 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 08:18:31.355  1036  7244 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 08:18:31.355  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:31.355  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:31.355  1036  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=210901
08-16 08:18:31.356  1036  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=210901
08-16 08:18:31.356  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:31.357  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:31.357  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=210902  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 08:18:31.358  1036  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=210903  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 08:18:31.359  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 08:18:31.360  6518  6965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 08:18:31.376  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:31.386  7389  7405 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:31.386  7389  7405 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:31.386  7389  7405 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:31.386  7389  7405 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:31.386  7389  7405 I Adreno-EGL: Remote Branch: 
08-16 08:18:31.386  7389  7405 I Adreno-EGL: Local Patches: 
08-16 08:18:31.386  7389  7405 I Adreno-EGL: Reconstruct Branch: 
08-16 08:18:31.389  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 08:18:31.389  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:31.389  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 08:18:31.389  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 08:18:31.392  7167  7167 I AppUp4:CustModeStarterReceiver: onReceive
08-16 08:18:31.394  7167  7167 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d862024
08-16 08:18:31.394  7167  7167 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-16 08:18:31.394  7167  7167 D AppUp4:CustFacade: isPhone : true
08-16 08:18:31.395  7167  7167 D AppUp4:CustModeStarterReceiver: begin check event
08-16 08:18:31.395  7167  7167 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 08:18:31.400  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:31.401  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 08:18:31.405  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:31.409  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:31.416  7203  7203 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 08:18:31.418  4349  7485 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 08:18:31.424  4349  7487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:31.424  4349  7487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 08:18:31.428  7389  7405 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:31.428  7389  7405 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:31.428  7389  7405 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:31.428  7389  7405 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:31.428  7389  7405 I Adreno-EGL: Remote Branch: 
08-16 08:18:31.428  7389  7405 I Adreno-EGL: Local Patches: 
08-16 08:18:31.428  7389  7405 I Adreno-EGL: Reconstruct Branch: 
,08-16 08:18:31.454  7203  7490 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:18:31.457  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 08:18:31.457  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:31.457  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 08:18:31.457  7066  7493 V FormManager: Network unavailable.
08-16 08:18:31.461  7252  7252 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 08:18:31.461  7252  7252 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 08:18:31.462  7066  7492 W FormManager: Network not available. Please check & try again.
08-16 08:18:31.463  7233  7233 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 08:18:31.463  7066  7493 V FormManager: Network unavailable.
08-16 08:18:31.463  1036  7244 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 08:18:31.463  1036  7244 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 08:18:31.463  1036  7244 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 08:18:31.464  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-16 08:18:31.495  7324  7324 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:31
08-16 08:18:31.498  7324  7324 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 08:18:31.498  7324  7324 D Weather.Utils: 2 : All the weather widget is gone.
08-16 08:18:31.500  7324  7324 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 08:18:31.504  7324  7324 D WeatherAncestor: connectivity changed - connection : true
08-16 08:18:31.504  7324  7324 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3dfced42
08-16 08:18:31.505  7324  7324 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 08:18:31.505  7324  7324 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 08:18:31.506  7324  7324 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 08:18:31.506  7324  7324 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 08:18:31.506  7324  7324 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:31
08-16 08:18:31.536   317  7497 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 08:18:31.537  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 08:18:31.537  1819  7371 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-16 08:18:31.540  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 08:18:31.540  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 08:18:31.540  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 08:18:31.540  6953  6953 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 08:18:31.541  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 08:18:31.542  6953  6953 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 08:18:31.542  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 08:18:31.542  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 08:18:31.542  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 08:18:31.542  6953  6953 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 08:18:31.542  6953  6953 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 08:18:31.552  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:31.556  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 08:18:31.563  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.567  1036  1440 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 08:18:31.567  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:31.567  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:31.567  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 08:18:31.572  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-16 08:18:31.572  1943  2385 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 08:18:31.572  1943  2385 D WfdsService: Set the WFDS Monitor: false
08-16 08:18:31.572  1943  2385 D WfdsMonitor: WFDS Monitor is stopped
08-16 08:18:31.575  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:31.576  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 08:18:31.577  1819  7371 I CheckinService: active receiver: disabled
08-16 08:18:31.578  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:18:31.583  7066  7499 W FormManager: Network not available. Please check & try again.
08-16 08:18:31.589  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 08:18:31.589  1036  1473 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 08:18:31.589  1036  1473 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 08:18:31.593  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:31.593  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:31.595  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:31.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:18:31.600  7066  7500 V FormManager: Network unavailable.
08-16 08:18:31.602  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:31.607  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 08:18:31.610  7066  7500 V FormManager: Network unavailable.
08-16 08:18:31.616  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.628  7066  7503 V FormManager: Network unavailable.
08-16 08:18:31.629  7066  7502 W FormManager: Network not available. Please check & try again.
,08-16 08:18:31.632  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:31.633  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:31.634  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:31.636  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:31.642  4349  7504 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 08:18:31.652  4349  7505 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:31.652  4349  7505 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 08:18:31.675  1036  2007 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7506 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 08:18:31.677  7066  7503 V FormManager: Network unavailable.
,08-16 08:18:31.739  7506  7506 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 08:18:31.740  7506  7506 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 08:18:31.746  7506  7506 V [BNRBootReceiver]: Boot Receiver Return
08-16 08:18:31.746  7506  7506 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 08:18:31.751  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:31.761  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:31.766  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.785  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:31.785  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 08:18:31.788  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 08:18:31.791  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 08:18:31.793  6953  6953 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 08:18:31.796  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:31.801  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:31.808  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.815  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:31.815  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:31.816  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 08:18:31.819  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:31.831  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:31.841  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 08:18:31.849  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:31.849  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:31.850  7027  7027 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 08:18:31.854  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:31.860  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:31.867  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.874  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:31.875  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:31.875  7027  7027 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:31.880  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:31.886  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:31.893  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.900  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:31.901  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:31.901  7027  7027 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 08:18:31.905  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:31.912  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:31.917  6764  7140 D UEI.SmartControl: Internal timer expired: 2
08-16 08:18:31.917  6764  7140 D UEI.SmartControl: unbind internal service
08-16 08:18:31.919  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.926  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:31.927  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:31.928  7027  7027 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 08:18:31.932  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:31.941  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:31.950  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:31.959  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:31.959  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:31.960  7027  7027 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 08:18:31.968  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:31.984  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:31.993  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:32.004  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:32.004  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 08:18:32.012  7027  7027 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:32.014  6764  7134 D serial_port: close(fd = 24)
,08-16 08:18:32.018  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:32.020  6764  7134 I UEI.SmartControl: Serial port is closed.
,08-16 08:18:32.033  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:32.041  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 08:18:32.050  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:32.051  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 08:18:32.053  7027  7027 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:32.062  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:32.067  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 08:18:32.078  1036  1506 D WifiService: New client listening to asynchronous messages
08-16 08:18:32.078  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 08:18:32.084  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:32.096  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 08:18:32.106  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:32.106  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:32.107  7027  7027 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 08:18:32.108  7027  7027 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 08:18:32.109  7027  7027 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 08:18:32.114  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:32.118  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 08:18:32.119  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:32.124  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:32.130  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:32.137  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 08:18:32.138  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:32.139  7027  7027 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 08:18:32.140  7027  7027 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 08:18:32.140  7027  7027 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 08:18:32.143  1036  1595 I ActivityManager: Killing 7003:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 08:18:32.389  1036  1052 W libprocessgroup: failed to open /acct/uid_10037/pid_7003/cgroup.procs: No such file or directory
,08-16 08:18:32.399  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 08:18:32.410  2194  2194 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 08:18:32.412  2194  2194 D c       : Getting all permits...
08-16 08:18:32.412  2194  2194 D a       : Opening database...
08-16 08:18:32.417  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-16 08:18:32.417  2194  2194 D a       : Closing database...
08-16 08:18:32.428  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:32.433  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 08:18:32.433  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:32.433  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:32.436  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:32.441  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:32.446  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 08:18:32.446  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 08:18:32.451  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 08:18:32.454  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:32.458  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 08:18:32.458  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:32.458  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:32.463  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:32.470  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:32.477  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:32.477  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 08:18:32.482  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 08:18:32.485  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:32.489  6976  6976 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 08:18:32.489  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:32.489  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:32.494  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:32.502  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:32.507  7027  7027 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:32.508  7027  7027 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:32.509  7027  7027 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 08:18:32.518  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:32.522  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 08:18:32.530  7066  7536 W FormManager: Network not available. Please check & try again.
08-16 08:18:32.533  7066  7537 V FormManager: Network unavailable.
08-16 08:18:32.534  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:32.540  7066  7537 V FormManager: Network unavailable.
,08-16 08:18:32.551  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:32.551  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:32.553  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 08:18:32.555  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:32.560  4349  7538 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 08:18:32.562  4349  7539 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:32.563  4349  7539 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 08:18:32.565  6976  6976 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 08:18:32.565  6976  6976 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 08:18:32.565  6976  6976 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:32.570  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 08:18:32.579  7066  7542 V FormManager: Network unavailable.
,08-16 08:18:32.579  7066  7541 W FormManager: Network not available. Please check & try again.
08-16 08:18:32.581  7066  7542 V FormManager: Network unavailable.
08-16 08:18:32.582  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:32.597  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 08:18:33.022  1036  1440 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1845469506] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 08:18:33.023  1036  1440 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1845469505] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 08:18:33.123  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:33.145  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-16 08:18:33.152  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:33.155  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:33.155  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:33.161  5823  5823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 08:18:33.162  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 08:18:33.182  6518  6965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 08:18:33.193  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:33.213  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 08:18:33.222  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 08:18:33.222  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:33.222  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 08:18:33.222  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 08:18:33.224  7167  7167 I AppUp4:CustModeStarterReceiver: onReceive
08-16 08:18:33.226  7167  7167 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d862024
08-16 08:18:33.226  7167  7167 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 08:18:33.226  7167  7167 D AppUp4:CustFacade: isPhone : true
08-16 08:18:33.226  7167  7167 D AppUp4:CustModeStarterReceiver: begin check event
08-16 08:18:33.226  7167  7167 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 08:18:33.228  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:33.228  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:33.230  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:33.233  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 08:18:33.241  7203  7203 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 08:18:33.242  4349  7558 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 08:18:33.246  4349  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:33.246  4349  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 08:18:33.257  7203  7561 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:33.259  7066  7562 W FormManager: Network not available. Please check & try again.
08-16 08:18:33.263  7066  7563 V FormManager: Network unavailable.
,08-16 08:18:33.265  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 08:18:33.265  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:33.265  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 08:18:33.265  3422  3422 D PhoneState: setPdpRejectCasuse : false
08-16 08:18:33.266  7252  7252 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 08:18:33.266  7252  7252 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 08:18:33.267  7066  7563 V FormManager: Network unavailable.
08-16 08:18:33.273  7324  7324 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:33
08-16 08:18:33.274  7324  7324 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 08:18:33.274  7324  7324 D Weather.Utils: 2 : All the weather widget is gone.
08-16 08:18:33.275  7324  7324 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 08:18:33.275  7324  7324 D WeatherAncestor: connectivity changed - connection : true
08-16 08:18:33.275  7324  7324 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3dfced42
08-16 08:18:33.275  7324  7324 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 08:18:33.275  7324  7324 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 08:18:33.275  7324  7324 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 08:18:33.275  7324  7324 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 08:18:33.275  7324  7324 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:33
,08-16 08:18:33.979  7372  7372 D dhcpcd  : wlan0: sending REQUEST (xid 0xa0afd202), next in 7.03 seconds
08-16 08:18:33.979  7372  7372 E dhcpcd  : wlan0: send_raw_packet: m
08-16 08:18:33.979  7372  7372 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason FAIL
,08-16 08:18:34.110  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:34.110  1036  2036 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 08:18:34.132  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 08:18:34.132  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 08:18:34.132  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 08:18:34.133  1036  1118 D BluetoothManagerService: Message: 1
08-16 08:18:34.133  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 08:18:34.158  1036  1118 D BluetoothManagerService: Message: 20
08-16 08:18:34.159  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28626a09:true
,08-16 08:18:34.164  7113  7113 D BluetoothAdapterState: make
08-16 08:18:34.169  7113  7113 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 08:18:34.169  7113  7113 I bluedroid-qcom: init
08-16 08:18:34.170  7113  7588 I BluetoothAdapterState: Entering OffState
08-16 08:18:34.171  7113  7113 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 08:18:34.171  7113  7113 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 08:18:34.171  7113  7113 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 08:18:34.171  7113  7113 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 08:18:34.171  7113  7113 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 08:18:34.173  7113  7113 I bluedroid-qcom: get_profile_interface socket
08-16 08:18:34.173  7113  7113 I bluedroid-qcom: get_profile_interface map_client
,08-16 08:18:34.178  7113  7592 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 08:18:34.161  7591  7591 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:34.171  7591  7591 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:34.190  7591  7591 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 08:18:34.191  7591  7591 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 08:18:34.191  7591  7591 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 08:18:34.197  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 08:18:34.197  1036  1118 D BluetoothManagerService: Message: 40
08-16 08:18:34.197  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 08:18:34.198  7113  7129 I bluedroid-qcom: config_hci_snoop_log
08-16 08:18:34.199  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 08:18:34.199  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 08:18:34.203  7113  7592 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 08:18:34.203  7591  7591 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 08:18:34.206  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 08:18:34.206  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 08:18:34.211  7113  7588 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 08:18:34.211  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.211  7113  7592 D BluetoothAdapterProperties: Name is: G3
08-16 08:18:34.211  7113  7588 D BluetoothAdapterProperties: Setting state to 11
08-16 08:18:34.212  7113  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 08:18:34.212  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:34.213  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 08:18:34.213  7591  7591 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 08:18:34.213  7591  7591 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 08:18:34.215  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 08:18:34.215  7113  7588 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 08:18:34.219  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.229  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:34.230  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-16 08:18:34.230  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-16 08:18:34.233  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 08:18:34.238  6953  6953 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 08:18:34.238  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:34.238  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:34.240  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 08:18:34.240  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:34.241  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:34.244  5823  5823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 08:18:34.245  1036  1113 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.246  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:34.246  1036  1113 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:34.249  7113  7588 D BluetoothBondStateMachine: make
08-16 08:18:34.253  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:34.253  1036  7343 D NetUtils: dhcp_do_request failed : wlan0 (new)
,08-16 08:18:34.259  7113  7113 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 08:18:34.259  1036  7343 V LgDhcpStateMachineHelper: [getKeyforDhcp] getBSSID, getSSID is null 
08-16 08:18:34.259  1036  7343 E DhcpStateMachine: DHCP failed on wlan0: DHCP result was failed
08-16 08:18:34.260  7113  7113 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:34.260  7113  7113 V BluetoothPbapReceiver: ***********state = 11
08-16 08:18:34.261  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:34.262  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:34.264  7113  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.264  7113  7588 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 08:18:34.264  7113  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.264  7113  7588 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 08:18:34.265  7113  7588 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 08:18:34.266  7113  7606 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 08:18:34.269  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 08:18:34.270  6518  6965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 08:18:34.272  7113  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:34.321  1036  1953 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7612 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 08:18:34.328  7113  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:34.328  5823  5823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 08:18:34.333  7113  7113 D HeadsetService: Received start request. Starting profile...
08-16 08:18:34.334  7113  7113 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 08:18:34.335  7113  7113 D LGBluetoothHfpAdapter: Version 1.6
08-16 08:18:34.337  7113  7588 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 08:18:34.342  7113  7113 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 08:18:34.343  7113  7113 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 08:18:34.344  7113  7113 D HeadsetStateMachine: make
08-16 08:18:34.344  7113  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:34.351  7113  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:34.358  7113  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:34.361  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:34.372  7113  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:34.379  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 08:18:34.379  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.379  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 08:18:34.379  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 08:18:34.382  7167  7167 I AppUp4:CustModeStarterReceiver: onReceive
08-16 08:18:34.384  7113  7113 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:34.384  7113  7113 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 08:18:34.387  7167  7167 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d862024
08-16 08:18:34.387  7167  7167 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 08:18:34.387  7167  7167 D AppUp4:CustFacade: isPhone : true
08-16 08:18:34.388  7167  7167 D AppUp4:CustModeStarterReceiver: begin check event
08-16 08:18:34.388  7167  7167 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 08:18:34.390  7113  7113 D HeadsetStateMachine: max_hf_connections = 1
08-16 08:18:34.390  7113  7113 I bluedroid-qcom: get_profile_interface handsfree
08-16 08:18:34.392  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.392  7113  7113 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 08:18:34.392  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:34.393   322  1397 V AudioPolicyService: registerClient() client 0xb0403d00, uid 1002
08-16 08:18:34.393   322  1398 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 08:18:34.393   322  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 08:18:34.393   322  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 08:18:34.393  7113  7113 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 08:18:34.394   322  2144 V AudioFlinger: registerClient() client 0xb5581568, pid 7113
08-16 08:18:34.394  7113  7588 V LGMDMManager: Create singleton instance
08-16 08:18:34.394  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:34.394  7113  7113 V ToneGenerator: Create Track: 0xb4928080
08-16 08:18:34.394  7113  7113 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 08:18:34.394  7113  7113 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 08:18:34.395   322  2145 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 08:18:34.395   322  2145 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 08:18:34.395   322  2145 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 08:18:34.395   322  2145 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 08:18:34.395  7113  7113 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-16 08:18:34.395   322  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:34.395   322  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:34.395   322  1398 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 08:18:34.395  3422  3441 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:34.395  3422  3441 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:34.396   322  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 08:18:34.396   322  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 08:18:34.396   322  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 08:18:34.396   322  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 08:18:34.396  7113  7113 V AudioSystem: getLatency() output 2, latency 50
08-16 08:18:34.396  1036  1595 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:34.396  1036  1595 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:34.396  7113  7128 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:34.396  7113  7128 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 08:18:34.397   322  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:34.397   322  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:34.397  3422  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:34.397  3422  3440 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:34.398  7113  7129 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:34.398  1604  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:34.398  1604  2099 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:34.398  7113  7129 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 08:18:34.398  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:34.398  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:34.398  1036  1595 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:34.398  1036  1595 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:34.398  7113  7113 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 08:18:34.398  1604  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:34.398  7113  7113 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 08:18:34.398  1604  2099 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:34.398  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:34.398  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:34.399   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 08:18:34.399   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 08:18:34.399   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 08:18:34.399   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 08:18:34.399   322  2145 V AudioFlinger: createTrack() lSessionId: 22
08-16 08:18:34.399  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:34.400  7113  7588 I BluetoothAdapterState: Entering PendingCommandState Stat,e: isTurningOn()=true, isTurningOff()=false
08-16 08:18:34.400  7113  7113 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 08:18:34.400   322  2145 V AudioFlinger: acquiring 22 from 7113, for 7113
08-16 08:18:34.401   322  2145 V AudioFlinger:  added new entry for 22
08-16 08:18:34.403  7113  7113 V ToneGenerator: ToneGenerator INIT OK, time: 213961
08-16 08:18:34.403  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.403  7113  7629 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 08:18:34.404  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.405  7113  7629 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 08:18:34.405  7113  7629 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 08:18:34.405  7113  7113 D A2dpService: Received start request. Starting profile...
08-16 08:18:34.405  7113  7629 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 08:18:34.406   322  2144 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7113
08-16 08:18:34.406  7113  7113 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 08:18:34.406   322  2144 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 08:18:34.406   322  2144 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 08:18:34.406   322  2144 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 08:18:34.406   322  2144 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 08:18:34.406   322  2144 V voice   : voice_set_parameters: exit with code(0)
08-16 08:18:34.406   322  2144 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 08:18:34.407   322  2144 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 08:18:34.407   322  2144 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 08:18:34.407   322  2144 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 08:18:34.407   322  2144 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 08:18:34.407   322  2144 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 08:18:34.407  7113  7629 V ToneGenerator: ToneGenerator destructor
08-16 08:18:34.407  7113  7629 V ToneGenerator: stopTone
08-16 08:18:34.407  7113  7629 V ToneGenerator: Delete Track: 0xb4928080
08-16 08:18:34.407  7113  7113 V Avrcp   : make
08-16 08:18:34.408  7113  7629 V AudioTrack: ~AudioTrack, releasing session id from 7113 on behalf of 7113
08-16 08:18:34.408   322  1398 V AudioFlinger: releasing 22 from 7113 for 7113
08-16 08:18:34.408   322  1398 V AudioFlinger:  decremented refcount to 0
,08-16 08:18:34.408   322  1398 V AudioFlinger: purging stale effects
08-16 08:18:34.408   322  1398 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 08:18:34.408   322  1398 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 08:18:34.408  7113  7113 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 08:18:34.408   322  1274 V AudioPolicyService: AudioCommandThread() waking up
08-16 08:18:34.408  7113  7113 I bluedroid-qcom: get_profile_interface avrcp
08-16 08:18:34.408   322  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 08:18:34.408   322  1274 V AudioPolicyManager: releaseOutput() 2
08-16 08:18:34.408   322  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 08:18:34.408   322  1398 V AudioFlinger: PlaybackThread::Track destructor
08-16 08:18:34.408   322  1398 V AudioFlinger: removeClient_l() pid 7113, calling pid 322
08-16 08:18:34.414  7203  7203 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 08:18:34.413  4349  7632 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 08:18:34.418  7113  7113 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 08:18:34.422  7113  7113 E AudioManager: No RCC entry present to update
08-16 08:18:34.422  7113  7113 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 08:18:34.425  7113  7113 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 08:18:34.428  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 08:18:34.428  7113  7113 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 08:18:34.428  7203  7635 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:18:34.433  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 08:18:34.442  4349  7633 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.442  4349  7633 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 08:18:34.460  1036  7343 V LgDhcpStateMachineHelper: [getKeyforDhcp] getBSSID, getSSID is null 
08-16 08:18:34.460  1036  7343 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 08:18:34.460  1036  7343 D DhcpStateMachine: StoppedState
08-16 08:18:34.460  1036  7343 D DhcpStateMachine: StoppedState{ when=-3s346ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:34.460  1036  7343 D DhcpStateMachine: StoppedState{ when=-3s302ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:34.461  1036  1440 E WifiStateMachine:  InitialState CMD_POST_DHCP_ACTION 2 0 FAIL 
08-16 08:18:34.462  1036  1440 E WifiStateMachine:  DefaultState CMD_POST_DHCP_ACTION 2 0 FAIL 
08-16 08:18:34.475  1036  1440 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
08-16 08:18:34.475  1036  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-16 08:18:34.478  7066  7638 W FormManager: Network not available. Please check & try again.
08-16 08:18:34.478  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 08:18:34.478  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.479  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 08:18:34.479  7612  7612 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 08:18:34.480  7612  7612 W LG Account v2.2: No ProfileInfo entries
08-16 08:18:34.480  7612  7612 I LG Account v2.2: isEnabled: false
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Country: EU
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Operator: OPEN
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Ranking support: false
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Comfort support: false
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Accessory: true
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Health device: true
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Extra Pedometer: false
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Blood glucose device: false
08-16 08:18:34.480  7612  7612 I Feature : [Lifetracker]Device Number: 3
08-16 08:18:34.483  7252  7252 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 08:18:34.484  7252  7252 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 08:18:34.484  7066  7639 V FormManager: Network unavailable.
08-16 08:18:34.498  6953  6953 D BluetoothPermissionRequest: onReceive
,08-16 08:18:34.499  7066  7639 V FormManager: Network unavailable.
,08-16 08:18:34.503  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:34.520  1036  1649 V SIM_STK : Menu title from STK is T-Mobile
08-16 08:18:34.520  1036  1649 V SIM_STK : Menu title from STK is T-Mobile
,08-16 08:18:34.527  7324  7324 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:34
08-16 08:18:34.528  7324  7324 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 08:18:34.528  7324  7324 D Weather.Utils: 2 : All the weather widget is gone.
08-16 08:18:34.529  7324  7324 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 08:18:34.529  7324  7324 D WeatherAncestor: connectivity changed - connection : true
08-16 08:18:34.529  7324  7324 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3dfced42
08-16 08:18:34.529  7324  7324 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 08:18:34.529  7324  7324 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 08:18:34.529  7324  7324 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 08:18:34.529  7324  7324 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 08:18:34.529  7324  7324 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:34
08-16 08:18:34.549  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 08:18:34.551  6518  6965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 08:18:34.562  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:34.572  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 08:18:34.572  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.572  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 08:18:34.572  7167  7167 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 08:18:34.573  1036  1649 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 08:18:34.573  7167  7167 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 08:18:34.577  7167  7167 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d862024
08-16 08:18:34.577  7167  7167 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 08:18:34.577  7167  7167 D AppUp4:CustFacade: isPhone : true
08-16 08:18:34.578  7167  7167 D AppUp4:CustModeStarterReceiver: begin check event
,08-16 08:18:34.578  7167  7167 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 08:18:34.579  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 08:18:34.580  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.581  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 08:18:34.582  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 08:18:34.583  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:34.583  7113  7113 I BluetoothA2dpServiceJni: classInitNative
08-16 08:18:34.583  7113  7113 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 08:18:34.583  7113  7113 D A2dpStateMachine: make
08-16 08:18:34.584  7113  7113 I bluedroid-qcom: get_profile_interface a2dp
08-16 08:18:34.584  7113  7644 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 08:18:34.584  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:34.585  7113  7113 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 08:18:34.585  7113  7113 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 08:18:34.586  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.586  7113  7643 D A2dpStateMachine: Enter Disconnected: -2
08-16 08:18:34.586  7113  7113 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 08:18:34.587  7113  7113 D HidService: Received start request. Starting profile...
08-16 08:18:34.587  7113  7113 I bluedroid-qcom: get_profile_interface hidhost
08-16 08:18:34.587  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.588  7113  7113 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 08:18:34.589  7113  7113 D HealthService: Received start request. Starting profile...
08-16 08:18:34.590  7113  7113 I bluedroid-qcom: get_profile_interface health
08-16 08:18:34.590  7113  7113 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 08:18:34.590  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.590  7113  7113 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 08:18:34.591  7113  7113 D PanService: Received start request. Starting profile...
08-16 08:18:34.591  7113  7113 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 08:18:34.591  7113  7113 I bluedroid-qcom: get_profile_interface pan
08-16 08:18:34.592  7203  7203 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 08:18:34.596  4349  7647 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 08:18:34.597  7113  7113 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 08:18:34.597  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.598  7113  7113 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 08:18:34.598  4349  7650 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:18:34.598  4349  7650 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 08:18:34.604  7113  7113 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 08:18:34.605  7113  7113 D BtGatt.GattService: Received start request. Starting profile...
08-16 08:18:34.605  7113  7113 D BtGatt.GattService: start()
08-16 08:18:34.605  7113  7113 I bluedroid-qcom: get_profile_interface gatt
08-16 08:18:34.605  7113  7113 D BtGatt.AdvertiseManager: advertise manager created
08-16 08:18:34.612  3422  3422 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 08:18:34.612  3422  3422 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:34.612  3422  3422 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 08:18:34.614  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.615  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.615  7113  7113 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 08:18:34.616  7113  7113 V BluetoothMapService: BluetoothMapBinder()
08-16 08:18:34.616  7113  7113 D BluetoothMapService: Received start request. Starting profile...
08-16 08:18:34.616  7113  7113 D BluetoothMapService: start()
08-16 08:18:34.616  7203  7651 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:34.617  7066  7653 W FormManager: Network not available. Please check & try again.
08-16 08:18:34.617  7252  7252 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 08:18:34.617  7252  7252 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 08:18:34.619  7113  7113 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 08:18:34.619  7113  7113 D BluetoothMapEmailAppObserver: createReceiver()
08-16 08:18:34.621  7113  7113 D BluetoothMapEmailAppObserver: initObservers()
08-16 08:18:34.621  7113  7113 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 08:18:34.627  7324  7324 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:34
,08-16 08:18:34.628  7324  7324 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 08:18:34.628  7324  7324 D Weather.Utils: 2 : All the weather widget is gone.
08-16 08:18:34.628  7324  7324 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 08:18:34.628  7324  7324 D WeatherAncestor: connectivity changed - connection : true
08-16 08:18:34.628  7324  7324 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3dfced42
08-16 08:18:34.629  7324  7324 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 08:18:34.629  7324  7324 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 08:18:34.629  7324  7324 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 08:18:34.629  7324  7324 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 08:18:34.629  7324  7324 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:18:34
08-16 08:18:34.629  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:34.629  7113  7113 D HeadsetStateMachine: Proxy object connected
08-16 08:18:34.630  7113  7113 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 08:18:34.630  7113  7113 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 08:18:34.631  7066  7654 V FormManager: Network unavailable.
08-16 08:18:34.634  7113  7113 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 08:18:34.634  7113  7629 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 08:18:34.635  7113  7629 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 08:18:34.635  7113  7629 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 08:18:34.637  7066  7654 V FormManager: Network unavailable.
08-16 08:18:34.637  7113  7113 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 08:18:34.639  7113  7113 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 08:18:34.643  7113  7113 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 08:18:34.645  7113  7113 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 08:18:34.645  7113  7113 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 08:18:34.647  7113  7113 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-16 08:18:34.647  7113  7113 V BluetoothMapService: Handler(): got msg=1
08-16 08:18:34.648  7113  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 08:18:34.648  7113  7588 I bluedroid-qcom: enable
08-16 08:18:34.648  7113  7658 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 08:18:34.648  7113  7658 I bt-btu  : btu_task pending for preload complete event
08-16 08:18:34.648  7113  7588 I bt_hci_bdroid: init
08-16 08:18:34.649  7113  7588 I bt_vendor: bt-vendor : init
08-16 08:18:34.649  7113  7588 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 08:18:34.649  7113  7588 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 08:18:34.649  7113  7588 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 08:18:34.649  7113  7588 D bt_userial_mct: userial_init
08-16 08:18:34.649  7113  7588 D bt_hci_bdroid: set_power 1
08-16 08:18:34.649  7113  7588 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 08:18:34.649  7113  7588 I bt_vendor: Starting hciattach daemon
08-16 08:18:34.650  7113  7588 I bt_vendor: try to set true
08-16 08:18:34.641  7661  7661 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:34.641  7661  7661 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:34.652  7113  7113 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:18:34.641  7661  7661 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:34.641  7661  7661 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:34.653  7113  7113 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 08:18:34.654  7113  7113 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:34.654  7113  7113 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:34.654  7113  7113 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:34.654  7113  7113 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 08:18:34.665  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 08:18:34.724  7668  7668 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 08:18:34.734  7669  7669 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 08:18:34.755  7671  7671 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 08:18:34.767  7672  7672 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 08:18:34.783  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 08:18:34.804  7674  7674 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 08:18:34.822  7676  7676 I libmdmdetect: ESOC framework not supported
08-16 08:18:34.823  7676  7676 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 08:18:34.832  7676  7676 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 08:18:34.832  7676  7676 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 08:18:34.832  7676  7676 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 08:18:34.832  7676  7676 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 08:18:34.832  7676  7676 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 08:18:34.832  7676  7676 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 08:18:34.832  7676  7676 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 08:18:34.872  7676  7677 E QC-QMI  : qmi_client [7676] 14: failed to locate client data
,08-16 08:18:34.873   477   477 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 08:18:34.873   477   477 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-16 08:18:34.943  7681  7681 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 08:18:34.958  7682  7682 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 08:18:35.009  7113  7588 I bt_vendor: bluetooth satus is on
08-16 08:18:35.009  7113  7588 D bt_hci_bdroid: preload
,08-16 08:18:35.009  7113  7660 D bt_userial_mct: userial_open(port:0)
08-16 08:18:35.009  7113  7660 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 08:18:35.013  7113  7660 I bt_vendor: Done intiailizing UART
08-16 08:18:35.013  7113  7660 I bt_vendor: Done intiailizing UART
08-16 08:18:35.013  7113  7660 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 08:18:35.014  7113  7660 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 08:18:35.014  7113  7684 D bt_userial_mct: Entering userial_read_thread()
08-16 08:18:35.014  7113  7658 I bt-btu  : btu_task received preload complete event
08-16 08:18:35.014  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 08:18:35.014  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 08:18:35.017  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 08:18:35.020  7113  7658 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 08:18:35.021  7113  7658 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 08:18:35.108  7113  7658 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-16 08:18:35.108  7113  7658 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d3061 
08-16 08:18:35.108  7113  7658 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d3061 
,08-16 08:18:35.167  7113  7592 E bt-btif : Calling BTA_HhEnable
,08-16 08:18:35.167  7113  7592 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 08:18:35.168  7113  7592 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 08:18:35.178  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-16 08:18:35.178  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 08:18:35.179  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 08:18:35.179  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 08:18:35.179  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 08:18:35.186  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 08:18:35.186  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 08:18:35.194  7113  7592 D BluetoothAdapterProperties: Name is: G3
08-16 08:18:35.196  7113  7592 D BluetoothAdapterProperties: Scan Mode:20
08-16 08:18:35.196  7113  7592 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 08:18:35.196  7113  7592 D bt_hci_bdroid: postload
08-16 08:18:35.196  7113  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 08:18:35.197  7113  7592 D bte_conf: Device ID record 1 : primary
08-16 08:18:35.197  7113  7592 D bte_conf:   vendorId            = 00c4
08-16 08:18:35.197  7113  7592 D bte_conf:   vendorIdSource      = 0001
08-16 08:18:35.197  7113  7592 D bte_conf:   product             = 13a1
08-16 08:18:35.197  7113  7592 D bte_conf:   version             = 1000
08-16 08:18:35.197  7113  7592 D bte_conf:   clientExecutableURL = 
08-16 08:18:35.197  7113  7592 D bte_conf:   serviceDescription  = 
08-16 08:18:35.197  7113  7592 D bte_conf:   documentationURL    = 
08-16 08:18:35.197  7113  7592 D bte_conf: bte_load_did_conf no section named DID2.
08-16 08:18:35.198  7113  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 08:18:35.203  7113  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:35.203  7113  7658 W bt-smp  : Plain text(LSB ~ MSB) = 17 27 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:35.203  7113  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e 15 41 38 c3 d6 2f 1f e9 de cc 79 2e b0 07 85 
,08-16 08:18:35.207  7113  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 08:18:35.208  7113  7658 W bt-btm  : Stopping oneshot timer
08-16 08:18:35.208  7113  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 08:18:35.209  7113  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 08:18:35.209  7113  7588 D BluetoothAdapterProperties: ScanMode =  20
08-16 08:18:35.209  7113  7588 D BluetoothAdapterProperties: State =  11
08-16 08:18:35.209  7113  7588 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 08:18:35.209  7113  7588 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 08:18:35.210  7113  7588 D BluetoothAdapterProperties: Setting state to 12
08-16 08:18:35.210  7113  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 08:18:35.191  7692  7692 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:35.201  7692  7692 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:35.216  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:35.216  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 08:18:35.216  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 08:18:35.217  7113  7588 I BluetoothAdapterState: Entering On State
,08-16 08:18:35.230  7113  7660 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 08:18:35.236  7113  7684 E bt_mct  : hci lib postload completed
08-16 08:18:35.237  7113  7592 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 08:18:35.239  7113  7588 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 08:18:35.239  7113  7588 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 08:18:35.239  7113  7588 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 08:18:35.240  7113  7588 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 08:18:35.261  7113  7592 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 08:18:35.270  7113  7588 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 08:18:35.273  7113  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:35.273  7113  7658 W bt-smp  : Plain text(LSB ~ MSB) = fd 32 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:35.273  7113  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 35 ff cd 9a e8 ad ef 82 15 8b 71 37 81 40 b3 
,08-16 08:18:35.276  7113  7658 W bt-btm  : Stopping oneshot timer
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:35.287  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:18:35.290  7113  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:35.290  7113  7658 W bt-smp  : Plain text(LSB ~ MSB) = 14 0e 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:35.290  7113  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 21 2b 34 b8 cc a4 d3 53 a9 bc 61 df 34 cf 8d 
08-16 08:18:35.290  7113  7658 W bt-btm  : Stopping oneshot timer
08-16 08:18:35.298  7113  7592 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 08:18:35.298  7113  7592 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 08:18:35.301  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:18:35.304  7113  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:35.304  7113  7658 W bt-smp  : Plain text(LSB ~ MSB) = f7 1e 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:35.304  7113  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 dc 36 97 38 d0 8e b4 e4 29 9f 24 a5 5a 03 33 
08-16 08:18:35.306  7113  7658 W bt-btm  : Stopping oneshot timer
08-16 08:18:35.345  7697  7697 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 08:18:35.350  6953  6974 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:35.350  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:35.353  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:35.353  1855  2447 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:35.357  7113  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:35.357  7113  7658 W bt-smp  : Plain text(LSB ~ MSB) = 20 4d 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:35.357  7113  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = ba d7 38 08 b7 81 d9 3c 17 7d c1 5c 8b fa ee bb 
08-16 08:18:35.357  7113  7658 W bt-btm  : Stopping oneshot timer
,08-16 08:18:35.362  1855  1855 D BluetoothHeadset: Proxy object connected
08-16 08:18:35.370  6953  7098 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 08:18:35.376  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:35.376  6953  6953 D BluetoothInputDevice: Proxy object connected
08-16 08:18:35.376  6953  6953 D HidProfile: Bluetooth service connected
08-16 08:18:35.379  1855  1855 D BluetoothHeadset: Proxy object connected
08-16 08:18:35.379  1855  3981 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:35.381  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:35.382  1855  1855 D BluetoothHeadset: Proxy object connected
08-16 08:18:35.382  1036  1036 D BluetoothHeadset: Proxy object connected
08-16 08:18:35.382  6953  6974 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 08:18:35.387  6953  6981 D BluetoothPan: onBluetoothStateChange on: true
08-16 08:18:35.387  6953  6981 D BluetoothPan: onBluetoothStateChange call bindService
08-16 08:18:35.390  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 08:18:35.392  1036  1036 D BluetoothA2dp: Proxy object connected
08-16 08:18:35.397  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 08:18:35.397  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 08:18:35.397  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 08:18:35.398  1036  1118 D BluetoothManagerService: Message: 40
08-16 08:18:35.398  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-16 08:18:35.401  6953  6953 D BluetoothMap: Proxy object connected
08-16 08:18:35.401  6953  6953 D MapProfile: Bluetooth service connected
08-16 08:18:35.401  6953  6953 D BluetoothMap: getConnectedDevices()
08-16 08:18:35.403  7113  7129 V BluetoothMapService: getConnectedDevices()
08-16 08:18:35.405  6953  6953 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 08:18:35.405  6953  6953 D PanProfile: Bluetooth service connected
08-16 08:18:35.410  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:18:35.410  7347  7386 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-16 08:18:35.410  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 08:18:35.411  1943  2173 D LGBluetoothAPIService: Message: 1
08-16 08:18:35.411  1943  2173 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 08:18:35.418  1943  2173 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 08:18:35.419  7113  7113 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:35.419  7113  7113 D BluetoothMapService: STATE_ON
08-16 08:18:35.419  6862  6862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 08:18:35.421  7113  7113 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-16 08:18:35.421  7113  7113 V BluetoothMapService: Handler(): got msg=1
08-16 08:18:35.422  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:35.423  7113  7113 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 08:18:35.423  6953  6953 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 08:18:35.423  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:35.423  7113  7113 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 08:18:35.424  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 08:18:35.424  1943  2173 D LGBluetoothAPIService: Message: 100
08-16 08:18:35.424  1943  2173 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 08:18:35.425  7113  7716 D BluetoothMapMasInstance: MAS initSocket()
08-16 08:18:35.425  7113  7716 D BluetoothMapMasInstance:   masId = 00
08-16 08:18:35.425  7113  7716 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 08:18:35.425  7113  7716 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 08:18:35.425  7113  7716 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 08:18:35.426  1036  1118 D BluetoothManagerService: Message: 30
08-16 08:18:35.429  6953  6953 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 08:18:35.432  1036  1118 D BluetoothManagerService: Message: 30
08-16 08:18:35.432  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 08:18:35.438  6953  6953 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 08:18:35.438  7113  7716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:35.440  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:35.440  7113  7592 D BluetoothAdapterProperties: Scan Mode:21
08-16 08:18:35.440  7113  7113 V BluetoothPbapService: Pbap Service onCreate
08-16 08:18:35.440  7113  7113 V BluetoothPbapService: Starting PBAP service
08-16 08:18:35.440  7113  7716 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 08:18:35.441  7113  7716 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 08:18:35.441  7113  7716 D BluetoothMapMasInstance: Accepting socket connection...
08-16 08:18:35.441  7113  7592 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 08:18:35.442  6953  6953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 08:18:35.443  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:35.444  7113  7113 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 08:18:35.444  7113  7113 V BluetoothPbapService: Pbap Service onBind
,08-16 08:18:35.446  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:35.447  6953  6953 D BluetoothA2dp: Proxy object connected
08-16 08:18:35.447  7113  7113 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:35.448  7113  7113 V BluetoothPbapService: state: 12
08-16 08:18:35.448  7113  7113 V BluetoothPbapService: Handler(): got msg=1
08-16 08:18:35.448  6953  6953 D A2dpProfile: Bluetooth service connected
08-16 08:18:35.450  7113  7113 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 08:18:35.451  7113  7113 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 08:18:35.451  7113  7113 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:35.451  7113  7718 V BluetoothPbapService: Pbap Service initSocket
08-16 08:18:35.451  7113  7113 V BluetoothPbapReceiver: ***********state = 12
08-16 08:18:35.452  1036  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:35.453  7113  7718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:35.454  6953  6953 D BluetoothHeadset: Proxy object connected
08-16 08:18:35.454  6953  6953 D HeadsetProfile: Bluetooth service connected
08-16 08:18:35.455  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 08:18:35.455  2194  2194 D c       : Getting all permits...
08-16 08:18:35.455  2194  2194 D a       : Opening database...
,08-16 08:18:35.458  7113  7718 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 08:18:35.458  7113  7718 V BluetoothPbapService: Succeed to create listening socket 
08-16 08:18:35.458  7113  7718 V BluetoothPbapService: Accepting socket connection...
08-16 08:18:35.459  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-16 08:18:35.460  2194  2194 D a       : Closing database...
08-16 08:18:35.463  6953  6953 D BluetoothPbap: Proxy object connected
08-16 08:18:35.464  6953  6953 D PbapServerProfile: Bluetooth service connected
08-16 08:18:35.466  6953  6953 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:18:35.471  6953  6953 D BluetoothPermissionRequest: onReceive
08-16 08:18:35.473  6953  6953 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 08:18:35.475  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:35.478  7113  7113 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-16 08:18:35.479  7113  7113 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 08:18:35.487  7113  7113 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 08:18:35.516  7113  7113 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 08:18:35.516  7113  7113 V BtOppService: onCreate
,08-16 08:18:35.523  7113  7113 V BluetoothOppNotification: send message
08-16 08:18:35.529  7113  7113 V BtOppService: Starting RfcommListener
,08-16 08:18:35.538  7113  7723 V BtOppService: Deleted complete outbound shares, number =  0
08-16 08:18:35.538  7113  7113 D BluetoothOppPreference: Dumping Names:  
08-16 08:18:35.538  7113  7113 D BluetoothOppPreference: {}
08-16 08:18:35.539  7113  7113 D BluetoothOppPreference: Dumping Channels:  
08-16 08:18:35.539  7113  7113 D BluetoothOppPreference: {}
08-16 08:18:35.539  7113  7113 V BtOppService: onStartCommand
08-16 08:18:35.540  7113  7723 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 08:18:35.542  7113  7723 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-16 08:18:35.542  7113  7726 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 08:18:35.544  7113  7723 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c111c7f on behalf of 
08-16 08:18:35.544  7113  7726 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 08:18:35.546  7113  7113 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:35.546  7113  7113 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 08:18:35.550  7113  7726 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2332044c on behalf of 
08-16 08:18:35.551  7113  7113 V BluetoothOppNotification: new notify threadi!
08-16 08:18:35.553  7113  7113 V BluetoothOppNotification: send delay message
08-16 08:18:35.553  7113  7726 V BluetoothOppNotification: update too frequent, put in queue
08-16 08:18:35.554  7113  7113 V BtOppService: start RfcommListener
08-16 08:18:35.554  7113  7727 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 08:18:35.556  7113  7727 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18632c95 on behalf of 
08-16 08:18:35.556  7113  7726 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-16 08:18:35.557  7113  7727 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 08:18:35.559  7113  7726 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 08:18:35.559  7113  7113 V BtOppService: RfcommListener started
08-16 08:18:35.560  7113  7726 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a0d91aa on behalf of 
08-16 08:18:35.560  7113  7113 V BtOppService: ContentObserver received notification
08-16 08:18:35.561  7113  7113 V BtOppService: ContentObserver received notification
08-16 08:18:35.561  7113  7727 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 08:18:35.562  7113  7728 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 08:18:35.563  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:35.563  7113  7727 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1da5019b on behalf of 
08-16 08:18:35.564  7113  7726 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 08:18:35.564  7113  7728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:35.565  7113  7727 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 08:18:35.565  7113  7728 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 08:18:35.565  7113  7728 V BtOppRfcommListener: Started RFCOMM listener....
08-16 08:18:35.565  7113  7728 I BtOppRfcommListener: Accept thread started.
08-16 08:18:35.566  7113  7728 V BtOppRfcommListener: Accepting connection...
08-16 08:18:35.566  7113  7726 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 08:18:35.566  7113  7726 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ea11938 on behalf of 
08-16 08:18:35.567  7113  7727 V BluetoothOppNotification: outbound notification was removed.
08-16 08:18:35.567  7113  7727 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 08:18:35.567  7113  7726 V BluetoothOppNotification: update too frequent, put in queue
08-16 08:18:35.568  7113  7726 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 08:18:35.569  7113  7727 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3996fd11 on behalf of 
08-16 08:18:35.569  7113  7727 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 08:18:35.573  7113  7727 V BluetoothOppNotification: inbound notification was removed.
08-16 08:18:35.573  7113  7727 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 08:18:35.575  7113  7727 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@128b1e76 on behalf of 
08-16 08:18:35.592  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
,08-16 08:18:35.592  7113  7113 V BluetoothFtpService: Ftp Service onCreate
08-16 08:18:35.592  7113  7113 I BluetoothFtpService: Ftp Service onCreate
,08-16 08:18:35.593  7113  7113 V BluetoothFtpService: Ftp Service onStartCommand
08-16 08:18:35.593  7113  7113 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:35.593  7113  7113 V BluetoothFtpService: Starting Listening on sockets
08-16 08:18:35.593  7113  7113 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 08:18:35.593  7113  7113 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:35.593  7113  7113 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:35.593  7113  7113 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:35.593  7113  7113 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 08:18:35.593  7113  7113 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 08:18:35.595  7113  7113 V BluetoothFtpService: Handler(): got msg=1
08-16 08:18:35.596  7113  7113 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 08:18:35.596  7113  7113 V BluetoothFtpService: Ftp Service initSocket
08-16 08:18:35.598  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:35.599  7113  7113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:35.602  7113  7113 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 08:18:35.603  7113  7113 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 08:18:35.604  7113  7729 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 08:18:35.618  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
,08-16 08:18:35.619  7113  7113 V BluetoothSapService: Sap Service onCreate
08-16 08:18:35.621  7113  7113 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:35.621  7113  7113 V BluetoothSapService: state: 12
08-16 08:18:35.621  7113  7113 V BluetoothSapService: Starting SAP server process
08-16 08:18:35.623  7113  7113 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 08:18:35.625  7113  7731 V BluetoothSapService: Sap Service initRfcommSocket
08-16 08:18:35.611  7730  7730 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:35.625  1036  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:35.611  7730  7730 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:35.626  7113  7731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:35.627  7113  7731 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 08:18:35.628  7113  7731 V BluetoothSapService: Succeed to create listening socket 
,08-16 08:18:35.628  7113  7731 V BluetoothSapService: Accepting socket connection...
08-16 08:18:35.647  7730  7730 V BT_SAP  : Event pipe created
08-16 08:18:35.647  7730  7730 V BT_SAP  : create_server_socket qcom.sap.server
08-16 08:18:35.647  7730  7730 V BT_SAP  : created socket fd 6
,08-16 08:18:36.150  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:36.150  1036  1391 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 08:18:36.205  1036  1440 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 08:18:36.207  1036  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 08:18:36.376  1036  1973 I ActivityManager: Killing 7506:com.lge.bnr/1000 (adj 15): empty #17
,08-16 08:18:36.407  1036  1738 W libprocessgroup: failed to open /acct/uid_1000/pid_7506/cgroup.procs: No such file or directory
,08-16 08:18:36.536  1036  1924 I ActivityManager: Killing 6764:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 08:18:36.555  7113  7113 V BluetoothOppNotification: new notify threadi!
08-16 08:18:36.556  7113  7113 V BluetoothOppNotification: send delay message
,08-16 08:18:36.564  7113  7741 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 08:18:36.574  7113  7741 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13980913 on behalf of 
08-16 08:18:36.575  7113  7741 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 08:18:36.580  7027  7027 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 08:18:36.581  7027  7027 W System.err: android.os.DeadObjectException
08-16 08:18:36.581  7027  7027 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 08:18:36.581  7027  7027 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 08:18:36.581  7027  7027 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 08:18:36.581  7027  7027 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 08:18:36.581  7027  7027 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 08:18:36.581  7027  7027 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 08:18:36.582  7027  7027 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 08:18:36.582  7027  7027 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 08:18:36.582  7027  7027 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 08:18:36.582  7027  7027 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 08:18:36.582  7027  7027 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:18:36.582  7027  7027 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 08:18:36.582  7027  7027 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 08:18:36.582  7027  7027 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 08:18:36.582  7027  7027 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 08:18:36.582  7027  7027 W System.err: android.os.DeadObjectException
08-16 08:18:36.582  7027  7027 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 08:18:36.583  7027  7027 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 08:18:36.583  7027  7027 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 08:18:36.583  7027  7027 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 08:18:36.583  7027  7027 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 08:18:36.583  7027  7027 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 08:18:36.583  7027  7027 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 08:18:36.583  7027  7027 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 08:18:36.583  7027  7027 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 08:18:36.583  7027  7027 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 08:18:36.583  7027  7027 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:18:36.583  7027  7027 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 08:18:36.583  7027  7027 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 08:18:36.583  7027  7027 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 08:18:36.583  7027  7027 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 08:18:36.584  7027  7027 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 08:18:36.587  7113  7741 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 08:18:36.595  7113  7741 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@231d750 on behalf of 
08-16 08:18:36.595  7113  7741 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 08:18:36.597  7113  7741 V BluetoothOppNotification: outbound notification was removed.
08-16 08:18:36.597  7113  7741 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 08:18:36.599  7113  7741 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36b33d49 on behalf of 
08-16 08:18:36.599  7113  7741 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 08:18:36.603  7113  7741 V BluetoothOppNotification: inbound notification was removed.
08-16 08:18:36.603  7113  7741 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 08:18:36.604  7113  7741 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1673864e on behalf of 
08-16 08:18:36.608  1036  1649 W libprocessgroup: failed to open /acct/uid_1000/pid_6764/cgroup.procs: No such file or directory
08-16 08:18:36.608  1036  1649 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-16 08:18:36.612  7027  7027 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 08:18:36.612  7027  7027 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 08:18:36.661  1036  2053 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7742 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 08:18:36.719  7027  7027 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 08:18:36.774  7742  7742 D UEI.SmartControl: Quickset Services start...
08-16 08:18:36.776  7742  7742 I UEI.SmartControl: Manufacture = LGE
08-16 08:18:36.776  7742  7742 D UEI.SmartControl: Id = LGNevo
08-16 08:18:36.778  7742  7742 D UEI.SmartControl: File observer start...
08-16 08:18:36.779  7742  7742 E UEI.SmartControl: IR Port is disabled: false
,08-16 08:18:36.779  7742  7742 D UEI.SmartControl: Starting file observer...
08-16 08:18:36.780  7742  7742 D UEI.SmartControl: Extracting JNI libs...
08-16 08:18:36.780  7742  7742 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 08:18:36.877  7742  7742 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 08:18:36.877  7742  7742 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 08:18:36.878  7742  7742 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 08:18:36.919  7742  7742 I UEI.SmartControl: --- Selecting new region: 6
,08-16 08:18:36.923  7742  7742 I UEI.SmartControl: Model = LG-D855
,08-16 08:18:36.925  7742  7742 D UEI.SmartControl: QS Service created
08-16 08:18:36.945  7742  7742 I UEI.SmartControl: Service initServices...
,08-16 08:18:36.954  7742  7742 D UEI.SmartControl: QS start get config
08-16 08:18:37.045  7742  7742 D UEI.SmartControl: Loading JNI Libs...
,08-16 08:18:37.144  1036  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:37.144  1036  2034 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21358748 mBinding = false
,08-16 08:18:37.168  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 08:18:37.169  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 08:18:37.172  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 08:18:37.174  1036  1118 D BluetoothManagerService: Message: 2
08-16 08:18:37.175  1036  1118 D BluetoothManagerService: Sending off request.
08-16 08:18:37.175  7113  7609 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 08:18:37.176  7113  7588 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 08:18:37.176  7113  7588 D BluetoothAdapterProperties: Setting state to 13
08-16 08:18:37.176  7113  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 08:18:37.177  7113  7588 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 08:18:37.177  7113  7588 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 08:18:37.178  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:37.178  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 08:18:37.178  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 08:18:37.178  7113  7592 D BluetoothAdapterProperties: Scan Mode:20
08-16 08:18:37.179  7113  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 08:18:37.180  7113  7588 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 08:18:37.180  7113  7716 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 08:18:37.181  7113  7729 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:37.184  7113  7728 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 08:18:37.184  7113  7731 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:37.185  7113  7718 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:18:37.186  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 08:18:37.186  7113  7658 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 08:18:37.189  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 08:18:37.189  7113  7658 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 08:18:37.190  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:37.190  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:37.192  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 08:18:37.193  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.194  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:37.194  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:37.198  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:37.198  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:37.198  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:37.198  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:37.198  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:37.198  6862,  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:18:37.198  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:37.198  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:37.198  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:37.199  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:18:37.199  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:18:37.206  7113  7113 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.206  7113  7113 D BluetoothMapService: STATE_TURNING_OFF
08-16 08:18:37.206  7113  7113 V BluetoothMapService: Handler(): got msg=4
08-16 08:18:37.207  7113  7113 D BluetoothMapService: MAP Service closeService in
08-16 08:18:37.207  7113  7113 D BluetoothMapMasInstance: MAP Service shutdown
08-16 08:18:37.207  7113  7113 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 08:18:37.207  7113  7113 V BluetoothMapService: MAP Service closeService out
08-16 08:18:37.208  7113  7113 V BtOppService: Receiver DISABLED_ACTION 
08-16 08:18:37.208  7113  7113 I BtOppRfcommListener: stopping Accept Thread
08-16 08:18:37.208  7113  7113 V BtOppRfcommListener: close mBtServerSocket
08-16 08:18:37.209  7113  7728 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 08:18:37.212  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:37.212  7113  7113 V BtOppRfcommListener: waiting for thread to terminate
08-16 08:18:37.212  7113  7113 V BtOppRfcommListener: done waiting for thread to terminate
,08-16 08:18:37.215  6953  6953 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 08:18:37.216  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:37.216  7113  7113 V BtOppService: onDestroy
08-16 08:18:37.218  6953  6953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 08:18:37.221  7113  7113 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 08:18:37.395  1036  1649 I art     : Explicit concurrent mark sweep GC freed 91457(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.237ms total 170.158ms
,08-16 08:18:37.407  7113  7113 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 08:18:37.407  7113  7113 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.407  7113  7113 V BluetoothPbapReceiver: ***********state = 13
08-16 08:18:37.408  7113  7113 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-16 08:18:37.411  6953  6953 D DockEventReceiver: finishStartingService: stopping service
08-16 08:18:37.412  7113  7113 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.412  7113  7113 V BluetoothPbapService: state: 13
08-16 08:18:37.412  7113  7113 V BluetoothPbapService: Pbap Service closeService in
08-16 08:18:37.413  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 08:18:37.413  7113  7113 V BluetoothPbapService: successfully stopped pbap service
08-16 08:18:37.413  7113  7113 V BluetoothPbapService: Pbap Service closeService out
08-16 08:18:37.413  7113  7113 V BluetoothPbapService: Pbap Service onDestroy
08-16 08:18:37.413  7113  7113 V BluetoothPbapService: Pbap Service closeService in
08-16 08:18:37.413  7113  7113 V BluetoothPbapService: Pbap Service closeService out
08-16 08:18:37.414  7113  7113 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 08:18:37.414  6953  6953 D BluetoothPbap: Proxy object disconnected
08-16 08:18:37.414  6953  6953 D PbapServerProfile: Bluetooth service disconnected
08-16 08:18:37.424  6953  6953 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 08:18:37.427  6953  6953 D BluetoothPermissionRequest: onReceive
08-16 08:18:37.427  6953  6953 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 08:18:37.432  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:37.434  7113  7113 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 08:18:37.435  7113  7113 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 08:18:37.435  7113  7113 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 08:18:37.438  7113  7113 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.439  7113  7113 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 08:18:37.439  7113  7113 V BluetoothFtpService: Ftp Service onStartCommand
08-16 08:18:37.439  7113  7113 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.439  7113  7113 V BluetoothFtpService: Ftp Service closeService
08-16 08:18:37.440  7113  7113 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 08:18:37.442  7113  7113 V BluetoothFtpService: successfully stopped ftp service
08-16 08:18:37.442  7113  7113 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 08:18:37.442  7113  7113 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:37.442  7113  7113 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:37.442  7113  7113 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.442  7113  7113 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 08:18:37.442  7113  7113 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 08:18:37.443  7113  7113 V BluetoothFtpService: Ftp Service onDestroy
08-16 08:18:37.443  7113  7113 V BluetoothFtpService: Ftp Service closeService
08-16 08:18:37.448  7113  7113 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:37.448  7113  7113 V BluetoothSapService: state: 13
08-16 08:18:37.448  7113  7113 V BluetoothSapService: Stopping SAP server process
08-16 08:18:37.449  7113  7113 V BluetoothSapService: Sap Service closeSapService in
08-16 08:18:37.449  7113  7113 V BluetoothSapService: Close listen Socket : 
08-16 08:18:37.450  7113  7113 V BluetoothSapService: Close rfcomm Socket : 
08-16 08:18:37.450  7113  7113 V BluetoothSapService: Close sapd  Socket : 
,08-16 08:18:37.454  7113  7113 V BluetoothSapService: Sap Service closeSapService out
08-16 08:18:37.455  7113  7113 V BluetoothSapService: Sap Service onDestroy
08-16 08:18:37.455  7113  7113 V BluetoothSapService: Sap Service closeSapService in
08-16 08:18:37.455  7113  7113 V BluetoothSapService: Close listen Socket : 
08-16 08:18:37.455  7113  7113 V BluetoothSapService: Close rfcomm Socket : 
08-16 08:18:37.455  7113  7113 V BluetoothSapService: Close sapd  Socket : 
08-16 08:18:37.455  7113  7113 V BluetoothSapService: Sap Service closeSapService out
08-16 08:18:37.525  7742  7742 I UEI.SmartControl: Supports setup maps: true
,08-16 08:18:37.528  7742  7742 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 08:18:37.528  7742  7742 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 08:18:37.528  7742  7742 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 08:18:37.528  7742  7742 I UEI.SmartControl: ### init IR Blaster...
08-16 08:18:37.533  7742  7742 D serial_port: Configuring serial port
08-16 08:18:37.537  7742  7742 E UEI.SmartControl: UEIBLaster setting for 616
08-16 08:18:37.537  7742  7742 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 08:18:37.537  7742  7742 I UEI.SmartControl: configuring settings for MAXQ616
08-16 08:18:37.538  7742  7742 I UEI.SmartControl: Get version...
08-16 08:18:37.554  7742  7797 D UEI.SmartControl: serial port data available: 21
,08-16 08:18:37.581  7742  7742 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-16 08:18:37.581  7742  7742 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 08:18:37.581  7742  7742 I UEI.SmartControl: QS saving settings...
08-16 08:18:37.585  7742  7742 D UEI.SmartControl: IR Blaster version: 25672567
08-16 08:18:37.603  7742  7797 D UEI.SmartControl: serial port data available: 4
,08-16 08:18:37.646  7742  7800 I UEI.SmartControl: Device manager: loading config....
,08-16 08:18:37.648  7742  7800 D UEI.SmartControl: ----------- loading internal config...
08-16 08:18:37.652  7742  7742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 08:18:37.658  7742  7742 E UEI.SmartControl: Services init done
08-16 08:18:37.658  7742  7742 D UEI.SmartControl: QS Service init finished
08-16 08:18:37.662  7742  7742 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 08:18:37.662  7742  7742 D UEI.SmartControl: QS Service version code: 201091
08-16 08:18:37.663  7742  7742 D UEI.SmartControl: Service requested: Control
,08-16 08:18:37.669  7742  7742 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 08:18:37.669  7742  7800 E UEI.SmartControl: Loading SETTINGS...
08-16 08:18:37.672  7027  7027 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 08:18:37.673  7742  7757 I UEI.SmartControl: ------ IControl API: 11
08-16 08:18:37.674  1036  2007 I ActivityManager: Killing 7027:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 08:18:37.676  7742  7757 I UEI.SmartControl: Registering callback...
08-16 08:18:37.681  7742  7800 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 08:18:37.700  7742  7799 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 08:18:37.701  7742  7799 D UEI.SmartControl: -----service ready thread exits
,08-16 08:18:37.784  1036  1051 W libprocessgroup: failed to open /acct/uid_10112/pid_7027/cgroup.procs: No such file or directory
,08-16 08:18:37.795  7742  7742 D UEI.SmartControl: Internal service binding...
,08-16 08:18:38.096  7113  7592 D bt_hci_bdroid: cleanup
,08-16 08:18:38.105  7113  7684 I bt_userial_mct: exiting userial_read_thread
08-16 08:18:38.105  7113  7684 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 08:18:38.107  7113  7660 I bt_lpm  : LPM is already off!!!
08-16 08:18:38.107  7113  7658 W bt-btif : ag scb idx 1 not allocated
08-16 08:18:38.107  7113  7658 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 08:18:38.107  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:38.107  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:38.107  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:38.107  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:38.107  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:38.107  7113  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 08:18:38.108  7113  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 08:18:38.108  7113  7658 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 08:18:38.111  7113  7592 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 08:18:38.112  7113  7660 I bt_vendor: hw_epilog_process
08-16 08:18:38.113  7113  7592 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 08:18:38.113  7113  7592 D bt_userial_mct: userial_close
08-16 08:18:38.113  7113  7592 E bt_userial_mct: pthread_join() FAILED result:3
08-16 08:18:38.113  7113  7592 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 08:18:38.123  7113  7592 D bt_hci_bdroid: set_power 0
08-16 08:18:38.123  7113  7592 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 08:18:38.127  7113  7592 I bt_vendor: bluetooth satus is on
08-16 08:18:38.127  7113  7592 I bt_vendor: bt-vendor : resetting BT status
08-16 08:18:38.128  7113  7592 I bt_vendor: Starting hciattach daemon
08-16 08:18:38.128  7113  7592 I bt_vendor: try to set false
08-16 08:18:38.130  7113  7592 I bt_vendor: Starting hciattach daemon
08-16 08:18:38.130  7113  7592 I bt_vendor: try to set false
08-16 08:18:38.131  7113  7592 I bt_vendor: cleanup
08-16 08:18:38.131  7113  7658 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 08:18:38.132  7113  7592 I GKI_LINUX: GKI_exit_task 0 done
08-16 08:18:38.132  7113  7592 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 08:18:38.134  7113  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 08:18:38.138  7113  7113 D HeadsetService: Received stop request...Stopping profile...
,08-16 08:18:38.142  7113  7113 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 08:18:38.143  7113  7113 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 08:18:38.143  7113  7629 D HeadsetStateMachine: Exit Disconnected: -1
08-16 08:18:38.147  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:38.149  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:38.149  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:38.149  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:38.150  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-16 08:18:38.150  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 08:18:38.154  7113  7588 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 08:18:38.154  7113  7113 D A2dpService: Received stop request...Stopping profile...
08-16 08:18:38.155  7113  7643 D A2dpStateMachine: Exit Disconnected: -1
08-16 08:18:38.156  7113  7113 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 08:18:38.159  7113  7113 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 08:18:38.159  7113  7113 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 08:18:38.159  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:38.162  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-16 08:18:38.162  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 08:18:38.163  7113  7113 D HidService: Received stop request...Stopping profile...
08-16 08:18:38.163  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
,08-16 08:18:38.168  7113  7113 D HealthService: Received stop request...Stopping profile...
08-16 08:18:38.169  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:38.171  7113  7113 D PanService: Received stop request...Stopping profile...
08-16 08:18:38.171  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:38.172  7113  7113 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 08:18:38.174  7113  7113 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 08:18:38.174  7113  7113 D BtGatt.GattService: stop()
08-16 08:18:38.174  7113  7113 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 08:18:38.175  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
,08-16 08:18:38.179  7113  7113 D BluetoothMapService: Received stop request...Stopping profile...
08-16 08:18:38.179  7113  7113 D BluetoothMapService: stop()
08-16 08:18:38.180  7113  7113 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 08:18:38.180  7113  7113 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 08:18:38.181  7113  7113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3dfced42
08-16 08:18:38.182  7113  7113 D HeadsetStateMachine: Unbinding service...
08-16 08:18:38.183  7113  7113 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 08:18:38.183  7113  7113 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 08:18:38.183  7113  7113 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 08:18:38.183  7113  7113 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 08:18:38.184  7113  7113 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 08:18:38.184  7113  7113 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 08:18:38.184  7113  7113 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 08:18:38.184  7113  7113 I BluetoothA2dpServiceJni: cleanupNative
08-16 08:18:38.184  7113  7644 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 08:18:38.185  7113  7113 I GKI_LINUX: GKI_exit_task 2 done
08-16 08:18:38.185  7113  7113 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 08:18:38.185  7113  7113 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 08:18:38.185  7113  7113 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 08:18:38.186  7113  7113 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 08:18:38.186  7113  7113 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 08:18:38.186  7113  7113 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 08:18:38.186  7113  7113 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 08:18:38.186  7113  7113 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 08:18:38.190  7113  7113 V BluetoothMapService: Handler(): got msg=4
08-16 08:18:38.190  7113  7113 D BluetoothMapService: MAP Service closeService in
08-16 08:18:38.190  7113  7113 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 08:18:38.190  7113  7113 V BluetoothMapService: MAP Service closeService out
,08-16 08:18:38.197  7113  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 08:18:38.197  7113  7588 D BluetoothAdapterProperties: Setting state to 10
08-16 08:18:38.197  7113  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 08:18:38.198  7113  7113 D BluetoothMapService: cleanup()
08-16 08:18:38.198  7113  7113 D BluetoothMapService: MAP Service closeService in
08-16 08:18:38.198  7113  7113 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 08:18:38.198  7113  7113 V BluetoothMapService: MAP Service closeService out
08-16 08:18:38.200  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:38.200  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 08:18:38.200  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 08:18:38.201  7113  7588 I BluetoothAdapterState: Entering OffState
08-16 08:18:38.202  6953  6974 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:38.202  6953  6974 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 08:18:38.204  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 08:18:38.207  6953  6974 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 08:18:38.207  1855  3981 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:38.208  6953  6974 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 08:18:38.209  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:38.209  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:18:38.209  6953  6974 D BluetoothMap: onBluetoothStateChange: up=false
08-16 08:18:38.210  6953  6974 D BluetoothPan: onBluetoothStateChange on: false
08-16 08:18:38.210  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 08:18:38.211  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 08:18:38.211  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 08:18:38.213  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 08:18:38.213  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 08:18:38.213  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21358748 mBinding = false
08-16 08:18:38.214  1036  1118 D BluetoothManagerService: Sending unbind request.
08-16 08:18:38.218  7113  7592 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 08:18:38.221  7113  7113 I GKI_LINUX: GKI_exit_task 1 done
08-16 08:18:38.221  7113  7113 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 08:18:38.222  7113  7113 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 08:18:38.222  7113  7113 I art     : --- WEIRD: removing null entry 248
08-16 08:18:38.222  7113  7113 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 08:18:38.222  7113  7113 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 08:18:38.223  7113  7113 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 08:18:38.224  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 08:18:38.226  7113  7113 I art     : System.exit called, status: 0
08-16 08:18:38.226  7113  7113 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 08:18:38.246   322  2144 V AudioFlinger: 7113 died, releasing its sessions
08-16 08:18:38.246   322  2144 V AudioFlinger:  pid 1855 @ 0
08-16 08:18:38.246   322  2144 V AudioFlinger:  pid 3422 @ 1
08-16 08:18:38.246   322  2144 V AudioFlinger:  pid 3422 @ 2
,08-16 08:18:38.250  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 08:18:38.250  1943  2173 D LGBluetoothAPIService: Message: 101
08-16 08:18:38.250  1943  2173 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 08:18:38.251  1943  2173 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 08:18:38.251  1943  2173 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 08:18:38.252  6953  6953 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 08:18:38.261  1036  1905 I ActivityManager: Process com.android.bluetooth (pid 7113) has died
08-16 08:18:38.261  1036  1905 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-16 08:18:38.262  1036  1905 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-16 08:18:38.270  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:38.271  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 08:18:38.271  1943  2173 D LGBluetoothAPIService: Message: 2
08-16 08:18:38.271  1943  2173 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 08:18:38.272  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:38.273  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:38.278  6953  6953 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 08:18:38.278  6953  6953 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-16 08:18:38.284  6953  6953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 08:18:38.301  1604  1604 D BluetoothAdapter: 990594108: getState() :  mService = null. Returning STATE_OFF
08-16 08:18:38.301  1604  1604 D BluetoothAdapter: 990594108: getState() :  mService = null. Returning STATE_OFF
,08-16 08:18:38.346  1036  1924 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7825 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 08:18:38.348  6953  6953 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:18:38.394  7825  7825 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 08:18:38.395  7825  7825 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 08:18:38.395  7825  7825 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 08:18:38.396  7825  7825 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 08:18:38.416  7825  7825 D BluetoothAdapterApp: Loading JNI Library
,08-16 08:18:38.454  7825  7825 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f7deaea Instance Count = 1
,08-16 08:18:38.460  7825  7825 D BluetoothAdapterApp: onCreate
08-16 08:18:38.487  7825  7825 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 08:18:38.488  7825  7825 D ProfileConfigQcom: Adding HeadsetService
08-16 08:18:38.488  7825  7825 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 08:18:38.489  7825  7825 D ProfileConfigQcom: Adding A2dpService
08-16 08:18:38.489  7825  7825 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 08:18:38.490  7825  7825 D ProfileConfigQcom: Adding HidService
08-16 08:18:38.490  7825  7825 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 08:18:38.491  7825  7825 D ProfileConfigQcom: Adding HealthService
,08-16 08:18:38.495  7825  7825 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 08:18:38.497  7825  7825 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 08:18:38.497  7825  7825 D ProfileConfigQcom: Adding PanService
08-16 08:18:38.497  7825  7825 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 08:18:38.497  7825  7825 D ProfileConfigQcom: Adding GattService
08-16 08:18:38.497  7825  7825 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 08:18:38.498  7825  7825 D ProfileConfigQcom: Adding BluetoothMapService
08-16 08:18:38.498  7825  7825 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 08:18:38.499  7825  7825 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 08:18:38.500  7825  7825 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:38.500  7825  7825 V BluetoothPbapReceiver: ***********state = 10
08-16 08:18:38.503  7825  7825 V LGMDMManagerInternal: Create singleton instance
,08-16 08:18:38.598  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:18:38.607  6953  6953 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 08:18:38.613  7825  7825 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 08:18:38.613  7825  7825 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 08:18:38.616  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 08:18:38.616  1943  2173 D LGBluetoothAPIService: Message: 100
,08-16 08:18:38.616  1943  2173 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 08:18:38.622  6953  6953 D BluetoothPermissionRequest: onReceive
08-16 08:18:38.627  6953  6953 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 08:18:38.627  6953  6953 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-16 08:18:38.632  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:38.638  7825  7825 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 08:18:38.642  7825  7825 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:18:38.649  7825  7825 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 08:18:38.649  7825  7825 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:38.649  7825  7825 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:38.651  7825  7825 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:38.651  7825  7825 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 08:18:38.655  7046  7046 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 08:18:40.175  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 08:18:40.175  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:18:40.300  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 08:18:40.362  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 08:18:40.374   364   364 I art     : Background concurrent mark sweep GC freed 788(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.481ms total 40.521ms
,08-16 08:18:40.399  1036  1114 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7858 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 08:18:40.413  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 08:18:40.468  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 08:18:40.468  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 08:18:40.494  1036  1036 D administrator: Handling package changes for user 0
,08-16 08:18:40.496  7858  7858 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 08:18:40.500  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 08:18:40.572  7858  7858 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:40.573  7858  7858 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:40.616  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 08:18:40.616  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 08:18:40.667  7858  7902 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 08:18:40.668  7858  7902 I Babel   : MmsConfig.loadMmsSettings
,08-16 08:18:40.670  7858  7902 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 08:18:40.670  7858  7902 I Babel   : MmsConfig.loadFromDatabase
,08-16 08:18:40.688  7858  7902 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 08:18:40.689  7858  7902 I Babel   : MmsConfig.loadFromResources
08-16 08:18:40.695  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:40.702  7858  7902 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 08:18:40.702  7858  7902 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 08:18:40.702  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 08:18:40.710  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 08:18:40.713  7858  7900 W AudioCapabilities: Unsupported mime audio/evrc
08-16 08:18:40.715  7858  7900 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 08:18:40.715  2477  2477 V GmsNetworkLocationProvi: DISABLE
08-16 08:18:40.716  7858  7900 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 08:18:40.724  7858  7900 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 08:18:40.725  7858  7900 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 08:18:40.725  7858  7900 W AudioCapabilities: Unsupported mime audio/evrc
08-16 08:18:40.728  7858  7858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:18:40.745  7858  7900 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 08:18:40.749  7858  7900 W VideoCapabilities: Unsupported mime video/divx
,08-16 08:18:40.755  1036  1113 D LocationProviderProxy: applying state to connected service
08-16 08:18:40.756  2477  2477 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 08:18:40.757  7858  7900 W VideoCapabilities: Unsupported mime video/divx311
08-16 08:18:40.764  7858  7900 W VideoCapabilities: Unsupported mime video/divx4
,08-16 08:18:40.768  1819  7905 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 08:18:40.768  1819  7905 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 08:18:40.772  7167  7167 I AppUp4:CustModeStarterReceiver: onReceive
08-16 08:18:40.775  7858  7900 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 08:18:40.776  7167  7167 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1d862024
08-16 08:18:40.776  7167  7167 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 08:18:40.776  7167  7167 D AppUp4:CustFacade: isPhone : true
08-16 08:18:40.776  7167  7167 D AppUp4:CustModeStarterReceiver: begin check event
08-16 08:18:40.776  7167  7167 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 08:18:40.778  1819  4681 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 08:18:40.789  7858  7900 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 08:18:40.795  7858  7900 W AudioCapabilities: Unsupported mime audio/eac3
08-16 08:18:40.796  7858  7900 W AudioCapabilities: Unsupported mime audio/ac3
08-16 08:18:40.802  7858  7900 W AudioCapabilities: Unsupported mime audio/g726
08-16 08:18:40.803  7858  7900 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 08:18:40.805  7858  7900 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 08:18:40.807  7858  7900 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 08:18:40.809  7858  7900 W VideoCapabilities: Unsupported mime video/theora
08-16 08:18:40.811  7858  7900 W VideoCapabilities: Unsupported mime video/mjpg
08-16 08:18:40.820  1036  2007 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7909 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 08:18:40.843  1036  1997 I ActivityManager: Killing 6976:com.lge.sync/1000 (adj 15): empty #17
,08-16 08:18:40.852  1036  1506 D WifiService: Client connection lost with reason: 4
,08-16 08:18:40.947  1036  1649 W libprocessgroup: failed to open /acct/uid_1000/pid_6976/cgroup.procs: No such file or directory
08-16 08:18:40.974  7909  7909 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:40.974  7909  7909 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:40.974  7909  7909 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 08:18:40.975  7909  7909 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 08:18:40.975  7909  7909 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 08:18:41.024  7909  7909 I SystemConfig: BUILD Country: EU
,08-16 08:18:41.024  7909  7909 I SystemConfig: BUILD Operator: OPEN
,08-16 08:18:41.058  1036  1953 I ActivityManager: Killing 7203:com.lge.email/u0a23 (adj 15): empty #17,
,08-16 08:18:41.195  1036  1738 W libprocessgroup: failed to open /acct/uid_10023/pid_7203/cgroup.procs: No such file or directory
,08-16 08:18:41.211  7909  7927 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-16 08:18:41.213  7909  7927 I SystemConfig: existFile = false
08-16 08:18:41.213  7909  7927 I SystemConfig: canReadFile = false
08-16 08:18:41.214  7909  7927 I SystemConfig: systemFeature RCS result false
08-16 08:18:41.214  7909  7927 D SystemConfig: refreshRcsSupport() :false
,08-16 08:18:41.221  1036  1527 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-16 08:18:41.271  1036  1953 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7929 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 08:18:41.366  7929  7929 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:41.367  7929  7929 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 08:18:41.367  7929  7929 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 08:18:41.367  7929  7929 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 08:18:41.471  7929  7929 I AppConfig: Total System Memory = 2995761152
,08-16 08:18:41.483  7929  7929 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 08:18:41.586  1036  1956 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7951 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 08:18:41.590  1036  1956 I ActivityManager: Killing 7066:com.lge.formmanager/u0a26 (adj 15): empty #17
08-16 08:18:41.694  1036  1052 W libprocessgroup: failed to open /acct/uid_10026/pid_7066/cgroup.procs: No such file or directory
,08-16 08:18:41.901  7951  7951 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 08:18:42.025  7951  7951 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 08:18:42.025  7951  7951 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:42.079  7951  7951 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 08:18:42.100  7951  7951 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 08:18:42.101  7951  7951 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 08:18:42.118  7951  7951 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 08:18:42.118  7951  7951 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 08:18:42.141  1036  1973 I ActivityManager: Killing 6518:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 08:18:42.176  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6518/cgroup.procs: No such file or directory
,08-16 08:18:42.184  3488  4523 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 08:18:42.185  3488  4523 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@21261e08 on behalf of 7951
08-16 08:18:42.187  4621  7991 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 08:18:42.235  1036  1649 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7992 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 08:18:42.281  7951  7951 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 08:18:42.314  7951  7951 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 08:18:42.344  7992  7992 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 08:18:42.367  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 08:18:42.367  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 08:18:42.367  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 08:18:42.367  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 08:18:42.367  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 08:18:42.367  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 08:18:42.390  1036  1938 I ActivityManager: Killing 7252:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-16 08:18:42.516  1036  2053 W libprocessgroup: failed to open /acct/uid_10046/pid_7252/cgroup.procs: No such file or directory
,08-16 08:18:42.645  7742  7801 D UEI.SmartControl: Internal timer expired: 1
,08-16 08:18:42.647  7742  7801 D UEI.SmartControl: unbind internal service
08-16 08:18:42.654  7742  7742 D UEI.SmartControl: Service.onUnbind: IControl
08-16 08:18:42.654  7742  7742 D UEI.SmartControl: Service.onDestroy
08-16 08:18:42.654  7742  7742 D UEI.SmartControl: Lock is in USE false
08-16 08:18:42.654  7742  7742 D UEI.SmartControl: unbind internal service
08-16 08:18:42.654  7742  7742 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@f171a90
08-16 08:18:42.655  7742  7742 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 08:18:42.655  7742  7742 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 08:18:42.655  7742  7742 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 08:18:42.655  7742  7742 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 08:18:42.655  7742  7742 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 08:18:42.655  7742  7742 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 08:18:42.655  7742  7742 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,08-16 08:18:42.655  7742  7742 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 08:18:42.655  7742  7742 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:18:42.655  7742  7742 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-16 08:18:42.655  7742  7742 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 08:18:42.655  7742  7742 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:18:42.655  7742  7742 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-16 08:18:42.655  7742  7742 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 08:18:42.655  7742  7742 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 08:18:42.656  7742  7742 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@f171a90
08-16 08:18:42.658  7742  7742 D serial_port: close(fd = 25)
,08-16 08:18:42.670  7742  7742 I UEI.SmartControl: Serial port is closed.
08-16 08:18:42.670  7742  7742 I UEI.SmartControl: Serial port is closed.
08-16 08:18:42.670  7742  7742 D UEI.SmartControl: Blaster closed
08-16 08:18:42.670  7742  7742 D UEI.SmartControl: Shut down QS...
08-16 08:18:42.672  7742  7742 D UEI.SmartControl: Stopping QS lib
08-16 08:18:42.672  7742  7742 D UEI.SmartControl: QS lib stop result = true
08-16 08:18:42.673  7742  7742 D UEI.SmartControl: Stopped QS lib
08-16 08:18:42.673  7742  7742 D UEI.SmartControl: Stopped file observer...
08-16 08:18:42.673  7742  7742 D UEI.SmartControl: QS shutdown complete
08-16 08:18:42.792  1036  1924 V SIM_STK : Menu title from STK is T-Mobile
,08-16 08:18:42.816  4621  7991 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 629 ms] updated apps [took 629 ms] 
,08-16 08:18:43.190  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 08:18:43.190  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26d7caec added. We now have 6 listener(s)
,08-16 08:18:43.190  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:18:43.204  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:43.204  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@283d7eb5 added. We now have 7 listener(s)
08-16 08:18:43.204  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:43.208  6862  6923 I System.out: IsBluetoothEnabled
08-16 08:18:43.209  1036  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:43.209  1036  1953 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-16 08:18:43.209  1036  1118 D BluetoothManagerService: Message: 2
08-16 08:18:43.213  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:43.215  1036  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:43.215  1036  1738 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 08:18:43.234  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 08:18:43.234  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 08:18:43.235  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 08:18:43.235  1036  1118 D BluetoothManagerService: Message: 1
08-16 08:18:43.235  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 08:18:43.260  1036  1118 D BluetoothManagerService: Message: 20
08-16 08:18:43.260  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39680547:true
,08-16 08:18:43.265  7825  7825 D BluetoothAdapterState: make
08-16 08:18:43.269  7825  7825 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 08:18:43.270  7825  7825 I bluedroid-qcom: init
08-16 08:18:43.271  7825  8036 I BluetoothAdapterState: Entering OffState
08-16 08:18:43.271  7825  7825 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 08:18:43.272  7825  7825 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 08:18:43.272  7825  7825 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 08:18:43.272  7825  7825 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 08:18:43.272  7825  7825 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 08:18:43.274  7825  7825 I bluedroid-qcom: get_profile_interface socket
08-16 08:18:43.274  7825  7825 I bluedroid-qcom: get_profile_interface map_client
,08-16 08:18:43.278  7825  8040 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 08:18:43.261  8039  8039 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:43.284  7825  8040 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 08:18:43.271  8039  8039 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:43.294  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-16 08:18:43.296  1036  1118 D BluetoothManagerService: Message: 40
08-16 08:18:43.296  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 08:18:43.298  7825  7845 I bluedroid-qcom: config_hci_snoop_log
08-16 08:18:43.299  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 08:18:43.299  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 08:18:43.301  8039  8039 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 08:18:43.301  8039  8039 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 08:18:43.301  8039  8039 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 08:18:43.304  8039  8039 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 08:18:43.308  8039  8039 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 08:18:43.308  8039  8039 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-16 08:18:43.313  7825  8036 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 08:18:43.314  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 08:18:43.314  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 08:18:43.315  7825  8040 D BluetoothAdapterProperties: Name is: G3
08-16 08:18:43.315  7825  8036 D BluetoothAdapterProperties: Setting state to 11
08-16 08:18:43.315  7825  8036 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 08:18:43.316  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:43.316  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 08:18:43.316  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 08:18:43.318  7825  8036 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 08:18:43.324  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:18:43.327  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 08:18:43.329  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:43.334  6953  6953 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 08:18:43.340  7825  7825 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 08:18:43.340  7825  7825 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:43.340  7825  7825 V BluetoothPbapReceiver: ***********state = 11
,08-16 08:18:43.360  7825  8036 D BluetoothBondStateMachine: make
,08-16 08:18:43.362  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:18:43.367  7825  8036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.367  7825  8036 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 08:18:43.367  7825  8036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.367  7825  8036 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 08:18:43.369  7825  8036 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 08:18:43.371  7825  8053 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 08:18:43.375  7825  8036 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 08:18:43.378  6953  6953 D BluetoothPermissionRequest: onReceive
08-16 08:18:43.381  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:43.385  7825  8036 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:43.387  7825  7825 D HeadsetService: Received start request. Starting profile...
,08-16 08:18:43.387  7825  7825 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 08:18:43.388  7825  7825 D LGBluetoothHfpAdapter: Version 1.6
08-16 08:18:43.391  7825  7825 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 08:18:43.392  7825  7825 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 08:18:43.393  7825  7825 D HeadsetStateMachine: make
08-16 08:18:43.394  7825  8036 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:43.400  7825  8036 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 08:18:43.406  7825  8036 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:43.411  7825  8036 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 08:18:43.417  7825  8036 E BluetoothAdapterService: File transfer profiles supported!!
08-16 08:18:43.430  7825  8036 V LGMDMManager: Create singleton instance
,08-16 08:18:43.432  7825  8036 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 08:18:43.432  7825  7825 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:43.433  7825  7825 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 08:18:43.438  7825  7825 D HeadsetStateMachine: max_hf_connections = 1
08-16 08:18:43.438  7825  7825 I bluedroid-qcom: get_profile_interface handsfree
08-16 08:18:43.440  7825  7825 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 08:18:43.441   322   322 V AudioPolicyService: registerClient() client 0xb558a760, uid 1002
08-16 08:18:43.441   322   322 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 08:18:43.441   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 08:18:43.441   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 08:18:43.442  7825  7825 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 08:18:43.442   322  1397 V AudioFlinger: registerClient() client 0xb1783400, pid 7825
08-16 08:18:43.443   322  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:43.443   322  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:43.443  7825  7825 V ToneGenerator: Create Track: 0xb4928a80
08-16 08:18:43.443  7825  7825 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 08:18:43.443  7825  7825 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 08:18:43.443   322  2144 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 08:18:43.443   322  2144 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
,08-16 08:18:43.443   322  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 08:18:43.443   322  2144 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 08:18:43.443  3422  3441 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:43.443  7825  7846 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:43.443  7825  7846 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 08:18:43.443  3422  3441 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:43.444   322  1398 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 08:18:43.444   322  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:43.444   322  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:43.444   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 08:18:43.444   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 08:18:43.444   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 08:18:43.444  3422  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:43.445   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 08:18:43.445  3422  3440 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:43.445  7825  7846 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:43.445  7825  7846 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 08:18:43.445  7825  7825 V AudioSystem: getLatency() output 2, latency 50
08-16 08:18:43.445  7825  7825 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 08:18:43.445  7825  7825 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 08:18:43.445   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 08:18:43.445   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 08:18:43.445   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 08:18:43.445   322  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 08:18:43.445   322  2145 V AudioFlinger: createTrack() lSessionId: 23
08-16 08:18:43.445  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:43.445  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:43.446  1604  3133 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:43.446  1855  2447 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 08:18:43.446  1855  2447 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:43.446  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:43.446  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:43.446  1855  2447 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:43.446  1855  2447 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:43.446  1604  3133 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 08:18:43.446  1604  3133 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 08:18:43.446  1604  3133 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 08:18:43.446  7825  7825 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 08:18:43.447   322  2145 V AudioFlinger: acquiring 23 from 7825, for 7825
08-16 08:18:43.447   322  2145 V AudioFlinger:  added new entry for 23
08-16 08:18:43.447  7825  7825 V ToneGenerator: ToneGenerator INIT OK, time: 223005
08-16 08:18:43.447  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-,16 08:18:43.448  7825  8058 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 08:18:43.448  7825  8058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 08:18:43.448  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.450  7825  8058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 08:18:43.450  7825  7825 D A2dpService: Received start request. Starting profile...
08-16 08:18:43.451  7825  7825 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 08:18:43.451  7825  8058 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 08:18:43.452   322  2144 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7825
08-16 08:18:43.452   322  2144 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 08:18:43.452   322  2144 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 08:18:43.452   322  2144 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 08:18:43.452   322  2144 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 08:18:43.452   322  2144 V voice   : voice_set_parameters: exit with code(0)
08-16 08:18:43.452   322  2144 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 08:18:43.452   322  2144 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 08:18:43.452   322  2144 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 08:18:43.452   322  2144 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 08:18:43.452   322  2144 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 08:18:43.452   322  2144 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 08:18:43.452  7825  7825 V Avrcp   : make
08-16 08:18:43.452  7825  8058 V ToneGenerator: ToneGenerator destructor
08-16 08:18:43.452  7825  8058 V ToneGenerator: stopTone
08-16 08:18:43.452  7825  8058 V ToneGenerator: Delete Track: 0xb4928a80
08-16 08:18:43.453   322  1398 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 08:18:43.453   322  1398 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 08:18:43.453   322  1274 V AudioPolicyService: AudioCommandThread() waking up
08-16 08:18:43.453   322  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 08:18:43.453   322  1274 V AudioPolicyManager: releaseOutput() 2
08-16 08:18:43.453   322  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 08:18:43.453   322  1398 V AudioFlinger: PlaybackThread::Track destructor
08-16 08:18:43.453   322  1398 V AudioFlinger: removeClient_l() pid 7825, calling pid 322
08-16 08:18:43.453  7825  7825 D Avrcp   : [BTUI] Use Native AVRCP : init jni
,08-16 08:18:43.453  7825  7825 I bluedroid-qcom: get_profile_interface avrcp
08-16 08:18:43.453  1036  1905 W Process : Unable to open /proc/8060/status
08-16 08:18:43.453  7825  8058 V AudioTrack: ~AudioTrack, releasing session id from 7825 on behalf of 7825
08-16 08:18:43.453   322  2145 V AudioFlinger: releasing 23 from 7825 for 7825
08-16 08:18:43.453   322  2145 V AudioFlinger:  decremented refcount to 0
08-16 08:18:43.454   322  2145 V AudioFlinger: purging stale effects
,08-16 08:18:43.462  7825  7825 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 08:18:43.466  7825  7825 E AudioManager: No RCC entry present to update
08-16 08:18:43.466  7825  7825 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 08:18:43.469  7825  7825 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-16 08:18:43.471  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-16 08:18:43.471  7825  7825 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 08:18:43.475  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 08:18:43.629  1036  1738 V SIM_STK : Menu title from STK is T-Mobile
,08-16 08:18:43.629  1036  1738 V SIM_STK : Menu title from STK is T-Mobile
,08-16 08:18:43.763  1036  2034 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 08:18:43.772  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 08:18:43.780  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 08:18:43.783  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 08:18:43.783  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 08:18:43.783  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 08:18:43.783  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 08:18:43.783  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 08:18:43.783  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 08:18:43.783  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 08:18:43.784  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 08:18:43.784  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 08:18:43.784  7825  7825 I BluetoothA2dpServiceJni: classInitNative
08-16 08:18:43.785  7825  7825 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 08:18:43.785  7825  7825 D A2dpStateMachine: make
08-16 08:18:43.787  7825  7825 I bluedroid-qcom: get_profile_interface a2dp
08-16 08:18:43.787  7825  8070 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 08:18:43.790  7825  7825 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 08:18:43.790  7825  7825 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 08:18:43.791  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.792  7825  8069 D A2dpStateMachine: Enter Disconnected: -2
,08-16 08:18:43.792  7825  7825 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 08:18:43.795  7825  7825 D HidService: Received start request. Starting profile...
08-16 08:18:43.795  7825  7825 I bluedroid-qcom: get_profile_interface hidhost
08-16 08:18:43.795  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.796  7825  7825 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 08:18:43.798  7825  7825 D HealthService: Received start request. Starting profile...
08-16 08:18:43.799  7825  7825 I bluedroid-qcom: get_profile_interface health
08-16 08:18:43.800  7825  7825 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 08:18:43.800  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.801  7825  7825 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 08:18:43.803  7825  7825 D PanService: Received start request. Starting profile...
08-16 08:18:43.803  7825  7825 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 08:18:43.803  7825  7825 I bluedroid-qcom: get_profile_interface pan
08-16 08:18:43.810  7825  7825 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 08:18:43.810  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
,08-16 08:18:43.811  7825  7825 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 08:18:43.817  7825  7825 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 08:18:43.818  7825  7825 D BtGatt.GattService: Received start request. Starting profile...
08-16 08:18:43.818  7825  7825 D BtGatt.GattService: start()
08-16 08:18:43.818  7825  7825 I bluedroid-qcom: get_profile_interface gatt
08-16 08:18:43.819  7825  7825 D BtGatt.AdvertiseManager: advertise manager created
08-16 08:18:43.824  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.826  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.826  7825  7825 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 08:18:43.827  7825  7825 V BluetoothMapService: BluetoothMapBinder()
,08-16 08:18:43.828  7825  7825 D BluetoothMapService: Received start request. Starting profile...
08-16 08:18:43.828  7825  7825 D BluetoothMapService: start()
08-16 08:18:43.832  7825  7825 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 08:18:43.832  7825  7825 D BluetoothMapEmailAppObserver: createReceiver()
08-16 08:18:43.833  7825  7825 D BluetoothMapEmailAppObserver: initObservers()
08-16 08:18:43.833  7825  7825 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 08:18:43.847  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:43.847  7825  7825 D HeadsetStateMachine: Proxy object connected
08-16 08:18:43.849  7825  7825 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 08:18:43.849  7825  7825 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 08:18:43.851  7825  8058 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 08:18:43.852  7825  8058 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 08:18:43.852  7825  8058 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 08:18:43.857  7825  7825 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 08:18:43.860  7825  7825 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:43.866  7825  7825 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 08:18:43.869  7825  7825 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 08:18:43.874  7825  7825 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 08:18:43.874  7825  7825 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 08:18:43.878  7825  7825 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 08:18:43.881  7825  7825 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 08:18:43.882  7825  7825 V BluetoothMapService: Handler(): got msg=1
,08-16 08:18:43.886  7825  7825 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 08:18:43.886  7825  7825 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:43.886  7825  7825 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:43.886  7825  7825 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:43.887  7825  7825 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 08:18:43.888  7825  8036 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 08:18:43.888  7825  8036 I bluedroid-qcom: enable
08-16 08:18:43.888  7825  8036 I bt_hci_bdroid: init
08-16 08:18:43.893  7825  8036 I bt_vendor: bt-vendor : init
08-16 08:18:43.893  7825  8036 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 08:18:43.893  7825  8036 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 08:18:43.893  7825  8036 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 08:18:43.893  7825  8036 D bt_userial_mct: userial_init
08-16 08:18:43.894  7825  8077 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 08:18:43.894  7825  8077 I bt-btu  : btu_task pending for preload complete event
,08-16 08:18:43.894  7825  8036 D bt_hci_bdroid: set_power 1
,08-16 08:18:43.894  7825  8036 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 08:18:43.894  7825  8036 I bt_vendor: Starting hciattach daemon
08-16 08:18:43.894  7825  8036 I bt_vendor: try to set true
08-16 08:18:43.881  8080  8080 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:43.881  8080  8080 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:43.922  8081  8081 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 08:18:43.995  8087  8087 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 08:18:44.021  8088  8088 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 08:18:44.047  8090  8090 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 08:18:44.060  8091  8091 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 08:18:44.072  8092  8092 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 08:18:44.085  8093  8093 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 08:18:44.109  8095  8095 I libmdmdetect: ESOC framework not supported
,08-16 08:18:44.110  8095  8095 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-16 08:18:44.118  8095  8095 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 08:18:44.118  8095  8095 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 08:18:44.118  8095  8095 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 08:18:44.118  8095  8095 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 08:18:44.118  8095  8095 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 08:18:44.118  8095  8095 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 08:18:44.118  8095  8095 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 08:18:44.158  8095  8096 E QC-QMI  : qmi_client [8095] 15: failed to locate client data
,08-16 08:18:44.162   477   477 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 08:18:44.162   477   477 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-16 08:18:44.194  8097  8097 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 08:18:44.208  8098  8098 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 08:18:44.251  7825  8036 I bt_vendor: bluetooth satus is on
08-16 08:18:44.251  7825  8036 D bt_hci_bdroid: preload
08-16 08:18:44.251  7825  8079 D bt_userial_mct: userial_open(port:0)
08-16 08:18:44.251  7825  8079 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 08:18:44.255  7825  8079 I bt_vendor: Done intiailizing UART
08-16 08:18:44.256  7825  8079 I bt_vendor: Done intiailizing UART
08-16 08:18:44.256  7825  8079 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 08:18:44.256  7825  8079 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 08:18:44.257  7825  8077 I bt-btu  : btu_task received preload complete event
08-16 08:18:44.257  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 08:18:44.257  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 08:18:44.258  7825  8100 D bt_userial_mct: Entering userial_read_thread()
08-16 08:18:44.262  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 08:18:44.271  7825  8077 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 08:18:44.338  7825  8077 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 08:18:44.338  7825  8077 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d3061 
08-16 08:18:44.338  7825  8077 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d3061 
,08-16 08:18:44.386  7825  8040 E bt-btif : Calling BTA_HhEnable,
,08-16 08:18:44.386  7825  8040 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 08:18:44.387  7825  8040 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17,
,08-16 08:18:44.396  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 08:18:44.396  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 08:18:44.396  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 08:18:44.396  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 08:18:44.396  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 08:18:44.399  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 08:18:44.399  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 08:18:44.400  7825  8040 D BluetoothAdapterProperties: Name is: G3
08-16 08:18:44.402  7825  8040 D BluetoothAdapterProperties: Scan Mode:20
08-16 08:18:44.402  7825  8040 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 08:18:44.402  7825  8040 D bt_hci_bdroid: postload
08-16 08:18:44.404  7825  8079 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 08:18:44.407  7825  8040 D bte_conf: Device ID record 1 : primary
08-16 08:18:44.407  7825  8040 D bte_conf:   vendorId            = 00c4
08-16 08:18:44.407  7825  8040 D bte_conf:   vendorIdSource      = 0001
08-16 08:18:44.407  7825  8040 D bte_conf:   product             = 13a1
08-16 08:18:44.407  7825  8040 D bte_conf:   version             = 1000
08-16 08:18:44.407  7825  8040 D bte_conf:   clientExecutableURL = 
08-16 08:18:44.407  7825  8040 D bte_conf:   serviceDescription  = 
08-16 08:18:44.407  7825  8040 D bte_conf:   documentationURL    = 
08-16 08:18:44.407  7825  8040 D bte_conf: bte_load_did_conf no section named DID2.
08-16 08:18:44.408  7825  8077 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 08:18:44.408  7825  8079 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 08:18:44.411  7825  8036 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 08:18:44.411  7825  8036 D BluetoothAdapterProperties: ScanMode =  20
08-16 08:18:44.411  7825  8036 D BluetoothAdapterProperties: State =  11
08-16 08:18:44.411  7825  8036 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 08:18:44.412  7825  8036 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 08:18:44.412  7825  8036 D BluetoothAdapterProperties: Setting state to 12
08-16 08:18:44.412  7825  8036 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 08:18:44.412  7825  8040 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 08:18:44.413  7825  8040 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 08:18:44.401  8105  8105 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 08:18:44.411  8105  8105 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:44.429  1036  1118 D BluetoothManagerService: Message: 60
08-16 08:18:44.429  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 08:18:44.429  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 08:18:44.430  7825  8079 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 08:18:44.439  7825  8079 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 08:18:44.443  7825  8100 E bt_mct  : hci lib postload completed
08-16 08:18:44.453  7825  8077 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:44.453  7825  8077 W bt-smp  : Plain text(LSB ~ MSB) = a9 c6 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:44.453  7825  8077 W bt-smp  : Encrypted text(LSB ~ MSB) = 59 a9 5c c1 b7 b6 e1 dc 9d ba 8c c3 c3 83 55 ad 
,08-16 08:18:44.455  7825  8077 W bt-btm  : Stopping oneshot timer
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:44.464  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:44.469  7825  8040 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 08:18:44.469  7825  8040 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 08:18:44.472  7825  8036 I BluetoothAdapterState: Entering On State
08-16 08:18:44.481  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:44.483  7825  8077 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:44.483  7825  8077 W bt-smp  : Plain text(LSB ~ MSB) = c7 99 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:44.483  7825  8077 W bt-smp  : Encrypted text(LSB ~ MSB) = 53 88 83 0d 93 a1 6d a4 ee 5e 84 82 46 97 54 e9 
,08-16 08:18:44.485  7825  8077 W bt-btm  : Stopping oneshot timer
08-16 08:18:44.499  7825  8036 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 08:18:44.500  7825  8036 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 08:18:44.500  7825  8036 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 08:18:44.503  7825  8036 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 08:18:44.504  7825  8077 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:44.504  7825  8077 W bt-smp  : Plain text(LSB ~ MSB) = 96 7b 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:44.504  7825  8077 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 9c 66 9e 15 9c 35 39 64 4d 5a f2 d6 6b 7f 23 
08-16 08:18:44.504  7825  8077 W bt-btm  : Stopping oneshot timer
08-16 08:18:44.504  6953  6981 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:44.519  7825  8077 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:44.519  7825  8077 W bt-smp  : Plain text(LSB ~ MSB) = 03 07 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 08:18:44.519  7825  8077 W bt-smp  : Encrypted text(LSB ~ MSB) = a0 5f 48 d4 58 35 d6 09 22 63 26 74 5a 23 79 e9 
,08-16 08:18:44.523  7825  8036 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 08:18:44.523  7825  8077 W bt-btm  : Stopping oneshot timer
08-16 08:18:44.524  6953  6981 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 08:18:44.532  1855  3981 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 08:18:44.552  7825  8077 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 08:18:44.553  7825  8077 W bt-smp  : Plain text(LSB ~ MSB) = 9b d1 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-16 08:18:44.553  7825  8077 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 86 e7 b3 14 84 60 2f fd a2 38 66 dd f0 8b 73 
08-16 08:18:44.553  7825  8077 W bt-btm  : Stopping oneshot timer
08-16 08:18:44.557  8110  8110 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 08:18:44.564  1855  1855 D BluetoothHeadset: Proxy object connected
08-16 08:18:44.564  6953  6953 D BluetoothHeadset: Proxy object connected
08-16 08:18:44.564  6953  6953 D HeadsetProfile: Bluetooth service connected
08-16 08:18:44.564  6953  6974 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 08:18:44.568  1855  2447 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:44.570  6953  6953 D BluetoothInputDevice: Proxy object connected
08-16 08:18:44.570  6953  6953 D HidProfile: Bluetooth service connected
08-16 08:18:44.572  1855  1855 D BluetoothHeadset: Proxy object connected
,08-16 08:18:44.573  6953  6981 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 08:18:44.576  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:44.580  1855  1855 D BluetoothHeadset: Proxy object connected
08-16 08:18:44.580  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:18:44.582  6953  6953 D BluetoothA2dp: Proxy object connected
08-16 08:18:44.582  6953  6953 D A2dpProfile: Bluetooth service connected
08-16 08:18:44.582  1036  1036 D BluetoothHeadset: Proxy object connected
08-16 08:18:44.583  6953  7098 D BluetoothMap: onBluetoothStateChange: up=true
08-16 08:18:44.585  6953  6981 D BluetoothPan: onBluetoothStateChange on: true
08-16 08:18:44.585  6953  6981 D BluetoothPan: onBluetoothStateChange call bindService
,08-16 08:18:44.588  6953  6953 D BluetoothMap: Proxy object connected
08-16 08:18:44.588  6953  6953 D MapProfile: Bluetooth service connected
08-16 08:18:44.588  6953  6953 D BluetoothMap: getConnectedDevices()
08-16 08:18:44.590  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 08:18:44.591  1036  1036 D BluetoothA2dp: Proxy object connected
08-16 08:18:44.591  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 08:18:44.591  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 08:18:44.593  7825  7846 V BluetoothMapService: getConnectedDevices()
08-16 08:18:44.595  6953  6953 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 08:18:44.595  6953  6953 D PanProfile: Bluetooth service connected
08-16 08:18:44.595  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:44.596  1943  2173 D LGBluetoothAPIService: Message: 1
08-16 08:18:44.596  1943  2173 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 08:18:44.596  1943  2173 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 08:18:44.596  1943  2173 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 08:18:44.598  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 08:18:44.604  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:44.607  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 08:18:44.607  1036  1118 D BluetoothManagerService: Message: 40
08-16 08:18:44.607  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 08:18:44.611  7825  7825 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:18:44.612  7825  7825 D BluetoothMapService: STATE_ON
08-16 08:18:44.613  6953  6953 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 08:18:44.615  6953  6953 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 08:18:44.619  6953  6953 D DockEventReceiver: finishStartingService: stopping service
08-16 08:18:44.627  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:44.627  7825  7825 V BluetoothPbapService: Pbap Service onCreate
08-16 08:18:44.627  7825  7825 V BluetoothPbapService: Starting PBAP service
,08-16 08:18:44.629  7825  7825 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 08:18:44.629  7825  7825 V BluetoothPbapService: Pbap Service onBind
08-16 08:18:44.630  7825  7825 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:44.630  6953  6953 D BluetoothPbap: Proxy object connected
08-16 08:18:44.630  7825  7825 V BluetoothPbapService: state: 12
08-16 08:18:44.630  6953  6953 D PbapServerProfile: Bluetooth service connected
08-16 08:18:44.631  7825  7825 V BluetoothMapService: Handler(): got msg=1
08-16 08:18:44.631  7825  7825 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 08:18:44.632  7825  7825 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 08:18:44.632  7825  7825 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:44.632  7825  7825 V BluetoothPbapReceiver: ***********state = 12
08-16 08:18:44.632  7825  8130 D BluetoothMapMasInstance: MAS initSocket()
08-16 08:18:44.633  7825  8130 D BluetoothMapMasInstance:   masId = 00
08-16 08:18:44.633  7825  8130 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 08:18:44.633  7825  8130 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 08:18:44.633  7825  8130 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 08:18:44.634  7825  7825 V BluetoothPbapService: Handler(): got msg=1
08-16 08:18:44.635  7825  7825 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 08:18:44.636  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:44.636  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 08:18:44.636  7825  8132 V BluetoothPbapService: Pbap Service initSocket
08-16 08:18:44.637  2194  2194 D c       : Getting all permits...
08-16 08:18:44.637  2194  2194 D a       : Opening database...
08-16 08:18:44.637  1036  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:44.641  2194  2194 D a       : Opening database auth.proximity.permit_store...
,08-16 08:18:44.642  2194  2194 D a       : Closing database...
08-16 08:18:44.642  7825  8130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:44.643  7825  8132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:44.646  7825  8130 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 08:18:44.647  7825  8040 D BluetoothAdapterProperties: Scan Mode:21
08-16 08:18:44.647  7825  8040 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 08:18:44.647  7825  8130 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 08:18:44.648  7825  8130 D BluetoothMapMasInstance: Accepting socket connection...
08-16 08:18:44.649  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:44.652  7825  8132 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 08:18:44.652  7825  8132 V BluetoothPbapService: Succeed to create listening socket 
08-16 08:18:44.652  7825  8132 V BluetoothPbapService: Accepting socket connection...
08-16 08:18:44.658  6953  6953 D BluetoothPermissionRequest: onReceive
,08-16 08:18:44.660  6953  6953 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 08:18:44.662  6953  6953 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 08:18:44.665  7825  7825 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 08:18:44.667  7825  7825 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 08:18:44.674  7825  7825 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 08:18:44.702  7825  7825 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 08:18:44.702  7825  7825 V BtOppService: onCreate
,08-16 08:18:44.708  7825  7825 V BluetoothOppNotification: send message
,08-16 08:18:44.712  7825  7825 V BtOppService: Starting RfcommListener
08-16 08:18:44.724  7825  7825 D BluetoothOppPreference: Dumping Names:  
,08-16 08:18:44.724  7825  7825 D BluetoothOppPreference: {}
08-16 08:18:44.724  7825  7825 D BluetoothOppPreference: Dumping Channels:  
08-16 08:18:44.724  7825  7825 D BluetoothOppPreference: {}
08-16 08:18:44.725  7825  7825 V BtOppService: onStartCommand
08-16 08:18:44.729  7825  7825 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:44.730  7825  7825 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 08:18:44.731  7825  8140 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 08:18:44.732  7825  8140 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 08:18:44.733  7825  8137 V BtOppService: Deleted complete outbound shares, number =  0
08-16 08:18:44.734  7825  7825 V BluetoothOppNotification: new notify threadi!
08-16 08:18:44.734  7825  7825 V BluetoothOppNotification: send delay message
08-16 08:18:44.735  7825  7825 V BtOppService: start RfcommListener
08-16 08:18:44.736  7825  8137 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 08:18:44.737  7825  8137 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 08:18:44.738  7825  7825 V BtOppService: RfcommListener started
,08-16 08:18:44.738  7825  8141 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 08:18:44.741  7825  7825 V BtOppService: ContentObserver received notification
,08-16 08:18:44.742  7825  8137 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c111c7f on behalf of 
08-16 08:18:44.742  7825  8142 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 08:18:44.743  7825  8140 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2332044c on behalf of 
08-16 08:18:44.743  1036  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:44.744  7825  8141 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18632c95 on behalf of 
08-16 08:18:44.745  7825  8142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:44.745  7825  8140 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 08:18:44.745  7825  8140 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 08:18:44.746  7825  8141 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 08:18:44.748  7825  8142 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-16 08:18:44.749  7825  8142 V BtOppRfcommListener: Started RFCOMM listener....
08-16 08:18:44.749  7825  8142 I BtOppRfcommListener: Accept thread started.
08-16 08:18:44.749  7825  8142 V BtOppRfcommListener: Accepting connection...
,08-16 08:18:44.760  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
08-16 08:18:44.761  7825  7825 V BluetoothFtpService: Ftp Service onCreate
08-16 08:18:44.761  7825  7825 I BluetoothFtpService: Ftp Service onCreate
08-16 08:18:44.761  7825  7825 V BluetoothFtpService: Ftp Service onStartCommand
,08-16 08:18:44.761  7825  7825 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:44.761  7825  7825 V BluetoothFtpService: Starting Listening on sockets
08-16 08:18:44.761  7825  7825 V BtOppService: ContentObserver received notification
08-16 08:18:44.762  7825  7825 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 08:18:44.762  7825  7825 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 08:18:44.762  7825  7825 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 08:18:44.762  7825  7825 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:44.762  7825  7825 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 08:18:44.762  7825  7825 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 08:18:44.764  7825  7825 V BluetoothFtpService: Handler(): got msg=1
08-16 08:18:44.764  7825  7825 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 08:18:44.764  7825  7825 V BluetoothFtpService: Ftp Service initSocket
08-16 08:18:44.771  1036  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:44.772  7825  7825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:44.773  7825  7825 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-16 08:18:44.773  7825  7825 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 08:18:44.774  7825  8143 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 08:18:44.789  7825  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38075153
,08-16 08:18:44.789  7825  7825 V BluetoothSapService: Sap Service onCreate
08-16 08:18:44.791  7825  7825 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:18:44.791  7825  7825 V BluetoothSapService: state: 12
08-16 08:18:44.791  7825  7825 V BluetoothSapService: Starting SAP server process
08-16 08:18:44.794  7825  7825 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 08:18:44.781  8144  8144 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:44.781  8144  8144 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:44.798  7825  8145 V BluetoothSapService: Sap Service initRfcommSocket
08-16 08:18:44.799  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:44.800  7825  8145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:18:44.802  7825  8145 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
08-16 08:18:44.802  7825  8145 V BluetoothSapService: Succeed to create listening socket 
08-16 08:18:44.802  7825  8145 V BluetoothSapService: Accepting socket connection...
,08-16 08:18:44.807  8144  8144 V BT_SAP  : Event pipe created
08-16 08:18:44.807  8144  8144 V BT_SAP  : create_server_socket qcom.sap.server
08-16 08:18:44.807  8144  8144 V BT_SAP  : created socket fd 6
08-16 08:18:44.870  1036  1924 I art     : Explicit concurrent mark sweep GC freed 26745(1304KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.528ms total 120.990ms
,08-16 08:18:44.870  7825  8140 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@128b1e76 on behalf of 
08-16 08:18:44.871  7825  8140 V BluetoothOppNotification: update too frequent, put in queue
08-16 08:18:44.873  7825  8140 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 08:18:44.874  7825  8140 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 08:18:44.874  7825  8140 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dc81c77 on behalf of 
08-16 08:18:44.876  7825  8140 V BluetoothOppNotification: update too frequent, put in queue
08-16 08:18:44.876  7825  8141 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 08:18:44.876  7825  8140 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 08:18:44.878  7825  8141 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11ea90e4 on behalf of 
08-16 08:18:44.880  7825  8141 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 08:18:44.892  7825  8141 V BluetoothOppNotification: outbound notification was removed.
08-16 08:18:44.893  7825  8141 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-16 08:18:44.897  7825  8141 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d5d594d on behalf of 
08-16 08:18:44.898  7825  8141 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 08:18:44.901  7825  8141 V BluetoothOppNotification: inbound notification was removed.
08-16 08:18:44.902  7825  8141 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 08:18:44.904  7825  8141 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@82ac02 on behalf of 
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:45.278  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:18:45.287  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:45.289  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:45.289  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13c8494a added. We now have 8 listener(s)
08-16 08:18:45.289  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:45.292  1036  2036 D WifiServiceImplEx: setWifiEnabled: false pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 08:18:45.293  1036  2036 D WifiService: setWifiEnabled: false pid=6862, uid=10118
08-16 08:18:45.293  1036  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 08:18:45.298  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:45.302  1036  1924 D WifiServiceImplEx: setWifiEnabled: true pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 08:18:45.303  1036  1924 D WifiService: setWifiEnabled: true pid=6862, uid=10118
08-16 08:18:45.303  1036  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 08:18:45.321  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 08:18:45.322  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 08:18:45.322  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 08:18:45.323  1036  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 08:18:45.323  1036  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 08:18:45.326  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 08:18:45.326  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 08:18:45.326  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 08:18:45.326  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 08:18:45.326  1036  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 08:18:45.326  1036  1440 E WifiHW  : unknown target_country: EU , set to default
08-16 08:18:45.326  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 08:18:45.326  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 08:18:45.326  1036  1440 I WifiUtil: gEnableBmps=1
08-16 08:18:45.736  7825  7825 V BluetoothOppNotification: new notify threadi!
08-16 08:18:45.737  7825  7825 V BluetoothOppNotification: send delay message
,08-16 08:18:45.756  7825  8160 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 08:18:45.792  7825  8160 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13980913 on behalf of 
08-16 08:18:45.793  7825  8160 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 08:18:45.803  7825  8160 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 08:18:45.805  7825  8160 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@231d750 on behalf of 
08-16 08:18:45.806  7825  8160 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 08:18:45.809  7825  8160 V BluetoothOppNotification: outbound notification was removed.
08-16 08:18:45.809  7825  8160 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 08:18:45.811  7825  8160 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36b33d49 on behalf of 
08-16 08:18:45.824  7825  8160 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 08:18:45.846  7825  8160 V BluetoothOppNotification: inbound notification was removed.
08-16 08:18:45.846  7825  8160 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 08:18:45.848  7825  8160 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1673864e on behalf of 
08-16 08:18:46.017   317   894 D SoftapController: Softap fwReload - Ok
,08-16 08:18:46.119  1036  1440 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (787ms)
,08-16 08:18:46.122   317   894 D CommandListener: Setting iface cfg
08-16 08:18:46.122   317   894 D CommandListener: Trying to bring down wlan0
08-16 08:18:46.124   317   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 08:18:46.126  1036  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 08:18:46.129  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 08:18:46.130  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:46.130  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:46.130  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 08:18:46.121  8180  8180 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:46.121  8180  8180 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 08:18:46.154  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 08:18:46.154  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 08:18:46.154  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 08:18:46.154  6953  6953 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 08:18:46.156  1036  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 08:18:46.156  1036  1440 D WifiMonitor: connecting to supplicant
,08-16 08:18:46.160  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 08:18:46.162  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:46.164  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 08:18:46.165  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:46.166  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 08:18:46.167  6953  6953 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 08:18:46.167  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 08:18:46.167  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 08:18:46.167  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 08:18:46.167  6953  6953 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 08:18:46.168  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 08:18:46.168  6953  6953 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 08:18:46.171  8180  8180 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 08:18:46.205  8180  8180 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 08:18:46.205  8180  8180 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 08:18:46.207  1036  2053 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8185 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 08:18:46.209  1036  1118 D Tethering: InitialState.processMessage what=4
08-16 08:18:46.210  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 08:18:46.228   364   364 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 23.252ms
08-16 08:18:46.243   364   364 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 297us total 14.484ms
,08-16 08:18:46.258   364   364 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 13.746ms
,08-16 08:18:46.276  8180  8180 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 08:18:46.312  1036  1052 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8206 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 08:18:46.321  8185  8204 W FormManager: Network not available. Please check & try again.
08-16 08:18:46.325  8185  8205 V FormManager: Network unavailable.
,08-16 08:18:46.330  8180  8180 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 08:18:46.330  8185  8205 V FormManager: Network unavailable.
,08-16 08:18:46.337  8180  8180 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 08:18:46.339  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 08:18:46.340  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 08:18:46.341  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 08:18:46.341  1036  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 08:18:46.341  1036  8224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 08:18:46.341  1036  8224 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 08:18:46.341  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:46.342  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:46.343  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 08:18:46.343  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 08:18:46.343  8180  8180 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 08:18:46.343  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:46.343  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 08:18:46.343  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:46.343  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 08:18:46.344  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 08:18:46.344  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 08:18:46.344  1036  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 08:18:46.344  1036  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 08:18:46.344  1036  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 08:18:46.345  1036  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 08:18:46.345  1036  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-16 08:18:46.345  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 08:18:46.345  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-16 08:18:46.345  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 08:18:46.346  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.346  1036  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 08:18:46.346  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.346  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.346  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.346  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 08:18:46.346  1036  1440 D WifiNative-wlan0: SET update_config 1: returned true
08-16 08:18:46.346  1036  1440 D WifiConfigStore: Loading config and enabling all networks 
08-16 08:18:46.346  1036  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 08:18:46.347  1036  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 08:18:46.348  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-16 08:18:46.353  1036  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 08:18:46.355  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 08:18:46.357  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 08:18:46.357  1036  1473 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 08:18:46.358  1036  2007 I ActivityManager: Killing 7272:com.android.chrome/u0a57 (adj 15): empty #17
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:18:46.360  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:18:46.362  1036  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 08:18:46.362  1036  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 08:18:46.362  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:18:46.399  8206  8206 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 08:18:46.413  1036  1440 D WifiStateMachine: enableVerboseLogging : level 2
08-16 08:18:46.413  1036  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 08:18:46.414  1036  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 08:18:46.414  1036  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-16 08:18:46.415  1036  1649 W libprocessgroup: failed to open /acct/uid_10057/pid_7272/cgroup.procs: No such file or directory
08-16 08:18:46.416  1036  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 08:18:46.416  1036  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 08:18:46.416  1036  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 08:18:46.416  1036  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 08:18:46.416  1036  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 08:18:46.416  1036  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 08:18:46.417  1036  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 08:18:46.417  1036  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 08:18:46.417  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 08:18:46.417  1036  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 08:18:46.417  1036  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 08:18:46.418  1036  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 08:18:46.418  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 08:18:46.418  1036  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 08:18:46.418  1036  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 08:18:46.419  1036  1440 D WifiNative-HAL: Setting external_sim to 1
08-16 08:18:46.419  1036  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 08:18:46.419  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-16 08:18:46.419  1943  2385 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 08:18:46.419  1943  2385 D WfdsService: Set the WFDS Monitor: true
08-16 08:18:46.419  1943  2385 D WfdsMonitor: WfdsMonitorThread create
08-16 08:18:46.419  1943  2385 D WfdsMonitor: WFDS Monitor is created and started
08-16 08:18:46.419  1943  2385 D WfdsService: WiFi: Supplicant connection re-established
08-16 08:18:46.419  1036  1440 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 08:18:46.419  1036  1440 I WifiNative-HAL: startHal
08-16 08:18:46.419  1036  1440 D wifi    : setting scan oui 0xaf7a8ec0
08-16 08:18:46.419  7858  7858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.419  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 08:18:46.419  1036  1440 I WifiNative-HAL: startHal
08-16 08:18:46.419  1036  1440 D wifi    : setting scan oui 0xaf7a8ec0
08-16 08:18:46.420  1036  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 08:18:46.420  1036  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 08:18:46.420  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 08:18:46.420  1943  8229 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 08:18:46.420  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 08:18:46.421  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 08:18:46.421  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 08:18:46.421  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 08:18:46.421  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 08:18:46.421  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 08:18:46.422  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-16 08:18:46.422  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 08:18:46.422  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 08:18:46.422  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 08:18:46.422  1943  8229 E CtrlSupplicant: Succeed to open control connection
08-16 08:18:46.422  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 08:18:46.422  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-16 08:18:46.422  1943  8229 E CtrlSupplicant: Succeed to open monitor connection
08-16 08:18:46.422  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 08:18:46.423  1943  8229 D WfdsMonitor: Supplicant connection established
08-16 08:18:46.423  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 08:18:46.423  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 08:18:46.423  1943  2385 D WfdsService: Connected to the supplicant for wfds
08-16 08:18:46.423  8180  8180 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 08:18:46.423  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:46.423  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 08:18:46.423  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 08:18:46.424  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-16 08:18:46.424  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 08:18:46.424  1036  1052 I ActivityManager: Killing 7293:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 08:18:46.425  1036  1440 E WifiNative: : [225,969,783 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 08:18:46.425  1036  1440 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 08:18:46.425  1036  1440 D WifiNative-wlan0: RECONNECT: returned true
08-16 08:18:46.425  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-16 08:18:46.425  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 08:18:46.425  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 08:18:46.425  1036  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 08:18:46.425  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 08:18:46.426  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:46.426  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.427   317   894 D CommandListener: Setting iface cfg
08-16 08:18:46.427   317   894 D CommandListener: Trying to bring up p2p0
08-16 08:18:46.428  1036  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 08:18:46.428  1036  1391 D LGWifiP2pService: P2pEnablingState
08-16 08:18:46.428  1036  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.428  1036  1391 D LGWifiP2pService: P2p socket connection successful
08-16 08:18:46.428  1036  1391 D LGWifiP2pService: P2pEnabledState
,08-16 08:18:46.454  1036  1391 D LGWifiP2pService: sending p2p connection changed broadcast
,08-16 08:18:46.455  1036  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 08:18:46.455  1036  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 08:18:46.455  1036  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 08:18:46.456  1036  1391 D WifiNative-p2p0: SET device_name G3: returned true
08-16 08:18:46.456  1036  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
,08-16 08:18:46.456  1036  1391 D LGWifiP2pService: before postfix = G3
08-16 08:18:46.456  1036  1391 D WifiServerServiceExt: postfix byte check : 2
08-16 08:18:46.456  1036  1391 D LGWifiP2pService: after postfix = G3
08-16 08:18:46.456  1036  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 08:18:46.457  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 08:18:46.457  1943  1943 D WfdsService: WifiP2pState is changed : true
08-16 08:18:46.457  1036  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 08:18:46.457  1036  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 08:18:46.457  1036  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 08:18:46.457  1036  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 08:18:46.458  1036  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 08:18:46.458  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 08:18:46.458  1036  1956 W libprocessgroup: failed to open /acct/uid_10062/pid_7293/cgroup.procs: No such file or directory
08-16 08:18:46.458  1943  2385 D WfdsService: Receive the WFDS_ENABLE Method
08-16 08:18:46.459  1943  2385 D WfdsService: Set the WFDS Monitor: true
08-16 08:18:46.459  1943  1943 D WfdsService: isConnected: false
08-16 08:18:46.459  1943  2385 D WfdsService: Connected to the supplicant for wfds
08-16 08:18:46.458  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 08:18:46.459  1036  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 08:18:46.459  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress
08-16 08:18:46.459  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 08:18:46.460  1943  2385 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 08:18:46.460  8180  8180 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 08:18:46.460  1943  2385 D WfdsService: selectPreferredScanChannel [36]
08-16 08:18:46.460  1943  2385 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-16 08:18:46.466  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 08:18:46.466  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.466  1036  1391 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 08:18:46.466  1036  1558 I WifiNative-HAL: startHal
08-16 08:18:46.466  1036  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 08:18:46.466  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-16 08:18:46.466  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf7a8ec0
08-16 08:18:46.466  1036  1558 D wifi    : failed to get capabilities : -3
08-16 08:18:46.466  1036  1558 E WifiScanningService: could not get scan capabilities
,08-16 08:18:46.467  1036  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.467  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 08:18:46.467  1036  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 08:18:46.467  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 08:18:46.467  1036  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 08:18:46.467  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 08:18:46.468  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 08:18:46.468  1943  1943 D WfdsService: Update P2p Interface State: 3
,08-16 08:18:46.468  1036  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 08:18:46.468  1036  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 08:18:46.468  1036  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 08:18:46.468  1036  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 08:18:46.468  1036  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 08:18:46.468  1036  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 08:18:46.468  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=226014  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 08:18:46.470  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=226015  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-16 08:18:46.470  1036  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-16 08:18:46.470  1036  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
,08-16 08:18:46.471  1036  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 08:18:46.471  1036  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 08:18:46.472  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:46.472  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:46.474  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:46.477  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.477  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.477  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 08:18:46.484  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 08:18:46.484  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 08:18:46.484  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 08:18:46.485  6953  6953 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 08:18:46.486  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 08:18:46.488  6953  6953 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 08:18:46.488  8180  8180 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 08:18:46.488  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 08:18:46.488  1036  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 08:18:46.488  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 08:18:46.488  1036  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 08:18:46.488  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 08:18:46.488  6953  6953 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 08:18:46.488  1036  1391 D LGWifiP2pService: InactiveState
08-16 08:18:46.488  6953  6953 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 08:18:46.488  1036  1391 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.488  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.488  1036  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 08:18:46.489  1036  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 08:18:46.489  1036  1440 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 08:18:46.489  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 08:18:46.490  1036  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 08:18:46.490  1036  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 08:18:46.490  8180  8180 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.490  1036  8224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-16 08:18:46.490  1036  8224 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.491  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.491  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.491  1943  8229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 08:18:46.491  8180  8180 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 08:18:46.491  8180  8180 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 08:18:46.491  8180  8180 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.491  1036  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 08:18:46.491  1036  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.491  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.491  1036  1391 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  8180  8180 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  1943  8229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  1943  8229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.492  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.493  1036  1391 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.493  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 08:18:46.493  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 08:18:46.494  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 08:18:46.494  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 08:18:46.494  1036  8224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:46.494  1036  8224 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.495  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.495  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.495  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 08:18:46.495  1036  8224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08,:18:46.495  1036  8224 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.495  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.495  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.495  8180  8180 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.496  8180  8180 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 08:18:46.496  1943  2385 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 08:18:46.496  8180  8180 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.496  1036  1036 E WifiServerServiceExt: No p2p device connected
08-16 08:18:46.496  1036  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 08:18:46.497  8180  8180 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.497  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 08:18:46.497  1943  8229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:46.497  1943  8229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:46.497  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 08:18:46.498  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.498  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.498  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 08:18:46.498  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 08:18:46.498  1036  8224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:46.498  1036  8224 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.498  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.498  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.498  1036  8224 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 08:18:46.498  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.498  1036  8224 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.498  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:46.498  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.498  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 08:18:46.498  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,08-16 08:18:46.498  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 08:18:46.498  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 08:18:46.499  8180  8180 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:46.500  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 08:18:46.500  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:46.500  1036  8224 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:46.500  1036  8224 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 08:18:46.500  1036  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 08:18:46.500  1036  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 08:18:46.502  1036  1440 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 08:18:46.502  1036  1440 D WifiNative-wlan0: doBoolean: SCAN
,08-16 08:18:46.502  1036  1440 D WifiNative-wlan0: SCAN: returned false
08-16 08:18:46.502  8206  8206 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:46.503  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=226048  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 08:18:46.507  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=226052  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 08:18:46.507  1036  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:46.508  1036  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:46.508  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.509  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:46.509  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 08:18:46.509  1036  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:46.509  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:46.509  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 08:18:46.509  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:46.510  1036  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:46.510  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:46.510  1036  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 08:18:46.512  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:46.512  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 08:18:46.513  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:46.513  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 08:18:46.518  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:46.527  8185  8232 V FormManager: Network unavailable.
,08-16 08:18:46.532  8185  8231 W FormManager: Network not available. Please check & try again.
,08-16 08:18:46.533  8185  8232 V FormManager: Network unavailable.
08-16 08:18:46.536  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:46.536  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 08:18:46.538  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 08:18:46.541  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 08:18:46.545  4349  8233 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 08:18:46.550  4349  8234 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 08:18:46.550  4349  8234 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 08:18:46.605  1036  1938 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8235 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 08:18:46.741  8235  8235 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 08:18:46.742  8235  8235 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 08:18:46.752  8235  8235 V [BNRBootReceiver]: Boot Receiver Return
08-16 08:18:46.753  8235  8235 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 08:18:46.805  1036  2034 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8256 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 08:18:46.807  1036  2034 I ActivityManager: Killing 7324:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 08:18:46.850  1036  1738 W libprocessgroup: failed to open /acct/uid_10085/pid_7324/cgroup.procs: No such file or directory
,08-16 08:18:46.899  8256  8256 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 08:18:46.922  8256  8256 D PluginManager: init()
,08-16 08:18:47.019  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 08:18:47.019  1036  8224 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 08:18:47.019  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 08:18:47.019  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-16 08:18:47.019  1036  8224 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 08:18:47.020  8180  8180 E wpa_supplicant: USIM:  scard_init function
08-16 08:18:47.021  1036  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-16 08:18:47.021  8180  8180 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 08:18:47.024  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 08:18:47.024  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 08:18:47.029  1036  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 08:18:47.030  1036  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 08:18:47.032  1036  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 08:18:47.032  1036  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 08:18:47.045  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=226590  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 08:18:47.048  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=226593  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 08:18:47.052  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.052  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:47.053  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.057  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:18:47.057  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.058  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 08:18:47.058  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:47.058  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-16 08:18:47.062  1036  1379 V AlarmManager: RTC_WAKEUP set : Alarm{2eb147e8 type 0 when 1471328321537 com.google.android.gms} when 1471328321537
08-16 08:18:47.063  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2ad47e01 type 2 when 224428 android} when 224428
08-16 08:18:47.063  1036  1379 V AlarmManager: RTC_WAKEUP set : Alarm{30a424a6 type 0 when 1471328326666 android} when 1471328326666
08-16 08:18:47.140  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 08:18:47.140  8180  8180 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 08:18:47.140  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 08:18:47.140  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 08:18:47.140  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-16 08:18:47.146  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=226691  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 08:18:47.147  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=226692  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 08:18:47.149  1036  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=226694
08-16 08:18:47.149  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:47.150  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:47.150  1036  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=226695
08-16 08:18:47.151  1036  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=226696
08-16 08:18:47.153  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 08:18:47.153  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=226698
,08-16 08:18:47.154  1036  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=226699
08-16 08:18:47.156  8180  8180 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 08:18:47.156  8180  8180 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 08:18:47.157  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:47.157  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:47.157  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 08:18:47.157  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 08:18:47.157  1036  8224 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 08:18:47.157  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 08:18:47.158  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 08:18:47.158  1036  8224 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 08:18:47.158  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=226703  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 08:18:47.158  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:47.158  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:47.159  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:47.159  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 08:18:47.161  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=226706  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 08:18:47.164  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.164  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.164  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 08:18:47.165  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=226710  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-16 08:18:47.166  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=226711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 08:18:47.166  1036  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=226711
08-16 08:18:47.166  1036  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=226712
08-16 08:18:47.167  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.167  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:47.167  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-16 08:18:47.167  1036  8224 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 08:18:47.167  1036  8224 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 08:18:47.168  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.168  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.168  1036  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 08:18:47.168  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 08:18:47.169  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.170  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.170  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:47.171  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.171  1036  1440 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 08:18:47.180  1036  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 08:18:47.180  1036  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-16 08:18:47.185  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.185  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.185  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 08:18:47.187  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.187  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:47.188  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.188  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.188  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 08:18:47.189  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.190  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.190  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:47.191  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.192  1036  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 08:18:47.192  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:18:47.192  1036  1527 D ConnectivityService: Got NetworkAgent Messenger
08-16 08:18:47.193  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 08:18:47.193  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 08:18:47.193  1036  1527 D ConnectivityService: NetworkAgent connected
08-16 08:18:47.193  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 08:18:47.193  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 08:18:47.200  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 08:18:47.201  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:18:47.201  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-16 08:18:47.201  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 08:18:47.201  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 08:18:47.207  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 08:18:47.209   317   894 D CommandListener: Setting iface cfg
08-16 08:18:47.212  1036  8274 D DhcpStateMachine: StoppedState
08-16 08:18:47.212  1036  1440 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 08:18:47.212  1036  8274 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.212  1036  8274 D DhcpStateMachine: WaitBeforeStartState
,08-16 08:18:47.212  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=226757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:47.213  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=226758  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:47.213  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=226758  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:47.214  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:47.214  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:47.215  1036  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:47.215  1036  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:47.215  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:47.216  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 08:18:47.217  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:47.217  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 08:18:47.217  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:47.217  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 08:18:47.217  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=226763  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:47.218  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=226763  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:47.218  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=226763  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 08:18:47.219  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14196] from screen [on:0 period:-1845455309] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 08:18:47.220  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1845455308] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 08:18:47.220  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 08:18:47.223  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.224  1036  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-16 08:18:47.225  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.225  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.225  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.226  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.226  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.227  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.227  1036  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 08:18:47.228  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=160,0,0
08-16 08:18:47.228  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=160,0,0
08-16 08:18:47.228  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 08:18:47.228  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 08:18:47.230  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 08:18:47.230  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 08:18:47.230  1036  1440 D WifiNative-wlan0: SET ps 0: returned true
08-16 08:18:47.230  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 08:18:47.230  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 08:18:47.230  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 08:18:47.230  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@267bdceb target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.230  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@267bdceb target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.231  1036  8274 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.231  1036  8274 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 08:18:47.231  1036  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 08:18:47.231  1036  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 08:18:47.231  1036  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 08:18:47.232   317   894 D CommandListener: Setting iface cfg
08-16 08:18:47.232   317   894 D CommandListener: Trying to bring up wlan0
08-16 08:18:47.234  1036  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 08:18:47.234  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:47.234  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 08:18:47.235  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.235  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.236  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.236  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.236  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.237  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 08:18:47.237  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 08:18:47.237  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 08:18:47.238  1036  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 1,02]; created=false
08-16 08:18:47.238  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 08:18:47.239  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 08:18:47.239  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.239  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.239  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 08:18:47.239  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 08:18:47.240  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 08:18:47.240  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 08:18:47.240  8180  8180 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 08:18:47.240  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 08:18:47.240  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 08:18:47.257  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-16 08:18:47.257  1036  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 08:18:47.258  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 08:18:47.258  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-16 08:18:47.258  1036  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 08:18:47.259  1036  1527 D ConnectivityService: ignoring duplicate network state non-change
08-16 08:18:47.263  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.263  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.263  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 08:18:47.264  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.264  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:47.265  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.266  1036  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 08:18:47.267  1036  1527 D ConnectivityService: Adding iface wlan0 to network 102
08-16 08:18:47.267  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.267  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.268  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 08:18:47.270  1036  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 08:18:47.270  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 08:18:47.272  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.272  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 08:18:47.274  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.277  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 08:18:47.278  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.279  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.279  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 08:18:47.280  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 08:18:47.284  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.285  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:18:47.285  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-16 08:18:47.292  1036  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 08:18:47.292  1036  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 08:18:47.292  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.293  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 08:18:47.293  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.293  1036  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 08:18:47.294   317   894 E Netd    : netlink response contains error (File exists)
08-16 08:18:47.295  1036  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 08:18:47.295  1036  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 08:18:47.295  1036  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 08:18:47.296  1036  1527 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 08:18:47.296  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 08:18:47.296  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 08:18:47.297  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.297  1036  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 08:18:47.297  1036  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 08:18:47.297  1036  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 08:18:47.297  1036  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 08:18:47.297  1036  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:47.297  1036  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:47.297  1036  8273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.297  1036  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 08:18:47.297  1036  8273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 08:18:47.297  1036  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.297  1036  8273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 08:18:47.297  1036  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 08:18:47.297  1036  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-16 08:18:47.297  1036  1527 D ConnectivityService:    accepting network in place of null
08-16 08:18:47.297  1036  8273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 08:18:47.297  1036  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.,300  1036  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.300  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:47.300  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.301  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 08:18:47.303  1036  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 08:18:47.303  1036  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 08:18:47.304   317  8283 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 08:18:47.304  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 08:18:47.304  1036  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:18:47.304  1036  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 08:18:47.304  1036  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 08:18:47.305  1036  1527 D ConnectivityService: validation of new default Network = false
08-16 08:18:47.305  1036  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 08:18:47.305  1036  1527 D DSQN    : enableDataServiceNotify 
08-16 08:18:47.305  1036  1527 D DSQN    : start dsqn bin
08-16 08:18:47.306  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 08:18:47.307  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 08:18:47.307  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 08:18:47.307  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-16 08:18:47.301  8284  8284 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:47.301  8284  8284 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:47.318  1036  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 08:18:47.318  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.318  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:47.318  1036  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 08:18:47.325  1036  1390 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 08:18:47.330  8284  8284 E DSQN    : DSQN ssw
08-16 08:18:47.331  1604  1836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:47.335  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:18:47.337  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:47.341  6862  6923 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 08:18:47.342  6862  6923 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 08:18:47.343  6862  6923 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7b88e66 Bundle[{}]
08-16 08:18:47.344  6862  6923 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 08:18:47.344  6862  6923 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 08:18:47.344  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 08:18:47.345  6862  6923 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 08:18:47.345  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.345  6862  6923 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 08:18:47.346  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.346  6862  6923 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 08:18:47.346  6862  6923 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 08:18:47.352  6862  6923 I System.out: Running OutgoingSocketThread
08-16 08:18:47.354  6862  8288 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
08-16 08:18:47.355  6862  8288 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57495
08-16 08:18:47.355  6862  8288 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 08:18:47.368   317  8283 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 08:18:47.401   317  8283 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 08:18:47.432   317   893 D LGDataListener: argv[0]=dsqncommand
08-16 08:18:47.432   317   893 D LGDataListener: argv[1]=wlan0
08-16 08:18:47.432   317   893 D LGDataListener: argv[2]=1
08-16 08:18:47.432   317   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-16 08:18:47.434  1036  8274 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 08:18:47.436  1036  8274 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 08:18:47.436  1036  8274 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 08:18:47.436  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 08:18:47.437  1036  1116 D DSQN    : start to monitor internet connection
08-16 08:18:47.440  8256  8256 W ExternalStrings: load override strings
08-16 08:18:47.440  8256  8256 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 08:18:47.440  8256  8256 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 08:18:47.431  8292  8292 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:47.431  8292  8292 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 08:18:47.446  8256  8256 D StatusProvider: onCreate
08-16 08:18:47.448  8292  8292 I dhcpcd  : version 5.5.6 starting
08-16 08:18:47.449  8292  8292 E dhcpcd  : get_duid: m
08-16 08:18:47.449  8292  8292 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
,08-16 08:18:47.449  8292  8292 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 08:18:47.463  1036  8273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 06:18:47 GMT], X-Android-Received-Millis=[1471328327463], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471328327433]}
08-16 08:18:47.464  1036  8273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 08:18:47.464  1036  8273 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 08:18:47.464  1036  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 08:18:47.464  1036  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 08:18:47.464  1036  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:47.464  1036  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:47.464  1036  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 08:18:47.464  1036  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 08:18:47.464  1036  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 08:18:47.464  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.464  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:47.465  1036  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:47.465  1036  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.465  1036  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 08:18:47.465  1036  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.466  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 08:18:47.466  1604  1836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 08:18:47.468  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:47.469  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 08:18:47.484  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 08:18:47.485  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.486  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 08:18:47.498  8292  8292 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 08:18:47.498  8292  8292 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 08:18:47.498  8292  8292 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 08:18:47.498  8292  8292 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 08:18:47.499  8292  8292 D dhcpcd  : wlan0: sending REQUEST (xid 0xa15c0ef8), next in 3.38 seconds
,08-16 08:18:47.518  8256  8256 V Signer  : override build config not found
,08-16 08:18:47.519  8256  8256 D Signer  : value of property debug is false
08-16 08:18:47.530  8292  8292 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 08:18:47.556  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 08:18:47.556  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 08:18:47.556  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-16 08:18:47.556  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 08:18:47.557  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 08:18:47.557  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 08:18:47.557  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 08:18:47.557  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 08:18:47.557  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 08:18:47.558  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 08:18:47.558  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 08:18:47.558  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 08:18:47.558  8256  8256 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-16 08:18:47.568  8256  8256 V LGMDMManager: Create singleton instance
,08-16 08:18:47.571  8292  8292 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 08:18:47.571  8292  8292 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-16 08:18:47.572  8292  8292 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 08:18:47.572  8292  8292 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 08:18:47.573  8292  8292 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 08:18:47.573  8292  8292 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 08:18:47.573  8292  8292 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 08:18:47.574  8292  8292 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 08:18:47.615  8256  8256 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 08:18:47.707  8256  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 08:18:47.710  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:47.725  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:47.732  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:47.782  1036  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8318 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 08:18:47.783  1036  1051 I ActivityManager: Killing 7347:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-16 08:18:47.843  1036  8274 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 08:18:47.844  1036  8274 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 08:18:47.844  1036  8274 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 08:18:47.844  1036  8274 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 08:18:47.844  1036  8274 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 08:18:47.844  1036  8274 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 08:18:47.844  1036  8274 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 08:18:47.844  1036  8274 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 08:18:47.845  1036  8274 D DhcpStateMachine: RunningState
,08-16 08:18:47.868  8256  8308 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,08-16 08:18:48.003  1036  1595 W libprocessgroup: failed to open /acct/uid_10093/pid_7347/cgroup.procs: No such file or directory
,08-16 08:18:48.030  8318  8318 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:48.054  8318  8318 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 08:18:48.085  8256  8308 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:48.085  8256  8308 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:48.093  8318  8318 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 08:18:48.094  8318  8318 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 08:18:48.095  8318  8318 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 08:18:48.096  8318  8318 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 08:18:48.097  8318  8318 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-16 08:18:48.101  8318  8318 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 08:18:48.113  8318  8318 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 08:18:48.124  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 08:18:48.130  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.154  8318  8318 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 08:18:48.158  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.159  8256  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 08:18:48.165  8318  8318 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 08:18:48.167  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:48.174  8318  8318 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 08:18:48.175  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.179  8256  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-16 08:18:48.182  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.183  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 08:18:48.186  8318  8318 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 08:18:48.189  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 08:18:48.193  6953  6953 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 08:18:48.198  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:48.199  8256  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 08:18:48.209  8256  8308 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 08:18:48.210  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:48.220  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.222  8256  8308 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 08:18:48.222  8256  8308 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-16 08:18:48.225  8256  8308 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 08:18:48.226  8256  8308 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 08:18:48.226  8256  8308 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 08:18:48.227  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.228  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.228  8318  8318 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:48.235  8256  8308 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-16 08:18:48.239  1036  1440 E WifiStateMachine:  ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-48 f=2447 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=87.0 fiv=20000 [on:0 tx:0 rx:0 period:1015] from screen [on:0 period:-1845454289]
08-16 08:18:48.240  8256  8308 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 08:18:48.240  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-48 f=2447 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=87.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1845454288]
08-16 08:18:48.242  1036  1440 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=80.00 rxSuccessRate=87.00 targetRoamBSSID=any RSSI=-48
08-16 08:18:48.246  8318  8318 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-16 08:18:48.247  8318  8318 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9811
08-16 08:18:48.255  1819  8362 I CheckinService: active receiver: enabled
08-16 08:18:48.269  1819  8362 I CheckinService: Preparing to send checkin request
08-16 08:18:48.269  1819  8362 I EventLogService: Accumulating logs since 1471328310252
,08-16 08:18:48.271  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 08:18:48.271  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 08:18:48.271  6953  6953 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 08:18:48.271  6953  6953 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 08:18:48.273  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 08:18:48.274  6953  6953 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 08:18:48.274  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 08:18:48.274  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 08:18:48.274  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 08:18:48.274  6953  6953 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 08:18:48.274  6953  6953 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 08:18:48.274  6953  6953 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 08:18:48.277  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.277  8256  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 08:18:48.283  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:48.288  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.295  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.296  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.297  8318  8318 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 08:18:48.299  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.299  8256  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 08:18:48.308  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:48.317  1819  8362 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 08:18:48.318  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 08:18:48.325  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.325  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.326  8318  8318 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:48.329  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.329  8256  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 08:18:48.335  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 08:18:48.345  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.351  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 08:18:48.352  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.353  8318  8318 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:48.354  6862  6923 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
08-16 08:18:48.354  6862  6923 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
08-16 08:18:48.355  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.355  8256  8310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 08:18:48.359  6862  6923 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
08-16 08:18:48.360  6862  6923 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 08:18:48.360  6862  6923 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
08-16 08:18:48.362  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:48.364  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.364  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd7f0bb added. We now have 2 listener(s)
08-16 08:18:48.365  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 08:18:48.369  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.369  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.369  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.369  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.370  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21eca9d8 added. We now have 9 listener(s)
08-16 08:18:48.370  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:18:48.370  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:18:48.372  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:48.376  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:18:48.378  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.379  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:48.379  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.379  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c9b016 added. We now have 3 listener(s)
08-16 08:18:48.379  1036  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 08:18:48.381  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.382  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.384  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 08:18:48.384  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.384  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.384  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.385  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8add97 added. We now have 10 listener(s)
,08-16 08:18:48.385  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.385  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:48.385  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:48.385  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:48.385  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.385  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.385  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:48.385  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.385  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd7f0bb removed from the list
08-16 08:18:48.385  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.385  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21eca9d8 removed from the list
08-16 08:18:48.387  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.388  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:48.388  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.388  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.388  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.389  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.389  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.389  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.389  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21eca9d8 not in the list
08-16 08:18:48.389  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.389  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:18:48.390  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.390  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.390  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.390  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8add97 removed from the list
08-16 08:18:48.390  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.390  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.390  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.390  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.390  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c9b016 removed from the list
08-16 08:18:48.392  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.392  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6e8b84 added. We now have 2 listener(s)
08-16 08:18:48.393  1036  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.395  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.396  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.396  8318  8318 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:48.399  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.399  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.399  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.399  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.399  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@babcf6d added. We now have 9 listener(s)
08-16 08:18:48.400  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.400  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:18:48.404  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:48.409  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:48.411  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.411  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:48.412  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.412  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1515bc33 added. We now have 3 listener(s)
08-16 08:18:48.412  1036  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.414  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.416  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.416  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.416  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.416  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.416  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c0adbf0 added. We now have 10 listener(s)
08-16 08:18:48.416  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.416  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:48.416  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:18:48.416  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:18:48.416  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:48.416  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:18:48.419  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:48.420  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.421  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:18:48.421  1036  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.426  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 08:18:48.426  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 08:18:48.428  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:18:48.428  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:48.430  6862  6923 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 08:18:48.430  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:48.430  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 08:18:48.432  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:48.432  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:48.432  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:48.432  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.432  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.432  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:48.433  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.433  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6e8b84 removed from the list
08-16 08:18:48.433  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.433  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@babcf6d removed from the list
08-16 08:18:48.433  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:48.433  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.433  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.433  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.434  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.434  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.434  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.434  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@babcf6d not in the list
08-16 08:18:48.434  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.434  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.435  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.436  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:48.436  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:48.436  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.436  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.436  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c0adbf0 removed from the list
08-16 08:18:48.436  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.436  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.436  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:,18:48.436  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.436  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1515bc33 removed from the list
08-16 08:18:48.437  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.437  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1865e88f added. We now have 2 listener(s)
08-16 08:18:48.438  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.441  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.441  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.441  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.441  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.441  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd9c71c added. We now have 9 listener(s)
08-16 08:18:48.441  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:18:48.447  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:18:48.454  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:48.462  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:48.463  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.464  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:48.464  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.464  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bad98fa added. We now have 3 listener(s)
08-16 08:18:48.465  1036  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.466  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:48.468  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.468  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.468  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.468  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.468  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28e27eab added. We now have 10 listener(s)
08-16 08:18:48.469  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.469  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:48.470  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:48.470  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:18:48.470  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:18:48.470  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:48.470  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:18:48.473  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.474  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:18:48.476  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:48.477  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 08:18:48.484  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 08:18:48.486  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.486  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 08:18:48.489  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:18:48.489  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 08:18:48.491  6862  6923 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 08:18:48.492  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:48.492  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:48.492  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:48.492  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.492  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.492  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:48.492  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.492  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1865e88f removed from the list
08-16 08:18:48.492  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.492  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd9c71c removed from the list
08-16 08:18:48.492  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:48.492  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.493  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.493  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.493  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.494  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.494  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.494  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.494  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.495  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd9c71c not in the list
08-16 08:18:48.495  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.495  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.495  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.496  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:48.496  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:48.496  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.496  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.496  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28e27eab removed from the list
08-16 08:18:48.496  6862  6923 I, org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.496  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.496  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.496  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.496  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bad98fa removed from the list
08-16 08:18:48.497  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.497  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dac4ac6 added. We now have 2 listener(s)
08-16 08:18:48.497  1036  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 08:18:48.500  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.500  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.500  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.500  8318  8318 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 08:18:48.500  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 08:18:48.501  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c485a87 added. We now have 9 listener(s)
08-16 08:18:48.501  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.502  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 08:18:48.504  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:48.506  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:48.510  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:18:48.512  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.512  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:48.514  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.514  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6c6ddd added. We now have 3 listener(s)
08-16 08:18:48.514  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.515  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:18:48.517  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.518  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.518  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.518  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.518  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.518  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c924d52 added. We now have 10 listener(s)
08-16 08:18:48.518  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.518  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:48.518  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:18:48.518  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:18:48.518  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:48.518  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:48.518  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:18:48.522  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:18:48.522  1036  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.527  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 08:18:48.527  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 08:18:48.529  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:18:48.530  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:48.532  6862  6923 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 08:18:48.532  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.535  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:48.535  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:48.535  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:48.535  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.535  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.535  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:48.535  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.535  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dac4ac6 removed from the list
08-16 08:18:48.535  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.535  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c485a87 removed from the list
08-16 08:18:48.535  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:48.535  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.538  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.538  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.539  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.539  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.539  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.539  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.539  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c485a87 not in the list
08-16 08:18:48.539  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.539  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:18:48.539  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.540  8318  8318 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 08:18:48.542  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.542  6862  6923 D BluetoothLeScanner: could not find callback wrapper
08-16 08:18:48.542  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:18:48.542  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.542  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.542  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c924d52 removed from the list
08-16 08:18:48.542  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.542  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.542  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.542  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.543  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6c6ddd removed from the list
08-16 08:18:48.543  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.543  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c470ad9 added. We now have 2 listener(s)
08-16 08:18:48.544  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.544  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.546  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.546  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.546  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.547  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.547  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c63ec9e added. We now have 9 listener(s)
08-16 08:18:48.547  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.547  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:18:48.549  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:18:48.549  8206  8206 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 08:18:48.554  8206  8206 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:48.554  6862  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:18:48.554  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:18:48.554  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 08:18:48.554  6862  6923 V i,o.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:18:48.554  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:18:48.554  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.554  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:18:48.554  6862  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:18:48.557  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:48.558  6862  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:18:48.558  6862  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:18:48.558  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:18:48.559  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d2b2f4c added. We now have 3 listener(s)
08-16 08:18:48.559  1036  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 08:18:48.561  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.562  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 08:18:48.562  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:18:48.562  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:18:48.562  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:18:48.562  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4947b95 added. We now have 10 listener(s)
08-16 08:18:48.563  6862  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:18:48.563  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:18:48.563  6862  6923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:18:48.563  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:48.563  6862  6923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:18:48.563  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.563  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.563  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:18:48.563  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.564  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c470ad9 removed from the list
08-16 08:18:48.564  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.564  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c63ec9e removed from the list
08-16 08:18:48.564  6862  6923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:18:48.564  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.564  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The gi,ven listener does not exist in the list - probably already removed
08-16 08:18:48.564  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.565  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.565  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.565  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.565  6862  6923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c63ec9e not in the list
08-16 08:18:48.565  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.565  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.566  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.566  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:18:48.566  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:18:48.566  6862  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:18:48.566  6862  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4947b95 removed from the list
08-16 08:18:48.566  6862  6923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:18:48.566  6862  6923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:18:48.566  6862  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:18:48.566  6862  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:18:48.567  6862  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d2b2f4c removed from the list
,08-16 08:18:48.567  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 08:18:48.568  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 08:18:48.568  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 08:18:48.568  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:18:48.568  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 08:18:48.568  6862  6923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 08:18:48.574  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.574  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.575  8318  8318 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 08:18:48.576  8318  8318 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 08:18:48.576  8318  8318 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 08:18:48.581  6862  8370 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
,08-16 08:18:48.581  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.581  6862  8370 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
08-16 08:18:48.581  6862  8370 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 08:18:48.585  6862  8371 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: My test thread name)
08-16 08:18:48.585  6862  8371 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
08-16 08:18:48.585  6862  8371 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 08:18:48.587  8206  8206 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 08:18:48.588  8206  8206 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 08:18:48.588  6862  6923 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 08:18:48.588  6862  6923 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 08:18:48.589  6862  6923 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 08:18:48.589  6862  6923 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 08:18:48.589  6862  6923 D com.test.thalitest.ThaliTestRunner: Total duration: 23803 ms
08-16 08:18:48.590  6953  6953 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 08:18:48.590  6862  6923 I jxcore-log: Total number of executed tests:  80
08-16 08:18:48.590  6862  6923 I jxcore-log: 
08-16 08:18:48.591  6862  6923 I jxcore-log: Number of passed tests:  80
08-16 08:18:48.591  6862  6923 I jxcore-log: 
08-16 08:18:48.591  6862  6923 I jxcore-log: Number of failed tests:  0
08-16 08:18:48.591  6862  6923 I jxcore-log: 
08-16 08:18:48.591  6862  6923 I jxcore-log: Number of ignored tests:  0
08-16 08:18:48.591  6862  6923 I jxcore-log: 
08-16 08:18:48.591  6862  6923 I jxcore-log: Total duration:  23803
08-16 08:18:48.591  6862  6923 I jxcore-log: 
08-16 08:18:48.592  6862  6923 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 08:18:48.592  6862  6923 I jxcore-log: 
08-16 08:18:48.595  6953  6953 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 08:18:48.595  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.595  6862  6923 I jxcore-log: 
08-16 08:18:48.598  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.598  6862  6923 I jxcore-log: 
,08-16 08:18:48.601  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.601  6862  6923 I jxcore-log: 
08-16 08:18:48.603  8318  8318 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 08:18:48.603  8318  8318 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 08:18:48.603  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.603  6862  6923 I jxcore-log: 
08-16 08:18:48.603  8318  8318 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 08:18:48.604  6862  6862 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 08:18:48.604  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.604  6862  6923 I jxcore-log: 
08-16 08:18:48.604  8318  8318 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 08:18:48.604  8318  8318 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 08:18:48.606  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.606  6862  6923 I jxcore-log: 
08-16 08:18:48.608  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.608  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:18:48.608  6862  6923 I jxcore-log: 
08-16 08:18:48.610  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.610  6862  6923 I jxcore-log: 
,08-16 08:18:48.611  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:18:48.611  6862  6923 I jxcore-log: 
08-16 08:18:48.612  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.612  6862  6923 I jxcore-log: 
08-16 08:18:48.613  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.613  6862  6923 I jxcore-log: 
08-16 08:18:48.614  8318  8318 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 08:18:48.615  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 08:18:48.615  6862  6923 I jxcore-log: 
08-16 08:18:48.615  8318  8318 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 08:18:48.615  8318  8318 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 08:18:48.616  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:18:48.616  6862  6923 I jxcore-log: 
08-16 08:18:48.617  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:18:48.617  6862  6923 I jxcore-log: 
08-16 08:18:48.617  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.617  6862  6923 I jxcore-log: 
08-16 08:18:48.618  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.618  6862  6923 I jxcore-log: 
08-16 08:18:48.619  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.619  6862  6923 I jxcore-log: 
08-16 08:18:48.619  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.619  6862  6923 I jxcore-log: 
08-16 08:18:48.620  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.620  6862  6923 I jxcore-log: 
08-16 08:18:48.621  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.621  6862  6923 I jxcore-log: 
08-16 08:18:48.622  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.622  6862  6923 I jxcore-log: 
,08-16 08:18:48.622  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:18:48.622  6862  6923 I jxcore-log: 
,08-16 08:18:48.623  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 08:18:48.623  6862  6923 I jxcore-log: 
08-16 08:18:48.624  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.624  6862  6923 I jxcore-log: 
08-16 08:18:48.625  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.625  6862  6923 I jxcore-log: 
08-16 08:18:48.626  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.626  6862  6923 I jxcore-log: 
08-16 08:18:48.626  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.626  6862  6923 I jxcore-log: 
08-16 08:18:48.627  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.627  6862  6923 I jxcore-log: 
08-16 08:18:48.627  6862  6923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:18:48.627  6862  6923 I jxcore-log: 
08-16 08:18:48.648  8318  8318 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:48.648  8318  8318 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:48.652  1036  1440 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 08:18:48.652  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 08:18:48.653  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 08:18:48.653  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 08:18:48.653  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 08:18:48.654  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 08:18:48.654  1036  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 08:18:48.654  1036  1527 D ConnectivityService: identical MTU - not setting
08-16 08:18:48.654  1036  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-16 08:18:48.654  1036  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 08:18:48.655  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 08:18:48.655  1036  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:48.655  1036  1527 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 08:18:48.656  1604  1836 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 08:18:48.658  8318  8318 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 08:18:48.659  8318  8318 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 08:18:48.659  8318  8318 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 08:18:48.659  8318  8318 V SoundPool: doLoad: loading sample sampleID=1
08-16 08:18:48.659  8318  8318 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 08:18:48.660  8318  8374 V SoundPool: Start decode
08-16 08:18:48.660  8318  8374 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-16 08:18:48.661   322  1398 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 08:18:48.661   322  1398 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 08:18:48.662   322  1398 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 08:18:48.662   322  1398 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 08:18:48.662   322  1398 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 08:18:48.662   322  1398 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 08:18:48.662   322  1398 V MediaPlayerService: player type = 3
08-16 08:18:48.662   322  1398 V AwesomePlayer: AwesomePlayer create()
08-16 08:18:48.662  7742  7742 D UEI.SmartControl: QS Service created
08-16 08:18:48.662   322  1398 V AwesomePlayer: reset_l() 
08-16 08:18:48.662   322  1398 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:48.662  8318  8318 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 08:18:48.662   322  1398 V AwesomePlayer: setAudioSink() 
08-16 08:18:48.662   322  1398 V AwesomePlayer: reset_l() 
08-16 08:18:48.662   322  1398 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-16 08:18:48.662   322  1398 V AudioCache: ignored
08-16 08:18:48.662   322  1398 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:48.662   322  1398 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 08:18:48.662   322  1398 V AwesomePlayer: setDataSource_l dataSource
08-16 08:18:48.662   322  1398 V LGParserOSAL: SniffLGParser start
08-16 08:18:48.663   322  1398 V LGParserOSAL: MainType:5, SubType=0
08-16 08:18:48.663   322  1398 V LGParserOSAL: #### check Mime : application/ogg
08-16 08:18:48.663   322  1398 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 08:18:48.663   322  1398 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 08:18:48.664  8318  8318 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 08:18:48.664  8318  8318 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 08:18:48.675  7742  7742 I UEI.SmartControl: Service initServices...
08-16 08:18:48.677  7742  7742 D UEI.SmartControl: QS start get config
08-16 08:18:48.688  8318  8318 V LGMDMManager: Create singleton instance
,08-16 08:18:48.720   322  1398 V LGParserOSAL: supported mime: application/ogg
08-16 08:18:48.720   322  1398 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,08-16 08:18:48.720   322  1398 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 08:18:48.720   322  1398 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 08:18:48.720   322  1398 V AwesomePlayer: AudioTrack Setting
08-16 08:18:48.720   322  1398 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 08:18:48.720   322  1398 V AwesomePlayer: setAudioSource() 
08-16 08:18:48.720   322  1398 V MediaPlayerService: prepare
08-16 08:18:48.720   322  1398 V AwesomePlayer: prepareAsync_l() 
08-16 08:18:48.720   322  1398 V MediaPlayerService: wait for prepare
08-16 08:18:48.722   322  8377 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 08:18:48.722   322  8377 V AwesomePlayer: initAudioDecoder() 
08-16 08:18:48.722   322  8377 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,08-16 08:18:48.722   322  8377 V AudioSystem: isOffloadSupported()
08-16 08:18:48.722   322  8377 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 08:18:48.722   322  8377 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 08:18:48.722   322  8377 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 08:18:48.722   322  8377 V AwesomePlayer: getUseOffload() = 0 
08-16 08:18:48.722   322  8377 V OMXCodec: OMXCodec::Create
08-16 08:18:48.722   322  8377 V OMXCodec: findMatchingCodecs()
08-16 08:18:48.722   322  8377 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 08:18:48.722   322  8377 V OMXCodec: matchingCodecs.size()=1
08-16 08:18:48.722   322  8377 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 08:18:48.723   322  8377 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 08:18:48.723   322  8377 V LGCodecAdapter: LG Codec Adapter start
08-16 08:18:48.723   322  8377 V OMXCodec: OMXCodec Createtor
08-16 08:18:48.723   322  8377 V OMXCodec: setComponentRole
08-16 08:18:48.723   322  8377 V OMXCodec: configureCodec protected=0
08-16 08:18:48.723   322  8377 V LGCodecAdapter: called getLGCodecSpecificData
08-16 08:18:48.723   322  8377 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 08:18:48.723   322  8377 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 08:18:48.723   322  8377 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 08:18:48.723   322  8377 V LGCodecOSAL: Not support LGCodec
08-16 08:18:48.723   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 08:18:48.724   322  8377 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 08:18:48.724   322  8377 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 08:18:48.724   322  8377 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 08:18:48.724   322  8377 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 08:18:48.724   322  8377 V AudioSystem: isOffloadSupported()
08-16 08:18:48.724   322  8377 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 08:18:48.724   322  8377 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 08:18:48.724   322  8377 V OMXCodec: init()
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 08:18:48.724   322  8377 V OMXCodec: allocateBuffers
08-16 08:18:48.724   322  8377 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on input port
08-16 08:18:48.724   322  8377 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decod,er] allocated buffer 0xb54f7f10 on output port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c14c0 on output port
08-16 08:18:48.724   322  8377 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c15b0 on output port
08-16 08:18:48.724   322  8377 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 08:18:48.731   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 08:18:48.731   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 08:18:48.731   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 08:18:48.731   322  8377 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 08:18:48.731   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 08:18:48.731   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 08:18:48.731   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,08-16 08:18:48.731   322  8377 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 08:18:48.731   322  8377 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 08:18:48.731   322  8377 V AudioCache: notify(0xb1432480, 5, 0, 0)
08-16 08:18:48.731   322  8377 V AudioCache: ignored
08-16 08:18:48.731   322  8377 V AudioCache: notify(0xb1432480, 1, 0, 0)
08-16 08:18:48.731   322  8377 V AudioCache: prepared
08-16 08:18:48.731   322  1398 V AudioCache: wait - success
08-16 08:18:48.731   322  1398 V MediaPlayerService: start
08-16 08:18:48.731   322  1398 V AwesomePlayer: play_l() 
08-16 08:18:48.732   322  1398 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 08:18:48.732   322  1398 V AwesomePlayer: createAudioPlayer_l
08-16 08:18:48.732   322  1398 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 08:18:48.732   322  1398 V AwesomePlayer: startAudioPlayer_l() 
08-16 08:18:48.732   322  1398 D AudioPlayer: start of Playback, useOffload 0
08-16 08:18:48.732   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 08:18:48.732   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 08:18:48.733   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 08:18:48.733   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 08:18:48.733   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 08:18:48.733   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 08:18:48.733   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 08:18:48.733   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807872
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044808112
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 08:18:48.734   322  8379 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c14c0 on output port
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1920 on output port
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 08:18:48.734   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 08:18:48.7,35   322  1398 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 08:18:48.735   322  1398 V AudioCache: notify(0xb1432480, 6, 0, 0)
08-16 08:18:48.736   322  1398 V AudioCache: ignored
08-16 08:18:48.736   322  1398 V MediaPlayerService: wait for playback complete
08-16 08:18:48.736   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.736   322  8380 V AudioCache: memcpy(0xaf006000, 0xb16f2000, 4096)
08-16 08:18:48.737   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.737   322  8380 V AudioCache: memcpy(0xaf007000, 0xb16f2000, 4096)
08-16 08:18:48.737   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.738   322  8380 V AudioCache: memcpy(0xaf008000, 0xb16f2000, 4096)
08-16 08:18:48.738   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.738   322  8380 V AudioCache: memcpy(0xaf009000, 0xb16f2000, 4096)
08-16 08:18:48.738   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.738   322  8380 V AudioCache: memcpy(0xaf00a000, 0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: memcpy(0xaf00b000, 0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: memcpy(0xaf00c000, 0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: memcpy(0xaf00d000, 0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: memcpy(0xaf00e000, 0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: memcpy(0xaf00f000, 0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.739   322  8380 V AudioCache: memcpy(0xaf010000, 0xb16f2000, 4096)
08-16 08:18:48.740   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.740   322  8380 V AudioCache: memcpy(0xaf011000, 0xb16f2000, 4096)
08-16 08:18:48.740   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.740   322  8380 V AudioCache: memcpy(0xaf012000, 0xb16f2000, 4096)
08-16 08:18:48.740   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.740   322  8380 V AudioCache: memcpy(0xaf013000, 0xb16f2000, 4096)
08-16 08:18:48.741   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.741   322  8380 V AudioCache: memcpy(0xaf014000, 0xb16f2000, 4096)
08-16 08:18:48.741   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.741   322  8380 V AudioCache: memcpy(0xaf015000, 0xb16f2000, 4096)
08-16 08:18:48.743   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.743   322  8380 V AudioCache: memcpy(0xaf016000, 0xb16f2000, 4096)
08-16 08:18:48.744   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.744   322  8380 V AudioCache: memcpy(0xaf017000, 0xb16f2000, 4096)
08-16 08:18:48.744   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.744   322  8380 V AudioCache: memcpy(0xaf018000, 0xb16f2000, 4096)
08-16 08:18:48.745   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.745   322  8380 V AudioCache: memcpy(0xaf019000, 0xb16f2000, 4096)
08-16 08:18:48.745   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.745   322  8380 V AudioCache: memcpy(0xaf01a000, 0xb16f2000, 4096)
08-16 08:18:48.746   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.746   322  8380 V AudioCache: memcpy(0xaf01b000, 0xb16f2000, 4096)
08-16 08:18:48.746   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.746   322  8380 V AudioCache: memcpy(0xaf01c000, 0xb16f2000, 4096)
08-16 08:18:48.750   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.750   322  8380 V AudioCache: memcpy(0xaf01d000, 0xb16f2000, 4096)
08-16 08:18:48.750   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.750   322  8380 V AudioCache: memcpy(0xaf01e000, 0xb16f2000, 4096)
08-16 ,08:18:48.751   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.751   322  8380 V AudioCache: memcpy(0xaf01f000, 0xb16f2000, 4096)
08-16 08:18:48.752   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.752   322  8380 V AudioCache: memcpy(0xaf020000, 0xb16f2000, 4096)
08-16 08:18:48.753   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.753   322  8380 V AudioCache: memcpy(0xaf021000, 0xb16f2000, 4096)
08-16 08:18:48.753   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.753   322  8380 V AudioCache: memcpy(0xaf022000, 0xb16f2000, 4096)
08-16 08:18:48.753  8318  8318 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 08:18:48.753   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.753   322  8380 V AudioCache: memcpy(0xaf023000, 0xb16f2000, 4096)
08-16 08:18:48.754  8318  8318 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 08:18:48.754   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.754   322  8380 V AudioCache: memcpy(0xaf024000, 0xb16f2000, 4096)
08-16 08:18:48.755   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.755   322  8380 V AudioCache: memcpy(0xaf025000, 0xb16f2000, 4096)
08-16 08:18:48.755   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.755   322  8380 V AudioCache: memcpy(0xaf026000, 0xb16f2000, 4096)
08-16 08:18:48.755   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.755   322  8380 V AudioCache: memcpy(0xaf027000, 0xb16f2000, 4096)
08-16 08:18:48.756  8318  8318 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:980
08-16 08:18:48.756   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.756   322  8380 V AudioCache: memcpy(0xaf028000, 0xb16f2000, 4096)
08-16 08:18:48.756   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.756   322  8380 V AudioCache: memcpy(0xaf029000, 0xb16f2000, 4096)
08-16 08:18:48.758  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.761  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.761   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.761   322  8380 V AudioCache: memcpy(0xaf02a000, 0xb16f2000, 4096)
08-16 08:18:48.762   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.762   322  8380 V AudioCache: memcpy(0xaf02b000, 0xb16f2000, 4096)
08-16 08:18:48.762   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.762   322  8380 V AudioCache: memcpy(0xaf02c000, 0xb16f2000, 4096)
08-16 08:18:48.763   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.763   322  8380 V AudioCache: memcpy(0xaf02d000, 0xb16f2000, 4096)
08-16 08:18:48.763   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.763   322  8380 V AudioCache: memcpy(0xaf02e000, 0xb16f2000, 4096)
08-16 08:18:48.764   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.764   322  8380 V AudioCache: memcpy(0xaf02f000, 0xb16f2000, 4096)
08-16 08:18:48.764   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.764   322  8380 V AudioCache: memcpy(0xaf030000, 0xb16f2000, 4096)
08-16 08:18:48.765   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.765   322  8380 V AudioCache: memcpy(0xaf031000, 0xb16f2000, 4096)
08-16 08:18:48.765   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.765   322  8380 V AudioCache: memcpy(0xaf032000, 0xb16f2000, 4096)
08-16 08:18:48.766   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.766   322  8380 V AudioCache: memcpy(0xaf033000, 0xb16f2000, 4096)
08-16 08:18:48.766   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.766   322  8380 V AudioCache: memcpy(0xaf034000, 0xb16f2000, 4096)
08-16 08:18:48.767   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.767   322  8380 V AudioCache: memcpy(0xaf035000, 0xb16f2000, 4096)
08-16 08:18:48.767   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.767   322  8380 V AudioCache: memcpy(0xaf036000, 0xb16f2000, 4096)
08-16 08:18:48.767   322  8380 V AudioCache: write(0xb16f2000, 4096)
08-16 08:18:48.767   322  8380 V AudioCache: memcpy(0xaf037000, 0xb16f2000, 4096)
08-16 08:18:48.768   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 08:18:48.768   322  8380 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 08:18:48.768   322  8380 V AwesomePlayer: postAudioEOS() 
08-16 08:18:48.768   322  8380 V AudioCache: write(0xb16f2000, 280)
08-16 08:18:48.768   322  8380 V AudioCache: memcpy(0xaf038000, 0xb16f2000, 280)
08-16 08:18:48.771   322  8377 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 08:18:48.771   322  8377 V AwesomePlayer: onStreamDone
08-16 08:18:48.771   322  8377 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 08:18:48.771   322  8377 V AudioCache: notify(0xb1432480, 2, 0, 0)
08-16 08:18:48.771   322  8377 V AudioCache: playback complete
08-16 08:18:48.771   322  8377 V AwesomePlayer: pause_l() 
08-16 08:18:48.771   322  8377 V AudioCache: notify(0xb1432480, 7, 0, 0)
08-16 08:18:48.771   322  8377 V AudioCache: ignored
08-16 08:18:48.771   322  8377 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:48.771   322  1398 V AudioCache: wait - success
08-16 08:18:48.771   322  1398 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 08:18:48.771   322  8377 D AudioPlayer: Pause Playback at 1068125
08-16 08:18:48.772   322  1398 V AwesomePlayer: reset_l() 
08-16 08:18:48.772   322  1398 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-16 08:18:48.772   322  1398 V AudioCache: ignored
08-16 08:18:48.772   322  1398 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:48.772   322  1398 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 08:18:48.772   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 08:18:48.772   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 08:18:48.772   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 08:18:48.772   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 0
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-16 08:18:48.772   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1920 on port 1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c14c0 on port 1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 08:18:48.773   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 08:18:48.773   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 08:18:48.773   322  8379 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 08:18:48.773   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 08:18:48.773   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 08:18:48.773   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 08:18:48.774   322  1398 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 08:18:48.774   322  1398 D AudioPlayer: AudioPlayer releasing audio source
08-16 08:18:48.774   322  1398 D AudioPlayer: AudioPlayer done releasing audio source
08-16 08:18:48.774   322  1398 V AwesomePlayer: reset_l() 
08-16 08:18:48.774   322  1398 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:48.774   322  1398 V AwesomePlayer: ~AwesomePlayer call
08-16 08:18:48.774   322  1398 V AwesomePlayer: reset_l() 
08-16 08:18:48.774   322  1398 V AwesomePlayer: cancelPlayerEvents
08-16 08:18:48.775  8318  8374 V SoundPool: close(31)
08-16 08:18:48.775  8318  8374 V SoundPool: pointer = 0xa004a000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 08:18:48.776  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.800  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.802  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 08:18:48.805  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 08:18:48.834  7389  7405 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:48.834  7389  7405 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:48.834  7389  7405 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:48.834  7389  7405 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:48.834  7389  7405 I Adreno-EGL: Remote Branch: 
08-16 08:18:48.834  7389  7405 I Adreno-EGL: Local Patches: 
08-16 08:18:48.834  7389  7405 I Adreno-EGL: Reconstruct Branch: 
08-16 08:18:48.844  8375  8375 D AndroidRuntime: 
08-16 08:18:48.844  8375  8375 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 08:18:48.847  8375  8375 D AndroidRuntime: CheckJNI is OFF
,08-16 08:18:48.965  7742  7742 I UEI.SmartControl: Supports setup maps: true
08-16 08:18:48.968  7742  7742 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 08:18:48.968  7742  7742 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 08:18:48.968  7742  7742 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 08:18:48.968  7742  7742 I UEI.SmartControl: ### init IR Blaster...
,08-16 08:18:48.972  7742  7742 D serial_port: Configuring serial port
08-16 08:18:48.972  7742  7742 E UEI.SmartControl: UEIBLaster setting for 616
08-16 08:18:48.972  7742  7742 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 08:18:48.972  7742  7742 I UEI.SmartControl: configuring settings for MAXQ616
08-16 08:18:48.972  7742  7742 I UEI.SmartControl: Get version...
08-16 08:18:48.984  7389  7405 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:48.984  7389  7405 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:48.984  7389  7405 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:48.984  7389  7405 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:48.984  7389  7405 I Adreno-EGL: Remote Branch: 
08-16 08:18:48.984  7389  7405 I Adreno-EGL: Local Patches: 
08-16 08:18:48.984  7389  7405 I Adreno-EGL: Reconstruct Branch: 
,08-16 08:18:48.990  7742  8392 D UEI.SmartControl: serial port data available: 21
08-16 08:18:49.017  7742  7742 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 08:18:49.017  7742  7742 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 08:18:49.017  7742  7742 I UEI.SmartControl: QS saving settings...
08-16 08:18:49.019  7742  7742 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 08:18:49.031  7389  7405 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 08:18:49.031  7389  7405 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 08:18:49.031  7389  7405 I Adreno-EGL: Build Date: 12/12/14 금
08-16 08:18:49.031  7389  7405 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 08:18:49.031  7389  7405 I Adreno-EGL: Remote Branch: 
08-16 08:18:49.031  7389  7405 I Adreno-EGL: Local Patches: 
08-16 08:18:49.031  7389  7405 I Adreno-EGL: Reconstruct Branch: 
08-16 08:18:49.035  7742  8392 D UEI.SmartControl: serial port data available: 4
,08-16 08:18:49.046  8375  8375 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-16 08:18:49.063  1036  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 08:18:49.064  1036  1114 I ActivityManager: Killing 6862:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 08:18:49.073  7742  7742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 08:18:49.076  7742  8397 I UEI.SmartControl: Device manager: loading config....
08-16 08:18:49.077  7742  8397 D UEI.SmartControl: ----------- loading internal config...
,08-16 08:18:49.082  7742  8397 E UEI.SmartControl: Loading SETTINGS...
,08-16 08:18:49.085  7742  8397 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 08:18:49.095  7742  8396 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 08:18:49.095  7742  8396 D UEI.SmartControl: -----service ready thread exits
,08-16 08:18:49.132  1036  2007 I WindowState: WIN DEATH: Window{b0fe71e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 08:18:49.133  1036  1506 D WifiService: Client connection lost with reason: 4
,08-16 08:18:49.143  1036  2007 D InputDispatcher: Window went away: Window{b0fe71e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 08:18:49.290  1036  1114 I ActivityManager:   Force finishing activity ActivityRecord{2dc4613b u0 com.test.thalitest/.MainActivity t6}
,08-16 08:18:49.347   342   354 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 08:18:49.355  1036  1953 W ActivityManager: Spurious death for ProcessRecord{33704d6d 6862:com.test.thalitest/u0a118}, curProc for 6862: null
08-16 08:18:49.355  7742  7742 E UEI.SmartControl: Services init done
08-16 08:18:49.355  7742  7742 D UEI.SmartControl: QS Service init finished
08-16 08:18:49.357  7742  7742 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 08:18:49.358  7742  7742 D UEI.SmartControl: QS Service version code: 201091
08-16 08:18:49.359  7742  7742 D UEI.SmartControl: Service requested: Control
08-16 08:18:49.360  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 08:18:49.364  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{2dc4613b u0 com.test.thalitest/.MainActivity t6 f}
08-16 08:18:49.365  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{2dc4613b u0 com.test.thalitest/.MainActivity t6 f}
,08-16 08:18:49.387  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-16 08:18:49.390  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 08:18:49.391  1943  3968 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 08:18:49.393  7742  7742 D UEI.SmartControl: Internal service binding...
08-16 08:18:49.393  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 08:18:49.394  2035  2143 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 08:18:49.395  1943  3968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{168d98e3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 08:18:49.396  8318  8318 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 08:18:49.396  1943  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 08:18:49.397  1943  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{217172e0 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 08:18:49.397  7742  7758 I UEI.SmartControl: ------ IControl API: 11
08-16 08:18:49.398  7742  7758 D UEI.SmartControl: File observer start...
08-16 08:18:49.398  7742  7758 E UEI.SmartControl: IR Port is disabled: false
08-16 08:18:49.398  7742  7758 D UEI.SmartControl: Starting file observer...
08-16 08:18:49.398  7742  7758 I UEI.SmartControl: Registering callback...
08-16 08:18:49.399  7742  8146 I UEI.SmartControl: ------ IControl API: 19
08-16 08:18:49.400  7742  8146 I UEI.SmartControl: Registering Services Ready callback...
08-16 08:18:49.400  7742  8146 I UEI.SmartControl: Notify client services are ready...
08-16 08:18:49.401  8318  8336 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 08:18:49.401  8318  8372 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 08:18:49.401  8318  8372 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 08:18:49.402  8318  8318 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,08-16 08:18:49.405  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 08:18:49.406  8318  8318 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 08:18:49.406  7742  7757 I UEI.SmartControl: ------ IControl API: 8
08-16 08:18:49.410  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 08:18:49.410  3813  3813 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 08:18:49.412  4493  4493 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 08:18:49.412  4493  4493 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 08:18:49.412  4493  4493 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 08:18:49.412  4493  4493 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 08:18:49.412  4493  4493 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 08:18:49.412  4493  4493 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 08:18:49.412  4493  4493 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 08:18:49.412  4493  4493 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 08:18:49.413  4493  4493 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:18:49.413  4493  4493 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-16 08:18:49.413  4493  4493 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 08:18:49.413  4493  4493 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 08:18:49.422  7825  7825 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 08:18:49.422  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 08:18:49.423  8256  8256 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 08:18:49.424  8318  8318 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 08:18:49.425  8318  8318 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 08:18:49.425  8318  8318 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,08-16 08:18:49.427  8318  8318 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-16 08:18:49.456  4621  4621 I art     : Explicit concurrent mark sweep GC freed 8205(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 610us total 74.714ms
08-16 08:18:49.459  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 08:18:49.490  8318  8318 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-16 08:18:49.491  8318  8318 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-16 08:18:49.503  2477  2619 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 08:18:49.525  1819  1819 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-16 08:18:49.530  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-16 08:18:49.530  1872  1872 D SplitUIService: removed split : 
08-16 08:18:49.534  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 08:18:49.536  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 08:18:49.537  1907  1907 D ActionManagerService: notifyUserLog: 1000003
08-16 08:18:49.539  3813  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-16 08:18:49.540  1604  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 08:18:49.540  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.540  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 08:18:49.541  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 08:18:49.552  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 08:18:49.552  2194  2194 I ConfigService: onCreate
,08-16 08:18:49.552  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 08:18:49.557  8318  8318 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-16 08:18:49.560  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 08:18:49.561  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 08:18:49.561  1604  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 08:18:49.561  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.562  1036  1036 D administrator: Handling package changes for user 0
08-16 08:18:49.565  2194  2194 I ConfigService: onBind returning update interface
08-16 08:18:49.567  1604  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 08:18:49.567  1604  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:49.567  1604  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 08:18:49.567  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 08:18:49.568  1604  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 08:18:49.569  1907  1907 D ActionManagerService: notifyUserLog: 1000004
,08-16 08:18:49.571  3813  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 08:18:49.572   317  8410 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 08:18:49.572   317  8410 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 08:18:49.572  1604  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 08:18:49.572  1604  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 08:18:49.573  1604  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 08:18:49.573  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.576  1604  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 08:18:49.576  1604  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:49.577  1604  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 08:18:49.577  1604  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 08:18:49.578  1604  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 08:18:49.578  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.582  3813  4510 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 08:18:49.584  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 08:18:49.584  2194  2194 I ConfigService: onBind returning config service
08-16 08:18:49.585  1604  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:49.585  1604  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 08:18:49.585  1604  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 08:18:49.585  1604  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 08:18:49.587  1604  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 08:18:49.587  1604  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 08:18:49.587  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 08:18:49.587  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 08:18:49.587  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-16 08:18:49.587  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 08:18:49.587  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 08:18:49.587  2035  2035 I GBoardWebViewUtils: , display: false
08-16 08:18:49.587  2035  2035 I GBoardWebViewUtils: , animation: false }
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , display: false
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , animation: false }
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_for,ms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , display: false
08-16 08:18:49.588  2035  2035 I GBoardWebViewUtils: , animation: false }
08-16 08:18:49.588  1819  1819 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 08:18:49.591  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
08-16 08:18:49.591  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
08-16 08:18:49.591  8318  8318 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 08:18:49.592  2035  8412 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-16 08:18:49.601  1604  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 08:18:49.601  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.604  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-16 08:18:49.604  1872  1872 I SplitUIService: split app #11
08-16 08:18:49.605  1036  1738 V SIM_STK : Menu title from STK is T-Mobile
08-16 08:18:49.606  1036  1113 W InputMethodInfo: Duplicated subtype definition found: , voice
08-16 08:18:49.609   317  8410 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-16 08:18:49.613  1819  1819 I ConfigFetchService: service connected
08-16 08:18:49.613  1819  1819 I ConfigClient: service connected
,08-16 08:18:49.623  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 08:18:49.623  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-16 08:18:49.653  1036  1595 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 08:18:49.654  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 08:18:49.654  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 08:18:49.654  7825  7825 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 08:18:49.661  1604  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 08:18:49.661  2194  2194 I ConfigService: onDestroy
08-16 08:18:49.661  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.662  1819  8414 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 08:18:49.666  1604  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 08:18:49.666  1604  1650 D KeyguardModel: createShortcutInfo...
,08-16 08:18:49.671  1604  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 08:18:49.671  1604  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 08:18:49.675  1604  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 08:18:49.675  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.677  1604  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 08:18:49.678  1604  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 08:18:49.681  1604  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 08:18:49.681  1604  1650 D KeyguardModel: createShortcutInfo...
,08-16 08:18:49.691  1604  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 08:18:49.691  1604  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 08:18:49.692  1604  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 08:18:49.692  1604  1650 D KeyguardModel: createShortcutInfo...
08-16 08:18:49.695  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 08:18:49.707  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-16 08:18:49.707  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 08:18:49.720  6007  8420 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-16 08:18:49.725  1819  8421 I PeopleContactsSync: CP2 sync disabled
,08-16 08:18:49.728  1819  8419 W GmsApplication: Using Auth Proxy for data requests.
08-16 08:18:49.729  1819  4681 I Icing   : doRemovePackageData com.test.thalitest
08-16 08:18:49.736  1819  8419 W GmsApplication: Using Auth Proxy for data requests.
08-16 08:18:49.741  1036  2007 V SIM_STK : Menu title from STK is T-Mobile
,08-16 08:18:49.755  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 08:18:49.755  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 08:18:49.755  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 08:18:49.756  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 08:18:49.759  7167  7167 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-16 08:18:49.766  2194  2210 I art     : Explicit concurrent mark sweep GC freed 6373(380KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 769us total 16.999ms
08-16 08:18:49.775  2340  8424 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 08:18:49.782  1036  1124 I art     : Explicit concurrent mark sweep GC freed 83363(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 5.408ms total 393.395ms
,08-16 08:18:49.807   334   416 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-16 08:18:49.808  3222  8427 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 08:18:49.809  1036  1905 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8425 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 08:18:49.809  8375  8375 D AndroidRuntime: Shutting down VM
08-16 08:18:49.821  1819  8362 I CheckinTask: Sending checkin request (7886 bytes)
,08-16 08:18:49.832  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 08:18:49.836  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 08:18:49.838  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-16 08:18:49.839  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 08:18:49.840  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 08:18:49.841  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 08:18:49.854  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{56d35d4 u0 com.lge.launcher2/.Launcher t5} time:229413
,08-16 08:18:49.860  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 08:18:49.860  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 08:18:49.861  2035  2189 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 08:18:49.862  2035  2189 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 08:18:49.875  8425  8425 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:49.876  8425  8425 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 08:18:49.877  8425  8425 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 08:18:49.877  8425  8425 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 08:18:49.878  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 08:18:49.879  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 08:18:49.879  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 08:18:49.889  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 08:18:49.891  2630  2630 D [Concierge]Service: onStartCommand(). Type : 8
08-16 08:18:49.891  2630  2630 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 08:18:49.893  2035  2035 D [Concierge]WidgetView: change position of spinner
,08-16 08:18:49.895  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1471328329895
08-16 08:18:49.895  2630  2630 D [Concierge]Service: Update widget ID : 11
08-16 08:18:49.895  2630  2630 D [Concierge]Service: onStartCommand(). Type : 0
08-16 08:18:49.920  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 790101679
08-16 08:18:49.921  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 08:18:49.921  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 08:18:49.924  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@20f5c05b
08-16 08:18:49.924  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 08:18:49.925  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 08:18:49.925  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 08:18:49.930  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 08:18:49.930  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 08:18:49.931  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471328128863, New one : 1471328329895
08-16 08:18:49.931  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-16 08:18:49.931  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 08:18:49.931  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 08:18:49.931  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 08:18:49.933  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 08:18:49.934  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 08:18:49.934  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 08:18:49.935  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 08:18:49.936  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 08:18:49.937  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-16 08:18:49.941  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 08:18:49.941  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 08:18:49.942  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 08:18:49.945  8425  8425 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 08:18:49.960  8425  8425 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 08:18:49.987  8425  8425 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 08:18:49.989  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 08:18:49.999  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 08:18:49.999  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 08:18:50.000  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 08:18:50.002  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 08:18:50.005  1819  8362 I art     : Explicit concurrent mark sweep GC freed 31788(2MB) AllocSpace objects, 20(312KB) LOS objects, 51% free, 30MB/62MB, paused 984us total 23.579ms
08-16 08:18:50.008  1819  1831 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 08:18:50.008  1819  1831 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 08:18:50.009  1819  1831 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 08:18:50.018  8425  8425 D LgDataFeature: LgDataFeature() Constructor: none
08-16 08:18:50.018  8425  8425 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 08:18:50.023  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1285fb14 time:229582
08-16 08:18:50.051  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8450 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 08:18:50.086  1819  8362 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-16 08:18:50.092  1819  8362 I CheckinService: active receiver: disabled
08-16 08:18:50.096  8425  8425 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 08:18:50.126  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 08:18:50.139  1036  2053 I ActivityManager: Killing 7858:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 08:18:50.163  2035  2915 I GBoardtInterface: onReloaded()
,08-16 08:18:50.165  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 08:18:50.182  1036  1595 W libprocessgroup: failed to open /acct/uid_10072/pid_7858/cgroup.procs: No such file or directory
,08-16 08:18:50.184  1036  2053 I ActivityManager: Killing 7951:com.android.vending/u0a44 (adj 15): empty #17
08-16 08:18:50.184  3813  4510 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 08:18:50.202  1998  1998 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 08:18:50.202  1998  1998 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-16 08:18:50.203  1036  1738 W libprocessgroup: failed to open /acct/uid_10044/pid_7951/cgroup.procs: No such file or directory
08-16 08:18:50.204  1998  1998 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 08:18:50.206  3813  3828 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-16 08:18:50.211  8256  8256 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 08:18:50.213  8256  8256 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 08:18:50.213  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-16 08:18:50.215  3813  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 08:18:50.215  3813  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-16 08:18:50.217  7612  7612 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-16 08:18:50.219  6953  6953 D PackageIntentReceiver: Not supported Hotkey customization function 
08-16 08:18:50.219  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-16 08:18:50.221  3813  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 08:18:50.221  3813  4510 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 08:18:50.221  3813  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 08:18:50.221  3813  4514 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 08:18:50.221  3813  4514 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 08:18:50.223  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 08:18:50.223  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 08:18:50.225  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 08:18:50.225  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 08:18:50.226  1036  1440 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=87.0 bcn=0 [on:0 tx:0 rx:0 period:1984] from screen [on:0 period:-1845452302] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 08:18:50.226  6953  6953 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-16 08:18:50.226  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2447 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=87.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1845452302] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 08:18:50.226  6953  6953 D HideNavigationAppsReceiver: replacing : false
08-16 08:18:50.226  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]

```
