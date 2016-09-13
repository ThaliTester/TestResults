#### Test 836273372e7ca3d_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 09:18:00.057  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
09-13 09:18:00.066  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 09:18:00.066  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-13 09:18:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-13 09:18:00.071  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 09:18:19.338  6652  6652 D AndroidRuntime: 
09-13 09:18:19.338  6652  6652 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 09:18:19.343  6652  6652 D AndroidRuntime: CheckJNI is OFF
09-13 09:18:19.468  6652  6652 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 09:18:19.473  1035  2019 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 09:18:19.483  1927  3115 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 09:18:19.486  1035  2019 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 09:18:19.487  1035  2019 D ActivityManager: setTaskToReturnTo : TaskRecord{25e34bf5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 09:18:19.487  1035  2019 D ActivityManager: setTaskToReturnTo : TaskRecord{25e34bf5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 09:18:19.488  1035  2019 D WindowStateEx: AppWindowTokenEx init.. 
09-13 09:18:19.489   337   371 E GBMv2   : DFP En is all cleared set to be enabled
09-13 09:18:19.520  1035  2019 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6667 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 09:18:19.521  6652  6652 D AndroidRuntime: Shutting down VM
09-13 09:18:19.563  1927  3115 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 09:18:19.563  1927  3115 D SplitWindowPolicy: topRunningActivity=ActivityInfo{fea7793 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 09:18:19.564  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 09:18:19.564  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5f5e3d0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 09:18:19.617  6667  6667 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 09:18:19.711  6667  6667 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-13 09:18:19.719  6667  6667 I LibraryLoader: Loading: webviewchromium
,09-13 09:18:19.722  6667  6667 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6420-6423)
09-13 09:18:19.723  6667  6667 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 09:18:19.747  6667  6667 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26d221b9}
,09-13 09:18:19.749  6667  6667 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 09:18:19.749  6667  6667 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 09:18:19.758  6667  6667 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 09:18:19.759  6667  6667 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 09:18:19.775  6667  6667 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-13 09:18:19.776  6667  6667 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 09:18:19.776  6667  6667 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-13 09:18:19.780   312   312 V AudioPolicyService: registerClient() client 0xb1427180, uid 10118
09-13 09:18:19.785  1035  1117 D BluetoothManagerService: Message: 20
09-13 09:18:19.785  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@109040d7:true
09-13 09:18:19.798  6667  6667 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 09:18:19.798  6667  6667 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 09:18:19.798  6667  6667 I Adreno-EGL: Build Date: 12/12/14 금
09-13 09:18:19.798  6667  6667 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 09:18:19.798  6667  6667 I Adreno-EGL: Remote Branch: 
09-13 09:18:19.798  6667  6667 I Adreno-EGL: Local Patches: 
09-13 09:18:19.798  6667  6667 I Adreno-EGL: Reconstruct Branch: 
,09-13 09:18:19.864  6667  6702 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 09:18:19.873  6667  6667 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-13 09:18:19.888  6667  6667 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 09:18:19.893  6667  6667 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 09:18:19.895  6667  6667 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 09:18:19.898  6667  6667 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 09:18:19.898  6667  6667 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 09:18:19.911  6667  6667 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 09:18:19.918  6667  6667 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 09:18:19.918  6667  6667 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 09:18:19.953  6667  6714 D OpenGLRenderer: Render dirty regions requested: true
09-13 09:18:19.953  6667  6714 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 09:18:19.968  6667  6714 D OpenGLRenderer: Enabling debug mode 0
,09-13 09:18:19.979  6667  6667 D Atlas   : Validating map...
09-13 09:18:19.983  1035  1890 D SplitWindow: check instance of lgWin Window{37842419 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 09:18:20.004  6667  6712 D LgDataFeature: LgDataFeature() Constructor: none
09-13 09:18:20.004  6667  6712 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 09:18:20.125  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +563ms (total +635ms)
09-13 09:18:20.125  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{176a2d8a u0 com.test.thalitest/.MainActivity t6} time:166827
,09-13 09:18:20.130  6667  6667 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bf687dc time:166832
09-13 09:18:20.230  6667  6667 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 09:18:20.303  6667  6712 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 09:18:20.303  6667  6712 I chromium: 
,09-13 09:18:20.439  6667  6725 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,09-13 09:18:20.454  6667  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 09:18:20.454  6667  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 09:18:20.454  6667  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 09:18:20.454  6667  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 09:18:20.454  6667  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 09:18:20.455  6667  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e2a05e0 added. We now have 1 listener(s)
09-13 09:18:20.460  1035  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 09:18:20.463  6667  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 09:18:20.467  6667  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 09:18:20.470  6667  6667 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 09:18:20.470  6667  6667 I chromium: 
,09-13 09:18:20.472  6667  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:18:20.472  6667  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 09:18:20.480  6667  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56acf3f added. We now have 1 listener(s)
09-13 09:18:20.481  6667  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:18:20.484  1035  1529 D WifiService: New client listening to asynchronous messages
09-13 09:18:20.488  6667  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:18:20.488  6667  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 09:18:20.490  6667  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 09:18:20.491  6667  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 09:18:20.491  6667  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 09:18:20.497  6667  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:20.498  1035  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:20.499  6667  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 09:18:20.511  6667  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:20.514  6667  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:20.514  6667  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 09:18:20.514  6667  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:20.516  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:20.518  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:20.518  6667  6725 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 09:18:20.551  6667  6667 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 09:18:21.186   337   373 E GBMv2   : DFP En is all cleared set to be enabled
09-13 09:18:21.186   337   373 E GBMv2   : Set value is all cleared set the max
09-13 09:18:21.186   337   373 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 09:18:21.226  6667  6728 W jxcore-log: Initializing JXcore engine
09-13 09:18:21.226  6667  6728 W jxcore-log: JXcore engine is ready
,09-13 09:18:21.249  6728  6728 W Thread-767: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9874]" dev="sockfs" ino=9874 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 09:18:21.249  6728  6728 W Thread-767: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-13 09:18:21.249  6728  6728 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8478]" dev="sockfs" ino=8478 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 09:18:21.249  6728  6728 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 09:18:21.249  6728  6728 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31322]" dev="sockfs" ino=31322 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-13 09:18:21.276  6667  6728 W jxcore-log: Starting JXcore engine
09-13 09:18:21.443  6667  6728 W jxcore-log: Platform android
09-13 09:18:21.443  6667  6728 W jxcore-log: 
09-13 09:18:21.443  6667  6728 W jxcore-log: Process ARCH arm
09-13 09:18:21.443  6667  6728 W jxcore-log: 
,09-13 09:18:21.677  6667  6728 I jxcore-log: JXcore Cordova bridge is ready!
09-13 09:18:21.677  6667  6728 I jxcore-log: 
09-13 09:18:21.678  6667  6728 W jxcore-log: JXcore engine is started
,09-13 09:18:21.686  6667  6725 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 09:18:21.689  6667  6667 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 09:18:31.293  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 09:18:31.293  6667  6728 I jxcore-log: 
,09-13 09:18:31.295  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 09:18:31.295  6667  6728 I jxcore-log: 
,09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:31.300  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:31.302  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:31.304  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 09:18:31.304  6667  6728 I jxcore-log: 
09-13 09:18:31.305  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 09:18:31.305  6667  6728 I jxcore-log: 
09-13 09:18:31.814  6667  6728 I jxcore-log: Unit Test app is loaded
09-13 09:18:31.814  6667  6728 I jxcore-log: 
,09-13 09:18:31.823  6667  6667 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 09:18:31.832  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:18:31.832  6667  6728 I jxcore-log: 
09-13 09:18:31.844  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 09:18:31.844  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7e25b9 added. We now have 2 listener(s)
,09-13 09:18:31.845  1035  1866 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:31.847  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 09:18:31.847  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:18:31.847  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:18:31.847  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:18:31.847  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a4a9dfe added. We now have 2 listener(s)
09-13 09:18:31.847  6667  6728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:18:31.847  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:18:31.849  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:31.851  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:31.852  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:31.853  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:31.853  6667  6728 D ExecuteNativeTests: Running unit tests
09-13 09:18:31.854  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:31.854  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 09:18:31.854  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@163dafac added. We now have 3 listener(s)
09-13 09:18:31.854  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:31.855  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:31.858  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 09:18:31.858  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:18:31.858  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:18:31.858  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:18:31.858  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed26475 added. We now have 3 listener(s)
09-13 09:18:31.859  6667  6728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:18:31.859  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:18:31.862  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:31.864  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:31.865  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:31.865  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:31.866  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:31.867  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:42.024  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 09:18:42.024  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b added. We now have 4 listener(s)
,09-13 09:18:42.027  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 09:18:42.030  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 09:18:42.030  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:18:42.030  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:18:42.030  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:18:42.030  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 added. We now have 4 listener(s)
09-13 09:18:42.030  6667  6728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:18:42.031  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:18:42.034  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:42.037  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:18:42.042  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.042  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:42.044  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.045  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.052  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 09:18:42.056  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.056  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.056  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.056  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.059  6667  6728 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 09:18:42.059  6667  6728 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 09:18:42.059  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 09:18:42.060  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.060  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.060  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.060  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.062  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.062  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.062  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.063  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 09:18:42.063  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b removed from the list
09-13 09:18:42.063  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.063  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 removed from the list
09-13 09:18:42.063  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.063  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.066  6667  6728 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 09:18:42.066  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.066  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.066  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.067  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.067  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.067  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.067  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09,:18:42.067  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.067  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.075  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 09:18:42.076  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 09:18:42.077  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.077  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.077  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.077  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.077  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.077  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.077  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.077  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.077  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.078  6667  6728 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 09:18:42.081  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:42.086  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:42.087  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.087  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:42.089  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.090  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.091  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:42.091  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 09:18:42.091  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 09:18:42.091  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.091  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 09:18:42.198  1035  1614 I art     : Explicit concurrent mark sweep GC freed 32675(1592KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.582ms total 92.197ms
,09-13 09:18:42.202  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 09:18:42.202  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:42.205  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 09:18:42.214  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 09:18:42.216  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 09:18:42.217  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:18:42.218  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.220  6667  6728 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 09:18:42.221  6667  6728 I io.jxcore.node.ConnectionHelper: start: OK
09-13 09:18:42.222  6667  6728 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-13 09:18:42.222  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 09:18:42.222  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 09:18:42.224  6667  6728 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 09:18:42.224  6667  6728 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 09:18:42.224  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:42.224  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 09:18:42.224  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 09:18:42.224  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.224  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:18:42.227  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 09:18:42.230  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.231  6667  6728 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 09:18:42.231  6667  6728 I io.jxcore.node.ConnectionHelper: start: OK
09-13 09:18:42.231  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.231  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.231  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.231  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.231  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.231  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.231  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.231  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.232  6667  6728 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 09:18:42.233  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:42.235  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:42.236  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.236  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:42.237  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.238  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:42.240  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:42.240  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 09:18:42.240  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 09:18:42.240  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.240  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:18:42.243  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:18:42.243  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.244  6667  6728 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 09:18:42.244  6667  6728 I io.jxcore.node.ConnectionHelper: start: OK
09-13 09:18:42.244  6667  6728 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 09:18:42.244  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 09:18:42.244  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 09:18:42.246  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.246  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.246  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.246  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.246  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.246  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.246  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.246  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.247  6667  6728 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 09:18:42.247  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.247  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.247  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.247  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.247  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.247  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.24,7  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.247  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.247  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.248  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 09:18:42.248  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.248  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.248  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.248  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
,09-13 09:18:42.248  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.248  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.248  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.248  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.248  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.252  6667  6728 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 09:18:42.252  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.252  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.253  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.253  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
,09-13 09:18:42.253  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.253  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.253  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.253  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.253  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.255  6667  6728 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 09:18:42.256  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:18:42.256  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.256  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:18:42.256  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.256  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.256  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
,09-13 09:18:42.256  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.256  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.256  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:18:42.258  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 09:18:42.265  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.265  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 09:18:42.265  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.266  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 09:18:42.266  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.266  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-13 09:18:42.266  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.266  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 09:18:42.266  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 09:18:42.267  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.267  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 09:18:42.267  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:18:42.267  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.267  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.267  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
,09-13 09:18:42.267  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.268  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.268  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 09:18:42.268  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.268  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.269  6667  6728 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 09:18:42.270  6667  6728 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 09:18:42.271  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 09:18:42.276  6667  6728 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 09:18:42.277  6667  6728 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 09:18:42.277  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 09:18:42.278  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 09:18:42.278  6667  6728 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 09:18:42.278  6667  6728 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 09:18:42.278  6667  6728 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 09:18:42.278  6667  6728 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 09:18:42.278  6667  6728 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 09:18:42.279  6667  6728 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 09:18:42.279  6667  6728 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 09:18:42.279  6667  6728 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 09:18:42.279  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 09:18:42.280  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 09:18:42.281  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 09:18:42.281  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 09:18:42.282  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 09:18:42.282  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 09:18:42.282  6667  6728 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 09:18:42.282  6667  6728 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 09:18:42.282  6667  6728 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 09:18:42.283  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.283  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.283  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.283  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 09:18:42.284  6667  6751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 864)
09-13 09:18:42.288  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.289  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.289  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.289  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.289  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.289  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.290  6667  6728 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 09:18:42.290  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.290  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.290  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.290  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.290  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.290  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.290  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.290  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.290  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.291  6667  6728 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 09:18:42.291  6667  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 864
09-13 09:18:42.292  6667  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 864)
09-13 09:18:42.292  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.292  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.292  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.292  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.292  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.292  6667  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 864)
09-13 09:18:42.292  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.292  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.292  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.292  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.293  6667  6728 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 09:18:42.293  6667  6728 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 09:18:42.293  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 09:18:42.293  6667  6728 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 09:18:42.293  6667  6728 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 09:18:42.293  6667  6728 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 09:18:42.293  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 09:18:42.294  6667  6728 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 09:18:42.294  6667  6728 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 09:18:42.294  6667  6728 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 09:18:42.294  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 09:18:42.294  6667  6728 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 09:18:42.294  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.294  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.294  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.294  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.294  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.294  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.294  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.294  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.294  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.295  6667  6728 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 09:18:42.299  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:42.303  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:42.309  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.309  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:42.310  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:42.310  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 09:18:42.310  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 09:18:42.310  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.310  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:18:42.312  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.314  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.315  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:18:42.315  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.317  6667  6728 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 09:18:42.317  6667  6728 I io.jxcore.node.ConnectionHelper: start: OK
09-13 09:18:42.317  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.317  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.317  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:42.317  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.317  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.317  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.317  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.317  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.320  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.320  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.320  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.320  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.320  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.320  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.320  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.320  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.320  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.322  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 09:18:42.322  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.323  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 09:18:42.324  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 09:18:42.324  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 09:18:42.324  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 09:18:42.324  6667  6667 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:18:42.324  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 09:18:42.325  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 09:18:42.325  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 09:18:42.325  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 09:18:42.325  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 09:18:42.326  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.326  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:18:42.328  6667  6667 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:18:42.328  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.328  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.328  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 09:18:42.328  6667  6728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 09:18:42.328  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 09:18:42.329  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 09:18:42.330  6667  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 09:18:42.330  6667  6756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 09:18:42.332  6667  6728 D BluetoothLeScanner: could not find callback wrapper
09-13 09:18:42.332  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 09:18:42.332  6667  6728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 09:18:42.332  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.332  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.339  6667  6728 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:18:42.339  6667  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:18:42.339  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.339  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.339  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.339  6667  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 09:18:42.339  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.339  6667  6667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 09:18:42.339  6667  6667 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 09:18:42.340  6667  6728 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 09:18:42.341  6667  6728 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 09:18:42.341  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 09:18:42.341  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.341  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.341  6667  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 09:18:42.341  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.341  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.341  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.342  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.342  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.342  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.342  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.342  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.342  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.343  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:42.344  1035  1614 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:42.345  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:42.345  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.345  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.345  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.345  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.345  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.345  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.345  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.346  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.346  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.346  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:42.346  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.346  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.346  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0aa6b not in the list
09-13 09:18:42.346  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:42.346  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2759c8 not in the list
09-13 09:18:42.346  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:42.347  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:42.347  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:42.348  6667  6728 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 09:18:42.348  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 09:18:42.348  6667  6728 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 09:18:42.349  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 09:18:42.349  6667  6728 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 09:18:42.349  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 09:18:42.350  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 09:18:42.350  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 09:18:42.351  6667  6728 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 09:18:42.351  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 09:18:42.351  6667  6728 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 09:18:42.351  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 09:18:42.351  6667  6728 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 09:18:42.351  6667  6728 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 09:18:42.352  6667  6728 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 09:18:42.352  6667  6728 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 09:18:42.353  6667  6728 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 09:18:42.353  6667  6728 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 09:18:42.353  6667  6728 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 09:18:42.353  6667  6728 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 09:18:42.354  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 09:18:42.354  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c0f35e added. We now have 4 listener(s)
09-13 09:18:42.354  1035  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:42.356  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 09:18:42.356  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:18:42.356  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:18:42.357  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:18:42.357  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3602733f added. We now have 4 listener(s)
09-13 09:18:42.357  6667  6728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:18:42.357  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:18:42.360  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:42.365  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:18:42.367  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-13 09:18:42.367  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 09:18:42.379  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.380  6667  6728 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 09:18:42.381  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:42.382  1035  1614 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:42.383  1035  1614 D WifiService: setWifiEnabled: true pid=6667, uid=10118
09-13 09:18:42.383  1035  1614 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:42.397  1035  1890 D WifiServiceImplEx: setWifiEnabled: false pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:42.398  1035  1890 D WifiService: setWifiEnabled: false pid=6667, uid=10118
09-13 09:18:42.398  1035  1890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 09:18:42.400  6667  6751 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,09-13 09:18:42.403  6667  6751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 864)
09-13 09:18:42.409  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:42.409  1035  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:42.409  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:42.409  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:42.409  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 09:18:42.409  1035  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:42.410  1035  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:42.410  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
,09-13 09:18:42.410  1035  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 09:18:42.410  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 09:18:42.410  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 09:18:42.411  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 09:18:42.411  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 09:18:42.416  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 09:18:42.416  1035  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.416  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.417  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 09:18:42.417  2643  2643 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 09:18:42.417  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 09:18:42.417  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 09:18:42.417  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:42.418  1035  2801 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.423   307   893 D CommandListener: Clearing all IP addresses on wlan0
,09-13 09:18:42.460  1035  1943 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-13 09:18:42.462  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.462  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.462  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 09:18:42.462  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.462  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 09:18:42.466  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 09:18:42.466  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-13 09:18:42.470  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 09:18:42.471  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:42.472  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:42.473  1035  1035 D WifiHS20: hidePasspointNotification off =false
,09-13 09:18:42.476  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:42.481  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.481  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.481  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:42.492  1035  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.492  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.492  1035  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cb9d8ff
09-13 09:18:42.493  1035  1522 D LGWifiP2pService: P2pDisablingState
,09-13 09:18:42.493  1035  1522 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.494  1035  1522 D LGWifiP2pService: p2p socket connection lost
09-13 09:18:42.494  1035  1522 D LGWifiP2pService: P2pDisabledState
09-13 09:18:42.497  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 09:18:42.500  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.500  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.500  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:42.501  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 09:18:42.501  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.501  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 09:18:42.501  1035  1542 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.502  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:42.503  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 09:18:42.504  1927  1927 D WfdsService: WifiP2pState is changed : false
09-13 09:18:42.504  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:42.504  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:42.505  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:42.505  1035  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 09:18:42.505  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 09:18:42.506  1035  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.506  1035  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.506  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 09:18:42.506  2643  2643 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 09:18:42.508  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 09:18:42.509  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
,09-13 09:18:42.509  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:42.508  1927  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 09:18:42.510  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-13 09:18:42.510  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-13 09:18:42.511  1927  2296 D WfdsService: STATE : WfdsDisabledState - enter
09-13 09:18:42.511  1927  2729 D CtrlSupplicant: Received on exit socket, terminate
09-13 09:18:42.511  1927  2729 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 09:18:42.511  1927  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 09:18:42.511  1927  2729 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 09:18:42.511  1927  2729 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 09:18:42.511  1927  2296 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 09:18:42.518  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:42.518  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:42.519  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:42.531   307   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 09:18:42.531  1035  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 09:18:42.531   307  6766 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 09:18:42.531  1035  1530 D DSQN    : disableDataServiceNotify
09-13 09:18:42.531  1035  1530 D DSQN    : stop dsqn bin
09-13 09:18:42.531  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 09:18:42.531  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 09:18:42.538  1035  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 09:18:42.538  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:42.538  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:42.538  1035  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:42.539  1035  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 09:18:42.539  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 09:18:42.539  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.539  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.539  1035  2010 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 09:18:42.539  1035  2797 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 09:18:42.539  1035  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 09:18:42.539  1035  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 09:18:42.540  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 09:18:42.541  1035  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 09:18:42.541  1035  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:42.542  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 09:18:42.542  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 09:18:42.542  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.543  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.543  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:42.543  1035  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 09:18:42.543  1035  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:42.544  1035  1523 D WifiNative-p2p0: TERMINATE: returned true
09-13 09:18:42.544  1035  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:4,2.544  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:42.544  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:42.544  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:42.544  1035  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:42.544  1035  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:42.544  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-13 09:18:42.544  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 09:18:42.544  1035  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 09:18:42.544  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 09:18:42.544  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 09:18:42.544  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 09:18:42.545  1035  1530 D NetworkManagementService: Removing idletimer
09-13 09:18:42.545  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 09:18:42.545  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:42.546  1035  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.546  1035  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 09:18:42.547  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 09:18:42.547  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:42.547  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 09:18:42.548  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:42.548  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 09:18:42.550  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 09:18:42.550  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 09:18:42.550  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 09:18:42.550  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 09:18:42.550  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:42.550  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:42.553  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:42.554  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:42.556  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:42.556  6667  6667 V io.jxcore.node.Conn,ectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.556  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.556  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:42.556  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.556  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:42.556  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:42.556  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:18:42.558  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:42.563  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:42.564  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:42.566  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:42.568  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:18:42.591  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 09:18:42.592  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:42.592  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:42.605  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 09:18:42.606  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:42.606  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:42.607  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:42.623  1035  2801 D DhcpStateMachine: StoppedState
09-13 09:18:42.623  1035  2801 D DhcpStateMachine: StoppedState{ when=-115ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:42.624  1035  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 09:18:42.624  1035  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-13 09:18:42.631  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 09:18:42.633  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 09:18:42.633  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:42.639  2643  2643 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 09:18:42.639  2643  2643 I wpa_supplicant: monitor socket send errors count : 1
09-13 09:18:42.639  2643  2643 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
,09-13 09:18:42.640  1035  2725 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 09:18:42.640  1035  2725 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 09:18:42.673  2643  2643 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 09:18:42.673  1035  2725 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 09:18:42.673  1035  2725 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 09:18:42.674  1035  2725 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 09:18:42.674  1035  2725 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,09-13 09:18:42.675  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 09:18:42.675  1035  2725 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:42.675  1035  2725 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:42.675  2643  2643 W wpa_supplicant: USIM:  scard_deinit function
09-13 09:18:42.676  1035  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189368
09-13 09:18:42.677  1035  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189369
09-13 09:18:42.678  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=189369  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 09:18:42.678  1035  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=189369  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 09:18:42.692  1035  1866 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6787 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 09:18:42.693  1035  1866 I ActivityManager: Killing 6106:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-13 09:18:42.739  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 09:18:42.741  1035  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:42.741  2643  2643 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 09:18:42.741  1035  1560 W libprocessgroup: failed to open /acct/uid_10014/pid_6106/cgroup.procs: No such file or directory
09-13 09:18:42.741  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:42.742  1035  2725 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 09:18:42.742  1035  2725 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 09:18:42.742  1035  2725 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 09:18:42.743  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-13 09:18:42.774  6787  6787 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 09:18:42.775  6787  6787 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 09:18:42.775  6787  6787 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 09:18:42.776  6787  6787 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 09:18:42.778  6787  6787 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 09:18:42.779  6787  6787 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 09:18:42.840  6667  6667 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 09:18:42.845  1035  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 09:18:42.846  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-13 09:18:42.846  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:42.846  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:42.846  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:42.846  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 09:18:42.846  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-13 09:18:42.846  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-13 09:18:42.849  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 09:18:42.849  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 09:18:42.849  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:42.851  1035  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 09:18:42.851  1035  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 09:18:42.852  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.861  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:42.863  2437  2437 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:42.869  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.871  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:42.910  6667  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:42.916  1035  1908 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:42.917  1035  1908 D WifiService: setWifiEnabled: true pid=6667, uid=10118
09-13 09:18:42.917  1035  1908 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:42.938  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:42.939  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:42.939  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-13 09:18:42.998  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:43.043  6787  6787 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 09:18:43.043  6787  6787 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 09:18:43.049  1035  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 09:18:43.049  1035  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 09:18:43.057  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 09:18:43.057  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 09:18:43.057  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 09:18:43.057  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 09:18:43.057  1035  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 09:18:43.057  1035  1523 E WifiHW  : unknown target_country: EU , set to default
09-13 09:18:43.057  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 09:18:43.057  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 09:18:43.057  1035  1523 I WifiUtil: gEnableBmps=1
,09-13 09:18:43.062  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:43.127  1035  1890 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6810 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-13 09:18:43.129  1035  1890 I ActivityManager: Killing 6223:com.android.defcontainer/u0a4 (adj 15): empty #17
09-13 09:18:43.191  1035  1051 W libprocessgroup: failed to open /acct/uid_10004/pid_6223/cgroup.procs: No such file or directory
,09-13 09:18:43.229  6810  6810 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 09:18:43.257  6810  6810 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 09:18:43.293  6810  6810 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 09:18:43.294  6810  6810 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,09-13 09:18:43.294  6810  6810 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 09:18:43.294  6810  6810 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 09:18:43.295  6810  6810 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 09:18:43.297  6810  6810 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 09:18:43.303  6810  6810 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 09:18:43.310  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 09:18:43.312  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 09:18:43.333  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 09:18:43.337  6810  6810 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 09:18:43.338  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:43.342  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 09:18:43.342  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 09:18:43.342  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:43.343  6810  6810 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-13 09:18:43.346  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:43.354  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:43.361  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 09:18:43.361  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:43.363  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:43.365  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:43.368  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 09:18:43.368  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 09:18:43.368  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:43.372  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:43.379  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:43.390  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 09:18:43.391  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 09:18:43.394  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:43.456  1035  1560 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6830 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 09:18:43.460  1035  1908 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:43.461  1035  1908 D WifiService: setWifiEnabled: true pid=6667, uid=10118
09-13 09:18:43.461  1035  1908 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:43.463  1035  1529 D WifiController: Mismatch in the state 1
,09-13 09:18:43.533  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 09:18:43.537  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 09:18:43.544  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:43.565  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-13 09:18:43.565  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 09:18:43.565  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 09:18:43.565  6787  6787 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 09:18:43.568  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 09:18:43.576  6830  6849 W FormManager: Network not available. Please check & try again.
09-13 09:18:43.577  6787  6787 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 09:18:43.577  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 09:18:43.577  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 09:18:43.577  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 09:18:43.578  6787  6787 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 09:18:43.578  6787  6787 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 09:18:43.586  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-13 09:18:43.586  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:43.591  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:43.598  6830  6850 V FormManager: Network unavailable.
09-13 09:18:43.600  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 09:18:43.610  4277  6858 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:43.610  6830  6850 V FormManager: Network unavailable.
09-13 09:18:43.618  6767  6767 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 09:18:43.618  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-13 09:18:43.618  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:43.621  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 09:18:43.621  4277  6859 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 09:18:43.622  4277  6859 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:43.629  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:43.638  6830  6861 W FormManager: Network not available. Please check & try again.
,09-13 09:18:43.642  6830  6862 V FormManager: Network unavailable.
09-13 09:18:43.646  6830  6862 V FormManager: Network unavailable.
09-13 09:18:43.646  6810  6810 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 09:18:43.647  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 09:18:43.648  6810  6810 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 09:18:43.652  1035  1943 I ActivityManager: Killing 6409:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-13 09:18:43.688  6810  6810 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 09:18:43.689  6810  6810 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 09:18:43.696  6810  6810 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 09:18:43.698  6810  6810 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 09:18:43.698  6810  6810 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 09:18:43.698  6810  6810 V SoundPool: doLoad: loading sample sampleID=1
09-13 09:18:43.698  6810  6869 V SoundPool: Start decode
09-13 09:18:43.698  6810  6869 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-13 09:18:43.699  6810  6810 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 09:18:43.699   312  1372 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 09:18:43.699   312  1372 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 09:18:43.699   312  1372 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 09:18:43.699   312  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 09:18:43.699   312  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 09:18:43.699   312  1372 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 09:18:43.699   312  1372 V MediaPlayerService: player type = 3
09-13 09:18:43.699   312  1372 V AwesomePlayer: AwesomePlayer create()
09-13 09:18:43.700   312  1372 V AwesomePlayer: reset_l() 
09-13 09:18:43.700   312  1372 V AwesomePlayer: cancelPlayerEvents
09-13 09:18:43.700   312  1372 V AwesomePlayer: setAudioSink() 
09-13 09:18:43.700   312  1372 V AwesomePlayer: reset_l() 
09-13 09:18:43.700   312  1372 V AudioCache: notify(0xb1432440, 8, 0, 0)
09-13 09:18:43.700   312  1372 V AudioCache: ignored
09-13 09:18:43.700   312  1372 V AwesomePlayer: cancelPlayerEvents
09-13 09:18:43.701   312  1372 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 09:18:43.701   312  1372 V AwesomePlayer: setDataSource_l dataSource
09-13 09:18:43.701   312  1372 V LGParserOSAL: SniffLGParser start
09-13 09:18:43.701   312  1372 V LGParserOSAL: MainType:5, SubType=0
09-13 09:18:43.701   312  1372 V LGParserOSAL: #### check Mime : application/ogg
09-13 09:18:43.701   312  1372 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 09:18:43.701   312  1372 E MediaExtractor: Use LGExtractor :application/ogg 
,09-13 09:18:43.751   312  1372 V LGParserOSAL: supported mime: application/ogg
09-13 09:18:43.751   312  1372 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 09:18:43.751   312  1372 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 09:18:43.751   312  1372 V AwesomePlayer: mBitrate = -1 bits/sec
,09-13 09:18:43.751   312  1372 V AwesomePlayer: AudioTrack Setting
09-13 09:18:43.751   312  1372 V AwesomePlayer: AudioTrack Setting channelCount = 2
,09-13 09:18:43.751   312  1372 V AwesomePlayer: setAudioSource() 
,09-13 09:18:43.751   312  1372 V MediaPlayerService: prepare
09-13 09:18:43.751   312  1372 V AwesomePlayer: prepareAsync_l() 
09-13 09:18:43.752   312  1372 V MediaPlayerService: wait for prepare
,09-13 09:18:43.752   312  6872 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 09:18:43.752   312  6872 V AwesomePlayer: initAudioDecoder() 
09-13 09:18:43.752   312  6872 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 09:18:43.752   312  6872 V AudioSystem: isOffloadSupported()
09-13 09:18:43.752   312  6872 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 09:18:43.752   312  6872 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 09:18:43.752   312  6872 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 09:18:43.752   312  6872 V AwesomePlayer: getUseOffload() = 0 
09-13 09:18:43.753   312  6872 V OMXCodec: OMXCodec::Create
09-13 09:18:43.753   312  6872 V OMXCodec: findMatchingCodecs()
09-13 09:18:43.753  1035  1866 W libprocessgroup: failed to open /acct/uid_10008/pid_6409/cgroup.procs: No such file or directory
09-13 09:18:43.753   312  6872 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 09:18:43.753   312  6872 V OMXCodec: matchingCodecs.size()=1
09-13 09:18:43.753   312  6872 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 09:18:43.758   312  6872 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 09:18:43.758   312  6872 V LGCodecAdapter: LG Codec Adapter start
09-13 09:18:43.762  6563  6563 D UEI.SmartControl: QS Service created
09-13 09:18:43.764  6810  6810 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 09:18:43.764   312  6872 V OMXCodec: OMXCodec Createtor
09-13 09:18:43.765   312  6872 V OMXCodec: setComponentRole
09-13 09:18:43.765   312  6872 V OMXCodec: configureCodec protected=0
09-13 09:18:43.765   312  6872 V LGCodecAdapter: called getLGCodecSpecificData
09-13 09:18:43.765   312  6872 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 09:18:43.765   312  6872 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 09:18:43.765   312  6872 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 09:18:43.765   312  6872 V LGCodecOSAL: Not support LGCodec
09-13 09:18:43.765   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 09:18:43.765   312  6872 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 09:18:43.765   312  6872 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 09:18:43.765   312  6872 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 09:18:43.766   312  6872 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 09:18:43.766   312  6872 V AudioSystem: isOffloadSupported()
09-13 09:18:43.766   312  6872 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 09:18:43.766   312  6872 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 09:18:43.766   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 09:18:43.766   312  6872 V OMXCodec: init()
09-13 09:18:43.766   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 09:18:43.766   312  6872 V OMXCodec: allocateBuffers
09-13 09:18:43.766   312  6872 V OMXCodec: allocateBuffersOnPort portIndex=0
,09-13 09:18:43.766   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 09:18:43.767   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-13 09:18:43.767   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-13 09:18:43.767   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-13 09:18:43.767   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-13 09:18:43.767   312  6872 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 09:18:43.767   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 09:18:43.768   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-13 09:18:43.768   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-13 09:18:43.768   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
09-13 09:18:43.768   312  6872 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c95b0 on output port
09-13 09:18:43.768   312  6872 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 09:18:43.770   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 09:18:43.770   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 09:18:43.770   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 09:18:43.770   312  6872 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 09:18:43.770   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 09:18:43.770   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 09:18:43.770   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 09:18:43.770   312  6872 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 09:18:43.770   312  6872 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 09:18:43.770   312  6872 V AudioCache: notify(0xb1432440, 5, 0, 0)
09-13 09:18:43.770   312  6872 V AudioCache: ignored
09-13 09:18:43.770   312  6872 V AudioCache: notify(0xb1432440, 1, 0, 0)
09-13 09:18:43.770   312  6872 V AudioCache: prepared
09-13 09:18:43.770   312  1372 V AudioCache: wait - success
09-13 09:18:43.770   312  1372 V MediaPlayerService: start
09-13 09:18:43.770   312  1372 V AwesomePlayer: play_l() 
09-13 09:18:43.770   312  1372 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 09:18:43.770   312  1372 V AwesomePlayer: createAudioPlayer_l
09-13 09:18:43.770   312  1372 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 09:18:43.770   312  1372 V AwesomePlayer: startAudioPlayer_l() 
09-13 09:18:43.770   312  1372 D AudioPlayer: start of Playback, useOffload 0
09-13 09:18:43.770   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 09:18:43.770   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 09:18:43.773   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 09:18:43.773   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 09:18:43.773   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 09:18:43.773   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 09:18:43.773   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 09:18:43.773   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, fre,eing buffer 3041885568
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044840880
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 09:18:43.774   312  6874 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-13 09:18:43.774   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c9830 on output port
09-13 09:18:43.775   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 09:18:43.775   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 09:18:43.779   312  1372 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 09:18:43.779   312  1372 V AudioCache: notify(0xb1432440, 6, 0, 0)
09-13 09:18:43.779   312  1372 V AudioCache: ignored
09-13 09:18:43.780   312  1372 V MediaPlayerService: wait for playback complete
09-13 09:18:43.780   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.780   312  6875 V AudioCache: memcpy(0xaf004000, 0xb1509000, 4096)
09-13 09:18:43.781   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.781   312  6875 V AudioCache: memcpy(0xaf005000, 0xb1509000, 4096)
09-13 09:18:43.785   307   893 D SoftapController: Softap fwReload - Ok
09-13 09:18:43.786   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.786   312  6875 V AudioCache: memcpy(0xaf006000, 0xb1509000, 4096)
09-13 09:18:43.786   312  6875 V AudioCache: write(0xb1509000, 4096)
,09-13 09:18:43.786   312  6875 V AudioCache: memcpy(0xaf007000, 0xb1509000, 4096)
09-13 09:18:43.787   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.787   312  6875 V AudioCache: memcpy(0xaf008000, 0xb1509000, 4096)
09-13 09:18:43.788   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.788   312  6875 V AudioCache: memcpy(0xaf009000, 0xb1509000, 4096)
,09-13 09:18:43.789   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.789   312  6875 V AudioCache: memcpy(0xaf00a000, 0xb1509000, 4096)
09-13 09:18:43.789  1035  1523 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (721ms)
09-13 09:18:43.790   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.790   312  6875 V AudioCache: memcpy(0xaf00b000, 0xb1509000, 4096)
,09-13 09:18:43.791   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.791   312  6875 V AudioCache: memcpy(0xaf00c000, 0xb1509000, 4096)
09-13 09:18:43.792   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.792   312  6875 V AudioCache: memcpy(0xaf00d000, 0xb1509000, 4096)
09-13 09:18:43.792   307   893 D CommandListener: Setting iface cfg
09-13 09:18:43.792   307   893 D CommandListener: Trying to bring down wlan0
09-13 09:18:43.793   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.793   312  6875 V AudioCache: memcpy(0xaf00e000, 0xb1509000, 4096)
09-13 09:18:43.794   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.794   312  6875 V AudioCache: memcpy(0xaf00f000, 0xb1509000, 4096)
09-13 09:18:43.795   307   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 09:18:43.795   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.795   312  6875 V AudioCache: memcpy(0xaf010000, 0xb1509000, 4096)
09-13 09:18:43.796   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.796   312  6875 V AudioCache: memcpy(0xaf011000, 0xb1509000, 4096)
09-13 09:18:43.798  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 09:18:43.798  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 09:18:43.799   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.799   312  6875 V AudioCache: memcpy(0xaf012000, 0xb1509000, 4096)
09-13 09:18:43.799  6810  6810 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 09:18:43.799  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 09:18:43.800   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.800   312  6875 V AudioCache: memcpy(0xaf013000, 0xb1509000, 4096)
09-13 09:18:43.800  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 09:18:43.801   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.801   312  6875 V AudioCache: memcpy(0xaf014000, 0xb1509000, 4096)
09-13 09:18:43.801  6563  6563 I UEI.SmartControl: Service initServices...
09-13 09:18:43.801  6563  6563 D UEI.SmartControl: QS start get config
09-13 09:18:43.802   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.802   312  6875 V AudioCache: memcpy(0xaf015000, 0xb1509000, 4096)
,09-13 09:18:43.807   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.807   312  6875 V AudioCache: memcpy(0xaf016000, 0xb1509000, 4096)
09-13 09:18:43.807  1035  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 09:18:43.808   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.808   312  6875 V AudioCache: memcpy(0xaf017000, 0xb1509000, 4096)
09-13 09:18:43.809   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.809   312  6875 V AudioCache: memcpy(0xaf018000, 0xb1509000, 4096)
09-13 09:18:43.810   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.810   312  6875 V AudioCache: memcpy(0xaf019000, 0xb1509000, 4096)
09-13 09:18:43.811   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.811   312  6875 V AudioCache: memcpy(0xaf01a000, 0xb1509000, 4096)
09-13 09:18:43.811   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.811   312  6875 V AudioCache: memcpy(0xaf01b000, 0xb1509000, 4096)
09-13 09:18:43.812   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.812   312  6875 V AudioCache: memcpy(0xaf01c000, 0xb1509000, 4096)
09-13 09:18:43.813  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:43.813  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:43.813  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:43.813   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.813   312  6875 V AudioCache: memcpy(0xaf01d000, 0xb1509000, 4096)
09-13 09:18:43.799  6877  6877 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:43.799  6877  6877 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:43.815  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:43.816   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.816   312  6875 V AudioCache: memcpy(0xaf01e000, 0xb1509000, 4096)
09-13 09:18:43.817   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.817   312  6875 V AudioCache: memcpy(0xaf01f000, 0xb1509000, 4096)
09-13 09:18:43.817   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.817   312  6875 V AudioCache: memcpy(0xaf020000, 0xb1509000, 4096)
09-13 09:18:43.818  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 09:18:43.818   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.818   312  6875 V AudioCache: memcpy(0xaf021000, 0xb1509000, 4096)
09-13 09:18:43.823  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:43.823  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 09:18:43.824  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:43.826  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:43.827  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:43.829   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.829   312  6875 V AudioCache: memcpy(0xaf022000, 0xb1509000, 4096)
09-13 09:18:43.830   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.830   312  6875 V AudioCache: memcpy(0xaf023000, 0xb1509000, 4096)
,09-13 09:18:43.831  1035  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 09:18:43.831  1035  1523 D WifiMonitor: connecting to supplicant
09-13 09:18:43.832   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.832   312  6875 V AudioCache: memcpy(0xaf024000, 0xb1509000, 4096)
09-13 09:18:43.839   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.839   312  6875 V AudioCache: memcpy(0xaf025000, 0xb1509000, 4096)
09-13 09:18:43.840   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.840   312  6875 V AudioCache: memcpy(0xaf026000, 0xb1509000, 4096)
09-13 09:18:43.841   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.841   312  6875 V AudioCache: memcpy(0xaf027000, 0xb1509000, 4096)
,09-13 09:18:43.842   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.842   312  6875 V AudioCache: memcpy(0xaf028000, 0xb1509000, 4096)
09-13 09:18:43.843  6877  6877 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 09:18:43.843  6810  6810 V LGMDMManager: Create singleton instance
09-13 09:18:43.844   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.844   312  6875 V AudioCache: memcpy(0xaf029000, 0xb1509000, 4096)
09-13 09:18:43.847   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.847   312  6875 V AudioCache: memcpy(0xaf02a000, 0xb1509000, 4096)
09-13 09:18:43.848   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.848   312  6875 V AudioCache: memcpy(0xaf02b000, 0xb1509000, 4096)
09-13 09:18:43.849   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.849   312  6875 V AudioCache: memcpy(0xaf02c000, 0xb1509000, 4096)
09-13 09:18:43.850   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.850   312  6875 V AudioCache: memcpy(0xaf02d000, 0xb1509000, 4096)
09-13 09:18:43.851   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.851   312  6875 V AudioCache: memcpy(0xaf02e000, 0xb1509000, 4096)
09-13 09:18:43.851   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.851   312  6875 V AudioCache: memcpy(0xaf02f000, 0xb1509000, 4096)
09-13 09:18:43.852   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.852   312  6875 V AudioCache: memcpy(0xaf030000, 0xb1509000, 4096)
,09-13 09:18:43.854   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.854   312  6875 V AudioCache: memcpy(0xaf031000, 0xb1509000, 4096)
,09-13 09:18:43.855   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.855   312  6875 V AudioCache: memcpy(0xaf032000, 0xb1509000, 4096)
09-13 09:18:43.856   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.856   312  6875 V AudioCache: memcpy(0xaf033000, 0xb1509000, 4096)
09-13 09:18:43.856   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.856   312  6875 V AudioCache: memcpy(0xaf034000, 0xb1509000, 4096)
09-13 09:18:43.857   312  6875 V AudioCache: write(0xb1509000, 4096)
09-13 09:18:43.857   312  6875 V AudioCache: memcpy(0xaf035000, 0xb1509000, 4096)
09-13 09:18:43.857   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 09:18:43.857   312  6875 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 09:18:43.857   312  6875 V AwesomePlayer: postAudioEOS() 
09-13 09:18:43.857   312  6875 V AudioCache: write(0xb1509000, 280)
09-13 09:18:43.857   312  6875 V AudioCache: memcpy(0xaf036000, 0xb1509000, 280)
09-13 09:18:43.859   312  6872 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 09:18:43.859   312  6872 V AwesomePlayer: onStreamDone
09-13 09:18:43.859   312  6872 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 09:18:43.859   312  6872 V AudioCache: notify(0xb1432440, 2, 0, 0)
09-13 09:18:43.859   312  6872 V AudioCache: playback complete
09-13 09:18:43.859   312  6872 V AwesomePlayer: pause_l() 
09-13 09:18:43.859   312  6872 V AudioCache: notify(0xb1432440, 7, 0, 0)
09-13 09:18:43.859   312  6872 V AudioCache: ignored
09-13 09:18:43.859   312  6872 V AwesomePlayer: cancelPlayerEvents
09-13 09:18:43.859   312  1372 V AudioCache: wait - success
09-13 09:18:43.859   312  1372 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 09:18:43.859   312  6872 D AudioPlayer: Pause Playback at 1068125
09-13 09:18:43.868   312  1372 V AwesomePlayer: reset_l() 
09-13 09:18:43.868   312  1372 V AudioCache: notify(0xb1432440, 8, 0, 0)
09-13 09:18:43.868   312  1372 V AudioCache: ignored
09-13 09:18:43.868   312  1372 V AwesomePlayer: cancelPlayerEvents
09-13 09:18:43.868   312  1372 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 09:18:43.868   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 09:18:43.868   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 09:18:43.868   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 09:18:43.869   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c9830 on port 1
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 09:18:43.871   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 09:18:43.871   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 09:18:43.871   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 09:18:43.872  6877  6877 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 09:18:43.872  6877  6877 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 09:18:43.872   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 09:18:43.872   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 09:18:43.872   312  6874 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 09:18:43.872   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 09:18:43.872   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 09:18:43.872   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 09:18:43.873   312  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 09:18:43.873   312  1372 D AudioPlayer: AudioPlayer releasing audio source
09-13 09:18:43.873   312  1372 D AudioPlayer: AudioPlayer done releasing audio source
09-13 09:18:43.873   312  1372 V AwesomePlayer: reset_l() 
09-13 09:18:43.873   312  1372 V AwesomePlayer: cancelPlayerEvents
09-13 09:18:43.873   312  1372 V AwesomePlayer: ~AwesomePlayer call
09-13 09:18:43.874   312  1372 V AwesomePlayer: reset_l() 
09-13 09:18:43.874   312  1372 V AwesomePlayer: cancelPlayerEvents
09-13 09:18:43.874  6810  6869 V SoundPool: close(31)
09-13 09:18:43.874  6810  6869 V SoundPool: pointer = 0x9fe9f000, size = 205080, sampleRate = 48000, numChannels = 2
09-13 09:18:43.914  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-13 09:18:43.915  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 09:18:43.916  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3122
09-13 09:18:43.918  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-13 09:18:43.918  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 09:18:43.918  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 09:18:43.918  6787  6787 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 09:18:43.918  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 09:18:43.919  6787  6787 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 09:18:43.919  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 09:18:43.919  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 09:18:43.919  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 09:18:43.919  6787  6787 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 09:18:43.919  6787  6787 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 09:18:43.923  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:43.925  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 09:18:43.926  6830  6879 W FormManager: Network not available. Please check & try again.
,09-13 09:18:43.929  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 09:18:43.932  6830  6880 V FormManager: Network unavailable.
09-13 09:18:43.938  6830  6880 V FormManager: Network unavailable.
,09-13 09:18:43.951  6877  6877 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 09:18:43.964  1035  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:43.965  1035  1050 D WifiService: setWifiEnabled: true pid=6667, uid=10118
,09-13 09:18:43.965  1035  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:44.057  6877  6877 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 09:18:44.073  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-13 09:18:44.074  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 09:18:44.074  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 09:18:44.074  1035  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 09:18:44.075  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
,09-13 09:18:44.075  6877  6877 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 09:18:44.076  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.076  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.076  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 09:18:44.076  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 09:18:44.076  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.076  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 09:18:44.077  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 09:18:44.077  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.077  1035  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 09:18:44.077  1035  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 09:18:44.078  1035  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,09-13 09:18:44.079  1035  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 09:18:44.079  1035  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 09:18:44.079  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:44.079  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:44.079  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:44.079  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.079  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.079  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.079  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.080  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:44.080  1035  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 09:18:44.080  1035  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-13 09:18:44.080  1035  1523 D WifiConfigStore: Loading config and enabling all networks 
09-13 09:18:44.080  1035  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 09:18:44.081  1035  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 09:18:44.083  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 09:18:44.083  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.086  1035  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 09:18:44.086  1035  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 09:18:44.087  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.089  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:44.091  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.093  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.093  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.093  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.093  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.093  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:44.093  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.093  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.093  6667  6667 V io.jxcore.no,de.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:44.095  1035  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 09:18:44.095  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.095  1035  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 09:18:44.096  1035  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-13 09:18:44.096  1035  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 09:18:44.097  1035  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 09:18:44.097  1035  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 09:18:44.097  1035  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 09:18:44.097  1035  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 09:18:44.097  1035  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 09:18:44.097  1035  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.098  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:44.098  1035  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 09:18:44.098  1035  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 09:18:44.098  1035  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 09:18:44.098  1035  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 09:18:44.099  1035  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 09:18:44.099  1035  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 09:18:44.099  1035  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 09:18:44.101  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-13 09:18:44.101  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 09:18:44.101  1927  2296 D WfdsService: Set the WFDS Monitor: true
09-13 09:18:44.101  1927  2296 D WfdsMonitor: WfdsMonitorThread create
,09-13 09:18:44.101  1927  2296 D WfdsMonitor: WFDS Monitor is created and started
09-13 09:18:44.101  1927  2296 D WfdsService: WiFi: Supplicant connection re-established
09-13 09:18:44.101  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.102  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 09:18:44.102  1035  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 09:18:44.102  1927  6882 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 09:18:44.103  1927  6882 E CtrlSupplicant: Succeed to open control connection
09-13 09:18:44.103  1035  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 09:18:44.103  1035  1523 D WifiNative-HAL: Setting external_sim to 1
09-13 09:18:44.103  1035  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 09:18:44.103  1927  6882 E CtrlSupplicant: Succeed to open monitor connection
,09-13 09:18:44.103  1927  6882 D WfdsMonitor: Supplicant connection established
09-13 09:18:44.103  1927  2296 D WfdsService: Connected to the supplicant for wfds
09-13 09:18:44.104  1035  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 09:18:44.104  1035  1523 I WifiNative-HAL: startHal
09-13 09:18:44.104  1035  1523 D wifi    : setting scan oui 0x953dc700
09-13 09:18:44.104  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 09:18:44.104  1035  1523 I WifiNative-HAL: startHal
09-13 09:18:44.104  1035  1523 D wifi    : setting scan oui 0x953dc700
09-13 09:18:44.105  1035  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.105  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:18:44.105  1035  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 09:18:44.105  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 09:18:44.105  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 09:18:44.106  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 09:18:44.106  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 09:18:44.106  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.106  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 09:18:44.107  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 09:18:44.107  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 09:18:44.107  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,09-13 09:18:44.107  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 09:18:44.107  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 09:18:44.108  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 09:18:44.108  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 09:18:44.108  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 09:18:44.108  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 09:18:44.109  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 09:18:44.109  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 09:18:44.109  6877  6877 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 09:18:44.109  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,09-13 09:18:44.109  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 09:18:44.110  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 09:18:44.110  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 09:18:44.111  1035  1523 E WifiNative: : [190,802,013 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 09:18:44.111  1035  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 09:18:44.112  1035  1523 D WifiNative-wlan0: RECONNECT: returned true
09-13 09:18:44.112  1035  1523 D WifiNative-wlan0: doString: [STATUS]
09-13 09:18:44.112  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 09:18:44.113  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,09-13 09:18:44.113  1035  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 09:18:44.113  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 09:18:44.113  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:44.114  1035  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.115   307   893 D CommandListener: Setting iface cfg
09-13 09:18:44.115   307   893 D CommandListener: Trying to bring up p2p0
09-13 09:18:44.115  1035  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 09:18:44.115  1035  1522 D LGWifiP2pService: P2pEnablingState
09-13 09:18:44.115  1035  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.115  1035  1522 D LGWifiP2pService: P2p socket connection successful
09-13 09:18:44.115  1035  1522 D LGWifiP2pService: P2pEnabledState
09-13 09:18:44.115  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 09:18:44.115  1035  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 09:18:44.116  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-13 09:18:44.116  1035  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 09:18:44.116  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.116  1035  1541 I WifiNative-HAL: startHal
09-13 09:18:44.116  1035  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.116  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 09:18:44.117  1035  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 09:18:44.117  1035  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 09:18:44.117  1035  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 09:18:44.117  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 09:18:44.118  1927  1927 D WfdsService: WifiP2pState is changed : true
09-13 09:18:44.118  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 09:18:44.118  1035  1523 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 09:18:44.118  1927  1927 D WfdsService: isConnected: false
09-13 09:18:44.118  1035  1523 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 09:18:44.118  1927  2296 D WfdsService: Receive the WFDS_ENABLE Method
09-13 09:18:44.118  1927  2296 D WfdsService: Set the WFDS Monitor: true
09-13 09:18:44.118  1927  2296 D WfdsService: Connected to the supplicant for wfds
09-13 09:18:44.118  1927  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 09:18:44.118  6877  6877 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 09:18:44.118  1035  1523 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 09:18:44.118  1927  2296 D WfdsService: selectPreferredScanChannel [36]
09-13 09:18:44.118  1927  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 09:18:44.119  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 09:18:44.119  1035  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 09:18:44.119  1035  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 09:18:44.119  1035  1523 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 09:18:44.119  1035  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-13 09:18:44.119  1035  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 09:18:44.119  1035  1522 D LGWifiP2pService: before postfix = G3
09-13 09:18:44.119  1035  1522 D WifiServerServiceExt: postfix byte check : 2
09-13 09:18:44.119  1035  1522 D LGWifiP2pService,: after postfix = G3
09-13 09:18:44.119  1035  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 09:18:44.119  1035  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 09:18:44.119  1035  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 09:18:44.119  1035  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 09:18:44.120  1035  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 09:18:44.120  1035  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 09:18:44.120  1035  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 09:18:44.120  1035  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 09:18:44.120  1035  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 09:18:44.120  1035  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 09:18:44.120  1035  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-13 09:18:44.120  1035  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 09:18:44.120  1035  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 09:18:44.120  6877  6877 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 09:18:44.120  1035  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 09:18:44.120  1035  1541 D wifi    : getting scan capabilities on interface[1] = 0x953dc700
09-13 09:18:44.120  1035  1541 D wifi    : failed to get capabilities : -3
09-13 09:18:44.120  1035  1541 E WifiScanningService: could not get scan capabilities
09-13 09:18:44.121  1035  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 09:18:44.121  1035  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 09:18:44.121  1035  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 09:18:44.121  1035  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 09:18:44.122  6877  6877 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 09:18:44.122  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 09:18:44.122  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 09:18:44.123  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 09:18:44.123  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 09:18:44.123  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 09:18:44.123  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:44.124  6877  6877 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.124  1035  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 09:18:44.124  1035  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 09:18:44.124  6877  6877 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 09:18:44.124  6877  6877 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-13 09:18:44.125  6877  6877 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.125  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 09:18:44.125  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 09:18:44.125  1927  1927 D WfdsService: Update P2p Interface State: 3
09-13 09:18:44.127  1927  6882 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.127  1927  6882 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.127  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 09:18:44.127  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.127  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.127  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.127  1035  6881 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.127  1035  6881 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.127  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.127  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.127  1035  6881 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.127  1035  6881 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.127  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.127  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.128  1035  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 09:18:44.128  1035  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 09:18:44.128  1035  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 09:18:44.128  1035  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 09:18:44.128  1035  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 09:18:44.128  1035  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 09:18:44.128  1035  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 09:18:44.131  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 09:18:44.131  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 09:18:44.131  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 09:18:44.131  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 09:18:44.132  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 09:18:44.135  6830  6885 V FormManager: Network unavailable.
09-13 09:18:44.136  6830  6884 W FormManager: Network not available. Please check & try again.
,09-13 09:18:44.138  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:44.140  6563  6563 I UEI.SmartControl: Supports setup maps: true
09-13 09:18:44.142  6830  6885 V FormManager: Network unavailable.
09-13 09:18:44.143  6563  6563 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 09:18:44.143  6563  6563 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 09:18:44.143  6563  6563 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 09:18:44.143  6563  6563 I UEI.SmartControl: ### init IR Blaster...
09-13 09:18:44.146  6563  6563 D serial_port: Configuring serial port
09-13 09:18:44.146  6563  6563 E UEI.SmartControl: UEIBLaster setting for 616
,09-13 09:18:44.146  6563  6563 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 09:18:44.146  6563  6563 I UEI.SmartControl: configuring settings for MAXQ616
09-13 09:18:44.146  6563  6563 I UEI.SmartControl: Get version...
09-13 09:18:44.151  1035  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 09:18:44.151  1035  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 09:18:44.151  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 09:18:44.151  6877  6877 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:44.152  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 09:18:44.152  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:44.152  1035  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 09:18:44.152  1035  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 09:18:44.152  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:44.152  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:44.152  1035  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 09:18:44.152  1035  1523 D WifiNative-wlan0: doBoolean: SCAN
,09-13 09:18:44.152  1035  1523 D WifiNative-wlan0: SCAN: returned false
09-13 09:18:44.153  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=190844  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 09:18:44.153  1035  1522 D LGWifiP2pService: InactiveState
09-13 09:18:44.153  1035  1522 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.153  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.153  1035  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 09:18:44.154  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 09:18:44.154  6877  6877 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.154  1927  6882 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 09:18:44.154  1035  6881 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 09:18:44.154  1035  6881 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.155  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.155  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:44.155  6877  6877 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 09:18:44.155  6877  6877 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.155  1927  6882 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.155  1035  6881 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.155  1035  6881 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.155  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.155  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.155  6877  6877 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.155  1927  6882 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.156  1035  6881 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:44.156  1035  6881 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.156  1035  6881 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.156  1035  6881 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:44.157  1035  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: InactiveState{ when=-29ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-29ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=190849  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: Inactive,State{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.157  1035  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:44.157  1035  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.158  1035  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:44.158  1035  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:44.158  1035  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:44.158  1927  2296 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 09:18:44.159  1035  1035 E WifiServerServiceExt: No p2p device connected
09-13 09:18:44.159  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.159  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.159  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 09:18:44.159  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.159  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.160  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:44.160  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 09:18:44.160  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.160  6563  6886 D UEI.SmartControl: serial port data available: 21
09-13 09:18:44.162  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 09:18:44.162  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:44.163  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 09:18:44.164  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:44.167  4277  6887 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:44.169  6542  6542 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 09:18:44.169  6542  6542 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 09:18:44.170  4277  6888 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 09:18:44.170  4277  6888 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:44.174  6542  6542 V [BNRBootReceiver]: Boot Receiver Return
09-13 09:18:44.176  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 09:18:44.181  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:44.185  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:44.186  6563  6563 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 09:18:44.186  6563  6563 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 09:18:44.186  6563  6563 I UEI.SmartControl: QS saving settings...
09-13 09:18:44.186  6563  6563 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 09:18:44.189  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:44.189  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:44.190  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:44.203  6563  6886 D UEI.SmartControl: serial port data available: 4
,09-13 09:18:44.234  6563  6892 I UEI.SmartControl: Device manager: loading config....
,09-13 09:18:44.238  6563  6892 D UEI.SmartControl: ----------- loading internal config...
,09-13 09:18:44.238  6563  6563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 09:18:44.242  6563  6563 E UEI.SmartControl: Services init done
09-13 09:18:44.242  6563  6563 D UEI.SmartControl: QS Service init finished
09-13 09:18:44.244  6563  6563 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 09:18:44.244  6563  6563 D UEI.SmartControl: QS Service version code: 201091
09-13 09:18:44.245  6563  6563 D UEI.SmartControl: Service requested: Control
09-13 09:18:44.251  6563  6892 E UEI.SmartControl: Loading SETTINGS...
,09-13 09:18:44.252  6563  6563 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 09:18:44.258  6810  6810 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 09:18:44.259  6563  6563 D UEI.SmartControl: Internal service binding...
09-13 09:18:44.261  6563  6578 I UEI.SmartControl: ------ IControl API: 11
09-13 09:18:44.261  6563  6578 D UEI.SmartControl: File observer start...
09-13 09:18:44.262  6563  6578 E UEI.SmartControl: IR Port is disabled: false
09-13 09:18:44.262  6563  6578 D UEI.SmartControl: Starting file observer...
09-13 09:18:44.265  6563  6578 I UEI.SmartControl: Registering callback...
09-13 09:18:44.267  6563  6579 I UEI.SmartControl: ------ IControl API: 19
,09-13 09:18:44.269  6563  6892 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 09:18:44.270  6563  6579 I UEI.SmartControl: Registering Services Ready callback...
09-13 09:18:44.297  6563  6891 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-13 09:18:44.297  6563  6891 D UEI.SmartControl: -----service ready thread exits
09-13 09:18:44.298  6810  6825 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,09-13 09:18:44.298  6810  6867 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 09:18:44.298  6810  6867 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 09:18:44.299  6810  6810 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 09:18:44.300  6810  6810 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,09-13 09:18:44.300  6563  6578 I UEI.SmartControl: ------ IControl API: 8
,09-13 09:18:44.304  6810  6810 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 09:18:44.305  6810  6810 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 09:18:44.305  6810  6810 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 09:18:44.306  6810  6810 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 09:18:44.308  6810  6810 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 09:18:44.309  6810  6810 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 09:18:44.311  6810  6810 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 09:18:44.316  6810  6810 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 09:18:44.318  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 09:18:44.319  6810  6810 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 09:18:44.320  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 09:18:44.322  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 09:18:44.323  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 09:18:44.324  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 09:18:44.326  6810  6810 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473751124325]
09-13 09:18:44.328  6810  6810 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-13 09:18:44.340  1035  1943 I ActivityManager: Killing 5893:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-13 09:18:44.365  6810  6894 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 09:18:44.381  1035  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_5893/cgroup.procs: No such file or directory
,09-13 09:18:44.388  6810  6810 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-13 09:18:44.389  6810  6810 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 09:18:44.389  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 09:18:44.390  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 09:18:44.390  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-13 09:18:44.390  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 09:18:44.391  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 09:18:44.401  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-13 09:18:44.470  6667  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:44.481  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:44.482  1035  1998 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
,09-13 09:18:44.512  1035  1117 D BluetoothManagerService: Message: 2
09-13 09:18:44.513  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:44.514  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:44.514  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 09:18:44.514  1035  1117 D BluetoothManagerService: Sending off request.
09-13 09:18:44.516  3840  3857 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 09:18:44.518  3840  3913 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 09:18:44.519  3840  3913 D BluetoothAdapterProperties: Setting state to 13
09-13 09:18:44.519  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 09:18:44.521  3840  3913 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 09:18:44.521  3840  3913 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 09:18:44.521  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:44.522  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 09:18:44.522  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-13 09:18:44.529  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.529  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 09:18:44.532  3840  3840 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.533  3840  3840 D BluetoothMapService: STATE_TURNING_OFF
09-13 09:18:44.533  3840  3840 V BluetoothMapService: Handler(): got msg=4
09-13 09:18:44.533  3840  3840 D BluetoothMapService: MAP Service closeService in
09-13 09:18:44.533  3840  3840 D BluetoothMapMasInstance: MAP Service shutdown
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: 	,at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 09:18:44.534  3840  4114 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 09:18:44.535  3840  3840 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 09:18:44.535  3840  3840 V BluetoothMapService: MAP Service closeService out
09-13 09:18:44.535  3840  3840 V BtOppService: Receiver DISABLED_ACTION 
09-13 09:18:44.536  3840  3840 I BtOppRfcommListener: stopping Accept Thread
09-13 09:18:44.536  3840  3840 V BtOppRfcommListener: close mBtServerSocket
09-13 09:18:44.536  3840  4169 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:18:44.537  3840  3840 V BtOppRfcommListener: waiting for thread to terminate
09-13 09:18:44.537  3840  4169 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 09:18:44.539  3840  3840 V BtOppRfcommListener: done waiting for thread to terminate
09-13 09:18:44.541  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.541  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:44.543  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.543  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.546  3840  3917 D BluetoothAdapterProperties: Scan Mode:20
,09-13 09:18:44.547  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 09:18:44.548  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.548  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:44.549  3840  3840 V BtOppService: onDestroy
09-13 09:18:44.549  3840  4170 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:18:44.550  3840  3913 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 09:18:44.550  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 09:18:44.551  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.551  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.551  3840  4172 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:18:44.552  3840  3999 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 09:18:44.552  3840  4118 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:18:44.555  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.555  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:44.555  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.555  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.558  6667  6667 W org.thaliproject.p2p,.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:44.559  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:44.559  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:44.559  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 09:18:44.559  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 09:18:44.559  3840  3999 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-13 09:18:44.561  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:44.562  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:44.564  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:44.567  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:44.568  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 09:18:44.604  1035  1098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6897 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 09:18:44.604  3840  3840 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 09:18:44.609  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:44.609  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.609  3840  3840 V BluetoothPbapReceiver: ***********state = 13
09-13 09:18:44.612  3840  3840 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 09:18:44.613  1035  1117 D BluetoothManagerService: Message: 20
09-13 09:18:44.613  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9394c76:true
09-13 09:18:44.614  3840  3840 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.614  3840  3840 V BluetoothPbapService: state: 13
09-13 09:18:44.615  3840  3840 V BluetoothPbapService: Pbap Service closeService in
09-13 09:18:44.618  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:18:44.619  3840  3840 V BluetoothPbapService: successfully stopped pbap service
09-13 09:18:44.619  3840  3840 V BluetoothPbapService: Pbap Service closeService out
09-13 09:18:44.619  3840  3840 V BluetoothPbapService: Pbap Service onDestroy
09-13 09:18:44.619  3840  3840 V BluetoothPbapService: Pbap Service closeService in
09-13 09:18:44.619  3840  3840 V BluetoothPbapService: Pbap Service closeService out
09-13 09:18:44.619  3840  3840 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-13 09:18:44.623   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 21.031ms
,09-13 09:18:44.627  1035  1117 D BluetoothManagerService: Message: 30
09-13 09:18:44.631  1035  1117 D BluetoothManagerService: Message: 30
09-13 09:18:44.633  6787  6787 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 09:18:44.634  6787  6787 D BluetoothMap: Create BluetoothMap proxy object
09-13 09:18:44.634  1035  1117 D BluetoothManagerService: Message: 30
,09-13 09:18:44.637  1035  1117 D BluetoothManagerService: Message: 30
09-13 09:18:44.642   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 395us total 18.346ms
09-13 09:18:44.645  6787  6787 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 09:18:44.646  6787  6787 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-13 09:18:44.660   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 353us total 16.850ms
,09-13 09:18:44.663  6787  6787 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-13 09:18:44.665  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 09:18:44.671  6787  6787 D DockEventReceiver: finishStartingService: stopping service
09-13 09:18:44.671  6787  6787 D BluetoothInputDevice: Proxy object connected
09-13 09:18:44.672  6787  6787 D HidProfile: Bluetooth service connected
09-13 09:18:44.673  6787  6787 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 09:18:44.673  6787  6787 D PanProfile: Bluetooth service connected
,09-13 09:18:44.674  6787  6787 D BluetoothMap: Proxy object connected
09-13 09:18:44.674  6787  6787 D MapProfile: Bluetooth service connected
09-13 09:18:44.675  6787  6787 D BluetoothMap: getConnectedDevices()
09-13 09:18:44.675  6787  6787 D BluetoothMap: Bluetooth is Not enabled
09-13 09:18:44.675  6787  6787 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 09:18:44.690  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,09-13 09:18:44.690  6877  6877 E wpa_supplicant: USIM:  scard_init function
09-13 09:18:44.690  1035  6881 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 09:18:44.690  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 09:18:44.690  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-13 09:18:44.690  1035  6881 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 09:18:44.690  6877  6877 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 09:18:44.690  1035  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:44.690  1035  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:44.691  1035  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:44.691  1035  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:44.691  1035  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 09:18:44.692  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 09:18:44.692  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 09:18:44.695  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=191386  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 09:18:44.698  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.698  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.699  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.699  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.699  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 09:18:44.699  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.701  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=191393  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 09:18:44.702  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.702  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.702  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 09:18:44.703  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:44.703  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 09:18:44.711  6897  6897 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 09:18:44.712  6897  6897 W LG Account v2.2: No ProfileInfo entries
09-13 09:18:44.712  6897  6897 I LG Account v2.2: isEnabled: false
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Country: EU
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Operator: OPEN
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Ranking support: false
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Comfort support: false
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Accessory: true
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Health device: true
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Extra Pedometer: false
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Blood glucose device: false
09-13 09:18:44.712  6897  6897 I Feature : [Lifetracker]Device Number: 3
,09-13 09:18:44.716  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.716  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.719  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 09:18:44.719  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.721  6787  6787 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 09:18:44.721  6787  6787 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 09:18:44.724  6787  6787 D BluetoothPermissionRequest: onReceive
09-13 09:18:44.725  6787  6787 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 09:18:44.730  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 09:18:44.730  1035  1051 I ActivityManager: Killing 5914:com.android.contacts/u0a19 (adj 15): empty #17
09-13 09:18:44.750  3840  3840 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-13 09:18:44.750  3840  3840 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 09:18:44.750  3840  3840 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 09:18:44.750  1035  1998 W libprocessgroup: failed to open /acct/uid_10019/pid_5914/cgroup.procs: No such file or directory
09-13 09:18:44.753  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:44.756  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.756  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 09:18:44.757  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:44.757  3840  3840 V BluetoothFtpService: Ftp Service onStartCommand
09-13 09:18:44.757  3840  3840 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.758  3840  3840 V BluetoothFtpService: Ftp Service closeService
09-13 09:18:44.758  3840  3840 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 09:18:44.758  3840  3840 V BluetoothFtpService: successfully stopped ftp service
09-13 09:18:44.758  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 09:18:44.759  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:44.759  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:44.759  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.759  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 09:18:44.759  3840  3840 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 09:18:44.760  3840  3840 V BluetoothFtpService: Ftp Service onDestroy
09-13 09:18:44.760  3840  3840 V BluetoothFtpService: Ftp Service closeService
,09-13 09:18:44.764  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:44.818  6877  6877 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 09:18:44.820  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 09:18:44.823  1035  2019 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6923 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 09:18:44.823  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 09:18:44.824  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 09:18:44.824  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 09:18:44.826  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=191518  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 09:18:44.828  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=191519  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 09:18:44.829  3840  3840 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:44.829  3840  3840 V BluetoothSapService: state: 13
09-13 09:18:44.829  3840  3840 V BluetoothSapService: Stopping SAP server process
09-13 09:18:44.830  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 09:18:44.830  1035  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191522
09-13 09:18:44.830  1035  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191522
09-13 09:18:44.831  1035  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191522
09-13 09:18:44.831  3840  3840 V BluetoothSapService: Sap Service closeSapService in
09-13 09:18:44.831  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191523
09-13 09:18:44.831  3840  3840 V BluetoothSapService: Close listen Socket : 
09-13 09:18:44.832  3840  3840 V BluetoothSapService: Close rfcomm Socket : 
09-13 09:18:44.832  3840  3840 V BluetoothSapService: Close sapd  Socket : 
09-13 09:18:44.832  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:44.832  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:44.832  1035  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191523
09-13 09:18:44.833  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:44.833  1035  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.833  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 09:18:44.833  1035  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,09-13 09:18:44.833  1035  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.833  3840  3840 V BluetoothSapService: Sap Service closeSapService out
09-13 09:18:44.834  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.834  3840  3840 V BluetoothSapService: Sap Service onDestroy
09-13 09:18:44.834  3840  3840 V BluetoothSapService: Sap Service closeSapService in
09-13 09:18:44.834  3840  3840 V BluetoothSapService: Close listen Socket : 
09-13 09:18:44.834  3840  3840 V BluetoothSapService: Close rfcomm Socket : 
09-13 09:18:44.834  3840  3840 V BluetoothSapService: Close sapd  Socket : 
09-13 09:18:44.834  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:44.835  3840  3840 V BluetoothSapService: Sap Service closeSapService out
09-13 09:18:44.835  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=191526  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 09:18:44.837  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.837  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.838  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.839  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.839  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.839  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 09:18:44.841  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=191532  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 09:18:44.842  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.842  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.842  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 09:18:44.844  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:44.844  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:44.844  6877  6877 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 09:18:44.845  6877  6877 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-13 09:18:44.846  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 09:18:44.846  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 09:18:44.846  1035  6881 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 09:18:44.846  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 09:18:44.846  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 09:18:44.846  1035  6881 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 09:18:44.846  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:44.846  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:44.852  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:44.853  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=191544  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 09:18:44.853  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:44.853  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=191545  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 09:18:44.854  1035  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=191545
09-13 09:18:44.854  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:44.854  1035  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=191546
09-13 09:18:44.855  1035  1523 D WifiNative-wlan0: doString: [STATUS]
09-13 09:18:44.856  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:44.856  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 09:18:44.856  1035  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-13 09:18:44.856  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:44.857  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:44.858  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.858  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.858  1035  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 09:18:44.859  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:44.859  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.866  1035  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 09:18:44.866  1035  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 09:18:44.870  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:44.873  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.874  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.874  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 09:18:44.875  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.875  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.875  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 09:18:44.881  1035  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 09:18:44.881  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.881  1035  1530 D ConnectivityService: Got NetworkAgent Messenger
09-13 09:18:44.881  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.881  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 09:18:44.881  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 09:18:44.881  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 09:18:44.881  1035  1530 D ConnectivityService: NetworkAgent connected
09-13 09:18:44.881  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 09:18:44.881  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 09:18:44.883  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.885  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.885  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 09:18:44.886  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.890  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:44.890  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 09:18:44.890  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 09:18:44.890  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 09:18:44.891  6923  6923 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 09:18:44.891  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 09:18:44.892  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 09:18:44.895  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 09:18:44.897   307   893 D CommandListener: Setting iface cfg
,09-13 09:18:44.898  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:44.898  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:44.899  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:44.901  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 09:18:44.902  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 09:18:44.902  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 09:18:44.902  6787  6787 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 09:18:44.902  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 09:18:44.902  1035  1523 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 09:18:44.903  6787  6787 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 09:18:44.903  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=191594  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:44.903  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 09:18:44.903  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 09:18:44.903  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 09:18:44.903  6787  6787 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 09:18:44.903  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 09:18:44.903  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=191595  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:44.903  6787  6787 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 09:18:44.904  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=191595  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:44.904  1035  6941 D DhcpStateMachine: StoppedState
09-13 09:18:44.904  1035  6941 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.904  1035  6941 D DhcpStateMachine: WaitBeforeStartState
09-13 09:18:44.906  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:44.908  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=191599  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:44.908  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=191599  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:44.908  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:44.908  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 09:18:44.909  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=191600  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:44.910  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:145430] from screen [on:0 period:577342382] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 09:18:44.910  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:577342382] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 09:18:44.910  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 09:18:44.916  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.917  1035  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 09:18:44.917  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.918  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.918  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:44.919  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.919  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.919  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 09:18:44.920  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.920  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 09:18:44.921  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=108,0,0
09-13 09:18:44.921  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:44.921  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 09:18:44.921  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=108,0,0
09-13 09:18:44.921  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 09:18:44.921  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 09:18:44.922  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 09:18:44.922  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 0
,09-13 09:18:44.922  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:44.923  1035  1523 D WifiNative-wlan0: SET ps 0: returned true
09-13 09:18:44.923  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 09:18:44.923  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,09-13 09:18:44.924  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 09:18:44.924  1035  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 09:18:44.924  1035  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 09:18:44.924  1035  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@170f569d target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.924  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@170f569d target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.924  1035  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 09:18:44.924  1035  6941 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.924  1035  6941 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 09:18:44.925   307   893 D CommandListener: Setting iface cfg
09-13 09:18:44.925   307   893 D CommandListener: Trying to bring up wlan0
09-13 09:18:44.925  1035  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 09:18:44.928  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:44.928  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:44.928  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:44.928  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 09:18:44.928  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:44.928  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.929  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.929  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.929  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.930  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.930  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:44.930  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 09:18:44.932  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:44.932  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 09:18:44.932  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 09:18:44.932  1035  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.932  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:44.933  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 09:18:44.933  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 09:18:44.933  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 09:18:44.933  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 09:18:44.933  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 09:18:44.934  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 09:18:44.934  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
,09-13 09:18:44.939  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:44.943  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:44.948  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:44.949  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 09:18:44.949  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:44.950  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:44.950  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 09:18:44.951  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 09:18:44.951  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 09:18:44.951  1035  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 09:18:44.952  1035  1530 D ConnectivityService: ignoring duplicate network state non-change
,09-13 09:18:44.955  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:44.956  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 09:18:44.957  1035  1530 D ConnectivityService: Adding iface wlan0 to network 101
09-13 09:18:44.957  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.957  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.958  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.958  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.958  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 09:18:44.969  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:44.975  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.976  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.976  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 09:18:44.976  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 09:18:44.980  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 09:18:44.980  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.980  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.980  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 09:18:44.981  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-13 09:18:44.985  1035  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 09:18:44.989  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.989  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:44.989  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 09:18:44.992  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.992  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:44.994  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:44.996  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:44.997  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:44.997  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 09:18:44.997  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:45.001  1035  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 09:18:45.001  1035  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-13 09:18:45.002  1035  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 09:18:45.003   307   893 E Netd    : netlink response contains error (File exists)
09-13 09:18:45.003  1035  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 09:18:45.004  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:45.004  1035  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 09:18:45.004  1035  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 09:18:45.005  1035  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 09:18:45.005  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:45.006  1035  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 09:18:45.006  1035  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 09:18:45.006  1035  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 09:18:45.006  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 09:18:45.006  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:45.006  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:45.006  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:45.006  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.006  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 09:18:45.006  1035  1530 D ConnectivityService: currentScore = 0, newScore = 20
09-13 09:18:45.006  1035  1530 D ConnectivityService:    accepting network in place of null
09-13 09:18:45.006  1035  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.007  1035  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.007  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:45.007  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.007  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT,_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 09:18:45.009  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:45.009  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 09:18:45.009  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:45.009  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 09:18:45.011   307  6945 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,09-13 09:18:45.015  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 09:18:45.016  1035  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 09:18:45.016  1035  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 09:18:45.016  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 09:18:45.017  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:45.018  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:45.019  1035  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:45.019  1035  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 09:18:45.020  1035  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 09:18:45.021  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 09:18:45.021  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 09:18:45.021  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 09:18:45.021  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 09:18:45.022  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:45.023  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 09:18:45.023  1035  1530 D ConnectivityService: validation of new default Network = false
09-13 09:18:45.023  1035  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 09:18:45.023  1035  1530 D DSQN    : enableDataServiceNotify 
09-13 09:18:45.023  1035  1530 D DSQN    : start dsqn bin
09-13 09:18:45.025  6667  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:45.025  6667  6895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:45.026  6667  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.026  6667  6895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.028  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 09:18:45.028  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.028  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:45.029  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:45.029  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 09:18:45.030  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:45.019  6947  6947 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:45.019  6947  6947 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:45.035  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 09:18:45.036  1035  1560 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
09-13 09:18:45.047  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:45.050  6947  6947 E DSQN    : DSQN ssw
,09-13 09:18:45.051  1035  1117 D BluetoothManagerService: Message: 1
09-13 09:18:45.051  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b
09-13 09:18:45.052  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:45.053  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:45.053  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 09:18:45.054  3840  6730 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 09:18:45.055  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 09:18:45.055  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:45.062  1035  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-13 09:18:45.066  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:45.067  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:45.067  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:45.074  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 09:18:45.074  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:45.074  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:45.075  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:45.083  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:45.088  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:45.088   307  6945 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 09:18:45.093  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:45.093  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:45.097  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 09:18:45.100  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 09:18:45.108  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:45.116  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:45.126  1035  6941 D DhcpStateMachine: DHCPV4 request on wlan0
,09-13 09:18:45.126   307  6945 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 09:18:45.127  1035  6941 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 09:18:45.127  1035  6941 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 09:18:45.119  6952  6952 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:45.119  6952  6952 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:45.129  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:45.130  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:45.131  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:45.137  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:45.143  6952  6952 I dhcpcd  : version 5.5.6 starting
09-13 09:18:45.144  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 09:18:45.145  6952  6952 E dhcpcd  : get_duid: m
09-13 09:18:45.145  6952  6952 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 09:18:45.145  6952  6952 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-13 09:18:45.149  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:45.154   307   892 D LGDataListener: argv[0]=dsqncommand
09-13 09:18:45.154   307   892 D LGDataListener: argv[1]=wlan0
09-13 09:18:45.154   307   892 D LGDataListener: argv[2]=1
09-13 09:18:45.154   307   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 09:18:45.155  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:45.155  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 09:18:45.155  1035  1115 D DSQN    : start to monitor internet connection
,09-13 09:18:45.164  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:45.172  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 09:18:45.173  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:45.174  6810  6810 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 09:18:45.175  6810  6810 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 09:18:45.176  6810  6810 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 09:18:45.180  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:45.185  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:18:45 GMT], X-Android-Received-Millis=[1473751125184], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473751125154]}
09-13 09:18:45.185  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 09:18:45.185  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 09:18:45.185  1035  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 09:18:45.185  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 09:18:45.185  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:45.185  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:45.185  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:45.185  1035  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,09-13 09:18:45.185  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 09:18:45.185  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.185  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:45.186  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 09:18:45.186  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:45.187  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 09:18:45.187  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:45.188  1035  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.188  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 09:18:45.188  1035  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.188  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:45.189  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:45.190  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 09:18:45.194  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:45.202  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:45.210  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 09:18:45.211  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:45.212  6810  6810 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-13 09:18:45.212  6952  6952 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 09:18:45.213  6810  6810 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 09:18:45.213  6952  6952 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 09:18:45.213  6952  6952 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 09:18:45.213  6810  6810 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 09:18:45.213  6952  6952 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 09:18:45.213  6952  6952 D dhcpcd  : wlan0: sending REQUEST (xid 0x8f96d298), next in 3.20 seconds
09-13 09:18:45.217  1035  1890 I ActivityManager: Killing 6457:com.lge.email/u0a23 (adj 15): empty #17
09-13 09:18:45.246  6952  6952 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 09:18:45.251  6952  6952 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-13 09:18:45.251  6952  6952 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 09:18:45.251  6952  6952 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 09:18:45.252  6952  6952 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 09:18:45.252  6952  6952 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 09:18:45.253  6952  6952 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 09:18:45.253  6952  6952 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 09:18:45.253  6952  6952 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 09:18:45.274  1035  2010 W libprocessgroup: failed to open /acct/uid_10023/pid_6457/cgroup.procs: No such file or directory
,09-13 09:18:45.303  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 09:18:45.305  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:45.306  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:45.542  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:45.549  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:45.556  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 09:18:45.559  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:45.560  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:45.562  3840  3917 D bt_hci_bdroid: cleanup
09-13 09:18:45.563  3840  4003 I bt_lpm  : LPM is already off!!!
09-13 09:18:45.563  3840  3999 W bt-btif : ag scb idx 1 not allocated
09-13 09:18:45.563  3840  3999 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:45.563  3840  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:45.563  3840  3999 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 09:18:45.564  3840  4104 I bt_userial_mct: exiting userial_read_thread
09-13 09:18:45.564  3840  4104 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-13 09:18:45.566  3840  3917 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 09:18:45.566  3840  4003 I bt_vendor: hw_epilog_process
09-13 09:18:45.566  3840  3917 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 09:18:45.566  3840  3917 D bt_userial_mct: userial_close
09-13 09:18:45.566  3840  3917 E bt_userial_mct: pthread_join() FAILED result:3
09-13 09:18:45.566  3840  3917 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 09:18:45.572  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 09:18:45.576  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:45.581  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:45.581  1035  1908 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
09-13 09:18:45.582  1035  1117 D BluetoothManagerService: Message: 1
09-13 09:18:45.582  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b
09-13 09:18:45.583  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:45.583  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:45.583  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.583  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.587  5652  5652 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 09:18:45.588  3840  3858 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 09:18:45.589  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 09:18:45.591  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:45.591  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:18:45.593  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 09:18:45.597  6368  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 09:18:45.600  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:45.602  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.602  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.605  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:45.606  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:18:45.606  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:45.606  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:45.609  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.611  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.614  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.618  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:45.622  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.622  5652  5652 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 09:18:45.638  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:45.647   307  6995 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 09:18:45.647   307  6995 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 09:18:45.678  3840  3917 D bt_hci_bdroid: set_power 0
09-13 09:18:45.678  3840  3917 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 09:18:45.679  3840  3917 I bt_vendor: bluetooth satus is on
09-13 09:18:45.679  3840  3917 I bt_vendor: bt-vendor : resetting BT status
09-13 09:18:45.679  3840  3917 I bt_vendor: Starting hciattach daemon
09-13 09:18:45.679  3840  3917 I bt_vendor: try to set false
09-13 09:18:45.680  3840  3917 I bt_vendor: Starting hciattach daemon
,09-13 09:18:45.680  3840  3917 I bt_vendor: try to set false
09-13 09:18:45.680  3840  3917 I bt_vendor: cleanup
09-13 09:18:45.681  3840  3999 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 09:18:45.681   307  6995 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-13 09:18:45.707  1035  1926 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6997 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-13 09:18:45.716  3840  3917 I GKI_LINUX: GKI_exit_task 0 done
09-13 09:18:45.716  3840  3917 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 09:18:45.719  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 09:18:45.723  3840  3840 D HeadsetService: Received stop request...Stopping profile...
,09-13 09:18:45.728  3840  3840 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 09:18:45.728  3840  3840 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 09:18:45.728  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:45.730  3840  3941 D HeadsetStateMachine: Exit Disconnected: -1
09-13 09:18:45.731  1035  6941 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-13 09:18:45.732  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 09:18:45.732  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 09:18:45.733  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-13 09:18:45.733  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 09:18:45.733  1035  6941 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 09:18:45.733  1035  6941 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 09:18:45.734  1035  6941 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 09:18:45.734  1035  6941 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 09:18:45.734  1035  6941 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 09:18:45.734  1035  6941 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 09:18:45.734  1035  6941 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 09:18:45.735  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 09:18:45.735  1035  6941 D DhcpStateMachine: RunningState
09-13 09:18:45.736  3840  3840 D A2dpService: Received stop request...Stopping profile...
09-13 09:18:45.736  3840  3980 D A2dpStateMachine: Exit Disconnected: -1
09-13 09:18:45.738  3840  3913 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 09:18:45.738  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-13 09:18:45.742  3840  3840 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 09:18:45.742  3840  3840 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 09:18:45.742  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:45.743  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 09:18:45.743  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 09:18:45.744  3840  3840 D HidService: Received stop request...Stopping profile...
,09-13 09:18:45.744  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:45.745  6787  6787 D BluetoothInputDevice: Proxy object disconnected
09-13 09:18:45.745  6787  6787 D HidProfile: Bluetooth service disconnected
09-13 09:18:45.745  3840  3840 D HealthService: Received stop request...Stopping profile...
09-13 09:18:45.746  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:45.747  3840  3840 D HeadsetStateMachine: Unbinding service...
09-13 09:18:45.748  3840  3840 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 09:18:45.748  3840  3840 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 09:18:45.748  3840  3840 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 09:18:45.748  3840  3840 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 09:18:45.748  3840  3840 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 09:18:45.748  3840  3840 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 09:18:45.748  3840  3840 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 09:18:45.749  3840  3840 D PanService: Received stop request...Stopping profile...
09-13 09:18:45.749  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:45.750  3840  3840 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 09:18:45.751  3840  3840 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 09:18:45.751  3840  3840 D BtGatt.GattService: stop()
09-13 09:18:45.751  3840  3840 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 09:18:45.752  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
,09-13 09:18:45.753  3840  3840 D BluetoothMapService: Received stop request...Stopping profile...
09-13 09:18:45.753  3840  3840 D BluetoothMapService: stop()
09-13 09:18:45.753  6787  6787 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 09:18:45.753  6787  6787 D PanProfile: Bluetooth service disconnected
09-13 09:18:45.754  3840  3840 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 09:18:45.754  3840  3840 D BluetoothMapEmailAppObserver: removeReceiver()
,09-13 09:18:45.754  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
,09-13 09:18:45.756  3840  3840 I BluetoothA2dpServiceJni: cleanupNative
09-13 09:18:45.756  3840  3981 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 09:18:45.757  6787  6787 D BluetoothMap: Proxy object disconnected
09-13 09:18:45.757  6787  6787 D MapProfile: Bluetooth service disconnected
09-13 09:18:45.757  3840  3840 I GKI_LINUX: GKI_exit_task 2 done
09-13 09:18:45.757  3840  3840 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 09:18:45.757  3840  3840 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 09:18:45.757  3840  3840 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 09:18:45.758  3840  3840 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 09:18:45.758  3840  3840 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 09:18:45.758  3840  3840 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 09:18:45.758  3840  3840 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 09:18:45.758  3840  3840 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 09:18:45.760  3840  3840 V BluetoothMapService: Handler(): got msg=4
09-13 09:18:45.760  3840  3840 D BluetoothMapService: MAP Service closeService in
09-13 09:18:45.760  3840  3840 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 09:18:45.760  3840  3840 V BluetoothMapService: MAP Service closeService out
09-13 09:18:45.760  3840  3840 D BluetoothMapService: cleanup()
09-13 09:18:45.761  3840  3840 D BluetoothMapService: MAP Service closeService in
09-13 09:18:45.761  3840  3840 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 09:18:45.761  3840  3840 V BluetoothMapService: MAP Service closeService out
09-13 09:18:45.762  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 09:18:45.762  3840  3913 D BluetoothAdapterProperties: Setting state to 10
09-13 09:18:45.762  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 09:18:45.763  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:45.763  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 09:18:45.763  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 09:18:45.763  6787  6803 D BluetoothMap: onBluetoothStateChange: up=false
09-13 09:18:45.763  3840  3913 I BluetoothAdapterState: Entering OffState
09-13 09:18:45.764  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:45.764  6787  6802 D BluetoothPan: onBluetoothStateChange on: false
09-13 09:18:45.765  6787  6803 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 09:18:45.765  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:45.766  1837  3940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:45.767  1837  3943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:45.767  6787  6802 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 09:18:45.768  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 09:18:45.768  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 09:18:45.771  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:45.772  1927  2110 D LGBluetoothAPIService: Message: 2
09-13 09:18:45.772  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 09:18:45.772  1927  2110 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@37fb8fc9 mBinding = false
09-13 09:18:45.772  1927  2110 D LGBluetoothAPIService: Sending unbind request.
09-13 09:18:45.775  6787  6787 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 09:18:45.776  6787  6787 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 09:18:45.776  6787  6787 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 09:18:45.778  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.779  3840  3840 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 09:18:45.779  3840  3840 D LGBluetoothAPIServer: [BTUI] cleanup() done
,09-13 09:18:45.780  3840  3840 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 09:18:45.781  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.781  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 09:18:45.783  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.786  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:45.786  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:45.786  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:45.786  3840  3840 V BluetoothPbapReceiver: ***********state = 10
09-13 09:18:45.790  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 09:18:45.792  6787  6787 D DockEventReceiver: finishStartingService: stopping service
,09-13 09:18:45.808  6787  6787 D BluetoothPermissionRequest: onReceive
,09-13 09:18:45.811  6787  6787 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 09:18:45.812  6787  6787 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 09:18:45.815  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 09:18:45.823  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 09:18:45.825  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-13 09:18:45.825  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:45.825  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:45.825  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-13 09:18:45.825  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 09:18:45.833  6923  6923 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 09:18:45.845  6997  6997 I AppUp4:AppBoxCP: onCreate
09-13 09:18:45.846  6997  6997 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-13 09:18:45.855  6997  6997 I AppUp4:DB:  setFingerPrint start
09-13 09:18:45.856  6997  6997 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-13 09:18:45.864  6997  6997 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-13 09:18:45.864  6997  6997 I AppUp4:DB:  SDK version = 21
,09-13 09:18:45.864  6997  6997 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-13 09:18:45.865  6997  6997 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-13 09:18:45.867  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 09:18:45.867  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:45.869  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 09:18:45.870  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 09:18:45.876  6997  6997 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 09:18:45.914  6997  6997 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 09:18:45.914  6997  6997 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 09:18:45.923  6997  6997 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26d221b9
09-13 09:18:45.923  6997  6997 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 09:18:45.923  6997  6997 D AppUp4:CustFacade: isPhone : true
09-13 09:18:45.925  6997  6997 D AppUp4:CustModeStarterReceiver: begin check event
09-13 09:18:45.926  6997  6997 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-13 09:18:45.926  6997  6997 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 09:18:45.928  6997  7018 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 09:18:45.928  6997  7018 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 09:18:45.929  6997  7018 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-13 09:18:45.930  1035  1693 I ActivityManager: Killing 5941:com.android.gallery3d/u0a27 (adj 15): empty #17
09-13 09:18:45.941  2214  7016 D GCM     : Connected
,09-13 09:18:46.030  1035  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 09:18:46.056  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:46.057  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:46.058  1035  1866 W libprocessgroup: failed to open /acct/uid_10027/pid_5941/cgroup.procs: No such file or directory
09-13 09:18:46.063  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 09:18:46.071  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:46.084  2832  2832 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:46.086  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:46.087  1035  1943 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
09-13 09:18:46.090  2214  7016 D GCM     : Message class com.google.e.a.a.q
09-13 09:18:46.090  1035  1117 D BluetoothManagerService: Message: 1
09-13 09:18:46.090  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b
09-13 09:18:46.092  4277  7020 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:46.093  2832  2832 V DownloadManager: DownloadService onCreate
09-13 09:18:46.097  3840  3913 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 09:18:46.097  3840  3913 D BluetoothAdapterProperties: Setting state to 11
09-13 09:18:46.097  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-13 09:18:46.098  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:46.098  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 09:18:46.098  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 09:18:46.098  3840  3913 D BluetoothBondStateMachine: make
09-13 09:18:46.101  3840  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.101  3840  3913 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 09:18:46.101  3840  7024 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 09:18:46.101  3840  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.101  3840  3913 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 09:18:46.101  3840  3913 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 09:18:46.106  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:46.111  2832  7022 I DownloadManager: in removeSpuriousFiles
09-13 09:18:46.112  2832  7022 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 09:18:46.113  2832  7022 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3b00820d on behalf of 2832
09-13 09:18:46.114  4277  7020 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 09:18:46.115  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 09:18:46.115  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 09:18:46.115  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 09:18:46.115  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 09:18:46.116  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 09:18:46.116  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 09:18:46.116  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 09:18:46.116  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 09:18:46.116  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 09:18:46.116  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 09:18:46.116  2832  7022 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 09:18:46.117  4277  7021 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:46.117  4277  7021 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:46.119  2832  7022 I DownloadManager: in trimDatabase
09-13 09:18:46.120  2832  7022 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 09:18:46.121  2832  7022 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29e585c2 on behalf of 2832
09-13 09:18:46.163  1035  1962 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7026 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 09:18:46.170  3840  3840 D HeadsetService: Received start request. Starting profile...
,09-13 09:18:46.171  3840  3840 D HeadsetStateMachine: make
09-13 09:18:46.173  2832  2832 V DownloadManager: DownloadService onStartCommand
09-13 09:18:46.173  2832  7023 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 09:18:46.174  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 09:18:46.175  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:46.175  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:46.181  6787  6787 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 09:18:46.185  4277  7020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-13 09:18:46.187  3840  3840 D HeadsetStateMachine: max_hf_connections = 1
09-13 09:18:46.187  3840  3840 I bluedroid-qcom: get_profile_interface handsfree
09-13 09:18:46.187  3840  3840 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 09:18:46.188  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.189  3840  7035 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 09:18:46.189  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:46.189  3840  7035 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 09:18:46.189  3840  7035 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 09:18:46.189  3840  7035 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 09:18:46.190   312  2137 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3840
09-13 09:18:46.191   312  2137 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 09:18:46.191   312  2137 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 09:18:46.191   312  2137 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 09:18:46.191   312  2137 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 09:18:46.191   312  2137 V voice   : voice_set_parameters: exit with code(0)
09-13 09:18:46.191   312  2137 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 09:18:46.191   312  2137 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 09:18:46.191  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.191   312  2137 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 09:18:46.191   312  2137 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 09:18:46.191   312  2137 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 09:18:46.191   312  2137 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 09:18:46.192  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:46.192  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:46.194  3840  3840 D A2dpService: Received start request. Starting profile...
09-13 09:18:46.194  3840  3840 V Avrcp   : make
09-13 09:18:46.194  3840  3840 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 09:18:46.194  3840  3840 I bluedroid-qcom: get_profile_interface avrcp
,09-13 09:18:46.199  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:46.199  2832  7023 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@24403209 on behalf of 2832
09-13 09:18:46.204  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:46.208  4277  4277 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 09:18:46.208  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 09:18:46.210  4277  4277 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 09:18:46.211  2832  7023 V DownloadManager: processing inserted download 1
09-13 09:18:46.211  4277  4277 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 09:18:46.212  3840  3840 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 09:18:46.212  2832  7023 V DownloadManager: processing inserted download 4
09-13 09:18:46.213  4277  4277 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 09:18:46.214  2832  7023 V DownloadManager: processing inserted download 7
09-13 09:18:46.214  3840  3840 E AudioManager: No RCC entry present to update
09-13 09:18:46.214  3840  3840 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 09:18:46.214  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 09:18:46.214  3840  3840 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 09:18:46.215  2832  7023 V DownloadManager: processing inserted download 8
09-13 09:18:46.216  4277  4277 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 09:18:46.216  2832  7023 V DownloadManager: processing inserted download 9
09-13 09:18:46.217  2832  7023 V DownloadManager: processing inserted download 10
09-13 09:18:46.218  2832  7023 V DownloadManager: processing inserted download 11
09-13 09:18:46.219  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 09:18:46.219  2832  7023 V DownloadManager: processing inserted download 12
09-13 09:18:46.221  2832  7023 V DownloadManager: processing inserted download 13
09-13 09:18:46.222  2832  7023 V DownloadManager: processing inserted download 14
09-13 09:18:46.223  2832  7023 V DownloadManager: processing inserted download 16
09-13 09:18:46.226  2832  2832 V DownloadManager: DownloadService onDestroy
09-13 09:18:46.226  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:46.231  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 09:18:46.233  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:46.282  3840  3913 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 09:18:46.320  7026  7026 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 09:18:46.321  7026  7026 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 09:18:46.322  7026  7026 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 09:18:46.323  7026  7026 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 09:18:46.382  1035  1978 V SIM_STK : Menu title from STK is T-Mobile
09-13 09:18:46.383  1035  1978 V SIM_STK : Menu title from STK is T-Mobile
09-13 09:18:46.386  7026  7026 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 09:18:46.398  7026  7026 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 09:18:46.455  7026  7026 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 09:18:46.501  1035  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:46.502  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:46.503  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:46.505  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:46.506  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:46.507  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:46.508  1035  1998 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 09:18:46.509  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 09:18:46.509  1035  1530 D ConnectivityService: identical MTU - not setting
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 09:18:46.509  1035  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 09:18:46.509  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 09:18:46.509  3840  3840 D A2dpStateMachine: make
09-13 09:18:46.509  1035  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 09:18:46.510  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:46.510  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:46.511  1035  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:46.514  7026  7026 D LgDataFeature: LgDataFeature() Constructor: none
09-13 09:18:46.514  7026  7026 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 09:18:46.515  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 09:18:46.516  3840  3840 I bluedroid-qcom: get_profile_interface a2dp
09-13 09:18:46.516  3840  7051 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 09:18:46.517  3840  3840 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 09:18:46.517  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.517  3840  7050 D A2dpStateMachine: Enter Disconnected: -2
,09-13 09:18:46.517  3840  3840 D HeadsetStateMachine: Proxy object connected
09-13 09:18:46.517  3840  3840 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 09:18:46.517  3840  3840 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 09:18:46.518  3840  7035 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 09:18:46.518  3840  7035 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 09:18:46.518  3840  7035 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 09:18:46.521  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:46.521  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:46.521  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:46.522  3840  3840 V BluetoothPbapReceiver: ***********state = 11
09-13 09:18:46.524  3840  3840 D HidService: Received start request. Starting profile...
09-13 09:18:46.524  3840  3840 I bluedroid-qcom: get_profile_interface hidhost
09-13 09:18:46.524  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.525  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 09:18:46.526  3840  3840 D HealthService: Received start request. Starting profile...
09-13 09:18:46.528  3840  3840 I bluedroid-qcom: get_profile_interface health
09-13 09:18:46.528  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.529  3840  3840 D PanService: Received start request. Starting profile...
09-13 09:18:46.529  3840  3840 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 09:18:46.529  3840  3840 I bluedroid-qcom: get_profile_interface pan
09-13 09:18:46.534  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.534  3840  3840 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 09:18:46.536  3840  3840 D BtGatt.GattService: Received start request. Starting profile...
,09-13 09:18:46.536  3840  3840 D BtGatt.GattService: start()
09-13 09:18:46.536  3840  3840 D BtGatt.AdvertiseManager: advertise manager created
09-13 09:18:46.544  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.544  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.544  3840  3840 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 09:18:46.544  3840  3840 V BluetoothMapService: BluetoothMapBinder()
09-13 09:18:46.545  3840  3840 D BluetoothMapService: Received start request. Starting profile...
09-13 09:18:46.545  3840  3840 D BluetoothMapService: start()
09-13 09:18:46.547  3840  3840 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 09:18:46.547  3840  3840 D BluetoothMapEmailAppObserver: createReceiver()
09-13 09:18:46.548  6787  6787 D BluetoothPermissionRequest: onReceive
,09-13 09:18:46.550  3840  3840 D BluetoothMapEmailAppObserver: initObservers()
09-13 09:18:46.550  3840  3840 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 09:18:46.550  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:46.553  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:46.554  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 09:18:46.557  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:46.559  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:46.562  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:46.562  3840  3840 V PanService: [BTUI] SIM Extra State :ABSENT
,09-13 09:18:46.565  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 09:18:46.565  3840  3840 V BluetoothMapService: Handler(): got msg=1
09-13 09:18:46.566  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 09:18:46.566  3840  3913 I bluedroid-qcom: enable
09-13 09:18:46.566  3840  3913 I bt_hci_bdroid: init
09-13 09:18:46.566  3840  7060 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 09:18:46.567  3840  3913 I bt_vendor: bt-vendor : init
09-13 09:18:46.567  3840  3913 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 09:18:46.567  3840  3913 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 09:18:46.567  3840  3913 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 09:18:46.567  3840  3913 D bt_userial_mct: userial_init
09-13 09:18:46.566  3840  7060 I bt-btu  : btu_task pending for preload complete event
09-13 09:18:46.567  3840  3913 D bt_hci_bdroid: set_power 1
09-13 09:18:46.567  3840  3913 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 09:18:46.567  3840  3913 I bt_vendor: Starting hciattach daemon
09-13 09:18:46.567  3840  3913 I bt_vendor: try to set true
09-13 09:18:46.559  7063  7063 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:46.559  7063  7063 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:46.570  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:46.572  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 09:18:46.572  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:46.572  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:46.572  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:46.572  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-13 09:18:46.583  7064  7064 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-13 09:18:46.591  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 09:18:46.591  1035  1998 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
09-13 09:18:46.591  1035  1117 D BluetoothManagerService: Message: 1
09-13 09:18:46.591  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b
09-13 09:18:46.593  3840  3858 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 09:18:46.593  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
,09-13 09:18:46.641  7026  7026 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 09:18:46.671  3440  3440 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 09:18:46.671  3440  3440 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:46.671  3440  3440 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 09:18:46.676  7074  7074 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
09-13 09:18:46.677  7026  7026 I HubEmail: JNI_OnLoad()
09-13 09:18:46.677  7026  7026 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 09:18:46.677  7026  7026 I HubEmail: registerNatives()
09-13 09:18:46.677  7026  7026 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 09:18:46.677  7026  7026 I HubEmail: registerNativeMethods()
09-13 09:18:46.677  7026  7026 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 09:18:46.677  7026  7026 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-13 09:18:46.689  7080  7080 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 09:18:46.704   307  7085 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 09:18:46.704   307  7085 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-13 09:18:46.713  7086  7086 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 09:18:46.723  1035  1051 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7088 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-13 09:18:46.724  7087  7087 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 09:18:46.727  7026  7081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:46.735  7098  7098 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 09:18:46.746  7104  7104 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 09:18:46.761  7108  7108 I libmdmdetect: ESOC framework not supported
09-13 09:18:46.762  7108  7108 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-13 09:18:46.773  7108  7108 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 09:18:46.773  7108  7108 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 09:18:46.774  7108  7108 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 09:18:46.774  7108  7108 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 09:18:46.774  7108  7108 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 09:18:46.774  7108  7108 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 09:18:46.774  7108  7108 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-13 09:18:46.815  7088  7088 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 09:18:46.815  7088  7088 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 09:18:46.817  7088  7088 D PhoneMonitor: Register our PhoneStateListener
09-13 09:18:46.821  7108  7109 E QC-QMI  : qmi_client [7108] 14: failed to locate client data
09-13 09:18:46.822   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 09:18:46.822   468   468 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-13 09:18:46.831  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 09:18:46.833  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 09:18:46.858  7088  7088 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-13 09:18:46.859  7088  7088 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 09:18:46.860  7088  7088 D TelephonyAutoProfiling: [parse] Load xml
09-13 09:18:46.865  7088  7088 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 09:18:46.865  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 09:18:46.866  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 09:18:46.866  7088  7088 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-13 09:18:46.875  7088  7088 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-13 09:18:46.881  7112  7112 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 09:18:46.896  7113  7113 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 09:18:46.903  1035  1962 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7114 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 09:18:46.906  1035  1098 I ActivityManager: Killing 6007:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-13 09:18:46.920  3840  3913 I bt_vendor: bluetooth satus is on
09-13 09:18:46.920  3840  3913 D bt_hci_bdroid: preload
09-13 09:18:46.920  3840  7062 D bt_userial_mct: userial_open(port:0)
09-13 09:18:46.920  3840  7062 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 09:18:46.924  3840  7062 I bt_vendor: Done intiailizing UART
09-13 09:18:46.925  3840  7062 I bt_vendor: Done intiailizing UART
09-13 09:18:46.925  3840  7062 I bt_userial_mct: CMD=82, EVT=82, ACL_Out=83, ACL_In=83
,09-13 09:18:46.926  3840  7062 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 09:18:46.926  3840  7130 D bt_userial_mct: Entering userial_read_thread()
09-13 09:18:46.926  3840  7060 I bt-btu  : btu_task received preload complete event
09-13 09:18:46.926  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 09:18:46.926  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 09:18:46.926  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 09:18:46.929  3840  7060 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 09:18:46.973  1035  1978 W libprocessgroup: failed to open /acct/uid_10080/pid_6007/cgroup.procs: No such file or directory
,09-13 09:18:46.988  3840  7060 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 09:18:46.988  3840  7060 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b5061 
09-13 09:18:46.988  3840  7060 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b5061 
,09-13 09:18:47.022  3840  3917 E bt-btif : Calling BTA_HhEnable
,09-13 09:18:47.022  3840  3917 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 09:18:47.022  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 09:18:47.022  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 09:18:47.022  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 09:18:47.023  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 09:18:47.023  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 09:18:47.023  3840  3917 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 09:18:47.024  3840  3917 D BluetoothAdapterProperties: Name is: G3
09-13 09:18:47.025  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 09:18:47.026  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 09:18:47.027  3840  3917 D BluetoothAdapterProperties: Scan Mode:20
09-13 09:18:47.027  3840  3917 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 09:18:47.027  3840  3917 D bt_hci_bdroid: postload
09-13 09:18:47.028  3840  7062 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:47.029  3840  7062 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:47.029  3840  7060 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 09:18:47.030  3840  3917 D bte_conf: Device ID record 1 : primary
09-13 09:18:47.030  3840  3917 D bte_conf:   vendorId            = 00c4
09-13 09:18:47.030  3840  3917 D bte_conf:   vendorIdSource      = 0001
09-13 09:18:47.030  3840  3917 D bte_conf:   product             = 13a1
09-13 09:18:47.030  3840  3917 D bte_conf:   version             = 1000
09-13 09:18:47.030  3840  3917 D bte_conf:   clientExecutableURL = 
09-13 09:18:47.030  3840  3917 D bte_conf:   serviceDescription  = 
09-13 09:18:47.030  3840  3917 D bte_conf:   documentationURL    = 
09-13 09:18:47.030  3840  3917 D bte_conf: bte_load_did_conf no section named DID2.
09-13 09:18:47.031  3840  7062 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:47.031  3840  7062 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:47.031  1802  7133 I CheckinService: active receiver: enabled
09-13 09:18:47.032  3840  7062 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:47.033  3840  7062 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:47.035  3840  7130 E bt_mct  : hci lib postload completed
09-13 09:18:47.035  3840  3917 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 09:18:47.035  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 09:18:47.035  3840  3913 D BluetoothAdapterProperties: ScanMode =  20
,09-13 09:18:47.035  3840  3913 D BluetoothAdapterProperties: State =  11
09-13 09:18:47.035  3840  3913 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 09:18:47.036  3840  3913 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 09:18:47.036  3840  3913 D BluetoothAdapterProperties: Setting state to 12
09-13 09:18:47.036  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 09:18:47.036  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:47.036  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 09:18:47.036  3840  3917 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 09:18:47.036  3840  3913 I BluetoothAdapterState: Entering On State
09-13 09:18:47.037  3840  3913 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 09:18:47.037  3840  3913 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 09:18:47.037  3840  3913 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 09:18:47.037  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 09:18:47.038  6787  6803 D BluetoothMap: onBluetoothStateChange: up=true
09-13 09:18:47.029  7135  7135 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:47.029  7135  7135 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:47.042  3840  7060 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 09:18:47.042  3840  7060 W bt-smp  : Plain text(LSB ~ MSB) = 69 89 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 09:18:47.042  3840  7060 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d dd 61 9f 57 0c 02 34 5c e7 7c 44 5c 5f a8 65 
09-13 09:18:47.042  3840  7060 W bt-btm  : Stopping oneshot timer
09-13 09:18:47.056  3840  7060 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 09:18:47.056  3840  7060 W bt-smp  : Plain text(LSB ~ MSB) = 40 b7 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 09:18:47.056  3840  7060 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 59 c3 ab b8 ec b2 7d ca 59 9c 6d 11 dc 07 7a 
09-13 09:18:47.056  3840  7060 W bt-btm  : Stopping oneshot timer
,09-13 09:18:47.063   307  7085 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-13 09:18:47.067  3840  3913 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 09:18:47.070  3840  7060 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 09:18:47.070  3840  7060 W bt-smp  : Plain text(LSB ~ MSB) = e9 7d 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 09:18:47.070  3840  7060 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 6e 83 94 d3 a2 7a 7d 3e 37 78 75 ed 78 fc 1a 
09-13 09:18:47.070  3840  7060 W bt-btm  : Stopping oneshot timer
09-13 09:18:47.071  3840  3917 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 09:18:47.071  3840  3917 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.071  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:18:47.076  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:47.077  6787  6803 D BluetoothPan: onBluetoothStateChange on: true
09-13 09:18:47.078  6787  6803 D BluetoothPan: onBluetoothStateChange call bindService
09-13 09:18:47.078  1035  1035 D BluetoothHeadset: Proxy object connected
09-13 09:18:47.078  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.079  3840  7060 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 09:18:47.079  3840  7060 W bt-smp  : Plain text(LSB ~ MSB) = bc 95 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 09:18:47.080  3840  7060 W bt-smp  : Encrypted text(LSB ~ MSB) = 99 7d 9b 1f 42 1c 3b 56 d8 ef 83 98 e0 22 95 5c 
09-13 09:18:47.080  3840  7060 W bt-btm  : Stopping oneshot timer
09-13 09:18:47.080  6787  6787 D BluetoothMap: Proxy object connected
09-13 09:18:47.080  6787  6787 D MapProfile: Bluetooth service connected
09-13 09:18:47.080  6787  6787 D BluetoothMap: getConnectedDevices()
09-13 09:18:47.083  3840  6730 V BluetoothMapService: getConnectedDevices()
09-13 09:18:47.086  6787  6802 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 09:18:47.086  1802  7133 I CheckinService: Preparing to send checkin request
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.087  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:47.087  3840  3913 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 09:18:47.089  3840  7060 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 09:18:47.089  3840  7060 W bt-smp  : Plain text(LSB ~ MSB) = fd 38 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 09:18:47.089  3840  7060 W bt-smp  : Encrypted text(LSB ~ MSB) = 68 f1 a8 f1 f3 76 83 76 93 14 90 52 f6 63 4a 53 
09-13 09:18:47.089  3840  7060 W bt-btm  : Stopping oneshot timer
09-13 09:18:47.089  6787  6787 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 09:18:47.089  6787  6787 D PanProfile: Bluetooth service connected
09-13 09:18:47.091  1837  3943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:47.094  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.094  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 09:18:47.096  1837  2433 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:47.096  1802  7133 I EventLogService: Accumulating logs since 1473750990452
09-13 09:18:47.096  6787  6787 D BluetoothInputDevice: Proxy object connected
09-13 09:18:47.096  6787  6787 D HidProfile: Bluetooth service connected
09-13 09:18:47.098  1837  1837 D BluetoothHeadset: Proxy object connected
,09-13 09:18:47.099  1837  3940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:47.101  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 09:18:47.102  6787  6802 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.102  6667  6946 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.106  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:47.107  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 09:18:47.109  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 09:18:47.109  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 09:18:47.111  6830  7078 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 09:18:47.112  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 09:18:47.113  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.113  1927  2110 D LGBluetoothAPIService: Message: 1
09-13 09:18:47.113  1927  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 09:18:47.114  7143  7143 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 09:18:47.114  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 09:18:47.118  6830  7078 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 09:18:47.119  6667  6946 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.120  1927  2110 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 09:18:47.121  6787  6787 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 09:18:47.122  3840  3840 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.122  3840  3840 D BluetoothMapService: STATE_ON
09-13 09:18:47.122  3840  3840 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 09:18:47.122  3840  3840 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 09:18:47.123  3840  3840 V BluetoothMapService: Handler(): got msg=1
09-13 09:18:47.124  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:18:47.127  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 09:18:47.128  3840  3840 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 09:18:47.129  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:47.129  3840  3840 V BluetoothPbapService: Pbap Service onCreate
09-13 09:18:47.129  3840  3840 V BluetoothPbapService: Starting PBAP service
09-13 09:18:47.129  1927  2110 D LGBluetoothAPIService: Message: 100
09-13 09:18:47.129  1927  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 09:18:47.130  3840  7145 D BluetoothMapMasInstance: MAS initSocket()
09-13 09:18:47.130  3840  7145 D BluetoothMapMasInstance:   masId = 00
09-13 09:18:47.130  3840  7145 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 09:18:47.130  3840  7145 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 09:18:47.130  3840  7145 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 09:18:47.133  3840  3840 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 09:18:47.133  3840  3840 V BluetoothPbapService: Pbap Service onBind
09-13 09:18:47.133  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:47.134  3840  7145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:47.135  3840  7145 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=87 mFd=83
09-13 09:18:47.135  3840  7145 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 09:18:47.135  3840  7145 D BluetoothMapMasInstance: Accepting socket connection...
09-13 09:18:47.137  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.137  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:47.137  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:18:47.152  6667  6667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 09:18:47.157  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:47.158  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.159  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.225  1035  1693 I art     : Explicit concurrent mark sweep GC freed 115005(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.162ms total 102.433ms
09-13 09:18:47.226  1035  1048 I art     : WaitForGcToComplete blocked for 40.836ms for cause HeapTrim
09-13 09:18:47.226  3840  3840 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.226  3840  3840 V BluetoothPbapService: state: 12
09-13 09:18:47.226  1035  1117 D BluetoothManagerService: Message: 30
09-13 09:18:47.226  3840  3840 V BluetoothPbapService: Handler(): got msg=1
09-13 09:18:47.226  3840  3840 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 09:18:47.228  3840  7147 V BluetoothPbapService: Pbap Service initSocket
09-13 09:18:47.229  1035  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 09:18:47.233  1802  7133 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-13 09:18:47.233  3840  3917 D BluetoothAdapterProperties: Scan Mode:21
09-13 09:18:47.234  3840  3917 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 09:18:47.234  3840  7147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:47.234  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.235  3840  7147 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=89 mFd=87
09-13 09:18:47.235  3840  7147 V BluetoothPbapService: Succeed to create listening socket 
09-13 09:18:47.235  3840  7147 V BluetoothPbapService: Accepting socket connection...
09-13 09:18:47.236  6787  6787 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 09:18:47.238  1035  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:47.238  1035  2010 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
09-13 09:18:47.239  1035  1117 D BluetoothManagerService: Message: 30
09-13 09:18:47.239  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.241  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:47.244  6787  6787 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 09:18:47.245  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 09:18:47.247  6787  6787 D BluetoothPbap: Proxy object connected
09-13 09:18:47.248  6787  6787 D PbapServerProfile: Bluetooth service connected
09-13 09:18:47.249  6787  6787 D BluetoothA2dp: Proxy object connected
09-13 09:18:47.250  6787  6787 D A2dpProfile: Bluetooth service connected
,09-13 09:18:47.258  1035  1117 D BluetoothManagerService: Message: 2
09-13 09:18:47.258  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:47.258  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:47.258  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 09:18:47.258  1035  1117 D BluetoothManagerService: Sending off request.
09-13 09:18:47.259  3840  7139 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 09:18:47.259  3840  3913 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 09:18:47.259  3840  3913 D BluetoothAdapterProperties: Setting state to 13
09-13 09:18:47.259  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 09:18:47.259  3840  3913 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 09:18:47.260  3840  3913 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 09:18:47.261  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:47.261  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 09:18:47.261  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-13 09:18:47.297  1035  1908 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7151 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-13 09:18:47.300  1035  1908 I ActivityManager: Killing 6491:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-13 09:18:47.416  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:47.416  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-13 09:18:47.416  3840  3840 V BluetoothPbapReceiver: ***********state = 12
09-13 09:18:47.417  1035  1890 W libprocessgroup: failed to open /acct/uid_10061/pid_6491/cgroup.procs: No such file or directory
09-13 09:18:47.418  3840  3917 D BluetoothAdapterProperties: Scan Mode:20
,09-13 09:18:47.419  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 09:18:47.423  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 09:18:47.425  3840  7147 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:18:47.425  3840  7060 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 09:18:47.426  3840  3913 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 09:18:47.427  3840  7145 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 09:18:47.431  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:47.431  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:47.431  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 09:18:47.432  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 09:18:47.432  3840  7060 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 09:18:47.437  6787  6787 D BluetoothHeadset: Proxy object connected
,09-13 09:18:47.440  6787  6787 D HeadsetProfile: Bluetooth service connected
09-13 09:18:47.441  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.444  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 09:18:47.446  3840  3840 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.446  3840  3840 D BluetoothMapService: STATE_TURNING_OFF
09-13 09:18:47.446  3840  3840 V BluetoothMapService: Handler(): got msg=4
09-13 09:18:47.446  3840  3840 D BluetoothMapService: MAP Service closeService in
09-13 09:18:47.446  3840  3840 D BluetoothMapMasInstance: MAP Service shutdown
09-13 09:18:47.446  3840  3840 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 09:18:47.446  3840  3840 V BluetoothMapService: MAP Service closeService out
09-13 09:18:47.447  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:18:47.448  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.448  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:47.448  2214  2214 D c       : Getting all permits...
09-13 09:18:47.448  2214  2214 D a       : Opening database...
09-13 09:18:47.450  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:47.450  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:18:47.453  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:47.453  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:47.453  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.455  2214  2214 D a       : Opening database auth.proximity.permit_store...
09-13 09:18:47.456  2214  2214 D a       : Closing database...
09-13 09:18:47.456  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:47.457  6667  6667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:47.457  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.459  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.461  6787  6787 D DockEventReceiver: finishStartingService: stopping service
09-13 09:18:47.463  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:47.465  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.465  6787  6787 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-13 09:18:47.471  6787  6787 D BluetoothPermissionRequest: onReceive
09-13 09:18:47.472  6787  6787 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 09:18:47.474  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 09:18:47.476  1035  2010 I ActivityManager: Killing 6027:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-13 09:18:47.496  1035  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:47.496  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:47.496  1035  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:47.520  3840  3840 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-13 09:18:47.520  1035  2019 W libprocessgroup: failed to open /acct/uid_10097/pid_6027/cgroup.procs: No such file or directory
09-13 09:18:47.521  3840  3840 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-13 09:18:47.546  1035  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 09:18:47.546  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 09:18:47.547  1035  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 09:18:47.547  1035  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 09:18:47.548  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 09:18:47.549  1035  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 09:18:47.601  1035  2010 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7169 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 09:18:47.603  1035  2010 I ActivityManager: Killing 6525:com.lge.eula/1000 (adj 15): empty #17
09-13 09:18:47.660  3840  3840 V BtOppService: onCreate
09-13 09:18:47.660  3840  3840 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-13 09:18:47.661  1035  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_6525/cgroup.procs: No such file or directory
,09-13 09:18:47.661  3840  3840 V BluetoothOppNotification: send message
09-13 09:18:47.673  3840  7186 V BtOppService: Deleted complete outbound shares, number =  0
09-13 09:18:47.674  3840  3840 D BluetoothOppPreference: Dumping Names:  
09-13 09:18:47.674  3840  3840 D BluetoothOppPreference: {}
09-13 09:18:47.674  3840  3840 D BluetoothOppPreference: Dumping Channels:  
09-13 09:18:47.674  3840  3840 D BluetoothOppPreference: {}
09-13 09:18:47.674  3840  3840 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 09:18:47.675  3840  3840 V BtOppService: onStartCommand
,09-13 09:18:47.676  3840  7186 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 09:18:47.676  3840  7186 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 09:18:47.678  3840  3840 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 09:18:47.679  3840  7186 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1dd25ce8 on behalf of 
09-13 09:18:47.679  3840  3840 V BluetoothOppNotification: previous thread is not finished yet
,09-13 09:18:47.688  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.689  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 09:18:47.692  3840  3840 V BtOppService: ContentObserver received notification
09-13 09:18:47.692  3840  3840 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 09:18:47.693  3840  3840 V BtOppService: ContentObserver received notification
09-13 09:18:47.693  3840  3840 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 09:18:47.694  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:47.694  3840  3840 V BluetoothFtpService: Ftp Service onCreate
09-13 09:18:47.694  3840  3840 I BluetoothFtpService: Ftp Service onCreate
09-13 09:18:47.695  3840  3840 V BluetoothFtpService: Ftp Service onStartCommand
09-13 09:18:47.695  3840  3840 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 09:18:47.695  3840  3840 V BluetoothFtpService: Starting Listening on sockets
09-13 09:18:47.695  3840  3840 V BluetoothFtpService: Handler(): got msg=1
09-13 09:18:47.696  3840  3840 V BluetoothFtpService: Ftp Service closeService
09-13 09:18:47.699  3840  3840 V BluetoothFtpService: successfully stopped ftp service
09-13 09:18:47.700  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 09:18:47.700  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:47.700  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:47.700  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.700  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 09:18:47.700  3840  3840 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 09:18:47.705  3840  3840 V BluetoothFtpService: Ftp Service onDestroy
09-13 09:18:47.705  3840  3840 V BluetoothFtpService: Ftp Service closeService
09-13 09:18:47.710  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:47.710  3840  3840 V BluetoothSapService: Sap Service onCreate
09-13 09:18:47.715  3840  3840 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.715  3840  3840 V BluetoothSapService: state: 12
09-13 09:18:47.715  3840  3840 V BluetoothSapService: Starting SAP server process
,09-13 09:18:47.717  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 09:18:47.699  7187  7187 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 09:18:47.709  7187  7187 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:47.719  7169  7169 I art     : Almond Protected OAT
09-13 09:18:47.724  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:47.724  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.724  3840  3840 V BluetoothPbapReceiver: ***********state = 13
09-13 09:18:47.724  6787  6787 D DockEventReceiver: finishStartingService: stopping service
09-13 09:18:47.726  3840  3840 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 09:18:47.727  3840  3840 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.727  3840  3840 V BluetoothPbapService: state: 13
09-13 09:18:47.727  3840  3840 V BluetoothPbapService: Pbap Service closeService in
09-13 09:18:47.728  6787  6787 D BluetoothPbap: Proxy object disconnected
09-13 09:18:47.728  6787  6787 D PbapServerProfile: Bluetooth service disconnected
09-13 09:18:47.729  3840  3840 V BluetoothPbapService: successfully stopped pbap service
09-13 09:18:47.729  3840  3840 V BluetoothPbapService: Pbap Service closeService out
09-13 09:18:47.729  3840  3840 V BluetoothPbapService: Pbap Service onDestroy
09-13 09:18:47.729  3840  3840 V BluetoothPbapService: Pbap Service closeService in
09-13 09:18:47.729  3840  3840 V BluetoothPbapService: Pbap Service closeService out
09-13 09:18:47.729  3840  3840 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 09:18:47.730  7187  7187 V BT_SAP  : Event pipe created
09-13 09:18:47.730  7187  7187 V BT_SAP  : create_server_socket qcom.sap.server
09-13 09:18:47.730  7187  7187 V BT_SAP  : created socket fd 6
,09-13 09:18:47.733  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:18:47.761  6667  7148 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:47.761  6667  7148 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:18:47.761  6667  7148 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 09:18:47.761  6667  7148 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:47.764  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:47.799  1035  1943 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7190 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-13 09:18:47.801  1035  1614 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:47.801  1035  1614 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
,09-13 09:18:47.803  7169  7169 D WeatherApplication: removeAccount
09-13 09:18:47.803  6787  6787 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 09:18:47.804  7169  7169 D WeatherApplication: Account.length = 0
09-13 09:18:47.804  7169  7169 E WeatherApplication: OPERATOR:OPEN
09-13 09:18:47.808  6787  6787 D BluetoothPermissionRequest: onReceive
09-13 09:18:47.808  6787  6787 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 09:18:47.809  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:47
09-13 09:18:47.812  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 09:18:47.812  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
09-13 09:18:47.815  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 09:18:47.816  1035  1117 D BluetoothManagerService: Message: 1
09-13 09:18:47.816  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b
09-13 09:18:47.817  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:47.817  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:47.817  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 09:18:47.818  3840  3857 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 09:18:47.819  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 09:18:47.819  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 09:18:47.823  7169  7169 D WeatherAncestor: connectivity changed - connection : true
09-13 09:18:47.824  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-13 09:18:47.826  3840  3840 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 09:18:47.826  3840  3840 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 09:18:47.827  3840  3840 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 09:18:47.831  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 09:18:47.831  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 09:18:47.832  7169  7169 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-13 09:18:47.832  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.832  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 09:18:47.834  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:47.834  3840  3840 V BluetoothFtpService: Ftp Service onCreate
09-13 09:18:47.835  3840  3840 I BluetoothFtpService: Ftp Service onCreate
09-13 09:18:47.835  3840  3840 V BluetoothFtpService: Ftp Service onStartCommand
09-13 09:18:47.835  3840  3840 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.835  3840  3840 V BluetoothFtpService: Ftp Service closeService
09-13 09:18:47.836  3840  3840 V BluetoothFtpService: successfully stopped ftp service
,09-13 09:18:47.837  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 09:18:47.837  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:47.837  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:47.837  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.837  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 09:18:47.837  3840  3840 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 09:18:47.838  3840  3840 V BluetoothFtpService: Ftp Service onDestroy
09-13 09:18:47.838  3840  3840 V BluetoothFtpService: Ftp Service closeService
09-13 09:18:47.840  3840  3840 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:47.840  3840  3840 V BluetoothSapService: state: 13
09-13 09:18:47.840  3840  3840 V BluetoothSapService: Stopping SAP server process
09-13 09:18:47.842  3840  3840 V BluetoothSapService: Sap Service closeSapService in
09-13 09:18:47.842  3840  3840 V BluetoothSapService: Close listen Socket : 
09-13 09:18:47.842  3840  3840 V BluetoothSapService: Close rfcomm Socket : 
09-13 09:18:47.842  3840  3840 V BluetoothSapService: Close sapd  Socket : 
09-13 09:18:47.842  3840  3840 V BluetoothSapService: Sap Service closeSapService out
09-13 09:18:47.842  3840  3840 V BluetoothSapService: Sap Service onDestroy
09-13 09:18:47.842  3840  3840 V BluetoothSapService: Sap Service closeSapService in
09-13 09:18:47.843  3840  3840 V BluetoothSapService: Close listen Socket : 
09-13 09:18:47.843  3840  3840 V BluetoothSapService: Close rfcomm Socket : 
09-13 09:18:47.843  3840  3840 V BluetoothSapService: Close sapd  Socket : 
09-13 09:18:47.843  3840  3840 V BluetoothSapService: Sap Service closeSapService out
09-13 09:18:47.854  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 09:18:47.855  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:47
,09-13 09:18:47.866  7190  7190 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 09:18:47.867  7190  7190 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 09:18:47.895  1035  1614 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7209 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 09:18:47.895  7190  7190 I MultiDex: VM with version 2.1.0 has multidex support
09-13 09:18:47.896  1035  1614 I ActivityManager: Killing 2113:com.lge.music/u0a34 (adj 15): empty #17
09-13 09:18:47.896  7190  7190 I MultiDex: install
09-13 09:18:47.896  7190  7190 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 09:18:47.916   312   312 V AudioFlinger: 2113 died, releasing its sessions
09-13 09:18:47.916   312   312 V AudioFlinger:  pid 1837 @ 0
,09-13 09:18:47.916   312   312 V AudioFlinger:  pid 3440 @ 1
09-13 09:18:47.916   312   312 V AudioFlinger:  pid 3440 @ 2
09-13 09:18:47.919  1035  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=54.0, 0.0, 0.0  rx=61.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:577345391] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:47.920  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=54.0, 0.0, 0.0  rx=61.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:577345392] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:47.920  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 09:18:47.930  1035  1051 W libprocessgroup: failed to open /acct/uid_10034/pid_2113/cgroup.procs: No such file or directory
,09-13 09:18:47.938  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:47.940  7190  7190 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-13 09:18:47.978  1035  1525 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-13 09:18:48.020  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:48.022  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:48.023  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 09:18:48.026  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:48.030  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.031  5652  5652 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 09:18:48.032  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.034  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:48.058   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 09:18:48.058   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 09:18:48.058   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 09:18:48.060  7209  7228 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 09:18:48.061   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 09:18:48.061   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 09:18:48.061   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 09:18:48.061  7209  7228 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-13 09:18:48.066   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 09:18:48.066   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 09:18:48.066   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 09:18:48.066  7209  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-13 09:18:48.068   278   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 09:18:48.068   278   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 09:18:48.068   278   433 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 09:18:48.068  7209  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 09:18:48.258  7190  7207 D LgDataFeature: LgDataFeature() Constructor: none
09-13 09:18:48.258  7190  7207 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 09:18:48.316  7209  7209 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 09:18:48.318  1035  1614 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:48.318  1035  1614 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
09-13 09:18:48.319  1035  1117 D BluetoothManagerService: Message: 1
09-13 09:18:48.319  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b
09-13 09:18:48.320  3840  7139 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 09:18:48.320  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 09:18:48.326  7209  7209 I LibraryLoader: Loading: webviewchromium
09-13 09:18:48.330  7209  7209 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5027-5031)
09-13 09:18:48.330  7209  7209 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 09:18:48.338  7209  7209 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {365245c8}
,09-13 09:18:48.339  7209  7209 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 09:18:48.340  7209  7209 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 09:18:48.351  7209  7209 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 09:18:48.352  7209  7209 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 09:18:48.368  7209  7209 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-13 09:18:48.370  7209  7209 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 09:18:48.370  7209  7209 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-13 09:18:48.382  7209  7209 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 09:18:48.382  7209  7209 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 09:18:48.382  7209  7209 I Adreno-EGL: Build Date: 12/12/14 금
09-13 09:18:48.382  7209  7209 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 09:18:48.382  7209  7209 I Adreno-EGL: Remote Branch: 
09-13 09:18:48.382  7209  7209 I Adreno-EGL: Local Patches: 
09-13 09:18:48.382  7209  7209 I Adreno-EGL: Reconstruct Branch: 
09-13 09:18:48.391   312  1371 V AudioPolicyService: registerClient() client 0xb100f0e0, uid 10093
,09-13 09:18:48.396  7209  7252 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 09:18:48.437  3840  7060 W bt-btif : ag scb idx 1 not allocated
09-13 09:18:48.437  3840  3917 D bt_hci_bdroid: cleanup
09-13 09:18:48.437  3840  7060 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:48.437  3840  7062 I bt_lpm  : LPM is already off!!!
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:48.437  3840  7130 I bt_userial_mct: exiting userial_read_thread
09-13 09:18:48.437  3840  7130 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 09:18:48.437  3840  3917 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 09:18:48.437  3840  7060 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 09:18:48.437  3840  7062 I bt_vendor: hw_epilog_process
09-13 09:18:48.437  3840  7060 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 09:18:48.437  3840  3917 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 09:18:48.437  3840  3917 D bt_userial_mct: userial_close
09-13 09:18:48.437  3840  3917 E bt_userial_mct: pthread_join() FAILED result:3
09-13 09:18:48.437  3840  3917 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-13 09:18:48.466  7209  7209 I NSApplication: Starting up...
,09-13 09:18:48.497  7265  7265 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 09:18:48.549  1035  2010 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7272 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-13 09:18:48.550  1035  2010 I ActivityManager: Killing 5963:com.android.vending/u0a44 (adj 15): empty #17
,09-13 09:18:48.576  7265  7265 I dex2oat : dex2oat took 78.363ms (threads: 4)
,09-13 09:18:48.589  3840  3917 D bt_hci_bdroid: set_power 0
09-13 09:18:48.589  3840  3917 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 09:18:48.589  3840  3917 I bt_vendor: bluetooth satus is on
09-13 09:18:48.589  3840  3917 I bt_vendor: bt-vendor : resetting BT status
09-13 09:18:48.589  3840  3917 I bt_vendor: Starting hciattach daemon
09-13 09:18:48.589  3840  3917 I bt_vendor: try to set false
09-13 09:18:48.589  3840  3917 I bt_vendor: Starting hciattach daemon
09-13 09:18:48.589  3840  3917 I bt_vendor: try to set false
09-13 09:18:48.590  3840  3917 I bt_vendor: cleanup
09-13 09:18:48.591  3840  7060 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-13 09:18:48.591  3840  3917 I GKI_LINUX: GKI_exit_task 0 done
09-13 09:18:48.591  3840  3917 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 09:18:48.592  7190  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 09:18:48.592  7190  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 09:18:48.592  7190  7207 I Adreno-EGL: Build Date: 12/12/14 금
09-13 09:18:48.592  7190  7207 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 09:18:48.592  7190  7207 I Adreno-EGL: Remote Branch: 
09-13 09:18:48.592  7190  7207 I Adreno-EGL: Local Patches: 
09-13 09:18:48.592  7190  7207 I Adreno-EGL: Reconstruct Branch: 
09-13 09:18:48.592  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 09:18:48.664  1035  1050 W libprocessgroup: failed to open /acct/uid_10044/pid_5963/cgroup.procs: No such file or directory
,09-13 09:18:48.679  3840  3840 D HeadsetService: Received stop request...Stopping profile...
09-13 09:18:48.685  3840  3840 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 09:18:48.685  3840  3840 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 09:18:48.685  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.686  3840  7035 D HeadsetStateMachine: Exit Disconnected: -1
,09-13 09:18:48.690  1035  1035 D BluetoothHeadset: Proxy object disconnected
,09-13 09:18:48.690  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-13 09:18:48.691  1837  1837 D BluetoothHeadset: Proxy object disconnected
,09-13 09:18:48.691  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 09:18:48.691  1837  1837 D BluetoothHeadset: Proxy object disconnected
09-13 09:18:48.692  3840  3840 D A2dpService: Received stop request...Stopping profile...
09-13 09:18:48.692  3840  7050 D A2dpStateMachine: Exit Disconnected: -1
09-13 09:18:48.693  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 09:18:48.694  3840  3840 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 09:18:48.695  3840  3840 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 09:18:48.695  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.696  3840  3840 V BluetoothOppNotification: previous thread is not finished yet
09-13 09:18:48.696  6787  6787 D BluetoothHeadset: Proxy object disconnected
09-13 09:18:48.696  6787  6787 D HeadsetProfile: Bluetooth service disconnected
09-13 09:18:48.697  3840  3840 D HidService: Received stop request...Stopping profile...
09-13 09:18:48.697  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.698  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 09:18:48.698  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 09:18:48.699  3840  3913 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 09:18:48.699  6787  6787 D BluetoothA2dp: Proxy object disconnected
09-13 09:18:48.699  6787  6787 D A2dpProfile: Bluetooth service disconnected
09-13 09:18:48.699  6787  6787 D BluetoothInputDevice: Proxy object disconnected
09-13 09:18:48.699  6787  6787 D HidProfile: Bluetooth service disconnected
09-13 09:18:48.701  3840  3840 D HealthService: Received stop request...Stopping profile...
09-13 09:18:48.701  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
,09-13 09:18:48.704  3840  3840 D HeadsetStateMachine: Unbinding service...
09-13 09:18:48.705  3840  3840 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 09:18:48.705  3840  3840 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 09:18:48.705  3840  3840 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 09:18:48.706  3840  3840 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 09:18:48.706  3840  3840 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 09:18:48.706  3840  3840 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 09:18:48.706  3840  3840 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 09:18:48.706  3840  3840 D PanService: Received stop request...Stopping profile...
09-13 09:18:48.707  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.708  3840  3840 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 09:18:48.708  3840  3840 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 09:18:48.708  3840  3840 D BtGatt.GattService: stop()
09-13 09:18:48.708  3840  3840 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 09:18:48.709  6787  6787 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 09:18:48.709  6787  6787 D PanProfile: Bluetooth service disconnected
09-13 09:18:48.709  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.710  3840  3840 I BluetoothA2dpServiceJni: cleanupNative
09-13 09:18:48.711  3840  7051 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 09:18:48.711  3840  3840 I GKI_LINUX: GKI_exit_task 2 done
09-13 09:18:48.711  3840  3840 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 09:18:48.711  3840  3840 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 09:18:48.711  3840  3840 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 09:18:48.713  3840  3840 D BluetoothMapService: Received stop request...Stopping profile...
09-13 09:18:48.713  3840  3840 D BluetoothMapService: stop()
09-13 09:18:48.713  3840  3840 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 09:18:48.713  3840  3840 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 09:18:48.714  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
,09-13 09:18:48.715  3840  3840 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 09:18:48.715  3840  3840 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 09:18:48.715  3840  3840 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 09:18:48.715  3840  3840 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 09:18:48.715  3840  3840 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 09:18:48.719  3840  3840 V BluetoothMapService: Handler(): got msg=4
09-13 09:18:48.719  3840  3840 D BluetoothMapService: MAP Service closeService in
09-13 09:18:48.719  3840  3840 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 09:18:48.719  3840  3840 V BluetoothMapService: MAP Service closeService out
09-13 09:18:48.719  6787  6787 D BluetoothMap: Proxy object disconnected
09-13 09:18:48.720  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 09:18:48.720  3840  3913 D BluetoothAdapterProperties: Setting state to 10
09-13 09:18:48.720  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 09:18:48.720  3840  3840 D BluetoothMapService: cleanup()
09-13 09:18:48.720  3840  3840 D BluetoothMapService: MAP Service closeService in
09-13 09:18:48.720  3840  3840 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 09:18:48.720  3840  3840 V BluetoothMapService: MAP Service closeService out
09-13 09:18:48.720  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:48.720  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 09:18:48.720  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-13 09:18:48.721  3840  3913 I BluetoothAdapterState: Entering OffState
09-13 09:18:48.721  6787  6802 D BluetoothMap: onBluetoothStateChange: up=false
09-13 09:18:48.721  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:48.722  6787  6803 D BluetoothPan: onBluetoothStateChange on: false
09-13 09:18:48.722  6787  7140 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 09:18:48.723  1837  2433 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 09:18:48.724  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:48.724  6787  6787 D MapProfile: Bluetooth service disconnected
09-13 09:18:48.724  1837  3940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:48.725  6787  6802 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 09:18:48.725  6787  6803 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 09:18:48.726  6787  7140 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 09:18:48.726  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 09:18:48.726  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 09:18:48.729  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:48.729  1927  2110 D LGBluetoothAPIService: Message: 2
09-13 09:18:48.729  1927  2110 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3a61a6ce mBinding = false
09-13 09:18:48.729  1927  2110 D LGBluetoothAPIService: Sending unbind request.
09-13 09:18:48.729  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 09:18:48.733  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.735  6787  6787 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 09:18:48.735  6787  6787 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 09:18:48.735  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.737  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.738  3840  3840 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 09:18:48.738  3840  3840 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-13 09:18:48.738  3840  3840 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 09:18:48.740  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 09:18:48.745  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:48.745  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:48.745  3840  3840 V BluetoothPbapReceiver: ***********state = 10
09-13 09:18:48.747  6787  6787 D DockEventReceiver: finishStartingService: stopping service
09-13 09:18:48.749  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:18:48.752  7272  7272 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 09:18:48.767  6787  6787 D BluetoothPermissionRequest: onReceive
,09-13 09:18:48.768  7190  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 09:18:48.768  7190  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 09:18:48.768  7190  7207 I Adreno-EGL: Build Date: 12/12/14 금
09-13 09:18:48.768  7190  7207 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 09:18:48.768  7190  7207 I Adreno-EGL: Remote Branch: 
09-13 09:18:48.768  7190  7207 I Adreno-EGL: Local Patches: 
09-13 09:18:48.768  7190  7207 I Adreno-EGL: Reconstruct Branch: 
09-13 09:18:48.768  6787  6787 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 09:18:48.768  6787  6787 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 09:18:48.770  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 09:18:48.778  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:48.779  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 09:18:48.779  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:48.779  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:48.779  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:48.780  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-13 09:18:48.782  6923  6923 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 09:18:48.820  1035  1866 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:48.820  1035  1866 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@3705379b mBinding = false
09-13 09:18:48.821  1035  1117 D BluetoothManagerService: Message: 1
09-13 09:18:48.821  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3705379b
,09-13 09:18:48.822  3840  3913 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 09:18:48.822  3840  3913 D BluetoothAdapterProperties: Setting state to 11
09-13 09:18:48.822  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 09:18:48.823  3840  3913 D BluetoothBondStateMachine: make
09-13 09:18:48.823  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:48.823  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 09:18:48.824  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 09:18:48.825  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:48.825  3840  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.825  3840  3913 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 09:18:48.825  3840  3913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.825  3840  3913 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 09:18:48.825  3840  3913 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 09:18:48.825  3840  7293 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 09:18:48.826  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 09:18:48.827  6787  6787 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 09:18:48.827  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:48.828  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.829  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.831  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:48.831  3840  3840 D HeadsetService: Received start request. Starting profile...
09-13 09:18:48.832  3840  3840 D HeadsetStateMachine: make
,09-13 09:18:48.835  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:48.836  3840  3840 D HeadsetStateMachine: max_hf_connections = 1
09-13 09:18:48.836  3840  3840 I bluedroid-qcom: get_profile_interface handsfree
09-13 09:18:48.836  3840  3840 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 09:18:48.836  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.836  3840  7294 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 09:18:48.836  3840  7294 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 09:18:48.836  3840  7294 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 09:18:48.836  3840  7294 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 09:18:48.836   312  2137 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3840
09-13 09:18:48.836   312  2137 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 09:18:48.836   312  2137 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 09:18:48.836   312  2137 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 09:18:48.836   312  2137 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 09:18:48.836   312  2137 V voice   : voice_set_parameters: exit with code(0)
09-13 09:18:48.837   312  2137 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 09:18:48.837   312  2137 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 09:18:48.837   312  2137 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 09:18:48.837   312  2137 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 09:18:48.837   312  2137 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 09:18:48.837   312  2137 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 09:18:48.838  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.838  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:48.838  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:48.838  3840  3840 V BluetoothPbapReceiver: ***********state = 11
09-13 09:18:48.839  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:48.839  3840  3840 D HeadsetStateMachine: Proxy object connected
09-13 09:18:48.839  3840  3840 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 09:18:48.839  3840  3840 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 09:18:48.841  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:18:48.842  3840  3840 D A2dpService: Received start request. Starting profile...
09-13 09:18:48.842  3840  3840 V Avrcp   : make
09-13 09:18:48.842  3840  3840 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 09:18:48.842  3840  3840 I bluedroid-qcom: get_profile_interface avrcp
09-13 09:18:48.843  7190  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 09:18:48.843  7190  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 09:18:48.843  7190  7207 I Adreno-EGL: Build Date: 12/12/14 금
09-13 09:18:48.843  7190  7207 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 09:18:48.843  7190  7207 I Adreno-EGL: Remote Branch: 
09-13 09:18:48.843  7190  7207 I Adreno-EGL: Local Patches: 
09-13 09:18:48.843  7190  7207 I Adreno-EGL: Reconstruct Branch: 
,09-13 09:18:48.846  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:48.847  3840  3840 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 09:18:48.849  3840  3840 E AudioManager: No RCC entry present to update
09-13 09:18:48.849  3840  3840 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 09:18:48.849  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 09:18:48.849  3840  3840 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 09:18:48.851  6787  6787 D BluetoothPermissionRequest: onReceive
09-13 09:18:48.854  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:48.857  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 09:18:48.893  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 09:18:48.894  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 09:18:48.897  3840  3913 E BluetoothAdapterService: File transfer profiles supported!!
09-13 09:18:48.901  3840  3913 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 09:18:48.917  1035  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=87004055, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,09-13 09:18:48.927   307  7299 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 09:18:48.927   307  7299 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-13 09:18:48.939  1035  1962 V SIM_STK : Menu title from STK is T-Mobile
,09-13 09:18:48.939  1035  1962 V SIM_STK : Menu title from STK is T-Mobile
09-13 09:18:48.969  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 09:18:48.970  6368  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 09:18:48.980  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:48.987  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 09:18:48.987  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:48.987  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 09:18:48.987  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 09:18:48.987  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 09:18:48.987  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 09:18:48.988  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 09:18:48.988  3840  3840 D A2dpStateMachine: make
09-13 09:18:48.988  6997  6997 I AppUp4:CustModeStarterReceiver: onReceive
09-13 09:18:48.988  3840  3840 I bluedroid-qcom: get_profile_interface a2dp
09-13 09:18:48.989  3840  7305 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 09:18:48.989  3840  3840 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 09:18:48.989  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.989  3840  7304 D A2dpStateMachine: Enter Disconnected: -2
09-13 09:18:48.991  6997  6997 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26d221b9
09-13 09:18:48.991  6997  6997 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 09:18:48.991  6997  6997 D AppUp4:CustFacade: isPhone : true
09-13 09:18:48.991  6997  6997 D AppUp4:CustModeStarterReceiver: begin check event
09-13 09:18:48.992  6997  6997 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 09:18:48.992  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:48.992  3840  7294 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 09:18:48.992  3840  7294 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 09:18:48.992  3840  7294 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-13 09:18:48.992  3840  3840 D HidService: Received start request. Starting profile...
09-13 09:18:48.992  3840  3840 I bluedroid-qcom: get_profile_interface hidhost
09-13 09:18:48.992  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
,09-13 09:18:48.993  3840  3840 D HealthService: Received start request. Starting profile...
09-13 09:18:48.993  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:48.993  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:48.994  3840  3840 I bluedroid-qcom: get_profile_interface health
09-13 09:18:48.994  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.994  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:48.995  3840  3840 D PanService: Received start request. Starting profile...
09-13 09:18:48.995  3840  3840 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 09:18:48.995  3840  3840 I bluedroid-qcom: get_profile_interface pan
09-13 09:18:48.995  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:48.995  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:48.996  3840  3840 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 09:18:48.996  3840  3840 D BtGatt.GattService: Received start request. Starting profile...
09-13 09:18:48.996  3840  3840 D BtGatt.GattService: start()
09-13 09:18:48.996  3840  3840 D BtGatt.AdvertiseManager: advertise manager created
09-13 09:18:48.998  2832  2832 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:48.999  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:49.000  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:49.000  3840  3840 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 09:18:49.000  3840  3840 V BluetoothMapService: BluetoothMapBinder()
09-13 09:18:49.000  3840  3840 D BluetoothMapService: Received start request. Starting profile...
09-13 09:18:49.000  3840  3840 D BluetoothMapService: start()
09-13 09:18:49.001  2832  2832 V DownloadManager: DownloadService onCreate
09-13 09:18:49.002   307  7299 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-13 09:18:49.002  3840  3840 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 09:18:49.002  3840  3840 D BluetoothMapEmailAppObserver: createReceiver()
09-13 09:18:49.003  3840  3840 D BluetoothMapEmailAppObserver: initObservers()
09-13 09:18:49.003  3840  3840 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 09:18:49.003  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
,09-13 09:18:49.005  4277  7312 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:49.005  2832  7314 I DownloadManager: in removeSpuriousFiles
09-13 09:18:49.007  2832  7314 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 09:18:49.008  4277  7316 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.008  4277  7316 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:49.008  2832  7314 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@bfc062f on behalf of 2832
09-13 09:18:49.008  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 09:18:49.008  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 09:18:49.008  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
,09-13 09:18:49.008  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 09:18:49.009  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 09:18:49.009  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 09:18:49.009  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 09:18:49.009  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 09:18:49.009  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 09:18:49.009  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 09:18:49.009  2832  7314 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 09:18:49.009  4277  7312 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 09:18:49.010  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:49.011  2832  2832 V DownloadManager: DownloadService onStartCommand
09-13 09:18:49.011  2832  7314 I DownloadManager: in trimDatabase
09-13 09:18:49.011  2832  7314 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 09:18:49.012  2832  7314 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39b20b1a on behalf of 2832
09-13 09:18:49.014  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:49.014  4277  7312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 09:18:49.015  2832  7315 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 09:18:49.016  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:49.016  2832  7315 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@4cd64b on behalf of 2832
,09-13 09:18:49.018  2832  7315 V DownloadManager: processing inserted download 1
09-13 09:18:49.018  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 09:18:49.018  3840  3840 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 09:18:49.019  2832  7315 V DownloadManager: processing inserted download 4
09-13 09:18:49.019  4277  4277 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 09:18:49.020  2832  7315 V DownloadManager: processing inserted download 7
09-13 09:18:49.021  2832  7315 V DownloadManager: processing inserted download 8
09-13 09:18:49.021  2832  7315 V DownloadManager: processing inserted download 9
09-13 09:18:49.022  2832  7315 V DownloadManager: processing inserted download 10
09-13 09:18:49.022  2832  7315 V DownloadManager: processing inserted download 11
09-13 09:18:49.023  2832  7315 V DownloadManager: processing inserted download 12
09-13 09:18:49.024  2832  7315 V DownloadManager: processing inserted download 13
09-13 09:18:49.024  2832  7315 V DownloadManager: processing inserted download 14
09-13 09:18:49.025  2832  7315 V DownloadManager: processing inserted download 16
09-13 09:18:49.026  4277  4277 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 09:18:49.026  4277  4277 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 09:18:49.027  4277  4277 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 09:18:49.030  3840  3840 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-13 09:18:49.031  4277  4277 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 09:18:49.032  7026  7320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.035  2832  2832 V DownloadManager: DownloadService onDestroy
09-13 09:18:49.035  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.035  3840  3840 V BluetoothMapService: Handler(): got msg=1
09-13 09:18:49.035  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 09:18:49.035  3840  3913 I bluedroid-qcom: enable
09-13 09:18:49.036  3840  3913 I bt_hci_bdroid: init
09-13 09:18:49.036  3840  3913 I bt_vendor: bt-vendor : init
09-13 09:18:49.036  3840  3913 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 09:18:49.036  3840  3913 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 09:18:49.036  3840  3913 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 09:18:49.037  3840  3913 D bt_userial_mct: userial_init
09-13 09:18:49.037  3840  7322 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 09:18:49.037  3840  7322 I bt-btu  : btu_task pending for preload complete event
09-13 09:18:49.037  3840  3913 D bt_hci_bdroid: set_power 1
09-13 09:18:49.037  3840  3913 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 09:18:49.037  3840  3913 I bt_vendor: Starting hciattach daemon
09-13 09:18:49.037  3840  3913 I bt_vendor: try to set true
09-13 09:18:49.038  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 09:18:49.038  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:49.038  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:49.038  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.038  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 09:18:49.019  7326  7326 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:49.019  7326  7326 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:49.050  7329  7329 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 09:18:49.053  3440  3440 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 09:18:49.053  3440  3440 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.053  3440  3440 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 09:18:49.055  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 09:18:49.055  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 09:18:49.067  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:49
09-13 09:18:49.068  2617  2617 D [Concierge]Service: onStartCommand(). Type : 9
,09-13 09:18:49.071  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-13 09:18:49.071  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
09-13 09:18:49.071  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 09:18:49.071  7169  7169 D WeatherAncestor: connectivity changed - connection : true
09-13 09:18:49.072  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3167355f
09-13 09:18:49.072  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 09:18:49.072  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 09:18:49.072  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 09:18:49.072  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 09:18:49.072  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:49
09-13 09:18:49.085  7336  7336 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 09:18:49.091  7337  7337 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 09:18:49.100  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-13 09:18:49.102  7339  7339 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 09:18:49.106  2214  2214 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-13 09:18:49.106  2214  2214 D c       : Getting all permits...
09-13 09:18:49.106  2214  2214 D a       : Opening database...
09-13 09:18:49.108  7340  7340 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 09:18:49.109  2214  2214 D a       : Opening database auth.proximity.permit_store...
09-13 09:18:49.109  2214  2214 D a       : Closing database...
09-13 09:18:49.114  7342  7342 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-13 09:18:49.116  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 09:18:49.117  6368  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 09:18:49.118  6830  7330 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 09:18:49.119  7344  7344 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 09:18:49.121  6830  7330 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 09:18:49.126  1802  7133 I CheckinTask: Sending checkin request (8012 bytes)
09-13 09:18:49.128  7346  7346 I libmdmdetect: ESOC framework not supported
09-13 09:18:49.129  7346  7346 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 09:18:49.133  7346  7346 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 09:18:49.133  7346  7346 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 09:18:49.133  7346  7346 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 09:18:49.133  7346  7346 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 09:18:49.133  7346  7346 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 09:18:49.133  7346  7346 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 09:18:49.133  7346  7346 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 09:18:49.139  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.145  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-13 09:18:49.145  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.145  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 09:18:49.145  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 09:18:49.146  6997  6997 I AppUp4:CustModeStarterReceiver: onReceive
09-13 09:18:49.148  6997  6997 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26d221b9
09-13 09:18:49.148  6997  6997 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 09:18:49.148  6997  6997 D AppUp4:CustFacade: isPhone : true
09-13 09:18:49.148  6997  6997 D AppUp4:CustModeStarterReceiver: begin check event
09-13 09:18:49.148  6997  6997 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 09:18:49.149  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.150  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:49.150  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:49.152  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:49.154  2832  2832 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.154  4277  7348 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:49.154  4277  7349 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.154  4277  7349 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:49.155  2832  2832 V DownloadManager: DownloadService onCreate
09-13 09:18:49.155  4277  7348 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-13 09:18:49.159  4277  7348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 09:18:49.161  2832  7350 I DownloadManager: in removeSpuriousFiles
09-13 09:18:49.161  2832  7350 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 09:18:49.161  4277  4277 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 09:18:49.162  4277  4277 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 09:18:49.162  4277  4277 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 09:18:49.163  7346  7347 E QC-QMI  : qmi_client [7346] 15: failed to locate client data
09-13 09:18:49.163  4277  4277 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 09:18:49.164   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 09:18:49.164   468   468 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-13 09:18:49.166  2832  7350 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1dbf1941 on behalf of 2832
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 09:18:49.167  2832  7350 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 09:18:49.168  2832  7350 I DownloadManager: in trimDatabase
09-13 09:18:49.168  2832  7350 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 09:18:49.168  4277  4277 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-13 09:18:49.169  2832  2832 V DownloadManager: DownloadService onStartCommand
09-13 09:18:49.169  2832  7350 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a69bed4 on behalf of 2832
09-13 09:18:49.169  7026  7352 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.170  2832  7351 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 09:18:49.172  2832  7351 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2323087d on behalf of 2832
09-13 09:18:49.175  3440  3440 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 09:18:49.175  3440  3440 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.175  3440  3440 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 09:18:49.175  3440  3440 D PhoneState: setPdpRejectCasuse : false
09-13 09:18:49.175  2832  7351 V DownloadManager: processing inserted download 1
09-13 09:18:49.176  2832  7351 V DownloadManager: processing inserted download 4
09-13 09:18:49.177  2832  7351 V DownloadManager: processing inserted download 7
09-13 09:18:49.178  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 09:18:49.178  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 09:18:49.178  2832  7351 V DownloadManager: processing inserted download 8
09-13 09:18:49.180  2832  7351 V DownloadManager: processing inserted download 9
,09-13 09:18:49.182  2832  7351 V DownloadManager: processing inserted download 10
09-13 09:18:49.183  2832  7351 V DownloadManager: processing inserted download 11
09-13 09:18:49.183  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:49
09-13 09:18:49.184  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 09:18:49.184  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
09-13 09:18:49.184  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 09:18:49.184  7169  7169 D WeatherAncestor: connectivity changed - connection : true
09-13 09:18:49.184  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3167355f
09-13 09:18:49.184   307  7358 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 09:18:49.184   307  7358 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-13 09:18:49.184  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 09:18:49.184  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 09:18:49.185  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 09:18:49.185  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 09:18:49.185  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:49
09-13 09:18:49.186  2832  7351 V DownloadManager: processing inserted download 12
09-13 09:18:49.186  2832  7351 V DownloadManager: processing inserted download 13
09-13 09:18:49.189  2832  7351 V DownloadManager: processing inserted download 14
09-13 09:18:49.190  2832  7351 V DownloadManager: processing inserted download 16
09-13 09:18:49.197  7359  7359 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 09:18:49.201  6810  6810 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-13 09:18:49.201  2832  2832 V DownloadManager: DownloadService onDestroy
09-13 09:18:49.201  6810  6810 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3122
09-13 09:18:49.202  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=87004055 [*alarm*], flags=0x0
09-13 09:18:49.203  7360  7360 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 09:18:49.216  6830  7356 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 09:18:49.219  6830  7356 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 09:18:49.227   307  7358 D libc-netbsd: res_queryN name = www.google.com succeed
09-13 09:18:49.229   307  7363 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 09:18:49.229   307  7363 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 09:18:49.229   307  7363 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 09:18:49.234  6563  6893 D UEI.SmartControl: Internal timer expired: 4
09-13 09:18:49.234  6563  6893 D UEI.SmartControl: unbind internal service
09-13 09:18:49.237  3840  3913 I bt_vendor: bluetooth satus is on
09-13 09:18:49.237  3840  3913 D bt_hci_bdroid: preload
09-13 09:18:49.238  3840  7325 D bt_userial_mct: userial_open(port:0)
09-13 09:18:49.238  3840  7325 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 09:18:49.238  3840  7325 I bt_vendor: Done intiailizing UART
09-13 09:18:49.238  3840  7325 I bt_vendor: Done intiailizing UART
09-13 09:18:49.238  3840  7325 I bt_userial_mct: CMD=94, EVT=94, ACL_Out=95, ACL_In=95
09-13 09:18:49.238  3840  7325 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 09:18:49.238  3840  7322 I bt-btu  : btu_task received preload complete event
09-13 09:18:49.239  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 09:18:49.239  3840  7364 D bt_userial_mct: Entering userial_read_thread()
09-13 09:18:49.239  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 09:18:49.239  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 09:18:49.239  3840  7322 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 09:18:49.254  6563  6890 D serial_port: close(fd = 24)
,09-13 09:18:49.257  6563  6890 I UEI.SmartControl: Serial port is closed.
09-13 09:18:49.278  3840  7322 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 09:18:49.278  3840  7322 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b5061 
09-13 09:18:49.278  3840  7322 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b5061 
,09-13 09:18:49.285  1035  1526 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-13 09:18:49.288  3840  3917 E bt-btif : Calling BTA_HhEnable
09-13 09:18:49.288  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 09:18:49.288  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 09:18:49.288  3840  3917 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 09:18:49.288  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 09:18:49.289  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 09:18:49.289  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 09:18:49.289  3840  3917 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 09:18:49.291  3840  3917 D BluetoothAdapterProperties: Name is: G3
09-13 09:18:49.291  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 09:18:49.292  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-13 09:18:49.297  3840  7322 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 09:18:49.297  3840  7322 W bt-smp  : Plain text(LSB ~ MSB) = 09 f8 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 09:18:49.297  3840  7322 W bt-smp  : Encrypted text(LSB ~ MSB) = ab 93 b5 5f d0 dd 61 d8 d9 57 2b e3 a1 a1 0b 4f 
09-13 09:18:49.297  3840  7322 W bt-btm  : Stopping oneshot timer
09-13 09:18:49.299  3840  3917 D BluetoothAdapterProperties: Scan Mode:20
09-13 09:18:49.299  3840  3917 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 09:18:49.299  3840  3917 D bt_hci_bdroid: postload
09-13 09:18:49.300  3840  7325 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:49.300  3840  7322 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 09:18:49.301  3840  3917 D bte_conf: Device ID record 1 : primary
09-13 09:18:49.301  3840  7325 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:49.301  3840  3917 D bte_conf:   vendorId            = 00c4
09-13 09:18:49.301  3840  3917 D bte_conf:   vendorIdSource      = 0001
09-13 09:18:49.301  3840  3917 D bte_conf:   product             = 13a1
09-13 09:18:49.301  3840  3917 D bte_conf:   version             = 1000
09-13 09:18:49.301  3840  3917 D bte_conf:   clientExecutableURL = 
09-13 09:18:49.301  3840  3917 D bte_conf:   serviceDescription  = 
09-13 09:18:49.301  3840  3917 D bte_conf:   documentationURL    = 
09-13 09:18:49.301  3840  7325 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:49.301  3840  3917 D bte_conf: bte_load_did_conf no section named DID2.
09-13 09:18:49.302  3840  7325 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 09:18:49.302  3840  7364 E bt_mct  : hci lib postload completed
09-13 09:18:49.305  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:49.307  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:49.309  3840  3917 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 09:18:49.299  7366  7366 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:49.299  7366  7366 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:49.309  3840  3913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 09:18:49.309  3840  3913 D BluetoothAdapterProperties: ScanMode =  20
09-13 09:18:49.309  3840  3913 D BluetoothAdapterProperties: State =  11
09-13 09:18:49.309  3840  3913 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 09:18:49.310  3840  3913 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 09:18:49.310  3840  3913 D BluetoothAdapterProperties: Setting state to 12
09-13 09:18:49.310  3840  3913 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 09:18:49.311  3840  3917 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 09:18:49.312  1035  1117 D BluetoothManagerService: Message: 60
09-13 09:18:49.312  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 09:18:49.312  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-13 09:18:49.312  3840  3913 I BluetoothAdapterState: Entering On State
09-13 09:18:49.314  6787  7140 D BluetoothMap: onBluetoothStateChange: up=true
09-13 09:18:49.314  3840  3913 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 09:18:49.314  3840  3913 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 09:18:49.314  3840  3913 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 09:18:49.315  3840  3913 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:49.317  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:49.319  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:49.323  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 09:18:49.326  6787  6803 D BluetoothPan: onBluetoothStateChange on: true
09-13 09:18:49.326  6787  6803 D BluetoothPan: onBluetoothStateChange call bindService
09-13 09:18:49.329  6787  6787 D BluetoothMap: Proxy object connected
09-13 09:18:49.329  6787  6787 D MapProfile: Bluetooth service connected
09-13 09:18:49.329  6787  6787 D BluetoothMap: getConnectedDevices()
09-13 09:18:49.330  1035  1035 D BluetoothHeadset: Proxy object connected
09-13 09:18:49.331  6787  7140 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 09:18:49.332  3840  6730 V BluetoothMapService: getConnectedDevices()
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:49.333  6667  7189 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:49.334  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:49.337  6667  7189 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:18:49.338  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 09:18:49.339  6787  6787 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 09:18:49.339  6787  6787 D PanProfile: Bluetooth service connected
09-13 09:18:49.339  1837  3940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:49.342  1837  2433 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:49.342  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 09:18:49.344  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:49.345  1837  1837 D BluetoothHeadset: Proxy object connected
09-13 09:18:49.345  6787  6803 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 09:18:49.345  6787  6787 D BluetoothInputDevice: Proxy object connected
09-13 09:18:49.345  6787  6787 D HidProfile: Bluetooth service connected
09-13 09:18:49.347  1035  1890 D WifiServiceImplEx: setWifiEnabled: false pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:49.347  1035  1890 D WifiService: setWifiEnabled: false pid=6667, uid=10118
09-13 09:18:49.347  1035  1890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:49.348  3840  3917 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 09:18:49.348  3840  3917 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-13 09:18:49.349  6787  6802 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 09:18:49.352  6787  6787 D BluetoothA2dp: Proxy object connected
09-13 09:18:49.352  6787  6787 D A2dpProfile: Bluetooth service connected
09-13 09:18:49.353  6787  7140 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 09:18:49.355  6787  6787 D BluetoothHeadset: Proxy object connected
09-13 09:18:49.355  6787  6787 D HeadsetProfile: Bluetooth service connected
09-13 09:18:49.356  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 09:18:49.356  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:49.356  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:49.357  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 09:18:49.357  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 09:18:49.357  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 09:18:49.357  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 09:18:49.358  1035  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:49.358  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:49.359  1035  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:49.360  1035  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,09-13 09:18:49.361  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.361  1927  2110 D LGBluetoothAPIService: Message: 1
09-13 09:18:49.361  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 09:18:49.361  1927  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 09:18:49.361  1035  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 09:18:49.361  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 09:18:49.361  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 09:18:49.363  3840  3913 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 09:18:49.363  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 09:18:49.363  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 09:18:49.364  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 09:18:49.365  1035  1614 D WifiServiceImplEx: setWifiEnabled: false pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:49.365  1035  1614 D WifiService: setWifiEnabled: false pid=6667, uid=10118
09-13 09:18:49.365  1035  1614 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:49.369  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 09:18:49.370  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 09:18:49.370  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 09:18:49.370  1035  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.370  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 09:18:49.371  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 09:18:49.371  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 09:18:49.372  3840  3840 V BtOppService: Receiver BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 09:18:49.372  3840  3840 V BtOppService: start RfcommListener
09-13 09:18:49.373  3840  3840 V BtOppService: RfcommListener started
09-13 09:18:49.373  3840  3840 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.373  3840  3840 D BluetoothMapService: STATE_ON
09-13 09:18:49.373  3840  3840 V BluetoothMapService: Handler(): got msg=1
09-13 09:18:49.373  3840  3840 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 09:18:49.374  3840  7375 D BluetoothMapMasInstance: MAS initSocket()
09-13 09:18:49.375  3840  7375 D BluetoothMapMasInstance:   masId = 00
09-13 09:18:49.375  3840  7375 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 09:18:49.375  3840  7375 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 09:18:49.375  3840  7375 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 09:18:49.375  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:49.375  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:49.375  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:49.375  3840  3840 V BluetoothPbapService: Pbap Service onCreate
09-13 09:18:49.375  3840  3840 V BluetoothPbapService: Starting PBAP service
09-13 09:18:49.375   307   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 09:18:49.376  3840  3840 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 09:18:49.376  3840  3840 V BluetoothPbapService: Pbap Service onBind
09-13 09:18:49.376  3840  7374 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 09:18:49.377  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:49.377  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:49.379  1035  6941 D DhcpStateMachine: RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.379  7373  7373 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 09:18:49.379  1927  2110 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 09:18:49.379  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:49.385  3840  3840 V BluetoothPbapService: Handler(): got msg=1
,09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:49.391  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:49.391  3840  3840 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 09:18:49.391  3840  7375 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:49.391  3840  7374 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:49.391  3840  3840 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.391  3840  3840 V BluetoothPbapService: state: 12
09-13 09:18:49.392  3840  3840 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 09:18:49.393  3840  3840 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 09:18:49.395  3840  7375 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=99 mFd=89
09-13 09:18:49.395  3840  7374 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=101 mFd=99
09-13 09:18:49.395  3840  7375 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 09:18:49.395  3840  7375 D BluetoothMapMasInstance: Accepting socket connection...
09-13 09:18:49.395  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 09:18:49.395  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-13 09:18:49.396  3840  7374 V BtOppRfcommListener: Started RFCOMM listener....
09-13 09:18:49.396  3840  7374 I BtOppRfcommListener: Accept thread started.
09-13 09:18:49.396  3840  7374 V BtOppRfcommListener: Accepting connection...
09-13 09:18:49.396  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:49.398  3840  7376 V BluetoothPbapService: Pbap Service initSocket
09-13 09:18:49.398  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 09:18:49.401  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:49.402  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:49.402  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:49.402  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:49.403  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:49.403  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:49.403  1035  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 09:18:49.405  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 09:18:49.406  1035  1522 D LGWifiP2pService: InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.407  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.407  1035  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cb9d8ff
09-13 09:18:49.407  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 09:18:49.407  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.407  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.407  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:49.407  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 09:18:49.407  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.408  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.408  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:49.408  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 09:18:49.408  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 09:18:49.408  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.408  1035  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 09:18:49.412  1035  1522 D LGWifiP2pService: P2pDisablingState
,09-13 09:18:49.412  1035  1522 D LGWifiP2pService: P2pDisablingState{ when=-5ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.412  1035  1522 D LGWifiP2pService: p2p socket connection lost
09-13 09:18:49.412  1035  1522 D LGWifiP2pService: P2pDisabledState
09-13 09:18:49.414  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 09:18:49.415  1927  1927 D WfdsService: WifiP2pState is changed : false
09-13 09:18:49.415  1927  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 09:18:49.415  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-13 09:18:49.415  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-13 09:18:49.415  1927  2296 D WfdsService: STATE : WfdsDisabledState - enter
09-13 09:18:49.415  1927  6882 D CtrlSupplicant: Received on exit socket, terminate
09-13 09:18:49.415  1927  6882 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 09:18:49.416  1927  6882 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 09:18:49.416  1927  6882 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:49.416  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:49.416  1927  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 09:18:49.416  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 09:18:49.416  1927  2296 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 09:18:49.417  1035  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.417  1035  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.417  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 09:18:49.417  6877  6877 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 09:18:49.418  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:49.418  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:49.418  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:49.418  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 09:18:49.418  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 09:18:49.419  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:49.420  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:49.421  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:49.424  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:49.424  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:49.425  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:49.433   307   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 09:18:49.433  1035  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 09:18:49.433  1035  1530 D DSQN    : disableDataServiceNotify
09-13 09:18:49.433  1035  1530 D DSQN    : stop dsqn bin
,09-13 09:18:49.434  1035  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 09:18:49.435  1035  1523 D WifiNative-p2p0: TERMINATE: returned true
09-13 09:18:49.435  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:49.435  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:49.435  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:49.435  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 09:18:49.436  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.436  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.436  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:49.438  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 09:18:49.438  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:49.438  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 09:18:49.439  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 09:18:49.441  1035  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 09:18:49.441  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:49.441  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:49.442  1035  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:49.442  1035  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 09:18:49.442  1035  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 09:18:49.442  1035  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 09:18:49.442  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 09:18:49.443  1035  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.443  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 09:18:49.443  1035  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:49.443  1035  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:49.443  1035  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:49.443  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, fa,ilover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 09:18:49.443  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:49.443  1035  1530 D NetworkManagementService: Removing idletimer
09-13 09:18:49.443  1035  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.443  1035  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 09:18:49.443  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.443  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.443  1035  6940 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 09:18:49.444  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:49.444  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 09:18:49.444  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 09:18:49.444  1035  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 09:18:49.444  1035  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:49.444  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:49.445  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 09:18:49.445  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 09:18:49.445  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 09:18:49.445  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 09:18:49.445  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 09:18:49.446  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 09:18:49.446  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,09-13 09:18:49.446  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 09:18:49.446  1035  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 09:18:49.446  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:49.447  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:49.451  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:49.451  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:49.453  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:49.454  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:49.456  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:49.456  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:18:49.471  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 09:18:49.472  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:49.472  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:49.485  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 09:18:49.486  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:49.486  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:49.489  6877  6877 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 09:18:49.489  6877  6877 I wpa_supplicant: monitor socket send errors count : 1
09-13 09:18:49.489  6877  6877 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
09-13 09:18:49.490  1035  6881 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 09:18:49.490  1035  6881 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 09:18:49.497  1035  1998 I art     : Explicit concurrent mark sweep GC freed 56477(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.445ms total 114.960ms
,09-13 09:18:49.500  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 09:18:49.500  1927  2110 D LGBluetoothAPIService: Message: 100
09-13 09:18:49.500  1927  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 09:18:49.500  3840  3917 D BluetoothAdapterProperties: Scan Mode:21
09-13 09:18:49.500  3840  3917 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 09:18:49.501  3840  7376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:49.502  6787  6787 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:49.505  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:49.506  6787  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 09:18:49.507  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:49.508  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:49.510  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 09:18:49.510  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 09:18:49.510  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:49.511  3840  7376 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=103 mFd=101
09-13 09:18:49.512  3840  7376 V BluetoothPbapService: Succeed to create listening socket 
,09-13 09:18:49.512  3840  7376 V BluetoothPbapService: Accepting socket connection...
09-13 09:18:49.514  6787  6787 D BluetoothPbap: Proxy object connected
09-13 09:18:49.514  6787  6787 D PbapServerProfile: Bluetooth service connected
09-13 09:18:49.515  6877  6877 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 09:18:49.516  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 09:18:49.516  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 09:18:49.516  1035  6881 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 09:18:49.516  1035  6881 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 09:18:49.516  1035  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=196208
09-13 09:18:49.516  1035  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=196208
09-13 09:18:49.516  6877  6877 W wpa_supplicant: USIM:  scard_deinit function
09-13 09:18:49.516  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:49.516  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:49.517  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=196208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 09:18:49.517  1035  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=196209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 09:18:49.518  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 09:18:49.520  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 09:18:49.521  1035  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:49.521  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:49.522  6787  6787 D DockEventReceiver: finishStartingService: stopping service
09-13 09:18:49.523  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:49.527  3840  3840 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 09:18:49.527  3840  3840 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.527  3840  3840 V BluetoothPbapReceiver: ***********state = 12
09-13 09:18:49.527  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:49.533  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 09:18:49.534  2214  2214 D c       : Getting all permits...
09-13 09:18:49.534  2214  2214 D a       : Opening database...
09-13 09:18:49.536  2214  2214 D a       : Opening database auth.proximity.permit_store...
09-13 09:18:49.536  2214  2214 D a       : Closing database...
,09-13 09:18:49.538  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:49.538  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:49.541  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:49.545  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:49.547  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 09:18:49.548  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 09:18:49.548  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 09:18:49.550  6787  6787 D BluetoothPermissionRequest: onReceive
09-13 09:18:49.553  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:49.558  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:49.558  6787  6787 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 09:18:49.559  6787  6787 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 09:18:49.560  1802  7133 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
09-13 09:18:49.561  3840  3840 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-13 09:18:49.562  3840  3840 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 09:18:49.563  3840  3840 V BtOppService: onStartCommand
09-13 09:18:49.564  3840  3840 V BtOppService: Starting RfcommListener
09-13 09:18:49.565  3840  3840 V BtOppService: start RfcommListener
09-13 09:18:49.565  3840  3840 V BtOppService: RfcommListener started
09-13 09:18:49.565  3840  7383 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 09:18:49.565  3840  7383 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 09:18:49.567  3840  7383 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a8041b6 on behalf of 
09-13 09:18:49.569  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:49.569  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:49.569  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.569  3840  3840 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 09:18:49.570  3840  7383 V BluetoothOppNotification: update too frequent, put in queue
09-13 09:18:49.570  3840  7383 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 09:18:49.571  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
09-13 09:18:49.571  3840  3840 V BluetoothFtpService: Ftp Service onCreate
09-13 09:18:49.571  3840  3840 I BluetoothFtpService: Ftp Service onCreate
09-13 09:18:49.572  3840  3840 V BluetoothFtpService: Ftp Service onStartCommand
09-13 09:18:49.572  3840  3840 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.572  3840  3840 V BluetoothFtpService: Starting Listening on sockets
09-13 09:18:49.572  3840  3840 V BluetoothFtpService: Handler(): got msg=1
,09-13 09:18:49.573  3840  3840 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,09-13 09:18:49.573  3840  3840 V BluetoothFtpService: Ftp Service initSocket
09-13 09:18:49.574  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:49.575  3840  3840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:49.575  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:49.577  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:49.579  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 09:18:49.579  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 09:18:49.579  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:49.579  1802  7133 I CheckinService: active receiver: disabled
09-13 09:18:49.580  3840  3840 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=105 mFd=103
09-13 09:18:49.580  3840  3840 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 09:18:49.580  3840  3840 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 09:18:49.580  3840  3840 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 09:18:49.580  3840  3840 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 09:18:49.580  3840  3840 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.580  3840  3840 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 09:18:49.580  3840  3840 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 09:18:49.581  3840  7384 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-13 09:18:49.589  3840  3840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bd4e9fe
,09-13 09:18:49.589  3840  3840 V BluetoothSapService: Sap Service onCreate
09-13 09:18:49.591  3840  3840 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 09:18:49.591  3840  3840 V BluetoothSapService: state: 12
09-13 09:18:49.591  3840  3840 V BluetoothSapService: Starting SAP server process
09-13 09:18:49.592  3840  3840 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-13 09:18:49.593  3840  7386 V BluetoothSapService: Sap Service initRfcommSocket
09-13 09:18:49.579  7385  7385 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:49.579  7385  7385 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:49.594  1035  6941 D DhcpStateMachine: StoppedState
09-13 09:18:49.594  1035  6941 D DhcpStateMachine: StoppedState{ when=-176ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:49.594  1035  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:49.595  3840  7386 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:49.596  3840  7386 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=107 mFd=105
09-13 09:18:49.596  3840  7386 V BluetoothSapService: Succeed to create listening socket 
09-13 09:18:49.596  3840  7386 V BluetoothSapService: Accepting socket connection...
09-13 09:18:49.596  1035  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 09:18:49.596  1035  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 09:18:49.600  7385  7385 V BT_SAP  : Event pipe created
09-13 09:18:49.600  7385  7385 V BT_SAP  : create_server_socket qcom.sap.server
09-13 09:18:49.600  7385  7385 V BT_SAP  : created socket fd 6
,09-13 09:18:49.601  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:49.609  6877  6877 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-13 09:18:49.610  1035  6881 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 09:18:49.610  1035  6881 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 09:18:49.610  1035  6881 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 09:18:49.610  1802  7387 I CheckinService: active receiver: disabled
09-13 09:18:49.610  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-13 09:18:49.620  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:49.623  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:49.623  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:49.625  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 09:18:49.632  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:49.635  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 09:18:49.638  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:49.643  6830  7389 W FormManager: Network not available. Please check & try again.
09-13 09:18:49.646  6830  7390 V FormManager: Network unavailable.
09-13 09:18:49.649  6830  7390 V FormManager: Network unavailable.
,09-13 09:18:49.669  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 09:18:49.669  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 09:18:49.669  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 09:18:49.669  6787  6787 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 09:18:49.669  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 09:18:49.670  6787  6787 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 09:18:49.670  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 09:18:49.670  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 09:18:49.670  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 09:18:49.670  6787  6787 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 09:18:49.670  6787  6787 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 09:18:49.673  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-13 09:18:49.682  2214  2214 I GCM     : GCM config loaded
,09-13 09:18:49.688   307  7393 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 09:18:49.689  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 09:18:49.697  3840  3840 V BluetoothOppNotification: new notify threadi!
09-13 09:18:49.697  3840  3840 V BluetoothOppNotification: send delay message
,09-13 09:18:49.699  3840  7395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 09:18:49.699  7088  7088 V SetupWizard: Connected to Gservices successfully
09-13 09:18:49.700  3840  7395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@162b6f53 on behalf of 
09-13 09:18:49.703  3840  7395 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 09:18:49.704  3840  7395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 09:18:49.704  3840  7395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@199be090 on behalf of 
09-13 09:18:49.705  3840  7395 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 09:18:49.706  3840  7395 V BluetoothOppNotification: outbound notification was removed.
09-13 09:18:49.706  3840  7395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 09:18:49.707  3840  7395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@252aad89 on behalf of 
09-13 09:18:49.707  3840  7395 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 09:18:49.708  3840  7395 V BluetoothOppNotification: inbound notification was removed.
09-13 09:18:49.708  3840  7395 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 09:18:49.709  3840  7395 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1501d18e on behalf of 
,09-13 09:18:49.711  1035  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 09:18:49.711  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:49.711  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:49.711  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:49.712  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-13 09:18:49.712  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 09:18:49.712  1927  2296 D WfdsService: Set the WFDS Monitor: false
09-13 09:18:49.713  1927  2296 D WfdsMonitor: WFDS Monitor is stopped
09-13 09:18:49.713  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:49.714  2437  2437 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:49.715  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 09:18:49.716  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 09:18:49.716  1035  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 09:18:49.716  1035  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 09:18:49.716  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:49.717  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:49.718  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 09:18:49.718  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:49.719  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:49.721  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 09:18:49.724  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:49.727  4277  7396 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:49.730  6767  6767 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 09:18:49.730  6767  6767 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 09:18:49.730  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:49.732  4277  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 09:18:49.732  4277  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 09:18:49.738  6830  7399 W FormManager: Network not available. Please check & try again.
09-13 09:18:49.739  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 09:18:49.742  6830  7400 V FormManager: Network unavailable.
09-13 09:18:49.743  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:49.748  6830  7400 V FormManager: Network unavailable.
,09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:49.874  6667  7371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 09:18:49.880  6667  7371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:18:49.889  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 09:18:49.892  1035  1560 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 09:18:49.893  1035  1560 D WifiService: setWifiEnabled: true pid=6667, uid=10118
09-13 09:18:49.894  1035  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:49.919  1035  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-13 09:18:49.919  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 09:18:49.919  1035  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 09:18:49.920  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 09:18:49.920  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 09:18:49.923  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 09:18:49.923  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 09:18:49.923  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 09:18:49.923  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 09:18:49.924  1035  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 09:18:49.925  1035  1523 E WifiHW  : unknown target_country: EU , set to default
09-13 09:18:49.926  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 09:18:49.926  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 09:18:49.926  1035  1523 I WifiUtil: gEnableBmps=1
09-13 09:18:49.926  1035  1962 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:49.929  1035  1962 D WifiService: setWifiEnabled: true pid=6667, uid=10118
09-13 09:18:49.929  1035  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:49.931  1035  1529 D WifiController: Mismatch in the state 1
09-13 09:18:50.433  1035  1866 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 09:18:50.439  1035  1866 D WifiService: setWifiEnabled: true pid=6667, uid=10118
09-13 09:18:50.439  1035  1866 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:50.441  1035  1529 D WifiController: Mismatch in the state 1
09-13 09:18:50.633   307   893 D SoftapController: Softap fwReload - Ok
,09-13 09:18:50.636  1035  1523 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (706ms)
09-13 09:18:50.640  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 09:18:50.655   307   893 D CommandListener: Setting iface cfg
09-13 09:18:50.655   307   893 D CommandListener: Trying to bring down wlan0
09-13 09:18:50.656  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 09:18:50.656  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 09:18:50.657   307   893 D CommandListener: Clearing all IP addresses on wlan0
09-13 09:18:50.669  1035  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-13 09:18:50.676  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 09:18:50.677  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 09:18:50.677  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 09:18:50.677  6787  6787 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 09:18:50.677  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:50.677  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:50.677  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:50.669  7419  7419 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:50.683  1035  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 09:18:50.683  1035  1523 D WifiMonitor: connecting to supplicant
,09-13 09:18:50.669  7419  7419 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 09:18:50.713  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:50.717  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 09:18:50.740  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-13 09:18:50.749  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:50.750  7419  7419 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 09:18:50.750  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 09:18:50.752  6787  6787 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 09:18:50.753  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 09:18:50.753  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 09:18:50.753  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 09:18:50.753  6787  6787 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 09:18:50.753  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 09:18:50.753  6787  6787 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 09:18:50.754  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:50.760  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:50.760  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 09:18:50.760  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 09:18:50.761  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 09:18:50.761  6787  6787 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 09:18:50.761  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 09:18:50.762  6787  6787 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 09:18:50.762  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 09:18:50.762  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 09:18:50.762  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 09:18:50.762  6787  6787 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 09:18:50.762  6787  6787 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 09:18:50.771  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 09:18:50.774  7419  7419 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 09:18:50.774  7419  7419 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 09:18:50.775  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 09:18:50.781  6830  7438 V FormManager: Network unavailable.
09-13 09:18:50.781  6830  7437 W FormManager: Network not available. Please check & try again.
09-13 09:18:50.781  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:50.787  6830  7438 V FormManager: Network unavailable.
,09-13 09:18:50.847  7419  7419 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 09:18:50.897  7419  7419 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 09:18:50.917  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-13 09:18:50.918  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 09:18:50.918  7419  7419 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-13 09:18:50.919  1035  7440 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-13 09:18:50.919  1035  7440 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 09:18:50.919  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 09:18:50.919  7419  7419 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 09:18:50.919  1035  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 09:18:50.920  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 09:18:50.920  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 09:18:50.920  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.920  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 09:18:50.920  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 09:18:50.920  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.921  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:50.921  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:50.922  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:50.922  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:50.923  1035  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 09:18:50.923  1035  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 09:18:50.924  1035  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 09:18:50.925  1035  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 09:18:50.925  1035  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 09:18:50.926  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 09:18:50.926  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
09-13 09:18:50.926  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 09:18:50.926  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:50.926  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:50.927  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:50.927  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:50.927  1035  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 09:18:50.928  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 09:18:50.929  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:50.930  1035  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-13 09:18:50.930  1035  1523 D WifiConfigStore: Loading config and enabling all networks 
09-13 09:18:50.930  1035  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 09:18:50.931  1035  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 09:18:50.932  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-13 09:18:50.936  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 09:18:50.936  1035  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:50.940  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:50.942  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:50.943  1035  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:50.949  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:50.952  1035  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 09:18:50.953  1035  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 09:18:50.954  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 09:18:50.954  1035  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-13 09:18:50.954  1035  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 09:18:50.955  1035  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 09:18:50.955  1035  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 09:18:50.955  1035  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 09:18:50.955  1035  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 09:18:50.956  1035  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 09:18:50.956  1035  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 09:18:50.956  1035  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 09:18:50.956  1035  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 09:18:50.956  1035  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 09:18:50.957  1035  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 09:18:50.957  1035  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 09:18:50.957  1035  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 09:18:50.957  1035  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 09:18:50.958  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:50.958  6667  7402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:50.959  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 09:18:50.959  1035  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 09:18:50.959  1035  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,09-13 09:18:50.960  1035  1523 D WifiNative-HAL: Setting external_sim to 1
09-13 09:18:50.960  1035  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 09:18:50.960  1035  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 09:18:50.960  1035  1523 I WifiNative-HAL: startHal
09-13 09:18:50.960  1035  1523 D wifi    : setting scan oui 0x953dc700
09-13 09:18:50.961  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 09:18:50.961  1035  1523 I WifiNative-HAL: startHal
09-13 09:18:50.961  1035  1523 D wifi    : setting scan oui 0x953dc700
09-13 09:18:50.961  1035  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 09:18:50.961  1035  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 09:18:50.962  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 09:18:50.962  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 09:18:50.962  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 09:18:50.962  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 09:18:50.963  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 09:18:50.963  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 09:18:50.963  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 09:18:50.963  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 09:18:50.964  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 09:18:50.964  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 09:18:50.964  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 09:18:50.964  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 09:18:50.964  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 09:18:50.965  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 09:18:50.965  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-13 09:18:50.965  1927  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 09:18:50.965  1927  2296 D WfdsService: Set the WFDS Monitor: true,
09-13 09:18:50.965  1927  2296 D WfdsMonitor: WfdsMonitorThread create
09-13 09:18:50.965  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 09:18:50.965  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 09:18:50.965  1927  2296 D WfdsMonitor: WFDS Monitor is created and started
09-13 09:18:50.965  1927  2296 D WfdsService: WiFi: Supplicant connection re-established
09-13 09:18:50.965  7419  7419 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 09:18:50.965  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 09:18:50.966  1927  7441 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 09:18:50.966  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,09-13 09:18:50.966  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 09:18:50.966  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 09:18:50.966  1927  7441 E CtrlSupplicant: Succeed to open control connection
09-13 09:18:50.967  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 09:18:50.967  1927  7441 E CtrlSupplicant: Succeed to open monitor connection
09-13 09:18:50.968  1035  1523 E WifiNative: : [197,658,692 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 09:18:50.968  1035  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 09:18:50.968  1927  7441 D WfdsMonitor: Supplicant connection established
09-13 09:18:50.968  6667  7402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:50.968  1927  2296 D WfdsService: Connected to the supplicant for wfds
,09-13 09:18:50.970  1035  1523 D WifiNative-wlan0: RECONNECT: returned true
09-13 09:18:50.970  1035  1523 D WifiNative-wlan0: doString: [STATUS]
09-13 09:18:50.971  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 09:18:50.971  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 09:18:50.971  1035  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 09:18:50.971  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 09:18:50.972  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:50.972  1035  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:50.972  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 09:18:50.974   307   893 D CommandListener: Setting iface cfg
09-13 09:18:50.974   307   893 D CommandListener: Trying to bring up p2p0
09-13 09:18:50.974  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:50.974  1035  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 09:18:50.974  1035  1522 D LGWifiP2pService: P2pEnablingState
09-13 09:18:50.974  1035  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:50.974  1035  1522 D LGWifiP2pService: P2p socket connection successful
09-13 09:18:50.975  1035  1522 D LGWifiP2pService: P2pEnabledState
09-13 09:18:50.975  1035  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 09:18:50.975  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 09:18:50.975  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 09:18:50.975  1035  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 09:18:50.976  1035  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 09:18:50.976  1035  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 09:18:50.976  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 09:18:50.977  1035  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 09:18:50.977  1927  1927 D WfdsService: WifiP2pState is changed : true
09-13 09:18:50.977  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 09:18:50.977  1035  1523 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.977  1035  1035 D RttService: SCAN_AVAILABLE : 3
,09-13 09:18:50.977  1927  2296 D WfdsService: Receive the WFDS_ENABLE Method
09-13 09:18:50.977  1927  2296 D WfdsService: Set the WFDS Monitor: true
09-13 09:18:50.977  1035  1523 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.977  1927  2296 D WfdsService: Connected to the supplicant for wfds
09-13 09:18:50.977  1927  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 09:18:50.978  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 09:18:50.978  7419  7419 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 09:18:50.978  1035  1523 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.978  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.978  1927  1927 D WfdsService: isConnected: false
09-13 09:18:50.978  1035  1542 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:50.979  1035  1523 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.979  1035  1541 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:50.979  1035  1523 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.979  1927  2296 D WfdsService: selectPreferredScanChannel [36]
09-13 09:18:50.979  1927  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 09:18:50.979  1035  1523 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.980  1035  1541 I WifiNative-HAL: startHal
09-13 09:18:50.980  1035  1523 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.980  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.978  1035  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 09:18:50.981  1035  1523 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 09:18:50.981  1035  1541 D wifi    : getting scan capabilities on interface[1] = 0x953dc700
09-13 09:18:50.981  1035  1541 D wifi    : failed to get capabilities : -3
09-13 09:18:50.981  1035  1541 E WifiScanningService: could not get scan capabilities
09-13 09:18:50.981  1035  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 09:18:50.981  1035  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 09:18:50.982  1035  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 09:18:50.982  1035  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 09:18:50.982  1035  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 09:18:50.982  7419  7419 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 09:18:50.982  1035  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 09:18:50.982  1035  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-13 09:18:50.982  1035  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 09:18:50.983  1035  1522 D LGWifiP2pService: before postfix = G3
09-13 09:18:50.983  1035  1522 D WifiServerServiceExt: postfix byte check : 2
09-13 09:18:50.983  1035  1522 D LGWifiP2pService: after postfix = G3
09-13 09:18:50.983  1035  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 09:18:50.983  1035  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 09:18:50.983  1035  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 09:18:50.983  1035  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 09:18:50.983  7419  7419 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 09:18:50.984  1035  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 09:18:50.984  1035  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 09:18:50.984  1035  1523 E WifiStateMachine:  DisconnectedState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  ,rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3045] from screen [on:0 period:577348456] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:50.984  1035  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 09:18:50.984  1035  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 09:18:50.985  1035  1523 E WifiStateMachine:  ConnectModeState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:577348457] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:50.985  1035  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 09:18:50.985  1035  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 09:18:50.985  1035  1523 E WifiStateMachine:  DriverStartedState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:577348457] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:50.986  1035  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 09:18:50.986  1035  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-13 09:18:50.986  1035  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 09:18:50.986  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:577348458] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:50.986  1035  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 09:18:50.986  1035  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 09:18:50.987  1035  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:577348459] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:50.987  1035  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 09:18:50.987  1035  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 09:18:50.987  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:50.987  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 09:18:50.988  1035  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 09:18:50.988  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 09:18:50.988  1035  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 09:18:50.988  6667  6728 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 09:18:50.988  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 09:18:50.988  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 09:18:50.988  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 09:18:50.988  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 09:18:50.989  1927  1927 D WfdsService: Update P2p Interface State: 3
09-13 09:18:50.989  1035  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 09:18:50.989  1035  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-13 09:18:50.997  1035  1693 D WifiServiceImplEx: setWifiEnabled: true pid=6667, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 09:18:50.998  1035  1693 D WifiService: setWifiEnabled: true pid=6667, uid=10118
09-13 09:18:50.998  1035  1693 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 09:18:51.000  1035  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 09:18:51.000  1035  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 09:18:51.000  1035  1522 D LGWifiP2pService: InactiveState
09-13 09:18:51.000  1035  1522 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.000  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.000  1035  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 09:18:51.001  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 09:18:51.001  7419  7419 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.002  7419  7419 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 09:18:51.002  7419  7419 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.002  6830  7443 W FormManager: Network not available. Please check & try again.
09-13 09:18:51.003  7419  7419 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-13 09:18:51.004  1927  7441 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 09:18:51.004  1927  7441 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.004  1927  7441 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.004  1035  7440 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 09:18:51.004  1035  7440 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.004  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.004  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.004  1035  7440 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.004  1035  7440 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.004  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.004  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.004  1035  7440 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.004  1035  7440 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.004  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.004  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.007  1035  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 09:18:51.007  1035  1522 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.008  1035  1522 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.009  1927  2296 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 09:18:51.009  1035  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.009  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.009  1035  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.009  1035  1035 E WifiServerServiceExt: No p2p device connected
09-13 09:18:51.009  6830  7444 V FormManager: Network unavailable.
09-13 09:18:51.010  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 09:18:51.010  7419  7,419 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.010  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 09:18:51.010  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.010  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.010  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 09:18:51.011  7419  7419 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 09:18:51.011  7419  7419 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.011  1927  7441 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.011  1035  7440 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.011  1035  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 09:18:51.011  1035  7440 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.011  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.011  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.012  7419  7419 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.012  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 09:18:51.012  1927  7441 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.012  1035  7440 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 09:18:51.012  1035  7440 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.012  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 09:18:51.012  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.012  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 09:18:51.012  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 09:18:51.012  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 09:18:51.013  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 09:18:51.013  7419  7419 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:51.013  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 09:18:51.013  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:51.013  1035  7440 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:51.013  1035  7440 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 09:18:51.014  1035  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 09:18:51.014  1035  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 09:18:51.014  1035  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 09:18:51.014  1035  1523 D WifiNative-wlan0: doBoolean: SCAN
09-13 09:18:51.014  1035  1523 D WifiNative-wlan0: SCAN: returned false
,09-13 09:18:51.015  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=197706  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 09:18:51.015  1035  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.015  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,09-13 09:18:51.017  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 09:18:51.017  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:51.018  6830  7444 V FormManager: Network unavailable.
09-13 09:18:51.018  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:51.019  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=197711  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 09:18:51.020  1035  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:51.021  1035  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:51.022  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.022  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:51.022  1035  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:51.023  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.023  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.023  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 09:18:51.024  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.024  1035  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:51.024  1035  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 09:18:51.025  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:51.025  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 09:18:51.026  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:51.028  6667  7446 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 09:18:51.028  6667  7446 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 09:18:51.029  6542  6542 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 09:18:51.029  6542  6542 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 09:18:51.030  6542  6542 V [BNRBootReceiver]: Boot Receiver Return
09-13 09:18:51.032  4277  7448 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:51.033  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.034  4277  7449 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 09:18:51.035  4277  7449 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:51.039  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:51.046  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.050  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 09:18:51.050  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 09:18:51.051  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:51.555  6667  7446 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 09:18:51.556  6667  7446 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 09:18:51.562  6667  7446 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:18:51.562  6667  7446 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:18:51.563  6667  7459 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 09:18:51.564  6667  7459 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 09:18:51.564  6667  7459 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:18:51.564  6667  7459 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:18:51.565  6667  7459 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 09:18:51.566  6667  7446 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 09:18:51.572  6667  7462 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 925, name: OutgoingSocketThread/Sender)
,09-13 09:18:51.575  6667  7465 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 928, name: IncomingSocketThread/Receiver)
09-13 09:18:51.576  6667  7465 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 928, thread name: IncomingSocketThread/Receiver)
09-13 09:18:51.576  6667  7464 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 927, name: IncomingSocketThread/Sender)
09-13 09:18:51.577  6667  7463 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 926, name: OutgoingSocketThread/Receiver)
09-13 09:18:51.577  6667  7463 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 926, thread name: OutgoingSocketThread/Receiver)
09-13 09:18:51.577  6667  7463 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 09:18:51.578  6667  7463 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 926, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 09:18:51.579  6667  7465 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 09:18:51.579  6667  7465 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 928, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 09:18:51.591  7419  7419 E wpa_supplicant: USIM:  scard_init function
09-13 09:18:51.592  7419  7419 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-13 09:18:51.599  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 09:18:51.599  1035  7440 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 09:18:51.599  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 09:18:51.599  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-13 09:18:51.599  1035  7440 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 09:18:51.599  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 09:18:51.599  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 09:18:51.601  1035  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:51.601  1035  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:51.601  1035  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:51.602  1035  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 09:18:51.602  1035  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 09:18:51.618  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=198309  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 09:18:51.629  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.629  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 09:18:51.635  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.637  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.637  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.637  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-13 09:18:51.649  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.649  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.649  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 09:18:51.649  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=198341  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 09:18:51.650  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:51.650  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 09:18:51.655  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.655  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:51.657  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-13 09:18:51.664  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:51.674  6787  6787 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 09:18:51.679  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.691  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:51.700  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.707  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.707  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 09:18:51.711  6810  6810 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 09:18:51.715  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.724  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:51.730  7419  7419 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 09:18:51.735  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 09:18:51.735  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 09:18:51.735  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 09:18:51.735  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 09:18:51.735  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:51.735  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:51.742  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-13 09:18:51.741  7419  7419 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 09:18:51.748  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:51.749  7419  7419 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 09:18:51.752  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=198444  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 09:18:51.754  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=198445  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 09:18:51.758  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 09:18:51.759  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 09:18:51.760  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 09:18:51.760  1035  7440 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 09:18:51.760  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 09:18:51.760  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 09:18:51.760  1035  7440 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 09:18:51.762  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.763  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:51.763  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:51.768  1035  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198459
09-13 09:18:51.771  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.772  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.772  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:51.772  1035  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198464
09-13 09:18:51.772  1035  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198464
09-13 09:18:51.773  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198464
09-13 09:18:51.773  1035  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198465
09-13 09:18:51.774  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=198465  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 09:18:51.783  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.783  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:51.784  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.784  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.784  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 09:18:51.784  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.785  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=198476  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 09:18:51.785  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=198477  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 09:18:51.786  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 09:18:51.786  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 09:18:51.786  6787  6787 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 09:18:51.786  6787  6787 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 09:18:51.786  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=198477  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 09:18:51.786  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 09:18:51.787  1035  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:51.787  1035  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:51.787  1035  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 09:18:51.788  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-13 09:18:51.789  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 09:18:51.790  1035  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198481
09-13 09:18:51.790  1035  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198482
09-13 09:18:51.790  1035  1523 D WifiNative-wlan0: doString: [STATUS]
09-13 09:18:51.791  1035  7440 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 09:18:51.791  1035  7440 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 09:18:51.791  1035  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 09:18:51.792  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.792  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.792  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 09:18:51.792  6787  6787 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 09:18:51.792  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 09:18:51.792  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 09:18:51.792  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 09:18:51.792  6787  6787 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 09:18:51.792  6787  6787 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 09:18:51.793  1035  1523 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 09:18:51.793  6787  6787 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 09:18:51.796  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.799  1035  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 09:18:51.799  1035  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-13 09:18:51.804  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.804  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:51.805  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.810  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.810  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.810  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 09:18:51.811  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.811  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.811  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 09:18:51.812  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:51.813  1035  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 09:18:51.813  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 09:18:51.814  1035  1530 D ConnectivityService: Got NetworkAgent Messenger
09-13 09:18:51.814  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 09:18:51.814  1035  1530 D ConnectivityService: NetworkAgent connected
09-13 09:18:51.813  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 09:18:51.814  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 09:18:51.814  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 09:18:51.819  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.819  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 09:18:51.819  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 09:18:51.819  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 09:18:51.819  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 09:18:51.819  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 09:18:51.822  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 09:18:51.824   307   893 D CommandListener: Setting iface cfg
09-13 09:18:51.824  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.824  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.825  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 09:18:51.826  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 09:18:51.826  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:51.827  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.829  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.829  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:51.830  1035  1523 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 09:18:51.830  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:51.831  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=198522  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:51.831  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=198523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:51.831  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.831  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=198523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:51.832  1035  7485 D DhcpStateMachine: StoppedState
09-13 09:18:51.832  1035  7485 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.832  1035  7485 D DhcpStateMachine: WaitBeforeStartState
09-13 09:18:51.834  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:51.834  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 09:18:51.837  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:51.837  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198529  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:51.838  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198529  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 09:18:51.838  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198530  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 09:18:51.840  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:853] from screen [on:0 period:577349312] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:51.840  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:51.840  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 09:18:51.841  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:577349313] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:51.841  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 09:18:51.843  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.845  1035  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-13 09:18:51.846  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:51.846  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:51.846  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:51.847  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:51.847  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:51.847  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.847  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 09:18:51.848  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 09:18:51.848  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:51.848  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 09:18:51.848  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=156,0,0
09-13 09:18:51.849  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=156,0,0
09-13 09:18:51.849  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 09:18:51.849  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 09:18:51.849  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 09:18:51.849  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 09:18:51.850  1035  1523 D WifiNative-wlan0: SET ps 0: returned true
09-13 09:18:51.850  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 09:18:51.850  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 09:18:51.850  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 09:18:51.850  1035  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 09:18:51.850  1035  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 09:18:51.850  1035  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f2e628 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.851  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f2e628 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.851  1035  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-13 09:18:51.851  1035  7485 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.851  1035  7485 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 09:18:51.851   307   893 D CommandListener: Setting iface cfg
09-13 09:18:51.851   307   893 D CommandListener: Trying to bring up wlan0
09-13 09:18:51.852  1035  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 09:18:51.853  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 09:18:51.853  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 09:18:51.853  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 09:18:51.853  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 09:18:51.853  1035  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.854  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.854  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 09:18:51.854  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.854  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 09:18:51.854  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.854  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:51.856  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 09:18:51.856  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 09:18:51.856  7419  7419 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 09:18:51.857  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 09:18:51.857  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 09:18:51.857  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.862  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:51.867  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.872  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.872  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.872  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 09:18:51.874  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 09:18:51.876  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
09-13 09:18:51.876  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 09:18:51.877  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:51.877  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:51.877  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:51.878  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:51.878  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:51.878  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:51.879  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 09:18:51.879  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 09:18:51.880  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 09:18:51.880  1035  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 09:18:51.880  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:51.880  1035  1530 D ConnectivityService: ignoring duplicate network state non-change
09-13 09:18:51.883  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.883  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.884  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 09:18:51.884  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.884  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 09:18:51.885  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.887  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.887  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.887  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 09:18:51.887  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.888  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 09:18:51.888  1035  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 09:18:51.889  1035  1530 D ConnectivityService: Adding iface wlan0 to network 102
09-13 09:18:51.889  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.891  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 09:18:51.893  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 09:18:51.895  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.895  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.895  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 09:18:51.896  1035  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 09:18:51.896  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.898  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-13 09:18:51.901  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.901  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:51.901  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-13 09:18:51.906  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.906  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 09:18:51.907  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.909  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.909  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.909  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 09:18:51.912  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:51.912  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 09:18:51.913  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.913  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.913  1035  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 09:18:51.913  1035  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-13 09:18:51.914  1035  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-13 09:18:51.915   307   893 E Netd    : netlink response contains error (File exists)
09-13 09:18:51.915  1035  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-13 09:18:51.916  1035  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 09:18:51.916  1035  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-13 09:18:51.916  1035  1530 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-13 09:18:51.917  1035  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 09:18:51.917  1035  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:51.917  1035  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:51.917  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 09:18:51.918  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:51.918  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:51.918  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:51.918  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.918  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 09:18:51.918  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:51.918  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:51.918  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 09:18:51.918  1035  1530 D ConnectivityService: currentScore = 0, newScore = 20
09-13 09:18:51.918  1035  1530 D ConnectivityService:    accepting network in place of null
09-13 09:18:51.918  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 09:18:51.918  1035  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:51.918  1035  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:51.919  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kb,ps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:51.919  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:51.919  1035  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 09:18:51.919  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 09:18:51.919  1035  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 09:18:51.919  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 09:18:51.921   307  7489 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 09:18:51.923  1035  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:51.923  1035  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,09-13 09:18:51.923  1035  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 09:18:51.927  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:51.928  1035  1530 D ConnectivityService: validation of new default Network = false
09-13 09:18:51.928  1035  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 09:18:51.928  1035  1530 D DSQN    : enableDataServiceNotify 
09-13 09:18:51.928  1035  1530 D DSQN    : start dsqn bin
09-13 09:18:51.931  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 09:18:51.931  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 09:18:51.931  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 09:18:51.931  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-13 09:18:51.935  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:51.936  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:51.936  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:51.936  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:51.919  7490  7490 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:51.919  7490  7490 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:51.938  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 09:18:51.942  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.950  7490  7490 E DSQN    : DSQN ssw
,09-13 09:18:51.953  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.954  1035  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 09:18:51.954  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.954  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 09:18:51.957  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.963  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:51.970  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.970  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 09:18:51.971  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.971  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:51.974  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.974  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.975  6810  6810 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 09:18:51.978  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 09:18:51.981  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 09:18:51.981  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:51.984  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 09:18:51.987  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:51.995  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:51.995  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:51.996  6810  6810 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 09:18:51.996  6810  6810 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 09:18:51.997  6810  6810 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 09:18:52.001  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 09:18:52.004  6767  6767 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 09:18:52.004  6767  6767 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 09:18:52.006  6787  6787 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 09:18:52.011  6787  6787 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 09:18:52.016  6810  6810 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 09:18:52.016  6810  6810 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 09:18:52.017  6810  6810 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-13 09:18:52.017  6810  6810 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 09:18:52.017  6810  6810 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 09:18:52.022   307  7489 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 09:18:52.042  6667  6728 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 09:18:52.043  6667  6728 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 09:18:52.045  6667  6728 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@125ccbf3 Bundle[{}]
09-13 09:18:52.046  6667  6728 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 09:18:52.046  6667  6728 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 09:18:52.047  6667  6728 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 09:18:52.047  6667  6728 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 09:18:52.048  6667  6728 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 09:18:52.049  6667  6728 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 09:18:52.053  1035  7485 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 09:18:52.054  1035  7485 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-13 09:18:52.054  1035  7485 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 09:18:52.039  7494  7494 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:52.039  7494  7494 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 09:18:52.061  6667  7495 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 09:18:52.061  6667  7495 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 09:18:52.064  7494  7494 I dhcpcd  : version 5.5.6 starting
,09-13 09:18:52.065  7494  7494 E dhcpcd  : get_duid: m
09-13 09:18:52.065  7494  7494 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 09:18:52.065  7494  7494 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 09:18:52.066   307  7489 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 09:18:52.075  6667  7498 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 09:18:52.075  6667  7498 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 09:18:52.075  6667  7498 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:18:52.076  6667  7498 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 09:18:52.077  6667  7495 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 09:18:52.077  6667  7495 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 09:18:52.077  6667  7498 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 09:18:52.077  6667  7495 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:18:52.080  6667  7502 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 939, name: IncomingSocketThread/Sender)
09-13 09:18:52.080  6667  7495 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:18:52.083  6667  7503 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 940, name: IncomingSocketThread/Receiver)
09-13 09:18:52.084  6667  7504 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 941, name: OutgoingSocketThread/Sender)
09-13 09:18:52.084  6667  7495 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 09:18:52.085  6667  7505 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 942, name: OutgoingSocketThread/Receiver)
09-13 09:18:52.085  6667  7505 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 942, thread name: OutgoingSocketThread/Receiver)
09-13 09:18:52.085  6667  7505 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 09:18:52.085  6667  7505 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 942, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 09:18:52.087  6667  7503 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 940, thread name: IncomingSocketThread/Receiver)
,09-13 09:18:52.087  6667  7503 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 09:18:52.087  6667  7503 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 940, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 09:18:52.096   307   892 D LGDataListener: argv[0]=dsqncommand
09-13 09:18:52.096   307   892 D LGDataListener: argv[1]=wlan0
09-13 09:18:52.096   307   892 D LGDataListener: argv[2]=1
09-13 09:18:52.096   307   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 09:18:52.096  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 09:18:52.096  1035  1115 D DSQN    : start to monitor internet connection
09-13 09:18:52.142  7494  7494 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 09:18:52.142  7494  7494 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 09:18:52.142  7494  7494 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 09:18:52.143  7494  7494 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 09:18:52.143  7494  7494 D dhcpcd  : wlan0: sending REQUEST (xid 0xd187b46e), next in 3.86 seconds
,09-13 09:18:52.172  7494  7494 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 09:18:52.179  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:18:52 GMT], X-Android-Received-Millis=[1473751132178], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473751132095]}
,09-13 09:18:52.179  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 09:18:52.179  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 09:18:52.179  1035  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 09:18:52.180  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 09:18:52.180  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:52.180  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:52.180  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:52.181  1035  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 09:18:52.181  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:52.181  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:52.181  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:52.183  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:52.184  1035  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:52.184  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 09:18:52.184  1035  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:52.184  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 09:18:52.185  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:52.187  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:52.188  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 09:18:52.189  7494  7494 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 09:18:52.189  7494  7494 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 09:18:52.190  7494  7494 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 09:18:52.190  7494  7494 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 09:18:52.191  7494  7494 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-13 09:18:52.192  7494  7494 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-13 09:18:52.192  7494  7494 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-13 09:18:52.192  7494  7494 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 09:18:52.216  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 09:18:52.218  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 09:18:52.220  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:52.443  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.444  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:52.452  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 09:18:52.452  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 09:18:52.461  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:52.462  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 09:18:52.474  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 09:18:52.475  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.477  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:52.477  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:52.485  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:52.489  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:52.491  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:52.494  6667  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:52.497  6667  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:52.499  6368  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 09:18:52.504  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:52.506  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:52.509  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:52.519  5652  5652 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 09:18:52.525  5652  5652 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 09:18:52.536  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7512
09-13 09:18:52.536  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7531
09-13 09:18:52.541  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:52.545  1035  1962 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-13 09:18:52.546  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:52.546  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:52.546  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 09:18:52.546  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 09:18:52.546  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 09:18:52.549   307  7541 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 09:18:52.549   307  7541 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 09:18:52.553  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 09:18:52.553  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.553  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 09:18:52.553  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 09:18:52.555  6997  6997 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 09:18:52.558  6997  6997 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26d221b9
09-13 09:18:52.558  6997  6997 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 09:18:52.558  6997  6997 D AppUp4:CustFacade: isPhone : true
09-13 09:18:52.558  6997  6997 D AppUp4:CustModeStarterReceiver: begin check event
09-13 09:18:52.559  6997  6997 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 09:18:52.562  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.562  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:52.564  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:52.566  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:52.570  2832  2832 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:52.577  6667  6728 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 951)
09-13 09:18:52.578  6667  6728 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 09:18:52.579  6667  6728 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 952)
09-13 09:18:52.579  4277  7543 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:52.581  2832  2832 V DownloadManager: DownloadService onCreate
09-13 09:18:52.582  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 09:18:52.582  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@200f4155 added. We now have 5 listener(s)
,09-13 09:18:52.583  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:52.583  4277  7544 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.584  4277  7544 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:52.584  4277  7543 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 09:18:52.585  2832  7545 I DownloadManager: in removeSpuriousFiles
09-13 09:18:52.585  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 09:18:52.585  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 09:18:52.585  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 09:18:52.586  2832  7545 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 09:18:52.586  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 09:18:52.586  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2924e76a added. We now have 5 listener(s)
09-13 09:18:52.586  6667  6728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 09:18:52.587  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:18:52 GMT], X-Android-Received-Millis=[1473751132586], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473751132547]}
09-13 09:18:52.587  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 09:18:52.587  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 09:18:52.587  1035  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 09:18:52.587  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 09:18:52.587  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:52.587  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:52.587  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:52.587  1035  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 09:18:52.587  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:52.587  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:52.587  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:52.588  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:52.588  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 09:18:52.588  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 5,24290
09-13 09:18:52.590  2832  7545 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@296fc3c3 on behalf of 2832
09-13 09:18:52.592  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:52.592  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 09:18:52.592  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 09:18:52.592  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 09:18:52.593   307  7541 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-13 09:18:52.595  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 09:18:52.596  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 09:18:52.596  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 09:18:52.596  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 09:18:52.596  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 09:18:52.596  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 09:18:52.596  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 09:18:52.596  2832  7545 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 09:18:52.597  2832  7545 I DownloadManager: in trimDatabase
09-13 09:18:52.597  2832  7545 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 09:18:52.598  2832  7545 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1e0df440 on behalf of 2832
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 09:18:52.599  6667  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 09:18:52.604  6667  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 09:18:52.604  6667  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 09:18:52.607  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:52.607  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:52.607  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:52.607  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:52.607  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 09:18:52.608  6667  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@200f4155 removed from the list
09-13 09:18:52.608  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:52.608  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2924e76a removed from the list
09-13 09:18:52.609  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:52.609  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:52.609  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:52.609  7026  7548 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:52.611  4277  7543 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 09:18:52.615  3440  3440 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 09:18:52.615  3440  3440 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.615  3440  3440 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 09:18:52.618  2832  2832 V DownloadManager: DownloadService onStartCommand
,09-13 09:18:52.618  2832  7546 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 09:18:52.619  4277  4277 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 09:18:52.619  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:52.619  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 09:18:52.619  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 09:18:52.619  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:52.619  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:18:52.619  4277  4277 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 09:18:52.619  4277  4277 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 09:18:52.621  4277  4277 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 09:18:52.621  2832  7546 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2980d91f on behalf of 2832
09-13 09:18:52.623  2832  7546 V DownloadManager: processing inserted download 1
09-13 09:18:52.624  6667  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 09:18:52.624  1035  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 09:18:52.625  2832  7546 V DownloadManager: processing inserted download 4
09-13 09:18:52.625  4277  4277 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 09:18:52.627  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 09:18:52.627  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 09:18:52.627  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 09:18:52.628  2832  7546 V DownloadManager: processing inserted download 7
09-13 09:18:52.628  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 09:18:52.628  2832  7546 V DownloadManager: processing inserted download 8
09-13 09:18:52.629  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:18:52.630  2832  7546 V DownloadManager: processing inserted download 9
09-13 09:18:52.631  2832  7546 V DownloadManager: processing inserted download 10
09-13 09:18:52.632  2832  7546 V DownloadManager: processing inserted download 11
09-13 09:18:52.632  2832  7546 V DownloadManager: processing inserted download 12
09-13 09:18:52.633  2832  7546 V DownloadManager: processing inserted download 13
09-13 09:18:52.633  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 09:18:52.636   307  7554 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 09:18:52.636   307  7554 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-13 09:18:52.637  6667  6728 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 09:18:52.637  2832  7546 V DownloadManager: processing inserted download 14
09-13 09:18:52.638  2832  7546 V DownloadManager: processing inserted download 16
09-13 09:18:52.642  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:52
09-13 09:18:52.643  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-13 09:18:52.643  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
09-13 09:18:52.644  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 09:18:52.644  7169  7169 D WeatherAncestor: connectivity changed - connection : true
09-13 09:18:52.644  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3167355f
09-13 09:18:52.645  2832  2832 V DownloadManager: DownloadService onDestroy
09-13 09:18:52.645  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 09:18:52.645  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 09:18:52.645  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,09-13 09:18:52.645  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 09:18:52.646  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:52
09-13 09:18:52.660  1035  7485 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 09:18:52.662  1035  7485 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 09:18:52.662  1035  7485 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 09:18:52.662  1035  7485 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 09:18:52.662  1035  7485 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 09:18:52.662  1035  7485 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 09:18:52.662  1035  7485 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 09:18:52.662  1035  7485 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 09:18:52.662  1035  7485 D DhcpStateMachine: RunningState
,09-13 09:18:52.664  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 09:18:52.665  6368  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 09:18:52.676  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:52.683  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 09:18:52.683  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.684  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 09:18:52.684  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 09:18:52.685  6997  6997 I AppUp4:CustModeStarterReceiver: onReceive
09-13 09:18:52.687  6997  6997 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26d221b9
09-13 09:18:52.687  6997  6997 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 09:18:52.687  6997  6997 D AppUp4:CustFacade: isPhone : true
09-13 09:18:52.688  6997  6997 D AppUp4:CustModeStarterReceiver: begin check event
09-13 09:18:52.688  6997  6997 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-13 09:18:52.693  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.693  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:52.695  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:52.698  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:52.703  2832  2832 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:52.705  2832  2832 V DownloadManager: DownloadService onCreate
09-13 09:18:52.705  4277  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.706  4277  7558 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:52.706  4277  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:52.707  2832  7560 I DownloadManager: in removeSpuriousFiles
09-13 09:18:52.709  4277  7558 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 09:18:52.713  2832  7560 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 09:18:52.715  2832  7560 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3fefca35 on behalf of 2832
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 09:18:52.716  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 09:18:52.717  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 09:18:52.717  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
,09-13 09:18:52.717  2832  7560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 09:18:52.717  4277  7558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-13 09:18:52.720  2832  2832 V DownloadManager: DownloadService onStartCommand
09-13 09:18:52.720  2832  7561 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-13 09:18:52.722  4277  4277 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,09-13 09:18:52.724  4277  4277 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 09:18:52.724  4277  4277 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 09:18:52.726  2832  7561 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2fee0b58 on behalf of 2832
09-13 09:18:52.727  7026  7563 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 09:18:52.727  2832  7560 I DownloadManager: in trimDatabase
09-13 09:18:52.727  2832  7560 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 09:18:52.729  4277  4277 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 09:18:52.731  2832  7560 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@ddfd4b1 on behalf of 2832
,09-13 09:18:52.733  3440  3440 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 09:18:52.733  3440  3440 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:52.733  3440  3440 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 09:18:52.734  2832  7561 V DownloadManager: processing inserted download 1
09-13 09:18:52.736  2832  7561 V DownloadManager: processing inserted download 4
09-13 09:18:52.736  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 09:18:52.737  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 09:18:52.737  2832  7561 V DownloadManager: processing inserted download 7
09-13 09:18:52.738  2832  7561 V DownloadManager: processing inserted download 8
09-13 09:18:52.740  4277  4277 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 09:18:52.740  2832  7561 V DownloadManager: processing inserted download 9
09-13 09:18:52.741   307  7554 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-13 09:18:52.741  2832  7561 V DownloadManager: processing inserted download 10
09-13 09:18:52.743  2832  7561 V DownloadManager: processing inserted download 11
09-13 09:18:52.745  2832  7561 V DownloadManager: processing inserted download 12
09-13 09:18:52.747  2832  7561 V DownloadManager: processing inserted download 13
,09-13 09:18:52.748  2832  7561 V DownloadManager: processing inserted download 14
09-13 09:18:52.749  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:52
09-13 09:18:52.750  2832  7561 V DownloadManager: processing inserted download 16
09-13 09:18:52.752  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 09:18:52.752  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
09-13 09:18:52.752  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 09:18:52.753  2832  2832 V DownloadManager: DownloadService onDestroy
09-13 09:18:52.753  7169  7169 D WeatherAncestor: connectivity changed - connection : true
09-13 09:18:52.753  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3167355f
09-13 09:18:52.754  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 09:18:52.754  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 09:18:52.754  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 09:18:52.754  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 09:18:52.754  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:52
,09-13 09:18:52.937  1035  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 09:18:53.089  7209  7230 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-13 09:18:53.434  1035  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:53.434  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:53.435  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:53.435  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:53.436  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 09:18:53.436  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 09:18:53.449  1035  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-13 09:18:53.449  1035  1530 D ConnectivityService: identical MTU - not setting
09-13 09:18:53.449  1035  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 09:18:53.449  1035  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:53.450  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:53.450  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:53.450  1035  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 09:18:53.454  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-13 09:18:53.532  2214  7566 D GCM     : Connected
,09-13 09:18:53.583  2214  7566 D GCM     : Message class com.google.e.a.a.q
,09-13 09:18:53.945  1035  1978 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
09-13 09:18:53.945  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:53.945  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:53.945  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 09:18:53.945  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:53.945  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 09:18:53.966  1035  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,09-13 09:18:53.984  1035  1926 I ActivityManager: Killing 6923:com.lge.settings.easy/1000 (adj 15): empty #17
,09-13 09:18:54.015  1035  2019 W libprocessgroup: failed to open /acct/uid_1000/pid_6923/cgroup.procs: No such file or directory
,09-13 09:18:54.153  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:18:54 GMT], X-Android-Received-Millis=[1473751134150], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473751133958]}
,09-13 09:18:54.153  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 09:18:54.153  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-13 09:18:54.161  1035  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 09:18:54.161  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 09:18:54.162  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:54.162  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:54.162  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:54.162  1035  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 09:18:54.162  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:54.162  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:54.162  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:54.163  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:54.164  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 09:18:54.165  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-199ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:54.165  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-199ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:54.165  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 09:18:54.165  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:54.165  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 09:18:54.202  6830  7552 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 09:18:54.212  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:18:54 GMT], X-Android-Received-Millis=[1473751134211], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473751134170]}
09-13 09:18:54.212  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 09:18:54.212  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 09:18:54.213  1035  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 09:18:54.213  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 09:18:54.213  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:54.213  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:54.214  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:54.214  1035  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 09:18:54.214  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:54.214  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 09:18:54.214  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:54.215  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 09:18:54.216  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 09:18:54.221  6830  7552 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-13 09:18:54.293  6830  7580 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 09:18:54.300  6830  7580 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 09:18:54.323  1035  1908 I ActivityManager: Killing 6897:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-13 09:18:54.354  1035  2010 W libprocessgroup: failed to open /acct/uid_10037/pid_6897/cgroup.procs: No such file or directory
,09-13 09:18:54.415  1035  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 09:18:54.415  1035  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 09:18:54.416  1035  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 09:18:54.436  1035  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 09:18:54.436  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 09:18:54.436  1035  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 09:18:54.437  1035  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 09:18:54.437  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 09:18:54.438  1035  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 09:18:54.849  1035  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=78.0, 0.0, 0.0  rx=79.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:577352321] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 09:18:54.852  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=78.0, 0.0, 0.0  rx=79.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:577352324] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:54.853  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 09:18:54.873  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 09:18:54.893  1035  1525 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-13 09:18:54.924  1035  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:54.942  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 09:18:54.953  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:54.960  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:54.962  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:54.965  6667  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 09:18:54.969  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 09:18:54.974  6368  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 09:18:54.985  5652  5652 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 09:18:55.004  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:55.019  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 09:18:55.020  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:55.020  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 09:18:55.020  6997  6997 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 09:18:55.025  6997  6997 I AppUp4:CustModeStarterReceiver: onReceive
09-13 09:18:55.029  6997  6997 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26d221b9
09-13 09:18:55.029  6997  6997 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 09:18:55.029  6997  6997 D AppUp4:CustFacade: isPhone : true
09-13 09:18:55.030  6997  6997 D AppUp4:CustModeStarterReceiver: begin check event
09-13 09:18:55.030  6997  6997 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 09:18:55.035  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:55.035  4277  4277 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 09:18:55.036  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 09:18:55.042  4277  4277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 09:18:55.052   307  7583 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 09:18:55.055   307  7583 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 09:18:55.055   307  7583 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-13 09:18:55.061  2832  2832 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:55.069  2832  2832 V DownloadManager: DownloadService onCreate
,09-13 09:18:55.096  2832  7584 I DownloadManager: in removeSpuriousFiles
,09-13 09:18:55.105  2832  7584 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 09:18:55.108  3440  3440 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 09:18:55.108  3440  3440 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 09:18:55.108  3440  3440 I LgeMiscReceiver: networkInfo.isConnected() = true
,09-13 09:18:55.108  3440  3440 D PhoneState: setPdpRejectCasuse : false
09-13 09:18:55.111  2832  2832 V DownloadManager: DownloadService onStartCommand
09-13 09:18:55.117  4277  7601 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 09:18:55.118  2832  7584 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16ec0aed on behalf of 2832
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 09:18:55.119  2832  7584 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 09:18:55.120  4277  7609 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-13 09:18:55.120  4277  7609 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 09:18:55.122  7026  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 09:18:55.123  2832  7585 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 09:18:55.124  4277  7601 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 09:18:55.127  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 09:18:55.127  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 09:18:55.127  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 09:18:55.128  2832  7584 I DownloadManager: in trimDatabase
09-13 09:18:55.128  2832  7584 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 09:18:55.135  2832  7584 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@e230d22 on behalf of 2832
,09-13 09:18:55.138  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:55
09-13 09:18:55.139  2832  7585 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d3923b3 on behalf of 2832
09-13 09:18:55.141  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 09:18:55.141  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
09-13 09:18:55.141  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 09:18:55.141  7169  7169 D WeatherAncestor: connectivity changed - connection : true
09-13 09:18:55.142  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3167355f
09-13 09:18:55.142  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 09:18:55.142  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 09:18:55.142  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 09:18:55.142  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 09:18:55.143  4277  7601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 09:18:55.143  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:18:55
09-13 09:18:55.144  6830  7600 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 09:18:55.145  2832  7585 V DownloadManager: processing inserted download 1
09-13 09:18:55.146  6830  7600 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 09:18:55.147  2832  7585 V DownloadManager: processing inserted download 4
09-13 09:18:55.148  4277  4277 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 09:18:55.148  4277  4277 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 09:18:55.149  4277  4277 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-13 09:18:55.151  4277  4277 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 09:18:55.155  2832  7585 V DownloadManager: processing inserted download 7
09-13 09:18:55.156  2832  7585 V DownloadManager: processing inserted download 8
09-13 09:18:55.157  2832  7585 V DownloadManager: processing inserted download 9
09-13 09:18:55.158  2832  7585 V DownloadManager: processing inserted download 10
09-13 09:18:55.160  4277  4277 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 09:18:55.162  2832  7585 V DownloadManager: processing inserted download 11
09-13 09:18:55.163  2832  7585 V DownloadManager: processing inserted download 12
09-13 09:18:55.164  2832  7585 V DownloadManager: processing inserted download 13
09-13 09:18:55.164  2832  7585 V DownloadManager: processing inserted download 14
09-13 09:18:55.165  2832  7585 V DownloadManager: processing inserted download 16
,09-13 09:18:55.170  2832  2832 V DownloadManager: DownloadService onDestroy
,09-13 09:18:55.188  1035  1998 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,09-13 09:18:55.188  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:55.189  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:55.189  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 09:18:55.189  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 09:18:55.189  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-13 09:18:55.236  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 07:18:55 GMT], X-Android-Received-Millis=[1473751135235], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473751135191]}
,09-13 09:18:55.236  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 09:18:55.237  1035  7484 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 09:18:55.237  1035  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 09:18:55.237  1035  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 09:18:55.237  1035  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 09:18:55.238  1035  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 09:18:55.238  1035  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 09:18:55.238  1035  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 09:18:55.238  1035  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 09:18:55.239  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 09:18:55.239  1035  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 09:18:55.242  1035  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 09:18:55.246  1588  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 09:18:55.637  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 09:18:55.637  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 09:18:55.654  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:55.654  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:55.654  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:55.654  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@200f4155 not in the list
09-13 09:18:55.654  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:55.654  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2924e76a not in the list
09-13 09:18:55.654  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:55.654  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:55.654  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:55.656  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 09:18:55.657  6667  6728 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 09:18:55.657  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 09:18:55.662  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 09:18:55.662  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 09:18:55.662  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 09:18:55.662  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:55.665  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 09:18:55.666  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 09:18:55.666  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 09:18:55.667  6667  6667 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 09:18:55.669  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 09:18:55.669  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 09:18:55.669  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:55.669  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 09:18:55.680  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:18:55.678  1035  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 09:18:55.684  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 09:18:55.686  6667  6728 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 09:18:55.686  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:55.687  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 09:18:55.687  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 09:18:55.687  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 09:18:55.687  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:55.687  6667  6728 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 09:18:55.687  6667  6667 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 09:18:55.687  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@200f4155 not in the list
09-13 09:18:55.687  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:55.687  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2924e76a not in the list
09-13 09:18:55.687  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:55.687  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:55.688  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:55.689  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:55.689  6667  6728 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 09:18:55.689  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 09:18:55.689  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 09:18:55.689  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 09:18:55.692  6667  7621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 09:18:55.695  3840  6730 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=109 mFd=107
,09-13 09:18:55.700  6667  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 09:18:55.700  6667  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 09:18:55.700  6667  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 09:18:55.702  6667  6728 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 09:18:55.702  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:55.703  6667  6667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 09:18:55.705  6667  6728 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 09:18:56.107   307  7622 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 09:18:56.112   307  7622 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-13 09:18:56.146   307  7622 D libc-netbsd: res_queryN name = www.google.com succeed
,09-13 09:18:56.157   307  7624 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 09:18:56.157   307  7624 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 09:18:56.160   307  7624 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 09:18:56.221  1035  1526 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-13 09:18:57.136  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 09:18:57.152  1035  1418 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 09:18:57.280  1035  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7625 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 09:18:57.286  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-13 09:18:57.287  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 09:18:57.292  1035  1035 D administrator: Handling package changes for user 0
09-13 09:18:57.300   343   343 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 481us total 44.646ms
,09-13 09:18:57.303  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 09:18:57.322   343   343 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 20.239ms
,09-13 09:18:57.343   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 19.155ms
09-13 09:18:57.351  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 09:18:57.358  7625  7625 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 09:18:57.384  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-13 09:18:57.384  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 09:18:57.424  7625  7625 D LgDataFeature: LgDataFeature() Constructor: none
09-13 09:18:57.424  7625  7625 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 09:18:57.438  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 09:18:57.443  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 09:18:57.450  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 09:18:57.452  2437  2437 V GmsNetworkLocationProvi: DISABLE
,09-13 09:18:57.481  1035  1097 D LocationProviderProxy: applying state to connected service
,09-13 09:18:57.485  2437  2437 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-13 09:18:57.516  7625  7671 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 09:18:57.516  7625  7671 I Babel   : MmsConfig.loadMmsSettings
,09-13 09:18:57.519  7625  7671 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 09:18:57.519  7625  7671 I Babel   : MmsConfig.loadFromDatabase
,09-13 09:18:57.528  7625  7671 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-13 09:18:57.528  7625  7671 I Babel   : MmsConfig.loadFromResources
,09-13 09:18:57.544  7625  7671 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 09:18:57.545  7625  7671 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-13 09:18:57.553  7625  7625 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 09:18:57.577  1802  7672 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-13 09:18:57.578  1802  7672 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-13 09:18:57.581  6997  6997 I AppUp4:CustModeStarterReceiver: onReceive
09-13 09:18:57.584  7625  7669 W AudioCapabilities: Unsupported mime audio/evrc
09-13 09:18:57.585  6997  6997 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26d221b9
09-13 09:18:57.585  6997  6997 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 09:18:57.585  6997  6997 D AppUp4:CustFacade: isPhone : true
09-13 09:18:57.585  6997  6997 D AppUp4:CustModeStarterReceiver: begin check event
09-13 09:18:57.585  6997  6997 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 09:18:57.589  1802  4685 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-13 09:18:57.590  7625  7669 W AudioCapabilities: Unsupported mime audio/qcelp
,09-13 09:18:57.597  7625  7669 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 09:18:57.613  7625  7669 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 09:18:57.614  7625  7669 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 09:18:57.615  1035  1926 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7676 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-13 09:18:57.616  7625  7669 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 09:18:57.620  1035  1962 I ActivityManager: Killing 6542:com.lge.bnr/1000 (adj 15): empty #17
09-13 09:18:57.635  7625  7669 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 09:18:57.638  7625  7669 W VideoCapabilities: Unsupported mime video/divx
09-13 09:18:57.640  7625  7669 W VideoCapabilities: Unsupported mime video/divx311
09-13 09:18:57.642  7625  7669 W VideoCapabilities: Unsupported mime video/divx4
09-13 09:18:57.647  7625  7669 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-13 09:18:57.658  7625  7669 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 09:18:57.662  7625  7669 W AudioCapabilities: Unsupported mime audio/eac3
09-13 09:18:57.664  7625  7669 W AudioCapabilities: Unsupported mime audio/ac3
09-13 09:18:57.664  7625  7669 W AudioCapabilities: Unsupported mime audio/g726
09-13 09:18:57.665  7625  7669 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 09:18:57.666  7625  7669 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 09:18:57.666  7625  7669 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 09:18:57.668  7625  7669 W VideoCapabilities: Unsupported mime video/theora
09-13 09:18:57.669  7625  7669 W VideoCapabilities: Unsupported mime video/mjpg
,09-13 09:18:57.725  1035  1890 W libprocessgroup: failed to open /acct/uid_1000/pid_6542/cgroup.procs: No such file or directory
09-13 09:18:57.753  7676  7676 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 09:18:57.753  7676  7676 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 09:18:57.753  7676  7676 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 09:18:57.755  7676  7676 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 09:18:57.755  7676  7676 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-13 09:18:57.825  7676  7676 I SystemConfig: BUILD Country: EU
09-13 09:18:57.825  7676  7676 I SystemConfig: BUILD Operator: OPEN
,09-13 09:18:57.865  1035  2019 I ActivityManager: Killing 6767:com.lge.sync/1000 (adj 15): empty #17
,09-13 09:18:57.879  1035  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=63.5, 0.0, 0.0  rx=58.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:577355351] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:57.880  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=63.5, 0.0, 0.0  rx=58.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:577355352] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:18:57.880  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 09:18:57.944  1035  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_6767/cgroup.procs: No such file or directory
,09-13 09:18:57.950  7676  7694 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 09:18:57.950  7676  7694 I SystemConfig: existFile = false
09-13 09:18:57.950  7676  7694 I SystemConfig: canReadFile = false
09-13 09:18:57.950  7676  7694 I SystemConfig: systemFeature RCS result false
09-13 09:18:57.951  7676  7694 D SystemConfig: refreshRcsSupport() :false
,09-13 09:18:58.033  1035  2019 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7696 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-13 09:18:58.101  7696  7696 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 09:18:58.101  7696  7696 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 09:18:58.101  7696  7696 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 09:18:58.102  7696  7696 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 09:18:58.226  7696  7696 I AppConfig: Total System Memory = 2995761152
,09-13 09:18:58.238  7696  7696 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-13 09:18:58.306  1035  1890 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7721 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 09:18:58.308  1035  1890 I ActivityManager: Killing 6563:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-13 09:18:58.341  6810  6810 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 09:18:58.342  6810  6810 W System.err: android.os.DeadObjectException
09-13 09:18:58.342  6810  6810 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 09:18:58.342  6810  6810 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 09:18:58.343  6810  6810 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 09:18:58.343  6810  6810 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-13 09:18:58.343  6810  6810 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 09:18:58.343  6810  6810 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 09:18:58.343  6810  6810 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 09:18:58.343  6810  6810 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 09:18:58.343  6810  6810 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 09:18:58.343  6810  6810 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 09:18:58.344  6810  6810 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:18:58.344  6810  6810 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 09:18:58.344  6810  6810 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 09:18:58.344  6810  6810 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 09:18:58.344  6810  6810 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-13 09:18:58.345  6810  6810 W System.err: android.os.DeadObjectException
09-13 09:18:58.345  6810  6810 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 09:18:58.345  6810  6810 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 09:18:58.346  6810  6810 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-13 09:18:58.346  6810  6810 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 09:18:58.346  6810  6810 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 09:18:58.346  6810  6810 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 09:18:58.346  6810  6810 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 09:18:58.346  6810  6810 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 09:18:58.346  6810  6810 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 09:18:58.346  6810  6810 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 09:18:58.346  6810  6810 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:18:58.347  6810  6810 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 09:18:58.347  6810  6810 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 09:18:58.347  6810  6810 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 09:18:58.347  6810  6810 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 09:18:58.348  6810  6810 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-13 09:18:58.421  1035  1614 W libprocessgroup: failed to open /acct/uid_1000/pid_6563/cgroup.procs: No such file or directory
,09-13 09:18:58.422  1035  1614 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-13 09:18:58.432  6810  6810 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 09:18:58.433  6810  6810 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 09:18:58.529  1035  1908 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7749 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 09:18:58.530  6810  6810 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 09:18:58.625  7749  7749 D UEI.SmartControl: Quickset Services start...
,09-13 09:18:58.628  7749  7749 I UEI.SmartControl: Manufacture = LGE
,09-13 09:18:58.628  7749  7749 D UEI.SmartControl: Id = LGNevo
09-13 09:18:58.629  7749  7749 D UEI.SmartControl: File observer start...
09-13 09:18:58.630  7749  7749 E UEI.SmartControl: IR Port is disabled: false
09-13 09:18:58.631  7749  7749 D UEI.SmartControl: Starting file observer...
09-13 09:18:58.631  7749  7749 D UEI.SmartControl: Extracting JNI libs...
09-13 09:18:58.631  7749  7749 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-13 09:18:58.672  7721  7721 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 09:18:58.707  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:58.707  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:58.707  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:58.708  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@200f4155 not in the list
09-13 09:18:58.708  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:58.708  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2924e76a not in the list
09-13 09:18:58.708  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:58.708  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:58.708  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:58.711  6667  6728 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 09:18:58.711  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:58.711  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:58.712  6667  6728 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@200f4155 not in the list
09-13 09:18:58.712  6667  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 09:18:58.712  6667  6728 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2924e76a not in the list
09-13 09:18:58.712  6667  6728 D io.jxcore.node.ConnectivityMonitor: stop
09-13 09:18:58.712  6667  6728 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 09:18:58.712  6667  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 09:18:58.715  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 09:18:58.715  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 09:18:58.715  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 09:18:58.716  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 09:18:58.716  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 09:18:58.717  6667  6728 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 09:18:58.731  6667  7780 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 971, name: My test thread name)
09-13 09:18:58.742  7749  7749 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 09:18:58.742  7749  7749 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 09:18:58.742  7749  7749 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-13 09:18:58.781  7749  7749 I UEI.SmartControl: --- Selecting new region: 6
,09-13 09:18:58.782  7721  7721 D LgDataFeature: LgDataFeature() Constructor: none
09-13 09:18:58.782  7721  7721 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 09:18:58.783  7749  7749 I UEI.SmartControl: Model = LG-D855
09-13 09:18:58.785  7749  7749 D UEI.SmartControl: QS Service created
,09-13 09:18:58.801  7749  7749 I UEI.SmartControl: Service initServices...
09-13 09:18:58.806  7749  7749 D UEI.SmartControl: QS start get config
,09-13 09:18:58.840  7721  7721 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-13 09:18:58.848  7749  7749 D UEI.SmartControl: Loading JNI Libs...
09-13 09:18:58.859  7721  7721 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 09:18:58.860  7721  7721 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 09:18:58.879  7721  7721 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 09:18:58.880  7721  7721 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-13 09:18:58.901  1035  1978 I ActivityManager: Killing 6787:com.android.settings/1000 (adj 15): empty #17
,09-13 09:18:58.992  1035  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_6787/cgroup.procs: No such file or directory
,09-13 09:18:59.014  2832  6136 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-13 09:18:59.020  2832  6136 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@d0b68e9 on behalf of 7721
09-13 09:18:59.029  4546  7792 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-13 09:18:59.034  7721  7721 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-13 09:18:59.082  1035  1050 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7794 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 09:18:59.112  7721  7721 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 09:18:59.230  1035  1998 I art     : Explicit concurrent mark sweep GC freed 127097(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.956ms total 115.041ms
,09-13 09:18:59.242  7749  7749 I UEI.SmartControl: Supports setup maps: true
09-13 09:18:59.246  7749  7749 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 09:18:59.246  7749  7749 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 09:18:59.246  7749  7749 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 09:18:59.247  7749  7749 I UEI.SmartControl: ### init IR Blaster...
,09-13 09:18:59.259  7749  7749 D serial_port: Configuring serial port
,09-13 09:18:59.264  7749  7749 E UEI.SmartControl: UEIBLaster setting for 616
,09-13 09:18:59.264  7749  7749 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 09:18:59.265  7749  7749 I UEI.SmartControl: configuring settings for MAXQ616
09-13 09:18:59.265  7749  7749 I UEI.SmartControl: Get version...
09-13 09:18:59.274  7794  7794 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 09:18:59.281  7749  7819 D UEI.SmartControl: serial port data available: 21
09-13 09:18:59.297  7794  7794 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 09:18:59.297  7794  7794 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 09:18:59.298  7794  7794 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 09:18:59.298  7794  7794 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 09:18:59.298  7794  7794 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 09:18:59.298  7794  7794 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-13 09:18:59.307  7749  7749 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 09:18:59.307  7749  7749 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 09:18:59.307  7749  7749 I UEI.SmartControl: QS saving settings...
09-13 09:18:59.308  7749  7749 D UEI.SmartControl: IR Blaster version: 25672567
09-13 09:18:59.312  1035  1998 I ActivityManager: Killing 6810:com.lge.qremote/u0a112 (adj 15): empty #17
,09-13 09:18:59.324  7749  7819 D UEI.SmartControl: serial port data available: 4
,09-13 09:18:59.341  1035  1693 W libprocessgroup: failed to open /acct/uid_10112/pid_6810/cgroup.procs: No such file or directory
,09-13 09:18:59.362  7749  7824 I UEI.SmartControl: Device manager: loading config....
,09-13 09:18:59.364  7749  7824 D UEI.SmartControl: ----------- loading internal config...
09-13 09:18:59.364  7749  7749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 09:18:59.366  7749  7749 E UEI.SmartControl: Services init done
09-13 09:18:59.366  7749  7749 D UEI.SmartControl: QS Service init finished
09-13 09:18:59.367  7749  7749 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 09:18:59.367  7749  7749 D UEI.SmartControl: QS Service version code: 201091
09-13 09:18:59.367  7749  7749 D UEI.SmartControl: Service requested: Control
09-13 09:18:59.375  7749  7824 E UEI.SmartControl: Loading SETTINGS...
,09-13 09:18:59.378  7749  7749 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 09:18:59.378  7749  7749 D UEI.SmartControl: Service.onUnbind: IControl
09-13 09:18:59.379  7749  7749 D UEI.SmartControl: Service.onDestroy
09-13 09:18:59.379  7749  7749 D UEI.SmartControl: Lock is in USE false
09-13 09:18:59.379  7749  7749 D UEI.SmartControl: unbind internal service
09-13 09:18:59.379  7749  7749 D serial_port: close(fd = 25)
09-13 09:18:59.383  7749  7749 I UEI.SmartControl: Serial port is closed.
09-13 09:18:59.383  7749  7749 I UEI.SmartControl: Serial port is closed.
09-13 09:18:59.384  7749  7749 D UEI.SmartControl: Blaster closed
09-13 09:18:59.384  7749  7749 D UEI.SmartControl: Shut down QS...
09-13 09:18:59.384  7749  7749 D UEI.SmartControl: Stopping QS lib
09-13 09:18:59.384  7749  7749 D UEI.SmartControl: QS lib stop result = true
09-13 09:18:59.384  7749  7749 D UEI.SmartControl: Stopped QS lib
09-13 09:18:59.384  7749  7749 D UEI.SmartControl: Stopped file observer...
09-13 09:18:59.384  7749  7749 D UEI.SmartControl: QS shutdown complete
09-13 09:18:59.385  7749  7749 D UEI.SmartControl: QS Service created
09-13 09:18:59.387  7749  7824 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 09:18:59.398  7749  7749 I UEI.SmartControl: Service initServices...
09-13 09:18:59.398  7749  7749 D UEI.SmartControl: QS start get config
,09-13 09:18:59.402  7749  7823 I UEI.SmartControl: Notify AllClients services are ready: 11
,09-13 09:18:59.402  7749  7823 D UEI.SmartControl: -----service ready thread exits
09-13 09:18:59.449  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,09-13 09:18:59.468  4546  7792 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 438 ms] updated apps [took 438 ms] 
,09-13 09:18:59.723  7749  7749 I UEI.SmartControl: Supports setup maps: true
09-13 09:18:59.725  7749  7749 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 09:18:59.725  7749  7749 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 09:18:59.725  7749  7749 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 09:18:59.725  7749  7749 I UEI.SmartControl: ### init IR Blaster...
,09-13 09:18:59.729  7749  7749 D serial_port: Configuring serial port
09-13 09:18:59.730  7749  7749 E UEI.SmartControl: UEIBLaster setting for 616
09-13 09:18:59.730  7749  7749 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 09:18:59.730  7749  7749 I UEI.SmartControl: configuring settings for MAXQ616
09-13 09:18:59.730  7749  7749 I UEI.SmartControl: Get version...
09-13 09:18:59.746  7749  7833 D UEI.SmartControl: serial port data available: 21
,09-13 09:18:59.773  7749  7749 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 09:18:59.774  7749  7749 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-13 09:18:59.774  7749  7749 I UEI.SmartControl: QS saving settings...
,09-13 09:18:59.776  7749  7749 D UEI.SmartControl: IR Blaster version: 25672567
09-13 09:18:59.809  7749  7833 D UEI.SmartControl: serial port data available: 4
,09-13 09:18:59.845  7749  7839 I UEI.SmartControl: Device manager: loading config....
,09-13 09:18:59.846  7749  7839 D UEI.SmartControl: ----------- loading internal config...
,09-13 09:18:59.857  7749  7749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 09:18:59.865  7749  7749 E UEI.SmartControl: Services init done
09-13 09:18:59.865  7749  7749 D UEI.SmartControl: QS Service init finished
,09-13 09:18:59.873  7749  7749 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 09:18:59.873  7749  7749 D UEI.SmartControl: QS Service version code: 201091
09-13 09:18:59.873  7749  7749 D UEI.SmartControl: Service requested: Control
09-13 09:18:59.876  7749  7839 E UEI.SmartControl: Loading SETTINGS...
09-13 09:18:59.878  7749  7749 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 09:18:59.882  1035  1962 I ActivityManager: Killing 7190:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-13 09:18:59.895  7749  7839 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 09:18:59.926  7749  7838 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 09:18:59.926  7749  7838 D UEI.SmartControl: -----service ready thread exits
,09-13 09:18:59.941  1035  2010 W libprocessgroup: failed to open /acct/uid_10005/pid_7190/cgroup.procs: No such file or directory
,09-13 09:18:59.946  7749  7749 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@316a2075 that was originally bound here
09-13 09:18:59.946  7749  7749 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@316a2075 that was originally bound here
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 09:18:59.946  7749  7749 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 09:18:59.947  7749  7749 D UEI.SmartControl: Internal service binding...,
,09-13 09:19:00.050  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-13 09:19:00.050  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated(),
09-13 09:19:00.051  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated(),
,09-13 09:19:00.051  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
,09-13 09:19:00.074  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 09:19:00.074  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-13 09:19:00.076  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
09-13 09:19:00.078  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 09:19:00.380  7749  7826 D UEI.SmartControl: Internal timer expired: 2
,09-13 09:19:00.731  6667  6728 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 971
,09-13 09:19:00.732  6667  6728 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 971, name: My test thread name)
,09-13 09:19:00.750  6667  7841 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 972, name: My test thread name)
09-13 09:19:00.750  6667  7841 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 972, thread name: My test thread name)
09-13 09:19:00.750  6667  7841 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 972, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 09:19:00.752  6667  6728 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 09:19:00.757  6667  7842 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 976, name: My test thread name)
,09-13 09:19:00.759  6667  7780 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 971, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-13 09:19:00.760  6667  7842 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 976, thread name: My test thread name): Test exception.
09-13 09:19:00.760  6667  7842 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 976, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 09:19:00.765  6667  6728 I jxcore-log: Total number of executed tests:  82
09-13 09:19:00.765  6667  6728 I jxcore-log: 
09-13 09:19:00.766  6667  6728 I jxcore-log: Number of passed tests:  82
09-13 09:19:00.766  6667  6728 I jxcore-log: 
09-13 09:19:00.766  6667  6728 I jxcore-log: Number of failed tests:  0
09-13 09:19:00.766  6667  6728 I jxcore-log: 
09-13 09:19:00.766  6667  6728 I jxcore-log: Number of ignored tests:  0
09-13 09:19:00.766  6667  6728 I jxcore-log: 
09-13 09:19:00.767  6667  6728 I jxcore-log: Total duration:  18742
09-13 09:19:00.767  6667  6728 I jxcore-log: 
09-13 09:19:00.771  6667  6728 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 09:19:00.771  6667  6728 I jxcore-log: 
09-13 09:19:00.772  6667  6728 I jxcore-log: My device name is: LGE-LG-D855
09-13 09:19:00.772  6667  6728 I jxcore-log: 
,09-13 09:19:00.787  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.787  6667  6728 I jxcore-log: 
,09-13 09:19:00.794  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.794  6667  6728 I jxcore-log: 
09-13 09:19:00.795  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.795  6667  6728 I jxcore-log: 
09-13 09:19:00.797  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.797  6667  6728 I jxcore-log: 
09-13 09:19:00.798  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.798  6667  6728 I jxcore-log: 
09-13 09:19:00.801  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.801  6667  6728 I jxcore-log: 
09-13 09:19:00.803  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.803  6667  6728 I jxcore-log: 
09-13 09:19:00.804  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.804  6667  6728 I jxcore-log: 
09-13 09:19:00.805  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.805  6667  6728 I jxcore-log: 
09-13 09:19:00.806  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.806  6667  6728 I jxcore-log: 
09-13 09:19:00.807  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.807  6667  6728 I jxcore-log: 
,09-13 09:19:00.812  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 09:19:00.812  6667  6728 I jxcore-log: 
09-13 09:19:00.814  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.814  6667  6728 I jxcore-log: 
09-13 09:19:00.815  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.815  6667  6728 I jxcore-log: 
09-13 09:19:00.815  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.815  6667  6728 I jxcore-log: 
09-13 09:19:00.816  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.816  6667  6728 I jxcore-log: 
09-13 09:19:00.817  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.817  6667  6728 I jxcore-log: 
09-13 09:19:00.818  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.818  6667  6728 I jxcore-log: 
09-13 09:19:00.819  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.819  6667  6728 I jxcore-log: 
09-13 09:19:00.820  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.820  6667  6728 I jxcore-log: 
09-13 09:19:00.821  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.821  6667  6728 I jxcore-log: 
09-13 09:19:00.821  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.821  6667  6728 I jxcore-log: 
09-13 09:19:00.822  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.822  6667  6728 I jxcore-log: 
09-13 09:19:00.823  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.823  6667  6728 I jxcore-log: 
09-13 09:19:00.824  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.824  6667  6728 I jxcore-log: 
09-13 09:19:00.825  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.825  6667  6728 I jxcore-log: 
09-13 09:19:00.825  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.825  6667  6728 I jxcore-log: 
09-13 09:19:00.826  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.826  6667  6728 I jxcore-log: 
,09-13 09:19:00.827  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.827  6667  6728 I jxcore-log: 
09-13 09:19:00.828  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.828  6667  6728 I jxcore-log: 
09-13 09:19:00.829  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.829  6667  6728 I jxcore-log: 
09-13 09:19:00.830  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.830  6667  6728 I jxcore-log: 
09-13 09:19:00.831  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.831  6667  6728 I jxcore-log: 
09-13 09:19:00.832  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.832  6667  6728 I jxcore-log: 
09-13 09:19:00.833  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.833  6667  6728 I jxcore-log: 
,09-13 09:19:00.839  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.839  6667  6728 I jxcore-log: 
09-13 09:19:00.840  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.840  6667  6728 I jxcore-log: 
09-13 09:19:00.840  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.840  6667  6728 I jxcore-log: 
09-13 09:19:00.841  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.841  6667  6728 I jxcore-log: 
09-13 09:19:00.842  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.842  6667  6728 I jxcore-log: 
09-13 09:19:00.843  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 09:19:00.843  6667  6728 I jxcore-log: 
09-13 09:19:00.844  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.844  6667  6728 I jxcore-log: 
09-13 09:19:00.844  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.844  6667  6728 I jxcore-log: 
09-13 09:19:00.845  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.845  6667  6728 I jxcore-log: 
09-13 09:19:00.859  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 09:19:00.859  6667  6728 I jxcore-log: 
09-13 09:19:00.860  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.860  6667  6728 I jxcore-log: 
09-13 09:19:00.861  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.861  6667  6728 I jxcore-log: 
09-13 09:19:00.861  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.861  6667  6728 I jxcore-log: 
09-13 09:19:00.862  6667  6728 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 09:19:00.862  6667  6728 I jxcore-log: 
,09-13 09:19:00.894  1035  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=40.2, 0.0, 0.0  rx=34.5 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:577358366] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:19:00.897  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=40.2, 0.0, 0.0  rx=34.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:577358369] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 09:19:00.897  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 09:19:01.051  7843  7843 D AndroidRuntime: 
09-13 09:19:01.051  7843  7843 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 09:19:01.054  7843  7843 D AndroidRuntime: CheckJNI is OFF
,09-13 09:19:01.232  7843  7843 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 09:19:01.245  1035  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 09:19:01.245  1035  1098 I ActivityManager: Killing 6667:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 09:19:01.291  1035  1998 I WindowState: WIN DEATH: Window{37842419 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 09:19:01.292  1035  1529 D WifiService: Client connection lost with reason: 4
09-13 09:19:01.296  1035  1998 D InputDispatcher: Window went away: Window{37842419 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 09:19:01.426  1035  1098 I ActivityManager:   Force finishing activity ActivityRecord{176a2d8a u0 com.test.thalitest/.MainActivity t6}
,09-13 09:19:01.481   337   371 E GBMv2   : DFP En is all cleared set to be enabled
,09-13 09:19:01.489  1035  1560 W ActivityManager: Spurious death for ProcessRecord{5edbd13 6667:com.test.thalitest/u0a118}, curProc for 6667: null
09-13 09:19:01.489  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-13 09:19:01.491  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{176a2d8a u0 com.test.thalitest/.MainActivity t6 f}
09-13 09:19:01.491  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{176a2d8a u0 com.test.thalitest/.MainActivity t6 f}
09-13 09:19:01.508  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,09-13 09:19:01.510  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 09:19:01.511  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 09:19:01.512  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17245f85 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 09:19:01.513  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 09:19:01.514  2018  2112 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-13 09:19:01.515  1927  3115 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 09:19:01.515  1927  3115 D SplitWindowPolicy: topRunningActivity=ActivityInfo{157561da co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 09:19:01.526  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-13 09:19:01.532  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 09:19:01.532  3786  3786 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-13 09:19:01.536  4438  4438 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 09:19:01.536  4438  4438 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 09:19:01.537  4438  4438 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 09:19:01.537  4438  4438 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 09:19:01.537  4438  4438 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 09:19:01.537  4438  4438 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 09:19:01.537  4438  4438 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 09:19:01.537  4438  4438 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 09:19:01.537  4438  4438 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 09:19:01.537  2437  2596 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 09:19:01.537  4438  4438 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 09:19:01.537  4438  4438 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 09:19:01.537  4438  4438 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 09:19:01.541  3840  3840 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 09:19:01.541  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 09:19:01.552  1035  1418 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 09:19:01.570  4546  4546 I art     : Explicit concurrent mark sweep GC freed 8164(468KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 585us total 72.027ms
,09-13 09:19:01.582  1035  1890 V SIM_STK : Menu title from STK is T-Mobile
,09-13 09:19:01.592  1035  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 09:19:01.611  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-13 09:19:01.615  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 09:19:01.618  1891  1891 D ActionManagerService: notifyUserLog: 1000003
09-13 09:19:01.619  3786  4429 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 09:19:01.624  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 09:19:01.624  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-13 09:19:01.627  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-13 09:19:01.631  6368  6368 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 09:19:01.633  1588  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 09:19:01.633  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.638  1891  1891 D ActionManagerService: notifyUserLog: 1000004
09-13 09:19:01.638  3786  4429 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,09-13 09:19:01.640  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 09:19:01.643  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 09:19:01.660  3786  3804 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , display: false
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , animation: false }
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , display: false
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , animation: false }
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , expire_time: 0
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , display: false
09-13 09:19:01.665  2018  2018 I GBoardWebViewUtils: , animation: false }
09-13 09:19:01.667  1588  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 09:19:01.667  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.673  2214  2214 I ConfigService: onCreate
09-13 09:19:01.682  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 09:19:01.684  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 09:19:01.684  1588  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 09:19:01.684  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 09:19:01.685  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 09:19:01.687  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 09:19:01.687  1588  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 09:19:01.690  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 09:19:01.690  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 09:19:01.690  1588  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 09:19:01.690  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.690  2018  7885 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 09:19:01.693  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 09:19:01.695  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 09:19:01.696  1854  1854 D SplitUIService: removed split : 
09-13 09:19:01.702  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 09:19:01.702  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 09:19:01.704  1035  1978 V SIM_STK : Menu title from STK is T-Mobile
09-13 09:19:01.704  1035  1978 V SIM_STK : Menu title from STK is T-Mobile
,09-13 09:19:01.718  2214  2214 I ConfigService: onBind returning update interface
09-13 09:19:01.719  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 09:19:01.719  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 09:19:01.720  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 09:19:01.720  1588  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 09:19:01.720  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 09:19:01.720  2214  2214 I ConfigService: onBind returning config service
,09-13 09:19:01.722  1588  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 09:19:01.722  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.725  1035  1035 D administrator: Handling package changes for user 0
09-13 09:19:01.734  1588  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 09:19:01.734  1588  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 09:19:01.734  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 09:19:01.734  1588  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 09:19:01.740  2214  2214 I ConfigService: onDestroy
09-13 09:19:01.741  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 09:19:01.741  1588  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 09:19:01.745  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 09:19:01.745  1854  1854 I SplitUIService: split app #11
09-13 09:19:01.745  1588  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 09:19:01.745  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.751  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-13 09:19:01.751  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-13 09:19:01.757  1802  7888 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 09:19:01.764  1588  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 09:19:01.764  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.765  1035  1693 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 09:19:01.765  3840  3840 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 09:19:01.766  1588  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 09:19:01.766  1588  1650 D KeyguardModel: createShortcutInfo...
,09-13 09:19:01.771  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 09:19:01.771  1588  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 09:19:01.773  1588  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 09:19:01.774  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.778  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 09:19:01.778  1588  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 09:19:01.782  1588  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 09:19:01.782  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.783  1588  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 09:19:01.783  1588  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 09:19:01.784  1588  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 09:19:01.784  1588  1650 D KeyguardModel: createShortcutInfo...
09-13 09:19:01.787  1588  1588 D KeyguardModel: handleShortcutListChanged...
09-13 09:19:01.787  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 09:19:01.788  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-13 09:19:01.794  5824  7893 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-13 09:19:01.800  1802  7895 I PeopleContactsSync: CP2 sync disabled
09-13 09:19:01.801  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
09-13 09:19:01.804  1802  4685 I Icing   : doRemovePackageData com.test.thalitest
,09-13 09:19:01.838  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 09:19:01.839  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 09:19:01.839  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 09:19:01.842  2214  2234 I art     : Explicit concurrent mark sweep GC freed 12030(763KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 541us total 19.165ms
09-13 09:19:01.843  1035  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 09:19:01.849   322   408 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 09:19:01.849  3177  7897 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-13 09:19:01.851  1802  7894 W GmsApplication: Using Auth Proxy for data requests.
,09-13 09:19:01.857  1802  7894 W GmsApplication: Using Auth Proxy for data requests.
09-13 09:19:01.915  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-13 09:19:01.919  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 09:19:01.921  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 09:19:01.922  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 09:19:01.923  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 09:19:01.924  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 09:19:01.933  6997  6997 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-13 09:19:01.939  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 09:19:01.939  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 09:19:01.941  2018  2310 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 09:19:01.941  2018  2310 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 09:19:01.942  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18300d83 u0 com.lge.launcher2/.Launcher t5} time:208643
09-13 09:19:01.952  7026  7026 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-13 09:19:01.954  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-13 09:19:01.955  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 09:19:01.955  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 09:19:01.957  2353  7900 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 09:19:01.963  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-13 09:19:01.963  1981  1981 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 09:19:01.963  1981  1981 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-13 09:19:01.964  2617  2617 D [Concierge]Service: onStartCommand(). Type : 8
,09-13 09:19:01.964  2617  2617 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 09:19:01.964  1981  1981 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-13 09:19:01.966  2617  2617 D [Concierge]Service: Update widget ID : 11
09-13 09:19:01.966  2018  2018 D [Concierge]WidgetView: change position of spinner
,09-13 09:19:01.967  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1473751141967
,09-13 09:19:01.968  2617  2617 D [Concierge]Service: onStartCommand(). Type : 0
09-13 09:19:01.968  6368  6368 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 09:19:01.975  1035  1123 I art     : Explicit concurrent mark sweep GC freed 25685(1777KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.137ms total 337.149ms
09-13 09:19:01.997  7843  7843 D AndroidRuntime: Shutting down VM
,09-13 09:19:02.000  7843  7874 W art     : No such thread id for suspend: 13
09-13 09:19:02.005  1035  1943 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7904 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 09:19:02.025  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1013309716
09-13 09:19:02.025  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 09:19:02.025  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 09:19:02.028  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3a26294
09-13 09:19:02.028  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 09:19:02.029  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 09:19:02.029  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 09:19:02.035  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 09:19:02.035  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 09:19:02.036  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 09:19:02.036  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473750961652, New one : 1473751141967
09-13 09:19:02.036  2018  2018 D [Concierge]WidgetView: Unregister all receivers
09-13 09:19:02.036  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 09:19:02.037  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 09:19:02.040  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 09:19:02.041  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 09:19:02.042  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 09:19:02.043  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 09:19:02.044  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-13 09:19:02.048  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 09:19:02.048  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 09:19:02.054  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 09:19:02.060  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 09:19:02.076  7904  7904 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 09:19:02.076  7904  7904 W LG Account v2.2: No ProfileInfo entries
09-13 09:19:02.076  7904  7904 I LG Account v2.2: isEnabled: false
09-13 09:19:02.076  7904  7904 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 09:19:02.076  7904  7904 I Feature : [Lifetracker]Country: EU
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Operator: OPEN
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Ranking support: false
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Comfort support: false
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Accessory: true
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Health device: true
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Extra Pedometer: false
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Blood glucose device: false
09-13 09:19:02.077  7904  7904 I Feature : [Lifetracker]Device Number: 3
09-13 09:19:02.077  7904  7904 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,09-13 09:19:02.088  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 09:19:02.096  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 09:19:02.096  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-13 09:19:02.097  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-13 09:19:02.099  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 09:19:02.107  1035  1998 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7924 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 09:19:02.107  1035  1998 I ActivityManager: Killing 6830:com.lge.formmanager/u0a26 (adj 15): empty #17
09-13 09:19:02.119  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d0b68e9 time:208820
,09-13 09:19:02.220  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-13 09:19:02.252  1035  1943 W libprocessgroup: failed to open /acct/uid_10026/pid_6830/cgroup.procs: No such file or directory
,09-13 09:19:02.256  2018  2897 I GBoardtInterface: onReloaded()
09-13 09:19:02.258  2018  2018 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-13 09:19:02.267  7924  7924 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 09:19:02.267  7924  7924 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,09-13 09:19:02.268  7924  7924 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 09:19:02.268  7924  7924 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 09:19:02.269  7924  7924 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 09:19:02.269  7924  7924 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 09:19:02.291  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7942 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 09:19:02.292  3786  3804 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 09:19:02.294  3786  3805 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 09:19:02.300  1891  1891 D ActionManagerService: notifyUserLog: 1000001
09-13 09:19:02.301  3786  4429 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 09:19:02.301  3786  4429 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 09:19:02.304  1891  1891 D ActionManagerService: notifyUserLog: 1000001
,09-13 09:19:02.305  3786  4429 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 09:19:02.305  3786  4429 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 09:19:02.305  3786  4429 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-13 09:19:02.305  3786  4429 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-13 09:19:02.306  3786  3804 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 09:19:02.307  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-13 09:19:02.307  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-13 09:19:02.309  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-13 09:19:02.309  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 09:19:02.311  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-13 09:19:02.311  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 09:19:02.336  1035  1978 I ActivityManager: Killing 7088:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-13 09:19:02.362  7924  7924 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-13 09:19:02.409  1035  1693 W libprocessgroup: failed to open /acct/uid_10046/pid_7088/cgroup.procs: No such file or directory
,09-13 09:19:02.416  7924  7924 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-13 09:19:02.416  7924  7924 D HideNavigationAppsReceiver: replacing : false
09-13 09:19:02.418  7924  7924 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-13 09:19:02.420  7924  7924 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-13 09:19:02.420  7924  7924 D ButtonCombinationReceiver: replacing : false

```
