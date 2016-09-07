#### Test 83627337941f206_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-07 12:34:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:34:00.095  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:34:00.102  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:34:00.102  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:34:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:34:00.103  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:34:06.541  6606  6606 D AndroidRuntime: 
09-07 12:34:06.541  6606  6606 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 12:34:06.544  6606  6606 D AndroidRuntime: CheckJNI is OFF
09-07 12:34:06.670  6606  6606 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 12:34:06.675  1044  1887 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 12:34:06.684  1925  1942 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-07 12:34:06.687  1044  1887 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-07 12:34:06.689  1044  1887 D ActivityManager: setTaskToReturnTo : TaskRecord{364d6749 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 12:34:06.689  1044  1887 D ActivityManager: setTaskToReturnTo : TaskRecord{364d6749 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 12:34:06.690  1044  1887 D WindowStateEx: AppWindowTokenEx init.. 
09-07 12:34:06.691   340   350 E GBMv2   : DFP En is all cleared set to be enabled
09-07 12:34:06.710  1044  1887 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6621 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 12:34:06.711  6606  6606 D AndroidRuntime: Shutting down VM
09-07 12:34:06.758  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-07 12:34:06.758  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{38683367 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 12:34:06.759  1925  2924 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-07 12:34:06.759  1925  2924 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2cb17514 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 12:34:06.807  6621  6621 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 12:34:06.864  6621  6621 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-07 12:34:06.870  6621  6621 I LibraryLoader: Loading: webviewchromium
09-07 12:34:06.872  6621  6621 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5908-5911)
09-07 12:34:06.872  6621  6621 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:34:06.888  6621  6621 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3823f0ad}
09-07 12:34:06.889  6621  6621 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:34:06.889  6621  6621 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 12:34:06.899  6621  6621 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 12:34:06.899  6621  6621 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 12:34:06.922  6621  6621 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-07 12:34:06.923  6621  6621 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-07 12:34:06.923  6621  6621 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,09-07 12:34:06.933   319   319 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
09-07 12:34:06.944  1044  1119 D BluetoothManagerService: Message: 20
09-07 12:34:06.944  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f3e618b:true
,09-07 12:34:06.952  6621  6621 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 12:34:06.952  6621  6621 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 12:34:06.952  6621  6621 I Adreno-EGL: Build Date: 12/12/14 금
09-07 12:34:06.952  6621  6621 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 12:34:06.952  6621  6621 I Adreno-EGL: Remote Branch: 
09-07 12:34:06.952  6621  6621 I Adreno-EGL: Local Patches: 
09-07 12:34:06.952  6621  6621 I Adreno-EGL: Reconstruct Branch: 
09-07 12:34:07.048  6621  6667 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-07 12:34:07.058  6621  6621 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-07 12:34:07.084  6621  6621 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 12:34:07.089  6621  6621 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 12:34:07.093  6621  6621 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 12:34:07.096  6621  6621 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 12:34:07.096  6621  6621 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-07 12:34:07.113  6621  6621 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-07 12:34:07.121  6621  6621 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 12:34:07.121  6621  6621 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 12:34:07.146  6621  6683 D OpenGLRenderer: Render dirty regions requested: true
,09-07 12:34:07.147  6621  6683 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 12:34:07.164  6621  6683 D OpenGLRenderer: Enabling debug mode 0
,09-07 12:34:07.175  6621  6621 D Atlas   : Validating map...
,09-07 12:34:07.184  1044  1888 D SplitWindow: check instance of lgWin Window{21fe0c2d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 12:34:07.235  6621  6681 D LgDataFeature: LgDataFeature() Constructor: none
09-07 12:34:07.235  6621  6681 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 12:34:07.362  1044  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +605ms (total +670ms)
09-07 12:34:07.363  6621  6621 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7a4b360 time:166402
,09-07 12:34:07.364  1044  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1fe3684e u0 com.test.thalitest/.MainActivity t6} time:166403
09-07 12:34:07.486  6621  6621 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-07 12:34:07.486  6621  6621 I chromium: 
,09-07 12:34:07.541  6621  6621 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 12:34:07.683  6621  6697 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435182080
,09-07 12:34:07.697  6621  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 12:34:07.697  6621  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 12:34:07.697  6621  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 12:34:07.697  6621  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 12:34:07.697  6621  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 12:34:07.697  6621  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3df51a24 added. We now have 1 listener(s)
09-07 12:34:07.703  1044  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:34:07.707  6621  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-07 12:34:07.708  6621  6697 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:34:07.710  6621  6697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 12:34:07.710  6621  6697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 12:34:07.718  6621  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38161353 added. We now have 1 listener(s)
09-07 12:34:07.719  6621  6697 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:34:07.726  1044  1528 D WifiService: New client listening to asynchronous messages
,09-07 12:34:07.731  6621  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:34:07.731  6621  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 12:34:07.731  6621  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 12:34:07.732  6621  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 12:34:07.732  6621  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 12:34:07.736  6621  6697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:34:07.738  1044  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:34:07.739  6621  6697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,09-07 12:34:07.748   340   352 E GBMv2   : DFP En is all cleared set to be enabled
09-07 12:34:07.748   340   352 E GBMv2   : Set value is all cleared set the max
09-07 12:34:07.748   340   352 I GBMv2   : DFP Enabled. Ignore VFP set
09-07 12:34:07.750  6621  6697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:34:07.750  6621  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:34:07.750  6621  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 12:34:07.751  6621  6697 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:34:07.754  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:34:07.756  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:34:07.757  6621  6697 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 12:34:07.805  6621  6681 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-07 12:34:07.805  6621  6681 I chromium: 
,09-07 12:34:07.874  6621  6621 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 12:34:08.619  6621  6700 W jxcore-log: Initializing JXcore engine
,09-07 12:34:08.619  6621  6700 W jxcore-log: JXcore engine is ready
,09-07 12:34:08.700  6700  6700 W Thread-772: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10270]" dev="sockfs" ino=10270 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-07 12:34:08.700  6700  6700 W Thread-772: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-07 12:34:08.700  6700  6700 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8731]" dev="sockfs" ino=8731 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 12:34:08.700  6700  6700 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-07 12:34:08.700  6700  6700 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32166]" dev="sockfs" ino=32166 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-07 12:34:08.733  6621  6700 W jxcore-log: Starting JXcore engine
,09-07 12:34:08.865  6621  6700 W jxcore-log: Platform android
09-07 12:34:08.865  6621  6700 W jxcore-log: 
09-07 12:34:08.865  6621  6700 W jxcore-log: Process ARCH arm
09-07 12:34:08.865  6621  6700 W jxcore-log: 
,09-07 12:34:09.083  6621  6700 I jxcore-log: JXcore Cordova bridge is ready!
09-07 12:34:09.083  6621  6700 I jxcore-log: 
09-07 12:34:09.083  6621  6700 W jxcore-log: JXcore engine is started
,09-07 12:34:09.090  6621  6697 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 12:34:09.092  6621  6621 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 12:34:19.043  6621  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 12:34:19.043  6621  6700 I jxcore-log: 
,09-07 12:34:19.046  6621  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 12:34:19.046  6621  6700 I jxcore-log: 
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:34:19.050  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:34:19.053  6621  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:19.055  6621  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 12:34:19.055  6621  6700 I jxcore-log: 
,09-07 12:34:19.057  6621  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 12:34:19.057  6621  6700 I jxcore-log: 
,09-07 12:34:19.561  6621  6700 I jxcore-log: Unit Test app is loaded
09-07 12:34:19.561  6621  6700 I jxcore-log: 
,09-07 12:34:19.570  6621  6621 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 12:34:19.578  6621  6700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:34:19.578  6621  6700 I jxcore-log: 
,09-07 12:34:19.594  6621  6700 D executeNativeTests: Running unit tests
,09-07 12:34:19.743  6621  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:34:19.743  6621  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 added. We now have 2 listener(s)
09-07 12:34:19.744  1044  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 12:34:19.746  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 12:34:19.746  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:34:19.746  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:34:19.746  6621  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 12:34:19.746  6621  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d added. We now have 2 listener(s)
09-07 12:34:19.746  6621  6700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:34:19.747  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:34:19.750  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:34:19.753  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:34:19.754  6621  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:19.754  6621  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:34:19.758  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:34:19.764  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:34:19.764  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:34:19.766  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:34:19.766  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:34:19.769  6621  6700 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 12:34:19.769  6621  6700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:34:19.769  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:34:19.770  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:34:19.770  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:34:19.770  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:19.770  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:19.770  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:34:19.770  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 12:34:19.771  6621  6700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 removed from the list
09-07 12:34:19.771  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:19.771  6621  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d removed from the list
09-07 12:34:19.771  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:19.771  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:19.773  6621  6700 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 12:34:19.773  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:19.773  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:19.773  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:19.773  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:19.773  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:19.773  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:19.773  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:19.773  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:19.773  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:34:19.779  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:34:19.780  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:19.780  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:19.780  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:19.780  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:19.780  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:34:19.780  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:19.780  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:19.780  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:19.780  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:19.781  6621  6700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:34:19.784  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:34:19.791  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:34:19.793  6621  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:19.793  6621  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:34:19.794  6621  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:34:19.794  6621  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:34:19.795  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:34:19.795  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:34:19.795  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:34:19.799  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:34:19.807  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:34:19.938  1044  1764 I art     : Explicit concurrent mark sweep GC freed 31094(1481KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.220ms total 141.565ms
,09-07 12:34:19.944  6621  6700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 12:34:19.945  1044  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 12:34:19.955  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 12:34:19.963  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 12:34:19.971  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 12:34:19.972  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:34:19.973  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:34:19.974  6621  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 12:34:19.975  6621  6700 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:34:22.980  6621  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 12:34:22.981  6621  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 12:34:22.982  6621  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 12:34:25.994  6621  6700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:34:25.995  6621  6700 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 12:34:25.995  6621  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:34:25.995  6621  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:34:25.995  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:34:25.995  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:34:25.996  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:34:26.019  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 12:34:26.023  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:34:26.026  6621  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:34:26.027  6621  6700 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:34:29.028  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:29.028  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:29.029  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:34:29.029  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:29.029  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:29.029  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:29.029  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:29.029  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:34:29.042  6621  6700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:34:29.045  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:34:29.051  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:34:29.052  6621  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:29.053  6621  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:34:29.055  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:34:29.056  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:34:29.057  6621  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:34:29.057  6621  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:34:29.057  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:34:29.057  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:34:29.057  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:34:29.063  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 12:34:29.065  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:34:29.067  6621  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:34:29.067  6621  6700 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:34:29.324  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 12:34:29.324  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 12:34:29.341  1925  2107 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 12:34:29.341  1925  2107 D LEDHandler: Battery Level Remaining: 100%
,09-07 12:34:29.341  1925  2107 D LEDHandler: Battery Temp: 283, mChargingStatus=5, mChargingStop=false
,09-07 12:34:29.344  1587  1587 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
09-07 12:34:29.344  1587  1587 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 12:34:29.345  1044  1528 D WifiController: battery changed pluggedType: 2
09-07 12:34:29.347  1587  1587 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 12:34:29.351  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:34:29.351  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:34:29.352  3862  3985 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 12:34:29.357  6502  6502 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 12:34:32.068  6621  6700 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 12:34:32.068  6621  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 12:34:32.068  6621  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 12:34:35.085  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.085  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.085  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:34:35.085  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.085  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.085  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.085  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.086  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:34:35.097  6621  6700 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 12:34:35.098  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.098  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.098  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.099  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.099  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.099  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.099  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.099  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.099  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.104  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:34:35.104  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.104  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.104  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.104  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.104  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.104  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.104  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.104  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.104  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.105  6621  6700 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-07 12:34:35.109  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.110  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.110  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.110  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.110  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.110  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.110  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.110  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.110  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.111  6621  6700 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 12:34:35.111  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.111  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.111  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.112  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.112  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.112  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.112  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.112  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.112  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.112  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:34:35.116  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:34:35.116  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:34:35.116  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:34:35.116  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:34:35.116  6621  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:34:35.116  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.116  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.116  6621  6700, D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.117  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.117  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.117  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.117  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.117  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.117  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.118  6621  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:34:35.118  6621  6700 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:34:35.118  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 12:34:35.123  6621  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:34:35.123  6621  6700 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-07 12:34:35.123  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:34:35.123  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:34:35.123  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:34:35.123  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:34:35.123  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
09-07 12:34:35.123  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:34:35.123  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-07 12:34:35.124  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:34:35.136  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:34:35.136  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:34:35.136  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:34:35.136  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:34:35.137  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:34:35.137  6621  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 12:34:35.137  6621  6700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:34:35.137  6621  6700 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 12:34:35.138  6621  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:34:35.138  6621  6700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:34:35.138  6621  6700 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 12:34:35.138  6621  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:34:35.140  6621  6700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:34:35.140  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-07 12:34:35.148  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 12:34:35.151  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 12:34:35.153  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 12:34:35.156  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 12:34:35.156  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 12:34:35.156  6621  6700 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 12:34:35.156  6621  6700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:34:35.156  6621  6700 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 12:34:35.157  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.157  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.157  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.157  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 12:34:35.158  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.158  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.158  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.158  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.158  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.158  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.159  6621  6700 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 12:34:35.159  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.159  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.159  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.159  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.160  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.160  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.160  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.160  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.160  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.163  6621  6707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 869
09-07 12:34:35.166  6621  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 869)
09-07 12:34:35.167  6621  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 869)
,09-07 12:34:35.170  6621  6700 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 12:34:35.172  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.172  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.172  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.172  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.172  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.172  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.172  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.172  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.172  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.173  6621  6700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 12:34:35.173  6621  6700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 12:34:35.173  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:34:35.173  6621  6700 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 12:34:35.173  6621  6700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:34:35.173  6621  6700 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 12:34:35.173  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:34:35.174  6621  6700 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 12:34:35.174  6621  6700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:34:35.174  6621  6700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:34:35.174  6621  6700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:34:35.174  6621  6700 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 12:34:35.174  6621  6700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:34:35.174  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.174  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.174  6621  6700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a471ff4 not in the list
09-07 12:34:35.174  6621  6700 I org.thaliproject.p2p.,btconnectorlib.DiscoveryManager: dispose
09-07 12:34:35.174  6621  6700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bd231d not in the list
09-07 12:34:35.174  6621  6700 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:34:35.174  6621  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:34:35.174  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:34:35.175  6621  6700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:34:35.178  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:34:35.186  6621  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:34:35.188  6621  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:34:35.188  6621  6700 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:34:35.190  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:34:35.193  6621  6621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:34:35.194  6621  6700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:34:35.194  6621  6700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:34:35.194  6621  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:34:35.194  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:34:35.194  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:34:35.200  6621  6700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:34:35.200  6621  6700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:34:35.202  6621  6700 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:34:35.203  6621  6700 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:35:00.078  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:35:00.078  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:35:00.078  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:35:00.079  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:35:00.092  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:35:00.092  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:35:00.093  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:35:00.094  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:36:00.090  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:36:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:36:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:36:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:36:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:36:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:36:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:36:00.104  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:36:18.204  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:36:18.213  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1cd01ad3 type 2 when 222089 android} when 222089
09-07 12:36:18.250  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:36:18.283  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
,09-07 12:36:56.004  1044  3540 I LocationManagerService: remove 1db5c7
09-07 12:36:56.005  1044  3540 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
09-07 12:36:56.005  1044  3540 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 12:36:56.006  1044  3540 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-07 12:36:56.008  1044  3540 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
09-07 12:36:56.009  1044  3540 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,09-07 12:37:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:37:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:37:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:37:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:37:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:37:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:37:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:37:00.104  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:37:06.906  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:37:06.955  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:37:06.984  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
,09-07 12:38:00.101  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:38:00.101  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:38:00.102  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:38:00.102  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:38:00.114  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:38:00.114  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:38:00.116  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:38:00.118  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:38:29.973  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 12:38:29.973  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 12:38:29.993  1925  2107 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 12:38:29.994  1925  2107 D LEDHandler: Battery Level Remaining: 100%
09-07 12:38:29.994  1925  2107 D LEDHandler: Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,09-07 12:38:29.996  1587  1587 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
09-07 12:38:29.996  1587  1587 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 12:38:29.999  1044  1528 D WifiController: battery changed pluggedType: 2
09-07 12:38:30.002  1587  1587 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 12:38:30.004  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:38:30.004  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:38:30.006  3862  3985 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 12:38:30.012  6502  6502 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 12:39:00.081  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:39:00.081  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:39:00.082  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:39:00.082  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:39:00.094  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:39:00.094  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:39:00.096  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:39:00.098  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:40:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:40:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:40:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:40:00.098  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:40:00.104  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:40:00.105  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:40:00.107  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:40:00.109  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:41:00.105  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:41:00.105  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:41:00.105  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:41:00.106  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:41:00.117  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:41:00.117  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:41:00.120  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:41:00.122  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:41:33.870  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 12:41:33.870  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 12:41:33.882  1925  2107 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 12:41:33.883  1925  2107 D LEDHandler: Battery Level Remaining: 100%
09-07 12:41:33.883  1925  2107 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
,09-07 12:41:33.885  1587  1587 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
09-07 12:41:33.886  1044  1528 D WifiController: battery changed pluggedType: 2
09-07 12:41:33.885  1587  1587 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 12:41:33.888  1587  1587 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 12:41:33.891  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:41:33.891  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:41:33.892  3862  3985 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 12:41:33.897  6502  6502 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-07 12:42:00.077  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:42:00.077  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:42:00.077  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:42:00.078  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:42:00.089  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:42:00.090  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:42:00.093  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
,09-07 12:42:00.096  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:43:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:43:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:43:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:43:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:43:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:43:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:43:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:43:00.105  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:43:07.817  1044  1943 I ActivityManager: Killing 6107:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-07 12:43:07.873  1044  2016 W libprocessgroup: failed to open /acct/uid_10014/pid_6107/cgroup.procs: No such file or directory
,09-07 12:44:00.090  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:44:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:44:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:44:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:44:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:44:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:44:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:44:00.104  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:45:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:45:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:45:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:45:00.098  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:45:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:45:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:45:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:45:00.105  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:45:01.999  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:45:02.062  1044  1112 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6729 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-07 12:45:02.095  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:45:02.211  6729  6729 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-07 12:45:02.215  6729  6729 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@127b5456
09-07 12:45:02.216  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
09-07 12:45:02.217  1044  1764 I ActivityManager: Killing 6216:com.android.defcontainer/u0a4 (adj 15): empty #17
09-07 12:45:02.316  1044  1887 W libprocessgroup: failed to open /acct/uid_10004/pid_6216/cgroup.procs: No such file or directory
,09-07 12:46:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:46:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:46:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:46:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:46:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:46:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:46:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:46:00.104  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:46:26.373  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:46:26.388  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ef9e610 type 2 when 905396 com.google.android.gms} when 905396
,09-07 12:46:26.426  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:46:26.453  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
,09-07 12:46:26.482  1801  1801 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 12:46:26.487  2139  2139 I ConfigService: onCreate
09-07 12:46:26.487  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 12:46:26.495  1801  6771 I ConfigFetchService: running network task: configservice_periodic
,09-07 12:46:26.498  1801  6771 I ConfigFetchService: launchTask
09-07 12:46:26.500  2139  2139 I ConfigService: onBind returning update interface
09-07 12:46:26.501  1801  1801 I ConfigFetchService: service connected
09-07 12:46:26.501  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 12:46:26.502  2139  2139 I ConfigService: onBind returning config service
09-07 12:46:26.503  1801  1801 I ConfigClient: service connected
09-07 12:46:26.581  1044  2034 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:46:26.604  1801  6773 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 12:46:26.609   315  6790 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 12:46:26.609   315  6790 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 12:46:26.704   315  6790 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 12:46:27.037  1801  6773 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 12:46:27.045  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
09-07 12:46:27.048  1801  1801 I ConfigFetchService: stopping self
09-07 12:46:27.087  1044  1379 V AlarmManager: RTC_WAKEUP set : Alarm{18255ec3 type 0 when 1473244852444 com.google.android.gms} when 1473244852444
,09-07 12:46:27.127  1801  2340 I EventLogService: Aggregate from 1473244337837 (log), 1473243052302 (data)
,09-07 12:46:27.133  2139  2139 I ConfigService: onDestroy
,09-07 12:46:57.136  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{33974279 type 2 when 936160 com.google.android.gms} when 936160
,09-07 12:46:57.196  1801  1801 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 12:46:57.201  2139  2139 I ConfigService: onCreate
09-07 12:46:57.202  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 12:46:57.210  1801  6802 I ConfigFetchService: running network task: configservice_periodic
,09-07 12:46:57.215  1801  6802 I ConfigFetchService: launchTask
09-07 12:46:57.216  2139  2139 I ConfigService: onBind returning update interface
09-07 12:46:57.217  1801  1801 I ConfigFetchService: service connected
09-07 12:46:57.217  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 12:46:57.217  2139  2139 I ConfigService: onBind returning config service
09-07 12:46:57.219  1801  1801 I ConfigClient: service connected
09-07 12:47:00.082  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:47:00.082  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:47:00.082  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:47:00.083  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:47:00.096  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:47:00.096  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:47:00.099  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
,09-07 12:47:00.105  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:47:03.919  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:47:03.928  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3717817 type 2 when 942943 com.android.bluetooth} when 942943
09-07 12:47:03.954  3862  4073 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 12:47:03.954  3862  4073 W bt-smp  : Plain text(LSB ~ MSB) = 27 25 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 12:47:03.955  3862  4073 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 b3 f9 9c 3d 3e 18 20 a9 63 50 ee f5 d1 46 d7 
09-07 12:47:03.955  3862  4073 W bt-btm  : Stopping oneshot timer
,09-07 12:47:03.968  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:47:03.993  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
,09-07 12:47:07.311  1044  1559 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:47:07.342  1801  2376 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 12:47:07.350   315  6804 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 12:47:07.351   315  6804 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 12:47:07.351   315  6804 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-07 12:47:07.638  1801  2376 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 12:47:07.648  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
09-07 12:47:07.651  1801  1801 I ConfigFetchService: stopping self
09-07 12:47:07.703  2139  2139 I ConfigService: onDestroy
,09-07 12:48:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:48:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:48:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:48:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:48:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:48:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:48:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:48:00.104  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:48:29.109  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:48:29.122  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1410bbe9 type 2 when 981110 com.google.android.gms} when 981110
09-07 12:48:29.124  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2397306e type 2 when 1006689 com.google.android.gms} when 1006689
,09-07 12:48:29.161  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:48:29.196  2139  6106 D GCM     : Message class com.google.e.a.a.h
09-07 12:48:29.231  1801  1801 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 12:48:29.237  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
09-07 12:48:29.243  2139  2139 I ConfigService: onCreate
,09-07 12:48:29.246  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 12:48:29.252  2139  2139 I ConfigService: onBind returning update interface
09-07 12:48:29.254  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 12:48:29.254  2139  2139 I ConfigService: onBind returning config service
09-07 12:48:29.266  1801  1801 I ConfigFetchService: service connected
09-07 12:48:29.267  1801  1801 I ConfigClient: service connected
,09-07 12:48:29.274  1801  6811 I ConfigFetchService: running network task: configservice_periodic
09-07 12:48:29.275  1801  6811 I ConfigFetchService: launchTask
09-07 12:48:29.323  1044  2034 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:48:29.335  1801  3997 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 12:48:29.339   315  6824 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-07 12:48:29.339   315  6824 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 12:48:29.340   315  6824 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-07 12:48:29.540  1801  3997 W ConfigFetchTask: bad response from server: 401 Unauthorized
09-07 12:48:29.542  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
,09-07 12:48:29.545  1801  1801 I ConfigFetchService: stopping self
09-07 12:48:29.587  2139  2139 I ConfigService: onDestroy
,09-07 12:49:00.079  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:49:00.080  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:49:00.080  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:49:00.087  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:49:00.093  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:49:00.093  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:49:00.094  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:49:00.095  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:50:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:50:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:50:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:50:00.098  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:50:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:50:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:50:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:50:00.105  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:50:29.561  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:50:29.575  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{19537159 type 2 when 1148584 com.google.android.gms} when 1148584
09-07 12:50:29.609  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:50:29.635  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
,09-07 12:50:29.662  1801  1801 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 12:50:29.667  2139  2139 I ConfigService: onCreate
09-07 12:50:29.668  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 12:50:29.675  1801  6837 I ConfigFetchService: running network task: configservice_periodic
,09-07 12:50:29.679  1801  6837 I ConfigFetchService: launchTask
09-07 12:50:29.679  2139  2139 I ConfigService: onBind returning update interface
09-07 12:50:29.681  1801  1801 I ConfigFetchService: service connected
09-07 12:50:29.681  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 12:50:29.681  2139  2139 I ConfigService: onBind returning config service
09-07 12:50:29.683  1801  1801 I ConfigClient: service connected
09-07 12:50:29.759  1044  1907 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:50:29.784  1801  6352 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 12:50:29.789   315  6856 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 12:50:29.789   315  6856 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 12:50:29.790   315  6856 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-07 12:50:29.986  1801  6352 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 12:50:29.989  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
09-07 12:50:29.992  1801  1801 I ConfigFetchService: stopping self
09-07 12:50:30.039  2139  2139 I ConfigService: onDestroy
,09-07 12:51:00.079  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:51:00.079  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:51:00.079  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:51:00.080  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:51:00.093  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:51:00.093  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:51:00.094  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:51:00.094  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:51:41.104  1044  1109 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 12:52:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:52:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:52:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:52:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:52:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:52:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:52:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:52:00.104  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:53:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:53:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:53:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:53:00.098  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:53:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:53:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:53:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:53:00.105  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:54:00.090  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:54:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:54:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:54:00.098  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:54:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:54:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:54:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:54:00.105  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:54:30.006  1044  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=594914083, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,09-07 12:54:30.020  1044  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{378c22d0 type 2 when 1389028 com.google.android.gms} when 1389028
09-07 12:54:30.056  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 12:54:30.083  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=594914083 [*alarm*], flags=0x0
,09-07 12:54:30.112  1801  1801 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-07 12:54:30.116  2139  2139 I ConfigService: onCreate
09-07 12:54:30.117  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 12:54:30.123  2139  2139 I ConfigService: onBind returning update interface
,09-07 12:54:30.127  2139  2139 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 12:54:30.127  2139  2139 I ConfigService: onBind returning config service
09-07 12:54:30.130  1801  1801 I ConfigFetchService: service connected
09-07 12:54:30.130  1801  1801 I ConfigClient: service connected
09-07 12:54:30.133  1801  6870 I ConfigFetchService: running network task: configservice_periodic
09-07 12:54:30.142  1801  6870 I ConfigFetchService: launchTask
,09-07 12:54:30.224  1044  2010 V SIM_STK : Menu title from STK is T-Mobile
,09-07 12:54:30.230  1801  6773 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-07 12:54:30.233   315  6887 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 12:54:30.233   315  6887 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-07 12:54:30.274   315  6887 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-07 12:54:30.550  1801  6773 W ConfigFetchTask: bad response from server: 401 Unauthorized
,09-07 12:54:30.554  1801  1801 I ConfigFetchService: fetch service done; releasing wakelock
09-07 12:54:30.555  1801  1801 I ConfigFetchService: stopping self
09-07 12:54:30.585  2139  2139 I ConfigService: onDestroy
,09-07 12:55:00.078  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:55:00.078  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:55:00.078  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 12:55:00.079  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,09-07 12:55:00.092  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:55:00.092  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:55:00.093  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:55:00.094  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:56:00.090  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:56:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:56:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-07 12:56:00.097  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
09-07 12:56:00.103  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 12:56:00.103  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:56:00.104  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
09-07 12:56:00.104  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 12:57:00.089  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 12:57:00.090  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 12:57:00.090  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
