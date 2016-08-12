#### Test 79763830b0b67a9_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 13:04:08.152  4295  4468 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 13:04:08.157  1599  1599 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-12 13:04:08.157  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 13:04:08.159  1599  1599 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 13:04:08.160  5597  5597 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-12 13:04:10.131  6847  6847 D AndroidRuntime: 
08-12 13:04:10.131  6847  6847 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 13:04:10.137  6847  6847 D AndroidRuntime: CheckJNI is OFF
08-12 13:04:10.341  6847  6847 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 13:04:10.353  1034  1050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 13:04:10.368  1939  2948 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 13:04:10.374  1034  1050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 13:04:10.376  1034  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{3af0bcb8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 13:04:10.376  1034  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{3af0bcb8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 13:04:10.378  1034  1050 D WindowStateEx: AppWindowTokenEx init.. 
08-12 13:04:10.379   336   341 E GBMv2   : DFP En is all cleared set to be enabled
08-12 13:04:10.407  1034  1050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6862 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 13:04:10.409  6847  6847 D AndroidRuntime: Shutting down VM
08-12 13:04:10.470  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 13:04:10.470  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{22e4006e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 13:04:10.472  1939  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 13:04:10.472  1939  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1649e30f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 13:04:10.516  6862  6862 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 13:04:10.591  6862  6862 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-12 13:04:10.599  6862  6862 I LibraryLoader: Loading: webviewchromium
08-12 13:04:10.602  6862  6862 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 845-848)
08-12 13:04:10.602  6862  6862 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 13:04:10.636  6862  6862 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2dce864c}
,08-12 13:04:10.639  6862  6862 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 13:04:10.641  6862  6862 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 13:04:10.655  6862  6862 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 13:04:10.657  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 13:04:10.670  6862  6862 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-12 13:04:10.673  6862  6862 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 13:04:10.673  6862  6862 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 13:04:10.683   315  2193 V AudioPolicyService: registerClient() client 0xb558a940, uid 10118
,08-12 13:04:10.690  1034  1116 D BluetoothManagerService: Message: 20
08-12 13:04:10.690  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c893382:true
08-12 13:04:10.690  6862  6862 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 13:04:10.690  6862  6862 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 13:04:10.690  6862  6862 I Adreno-EGL: Build Date: 12/12/14 금
08-12 13:04:10.690  6862  6862 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 13:04:10.690  6862  6862 I Adreno-EGL: Remote Branch: 
08-12 13:04:10.690  6862  6862 I Adreno-EGL: Local Patches: 
08-12 13:04:10.690  6862  6862 I Adreno-EGL: Reconstruct Branch: 
08-12 13:04:10.785  6862  6903 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 13:04:10.788  6862  6862 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 13:04:10.827  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 13:04:10.832  6862  6862 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 13:04:10.836  6862  6862 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 13:04:10.839  6862  6862 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 13:04:10.839  6862  6862 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 13:04:10.856  6862  6862 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 13:04:10.866  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 13:04:10.866  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 13:04:10.911  6862  6915 D OpenGLRenderer: Render dirty regions requested: true
08-12 13:04:10.911  6862  6915 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 13:04:10.921  6862  6915 D OpenGLRenderer: Enabling debug mode 0
,08-12 13:04:10.940  6862  6862 D Atlas   : Validating map...
,08-12 13:04:10.955  1034  1899 D SplitWindow: check instance of lgWin Window{20adc42c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 13:04:10.966  1034  1095 W ActivityManager: Activity pause timeout for ActivityRecord{20509a91 u0 com.test.thalitest/.MainActivity t6}
,08-12 13:04:11.012  6862  6913 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 13:04:11.012  6862  6913 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 13:04:11.116  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +651ms (total +736ms)
08-12 13:04:11.117  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20509a91 u0 com.test.thalitest/.MainActivity t6} time:191363
,08-12 13:04:11.125  6862  6862 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24f3f18b time:191371
08-12 13:04:11.247  6862  6862 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 13:04:11.304  6862  6862 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 13:04:11.304  6862  6862 I chromium: 
,08-12 13:04:11.430  6862  6929 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435147776
,08-12 13:04:11.454  6862  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 13:04:11.454  6862  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 13:04:11.454  6862  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 13:04:11.454  6862  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 13:04:11.454  6862  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 13:04:11.454  6862  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3059105f added. We now have 1 listener(s)
08-12 13:04:11.460  1034  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 13:04:11.463  6862  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 13:04:11.464  6862  6929 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 13:04:11.466  6862  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 13:04:11.466  6862  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 13:04:11.474  6862  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c657f0a added. We now have 1 listener(s)
08-12 13:04:11.475  6862  6929 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 13:04:11.479  1034  1448 D WifiService: New client listening to asynchronous messages
,08-12 13:04:11.485  6862  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 13:04:11.485  6862  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 13:04:11.485  6862  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 13:04:11.485  6862  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 13:04:11.486  6862  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 13:04:11.490  6862  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 13:04:11.491  1034  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-12 13:04:11.494  6862  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 13:04:11.503  6862  6929 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:04:11.504  6862  6929 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 13:04:11.504  6862  6929 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 13:04:11.504  6862  6929 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 13:04:11.508  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 13:04:11.510  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 13:04:11.511  6862  6929 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 13:04:11.557  6862  6913 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 13:04:11.557  6862  6913 I chromium: 
,08-12 13:04:11.603   336   343 E GBMv2   : DFP En is all cleared set to be enabled
08-12 13:04:11.604   336   343 E GBMv2   : Set value is all cleared set the max
08-12 13:04:11.604   336   343 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 13:04:11.630  6862  6862 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 13:04:12.636  6862  6932 W jxcore-log: Initializing JXcore engine
,08-12 13:04:12.636  6862  6932 W jxcore-log: JXcore engine is ready
,08-12 13:04:12.710  6932  6932 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9727]" dev="sockfs" ino=9727 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 13:04:12.710  6932  6932 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 13:04:12.710  6932  6932 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10426]" dev="sockfs" ino=10426 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 13:04:12.710  6932  6932 W Thread-812: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 13:04:12.710  6932  6932 W Thread-812: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32696]" dev="sockfs" ino=32696 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 13:04:12.742  6862  6932 W jxcore-log: Starting JXcore engine
,08-12 13:04:12.895  6862  6932 W jxcore-log: Platform android
08-12 13:04:12.895  6862  6932 W jxcore-log: 
08-12 13:04:12.895  6862  6932 W jxcore-log: Process ARCH arm
08-12 13:04:12.895  6862  6932 W jxcore-log: 
,08-12 13:04:13.097  6862  6932 I jxcore-log: JXcore Cordova bridge is ready!
08-12 13:04:13.097  6862  6932 I jxcore-log: 
08-12 13:04:13.097  6862  6932 W jxcore-log: JXcore engine is started
,08-12 13:04:13.107  6862  6929 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 13:04:13.112  6862  6862 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 13:04:22.979  6862  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 13:04:22.979  6862  6932 I jxcore-log: 
,08-12 13:04:22.982  6862  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 13:04:22.982  6862  6932 I jxcore-log: 
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:04:22.985  6862  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 13:04:22.988  6862  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 13:04:22.990  6862  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 13:04:22.990  6862  6932 I jxcore-log: 
08-12 13:04:22.992  6862  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 13:04:22.992  6862  6932 I jxcore-log: 
,08-12 13:04:23.315  6862  6932 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 13:04:23.316  6862  6932 I jxcore-log: Failed to execute UT.
08-12 13:04:23.316  6862  6932 I jxcore-log: 
08-12 13:04:23.316  6862  6932 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 13:04:23.316  6862  6932 I jxcore-log: 
,08-12 13:04:23.326  6862  6862 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 13:04:23.327  6862  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 13:04:23.327  6862  6932 I jxcore-log: 
08-12 13:04:23.680  6933  6933 D AndroidRuntime: 
08-12 13:04:23.680  6933  6933 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 13:04:23.685  6933  6933 D AndroidRuntime: CheckJNI is OFF
08-12 13:04:23.914  6933  6933 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 13:04:23.930  1034  1095 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 13:04:23.931  1034  1095 I ActivityManager: Killing 6862:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 13:04:24.007  1034  1911 I WindowState: WIN DEATH: Window{20adc42c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 13:04:24.010  1034  1448 D WifiService: Client connection lost with reason: 4
08-12 13:04:24.026  1034  1911 D InputDispatcher: Window went away: Window{20adc42c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 13:04:24.148  1034  1095 I ActivityManager:   Force finishing activity ActivityRecord{20509a91 u0 com.test.thalitest/.MainActivity t6}
,08-12 13:04:24.183   336   341 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 13:04:24.189  1034  1571 W ActivityManager: Spurious death for ProcessRecord{34b09ae2 6862:com.test.thalitest/u0a118}, curProc for 6862: null
08-12 13:04:24.189  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 13:04:24.192  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{20509a91 u0 com.test.thalitest/.MainActivity t6 f}
08-12 13:04:24.192  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{20509a91 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 13:04:24.250  5042  5042 I art     : Explicit concurrent mark sweep GC freed 473(32KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 553us total 49.314ms
,08-12 13:04:24.256  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 13:04:24.257  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d3e6f9c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 13:04:24.258  1939  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 13:04:24.258  1939  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{383f3da5 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 13:04:24.258  2031  2031 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 13:04:24.260  2031  2031 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 13:04:24.261  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 13:04:24.263  2031  2101 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,08-12 13:04:24.268  1902  1902 D ActionManagerService: notifyUserLog: 1000003
08-12 13:04:24.269  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 13:04:24.269  3802  4962 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 13:04:24.271  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 13:04:24.284  4295  4295 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 13:04:24.284  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-12 13:04:24.290  1993  1993 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 13:04:24.290  3802  3802 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-12 13:04:24.294  1034  1378 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 13:04:24.299  2480  2677 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 13:04:24.300  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 13:04:24.319  1034  2010 V SIM_STK : Menu title from STK is T-Mobile
,08-12 13:04:24.327  1034  1093 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 13:04:24.354  4941  4941 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 13:04:24.354  4941  4941 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 13:04:24.354  4941  4941 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 13:04:24.354  4941  4941 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 13:04:24.354  4941  4941 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 13:04:24.355  4941  4941 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 13:04:24.355  4941  4941 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:04:24.355  4941  4941 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 13:04:24.355  4941  4941 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 13:04:24.355  4941  4941 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 13:04:24.355  4941  4941 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 13:04:24.355  4941  4941 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-12 13:04:24.367  2031  2031 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 13:04:24.371  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-12 13:04:24.375  2031  2031 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 13:04:24.377  2031  2031 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 13:04:24.381  1902  1902 D ActionManagerService: notifyUserLog: 1000004
08-12 13:04:24.381  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 13:04:24.381  3802  4962 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 13:04:24.391  3802  3817 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-12 13:04:24.392  1599  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 13:04:24.392  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.393  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-12 13:04:24.404  1034  1034 I art     : Explicit concurrent mark sweep GC freed 24065(1455KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.460ms total 153.244ms
,08-12 13:04:24.407  1599  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 13:04:24.407  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , display: false
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , animation: false }
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , display: false
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , animation: false }
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , create_time: 1470393743569
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , expire_time: 0
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , display: false
08-12 13:04:24.410  2031  2031 I GBoardWebViewUtils: , animation: false }
08-12 13:04:24.410  2163  2163 I ConfigService: onCreate
08-12 13:04:24.411  2163  2163 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 13:04:24.412  1599  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 13:04:24.413  1599  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 13:04:24.413  1599  1648 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 13:04:24.414  1599  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 13:04:24.416  1599  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:04:24.416  1599  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 13:04:24.417  2163  2163 I ConfigService: onBind returning update interface
,08-12 13:04:24.429  1599  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 13:04:24.429  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.433  2031  6960 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 13:04:24.434  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 13:04:24.435  2163  2163 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 13:04:24.435  2163  2163 I ConfigService: onBind returning config service
08-12 13:04:24.439  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 13:04:24.439  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 13:04:24.441  1599  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 13:04:24.441  1599  1648 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 13:04:24.441  1815  1815 I ConfigFetchService: service connected
08-12 13:04:24.444  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-12 13:04:24.445  1867  1867 D SplitUIService: removed split : 
08-12 13:04:24.446  2163  2163 I ConfigService: onDestroy
08-12 13:04:24.448  1599  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:04:24.448  1599  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 13:04:24.451  2031  2031 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 13:04:24.455  1599  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 13:04:24.455  1599  1648 D KeyguardModel: createShortcutInfo...
,08-12 13:04:24.468  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-12 13:04:24.468  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-12 13:04:24.469  1599  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 13:04:24.469  1599  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 13:04:24.469  1599  1648 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 13:04:24.469  1599  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 13:04:24.471  1599  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:04:24.471  1599  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-12 13:04:24.474  1815  6963 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 13:04:24.479  1599  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 13:04:24.479  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.482  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-12 13:04:24.482  1867  1867 I SplitUIService: split app #11
08-12 13:04:24.493  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-12 13:04:24.493  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-12 13:04:24.502  1599  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 13:04:24.502  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.504  1599  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 13:04:24.504  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.507  1599  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:04:24.507  1599  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-12 13:04:24.509  1599  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 13:04:24.509  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.511  1599  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:04:24.511  1599  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 13:04:24.512  1599  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 13:04:24.512  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.513  1599  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:04:24.513  1599  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 13:04:24.514  1599  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 13:04:24.514  1599  1648 D KeyguardModel: createShortcutInfo...
08-12 13:04:24.515  1034  1975 V SIM_STK : Menu title from STK is T-Mobile
08-12 13:04:24.520  1034  2025 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 13:04:24.521  4295  4295 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 13:04:24.522  1034  1034 D administrator: Handling package changes for user 0
08-12 13:04:24.528  5862  6968 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-12 13:04:24.542  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 13:04:24.552  1815  6970 I PeopleContactsSync: CP2 sync disabled
,08-12 13:04:24.554  1815  5227 I Icing   : doRemovePackageData com.test.thalitest
,08-12 13:04:24.560  2031  2031 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 13:04:24.561  6491  6491 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 13:04:24.565  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-12 13:04:24.565  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 13:04:24.573  1815  6969 W GmsApplication: Using Auth Proxy for data requests.
,08-12 13:04:24.582  1815  6969 W GmsApplication: Using Auth Proxy for data requests.
08-12 13:04:24.593  2348  6973 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 13:04:24.595  6513  6513 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 13:04:24.607  1993  1993 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 13:04:24.607  1993  1993 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-12 13:04:24.609  1993  1993 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 13:04:24.613  6395  6395 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 13:04:24.636  1034  1975 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6976 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 13:04:24.643  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 13:04:24.643  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 13:04:24.643  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 13:04:24.645  1034  1574 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-12 13:04:24.705  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-12 13:04:24.708  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:04:24.709  6976  6976 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 13:04:24.709  6976  6976 W LG Account v2.2: No ProfileInfo entries
08-12 13:04:24.709  6976  6976 I LG Account v2.2: isEnabled: false
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Country: EU
08-12 13:04:24.710  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Operator: OPEN
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Ranking support: false
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Comfort support: false
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Accessory: true
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Health device: true
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Extra Pedometer: false
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Blood glucose device: false
08-12 13:04:24.710  6976  6976 I Feature : [Lifetracker]Device Number: 3
08-12 13:04:24.711  6976  6976 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 13:04:24.711  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 13:04:24.712  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 13:04:24.713  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 13:04:24.744  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 13:04:24.744  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:04:24.745  2031  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 13:04:24.745  2031  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-12 13:04:24.751  1034  2030 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6997 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 13:04:24.752  1034  1122 I art     : Explicit concurrent mark sweep GC freed 13180(904KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.030ms total 332.123ms
08-12 13:04:24.752  1034  2030 I ActivityManager: Killing 6197:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-12 13:04:24.761  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 13:04:24.762  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 13:04:24.762  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 13:04:24.769  2031  2031 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 13:04:24.801  1034  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 13:04:24.805  1034  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 13:04:24.815  1034  1911 W libprocessgroup: failed to open /acct/uid_10014/pid_6197/cgroup.procs: No such file or directory
,08-12 13:04:24.828  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c71feb8 u0 com.lge.launcher2/.Launcher t5} time:205074
,08-12 13:04:24.828  2575  2575 D [Concierge]Service: onStartCommand(). Type : 8
08-12 13:04:24.828  2575  2575 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 13:04:24.831  2575  2575 D [Concierge]Service: Update widget ID : 11
08-12 13:04:24.832  2031  2031 D [Concierge]WidgetView: change position of spinner
08-12 13:04:24.834  2031  2031 I [Concierge]WidgetView: initWebView(). Time : 1470999864834
08-12 13:04:24.834  2575  2575 D [Concierge]Service: onStartCommand(). Type : 0
,08-12 13:04:24.848  6997  6997 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 13:04:24.848  6997  6997 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-12 13:04:24.848  6997  6997 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 13:04:24.848  6997  6997 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 13:04:24.850  6997  6997 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 13:04:24.850  6997  6997 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 13:04:24.852  2031  2031 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 657709603
08-12 13:04:24.852  2031  2031 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 13:04:24.853  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 13:04:24.856  2031  2031 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@5cf34d2
08-12 13:04:24.857  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 13:04:24.858  2031  2031 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 13:04:24.858  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:04:24.866  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 13:04:24.866  2031  2031 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 13:04:24.867  2031  2031 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 13:04:24.868  2031  2031 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 13:04:24.868  2031  2031 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470999688083, New one : 1470999864834
08-12 13:04:24.868  2031  2031 D [Concierge]WidgetView: Unregister all receivers
08-12 13:04:24.868  2031  2031 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 13:04:24.869  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:04:24.871  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 13:04:24.872  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 13:04:24.873  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 13:04:24.875  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 13:04:24.876  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 13:04:24.877  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:04:24.877  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:04:24.916  2031  2031 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 13:04:24.921  6933  6933 D AndroidRuntime: Shutting down VM
08-12 13:04:24.925  2031  2031 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 13:04:24.926  2031  2031 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 13:04:24.927  2031  2031 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 13:04:24.949  2031  2031 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1738a33c time:205195
,08-12 13:04:24.994  6997  6997 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-12 13:04:25.001  6997  6997 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-12 13:04:25.001  6997  6997 D HideNavigationAppsReceiver: replacing : false
08-12 13:04:25.004  6997  6997 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-12 13:04:25.007  6997  6997 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 13:04:25.007  6997  6997 D ButtonCombinationReceiver: replacing : false
,08-12 13:04:25.020  1034  1050 I ActivityManager: Killing 6442:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-12 13:04:25.084  2031  2031 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 13:04:25.097  1034  2010 W libprocessgroup: failed to open /acct/uid_10008/pid_6442/cgroup.procs: No such file or directory
08-12 13:04:25.118  5042  7016 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 13:04:25.126  2031  2869 I GBoardtInterface: onReloaded()
08-12 13:04:25.128  2031  2031 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 13:04:25.130  3802  3817 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-12 13:04:25.134  3802  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 13:04:25.182  1034  1974 V SIM_STK : Menu title from STK is T-Mobile
,08-12 13:04:25.214  1034  1050 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7018 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-12 13:04:25.217  1902  1902 D ActionManagerService: notifyUserLog: 1000001
08-12 13:04:25.219  3802  4962 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 13:04:25.219  3802  4962 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 13:04:25.222  1902  1902 D ActionManagerService: notifyUserLog: 1000001
08-12 13:04:25.224  3802  4962 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 13:04:25.224  3802  4962 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 13:04:25.224  3802  4962 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 13:04:25.224  3802  4962 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 13:04:25.225  3802  3817 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 13:04:25.228  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 13:04:25.228  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-12 13:04:25.232  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 13:04:25.232  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 13:04:25.234  2031  2031 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 13:04:25.234  2031  2031 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-12 13:04:25.265  5042  7016 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 13:04:25.275  2163  2179 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-12 13:04:25.276  2163  2179 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.b(SourceFile:56)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.a(SourceFile:48)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at com.google.android.gms.common.internal.be.a(SourceFile:45)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at com.google.android.gms.icing.service.n.b(SourceFile:118)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at com.google.android.gms.common.internal.bd.b(SourceFile:218)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at com.google.android.gms.common.internal.ao.onTransact(SourceFile:460)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at android.os.Binder.execTransact(Binder.java:446)
08-12 13:04:25.276  2163  2179 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 13:04:25.276  2163  2179 W ServiceConnection: 	... 10 more
,08-12 13:04:25.281  1815  5227 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-12 13:04:25.281  1815  5227 E Icing   : Could not init tag ds.tag.corpusid-1
08-12 13:04:25.281  1815  5227 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-12 13:04:25.281  1815  5227 E Icing   : Could not init tag ds.tag.corpusid-13
08-12 13:04:25.281  1815  5227 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-12 13:04:25.281  1815  5227 E Icing   : Could not init tag ds.tag.corpusid-7
08-12 13:04:25.281  1815  5227 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-12 13:04:25.281  1815  5227 E Icing   : Could not init tag ds.tag.corpusid-8
08-12 13:04:25.281  1815  5227 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-12 13:04:25.281  1815  5227 E Icing   : Could not init tag ds.tag.corpusid-9
08-12 13:04:25.281  1815  5227 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-12 13:04:25.281  1815  5227 E Icing   : Could not init tag ds.tag.deleted
08-12 13:04:25.282  1815  5227 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-12 13:04:25.282  1815  5227 E Icing   : Writing status failed
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: Exception thrown from notifyTableChanged
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at beg.a(PG:301)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at beg.c(PG:222)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at cun.b(PG:660)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at cun.a(PG:651)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at cun.g(PG:597)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at cuw.Tg(PG:368)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at cuy.ub(PG:301)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.execute(,SQLiteConnection.java:560)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at bea.a(PG:382)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at beg.i(PG:325)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at beh.call(PG:215)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	at beg.a(PG:299)
08-12 13:04:25.282  5042  7016 E IcingCorporaProvider: 	... 15 more
08-12 13:04:25.282  5042  7016 W IcingCorporaProvider: notifyTableChanged failed.
08-12 13:04:25.282  5042  7016 W IcingCorporaProvider: Table change notification failed for TableStorageSpec[applications]
08-12 13:04:25.282  5042  7016 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 164 ms] updated apps [took 164 ms] 
08-12 13:04:25.286  7018  7018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
08-12 13:04:25.305  6656  6656 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-12 13:04:25.307  6656  6656 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-12 13:04:25.307  6656  6656 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-12 13:04:25.307  6656  6656 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-12 13:04:25.307  6656  6656 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-12 13:04:25.307  6656  6656 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-12 13:04:25.319  5597  5597 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
08-12 13:04:25.327  6997  6997 D PackageIntentReceiver: Not supported Hotkey customization function 
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:04:25.335  7018  7037 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
08-12 13:04:25.336  7018  7037 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-12 13:04:25.336  7018  7037 E AndroidRuntime: Process: com.android.keychain, PID: 7018
08-12 13:04:25.336  7018  7037 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDa,tabase.java:907)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:04:25.336  7018  7037 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 13:04:25.364  1034  1729 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7040 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a
,08-12 13:04:25.369  7018  7037 I Process : Sending signal. PID: 7018 SIG: 9
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: Can't write: system_app_crash
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 13:04:25.374  1034  7050 E DropBoxManagerService: 	... 5 more
08-12 13:04:25.424  1034  1571 I ActivityManager: Process com.android.keychain (pid 7018) has died
,08-12 13:04:25.424  1034  1571 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
08-12 13:04:25.459   281   791 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
