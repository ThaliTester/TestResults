#### Test 827284243e10cd0_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 17:21:00.107  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-25 17:21:00.116  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 17:21:00.116  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-25 17:21:00.119  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-25 17:21:00.119  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 17:21:04.773  6700  6700 D AndroidRuntime: 
08-25 17:21:04.773  6700  6700 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 17:21:04.779  6700  6700 D AndroidRuntime: CheckJNI is OFF
08-25 17:21:04.904  6700  6700 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 17:21:04.909  1034  1888 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 17:21:04.918  1942  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 17:21:04.922  1034  1888 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 17:21:04.923  1034  1888 D ActivityManager: setTaskToReturnTo : TaskRecord{4ef2028 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 17:21:04.923  1034  1888 D ActivityManager: setTaskToReturnTo : TaskRecord{4ef2028 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 17:21:04.924  1034  1888 D WindowStateEx: AppWindowTokenEx init.. 
08-25 17:21:04.925   334   343 E GBMv2   : DFP En is all cleared set to be enabled
08-25 17:21:04.957  1034  1888 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6715 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 17:21:04.958  6700  6700 D AndroidRuntime: Shutting down VM
08-25 17:21:05.012  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 17:21:05.012  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ef22f3f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 17:21:05.014  1942  2772 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 17:21:05.014  1942  2772 D SplitWindowPolicy: topRunningActivity=ActivityInfo{313d800c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 17:21:05.074  6715  6715 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-25 17:21:05.145  6715  6715 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-25 17:21:05.155  6715  6715 I LibraryLoader: Loading: webviewchromium
08-25 17:21:05.158  6715  6715 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5567-5571)
08-25 17:21:05.158  6715  6715 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 17:21:05.179  6715  6715 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12779245}
,08-25 17:21:05.181  6715  6715 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:21:05.181  6715  6715 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 17:21:05.190  6715  6715 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 17:21:05.191  6715  6715 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 17:21:05.206  6715  6715 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 17:21:05.206  6715  6715 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-25 17:21:05.206  6715  6715 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-25 17:21:05.215   318  1396 V AudioPolicyService: registerClient() client 0xb558a900, uid 10118
08-25 17:21:05.220  1034  1116 D BluetoothManagerService: Message: 20
08-25 17:21:05.221  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d02fb72:true
,08-25 17:21:05.229  6715  6715 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:21:05.229  6715  6715 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:21:05.229  6715  6715 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:21:05.229  6715  6715 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:21:05.229  6715  6715 I Adreno-EGL: Remote Branch: 
08-25 17:21:05.229  6715  6715 I Adreno-EGL: Local Patches: 
08-25 17:21:05.229  6715  6715 I Adreno-EGL: Reconstruct Branch: 
08-25 17:21:05.310  6715  6750 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 17:21:05.317  6715  6715 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 17:21:05.334  6715  6715 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:21:05.339  6715  6715 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 17:21:05.342  6715  6715 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-25 17:21:05.345  6715  6715 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 17:21:05.345  6715  6715 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-25 17:21:05.360  6715  6715 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 17:21:05.367  6715  6715 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 17:21:05.367  6715  6715 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:21:05.397  6715  6762 D OpenGLRenderer: Render dirty regions requested: true
08-25 17:21:05.397  6715  6762 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 17:21:05.403  6715  6762 D OpenGLRenderer: Enabling debug mode 0
,08-25 17:21:05.410  6715  6715 D Atlas   : Validating map...
08-25 17:21:05.413  1034  1961 D SplitWindow: check instance of lgWin Window{28dec89c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 17:21:05.462  6715  6760 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:05.463  6715  6760 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:05.481  6715  6715 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@303ea1d8 time:175895
,08-25 17:21:05.504  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +493ms (total +578ms)
08-25 17:21:05.504  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c8d1141 u0 com.test.thalitest/.MainActivity t6} time:175918
,08-25 17:21:05.606  6715  6715 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 17:21:05.671  6715  6760 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 17:21:05.671  6715  6760 I chromium: 
,08-25 17:21:05.804  6715  6773 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-25 17:21:05.817  6715  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 17:21:05.817  6715  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 17:21:05.817  6715  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 17:21:05.817  6715  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 17:21:05.817  6715  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 17:21:05.817  6715  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220a3f1c added. We now have 1 listener(s)
08-25 17:21:05.823  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:05.824  6715  6715 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 17:21:05.824  6715  6715 I chromium: 
08-25 17:21:05.829  6715  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-25 17:21:05.838  6715  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 17:21:05.841  6715  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:05.842  6715  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 17:21:05.850  6715  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4756ab added. We now have 1 listener(s)
,08-25 17:21:05.851  6715  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:21:05.856  1034  1525 D WifiService: New client listening to asynchronous messages
08-25 17:21:05.861  6715  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:21:05.861  6715  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 17:21:05.863  6715  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 17:21:05.863  6715  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 17:21:05.863  6715  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 17:21:05.871  6715  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:05.872  1034  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:21:05.873  6715  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 17:21:05.889  6715  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:05.892  6715  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:05.892  6715  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 17:21:05.892  6715  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:05.895  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:05.898  6715  6773 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 17:21:05.899  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:05.937  6715  6715 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 17:21:06.389   334   345 E GBMv2   : DFP En is all cleared set to be enabled
08-25 17:21:06.389   334   345 E GBMv2   : Set value is all cleared set the max
08-25 17:21:06.389   334   345 I GBMv2   : DFP Enabled. Ignore VFP set
,08-25 17:21:06.805  6715  6776 W jxcore-log: Initializing JXcore engine
08-25 17:21:06.805  6715  6776 W jxcore-log: JXcore engine is ready
,08-25 17:21:06.837  6776  6776 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7354]" dev="sockfs" ino=7354 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-25 17:21:06.837  6776  6776 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-25 17:21:06.837  6776  6776 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8832]" dev="sockfs" ino=8832 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 17:21:06.837  6776  6776 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 17:21:06.837  6776  6776 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32210]" dev="sockfs" ino=32210 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 17:21:06.866  6715  6776 W jxcore-log: Starting JXcore engine
,08-25 17:21:06.945  6715  6776 W jxcore-log: Platform android
08-25 17:21:06.945  6715  6776 W jxcore-log: 
,08-25 17:21:06.945  6715  6776 W jxcore-log: Process ARCH arm
08-25 17:21:06.945  6715  6776 W jxcore-log: 
08-25 17:21:07.141  6715  6776 I jxcore-log: JXcore Cordova bridge is ready!
08-25 17:21:07.141  6715  6776 I jxcore-log: 
08-25 17:21:07.141  6715  6776 W jxcore-log: JXcore engine is started
,08-25 17:21:07.150  6715  6773 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 17:21:07.153  6715  6715 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 17:21:16.764  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 17:21:16.764  6715  6776 I jxcore-log: 
,08-25 17:21:16.767  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 17:21:16.767  6715  6776 I jxcore-log: 
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:16.773  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:16.776  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:16.779  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 17:21:16.779  6715  6776 I jxcore-log: 
08-25 17:21:16.780  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 17:21:16.780  6715  6776 I jxcore-log: 
,08-25 17:21:17.282  6715  6776 D executeNativeTests: Running unit tests
,08-25 17:21:17.364  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:21:17.364  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec added. We now have 2 listener(s)
08-25 17:21:17.364  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:17.366  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 17:21:17.367  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:17.367  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:17.367  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:17.367  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 added. We now have 2 listener(s)
08-25 17:21:17.367  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:21:17.367  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:21:17.370  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:17.375  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:17.376  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.376  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:17.377  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.378  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.381  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:21:17.381  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:21:17.381  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:21:17.383  6715  6776 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 17:21:17.389  6715  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:21:17.389  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:21:17.389  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:21:17.389  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:21:17.391  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.393  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.393  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.394  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.394  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.394  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:17.394  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:17.395  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec removed from the list
,08-25 17:21:17.395  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.395  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 removed from the list
08-25 17:21:17.395  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.395  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.398  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.398  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.401  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:21:17.401  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.401  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.401  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.406  6715  6776 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 17:21:17.407  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.407  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.407  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.407  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.407  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.407  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.407  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.407  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.407  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.407  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.407  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.407  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.407  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.407  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:21:17.408  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.409  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.409  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.409  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:21:17.415  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:21:17.416  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:21:17.416  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.416  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.416  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.417  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.417  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.417  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.417  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.417  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.417  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.417  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.417  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.417  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.417  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.417  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.418  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.418  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.418  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.418  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.419  6715  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 17:21:17.421  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:17.424  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:17.425  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.425  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:17.426  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:17.426  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:21:17.427  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:21:17.427  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.427  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:21:17.427  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.430  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:17.571  1034  1995 I art     : Explicit concurrent mark sweep GC freed 30031(1400KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.738ms total 141.311ms
,08-25 17:21:17.578  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:21:17.578  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:17.585  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:21:17.592  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:21:17.594  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 17:21:17.596  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:21:17.596  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:21:17.599  6715  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:21:17.599  6715  6776 I io.jxcore.node.ConnectionHelper: start: OK
08-25 17:21:17.602  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.603  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.603  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.603  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.603  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.603  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:17.603  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.603  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.603  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.603  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.603  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.606  6715  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:21:17.608  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:17.611  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:17.612  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.613  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:17.613  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:17.613  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:21:17.613  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:21:17.614  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.614  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:21:17.614  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.616  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.619  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:21:17.619  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:21:17.620  6715  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:21:17.620  6715  6776 I io.jxcore.node.ConnectionHelper: start: OK
08-25 17:21:17.622  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.622  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.622  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.622  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.622  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.623  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:17.623  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.623  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.623  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.623  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.623  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.623  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.623  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.624  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.624  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.626  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.626  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.626  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.626  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.627  6715  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:21:17.628  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:17.631  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:21:17.632  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.632  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:17.634  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.635  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.635  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:17.635  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:21:17.635  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:21:17.635  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.635  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:21:17.640  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:21:17.640  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:17.641  6715  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:21:17.642  6715  6776 I io.jxcore.node.ConnectionHelper: start: OK
08-25 17:21:17.642  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.642  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.642  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.643  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.643  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:21:17.643  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.643  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.643  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.643  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:21:17.643  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.643  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:21:17.643  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.643  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.643  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.644  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.644  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.644  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.644  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.645  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.645  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.645  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.645  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.646  6715  6776 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 17:21:17.647  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.647  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.647  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.647  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.647  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.647  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.647  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.647  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.647  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.647  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.647  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.647  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.647  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.647  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.648  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.648  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.649  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.649  6715  6776 D org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.649  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.649  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.650  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:21:17.650  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.650  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.650  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.650  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.650  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.650  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.651  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.651  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.651  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.651  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.651  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.651  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.651  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.651  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.651  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.652  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.652  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.652  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.652  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.652  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.653  6715  6776 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 17:21:17.653  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.653  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.653  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.654  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.654  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.654  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.654  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.654  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.654  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.654  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.654  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.654  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.654  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.654  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.655  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.655  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.656  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.656  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.656  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.656  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.657  6715  6776 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 17:21:17.657  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.657  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.657  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.658  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.658  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.658  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.658  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.658  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.658  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.658  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.658  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.658  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.658  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.658  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.659  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.660  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.660  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.660  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.660  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.660  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.661  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:21:17.663  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:21:17.663  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:21:17.663  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:21:17.663  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:21:17.663  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:21:17.663  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.663  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.663  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.664  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.664  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.664  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.664  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.664  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.664  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.664  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.664  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.664  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.664  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.664  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.666  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.666  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.667  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.667  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.667  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.667  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.668  6715  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:21:17.670  6715  6776 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:21:17.670  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:21:17.675  6715  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:21:17.676  6715  6776 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 17:21:17.676  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:21:17.676  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 17:21:17.676  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:21:17.676  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:21:17.676  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:21:17.677  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:21:17.678  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:21:17.679  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:21:17.679  6715  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 17:21:17.679  6715  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:21:17.679  6715  6776 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 17:21:17.680  6715  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:21:17.680  6715  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:21:17.680  6715  6776 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 17:21:17.680  6715  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:21:17.680  6715  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:21:17.680  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 17:21:17.683  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 17:21:17.684  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 17:21:17.684  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 17:21:17.685  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 17:21:17.685  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 17:21:17.686  6715  6776 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 17:21:17.686  6715  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:21:17.686  6715  6776 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 17:21:17.687  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.687  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.687  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.687  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.687  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.687  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.687  6715  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-25 17:21:17.689  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 17:21:17.689  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.689  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.689  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.689  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.689  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.689  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.689  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.689  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.697  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.697  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.699  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.699  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.699  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.699  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.700  6715  6776 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 17:21:17.700  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.700  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.700  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.701  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.701  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.701  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.703  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.703  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.704  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.704  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.704  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.704  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.704  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.704  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.705  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.705  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.705  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.705  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.705  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.705  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.706  6715  6776 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 17:21:17.707  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.707  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.707  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.707  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.707  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.707  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.708  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.708  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.708  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.708  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.708  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.708  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.708  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.708  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.709  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.709  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.710  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.710  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.710  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.710  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.711  6715  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 17:21:17.711  6715  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 17:21:17.711  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:21:17.711  6715  6776 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 17:21:17.711  6715  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:21:17.711  6715  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 17:21:17.711  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:21:17.711  6715  6776 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 17:21:17.711  6715  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:21:17.711  6715  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:21:17.711  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:21:17.711  6715  6776 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 17:21:17.712  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.712  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.712  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.716  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.716  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.716  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.716  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.716  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.716  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.716  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.717  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.717  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.717  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.717  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.718  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.718  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.718  6715  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-25 17:21:17.718  6715  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-25 17:21:17.719  6715  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
08-25 17:21:17.719  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.719  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.719  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.719  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.720  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.720  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.720  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.720  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.720  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.720  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.720  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.720  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.720  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.720  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.720  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.720  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.720  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.720  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.720  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.720  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.720  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.720  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.722  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.722  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.722  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.722  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.722  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.722  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.722  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.722  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.722  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.722  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.722  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.724  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.724  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.724  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.724  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.724  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.724  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.727  6715  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 17:21:17.727  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.727  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 17:21:17.728  6715  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 17:21:17.728  6715  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 17:21:17.729  6715  6715 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 17:21:17.729  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 17:21:17.729  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:21:17.730  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.731  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 17:21:17.731  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 17:21:17.731  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 17:21:17.731  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.731  6715  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 17:21:17.731  6715  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 17:21:17.732  6715  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 17:21:17.732  6715  6715 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-25 17:21:17.733  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.733  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.733  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:21:17.733  6715  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:21:17.733  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:21:17.735  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:21:17.735  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:17.735  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:17.735  6715  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:21:17.735  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.735  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.736  6715  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:21:17.737  6715  6715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:21:17.737  6715  6715 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 17:21:17.737  6715  6715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:21:17.737  6715  6715 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:21:17.737  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.737  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.737  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.737  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.737  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.738  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.738  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.738  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.738  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.738  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.738  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.738  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.738  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.738  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.738  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.739  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.739  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.739  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.739  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.739  6715  6776 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 17:21:17.740  6715  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:21:17.740  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:21:17.741  6715  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:21:17.741  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.741  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.741  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.742  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.742  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.742  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.742  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.742  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.742  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.742  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.742  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.742  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.742  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.742  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.743  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.743  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.743  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.743  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.744  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:17.748  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:17.749  1034  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:17.750  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.750  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.750  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.750  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.750  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.750  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.750  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.750  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.750  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.750  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.750  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.750  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.750  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.750  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.751  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.751  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.751  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.751  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.752  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:17.752  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:17.752  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:17.752  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:17.752  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.753  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.753  6715  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171516ec not in the list
08-25 17:21:17.753  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.753  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.753  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:17.753  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.753  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.753  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:17.753  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:17.754  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:17.754  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:17.754  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:17.754  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277edab5 not in the list
08-25 17:21:17.755  6715  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 17:21:17.755  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:21:17.756  6715  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 17:21:17.756  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:21:17.756  6715  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 17:21:17.756  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:21:17.759  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:21:17.759  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 17:21:17.759  6715  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 17:21:17.760  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:21:17.760  6715  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 17:21:17.760  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:21:17.760  6715  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 17:21:17.760  6715  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 17:21:17.760  6715  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 17:21:17.760  6715  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 17:21:17.761  6715  6776 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 17:21:17.761  6715  6776 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 17:21:17.761  6715  6776 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 17:21:17.761  6715  6776 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 17:21:17.762  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:17.762  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5e63a2 added. We now have 2 listener(s)
08-25 17:21:17.762  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:17.766  6715  6776 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 17:21:17.768  1034  1960 D WifiServiceImplEx: setWifiEnabled: true pid=6715, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:21:17.768  1034  1960 D WifiService: setWifiEnabled: true pid=6715, uid=10118
08-25 17:21:17.768  1034  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:21:17.769  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:17.769  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ed7f833 added. We now have 3 listener(s)
08-25 17:21:17.769  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:17.772  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:17.772  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a0667f0 added. We now have 4 listener(s)
08-25 17:21:17.772  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:17.774  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:17.774  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c059169 added. We now have 5 listener(s)
08-25 17:21:17.774  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:17.775  1034  1755 D WifiServiceImplEx: setWifiEnabled: false pid=6715, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-25 17:21:17.775  1034  1755 D WifiService: setWifiEnabled: false pid=6715, uid=10118
08-25 17:21:17.775  1034  1755 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:21:17.785  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:21:17.785  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:17.785  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 17:21:17.786  1034  1439 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-25 17:21:17.786  1034  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:17.787  1034  1961 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@b1eb1ef mBinding = false
08-25 17:21:17.787  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:17.787  1034  1439 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:17.788  1034  1439 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:17.788  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:17.789  1034  1439 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 17:21:17.789  1034  1439 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:21:17.789  1034  1439 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:21:17.789  1034  1439 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:21:17.789  1034  1439 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:21:17.796  1034  1439 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 17:21:17.796  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:21:17.797  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.797  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.797  2703  2703 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:21:17.798  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:21:17.798  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:21:17.799  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:21:17.799  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:17.799  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 17:21:17.799  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:17.799  1034  1116 D BluetoothManagerService: Message: 2
08-25 17:21:17.799  1034  2861 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.799   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:21:17.800  1034  1116 D BluetoothManagerService: Sending off request.
08-25 17:21:17.800  3830  3847 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 17:21:17.801  3830  3911 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 17:21:17.801  3830  3911 D BluetoothAdapterProperties: Setting state to 13
08-25 17:21:17.801  3830  3911 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:21:17.802  3830  3911 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:21:17.802  3830  3911 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 17:21:17.803  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:17.803  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 17:21:17.803  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 17:21:17.807  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:17.809  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:21:17.812  3830  3830 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:17.812  3830  3830 D BluetoothMapService: STATE_TURNING_OFF
08-25 17:21:17.812  3830  3830 V BluetoothMapService: Handler(): got msg=4
08-25 17:21:17.812  3830  3830 D BluetoothMapService: MAP Service closeService in
08-25 17:21:17.812  3830  3830 D BluetoothMapMasInstance: MAP Service shutdown
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 17:21:17.817  3830  4234 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-25 17:21:17.817  3830  3830 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:21:17.817  3830  3830 V BluetoothMapService: MAP Service closeService out
08-25 17:21:17.818  3830  3830 V BtOppService: Receiver DISABLED_ACTION 
08-25 17:21:17.818  3830  3830 I BtOppRfcommListener: stopping Accept Thread
08-25 17:21:17.818  3830  3830 V BtOppRfcommListener: close mBtServerSocket
08-25 17:21:17.818  3830  3830 V BtOppRfcommListener: waiting for thread to terminate
08-25 17:21:17.824  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:17.824  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:17.826  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.826  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:17.826  3830  4295 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:17.826  3830  4295 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:21:17.827  3830  3830 V BtOppRfcommListener: done waiting for thread to terminate
08-25 17:21:17.845  1034  1921 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-25 17:21:17.845  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:21:17.845  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.845  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 17:21:17.845  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.846  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 17:21:17.850   309  6796 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 17:21:17.851  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-25 17:21:17.855  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 17:21:17.855  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-25 17:21:17.855  1034  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6797 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 17:21:17.856  1034  1114 D DSQN    : Dns fail occured do internet check.
08-25 17:21:17.857  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-25 17:21:17.857  1034  1034 D DSQN    : try Internet connection check
08-25 17:21:17.860  3830  3914 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:21:17.861  3830  3911 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 17:21:17.861  3830  3911 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 17:21:17.862  3830  4235 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:17.862  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 17:21:17.863  3830  4299 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:17.863  3830  4027 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 17:21:17.863  6715  6778 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-25 17:21:17.863  6715  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-25 17:21:17.863  3830  4296 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 17:21:17.865  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 17:21:17.865  3830  4027 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 17:21:17.866  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.866  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.866  1034  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@5288c6b
08-25 17:21:17.867  3830  3830 V BtOppService: onDestroy
08-25 17:21:17.869  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 17:21:17.869  1034  1439 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.870  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.870  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.870  1034  1439 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.871  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 17:21:17.871  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.871  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:17.871  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:17.871  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:17.871  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.871  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 17:21:17.871  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:17.871  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:17.871  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:17.872  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 17:21:17.872  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-25 17:21:17.872  1034  1439 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 17:21:17.872  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.872  1034  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.872  1034  1439 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.873  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.873  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:17.873  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:17.875  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.875  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:17.,875  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.875  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.875  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:17.875  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:17.875  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:17.875  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:17.875  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:21:17.876  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.877  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:17.879  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:17.880  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:17.880  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.880  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:17.881  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:17.882  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.883  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:17.894  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 17:21:17.894  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:17.895  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:17.897  1034  1540 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 17:21:17.897  1034  1540 D DSQN    : disableDataServiceNotify
08-25 17:21:17.897  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:17.897  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:17.897  1034  1540 D DSQN    : stop dsqn bin
08-25 17:21:17.897   309  6819 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 17:21:17.898  1034  6806 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-25 17:21:17.898  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 17:21:17.898  1034  6803 D DSQN    : ThreadInternetCheck internet check NOK 
08-25 17:21:17.898  1034  6803 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-25 17:21:17.899  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:17.906  1034  1540 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 17:21:17.906  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:17.906  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 17:21:17.907  1034  1540 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:17.907  1034  1540 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 17:21:17.907  1034  1540 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 17:21:17.907  1034  1540 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 17:21:17.908  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:21:17.908  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.908  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.908  1034  2852 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 17:21:17.908  1034  1105 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6821 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-25 17:21:17.908  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 17:21:17.910  1034  1390 D LGWifiP2pService: P2pDisablingState
08-25 17:21:17.911  1034  1390 D LGWifiP2pService: P2pDisablingState{ when=-44ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.911  3830  3830 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 17:21:17.911  1034  1390 D LGWifiP2pService: p2p socket connection lost
08-25 17:21:17.911  1034  1390 D LGWifiP2pService: P2pDisabledState
08-25 17:21:17.911  1034  1439 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 17:21:17.911  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:21:17.911  1034  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:17.912  2703  2703 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:21:17.912  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:21:17.912  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 17:21:17.912  1942  1942 D WfdsService: WifiP2pState is changed : false
08-25 17:21:17.912  1942  2318 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 17:21:17.912  1942  2318 D WfdsService: Set the WFDS Monitor: false
08-25 17:21:17.913  1942  2318 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:21:17.913  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 17:21:17.913  1942  2318 D WfdsService: STATE : WfdsDisabledState - enter
08-25 17:21:17.913  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 17:21:17.913  1942  2751 D CtrlSupplicant: Received on exit socket, terminate
08-25 17:21:17.913  1942  2751 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 ,17:21:17.913  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:21:17.913  1942  2751 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 17:21:17.913  1942  2751 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 17:21:17.913  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:21:17.913  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:21:17.913  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:21:17.913  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:21:17.914  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.914  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:17.914  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:17.914  1942  2318 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 17:21:17.914   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:21:17.914  1942  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 17:21:17.914  1034  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:17.915  1034  1540 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:17.915  1034  1540 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:17.915  1034  1540 D NetworkManagementService: Removing idletimer
08-25 17:21:17.915  1034  1540 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:17.916  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 17:21:17.916  1034  1540 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 17:21:17.916  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:17.916  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 17:21:17.917  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-25 17:21:17.920  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:21:17.920  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:21:17.920  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:21:17.920  1034  1439 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 17:21:17.921  1034  1439 D WifiNative-p2p0: TERMINATE: returned true
08-25 17:21:17.921  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:17.921  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:17.921  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:21:17.922  1034  1439 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:17.922  1034  1439 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:17.923  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 17:21:17.924  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:17.924  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:17.924  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:17.927  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 17:21:17.927  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:17.927  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 17:21:17.928  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 17:21:17.931  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:17.931  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:21:17.932  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.932  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:17.934  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:17.934  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:17.934  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:17.934  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:17.934  6797  6797 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:21:17.934  6797  6797 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 17:21:17.935  6797  6797 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:17.935  6797  6797 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 17:21:17.936  6797  6797 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 17:21:17.936  6797  6797 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 17:21:17.948  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:17.948  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:17.949  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:17.964  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:17.965  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:17.965  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:17.966  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 17:21:17.966  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:17.966  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:18.007  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:18.014  6821  6821 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 17:21:18.015  6821  6821 W LG Account v2.2: No ProfileInfo entries
08-25 17:21:18.015  6821  6821 I LG Account v2.2: isEnabled: false
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Country: EU
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Operator: OPEN
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Ranking support: false
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Comfort support: false
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Accessory: true
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Health device: true
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Extra Pedometer: false
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Blood glucose device: false
08-25 17:21:18.015  6821  6821 I Feature : [Lifetracker]Device Number: 3
08-25 17:21:18.017  2703  2703 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 17:21:18.017  2703  2703 I wpa_supplicant: monitor socket send errors count : 1
08-25 17:21:18.017  2703  2703 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
08-25 17:21:18.018  1034  2749 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 17:21:18.018  1034  2749 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-25 17:21:18.020  6797  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:21:18.022  3830  3830 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:21:18.022  3830  3830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:18.022  3830  3830 V BluetoothPbapReceiver: ***********state = 13
08-25 17:21:18.023  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:18.023  3830  3830 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 17:21:18.026  1034  1116 D BluetoothManagerService: Message: 20
08-25 17:21:18.026  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@357259a6:true
08-25 17:21:18.031  1034  2861 D DhcpStateMachine: StoppedState
08-25 17:21:18.031  1034  2861 D DhcpStateMachine: StoppedState{ when=-117ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:21:18.054  1034  1575 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6841 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 17:21:18.055  2703  2703 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 17:21:18.056  2703  2703 W wpa_supplicant: USIM:  scard_deinit function
08-25 17:21:18.056  1034  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 17:21:18.056  1034  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:21:18.056  1034  2749 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:21:18.056  1034  2749 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 17:21:18.057  1034  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:18.057  1034  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:18.057  1034  1575 I ActivityManager: Killing 6199:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-25 17:21:18.057  1034  1439 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188456
08-25 17:21:18.057  1034  1439 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188456
08-25 17:21:18.058  1034  1439 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=188456  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 17:21:18.058  1034  1116 D Tethering: InitialState.processMessage what=4
08-25 17:21:18.059  1034  1439 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=188456  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 17:21:18.108  1034  1439 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 17:21:18.108  1034  1439 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-25 17:21:18.108  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 17:21:18.109  3830  3830 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:18.109  3830  3830 V BluetoothPbapService: state: 13
08-25 17:21:18.109  3830  3830 V BluetoothPbapService: Pbap Service closeService in
08-25 17:21:18.114  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:21:18.115  1034  1116 D BluetoothManagerService: Message: 30
08-25 17:21:18.116  1034  1439 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:18.117  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:18.119  2703  2703 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 17:21:18.119  1034  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 17:21:18.119  1034  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 17:21:18.120  1034  2749 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-25 17:21:18.122  1034  1439 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-25 17:21:18.124  1034  1961 W libprocessgroup: failed to open /acct/uid_10014/pid_6199/cgroup.procs: No such file or directory
08-25 17:21:18.125  3830  3830 V BluetoothPbapService: successfully stopped pbap service
08-25 17:21:18.125  3830  3830 V BluetoothPbapService: Pbap Service closeService out
08-25 17:21:18.125  3830  3830 V BluetoothPbapService: Pbap Service onDestroy
08-25 17:21:18.125  3830  3830 V BluetoothPbapService: Pbap Service closeService in
08-25 17:21:18.125  3830  3830 V BluetoothPbapService: Pbap Service closeService out
08-25 17:21:18.125  3830  3830 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 17:21:18.141  1034  1116 D BluetoothManagerService: Message: 30
,08-25 17:21:18.147  6797  6797 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 17:21:18.150  6797  6797 D BluetoothMap: Create BluetoothMap proxy object
08-25 17:21:18.151  1034  1116 D BluetoothManagerService: Message: 30
08-25 17:21:18.156  1034  1116 D BluetoothManagerService: Message: 30
,08-25 17:21:18.158  6797  6797 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 17:21:18.160  6797  6797 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 17:21:18.173  6797  6797 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 17:21:18.174  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:21:18.178  6797  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 17:21:18.179  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:18.180  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:18.188  1034  1049 I ActivityManager: Killing 6278:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-25 17:21:18.220  1034  1961 W libprocessgroup: failed to open /acct/uid_10004/pid_6278/cgroup.procs: No such file or directory
,08-25 17:21:18.220  6797  6797 D DockEventReceiver: finishStartingService: stopping service
08-25 17:21:18.221  6797  6797 D BluetoothInputDevice: Proxy object connected
08-25 17:21:18.222  6797  6797 D HidProfile: Bluetooth service connected
08-25 17:21:18.225  1034  1439 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 17:21:18.225  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:18.225  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:18.225  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:21:18.226  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-25 17:21:18.226  1942  2318 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 17:21:18.226  1942  2318 D WfdsService: Set the WFDS Monitor: false
08-25 17:21:18.226  1942  2318 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:21:18.228  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:18.230  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 17:21:18.232  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 17:21:18.232  1034  1484 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,08-25 17:21:18.232  1034  1484 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 17:21:18.233  2447  2447 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:18.237  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:18.239  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:18.240  6715  6715 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 17:21:18.248  6797  6797 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:21:18.249  6797  6797 D PanProfile: Bluetooth service connected
08-25 17:21:18.251  6797  6797 D BluetoothMap: Proxy object connected
,08-25 17:21:18.253  6797  6797 D MapProfile: Bluetooth service connected
,08-25 17:21:18.253  6797  6797 D BluetoothMap: getConnectedDevices()
08-25 17:21:18.254  6797  6797 D BluetoothMap: Bluetooth is Not enabled
08-25 17:21:18.275  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:18.327  6797  6797 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:18.327  6797  6797 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:18.339  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:18.340  6797  6797 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 17:21:18.342  6797  6797 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 17:21:18.349  6797  6797 D BluetoothPermissionRequest: onReceive
08-25 17:21:18.352  6797  6797 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 17:21:18.364  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 17:21:18.366  1034  1960 I ActivityManager: Killing 6434:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-25 17:21:18.400  3830  3830 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-25 17:21:18.400  3830  3830 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 17:21:18.403  3830  3830 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 17:21:18.403  1034  1959 W libprocessgroup: failed to open /acct/uid_10008/pid_6434/cgroup.procs: No such file or directory
08-25 17:21:18.478  1034  2036 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6870 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 17:21:18.490  3830  3830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:18.491  3830  3830 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:21:18.494  3830  3830 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:21:18.495  3830  3830 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:21:18.495  3830  3830 V BluetoothFtpService: Ftp Service closeService
08-25 17:21:18.495  3830  3830 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 17:21:18.498  3830  3830 V BluetoothFtpService: successfully stopped ftp service
08-25 17:21:18.499  3830  3830 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:21:18.499  3830  3830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:18.499  3830  3830 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:18.500  3830  3830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:18.500  3830  3830 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 17:21:18.500  3830  3830 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:21:18.501   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 23.432ms
08-25 17:21:18.502  3830  3830 V BluetoothFtpService: Ftp Service onDestroy
08-25 17:21:18.502  3830  3830 V BluetoothFtpService: Ftp Service closeService
08-25 17:21:18.520   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 18.502ms
,08-25 17:21:18.536   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 15.834ms
,08-25 17:21:18.583  1034  1995 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6887 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 17:21:18.593  3830  3830 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:18.594  3830  3830 V BluetoothSapService: state: 13
08-25 17:21:18.594  3830  3830 V BluetoothSapService: Stopping SAP server process
08-25 17:21:18.597  3830  3830 V BluetoothSapService: Sap Service closeSapService in
08-25 17:21:18.597  3830  3830 V BluetoothSapService: Close listen Socket : 
08-25 17:21:18.597  3830  3830 V BluetoothSapService: Close rfcomm Socket : 
08-25 17:21:18.597  3830  3830 V BluetoothSapService: Close sapd  Socket : 
,08-25 17:21:18.602  3830  3830 V BluetoothSapService: Sap Service closeSapService out
08-25 17:21:18.603  3830  3830 V BluetoothSapService: Sap Service onDestroy
08-25 17:21:18.603  3830  3830 V BluetoothSapService: Sap Service closeSapService in
08-25 17:21:18.603  3830  3830 V BluetoothSapService: Close listen Socket : 
08-25 17:21:18.603  3830  3830 V BluetoothSapService: Close rfcomm Socket : 
08-25 17:21:18.603  3830  3830 V BluetoothSapService: Close sapd  Socket : 
08-25 17:21:18.604  3830  3830 V BluetoothSapService: Sap Service closeSapService out
08-25 17:21:18.628  6870  6870 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:21:18.659  6887  6887 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:21:18.668  6870  6870 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 17:21:18.677  1034  1575 I ActivityManager: Killing 6007:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 17:21:18.707  6870  6870 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 17:21:18.708  6870  6870 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 17:21:18.708  6870  6870 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 17:21:18.709  6870  6870 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 17:21:18.709  6870  6870 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 17:21:18.711  6870  6870 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-25 17:21:18.717  6870  6870 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 17:21:18.728  1034  1050 W libprocessgroup: failed to open /acct/uid_10011/pid_6007/cgroup.procs: No such file or directory
,08-25 17:21:18.741  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:21:18.745  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:18.772  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 17:21:18.778  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:18.779  6870  6870 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-25 17:21:18.784  6870  6870 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 17:21:18.788  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:21:18.788  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:18.788  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:21:18.793  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:18.803  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:21:18.815  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:21:18.815  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:18.818  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:21:18.822  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:18.826  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:21:18.826  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:18.826  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:18.827  1034  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=487546309, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
08-25 17:21:18.827  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d0e7c65 type 2 when 189224 com.google.android.gms} when 189224
08-25 17:21:18.833  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:18.842  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:18.852  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:21:18.852  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:18.854  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:21:18.869  3830  3914 D bt_hci_bdroid: cleanup
08-25 17:21:18.870  3830  4219 I bt_userial_mct: exiting userial_read_thread
08-25 17:21:18.870  3830  4219 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 17:21:18.870  3830  3914 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-25 17:21:18.872  3830  4031 I bt_lpm  : LPM is already off!!!
08-25 17:21:18.872  3830  4031 I bt_vendor: hw_epilog_process
08-25 17:21:18.873  3830  3914 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 17:21:18.873  3830  3914 D bt_userial_mct: userial_close
08-25 17:21:18.873  3830  3914 E bt_userial_mct: pthread_join() FAILED result:3
08-25 17:21:18.873  3830  3914 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 17:21:18.873  3830  4027 W bt-btif : ag scb idx 1 not allocated
08-25 17:21:18.873  3830  4027 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:18.873  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-25 17:21:18.874  3830  4027 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:18.874  3830  4027 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-25 17:21:18.898  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-25 17:21:18.906  1034  2010 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6911 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 17:21:18.922  2597  2597 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 17:21:18.977  3830  3914 D bt_hci_bdroid: set_power 0
08-25 17:21:18.977  3830  3914 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 17:21:18.977  3830  3914 I bt_vendor: bluetooth satus is on
08-25 17:21:18.977  3830  3914 I bt_vendor: bt-vendor : resetting BT status
08-25 17:21:18.977  3830  3914 I bt_vendor: Starting hciattach daemon
08-25 17:21:18.977  3830  3914 I bt_vendor: try to set false
,08-25 17:21:18.978  3830  3914 I bt_vendor: Starting hciattach daemon
08-25 17:21:18.978  3830  3914 I bt_vendor: try to set false
08-25 17:21:18.980  3830  3914 I bt_vendor: cleanup
08-25 17:21:18.981  3830  4027 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 17:21:18.981  3830  3914 I GKI_LINUX: GKI_exit_task 0 done
08-25 17:21:18.981  3830  3914 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 17:21:18.982  3830  3911 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 17:21:18.984  3830  3830 D HeadsetService: Received stop request...Stopping profile...
08-25 17:21:18.985  3830  3830 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:21:18.985  3830  3830 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:21:18.985  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d87d9a
08-25 17:21:18.987  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:18.987  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:18.987  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:18.987  3830  3939 D HeadsetStateMachine: Exit Disconnected: -1
08-25 17:21:18.989  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:18.989  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 17:21:18.989  3830  3830 D A2dpService: Received stop request...Stopping profile...
08-25 17:21:18.989  3830  4005 D A2dpStateMachine: Exit Disconnected: -1
,08-25 17:21:18.991  3830  3911 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 17:21:18.992  3830  3830 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 17:21:18.993  3830  3830 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 17:21:18.993  3830  3830 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:21:18.993  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d87d9a
08-25 17:21:18.994  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-25 17:21:18.994  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 17:21:18.995  3830  3830 D HidService: Received stop request...Stopping profile...
08-25 17:21:18.995  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d87d9a
08-25 17:21:18.996  6797  6797 D BluetoothInputDevice: Proxy object disconnected
08-25 17:21:18.996  3830  3830 D HealthService: Received stop request...Stopping profile...
,08-25 17:21:18.996  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d87d9a
08-25 17:21:18.996  6797  6797 D HidProfile: Bluetooth service disconnected
08-25 17:21:18.997  3830  3830 D HeadsetStateMachine: Unbinding service...
08-25 17:21:18.999  3830  3830 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:21:18.999  3830  3830 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:21:18.999  3830  3830 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:21:18.999  3830  3830 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:21:18.999  3830  3830 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:21:18.999  3830  3830 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:21:18.999  3830  3830 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:21:18.999  3830  3830 D PanService: Received stop request...Stopping profile...
08-25 17:21:19.000  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d87d9a
08-25 17:21:19.001  3830  3830 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:21:19.001  3830  3830 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:21:19.001  3830  3830 D BtGatt.GattService: stop()
08-25 17:21:19.001  3830  3830 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 17:21:19.002  6797  6797 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:21:19.002  6797  6797 D PanProfile: Bluetooth service disconnected
,08-25 17:21:19.003  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d87d9a
08-25 17:21:19.003  3830  3830 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:21:19.003  3830  3830 D BluetoothMapService: stop()
08-25 17:21:19.004  3830  3830 D BluetoothMapEmailAppObserver: deinitObservers()
,08-25 17:21:19.004  3830  3830 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 17:21:19.005  3830  3830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d87d9a
08-25 17:21:19.005  6797  6797 D BluetoothMap: Proxy object disconnected
08-25 17:21:19.005  6797  6797 D MapProfile: Bluetooth service disconnected
08-25 17:21:19.006  3830  3830 I BluetoothA2dpServiceJni: cleanupNative
08-25 17:21:19.006  3830  4009 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 17:21:19.006  3830  3830 I GKI_LINUX: GKI_exit_task 2 done
08-25 17:21:19.006  3830  3830 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 17:21:19.007  3830  3830 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:21:19.007  3830  3830 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:21:19.007  3830  3830 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 17:21:19.008  3830  3830 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:21:19.008  3830  3830 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:21:19.008  3830  3830 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:21:19.008  3830  3830 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:21:19.009  3830  3830 V BluetoothMapService: Handler(): got msg=4
08-25 17:21:19.009  3830  3830 D BluetoothMapService: MAP Service closeService in
08-25 17:21:19.009  3830  3830 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:21:19.009  3830  3830 V BluetoothMapService: MAP Service closeService out
08-25 17:21:19.009  3830  3830 D BluetoothMapService: cleanup()
08-25 17:21:19.009  3830  3830 D BluetoothMapService: MAP Service closeService in
08-25 17:21:19.009  3830  3830 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:21:19.010  3830  3830 V BluetoothMapService: MAP Service closeService out
08-25 17:21:19.010  3830  3911 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 17:21:19.010  3830  3911 D BluetoothAdapterProperties: Setting state to 10
08-25 17:21:19.010  3830  3911 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 17:21:19.010  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:19.010  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 17:21:19.010  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 17:21:19.010  3830  3911 I BluetoothAdapterState: Entering OffState
08-25 17:21:19.010  6797  6818 D BluetoothMap: onBluetoothStateChange: up=false
08-25 17:21:19.011  6797  6820 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:21:19.012  1854  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:19.012  1854  2420 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:19.013  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:19.016  6797  6818 D BluetoothPan: onBluetoothStateChange on: false
,08-25 17:21:19.019  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:19.022  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:19.022  6797  6820 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:21:19.025  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:21:19.026  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:21:19.027  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 17:21:19.028  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-25 17:21:19.030  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 17:21:19.030  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 17:21:19.030  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@b1eb1ef mBinding = false
08-25 17:21:19.031  1034  1116 D BluetoothManagerService: Sending unbind request.
08-25 17:21:19.032  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 17:21:19.034  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:19.035  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:19.035  1942  2125 D LGBluetoothAPIService: Message: 2
08-25 17:21:19.035  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:21:19.035  1942  2125 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@97b5d55 mBinding = false
08-25 17:21:19.036  1942  2125 D LGBluetoothAPIService: Sending unbind request.
08-25 17:21:19.036  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:19.037  6797  6797 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:21:19.038  6797  6797 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 17:21:19.039  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:19.040  6797  6797 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 17:21:19.041  1603  1603 D BluetoothAdapter: 962572157: getState() :  mService = null. Returning STATE_OFF
08-25 17:21:19.041  1603  1603 D BluetoothAdapter: 962572157: getState() :  mService = null. Returning STATE_OFF
,08-25 17:21:19.047  3830  3914 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 17:21:19.048  3830  3830 I GKI_LINUX: GKI_exit_task 1 done
08-25 17:21:19.048  3830  3830 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-25 17:21:19.048  3830  3830 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 17:21:19.049  3830  3830 I art     : --- WEIRD: removing null entry 246
08-25 17:21:19.049  3830  3830 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 17:21:19.049  3830  3830 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 17:21:19.049  3830  3830 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 17:21:19.049  6797  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:21:19.051  3830  3830 I art     : System.exit called, status: 0
08-25 17:21:19.051  3830  3830 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 17:21:19.058  6911  6937 W FormManager: Network not available. Please check & try again.
08-25 17:21:19.061  6797  6797 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:21:19.063  6911  6938 V FormManager: Network unavailable.
08-25 17:21:19.070  6911  6938 V FormManager: Network unavailable.
,08-25 17:21:19.071  6797  6797 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 17:21:19.071   318  1397 V AudioFlinger: 3830 died, releasing its sessions
08-25 17:21:19.071   318  1397 V AudioFlinger:  pid 1854 @ 0
08-25 17:21:19.071   318  1397 V AudioFlinger:  pid 3421 @ 1
08-25 17:21:19.071   318  1397 V AudioFlinger:  pid 3421 @ 2
,08-25 17:21:19.177  1034  1888 I ActivityManager: Process com.android.bluetooth (pid 3830) has died
,08-25 17:21:19.177  1034  1888 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-25 17:21:19.200  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:21:19.204  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:21:19.204  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:21:19.205  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-25 17:21:19.205  6797  6797 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 17:21:19.216  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-25 17:21:19.239  6797  6797 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-25 17:21:19.239  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 17:21:19.239  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:21:19.239  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:21:19.239  6797  6797 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:21:19.240  6797  6797 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:21:19.251  6797  6797 D BluetoothPermissionRequest: onReceive
,08-25 17:21:19.258  6797  6797 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 17:21:19.259  6797  6797 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 17:21:19.262  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:21:19.319  1034  1575 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6943 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 17:21:19.321  1034  1575 I ActivityManager: Killing 6029:com.android.contacts/u0a19 (adj 15): empty #17
08-25 17:21:19.390  1034  1888 W libprocessgroup: failed to open /acct/uid_10019/pid_6029/cgroup.procs: No such file or directory
08-25 17:21:19.393  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 17:21:19.393  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:21:19.395  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:19.403  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 17:21:19.419  6841  6841 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 17:21:19.419  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:19.419  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:21:19.424  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:21:19.425  6943  6943 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 17:21:19.426  6943  6943 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:19.426  6943  6943 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 17:21:19.427  6943  6943 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 17:21:19.430  6911  6965 W FormManager: Network not available. Please check & try again.
08-25 17:21:19.431  4302  6963 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 17:21:19.434  6911  6966 V FormManager: Network unavailable.
,08-25 17:21:19.439  4302  6967 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:21:19.440  6911  6966 V FormManager: Network unavailable.
08-25 17:21:19.440  4302  6967 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:19.445  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:19.457  6943  6943 D BluetoothAdapterApp: Loading JNI Library
,08-25 17:21:19.463  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 17:21:19.464  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 17:21:19.465  6870  6870 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 17:21:19.503  6870  6870 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:19.503  6943  6943 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d837053 Instance Count = 1
08-25 17:21:19.504  6870  6870 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:19.512  6943  6943 D BluetoothAdapterApp: onCreate
08-25 17:21:19.521  6870  6870 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-25 17:21:19.525  6870  6870 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 17:21:19.525  6870  6870 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 17:21:19.525  6870  6870 V SoundPool: doLoad: loading sample sampleID=1
08-25 17:21:19.526  6870  6870 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 17:21:19.529  6870  6974 V SoundPool: Start decode
08-25 17:21:19.529  6870  6974 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 17:21:19.530  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 17:21:19.530   318  2208 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 17:21:19.531   318  2208 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 17:21:19.531   318  2208 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 17:21:19.531   318  2208 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 17:21:19.531   318  2208 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 17:21:19.531   318  2208 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 17:21:19.531   318  2208 V MediaPlayerService: player type = 3
08-25 17:21:19.531   318  2208 V AwesomePlayer: AwesomePlayer create()
08-25 17:21:19.531  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 17:21:19.531   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:19.531  6592  6592 D UEI.SmartControl: QS Service created
08-25 17:21:19.531   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:19.531   318  2208 V AwesomePlayer: setAudioSink() 
08-25 17:21:19.531   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:19.531   318  2208 V AudioCache: notify(0xb16a6880, 8, 0, 0)
08-25 17:21:19.532   318  2208 V AudioCache: ignored
08-25 17:21:19.532   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:19.532  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 17:21:19.532   318  2208 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 17:21:19.532   318  2208 V AwesomePlayer: setDataSource_l dataSource
08-25 17:21:19.532   318  2208 V LGParserOSAL: SniffLGParser start
08-25 17:21:19.532   318  2208 V LGParserOSAL: MainType:5, SubType=0
08-25 17:21:19.532   318  2208 V LGParserOSAL: #### check Mime : application/ogg
08-25 17:21:19.532   318  2208 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 17:21:19.532   318  2208 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 17:21:19.541  6943  6943 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-25 17:21:19.541  6943  6943 D ProfileConfigQcom: Adding HeadsetService
,08-25 17:21:19.541  6943  6943 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 17:21:19.541  6943  6943 D ProfileConfigQcom: Adding A2dpService
08-25 17:21:19.542  6943  6943 D ProfileConfigQcom: [BTUI] HidService is supported
,08-25 17:21:19.542  6943  6943 D ProfileConfigQcom: Adding HidService
08-25 17:21:19.542  6943  6943 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 17:21:19.542  6943  6943 D ProfileConfigQcom: Adding HealthService
08-25 17:21:19.543  6943  6943 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-25 17:21:19.543  6943  6943 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 17:21:19.544  6943  6943 D ProfileConfigQcom: Adding PanService
08-25 17:21:19.544  6870  6870 V LGMDMManager: Create singleton instance
,08-25 17:21:19.544  6943  6943 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 17:21:19.544  6943  6943 D ProfileConfigQcom: Adding GattService
08-25 17:21:19.544  6943  6943 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 17:21:19.545  6943  6943 D ProfileConfigQcom: Adding BluetoothMapService
,08-25 17:21:19.545  6943  6943 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 17:21:19.547  6943  6943 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 17:21:19.557  6797  6797 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 17:21:19.559  6943  6943 V LGMDMManagerInternal: Create singleton instance
,08-25 17:21:19.569  6592  6592 I UEI.SmartControl: Service initServices...
08-25 17:21:19.569  6592  6592 D UEI.SmartControl: QS start get config
08-25 17:21:19.590   318  2208 V LGParserOSAL: supported mime: application/ogg
08-25 17:21:19.590   318  2208 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 17:21:19.590   318  2208 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 17:21:19.590   318  2208 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 17:21:19.590   318  2208 V AwesomePlayer: AudioTrack Setting
08-25 17:21:19.590   318  2208 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 17:21:19.590   318  2208 V AwesomePlayer: setAudioSource() 
08-25 17:21:19.590   318  2208 V MediaPlayerService: prepare
08-25 17:21:19.590   318  2208 V AwesomePlayer: prepareAsync_l() 
08-25 17:21:19.590   318  2208 V MediaPlayerService: wait for prepare
,08-25 17:21:19.595   318  6977 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 17:21:19.595   318  6977 V AwesomePlayer: initAudioDecoder() 
08-25 17:21:19.595   318  6977 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 17:21:19.595   318  6977 V AudioSystem: isOffloadSupported()
08-25 17:21:19.596   318  6977 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 17:21:19.596   318  6977 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 17:21:19.596   318  6977 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 17:21:19.596   318  6977 V AwesomePlayer: getUseOffload() = 0 
08-25 17:21:19.596   318  6977 V OMXCodec: OMXCodec::Create
08-25 17:21:19.596   318  6977 V OMXCodec: findMatchingCodecs()
08-25 17:21:19.596   318  6977 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 17:21:19.596   318  6977 V OMXCodec: matchingCodecs.size()=1
08-25 17:21:19.597   318  6977 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 17:21:19.601   318  6977 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 17:21:19.601   318  6977 V LGCodecAdapter: LG Codec Adapter start
08-25 17:21:19.601   318  6977 V OMXCodec: OMXCodec Createtor
08-25 17:21:19.601   318  6977 V OMXCodec: setComponentRole
08-25 17:21:19.601   318  6977 V OMXCodec: configureCodec protected=0
08-25 17:21:19.601   318  6977 V LGCodecAdapter: called getLGCodecSpecificData
08-25 17:21:19.601   318  6977 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 17:21:19.601   318  6977 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 17:21:19.601   318  6977 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 17:21:19.601   318  6977 V LGCodecOSAL: Not support LGCodec
08-25 17:21:19.601   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 17:21:19.602   318  6977 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 17:21:19.602   318  6977 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 17:21:19.602   318  6977 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 17:21:19.602   318  6977 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 17:21:19.602   318  6977 V AudioSystem: isOffloadSupported()
08-25 17:21:19.602   318  6977 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 17:21:19.602   318  6977 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 17:21:19.602   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 17:21:19.602   318  6977 V OMXCodec: init()
08-25 17:21:19.602   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 17:21:19.602   318  6977 V OMXCodec: allocateBuffers
08-25 17:21:19.602   318  6977 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 17:21:19.603   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,08-25 17:21:19.603   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-25 17:21:19.603   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-25 17:21:19.603   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-25 17:21:19.604   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-25 17:21:19.604   318  6977 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 17:21:19.604   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 17:21:19.604   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 17:21:19.604   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-25 17:21:19.604   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f92e0 on output port
08-25 17:21:19.604   318  6977 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9330 on output port
08-25 17:21:19.604   318  6977 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 17:21:19.604   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 17:21:19.604   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 17:21:19.604   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 17:21:19.605   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 17:21:19.605   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 17:21:19.605   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 17:21:19.605   318  6977 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 17:21:19.605   318  6977 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 17:21:19.605   318  6977 V AudioCache: notify(0xb16a6880, 5, 0, 0)
08-25 17:21:19.605   318  6977 V AudioCache: ignored
08-25 17:21:19.605   318  6977 V AudioCache: notify(0xb16a6880, 1, 0, 0)
08-25 17:21:19.605   318  6977 V AudioCache: prepared
08-25 17:21:19.605   318  2208 V AudioCache: wait - success
08-25 17:21:19.605   318  2208 V MediaPlayerService: start
08-25 17:21:19.605   318  2208 V AwesomePlayer: play_l() 
08-25 17:21:19.605   318  2208 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 17:21:19.605   318  2208 V AwesomePlayer: createAudioPlayer_l
08-25 17:21:19.605   318  2208 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 17:21:19.605   318  2208 V AwesomePlayer: startAudioPlayer_l() 
08-25 17:21:19.605   318  2208 D AudioPlayer: start of Playback, useOffload 0
08-25 17:21:19.605   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 17:21:19.605   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 17:21:19.607   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 17:21:19.607   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 17:21:19.607   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 17:21:19.607   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 17:21:19.607   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 17:21:19.607   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decod,er] Port is disabled, freeing buffer 3045036768
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036848
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 17:21:19.609   318  6979 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f92e0 on output port
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f1f0 on output port
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 17:21:19.609   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 17:21:19.610   318  2208 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 17:21:19.610   318  2208 V AudioCache: notify(0xb16a6880, 6, 0, 0)
08-25 17:21:19.610   318  2208 V AudioCache: ignored
08-25 17:21:19.611   318  2208 V MediaPlayerService: wait for playback complete
08-25 17:21:19.611   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.611   318  6980 V AudioCache: memcpy(0xb0457000, 0xb16ab000, 4096)
08-25 17:21:19.612   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.612   318  6980 V AudioCache: memcpy(0xb0458000, 0xb16ab000, 4096)
08-25 17:21:19.612   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.612   318  6980 V AudioCache: memcpy(0xb0459000, 0xb16ab000, 4096)
08-25 17:21:19.614   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.614   318  6980 V AudioCache: memcpy(0xb045a000, 0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: memcpy(0xb045b000, 0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: memcpy(0xb045c000, 0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: memcpy(0xb045d000, 0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.615   318  6980 V AudioCache: memcpy(0xb045e000, 0xb16ab000, 4096)
,08-25 17:21:19.616   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.616   318  6980 V AudioCache: memcpy(0xb045f000, 0xb16ab000, 4096)
08-25 17:21:19.617   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.617   318  6980 V AudioCache: memcpy(0xb0460000, 0xb16ab000, 4096)
08-25 17:21:19.617   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.617   318  6980 V AudioCache: memcpy(0xb0461000, 0xb16ab000, 4096)
08-25 17:21:19.618   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.618   318  6980 V AudioCache: memcpy(0xb0462000, 0xb16ab000, 4096)
08-25 17:21:19.618   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.618   318  6980 V AudioCache: memcpy(0xb0463000, 0xb16ab000, 4096)
08-25 17:21:19.619   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.619   318  6980 V AudioCache: memcpy(0xb0464000, 0xb16ab000, 4096)
08-25 17:21:19.620   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.620   318  6980 V AudioCache: memcpy(0xb0465000, 0xb16ab000, 4096),
,08-25 17:21:19.620   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.620   318  6980 V AudioCache: memcpy(0xb0466000, 0xb16ab000, 4096)
08-25 17:21:19.620   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.621   318  6980 V AudioCache: memcpy(0xb0467000, 0xb16ab000, 4096)
08-25 17:21:19.621   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.621   318  6980 V AudioCache: memcpy(0xb0468000, 0xb16ab000, 4096)
08-25 17:21:19.622   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.622   318  6980 V AudioCache: memcpy(0xb0469000, 0xb16ab000, 4096)
08-25 17:21:19.622   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.622   318  6980 V AudioCache: memcpy(0xb046a000, 0xb16ab000, 4096)
08-25 17:21:19.623  6943  6943 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:19.623   318  6980 V AudioCache: write(0xb16ab000, 4096)
,08-25 17:21:19.623   318  6980 V AudioCache: memcpy(0xb046b000, 0xb16ab000, 4096)
08-25 17:21:19.623   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.623   318  6980 V AudioCache: memcpy(0xb046c000, 0xb16ab000, 4096)
08-25 17:21:19.624   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.624   318  6980 V AudioCache: memcpy(0xb046d000, 0xb16ab000, 4096)
08-25 17:21:19.625   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.625   318  6980 V AudioCache: memcpy(0xb046e000, 0xb16ab000, 4096)
08-25 17:21:19.625   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.625   318  6980 V AudioCache: memcpy(0xb046f000, 0xb16ab000, 4096)
,08-25 17:21:19.626   318  6980 V AudioCache: write(0xb16ab000, 4096)
,08-25 17:21:19.626   318  6980 V AudioCache: memcpy(0xb0470000, 0xb16ab000, 4096)
08-25 17:21:19.626  6943  6943 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:21:19.627  6943  6943 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:19.627  6943  6943 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:19.627   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.627   318  6980 V AudioCache: memcpy(0xb0471000, 0xb16ab000, 4096)
08-25 17:21:19.628   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.628   318  6980 V AudioCache: memcpy(0xb0472000, 0xb16ab000, 4096)
08-25 17:21:19.628  6943  6943 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:19.628  6943  6943 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 17:21:19.628   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.628   318  6980 V AudioCache: memcpy(0xb0473000, 0xb16ab000, 4096)
08-25 17:21:19.629   318  6980 V AudioCache: write(0xb16ab000, 4096)
,08-25 17:21:19.629   318  6980 V AudioCache: memcpy(0xb0474000, 0xb16ab000, 4096)
08-25 17:21:19.629   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.629   318  6980 V AudioCache: memcpy(0xb0475000, 0xb16ab000, 4096)
08-25 17:21:19.631   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.631   318  6980 V AudioCache: memcpy(0xb0476000, 0xb16ab000, 4096)
08-25 17:21:19.632   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.632   318  6980 V AudioCache: memcpy(0xb0477000, 0xb16ab000, 4096)
08-25 17:21:19.633   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.633   318  6980 V AudioCache: memcpy(0xb0478000, 0xb16ab000, 4096)
08-25 17:21:19.633   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.633   318  6980 V AudioCache: memcpy(0xb0479000, 0xb16ab000, 4096)
08-25 17:21:19.634  6887  6887 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 17:21:19.634   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.634   318  6980 V AudioCache: memcpy(0xb047a000, 0xb16ab000, 4096)
08-25 17:21:19.638   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.638   318  6980 V AudioCache: memcpy(0xb047b000, 0xb16ab000, 4096)
08-25 17:21:19.638   318  6980 V AudioCache: write(0xb16ab000, 4096)
,08-25 17:21:19.638   318  6980 V AudioCache: memcpy(0xb047c000, 0xb16ab000, 4096)
08-25 17:21:19.639   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.639   318  6980 V AudioCache: memcpy(0xb047d000, 0xb16ab000, 4096)
08-25 17:21:19.639   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.640   318  6980 V AudioCache: memcpy(0xb047e000, 0xb16ab000, 4096)
08-25 17:21:19.640   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.640   318  6980 V AudioCache: memcpy(0xb047f000, 0xb16ab000, 4096)
08-25 17:21:19.640   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.640   318  6980 V AudioCache: memcpy(0xb0480000, 0xb16ab000, 4096)
08-25 17:21:19.641   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.641   318  6980 V AudioCache: memcpy(0xb0481000, 0xb16ab000, 4096)
08-25 17:21:19.641   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.641   318  6980 V AudioCache: memcpy(0xb0482000, 0xb16ab000, 4096)
08-25 17:21:19.642   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.642   318  6980 V AudioCache: memcpy(0xb0483000, 0xb16ab000, 4096)
08-25 17:21:19.642   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.642   318  6980 V AudioCache: memcpy(0xb0484000, 0xb16ab000, 4096)
,08-25 17:21:19.643   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.643   318  6980 V AudioCache: memcpy(0xb0485000, 0xb16ab000, 4096)
08-25 17:21:19.644   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.644   318  6980 V AudioCache: memcpy(0xb0486000, 0xb16ab000, 4096)
08-25 17:21:19.645   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.645   318  6980 V AudioCache: memcpy(0xb0487000, 0xb16ab000, 4096)
08-25 17:21:19.645   318  6980 V AudioCache: write(0xb16ab000, 4096)
08-25 17:21:19.645   318  6980 V AudioCache: memcpy(0xb0488000, 0xb16ab000, 4096)
08-25 17:21:19.645   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 17:21:19.645   318  6980 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 17:21:19.645   318  6980 V AwesomePlayer: postAudioEOS() 
08-25 17:21:19.645   318  6980 V AudioCache: write(0xb16ab000, 280)
08-25 17:21:19.645   318  6980 V AudioCache: memcpy(0xb0489000, 0xb16ab000, 280)
08-25 17:21:19.647  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 17:21:19.647   318  6977 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 17:21:19.647   318  6977 V AwesomePlayer: onStreamDone
08-25 17:21:19.647   318  6977 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 17:21:19.647   318  6977 V AudioCache: notify(0xb16a6880, 2, 0, 0)
08-25 17:21:19.647   318  6977 V AudioCache: playback complete
08-25 17:21:19.647   318  6977 V AwesomePlayer: pause_l() 
08-25 17:21:19.647   318  6977 V AudioCache: notify(0xb16a6880, 7, 0, 0)
08-25 17:21:19.647   318  6977 V AudioCache: ignored
08-25 17:21:19.647   318  6977 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:19.647   318  2208 V AudioCache: wait - success
08-25 17:21:19.647   318  2208 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 17:21:19.647   318  6977 D AudioPlayer: Pause Playback at 1068125
08-25 17:21:19.648  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 17:21:19.648   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:19.648   318  2208 V AudioCache: notify(0xb16a6880, 8, 0, 0)
08-25 17:21:19.648   318  2208 V AudioCache: ignored
08-25 17:21:19.648   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:19.648   318  2208 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 17:21:19.648   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 17:21:19.648   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 17:21:19.648   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 17:21:19.648   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 17:21:19.,649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f1f0 on port 1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 17:21:19.649  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5566
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f92e0 on port 1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 17:21:19.649   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 17:21:19.649   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 17:21:19.649   318  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 17:21:19.650   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 17:21:19.650   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 17:21:19.650   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 17:21:19.652   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 17:21:19.652   318  2208 D AudioPlayer: AudioPlayer releasing audio source
08-25 17:21:19.652   318  2208 D AudioPlayer: AudioPlayer done releasing audio source
08-25 17:21:19.652   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:19.652   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:19.652   318  2208 V AwesomePlayer: ~AwesomePlayer call
08-25 17:21:19.652  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=487546309 [*alarm*], flags=0x0
08-25 17:21:19.653   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:19.653   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:19.653  6870  6974 V SoundPool: close(31)
08-25 17:21:19.653  6870  6974 V SoundPool: pointer = 0xa0038000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 17:21:19.653   309  6984 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 17:21:19.654  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-25 17:21:19.873  6592  6592 I UEI.SmartControl: Supports setup maps: true
08-25 17:21:19.876  6592  6592 D UEI.SmartControl: QS start statue = true Error code = 0
,08-25 17:21:19.876  6592  6592 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-25 17:21:19.876  6592  6592 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 17:21:19.876  6592  6592 I UEI.SmartControl: ### init IR Blaster...
08-25 17:21:19.880  6592  6592 D serial_port: Configuring serial port
08-25 17:21:19.880  6592  6592 E UEI.SmartControl: UEIBLaster setting for 616
08-25 17:21:19.880  6592  6592 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 17:21:19.880  6592  6592 I UEI.SmartControl: configuring settings for MAXQ616
08-25 17:21:19.880  6592  6592 I UEI.SmartControl: Get version...
08-25 17:21:19.899  6592  6985 D UEI.SmartControl: serial port data available: 21
,08-25 17:21:19.926  6592  6592 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 17:21:19.926  6592  6592 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 17:21:19.926  6592  6592 I UEI.SmartControl: QS saving settings...
08-25 17:21:19.928  6592  6592 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 17:21:19.945  6592  6985 D UEI.SmartControl: serial port data available: 4
,08-25 17:21:19.978  6592  6994 I UEI.SmartControl: Device manager: loading config....
,08-25 17:21:19.982  6592  6994 D UEI.SmartControl: ----------- loading internal config...
,08-25 17:21:19.986  6592  6592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 17:21:19.992  6592  6592 E UEI.SmartControl: Services init done
08-25 17:21:19.992  6592  6592 D UEI.SmartControl: QS Service init finished
08-25 17:21:19.995  6592  6592 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 17:21:19.995  6592  6592 D UEI.SmartControl: QS Service version code: 201091
08-25 17:21:19.997  6592  6592 D UEI.SmartControl: Service requested: Control
08-25 17:21:19.999  6592  6994 E UEI.SmartControl: Loading SETTINGS...
,08-25 17:21:20.003  6592  6592 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 17:21:20.004  6592  6994 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 17:21:20.007  6592  6592 D UEI.SmartControl: Internal service binding...
08-25 17:21:20.007  6870  6870 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 17:21:20.009  6592  6613 I UEI.SmartControl: ------ IControl API: 11
08-25 17:21:20.009  6592  6613 D UEI.SmartControl: File observer start...
08-25 17:21:20.009  6592  6613 E UEI.SmartControl: IR Port is disabled: false
08-25 17:21:20.009  6592  6613 D UEI.SmartControl: Starting file observer...
08-25 17:21:20.011  6592  6613 I UEI.SmartControl: Registering callback...
08-25 17:21:20.012  6592  6612 I UEI.SmartControl: ------ IControl API: 19
08-25 17:21:20.013  6592  6612 I UEI.SmartControl: Registering Services Ready callback...
08-25 17:21:20.013  6592  6612 I UEI.SmartControl: Notify client services are ready...
08-25 17:21:20.014  6870  6885 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-25 17:21:20.015  6870  6972 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 17:21:20.015  6870  6972 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 17:21:20.016  6592  6993 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 17:21:20.017  6870  6886 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 17:21:20.017  6870  6972 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 17:21:20.017  6592  6993 D UEI.SmartControl: -----service ready thread exits
08-25 17:21:20.017  6870  6972 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 17:21:20.017  6870  6870 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 17:21:20.018  6870  6870 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 17:21:20.018  6592  6613 I UEI.SmartControl: ------ IControl API: 8
08-25 17:21:20.020  6870  6870 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 17:21:20.020  6870  6870 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 17:21:20.020  6870  6870 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 17:21:20.020  6870  6870 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 17:21:20.021  6870  6870 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 17:21:20.022  6870  6870 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 17:21:20.023  6870  6870 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 17:21:20.028  6870  6870 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-25 17:21:20.029  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-25 17:21:20.030  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 17:21:20.031  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 17:21:20.031  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 17:21:20.032  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 17:21:20.033  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 17:21:20.034  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 17:21:20.035  6870  6870 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472138480035]
08-25 17:21:20.038  6870  6870 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 17:21:20.048  1034  1710 I ActivityManager: Killing 6055:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-25 17:21:20.061  6870  6996 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-25 17:21:20.076  1034  1710 I ActivityManager: Killing 6485:com.lge.email/u0a23 (adj 15): empty #18
,08-25 17:21:20.109  1034  1888 W libprocessgroup: failed to open /acct/uid_10027/pid_6055/cgroup.procs: No such file or directory
,08-25 17:21:20.114  1034  2010 W libprocessgroup: failed to open /acct/uid_10023/pid_6485/cgroup.procs: No such file or directory
08-25 17:21:20.121  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-25 17:21:20.122  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-25 17:21:20.123  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 17:21:20.124  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 17:21:20.125  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 17:21:20.126  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 17:21:20.127  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-25 17:21:20.148  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-25 17:21:20.887  1034  1959 D WifiServiceImplEx: setWifiEnabled: true pid=6715, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:21:20.889  1034  1959 D WifiService: setWifiEnabled: true pid=6715, uid=10118
08-25 17:21:20.889  1034  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:21:20.914  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:20.922  1034  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:20.925  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-25 17:21:20.928  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:20.931  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:20.937  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:20.943  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-25 17:21:20.953  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:20.957  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:21:20.958  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:20.958  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 17:21:20.960  1034  1439 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 17:21:20.960  1034  1439 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 17:21:20.962  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:20.963  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 17:21:20.963  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:21:20.963  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 17:21:20.963  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:21:20.963  1034  1439 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 17:21:20.963  1034  1439 E WifiHW  : unknown target_country: EU , set to default
08-25 17:21:20.963  1034  1439 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 17:21:20.963  1034  1439 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 17:21:20.963  1034  1439 I WifiUtil: gEnableBmps=1
08-25 17:21:20.970  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 17:21:20.977  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 17:21:20.992  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 17:21:20.993  6385  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 17:21:21.020  2155  2155 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:21.057  1034  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:21.085  1034  2036 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7001 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 17:21:21.146  1034  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:21.146  1034  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 17:21:21.166  7001  7001 I AppUp4:AppBoxCP: onCreate
08-25 17:21:21.167  7001  7001 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-25 17:21:21.173  7001  7001 I AppUp4:DB:  setFingerPrint start
08-25 17:21:21.174  7001  7001 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-25 17:21:21.184  7001  7001 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 17:21:21.184  7001  7001 I AppUp4:DB:  SDK version = 21
08-25 17:21:21.184  7001  7001 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-25 17:21:21.186  7001  7001 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 17:21:21.187  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 17:21:21.187  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:21.189  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 17:21:21.189  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 17:21:21.194  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
08-25 17:21:21.217  7001  7001 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:21.217  7001  7001 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:21.223  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12779245
08-25 17:21:21.223  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:21:21.223  7001  7001 D AppUp4:CustFacade: isPhone : true
08-25 17:21:21.223  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:21:21.224  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 17:21:21.224  7001  7001 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 17:21:21.224  7001  7018 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 17:21:21.224  7001  7018 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 17:21:21.225  7001  7018 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 17:21:21.226  1034  1959 I ActivityManager: Killing 6115:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-25 17:21:21.247  1034  1927 W libprocessgroup: failed to open /acct/uid_10080/pid_6115/cgroup.procs: No such file or directory
,08-25 17:21:21.252  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:21.252  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:21:21.253  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:21.255  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:21.268  4302  7020 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:21:21.277  4302  7021 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:21.277  4302  7021 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:21.299  1034  2036 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7022 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 17:21:21.334  7022  7022 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:21:21.335  7022  7022 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:21.335  7022  7022 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 17:21:21.336  7022  7022 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 17:21:21.431  7022  7022 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 17:21:21.446  7022  7022 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 17:21:21.484  7022  7022 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 17:21:21.523  7022  7022 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 17:21:21.523  7022  7022 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:21.647  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 17:21:21.653   309   892 D SoftapController: Softap fwReload - Ok
08-25 17:21:21.657  1034  1439 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (689ms)
,08-25 17:21:21.672   309   892 D CommandListener: Setting iface cfg
08-25 17:21:21.672   309   892 D CommandListener: Trying to bring down wlan0
08-25 17:21:21.672   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:21:21.674  1034  1439 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 17:21:21.678  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:21.678  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:21.678  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:21:21.681  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:21.683  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 17:21:21.684  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 17:21:21.677  7056  7056 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:21.677  7056  7056 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:21.691  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:21.692  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:21.695  1034  1439 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 17:21:21.695  1034  1439 D WifiMonitor: connecting to supplicant
08-25 17:21:21.701  7022  7022 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 17:21:21.713  7056  7056 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 17:21:21.740  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 17:21:21.740  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:21.741  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 17:21:21.744  7056  7056 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 17:21:21.745  7056  7056 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 17:21:21.749  1034  1116 D Tethering: InitialState.processMessage what=4
08-25 17:21:21.779  1034  1888 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7071 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-25 17:21:21.780  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 17:21:21.785  6911  7068 W FormManager: Network not available. Please check & try again.
08-25 17:21:21.786  6911  7069 V FormManager: Network unavailable.
08-25 17:21:21.789  6911  7069 V FormManager: Network unavailable.
08-25 17:21:21.794  7022  7022 I HubEmail: JNI_OnLoad()
08-25 17:21:21.794  7022  7022 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 17:21:21.794  7022  7022 I HubEmail: registerNatives()
08-25 17:21:21.794  7022  7022 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 17:21:21.794  7022  7022 I HubEmail: registerNativeMethods()
08-25 17:21:21.794  7022  7022 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 17:21:21.794  7022  7022 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-25 17:21:21.801  1034  2036 I ActivityManager: Killing 6521:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-25 17:21:21.833  7056  7056 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 17:21:21.838  7022  7088 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:21:21.840  1034  1927 W libprocessgroup: failed to open /acct/uid_10061/pid_6521/cgroup.procs: No such file or directory
08-25 17:21:21.881  7071  7071 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:21.881  7071  7071 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:21.884  7071  7071 D PhoneMonitor: Register our PhoneStateListener
08-25 17:21:21.900  7071  7071 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 17:21:21.904  7071  7071 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 17:21:21.926  7056  7056 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 17:21:21.937  7071  7071 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 17:21:21.938  7071  7071 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 17:21:21.938  7071  7071 D TelephonyAutoProfiling: [parse] Load xml
08-25 17:21:21.941  7071  7071 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 17:21:21.941  7071  7071 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 17:21:21.941  7071  7071 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-25 17:21:21.943  1034  1921 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7092 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 17:21:21.944  1034  1921 I ActivityManager: Killing 6141:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 17:21:21.946  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:21:21.946  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 17:21:21.946  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 17:21:21.947  1034  1439 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 17:21:21.947  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 17:21:21.947  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:21.947  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 17:21:21.947  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:21.947  1034  7098 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 17:21:21.947  1034  7098 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 17:21:21.947  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 17:21:21.947  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 17:21:21.947  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:21.947  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 17:21:21.947  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 17:21:21.947  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:21.948  1034  1439 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 17:21:21.948  1034  1439 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 17:21:21.949  1034  1439 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 17:21:21.950  1034  1439 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 17:21:21.950  1034  1439 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 17:21:21.952  7071  7071 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-25 17:21:21.988  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:21.988  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:21.988  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 17:21:21.988  1034  1439 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 17:21:21.989  1034  1439 D WifiNative-wlan0: SET update_config 1: returned true
08-25 17:21:21.989  1034  1439 D WifiConfigStore: Loading config and enabling all networks 
08-25 17:21:21.989  1034  1439 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 17:21:21.989  1034  1439 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 17:21:21.994  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:21.995  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:21.995  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:21.995  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:21.995  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:21.995  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:21.996  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-25 17:21:21.997  1034  1961 W libprocessgroup: failed to open /acct/uid_10097/pid_6141/cgroup.procs: No such file or directory
08-25 17:21:22.000  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:22.000  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:22.000  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:22.000  1034  1439 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 17:21:22.000  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:22.001  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 17:21:22.001  1034  1484 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-25 17:21:22.002  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:22.002  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:22.003  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:22.003  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:22.009  1034  1439 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 17:21:22.009  1034  1439 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 17:21:22.011  1034  1439 D WifiStateMachine: enableVerboseLogging : level 2
08-25 17:21:22.011  1034  1439 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 17:21:22.011  1034  1439 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 17:21:22.011  1034  1439 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 17:21:22.012  1034  1439 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 17:21:22.012  1034  1439 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 17:21:22.012  1034  1439 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 17:21:22.012  1034  1439 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 17:21:22.012  1034  1439 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 17:21:22.012  1034  1439 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 17:21:22.013  1034  1439 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 17:21:22.013  1034  1439 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 17:21:22.013  1034  1439 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 17:21:22.013  1034  1439 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 17:21:22.014  1034  1439 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 17:21:22.015  1034  1439 D WifiStateMachine: Setting OUI to DA-A1-19
,08-25 17:21:22.015  1034  1439 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 17:21:22.015  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-25 17:21:22.016  1034  1439 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 17:21:22.016  1034  1439 D WifiNative-HAL: Setting external_sim to 1
08-25 17:21:22.016  1034  1439 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 17:21:22.016  1034  1439 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 17:21:22.016  1034  1439 I WifiNative-HAL: startHal
08-25 17:21:22.016  1034  1439 D wifi    : setting scan oui 0xaf64f5c0
08-25 17:21:22.017  1034  1439 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:21:22.017  1034  1439 I WifiNative-HAL: startHal
08-25 17:21:22.017  1034  1439 D wifi    : setting scan oui 0xaf64f5c0
08-25 17:21:22.017  1034  1439 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 17:21:22.018  1942  2318 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 17:21:22.018  1034  1439 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 17:21:22.018  1942  2318 D WfdsService: Set the WFDS Monitor: true
08-25 17:21:22.018  1942  2318 D WfdsMonitor: WfdsMonitorThread create
08-25 17:21:22.018  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 17:21:22.018  1942  2318 D WfdsMonitor: WFDS Monitor is created and started
08-25 17:21:22.018  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 17:21:22.018  1942  2318 D WfdsService: WiFi: Supplicant connection re-established
08-25 17:21:22.019  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 17:21:22.019  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:21:22.019  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:21:22.019  1942  7110 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-25 17:21:22.019  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:21:22.019  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 17:21:22.019  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 17:21:22.020  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 17:21:22.020  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:21:22.020  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:21:22.020  1942  7110 E CtrlSupplicant: Succeed to open control connection
08-25 17:21:22.020  1942  7110 E CtrlSupplicant: Succeed to open monitor connection
08-25 17:21:22.020  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:21:22.020  1942  7110 D WfdsMonitor: Supplicant connection established
08-25 17:21:22.021  1942  2318 D WfdsService: Connected to the supplicant for wfds
08-25 17:21:22.021  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:21:22.021  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:21:22.021  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:21:22.021  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 17:21:22.021  7056  7056 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 17:21:22.022  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 17:21:22.022  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:21:22.022  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:21:22.022  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:21:22.023  1034  1439 E WifiNative: : [192,421,249 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 17:21:22.023  1034  1439 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 17:21:22.023  1034  1439 D WifiNative-wlan0: RECONNECT: returned true
08-25 17:21:22.023  1034  1439 D WifiNative-wlan0: doString: [STATUS]
08-25 17:21:22.024  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:21:22.024  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 17:21:22.024  1034  1439 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 17:21:22.024  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:21:22.025  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:22.025  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.026  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 17:21:22.026  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-25 17:21:22.026  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.026  1034  1556 I WifiNative-HAL: startHal
08-25 17:21:22.027  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf64f5c0
08-25 17:21:22.027  1034  1556 D wifi    : failed to get capabilities : -3
08-25 17:21:22.027  1034  1556 E WifiScanningService: could not get scan capabilities
08-25 17:21:22.027  1034  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.028  1034  1439 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:21:22.028  1034  1439 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
,08-25 17:21:22.028  1034  1439 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0,
08-25 17:21:22.029  1034  1439 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 17:21:22.029  1034  1439 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 17:21:22.030  1034  1439 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 17:21:22.030  1034  1439 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 17:21:22.030  1034  1439 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 17:21:22.030   309   892 D CommandListener: Setting iface cfg
08-25 17:21:22.030   309   892 D CommandListener: Trying to bring up p2p0
08-25 17:21:22.030  7056  7056 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-25 17:21:22.030  1034  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 17:21:22.031  1034  1390 D LGWifiP2pService: P2pEnablingState
08-25 17:21:22.031  1034  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.031  1034  1390 D LGWifiP2pService: P2p socket connection successful
08-25 17:21:22.031  1034  1390 D LGWifiP2pService: P2pEnabledState
08-25 17:21:22.031  1034  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 17:21:22.032  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 17:21:22.032  1942  1942 D WfdsService: WifiP2pState is changed : true
08-25 17:21:22.032  1942  2318 D WfdsService: Receive the WFDS_ENABLE Method
,08-25 17:21:22.032  1942  2318 D WfdsService: Set the WFDS Monitor: true
08-25 17:21:22.032  1942  2318 D WfdsService: Connected to the supplicant for wfds
08-25 17:21:22.032  1942  2318 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 17:21:22.032  7056  7056 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 17:21:22.033  1942  2318 D WfdsService: selectPreferredScanChannel [36]
08-25 17:21:22.033  1034  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 17:21:22.033  1942  2318 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 17:21:22.033  1034  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-25 17:21:22.033  1034  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 17:21:22.034  1034  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-25 17:21:22.034  1034  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 17:21:22.034  1034  1390 D LGWifiP2pService: before postfix = G3
08-25 17:21:22.034  1034  1390 D WifiServerServiceExt: postfix byte check : 2
08-25 17:21:22.034  1034  1390 D LGWifiP2pService: after postfix = G3
08-25 17:21:22.034  1034  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 17:21:22.034  1034  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 17:21:22.034  1034  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
,08-25 17:21:22.035  1034  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 17:21:22.035  1034  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 17:21:22.035  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 17:21:22.035  1034  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 17:21:22.036  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 17:21:22.036  1942  1942 D WfdsService: isConnected: false
08-25 17:21:22.036  1034  1439 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 17:21:22.036  1034  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-25 17:21:22.036  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-25 17:21:22.036  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 17:21:22.036  1034  1439 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 17:21:22.037  1034  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 17:21:22.037  1034  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 17:21:22.037  1034  1439 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 17:21:22.037  1034  1439 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 17:21:22.037  7056  7056 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-25 17:21:22.038  1034  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 17:21:22.038  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 17:21:22.038  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 17:21:22.038  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 17:21:22.038  1942  1942 D WfdsService: Update P2p Interface State: 3
08-25 17:21:22.038  1034  1439 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 17:21:22.038  1034  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 17:21:22.038  1034  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 17:21:22.039  1034  1439 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 17:21:22.039  1034  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-25 17:21:22.039  1034  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 17:21:22.039  1034  1439 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 17:21:22.039  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-25 17:21:22.050  1034  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 17:21:22.050  1034  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 17:21:22.050  1034  1390 D LGWifiP2pService: InactiveState
08-25 17:21:22.050  1034  1390 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.050  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.050  1034  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 17:21:22.051  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:21:22.051  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 17:21:22.052  7056  7056 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,08-25 17:21:22.052  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.052  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:21:22.052  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:22.052  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:22.052  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:22.052  1034  7098 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.052  1034  7098 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.052  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.053  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.053  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.053  1034  7098 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.053  1034  7098 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.053  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.053  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.054  1942  7110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.054  1942  7110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.054  1034  1439 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 17:21:22.054  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:21:22.055  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:22.055  1942  7110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:21:22.055  1034  7098 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:21:22.055  1034  7098 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:22.055  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:22.055  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:22.055  1034  1439 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:21:22.055  7056  7056 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 17:21:22.056  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.056  1034  1439 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:21:22.056  1034  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 17:21:22.056  1034  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.056  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.056  1034  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.056  1942  7110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.056  1034  7098 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.056  1034  1439 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:21:22.056  1034,  7098 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.056  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 17:21:22.056  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.056  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.056  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.056  1942  7110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.056  1034  7098 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:22.056  1034  7098 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.057  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.057  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:22.057  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 17:21:22.057  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:22.057  1034  1390 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.057  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.057  1034  1390 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.057  1034  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.057  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.057  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.057  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.058  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.058  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.058  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.058  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.058  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 17:21:22.058  1034  1034 E WifiServerServiceExt: No p2p device connected
08-25 17:21:22.058  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:22.058  1034  7098 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:22.058  1034  7098 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:22.058  1034  1439 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 17:21:22.058  1034  1439 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-25 17:21:22.058  1942  2318 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 17:21:22.058  1034  1439 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 17:21:22.058  1034  1439 D WifiNative-wlan0: doBoolean: SCAN
08-25 17:21:22.059  1034  1439 D WifiNative-wlan0: SCAN: returned false
08-25 17:21:22.059  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=192458  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:21:22.061  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.061  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.062  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.062  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=192461  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:21:22.063  1034  1439 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:22.063  1034  1439 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-25 17:21:22.063  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.063  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.063  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:21:22.063  1034  1439 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:22.064  1034  1439 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:22.064  1034  1439 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:22.065  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:22.065  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-25 17:21:22.213  1034  1575 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7113 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a,
,08-25 17:21:22.218  1034  1575 I ActivityManager: Killing 6554:com.lge.eula/1000 (adj 15): empty #17
08-25 17:21:22.277  1034  2036 W libprocessgroup: failed to open /acct/uid_1000/pid_6554/cgroup.procs: No such file or directory
,08-25 17:21:22.416  1034  2010 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7133 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:21:22.417  1034  2010 I ActivityManager: Killing 6571:com.lge.bnr/1000 (adj 15): empty #17
,08-25 17:21:22.469  1034  1575 W libprocessgroup: failed to open /acct/uid_1000/pid_6571/cgroup.procs: No such file or directory
,08-25 17:21:22.492  7056  7056 E wpa_supplicant: USIM:  scard_init function
08-25 17:21:22.492  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 17:21:22.492  1034  7098 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 17:21:22.492  7056  7056 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 17:21:22.492  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 17:21:22.492  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-25 17:21:22.492  1034  7098 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 17:21:22.493  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:21:22.493  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-25 17:21:22.497  1034  1439 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:22.497  1034  1439 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:22.498  1034  1439 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:22.498  1034  1439 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:22.498  1034  1439 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 17:21:22.506  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=192904  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 17:21:22.510  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.510  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.510  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:21:22.511  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.511  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.513  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=192912  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 17:21:22.517  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.517  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.517  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 17:21:22.518  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.520  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:22.521  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 17:21:22.521  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.522  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.523  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.535  7133  7133 I art     : Almond Protected OAT
,08-25 17:21:22.591  7133  7133 D WeatherApplication: removeAccount
08-25 17:21:22.592  7133  7133 D WeatherApplication: Account.length = 0
,08-25 17:21:22.592  7133  7133 E WeatherApplication: OPERATOR:OPEN
08-25 17:21:22.599  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:22
08-25 17:21:22.602  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 17:21:22.602  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-25 17:21:22.608  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-25 17:21:22.608  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 17:21:22.608  7056  7056 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 17:21:22.609  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 17:21:22.609  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 17:21:22.609  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:22.609  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:22.611  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 17:21:22.614  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-25 17:21:22.615  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-25 17:21:22.618  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=193015  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 17:21:22.619  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=193017  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 17:21:22.620  1034  1439 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193019
08-25 17:21:22.621  1034  1439 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193020
08-25 17:21:22.621  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 17:21:22.624  1034  1439 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193022
08-25 17:21:22.624  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193023
08-25 17:21:22.625  1034  1439 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193023
08-25 17:21:22.625  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=193024  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 17:21:22.626  7056  7056 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:21:22.626  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:21:22.627  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:22.627  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:22.628  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 17:21:22.628  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 17:21:22.628  1034  7098 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:21:22.628  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 17:21:22.628  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:21:22.628  1034  7098 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:21:22.628  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:22.628  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:22.631  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 17:21:22.631  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 17:21:22.631  7133  7133 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-25 17:21:22.634  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.635  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 17:21:22.638  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.639  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.639  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.639  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 17:21:22.640  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=193039  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 17:21:22.641  1034  1439 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:22.641  1034  1439 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:22.642  1034  1439 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:22.642  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:22.642  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:22.643  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 17:21:22.643  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.643  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.643  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193042  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 17:21:22.643  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 17:21:22.644  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:22.644  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 17:21:22.644  1034  1439 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193043
08-25 17:21:22.645  1034  1439 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193043
08-25 17:21:22.645  1034  1439 D WifiNative-wlan0: doString: [STATUS]
08-25 17:21:22.646  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:22.646  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:22.646  1034  1439 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 17:21:22.650  1034  1439 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 17:21:22.654  1034  1439 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 17:21:22.654  1034  1439 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 17:21:22.659  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.659  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.660  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 17:21:22.660  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:22
08-25 17:21:22.663  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.663  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.663  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 17:21:22.663  1034  1439 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 17:21:22.663  1034  1540 D ConnectivityService: Got NetworkAgent Messenger
08-25 17:21:22.663  1034  1439 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:21:22.663  1034  1439 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:21:22.663  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 17:21:22.664  1034  1540 D ConnectivityService: NetworkAgent connected
08-25 17:21:22.664  1034  1439 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:21:22.664  1034  1439 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 17:21:22.667  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.667  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.667  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 17:21:22.669  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.670  1034  1439 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 17:21:22.670  1034  1439 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:21:22.670  1034  1439 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:21:22.671  1034  1439 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:21:22.671  1034  1439 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:21:22.673  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.673  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.674  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.676  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.676  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.676  1034  1439 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 17:21:22.678   309   892 D CommandListener: Setting iface cfg
08-25 17:21:22.679  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.718  1034  1755 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7157 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 17:21:22.719  1034  1755 I ActivityManager: Killing 2182:com.lge.music/u0a34 (adj 15): empty #17
,08-25 17:21:22.737   318   318 V AudioFlinger: 2182 died, releasing its sessions
08-25 17:21:22.737   318   318 V AudioFlinger:  pid 1854 @ 0
08-25 17:21:22.737   318   318 V AudioFlinger:  pid 3421 @ 1
08-25 17:21:22.737   318   318 V AudioFlinger:  pid 3421 @ 2
,08-25 17:21:22.794  1034  1050 W libprocessgroup: failed to open /acct/uid_10034/pid_2182/cgroup.procs: No such file or directory
,08-25 17:21:22.804  1034  1439 E WifiStateMachine: Start Dhcp Watchdog 2
08-25 17:21:22.804  1034  7152 D DhcpStateMachine: StoppedState
08-25 17:21:22.805  1034  7152 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.805  1034  7152 D DhcpStateMachine: WaitBeforeStartState
08-25 17:21:22.806  1034  1439 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=193204  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:22.807  1034  1439 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=193206  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:22.809  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=193207  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:22.813  1034  1439 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193211  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:22.815  1034  1439 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193213  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-25 17:21:22.816  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193214  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:22.820  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:146953] from screen [on:0 period:-1035299709] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 17:21:22.823  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1035299706] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 17:21:22.823  1034  1439 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 17:21:22.832  1034  1540 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 17:21:22.833  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.834  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.835  1034  1439 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.837  1034  1439 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.838  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.838  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.840  1034  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 17:21:22.840  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
08-25 17:21:22.841  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
08-25 17:21:22.841  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 17:21:22.842  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-25 17:21:22.842  1034  1439 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 17:21:22.842  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 0
,08-25 17:21:22.843  1034  1439 D WifiNative-wlan0: SET ps 0: returned true
08-25 17:21:22.843  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 17:21:22.843  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 17:21:22.844  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 17:21:22.844  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26cd024c target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.845  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26cd024c target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.845  1034  7152 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.845  1034  1439 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 17:21:22.845  1034  7152 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 17:21:22.845  1034  1439 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 17:21:22.845  1034  1439 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 17:21:22.847   309   892 D CommandListener: Setting iface cfg,
08-25 17:21:22.848   309   892 D CommandListener: Trying to bring up wlan0
08-25 17:21:22.849  1034  1439 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 17:21:22.850  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.851  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.851  1034  1439 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.852  1034  1439 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.852  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.853  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:22.853  1034  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 17:21:22.854  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 17:21:22.854  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 17:21:22.854  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:21:22.854  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.854  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.854  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:21:22.855  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:21:22.855  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 17:21:22.855  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 17:21:22.855  1034  1439 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 17:21:22.855  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
,08-25 17:21:22.868  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION,
08-25 17:21:22.868  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-25 17:21:22.869  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.872  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:22.872  1034  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 17:21:22.873  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 17:21:22.873  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 17:21:22.873  1034  1439 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 17:21:22.873  1034  1540 D ConnectivityService: ignoring duplicate network state non-change
08-25 17:21:22.877  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.877  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.880  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:22.880  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.880  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.880  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 17:21:22.884  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 17:21:22.885  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.885  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.885  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 17:21:22.885  1034  1540 D ConnectivityService: Adding iface wlan0 to network 101
08-25 17:21:22.887  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 17:21:22.889  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 17:21:22.891  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.891  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.891  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 17:21:22.893  1034  1439 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 17:21:22.894  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 17:21:22.900  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.900  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:22.901  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.904  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.904  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 17:21:22.905  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.908  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.908  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:22.908  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-25 17:21:22.912  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.912  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:22.912  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.912  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.912  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 17:21:22.913  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.921  1034  1540 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 17:21:22.921  1034  1540 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 17:21:22.923  1034  1439 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:21:22.924  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:21:22.924  1034  1439 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:21:22.925  1034  1439 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-25 17:21:22.926  1034  1540 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 17:21:22.926  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:21:22.927   309   892 E Netd    : netlink response contains error (File exists)
08-25 17:21:22.927  1034  1540 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 17:21:22.927  1034  1439 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 17:21:22.929  1034  1540 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 17:21:22.929  1034  1540 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 17:21:22.929  1034  1540 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 17:21:22.930  1034  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 17:21:22.930  1034  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 17:21:22.930  1034  1540 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 17:21:22.930  1034  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 17:21:22.930  1034  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:22.930  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.930  1034  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:22.930  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 17:21:22.930  1034  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 17:21:22.930  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:22.930  1034  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:22.930  1034  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 17:21:22.930  1034  1540 D ConnectivityService: currentScore = 0, newScore = 20
08-25 17:21:22.930  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 17:21:22.930  1034  1540 D ConnectivityService:    accepting network in place of null
08-25 17:21:22.930  1034  1540 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:22.931  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:22.931  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 17:21:22.934   309  7179 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 17:21:22.935  1034  1540 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 17:21:22.935  1034  1540 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 17:21:22.935  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:21:22.936  1034  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:22.936  1034  1540 D CSLegacyTypeTracker: [e] list.add(nai) em,pty : false size: 1
08-25 17:21:22.936  1034  1540 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 17:21:22.936  1034  1439 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:22.936  1034  1439 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:22.937  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 17:21:22.937  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:21:22.937  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-25 17:21:22.937  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:21:22.939  1034  1540 D ConnectivityService: validation of new default Network = false
08-25 17:21:22.939  1034  1540 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 17:21:22.939  1034  1540 D DSQN    : enableDataServiceNotify 
08-25 17:21:22.939  1034  1540 D DSQN    : start dsqn bin
08-25 17:21:22.947  1034  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 17:21:22.952  1034  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 17:21:22.952  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:22.952  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 17:21:22.953  1034  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:22.953  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:21:22.937  7181  7181 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:22.937  7181  7181 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:22.968  7181  7181 E DSQN    : DSQN ssw
,08-25 17:21:22.974   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:21:22.974   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 17:21:22.974   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:21:22.978  7157  7182 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 17:21:22.980   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:21:22.980   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 17:21:22.980   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:21:22.980  7157  7182 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-25 17:21:22.987   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:21:22.987   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 17:21:22.987   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:21:22.988  7157  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 17:21:22.990   309  7179 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 17:21:22.991  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:22.992  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.992  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:22.992  1818  7187 I CheckinService: active receiver: enabled
08-25 17:21:22.993   278   436 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 17:21:22.993   278   436 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 17:21:22.993   278   436 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 17:21:22.993  7157  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-25 17:21:23.006  1818  7187 I CheckinService: Preparing to send checkin request
08-25 17:21:23.006  1818  7187 I EventLogService: Accumulating logs since 1472138348246
08-25 17:21:23.027   309  7179 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 17:21:23.032  1818  7187 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-25 17:21:23.046  1034  7152 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 17:21:23.047  1034  7152 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 17:21:23.047  1034  7152 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 17:21:23.037  7193  7193 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:23.037  7193  7193 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:23.055  7193  7193 I dhcpcd  : version 5.5.6 starting
08-25 17:21:23.057  7193  7193 E dhcpcd  : get_duid: m
08-25 17:21:23.057  7193  7193 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 17:21:23.057  7193  7193 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-25 17:21:23.059   309   891 D LGDataListener: argv[0]=dsqncommand
08-25 17:21:23.059   309   891 D LGDataListener: argv[1]=wlan0
,08-25 17:21:23.059   309   891 D LGDataListener: argv[2]=1
08-25 17:21:23.059   309   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 17:21:23.059  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 17:21:23.059  1034  1114 D DSQN    : start to monitor internet connection
08-25 17:21:23.107  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:21:23 GMT], X-Android-Received-Millis=[1472138483107], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472138483058]}
08-25 17:21:23.107  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 17:21:23.108  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 17:21:23.108  1034  1540 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 17:21:23.108  1034  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 17:21:23.108  1034  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:23.108  1034  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:23.108  1034  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 17:21:23.108  1034  1540 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 17:21:23.108  1034  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 17:21:23.108  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:23.108  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 17:21:23.108  1034  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 17:21:23.108  1034  1540 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:23.109  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 17:21:23.109  1034  1439 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:23.109  1034  1439 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:23.109  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:21:23.109  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:23.110  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 17:21:23.116  7193  7193 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 17:21:23.116  7193  7193 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 17:21:23.116  7193  7193 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 17:21:23.116  7193  7193 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 17:21:23.117  7193  7193 D dhcpcd  : wlan0: sending REQUEST (xid 0xefd6ae20), next in 3.32 seconds
08-25 17:21:23.123  1034  1755 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7214 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 17:21:23.153  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:23.154  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:23.155  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:23.156   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 32.113ms
,08-25 17:21:23.175  7193  7193 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 17:21:23.176   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 19.549ms
08-25 17:21:23.185  7214  7214 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 17:21:23.185  7214  7214 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 17:21:23.194   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 17.009ms
08-25 17:21:23.204  7214  7214 I MultiDex: VM with version 2.1.0 has multidex support
08-25 17:21:23.204  7214  7214 I MultiDex: install
08-25 17:21:23.204  7214  7214 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 17:21:23.207  7193  7193 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 17:21:23.208  7193  7193 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 17:21:23.208  7193  7193 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 17:21:23.208  7193  7193 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 17:21:23.208  7193  7193 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 17:21:23.208  7193  7193 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 17:21:23.208  7193  7193 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 17:21:23.208  7193  7193 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 17:21:23.213  7214  7214 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-25 17:21:23.225  7157  7157 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 17:21:23.239  7157  7157 I LibraryLoader: Loading: webviewchromium
08-25 17:21:23.241  7157  7157 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3651-3654)
08-25 17:21:23.241  7157  7157 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 17:21:23.247  7157  7157 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37e80384}
08-25 17:21:23.250  7157  7157 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:21:23.251  7157  7157 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 17:21:23.270  7157  7157 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 17:21:23.272  7157  7157 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 17:21:23.283  7157  7157 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 17:21:23.284  7157  7157 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 17:21:23.284  7157  7157 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 17:21:23.287   318  2206 V AudioPolicyService: registerClient() client 0xb558ad40, uid 10093
08-25 17:21:23.289  7157  7250 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 17:21:23.295  7157  7157 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:21:23.295  7157  7157 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:21:23.295  7157  7157 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:21:23.295  7157  7157 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:21:23.295  7157  7157 I Adreno-EGL: Remote Branch: 
08-25 17:21:23.295  7157  7157 I Adreno-EGL: Local Patches: 
08-25 17:21:23.295  7157  7157 I Adreno-EGL: Reconstruct Branch: 
08-25 17:21:23.330  1034  1959 I art     : Explicit concurrent mark sweep GC freed 103260(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.908ms total 103.701ms
,08-25 17:21:23.355  7157  7157 I NSApplication: Starting up...
,08-25 17:21:23.418  1034  1755 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7272 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-25 17:21:23.419  1034  1755 I ActivityManager: Killing 6077:com.android.vending/u0a44 (adj 15): empty #17
,08-25 17:21:23.449  1034  7152 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 17:21:23.450  1034  7152 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 17:21:23.450  1034  7152 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 17:21:23.450  1034  7152 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 17:21:23.450  1034  7152 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 17:21:23.450  1034  7152 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 17:21:23.450  1034  7152 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 17:21:23.450  1034  7152 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 17:21:23.451  1034  7152 D DhcpStateMachine: RunningState
08-25 17:21:23.468  1034  1049 W libprocessgroup: failed to open /acct/uid_10044/pid_6077/cgroup.procs: No such file or directory
,08-25 17:21:23.490  7272  7272 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 17:21:23.707  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 17:21:23.710  6385  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 17:21:23.718  2155  2155 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:23.725  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-25 17:21:23.725  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:23.725  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 17:21:23.725  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 17:21:23.725  1034  1921 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-25 17:21:23.725  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:23.725  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:23.725  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 17:21:23.725  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:23.725  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-25 17:21:23.727  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
08-25 17:21:23.728   309  7301 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 17:21:23.728   309  7301 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-25 17:21:23.738  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12779245
08-25 17:21:23.738  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:21:23.738  7001  7001 D AppUp4:CustFacade: isPhone : true
,08-25 17:21:23.741  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:21:23.741  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 17:21:23.744  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:23.744  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:21:23.745  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:23.747  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:23.750  2842  2842 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:23.752  7022  7022 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 17:21:23.753  2842  2842 V DownloadManager: DownloadService onCreate
,08-25 17:21:23.755  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:21:23 GMT], X-Android-Received-Millis=[1472138483754], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472138483732]}
08-25 17:21:23.755  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 17:21:23.755  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 17:21:23.755  1034  1540 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 17:21:23.755  1034  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 17:21:23.755  4302  7305 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:23.755  1034  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:23.755  1034  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:23.755  4302  7305 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:23.755  1034  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 17:21:23.755  1034  1540 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 17:21:23.755  1034  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 17:21:23.755  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:23.755  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:23.756  4302  7304 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 17:21:23.756  1034  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:23.756  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:21:23.758  2842  7306 I DownloadManager: in removeSpuriousFiles
08-25 17:21:23.759  2842  7306 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-25 17:21:23.759   309  7301 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-25 17:21:23.760  2842  7306 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f8ea2d9 on behalf of 2842
08-25 17:21:23.760  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-25 17:21:23.760  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-25 17:21:23.760  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-25 17:21:23.760  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-25 17:21:23.761  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-25 17:21:23.761  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-25 17:21:23.761  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemo,plus(LG-D855_user)_20150902050954661.apk
08-25 17:21:23.761  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-25 17:21:23.761  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-25 17:21:23.761  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-25 17:21:23.761  2842  7306 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-25 17:21:23.762  2842  7306 I DownloadManager: in trimDatabase
08-25 17:21:23.762  2842  7306 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-25 17:21:23.762  2842  7306 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@322fa49e on behalf of 2842
08-25 17:21:23.764  4302  7304 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-25 17:21:23.764  2842  2842 V DownloadManager: DownloadService onStartCommand
08-25 17:21:23.764  2842  7307 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-25 17:21:23.766  2842  7307 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@bd9395 on behalf of 2842
08-25 17:21:23.771  2842  7307 V DownloadManager: processing inserted download 1
08-25 17:21:23.773  2842  7307 V DownloadManager: processing inserted download 4
08-25 17:21:23.774  2842  7307 V DownloadManager: processing inserted download 7
08-25 17:21:23.774  2842  7307 V DownloadManager: processing inserted download 8
08-25 17:21:23.775  2842  7307 V DownloadManager: processing inserted download 9
08-25 17:21:23.775  2842  7307 V DownloadManager: processing inserted download 10
08-25 17:21:23.776  2842  7307 V DownloadManager: processing inserted download 11
08-25 17:21:23.776  2842  7307 V DownloadManager: processing inserted download 12
08-25 17:21:23.778  2842  7307 V DownloadManager: processing inserted download 13
08-25 17:21:23.778  4302  7304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-25 17:21:23.778  2842  7307 V DownloadManager: processing inserted download 14
08-25 17:21:23.780  4302  4302 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-25 17:21:23.780  4302  4302 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-25 17:21:23.780  4302  4302 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-25 17:21:23.781  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 17:21:23.781  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:23.781  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 17:21:23.782  4302  4302 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-25 17:21:23.783  7071  7071 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 17:21:23.783  7071  7071 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 17:21:23.784  2842  7307 V DownloadManager: processing inserted download 16
08-25 17:21:23.791  4302  4302 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-25 17:21:23.800  7022  7310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:23.801  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:23
08-25 17:21:23.803  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 17:21:23.803  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-25 17:21:23.809  2842  2842 V DownloadManager: DownloadService onDestroy
08-25 17:21:23.809  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 17:21:23.810  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-25 17:21:23.810  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e8e96cb
08-25 17:21:23.810  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 17:21:23.810  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-25 17:21:23.811  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 17:21:23.811  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 17:21:23.811  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:23
08-25 17:21:23.857   309  7322 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 17:21:23.857   309  7322 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-25 17:21:23.860  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:21:23.860  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:21:23.860  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:21:23.860  6797  6797 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 17:21:23.863  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:21:23.863  6797  6797 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:21:23.863  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 17:21:23.863  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:21:23.863  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:21:23.863  6797  6797 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:21:23.863  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 17:21:23.864  6797  6797 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:21:23.871  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:21:23.875  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:21:23.878  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:23.893  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:21:23.899  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:21:23.899   309  7322 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
08-25 17:21:23.899  7214  7231 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:23.900  7214  7231 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 17:21:23.904  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:23.915  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 17:21:23.916  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:21:23.918  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:23.921  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:23.927  4302  7326 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:21:23.928  4302  7328 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:21:23.928  4302  7328 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:23.934  4302  7326 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-25 17:21:23.939  6911  7315 V FormManager: There are no updated forms. The schedule will be deleted.
,08-25 17:21:23.942  6911  7315 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-25 17:21:23.944  7327  7327 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-25 17:21:23.954  1034  1540 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 17:21:23.973  1034  2010 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7334 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 17:21:23.974  1034  1888 D WifiServiceImplEx: setWifiEnabled: false pid=6715, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:21:23.975  1034  1888 D WifiService: setWifiEnabled: false pid=6715, uid=10118
08-25 17:21:23.975  1034  1888 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:21:23.977  4302  7326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-25 17:21:23.979  4302  4302 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-25 17:21:23.979  4302  4302 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-25 17:21:23.980  4302  4302 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-25 17:21:23.981  4302  4302 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-25 17:21:23.981  7327  7327 I dex2oat : dex2oat took 37.461ms (threads: 4)
08-25 17:21:23.986  1034  1439 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:23.986  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:23.986  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:21:23.986  1034  1439 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-25 17:21:23.986  1034  1439 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:23.986  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:23.986  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 17:21:23.986  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 17:21:23.986  1034  1439 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 17:21:23.987  1034  1439 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:21:23.987  1034  1439 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:21:23.987  1034  1439 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:21:23.987  1034  1439 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:21:23.987  4302  4302 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-25 17:21:23.991  1034  1439 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 17:21:23.991  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:21:23.991  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:23.991  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:23.991  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:21:23.991  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:21:23.991  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:21:23.992  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:23.992   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:21:23.992  1034  7152 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:23.998  7214  7231 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:21:23.998  7214  7231 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:21:23.998  7214  7231 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:21:23.998  7214  7231 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:21:23.998  7214  7231 I Adreno-EGL: Remote Branch: 
08-25 17:21:23.998  7214  7231 I Adreno-EGL: Local Patches: 
08-25 17:21:23.998  7214  7231 I Adreno-EGL: Reconstruct Branch: 
,08-25 17:21:24.011  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 17:21:24.011  1034  1540 D ConnectivityService: ignoring duplicate network state non-change
08-25 17:21:24.011  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-25 17:21:24.012  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 17:21:24.013  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:24.013  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:24.013  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.013  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.013  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:24.015  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 17:21:24.015  1034  1439 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:24.015  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:24.015  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:24.015  1034  1439 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 17:21:24.016  1034  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.016  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.016  1034  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@5288c6b
08-25 17:21:24.017  1034  1390 D LGWifiP2pService: P2pDisablingState
08-25 17:21:24.018  1034  1390 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.018  1034  1390 D LGWifiP2pService: p2p socket connection lost
08-25 17:21:24.018  1034  1390 D LGWifiP2pService: P2pDisabledState
08-25 17:21:24.018  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 17:21:24.018  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.018  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.018  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:24.018  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 17:21:24.018  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-25 17:21:24.018  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.018  1034  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.018  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:24.021  1034  1439 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 17:21:24.021  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:21:24.022  7056  7056 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-25 17:21:24.023  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.023  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.025  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 17:21:24.025  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:21:24.025  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:21:24.025  1942  1942 D WfdsService: WifiP2pState is changed : false
08-25 17:21:24.025  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:24.025  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:24.025  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:24.025  1942  2318 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 17:21:24.025  1942  2318 D WfdsService: Set the WFDS Monitor: false
08-25 17:21:24.026  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:24.026  1942  2318 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:21:24.026  1942  2318 D WfdsService: STATE : WfdsDisabledState - enter
08-25 17:21:24.027  1942  7110 D CtrlSupplicant: Received on exit socket, terminate
08-25 17:21:24.027  1942  7110 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 17:21:24.027  1942  7110 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 17:21:24.027  1942  7110 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 17:21:24.027  1942  2318 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 17:21:24.027  1942  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 17:21:24.040  6911  7315 V FormManager: Network unavailable.
,08-25 17:21:24.043  6911  7315 V FormManager: Network unavailable.
08-25 17:21:24.045  6911  7315 V FormManager: Network unavailable.
08-25 17:21:24.045   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:21:24.045  1034  1540 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 17:21:24.046  1034  1540 D DSQN    : disableDataServiceNotify
08-25 17:21:24.046  1034  1540 D DSQN    : stop dsqn bin
08-25 17:21:24.047  1034  1439 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 17:21:24.047  1034  1439 D WifiNative-p2p0: TERMINATE: returned true
08-25 17:21:24.047  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:24.047  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:24.047  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:21:24.047  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 17:21:24.048  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.048  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.048  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:24.048  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 17:21:24.048  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:24.049  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:24.050  1034  1540 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 17:21:24.050  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:24.050  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:24.050  1034  1540 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:24.050  1034  1540 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 17:21:24.051  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.051  1034  1540 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 17:21:24.051  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.051  1034  7151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 17:21:24.051  1034  1540 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 17:21:24.051  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.,CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:21:24.051  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 17:21:24.051  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:24.051  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 17:21:24.052  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 17:21:24.052  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 17:21:24.053  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:24.053  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:24.053  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:24.053  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:21:24.054  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:24.054  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:24.054  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:24.054  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:24.055  1034  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:24.055  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:21:24.055  1034  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:24.055  1034  1540 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:24.055  1034  1540 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:24.056  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 17:21:24.056  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:21:24.056  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:21:24.056  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:21:24.057  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 17:21:24.057  1034  1439 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:24.058  1034  1439 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:24.058  1034  1540 D NetworkManagementService: Removing idletimer
08-25 17:21:24.058  1034  1540 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.058  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 17:21:24.058  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:21:24.058  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:21:24.058  1034  1034, D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:21:24.059  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:24.059  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 17:21:24.059  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 17:21:24.062  6911  7358 W FormManager: Network not available. Please check & try again.
08-25 17:21:24.066  6911  7359 V FormManager: Network unavailable.
08-25 17:21:24.068  6911  7359 V FormManager: Network unavailable.
,08-25 17:21:24.071  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:24.074  6911  7360 W FormManager: Network not available. Please check & try again.
08-25 17:21:24.078  6911  7361 V FormManager: Network unavailable.
08-25 17:21:24.081  6911  7361 V FormManager: Network unavailable.
,08-25 17:21:24.086  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:24.087  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:24.087  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:24.098  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:24.098  7334  7334 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 17:21:24.098  7334  7334 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-25 17:21:24.099  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:24.099  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:24.103  7334  7334 V [BNRBootReceiver]: Boot Receiver Return
08-25 17:21:24.105  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.105  7334  7334 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 17:21:24.107  7214  7231 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:21:24.107  7214  7231 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:21:24.107  7214  7231 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:21:24.107  7214  7231 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:21:24.107  7214  7231 I Adreno-EGL: Remote Branch: 
08-25 17:21:24.107  7214  7231 I Adreno-EGL: Local Patches: 
08-25 17:21:24.107  7214  7231 I Adreno-EGL: Reconstruct Branch: 
08-25 17:21:24.109  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.113  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.119  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.119  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.119  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:21:24.121  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 17:21:24.123  6797  6797 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-25 17:21:24.124  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.128  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:24.131  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.134  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.134  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.135  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 17:21:24.137  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.141  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:24.144  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.147  7056  7056 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 17:21:24.147  7056  7056 I wpa_supplicant: monitor socket send errors count : 1
08-25 17:21:24.147  7056  7056 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
08-25 17:21:24.149  1034  7098 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 17:21:24.149  1034  7098 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 17:21:24.149  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.149  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.149  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:24.151  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.155  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.159  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.162  7214  7231 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 17:21:24.162  7214  7231 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 17:21:24.162  7214  7231 I Adreno-EGL: Build Date: 12/12/14 금
08-25 17:21:24.162  7214  7231 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 17:21:24.162  7214  7231 I Adreno-EGL: Remote Branch: 
08-25 17:21:24.162  7214  7231 I Adreno-EGL: Local Patches: 
08-25 17:21:24.162  7214  7231 I Adreno-EGL: Reconstruct Branch: 
08-25 17:21:24.162  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.163  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.163  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:24.165  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.168  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:21:24.169  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 17:21:24.169  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:21:24.169  1034  7098 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:21:24.169  1034  7098 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 17:21:24.169  7056  7056 W wpa_supplicant: USIM:  scard_deinit function
08-25 17:21:24.169  1034  1439 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194568
08-25 17:21:24.170  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:24.170  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:24.170  1034  1439 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194569
08-25 17:21:24.170  1034  1116 D Tethering: InitialState.processMessage what=4
08-25 17:21:24.171  1034  1439 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=194569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 17:21:24.171  1034  1439 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=194569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-25 17:21:24.172  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 17:21:24.173  1034  1439 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:24.173  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:24.174  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:24.181  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.184  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.184  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.185  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 17:21:24.188  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.192  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.195  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.196  1034  7152 D DhcpStateMachine: StoppedState
08-25 17:21:24.196  1034  7152 D DhcpStateMachine: StoppedState{ when=-170ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:24.196  1034  1439 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 17:21:24.197  1034  1439 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-25 17:21:24.201  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.201  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:24.201  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:24.203  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.207  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.212  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.218  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:21:24.219  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.219  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:24.224  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.231  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.236  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.241  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.241  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.244  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 17:21:24.247  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.256  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.261  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.265  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:21:24.265  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.266  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:24.270   309  7364 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 17:21:24.270  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.271  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 17:21:24.272  1818  7187 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-25 17:21:24.277  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 17:21:24.280  1818  7187 I CheckinService: active receiver: disabled
08-25 17:21:24.289  7056  7056 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-25 17:21:24.291  1034  7098 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 17:21:24.291  1034  7098 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 17:21:24.292  1034  7098 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 17:21:24.293  1034  1439 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-25 17:21:24.296  1034  1525 D WifiService: New client listening to asynchronous messages
08-25 17:21:24.296  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:24.300  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.307  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.313  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.313  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:24.314  6870  6870 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 17:21:24.315  6870  6870 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 17:21:24.315  6870  6870 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 17:21:24.320  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.323  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 17:21:24.325  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:21:24.328  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:24.332  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.337  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.338  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:24.338  6870  6870 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 17:21:24.339  6870  6870 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 17:21:24.340  6870  6870 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 17:21:24.342  1034  1995 I ActivityManager: Killing 6821:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-25 17:21:24.378  1034  1710 W libprocessgroup: failed to open /acct/uid_10037/pid_6821/cgroup.procs: No such file or directory
,08-25 17:21:24.385  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{217470c8 type 2 when 194767 com.google.android.gms} when 194767
08-25 17:21:24.389  2155  2155 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 17:21:24.406  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-25 17:21:24.407  1942  2318 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-25 17:21:24.406  1034  1439 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 17:21:24.407  1942  2318 D WfdsService: Set the WFDS Monitor: false
08-25 17:21:24.407  1942  2318 D WfdsMonitor: WFDS Monitor is stopped
08-25 17:21:24.407  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:24.407  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:24.407  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:21:24.413  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 17:21:24.415  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:24.416  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 17:21:24.416  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:24.417  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:24.417  1034  1484 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 17:21:24.417  1034  1484 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 17:21:24.418  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:24.418  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:24.421  2155  2155 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-25 17:21:24.422  2447  2447 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:24.423  2155  2155 D c       : Getting all permits...
08-25 17:21:24.423  2155  2155 D a       : Opening database...
,08-25 17:21:24.432  2155  2155 D a       : Opening database auth.proximity.permit_store...
08-25 17:21:24.433  2155  2155 D a       : Closing database...
08-25 17:21:24.448  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:21:24.451  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:21:24.451  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:24.452  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:24.455  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:24.460  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.467  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.468  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:24.469  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:21:24.473  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:24.476  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:21:24.476  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:24.476  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:24.480  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.488  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:21:24.498  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:24.499  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:24.505  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:21:24.512  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:21:24.516  6841  6841 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 17:21:24.516  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:24.516  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:24.521  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:24.530  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.542  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 17:21:24.542  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:24.545  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:21:24.556  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:21:24.564  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:21:24.570  6911  7369 W FormManager: Network not available. Please check & try again.
,08-25 17:21:24.576  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.586  6911  7370 V FormManager: Network unavailable.
,08-25 17:21:24.594  6911  7370 V FormManager: Network unavailable.
08-25 17:21:24.604  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-25 17:21:24.604  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:21:24.604  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:21:24.604  6797  6797 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 17:21:24.611  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:21:24.612  6797  6797 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:21:24.612  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 17:21:24.613  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:21:24.613  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:21:24.613  6797  6797 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:21:24.614  6797  6797 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:21:24.622  2155  2155 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-25 17:21:24.649  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:21:24.649  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 17:21:24.656  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:24.660  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 17:21:24.670  4302  7372 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 17:21:24.675  6841  6841 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 17:21:24.676  6841  6841 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 17:21:24.676  6841  6841 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:24.678  4302  7373 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:21:24.679  4302  7373 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:24.681  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:21:24.688  6911  7375 W FormManager: Network not available. Please check & try again.
08-25 17:21:24.690  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:24.698  6911  7376 V FormManager: Network unavailable.
,08-25 17:21:24.702  6911  7376 V FormManager: Network unavailable.
08-25 17:21:24.980  6592  6995 D UEI.SmartControl: Internal timer expired: 4
08-25 17:21:24.980  6592  6995 D UEI.SmartControl: unbind internal service
,08-25 17:21:25.078  6592  6989 D serial_port: close(fd = 24)
,08-25 17:21:25.091  6592  6989 I UEI.SmartControl: Serial port is closed.
,08-25 17:21:25.833  1034  1439 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1035296695] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 17:21:25.835  1034  1439 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1035296693] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 17:21:25.938  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:25.954  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-25 17:21:25.960  1034  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:25.969  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:25.970  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:25.976  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 17:21:25.981  6385  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 17:21:25.992  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 17:21:26.015  2155  2155 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:26.043  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 17:21:26.044  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:26.044  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 17:21:26.044  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 17:21:26.051  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
08-25 17:21:26.054  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12779245
08-25 17:21:26.054  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:21:26.054  7001  7001 D AppUp4:CustFacade: isPhone : true
08-25 17:21:26.055  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:21:26.055  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 17:21:26.060  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:26.060  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:21:26.062  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 17:21:26.069  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:26.078  7022  7022 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 17:21:26.109  4302  7388 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:21:26.114  1034  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 17:21:26.116  7022  7387 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:26.122  4302  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:26.122  4302  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:26.128  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 17:21:26.128  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:26.129  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 17:21:26.129  3421  3421 D PhoneState: setPdpRejectCasuse : false
08-25 17:21:26.133  6911  7403 W FormManager: Network not available. Please check & try again.
08-25 17:21:26.134  7071  7071 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 17:21:26.134  7071  7071 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 17:21:26.143  6911  7405 V FormManager: Network unavailable.
,08-25 17:21:26.145  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:26
,08-25 17:21:26.147  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 17:21:26.147  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-25 17:21:26.149  6911  7405 V FormManager: Network unavailable.
,08-25 17:21:26.149  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 17:21:26.149  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-25 17:21:26.149  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e8e96cb
08-25 17:21:26.150  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 17:21:26.150  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-25 17:21:26.150  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0,
,08-25 17:21:26.150  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-25 17:21:26.150  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:26
,08-25 17:21:26.988  1034  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:21:26.988  1034  2010 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false,
,08-25 17:21:27.028  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:21:27.029  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:27.029  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-25 17:21:27.033  1034  1116 D BluetoothManagerService: Message: 1
08-25 17:21:27.033  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 17:21:27.056  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:27.067  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:27.067  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-25 17:21:27.070  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:27.075  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.080  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-25 17:21:27.092  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:27.097  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:27.103  1034  1116 D BluetoothManagerService: Message: 20
08-25 17:21:27.103  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c4a810d:true
08-25 17:21:27.104  6943  6943 D BluetoothAdapterState: make
08-25 17:21:27.108  6943  6943 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 17:21:27.109  6943  6943 I bluedroid-qcom: init
,08-25 17:21:27.113  6943  7420 I BluetoothAdapterState: Entering OffState
08-25 17:21:27.113  6943  6943 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 17:21:27.114  6943  6943 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 17:21:27.114  6943  6943 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 17:21:27.114  6943  6943 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 17:21:27.114  6943  6943 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 17:21:27.116  6943  6943 I bluedroid-qcom: get_profile_interface socket
08-25 17:21:27.116  6943  6943 I bluedroid-qcom: get_profile_interface map_client
08-25 17:21:27.117  6943  7424 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 17:21:27.119  6943  7424 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 17:21:27.107  7423  7423 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:27.107  7423  7423 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:27.129  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 17:21:27.129  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-25 17:21:27.137  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 17:21:27.137  1034  1116 D BluetoothManagerService: Message: 40
08-25 17:21:27.137  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 17:21:27.138  6943  6961 I bluedroid-qcom: config_hci_snoop_log
08-25 17:21:27.139  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 17:21:27.139  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 17:21:27.141  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 17:21:27.141  7423  7423 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 17:21:27.141  7423  7423 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 17:21:27.143  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-25 17:21:27.155  6943  7420 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 17:21:27.155  6943  7424 D BluetoothAdapterProperties: Name is: G3
08-25 17:21:27.155  6943  7420 D BluetoothAdapterProperties: Setting state to 11
08-25 17:21:27.155  6943  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 17:21:27.158  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:27.158  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,08-25 17:21:27.161  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 17:21:27.166  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:27.166  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:21:27.170  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:27.172  6797  6797 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-25 17:21:27.175  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:27.188  7423  7423 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 17:21:27.188  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-25 17:21:27.193  1034  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.197  6943  7420 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 17:21:27.199  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 17:21:27.200  6385  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 17:21:27.210  6943  6943 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:21:27.211  6943  6943 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:27.211  6943  6943 V BluetoothPbapReceiver: ***********state = 11
08-25 17:21:27.212  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 17:21:27.215  6943  7420 D BluetoothBondStateMachine: make
,08-25 17:21:27.217  6943  7441 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 17:21:27.217  6943  7420 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.217  6943  7420 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 17:21:27.217  6943  7420 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.217  6943  7420 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 17:21:27.218  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:21:27.218  6943  7420 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 17:21:27.219  1034  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.225  6943  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:21:27.268  1034  1961 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7443 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 17:21:27.275  6943  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:27.277  6943  6943 D HeadsetService: Received start request. Starting profile...
08-25 17:21:27.277  6943  6943 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:21:27.278  6943  6943 D LGBluetoothHfpAdapter: Version 1.6
08-25 17:21:27.278  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 17:21:27.280  1034  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 17:21:27.280  1034  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:27.281  6943  6943 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:21:27.282  6943  6943 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:21:27.282  6943  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:27.283  6943  6943 D HeadsetStateMachine: make
08-25 17:21:27.296  6943  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:21:27.299  2155  2155 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.310  6943  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:21:27.316  6943  6943 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:27.316  6943  6943 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 17:21:27.318  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 17:21:27.318  6943  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:27.318  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.318  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 17:21:27.319  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 17:21:27.321  6943  6943 D HeadsetStateMachine: max_hf_connections = 1
08-25 17:21:27.322  6943  6943 I bluedroid-qcom: get_profile_interface handsfree
08-25 17:21:27.322  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
08-25 17:21:27.323  6943  6943 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-25 17:21:27.324   318  2208 V AudioPolicyService: registerClient() client 0xb0003e60, uid 1002
08-25 17:21:27.324   318   318 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 17:21:27.324   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:21:27.324   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:21:27.325  6943  6943 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 17:21:27.325   318  2206 V AudioFlinger: registerClient() client 0xb55814f0, pid 6943
08-25 17:21:27.326   318  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:27.326   318  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:27.326  6943  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:27.326  6943  6943 V ToneGenerator: Create Track: 0xb4928a80
08-25 17:21:27.326  6943  6943 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 17:21:27.326  1034  2036 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:27.326  6943  6943 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 17:21:27.326   318  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:21:27.326   318  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 17:21:27.326   318  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:21:27.326   318  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:21:27.326  6943  6943 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 17:21:27.327   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 17:21:27.327   318  2206 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:21:27.327   318  2206 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 17:21:27.327   318  2206 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:21:27.327   318  2206 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:21:27.327  1603  2100 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:27.327  1603  2100 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:27.327   318  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:27.327   318  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:27.327  1854  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:27.327  1854  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:27.327  1854  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:27.327  1854  1869 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:27.327  3421  3437 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:27.327  3421  3437 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:27.328  3421  3437 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:27.328  3421  3437 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:27.328  6943  6961 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:27.328  6943  6961 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 17:21:27.328  6943  6961 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:27.328  6943  6961 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 17:21:27.328  1603  4417 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:27.,328  1603  4417 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:27.328  1034  2036 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:27.328  1034  2036 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:27.328  1034  2036 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:27.328  6943  6943 V AudioSystem: getLatency() output 2, latency 50
08-25 17:21:27.328  6943  6943 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 17:21:27.328  6943  6943 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 17:21:27.328   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 17:21:27.328   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:21:27.328   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 17:21:27.328   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:21:27.328   318  1397 V AudioFlinger: createTrack() lSessionId: 22
08-25 17:21:27.329  6943  6943 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 17:21:27.329   318  2208 V AudioFlinger: acquiring 22 from 6943, for 6943
08-25 17:21:27.330   318  2208 V AudioFlinger:  added new entry for 22
08-25 17:21:27.330  6943  6943 V ToneGenerator: ToneGenerator INIT OK, time: 197743
08-25 17:21:27.330  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.331  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.332  6943  6943 D A2dpService: Received start request. Starting profile...
08-25 17:21:27.332  6943  6943 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:21:27.333  6943  6943 V Avrcp   : make
08-25 17:21:27.333  6943  6943 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 17:21:27.333  6943  6943 I bluedroid-qcom: get_profile_interface avrcp
08-25 17:21:27.334  6943  7458 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 17:21:27.334  6943  7458 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:21:27.334  6943  7458 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:21:27.335  6943  7458 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 17:21:27.335   318   318 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6943
08-25 17:21:27.335   318   318 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 17:21:27.335   318   318 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 17:21:27.335   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 17:21:27.335   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 17:21:27.335   318   318 V voice   : voice_set_parameters: exit with code(0)
08-25 17:21:27.335   318   318 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 17:21:27.335   318   318 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 17:21:27.335   318   318 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 17:21:27.335   318   318 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 17:21:27.335   318   318 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 17:21:27.335   318   318 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 17:21:27.335  6943  7458 V ToneGenerator: ToneGenerator destructor
08-25 17:21:27.335  6943  7458 V ToneGenerator: stopTone
08-25 17:21:27.335  6943  7458 V ToneGenerator: Delete Track: 0xb4928a80
08-25 17:21:27.336  6943  7458 V AudioTrack: ~AudioTrack, releasing session id from 694,3 on behalf of 6943
08-25 17:21:27.336   318  2206 V AudioFlinger: releasing 22 from 6943 for 6943
08-25 17:21:27.336   318  2206 V AudioFlinger:  decremented refcount to 0
08-25 17:21:27.336   318  2206 V AudioFlinger: purging stale effects
08-25 17:21:27.336   318  2206 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 17:21:27.336   318  2206 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 17:21:27.337   318  1272 V AudioPolicyService: AudioCommandThread() waking up
08-25 17:21:27.337   318  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 17:21:27.337   318  1272 V AudioPolicyManager: releaseOutput() 2
08-25 17:21:27.337   318  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 17:21:27.338  1034  1575 W Process : Unable to open /proc/7461/status
08-25 17:21:27.338   318  2206 V AudioFlinger: PlaybackThread::Track destructor
08-25 17:21:27.338   318  2206 V AudioFlinger: removeClient_l() pid 6943, calling pid 318
08-25 17:21:27.342  6943  7420 V LGMDMManager: Create singleton instance
08-25 17:21:27.343  6943  7420 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 17:21:27.344  6943  6943 V AudioManager: registerRemoteController: size of Media player list: 0
08-25 17:21:27.347  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12779245
08-25 17:21:27.347  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:21:27.347  7001  7001 D AppUp4:CustFacade: isPhone : true
08-25 17:21:27.347  6943  6943 E AudioManager: No RCC entry present to update
08-25 17:21:27.347  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:21:27.347  6943  6943 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 17:21:27.347  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 17:21:27.349  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.350  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 17:21:27.350  6943  6943 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 17:21:27.350  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 17:21:27.350  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:27.350  6943  6943 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 17:21:27.352  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:27.354  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 17:21:27.358  4302  7465 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 17:21:27.359  4302  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.359  4302  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:27.397  7443  7443 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 17:21:27.397  7443  7443 W LG Account v2.2: No ProfileInfo entries
08-25 17:21:27.397  7443  7443 I LG Account v2.2: isEnabled: false
,08-25 17:21:27.397  7443  7443 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 17:21:27.397  7443  7443 I Feature : [Lifetracker]Country: EU
08-25 17:21:27.397  7443  7443 I Feature : [Lifetracker]Operator: OPEN
08-25 17:21:27.397  7443  7443 I Feature : [Lifetracker]Ranking support: false
08-25 17:21:27.397  7443  7443 I Feature : [Lifetracker]Comfort support: false
08-25 17:21:27.397  7443  7443 I Feature : [Lifetracker]Accessory: true
08-25 17:21:27.397  7443  7443 I Feature : [Lifetracker]Health device: true
08-25 17:21:27.398  7443  7443 I Feature : [Lifetracker]Extra Pedometer: false
08-25 17:21:27.398  7443  7443 I Feature : [Lifetracker]Blood glucose device: false
08-25 17:21:27.398  7443  7443 I Feature : [Lifetracker]Device Number: 3
08-25 17:21:27.398  7022  7022 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 17:21:27.414  6797  6797 D BluetoothPermissionRequest: onReceive
,08-25 17:21:27.419  7022  7469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:27.420  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:21:27.430  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 17:21:27.431  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.431  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 17:21:27.431  6911  7471 W FormManager: Network not available. Please check & try again.
,08-25 17:21:27.432  7071  7071 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 17:21:27.433  7071  7071 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 17:21:27.436  6911  7472 V FormManager: Network unavailable.
08-25 17:21:27.441  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:27
08-25 17:21:27.442  1034  1995 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:21:27.442  1034  1995 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:21:27.443  6911  7472 V FormManager: Network unavailable.
,08-25 17:21:27.446  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-25 17:21:27.446  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-25 17:21:27.447  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 17:21:27.447  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-25 17:21:27.447  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e8e96cb
08-25 17:21:27.447  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 17:21:27.447  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 17:21:27.447  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 17:21:27.447  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 17:21:27.447  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:27
08-25 17:21:27.463  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 17:21:27.464  6385  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 17:21:27.474  2155  2155 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.479  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 17:21:27.479  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:27.479  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 17:21:27.479  7001  7001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 17:21:27.481  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
08-25 17:21:27.483  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12779245
08-25 17:21:27.483  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:21:27.483  7001  7001 D AppUp4:CustFacade: isPhone : true
08-25 17:21:27.483  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:21:27.484  7001  7001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 17:21:27.486  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.487  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 17:21:27.488  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:27.489  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:27.494  7022  7022 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 17:21:27.496  4302  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:21:27.496  4302  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:27.497  4302  7474 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 17:21:27.506  7022  7476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:21:27.511  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 17:21:27.511  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:27.511  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 17:21:27.513  7071  7071 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 17:21:27.513  7071  7071 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 17:21:27.516  6911  7479 V FormManager: Network unavailable.
08-25 17:21:27.520  6911  7478 W FormManager: Network not available. Please check & try again.
,08-25 17:21:27.522  7133  7133 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:27
08-25 17:21:27.522  7133  7133 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 17:21:27.523  6911  7479 V FormManager: Network unavailable.
08-25 17:21:27.523  7133  7133 D Weather.Utils: 2 : All the weather widget is gone.
08-25 17:21:27.523  7133  7133 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 17:21:27.523  7133  7133 D WeatherAncestor: connectivity changed - connection : true
08-25 17:21:27.523  7133  7133 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e8e96cb
08-25 17:21:27.523  7133  7133 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 17:21:27.523  7133  7133 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 17:21:27.524  7133  7133 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 17:21:27.524  7133  7133 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 17:21:27.524  7133  7133 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:27
08-25 17:21:27.527  1034  1960 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 17:21:27.533  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 17:21:27.537  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 17:21:27.538  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:21:27.538  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 17:21:27.538  6943  6943 I BluetoothA2dpServiceJni: classInitNative
08-25 17:21:27.538  6943  6943 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:21:27.538  6943  6943 D A2dpStateMachine: make
08-25 17:21:27.539  6943  6943 I bluedroid-qcom: get_profile_interface a2dp
08-25 17:21:27.539  6943  7482 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 17:21:27.540  6943  6943 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:21:27.541  6943  6943 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 17:21:27.541  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.541  6943  7481 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:21:27.542  6943  6943 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 17:21:27.543  6943  6943 D HidService: Received start request. Starting profile...
08-25 17:21:27.543  6943  6943 I bluedroid-qcom: get_profile_interface hidhost
08-25 17:21:27.543  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.543  6943  6943 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:21:27.545  6943  6943 D HealthService: Received start request. Starting profile...
08-25 17:21:27.546  6943  6943 I bluedroid-qcom: get_profile_interface health
,08-25 17:21:27.546  6943  6943 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,08-25 17:21:27.546  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.547  6943  6943 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 17:21:27.548  6943  6943 D PanService: Received start request. Starting profile...
08-25 17:21:27.548  6943  6943 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 17:21:27.548  6943  6943 I bluedroid-qcom: get_profile_interface pan
08-25 17:21:27.553  6943  6943 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 17:21:27.553  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.553  6943  6943 D HeadsetStateMachine: Proxy object connected
08-25 17:21:27.553  6943  6943 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 17:21:27.553  6943  6943 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 17:21:27.555  6943  6943 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 17:21:27.559  6943  6943 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:21:27.559  6943  6943 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:21:27.559  6943  6943 D BtGatt.GattService: start()
08-25 17:21:27.559  6943  6943 I bluedroid-qcom: get_profile_interface gatt
08-25 17:21:27.559  6943  6943 D BtGatt.AdvertiseManager: advertise manager created
,08-25 17:21:27.563  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.564  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:27.564  6943  6943 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 17:21:27.565  6943  6943 V BluetoothMapService: BluetoothMapBinder()
08-25 17:21:27.565  6943  6943 D BluetoothMapService: Received start request. Starting profile...
08-25 17:21:27.565  6943  6943 D BluetoothMapService: start()
08-25 17:21:27.567  6943  6943 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 17:21:27.567  6943  6943 D BluetoothMapEmailAppObserver: createReceiver()
08-25 17:21:27.568  6943  6943 D BluetoothMapEmailAppObserver: initObservers()
08-25 17:21:27.568  6943  6943 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 17:21:27.574  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
,08-25 17:21:27.575  6943  7458 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 17:21:27.575  6943  7458 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 17:21:27.576  6943  7458 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 17:21:27.577  6943  6943 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:21:27.580  6943  6943 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:21:27.582  6943  6943 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:21:27.584  6943  6943 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:21:27.585  6943  6943 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 17:21:27.587  6943  6943 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 17:21:27.589  6943  6943 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 17:21:27.589  6943  6943 V BluetoothMapService: Handler(): got msg=1
08-25 17:21:27.590  6943  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 17:21:27.590  6943  7420 I bluedroid-qcom: enable
08-25 17:21:27.590  6943  7420 I bt_hci_bdroid: init
08-25 17:21:27.590  6943  7489 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 17:21:27.591  6943  6943 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:27.591  6943  7420 I bt_vendor: bt-vendor : init
08-25 17:21:27.591  6943  7420 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 17:21:27.591  6943  7420 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 17:21:27.591  6943  7420 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 17:21:27.591  6943  7420 D bt_userial_mct: userial_init
08-25 17:21:27.591  6943  7489 I bt-btu  : btu_task pending for preload complete event
08-25 17:21:27.591  6943  7420 D bt_hci_bdroid: set_power 1
08-25 17:21:27.591  6943  7420 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 17:21:27.591  6943  7420 I bt_vendor: Starting hciattach daemon
08-25 17:21:27.591  6943  7420 I bt_vendor: try to set true
08-25 17:21:27.577  7492  7492 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:27.577  7492  7492 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:27.595  6943  6943 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:21:27.595  6943  6943 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:27.596  6943  6943 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:27.596  6943  6943 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:27.596  6943  6943 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 17:21:27.610  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 17:21:27.675  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 17:21:27.682  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 17:21:27.713  7502  7502 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:21:27.724  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 17:21:27.741  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:21:27.754  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 17:21:27.798  7507  7507 I libmdmdetect: ESOC framework not supported
08-25 17:21:27.800  7507  7507 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 17:21:27.810  7507  7507 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 17:21:27.810  7507  7507 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 17:21:27.810  7507  7507 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 17:21:27.810  7507  7507 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 17:21:27.810  7507  7507 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 17:21:27.810  7507  7507 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 17:21:27.810  7507  7507 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 17:21:27.857  7507  7511 E QC-QMI  : qmi_client [7507] 14: failed to locate client data
,08-25 17:21:27.857   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 17:21:27.857   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-25 17:21:27.885  1034  1105 W ProcessCpuTracker: Skipping unknown process pid 7435
,08-25 17:21:27.886  1034  1105 W ProcessCpuTracker: Skipping unknown process pid 7436
08-25 17:21:27.887  1034  1105 W ProcessCpuTracker: Skipping unknown process pid 7439
08-25 17:21:27.888  1034  1105 W ProcessCpuTracker: Skipping unknown process pid 7442
08-25 17:21:27.890  1034  1105 W ProcessCpuTracker: Skipping unknown process pid 7508
08-25 17:21:27.906  7515  7515 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 17:21:27.921  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:21:27.944  6943  7420 I bt_vendor: bluetooth satus is on
08-25 17:21:27.944  6943  7420 D bt_hci_bdroid: preload
08-25 17:21:27.944  6943  7491 D bt_userial_mct: userial_open(port:0)
08-25 17:21:27.945  6943  7491 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 17:21:27.949  6943  7491 I bt_vendor: Done intiailizing UART
08-25 17:21:27.950  6943  7491 I bt_vendor: Done intiailizing UART
08-25 17:21:27.950  6943  7491 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 17:21:27.950  6943  7491 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 17:21:27.951  6943  7518 D bt_userial_mct: Entering userial_read_thread()
08-25 17:21:27.951  6943  7489 I bt-btu  : btu_task received preload complete event
08-25 17:21:27.951  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 17:21:27.951  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 17:21:27.953  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:21:27.956  6943  7489 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 17:21:27.957  6943  7489 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 17:21:27.957  6943  7489 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:21:27.957  6943  7489 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:21:27.957  6943  7489 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 17:21:27.957  6943  7489 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:21:27.957  6943  7489 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:21:27.957  6943  7489 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 17:21:28.016  7157  7188 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-25 17:21:28.035  6943  7489 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-25 17:21:28.035  6943  7489 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c1061 
08-25 17:21:28.035  6943  7489 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c1061 
,08-25 17:21:28.048  6943  7424 E bt-btif : Calling BTA_HhEnable
08-25 17:21:28.048  6943  7424 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 17:21:28.048  6943  7424 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 17:21:28.048  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 17:21:28.048  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 17:21:28.048  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-25 17:21:28.049  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-25 17:21:28.049  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 17:21:28.053  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-25 17:21:28.053  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 17:21:28.053  6943  7424 D BluetoothAdapterProperties: Name is: G3
08-25 17:21:28.055  6943  7424 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:21:28.055  6943  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:21:28.055  6943  7424 D bt_hci_bdroid: postload
08-25 17:21:28.055  6943  7491 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:28.058  6943  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 17:21:28.058  6943  7491 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:28.058  6943  7491 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:28.058  6943  7424 D bte_conf: Device ID record 1 : primary
08-25 17:21:28.058  6943  7424 D bte_conf:   vendorId            = 00c4
08-25 17:21:28.058  6943  7424 D bte_conf:   vendorIdSource      = 0001
08-25 17:21:28.058  6943  7424 D bte_conf:   product             = 13a1
,08-25 17:21:28.058  6943  7424 D bte_conf:   version             = 1000
08-25 17:21:28.058  6943  7424 D bte_conf:   clientExecutableURL = 
,08-25 17:21:28.058  6943  7424 D bte_conf:   serviceDescription  = 
,08-25 17:21:28.058  6943  7424 D bte_conf:   documentationURL    = 
,08-25 17:21:28.058  6943  7424 D bte_conf: bte_load_did_conf no section named DID2.
08-25 17:21:28.059  6943  7491 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:28.059  6943  7491 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:28.065  6943  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:28.065  6943  7489 W bt-smp  : Plain text(LSB ~ MSB) = 22 f8 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-25 17:21:28.065  6943  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 ac 20 06 48 94 47 07 ed dd af c4 a3 38 4c b9 
08-25 17:21:28.065  6943  7489 W bt-btm  : Stopping oneshot timer
08-25 17:21:28.065  6943  7424 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 17:21:28.057  7522  7522 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:28.057  7522  7522 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:28.067  6943  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 17:21:28.067  6943  7420 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:21:28.067  6943  7420 D BluetoothAdapterProperties: State =  11
08-25 17:21:28.068  6943  7420 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 17:21:28.068  6943  7420 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 17:21:28.068  6943  7420 D BluetoothAdapterProperties: Setting state to 12
08-25 17:21:28.068  6943  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 17:21:28.071  6943  7424 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 17:21:28.074  6943  7491 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:28.074  6943  7491 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 17:21:28.081  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:28.081  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 17:21:28.081  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 17:21:28.081  6943  7518 E bt_mct  : hci lib postload completed
08-25 17:21:28.084  6943  7420 I BluetoothAdapterState: Entering On State
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:28.087  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:28.088  6943  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:21:28.089  6943  7424 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 17:21:28.090  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:28.097  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:28.101  6943  7420 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 17:21:28.101  6943  7420 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 17:21:28.101  6943  7420 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 17:21:28.104  6943  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:28.104  6943  7489 W bt-smp  : Plain text(LSB ~ MSB) = dc bd 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:28.104  6943  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = 9e d2 bb c6 cb 27 ac d2 8e 05 15 bd 09 8b fe 55 
08-25 17:21:28.104  6943  7489 W bt-btm  : Stopping oneshot timer
,08-25 17:21:28.106  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:28.107  6943  7420 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 17:21:28.108  6797  6935 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:21:28.111  6797  6818 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:21:28.115  1854  2420 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:21:28.116  6797  6797 D BluetoothMap: Proxy object connected
08-25 17:21:28.116  6797  6797 D MapProfile: Bluetooth service connected
08-25 17:21:28.116  6797  6797 D BluetoothMap: getConnectedDevices()
,08-25 17:21:28.122  1854  1854 D BluetoothHeadset: Proxy object connected
08-25 17:21:28.123  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:21:28.125  1854  1854 D BluetoothHeadset: Proxy object connected
08-25 17:21:28.125  1854  3945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:21:28.126  6943  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:28.126  6943  7489 W bt-smp  : Plain text(LSB ~ MSB) = 56 b0 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:28.126  6943  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 a8 69 83 06 e3 53 c3 14 65 a7 68 58 12 dd 9a 
08-25 17:21:28.126  6943  7489 W bt-btm  : Stopping oneshot timer
08-25 17:21:28.128  1854  1854 D BluetoothHeadset: Proxy object connected
08-25 17:21:28.130  6797  6935 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:21:28.130  6797  6935 D BluetoothPan: onBluetoothStateChange call bindService
,08-25 17:21:28.134  6943  7420 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 17:21:28.135  6943  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:28.135  6943  7489 W bt-smp  : Plain text(LSB ~ MSB) = 85 ed 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:28.135  6943  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = ef 05 33 fc 45 e2 67 79 be b3 25 7b 64 82 2b ec 
08-25 17:21:28.135  6943  7489 W bt-btm  : Stopping oneshot timer
08-25 17:21:28.138  6943  6961 V BluetoothMapService: getConnectedDevices()
08-25 17:21:28.138  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:21:28.140  6797  6797 D BluetoothInputDevice: Proxy object connected
08-25 17:21:28.141  6797  6797 D HidProfile: Bluetooth service connected
08-25 17:21:28.143  1034  1034 D BluetoothHeadset: Proxy object connected
,08-25 17:21:28.149  6797  6818 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:21:28.151  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:21:28.152  7527  7527 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 17:21:28.153  1034  1034 D BluetoothA2dp: Proxy object connected
,08-25 17:21:28.155  6943  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:28.155  6943  7489 W bt-smp  : Plain text(LSB ~ MSB) = 42 c2 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:28.155  6943  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = 3f de 78 f8 af b8 f8 99 b1 cd ec 53 5a fb 3f 1b 
08-25 17:21:28.156  6943  7489 W bt-btm  : Stopping oneshot timer
08-25 17:21:28.157  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 17:21:28.157  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 17:21:28.160  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:28.160  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:21:28.160  1942  2125 D LGBluetoothAPIService: Message: 1
08-25 17:21:28.160  1942  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 17:21:28.164  6797  6797 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:21:28.164  6797  6797 D PanProfile: Bluetooth service connected
08-25 17:21:28.165  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 17:21:28.165  1034  1116 D BluetoothManagerService: Message: 40
08-25 17:21:28.165  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 17:21:28.168  6715  6715 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-25 17:21:28.171  1942  2125 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 17:21:28.174  6943  6943 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:28.174  6943  6943 D BluetoothMapService: STATE_ON
08-25 17:21:28.176  6943  6943 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 17:21:28.176  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:28.177  6943  6943 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 17:21:28.178  6943  6943 V BluetoothMapService: Handler(): got msg=1
08-25 17:21:28.178  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 17:21:28.178  1942  2125 D LGBluetoothAPIService: Message: 100
08-25 17:21:28.178  1942  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 17:21:28.178  6943  6943 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 17:21:28.180  6797  6797 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 17:21:28.180  6943  7541 D BluetoothMapMasInstance: MAS initSocket()
08-25 17:21:28.181  6943  7541 D BluetoothMapMasInstance:   masId = 00
08-25 17:21:28.181  6943  7541 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 17:21:28.181  6943  7541 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 17:21:28.181  6943  7541 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-25 17:21:28.183  1034  1116 D BluetoothManagerService: Message: 30
08-25 17:21:28.183  1034  1710 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:28.185  6797  6797 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 17:21:28.189  1034  1116 D BluetoothManagerService: Message: 30
08-25 17:21:28.190  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:28.191  6943  7541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:28.193  6943  7541 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 17:21:28.193  6943  7541 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 17:21:28.194  6943  7541 D BluetoothMapMasInstance: Accepting socket connection...
,08-25 17:21:28.195  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:28.195  6943  6943 V BluetoothPbapService: Pbap Service onCreate
08-25 17:21:28.195  6943  6943 V BluetoothPbapService: Starting PBAP service
08-25 17:21:28.197  6943  7424 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:21:28.197  6943  7424 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 17:21:28.199  6943  6943 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 17:21:28.199  6943  6943 V BluetoothPbapService: Pbap Service onBind
08-25 17:21:28.200  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:28.200  6943  6943 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:28.201  6943  6943 V BluetoothPbapService: state: 12
08-25 17:21:28.201  6943  6943 V BluetoothPbapService: Handler(): got msg=1
08-25 17:21:28.201  6943  6943 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 17:21:28.202  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:28.202  6797  6797 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 17:21:28.203  6943  7542 V BluetoothPbapService: Pbap Service initSocket
08-25 17:21:28.203  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:28.204  6797  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:21:28.205  6943  7542 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:21:28.208  6797  6797 D BluetoothA2dp: Proxy object connected
08-25 17:21:28.209  6797  6797 D A2dpProfile: Bluetooth service connected
08-25 17:21:28.210  6943  7542 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 17:21:28.210  6943  7542 V BluetoothPbapService: Succeed to create listening socket 
08-25 17:21:28.210  6943  7542 V BluetoothPbapService: Accepting socket connection...
08-25 17:21:28.212  6943  6943 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:21:28.212  6943  6943 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:28.212  6943  6943 V BluetoothPbapReceiver: ***********state = 12
08-25 17:21:28.214  6797  6797 D BluetoothHeadset: Proxy object connected
08-25 17:21:28.215  6797  6797 D HeadsetProfile: Bluetooth service connected
08-25 17:21:28.218  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:21:28.218  6797  6797 D BluetoothPbap: Proxy object connected
,08-25 17:21:28.218  2155  2155 D c       : Getting all permits...
08-25 17:21:28.218  2155  2155 D a       : Opening database...
08-25 17:21:28.220  6797  6797 D PbapServerProfile: Bluetooth service connected
08-25 17:21:28.222  2155  2155 D a       : Opening database auth.proximity.permit_store...
08-25 17:21:28.223  6797  6797 D DockEventReceiver: finishStartingService: stopping service
08-25 17:21:28.223  2155  2155 D a       : Closing database...
08-25 17:21:28.235  6797  6797 D BluetoothPermissionRequest: onReceive
,08-25 17:21:28.238  6797  6797 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 17:21:28.239  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:21:28.242  6943  6943 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 17:21:28.243  6943  6943 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 17:21:28.249  6943  6943 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 17:21:28.269  6943  6943 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 17:21:28.269  6943  6943 V BtOppService: onCreate
08-25 17:21:28.274  6943  6943 V BluetoothOppNotification: send message
08-25 17:21:28.278  6943  6943 V BtOppService: Starting RfcommListener
08-25 17:21:28.283  6943  6943 D BluetoothOppPreference: Dumping Names:  
08-25 17:21:28.283  6943  6943 D BluetoothOppPreference: {}
,08-25 17:21:28.283  6943  6943 D BluetoothOppPreference: Dumping Channels:  
08-25 17:21:28.283  6943  6943 D BluetoothOppPreference: {}
08-25 17:21:28.284  6943  6943 V BtOppService: onStartCommand
08-25 17:21:28.285  6943  7549 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 17:21:28.288  6943  7546 V BtOppService: Deleted complete outbound shares, number =  0
08-25 17:21:28.289  6943  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 17:21:28.290  6943  7546 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 17:21:28.290  6943  7546 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 17:21:28.292  6943  6943 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:28.292  6943  7546 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e1393e4 on behalf of 
08-25 17:21:28.292  6943  6943 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:21:28.295  6943  6943 V BluetoothOppNotification: new notify threadi!
08-25 17:21:28.296  6943  6943 V BluetoothOppNotification: send delay message
,08-25 17:21:28.297  6943  6943 V BtOppService: start RfcommListener
08-25 17:21:28.298  6943  7550 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 17:21:28.300  6943  6943 V BtOppService: RfcommListener started
08-25 17:21:28.300  6943  6943 V BtOppService: ContentObserver received notification
08-25 17:21:28.300  6943  6943 V BtOppService: ContentObserver received notification
08-25 17:21:28.301  6943  7551 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 17:21:28.309  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:21:28.310  6943  7551 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:28.312  6943  7551 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-25 17:21:28.312  6943  7551 V BtOppRfcommListener: Started RFCOMM listener....
08-25 17:21:28.313  6943  7551 I BtOppRfcommListener: Accept thread started.
08-25 17:21:28.313  6943  7551 V BtOppRfcommListener: Accepting connection...
08-25 17:21:28.315  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:28.316  6943  6943 V BluetoothFtpService: Ftp Service onCreate
08-25 17:21:28.316  6943  6943 I BluetoothFtpService: Ftp Service onCreate
08-25 17:21:28.316  6943  6943 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:21:28.316  6943  6943 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:28.316  6943  6943 V BluetoothFtpService: Starting Listening on sockets
08-25 17:21:28.316  6943  6943 V BluetoothFtpService: Handler(): got msg=1
08-25 17:21:28.317  6943  6943 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 17:21:28.317  6943  6943 V BluetoothFtpService: Ftp Service initSocket
08-25 17:21:28.319  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:28.320  6943  6943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:28.321  6943  6943 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
,08-25 17:21:28.323  6943  6943 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 17:21:28.325  6943  7552 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 17:21:28.420  1034  2032 I art     : Explicit concurrent mark sweep GC freed 94527(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.318ms total 126.311ms
08-25 17:21:28.420  6943  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f22e702 on behalf of 
,08-25 17:21:28.423  6943  7550 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21cb2813 on behalf of 
08-25 17:21:28.423  6943  7550 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 17:21:28.423  6943  6943 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:21:28.423  6943  6943 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:28.424  6943  6943 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:28.424  6943  6943 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:21:28.424  6943  6943 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 17:21:28.424  6943  6943 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:21:28.425  6943  7549 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 17:21:28.425  6943  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 17:21:28.427  6943  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b680a50 on behalf of 
08-25 17:21:28.429  6943  7549 V BluetoothOppNotification: update too frequent, put in queue
08-25 17:21:28.434  6943  7549 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-25 17:21:28.435  6943  7550 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 17:21:28.438  6943  7550 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2850f449 on behalf of 
08-25 17:21:28.440  6943  7550 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 17:21:28.441  6943  7550 V BluetoothOppNotification: outbound notification was removed.
08-25 17:21:28.442  6943  7550 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 17:21:28.443  6943  7550 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e5c714e on behalf of 
08-25 17:21:28.444  6943  7550 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 17:21:28.444  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:28.444  6943  6943 V BluetoothSapService: Sap Service onCreate
08-25 17:21:28.444  6943  7550 V BluetoothOppNotification: inbound notification was removed.
,08-25 17:21:28.445  6943  7550 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 17:21:28.446  6943  7550 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3836326f on behalf of 
08-25 17:21:28.452  6943  6943 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:28.452  6943  6943 V BluetoothSapService: state: 12
08-25 17:21:28.452  6943  6943 V BluetoothSapService: Starting SAP server process
08-25 17:21:28.454  6943  6943 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 17:21:28.456  6943  7554 V BluetoothSapService: Sap Service initRfcommSocket
08-25 17:21:28.456  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:28.447  7553  7553 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:28.457  6943  7554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:28.447  7553  7553 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:21:28.458  6943  7554 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-25 17:21:28.458  6943  7554 V BluetoothSapService: Succeed to create listening socket 
08-25 17:21:28.458  6943  7554 V BluetoothSapService: Accepting socket connection...
08-25 17:21:28.463  7553  7553 V BT_SAP  : Event pipe created
08-25 17:21:28.463  7553  7553 V BT_SAP  : create_server_socket qcom.sap.server
08-25 17:21:28.463  7553  7553 V BT_SAP  : created socket fd 6
08-25 17:21:28.723  1034  1049 I ActivityManager: Killing 7334:com.lge.bnr/1000 (adj 15): empty #17
,08-25 17:21:28.767  1034  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_7334/cgroup.procs: No such file or directory
,08-25 17:21:29.020  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:21:29.021  1034  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:21:29.052  1034  1439 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 17:21:29.053  1034  1439 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 17:21:29.269  1034  1050 I ActivityManager: Killing 6592:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-25 17:21:29.297  6870  6870 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-25 17:21:29.300  6943  6943 V BluetoothOppNotification: new notify threadi!
08-25 17:21:29.301  6943  6943 V BluetoothOppNotification: send delay message
08-25 17:21:29.297  6870  6870 W System.err: android.os.DeadObjectException
08-25 17:21:29.302  6870  6870 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 17:21:29.302  6870  6870 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 17:21:29.302  6870  6870 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 17:21:29.302  6870  6870 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 17:21:29.302  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 17:21:29.302  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 17:21:29.303  6870  6870 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:21:29.303  6870  6870 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:21:29.303  6870  6870 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:29.303  6870  6870 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:21:29.303  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:29.303  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:21:29.303  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:29.303  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:21:29.303  6870  6870 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 17:21:29.303  6870  6870 W System.err: android.os.DeadObjectException
08-25 17:21:29.304  6870  6870 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 17:21:29.304  6870  6870 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 17:21:29.304  6870  6870 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 17:21:29.304  6870  6870 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 17:21:29.304  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 17:21:29.304  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 17:21:29.304  6870  6870 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:21:29.304  6870  6870 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:21:29.304  6870  6870 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:29.304  6870  6870 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:21:29.304  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:29.304  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:21:29.304  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:29.304  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:21:29.304  6870  6870 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 17:21:29.307  6870  6870 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-25 17:21:29.307  6943  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; ,sort is _id.
08-25 17:21:29.308  6943  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@159d868b on behalf of 
08-25 17:21:29.309  6943  7564 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 17:21:29.310  6943  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-25 17:21:29.319  6943  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d92d368 on behalf of 
08-25 17:21:29.319  6943  7564 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 17:21:29.321  6943  7564 V BluetoothOppNotification: outbound notification was removed.
08-25 17:21:29.321  6943  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 17:21:29.322  6943  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e5de381 on behalf of 
08-25 17:21:29.323  6943  7564 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 17:21:29.326  6943  7564 V BluetoothOppNotification: inbound notification was removed.
08-25 17:21:29.327  6943  7564 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 17:21:29.328  6943  7564 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10115c26 on behalf of 
08-25 17:21:29.337  1034  1960 W libprocessgroup: failed to open /acct/uid_1000/pid_6592/cgroup.procs: No such file or directory
08-25 17:21:29.337  1034  1960 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-25 17:21:29.344  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 17:21:29.344  6870  6870 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 17:21:29.385  1034  1755 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7565 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 17:21:29.444  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 17:21:29.480  7565  7565 D UEI.SmartControl: Quickset Services start...
,08-25 17:21:29.481  7565  7565 I UEI.SmartControl: Manufacture = LGE
08-25 17:21:29.482  7565  7565 D UEI.SmartControl: Id = LGNevo
,08-25 17:21:29.487  7565  7565 D UEI.SmartControl: File observer start...
08-25 17:21:29.488  7565  7565 E UEI.SmartControl: IR Port is disabled: false
08-25 17:21:29.489  7565  7565 D UEI.SmartControl: Starting file observer...
08-25 17:21:29.489  7565  7565 D UEI.SmartControl: Extracting JNI libs...
08-25 17:21:29.490  7565  7565 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-25 17:21:29.600  7565  7565 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-25 17:21:29.600  7565  7565 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 17:21:29.600  7565  7565 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-25 17:21:29.640  7565  7565 I UEI.SmartControl: --- Selecting new region: 6
,08-25 17:21:29.643  7565  7565 I UEI.SmartControl: Model = LG-D855
,08-25 17:21:29.645  7565  7565 D UEI.SmartControl: QS Service created
,08-25 17:21:29.662  7565  7565 I UEI.SmartControl: Service initServices...
,08-25 17:21:29.667  7565  7565 D UEI.SmartControl: QS start get config
,08-25 17:21:29.715  7565  7565 D UEI.SmartControl: Loading JNI Libs...
,08-25 17:21:30.036  1034  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:30.037  1034  1888 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@5f6945c mBinding = false
,08-25 17:21:30.051  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:21:30.052  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:30.052  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 17:21:30.053  1034  1116 D BluetoothManagerService: Message: 2
,08-25 17:21:30.055  1034  1116 D BluetoothManagerService: Sending off request.
08-25 17:21:30.057  6943  7528 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 17:21:30.058  6943  7420 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 17:21:30.058  6943  7420 D BluetoothAdapterProperties: Setting state to 13
08-25 17:21:30.058  6943  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:21:30.059  6943  7420 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:21:30.059  6943  7420 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 17:21:30.060  6943  7424 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:21:30.062  6943  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 17:21:30.063  6943  7420 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 17:21:30.064  6943  7541 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 17:21:30.066  6943  7551 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 17:21:30.068  6943  7552 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:30.069  6943  7554 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:30.070  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 17:21:30.070  6943  7489 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 17:21:30.071  6943  7542 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 17:21:30.077  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 17:21:30.078  6943  7489 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-25 17:21:30.084  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:30.084  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:30.085  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:30.085  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:30.089  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:30.089  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:30.091  6715  6715 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:21:30.093  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:30.094  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:30.094  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 17:21:30.094  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 17:21:30.097  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:21:30.099  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.104  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:30.113  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:30.114  6943  6943 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.114  6943  6943 D BluetoothMapService: STATE_TURNING_OFF
08-25 17:21:30.114  6943  6943 V BluetoothMapService: Handler(): got msg=4
08-25 17:21:30.114  6943  6943 D BluetoothMapService: MAP Service closeService in
08-25 17:21:30.114  6943  6943 D BluetoothMapMasInstance: MAP Service shutdown
08-25 17:21:30.115  6943  6943 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:21:30.115  6943  6943 V BluetoothMapService: MAP Service closeService out
08-25 17:21:30.119  6943  6943 V BtOppService: Receiver DISABLED_ACTION 
08-25 17:21:30.119  6943  6943 I BtOppRfcommListener: stopping Accept Thread
08-25 17:21:30.119  6943  6943 V BtOppRfcommListener: close mBtServerSocket
,08-25 17:21:30.122  6943  7551 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:21:30.122  6943  6943 V BtOppRfcommListener: waiting for thread to terminate
08-25 17:21:30.123  6943  6943 V BtOppRfcommListener: done waiting for thread to terminate
08-25 17:21:30.127  6797  6797 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-25 17:21:30.131  6797  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:21:30.134  6943  6943 V BtOppService: onDestroy
,08-25 17:21:30.138  6943  6943 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 17:21:30.138  6943  6943 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:21:30.139  6943  6943 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.139  6943  6943 V BluetoothPbapReceiver: ***********state = 13
08-25 17:21:30.141  6943  6943 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 17:21:30.144  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:21:30.145  6943  6943 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.145  6943  6943 V BluetoothPbapService: state: 13
08-25 17:21:30.145  6943  6943 V BluetoothPbapService: Pbap Service closeService in
08-25 17:21:30.149  6943  6943 V BluetoothPbapService: successfully stopped pbap service
08-25 17:21:30.149  6943  6943 V BluetoothPbapService: Pbap Service closeService out
,08-25 17:21:30.152  6943  6943 V BluetoothPbapService: Pbap Service onDestroy
08-25 17:21:30.152  6943  6943 V BluetoothPbapService: Pbap Service closeService in
,08-25 17:21:30.152  6943  6943 V BluetoothPbapService: Pbap Service closeService out
08-25 17:21:30.152  6943  6943 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 17:21:30.161  6797  6797 D DockEventReceiver: finishStartingService: stopping service
08-25 17:21:30.161  6797  6797 D BluetoothPbap: Proxy object disconnected
08-25 17:21:30.161  6797  6797 D PbapServerProfile: Bluetooth service disconnected
08-25 17:21:30.164  6797  6797 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 17:21:30.167  6797  6797 D BluetoothPermissionRequest: onReceive
,08-25 17:21:30.167  6797  6797 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 17:21:30.172  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:21:30.175  6943  6943 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 17:21:30.176  6943  6943 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 17:21:30.176  6943  6943 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 17:21:30.186  6943  6943 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.187  6943  6943 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:21:30.187  6943  6943 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:21:30.187  6943  6943 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.188  6943  6943 V BluetoothFtpService: Ftp Service closeService
08-25 17:21:30.188  6943  6943 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 17:21:30.188  6943  6943 V BluetoothFtpService: successfully stopped ftp service
08-25 17:21:30.189  6943  6943 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:21:30.189  6943  6943 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:30.189  6943  6943 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:30.189  6943  6943 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.189  6943  6943 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 17:21:30.189  6943  6943 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:21:30.190  6943  6943 V BluetoothFtpService: Ftp Service onDestroy,
08-25 17:21:30.190  6943  6943 V BluetoothFtpService: Ftp Service closeService
,08-25 17:21:30.193  6943  6943 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:30.193  6943  6943 V BluetoothSapService: state: 13
08-25 17:21:30.193  6943  6943 V BluetoothSapService: Stopping SAP server process
08-25 17:21:30.193  6943  6943 V BluetoothSapService: Sap Service closeSapService in
08-25 17:21:30.193  6943  6943 V BluetoothSapService: Close listen Socket : 
08-25 17:21:30.193  6943  6943 V BluetoothSapService: Close rfcomm Socket : 
08-25 17:21:30.193  6943  6943 V BluetoothSapService: Close sapd  Socket : 
08-25 17:21:30.196  6943  6943 V BluetoothSapService: Sap Service closeSapService out
08-25 17:21:30.196  6943  6943 V BluetoothSapService: Sap Service onDestroy
08-25 17:21:30.196  6943  6943 V BluetoothSapService: Sap Service closeSapService in
,08-25 17:21:30.196  6943  6943 V BluetoothSapService: Close listen Socket : 
08-25 17:21:30.196  6943  6943 V BluetoothSapService: Close rfcomm Socket : 
08-25 17:21:30.196  6943  6943 V BluetoothSapService: Close sapd  Socket : 
08-25 17:21:30.197  6943  6943 V BluetoothSapService: Sap Service closeSapService out
08-25 17:21:30.252  7565  7565 I UEI.SmartControl: Supports setup maps: true
08-25 17:21:30.255  7565  7565 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 17:21:30.255  7565  7565 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 17:21:30.255  7565  7565 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 17:21:30.255  7565  7565 I UEI.SmartControl: ### init IR Blaster...
,08-25 17:21:30.260  7565  7565 D serial_port: Configuring serial port
08-25 17:21:30.263  7565  7565 E UEI.SmartControl: UEIBLaster setting for 616
,08-25 17:21:30.263  7565  7565 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 17:21:30.263  7565  7565 I UEI.SmartControl: configuring settings for MAXQ616
08-25 17:21:30.263  7565  7565 I UEI.SmartControl: Get version...
08-25 17:21:30.279  7565  7619 D UEI.SmartControl: serial port data available: 21
,08-25 17:21:30.309  7565  7565 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 17:21:30.309  7565  7565 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-25 17:21:30.310  7565  7565 I UEI.SmartControl: QS saving settings...
08-25 17:21:30.313  7565  7565 D UEI.SmartControl: IR Blaster version: 25672567
08-25 17:21:30.330  7565  7619 D UEI.SmartControl: serial port data available: 4
,08-25 17:21:30.372  7565  7622 I UEI.SmartControl: Device manager: loading config....
08-25 17:21:30.373  7565  7622 D UEI.SmartControl: ----------- loading internal config...
,08-25 17:21:30.376  7565  7565 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 17:21:30.383  7565  7565 E UEI.SmartControl: Services init done
08-25 17:21:30.383  7565  7565 D UEI.SmartControl: QS Service init finished
08-25 17:21:30.385  7565  7565 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 17:21:30.385  7565  7565 D UEI.SmartControl: QS Service version code: 201091
08-25 17:21:30.386  7565  7565 D UEI.SmartControl: Service requested: Control
08-25 17:21:30.389  7565  7622 E UEI.SmartControl: Loading SETTINGS...
,08-25 17:21:30.392  7565  7565 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 17:21:30.394  1034  1959 I ActivityManager: Killing 6870:com.lge.qremote/u0a112 (adj 15): empty #17
08-25 17:21:30.398  7565  7622 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 17:21:30.408  7565  7621 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 17:21:30.408  7565  7621 D UEI.SmartControl: -----service ready thread exits
,08-25 17:21:30.465  1034  1960 W libprocessgroup: failed to open /acct/uid_10112/pid_6870/cgroup.procs: No such file or directory
08-25 17:21:30.469  7565  7565 D UEI.SmartControl: Internal service binding...
,08-25 17:21:30.975  6943  7424 D bt_hci_bdroid: cleanup
,08-25 17:21:30.982  6943  7491 I bt_lpm  : LPM is already off!!!
08-25 17:21:30.983  6943  7489 W bt-btif : ag scb idx 1 not allocated
08-25 17:21:30.983  6943  7489 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 17:21:30.983  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:30.983  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:30.983  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:30.983  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 17:21:30.984  6943  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 17:21:30.984  6943  7489 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 17:21:30.988  6943  7518 I bt_userial_mct: exiting userial_read_thread
08-25 17:21:30.988  6943  7518 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 17:21:30.989  6943  7424 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 17:21:30.989  6943  7491 I bt_vendor: hw_epilog_process
08-25 17:21:30.995  6943  7424 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 17:21:30.995  6943  7424 D bt_userial_mct: userial_close
08-25 17:21:30.995  6943  7424 E bt_userial_mct: pthread_join() FAILED result:3
08-25 17:21:30.995  6943  7424 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 17:21:31.007  6943  7424 D bt_hci_bdroid: set_power 0
08-25 17:21:31.007  6943  7424 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 17:21:31.009  6943  7424 I bt_vendor: bluetooth satus is on
,08-25 17:21:31.010  6943  7424 I bt_vendor: bt-vendor : resetting BT status
08-25 17:21:31.010  6943  7424 I bt_vendor: Starting hciattach daemon
08-25 17:21:31.010  6943  7424 I bt_vendor: try to set false
08-25 17:21:31.012  6943  7424 I bt_vendor: Starting hciattach daemon
08-25 17:21:31.012  6943  7424 I bt_vendor: try to set false
08-25 17:21:31.012  6943  7424 I bt_vendor: cleanup
08-25 17:21:31.013  6943  7489 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 17:21:31.013  6943  7424 I GKI_LINUX: GKI_exit_task 0 done
08-25 17:21:31.014  6943  7424 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 17:21:31.015  6943  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 17:21:31.022  6943  7420 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-25 17:21:31.028  6943  6943 D HeadsetService: Received stop request...Stopping profile...
08-25 17:21:31.029  6943  6943 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:21:31.029  6943  6943 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:21:31.029  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:31.029  6943  7458 D HeadsetStateMachine: Exit Disconnected: -1
08-25 17:21:31.032  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:31.032  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:31.032  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:31.033  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-25 17:21:31.033  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 17:21:31.034  6943  6943 D A2dpService: Received stop request...Stopping profile...
08-25 17:21:31.036  6943  7481 D A2dpStateMachine: Exit Disconnected: -1
,08-25 17:21:31.040  6943  6943 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 17:21:31.041  6943  6943 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 17:21:31.042  6943  6943 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:21:31.042  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:31.044  6943  6943 D HidService: Received stop request...Stopping profile...
08-25 17:21:31.044  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:31.044  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-25 17:21:31.044  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 17:21:31.047  6943  6943 D HealthService: Received stop request...Stopping profile...
08-25 17:21:31.047  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:31.050  6943  6943 D PanService: Received stop request...Stopping profile...
,08-25 17:21:31.053  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:31.054  6943  6943 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:21:31.055  6943  6943 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:21:31.055  6943  6943 D BtGatt.GattService: stop()
08-25 17:21:31.055  6943  6943 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 17:21:31.057  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:31.059  6943  6943 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:21:31.059  6943  6943 D BluetoothMapService: stop()
08-25 17:21:31.059  6943  6943 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 17:21:31.060  6943  6943 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 17:21:31.061  6943  6943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e8e96cb
08-25 17:21:31.063  6943  6943 D HeadsetStateMachine: Unbinding service...
,08-25 17:21:31.066  6943  6943 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:21:31.067  6943  6943 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:21:31.067  6943  6943 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:21:31.067  6943  6943 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:21:31.067  6943  6943 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:21:31.067  6943  6943 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:21:31.067  6943  6943 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 17:21:31.067  6943  6943 I BluetoothA2dpServiceJni: cleanupNative
08-25 17:21:31.068  6943  7482 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 17:21:31.068  6943  6943 I GKI_LINUX: GKI_exit_task 2 done
08-25 17:21:31.068  6943  6943 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 17:21:31.068  6943  6943 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:21:31.069  6943  6943 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:21:31.069  6943  6943 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 17:21:31.069  6943  6943 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:21:31.069  6943  6943 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:21:31.070  6943  6943 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:21:31.070  6943  6943 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:21:31.071  6943  6943 V BluetoothMapService: Handler(): got msg=4
08-25 17:21:31.071  6943  6943 D BluetoothMapService: MAP Service closeService in
08-25 17:21:31.071  6943  6943 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:21:31.071  6943  6943 V BluetoothMapService: MAP Service closeService out
08-25 17:21:31.072  6943  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 17:21:31.072  6943  7420 D BluetoothAdapterProperties: Setting state to 10
08-25 17:21:31.072  6943  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 17:21:31.075  6943  6943 D BluetoothMapService: cleanup()
08-25 17:21:31.075  6943  6943 D BluetoothMapService: MAP Service closeService in
08-25 17:21:31.075  6943  6943 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 17:21:31.075  6943  6943 V BluetoothMapService: MAP Service closeService out
,08-25 17:21:31.080  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:31.080  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 17:21:31.080  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 17:21:31.081  6943  7420 I BluetoothAdapterState: Entering OffState
08-25 17:21:31.083  6797  6818 D BluetoothMap: onBluetoothStateChange: up=false
08-25 17:21:31.084  6797  6818 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:21:31.085  6797  6818 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:31.086  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:31.087  1854  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:31.087  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:31.088  6797  6818 D BluetoothPan: onBluetoothStateChange on: false
,08-25 17:21:31.090  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:21:31.090  6797  6818 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:21:31.091  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:21:31.091  6797  6818 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:21:31.092  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 17:21:31.092  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 17:21:31.094  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 17:21:31.094  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 17:21:31.094  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@5f6945c mBinding = false
08-25 17:21:31.095  1034  1116 D BluetoothManagerService: Sending unbind request.
08-25 17:21:31.099  6943  7424 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 17:21:31.102  6943  6943 I GKI_LINUX: GKI_exit_task 1 done
08-25 17:21:31.102  6943  6943 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 17:21:31.103  6943  6943 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 17:21:31.103  6943  6943 I art     : --- WEIRD: removing null entry 248
08-25 17:21:31.103  6943  6943 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 17:21:31.103  6943  6943 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 17:21:31.104  6943  6943 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 17:21:31.105  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 17:21:31.107  6943  6943 I art     : System.exit called, status: 0
08-25 17:21:31.107  6943  6943 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 17:21:31.133   318  1397 V AudioFlinger: 6943 died, releasing its sessions
08-25 17:21:31.133   318  1397 V AudioFlinger:  pid 1854 @ 0
08-25 17:21:31.133   318  1397 V AudioFlinger:  pid 3421 @ 1
08-25 17:21:31.133   318  1397 V AudioFlinger:  pid 3421 @ 2
08-25 17:21:31.134  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 17:21:31.135  1942  2125 D LGBluetoothAPIService: Message: 101
08-25 17:21:31.135  1942  2125 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
,08-25 17:21:31.135  1942  2125 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 17:21:31.136  1942  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,08-25 17:21:31.136  6797  6797 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 17:21:31.187  1034  1755 I ActivityManager: Process com.android.bluetooth (pid 6943) has died
08-25 17:21:31.187  1034  1755 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
,08-25 17:21:31.188  1034  1755 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-25 17:21:31.204  6797  6797 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 17:21:31.204  6797  6797 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 17:21:31.206  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:21:31.209  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:31.210  1942  2125 D LGBluetoothAPIService: Message: 2
08-25 17:21:31.210  1942  2125 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-25 17:21:31.211  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:31.213  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:31.220  6797  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 17:21:31.225  1603  1603 D BluetoothAdapter: 962572157: getState() :  mService = null. Returning STATE_OFF
08-25 17:21:31.225  1603  1603 D BluetoothAdapter: 962572157: getState() :  mService = null. Returning STATE_OFF
08-25 17:21:31.269  1034  1049 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7655 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 17:21:31.269  6797  6797 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:21:31.326  7655  7655 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 17:21:31.326  7655  7655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:31.327  7655  7655 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 17:21:31.327  7655  7655 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 17:21:31.347  7655  7655 D BluetoothAdapterApp: Loading JNI Library
,08-25 17:21:31.384  7655  7655 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d837053 Instance Count = 1
,08-25 17:21:31.390  7655  7655 D BluetoothAdapterApp: onCreate
08-25 17:21:31.415  7655  7655 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 17:21:31.415  7655  7655 D ProfileConfigQcom: Adding HeadsetService
,08-25 17:21:31.416  7655  7655 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-25 17:21:31.416  7655  7655 D ProfileConfigQcom: Adding A2dpService
08-25 17:21:31.416  7655  7655 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 17:21:31.416  7655  7655 D ProfileConfigQcom: Adding HidService
08-25 17:21:31.417  7655  7655 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 17:21:31.417  7655  7655 D ProfileConfigQcom: Adding HealthService
08-25 17:21:31.417  7655  7655 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 17:21:31.418  7655  7655 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 17:21:31.418  7655  7655 D ProfileConfigQcom: Adding PanService
08-25 17:21:31.418  7655  7655 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 17:21:31.419  7655  7655 D ProfileConfigQcom: Adding GattService
08-25 17:21:31.419  7655  7655 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 17:21:31.419  7655  7655 D ProfileConfigQcom: Adding BluetoothMapService
08-25 17:21:31.419  7655  7655 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 17:21:31.420  7655  7655 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:21:31.421  7655  7655 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:31.422  7655  7655 V BluetoothPbapReceiver: ***********state = 10
08-25 17:21:31.424  7655  7655 V LGMDMManagerInternal: Create singleton instance
08-25 17:21:31.515  7655  7655 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 17:21:31.515  7655  7655 D LGBluetoothAPIServer: [BTUI] onBind()
,08-25 17:21:31.535  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:21:31.538  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 17:21:31.539  1942  2125 D LGBluetoothAPIService: Message: 100
08-25 17:21:31.539  1942  2125 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 17:21:31.544  6797  6797 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 17:21:31.555  6797  6797 D BluetoothPermissionRequest: onReceive
,08-25 17:21:31.558  6797  6797 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 17:21:31.558  6797  6797 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 17:21:31.561  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:21:31.569  7655  7655 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-25 17:21:31.574  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:31.579  7655  7655 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-25 17:21:31.580  7655  7655 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:31.581  7655  7655 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:31.584  7655  7655 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:31.584  7655  7655 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 17:21:31.588  6887  6887 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 17:21:33.076  1034  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 17:21:33.087  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 17:21:33.096  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:33.096  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:21:33.175  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 17:21:33.192  1034  1105 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7684 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 17:21:33.203  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 17:21:33.204  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-25 17:21:33.246  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 17:21:33.258  1034  1034 D administrator: Handling package changes for user 0
08-25 17:21:33.281  7684  7684 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 17:21:33.351  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 17:21:33.351  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 17:21:33.363  7684  7684 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:33.363  7684  7684 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:33.380  1034  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 17:21:33.386  1034  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 17:21:33.395  2447  2447 V GmsNetworkLocationProvi: DISABLE
08-25 17:21:33.396  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-25 17:21:33.419  1034  1104 D LocationProviderProxy: applying state to connected service
,08-25 17:21:33.422  2447  2447 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-25 17:21:33.457  7684  7730 I Babel   : MmsConfig: mnc/mcc: 0/0
08-25 17:21:33.457  7684  7730 I Babel   : MmsConfig.loadMmsSettings
,08-25 17:21:33.459  7684  7730 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 17:21:33.459  7684  7730 I Babel   : MmsConfig.loadFromDatabase
08-25 17:21:33.471  7684  7730 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-25 17:21:33.471  7684  7730 I Babel   : MmsConfig.loadFromResources
,08-25 17:21:33.472  7684  7730 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 17:21:33.473  7684  7730 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-25 17:21:33.500  7684  7684 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:33.508  7684  7728 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 17:21:33.510  7684  7728 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 17:21:33.512  7684  7728 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 17:21:33.522  7684  7728 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-25 17:21:33.524  7684  7728 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 17:21:33.525  7684  7728 W AudioCapabilities: Unsupported mime audio/evrc
08-25 17:21:33.537  1818  7731 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-25 17:21:33.537  1818  7731 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-25 17:21:33.543  7001  7001 I AppUp4:CustModeStarterReceiver: onReceive
08-25 17:21:33.545  7684  7728 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-25 17:21:33.547  7001  7001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12779245
08-25 17:21:33.547  7001  7001 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 17:21:33.547  7001  7001 D AppUp4:CustFacade: isPhone : true
08-25 17:21:33.547  7001  7001 D AppUp4:CustModeStarterReceiver: begin check event
08-25 17:21:33.547  7001  7001 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-25 17:21:33.548  1818  4739 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-25 17:21:33.548  7684  7728 W VideoCapabilities: Unsupported mime video/divx
08-25 17:21:33.551  7684  7728 W VideoCapabilities: Unsupported mime video/divx311
08-25 17:21:33.553  7684  7728 W VideoCapabilities: Unsupported mime video/divx4
,08-25 17:21:33.559  7684  7728 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 17:21:33.573  7684  7728 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-25 17:21:33.576  7684  7728 W AudioCapabilities: Unsupported mime audio/eac3
08-25 17:21:33.576  7684  7728 W AudioCapabilities: Unsupported mime audio/ac3
08-25 17:21:33.577  7684  7728 W AudioCapabilities: Unsupported mime audio/g726
08-25 17:21:33.578  7684  7728 W AudioCapabilities: Unsupported mime audio/wma-voice
08-25 17:21:33.578  7684  7728 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 17:21:33.579  7684  7728 W AudioCapabilities: Unsupported mime audio/adpcm
08-25 17:21:33.580  7684  7728 W VideoCapabilities: Unsupported mime video/theora
,08-25 17:21:33.581  7684  7728 W VideoCapabilities: Unsupported mime video/mjpg
08-25 17:21:33.588  1034  1710 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7735 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-25 17:21:33.619  1034  1959 I ActivityManager: Killing 6841:com.lge.sync/1000 (adj 15): empty #17
08-25 17:21:33.625  7735  7735 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:21:33.625  7735  7735 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:33.625  7735  7735 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 17:21:33.626  7735  7735 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 17:21:33.626  7735  7735 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-25 17:21:33.631  1034  1525 D WifiService: Client connection lost with reason: 4
,08-25 17:21:33.759  1034  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_6841/cgroup.procs: No such file or directory
,08-25 17:21:33.816  7735  7735 I SystemConfig: BUILD Country: EU
08-25 17:21:33.817  7735  7735 I SystemConfig: BUILD Operator: OPEN
,08-25 17:21:33.875  1034  1575 I ActivityManager: Killing 7022:com.lge.email/u0a23 (adj 15): empty #17
,08-25 17:21:33.933  1034  1049 W libprocessgroup: failed to open /acct/uid_10023/pid_7022/cgroup.procs: No such file or directory
,08-25 17:21:33.940  7735  7756 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 17:21:33.941  7735  7756 I SystemConfig: existFile = false
08-25 17:21:33.941  7735  7756 I SystemConfig: canReadFile = false
08-25 17:21:33.941  7735  7756 I SystemConfig: systemFeature RCS result false
08-25 17:21:33.941  7735  7756 D SystemConfig: refreshRcsSupport() :false
,08-25 17:21:33.980  1034  1575 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7758 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-25 17:21:34.048  7758  7758 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 17:21:34.049  7758  7758 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 17:21:34.050  7758  7758 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 17:21:34.051  7758  7758 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 17:21:34.064  1034  1540 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-25 17:21:34.114  7758  7758 I AppConfig: Total System Memory = 2995761152
,08-25 17:21:34.121  7758  7758 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-25 17:21:34.183  1034  2036 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7780 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 17:21:34.186  1034  2036 I ActivityManager: Killing 6911:com.lge.formmanager/u0a26 (adj 15): empty #17
08-25 17:21:34.237  1034  1959 W libprocessgroup: failed to open /acct/uid_10026/pid_6911/cgroup.procs: No such file or directory
,08-25 17:21:34.398  7780  7780 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 17:21:34.503  7780  7780 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 17:21:34.503  7780  7780 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:34.553  7780  7780 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 17:21:34.574  7780  7780 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 17:21:34.576  7780  7780 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 17:21:34.592  7780  7780 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-25 17:21:34.593  7780  7780 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-25 17:21:34.617  1034  1710 I ActivityManager: Killing 6385:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-25 17:21:34.659  1034  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6385/cgroup.procs: No such file or directory
,08-25 17:21:34.662  2842  4486 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-25 17:21:34.663  2842  4486 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3aaf409b on behalf of 7780
08-25 17:21:34.672  4566  7817 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-25 17:21:34.715  1034  1961 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7818 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 17:21:34.739  7780  7780 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-25 17:21:34.761  7780  7780 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-25 17:21:34.812  7818  7818 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 17:21:34.843  7818  7818 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-25 17:21:34.843  7818  7818 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 17:21:34.843  7818  7818 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-25 17:21:34.843  7818  7818 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 17:21:34.843  7818  7818 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-25 17:21:34.843  7818  7818 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-25 17:21:34.859  1034  1959 I ActivityManager: Killing 7071:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-25 17:21:34.941  1034  1960 W libprocessgroup: failed to open /acct/uid_10046/pid_7071/cgroup.procs: No such file or directory
,08-25 17:21:35.180  1034  1960 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:21:35.201  4566  7817 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 528 ms] updated apps [took 528 ms] 
,08-25 17:21:35.373  7565  7623 D UEI.SmartControl: Internal timer expired: 1
08-25 17:21:35.374  7565  7623 D UEI.SmartControl: unbind internal service
,08-25 17:21:35.384  7565  7565 D UEI.SmartControl: Service.onUnbind: IControl
,08-25 17:21:35.385  7565  7565 D UEI.SmartControl: Service.onDestroy
08-25 17:21:35.385  7565  7565 D UEI.SmartControl: Lock is in USE false
08-25 17:21:35.386  7565  7565 D UEI.SmartControl: unbind internal service
08-25 17:21:35.387  7565  7565 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35840dc1
08-25 17:21:35.387  7565  7565 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-25 17:21:35.387  7565  7565 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-25 17:21:35.388  7565  7565 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-25 17:21:35.388  7565  7565 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-25 17:21:35.388  7565  7565 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-25 17:21:35.388  7565  7565 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-25 17:21:35.388  7565  7565 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-25 17:21:35.388  7565  7565 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-25 17:21:35.388  7565  7565 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:35.388  7565  7565 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-25 17:21:35.388  7565  7565 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-25 17:21:35.389  7565  7565 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:35.389  7565  7565 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:21:35.389  7565  7565 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:35.389  7565  7565 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:21:35.389  7565  7565 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35840dc1
08-25 17:21:35.393  7565  7565 D serial_port: close(fd = 25)
08-25 17:21:35.397  7565  7565 I UEI.SmartControl: Serial port is closed.
08-25 17:21:35.397  7565  7565 I UEI.SmartControl: Serial port is closed.
08-25 17:21:35.397  7565  7565 D UEI.SmartControl: Blaster closed
08-25 17:21:35.397  7565  7565 D UEI.SmartControl: Shut down QS...
08-25 17:21:35.398  7565  7565 D UEI.SmartControl: Stopping QS lib
08-25 17:21:35.398  7565  7565 D UEI.SmartControl: QS lib stop result = true
,08-25 17:21:35.398  7565  7565 D UEI.SmartControl: Stopped QS lib,
08-25 17:21:35.399  7565  7565 D UEI.SmartControl: Stopped file observer...
08-25 17:21:35.399  7565  7565 D UEI.SmartControl: QS shutdown complete
08-25 17:21:36.206  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:21:36.219  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@220fe48f added. We now have 6 listener(s)
08-25 17:21:36.219  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:36.221  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:36.221  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e02131c added. We now have 7 listener(s)
08-25 17:21:36.221  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:36.223  6715  6776 I System.out: IsBluetoothEnabled
08-25 17:21:36.224  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:36.224  1034  1959 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 17:21:36.225  1034  1116 D BluetoothManagerService: Message: 2
08-25 17:21:36.228  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:36.230  1034  1710 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:36.230  1034  1710 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 17:21:36.260  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 17:21:36.260  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:36.260  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 17:21:36.261  1034  1116 D BluetoothManagerService: Message: 1
08-25 17:21:36.261  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 17:21:36.287  1034  1116 D BluetoothManagerService: Message: 20
08-25 17:21:36.287  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34d5f5ba:true
,08-25 17:21:36.291  7655  7655 D BluetoothAdapterState: make
08-25 17:21:36.297  7655  7655 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 17:21:36.297  7655  7655 I bluedroid-qcom: init
08-25 17:21:36.298  7655  7864 I BluetoothAdapterState: Entering OffState
08-25 17:21:36.298  7655  7655 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 17:21:36.299  7655  7655 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 17:21:36.299  7655  7655 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 17:21:36.299  7655  7655 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 17:21:36.299  7655  7655 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 17:21:36.301  7655  7655 I bluedroid-qcom: get_profile_interface socket
08-25 17:21:36.301  7655  7655 I bluedroid-qcom: get_profile_interface map_client
,08-25 17:21:36.305  7655  7868 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 17:21:36.297  7867  7867 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:36.297  7867  7867 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:36.317  7655  7868 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 17:21:36.322  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 17:21:36.323  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 17:21:36.324  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 17:21:36.325  1034  1116 D BluetoothManagerService: Message: 40
08-25 17:21:36.325  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 17:21:36.325  7655  7672 I bluedroid-qcom: config_hci_snoop_log
08-25 17:21:36.327  7867  7867 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 17:21:36.327  7867  7867 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 17:21:36.327  7867  7867 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 17:21:36.328  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 17:21:36.328  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 17:21:36.330  7655  7868 D BluetoothAdapterProperties: Name is: G3
,08-25 17:21:36.334  7867  7867 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 17:21:36.340  7655  7864 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 17:21:36.340  7655  7864 D BluetoothAdapterProperties: Setting state to 11
08-25 17:21:36.340  7655  7864 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 17:21:36.342  7655  7864 I LGBluetoothServiceJni: classInitNative: succeeds
,08-25 17:21:36.345  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:36.345  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 17:21:36.345  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 17:21:36.346  7867  7867 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 17:21:36.346  7867  7867 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 17:21:36.355  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:21:36.364  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 17:21:36.366  6797  6797 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 17:21:36.367  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:36.373  7655  7864 D BluetoothBondStateMachine: make
,08-25 17:21:36.376  7655  7655 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:21:36.377  7655  7655 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:36.377  7655  7655 V BluetoothPbapReceiver: ***********state = 11
08-25 17:21:36.377  7655  7882 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 17:21:36.377  7655  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.377  7655  7864 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 17:21:36.377  7655  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.377  7655  7864 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 17:21:36.380  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:21:36.381  7655  7864 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 17:21:36.388  7655  7864 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:21:36.395  7655  7864 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:36.397  7655  7655 D HeadsetService: Received start request. Starting profile...
08-25 17:21:36.398  7655  7655 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:21:36.398  7655  7655 D LGBluetoothHfpAdapter: Version 1.6
08-25 17:21:36.401  7655  7655 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:21:36.402  6797  6797 D BluetoothPermissionRequest: onReceive
,08-25 17:21:36.402  7655  7864 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:36.402  7655  7655 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:21:36.402  7655  7655 D HeadsetStateMachine: make
08-25 17:21:36.405  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:21:36.412  7655  7864 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:36.418  7655  7864 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 17:21:36.424  7655  7864 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:36.428  7655  7864 E BluetoothAdapterService: File transfer profiles supported!!
08-25 17:21:36.439  7655  7655 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 17:21:36.439  7655  7655 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 17:21:36.443  7655  7655 D HeadsetStateMachine: max_hf_connections = 1
08-25 17:21:36.443  7655  7655 I bluedroid-qcom: get_profile_interface handsfree
08-25 17:21:36.444  7655  7864 V LGMDMManager: Create singleton instance
08-25 17:21:36.444  7655  7655 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 17:21:36.445   318  1396 V AudioPolicyService: registerClient() client 0xb558a600, uid 1002
08-25 17:21:36.445   318  2206 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 17:21:36.445   318  2206 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:21:36.445   318  2206 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:21:36.445  7655  7655 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 17:21:36.445   318  1397 V AudioFlinger: registerClient() client 0xb55819a0, pid 7655
08-25 17:21:36.446   318  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:36.446   318  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:36.446  1034  1888 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:36.446  1034  1888 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:36.446  7655  7671 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:36.446  1854  3945 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:36.446  7655  7671 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 17:21:36.446  1854  3945 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:36.446  3421  3436 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:36.446  3421  3436 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:36.446   318  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:36.446   318  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:36.446  1034  1710 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:36.446  1034  1710 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:36.446  1854  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:36.446  1854  1869 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:36.447  3421  3437 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:36.447  3421  3437 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:36.447  7655  7672 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:36.447  7655  7672 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 17:21:36.447  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 17:21:36.447  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 17:21:36.447  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 17:21:36.447  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 17:21:36.447  7655  7655 V ToneGenerator: Create Track: 0xb4928a80
08-25 17:21:36.447  7655  7655 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 17:21:36.447  7655  7655 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 17:21:36.447  7655  7864 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 17:21:36.447   318  1396 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:21:36.447   318  1396 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, form,at 0, channelMask 3, flags 0
08-25 17:21:36.447   318  1396 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:21:36.447   318  1396 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:21:36.447   318  2206 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 17:21:36.447   318  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 17:21:36.447   318  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 17:21:36.447   318  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 17:21:36.447   318  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 17:21:36.448  7655  7655 V AudioSystem: getLatency() output 2, latency 50
08-25 17:21:36.448  7655  7655 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 17:21:36.448  7655  7655 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 17:21:36.448   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 17:21:36.448   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:21:36.448   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 17:21:36.448   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 17:21:36.448   318  2208 V AudioFlinger: createTrack() lSessionId: 23
08-25 17:21:36.449  7655  7655 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 17:21:36.449   318  2208 V AudioFlinger: acquiring 23 from 7655, for 7655
08-25 17:21:36.449   318  2208 V AudioFlinger:  added new entry for 23
08-25 17:21:36.449  7655  7655 V ToneGenerator: ToneGenerator INIT OK, time: 206862
08-25 17:21:36.449  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.450  7655  7886 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 17:21:36.450  7655  7886 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 17:21:36.450  7655  7886 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 17:21:36.451  7655  7886 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 17:21:36.451  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.453  7655  7655 D A2dpService: Received start request. Starting profile...
08-25 17:21:36.453  7655  7655 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:21:36.454  7655  7655 V Avrcp   : make
08-25 17:21:36.454  7655  7655 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 17:21:36.454  7655  7655 I bluedroid-qcom: get_profile_interface avrcp
08-25 17:21:36.455   318   318 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7655
08-25 17:21:36.456   318   318 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 17:21:36.456   318   318 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 17:21:36.456   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 17:21:36.456   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 17:21:36.456   318   318 V voice   : voice_set_parameters: exit with code(0)
08-25 17:21:36.456   318   318 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 17:21:36.456   318   318 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 17:21:36.456   318   318 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 17:21:36.456   318   318 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 17:21:36.456   318   318 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 17:21:36.456   318   318 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 17:21:36.456  7655  7886 V ToneGenerator: ToneGenerator destructor
08-25 17:21:36.456  7655  7886 V ToneGenerator: stopTone
08-25 17:21:36.456  7655  7886 V ToneGenerator: Delete Track: 0xb4928a80
08-25 17:21:36.457  7655  7886 V AudioTrack: ~AudioTrack, releasing session id from 7655 on behalf of 7655
08-25 17:21:36.457   318  2206 V AudioFlinger: releasing 23 from 7655 for 7655
08-25 17:21:36.457   318  2206 V AudioFlinger:  decremented refcount to 0
08-25 17:21:36.457   318  2206 V AudioFlinger: purging stale effects
08-25 17:21:36.457   318  2206 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 17:21:36.457   318  2206 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 17:21:36.457   318  2206 V AudioFlinger: PlaybackThread::Track destructor
08-25 17:21:36.457   318  1272 V AudioPolicyService: AudioCommandThread() waking up
08-25 17:21:36.457   318  2206 V AudioFlinger: removeClient_l() pid 7655, calling pid 318
08-25 17:21:36.457   318  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 17:21:36.457   318  1272 V AudioPolicyManager: releaseOutput() 2
08-25 17:21:36.457   318  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 17:21:36.464  7655  7655 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 17:21:36.467  7655  7655 E AudioManager: No RCC entry present to update
,08-25 17:21:36.467  7655  7655 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 17:21:36.470  7655  7655 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 17:21:36.472  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 17:21:36.472  7655  7655 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 17:21:36.475  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 17:21:36.602  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:21:36.603  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:21:36.672  1034  2010 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 17:21:36.678  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 17:21:36.681  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:21:36.682  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 17:21:36.683  7655  7655 I BluetoothA2dpServiceJni: classInitNative
08-25 17:21:36.683  7655  7655 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:21:36.683  7655  7655 D A2dpStateMachine: make
08-25 17:21:36.686  7655  7655 I bluedroid-qcom: get_profile_interface a2dp
08-25 17:21:36.687  7655  7894 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 17:21:36.690  7655  7655 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:21:36.690  7655  7655 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 17:21:36.691  7655  7893 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:21:36.691  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.693  7655  7655 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 17:21:36.694  7655  7655 D HidService: Received start request. Starting profile...
08-25 17:21:36.694  7655  7655 I bluedroid-qcom: get_profile_interface hidhost
08-25 17:21:36.695  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.695  7655  7655 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:21:36.696  7655  7655 D HealthService: Received start request. Starting profile...
08-25 17:21:36.700  7655  7655 I bluedroid-qcom: get_profile_interface health
,08-25 17:21:36.700  7655  7655 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:21:36.700  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.701  7655  7655 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 17:21:36.703  7655  7655 D PanService: Received start request. Starting profile...
08-25 17:21:36.703  7655  7655 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 17:21:36.703  7655  7655 I bluedroid-qcom: get_profile_interface pan
08-25 17:21:36.713  7655  7655 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 17:21:36.713  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.714  7655  7655 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-25 17:21:36.718  7655  7655 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:21:36.718  7655  7655 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:21:36.718  7655  7655 D BtGatt.GattService: start()
08-25 17:21:36.718  7655  7655 I bluedroid-qcom: get_profile_interface gatt
08-25 17:21:36.719  7655  7655 D BtGatt.AdvertiseManager: advertise manager created
08-25 17:21:36.730  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
,08-25 17:21:36.735  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.737  7655  7655 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 17:21:36.738  7655  7655 V BluetoothMapService: BluetoothMapBinder()
08-25 17:21:36.739  7655  7655 D BluetoothMapService: Received start request. Starting profile...
08-25 17:21:36.739  7655  7655 D BluetoothMapService: start()
08-25 17:21:36.743  7655  7655 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 17:21:36.743  7655  7655 D BluetoothMapEmailAppObserver: createReceiver()
08-25 17:21:36.744  7655  7655 D BluetoothMapEmailAppObserver: initObservers()
08-25 17:21:36.744  7655  7655 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-25 17:21:36.749  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:36.750  7655  7655 D HeadsetStateMachine: Proxy object connected
08-25 17:21:36.750  7655  7655 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 17:21:36.750  7655  7655 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 17:21:36.752  7655  7886 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 17:21:36.753  7655  7886 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 17:21:36.754  7655  7886 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 17:21:36.754  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:21:36.757  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 17:21:36.761  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:36.764  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:21:36.768  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 17:21:36.768  7655  7655 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 17:21:36.771  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 17:21:36.774  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 17:21:36.774  7655  7655 V BluetoothMapService: Handler(): got msg=1
08-25 17:21:36.775  7655  7864 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 17:21:36.775  7655  7864 I bluedroid-qcom: enable
08-25 17:21:36.775  7655  7655 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:21:36.775  7655  7864 I bt_hci_bdroid: init
08-25 17:21:36.776  7655  7655 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:36.776  7655  7655 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:36.776  7655  7904 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 17:21:36.776  7655  7655 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:36.776  7655  7655 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 17:21:36.778  7655  7864 I bt_vendor: bt-vendor : init
08-25 17:21:36.778  7655  7864 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 17:21:36.779  7655  7864 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 17:21:36.779  7655  7864 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 17:21:36.779  7655  7864 D bt_userial_mct: userial_init
08-25 17:21:36.779  7655  7904 I bt-btu  : btu_task pending for preload complete event
08-25 17:21:36.779  7655  7864 D bt_hci_bdroid: set_power 1
,08-25 17:21:36.779  7655  7864 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 17:21:36.779  7655  7864 I bt_vendor: Starting hciattach daemon
08-25 17:21:36.779  7655  7864 I bt_vendor: try to set true
08-25 17:21:36.767  7907  7907 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:36.767  7907  7907 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:21:36.835  7908  7908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 17:21:36.917  7914  7914 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 17:21:36.932  7915  7915 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:21:36.971  7917  7917 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:21:36.983  7918  7918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 17:21:36.996  7919  7919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 17:21:37.009  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 17:21:37.033  7922  7922 I libmdmdetect: ESOC framework not supported
08-25 17:21:37.034  7922  7922 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 17:21:37.046  7922  7922 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-25 17:21:37.046  7922  7922 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 17:21:37.046  7922  7922 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 17:21:37.046  7922  7922 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-25 17:21:37.046  7922  7922 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 17:21:37.046  7922  7922 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 17:21:37.046  7922  7922 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-25 17:21:37.086  7922  7923 E QC-QMI  : qmi_client [7922] 15: failed to locate client data
08-25 17:21:37.087   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 17:21:37.087   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-25 17:21:37.125  7927  7927 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 17:21:37.139  7928  7928 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 17:21:37.183  7655  7864 I bt_vendor: bluetooth satus is on
,08-25 17:21:37.183  7655  7864 D bt_hci_bdroid: preload
08-25 17:21:37.184  7655  7906 D bt_userial_mct: userial_open(port:0)
08-25 17:21:37.184  7655  7906 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 17:21:37.188  7655  7906 I bt_vendor: Done intiailizing UART
,08-25 17:21:37.193  7655  7906 I bt_vendor: Done intiailizing UART
08-25 17:21:37.194  7655  7906 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 17:21:37.194  7655  7906 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 17:21:37.194  7655  7904 I bt-btu  : btu_task received preload complete event
08-25 17:21:37.196  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 17:21:37.196  7655  7930 D bt_userial_mct: Entering userial_read_thread()
08-25 17:21:37.196  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 17:21:37.203  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:21:37.215  7655  7904 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 17:21:37.216  7655  7904 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:21:37.216  7655  7904 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:21:37.216  7655  7904 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 17:21:37.320  7655  7904 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 17:21:37.320  7655  7904 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c1061 
08-25 17:21:37.321  7655  7904 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c1061 
,08-25 17:21:37.353  7655  7868 E bt-btif : Calling BTA_HhEnable
08-25 17:21:37.353  7655  7868 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 17:21:37.353  7655  7868 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 17:21:37.357  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 17:21:37.358  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 17:21:37.358  7655  7868 D BluetoothAdapterProperties: Name is: G3
08-25 17:21:37.360  7655  7868 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:21:37.360  7655  7868 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:21:37.360  7655  7868 D bt_hci_bdroid: postload
08-25 17:21:37.361  7655  7868 D bte_conf: Device ID record 1 : primary
08-25 17:21:37.361  7655  7868 D bte_conf:   vendorId            = 00c4
08-25 17:21:37.361  7655  7868 D bte_conf:   vendorIdSource      = 0001
08-25 17:21:37.361  7655  7868 D bte_conf:   product             = 13a1
08-25 17:21:37.361  7655  7868 D bte_conf:   version             = 1000
08-25 17:21:37.361  7655  7868 D bte_conf:   clientExecutableURL = 
08-25 17:21:37.361  7655  7868 D bte_conf:   serviceDescription  = 
08-25 17:21:37.361  7655  7868 D bte_conf:   documentationURL    = 
08-25 17:21:37.362  7655  7906 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:37.362  7655  7868 D bte_conf: bte_load_did_conf no section named DID2.
08-25 17:21:37.365  7655  7906 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 17:21:37.366  7655  7864 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 17:21:37.366  7655  7864 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:21:37.366  7655  7864 D BluetoothAdapterProperties: State =  11
08-25 17:21:37.366  7655  7864 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 17:21:37.366  7655  7864 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 17:21:37.367  7655  7864 D BluetoothAdapterProperties: Setting state to 12
08-25 17:21:37.367  7655  7864 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 17:21:37.372  7655  7868 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 17:21:37.357  7935  7935 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:37.375  1034  1116 D BluetoothManagerService: Message: 60
08-25 17:21:37.375  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 17:21:37.375  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 17:21:37.367  7935  7935 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:37.379  7655  7930 E bt_mct  : hci lib postload completed
08-25 17:21:37.387  7655  7864 I BluetoothAdapterState: Entering On State
,08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:37.416  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:21:37.420  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:37.421  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 17:21:37.421  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 17:21:37.421  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 17:21:37.422  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 17:21:37.422  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 17:21:37.422  7655  7904 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 17:21:37.425  7655  7864 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 17:21:37.425  7655  7864 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 17:21:37.425  7655  7864 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 17:21:37.430  7655  7864 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-25 17:21:37.434  6797  6820 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:21:37.437  7655  7864 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 17:21:37.446  7655  7868 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:21:37.446  7655  7868 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 17:21:37.446  7655  7868 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 17:21:37.450  7655  7904 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:37.450  7655  7904 W bt-smp  : Plain text(LSB ~ MSB) = f6 4b 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:37.450  7655  7904 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 fc 72 04 55 93 e2 38 79 79 e3 d4 6e 06 3d 24 
08-25 17:21:37.450  7655  7904 W bt-btm  : Stopping oneshot timer
08-25 17:21:37.451  6797  6820 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:21:37.458  6797  6818 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 17:21:37.483  1854  2662 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 17:21:37.488  1854  1854 D BluetoothHeadset: Proxy object connected
08-25 17:21:37.489  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:21:37.489  6797  6797 D BluetoothMap: Proxy object connected
08-25 17:21:37.489  6797  6797 D MapProfile: Bluetooth service connected
08-25 17:21:37.489  6797  6797 D BluetoothMap: getConnectedDevices()
08-25 17:21:37.495  1854  1854 D BluetoothHeadset: Proxy object connected
08-25 17:21:37.495  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:21:37.499  7655  7881 V BluetoothMapService: getConnectedDevices()
08-25 17:21:37.499  1854  1854 D BluetoothHeadset: Proxy object connected
08-25 17:21:37.500  6797  6818 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:21:37.500  6797  6818 D BluetoothPan: onBluetoothStateChange call bindService
,08-25 17:21:37.503  7655  7904 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:37.503  7655  7904 W bt-smp  : Plain text(LSB ~ MSB) = e2 27 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:37.503  7655  7904 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 85 f1 82 0a ac 6e 3a e4 ec 55 ec bf 87 3b 00 
08-25 17:21:37.503  7655  7904 W bt-btm  : Stopping oneshot timer
08-25 17:21:37.506  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:21:37.508  6797  6797 D BluetoothInputDevice: Proxy object connected
08-25 17:21:37.508  6797  6797 D HidProfile: Bluetooth service connected
08-25 17:21:37.511  6797  6818 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:21:37.513  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:21:37.515  6797  6820 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:21:37.516  6797  6797 D BluetoothHeadset: Proxy object connected
08-25 17:21:37.516  6797  6797 D HeadsetProfile: Bluetooth service connected
08-25 17:21:37.518  7655  7904 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:37.518  7655  7904 W bt-smp  : Plain text(LSB ~ MSB) = ff 62 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:37.518  7655  7904 W bt-smp  : Encrypted text(LSB ~ MSB) = e1 24 c9 6e 74 d1 25 3f 3e fa c3 0e 64 d7 62 cf 
08-25 17:21:37.518  7655  7904 W bt-btm  : Stopping oneshot timer
08-25 17:21:37.519  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 17:21:37.519  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 17:21:37.522  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.522  1942  2125 D LGBluetoothAPIService: Message: 1
08-25 17:21:37.522  1942  2125 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 17:21:37.523  1942  2125 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-25 17:21:37.523  1942  2125 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 17:21:37.524  7955  7955 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 17:21:37.525  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 17:21:37.527  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:37.531  7655  7904 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:37.531  7655  7904 W bt-smp  : Plain text(LSB ~ MSB) = 6a e3 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:37.531  7655  7904 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 10 3e c2 65 c9 67 ba 73 57 3e d9 7a ac 16 fd 
08-25 17:21:37.531  7655  7904 W bt-btm  : Stopping oneshot timer
08-25 17:21:37.536  7655  7655 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.536  7655  7655 D BluetoothMapService: STATE_ON
08-25 17:21:37.536  6797  6797 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:21:37.536  6797  6797 D PanProfile: Bluetooth service connected
08-25 17:21:37.539  6797  6797 D BluetoothA2dp: Proxy object connected
08-25 17:21:37.539  6797  6797 D A2dpProfile: Bluetooth service connected
,08-25 17:21:37.544  6797  6797 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 17:21:37.544  7655  7904 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 17:21:37.544  7655  7904 W bt-smp  : Plain text(LSB ~ MSB) = 0d 13 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 17:21:37.544  7655  7904 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b d7 66 64 41 40 a7 62 76 b9 7e 3a e6 bd 26 a9 
08-25 17:21:37.545  7655  7904 W bt-btm  : Stopping oneshot timer
08-25 17:21:37.546  6797  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 17:21:37.552  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:37.552  7655  7655 V BluetoothPbapService: Pbap Service onCreate
08-25 17:21:37.552  7655  7655 V BluetoothPbapService: Starting PBAP service
,08-25 17:21:37.554  7655  7655 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 17:21:37.554  7655  7655 V BluetoothMapService: Handler(): got msg=1
08-25 17:21:37.555  7655  7655 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 17:21:37.555  7655  7655 V BluetoothPbapService: Pbap Service onBind
08-25 17:21:37.556  7655  7959 D BluetoothMapMasInstance: MAS initSocket()
08-25 17:21:37.556  7655  7655 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.556  7655  7655 V BluetoothPbapService: state: 12
08-25 17:21:37.557  7655  7655 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 17:21:37.557  7655  7655 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.557  7655  7655 V BluetoothPbapReceiver: ***********state = 12
08-25 17:21:37.557  6797  6797 D DockEventReceiver: finishStartingService: stopping service
08-25 17:21:37.558  7655  7959 D BluetoothMapMasInstance:   masId = 00
08-25 17:21:37.558  7655  7959 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 17:21:37.558  7655  7959 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 17:21:37.558  7655  7959 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 17:21:37.558  7655  7655 V BluetoothPbapService: Handler(): got msg=1
08-25 17:21:37.558  6797  6797 D BluetoothPbap: Proxy object connected
08-25 17:21:37.559  6797  6797 D PbapServerProfile: Bluetooth service connected
08-25 17:21:37.559  1034  1755 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:37.559  7655  7655 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 17:21:37.560  7655  7960 V BluetoothPbapService: Pbap Service initSocket
08-25 17:21:37.561  2155  2155 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:21:37.561  2155  2155 D c       : Getting all permits...
08-25 17:21:37.561  2155  2155 D a       : Opening database...
08-25 17:21:37.562  7655  7959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:37.565  2155  2155 D a       : Opening database auth.proximity.permit_store...
08-25 17:21:37.565  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:21:37.567  7655  7868 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:21:37.567  7655  7868 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 17:21:37.567  7655  7959 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 17:21:37.567  7655  7959 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 17:21:37.568  7655  7959 D BluetoothMapMasInstance: Accepting socket connection...
08-25 17:21:37.568  2155  2155 D a       : Closing database...
08-25 17:21:37.570  7655  7960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:37.573  7655  7960 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 17:21:37.573  7655  7960 V BluetoothPbapService: Succeed to create listening socket 
08-25 17:21:37.573  7655  7960 V BluetoothPbapService: Accepting socket connection...
08-25 17:21:37.574  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:37.580  6797  6797 D BluetoothPermissionRequest: onReceive
,08-25 17:21:37.583  6797  6797 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 17:21:37.584  6797  6797 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 17:21:37.587  7655  7655 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 17:21:37.588  7655  7655 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 17:21:37.593  7655  7655 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 17:21:37.615  7655  7655 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 17:21:37.615  7655  7655 V BtOppService: onCreate
,08-25 17:21:37.619  7655  7655 V BluetoothOppNotification: send message
08-25 17:21:37.620  7655  7655 V BtOppService: Starting RfcommListener
08-25 17:21:37.623  7655  7655 D BluetoothOppPreference: Dumping Names:  
08-25 17:21:37.623  7655  7655 D BluetoothOppPreference: {}
08-25 17:21:37.623  7655  7655 D BluetoothOppPreference: Dumping Channels:  
08-25 17:21:37.623  7655  7655 D BluetoothOppPreference: {}
08-25 17:21:37.623  7655  7655 V BtOppService: onStartCommand
08-25 17:21:37.625  7655  7966 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 17:21:37.625  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.625  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 17:21:37.628  7655  7655 V BluetoothOppNotification: new notify threadi!
,08-25 17:21:37.628  7655  7966 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 17:21:37.629  7655  7963 V BtOppService: Deleted complete outbound shares, number =  0
08-25 17:21:37.629  7655  7655 V BluetoothOppNotification: send delay message
08-25 17:21:37.630  7655  7655 V BtOppService: start RfcommListener
08-25 17:21:37.631  7655  7963 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 17:21:37.631  7655  7963 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 17:21:37.632  7655  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e1393e4 on behalf of 
08-25 17:21:37.632  7655  7655 V BtOppService: RfcommListener started
08-25 17:21:37.633  7655  7969 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 17:21:37.633  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:37.634  7655  7969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:37.634  7655  7969 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-25 17:21:37.635  7655  7969 V BtOppRfcommListener: Started RFCOMM listener....
08-25 17:21:37.635  7655  7969 I BtOppRfcommListener: Accept thread started.
08-25 17:21:37.635  7655  7969 V BtOppRfcommListener: Accepting connection...
08-25 17:21:37.635  7655  7968 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 17:21:37.636  7655  7968 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bbda04d on behalf of 
08-25 17:21:37.636  7655  7966 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f22e702 on behalf of 
08-25 17:21:37.636  7655  7968 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 17:21:37.637  7655  7966 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 17:21:37.637  7655  7968 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 17:21:37.638  7655  7968 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21cb2813 on behalf of 
08-25 17:21:37.639  7655  7968 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-25 17:21:37.639  7655  7968 V BluetoothOppNotification: outbound notification was removed.
08-25 17:21:37.639  7655  7968 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 17:21:37.645  7655  7968 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b680a50 on behalf of 
08-25 17:21:37.645  7655  7968 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 17:21:37.647  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:37.647  7655  7655 V BluetoothFtpService: Ftp Service onCreate
08-25 17:21:37.647  7655  7655 I BluetoothFtpService: Ftp Service onCreate
08-25 17:21:37.647  7655  7655 V BluetoothFtpService: Ftp Service onStartCommand
08-25 17:21:37.647  7655  7655 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.647  7655  7655 V BluetoothFtpService: Starting Listening on sockets
08-25 17:21:37.647  7655  7655 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 17:21:37.647  7655  7655 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 17:21:37.647  7655  7655 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 17:21:37.647  7655  7655 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.647  7655  7655 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 17:21:37.647  7655  7655 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 17:21:37.649  7655  7968 V BluetoothOppNotification: inbound notification was removed.
08-25 17:21:37.649  7655  7968 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-25 17:21:37.650  7655  7655 V BtOppService: ContentObserver received notification
08-25 17:21:37.650  7655  7655 V BtOppService: ContentObserver received notification
08-25 17:21:37.650  7655  7655 V BluetoothFtpService: Handler(): got msg=1
08-25 17:21:37.650  7655  7968 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e5c714e on behalf of 
08-25 17:21:37.652  7655  7655 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 17:21:37.652  7655  7655 V BluetoothFtpService: Ftp Service initSocket
08-25 17:21:37.655  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:37.656  7655  7970 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 17:21:37.656  7655  7655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:21:37.656  7655  7970 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 17:21:37.657  7655  7655 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-25 17:21:37.657  7655  7655 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 17:21:37.657  7655  7970 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3836326f on behalf of 
08-25 17:21:37.658  7655  7970 V BluetoothOppNotification: update too frequent, put in queue
08-25 17:21:37.659  7655  7971 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 17:21:37.660  7655  7970 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 17:21:37.662  1034  1034 I art     : Explicit concurrent mark sweep GC freed 28475(1403KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.887ms total 153.168ms
08-25 17:21:37.662  1034  1034 D BluetoothHeadset: Proxy object connected
,08-25 17:21:37.663  1034  1034 D BluetoothA2dp: Proxy object connected
08-25 17:21:37.664  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 17:21:37.665  1034  1116 D BluetoothManagerService: Message: 40
08-25 17:21:37.665  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 17:21:37.666  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30aa3ea8
08-25 17:21:37.667  7655  7655 V BluetoothSapService: Sap Service onCreate
08-25 17:21:37.668  7655  7655 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:21:37.668  7655  7655 V BluetoothSapService: state: 12
08-25 17:21:37.668  7655  7655 V BluetoothSapService: Starting SAP server process
08-25 17:21:37.670  7655  7655 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 17:21:37.657  7972  7972 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:37.657  7972  7972 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:37.671  7655  7973 V BluetoothSapService: Sap Service initRfcommSocket
08-25 17:21:37.674  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:37.675  7655  7973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:21:37.676  7655  7973 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 17:21:37.676  7655  7973 V BluetoothSapService: Succeed to create listening socket 
08-25 17:21:37.676  7655  7973 V BluetoothSapService: Accepting socket connection...
08-25 17:21:37.680  7972  7972 V BT_SAP  : Event pipe created
08-25 17:21:37.680  7972  7972 V BT_SAP  : create_server_socket qcom.sap.server
08-25 17:21:37.680  7972  7972 V BT_SAP  : created socket fd 6
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:38.292  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:21:38.298  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:38.300  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:38.300  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c5cdb25 added. We now have 8 listener(s)
08-25 17:21:38.300  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:38.303  1034  1755 D WifiServiceImplEx: setWifiEnabled: false pid=6715, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:21:38.303  1034  1755 D WifiService: setWifiEnabled: false pid=6715, uid=10118
08-25 17:21:38.303  1034  1755 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:21:38.309  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:38.313  1034  1960 D WifiServiceImplEx: setWifiEnabled: true pid=6715, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 17:21:38.313  1034  1960 D WifiService: setWifiEnabled: true pid=6715, uid=10118
08-25 17:21:38.313  1034  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:21:38.337  1034  1439 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 17:21:38.337  1034  1439 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-25 17:21:38.342  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 17:21:38.342  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 17:21:38.343  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 17:21:38.343  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 17:21:38.343  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:21:38.343  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 17:21:38.343  1034  1439 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 17:21:38.343  1034  1439 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-25 17:21:38.343  1034  1439 E WifiHW  : unknown target_country: EU , set to default,
08-25 17:21:38.343  1034  1439 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-25 17:21:38.343  1034  1439 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-25 17:21:38.343  1034  1439 I WifiUtil: gEnableBmps=1,
08-25 17:21:38.632  7655  7655 V BluetoothOppNotification: new notify threadi!
,08-25 17:21:38.648  7655  7655 V BluetoothOppNotification: send delay message
,08-25 17:21:38.656  7655  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-25 17:21:38.667  7655  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@159d868b on behalf of 
08-25 17:21:38.668  7655  7986 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 17:21:38.678  7655  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-25 17:21:38.682  7655  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d92d368 on behalf of 
08-25 17:21:38.683  7655  7986 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 17:21:38.686  7655  7986 V BluetoothOppNotification: outbound notification was removed.
08-25 17:21:38.686  7655  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 17:21:38.687  7655  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e5de381 on behalf of 
08-25 17:21:38.687  7655  7986 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 17:21:38.689  7655  7986 V BluetoothOppNotification: inbound notification was removed.
08-25 17:21:38.689  7655  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 17:21:38.690  7655  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10115c26 on behalf of 
,08-25 17:21:38.947   309   892 D SoftapController: Softap fwReload - Ok
,08-25 17:21:38.955  1034  1439 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (602ms)
08-25 17:21:38.967   309   892 D CommandListener: Setting iface cfg
08-25 17:21:38.967   309   892 D CommandListener: Trying to bring down wlan0
,08-25 17:21:38.974  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 17:21:39.007   309   892 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:21:39.012  1034  1439 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 17:21:39.016  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:39.016  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:39.016  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:21:39.017  7994  7994 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:21:39.017  7994  7994 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:39.037  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 17:21:39.040  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:39.063  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-25 17:21:39.064  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:39.066  1034  1439 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 17:21:39.066  1034  1439 D WifiMonitor: connecting to supplicant
08-25 17:21:39.075  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:21:39.075  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:21:39.075  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:21:39.075  6797  6797 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 17:21:39.078  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:21:39.079  6797  6797 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:21:39.079  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 17:21:39.079  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:21:39.079  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:21:39.079  6797  6797 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:21:39.079  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 17:21:39.079  6797  6797 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:21:39.087  7994  7994 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 17:21:39.120  7994  7994 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 17:21:39.120  7994  7994 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 17:21:39.125  1034  1116 D Tethering: InitialState.processMessage what=4
08-25 17:21:39.136  1034  1961 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8011 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 17:21:39.139  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 17:21:39.150   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 17.385ms
,08-25 17:21:39.165   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 302us total 14.725ms
,08-25 17:21:39.179   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 13.370ms
,08-25 17:21:39.201  7994  7994 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 17:21:39.219  1034  2032 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8033 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 17:21:39.223  8011  8031 W FormManager: Network not available. Please check & try again.
08-25 17:21:39.228  8011  8032 V FormManager: Network unavailable.
08-25 17:21:39.230  8011  8032 V FormManager: Network unavailable.
08-25 17:21:39.239  1034  1995 I ActivityManager: Killing 7092:com.android.chrome/u0a57 (adj 15): empty #17
,08-25 17:21:39.258  7994  7994 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-25 17:21:39.262  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:21:39.263  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 17:21:39.263  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-25 17:21:39.263  1034  1439 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 17:21:39.264  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:39.264  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:39.264  1034  1439 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:39.264  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:39.265  1034  1439 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 17:21:39.265  1034  1439 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 17:21:39.265  1034  1439 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 17:21:39.265  1034  1439 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 17:21:39.265  1034  1439 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 17:21:39.267  7994  7994 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 17:21:39.267  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:21:39.267  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 17:21:39.267  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 17:21:39.268  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 17:21:39.268  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 17:21:39.268  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-25 17:21:39.314  1034  1888 W libprocessgroup: failed to open /acct/uid_10057/pid_7092/cgroup.procs: No such file or directory
08-25 17:21:39.319  1034  1439 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 17:21:39.319  1034  1439 E WifiStateMachine: useWiFiOffloading() : false
08-25 17:21:39.319  1034  1439 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 17:21:39.320  1034  1439 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-25 17:21:39.321  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.321  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.321  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.322  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.322  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 17:21:39.322  1034  1439 D WifiNative-wlan0: SET update_config 1: returned true
08-25 17:21:39.322  1034  1439 D WifiConfigStore: Loading config and enabling all networks 
08-25 17:21:39.322  1034  1439 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 17:21:39.323  1034  1439 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 17:21:39.325  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-25 17:21:39.326  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:39.329  1034  1439 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 17:21:39.330  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 17:21:39.331  1034  1484 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:39.339  6715  6715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:39.339  1034  1439 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-25 17:21:39.339  1034  1439 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 17:21:39.340  1034  1439 D WifiStateMachine: enableVerboseLogging : level 2
08-25 17:21:39.340  1034  1439 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 17:21:39.340  1034  1439 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 17:21:39.340  1034  1439 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 17:21:39.341  6715  6715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:21:39.341  1034  1439 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 17:21:39.342  1034  1439 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 17:21:39.342  1034  1439 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 17:21:39.342  1034  1439 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 17:21:39.342  1034  1439 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 17:21:39.342  1034  1439 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 17:21:39.343  1034  1439 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 17:21:39.343  1034  1439 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 17:21:39.343  1034  1439 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 17:21:39.343  1034  1439 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 17:21:39.344  1034  1439 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 17:21:39.344  1034  1439 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:21:39.345  1034  1439 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 17:21:39.345  1034  1439 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 17:21:39.345  1034  1439 D WifiNative-HAL: Setting external_sim to 1
08-25 17:21:39.345  1034  1439 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 17:21:39.345  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-25 17:21:39.345  7684  7684 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.345  1942  2318 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 17:21:39.346  1942  2318 D WfdsService: Set the WFDS Monitor: true
08-25 17:21:39.346  1942  2318 D WfdsMonitor: WfdsMonitorThread create
08-25 17:21:39.346  1034  1439 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 17:21:39.346  1034  1439 I WifiNative-HAL: startHal
08-25 17:21:39.346  1034  1439 D wifi    : setting scan oui 0xaf64f5c0
08-25 17:21:39.346  1942  2318 D WfdsMonitor: WFDS Monitor is created and started
08-25 17:21:39.346  1942  2318 D WfdsService: WiFi: Supplicant connection re-established
08-25 17:21:39.347  1034  1439 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 17:21:39.347  1034  1439 I WifiNative-HAL: startHal
08-25 17:21:39.347  1034  1439 D wifi    : setting scan oui 0xaf64f5c0
08-25 17:21:39.347  1034  1439 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 17:21:39.348  1034  1439 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 17:21:39.348  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 17:21:39.348  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 17:21:39.348  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 17:21:39.348  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:21:39.349  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:21:39.349  1942  8053 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 17:21:39.349  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:21,:39.349  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 17:21:39.349  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 17:21:39.349  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 17:21:39.349  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:21:39.350  1942  8053 E CtrlSupplicant: Succeed to open control connection
08-25 17:21:39.350  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:21:39.350  1942  8053 E CtrlSupplicant: Succeed to open monitor connection
08-25 17:21:39.350  1942  8053 D WfdsMonitor: Supplicant connection established
08-25 17:21:39.351  1942  2318 D WfdsService: Connected to the supplicant for wfds
08-25 17:21:39.352  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:21:39.352  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 17:21:39.352  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 17:21:39.352  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 17:21:39.352  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:21:39.353  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:21:39.354  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:21:39.354  7994  7994 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 17:21:39.356  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 17:21:39.356  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 17:21:39.356  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 17:21:39.356  1034  1439 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 17:21:39.357  1034  1439 E WifiNative: : [209,755,340 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 17:21:39.357  1034  1439 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 17:21:39.357  1034  1439 D WifiNative-wlan0: RECONNECT: returned true
08-25 17:21:39.357  1034  1439 D WifiNative-wlan0: doString: [STATUS]
08-25 17:21:39.358  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:21:39.358  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 17:21:39.358  1034  1439 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 17:21:39.358  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:21:39.359  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:39.359  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.359  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 17:21:39.359  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-25 17:21:39.359  1034  1439 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 17:21:39.360  1034  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.360  1034  1556 I WifiNative-HAL: startHal
08-25 17:21:39.360  1034  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.360  1034  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf64f5c0
08-25 17:21:39.360  1034  1556 D wifi    : failed to get capabilities : -3
08-25 17:21:39.360  1034  1556 E WifiScanningService: could not get scan capabilities
08-25 17:21:39.360  1034  1439 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 17:21:39.360  1034  1439 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 17:21:39.360   309   892 D CommandListener: Setting iface cfg
08-25 17:21:39.360   309   892 D CommandListener: Trying to bring up p2p0
08-25 17:21:39.360  1034  1439 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 17:21:39.360  1034  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 17:21:39.361  1034  1390 D LGWifiP2pService: P2pEnablingState
08-25 17:21:39.361  1034  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.361  1034  1390 D LGWifiP2pService: P2p socket connection successful
08-25 17:21:39.361  1034  1390 D LGWifiP2pService: P2pEnabledState
08-25 17:21:39.361  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=209759  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:21:39.361  1034  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 17:21:39.362  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 17:21:39.362  1034  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 17:21:39.362  1942  1942 D WfdsService: WifiP2pState is changed : true
08-25 17:21:39.363  1942  2318 D WfdsService: Receive the WFDS_ENABLE Method
08-25 17:21:39.363  1942  2318 D WfdsService: Set the WFDS Monitor: true
08-25 17:21:39.363  1942  2318 D WfdsService: Connected to t,he supplicant for wfds
08-25 17:21:39.363  1942  2318 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 17:21:39.363  7994  7994 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 17:21:39.363  1942  2318 D WfdsService: selectPreferredScanChannel [36]
08-25 17:21:39.364  1942  2318 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 17:21:39.364  1034  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 17:21:39.364  1034  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 17:21:39.365  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 17:21:39.365  1034  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-25 17:21:39.365  1942  1942 D WfdsService: isConnected: false
08-25 17:21:39.365  1034  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 17:21:39.365  1034  1390 D LGWifiP2pService: before postfix = G3
08-25 17:21:39.365  1034  1390 D WifiServerServiceExt: postfix byte check : 2
08-25 17:21:39.365  1034  1390 D LGWifiP2pService: after postfix = G3
08-25 17:21:39.365  1034  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 17:21:39.367  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:39.367  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 17:21:39.367  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=209764  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:21:39.366  1034  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 17:21:39.368  1034  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 17:21:39.368  1034  1439 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 17:21:39.368  1034  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 17:21:39.368  1034  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 17:21:39.368  1034  1439 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 17:21:39.369  1034  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 17:21:39.369  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 17:21:39.369  1034  1439 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 17:21:39.369  1034  1439 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 17:21:39.369  7994  7994 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 17:21:39.369  1034  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 17:21:39.369  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-25 17:21:39.369  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-25 17:21:39.370  6715  6776 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 17:21:39.370  1034  1439 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 17:21:39.370  1034  1439 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 17:21:39.370  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:39.371  1034  1439 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 17:21:39.371  1034  1439 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 17:21:39.371  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.371  7994  7994 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 17:21:39.371  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.371  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:21:39.371  1034  1390 D LGWifiP2pService: DeviceAddress: 
08-25 17:21:39.371  1034  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 17:21:39.372  1034  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 17:21:39.372  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 17:21:39.372  1034  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 17:21:39.372  6715  6776 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 17:21:39.372  1034  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 17:21:39.373  1034  1439 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 17:21:39.373  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 17:21:39.373  1034  1439 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 17:21:39.373  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 17:21:39.373  1942  1942 D WfdsService: Update P2p Interface State: 3
08-25 17:21:39.373  1034  1439 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 17:21:39.373  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 17:21:39.374  6715  6776 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@31aeb19f Bundle[{}]
08-25 17:21:39.374  1034  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 17:21:39.374  1034  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 17:21:39.375  6715  ,6776 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 17:21:39.375  6715  6776 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 17:21:39.375  6715  6776 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 17:21:39.376  6715  6776 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 17:21:39.377  6715  6776 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 17:21:39.378  6715  6776 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 17:21:39.383  8033  8033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:39.385  6715  6776 I System.out: Running OutgoingSocketThread
08-25 17:21:39.386  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 17:21:39.387  6715  8056 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
08-25 17:21:39.388  6715  8056 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39285
08-25 17:21:39.388  6715  8056 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 17:21:39.393  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:21:39.394  1034  1961 I ActivityManager: Killing 7113:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 17:21:39.395  1034  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 17:21:39.395  1034  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 17:21:39.396  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:21:39.396  7994  7994 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.397  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:21:39.397  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.397  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.397  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.397  7994  7994 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 17:21:39.397  7994  7994 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.397  1034  1439 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 17:21:39.397  1942  8053 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.398  1034  1439 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:21:39.398  7994  7994 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.398  1942  8053 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.398  1034  1439 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:21:39.398  1034  1439 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 17:21:39.398  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 17:21:39.398  1034  8051 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.398  1034  8051 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.398  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 17:21:39.398  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.398  7994  7994 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:39.398  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.398  1034  8051 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.398  1034  8051 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.399  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.399  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.399  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 17:21:39.399  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:39.399  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:39.399  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 17:21:39.399  1034  1439 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 17:21:39.399  1034  1439 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 17:21:39.399  1034  1439 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 17:21:39.399  1034  1439 D WifiNative-wlan0: doBoolean: SCAN
08-25 17:21:39.400  1034  1439 D WifiNative-wlan0: SCAN: returned false
08-25 17:21:39.400  1034  1439 E WifiStateMachine:  DisconnectedState SUPPL,ICANT_STATE_CHANGE_EVENT 46 0 rt=209799  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:21:39.428  1034  1390 D LGWifiP2pService: InactiveState
08-25 17:21:39.428  1034  1390 D LGWifiP2pService: InactiveState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.428  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:21:39.428  1034  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 17:21:39.429  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 17:21:39.429  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=209828  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 17:21:39.429  7994  7994 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.429  1034  8051 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:21:39.429  1034  8051 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.429  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.429  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 17:21:39.430  1942  8053 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 17:21:39.430  7994  7994 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 17:21:39.430  7994  7994 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.430  1034  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: InactiveState{ when=-32ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-32ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  7994  7994 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.430  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.431  1034  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.431  1034  8051 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.431  1034  8051 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.431  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.431  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.431  1034  8051 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.431  1034  8051 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.431  1034  8051 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.431  1034  8051 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-R,EGDOM-CHANGE init=DRIVER type=WORLD
08-25 17:21:39.431  1942  8053 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.431  1942  8053 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 17:21:39.431  1034  1439 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:39.432  1034  1439 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:39.432  1034  1439 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:39.432  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.432  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.432  1034  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:39.432  1942  2318 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 17:21:39.432  1034  1034 E WifiServerServiceExt: No p2p device connected
08-25 17:21:39.432  1034  1439 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:39.432  1034  1439 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 17:21:39.435  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:39.435  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:39.436  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:39.438  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.438  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.438  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 17:21:39.438  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:39.438  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 17:21:39.439  1034  1710 W libprocessgroup: failed to open /acct/uid_10062/pid_7113/cgroup.procs: No such file or directory
08-25 17:21:39.442  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:39.442  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-25 17:21:39.457  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-25 17:21:39.457  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:21:39.457  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:21:39.457  6797  6797 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 17:21:39.458  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-25 17:21:39.459  6797  6797 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:21:39.459  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 17:21:39.459  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:21:39.459  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:21:39.459  6797  6797 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:21:39.459  6797  6797 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:21:39.465  8033  8033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:39.468  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 17:21:39.474  8011  8058 W FormManager: Network not available. Please check & try again.
08-25 17:21:39.474  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:39.478  8011  8059 V FormManager: Network unavailable.
08-25 17:21:39.481  8011  8059 V FormManager: Network unavailable.
08-25 17:21:39.492  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 17:21:39.493  4302  4302 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 17:21:39.495  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:39.498  4302  4302 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 17:21:39.505  4302  8060 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 17:21:39.509  4302  8061 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 17:21:39.509  4302  8061 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 17:21:39.565  1034  1888 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8062 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 17:21:39.705  8062  8062 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 17:21:39.706  8062  8062 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 17:21:39.718  8062  8062 V [BNRBootReceiver]: Boot Receiver Return
,08-25 17:21:39.720  8062  8062 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-25 17:21:39.788  7994  7994 E wpa_supplicant: USIM:  scard_init function
08-25 17:21:39.789  7994  7994 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-25 17:21:39.794  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 17:21:39.794  1034  8051 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 17:21:39.794  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 17:21:39.794  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-25 17:21:39.794  1034  8051 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 17:21:39.794  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 17:21:39.794  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 17:21:39.796  1034  1439 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:39.796  1034  1921 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8086 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 17:21:39.799  1034  1439 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:39.800  1034  1439 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:39.801  1034  1439 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 17:21:39.801  1034  1439 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 17:21:39.804  1034  1921 I ActivityManager: Killing 7133:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-25 17:21:39.869  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=210268  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 17:21:39.873  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=210272  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 17:21:39.876  1034  1755 W libprocessgroup: failed to open /acct/uid_10085/pid_7133/cgroup.procs: No such file or directory
08-25 17:21:39.885  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:39.885  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:39.887  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.887  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.887  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 17:21:39.888  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:39.888  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-25 17:21:39.889  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:39.903  7994  7994 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 17:21:39.908  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 17:21:39.908  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 17:21:39.908  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 17:21:39.909  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 17:21:39.909  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:39.909  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:39.912  8086  8086 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:39.914  7994  7994 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:21:39.914  7994  7994 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:21:39.917  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210315  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 17:21:39.917  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210316  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 17:21:39.920  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:39.921  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:39.921  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 17:21:39.921  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:21:39.921  1034  8051 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 17:21:39.921  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 17:21:39.921  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:21:39.921  1034  8051 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 17:21:39.921  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:39.921  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 17:21:39.924  1034  1439 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210323
08-25 17:21:39.925  1034  1439 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210323
08-25 17:21:39.925  1034  1439 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210324
08-25 17:21:39.926  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210324
08-25 17:21:39.927  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 17:21:39.933  1034  1439 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210332
08-25 17:21:39.934  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=210332  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 17:21:39.938  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:39.938  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 17:21:39.942  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.942  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.942  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 17:21:39.942  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:39.943  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=210341  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 17:21:39.945  1034  1439 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210343  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 17:21:39.945  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210344  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 17:21:39.950  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.951  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.951  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 17:21:39.951  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:39.951  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 17:21:39.952  1034  1439 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210351
08-25 17:21:39.952  1034  1439 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210351
08-25 17:21:39.953  1034  1439 D WifiNative-wlan0: doString: [STATUS]
08-25 17:21:39.953  1034  8051 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 17:21:39.953  1034  8051 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 17:21:39.954  1034  1439 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-25 17:21:39.956  1034  1439 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 17:21:39.963  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:39.963  8086  8086 D PluginManager: init()
08-25 17:21:39.963  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:39.964  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:39.966  1034  1439 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 17:21:39.966  1034  1439 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 17:21:39.973  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:21:39.973  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.974  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 17:21:39.988  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:39.988  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 17:21:39.989  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.989  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:39.989  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 17:21:39.996  1034  1439 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 17:21:39.996  1034  1439 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:21:39.996  1034  1439 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:21:39.997  1034  1540 D ConnectivityService: Got NetworkAgent Messenger
08-25 17:21:39.997  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 17:21:39.997  1034  1540 D ConnectivityService: NetworkAgent connected
08-25 17:21:39.997  1034  1439 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:21:39.997  1034  1439 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:21:39.998  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.003  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:40.003  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:40.004  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:40.010  1034  1439 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 17:21:40.010  1034  1439 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:21:40.010  1034  1439 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 17:21:40.011  1034  1439 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 17:21:40.011  1034  1439 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 17:21:40.018  1034  1439 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 17:21:40.020   309   892 D CommandListener: Setting iface cfg
08-25 17:21:40.023  1034  1439 E WifiStateMachine: Start Dhcp Watchdog 3
08-25 17:21:40.023  1034  8114 D DhcpStateMachine: StoppedState
08-25 17:21:40.024  1034  8114 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:40.024  1034  8114 D DhcpStateMachine: WaitBeforeStartState
08-25 17:21:40.024  1034  1439 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210423  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:40.024  1034  1439 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210423  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:40.025  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210424  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:40.026  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:40.026  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:40.026  1034  1439 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:40.027  1034  1439 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:40.027  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:40.028  1034  1439 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 17:21:40.028  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:40.028  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 17:21:40.029  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:40.029  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 17:21:40.030  1034  1439 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:40.030  1034  1439 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:40.031  1034  1439 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 17:21:40.032  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14184] from screen [on:0 period:-1035282496] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 17:21:40.034  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1035282494] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 17:21:40.034  1034  1439 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 17:21:40.038  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.040  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:40.040  1034  1540 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-25 17:21:40.040  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:40.040  1034  1439 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:40.041  1034  1439 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:40.041  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:40.042  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 17:21:40.042  1034  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 17:21:40.042  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-25 17:21:40.043  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-25 17:21:40.043  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 17:21:40.043  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 17:21:40.044  1034  1439 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 17:21:40.044  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 17:21:40.044  1034  1439 D WifiNative-wlan0: SET ps 0: returned true
08-25 17:21:40.044  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 17:21:40.044  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 17:21:40.045  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 17:21:40.045  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20e73173 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 17:21:40.045  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20e73173 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:40.046  1034  8114 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:40.046  1034  8114 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 17:21:40.047  1034  1439 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 17:21:40.047  1034  1439 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 17:21:40.047  1034  1439 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 17:21:40.048   309   892 D CommandListener: Setting iface cfg
08-25 17:21:40.048   309   892 D CommandListener: Trying to bring up wlan0
08-25 17:21:40.049  1034  1439 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 17:21:40.050  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:40.050  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 17:21:40.051  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 17:21:40.052  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 17:21:40.053  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-25 17:21:40.054  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
,08-25 17:21:40.054  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:40.054  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 17:21:40.055  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:40.055  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 17:21:40.056  1034  1439 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 17:21:40.056  1034  1439 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 17:21:40.057  7994  7994 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 17:21:40.058  1034  1439 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 17:21:40.058  1034  1439 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 17:21:40.073  1034  1439 D WifiNative-wlan0: SET ps 1: returned true
08-25 17:21:40.074  1034  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-25 17:21:40.075  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 17:21:40.077  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:40.078  1034  1439 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:40.079  1034  1439 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:40.080  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:40.081  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:40.082  1034  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 17:21:40.083  1034  1439 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 17:21:40.084  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 17:21:40.085  1034  1439 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 17:21:40.085  1034  1540 D ConnectivityService: ignoring duplicate network state non-change
,08-25 17:21:40.089  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:40.089  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:40.090  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.090  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.090  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.090  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 17:21:40.094  1034  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 17:21:40.094  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.094  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.094  1034  1540 D ConnectivityService: Adding iface wlan0 to network 102
08-25 17:21:40.095  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 17:21:40.097  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 17:21:40.097  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 17:21:40.098  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.098  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.098  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-25 17:21:40.100  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 17:21:40.103  1034  1439 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 17:21:40.104  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.104  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:21:40.104  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 17:21:40.109  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:40.109  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 17:21:40.110  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:40.115  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:40.115  1034  1540 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 17:21:40.115  1034  1540 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 17:21:40.116  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 17:21:40.116  1034  1540 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 17:21:40.117  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.117   309   892 E Netd    : netlink response contains error (File exists)
08-25 17:21:40.117  1034  1540 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 17:21:40.118  1034  1540 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 17:21:40.118  1034  1540 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-25 17:21:40.118  1034  1540 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-25 17:21:40.119  1034  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 17:21:40.119  1034  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 17:21:40.119  1034  1540 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 17:21:40.119  1034  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 17:21:40.119  1034  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:40.119  1034  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:40.119  1034  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-25 17:21:40.119  1034  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.119  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 17:21:40.119  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 17:21:40.119  1034  8112 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:40.119  1034  8112 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 17:21:40.120  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.120  1034  8112 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 17:21:40.120  1034  8112 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 17:21:40.119  1034  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 17:21:40.122  1034  1540 D ConnectivityService: currentScore = 0, newScore = 20
08-25 17:21:40.122  1034  1540 D ConnectivityService:    accepting network in place of null
08-25 17:21:40.122  1034  1540 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.122  1034  1439 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.122   309  8120 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 17:21:40.123  1034  1439 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:40.123  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.123  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-25 17:21:40.124  1034  1540 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 17:21:40.124  1034  1540 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 17:21:40.124  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 17:21:40.125  1034  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:21:40.125  1034  1540 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 17:21:40.125  1034  1540 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 17:21:40.126  1034  1540 D ConnectivityService: validation of new default Network = false
08-25 17:21:40.126  1034  1540 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 17:21:40.126  1034  1540 D DSQN    : enableDataServiceNotify 
08-25 17:21:40.126  1034  1540 D DSQN    : start dsqn bin
08-25 17:21:40.128  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 17:21:40.128  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 17:21:40.128  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 17:21:40.128  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 17:21:40.140  1034  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-25 17:21:40.143  1034  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 17:21:40.143  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.143  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:40.144  1034  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:40.144  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:21:40.127  8121  8121 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:40.127  8121  8121 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 17:21:40.149  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:40.150  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.151  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.156  8121  8121 E DSQN    : DSQN ssw
,08-25 17:21:40.175   309  8120 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-25 17:21:40.211   309  8120 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 17:21:40.238   309   891 D LGDataListener: argv[0]=dsqncommand
,08-25 17:21:40.238   309   891 D LGDataListener: argv[1]=wlan0
08-25 17:21:40.238   309   891 D LGDataListener: argv[2]=1
08-25 17:21:40.238   309   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 17:21:40.239  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
,08-25 17:21:40.239  1034  1114 D DSQN    : start to monitor internet connection
,08-25 17:21:40.248  1034  8114 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 17:21:40.250  1034  8114 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 17:21:40.250  1034  8114 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 17:21:40.247  8127  8127 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:21:40.247  8127  8127 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 17:21:40.265  1034  8112 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:21:40 GMT], X-Android-Received-Millis=[1472138500263], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472138500237]}
08-25 17:21:40.265  1034  8112 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-25 17:21:40.265  1034  8112 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 17:21:40.265  1034  1540 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-25 17:21:40.266  1034  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-25 17:21:40.266  1034  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 17:21:40.266  1034  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:40.266  1034  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 17:21:40.266  1034  1540 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-25 17:21:40.267  1034  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 17:21:40.267  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.267  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:40.268  1034  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:40.269  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 17:21:40.269  1034  1540 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.270  1034  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 17:21:40.270  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.271  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 17:21:40.273  1034  1439 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:40.274  1034  1439 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 17:21:40.281  8127  8127 I dhcpcd  : version 5.5.6 starting
08-25 17:21:40.286  8127  8127 E dhcpcd  : get_duid: m
08-25 17:21:40.286  8127  8127 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 17:21:40.286  8127  8127 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 17:21:40.287  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 17:21:40.287  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 17:21:40.288  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 17:21:40.354  8127  8127 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-25 17:21:40.355  8127  8127 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 17:21:40.355  8127  8127 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 17:21:40.355  8127  8127 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 17:21:40.356  8127  8127 D dhcpcd  : wlan0: sending REQUEST (xid 0x414cf566), next in 3.68 seconds
,08-25 17:21:40.388  6715  6776 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
,08-25 17:21:40.389  6715  6776 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
08-25 17:21:40.393  8086  8086 W ExternalStrings: load override strings
08-25 17:21:40.393  8086  8086 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:40.393  8086  8086 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:21:40.395  8086  8086 D StatusProvider: onCreate
08-25 17:21:40.400  6715  6776 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
08-25 17:21:40.403  6715  6776 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 17:21:40.403  6715  6776 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
,08-25 17:21:40.408  8127  8127 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 17:21:40.410  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.410  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc4fa added. We now have 2 listener(s)
08-25 17:21:40.410  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 17:21:40.413  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.413  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.413  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:21:40.413  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.413  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9303aab added. We now have 9 listener(s)
08-25 17:21:40.413  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:21:40.416  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:21:40.418  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:40.423  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:40.425  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.425  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:40.425  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.425  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122504a1 added. We now have 3 listener(s)
08-25 17:21:40.425  1034  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.427  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.429  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.430  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.430  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.430  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.430  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.430  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36b236c6 added. We now have 10 listener(s)
08-25 17:21:40.430  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.430  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:40.430  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:40.430  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:40.430  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.430  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.430  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:40.430  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.430  6715  6776 V org.tha,liproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc4fa removed from the list
08-25 17:21:40.431  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.431  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9303aab removed from the list
08-25 17:21:40.431  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:40.431  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:21:40.436  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.436  8127  8127 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 17:21:40.436  8127  8127 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 17:21:40.436  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.437  8127  8127 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 17:21:40.437  8127  8127 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 17:21:40.438  8127  8127 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 17:21:40.438  8127  8127 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 17:21:40.439  8127  8127 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 17:21:40.439  8127  8127 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 17:21:40.441  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.441  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.442  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.442  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9303aab not in the list
08-25 17:21:40.442  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.442  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.444  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.444  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.444  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.444  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36b236c6 removed from the list
08-25 17:21:40.444  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.444  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.444  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.444  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.445  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122504a1 removed from the list
08-25 17:21:40.447  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.447  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b5d687 added. We now have 2 listener(s)
,08-25 17:21:40.447  1034  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.451  8086  8086 V Signer  : override build config not found
08-25 17:21:40.452  8086  8086 D Signer  : value of property debug is false
08-25 17:21:40.454  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.455  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.455  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.455  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.455  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d33a9b4 added. We now have 9 listener(s)
08-25 17:21:40.455  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.456  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:21:40.461  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:40.467  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:21:40.469  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.469  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:40.471  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.471  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e0af952 added. We now have 3 listener(s)
08-25 17:21:40.471  1034  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.471  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.473  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.475  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.475  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.475  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.475  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:21:40.476  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f5423 added. We now have 10 listener(s)
08-25 17:21:40.476  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.476  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:40.476  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:21:40.476  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:21:40.476  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:40.476  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:21:40.486  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:21:40.486  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.490  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:21:40.492  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 17:21:40.493  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:21:40.493  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:40.495  6715  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:21:40.495  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:40.495  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:21:40.497  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:40.497  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:40.497  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:40.498  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.498  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.498  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:40.498  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.498  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b5d687 removed from the list
08-25 17:21:40.498  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.498  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d33a9b4 removed from the list
08-25 17:21:40.498  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:40.498  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.498  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.498  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.499  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.499  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.499  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.499  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d33a9b4 not in the list
08-25 17:21:40.499  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.499  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.500  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.501  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:40.501  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:40.501  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.501  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.501  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0f5423 removed from the list
08-25 17:21:40.501  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.501  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.501  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 ,17:21:40.501  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.501  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e0af952 removed from the list
08-25 17:21:40.502  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.502  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abb589e added. We now have 2 listener(s)
08-25 17:21:40.503  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.507  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.507  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.508  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.508  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.508  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef90f7f added. We now have 9 listener(s)
08-25 17:21:40.508  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.508  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:21:40.511  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:40.511  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 17:21:40.512  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-25 17:21:40.512  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 17:21:40.512  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 17:21:40.512  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 17:21:40.513  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 17:21:40.513  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 17:21:40.513  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 17:21:40.513  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-25 17:21:40.513  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 17:21:40.514  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 17:21:40.514  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:40.514  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:40.514  8086  8086 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-25 17:21:40.515  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.515  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:40.517  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.518  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b3d795 added. We now have 3 listener(s)
08-25 17:21:40.518  1034  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.519  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.521  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.521  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.522  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.522  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.522  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSetti,ngs: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@258060aa added. We now have 10 listener(s)
08-25 17:21:40.522  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.522  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:40.523  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:40.523  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:21:40.523  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:21:40.523  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:40.523  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:21:40.523  8086  8086 V LGMDMManager: Create singleton instance
,08-25 17:21:40.529  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.531  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:21:40.531  1034  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.538  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:21:40.538  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:21:40.541  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:21:40.541  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:40.542  6715  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 17:21:40.543  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:40.543  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:40.543  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:40.543  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.543  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.543  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:40.543  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.543  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abb589e removed from the list
08-25 17:21:40.543  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.543  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef90f7f removed from the list
08-25 17:21:40.543  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:40.543  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.544  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.544  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.545  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.545  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.545  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.545  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef90f7f not in the list
08-25 17:21:40.545  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.545  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.546  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.547  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:40.547  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:40.547  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.547  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.547  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@258060aa removed from the list
08-,25 17:21:40.547  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.547  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.547  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.547  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.547  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b3d795 removed from the list
08-25 17:21:40.548  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.548  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c75811 added. We now have 2 listener(s)
08-25 17:21:40.548  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.550  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 17:21:40.550  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.550  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.550  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.551  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbdd76 added. We now have 9 listener(s)
08-25 17:21:40.551  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.551  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:21:40.553  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:40.558  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:40.559  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.559  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:40.560  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.560  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ceee7e4 added. We now have 3 listener(s)
08-25 17:21:40.560  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.562  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:21:40.563  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.564  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.564  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.564  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.564  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.564  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab8644d added. We now have 10 listener(s)
08-25 17:21:40.564  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.565  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:40.565  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:21:40.565  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:21:40.565  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:40.565  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:21:40.567  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:21:40.568  1034  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.571  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:21:40.572  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 17:21:40.573  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:21:40.574  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:21:40.576  6715  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-25 17:21:40.577  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:40.577  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:40.577  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:40.577  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.577  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.577  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:40.577  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.578  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c75811 removed from the list
08-25 17:21:40.578  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.578  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbdd76 removed from the list
08-25 17:21:40.578  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:40.578  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.578  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.578  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.579  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.579  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.579  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.579  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dbdd76 not in the list
08-25 17:21:40.579  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.579  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.580  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.580  6715  6776 D BluetoothLeScanner: could not find callback wrapper
08-25 17:21:40.580  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:21:40.580  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.580  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.580  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab8644d removed from the list
08-25 17:21:40.580  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.580  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.580  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 1,7:21:40.580  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.580  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ceee7e4 removed from the list
08-25 17:21:40.581  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.581  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea49e50 added. We now have 2 listener(s)
08-25 17:21:40.582  1034  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.584  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.584  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.584  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.584  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.584  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3633f849 added. We now have 9 listener(s)
08-25 17:21:40.585  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.586  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:21:40.597  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:21:40.600  6715  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:21:40.602  6715  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:21:40.602  6715  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:21:40.602  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:21:40.602  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bad66f added. We now have 3 listener(s)
08-25 17:21:40.602  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 17:21:40.604  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.605  6715  6715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:21:40.607  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 17:21:40.607  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:21:40.607  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:21:40.607  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:21:40.607  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fbd4f7c added. We now have 10 listener(s)
08-25 17:21:40.607  6715  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:21:40.608  6715  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:21:40.608  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:40.608  6715  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:21:40.608  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.608  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.608  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:21:40.608  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.608  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ea49e50 removed from the list
08-25 17:21:40.608  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.608  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3633f849 removed from the list
08-25 17:21:40.608  6715  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:21:40.608  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.609  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.609  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.609  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: ,stopAdvertising
08-25 17:21:40.610  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.610  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.610  6715  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3633f849 not in the list
08-25 17:21:40.610  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.610  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.610  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:21:40.610  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:21:40.610  6715  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:21:40.610  6715  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fbd4f7c removed from the list
08-25 17:21:40.610  6715  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:21:40.610  6715  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:21:40.611  6715  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:21:40.611  6715  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:21:40.611  6715  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bad66f removed from the list
08-25 17:21:40.611  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 17:21:40.612  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 17:21:40.612  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 17:21:40.612  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:21:40.612  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 17:21:40.612  6715  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:21:40.625  6715  8153 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
08-25 17:21:40.625  6715  8153 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
08-25 17:21:40.626  6715  8153 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 17:21:40.628  6715  8155 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: My test thread name)
08-25 17:21:40.628  6715  8155 D io.jxcore.node.StreamCopy,ingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
08-25 17:21:40.628  6715  8155 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 17:21:40.630  6715  6776 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 17:21:40.630  6715  6776 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 17:21:40.631  6715  6776 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 17:21:40.631  6715  6776 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 17:21:40.631  6715  6776 D com.test.thalitest.ThaliTestRunner: Total duration: 23269 ms
08-25 17:21:40.632  6715  6776 I jxcore-log: Total number of executed tests:  80
08-25 17:21:40.632  6715  6776 I jxcore-log: 
08-25 17:21:40.632  6715  6776 I jxcore-log: Number of passed tests:  80
08-25 17:21:40.632  6715  6776 I jxcore-log: 
08-25 17:21:40.632  6715  6776 I jxcore-log: Number of failed tests:  0
08-25 17:21:40.632  6715  6776 I jxcore-log: 
08-25 17:21:40.632  6715  6776 I jxcore-log: Number of ignored tests:  0
08-25 17:21:40.632  6715  6776 I jxcore-log: 
08-25 17:21:40.633  6715  6776 I jxcore-log: Total duration:  23269
08-25 17:21:40.633  6715  6776 I jxcore-log: 
08-25 17:21:40.633  6715  6776 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 17:21:40.633  6715  6776 I jxcore-log: 
08-25 17:21:40.634  8086  8086 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-25 17:21:40.637  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.637  6715  6776 I jxcore-log: 
08-25 17:21:40.640  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.640  6715  6776 I jxcore-log: 
08-25 17:21:40.641  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.641  6715  6776 I jxcore-log: 
08-25 17:21:40.642  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.642  6715  6776 I jxcore-log: 
08-25 17:21:40.643  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.643  6715  6776 I jxcore-log: 
08-25 17:21:40.645  6715  6715 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 17:21:40.645  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.645  6715  6776 I jxcore-log: 
08-25 17:21:40.648  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:21:40.648  6715  6776 I jxcore-log: 
08-25 17:21:40.650  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:21:40.650  6715  6776 I jxcore-log: 
08-25 17:21:40.650  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.650  6715  6776 I jxcore-log: 
08-25 17:21:40.651  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.651  6715  6776 I jxcore-log: 
08-25 17:21:40.652  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:21:40.652  6715  6776 I jxcore-log: 
08-25 17:21:40.653  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:21:40.653  6715  6776 I jxcore-log: 
08-25 17:21:40.654  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:21:40.654  6715  6776 I jxcore-log: 
,08-25 17:21:40.655  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.655  6715  6776 I jxcore-log: 
08-25 17:21:40.655  1034  8114 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-25 17:21:40.655  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.655  6715  6776 I jxcore-log: 
08-25 17:21:40.656  1034  8114 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 17:21:40.656  1034  8114 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 17:21:40.656  1034  8114 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 17:21:40.656  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.656  6715  6776 I jxcore-log: 
08-25 17:21:40.656  1034  8114 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 17:21:40.656  1034  8114 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 17:21:40.656  1034  8114 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 17:21:40.656  1034  8114 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 17:21:40.657  1034  8114 D DhcpStateMachine: RunningState
08-25 17:21:40.657  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.657  6715  6776 I jxcore-log: 
08-25 17:21:40.658  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.658  6715  6776 I jxcore-log: 
08-25 17:21:40.658  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.658  6715  6776 I jxcore-log: 
08-25 17:21:40.659  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.659  6715  6776 I jxcore-log: 
08-25 17:21:40.660  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:21:40.660  6715  6776 I jxcore-log: 
08-25 17:21:40.661  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:21:40.661  6715  6776 I jxcore-log: 
08-25 17:21:40.662  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:21:40.662  6715  6776 I jxcore-log: 
08-25 17:21:40.662  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.662  6715  6776 I jxcore-log: 
08-25 17:21:40.663  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.663  6715  6776 I jxcore-log: 
08-25 17:21:40.664  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.664  6715  6776 I jxcore-log: 
08-25 17:21:40.664  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.664  6715  6776 I jxcore-log: 
08-25 17:21:40.665  6715  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:21:40.665  6715  6776 I jxcore-log: 
08-25 17:21:40.694  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:40.694  8086  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 17:21:40.712  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:40.718  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:40.779  1034  1921 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8163 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-25 17:21:40.780  1034  1921 I ActivityManager: Killing 7157:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-25 17:21:40.855  8086  8157 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 17:21:40.940  8161  8161 D AndroidRuntime: 
08-25 17:21:40.940  8161  8161 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 17:21:40.944  8161  8161 D AndroidRuntime: CheckJNI is OFF
08-25 17:21:41.001  1034  1710 W libprocessgroup: failed to open /acct/uid_10093/pid_7157/cgroup.procs: No such file or directory
,08-25 17:21:41.060  8163  8163 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 17:21:41.089  8163  8163 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 17:21:41.125  8163  8163 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 17:21:41.125  8163  8163 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-25 17:21:41.126  8163  8163 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 17:21:41.127  8163  8163 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 17:21:41.128  8163  8163 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 17:21:41.129  8163  8163 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 17:21:41.130  8161  8161 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-25 17:21:41.137  8163  8163 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-25 17:21:41.143  1034  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 17:21:41.144  1034  1105 I ActivityManager: Killing 6715:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-25 17:21:41.147  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.151  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:41.175  8086  8157 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:41.175  8086  8157 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:41.183  1034  1888 I WindowState: WIN DEATH: Window{28dec89c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 17:21:41.184  1034  1525 D WifiService: Client connection lost with reason: 4
08-25 17:21:41.187  1034  1888 D InputDispatcher: Window went away: Window{28dec89c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 17:21:41.371  8086  8157 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-25 17:21:41.375  1034  1105 I ActivityManager:   Force finishing activity ActivityRecord{3c8d1141 u0 com.test.thalitest/.MainActivity t6}
,08-25 17:21:41.394   334   343 E GBMv2   : DFP En is all cleared set to be enabled
08-25 17:21:41.396  1034  1960 W ActivityManager: Spurious death for ProcessRecord{3ff403af 6715:com.test.thalitest/u0a118}, curProc for 6715: null
08-25 17:21:41.396  8163  8163 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 17:21:41.396  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 17:21:41.398  8163  8163 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 17:21:41.399  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{3c8d1141 u0 com.test.thalitest/.MainActivity t6 f}
08-25 17:21:41.399  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{3c8d1141 u0 com.test.thalitest/.MainActivity t6 f}
08-25 17:21:41.405  8163  8163 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-25 17:21:41.425  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-25 17:21:41.432  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 17:21:41.433  3778  3778 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-25 17:21:41.437  2447  2639 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 17:21:41.438  4458  4458 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 17:21:41.438  4458  4458 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 17:21:41.439  4458  4458 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 17:21:41.439  4458  4458 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 17:21:41.439  4458  4458 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:21:41.439  4458  4458 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:21:41.439  4458  4458 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:41.439  7655  7655 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 17:21:41.439  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 17:21:41.439  4458  4458 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:21:41.439  4458  4458 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:41.439  4458  4458 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-25 17:21:41.439  4458  4458 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:41.440  4458  4458 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 17:21:41.456  1034  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 17:21:41.471  4566  4566 I art     : Explicit concurrent mark sweep GC freed 8193(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 546us total 65.648ms
08-25 17:21:41.481  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-25 17:21:41.490  1034  1104 W InputMethodInfo: Duplicated subtype definition found: , voice
08-25 17:21:41.500  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:21:41.500  8086  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 17:21:41.508  1034  1034 D administrator: Handling package changes for user 0
08-25 17:21:41.521  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-25 17:21:41.522  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 17:21:41.523  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{64890f8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 17:21:41.524  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 17:21:41.525  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{20e179d1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 17:21:41.529  8086  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-25 17:21:41.532  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 17:21:41.533  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-25 17:21:41.536  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:41.545  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.547  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 17:21:41.547  2034  2104 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-25 17:21:41.548  1603  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 17:21:41.548  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.551  1603  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 17:21:41.551  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.551  8086  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-25 17:21:41.552  8086  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 17:21:41.553  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-25 17:21:41.553  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-25 17:21:41.554  3778  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 17:21:41.555  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 17:21:41.555  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-25 17:21:41.558  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-25 17:21:41.565  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 17:21:41.566  1603  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:21:41.567  8086  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 17:21:41.567  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-25 17:21:41.569  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 17:21:41.573  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 17:21:41.574  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:21:41.574  1603  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 17:21:41.575  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-25 17:21:41.579  1603  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 17:21:41.579  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.580  8086  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-25 17:21:41.580  8086  8157 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-25 17:21:41.583  8086  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-25 17:21:41.585  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-25 17:21:41.585  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:41.586  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:21:41.586  1603  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 17:21:41.590  1603  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 17:21:41.590  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.590  8086  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-25 17:21:41.596  1603  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:21:41.596  1603  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 17:21:41.597  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 17:21:41.597  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 17:21:41.598  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:21:41.598  1603  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 17:21:41.602  1603  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 17:21:41.602  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.607  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-25 17:21:41.607  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 17:21:41.609  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-25 17:21:41.609  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.609  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:41.609  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 17:21:41.609  3778  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 17:21:41.612  3778  4452 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 17:21:41.614  1034  1961 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:21:41.614  1034  1961 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:21:41.617  1603  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 17:21:41.617  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , display: false
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , animation: false }
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , display: false
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , animation: false }
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , display: false
08-25 17:21:41.617  2034  2034 I GBoardWebViewUtils: , animation: false }
08-25 17:21:41.618  1034  1439 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:41.618  1034  1439 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:41.618  1034  1439 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:41.619  1034  1439 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:41.619  1034  1439 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:41.619  1603  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 17:21:41.619  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.619  1034  1439 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 17:21:41.621  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-25 17:21:41.622  1871  1871 D SplitUIService: removed split : 
08-25 17:21:41.623 , 1034  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-25 17:21:41.623  1034  1540 D ConnectivityService: identical MTU - not setting
08-25 17:21:41.623  1034  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 17:21:41.623  1034  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 17:21:41.623  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 17:21:41.623  1034  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:41.624  1034  1540 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 17:21:41.624  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 17:21:41.627  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:21:41.627  1603  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-25 17:21:41.628  1603  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 17:21:41.628  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.629  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:21:41.629  1603  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 17:21:41.630  1603  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 17:21:41.630  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.631  8163  8163 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 17:21:41.632  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 17:21:41.632  1603  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 17:21:41.636  1603  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,08-25 17:21:41.636  1603  1651 D KeyguardModel: createShortcutInfo...
08-25 17:21:41.639  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 17:21:41.639  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-25 17:21:41.641  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 17:21:41.674  1034  2032 V SIM_STK : Menu title from STK is T-Mobile
08-25 17:21:41.682  1034  1755 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 17:21:41.683  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 17:21:41.683  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 17:21:41.684  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 17:21:41.685  2034  8217 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 17:21:41.689  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-25 17:21:41.689  1871  1871 I SplitUIService: split app #11
,08-25 17:21:41.701  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 17:21:41.701  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 17:21:41.702  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 17:21:41.705  1034  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 17:21:41.705  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-25 17:21:41.705  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 17:21:41.708  6797  6797 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 17:21:41.718  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-25 17:21:41.724  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:21:41.724  8086  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 17:21:41.728  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:41.739  2034  2049 I art     : Background partial concurrent mark sweep GC freed 7017(319KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 10.937ms total 30.655ms
08-25 17:21:41.742  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 17:21:41.752  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.752  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.752  8163  8163 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:41.754  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 17:21:41.754  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 17:21:41.754  6797  6797 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 17:21:41.754  6797  6797 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 17:21:41.757  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 17:21:41.757  6797  6797 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 17:21:41.757  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 17:21:41.757  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 17:21:41.757  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 17:21:41.757  6797  6797 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 17:21:41.757  6797  6797 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 17:21:41.758  6797  6797 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 17:21:41.759   328   395 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-25 17:21:41.760  3215  8220 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-25 17:21:41.761  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:41.761  8086  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 17:21:41.764  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:41.770  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.774  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.774  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.774  8163  8163 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:41.777  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:41.777  8086  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 17:21:41.783  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:41.797  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.806  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.807  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 17:21:41.807  8163  8163 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:41.808  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-25 17:21:41.810  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:21:41.812  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 17:21:41.813  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:41.814  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 17:21:41.815  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 17:21:41.816  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 17:21:41.833  2034  2233 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 17:21:41.833  2034  2233 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-25 17:21:41.833  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 17:21:41.833  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 17:21:41.834  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:41.835  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{368f2558 u0 com.lge.launcher2/.Launcher t5} time:212248
08-25 17:21:41.848  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-25 17:21:41.849  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 17:21:41.849  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:21:41.849  1034  1122 I art     : Explicit concurrent mark sweep GC freed 84363(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.736ms total 290.551ms
08-25 17:21:41.851  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.854  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.854  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.854  8163  8163 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:41.856  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:41.859  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:41.859  1034  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 17:21:41.860  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-25 17:21:41.861  2597  2597 D [Concierge]Service: onStartCommand(). Type : 8
08-25 17:21:41.861  2597  2597 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-25 17:21:41.862  2597  2597 D [Concierge]Service: Update widget ID : 11
08-25 17:21:41.863  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.864  2034  2034 D [Concierge]WidgetView: change position of spinner
08-25 17:21:41.884  8161  8161 D AndroidRuntime: Shutting down VM
,08-25 17:21:41.894  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472138501894
08-25 17:21:41.894  2597  2597 D [Concierge]Service: onStartCommand(). Type : 0
08-25 17:21:41.895  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.895  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.895  8163  8163 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 17:21:41.901  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:21:41.905  1034  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 17:21:41.909  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:41.912  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.916  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.916  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.919  8163  8163 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 17:21:41.921  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:21:41.925  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:41.925  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 927309908
08-25 17:21:41.926  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-25 17:21:41.926  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 17:21:41.927  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.928  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@dc5fa10
08-25 17:21:41.928  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-25 17:21:41.929  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 17:21:41.929  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:21:41.932  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.932  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.932  8163  8163 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 17:21:41.934  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:41.935  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 17:21:41.936  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 17:21:41.936  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 17:21:41.936  8033  8033 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 17:21:41.936  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472138317690, New one : 1472138501894
08-25 17:21:41.936  2034  2034 D [Concierge]WidgetView: Unregister all receivers
,08-25 17:21:41.937  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 17:21:41.937  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 17:21:41.938  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:21:41.938  8033  8033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 17:21:41.939  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 17:21:41.940  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 17:21:41.941  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 17:21:41.941  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-25 17:21:41.942  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.942  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 17:21:41.943  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 17:21:41.947  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:21:41.947  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:21:41.950  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.950  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.951  8163  8163 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 17:21:41.951  8163  8163 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 17:21:41.951  8163  8163 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 17:21:41.953  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 17:21:41.956  8033  8033 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 17:21:41.956  8033  8033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 17:21:41.958  6797  6797 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 17:21:41.961  6797  6797 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 17:21:41.964  8163  8163 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 17:21:41.965  8163  8163 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 17:21:41.965  8163  8163 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 17:21:41.966  8163  8163 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 17:21:41.966  8163  8163 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 17:21:41.970  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 17:21:41.976  8163  8163 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 17:21:41.977  8163  8163 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 17:21:41.977  8163  8163 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 17:21:41.983  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-25 17:21:41.991  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 17:21:41.992  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-25 17:21:41.994  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 17:21:41.997  8163  8163 D LgDataFeature: LgDataFeature() Constructor: none
08-25 17:21:41.997  8163  8163 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 17:21:42.003  8163  8163 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 17:21:42.004  8163  8163 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 17:21:42.004  8163  8163 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 17:21:42.004  8163  8163 V SoundPool: doLoad: loading sample sampleID=1
08-25 17:21:42.004  8163  8163 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 17:21:42.004  8163  8228 V SoundPool: Start decode
08-25 17:21:42.004  8163  8228 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 17:21:42.005   318  2208 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 17:21:42.005   318  2208 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 17:21:42.005   318  2208 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 17:21:42.005   318  2208 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 17:21:42.005   318  2208 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 17:21:42.005   318  2208 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 17:21:42.005   318  2208 V MediaPlayerService: player type = 3
08-25 17:21:42.005   318  2208 V AwesomePlayer: AwesomePlayer create()
08-25 17:21:42.005   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:42.005   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:42.005   318  2208 V AwesomePlayer: setAudioSink() 
08-25 17:21:42.005   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:42.005   318  2208 V AudioCache: notify(0xb1432f80, 8, 0, 0)
08-25 17:21:42.005   318  2208 V AudioCache: ignored
08-25 17:21:42.005   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:42.005   318  2208 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 17:21:42.005   318  2208 V AwesomePlayer: setDataSource_l dataSource
08-25 17:21:42.005   318  2208 V LGParserOSAL: SniffLGParser start
08-25 17:21:42.005   318  2208 V LGParserOSAL: MainType:5, SubType=0
08-25 17:21:42.005   318  2208 V LGParserOSAL: #### check Mime : application/ogg
08-25 17:21:42.005   318  2208 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 17:21:42.005   318  2208 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 17:21:42.006  8163  8163 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 17:21:42.007  8163  8163 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 17:21:42.007  8163  8163 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 17:21:42.010  7565  7565 D UEI.SmartControl: QS Service created
,08-25 17:21:42.013  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f008075 time:212426
08-25 17:21:42.013  8163  8163 V LGMDMManager: Create singleton instance
08-25 17:21:42.020  7565  7565 I UEI.SmartControl: Service initServices...
08-25 17:21:42.020  7565  7565 D UEI.SmartControl: QS start get config
08-25 17:21:42.031   318  2208 V LGParserOSAL: supported mime: application/ogg
,08-25 17:21:42.031   318  2208 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 17:21:42.031   318  2208 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 17:21:42.031   318  2208 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 17:21:42.031   318  2208 V AwesomePlayer: AudioTrack Setting
08-25 17:21:42.031   318  2208 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 17:21:42.031   318  2208 V AwesomePlayer: setAudioSource() 
08-25 17:21:42.031   318  2208 V MediaPlayerService: prepare
08-25 17:21:42.031   318  2208 V AwesomePlayer: prepareAsync_l() 
08-25 17:21:42.031   318  2208 V MediaPlayerService: wait for prepare
08-25 17:21:42.032   318  8229 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 17:21:42.032   318  8229 V AwesomePlayer: initAudioDecoder() 
08-25 17:21:42.032   318  8229 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 17:21:42.032   318  8229 V AudioSystem: isOffloadSupported()
08-25 17:21:42.032   318  8229 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 17:21:42.032   318  8229 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 17:21:42.032   318  8229 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 17:21:42.032   318  8229 V AwesomePlayer: getUseOffload() = 0 
08-25 17:21:42.032   318  8229 V OMXCodec: OMXCodec::Create
08-25 17:21:42.032   318  8229 V OMXCodec: findMatchingCodecs()
08-25 17:21:42.032   318  8229 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 17:21:42.032   318  8229 V OMXCodec: matchingCodecs.size()=1
08-25 17:21:42.032   318  8229 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 17:21:42.033   318  8229 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 17:21:42.033   318  8229 V LGCodecAdapter: LG Codec Adapter start
08-25 17:21:42.033   318  8229 V OMXCodec: OMXCodec Createtor
08-25 17:21:42.033   318  8229 V OMXCodec: setComponentRole
08-25 17:21:42.033   318  8229 V OMXCodec: configureCodec protected=0
08-25 17:21:42.033   318  8229 V LGCodecAdapter: called getLGCodecSpecificData
08-25 17:21:42.033   318  8229 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 17:21:42.033   318  8229 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 17:21:42.033   318  8229 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 17:21:42.033   318  8229 V LGCodecOSAL: Not support LGCodec
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 17:21:42.033   318  8229 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 17:21:42.033   318  8229 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 17:21:42.033   318  8229 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 17:21:42.033   318  8229 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 17:21:42.033   318  8229 V AudioSystem: isOffloadSupported()
08-25 17:21:42.033   318  8229 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 17:21:42.033   318  8229 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 17:21:42.033   318  8229 V OMXCodec: init()
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 17:21:42.033   318  8229 V OMXCodec: allocate,Buffers
08-25 17:21:42.033   318  8229 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-25 17:21:42.033   318  8229 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 17:21:42.033   318  8229 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-25 17:21:42.033   318  8229 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 17:21:42.036   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 17:21:42.036   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 17:21:42.036   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 17:21:42.036   318  8229 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 17:21:42.036   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 17:21:42.036   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 17:21:42.036   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 17:21:42.036   318  8229 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 17:21:42.036   318  8229 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 17:21:42.036   318  8229 V AudioCache: notify(0xb1432f80, 5, 0, 0)
08-25 17:21:42.036   318  8229 V AudioCache: ignored
08-25 17:21:42.036   318  8229 V AudioCache: notify(0xb1432f80, 1, 0, 0)
08-25 17:21:42.036   318  8229 V AudioCache: prepared
08-25 17:21:42.036   318  2208 V AudioCache: wait - success
08-25 17:21:42.036   318  2208 V MediaPlayerService: start
08-25 17:21:42.036   318  2208 V AwesomePlayer: play_l() 
08-25 17:21:42.036   318  2208 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 17:21:42.036   318  2208 V AwesomePlayer: createAudioPlayer_l
08-25 17:21:42.036   318  2208 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 17:21:42.036   318  2208 V AwesomePlayer: startAudioPlayer_l() 
08-25 17:21:42.036   318  2208 D AudioPlayer: start of Playback, useOffload 0
08-25 17:21:42.036   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 17:21:42.036   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25, 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 17:21:42.038   318  8231 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb00 on output port
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 17:21:42.038   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 17:21:42.039   318  2208 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 17:21:42.039   318  2208 V AudioCache: notify(0xb1432f80, 6, 0, 0)
08-25 17:21:42.039   318  2208 V AudioCache: ignored
08-25 17:21:42.039   318  2208 V MediaPlayerService: wait for playback complete
08-25 17:21:42.040   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.040   318  8232 V AudioCache: memcpy(0xb0457000, 0xb16ac000, 4096)
08-25 17:21:42.041   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.041   318  8232 V AudioCache: memcpy(0xb0458000, 0xb16ac000, 4096)
08-25 17:21:42.041   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.041   318  8232 V AudioCache: memcpy(0xb0459000, 0xb16ac000, 4096)
08-25 17:21:42.042   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.042   318  8232 V AudioCache: memcpy(0xb045a000, 0xb16ac000, 4096)
08-25 17:21:42.042   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.042   318  8232 V AudioCache: memcpy(0xb045b000, 0xb16ac000, 4096)
08-25 17:21:42.042   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.042   318  8232 V AudioCache: memcpy(0xb045c000, 0xb16ac000, 4096)
08-25 17:21:42.043   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.043   318  8232 V AudioCache: memcpy(0xb045d000, 0xb16ac000, 4096)
08-25 17:21:42.043   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.043   318  8232 V AudioCache: memcpy(0xb045e000, 0xb16ac000, 4096)
08-25 17:21:42.044   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.044   318  8232 V AudioCache: memcpy(0xb045f000, 0xb16ac000, 4096)
08-25 17:21:42.044   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.044   318  8232 V AudioCache: memcpy(0xb0460000, 0xb16ac000, 4096)
08-25 17:21:42.044   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.044   318  8232 V AudioCache: memcpy(0xb0461000, 0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: memcpy(0xb0462000, 0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: memcpy(0xb0463000, 0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: memcpy(0xb0464000, 0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.045   318  8232 V AudioCache: memcpy(0xb0465000, 0xb16ac000, 4096)
08-25 17:21:42.046   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.046   318  8232 V AudioCache: memcpy(0xb0466000, 0xb16ac000, 4096)
08-25 17:21:42.046   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.046   318  8232 V AudioCache: memcpy(0xb0467000, 0xb16ac000, 4096)
08-25 17:21:42.047   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.047   318  8232 V AudioCache: memcpy(0xb0468000, 0xb16ac000, 4096)
08-25 17:21:42.047   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.047   318  8232 V AudioCache: memcpy(0xb0469000, 0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: memcpy(0xb046a000, 0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: memcpy(0xb046b000, 0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: memcpy(0xb046c000, 0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.048   318  8232 V AudioCache: memcpy(0xb046d000, 0xb16ac000, 4096)
08-25 17:21:42.049   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.049   318  8232 V AudioCache: memcpy(0xb046e000, 0xb16ac000, 4096)
08-25 17:21:42.049   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.049   318  8232 V AudioCache: memcpy(0xb046f000, 0xb16ac000, 4096)
08-25 17:21:42.050   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.050   318  8232 V AudioCache: memcpy(0xb0470000, 0xb16ac000, 4096)
08-25 17:21:42.050   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.050   318  8232 V AudioCache: memcpy(0xb0471000, 0xb16ac000, 4096)
08-25 17:21:42.050   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.050   318  8232 V AudioCache: memcpy(0xb0472000, 0xb16ac000, 4096)
08-25 17:21:42.051   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.051   318  8232 V AudioCache: memcpy(0xb0473000, 0xb16ac000, 4096)
08-25 17:21:42.051   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.051   318  8232 V AudioCache: memcpy(0xb0474000, 0xb16ac000, 4096)
08-25 17:21:42.052   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.052   318  8232 V AudioCache: memcpy(0xb0475000, 0xb16ac000, 4096)
08-25 17:21:42.052   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.052   318  8232 V AudioCache: memcpy(0xb0476000, 0xb16ac000, 4096)
08-25 17:21:42.052   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.052   318  8232 V AudioCache: memcpy(0xb0477000, 0xb16ac000, 4096)
08-25 17:21:42.053   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.053   318  8232 V AudioCache: memcpy(0xb0478000, 0xb16ac000, 4096)
08-25 17:21:42.053   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.053   318  8232 V AudioCache: memcpy(0xb0479000, 0xb16ac000, 4096)
08-25 17:21:42.053   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.053   318  8232 V AudioCache: memcpy(0xb047a000, 0xb16ac000, 4096)
08-25 17:21:42.054   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.054   318  8232 V AudioCache: memcpy(0xb047b000, 0xb16ac000, 4096)
08-25 17:21:42.054   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.054   318  8232 V AudioCache: memcpy(0xb047c000, 0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: memcpy(0xb047d000, 0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: memcpy(0xb047e000, 0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: memcpy(0xb047f000, 0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.055   318  8232 V AudioCache: memcpy(0xb0480000, 0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: memcpy(0xb0481000, 0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: memcpy(0xb0482000, 0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: memcpy(0xb0483000, 0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.056   318  8232 V AudioCache: memcpy(0xb0484000, 0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: memcpy(0xb0485000, 0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: memcpy(0xb0486000, 0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: memcpy(0xb0487000, 0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: write(0xb16ac000, 4096)
08-25 17:21:42.057   318  8232 V AudioCache: memcpy(0xb0488000, 0xb16ac000, 4096)
08-25 17:21:42.057  8163  8163 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 17:21:42.057   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 17:21:42.057   318  8232 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 17:21:42.057   318  8232 V AwesomePlayer: postAudioEOS() 
08-25 17:21:42.057   318  8232 V AudioCache: write(0xb16ac000, 280)
08-25 17:21:42.057   318  8232 V AudioCache: memcpy(0xb0489000, 0xb16ac000, 280)
08-25 17:21:42.057  8163  8163 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 17:21:42.058  8163  8163 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2400
08-25 17:21:42.059   318  8229 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 17:21:42.059   318  8229 V AwesomePlayer: onStreamDone
08-25 17:21:42.059   318  8229 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 17:21:42.059   318  8229 V AudioCache: notify(0xb1432f80, 2, 0, 0)
08-25 17:21:42.059   318  8229 V AudioCache: playback complete
08-25 17:21:42.059   318  8229 V AwesomePlayer: pause_l() 
08-25 17:21:42.059   318  8229 V AudioCache: notify(0xb1432f80, 7, 0, 0)
08-25 17:21:42.059   318  8229 V AudioCache: ignored
08-25 17:21:42.059   318  8229 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:42.059   318  2208 V AudioCache: wait - success
08-25 17:21:42.059   318  2208 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 17:21:42.059   318  8229 D AudioPlayer: Pause Playback at 1068125
08-25 17:21:42.060   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:42.060   318  2208 V AudioCache: notify(0xb1432f80, 8, 0, 0)
08-25 17:21:42.060   318  2208 V AudioCache: ignored
08-25 17:21:42.060   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:42.060   318  2208 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 17:21:42.060   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 17:21:42.060   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 17:21:42.060   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 17:21:42.060   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 17:21:42.060  8086  8086 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fb00 on port 1
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 17:21:42.060   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 17:21:42.061   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 17:21:42.061   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 17:21:42.061   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 17:21:42.061   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 17:21:42.061   318  8231 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 17:21:42.061   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 17:21:42.061   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 17:21:42.061   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 17:21:42.062   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 17:21:42.062   318  2208 D AudioPlayer: AudioPlayer releasing audio source
08-25 17:21:42.062   318  2208 D AudioPlayer: AudioPlayer done releasing audio source
08-25 17:21:42.062   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:42.062   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:42.062   318  2208 V AwesomePlayer: ~AwesomePlayer call
08-25 17:21:42.062   318  2208 V AwesomePlayer: reset_l() 
08-25 17:21:42.062   318  2208 V AwesomePlayer: cancelPlayerEvents
08-25 17:21:42.062  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-25 17:21:42.062  8163  8228 V SoundPool: close(31)
08-25 17:21:42.062  8163  8228 V SoundPool: pointer = 0xa0038000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 17:21:42.067  2155  2155 I ConfigService: onCreate
08-25 17:21:42.068  2155  2155 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 17:21:42.069  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-25 17:21:42.071  2155  2155 I ConfigService: onBind returning update interface
08-25 17:21:42.071  2155  2155 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 17:21:42.072  2155  2155 I ConfigService: onBind returning config service
08-25 17:21:42.090  2155  2155 I ConfigService: onDestroy
,08-25 17:21:42.092  1818  8234 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 17:21:42.121  1034  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8236 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 17:21:42.145  5943  8257 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-25 17:21:42.150  1818  8259 I PeopleContactsSync: CP2 sync disabled
08-25 17:21:42.169  1818  4739 I Icing   : doRemovePackageData com.test.thalitest
,08-25 17:21:42.171  1818  8258 W GmsApplication: Using Auth Proxy for data requests.
08-25 17:21:42.183  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-25 17:21:42.197  1818  8258 W GmsApplication: Using Auth Proxy for data requests.
,08-25 17:21:42.224  2034  2900 I GBoardtInterface: onReloaded()
,08-25 17:21:42.225  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-25 17:21:42.226  3778  4452 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-25 17:21:42.228  3778  3794 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 17:21:42.233  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-25 17:21:42.234  3778  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 17:21:42.234  3778  4451 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 17:21:42.236  1906  1906 D ActionManagerService: notifyUserLog: 1000001
,08-25 17:21:42.237  3778  4451 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 17:21:42.237  3778  4451 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 17:21:42.237  3778  4451 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-25 17:21:42.237  3778  4451 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-25 17:21:42.238  3778  4452 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 17:21:42.239  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-25 17:21:42.239  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-25 17:21:42.241  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-25 17:21:42.241  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 17:21:42.242  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-25 17:21:42.242  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-25 17:21:42.323  7001  7001 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-25 17:21:42.330  2155  2174 I art     : Explicit concurrent mark sweep GC freed 7789(475KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 530us total 17.679ms
,08-25 17:21:42.338  2336  8263 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-25 17:21:42.355  1034  1755 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8264 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 17:21:42.366  2336  8263 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-25 17:21:42.367  2336  8263 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 17:21:42.367  2336  8263 E AndroidRuntime: Process: android.process.acore, PID: 2336
08-25 17:21:42.367  2336  8263 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:42.367  2336  8263 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:21:42.369  2336  8263 I Process : Sending signal. PID: 2336 SIG: 9
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: Can't write: system_app_crash
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 17:21:42.371  1034  8280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-2,5 17:21:42.371  1034  8280 E DropBoxManagerService: 	... 5 more
08-25 17:21:42.397  1818  8251 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-25 17:21:42.397  1818  8251 E DriveAsyncService: disk I/O error (code 3850)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:42.397  1818  8251 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 17:21:42.409  8264  8264 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 17:21:42.409  8264  8264 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 17:21:42.410  8264  8264 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 17:21:42.410  8264  8264 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 17:21:42.414  7565  7565 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac2: open failed: EROFS (Read-only file system)
08-25 17:21:42.415  7565  7565 I UEI.SmartControl: Specific region DB is not found, use default...
08-25 17:21:42.432  4458  4508 E SQLiteLog: (2570) os_unix.c:31441: (30) unlink(/mpt/MPT_CommonData.db-journal) - 
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: Error inserting f004=20 f005=2336 f002=1472138502401 f003= f006=-1
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:42.433  4458  4508 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
,08-25 17:21:42.437  7565  7565 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
08-25 17:21:42.437  7565  7565 I UEI.SmartControl: Supports setup maps: true
08-25 17:21:42.437  7565  7565 W System.err: java.lang.NullPointerException: Attempt to get length of null array
08-25 17:21:42.438  7565  7565 W System.err: 	at com.uei.control.core.ab.b(Unknown Source)
08-25 17:21:42.438  7565  7565 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-25 17:21:42.438  7565  7565 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-25 17:21:42.438  7565  7565 W System.err: 	at com.uei.control.Service.a(Unknown Source)
08-25 17:21:42.438  7565  7565 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
08-25 17:21:42.438  7565  7565 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-25 17:21:42.438  7565  7565 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-25 17:21:42.438  7565  7565 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-25 17:21:42.438  7565  7565 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:42.438  7565  7565 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:42.438  7565  7565 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:21:42.438  7565  7565 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:42.438  7565  7565 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:21:42.438  7565  7565 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:42.438  7565  7565 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-25 17:21,:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 17:21:42.439  7565  7565 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 17:21:42.439  7565  7565 I UEI.SmartControl: ### init IR Blaster...
08-25 17:21:42.442  7565  7565 D serial_port: Configuring serial port
08-25 17:21:42.442  7565  7565 E UEI.SmartControl: UEIBLaster setting for 616
08-25 17:21:42.442  7565  7565 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 17:21:42.442  7565  7565 I UEI.SmartControl: configuring settings for MAXQ616
08-25 17:21:42.442  7565  7565 I UEI.SmartControl: Get version...
08-25 17:21:42.446  1034  2010 I ActivityManager: Process android.process.acore (pid 2336) has died
08-25 17:21:42.446  1034  2010 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
08-25 17:21:42.446  1034  2010 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms

```
