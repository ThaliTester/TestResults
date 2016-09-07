#### Test 834440500e39eda_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-07 10:33:00.097  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 10:33:00.097  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 10:33:00.097  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-07 10:33:00.098  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
,09-07 10:33:00.112  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 10:33:00.112  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
09-07 10:33:00.115  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
09-07 10:33:00.116  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 10:33:00.433  6714  6714 D AndroidRuntime: 
09-07 10:33:00.433  6714  6714 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 10:33:00.438  6714  6714 D AndroidRuntime: CheckJNI is OFF
09-07 10:33:00.641  6714  6714 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 10:33:00.651  1043  1059 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 10:33:00.667  1925  2775 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-07 10:33:00.673  1043  1059 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-07 10:33:00.674  1043  1059 D ActivityManager: setTaskToReturnTo : TaskRecord{3fb4225f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 10:33:00.674  1043  1059 D ActivityManager: setTaskToReturnTo : TaskRecord{3fb4225f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 10:33:00.676  1043  1059 D WindowStateEx: AppWindowTokenEx init.. 
09-07 10:33:00.677   343   358 E GBMv2   : DFP En is all cleared set to be enabled
09-07 10:33:00.705  1043  1059 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6729 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 10:33:00.708  6714  6714 D AndroidRuntime: Shutting down VM
09-07 10:33:00.765  1925  3952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-07 10:33:00.765  1925  3952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{14507d4d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 10:33:00.766  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-07 10:33:00.766  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23010002 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-07 10:33:00.810  6729  6729 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 10:33:00.905  6729  6729 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-07 10:33:00.916  6729  6729 I LibraryLoader: Loading: webviewchromium
09-07 10:33:00.921  6729  6729 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4994-5000)
09-07 10:33:00.921  6729  6729 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 10:33:00.938  6729  6729 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31e99183}
,09-07 10:33:00.940  6729  6729 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 10:33:00.940  6729  6729 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 10:33:00.951  6729  6729 I BrowserStartupController: Initializing chromium process, renderers=0
,09-07 10:33:00.952  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 10:33:00.979  6729  6729 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-07 10:33:00.980  6729  6729 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,09-07 10:33:00.980  6729  6729 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-07 10:33:00.986   320  2117 V AudioPolicyService: registerClient() client 0xb558ad60, uid 10118
09-07 10:33:00.991  1043  1119 D BluetoothManagerService: Message: 20
09-07 10:33:00.992  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a6d3f1:true
,09-07 10:33:01.009  6729  6729 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:01.009  6729  6729 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:01.009  6729  6729 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:01.009  6729  6729 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:01.009  6729  6729 I Adreno-EGL: Remote Branch: 
09-07 10:33:01.009  6729  6729 I Adreno-EGL: Local Patches: 
09-07 10:33:01.009  6729  6729 I Adreno-EGL: Reconstruct Branch: 
,09-07 10:33:01.116  6729  6775 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-07 10:33:01.120  6729  6729 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-07 10:33:01.146  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 10:33:01.150  6729  6729 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 10:33:01.153  6729  6729 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 10:33:01.156  6729  6729 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 10:33:01.156  6729  6729 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 10:33:01.175  6729  6729 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-07 10:33:01.182  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 10:33:01.182  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 10:33:01.232  6729  6790 D OpenGLRenderer: Render dirty regions requested: true
09-07 10:33:01.232  6729  6790 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 10:33:01.245  6729  6790 D OpenGLRenderer: Enabling debug mode 0
,09-07 10:33:01.254  6729  6729 D Atlas   : Validating map...
09-07 10:33:01.262  1043  1906 D SplitWindow: check instance of lgWin Window{150b34e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 10:33:01.265  1043  1115 W ActivityManager: Activity pause timeout for ActivityRecord{36a5c4ac u0 com.test.thalitest/.MainActivity t6}
,09-07 10:33:01.307  6729  6788 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 10:33:01.307  6729  6788 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 10:33:01.392  1043  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +628ms (total +714ms)
09-07 10:33:01.392  1043  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36a5c4ac u0 com.test.thalitest/.MainActivity t6} time:165471
09-07 10:33:01.396  6729  6729 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d30022e time:165475
,09-07 10:33:01.575  6729  6729 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 10:33:01.644  6729  6788 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-07 10:33:01.644  6729  6788 I chromium: 
,09-07 10:33:01.772   343   363 E GBMv2   : DFP En is all cleared set to be enabled
09-07 10:33:01.773   343   363 E GBMv2   : Set value is all cleared set the max
09-07 10:33:01.773   343   363 I GBMv2   : DFP Enabled. Ignore VFP set
,09-07 10:33:01.789  6729  6804 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,09-07 10:33:01.803  6729  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 10:33:01.803  6729  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 10:33:01.803  6729  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 10:33:01.803  6729  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 10:33:01.803  6729  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 10:33:01.804  6729  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f6fcf92 added. We now have 1 listener(s)
09-07 10:33:01.809  1043  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:01.812  6729  6729 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-07 10:33:01.812  6729  6729 I chromium: 
09-07 10:33:01.812  6729  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-07 10:33:01.813  6729  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:01.815  6729  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:01.815  6729  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 10:33:01.829  6729  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17cb2219 added. We now have 1 listener(s)
09-07 10:33:01.830  6729  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:33:01.836  1043  1528 D WifiService: New client listening to asynchronous messages
09-07 10:33:01.840  6729  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:33:01.840  6729  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 10:33:01.841  6729  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 10:33:01.841  6729  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 10:33:01.841  6729  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 10:33:01.845  6729  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:01.845  1043  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:01.846  6729  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-07 10:33:01.855  6729  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:01.855  6729  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:01.855  6729  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 10:33:01.855  6729  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:01.859  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:01.862  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:01.862  6729  6804 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 10:33:01.907  6729  6729 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 10:33:03.095  6729  6807 W jxcore-log: Initializing JXcore engine
09-07 10:33:03.095  6729  6807 W jxcore-log: JXcore engine is ready
,09-07 10:33:03.163  6807  6807 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7357]" dev="sockfs" ino=7357 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-07 10:33:03.163  6807  6807 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-07 10:33:03.163  6807  6807 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8898]" dev="sockfs" ino=8898 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-07 10:33:03.163  6807  6807 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-07 10:33:03.163  6807  6807 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33828]" dev="sockfs" ino=33828 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-07 10:33:03.201  6729  6807 W jxcore-log: Starting JXcore engine
,09-07 10:33:03.362  6729  6807 W jxcore-log: Platform android
09-07 10:33:03.362  6729  6807 W jxcore-log: 
09-07 10:33:03.362  6729  6807 W jxcore-log: Process ARCH arm
09-07 10:33:03.362  6729  6807 W jxcore-log: 
,09-07 10:33:03.771  6729  6807 I jxcore-log: JXcore Cordova bridge is ready!
09-07 10:33:03.771  6729  6807 I jxcore-log: 
,09-07 10:33:03.771  6729  6807 W jxcore-log: JXcore engine is started
09-07 10:33:03.778  6729  6804 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 10:33:03.783  6729  6729 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-07 10:33:04.038  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 6747
09-07 10:33:04.038  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 6748
09-07 10:33:04.038  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 6755
09-07 10:33:04.039  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 6764
09-07 10:33:04.039  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 6808
,09-07 10:33:14.004  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 10:33:14.004  6729  6807 I jxcore-log: 
,09-07 10:33:14.007  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 10:33:14.007  6729  6807 I jxcore-log: 
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:14.011  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.014  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.016  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 10:33:14.016  6729  6807 I jxcore-log: 
09-07 10:33:14.017  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 10:33:14.017  6729  6807 I jxcore-log: 
09-07 10:33:14.524  6729  6807 D executeNativeTests: Running unit tests
,09-07 10:33:14.603  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:14.604  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 added. We now have 2 listener(s)
09-07 10:33:14.604  1043  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:14.605  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:14.605  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:14.605  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:14.606  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:14.606  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 added. We now have 2 listener(s)
09-07 10:33:14.606  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:33:14.608  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:33:14.611  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:14.613  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.614  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.614  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:14.616  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.618  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:14.619  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-07 10:33:14.620  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 10:33:14.620  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 10:33:14.622  6729  6807 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 10:33:14.623  6729  6807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 10:33:14.623  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 10:33:14.623  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 10:33:14.623  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-07 10:33:14.624  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.624  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.624  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.625  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.625  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.625  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:14.625  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:14.625  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 removed from the list
09-07 10:33:14.625  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.625  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 removed from the list
09-07 10:33:14.625  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.625  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.626  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.626  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.627  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.627  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.627  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.627  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.628  6729  6807 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 10:33:14.629  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.629  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.629  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.629  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.629  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.629  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.629  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.629  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.629  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.629  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.629  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.629  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.629  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.629  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.631  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.631  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.631  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.631  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 10:33:14.635  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 10:33:14.635  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.635  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.635  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.636  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.636  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.636  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.636  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.636  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.637  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.637  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.637  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.637  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.637  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.637  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.639  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.639  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.639  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:33:14.639  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.640  6729  6807 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 10:33:14.641  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:14.644  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.646  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.646  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:14.647  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.648  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.648  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:14.648  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:33:14.648  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:33:14.648  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.648  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:33:14.651  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:33:14.651  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:14.654  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:33:14.658  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:33:14.660  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,09-07 10:33:14.661  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:33:14.662  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:14.663  6729  6807 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 10:33:14.663  6729  6807 I io.jxcore.node.ConnectionHelper: start: OK
09-07 10:33:14.665  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.665  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.665  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.665  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.665  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.665  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:14.665  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.665  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.665  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.665  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.665  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.666  6729  6807 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 10:33:14.667  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:14.669  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.671  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.671  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:33:14.671  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:14.671  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:33:14.671  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:33:14.671  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.671  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:33:14.674  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.675  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.677  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:33:14.677  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:14.678  6729  6807 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 10:33:14.678  6729  6807 I io.jxcore.node.ConnectionHelper: start: OK
09-07 10:33:14.679  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.680  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.680  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.680  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.680  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.680  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:14.680  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.680  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.680  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.680  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.680  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.681  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.681  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.681  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.681  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.683  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.683  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.683  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.683  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.684  6729  6807 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 10:33:14.686  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:14.688  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.689  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.689  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:14.690  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.691  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.692  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:14.692  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:33:14.692  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:33:14.692  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.692  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:33:14.694  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:33:14.694  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:14.695  6729  6807 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 10:33:14.695  6729  6807 I io.jxcore.node.ConnectionHelper: start: OK
09-07 10:33:14.695  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.695  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.695  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.696  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.696  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.696  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:33:14.697  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.697  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.697  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:14.697  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.698  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.698  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.698  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.698  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.698  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.698  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.699  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.699  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.699  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.699  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.699  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.699  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.700  6729  6807 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 10:33:14.700  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.700  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.700  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.700  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.700  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.700  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.700  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.700  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.700  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.700  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.700  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.700  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.700  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.700  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.701  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.701  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.701  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.702  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.702  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.702  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.702  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 10:33:14.702  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.702  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.702  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.703  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.703  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.703  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.703  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.703  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.703  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.703  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.703  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.703  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.703  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.703  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.704  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.704  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.704  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.704  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.704  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.704  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.705  6729  6807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 10:33:14.705  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.705  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.705  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.705  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.705  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.705  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.705  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.705  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.705  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.705  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.705  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.705  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.705  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.705  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.706  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.706  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.707  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.707  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.707  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.707  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.707  6729  6807 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 10:33:14.707  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.707  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.707  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.708  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.708  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.708  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.708  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.708  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.708  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.708  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.708  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.708  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.708  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.708  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.708  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.708  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.709  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.709  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.709  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.709  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.710  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 10:33:14.713  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 10:33:14.713  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 10:33:14.713  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 10:33:14.715  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 10:33:14.715  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 10:33:14.716  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.716  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.716  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.716  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.716  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.716  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.716  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.716  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.716  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.716  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.716  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.717  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.717  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.717  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.718  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.718  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.719  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.719  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.719  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.719  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.720  6729  6807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:33:14.720  6729  6807 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 10:33:14.720  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 10:33:14.723  6729  6807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:33:14.723  6729  6807 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 10:33:14.723  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 10:33:14.724  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 10:33:14.725  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 10:33:14.725  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 10:33:14.725  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 10:33:14.725  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 10:33:14.726  6729  6807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 10:33:14.726  6729  6807 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:33:14.726  6729  6807 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 10:33:14.727  6729  6807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:33:14.727  6729  6807 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:33:14.727  6729  6807 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 10:33:14.727  6729  6807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:33:14.727  6729  6807 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:33:14.727  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 10:33:14.729  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 10:33:14.729  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 10:33:14.729  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 10:33:14.730  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 10:33:14.730  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 10:33:14.730  6729  6807 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 10:33:14.730  6729  6807 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:33:14.730  6729  6807 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 10:33:14.731  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.731  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.731  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.731  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.731  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.731  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.731  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 10:33:14.731  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.732  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.732  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.732  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.732  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.732  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.732  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.732  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.732  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.732  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.733  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.733  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.733  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.733  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.733  6729  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
09-07 10:33:14.733  6729  6807 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 10:33:14.734  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.734  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.734  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.734  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.734  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:33:14.734  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.734  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.734  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.734  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.734  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.734  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.734  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.734  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.734  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.735  6729  6824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
09-07 10:33:14.735  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.735  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.735  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.735  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.735  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.735  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.736  6729  6807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 10:33:14.736  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.736  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.736  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.736  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.736  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.736  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.736  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.736  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.736  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.736  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.736  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.736  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.736  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.737  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.737  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.737  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.738  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.738  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.738  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.738  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.738  6729  6807 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 10:33:14.738  6729  6807 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 10:33:14.739  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:33:14.739  6729  6807 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 10:33:14.739  6729  6807 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 10:33:14.739  6729  6807 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 10:33:14.739  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:33:14.739  6729  6807 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 10:33:14.739  6729  6807 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 10:33:14.739  6729  6807 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 10:33:14.739  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:33:14.739  6729  6807 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 10:33:14.739  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.739  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.739  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.739  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.739  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.739  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.739  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.739  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.739  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.739  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.739  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.739  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.739  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.739  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.740  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.740  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.741  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.741  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.741  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.741  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.741  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.742  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.742  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.742  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.742  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.742  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.742  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.742  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.742  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.742  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.742  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.742  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.742  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.742  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.742  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.742  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.742  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.742  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.742  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.742  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.742  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.742  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.742  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.742  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.742  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.742  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.742  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.742  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.742  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.744  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.744  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.744  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.744  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.744  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.744  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.746  6729  6807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 10:33:14.746  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.746  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 10:33:14.747  6729  6807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 10:33:14.747  6729  6807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 10:33:14.747  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 10:33:14.747  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 10:33:14.747  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:33:14.751  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.751  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 10:33:14.751  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 10:33:14.751  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 10:33:14.751  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.751  6729  6807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 10:33:14.752  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 10:33:14.752  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.752  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.753  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:33:14.753  6729  6807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:33:14.753  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:33:14.753  6729  6825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 10:33:14.753  6729  6825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 10:33:14.753  6729  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 10:33:14.758  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:33:14.759  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:14.759  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:14.759  6729  6807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:33:14.759  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.759  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.760  6729  6807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:33:14.760  6729  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:33:14.760  6729  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:33:14.760  6729  6729 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:33:14.761  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.761  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.761  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.761  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.761  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.761  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.761  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.761  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.761  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.761  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.761  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.761  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.761  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.761  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.761  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.762  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.762  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.762  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.762  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.763  6729  6807 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 10:33:14.763  6729  6807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 10:33:14.763  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 10:33:14.764  6729  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 10:33:14.764  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.764  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.764  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.765  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.765  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.765  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.765  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.765  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.765  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.765  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.765  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.765  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.765  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.765  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.766  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.766  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.766  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.766  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.770  1043  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:14.771  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:14.772  1043  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:14.773  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.773  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.773  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.773  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.773  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.773  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.773  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.773  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.773  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.773  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.773  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.773  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.773  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.773  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.774  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.774  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.774  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.774  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.775  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:14.775  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:14.775  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:14.775  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:14.775  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.775  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.775  6729  6807 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38f49de2 not in the list
09-07 10:33:14.775  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.775  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.775  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:14.775  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.775  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.775  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:14.775  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:14.776  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:14.776  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:14.776  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:14.776  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70e4573 not in the list
09-07 10:33:14.777  6729  6807 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 10:33:14.777  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:33:14.777  6729  6807 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 10:33:14.777  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:33:14.777  6729  6807 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 10:33:14.777  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:33:14.778  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 10:33:14.778  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 10:33:14.779  6729  6807 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 10:33:14.779  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 10:33:14.779  6729  6807 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 10:33:14.779  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 10:33:14.779  6729  6807 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 10:33:14.779  6729  6807 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 10:33:14.780  6729  6807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 10:33:14.780  6729  6807 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 10:33:14.780  6729  6807 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 10:33:14.781  6729  6807 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 10:33:14.781  6729  6807 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 10:33:14.781  6729  6807 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 10:33:14.781  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:14.781  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3073f148 added. We now have 2 listener(s)
09-07 10:33:14.782  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:14.783  6729  6807 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 10:33:14.784  1043  1870 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 10:33:14.784  1043  1870 D WifiService: setWifiEnabled: true pid=6729, uid=10118
09-07 10:33:14.784  1043  1870 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 10:33:14.785  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:14.785  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a91dbe1 added. We now have 3 listener(s)
09-07 10:33:14.785  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:14.788  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:14.788  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@321f5d06 added. We now have 4 listener(s)
09-07 10:33:14.788  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:14.789  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:14.789  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e569fc7 added. We now have 5 listener(s)
09-07 10:33:14.789  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:14.791  1043  1870 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 10:33:14.791  1043  1870 D WifiService: setWifiEnabled: false pid=6729, uid=10118
09-07 10:33:14.791  1043  1870 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:33:14.816  1043  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:14.817  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:14.817  1043  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:14.817  1043  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:14.818  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:14.818  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:14.818  1043  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 10:33:14.819  1043  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:33:14.819  1043  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 10:33:14.819  1043  1861 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:14.819  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:14.819  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-07 10:33:14.819  1043  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 10:33:14.819  1043  1861 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3a5472 mBinding = false
09-07 10:33:14.819  1043  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 10:33:14.828  6729  6822 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,09-07 10:33:14.828  6729  6822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:14.829  3845  3864 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:14.829  3845  4045 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-07 10:33:14.829  3845  3864 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
09-07 10:33:14.835  1043  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 10:33:14.835  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 10:33:14.835  2733  2733 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 10:33:14.836  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 10:33:14.836  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:14.837  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
09-07 10:33:14.837  1043  2853 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.837   315   903 D CommandListener: Clearing all IP addresses on wlan0
09-07 10:33:14.837  1043  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.837  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.846  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:14.847  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:14.847  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:14.847  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,09-07 10:33:14.849  1043  1119 D BluetoothManagerService: Message: 2
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:14.849  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.850  1043  1119 D BluetoothManagerService: Sending off request.
09-07 10:33:14.850  3845  3965 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 10:33:14.856  3845  3927 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 10:33:14.856  3845  3927 D BluetoothAdapterProperties: Setting state to 13
09-07 10:33:14.856  3845  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 10:33:14.856  3845  3927 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 10:33:14.857  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:14.857  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 10:33:14.857  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-07 10:33:14.868  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 10:33:14.868  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-07 10:33:14.872  1043  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:14.872  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:14.872  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:14.872  1043  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:14.873  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:14.873  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:14.873  1043  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 10:33:14.878  1043  1521 D LGWifiP2pService: InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.878  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.878  1043  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3540a5d9
09-07 10:33:14.879  1043  1521 D LGWifiP2pService: P2pDisablingState
09-07 10:33:14.879  1043  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.879  1043  1521 D LGWifiP2pService: p2p socket connection lost
09-07 10:33:14.879  1043  1521 D LGWifiP2pService: P2pDisabledState
,09-07 10:33:14.880  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:14.881  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 10:33:14.882  3845  3845 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:14.882  3845  3845 D BluetoothMapService: STATE_TURNING_OFF
09-07 10:33:14.882  3845  3845 V BluetoothMapService: Handler(): got msg=4
09-07 10:33:14.882  3845  3845 D BluetoothMapService: MAP Service closeService in
09-07 10:33:14.882  3845  3845 D BluetoothMapMasInstance: MAP Service shutdown
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 10:33:14.883  3845  4236 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-07 10:33:14.890  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 10:33:14.890  3845  3845 V BluetoothMapService: MAP Service closeService out
,09-07 10:33:14.891  3845  3845 V BtOppService: Receiver DISABLED_ACTION 
09-07 10:33:14.891  3845  3845 I BtOppRfcommListener: stopping Accept Thread
09-07 10:33:14.891  3845  3845 V BtOppRfcommListener: close mBtServerSocket
09-07 10:33:14.892  3845  4298 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:14.892  3845  3845 V BtOppRfcommListener: waiting for thread to terminate
09-07 10:33:14.892  3845  4298 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 10:33:14.892  3845  3845 V BtOppRfcommListener: done waiting for thread to terminate
09-07 10:33:14.893  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:14.893  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:14.894  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:14.894  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.895  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.895  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:14.896  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.897  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:14.897  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.898  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.898  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:14.8,98  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:14.914  1043  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 10:33:14.914  1043  1529 D DSQN    : disableDataServiceNotify
09-07 10:33:14.914  1043  1529 D DSQN    : stop dsqn bin
,09-07 10:33:14.920  1043  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 10:33:14.921  1043  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.921  1043  1521 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.922  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 10:33:14.922  2733  2733 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 10:33:14.923  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 10:33:14.923  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:14.926  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
09-07 10:33:14.927   315   903 D CommandListener: Clearing all IP addresses on wlan0
09-07 10:33:14.931  1043  1115 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6836 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 10:33:14.931  3845  3845 V BtOppService: onDestroy
09-07 10:33:14.932  3845  3845 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-07 10:33:14.934  1043  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 10:33:14.934  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:14.934  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:14.934  1043  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:14.934  1043  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-07 10:33:14.934  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 10:33:14.935  1043  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 10:33:14.935  1043  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 10:33:14.935  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 10:33:14.936  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-07 10:33:14.936  1043  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.936  1043  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.937  1043  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 10:33:14.938  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 10:33:14.939  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:14.939  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:14.939  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:14.941  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-07 10:33:14.947  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 10:33:14.947  1925  1925 D WfdsService: WifiP2pState is changed : false
09-07 10:33:14.947  1925  2279 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 10:33:14.947  1925  2279 D WfdsService: Set the WFDS Monitor: false
09-07 10:33:14.948  1925  2279 D WfdsMonitor: WFDS Monitor is stopped
09-07 10:33:14.948  1925  2279 D WfdsService: STATE : WfdsDisabledState - enter
09-07 10:33:14.948  1925  2765 D CtrlSupplicant: Received on exit socket, terminate
09-07 10:33:14.948  1925  2765 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 10:33:14.948  1925  2765 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 10:33:14.948  1925  2765 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 10:33:14.948  1925  2280 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
0,9-07 10:33:14.948  1925  2279 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 10:33:14.949  1043  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 10:33:14.950  1043  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:14.950  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 10:33:14.950  1043  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:14.950  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:14.950  1043  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:14.950  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:33:14.950  1043  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:14.950  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:14.950  1043  1529 D NetworkManagementService: Removing idletimer
09-07 10:33:14.951  1043  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:14.951  1834  1834 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:14.951  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 10:33:14.952  1043  1523 D WifiNative-p2p0: TERMINATE: returned true
09-07 10:33:14.952  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:14.952  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:14.952  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 10:33:14.952  1043  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:14.952  1043  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:14.953  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 10:33:14.953  1043  1043 D RttService: SCAN_AVAILABLE : 1
09-07 10:33:14.953  1043  1541 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.953  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-07 10:33:14.954  1043  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:14.955  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:14.955  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:14.955  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:14.955  1043  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 10:33:14.955  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 10:33:14.956  1043  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 10:33:14.958  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 10:33:14.962  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.962  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:14.962  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.962  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.962  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:14.962  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:14.962  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:14.962  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:14.962  6729  6729 V io.jxcore.node.Conn,ectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.962  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.962  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:33:14.964  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:14.964  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:14.965  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.965  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:14.968  1043  1863 I art     : Explicit concurrent mark sweep GC freed 39436(1866KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.481ms total 136.037ms
09-07 10:33:14.969  3845  3927 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 10:33:14.970  3845  3935 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:33:14.970  3845  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 10:33:14.970  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:14.970  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:14.971  1043  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 10:33:14.973  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 10:33:14.973  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 10:33:14.973  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:14.973  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-07 10:33:14.973  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 10:33:14.974  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 10:33:14.974  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 10:33:14.974  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 10:33:14.974  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 10:33:14.974  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-07 10:33:14.976  3845  4239 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:14.976  3845  4300 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:14.976  3845  3927 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 10:33:14.976  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 10:33:14.976  3845  4045 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-07 10:33:14.976  6729  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
09-07 10:33:14.976  3845  4302 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 10:33:14.978  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 10:33:14.978  3845  4045 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 10:33:14.982  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:14.988  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:14.988  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:14.988  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:14.992  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:14.993  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:15.026  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:15.026  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:15.027  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:15.027  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 10:33:15.027  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:15.028  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:15.036  1043  2015 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6855 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-07 10:33:15.056  6836  6836 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:15.056  6836  6836 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-07 10:33:15.056  6836  6836 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 10:33:15.056  6836  6836 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-07 10:33:15.057  6836  6836 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 10:33:15.057  6836  6836 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 10:33:15.058  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:15.059  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:15.059  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:15.067  2733  2733 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 10:33:15.067  2733  2733 I wpa_supplicant: monitor socket send errors count : 1
09-07 10:33:15.067  2733  2733 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
09-07 10:33:15.068  1043  2764 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-07 10:33:15.068  1043  2764 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-07 10:33:15.072  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:15.073  1043  2853 D DhcpStateMachine: StoppedState
09-07 10:33:15.074  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:15.074  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:15.074  1043  2853 D DhcpStateMachine: StoppedState{ when=-146ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:15.074  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:15.075  1043  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 10:33:15.075  1043  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-07 10:33:15.107  2733  2733 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 10:33:15.108  1043  2764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-07 10:33:15.108  1043  2764 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 10:33:15.108  2733  2733 W wpa_supplicant: USIM:  scard_deinit function
09-07 10:33:15.108  1043  2764 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 10:33:15.108  1043  2764 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 10:33:15.108  1043  1119 D Tethering: InitialState.processMessage what=4
09-07 10:33:15.108  1043  2764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:15.108  1043  2764 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:15.109  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:33:15.109  1043  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179173
09-07 10:33:15.109  1043  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179173
09-07 10:33:15.110  1043  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179174  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 10:33:15.110  1043  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179174  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 10:33:15.111  1043  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:15.112  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:15.124  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-07 10:33:15.126  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-07 10:33:15.126  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:15.127  1043  1861 I ActivityManager: Killing 6202:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-07 10:33:15.145  6836  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-07 10:33:15.162  1043  1060 W libprocessgroup: failed to open /acct/uid_10014/pid_6202/cgroup.procs: No such file or directory
,09-07 10:33:15.171  2733  2733 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 10:33:15.171  1043  2764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 10:33:15.171  1043  2764 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 10:33:15.171  1043  2764 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 10:33:15.172  1043  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-07 10:33:15.177  3845  3845 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-07 10:33:15.178  3845  3845 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:15.178  3845  3845 V BluetoothPbapReceiver: ***********state = 13
09-07 10:33:15.179  3845  3845 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-07 10:33:15.180  3845  3845 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:15.180  3845  3845 V BluetoothPbapService: state: 13
09-07 10:33:15.180  3845  3845 V BluetoothPbapService: Pbap Service closeService in
09-07 10:33:15.185  3845  3845 V BluetoothPbapService: successfully stopped pbap service
09-07 10:33:15.185  3845  3845 V BluetoothPbapService: Pbap Service closeService out
09-07 10:33:15.185  3845  3845 V BluetoothPbapService: Pbap Service onDestroy
09-07 10:33:15.185  3845  3845 V BluetoothPbapService: Pbap Service closeService in
09-07 10:33:15.185  3845  3845 V BluetoothPbapService: Pbap Service closeService out
09-07 10:33:15.185  3845  3845 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 10:33:15.185  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:33:15.189  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 10:33:15.223  6836  6836 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:15.223  6836  6836 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 10:33:15.231  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 10:33:15.239  1043  1119 D BluetoothManagerService: Message: 20
09-07 10:33:15.239  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1585fd6c:true
09-07 10:33:15.260  6729  6729 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:33:15.268  1043  1559 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6877 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-07 10:33:15.275  1925  1925 D WfdsService: Supplicant Connection state is changed : false
09-07 10:33:15.275  1925  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 10:33:15.275  1925  2279 D WfdsService: Set the WFDS Monitor: false
09-07 10:33:15.275  1925  2279 D WfdsMonitor: WFDS Monitor is stopped
09-07 10:33:15.275  1043  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 10:33:15.275  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:15.275  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:15.275  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-07 10:33:15.279  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-07 10:33:15.279  1043  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 10:33:15.280  1043  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 10:33:15.281  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 10:33:15.281  2471  2471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:15.282  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:15.283  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:15.285  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:15.287   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 22.257ms
,09-07 10:33:15.294  1043  1119 D BluetoothManagerService: Message: 30
09-07 10:33:15.299  1043  1119 D BluetoothManagerService: Message: 30
09-07 10:33:15.302  6836  6836 D LocalBluetoothProfileManager: Adding local MAP profile
09-07 10:33:15.303  6836  6836 D BluetoothMap: Create BluetoothMap proxy object
,09-07 10:33:15.304  1043  1119 D BluetoothManagerService: Message: 30
09-07 10:33:15.308   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 19.963ms
09-07 10:33:15.308  1043  1119 D BluetoothManagerService: Message: 30
09-07 10:33:15.311  6836  6836 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-07 10:33:15.312  6836  6836 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-07 10:33:15.326   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 18.347ms
,09-07 10:33:15.331  6836  6836 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-07 10:33:15.334  6836  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-07 10:33:15.340  6836  6836 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:33:15.348  6836  6836 D BluetoothInputDevice: Proxy object connected
09-07 10:33:15.349  6836  6836 D HidProfile: Bluetooth service connected
09-07 10:33:15.350  6836  6836 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 10:33:15.351  6836  6836 D PanProfile: Bluetooth service connected
09-07 10:33:15.351  6836  6836 D BluetoothMap: Proxy object connected
,09-07 10:33:15.352  6836  6836 D MapProfile: Bluetooth service connected
09-07 10:33:15.352  6836  6836 D BluetoothMap: getConnectedDevices()
09-07 10:33:15.352  6836  6836 D BluetoothMap: Bluetooth is Not enabled
09-07 10:33:15.352  6836  6836 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 10:33:15.389  1043  1907 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6902 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-07 10:33:15.391  1043  1907 I ActivityManager: Killing 6311:com.android.defcontainer/u0a4 (adj 15): empty #17
09-07 10:33:15.493  1043  1559 W libprocessgroup: failed to open /acct/uid_10004/pid_6311/cgroup.procs: No such file or directory
,09-07 10:33:15.523  6877  6877 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-07 10:33:15.524  6877  6877 W LG Account v2.2: No ProfileInfo entries
09-07 10:33:15.524  6877  6877 I LG Account v2.2: isEnabled: false
09-07 10:33:15.524  6877  6877 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 10:33:15.525  6877  6877 I Feature : [Lifetracker]Country: EU
09-07 10:33:15.525  6877  6877 I Feature : [Lifetracker]Operator: OPEN
09-07 10:33:15.525  6877  6877 I Feature : [Lifetracker]Ranking support: false
09-07 10:33:15.525  6877  6877 I Feature : [Lifetracker]Comfort support: false
,09-07 10:33:15.525  6877  6877 I Feature : [Lifetracker]Accessory: true
09-07 10:33:15.526  6877  6877 I Feature : [Lifetracker]Health device: true
09-07 10:33:15.526  6877  6877 I Feature : [Lifetracker]Extra Pedometer: false
09-07 10:33:15.527  6877  6877 I Feature : [Lifetracker]Blood glucose device: false
09-07 10:33:15.527  6877  6877 I Feature : [Lifetracker]Device Number: 3
09-07 10:33:15.542  6836  6836 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 10:33:15.549  6902  6902 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 10:33:15.556  6836  6836 D BluetoothPermissionRequest: onReceive
,09-07 10:33:15.560  6836  6836 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 10:33:15.577  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 10:33:15.579  1043  1559 I ActivityManager: Killing 6498:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-07 10:33:15.667  3845  3845 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-07 10:33:15.667  3845  3845 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 10:33:15.670  3845  3845 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-07 10:33:15.675  1043  1979 W libprocessgroup: failed to open /acct/uid_10008/pid_6498/cgroup.procs: No such file or directory
09-07 10:33:15.693  6902  6902 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-07 10:33:15.700  3845  3845 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:15.700  3845  3845 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-07 10:33:15.701  3845  3845 V BluetoothFtpService: Ftp Service onStartCommand
09-07 10:33:15.701  3845  3845 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:15.702  3845  3845 V BluetoothFtpService: Ftp Service closeService
09-07 10:33:15.702  3845  3845 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 10:33:15.703  3845  3845 V BluetoothFtpService: successfully stopped ftp service
09-07 10:33:15.703  3845  3845 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 10:33:15.704  3845  3845 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:15.704  3845  3845 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 10:33:15.704  3845  3845 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:15.704  3845  3845 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 10:33:15.704  3845  3845 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 10:33:15.705  3845  3845 V BluetoothFtpService: Ftp Service onDestroy
09-07 10:33:15.705  3845  3845 V BluetoothFtpService: Ftp Service closeService
09-07 10:33:15.750  1043  1870 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6927 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 10:33:15.752  3845  3845 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:15.752  3845  3845 V BluetoothSapService: state: 13
09-07 10:33:15.752  3845  3845 V BluetoothSapService: Stopping SAP server process
09-07 10:33:15.755  3845  3845 V BluetoothSapService: Sap Service closeSapService in
09-07 10:33:15.755  3845  3845 V BluetoothSapService: Close listen Socket : 
09-07 10:33:15.755  3845  3845 V BluetoothSapService: Close rfcomm Socket : 
09-07 10:33:15.756  3845  3845 V BluetoothSapService: Close sapd  Socket : 
09-07 10:33:15.756  3845  3845 V BluetoothSapService: Sap Service closeSapService out
09-07 10:33:15.757  3845  3845 V BluetoothSapService: Sap Service onDestroy
09-07 10:33:15.757  3845  3845 V BluetoothSapService: Sap Service closeSapService in
09-07 10:33:15.757  3845  3845 V BluetoothSapService: Close listen Socket : 
09-07 10:33:15.757  3845  3845 V BluetoothSapService: Close rfcomm Socket : 
09-07 10:33:15.757  3845  3845 V BluetoothSapService: Close sapd  Socket : 
09-07 10:33:15.757  3845  3845 V BluetoothSapService: Sap Service closeSapService out
09-07 10:33:15.759  6902  6902 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-07 10:33:15.759  6902  6902 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 10:33:15.760  6902  6902 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-07 10:33:15.760  6902  6902 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 10:33:15.760  6902  6902 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 10:33:15.762  6902  6902 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-07 10:33:15.774  6902  6902 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-07 10:33:15.800  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:15.806  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:15.825  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 10:33:15.827  6902  6902 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-07 10:33:15.828  6927  6927 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 10:33:15.830  6902  6902 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-07 10:33:15.830  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:15.835  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 10:33:15.835  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 10:33:15.835  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:15.839  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:15.848  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:15.852  1043  1559 I ActivityManager: Killing 5999:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-07 10:33:15.927  1043  1943 W libprocessgroup: failed to open /acct/uid_10011/pid_5999/cgroup.procs: No such file or directory
09-07 10:33:15.927  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:15.928  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:15.938  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 10:33:15.945  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:15.952  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 10:33:15.953  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 10:33:15.953  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 10:33:15.961  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:15.973  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:15.982  3845  4045 W bt-btif : ag scb idx 1 not allocated
,09-07 10:33:15.982  3845  3935 D bt_hci_bdroid: cleanup
09-07 10:33:15.983  3845  4045 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 10:33:15.983  3845  4047 I bt_lpm  : LPM is already off!!!
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:15.983  3845  4045 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:15.984  3845  4045 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:15.984  3845  4210 I bt_userial_mct: exiting userial_read_thread
09-07 10:33:15.984  3845  4045 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:15.984  3845  4210 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 10:33:15.984  3845  4045 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 10:33:15.984  3845  3935 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 10:33:15.984  3845  4047 I bt_vendor: hw_epilog_process
09-07 10:33:15.985  3845  3935 D bt_hci_bdroid: cleanup Finalizing cleanup
09-07 10:33:15.985  3845  3935 D bt_userial_mct: userial_close
09-07 10:33:15.985  3845  3935 E bt_userial_mct: pthread_join() FAILED result:3
09-07 10:33:15.985  3845  3935 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-07 10:33:15.988  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:15.988  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:15.990  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 10:33:16.068  1043  1708 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6960 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-07 10:33:16.071  3845  3935 D bt_hci_bdroid: set_power 0
09-07 10:33:16.071  3845  3935 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 10:33:16.071  3845  3935 I bt_vendor: bluetooth satus is on
09-07 10:33:16.071  3845  3935 I bt_vendor: bt-vendor : resetting BT status
09-07 10:33:16.071  3845  3935 I bt_vendor: Starting hciattach daemon
09-07 10:33:16.071  3845  3935 I bt_vendor: try to set false
,09-07 10:33:16.073  3845  3935 I bt_vendor: Starting hciattach daemon
09-07 10:33:16.073  3845  3935 I bt_vendor: try to set false
09-07 10:33:16.075  3845  3935 I bt_vendor: cleanup
09-07 10:33:16.077  3845  4045 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 10:33:16.077  3845  3935 I GKI_LINUX: GKI_exit_task 0 done
09-07 10:33:16.077  3845  3935 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-07 10:33:16.079  3845  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 10:33:16.081  3845  3845 D HeadsetService: Received stop request...Stopping profile...
09-07 10:33:16.082  3845  3845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 10:33:16.082  3845  3845 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 10:33:16.082  3845  3964 D HeadsetStateMachine: Exit Disconnected: -1
09-07 10:33:16.082  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391b0f00
09-07 10:33:16.084  1043  1043 D BluetoothHeadset: Proxy object disconnected
09-07 10:33:16.084  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 10:33:16.084  1834  1834 D BluetoothHeadset: Proxy object disconnected
09-07 10:33:16.084  1834  1834 D BluetoothHeadset: Proxy object disconnected
09-07 10:33:16.085  1834  1834 D BluetoothHeadset: Proxy object disconnected
,09-07 10:33:16.086  3845  3845 D A2dpService: Received stop request...Stopping profile...
09-07 10:33:16.087  3845  4021 D A2dpStateMachine: Exit Disconnected: -1
09-07 10:33:16.089  3845  3845 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-07 10:33:16.090  3845  3927 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 10:33:16.091  3845  3845 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 10:33:16.091  3845  3845 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 10:33:16.091  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391b0f00
09-07 10:33:16.092  1043  1043 D BluetoothA2dp: Proxy object disconnected
09-07 10:33:16.092  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 10:33:16.093  3845  3845 D HeadsetStateMachine: Unbinding service...
09-07 10:33:16.093  3845  3845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 10:33:16.094  3845  3845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 10:33:16.094  3845  3845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 10:33:16.094  3845  3845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 10:33:16.094  3845  3845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 10:33:16.094  3845  3845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 10:33:16.094  3845  3845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 10:33:16.094  3845  3845 D HidService: Received stop request...Stopping profile...
09-07 10:33:16.094  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391b0f00
09-07 10:33:16.095  6836  6836 D BluetoothInputDevice: Proxy object disconnected
09-07 10:33:16.095  6836  6836 D HidProfile: Bluetooth service disconnected
09-07 10:33:16.096  3845  3845 D HealthService: Received stop request...Stopping profile...
09-07 10:33:16.096  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391b0f00
09-07 10:33:16.097  3845  3845 D PanService: Received stop request...Stopping profile...
,09-07 10:33:16.097  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391b0f00
09-07 10:33:16.098  3845  3845 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 10:33:16.099  3845  3845 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 10:33:16.099  3845  3845 D BtGatt.GattService: stop()
09-07 10:33:16.099  3845  3845 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 10:33:16.100  6836  6836 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 10:33:16.100  6836  6836 D PanProfile: Bluetooth service disconnected
09-07 10:33:16.101  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391b0f00
09-07 10:33:16.102  3845  3845 D BluetoothMapService: Received stop request...Stopping profile...
09-07 10:33:16.102  3845  3845 D BluetoothMapService: stop()
09-07 10:33:16.102  3845  3845 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 10:33:16.103  3845  3845 D BluetoothMapEmailAppObserver: removeReceiver()
09-07 10:33:16.103  3845  3845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391b0f00
09-07 10:33:16.104  6836  6836 D BluetoothMap: Proxy object disconnected
09-07 10:33:16.104  6836  6836 D MapProfile: Bluetooth service disconnected
09-07 10:33:16.104  3845  3845 I BluetoothA2dpServiceJni: cleanupNative
09-07 10:33:16.104  3845  4023 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 10:33:16.105  3845  3845 I GKI_LINUX: GKI_exit_task 2 done
09-07 10:33:16.105  3845  3845 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 10:33:16.105  3845  3845 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 10:33:16.105  3845  3845 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 10:33:16.105  3845  3845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 10:33:16.105  3845  3845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 10:33:16.106  3845  3845 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 10:33:16.106  3845  3845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 10:33:16.106  3845  3845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 10:33:16.107  3845  3845 V BluetoothMapService: Handler(): got msg=4
09-07 10:33:16.107  3845  3845 D BluetoothMapService: MAP Service closeService in
09-07 10:33:16.107  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
,09-07 10:33:16.107  3845  3845 V BluetoothMapService: MAP Service closeService out
09-07 10:33:16.107  3845  3845 D BluetoothMapService: cleanup()
09-07 10:33:16.107  3845  3845 D BluetoothMapService: MAP Service closeService in
09-07 10:33:16.107  3845  3845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 10:33:16.107  3845  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 10:33:16.107  3845  3845 V BluetoothMapService: MAP Service closeService out
09-07 10:33:16.107  3845  3927 D BluetoothAdapterProperties: Setting state to 10
09-07 10:33:16.107  3845  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 10:33:16.108  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:16.108  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 10:33:16.108  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-07 10:33:16.108  3845  3927 I BluetoothAdapterState: Entering OffState
09-07 10:33:16.108  6836  6852 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 10:33:16.109  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:16.109  1834  2686 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:16.109  6836  6854 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 10:33:16.110  6836  6852 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 10:33:16.111  1834  3538 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:16.114  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:16.114  6836  6854 D BluetoothPan: onBluetoothStateChange on: false
09-07 10:33:16.115  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:33:16.115  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 10:33:16.115  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-07 10:33:16.117  1043  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 10:33:16.117  1043  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 10:33:16.118  1043  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3a5472 mBinding = false
09-07 10:33:16.118  1043  1119 D BluetoothManagerService: Sending unbind request.
09-07 10:33:16.119  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-07 10:33:16.122  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 10:33:16.123  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:16.123  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:16.123  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:16.124  6836  6836 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 10:33:16.125  6836  6836 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 10:33:16.125  6836  6836 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-07 10:33:16.125  3845  3935 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-07 10:33:16.125  1925  2097 D LGBluetoothAPIService: Message: 2
09-07 10:33:16.125  1925  2097 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@38f9cd13 mBinding = false
,09-07 10:33:16.125  3845  3845 I GKI_LINUX: GKI_exit_task 1 done
09-07 10:33:16.125  3845  3845 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 10:33:16.125  1925  2097 D LGBluetoothAPIService: Sending unbind request.
09-07 10:33:16.125  3845  3845 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 10:33:16.126  3845  3845 I art     : --- WEIRD: removing null entry 246
09-07 10:33:16.126  3845  3845 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-07 10:33:16.126  3845  3845 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-07 10:33:16.128  1586  1586 D BluetoothAdapter: 645274264: getState() :  mService = null. Returning STATE_OFF
09-07 10:33:16.128  1586  1586 D BluetoothAdapter: 645274264: getState() :  mService = null. Returning STATE_OFF
09-07 10:33:16.130  3845  3845 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-07 10:33:16.132  6836  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 10:33:16.133  3845  3845 I art     : System.exit called, status: 0
09-07 10:33:16.133  3845  3845 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 10:33:16.143  6836  6836 D DockEventReceiver: finishStartingService: stopping service
09-07 10:33:16.152   320  2128 V AudioFlinger: 3845 died, releasing its sessions
09-07 10:33:16.152   320  2128 V AudioFlinger:  pid 1834 @ 0
09-07 10:33:16.152   320  2128 V AudioFlinger:  pid 3486 @ 1
09-07 10:33:16.152   320  2128 V AudioFlinger:  pid 3486 @ 2
09-07 10:33:16.153  6836  6836 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-07 10:33:16.170  1043  1906 I ActivityManager: Process com.android.bluetooth (pid 3845) has died
,09-07 10:33:16.171  1043  1906 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-07 10:33:16.175  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:33:16.189  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:16.191  6836  6836 D BluetoothPermissionRequest: onReceive
,09-07 10:33:16.195  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:33:16.204  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:16.205  6836  6836 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 10:33:16.206  6836  6836 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-07 10:33:16.208  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 10:33:16.285  1043  1861 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6983 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-07 10:33:16.302  6960  6981 W FormManager: Network not available. Please check & try again.
,09-07 10:33:16.316  6960  6982 V FormManager: Network unavailable.
,09-07 10:33:16.329  6960  6982 V FormManager: Network unavailable.
09-07 10:33:16.330  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 10:33:16.330  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 10:33:16.330  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-07 10:33:16.330  6836  6836 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 10:33:16.331  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-07 10:33:16.354  6836  6836 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 10:33:16.354  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,09-07 10:33:16.354  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 10:33:16.354  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 10:33:16.355  6836  6836 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 10:33:16.355  6836  6836 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 10:33:16.357  1043  1907 I ActivityManager: Killing 6021:com.android.contacts/u0a19 (adj 15): empty #17
09-07 10:33:16.362  6983  6983 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 10:33:16.362  6983  6983 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 10:33:16.362  6983  6983 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 10:33:16.363  6983  6983 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-07 10:33:16.378  6983  6983 D BluetoothAdapterApp: Loading JNI Library
,09-07 10:33:16.402  6983  6983 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@37f84501 Instance Count = 1
,09-07 10:33:16.464  1043  1871 W libprocessgroup: failed to open /acct/uid_10019/pid_6021/cgroup.procs: No such file or directory
,09-07 10:33:16.466  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 10:33:16.467  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 10:33:16.473  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:16.474  6983  6983 D BluetoothAdapterApp: onCreate
09-07 10:33:16.479  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 10:33:16.494  4278  7002 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 10:33:16.503  4278  7003 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 10:33:16.503  4278  7003 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 10:33:16.504  6855  6855 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 10:33:16.504  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 10:33:16.504  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 10:33:16.510  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 10:33:16.514  6983  6983 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-07 10:33:16.514  6983  6983 D ProfileConfigQcom: Adding HeadsetService
09-07 10:33:16.514  6983  6983 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-07 10:33:16.515  6983  6983 D ProfileConfigQcom: Adding A2dpService
09-07 10:33:16.515  6983  6983 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 10:33:16.515  6983  6983 D ProfileConfigQcom: Adding HidService
09-07 10:33:16.515  6983  6983 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 10:33:16.516  6983  6983 D ProfileConfigQcom: Adding HealthService
09-07 10:33:16.516  6983  6983 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-07 10:33:16.517  6983  6983 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 10:33:16.517  6983  6983 D ProfileConfigQcom: Adding PanService
09-07 10:33:16.517  6983  6983 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 10:33:16.517  6983  6983 D ProfileConfigQcom: Adding GattService
09-07 10:33:16.518  6983  6983 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 10:33:16.518  6983  6983 D ProfileConfigQcom: Adding BluetoothMapService
09-07 10:33:16.518  6983  6983 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 10:33:16.521  6983  6983 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-07 10:33:16.522  6960  7005 W FormManager: Network not available. Please check & try again.
09-07 10:33:16.523  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:16.529  6836  6836 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-07 10:33:16.530  6960  7006 V FormManager: Network unavailable.
,09-07 10:33:16.531  6983  6983 V LGMDMManagerInternal: Create singleton instance
09-07 10:33:16.538  6960  7006 V FormManager: Network unavailable.
09-07 10:33:16.545  6902  6902 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-07 10:33:16.546  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-07 10:33:16.547  6902  6902 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-07 10:33:16.584  6902  6902 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:16.584  6902  6902 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 10:33:16.592  6902  6902 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-07 10:33:16.593  6902  6902 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-07 10:33:16.593  6902  6902 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-07 10:33:16.593  6902  6902 V SoundPool: doLoad: loading sample sampleID=1
09-07 10:33:16.594  6902  6902 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-07 10:33:16.596  6902  7010 V SoundPool: Start decode
09-07 10:33:16.596  6902  7010 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-07 10:33:16.597   320  1368 V MediaPlayerService: decode(23, 10857164, 17813)
09-07 10:33:16.597   320  1368 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-07 10:33:16.598   320  1368 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-07 10:33:16.598   320  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-07 10:33:16.598   320  1368 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-07 10:33:16.598   320  1368 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-07 10:33:16.598   320  1368 V MediaPlayerService: player type = 3
09-07 10:33:16.598   320  1368 V AwesomePlayer: AwesomePlayer create()
09-07 10:33:16.599   320  1368 V AwesomePlayer: reset_l() 
09-07 10:33:16.599   320  1368 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:16.599   320  1368 V AwesomePlayer: setAudioSink() 
09-07 10:33:16.599   320  1368 V AwesomePlayer: reset_l() 
09-07 10:33:16.599   320  1368 V AudioCache: notify(0xb5474840, 8, 0, 0)
09-07 10:33:16.599   320  1368 V AudioCache: ignored
09-07 10:33:16.599   320  1368 V AwesomePlayer: cancelPlayerEvents
,09-07 10:33:16.599   320  1368 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-07 10:33:16.599   320  1368 V AwesomePlayer: setDataSource_l dataSource
09-07 10:33:16.599   320  1368 V LGParserOSAL: SniffLGParser start
09-07 10:33:16.599   320  1368 V LGParserOSAL: MainType:5, SubType=0
09-07 10:33:16.600   320  1368 V LGParserOSAL: #### check Mime : application/ogg
09-07 10:33:16.600   320  1368 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-07 10:33:16.600   320  1368 E MediaExtractor: Use LGExtractor :application/ogg 
09-07 10:33:16.600  6639  6639 D UEI.SmartControl: QS Service created
09-07 10:33:16.602  6902  6902 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-07 10:33:16.605  6902  6902 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 10:33:16.605  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-07 10:33:16.611  6639  6639 I UEI.SmartControl: Service initServices...
09-07 10:33:16.611  6639  6639 D UEI.SmartControl: QS start get config
,09-07 10:33:16.627  6902  6902 V LGMDMManager: Create singleton instance
,09-07 10:33:16.641  6983  6983 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:16.643  6983  6983 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-07 10:33:16.644  6983  6983 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:16.644  6983  6983 V BluetoothSapReceiver: SapReceiver onReceive 
,09-07 10:33:16.645  6983  6983 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:16.645  6983  6983 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 10:33:16.652  6927  6927 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-07 10:33:16.656   320  1368 V LGParserOSAL: supported mime: application/ogg
09-07 10:33:16.656   320  1368 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-07 10:33:16.656   320  1368 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-07 10:33:16.656   320  1368 V AwesomePlayer: mBitrate = -1 bits/sec
09-07 10:33:16.656   320  1368 V AwesomePlayer: AudioTrack Setting
09-07 10:33:16.656   320  1368 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-07 10:33:16.656   320  1368 V AwesomePlayer: setAudioSource() 
09-07 10:33:16.656   320  1368 V MediaPlayerService: prepare
09-07 10:33:16.656   320  1368 V AwesomePlayer: prepareAsync_l() 
09-07 10:33:16.656   320  1368 V MediaPlayerService: wait for prepare
09-07 10:33:16.656   320  7012 V AwesomePlayer: onPrepareAsyncEvent() 
09-07 10:33:16.656   320  7012 V AwesomePlayer: initAudioDecoder() 
09-07 10:33:16.656   320  7012 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 10:33:16.656   320  7012 V AudioSystem: isOffloadSupported()
09-07 10:33:16.656   320  7012 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 10:33:16.656   320  7012 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 10:33:16.656   320  7012 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 10:33:16.656   320  7012 V AwesomePlayer: getUseOffload() = 0 
09-07 10:33:16.656   320  7012 V OMXCodec: OMXCodec::Create
,09-07 10:33:16.656   320  7012 V OMXCodec: findMatchingCodecs()
09-07 10:33:16.656   320  7012 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-07 10:33:16.656   320  7012 V OMXCodec: matchingCodecs.size()=1
09-07 10:33:16.656   320  7012 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-07 10:33:16.658   320  7012 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-07 10:33:16.658   320  7012 V LGCodecAdapter: LG Codec Adapter start
09-07 10:33:16.658   320  7012 V OMXCodec: OMXCodec Createtor
09-07 10:33:16.658   320  7012 V OMXCodec: setComponentRole
09-07 10:33:16.658   320  7012 V OMXCodec: configureCodec protected=0
09-07 10:33:16.658   320  7012 V LGCodecAdapter: called getLGCodecSpecificData
09-07 10:33:16.658   320  7012 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-07 10:33:16.658   320  7012 V LGCodecOSAL: Called LGconfigureCodecMETA
09-07 10:33:16.658   320  7012 V LGCodecOSAL: Called LGconfigureCodecMSG
09-07 10:33:16.658   320  7012 V LGCodecOSAL: Not support LGCodec
09-07 10:33:16.658   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 10:33:16.658   320  7012 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-07 10:33:16.658   320  7012 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-07 10:33:16.658   320  7012 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-07 10:33:16.658   320  7012 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 10:33:16.658   320  7012 V AudioSystem: isOffloadSupported()
09-07 10:33:16.658   320  7012 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 10:33:16.659   320  7012 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-07 10:33:16.659   320  7012 V OMXCodec: init()
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-07 10:33:16.659   320  7012 V OMXCodec: allocateBuffers
09-07 10:33:16.659   320  7012 V OMXCodec: allocateBuffersOnPort portIndex=0
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-07 10:33:16.659   320  7012 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
09-07 10:33:16.659   320  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f91a0 on output port
09-07 10:33:16.659   320  7012 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 10:33:16.659   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 10:33:16.659   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 10:33:16.659   320  7014 V OMXCodec:, [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-07 10:33:16.659   320  7012 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 10:33:16.659   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-07 10:33:16.660   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-07 10:33:16.660   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-07 10:33:16.660   320  7012 V OMXCodec: init() mAsyncCompletion wait free! 
09-07 10:33:16.660   320  7012 V AwesomePlayer: finishAsyncPrepare_l() 
09-07 10:33:16.660   320  7012 V AudioCache: notify(0xb5474840, 5, 0, 0)
09-07 10:33:16.660   320  7012 V AudioCache: ignored
09-07 10:33:16.660   320  7012 V AudioCache: notify(0xb5474840, 1, 0, 0)
09-07 10:33:16.660   320  7012 V AudioCache: prepared
09-07 10:33:16.660   320  1368 V AudioCache: wait - success
09-07 10:33:16.660   320  1368 V MediaPlayerService: start
09-07 10:33:16.660   320  1368 V AwesomePlayer: play_l() 
09-07 10:33:16.660   320  1368 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-07 10:33:16.660   320  1368 V AwesomePlayer: createAudioPlayer_l
09-07 10:33:16.660   320  1368 V AwesomePlayer: seekAudioIfNecessary_l() 
09-07 10:33:16.661   320  1368 V AwesomePlayer: startAudioPlayer_l() 
09-07 10:33:16.661   320  1368 D AudioPlayer: start of Playback, useOffload 0
09-07 10:33:16.661   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 10:33:16.661   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 10:33:16.662   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-07 10:33:16.662   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-07 10:33:16.662   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-07 10:33:16.662   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-07 10:33:16.662   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036448
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-07 10:33:16.663   320  7014 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
,09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-07 10:33:16.663   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-07 10:33:16.665   320  1368 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-07 10:33:16.665   320  1368 V AudioCache: notify(0xb5474840, 6, 0, 0)
09-07 10:33:16.665   320  1368 V AudioCache: ignored
09-07 10:33:16.665   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.665   320  7015 V AudioCache: memcpy(0xaf006000, 0xb178c000, 4096)
09-07 10:33:16.665   320  1368 V MediaPlayerService: wait for playback complete
09-07 10:33:16.668   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.668   320  7015 V AudioCache: memcpy(0xaf007000, 0xb178c000, 4096)
09-07 10:33:16.668   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.668   320  7015 V AudioCache: memcpy(0xaf008000, 0xb178c000, 4096)
,09-07 10:33:16.670   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.670   320  7015 V AudioCache: memcpy(0xaf009000, 0xb178c000, 4096)
09-07 10:33:16.670   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.670   320  7015 V AudioCache: memcpy(0xaf00a000, 0xb178c000, 4096)
09-07 10:33:16.671   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.671   320  7015 V AudioCache: memcpy(0xaf00b000, 0xb178c000, 4096)
09-07 10:33:16.671   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.671   320  7015 V AudioCache: memcpy(0xaf00c000, 0xb178c000, 4096)
09-07 10:33:16.672   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.672   320  7015 V AudioCache: memcpy(0xaf00d000, 0xb178c000, 4096)
09-07 10:33:16.673   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.673   320  7015 V AudioCache: memcpy(0xaf00e000, 0xb178c000, 4096)
09-07 10:33:16.674   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.674   320  7015 V AudioCache: memcpy(0xaf00f000, 0xb178c000, 4096)
09-07 10:33:16.674   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.674   320  7015 V AudioCache: memcpy(0xaf010000, 0xb178c000, 4096)
09-07 10:33:16.675   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.675   320  7015 V AudioCache: memcpy(0xaf011000, 0xb178c000, 4096)
09-07 10:33:16.676   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.676   320  7015 V AudioCache: memcpy(0xaf012000, 0xb178c000, 4096)
09-07 10:33:16.676   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.676   320  7015 V AudioCache: memcpy(0xaf013000, 0xb178c000, 4096)
09-07 10:33:16.677   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.677   320  7015 V AudioCache: memcpy(0xaf014000, 0xb178c000, 4096)
,09-07 10:33:16.677   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.677   320  7015 V AudioCache: memcpy(0xaf015000, 0xb178c000, 4096)
09-07 10:33:16.678   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.678   320  7015 V AudioCache: memcpy(0xaf016000, 0xb178c000, 4096)
09-07 10:33:16.679   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.679   320  7015 V AudioCache: memcpy(0xaf017000, 0xb178c000, 4096)
09-07 10:33:16.679   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.679   320  7015 V AudioCache: memcpy(0xaf018000, 0xb178c000, 4096)
09-07 10:33:16.680   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.681   320  7015 V AudioCache: memcpy(0xaf019000, 0xb178c000, 4096)
09-07 10:33:16.682   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.682   320  7015 V AudioCache: memcpy(0xaf01a000, 0xb178c000, 4096)
09-07 10:33:16.682   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.682   320  7015 V AudioCache: memcpy(0xaf01b000, 0xb178c000, 4096)
09-07 10:33:16.682   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.682   320  7015 V AudioCache: memcpy(0xaf01c000, 0xb178c000, 4096)
09-07 10:33:16.683   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.683   320  7015 V AudioCache: memcpy(0xaf01d000, 0xb178c000, 4096)
09-07 10:33:16.683   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.683   320  7015 V AudioCache: memcpy(0xaf01e000, 0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: memcpy(0xaf01f000, 0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: memcpy(0xaf020000, 0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: memcpy(0xaf021000, 0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.684   320  7015 V AudioCache: memcpy(0xaf022000, 0xb178c000, 4096)
09-07 10:33:16.685   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.685   320  7015 V AudioCache: memcpy(0xaf023000, 0xb178c000, 4096)
,09-07 10:33:16.685   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.685   320  7015 V AudioCache: memcpy(0xaf024000, 0xb178c000, 4096)
09-07 10:33:16.685   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.685   320  7015 V AudioCache: memcpy(0xaf025000, 0xb178c000, 4096)
09-07 10:33:16.685   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.685   320  7015 V AudioCache: memcpy(0xaf026000, 0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: memcpy(0xaf027000, 0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: memcpy(0xaf028000, 0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: memcpy(0xaf029000, 0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.686   320  7015 V AudioCache: memcpy(0xaf02a000, 0xb178c000, 4096)
,09-07 10:33:16.687   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.687   320  7015 V AudioCache: memcpy(0xaf02b000, 0xb178c000, 4096)
09-07 10:33:16.687   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.687   320  7015 V AudioCache: memcpy(0xaf02c000, 0xb178c000, 4096)
09-07 10:33:16.687   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.687   320  7015 V AudioCache: memcpy(0xaf02d000, 0xb178c000, 4096)
09-07 10:33:16.687   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.687   320  7015 V AudioCache: memcpy(0xaf02e000, 0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: memcpy(0xaf02f000, 0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: write(0xb178c000, 4096)
,09-07 10:33:16.688   320  7015 V AudioCache: memcpy(0xaf030000, 0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: memcpy(0xaf031000, 0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: memcpy(0xaf032000, 0xb178c000, 4096)
09-07 10:33:16.688   320  7015 V AudioCache: write(0xb178c000, 4096)
,09-07 10:33:16.688   320  7015 V AudioCache: memcpy(0xaf033000, 0xb178c000, 4096)
09-07 10:33:16.689   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.689   320  7015 V AudioCache: memcpy(0xaf034000, 0xb178c000, 4096)
09-07 10:33:16.689   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.689   320  7015 V AudioCache: memcpy(0xaf035000, 0xb178c000, 4096)
09-07 10:33:16.689   320  7015 V AudioCache: write(0xb178c000, 4096)
,09-07 10:33:16.689   320  7015 V AudioCache: memcpy(0xaf036000, 0xb178c000, 4096)
09-07 10:33:16.689   320  7015 V AudioCache: write(0xb178c000, 4096)
09-07 10:33:16.689   320  7015 V AudioCache: memcpy(0xaf037000, 0xb178c000, 4096)
09-07 10:33:16.689   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-07 10:33:16.690   320  7015 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 10:33:16.690   320  7015 V AwesomePlayer: postAudioEOS() 
,09-07 10:33:16.690   320  7015 V AudioCache: write(0xb178c000, 280)
09-07 10:33:16.690   320  7015 V AudioCache: memcpy(0xaf038000, 0xb178c000, 280)
09-07 10:33:16.691   320  7012 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-07 10:33:16.691   320  7012 V AwesomePlayer: onStreamDone
09-07 10:33:16.691   320  7012 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-07 10:33:16.691   320  7012 V AudioCache: notify(0xb5474840, 2, 0, 0)
,09-07 10:33:16.691   320  7012 V AudioCache: playback complete
09-07 10:33:16.691   320  7012 V AwesomePlayer: pause_l() 
09-07 10:33:16.691   320  7012 V AudioCache: notify(0xb5474840, 7, 0, 0)
09-07 10:33:16.691   320  7012 V AudioCache: ignored
09-07 10:33:16.691   320  7012 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:16.691   320  1368 V AudioCache: wait - success,
09-07 10:33:16.691   320  1368 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-07 10:33:16.691   320  7012 D AudioPlayer: Pause Playback at 1068125
09-07 10:33:16.692   320  1368 V AwesomePlayer: reset_l() 
09-07 10:33:16.692   320  1368 V AudioCache: notify(0xb5474840, 8, 0, 0)
09-07 10:33:16.692   320  1368 V AudioCache: ignored,
09-07 10:33:16.692   320  1368 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:16.692   320  1368 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-07 10:33:16.692   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-07 10:33:16.692   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-07 10:33:16.692   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
,09-07 10:33:16.692   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0,
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1,
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-07 10:33:16.692   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 10:33:16.692   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
,09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-07 10:33:16.692   320  7014 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-07 10:33:16.693   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 10:33:16.693   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-07 10:33:16.693   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1,
09-07 10:33:16.693   320  1368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-07 10:33:16.693   320  1368 D AudioPlayer: AudioPlayer releasing audio source
09-07 10:33:16.693   320  1368 D AudioPlayer: AudioPlayer done releasing audio source
09-07 10:33:16.693   320  1368 V AwesomePlayer: reset_l() 
09-07 10:33:16.693   320  1368 V AwesomePlayer: cancelPlayerEvents
,09-07 10:33:16.693   320  1368 V AwesomePlayer: ~AwesomePlayer call
09-07 10:33:16.694   320  1368 V AwesomePlayer: reset_l() 
09-07 10:33:16.694   320  1368 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:16.694  6902  7010 V SoundPool: close(31)
09-07 10:33:16.694  6902  7010 V SoundPool: pointer = 0x9fe5f000, size = 205080, sampleRate = 48000, numChannels = 2
,09-07 10:33:16.702  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-07 10:33:16.702  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-07 10:33:16.704  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8355
09-07 10:33:16.851  6639  6639 I UEI.SmartControl: Supports setup maps: true
,09-07 10:33:16.854  6639  6639 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 10:33:16.854  6639  6639 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 10:33:16.854  6639  6639 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 10:33:16.854  6639  6639 I UEI.SmartControl: ### init IR Blaster...
09-07 10:33:16.857  6639  6639 D serial_port: Configuring serial port
09-07 10:33:16.857  6639  6639 E UEI.SmartControl: UEIBLaster setting for 616
09-07 10:33:16.857  6639  6639 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 10:33:16.857  6639  6639 I UEI.SmartControl: configuring settings for MAXQ616
09-07 10:33:16.857  6639  6639 I UEI.SmartControl: Get version...
09-07 10:33:16.876  6639  7016 D UEI.SmartControl: serial port data available: 21
,09-07 10:33:16.903  6639  6639 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-07 10:33:16.903  6639  6639 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 10:33:16.903  6639  6639 I UEI.SmartControl: QS saving settings...
09-07 10:33:16.905  6639  6639 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 10:33:16.923  6639  7016 D UEI.SmartControl: serial port data available: 4
,09-07 10:33:16.956  6639  7019 I UEI.SmartControl: Device manager: loading config....
,09-07 10:33:16.957  6639  7019 D UEI.SmartControl: ----------- loading internal config...
,09-07 10:33:16.963  6639  6639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-07 10:33:16.965  6639  6639 E UEI.SmartControl: Services init done
09-07 10:33:16.965  6639  6639 D UEI.SmartControl: QS Service init finished
09-07 10:33:16.967  6639  6639 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 10:33:16.967  6639  6639 D UEI.SmartControl: QS Service version code: 201091
09-07 10:33:16.967  6639  6639 D UEI.SmartControl: Service requested: Control
09-07 10:33:16.969  6639  7019 E UEI.SmartControl: Loading SETTINGS...
09-07 10:33:16.972  6639  6639 D UEI.SmartControl: Request IControl service: devices are loaded...
09-07 10:33:16.974  6639  6639 D UEI.SmartControl: Internal service binding...
09-07 10:33:16.975  6902  6902 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-07 10:33:16.977  6639  7019 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 10:33:16.980  6639  6654 I UEI.SmartControl: ------ IControl API: 11
09-07 10:33:16.980  6639  6654 D UEI.SmartControl: File observer start...
09-07 10:33:16.981  6639  6654 E UEI.SmartControl: IR Port is disabled: false
09-07 10:33:16.982  6639  6654 D UEI.SmartControl: Starting file observer...
09-07 10:33:16.982  6639  6654 I UEI.SmartControl: Registering callback...
09-07 10:33:16.983  6639  6655 I UEI.SmartControl: ------ IControl API: 19
09-07 10:33:16.983  6639  6655 I UEI.SmartControl: Registering Services Ready callback...
09-07 10:33:16.983  6639  6655 I UEI.SmartControl: Notify client services are ready...
09-07 10:33:16.985  6902  6918 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-07 10:33:16.985  6902  7008 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-07 10:33:16.986  6902  7008 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-07 10:33:16.987  6902  6902 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-07 10:33:16.988  6902  6902 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,09-07 10:33:16.988  6639  6654 I UEI.SmartControl: ------ IControl API: 8
09-07 10:33:16.992  6639  7018 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 10:33:16.992  6902  6902 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-07 10:33:16.992  6639  7018 D UEI.SmartControl: -----service ready thread exits
09-07 10:33:16.993  6902  6917 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-07 10:33:16.993  6902  7008 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-07 10:33:16.993  6902  7008 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-07 10:33:16.994  6902  6902 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-07 10:33:16.994  6902  6902 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-07 10:33:16.995  6902  6902 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-07 10:33:16.997  6902  6902 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-07 10:33:16.998  6902  6902 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-07 10:33:16.999  6902  6902 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-07 10:33:17.001  6902  6902 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
09-07 10:33:17.002  6902  6902 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-07 10:33:17.003  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-07 10:33:17.004  6902  6902 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 10:33:17.004  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-07 10:33:17.005  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-07 10:33:17.007  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-07 10:33:17.007  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-07 10:33:17.008  6902  6902 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473237197008]
09-07 10:33:17.010  6902  6902 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-07 10:33:17.013  1043  1861 I ActivityManager: Killing 6047:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-07 10:33:17.032  6902  7024 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-07 10:33:17.051  1043  1861 I ActivityManager: Killing 6535:com.lge.email/u0a23 (adj 15): empty #18
,09-07 10:33:17.084  1043  1863 W libprocessgroup: failed to open /acct/uid_10027/pid_6047/cgroup.procs: No such file or directory
,09-07 10:33:17.094  1043  1631 W libprocessgroup: failed to open /acct/uid_10023/pid_6535/cgroup.procs: No such file or directory
09-07 10:33:17.095  6902  6902 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-07 10:33:17.097  6902  6902 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 10:33:17.098  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,09-07 10:33:17.098  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,09-07 10:33:17.099  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-07 10:33:17.099  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-07 10:33:17.100  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-07 10:33:17.115  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-07 10:33:17.898  1043  1906 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 10:33:17.900  1043  1906 D WifiService: setWifiEnabled: true pid=6729, uid=10118
09-07 10:33:17.900  1043  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:33:17.935  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:17.935  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:17.935  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,09-07 10:33:17.939  1043  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 10:33:17.939  1043  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-07 10:33:17.941  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 10:33:17.941  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 10:33:17.941  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-07 10:33:17.941  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 10:33:17.941  1043  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-07 10:33:17.942  1043  1523 E WifiHW  : unknown target_country: EU , set to default
09-07 10:33:17.942  1043  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-07 10:33:17.942  1043  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-07 10:33:17.942  1043  1523 I WifiUtil: gEnableBmps=1
09-07 10:33:17.953  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:17.960  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 10:33:17.969  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:17.974  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:17.975  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:17.980  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:17.981  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 10:33:17.991  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:17.995  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:17.997  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 10:33:18.000  6449  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 10:33:18.002  5741  5741 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 10:33:18.014  5741  5741 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 10:33:18.039  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:18.072  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:18.114  1043  1559 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7043 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-07 10:33:18.126  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 10:33:18.127  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 10:33:18.189  7043  7043 I AppUp4:AppBoxCP: onCreate
09-07 10:33:18.190  7043  7043 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-07 10:33:18.201  7043  7043 I AppUp4:DB:  setFingerPrint start
09-07 10:33:18.202  7043  7043 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-07 10:33:18.211  7043  7043 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-07 10:33:18.211  7043  7043 I AppUp4:DB:  SDK version = 21
09-07 10:33:18.211  7043  7043 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-07 10:33:18.213  7043  7043 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-07 10:33:18.215  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 10:33:18.215  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:18.218  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 10:33:18.218  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 10:33:18.225  7043  7043 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 10:33:18.267  7043  7043 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:18.267  7043  7043 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 10:33:18.276  7043  7043 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31e99183
,09-07 10:33:18.276  7043  7043 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 10:33:18.276  7043  7043 D AppUp4:CustFacade: isPhone : true
09-07 10:33:18.277  7043  7043 D AppUp4:CustModeStarterReceiver: begin check event
,09-07 10:33:18.277  7043  7043 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-07 10:33:18.278  7043  7043 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-07 10:33:18.279  7043  7061 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-07 10:33:18.279  7043  7061 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-07 10:33:18.279  7043  7061 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-07 10:33:18.282  1043  1979 I ActivityManager: Killing 6569:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-07 10:33:18.323  1043  1907 W libprocessgroup: failed to open /acct/uid_10061/pid_6569/cgroup.procs: No such file or directory
09-07 10:33:18.323  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:18.324  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 10:33:18.330  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:18.333  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:18.342  4278  7063 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 10:33:18.343  4278  7064 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:18.343  4278  7064 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 10:33:18.412  1043  2015 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7065 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-07 10:33:18.487  7065  7065 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:18.487  7065  7065 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 10:33:18.489  7065  7065 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 10:33:18.489  7065  7065 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 10:33:18.592  7065  7065 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-07 10:33:18.607  7065  7065 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-07 10:33:18.652  7065  7065 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 10:33:18.680  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:33:18.680  1043  1119 D Tethering: InitialState.processMessage what=4
,09-07 10:33:18.685   315   903 D SoftapController: Softap fwReload - Ok
09-07 10:33:18.686  1043  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (734ms)
09-07 10:33:18.687   315   903 D CommandListener: Setting iface cfg
09-07 10:33:18.687   315   903 D CommandListener: Trying to bring down wlan0
09-07 10:33:18.688   315   903 D CommandListener: Clearing all IP addresses on wlan0
09-07 10:33:18.690  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:33:18.691  1043  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-07 10:33:18.696  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:18.696  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:18.696  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-07 10:33:18.702  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-07 10:33:18.703  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:18.693  7099  7099 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:18.708  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:18.709  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:18.709  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 10:33:18.710  1043  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 10:33:18.710  1043  1523 D WifiMonitor: connecting to supplicant
,09-07 10:33:18.693  7099  7099 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 10:33:18.728  7099  7099 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 10:33:18.743  7065  7065 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:18.743  7065  7065 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 10:33:18.762  7099  7099 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 10:33:18.762  7099  7099 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-07 10:33:18.843  7099  7099 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 10:33:18.872  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 10:33:18.890  7099  7099 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-07 10:33:18.905  7065  7065 I HubEmail: JNI_OnLoad()
09-07 10:33:18.905  7065  7065 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 10:33:18.905  7065  7065 I HubEmail: registerNatives()
09-07 10:33:18.905  7065  7065 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 10:33:18.905  7065  7065 I HubEmail: registerNativeMethods()
09-07 10:33:18.905  7099  7099 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 10:33:18.905  7065  7065 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-07 10:33:18.906  7065  7065 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-07 10:33:18.909  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-07 10:33:18.909  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-07 10:33:18.910  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 10:33:18.910  1043  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 10:33:18.911  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:18.911  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:18.912  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:18.912  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:18.913  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 10:33:18.913  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 10:33:18.913  1043  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 10:33:18.913  1043  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 10:33:18.913  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 10:33:18.913  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-07 10:33:18.914  1043  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 10:33:18.914  1043  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 10:33:18.915  1043  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-07 10:33:18.916  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:18.916  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:18.916  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 10:33:18.916  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:18.916  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:18.916  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:18.916  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:18.916  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:18.918  1043  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-07 10:33:18.918  1043  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-07 10:33:18.918  1043  1523 D WifiConfigStore: Loading config and enabling all networks 
09-07 10:33:18.918  1043  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-07 10:33:18.919  1043  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-07 10:33:18.924  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:18.924  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:18.925  1925  1925 D WfdService: Waiting for WifiP2p enabling
09-07 10:33:18.924  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:18.925  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:18.926  1043  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-07 10:33:18.927  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:18.928  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 10:33:18.929  1043  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-07 10:33:18.932  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:18.932  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:18.932  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:18.932  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:18.932  7065  7110 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:18.935  3486  3486 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 10:33:18.935  3486  3486 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:18.935  3486  3486 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 10:33:18,.938  1043  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 10:33:18.938  1043  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 10:33:18.975  1043  1979 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7115 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-07 10:33:18.978  6960  7111 W FormManager: Network not available. Please check & try again.
09-07 10:33:18.979  1043  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-07 10:33:18.979  1043  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 10:33:18.980  1043  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 10:33:18.980  1043  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-07 10:33:18.980  1043  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 10:33:18.980  1043  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 10:33:18.981  1043  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 10:33:18.981  1043  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 10:33:18.981  1043  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-07 10:33:18.981  1043  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 10:33:18.982  1043  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 10:33:18.982  1043  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 10:33:18.982  1043  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 10:33:18.982  1043  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 10:33:18.983  1043  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-07 10:33:18.983  6960  7113 V FormManager: Network unavailable.
09-07 10:33:18.983  1043  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 10:33:18.983  1043  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-07 10:33:18.984  1925  1925 D WfdsService: Supplicant Connection state is changed : true
09-07 10:33:18.984  1043  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 10:33:18.984  1043  1523 D WifiNative-HAL: Setting external_sim to 1
09-07 10:33:18.984  1043  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-07 10:33:18.984  1925  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 10:33:18.984  1925  2279 D WfdsService: Set the WFDS Monitor: true
09-07 10:33:18.984  1925  2279 D WfdsMonitor: WfdsMonitorThread create
09-07 10:33:18.984  1925  2279 D WfdsMonitor: WFDS Monitor is created and started
09-07 10:33:18.984  1925  2279 D WfdsService: WiFi: Supplicant connection re-established
09-07 10:33:18.985  1043  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 10:33:18.985  1043  1523 I WifiNative-HAL: startHal
09-07 10:33:18.985  1043  1523 D wifi    : setting scan oui 0xaf75cf40
09-07 10:33:18.985  1043  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 10:33:18.985  1043  1523 I WifiNative-HAL: startHal
09-07 10:33:18.985  1043  1523 D wifi    : setting scan oui 0xaf75cf40
09-07 10:33:18.985  1043  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-07 10:33:18.986  6960  7113 V FormManager: Network unavailable.
09-07 10:33:18.986  1043  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 10:33:18.986  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-07 10:33:18.986  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 10:33:18.987  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-07 10:33:18.987  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 10:33:18.987  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 10:33:18.987  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 10:33:18.987  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-07 10:33:18.988  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 10:33:18.988  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 10:33:18.988  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 10:33:18.988  7099  7099 I, wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 10:33:18.989  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 10:33:18.989  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 10:33:18.989  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-07 10:33:18.989  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 10:33:18.989  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 10:33:18.990  7099  7099 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,09-07 10:33:18.990  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 10:33:18.990  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 10:33:18.990  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 10:33:18.991  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 10:33:18.991  1043  1523 E WifiNative: : [183,055,338 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 10:33:18.992  1043  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-07 10:33:18.992  1925  7128 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-07 10:33:18.992  1043  1523 D WifiNative-wlan0: RECONNECT: returned true
09-07 10:33:18.992  1043  1523 D WifiNative-wlan0: doString: [STATUS]
09-07 10:33:18.992  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-07 10:33:18.993  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-07 10:33:18.993  1925  7128 E CtrlSupplicant: Succeed to open control connection
09-07 10:33:18.993  1043  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 10:33:18.993  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:18.993  1925  7128 E CtrlSupplicant: Succeed to open monitor connection
09-07 10:33:18.993  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
09-07 10:33:18.994  1925  7128 D WfdsMonitor: Supplicant connection established
09-07 10:33:18.994  1925  2279 D WfdsService: Connected to the supplicant for wfds
09-07 10:33:18.994  1043  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:18.994  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 10:33:18.994  1043  1043 D RttService: SCAN_AVAILABLE : 3
09-07 10:33:18.994  1043  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:18.994  1043  1540 I WifiNative-HAL: startHal
09-07 10:33:18.994  1043  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf75cf40
09-07 10:33:18.994  1043  1540 D wifi    : failed to get capabilities : -3
09-07 10:33:18.994  1043  1540 E WifiScanningService: could not get scan capabilities
09-07 10:33:18.995  1043  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 10:33:18.995  1043  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 10:33:18.995  1043  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:18.995  1043  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 10:33:18.996  1043  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 10:33:18.996   315   903 D CommandListener: Setting iface cfg
09-07 10:33:18.996   315   903 D CommandListener: Trying to bring up p2p0
09-07 10:33:18.996  1043  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 10:33:18.996  1043  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 10:33:18.996  1043  1521 D LGWifiP2pService: P2pEnablingState
09-07 10:33:18.996  1043  1521 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:18.996  1043  1521 D LGWifiP2pService: P2p socket connection successful
09-07 10:33:18.996  1043  1521 D LGWifiP2pService: P2pEnabledState
09-07 10:33:18.996  1043  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 10:33:18.997  1043  1059 I ActivityManager: Killing 6114:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-07 10:33:18.997  1043  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0,
,09-07 10:33:18.997  1043  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 10:33:18.997  7099  7099 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 10:33:18.999  1043  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-07 10:33:18.999  1043  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 10:33:18.999  1043  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 10:33:19.000  1043  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,09-07 10:33:19.000  7099  7099 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 10:33:19.000  1043  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 10:33:19.001  1043  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 10:33:19.001  1043  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-07 10:33:19.001  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-07 10:33:19.002  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-07 10:33:19.002  7099  7099 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.002  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 10:33:19.002  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.003  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.003  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.003  7099  7099 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,09-07 10:33:19.003  7099  7099 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.003  1043  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-07 10:33:19.003  1043  7109 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:19.003  1043  7109 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.003  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
09-07 10:33:19.003  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-07 10:33:19.004  1043  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-07 10:33:19.004  7099  7099 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.004  1043  7109 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-07 10:33:19.004  1043  7109 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.004  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.004  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.004  1043  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 10:33:19.004  1925  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:19.004  1925  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-07 10:33:19.004  1043  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 10:33:19.004  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 10:33:19.005  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 10:33:19.005  7099  7099 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 10:33:19.005  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 10:33:19.006  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-07 10:33:19.006  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 10:33:19.006  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 10:33:19.006  1043  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,09-07 10:33:19.006  1043  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-07 10:33:19.006  1043  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 10:33:19.007  1043  1523 D WifiNative-wlan0: doBoolean: SCAN
09-07 10:33:19.007  1043  1523 D WifiNative-wlan0: SCAN: returned false
09-07 10:33:19.008  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=183072  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 10:33:19.031  1043  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 10:33:19.032  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 10:33:19.032  1925  1925 D WfdsService: WifiP2pState is changed : true
09-07 10:33:19.032  1925  2279 D WfdsService: Receive the WFDS_ENABLE Method
09-07 10:33:19.032  1925  2279 D WfdsService: Set the WFDS Monitor: true
,09-07 10:33:19.032  1925  2279 D WfdsService: Connected to the supplicant for wfds
09-07 10:33:19.032  1925  2279 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 10:33:19.032  7099  7099 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-07 10:33:19.033  1925  2279 D WfdsService: selectPreferredScanChannel [36]
09-07 10:33:19.033  1925  2279 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 10:33:19.035  1043  1979 W libprocessgroup: failed to open /acct/uid_10080/pid_6114/cgroup.procs: No such file or directory
09-07 10:33:19.037  1043  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-07 10:33:19.037  1043  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 10:33:19.038  1043  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 10:33:19.038  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=183102  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-07 10:33:19.038  1043  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-07 10:33:19.038  1043  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 10:33:19.038  1043  1521 D LGWifiP2pService: before postfix = G3
09-07 10:33:19.038  1043  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:19.038  1043  1521 D WifiServerServiceExt: postfix byte check : 2
09-07 10:33:19.038  1043  1521 D LGWifiP2pService: after postfix = G3
09-07 10:33:19.038  1043  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-07 10:33:19.038  1043  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:19.039  1043  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:19.039  1043  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:19.039  1043  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:19.041  1043  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 10:33:19.041  1043  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 10:33:19.041  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 10:33:19.041  1925  1925 D WfdsService: isConnected: false
09-07 10:33:19.042  1043  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 10:33:19.042  1043  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 10:33:19.042  1043  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 10:33:19.042  1043  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-07 10:33:19.042  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.042  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.042  1043  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 10:33:19.042  1043  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-07 10:33:19.043  1043  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,09-07 10:33:19.043  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.045  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.045  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.045  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 10:33:19.045  1043  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,09-07 10:33:19.045  1043  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-07 10:33:19.046  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:19.046  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
09-07 10:33:19.046  1043  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
09-07 10:33:19.046  1043  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 10:33:19.046  1043  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-07 10:33:19.046  1043  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-07 10:33:19.046  1043  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-07 10:33:19.046  1043  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-07 10:33:19.047  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
09-07 10:33:19.048  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 10:33:19.048  1925  1925 D WfdsService: Update P2p Interface State: 3
09-07 10:33:19.066  1043  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-07 10:33:19.066  1043  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 10:33:19.066  1043  1521 D LGWifiP2pService: InactiveState
09-07 10:33:19.067  1043  1521 D LGWifiP2pService: InactiveState{ when=-63ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.067  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-63ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.067  1043  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 10:33:19.067  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-07 10:33:19.068  7099  7099 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.068  1925  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 10:33:19.068  1043  7109 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 10:33:19.068  1043  7109 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.068  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.068  7099  7099 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 10:33:19.068  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:19.068  7099  7099 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.069  1925  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:19.069  1043  7109 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:19.069  1043  7109 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.069  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.069  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.069  7099  7099 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.069  1925  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:19.069  1043  7109 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:19.069  1043  7109 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.069  1043  7109 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.069  1043  7109 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:19.070  1043  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-07 10:33:19.070  1043  1521 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=cz target=co,m.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.070  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.070  1043  1521 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.070  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.071  1043  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:33:19.071  1043  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.071  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.071  1043  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.071  1043  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:33:19.071  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.071  1043  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.071  1925  2279 W WfdsService: DefaultState - msg [9441285] is not handled
09-07 10:33:19.071  1043  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.071  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.072  1043  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.072  1043  1043 E WifiServerServiceExt: No p2p device connected
09-07 10:33:19.087  7115  7115 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:19.087  7115  7115 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 10:33:19.090  7115  7115 D PhoneMonitor: Register our PhoneStateListener
09-07 10:33:19.099  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-07 10:33:19.100  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-07 10:33:19.114  7115  7115 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-07 10:33:19.115  7115  7115 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-07 10:33:19.116  7115  7115 D TelephonyAutoProfiling: [parse] Load xml
,09-07 10:33:19.119  7115  7115 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-07 10:33:19.119  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-07 10:33:19.119  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-07 10:33:19.119  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-07 10:33:19.119  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-07 10:33:19.119  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-07 10:33:19.119  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-07 10:33:19.119  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-07 10:33:19.120  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-07 10:33:19.120  7115  7115 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-07 10:33:19.134  7115  7115 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-07 10:33:19.171  1043  1631 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7136 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 10:33:19.172  1043  1631 I ActivityManager: Killing 6133:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-07 10:33:19.217  1043  1871 W libprocessgroup: failed to open /acct/uid_10097/pid_6133/cgroup.procs: No such file or directory
,09-07 10:33:19.422  1043  1871 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7157 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-07 10:33:19.423  1043  1871 I ActivityManager: Killing 6601:com.lge.eula/1000 (adj 15): empty #17
,09-07 10:33:19.472  1043  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_6601/cgroup.procs: No such file or directory
,09-07 10:33:19.502  7099  7099 E wpa_supplicant: USIM:  scard_init function
09-07 10:33:19.502  7099  7099 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-07 10:33:19.506  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-07 10:33:19.506  1043  7109 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 10:33:19.506  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-07 10:33:19.506  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-07 10:33:19.506  1043  7109 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 10:33:19.506  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-07 10:33:19.506  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-07 10:33:19.509  1043  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-07 10:33:19.509  1043  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
,09-07 10:33:19.510  1043  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-07 10:33:19.511  1043  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-07 10:33:19.511  1043  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-07 10:33:19.517  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183581  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-07 10:33:19.522  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.522  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.522  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-07 10:33:19.523  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.523  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.525  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.527  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183591  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-07 10:33:19.534  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.534  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.534  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 10:33:19.535  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:19.535  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-07 10:33:19.547  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.547  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-07 10:33:19.550  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.601  1043  1708 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7181 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 10:33:19.604  1043  1708 I ActivityManager: Killing 6618:com.lge.bnr/1000 (adj 15): empty #17
09-07 10:33:19.631  7099  7099 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-07 10:33:19.632  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 10:33:19.632  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-07 10:33:19.632  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-07 10:33:19.632  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-07 10:33:19.633  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:19.633  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-07 10:33:19.635  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183699  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-07 10:33:19.635  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183699  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 10:33:19.636  1043  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183700
09-07 10:33:19.636  1043  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183700
09-07 10:33:19.637  1043  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183701
09-07 10:33:19.637  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183701
09-07 10:33:19.637  1043  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183702
09-07 10:33:19.638  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=183702  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 10:33:19.644  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:19.644  7099  7099 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 10:33:19.645  7099  7099 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 10:33:19.647  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:19.648  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,09-07 10:33:19.648  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 10:33:19.648  1043  7109 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 10:33:19.648  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 10:33:19.648  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 10:33:19.648  1043  7109 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 10:33:19.648  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:19.648  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:19.661  1043  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_6618/cgroup.procs: No such file or directory
,09-07 10:33:19.665  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 10:33:19.670  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=183734  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-07 10:33:19.675  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.675  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.675  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 10:33:19.677  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.677  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.678  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.678  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.678  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.678  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-07 10:33:19.679  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183743  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 10:33:19.680  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183744  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 10:33:19.681  1043  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183745
09-07 10:33:19.681  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.681  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.682  1043  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183746
09-07 10:33:19.682  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.682  1043  1523 D WifiNative-wlan0: doString: [STATUS]
09-07 10:33:19.682  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:19.682  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-07 10:33:19.683  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:19.683  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:19.684  1043  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 10:33:19.686  1043  1523 I WifiServiceExtension: setVHTCapabilityType  : false
,09-07 10:33:19.708  1043  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-07 10:33:19.708  1043  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-07 10:33:19.715  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.715  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.715  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 10:33:19.717  7181  7181 I art     : Almond Protected OAT
,09-07 10:33:19.725  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.725  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.721  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.725  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.725  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 10:33:19.726  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.728  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.728  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.730  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.731  1043  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 10:33:19.731  1043  1529 D ConnectivityService: Got NetworkAgent Messenger
09-07 10:33:19.731  1043  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:33:19.731  1043  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 10:33:19.731  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 10:33:19.731  1043  1529 D ConnectivityService: NetworkAgent connected
09-07 10:33:19.732  1043  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 10:33:19.732  1043  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 10:33:19.747  1043  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 10:33:19.747  1043  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:33:19.747  1043  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 10:33:19.748  1043  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 10:33:19.748  1043  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-07 10:33:19.756  1043  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 10:33:19.758   315   903 D CommandListener: Setting iface cfg
09-07 10:33:19.760  1043  1523 E WifiStateMachine: Start Dhcp Watchdog 2
09-07 10:33:19.760  1043  7207 D DhcpStateMachine: StoppedState
09-07 10:33:19.760  1043  7207 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:33:19.761  1043  7207 D DhcpStateMachine: WaitBeforeStartState
09-07 10:33:19.761  1043  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=183825  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:19.761  1043  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=183825  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-07 10:33:19.762  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=183826  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:19.763  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:19.763  1043  1043 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-07 10:33:19.764  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:19.764  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:19.765  1043  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:19.765  1043  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:19.766  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:19.766  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:19.767  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:19.767  1043  1043 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 10:33:19.768  1043  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:19.769  1043  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:19.769  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:19.771  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:138446] from screen [on:0 period:63417243] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-07 10:33:19.772  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:63417244] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-07 10:33:19.772  1043  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-07 10:33:19.775  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.777  1043  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-07 10:33:19.777  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.777  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.778  1043  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.778  1043  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.779  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.779  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.779  1043  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 10:33:19.780  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
09-07 10:33:19.780  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
09-07 10:33:19.780  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-07 10:33:19.781  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 10:33:19.781  1043  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-07 10:33:19.781  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 10:33:19.782  1043  1523 D WifiNative-wlan0: SET ps 0: returned true
09-07 10:33:19.782  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-07 10:33:19.782  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-07 10:33:19.782  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 10:33:19.783  1043  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3cb9a8d target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.783  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3cb9a8d target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.783  1043  7207 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.783  1043  7207 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 10:33:19.783  1043  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 10:33:19.783  1043  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 10:33:19.783  1043  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 10:33:19.783  7181  7181 D WeatherApplication: removeAccount
09-07 10:33:19.784   315   903 D CommandListener: Setting iface cfg
09-07 10:33:19.784   315   903 D CommandListener: Trying to bring up wlan0
09-07 10:33:19.785  1043  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 10:33:19.785  7181  7181 D WeatherApplication: Account.length = 0
09-07 10:33:19.786  7181  7181 E WeatherApplication: OPERATOR:OPEN
09-07 10:33:19.786  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:19.786  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 10:33:19.787  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:19.787  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-07 10:33:19.787  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.788  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.788  1043  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.788  1043  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.789  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.789  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:19.790  1043  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 10:33:19.790  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 10:33:19.791  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 10:33:19.791  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 10:33:19.791  1043  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.791  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.791  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 10:33:19.792  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 10:33:19.792  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-07 10:33:19.792  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 10:33:19.793  7181  7181 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:19
09-07 10:33:19.793  1043  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-07 10:33:19.793  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:19.796  7181  7181 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 10:33:19.797  7181  7181 D Weather.Utils: 2 : All the weather widget is gone.
09-07 10:33:19.799  7181  7181 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-07 10:33:19.802  7181  7181 D WeatherAncestor: connectivity changed - connection : true
09-07 10:33:19.804  7181  7181 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-07 10:33:19.812  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
09-07 10:33:19.813  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 10:33:19.813  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 10:33:19.813  1043  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 10:33:19.814  1043  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-07 10:33:19.814  1043  1529 D ConnectivityService: ignoring duplicate network state non-change
09-07 10:33:19.815  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 10:33:19.817  1043  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 10:33:19.819  1043  1529 D ConnectivityService: Adding iface wlan0 to network 101
09-07 10:33:19.819  7181  7181 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 10:33:19.819  7181  7181 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 10:33:19.819  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.819  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.819  7181  7181 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-07 10:33:19.820  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.827  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.827  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.827  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 10:33:19.834  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.834  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.834  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-07 10:33:19.834  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 10:33:19.838  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-07 10:33:19.849  1043  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 10:33:19.849  1043  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-07 10:33:19.850  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.850  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.850  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-07 10:33:19.851  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.851  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:19.852  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 10:33:19.853  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.853  1043  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-07 10:33:19.855   315   903 E Netd    : netlink response contains error (File exists)
09-07 10:33:19.855  1043  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-07 10:33:19.855  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.856  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 10:33:19.856  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.857  1043  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 10:33:19.857  1043  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-07 10:33:19.857  1043  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-07 10:33:19.857  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.857  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:19.857  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 10:33:19.859  1043  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 10:33:19.860  1043  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-07 10:33:19.860  1043  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 10:33:19.860  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.860  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 10:33:19.861  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.861  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 10:33:19.862  1043  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-07 10:33:19.863  1043  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:19.863  1043  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:19.863  1043  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 10:33:19.863  1043  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:19.863  1043  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRe,quest:true
09-07 10:33:19.863  1043  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-07 10:33:19.863  1043  1529 D ConnectivityService:    accepting network in place of null
09-07 10:33:19.863  1043  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:19.863  1043  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:19.863  1043  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:19.864  1043  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 10:33:19.864  1043  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 10:33:19.865  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 10:33:19.865  1043  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:19.865  1043  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 10:33:19.865  1043  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-07 10:33:19.866   315  7212 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,09-07 10:33:19.867  1834  1834 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:19.867  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 10:33:19.868  1043  1529 D ConnectivityService: validation of new default Network = false
09-07 10:33:19.868  1043  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 10:33:19.868  1043  1529 D DSQN    : enableDataServiceNotify 
09-07 10:33:19.868  1043  1529 D DSQN    : start dsqn bin
09-07 10:33:19.869  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 10:33:19.869  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 10:33:19.869  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 10:33:19.869  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 10:33:19.875  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:19.875  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 10:33:19.875  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:19.877  7181  7181 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 10:33:19.877  7181  7181 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:19
,09-07 10:33:19.879  1043  1521 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.879  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.879  1043  1521 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:19.884  1043  1961 I ActivityManager: Killing 2138:com.lge.music/u0a34 (adj 15): empty #17
09-07 10:33:19.884  1043  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-07 10:33:19.884  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:19.884  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:19.884  1043  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:19.885  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 10:33:19.883  7213  7213 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:19.883  7213  7213 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 10:33:19.901   320   320 V AudioFlinger: 2138 died, releasing its sessions
09-07 10:33:19.901   320   320 V AudioFlinger:  pid 1834 @ 0
09-07 10:33:19.901   320   320 V AudioFlinger:  pid 3486 @ 1
09-07 10:33:19.901   320   320 V AudioFlinger:  pid 3486 @ 2
09-07 10:33:19.904  7213  7213 E DSQN    : DSQN ssw
,09-07 10:33:19.914  1043  2015 W libprocessgroup: failed to open /acct/uid_10034/pid_2138/cgroup.procs: No such file or directory
,09-07 10:33:19.930   315  7212 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-07 10:33:19.952  1043  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 10:33:19.953  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 10:33:19.953  1043  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 10:33:19.954  1043  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 10:33:19.954  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-07 10:33:19.955  1043  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-07 10:33:19.964  1043  1631 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7218 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 10:33:19.968   315  7212 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-07 10:33:19.978  1043  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-07 10:33:19.985  1043  7207 D DhcpStateMachine: DHCPV4 request on wlan0
09-07 10:33:19.986  1043  7207 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 10:33:19.986  1043  7207 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-07 10:33:19.991   347   347 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.773ms total 23.507ms
09-07 10:33:19.983  7229  7229 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:19.983  7229  7229 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:19.992  1799  7217 I CheckinService: active receiver: enabled
09-07 10:33:19.997   315   902 D LGDataListener: argv[0]=dsqncommand
09-07 10:33:19.997   315   902 D LGDataListener: argv[1]=wlan0
09-07 10:33:19.997   315   902 D LGDataListener: argv[2]=1
09-07 10:33:19.997   315   902 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-07 10:33:19.997  1043  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-07 10:33:19.997  1043  1117 D DSQN    : start to monitor internet connection
09-07 10:33:20.006  7229  7229 I dhcpcd  : version 5.5.6 starting
09-07 10:33:20.008  7229  7229 E dhcpcd  : get_duid: m
09-07 10:33:20.008  7229  7229 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 10:33:20.008  7229  7229 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-07 10:33:20.012   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.147ms
,09-07 10:33:20.025  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 08:33:20 GMT], X-Android-Received-Millis=[1473237200025], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473237199996]}
,09-07 10:33:20.027  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-07 10:33:20.027  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-07 10:33:20.027  1043  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-07 10:33:20.027  1043  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-07 10:33:20.027  1043  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:20.027  1043  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:20.027  1043  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 10:33:20.027  1043  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-07 10:33:20.028  1043  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-07 10:33:20.028  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:20.028  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:20.028  1043  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:20.029  1043  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:20.029  1043  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:20.030  1043  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:20.030  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 10:33:20.030  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 10:33:20.030   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 17.264ms
09-07 10:33:20.031  1834  1834 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:20.032  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-07 10:33:20.045  1799  7217 I CheckinService: Preparing to send checkin request
09-07 10:33:20.045  1799  7217 I EventLogService: Accumulating logs since 1473237073945
09-07 10:33:20.055  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:20.056  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:20.056  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:20.074  7229  7229 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 10:33:20.074  7229  7229 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 10:33:20.074  7229  7229 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 10:33:20.074  7229  7229 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-07 10:33:20.074  7229  7229 D dhcpcd  : wlan0: sending REQUEST (xid 0xb2cbb8ab), next in 4.10 seconds
,09-07 10:33:20.081  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:20.082  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:20.082  1799  7217 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-07 10:33:20.083  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:20.111  7229  7229 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-07 10:33:20.125   280   422 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 10:33:20.125   280   422 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 10:33:20.125   280   422 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:33:20.126  7218  7246 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-07 10:33:20.127   280   422 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 10:33:20.127   280   422 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 10:33:20.127   280   422 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 10:33:20.127  7218  7246 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-07 10:33:20.134   280   422 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 10:33:20.134   280   422 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-07 10:33:20.134   280   422 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 10:33:20.135  7218  7248 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-07 10:33:20.136   280   422 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-07 10:33:20.136   280   422 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-07 10:33:20.136   280   422 W Vold    : Returning OperationFailed - no handler for errno 0
09-07 10:33:20.137  7218  7248 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-07 10:33:20.140  7229  7229 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 10:33:20.140  7229  7229 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-07 10:33:20.141  7229  7229 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-07 10:33:20.141  7229  7229 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,09-07 10:33:20.141  7229  7229 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 10:33:20.141  7229  7229 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 10:33:20.188  1043  1979 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7252 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-07 10:33:20.200  7229  7229 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 10:33:20.200  7229  7229 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-07 10:33:20.244  7252  7252 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-07 10:33:20.245  7252  7252 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-07 10:33:20.278  7252  7252 I MultiDex: VM with version 2.1.0 has multidex support
09-07 10:33:20.278  7252  7252 I MultiDex: install
09-07 10:33:20.278  7252  7252 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-07 10:33:20.287  7252  7252 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-07 10:33:20.305  7218  7218 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-07 10:33:20.312  7218  7218 I LibraryLoader: Loading: webviewchromium
09-07 10:33:20.315  7218  7218 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4391-4394)
09-07 10:33:20.315  7218  7218 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 10:33:20.322  7218  7218 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28be133a}
09-07 10:33:20.323  7218  7218 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 10:33:20.323  7218  7218 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 10:33:20.335  7218  7218 I BrowserStartupController: Initializing chromium process, renderers=0
09-07 10:33:20.336  7218  7218 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 10:33:20.346  7218  7218 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-07 10:33:20.347  7218  7218 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-07 10:33:20.347  7218  7218 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-07 10:33:20.349   320  2128 V AudioPolicyService: registerClient() client 0xb1427180, uid 10093
09-07 10:33:20.350  7218  7305 W AudioManagerAndroid: Requires BLUETOOTH permission
09-07 10:33:20.359  7218  7218 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:20.359  7218  7218 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:20.359  7218  7218 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:20.359  7218  7218 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:20.359  7218  7218 I Adreno-EGL: Remote Branch: 
09-07 10:33:20.359  7218  7218 I Adreno-EGL: Local Patches: 
09-07 10:33:20.359  7218  7218 I Adreno-EGL: Reconstruct Branch: 
,09-07 10:33:20.388  1043  7207 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-07 10:33:20.390  1043  7207 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-07 10:33:20.390  1043  7207 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 10:33:20.390  1043  7207 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 10:33:20.390  1043  7207 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-07 10:33:20.390  1043  7207 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 10:33:20.390  1043  7207 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-07 10:33:20.390  1043  7207 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 10:33:20.391  1043  7207 D DhcpStateMachine: RunningState
09-07 10:33:20.444  7218  7218 I NSApplication: Starting up...
,09-07 10:33:20.534  1043  1559 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7321 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-07 10:33:20.536  1043  1559 I ActivityManager: Killing 6069:com.android.vending/u0a44 (adj 15): empty #17
,09-07 10:33:20.677  1043  1708 W libprocessgroup: failed to open /acct/uid_10044/pid_6069/cgroup.procs: No such file or directory
,09-07 10:33:20.719  7321  7321 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 10:33:20.753  7338  7338 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-07 10:33:20.822  7338  7338 I dex2oat : dex2oat took 68.661ms (threads: 4)
,09-07 10:33:20.849  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:20.849  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:20.849  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:20.849  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:20.849  7252  7270 I Adreno-EGL: Remote Branch: 
09-07 10:33:20.849  7252  7270 I Adreno-EGL: Local Patches: 
09-07 10:33:20.849  7252  7270 I Adreno-EGL: Reconstruct Branch: 
,09-07 10:33:20.886  1043  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 10:33:20.934  1043  1861 I art     : Explicit concurrent mark sweep GC freed 99732(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.453ms total 111.753ms
,09-07 10:33:20.953  1043  1559 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 10:33:20.953  1043  1559 D WifiService: setWifiEnabled: false pid=6729, uid=10118
09-07 10:33:20.953  1043  1559 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 10:33:20.963  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:20.963  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:20.963  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:20.963  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:20.963  7252  7270 I Adreno-EGL: Remote Branch: 
09-07 10:33:20.963  7252  7270 I Adreno-EGL: Local Patches: 
09-07 10:33:20.963  7252  7270 I Adreno-EGL: Reconstruct Branch: 
,09-07 10:33:20.971  1043  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:20.971  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:20.971  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:20.971  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,09-07 10:33:20.971  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:20.972  1043  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:20.973  1043  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:20.973  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-07 10:33:20.973  1043  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 10:33:20.973  1043  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:33:20.973  1043  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 10:33:20.974  1043  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 10:33:20.974  1043  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 10:33:20.980  1043  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 10:33:20.980  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 10:33:20.980  1043  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:20.980  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:20.981  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 10:33:20.981  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 10:33:20.981  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:20.981  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
,09-07 10:33:20.982   315   903 D CommandListener: Clearing all IP addresses on wlan0
09-07 10:33:20.982  1043  7207 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.007  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 10:33:21.007  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-07 10:33:21.014  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-07 10:33:21.014  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.014  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.014  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:21.018  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:21.018  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:21.019  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-07 10:33:21.021  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.026  1043  1521 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.026  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.026  1043  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3540a5d9
09-07 10:33:21.026  1043  1521 D LGWifiP2pService: P2pDisablingState
09-07 10:33:21.026  1043  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.026  1043  1521 D LGWifiP2pService: p2p socket connection lost
09-07 10:33:21.026  1043  1521 D LGWifiP2pService: P2pDisabledState
09-07 10:33:21.026  1043  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:21.027  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:21.027  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-07 10:33:21.027  1043  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:21.028  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:21.028  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:21.031  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-07 10:33:21.034  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.034  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.034  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:21.034  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 10:33:21.034  1043  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.035  1043  1043 D RttService: SCAN_AVAILABLE : 1
09-07 10:33:21.035  1043  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.036  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 10:33:21.036  1925  1925 D WfdsService: WifiP2pState is changed : false
09-07 10:33:21.036  1925  2279 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-07 10:33:21.036  1925  2279 D WfdsService: Set the WFDS Monitor: false
09-07 10:33:21.037  1925  2279 D WfdsMonitor: WFDS Monitor is stopped
09-07 10:33:21.037  1925  2279 D WfdsService: STATE : WfdsDisabledState - enter
09-07 10:33:21.037  1925  7128 D CtrlSupplicant: Received on exit socket, terminate
09-07 10:33:21.037  1925  7128 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-07 10:33:21.037  1925  7128 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-07 10:33:21.038  1925  7128 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-07 10:33:21.038  1925  2280 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-07 10:33:21.038  1925  2279 W WfdsService: DefaultState - msg [9445378] is not handled
09-07 10:33:21.040  1043  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-07 10:33:21.040  1043  1529 D DSQN    : disableDataServiceNotify
09-07 10:33:21.040  1043  1529 D DSQN    : stop dsqn bin
09-07 10:33:21.045  7252  7270 D LgDataFeature: LgDataFeature() Constructor: none
,09-07 10:33:21.045  7252  7270 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 10:33:21.046  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:21.046  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:21.047  1043  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 10:33:21.047  1043  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-07 10:33:21.047  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:21.047  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:21.048  1043  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:21.048  1043  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-07 10:33:21.048  1043  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-07 10:33:21.048  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 10:33:21.048  1043  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.048  1043  1521 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.049  1043  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-07 10:33:21.049  1043  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 10:33:21.049  7099  7099 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-07 10:33:21.049  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 10:33:21.049  1043  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:21.049  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 10:33:21.049  1043  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 10:33:21.049  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.049  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.049  1043  7206 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 10:33:21.050  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 10:33:21.050  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:21.050  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
09-07 10:33:21.050  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 10:33:21.050   315   903 D Comm,andListener: Clearing all IP addresses on wlan0
09-07 10:33:21.051  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 10:33:21.051  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.051  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 10:33:21.051  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 10:33:21.051  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 10:33:21.053  1043  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:21.053  1043  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:21.053  1043  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:21.054  1043  1523 D WifiNative-p2p0: doBoolean: TERMINATE
09-07 10:33:21.054  1043  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-07 10:33:21.054  1043  1523 D WifiNative-p2p0: TERMINATE: returned true
09-07 10:33:21.054  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:21.054  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:21.054  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 10:33:21.054  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-07 10:33:21.054  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 10:33:21.054  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 10:33:21.054  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 10:33:21.054  1043  1529 D NetworkManagementService: Removing idletimer
09-07 10:33:21.054  1043  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.055  1043  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 10:33:21.055  1834  1834 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:21.055  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 10:33:21.056  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-07 10:33:21.057  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.057  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.057  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:21.061  1043  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:21.061  1043  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-07 10:33:21.063  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-07 10:33:21.066  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:21.066  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:21.066  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:21.066  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:21.066  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:21.066  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:21.066  7252  7270 I Adreno-EGL: Remote Branch: 
09-07 10:33:21.066  7252  7270 I Adreno-EGL: Local Patches: 
09-07 10:33:21.066  7252  7270 I Adreno-EGL: Reconstruct Branch: 
09-07 10:33:21.066  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:21.066  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:21.066  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-07 10:33:21.066  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:21.066  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-07 10:33:21.067  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:21.067  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:21.067  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:21.067  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:21.082  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action ,'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 10:33:21.083  6449  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-07 10:33:21.092  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:21.092  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.093  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:21.105  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:21.112  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 10:33:21.112  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:21.112  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 10:33:21.112  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-07 10:33:21.115  7043  7043 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 10:33:21.118  7099  7099 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 10:33:21.118  7099  7099 I wpa_supplicant: monitor socket send errors count : 1
09-07 10:33:21.118  7099  7099 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
09-07 10:33:21.118  1043  7109 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-07 10:33:21.118  1043  7109 D WifiMonitor: Dropping event because (p2p0) is stopped
09-07 10:33:21.120  7043  7043 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31e99183
09-07 10:33:21.120  7043  7043 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 10:33:21.120  7043  7043 D AppUp4:CustFacade: isPhone : true
09-07 10:33:21.120  7043  7043 D AppUp4:CustModeStarterReceiver: begin check event
09-07 10:33:21.121  7043  7043 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 10:33:21.123  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:21.124  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 10:33:21.126  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:21.128  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:21.130  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:21.131  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.131  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.131  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 10:33:21.131  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:21.132  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.133  4278  7358 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 10:33:21.133  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.134  4278  7359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:21.134  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-07 10:33:21.134  4278  7359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 10:33:21.152  7065  7361 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.156  7099  7099 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 10:33:21.156  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-07 10:33:21.156  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 10:33:21.156  1043  7109 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 10:33:21.157  1043  7109 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-07 10:33:21.157  7099  7099 W wpa_supplicant: USIM:  scard_deinit function
09-07 10:33:21.158  1043  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185222
09-07 10:33:21.158  1043  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185222
09-07 10:33:21.159  1043  1119 D Tethering: InitialState.processMessage what=4
09-07 10:33:21.160  3486  3486 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 10:33:21.160  3486  3486 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:21.160  3486  3486 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 10:33:21.160  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:21.160  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:21.161  1043  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:21.161  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:21.161  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:33:21.162  1043  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185225  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 10:33:21.162  1043  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185226  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-07 10:33:21.164  6960  7365 W FormManager: Network not available. Please check & try again.
09-07 10:33:21.164  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 10:33:21.165  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 10:33:21.170  6960  7366 V FormManager: Network unavailable.
,09-07 10:33:21.173  7181  7181 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:21
,09-07 10:33:21.175  6960  7366 V FormManager: Network unavailable.
,09-07 10:33:21.175  7181  7181 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 10:33:21.175  7181  7181 D Weather.Utils: 2 : All the weather widget is gone.
09-07 10:33:21.176  7181  7181 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 10:33:21.176  7181  7181 D WeatherAncestor: connectivity changed - connection : true
09-07 10:33:21.176  7181  7181 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29179339
09-07 10:33:21.176  7181  7181 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 10:33:21.176  7181  7181 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 10:33:21.177  7181  7181 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 10:33:21.177  7181  7181 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 10:33:21.177  7181  7181 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:21
09-07 10:33:21.192  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 10:33:21.192  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 10:33:21.192  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 10:33:21.192  6836  6836 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 10:33:21.193  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 10:33:21.193  1043  7207 D DhcpStateMachine: StoppedState
09-07 10:33:21.193  1043  7207 D DhcpStateMachine: StoppedState{ when=-143ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:21.193  6836  6836 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 10:33:21.193  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 10:33:21.193  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 10:33:21.193  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 10:33:21.193  6836  6836 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 10:33:21.193  1043  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-07 10:33:21.194  6836  6836 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 10:33:21.194  1043  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-07 10:33:21.199  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:21.202  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:33:21.208  6960  7371 W FormManager: Network not available. Please check & try again.
09-07 10:33:21.209  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.214  6960  7372 V FormManager: Network unavailable.
09-07 10:33:21.216  6960  7372 V FormManager: Network unavailable.
,09-07 10:33:21.222  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:21.224  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 10:33:21.226  6960  7374 W FormManager: Network not available. Please check & try again.
09-07 10:33:21.229  6960  7375 V FormManager: Network unavailable.
09-07 10:33:21.230  6960  7375 V FormManager: Network unavailable.
,09-07 10:33:21.236  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.244  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 10:33:21.244  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 10:33:21.245  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:21.247  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 10:33:21.251  4278  7376 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 10:33:21.252  4278  7377 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 10:33:21.252  4278  7377 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 10:33:21.281  1043  2015 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7378 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-07 10:33:21.308  7099  7099 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 10:33:21.308  1043  7109 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-07 10:33:21.308  1043  7109 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-07 10:33:21.308  1043  7109 D WifiMonitor: Disconnecting from the supplicant, no more events
09-07 10:33:21.308  1043  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,09-07 10:33:21.339  7378  7378 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 10:33:21.339  7378  7378 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-07 10:33:21.343  7378  7378 V [BNRBootReceiver]: Boot Receiver Return
09-07 10:33:21.345  7378  7378 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 10:33:21.345  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.351  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.356  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.366  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:21.366  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:21.367  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 10:33:21.369  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-07 10:33:21.372  6836  6836 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 10:33:21.374  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.378  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.383  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.388  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:21.388  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.389  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 10:33:21.392  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:21.397  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 10:33:21.401  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.405  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:21.405  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.406  6902  6902 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:21.408  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.409  1925  1925 D WfdsService: Supplicant Connection state is changed : false
09-07 10:33:21.409  1043  1523 D WifiOffDelayIfNotUsed: stopMonitoring
09-07 10:33:21.409  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:21.409  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:21.409  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-07 10:33:21.409  1925  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-07 10:33:21.409  1925  2279 D WfdsService: Set the WFDS Monitor: false
09-07 10:33:21.410  1925  2279 D WfdsMonitor: WFDS Monitor is stopped
09-07 10:33:21.410  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-07 10:33:21.411  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:21.412  2471  2471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:21.414  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:21.414  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-07 10:33:21.414  1043  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-07 10:33:21.414  1043  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-07 10:33:21.415  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:21.415  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.421  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.425  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:21.426  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.426  6902  6902 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:21.430  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.436  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.443  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.446   315  7397 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 10:33:21.446  1043  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-07 10:33:21.447  1799  7217 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-07 10:33:21.447  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:21.448  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.448  6902  6902 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 10:33:21.451  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.458  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 10:33:21.458  1799  7217 I CheckinService: active receiver: disabled
,09-07 10:33:21.463  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.474  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:21.475  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.475  6902  6902 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:21.478  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.484  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.489  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 10:33:21.496  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:21.496  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.497  6902  6902 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 10:33:21.508  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:21.522  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.528  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 10:33:21.541  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:21.541  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:21.550  6902  6902 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 10:33:21.560  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:21.581  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.595  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.613  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:21.614  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:21.619  6902  6902 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:21.631  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:21.647  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-07 10:33:21.676  1043  1528 D WifiService: New client listening to asynchronous messages
,09-07 10:33:21.678  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 10:33:21.689  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.705  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 10:33:21.705  1043  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=891625733, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1043
,09-07 10:33:21.740  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:21.744  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.746  6902  6902 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 10:33:21.748  6902  6902 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 10:33:21.749  6902  6902 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 10:33:21.758  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:21.765  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-07 10:33:21.769  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:21.782  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.790  2565  2565 D [Concierge]Service: onStartCommand(). Type : 9
,09-07 10:33:21.801  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.813  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:21.813  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.814  6902  6902 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 10:33:21.815  6902  6902 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 10:33:21.815  6902  6902 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-07 10:33:21.819  1043  1943 I ActivityManager: Killing 6877:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-07 10:33:21.852  1043  1631 W libprocessgroup: failed to open /acct/uid_10037/pid_6877/cgroup.procs: No such file or directory
,09-07 10:33:21.857  2066  2066 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-07 10:33:21.873  2066  2066 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-07 10:33:21.873  2066  2066 D c       : Getting all permits...
09-07 10:33:21.873  2066  2066 D a       : Opening database...
,09-07 10:33:21.878  2066  2066 D a       : Opening database auth.proximity.permit_store...
,09-07 10:33:21.879  2066  2066 D a       : Closing database...
09-07 10:33:21.889  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:21.894  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 10:33:21.894  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 10:33:21.894  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:21.898  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.904  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-07 10:33:21.912  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:21.912  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.914  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-07 10:33:21.919  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.922  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-07 10:33:21.923  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 10:33:21.923  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:21.927  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.934  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.944  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:21.945  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.947  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 10:33:21.953  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:21.960  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-07 10:33:21.960  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 10:33:21.960  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:21.962  6639  7023 D UEI.SmartControl: Internal timer expired: 2
09-07 10:33:21.962  6639  7023 D UEI.SmartControl: unbind internal service
09-07 10:33:21.967  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:21.981  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:21.992  6902  6902 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:21.993  6902  6902 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:21.997  6902  6902 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-07 10:33:22.012  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 10:33:22.022  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:33:22.029  6960  7405 W FormManager: Network not available. Please check & try again.
09-07 10:33:22.033  6960  7406 V FormManager: Network unavailable.
,09-07 10:33:22.036  6960  7406 V FormManager: Network unavailable.
09-07 10:33:22.037  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:22.043  6639  7017 D serial_port: close(fd = 24)
,09-07 10:33:22.047  6639  7017 I UEI.SmartControl: Serial port is closed.
09-07 10:33:22.056  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 10:33:22.056  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-07 10:33:22.058  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:22.061  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:22.066  4278  7407 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 10:33:22.068  4278  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-07 10:33:22.069  4278  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 10:33:22.070  6855  6855 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-07 10:33:22.070  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-07 10:33:22.070  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 10:33:22.074  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 10:33:22.082  6960  7410 W FormManager: Network not available. Please check & try again.
09-07 10:33:22.084  6960  7411 V FormManager: Network unavailable.
,09-07 10:33:22.086  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:22.087  6960  7411 V FormManager: Network unavailable.
09-07 10:33:22.102  2066  2066 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-07 10:33:22.118  6902  6902 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-07 10:33:22.119  6902  6902 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8355
09-07 10:33:22.119  1043  1043 D PowerManagerServiceEx: releaseWakeLockInternal: lock=891625733 [*alarm*], flags=0x0
,09-07 10:33:22.780  1043  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:63420251] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-07 10:33:22.788  1043  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:63420260] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 10:33:22.868  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:22.881  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 10:33:22.890  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:22.894  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:22.898  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:22.900  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 10:33:22.902  6449  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-07 10:33:22.916  5741  5741 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 10:33:22.932  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:22.954  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 10:33:22.954  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:22.954  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 10:33:22.954  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-07 10:33:22.959  7043  7043 I AppUp4:CustModeStarterReceiver: onReceive
09-07 10:33:22.963  7043  7043 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31e99183
09-07 10:33:22.963  7043  7043 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 10:33:22.963  7043  7043 D AppUp4:CustFacade: isPhone : true
09-07 10:33:22.963  7043  7043 D AppUp4:CustModeStarterReceiver: begin check event
09-07 10:33:22.964  7043  7043 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 10:33:22.968  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:22.968  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 10:33:22.970  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 10:33:22.976  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:22.983  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 10:33:23.006  4278  7420 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 10:33:23.013  7065  7419 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:23.022  4278  7421 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:23.022  4278  7421 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-07 10:33:23.044  3486  3486 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 10:33:23.045  3486  3486 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:23.045  3486  3486 I LgeMiscReceiver: networkInfo.isConnected() = true
09-07 10:33:23.045  3486  3486 D PhoneState: setPdpRejectCasuse : false
,09-07 10:33:23.050  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 10:33:23.051  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 10:33:23.062  7181  7181 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:23
,09-07 10:33:23.066  7181  7181 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 10:33:23.066  7181  7181 D Weather.Utils: 2 : All the weather widget is gone.
09-07 10:33:23.067  7181  7181 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 10:33:23.067  7181  7181 D WeatherAncestor: connectivity changed - connection : true
09-07 10:33:23.067  7181  7181 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29179339
09-07 10:33:23.068  7181  7181 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 10:33:23.068  7181  7181 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 10:33:23.068  7181  7181 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 10:33:23.068  7181  7181 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 10:33:23.068  7181  7181 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:23
09-07 10:33:23.081  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 10:33:23.088  6960  7423 V FormManager: Network unavailable.
09-07 10:33:23.093  6960  7423 V FormManager: Network unavailable.
09-07 10:33:23.093  6960  7422 W FormManager: Network not available. Please check & try again.
,09-07 10:33:23.973  1043  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:23.973  1043  1870 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-07 10:33:23.998  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:23.999  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:23.999  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-07 10:33:24.000  1043  1119 D BluetoothManagerService: Message: 1
09-07 10:33:24.000  1043  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-07 10:33:24.025  1043  1119 D BluetoothManagerService: Message: 20
09-07 10:33:24.025  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33ab302:true
,09-07 10:33:24.029  6983  6983 D BluetoothAdapterState: make
09-07 10:33:24.034  6983  6983 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 10:33:24.034  6983  6983 I bluedroid-qcom: init
09-07 10:33:24.041  6983  7442 I BluetoothAdapterState: Entering OffState
,09-07 10:33:24.043  6983  6983 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 10:33:24.044  6983  6983 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 10:33:24.044  6983  6983 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 10:33:24.044  6983  6983 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 10:33:24.044  6983  6983 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 10:33:24.046  6983  6983 I bluedroid-qcom: get_profile_interface socket
09-07 10:33:24.046  6983  6983 I bluedroid-qcom: get_profile_interface map_client
09-07 10:33:24.047  6983  7446 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 10:33:24.050  6983  7446 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 10:33:24.043  7445  7445 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:24.043  7445  7445 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:24.061  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:24.065  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.066  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-07 10:33:24.073  7445  7445 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-07 10:33:24.073  7445  7445 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 10:33:24.073  7445  7445 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-07 10:33:24.075  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:24.077  7445  7445 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-07 10:33:24.080  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:24.082  7445  7445 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 10:33:24.082  7445  7445 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-07 10:33:24.090  1043  1119 D Tethering: MasterInitialState.processMessage what=3
,09-07 10:33:24.097  6983  7446 D BluetoothAdapterProperties: Name is: G3
09-07 10:33:24.102  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:24.104  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:24.106  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 10:33:24.106  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 10:33:24.107  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 10:33:24.107  1043  1119 D BluetoothManagerService: Message: 40
09-07 10:33:24.107  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 10:33:24.108  6983  7000 I bluedroid-qcom: config_hci_snoop_log
09-07 10:33:24.110  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 10:33:24.110  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 10:33:24.115  6983  7442 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-07 10:33:24.116  6983  7442 D BluetoothAdapterProperties: Setting state to 11
09-07 10:33:24.116  6983  7442 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-07 10:33:24.120  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:24.120  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 10:33:24.120  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-07 10:33:24.123  6983  7442 I LGBluetoothServiceJni: classInitNative: succeeds
09-07 10:33:24.137  6983  7442 D BluetoothBondStateMachine: make
,09-07 10:33:24.141  6983  7442 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.141  6983  7442 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-07 10:33:24.141  6983  7442 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.141  6983  7442 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 10:33:24.142  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:24.143  6983  7459 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 10:33:24.143  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-07 10:33:24.143  6983  7442 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-07 10:33:24.144  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 10:33:24.145  6449  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 10:33:24.147  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:24.149  6836  6836 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-07 10:33:24.150  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:24.151  6983  7442 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:24.154  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:24.162  5741  5741 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-07 10:33:24.165  6983  7442 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 10:33:24.168  6983  6983 D HeadsetService: Received start request. Starting profile...
09-07 10:33:24.169  6983  6983 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 10:33:24.169  6983  6983 D LGBluetoothHfpAdapter: Version 1.6
09-07 10:33:24.173  6983  6983 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 10:33:24.174  6983  6983 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 10:33:24.174  6983  6983 D HeadsetStateMachine: make
09-07 10:33:24.176  5741  5741 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-07 10:33:24.185  6983  7442 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:24.195  6983  7442 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 10:33:24.197  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.202  6983  7442 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:24.206  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.209  6983  7442 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 10:33:24.216  6983  6983 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:24.216  6983  6983 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 10:33:24.217  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:24.218  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:24.219  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-07 10:33:24.219  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.220  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 10:33:24.220  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 10:33:24.222  6983  6983 D HeadsetStateMachine: max_hf_connections = 1
09-07 10:33:24.222  6983  7442 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:24.222  6983  6983 I bluedroid-qcom: get_profile_interface handsfree
09-07 10:33:24.224  7043  7043 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 10:33:24.224  6983  6983 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-07 10:33:24.225   320  1368 V AudioPolicyService: registerClient() client 0xb558ad80, uid 1002
09-07 10:33:24.226   320   320 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 10:33:24.226   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 10:33:24.226   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 10:33:24.226  6983  6983 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 10:33:24.226   320  2128 V AudioFlinger: registerClient() client 0xb14330a0, pid 6983
09-07 10:33:24.227  6983  6983 V ToneGenerator: Create Track: 0xb4928a80
09-07 10:33:24.227  6983  6983 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 10:33:24.227  6983  6983 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 10:33:24.227   320  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 10:33:24.227   320  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 10:33:24.227   320  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 10:33:24.227   320  1369 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 10:33:24.227   320  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:24.227   320  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:24.227  1043  1907 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:24.227  1043  1907 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:24.227  1586  1602 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:24.227  1586  1602 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:24.227  6983  6983 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 10:33:24.228  6983  6999 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:24.228  6983  6999 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 10:33:24.228  3486  3501 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:24.228  3486  3501 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:24.228   320  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:24.228   320  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:24.228  1043  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:24.228  1043  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:24.228  1586  2248 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:24.228  1586  2248 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:24.228  1834  3538 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:24.228  6983  6999 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:24.228  1834  3538 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:24.228  6983  6999 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 10:33:24.228  1834  3538 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:24.228  1834  3538 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:24.229  3486  3501 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:24.229  3486  3501 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:24.229   320   320 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 10:33:24.229   320  2128 V AudioPolicyManag,er: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 10:33:24.229   320  2128 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-07 10:33:24.229   320  2128 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 10:33:24.230   320  2128 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 10:33:24.230  6983  6983 V AudioSystem: getLatency() output 2, latency 50
09-07 10:33:24.230  6983  6983 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 10:33:24.230  6983  6983 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 10:33:24.230   320  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 10:33:24.230   320  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 10:33:24.230   320  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 10:33:24.230   320  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 10:33:24.230   320  2117 V AudioFlinger: createTrack() lSessionId: 22
09-07 10:33:24.232  6983  6983 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 10:33:24.233   320  2128 V AudioFlinger: acquiring 22 from 6983, for 6983
09-07 10:33:24.233   320  2128 V AudioFlinger:  added new entry for 22
09-07 10:33:24.233  6983  6983 V ToneGenerator: ToneGenerator INIT OK, time: 188312
09-07 10:33:24.233  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.234  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.235  6983  6983 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 10:33:24.236  6983  6983 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:24.236  6983  6983 V BluetoothPbapReceiver: ***********state = 11
,09-07 10:33:24.239  6983  7442 V LGMDMManager: Create singleton instance
09-07 10:33:24.239  6983  6983 D A2dpService: Received start request. Starting profile...
09-07 10:33:24.240  6983  6983 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 10:33:24.241  6983  6983 V Avrcp   : make
09-07 10:33:24.241  6983  6983 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 10:33:24.241  6983  6983 I bluedroid-qcom: get_profile_interface avrcp
09-07 10:33:24.242  6983  7464 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 10:33:24.242  6983  7464 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 10:33:24.242  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:33:24.242  6983  7464 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 10:33:24.242  6983  7464 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 10:33:24.242   320  1368 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6983
09-07 10:33:24.242   320  1368 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-07 10:33:24.242   320  1368 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 10:33:24.242   320  1368 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-07 10:33:24.243   320  1368 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 10:33:24.243   320  1368 V voice   : voice_set_parameters: exit with code(0)
09-07 10:33:24.243   320  1368 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 10:33:24.243   320  1368 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 10:33:24.243   320  1368 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 10:33:24.243   320  1368 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 10:33:24.243   320  1368 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 10:33:24.243   320  1368 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 10:33:24.243  6983  7464 V ToneGenerator: ToneGenerator destructor
09-07 10:33:24.243  6983  7464 V ToneGenerator: stopTone
09-07 10:33:24.243  6983  7464 V ToneGenerator: Delete Track: 0xb4928a80
09-07 10:33:24.243  6983  7442 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 10:33:24.243  7043  7043 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31e99183
09-07 10:33:24.243  6983  7464 V AudioTrack: ~AudioTrack, releasing session id from 6983 on behalf of 6983
09-07 10:33:24.243   320  1369 V AudioFlinger: releasing 22 from 6983 for 6983
09-07 10:33:24.243   320  1369 V AudioFlinger:  decremented refcount to 0
09-07 10:33:24.243   320  1369 V AudioFlinger: purging stale effects
09-07 10:33:24.243   320  1369 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 10:33:24.243   320  1369 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-07 10:33:24.243   320  1369 V AudioFlinger: PlaybackThread::Track destructor
09-07 10:33:24.243   320  1272 V AudioPolicyService: AudioCommandThread() waking up
09-07 10:33:24.243   320  1369 V AudioFlinger: removeClient_l() pid 6983, calling pid 320
09-07 10:33:24.243   320  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 10:33:24.244   320  1272 V AudioPolicyManager: releaseOutput() 2
09-07 10:33:24.244   320  1272 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 10:33:24.244  7043  7043 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 10:33:24.244  7043  7043 D AppUp4:CustFacade: isPhone : true
09-07 10:33:24.244  7043  7043 D AppUp4,:CustModeStarterReceiver: begin check event
09-07 10:33:24.244  7043  7043 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 10:33:24.254  6983  6983 V AudioManager: registerRemoteController: size of Media player list: 0
,09-07 10:33:24.256  6983  6983 E AudioManager: No RCC entry present to update
09-07 10:33:24.256  6983  6983 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 10:33:24.260  6983  6983 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 10:33:24.261  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 10:33:24.261  6983  6983 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 10:33:24.271  1043  1906 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7469 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-07 10:33:24.273  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 10:33:24.274  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.274  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 10:33:24.278  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:24.329  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 10:33:24.361  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 10:33:24.372  4278  7488 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.373  4278  7488 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 10:33:24.382  4278  7487 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-07 10:33:24.401  3486  3486 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 10:33:24.401  3486  3486 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.401  3486  3486 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-07 10:33:24.402  7065  7489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:24.404  6960  7491 W FormManager: Network not available. Please check & try again.
09-07 10:33:24.411  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 10:33:24.411  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 10:33:24.425  7181  7181 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:24
,09-07 10:33:24.426  1043  1059 V SIM_STK : Menu title from STK is T-Mobile
09-07 10:33:24.426  1043  1059 V SIM_STK : Menu title from STK is T-Mobile
09-07 10:33:24.427  6960  7492 V FormManager: Network unavailable.
09-07 10:33:24.428  7181  7181 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 10:33:24.428  7181  7181 D Weather.Utils: 2 : All the weather widget is gone.
09-07 10:33:24.428  7181  7181 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 10:33:24.429  7181  7181 D WeatherAncestor: connectivity changed - connection : true
09-07 10:33:24.430  7181  7181 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29179339
09-07 10:33:24.430  7181  7181 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 10:33:24.431  7181  7181 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 10:33:24.431  7181  7181 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 10:33:24.431  7181  7181 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 10:33:24.431  7181  7181 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:24
09-07 10:33:24.431  6960  7492 V FormManager: Network unavailable.
09-07 10:33:24.436  7469  7469 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-07 10:33:24.437  7469  7469 W LG Account v2.2: No ProfileInfo entries
09-07 10:33:24.437  7469  7469 I LG Account v2.2: isEnabled: false
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Country: EU
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Operator: OPEN
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Ranking support: false
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Comfort support: false
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Accessory: true
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Health device: true
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Extra Pedometer: false
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Blood glucose device: false
09-07 10:33:24.437  7469  7469 I Feature : [Lifetracker]Device Number: 3
,09-07 10:33:24.449  6836  6836 D BluetoothPermissionRequest: onReceive
09-07 10:33:24.454  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 10:33:24.466  6449  6449 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-07 10:33:24.468  6449  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-07 10:33:24.478  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:24.496  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-07 10:33:24.496  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.496  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-07 10:33:24.496  7043  7043 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-07 10:33:24.497  7043  7043 I AppUp4:CustModeStarterReceiver: onReceive
09-07 10:33:24.500  7043  7043 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31e99183
09-07 10:33:24.501  7043  7043 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 10:33:24.501  7043  7043 D AppUp4:CustFacade: isPhone : true
09-07 10:33:24.501  7043  7043 D AppUp4:CustModeStarterReceiver: begin check event
09-07 10:33:24.501  7043  7043 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-07 10:33:24.505  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.505  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 10:33:24.507  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-07 10:33:24.508  1043  1708 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-07 10:33:24.509  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:24.513  4278  7497 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 10:33:24.514  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 10:33:24.515  7065  7065 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-07 10:33:24.517  4278  7498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.517  4278  7498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 10:33:24.519  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-07 10:33:24.520  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 10:33:24.521  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 10:33:24.521  6983  6983 I BluetoothA2dpServiceJni: classInitNative
09-07 10:33:24.521  6983  6983 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 10:33:24.521  6983  6983 D A2dpStateMachine: make
,09-07 10:33:24.523  6983  6983 I bluedroid-qcom: get_profile_interface a2dp
09-07 10:33:24.523  6983  7501 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 10:33:24.526  6983  6983 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-07 10:33:24.526  6983  6983 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 10:33:24.527  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.527  6983  7499 D A2dpStateMachine: Enter Disconnected: -2
09-07 10:33:24.528  6983  6983 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 10:33:24.530  6983  6983 D HidService: Received start request. Starting profile...
09-07 10:33:24.530  6983  6983 I bluedroid-qcom: get_profile_interface hidhost
09-07 10:33:24.530  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.531  6983  6983 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 10:33:24.531  7065  7500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:24.532  6983  6983 D HealthService: Received start request. Starting profile...
,09-07 10:33:24.534  6983  6983 I bluedroid-qcom: get_profile_interface health
09-07 10:33:24.534  6983  6983 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-07 10:33:24.534  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.534  6983  6983 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 10:33:24.536  6983  6983 D PanService: Received start request. Starting profile...
09-07 10:33:24.536  6983  6983 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 10:33:24.536  6983  6983 I bluedroid-qcom: get_profile_interface pan
09-07 10:33:24.538  3486  3486 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-07 10:33:24.538  3486  3486 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:24.539  3486  3486 I LgeMiscReceiver: networkInfo.isConnected() = false
09-07 10:33:24.539  6960  7504 W FormManager: Network not available. Please check & try again.
09-07 10:33:24.541  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-07 10:33:24.541  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-07 10:33:24.542  6983  6983 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 10:33:24.542  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.543  6983  6983 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-07 10:33:24.549  6983  6983 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 10:33:24.549  6983  6983 D BtGatt.GattService: Received start request. Starting profile...
09-07 10:33:24.550  6983  6983 D BtGatt.GattService: start()
09-07 10:33:24.550  6983  6983 I bluedroid-qcom: get_profile_interface gatt
09-07 10:33:24.550  6983  6983 D BtGatt.AdvertiseManager: advertise manager created
09-07 10:33:24.552  7181  7181 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:24
09-07 10:33:24.554  6960  7505 V FormManager: Network unavailable.
09-07 10:33:24.554  7181  7181 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-07 10:33:24.554  7181  7181 D Weather.Utils: 2 : All the weather widget is gone.
09-07 10:33:24.554  7181  7181 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-07 10:33:24.554  7181  7181 D WeatherAncestor: connectivity changed - connection : true
09-07 10:33:24.554  7181  7181 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29179339
09-07 10:33:24.555  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.555  6983  6983 D HeadsetStateMachine: Proxy object connected
09-07 10:33:24.555  6983  6983 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 10:33:24.555  6983  6983 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 10:33:24.556  7181  7181 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-07 10:33:24.556  7181  7181 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-07 10:33:24.556  7181  7181 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-07 10:33:24.556  7181  7181 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 10:33:24.556  7181  7181 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:33:24
09-07 10:33:24.556  6960  7505 V FormManager: Network unavailable.
09-07 10:33:24.560  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:24.560  6983  6983 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 10:33:24.561  6983  6983 V BluetoothMapService: BluetoothMapBinder()
,09-07 10:33:24.561  6983  6983 D BluetoothMapService: Received start request. Starting profile...
09-07 10:33:24.561  6983  6983 D BluetoothMapService: start()
09-07 10:33:24.567  6983  6983 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 10:33:24.567  6983  6983 D BluetoothMapEmailAppObserver: createReceiver()
09-07 10:33:24.568  6983  6983 D BluetoothMapEmailAppObserver: initObservers()
09-07 10:33:24.568  6983  6983 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-07 10:33:24.576  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
,09-07 10:33:24.579  6983  6983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:24.579  6983  7464 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 10:33:24.579  6983  7464 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 10:33:24.580  6983  7464 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 10:33:24.582  6983  6983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:24.584  6983  6983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:24.586  6983  6983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:24.587  6983  6983 V PanService: [BTUI] SIM Extra State :ABSENT
09-07 10:33:24.589  6983  6983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-07 10:33:24.592  6983  6983 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-07 10:33:24.592  6983  6983 V BluetoothMapService: Handler(): got msg=1
09-07 10:33:24.592  6983  7442 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 10:33:24.593  6983  7442 I bluedroid-qcom: enable
09-07 10:33:24.593  6983  7512 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 10:33:24.593  6983  7512 I bt-btu  : btu_task pending for preload complete event
09-07 10:33:24.593  6983  7442 I bt_hci_bdroid: init
09-07 10:33:24.594  6983  6983 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:24.594  6983  7442 I bt_vendor: bt-vendor : init
09-07 10:33:24.594  6983  7442 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 10:33:24.594  6983  7442 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 10:33:24.594  6983  7442 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 10:33:24.594  6983  7442 D bt_userial_mct: userial_init
09-07 10:33:24.594  6983  7442 D bt_hci_bdroid: set_power 1
09-07 10:33:24.594  6983  7442 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 10:33:24.594  6983  7442 I bt_vendor: Starting hciattach daemon
09-07 10:33:24.594  6983  7442 I bt_vendor: try to set true
09-07 10:33:24.596  6983  6983 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 10:33:24.596  6983  6983 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:24.596  6983  6983 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 10:33:24.596  6983  6983 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:24.596  6983  6983 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 10:33:24.583  7515  7515 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:24.583  7515  7515 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:24.622  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 10:33:24.729  7522  7522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 10:33:24.755  7523  7523 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 10:33:24.795  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 10:33:24.814  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-07 10:33:24.845  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 10:33:24.860  7531  7531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 10:33:24.883  7533  7533 I libmdmdetect: ESOC framework not supported
,09-07 10:33:24.884  7533  7533 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-07 10:33:24.896  7533  7533 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-07 10:33:24.896  7533  7533 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-07 10:33:24.897  7533  7533 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 10:33:24.897  7533  7533 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 10:33:24.897  7533  7533 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 10:33:24.897  7533  7533 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 10:33:24.897  7533  7533 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-07 10:33:24.939  7533  7537 E QC-QMI  : qmi_client [7533] 14: failed to locate client data
,09-07 10:33:24.941   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-07 10:33:24.941   444   444 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-07 10:33:24.966  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 10:33:24.983  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 10:33:25.008  6983  7442 I bt_vendor: bluetooth satus is on
09-07 10:33:25.008  6983  7442 D bt_hci_bdroid: preload
,09-07 10:33:25.011  6983  7514 D bt_userial_mct: userial_open(port:0)
09-07 10:33:25.011  6983  7514 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-07 10:33:25.015  6983  7514 I bt_vendor: Done intiailizing UART
09-07 10:33:25.016  6983  7514 I bt_vendor: Done intiailizing UART
09-07 10:33:25.016  6983  7514 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-07 10:33:25.016  6983  7514 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 10:33:25.016  6983  7512 I bt-btu  : btu_task received preload complete event
09-07 10:33:25.017  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 10:33:25.017  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-07 10:33:25.019  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-07 10:33:25.027  6983  7544 D bt_userial_mct: Entering userial_read_thread()
,09-07 10:33:25.031  6983  7512 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 10:33:25.031  6983  7512 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 10:33:25.032  6983  7512 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 10:33:25.046  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7448
09-07 10:33:25.046  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7449
,09-07 10:33:25.051  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7460
09-07 10:33:25.051  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7461
09-07 10:33:25.052  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7496
09-07 10:33:25.052  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7538
09-07 10:33:25.079  6983  7512 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-07 10:33:25.079  6983  7512 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016b061 
09-07 10:33:25.079  6983  7512 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016b061 
,09-07 10:33:25.105  6983  7446 E bt-btif : Calling BTA_HhEnable
09-07 10:33:25.105  6983  7446 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 10:33:25.105  6983  7446 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-07 10:33:25.108  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-07 10:33:25.108  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-07 10:33:25.108  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 10:33:25.108  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 10:33:25.108  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 10:33:25.110  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 10:33:25.110  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 10:33:25.110  6983  7446 D BluetoothAdapterProperties: Name is: G3
09-07 10:33:25.111  6983  7446 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:33:25.112  6983  7446 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 10:33:25.112  6983  7446 D bt_hci_bdroid: postload
09-07 10:33:25.112  6983  7514 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:25.113  6983  7514 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:25.114  6983  7446 D bte_conf: Device ID record 1 : primary
09-07 10:33:25.114  6983  7446 D bte_conf:   vendorId            = 00c4
09-07 10:33:25.114  6983  7446 D bte_conf:   vendorIdSource      = 0001
09-07 10:33:25.114  6983  7446 D bte_conf:   product             = 13a1
09-07 10:33:25.114  6983  7446 D bte_conf:   version             = 1000
09-07 10:33:25.114  6983  7446 D bte_conf:   clientExecutableURL = 
09-07 10:33:25.114  6983  7446 D bte_conf:   serviceDescription  = 
09-07 10:33:25.114  6983  7446 D bte_conf:   documentationURL    = 
09-07 10:33:25.114  6983  7446 D bte_conf: bte_load_did_conf no section named DID2.
09-07 10:33:25.114  6983  7512 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-07 10:33:25.115  6983  7514 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:25.115  6983  7514 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:25.116  6983  7514 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:25.118  6983  7544 E bt_mct  : hci lib postload completed
,09-07 10:33:25.122  6983  7442 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 10:33:25.123  6983  7442 D BluetoothAdapterProperties: ScanMode =  20
09-07 10:33:25.123  6983  7442 D BluetoothAdapterProperties: State =  11
09-07 10:33:25.123  6983  7442 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 10:33:25.123  6983  7442 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 10:33:25.123  6983  7442 D BluetoothAdapterProperties: Setting state to 12
09-07 10:33:25.123  6983  7442 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 10:33:25.124  6983  7446 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 10:33:25.124  6983  7446 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 10:33:25.113  7546  7546 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:25.113  7546  7546 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:25.129  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:25.129  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 10:33:25.130  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-07 10:33:25.132  6983  7512 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:25.132  6983  7512 W bt-smp  : Plain text(LSB ~ MSB) = dc 0b 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-07 10:33:25.135  6983  7512 W bt-smp  : Encrypted text(LSB ~ MSB) = 5f 12 5d f9 04 1f fa 45 e2 7a 05 54 6d 38 b4 2e 
09-07 10:33:25.135  6983  7512 W bt-btm  : Stopping oneshot timer
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:25.161  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:33:25.164  6983  7442 I BluetoothAdapterState: Entering On State
09-07 10:33:25.166  6983  7446 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 10:33:25.166  6983  7446 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-07 10:33:25.182  6983  7512 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:25.182  6983  7512 W bt-smp  : Plain text(LSB ~ MSB) = c2 8c 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:25.182  6983  7512 W bt-smp  : Encrypted text(LSB ~ MSB) = 63 27 94 75 8c ca 7a b1 60 25 03 bd e1 01 19 ef 
09-07 10:33:25.182  6983  7512 W bt-btm  : Stopping oneshot timer
,09-07 10:33:25.183  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:25.188  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:25.190  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:25.191  6836  7348 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 10:33:25.194  6983  7442 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 10:33:25.195  6983  7442 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 10:33:25.195  6983  7442 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-07 10:33:25.197  6983  7442 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-07 10:33:25.202  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:25.204  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:25.208  6983  7512 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:25.208  6983  7512 W bt-smp  : Plain text(LSB ~ MSB) = 3d 0a 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:25.208  6983  7512 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 39 34 a9 e8 7c 58 d1 34 eb cd 02 05 c3 5f 9f 
09-07 10:33:25.208  6983  7512 W bt-btm  : Stopping oneshot timer
,09-07 10:33:25.214  6983  7442 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-07 10:33:25.215  6836  6854 D BluetoothMap: onBluetoothStateChange: up=true
09-07 10:33:25.219  1043  1043 D BluetoothHeadset: Proxy object connected
09-07 10:33:25.220  6983  7512 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-07 10:33:25.220  6983  7512 W bt-smp  : Plain text(LSB ~ MSB) = a4 1f 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:25.221  1834  1834 D BluetoothHeadset: Proxy object connected
09-07 10:33:25.224  6983  7512 W bt-smp  : Encrypted text(LSB ~ MSB) = 52 1a 37 0b 7f 43 c8 17 ee e7 e5 2a 9b 53 13 86 
09-07 10:33:25.224  6983  7512 W bt-btm  : Stopping oneshot timer
09-07 10:33:25.227  6836  7348 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 10:33:25.229  7562  7562 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-07 10:33:25.231  1834  1849 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:25.233  1834  1834 D BluetoothHeadset: Proxy object connected
,09-07 10:33:25.235  6836  6836 D BluetoothMap: Proxy object connected
09-07 10:33:25.235  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:25.235  6836  6836 D MapProfile: Bluetooth service connected
09-07 10:33:25.235  6836  6836 D BluetoothMap: getConnectedDevices()
09-07 10:33:25.237  6983  7557 V BluetoothMapService: getConnectedDevices()
09-07 10:33:25.238  6836  6836 D BluetoothInputDevice: Proxy object connected
09-07 10:33:25.238  6836  6836 D HidProfile: Bluetooth service connected
09-07 10:33:25.238  1834  1834 D BluetoothHeadset: Proxy object connected
09-07 10:33:25.238  6836  6854 D BluetoothPan: onBluetoothStateChange on: true
09-07 10:33:25.238  6836  6854 D BluetoothPan: onBluetoothStateChange call bindService
09-07 10:33:25.239  6983  7512 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:25.239  6983  7512 W bt-smp  : Plain text(LSB ~ MSB) = b4 be 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:25.239  6983  7512 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 e2 f1 64 7e 86 dc db 12 69 6c 5e 9f 7f dd 92 
09-07 10:33:25.239  6983  7512 W bt-btm  : Stopping oneshot timer
09-07 10:33:25.241  6836  6836 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 10:33:25.241  6836  6836 D PanProfile: Bluetooth service connected
09-07 10:33:25.241  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 10:33:25.242  1043  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 10:33:25.242  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-07 10:33:25.244  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.244  1925  2097 D LGBluetoothAPIService: Message: 1
09-07 10:33:25.244  1925  2097 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 10:33:25.245  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-07 10:33:25.251  1043  1043 D BluetoothA2dp: Proxy object connected
09-07 10:33:25.253  6983  6983 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.253  6983  6983 D BluetoothMapService: STATE_ON
09-07 10:33:25.254  6983  6983 V BluetoothMapService: Handler(): got msg=1
09-07 10:33:25.255  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 10:33:25.255  6983  6983 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 10:33:25.257  6983  7571 D BluetoothMapMasInstance: MAS initSocket()
09-07 10:33:25.258  6983  7571 D BluetoothMapMasInstance:   masId = 00
09-07 10:33:25.258  6983  7571 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 10:33:25.258  6983  7571 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 10:33:25.258  6983  7571 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 10:33:25.260  1043  1119 D BluetoothManagerService: Message: 40
09-07 10:33:25.260  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,09-07 10:33:25.264  6836  6836 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 10:33:25.265  1925  2097 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-07 10:33:25.266  1043  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:25.268  6983  7571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:25.268  6729  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 10:33:25.270  6983  7571 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-07 10:33:25.270  1043  1119 D BluetoothManagerService: Message: 30
09-07 10:33:25.270  6983  7571 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 10:33:25.270  6983  7571 D BluetoothMapMasInstance: Accepting socket connection...
09-07 10:33:25.271  6983  7446 D BluetoothAdapterProperties: Scan Mode:21
09-07 10:33:25.271  6983  7446 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 10:33:25.272  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:25.274  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:25.274  6983  6983 V BluetoothPbapService: Pbap Service onCreate
09-07 10:33:25.274  6983  6983 V BluetoothPbapService: Starting PBAP service
09-07 10:33:25.276  6983  6983 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 10:33:25.276  6983  6983 V BluetoothPbapService: Pbap Service onBind
09-07 10:33:25.278  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:25.279  6983  6983 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.279  6983  6983 V BluetoothPbapService: state: 12
09-07 10:33:25.279  6836  6836 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 10:33:25.281  6983  6983 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 10:33:25.281  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:25.281  6983  6983 D LGBluetoothAPIServer: [BTUI] onBind()
09-07 10:33:25.283  1043  1119 D BluetoothManagerService: Message: 30
09-07 10:33:25.284  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:25.285  6983  6983 V BluetoothPbapService: Handler(): got msg=1
09-07 10:33:25.285  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 10:33:25.285  1925  2097 D LGBluetoothAPIService: Message: 100
09-07 10:33:25.285  1925  2097 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-07 10:33:25.285  6983  6983 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 10:33:25.287  6983  7573 V BluetoothPbapService: Pbap Service initSocket
09-07 10:33:25.287  1043  1861 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:25.288  6983  7573 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:25.288  6983  7573 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-07 10:33:25.288  6983  7573 V BluetoothPbapService: Succeed to create listening socket 
09-07 10:33:25.288  6983  7573 V BluetoothPbapService: Accepting socket connection...
09-07 10:33:25.289  7218  7249 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-07 10:33:25.291  6836  6836 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-07 10:33:25.292  6836  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 10:33:25.294  6836  6836 D BluetoothA2dp: Proxy object connected
09-07 10:33:25.295  6983  6983 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 10:33:25.295  6983  6983 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.295  6983  6983 V BluetoothPbapReceiver: ***********state = 12
09-07 10:33:25.295  6836  6836 D A2dpProfile: Bluetooth service connected
09-07 10:33:25.296  6836  6836 D BluetoothPbap: Proxy object connected
,09-07 10:33:25.297  6836  6836 D PbapServerProfile: Bluetooth service connected
09-07 10:33:25.297  6836  6836 D BluetoothHeadset: Proxy object connected
09-07 10:33:25.297  6836  6836 D HeadsetProfile: Bluetooth service connected
09-07 10:33:25.298  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:33:25.298  2066  2066 D c       : Getting all permits...
09-07 10:33:25.298  2066  2066 D a       : Opening database...
09-07 10:33:25.302  6836  6836 D DockEventReceiver: finishStartingService: stopping service
09-07 10:33:25.302  2066  2066 D a       : Opening database auth.proximity.permit_store...
09-07 10:33:25.303  2066  2066 D a       : Closing database...
09-07 10:33:25.312  6836  6836 D BluetoothPermissionRequest: onReceive
,09-07 10:33:25.315  6836  6836 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 10:33:25.317  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 10:33:25.319  6983  6983 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 10:33:25.321  6983  6983 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 10:33:25.326  6983  6983 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 10:33:25.344  6983  6983 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 10:33:25.344  6983  6983 V BtOppService: onCreate
09-07 10:33:25.347  6983  6983 V BluetoothOppNotification: send message
09-07 10:33:25.350  6983  6983 V BtOppService: Starting RfcommListener
09-07 10:33:25.353  6983  6983 D BluetoothOppPreference: Dumping Names:  
09-07 10:33:25.353  6983  6983 D BluetoothOppPreference: {}
09-07 10:33:25.353  6983  6983 D BluetoothOppPreference: Dumping Channels:  
09-07 10:33:25.353  6983  6983 D BluetoothOppPreference: {}
09-07 10:33:25.354  6983  6983 V BtOppService: onStartCommand
09-07 10:33:25.357  6983  6983 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.358  6983  6983 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-07 10:33:25.358  6983  7582 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 10:33:25.361  6983  6983 V BluetoothOppNotification: new notify threadi!
09-07 10:33:25.362  6983  6983 V BluetoothOppNotification: send delay message
09-07 10:33:25.363  6983  6983 V BtOppService: start RfcommListener
09-07 10:33:25.369  6983  6983 V BtOppService: RfcommListener started
09-07 10:33:25.370  6983  7585 V BtOppRfcommListener: Starting RFCOMM listener....
09-07 10:33:25.370  6983  7579 V BtOppService: Deleted complete outbound shares, number =  0
09-07 10:33:25.371  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:25.373  6983  7585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:25.373  6983  7579 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 10:33:25.375  6983  7579 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,09-07 10:33:25.377  6983  7579 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37dfb69a on behalf of 
09-07 10:33:25.378  6983  7585 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-07 10:33:25.379  6983  7585 V BtOppRfcommListener: Started RFCOMM listener....
09-07 10:33:25.379  6983  7585 I BtOppRfcommListener: Accept thread started.
09-07 10:33:25.379  6983  7585 V BtOppRfcommListener: Accepting connection...
09-07 10:33:25.379  6983  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 10:33:25.380  6983  7582 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 10:33:25.383  6983  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8ffdbcb on behalf of 
09-07 10:33:25.384  6983  7582 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13ea9fa8 on behalf of 
09-07 10:33:25.384  6983  7583 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 10:33:25.385  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:25.385  6983  6983 V BluetoothFtpService: Ftp Service onCreate
09-07 10:33:25.385  6983  6983 I BluetoothFtpService: Ftp Service onCreate
09-07 10:33:25.385  6983  7582 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 10:33:25.386  6983  6983 V BluetoothFtpService: Ftp Service onStartCommand
09-07 10:33:25.386  6983  6983 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.386  6983  6983 V BluetoothFtpService: Starting Listening on sockets
09-07 10:33:25.386  6983  6983 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-07 10:33:25.386  6983  6983 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:25.386  6983  6983 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 10:33:25.386  6983  6983 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.386  6983  6983 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,09-07 10:33:25.386  6983  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:25.387  6983  6983 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 10:33:25.389  6983  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b72a266 on behalf of 
09-07 10:33:25.390  6983  6983 V BtOppService: ContentObserver received notification
09-07 10:33:25.390  6983  6983 V BtOppService: ContentObserver received notification
09-07 10:33:25.390  6983  6983 V BluetoothFtpService: Handler(): got msg=1
09-07 10:33:25.391  6983  6983 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 10:33:25.391  6983  6983 V BluetoothFtpService: Ftp Service initSocket
09-07 10:33:25.395  6983  7586 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 10:33:25.395  6983  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 10:33:25.395  6983  7583 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 10:33:25.396  6983  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e2e69a7 on behalf of 
09-07 10:33:25.397  6983  7586 V BluetoothOppNotification: update too frequent, put in queue
09-07 10:33:25.398  6983  7586 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 10:33:25.398  6983  7583 V BluetoothOppNotification: outbound notification was removed.
09-07 10:33:25.398  6983  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:25.400  6983  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c1e0e54 on behalf of 
09-07 10:33:25.401  6983  7583 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 10:33:25.402  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 10:33:25.404  6983  7583 V BluetoothOppNotification: inbound notification was removed.
09-07 10:33:25.404  6983  6983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:25.404  6983  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 10:33:25.405  6983  6983 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-07 10:33:25.406  6983  6983 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-07 10:33:25.406  6983  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a21e1fd on behalf of 
09-07 10:33:25.408  6983  7587 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 10:33:25.425  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:25.425  6983  6983 V BluetoothSapService: Sap Service onCreate
,09-07 10:33:25.428  6983  6983 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:25.428  6983  6983 V BluetoothSapService: state: 12
09-07 10:33:25.428  6983  6983 V BluetoothSapService: Starting SAP server process
09-07 10:33:25.431  6983  6983 V BluetoothSapService: SAP Service startRfcommListenerThread
09-07 10:33:25.423  7588  7588 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:25.423  7588  7588 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:25.434  6983  7589 V BluetoothSapService: Sap Service initRfcommSocket
09-07 10:33:25.435  1043  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:25.436  6983  7589 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:25.438  6983  7589 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-07 10:33:25.438  6983  7589 V BluetoothSapService: Succeed to create listening socket 
09-07 10:33:25.438  6983  7589 V BluetoothSapService: Accepting socket connection...
,09-07 10:33:25.456  7588  7588 V BT_SAP  : Event pipe created
09-07 10:33:25.456  7588  7588 V BT_SAP  : create_server_socket qcom.sap.server
09-07 10:33:25.456  7588  7588 V BT_SAP  : created socket fd 6
,09-07 10:33:26.028  1043  1521 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:33:26.028  1043  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:33:26.057  1043  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-07 10:33:26.058  1043  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-07 10:33:26.083  1043  1906 I ActivityManager: Killing 7378:com.lge.bnr/1000 (adj 15): empty #17
,09-07 10:33:26.115  1043  1979 W libprocessgroup: failed to open /acct/uid_1000/pid_7378/cgroup.procs: No such file or directory
,09-07 10:33:26.364  6983  6983 V BluetoothOppNotification: new notify threadi!
,09-07 10:33:26.365  6983  6983 V BluetoothOppNotification: send delay message
,09-07 10:33:26.377  6983  7599 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 10:33:26.384  6983  7599 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33afa0f9 on behalf of 
09-07 10:33:26.385  6983  7599 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-07 10:33:26.389  6983  7599 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:26.390  6983  7599 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e69983e on behalf of 
09-07 10:33:26.391  6983  7599 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 10:33:26.392  6983  7599 V BluetoothOppNotification: outbound notification was removed.
09-07 10:33:26.392  6983  7599 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:26.393  6983  7599 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d4ce69f on behalf of 
09-07 10:33:26.394  6983  7599 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 10:33:26.395  6983  7599 V BluetoothOppNotification: inbound notification was removed.
09-07 10:33:26.396  6983  7599 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 10:33:26.397  6983  7599 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5fcd3ec on behalf of 
09-07 10:33:26.435  1043  1863 I ActivityManager: Killing 6855:com.lge.sync/1000 (adj 15): empty #17
,09-07 10:33:26.462  1043  1528 D WifiService: Client connection lost with reason: 4
,09-07 10:33:26.471  1043  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_6855/cgroup.procs: No such file or directory
,09-07 10:33:27.014  1043  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:27.014  1043  1559 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3ce4456e mBinding = false
,09-07 10:33:27.045  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:27.045  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:27.045  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-07 10:33:27.046  1043  1119 D BluetoothManagerService: Message: 2
09-07 10:33:27.047  1043  1119 D BluetoothManagerService: Sending off request.
09-07 10:33:27.048  6983  7569 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-07 10:33:27.048  6983  7442 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-07 10:33:27.049  6983  7442 D BluetoothAdapterProperties: Setting state to 13
09-07 10:33:27.049  6983  7442 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 10:33:27.049  6983  7442 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 10:33:27.049  6983  7442 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 10:33:27.051  6983  7446 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:33:27.053  6983  7442 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-07 10:33:27.054  6983  7571 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-07 10:33:27.059  6983  7573 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:27.060  6983  7585 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:27.061  6983  7442 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 10:33:27.062  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-07 10:33:27.063  6983  7512 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:27.064  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-07 10:33:27.065  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-07 10:33:27.065  6983  7512 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 10:33:27.074  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:27.075  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:33:27.079  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:27.080  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:27.082  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:27.082  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:27.083  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:33:27.083  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:27.087  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:27.087  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-07 10:33:27.087  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-07 10:33:27.093  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.094  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 10:33:27.099  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:27.102  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:27.105  6983  6983 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.105  6983  6983 D BluetoothMapService: STATE_TURNING_OFF
09-07 10:33:27.105  6983  6983 V BluetoothMapService: Handler(): got msg=4
09-07 10:33:27.105  6983  6983 D BluetoothMapService: MAP Service closeService in
09-07 10:33:27.105  6983  6983 D BluetoothMapMasInstance: MAP Service shutdown
09-07 10:33:27.105  6983  6983 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 10:33:27.106  6983  6983 V BluetoothMapService: MAP Service closeService out
09-07 10:33:27.107  6983  6983 V BtOppService: Receiver DISABLED_ACTION 
09-07 10:33:27.107  6983  6983 I BtOppRfcommListener: stopping Accept Thread
09-07 10:33:27.107  6983  6983 V BtOppRfcommListener: close mBtServerSocket
09-07 10:33:27.108  6983  7585 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 10:33:27.108  6983  6983 V BtOppRfcommListener: waiting for thread to terminate
09-07 10:33:27.108  6983  6983 V BtOppRfcommListener: done waiting for thread to terminate
09-07 10:33:27.111  6836  6836 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-07 10:33:27.116  6983  7587 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 10:33:27.122  6983  7589 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:33:27.127  6836  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 10:33:27.129  6983  6983 V BtOppService: onDestroy
,09-07 10:33:27.132  6983  6983 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-07 10:33:27.138  6983  6983 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 10:33:27.138  6983  6983 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.138  6983  6983 V BluetoothPbapReceiver: ***********state = 13
09-07 10:33:27.141  6983  6983 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-07 10:33:27.144  6983  6983 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.144  6983  6983 V BluetoothPbapService: state: 13
09-07 10:33:27.144  6983  6983 V BluetoothPbapService: Pbap Service closeService in
09-07 10:33:27.147  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:33:27.148  6983  6983 V BluetoothPbapService: successfully stopped pbap service
09-07 10:33:27.148  6983  6983 V BluetoothPbapService: Pbap Service closeService out
09-07 10:33:27.150  6983  6983 V BluetoothPbapService: Pbap Service onDestroy
09-07 10:33:27.150  6983  6983 V BluetoothPbapService: Pbap Service closeService in
09-07 10:33:27.150  6983  6983 V BluetoothPbapService: Pbap Service closeService out
09-07 10:33:27.150  6983  6983 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-07 10:33:27.168  6836  6836 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:33:27.175  6836  6836 D BluetoothPbap: Proxy object disconnected
09-07 10:33:27.175  6836  6836 D PbapServerProfile: Bluetooth service disconnected
09-07 10:33:27.189  6836  6836 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-07 10:33:27.197  6836  6836 D BluetoothPermissionRequest: onReceive
09-07 10:33:27.198  6836  6836 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-07 10:33:27.205  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-07 10:33:27.209  6983  6983 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-07 10:33:27.210  6983  6983 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-07 10:33:27.210  6983  6983 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-07 10:33:27.216  6983  6983 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.216  6983  6983 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-07 10:33:27.217  6983  6983 V BluetoothFtpService: Ftp Service onStartCommand
09-07 10:33:27.217  6983  6983 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.218  6983  6983 V BluetoothFtpService: Ftp Service closeService
,09-07 10:33:27.218  6983  6983 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-07 10:33:27.221  6983  6983 V BluetoothFtpService: successfully stopped ftp service
09-07 10:33:27.221  6983  6983 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 10:33:27.221  6983  6983 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:27.221  6983  6983 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 10:33:27.222  6983  6983 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.222  6983  6983 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-07 10:33:27.222  6983  6983 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 10:33:27.223  6983  6983 V BluetoothFtpService: Ftp Service onDestroy
09-07 10:33:27.223  6983  6983 V BluetoothFtpService: Ftp Service closeService
09-07 10:33:27.227  6983  6983 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:27.227  6983  6983 V BluetoothSapService: state: 13
09-07 10:33:27.227  6983  6983 V BluetoothSapService: Stopping SAP server process
09-07 10:33:27.228  6983  6983 V BluetoothSapService: Sap Service closeSapService in
09-07 10:33:27.229  6983  6983 V BluetoothSapService: Close listen Socket : 
09-07 10:33:27.229  6983  6983 V BluetoothSapService: Close rfcomm Socket : 
09-07 10:33:27.229  6983  6983 V BluetoothSapService: Close sapd  Socket : 
09-07 10:33:27.231  6983  6983 V BluetoothSapService: Sap Service closeSapService out
09-07 10:33:27.232  6983  6983 V BluetoothSapService: Sap Service onDestroy
09-07 10:33:27.232  6983  6983 V BluetoothSapService: Sap Service closeSapService in
09-07 10:33:27.232  6983  6983 V BluetoothSapService: Close listen Socket : 
09-07 10:33:27.232  6983  6983 V BluetoothSapService: Close rfcomm Socket : 
09-07 10:33:27.232  6983  6983 V BluetoothSapService: Close sapd  Socket : 
,09-07 10:33:27.233  6983  6983 V BluetoothSapService: Sap Service closeSapService out
09-07 10:33:28.043  6983  7446 D bt_hci_bdroid: cleanup
,09-07 10:33:28.049  6983  7514 I bt_lpm  : LPM is already off!!!
09-07 10:33:28.050  6983  7544 I bt_userial_mct: exiting userial_read_thread
09-07 10:33:28.053  6983  7512 W bt-btif : ag scb idx 1 not allocated
09-07 10:33:28.053  6983  7512 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:28.050  6983  7544 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:33:28.053  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-07 10:33:28.054  6983  7512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:33:28.054  6983  7512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-07 10:33:28.054  6983  7512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:33:28.054  6983  7512 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-07 10:33:28.054  6983  7446 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 10:33:28.054  6983  7514 I bt_vendor: hw_epilog_process
09-07 10:33:28.055  6983  7446 D bt_hci_bdroid: cleanup Finalizing cleanup
09-07 10:33:28.055  6983  7446 D bt_userial_mct: userial_close
09-07 10:33:28.055  6983  7446 E bt_userial_mct: pthread_join() FAILED result:3
09-07 10:33:28.055  6983  7446 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-07 10:33:28.061  6983  7446 D bt_hci_bdroid: set_power 0
09-07 10:33:28.061  6983  7446 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 10:33:28.061  6983  7446 I bt_vendor: bluetooth satus is on
09-07 10:33:28.061  6983  7446 I bt_vendor: bt-vendor : resetting BT status
09-07 10:33:28.061  6983  7446 I bt_vendor: Starting hciattach daemon
09-07 10:33:28.061  6983  7446 I bt_vendor: try to set false
,09-07 10:33:28.068  6983  7446 I bt_vendor: Starting hciattach daemon
09-07 10:33:28.068  6983  7446 I bt_vendor: try to set false
09-07 10:33:28.069  6983  7446 I bt_vendor: cleanup
09-07 10:33:28.070  6983  7512 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 10:33:28.070  6983  7446 I GKI_LINUX: GKI_exit_task 0 done
09-07 10:33:28.070  6983  7446 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-07 10:33:28.072  6983  7442 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 10:33:28.075  6983  6983 D HeadsetService: Received stop request...Stopping profile...
,09-07 10:33:28.078  6983  6983 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 10:33:28.078  6983  6983 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 10:33:28.078  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:28.080  6983  7464 D HeadsetStateMachine: Exit Disconnected: -1
09-07 10:33:28.082  1834  1834 D BluetoothHeadset: Proxy object disconnected
09-07 10:33:28.082  1834  1834 D BluetoothHeadset: Proxy object disconnected
09-07 10:33:28.082  1834  1834 D BluetoothHeadset: Proxy object disconnected
09-07 10:33:28.084  6983  6983 D HeadsetStateMachine: Unbinding service...
09-07 10:33:28.085  1043  1043 D BluetoothHeadset: Proxy object disconnected
09-07 10:33:28.085  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 10:33:28.085  6983  6983 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 10:33:28.086  6983  6983 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 10:33:28.086  6983  6983 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 10:33:28.086  6983  6983 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 10:33:28.086  6983  6983 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 10:33:28.086  6983  6983 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 10:33:28.086  6983  6983 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-07 10:33:28.091  6983  6983 D A2dpService: Received stop request...Stopping profile...
,09-07 10:33:28.095  6983  7499 D A2dpStateMachine: Exit Disconnected: -1
09-07 10:33:28.103  6983  6983 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-07 10:33:28.105  6983  7442 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-07 10:33:28.108  6983  6983 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-07 10:33:28.108  6983  6983 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 10:33:28.108  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:28.109  1043  1043 D BluetoothA2dp: Proxy object disconnected
09-07 10:33:28.109  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 10:33:28.111  6983  6983 D HidService: Received stop request...Stopping profile...
09-07 10:33:28.111  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:28.113  6983  6983 D HealthService: Received stop request...Stopping profile...
09-07 10:33:28.113  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:28.121  6983  6983 D PanService: Received stop request...Stopping profile...
,09-07 10:33:28.124  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:28.125  6983  6983 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 10:33:28.126  6983  6983 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 10:33:28.126  6983  6983 D BtGatt.GattService: stop()
09-07 10:33:28.126  6983  6983 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 10:33:28.127  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:28.128  6983  6983 D BluetoothMapService: Received stop request...Stopping profile...
09-07 10:33:28.128  6983  6983 D BluetoothMapService: stop()
09-07 10:33:28.129  6983  6983 D BluetoothMapEmailAppObserver: deinitObservers()
09-07 10:33:28.129  6983  6983 D BluetoothMapEmailAppObserver: removeReceiver()
09-07 10:33:28.130  6983  6983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:28.132  6983  6983 V BluetoothMapService: Handler(): got msg=4
09-07 10:33:28.132  6983  6983 D BluetoothMapService: MAP Service closeService in
09-07 10:33:28.132  6983  6983 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 10:33:28.132  6983  6983 V BluetoothMapService: MAP Service closeService out
09-07 10:33:28.133  6983  7442 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-07 10:33:28.133  6983  7442 D BluetoothAdapterProperties: Setting state to 10
09-07 10:33:28.133  6983  7442 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-07 10:33:28.136  6983  6983 I BluetoothA2dpServiceJni: cleanupNative
09-07 10:33:28.136  6983  7501 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 10:33:28.137  6983  6983 I GKI_LINUX: GKI_exit_task 2 done
09-07 10:33:28.137  6983  6983 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 10:33:28.138  6983  6983 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 10:33:28.138  6983  6983 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 10:33:28.138  6983  6983 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 10:33:28.138  6983  6983 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 10:33:28.138  6983  6983 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 10:33:28.140  6983  6983 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 10:33:28.140  6983  6983 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 10:33:28.141  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:28.141  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-07 10:33:28.141  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-07 10:33:28.142  6983  7442 I BluetoothAdapterState: Entering OffState
09-07 10:33:28.145  6836  6852 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 10:33:28.147  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 10:33:28.149  6836  6852 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:33:28.151  6983  6983 D BluetoothMapService: cleanup()
09-07 10:33:28.151  6983  6983 D BluetoothMapService: MAP Service closeService in
09-07 10:33:28.151  6983  6983 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-07 10:33:28.151  6983  6983 V BluetoothMapService: MAP Service closeService out
09-07 10:33:28.152  1834  2686 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:28.153  6836  6852 D BluetoothMap: onBluetoothStateChange: up=false
09-07 10:33:28.154  6836  6852 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 10:33:28.154  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:28.155  1834  1849 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:28.155  6836  6852 D BluetoothPan: onBluetoothStateChange on: false
09-07 10:33:28.156  6836  6852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 10:33:28.156  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:33:28.157  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-07 10:33:28.157  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-07 10:33:28.160  1043  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-07 10:33:28.160  1043  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-07 10:33:28.160  1043  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3ce4456e mBinding = false
,09-07 10:33:28.163  1043  1119 D BluetoothManagerService: Sending unbind request.
09-07 10:33:28.168  6983  7446 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-07 10:33:28.169  6983  6983 I GKI_LINUX: GKI_exit_task 1 done
09-07 10:33:28.169  6983  6983 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 10:33:28.169  6983  6983 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 10:33:28.169  6983  6983 I art     : --- WEIRD: removing null entry 248
09-07 10:33:28.169  6983  6983 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-07 10:33:28.169  6983  6983 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-07 10:33:28.171  6983  6983 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,09-07 10:33:28.174  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-07 10:33:28.176  6983  6983 I art     : System.exit called, status: 0
09-07 10:33:28.176  6983  6983 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-07 10:33:28.181  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:28.182  1925  2097 D LGBluetoothAPIService: Message: 2
09-07 10:33:28.182  1925  2097 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@e8a4b50 mBinding = false
09-07 10:33:28.182  1925  2097 D LGBluetoothAPIService: Sending unbind request.
,09-07 10:33:28.185  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:28.186  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:28.186  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 10:33:28.190  6836  6836 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-07 10:33:28.190  6836  6836 D LGBluetoothEventManager: [BTUI] clear device connection state
09-07 10:33:28.204  1586  1586 D BluetoothAdapter: 645274264: getState() :  mService = null. Returning STATE_OFF
09-07 10:33:28.205  1586  1586 D BluetoothAdapter: 645274264: getState() :  mService = null. Returning STATE_OFF
,09-07 10:33:28.214  6836  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-07 10:33:28.221  6836  6836 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:33:28.235   320  1368 V AudioFlinger: 6983 died, releasing its sessions
09-07 10:33:28.235   320  1368 V AudioFlinger:  pid 1834 @ 0
,09-07 10:33:28.235   320  1368 V AudioFlinger:  pid 3486 @ 1
,09-07 10:33:28.235   320  1368 V AudioFlinger:  pid 3486 @ 2
09-07 10:33:28.235  6836  6836 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-07 10:33:28.351  1043  1906 I ActivityManager: Process com.android.bluetooth (pid 6983) has died
,09-07 10:33:28.351  1043  1906 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-07 10:33:28.365  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:33:28.386  6836  6836 D BluetoothPermissionRequest: onReceive
,09-07 10:33:28.389  6836  6836 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 10:33:28.389  6836  6836 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-07 10:33:28.393  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 10:33:28.476  1043  1059 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7647 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-07 10:33:28.547  7647  7647 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-07 10:33:28.547  7647  7647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 10:33:28.548  7647  7647 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-07 10:33:28.548  7647  7647 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 10:33:28.584  7647  7647 D BluetoothAdapterApp: Loading JNI Library
,09-07 10:33:28.621  7647  7647 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@37f84501 Instance Count = 1
,09-07 10:33:28.628  7647  7647 D BluetoothAdapterApp: onCreate
09-07 10:33:28.656  7647  7647 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-07 10:33:28.657  7647  7647 D ProfileConfigQcom: Adding HeadsetService
09-07 10:33:28.657  7647  7647 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-07 10:33:28.658  7647  7647 D ProfileConfigQcom: Adding A2dpService
09-07 10:33:28.661  7647  7647 D ProfileConfigQcom: [BTUI] HidService is supported
09-07 10:33:28.661  7647  7647 D ProfileConfigQcom: Adding HidService
09-07 10:33:28.661  7647  7647 D ProfileConfigQcom: [BTUI] HealthService is supported
09-07 10:33:28.661  7647  7647 D ProfileConfigQcom: Adding HealthService
09-07 10:33:28.662  7647  7647 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-07 10:33:28.663  7647  7647 D ProfileConfigQcom: [BTUI] PanService is supported
09-07 10:33:28.663  7647  7647 D ProfileConfigQcom: Adding PanService
09-07 10:33:28.663  7647  7647 D ProfileConfigQcom: [BTUI] GattService is supported
09-07 10:33:28.664  7647  7647 D ProfileConfigQcom: Adding GattService
09-07 10:33:28.664  7647  7647 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-07 10:33:28.664  7647  7647 D ProfileConfigQcom: Adding BluetoothMapService
09-07 10:33:28.664  7647  7647 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-07 10:33:28.666  7647  7647 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-07 10:33:28.672  6836  6836 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-07 10:33:28.674  7647  7647 V LGMDMManagerInternal: Create singleton instance
09-07 10:33:28.769  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:33:28.774  7647  7647 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-07 10:33:28.775  7647  7647 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:28.776  7647  7647 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 10:33:28.779  7647  7647 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:28.780  7647  7647 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-07 10:33:28.785  6927  6927 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-07 10:33:28.789  1043  1943 I ActivityManager: Killing 6639:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-07 10:33:28.814  6902  6902 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-07 10:33:28.814  6902  6902 W System.err: android.os.DeadObjectException
09-07 10:33:28.815  6902  6902 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 10:33:28.815  6902  6902 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 10:33:28.815  6902  6902 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-07 10:33:28.815  6902  6902 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-07 10:33:28.815  6902  6902 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-07 10:33:28.815  6902  6902 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 10:33:28.815  6902  6902 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 10:33:28.815  6902  6902 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 10:33:28.815  6902  6902 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 10:33:28.815  6902  6902 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 10:33:28.815  6902  6902 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:33:28.815  6902  6902 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:33:28.815  6902  6902 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 10:33:28.815  6902  6902 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 10:33:28.816  6902  6902 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-07 10:33:28.816  6902  6902 W System.err: android.os.DeadObjectException
09-07 10:33:28.817  6902  6902 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 10:33:28.817  6902  6902 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 10:33:28.817  6902  6902 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-07 10:33:28.817  6902  6902 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-07 10:33:28.817  6902  6902 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,09-07 10:33:28.817  6902  6902 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-07 10:33:28.817  6902  6902 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 10:33:28.817  6902  6902 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 10:33:28.817  6902  6902 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 10:33:28.817  6902  6902 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 10:33:28.818  6902  6902 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:33:28.818  6902  6902 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:33:28.818  6902  6902 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 10:33:28.818  6902  6902 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 10:33:28.818  6902  6902 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-07 10:33:28.818  6902  6902 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-07 10:33:28.900  1043  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_6639/cgroup.procs: No such file or directory
09-07 10:33:28.901  1043  1906 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-07 10:33:28.926  6902  6902 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-07 10:33:28.926  6902  6902 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-07 10:33:29.098  1043  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27c4122b type 2 when 193158 com.google.android.gms} when 193158
,09-07 10:33:29.102  1043  2015 I art     : Explicit concurrent mark sweep GC freed 95394(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.743ms total 151.881ms
09-07 10:33:29.123   315  7677 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-07 10:33:29.124  1043  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-07 10:33:29.156  1043  2015 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7678 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 10:33:29.207  6902  6902 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-07 10:33:29.248  7678  7678 D UEI.SmartControl: Quickset Services start...
,09-07 10:33:29.251  7678  7678 I UEI.SmartControl: Manufacture = LGE
09-07 10:33:29.251  7678  7678 D UEI.SmartControl: Id = LGNevo
09-07 10:33:29.252  7678  7678 D UEI.SmartControl: File observer start...
09-07 10:33:29.253  7678  7678 E UEI.SmartControl: IR Port is disabled: false
09-07 10:33:29.254  7678  7678 D UEI.SmartControl: Starting file observer...
09-07 10:33:29.254  7678  7678 D UEI.SmartControl: Extracting JNI libs...
09-07 10:33:29.254  7678  7678 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-07 10:33:29.356  7678  7678 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-07 10:33:29.356  7678  7678 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-07 10:33:29.356  7678  7678 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-07 10:33:29.399  7678  7678 I UEI.SmartControl: --- Selecting new region: 6
,09-07 10:33:29.401  7678  7678 I UEI.SmartControl: Model = LG-D855
,09-07 10:33:29.403  7678  7678 D UEI.SmartControl: QS Service created
,09-07 10:33:29.421  7678  7678 I UEI.SmartControl: Service initServices...
,09-07 10:33:29.432  7678  7678 D UEI.SmartControl: QS start get config
09-07 10:33:29.522  7678  7678 D UEI.SmartControl: Loading JNI Libs...
,09-07 10:33:29.923  7678  7678 I UEI.SmartControl: Supports setup maps: true
,09-07 10:33:29.933  7678  7678 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 10:33:29.933  7678  7678 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 10:33:29.933  7678  7678 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 10:33:29.933  7678  7678 I UEI.SmartControl: ### init IR Blaster...
09-07 10:33:29.939  7678  7678 D serial_port: Configuring serial port
,09-07 10:33:29.948  7678  7678 E UEI.SmartControl: UEIBLaster setting for 616
09-07 10:33:29.948  7678  7678 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 10:33:29.948  7678  7678 I UEI.SmartControl: configuring settings for MAXQ616
09-07 10:33:29.948  7678  7678 I UEI.SmartControl: Get version...
09-07 10:33:29.966  7678  7714 D UEI.SmartControl: serial port data available: 21
,09-07 10:33:29.999  7678  7678 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-07 10:33:29.999  7678  7678 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 10:33:29.999  7678  7678 I UEI.SmartControl: QS saving settings...
,09-07 10:33:30.014  7678  7678 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 10:33:30.041  7678  7714 D UEI.SmartControl: serial port data available: 4
,09-07 10:33:30.108  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-07 10:33:30.125  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:30.125  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:33:30.142  1043  1410 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 10:33:30.195  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-07 10:33:30.226  1043  1115 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7716 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-07 10:33:30.237  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-07 10:33:30.237  7678  7678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-07 10:33:30.238  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-07 10:33:30.239  7678  7678 E UEI.SmartControl: Services init done
09-07 10:33:30.239  7678  7678 D UEI.SmartControl: QS Service init finished
09-07 10:33:30.239  7678  7678 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 10:33:30.239  7678  7678 D UEI.SmartControl: QS Service version code: 201091
,09-07 10:33:30.244  1043  1043 D administrator: Handling package changes for user 0
09-07 10:33:30.251  7678  7678 D UEI.SmartControl: Service requested: Control
09-07 10:33:30.256  7678  7747 I UEI.SmartControl: Device manager: loading config....
,09-07 10:33:30.256  7678  7747 D UEI.SmartControl: ----------- loading internal config...
09-07 10:33:30.259  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 10:33:30.269  7678  7747 E UEI.SmartControl: Loading SETTINGS...
09-07 10:33:30.271  7678  7678 D UEI.SmartControl: Request IControl service: devices are loaded...
09-07 10:33:30.273  1043  1631 I ActivityManager: Killing 6902:com.lge.qremote/u0a112 (adj 15): empty #17
09-07 10:33:30.273  6902  6902 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 10:33:30.274  7678  7694 I UEI.SmartControl: ------ IControl API: 11
09-07 10:33:30.275  7678  7694 I UEI.SmartControl: Registering callback...
09-07 10:33:30.277  7678  7747 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-07 10:33:30.287  7716  7716 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 10:33:30.295  7678  7746 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 10:33:30.295  7678  7746 D UEI.SmartControl: -----service ready thread exits
,09-07 10:33:30.342  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-07 10:33:30.342  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-07 10:33:30.342  1043  1059 W libprocessgroup: failed to open /acct/uid_10112/pid_6902/cgroup.procs: No such file or directory
09-07 10:33:30.342  7678  7678 D UEI.SmartControl: Internal service binding...
09-07 10:33:30.368  7716  7716 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:30.368  7716  7716 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 10:33:30.411  1043  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 10:33:30.418  1043  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 10:33:30.428  2471  2471 V GmsNetworkLocationProvi: DISABLE
,09-07 10:33:30.428  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-07 10:33:30.453  1043  1114 D LocationProviderProxy: applying state to connected service
,09-07 10:33:30.454  2471  2471 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-07 10:33:30.506  7716  7765 I Babel   : MmsConfig: mnc/mcc: 0/0
09-07 10:33:30.507  7716  7765 I Babel   : MmsConfig.loadMmsSettings
09-07 10:33:30.512  7716  7765 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-07 10:33:30.512  7716  7765 I Babel   : MmsConfig.loadFromDatabase
,09-07 10:33:30.535  7716  7765 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-07 10:33:30.535  7716  7765 I Babel   : MmsConfig.loadFromResources
09-07 10:33:30.540  7716  7765 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-07 10:33:30.541  7716  7765 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-07 10:33:30.549  7716  7716 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:30.550  7716  7763 W AudioCapabilities: Unsupported mime audio/evrc
09-07 10:33:30.551  7716  7763 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 10:33:30.561  7716  7763 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 10:33:30.571  7716  7763 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-07 10:33:30.572  7716  7763 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 10:33:30.576  7716  7763 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 10:33:30.589  7716  7763 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 10:33:30.594  7716  7763 W VideoCapabilities: Unsupported mime video/divx
09-07 10:33:30.597  7716  7763 W VideoCapabilities: Unsupported mime video/divx311
09-07 10:33:30.601  7716  7763 W VideoCapabilities: Unsupported mime video/divx4
09-07 10:33:30.605  7043  7043 I AppUp4:CustModeStarterReceiver: onReceive
,09-07 10:33:30.605  1799  7767 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-07 10:33:30.605  1799  7767 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-07 10:33:30.612  7043  7043 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31e99183
09-07 10:33:30.612  7043  7043 D AppUp4:CustFacade: isCustomizationCompleted : false
09-07 10:33:30.612  7043  7043 D AppUp4:CustFacade: isPhone : true
09-07 10:33:30.613  7043  7043 D AppUp4:CustModeStarterReceiver: begin check event
09-07 10:33:30.613  7043  7043 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-07 10:33:30.616  7716  7763 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-07 10:33:30.619  1799  4732 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-07 10:33:30.640  7716  7763 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 10:33:30.644  7716  7763 W AudioCapabilities: Unsupported mime audio/eac3
,09-07 10:33:30.645  7716  7763 W AudioCapabilities: Unsupported mime audio/ac3
,09-07 10:33:30.645  7716  7763 W AudioCapabilities: Unsupported mime audio/g726
09-07 10:33:30.646  7716  7763 W AudioCapabilities: Unsupported mime audio/wma-voice
09-07 10:33:30.647  7716  7763 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-07 10:33:30.649  7716  7763 W AudioCapabilities: Unsupported mime audio/adpcm
09-07 10:33:30.650  1043  1059 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7770 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-07 10:33:30.653  7716  7763 W VideoCapabilities: Unsupported mime video/theora
09-07 10:33:30.654  1043  1863 I ActivityManager: Killing 7065:com.lge.email/u0a23 (adj 15): empty #17
09-07 10:33:30.656  7716  7763 W VideoCapabilities: Unsupported mime video/mjpg
,09-07 10:33:30.722  1043  1907 W libprocessgroup: failed to open /acct/uid_10023/pid_7065/cgroup.procs: No such file or directory
,09-07 10:33:30.751  7770  7770 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:30.752  7770  7770 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 10:33:30.752  7770  7770 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-07 10:33:30.753  7770  7770 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-07 10:33:30.754  7770  7770 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 10:33:30.837  7770  7770 I SystemConfig: BUILD Country: EU
09-07 10:33:30.837  7770  7770 I SystemConfig: BUILD Operator: OPEN
,09-07 10:33:30.899  1043  2015 I ActivityManager: Killing 6960:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-07 10:33:31.003  1043  1861 W libprocessgroup: failed to open /acct/uid_10026/pid_6960/cgroup.procs: No such file or directory
,09-07 10:33:31.018  7770  7788 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-07 10:33:31.018  7770  7788 I SystemConfig: existFile = false
09-07 10:33:31.018  7770  7788 I SystemConfig: canReadFile = false
09-07 10:33:31.018  7770  7788 I SystemConfig: systemFeature RCS result false
09-07 10:33:31.018  7770  7788 D SystemConfig: refreshRcsSupport() :false
09-07 10:33:31.057  1043  1943 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7790 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-07 10:33:31.061  1043  1529 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-07 10:33:31.107  7790  7790 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:31.107  7790  7790 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 10:33:31.107  7790  7790 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 10:33:31.108  7790  7790 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 10:33:31.205  7790  7790 I AppConfig: Total System Memory = 2995761152
,09-07 10:33:31.225  7790  7790 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-07 10:33:31.350  1043  1863 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7809 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 10:33:31.354  1043  1863 I ActivityManager: Killing 6449:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-07 10:33:31.401  1043  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_6449/cgroup.procs: No such file or directory
,09-07 10:33:31.597  7809  7809 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-07 10:33:31.691  7809  7809 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:31.691  7809  7809 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-07 10:33:31.745  7809  7809 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-07 10:33:31.766  7809  7809 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 10:33:31.767  7809  7809 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 10:33:31.795  7809  7809 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-07 10:33:31.796  7809  7809 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-07 10:33:31.821  1043  1907 I ActivityManager: Killing 7115:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-07 10:33:31.855  1043  2015 W libprocessgroup: failed to open /acct/uid_10046/pid_7115/cgroup.procs: No such file or directory
,09-07 10:33:31.868  2830  3925 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-07 10:33:31.871  4560  7852 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-07 10:33:31.873  2830  3925 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@4d0e4b7 on behalf of 7809
09-07 10:33:31.926  1043  1906 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7853 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-07 10:33:31.960   347   347 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 32.604ms
,09-07 10:33:31.985   347   347 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 22.729ms
,09-07 10:33:32.008   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 20.261ms
,09-07 10:33:32.027  7809  7809 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-07 10:33:32.042  7809  7809 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-07 10:33:32.054  7853  7853 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
09-07 10:33:32.077  7853  7853 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-07 10:33:32.077  7853  7853 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-07 10:33:32.077  7853  7853 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-07 10:33:32.077  7853  7853 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-07 10:33:32.077  7853  7853 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-07 10:33:32.077  7853  7853 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-07 10:33:32.100  1043  1943 I ActivityManager: Killing 7136:com.android.chrome/u0a57 (adj 15): empty #17
,09-07 10:33:32.173  1043  1559 W libprocessgroup: failed to open /acct/uid_10057/pid_7136/cgroup.procs: No such file or directory
,09-07 10:33:32.408  1043  1979 V SIM_STK : Menu title from STK is T-Mobile
,09-07 10:33:32.437  4560  7852 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 566 ms] updated apps [took 566 ms] 
,09-07 10:33:33.235  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:33:33.236  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6f551d added. We now have 6 listener(s)
09-07 10:33:33.236  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:33:33.249  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:33.249  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bc44392 added. We now have 7 listener(s)
09-07 10:33:33.249  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:33.252  6729  6807 I System.out: IsBluetoothEnabled
09-07 10:33:33.254  1043  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:33.254  1043  1863 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,09-07 10:33:33.256  1043  1119 D BluetoothManagerService: Message: 2
09-07 10:33:33.259  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:33.259  1043  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:33.259  1043  2015 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-07 10:33:33.278  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:33.278  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:33.279  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-07 10:33:33.281  1043  1119 D BluetoothManagerService: Message: 1
09-07 10:33:33.281  1043  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-07 10:33:33.308  1043  1119 D BluetoothManagerService: Message: 20
,09-07 10:33:33.308  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f0b008:true
,09-07 10:33:33.312  7647  7647 D BluetoothAdapterState: make
09-07 10:33:33.317  7647  7647 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-07 10:33:33.317  7647  7647 I bluedroid-qcom: init
09-07 10:33:33.318  7647  7898 I BluetoothAdapterState: Entering OffState
09-07 10:33:33.319  7647  7647 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 10:33:33.319  7647  7647 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 10:33:33.319  7647  7647 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 10:33:33.319  7647  7647 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 10:33:33.319  7647  7647 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-07 10:33:33.321  7647  7647 I bluedroid-qcom: get_profile_interface socket
09-07 10:33:33.321  7647  7647 I bluedroid-qcom: get_profile_interface map_client
,09-07 10:33:33.325  7647  7902 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 10:33:33.313  7901  7901 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:33.313  7901  7901 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:33.333  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-07 10:33:33.334  1043  1119 D BluetoothManagerService: Message: 40
09-07 10:33:33.334  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-07 10:33:33.336  7647  7667 I bluedroid-qcom: config_hci_snoop_log
,09-07 10:33:33.341  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-07 10:33:33.341  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 10:33:33.345  7901  7901 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-07 10:33:33.345  7901  7901 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-07 10:33:33.345  7901  7901 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-07 10:33:33.350  7901  7901 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-07 10:33:33.355  7647  7898 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-07 10:33:33.355  7647  7898 D BluetoothAdapterProperties: Setting state to 11
09-07 10:33:33.355  7647  7898 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 10:33:33.357  7901  7901 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-07 10:33:33.357  7901  7901 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-07 10:33:33.360  7647  7902 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-07 10:33:33.362  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:33.362  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-07 10:33:33.362  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-07 10:33:33.369  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:33.369  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 10:33:33.373  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:33.376  6836  6836 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-07 10:33:33.378  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 10:33:33.379  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 10:33:33.386  7647  7902 D BluetoothAdapterProperties: Name is: G3
09-07 10:33:33.390  7647  7898 I LGBluetoothServiceJni: classInitNative: succeeds
,09-07 10:33:33.393  7647  7647 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 10:33:33.395  7647  7647 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:33.396  7647  7647 V BluetoothPbapReceiver: ***********state = 11
09-07 10:33:33.402  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:33:33.406  7647  7898 D BluetoothBondStateMachine: make
09-07 10:33:33.409  7647  7898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.409  7647  7898 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-07 10:33:33.409  7647  7898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.409  7647  7898 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-07 10:33:33.410  7647  7898 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-07 10:33:33.411  7647  7918 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 10:33:33.414  7647  7898 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:33.417  6836  6836 D BluetoothPermissionRequest: onReceive
,09-07 10:33:33.421  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 10:33:33.424  7647  7898 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:33.426  7647  7647 D HeadsetService: Received start request. Starting profile...
09-07 10:33:33.427  7647  7647 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 10:33:33.427  7647  7647 D LGBluetoothHfpAdapter: Version 1.6
,09-07 10:33:33.430  7647  7647 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-07 10:33:33.431  7647  7898 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:33.432  7647  7647 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 10:33:33.432  7647  7647 D HeadsetStateMachine: make
09-07 10:33:33.436  7647  7898 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:33.441  7647  7898 E BluetoothAdapterService: File transfer profiles supported!!
,09-07 10:33:33.447  7647  7898 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:33.452  7647  7898 E BluetoothAdapterService: File transfer profiles supported!!
09-07 10:33:33.467  7647  7898 V LGMDMManager: Create singleton instance
,09-07 10:33:33.469  7647  7898 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 10:33:33.470  7647  7647 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:33.470  7647  7647 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 10:33:33.474  7647  7647 D HeadsetStateMachine: max_hf_connections = 1
09-07 10:33:33.475  7647  7647 I bluedroid-qcom: get_profile_interface handsfree
09-07 10:33:33.477  7647  7647 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-07 10:33:33.477   320  2117 V AudioPolicyService: registerClient() client 0xb558a280, uid 1002
09-07 10:33:33.478   320  2128 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-07 10:33:33.478   320  2128 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,09-07 10:33:33.478   320  2128 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 10:33:33.478  7647  7647 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-07 10:33:33.478   320  1368 V AudioFlinger: registerClient() client 0xb55815e0, pid 7647
09-07 10:33:33.479   320  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,09-07 10:33:33.479   320  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:33.479  1834  1849 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:33.479  1834  1849 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:33.479  3486  3501 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:33.479  3486  3501 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:33.479   320  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:33.479   320  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:33.479  7647  7667 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:33.479  3486  3502 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:33.479  3486  3502 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-07 10:33:33.480  7647  7667 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-07 10:33:33.480  7647  7667 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:33.480  7647  7667 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-07 10:33:33.480  7647  7647 V ToneGenerator: Create Track: 0xb4928a80
09-07 10:33:33.480  1043  1861 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:33.480  7647  7647 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-07 10:33:33.480  1043  1861 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:33.480  7647  7647 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-07 10:33:33.480  1043  1861 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:33.480  1043  1861 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:33.480   320  2117 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 10:33:33.480   320  2117 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-07 10:33:33.480   320  2117 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 10:33:33.480   320  2117 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 10:33:33.480   320  2128 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 10:33:33.481   320  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-07 10:33:33.481   320  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-07 10:33:33.481   320  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-07 10:33:33.481   320  1369 V AudioPolicyManagerEx: getOutput() returns output 2
09-07 10:33:33.481  7647  7647 V AudioSystem: getLatency() output 2, latency 50
09-07 10:33:33.481  7647  7647 V AudioSystem: getFrameCount() output 2, frameCount 960
09-07 10:33:33.481  7647  7647 V AudioTrack: createTrack_l() output 2 afLatency 50
09-07 10:33:33.481  1834  3538 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:33.481  1834  3538 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:33.481   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 10:33:33.481   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 10:33:33.481   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-07 10:33:33.481   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-07 10:33:33.481   320   320 V AudioFlinger: createTrack() lSessionId: 23
09-07 10:33:33.481  1586  2248 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-07 10:33:33.482  1586  2248 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-07 10:33:33.482  1586  2248 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-07 10:33:33.482  1586  2248 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-07 10:33:33.482  7647  7647 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-07 10:33:33.482   320   320 V AudioFlinger: acquiring 23 from 7647, for 7647
09-07 10:33:33.482   320   320 V AudioFlinger:  added new entry for 23
09-07 10:33:33.482  7647  7647 V ToneGenerator: ToneGenerator INIT OK, time: 197562
09-07 10:33:33.482  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
,09-07 10:33:33.483  7647  7920 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-07 10:33:33.483  7647  7920 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-07 10:33:33.483  7647  7920 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-07 10:33:33.484  7647  7920 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-07 10:33:33.484   320  2117 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7647
09-07 10:33:33.484  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.486  7647  7647 D A2dpService: Received start request. Starting profile...
09-07 10:33:33.487   320  2117 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-07 10:33:33.487   320  2117 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-07 10:33:33.487   320  2117 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-07 10:33:33.487  7647  7647 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 10:33:33.487   320  2117 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 10:33:33.487   320  2117 V voice   : voice_set_parameters: exit with code(0)
09-07 10:33:33.487   320  2117 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-07 10:33:33.487   320  2117 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-07 10:33:33.487   320  2117 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 10:33:33.487   320  2117 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 10:33:33.487   320  2117 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 10:33:33.487   320  2117 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-07 10:33:33.488  7647  7920 V ToneGenerator: ToneGenerator destructor
09-07 10:33:33.488  7647  7920 V ToneGenerator: stopTone
09-07 10:33:33.488  7647  7920 V ToneGenerator: Delete Track: 0xb4928a80
09-07 10:33:33.488  7647  7647 V Avrcp   : make
09-07 10:33:33.488  7647  7647 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-07 10:33:33.488  7647  7647 I bluedroid-qcom: get_profile_interface avrcp
09-07 10:33:33.489  7647  7920 V AudioTrack: ~AudioTrack, releasing session id from 7647 on behalf of 7647
09-07 10:33:33.489  1043  2015 W Process : Unable to read /proc/7921/status
09-07 10:33:33.489   320  1368 V AudioFlinger: releasing 23 from 7647 for 7647
09-07 10:33:33.490   320  1368 V AudioFlinger:  decremented refcount to 0
09-07 10:33:33.490   320  1368 V AudioFlinger: purging stale effects
09-07 10:33:33.490   320  1368 V AudioPolicyService: AudioCommandThread() adding release output 2
09-07 10:33:33.490   320  1368 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-07 10:33:33.490   320  1272 V AudioPolicyService: AudioCommandThread() waking up
09-07 10:33:33.490   320  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
09-07 10:33:33.490   320  1272 V AudioPolicyManager: releaseOutput() 2
09-07 10:33:33.490   320  1272 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 10:33:33.490   320  1368 V AudioFlinger: PlaybackThread::Track destructor
09-07 10:33:33.490   320  1368 V AudioFlinger: removeClient_l() pid 7647, calling pid 320
09-07 10:33:33.496  7647  7647 V AudioManager: registerRemoteController: size of Media player list: 0
09-07 10:33:33.498  7647  7647 E AudioManager: No RCC entry present to update
09-07 10:33:33.498  7647  7647 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 10:33:33.501  7647  7647 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-07 10:33:33.502  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-07 10:33:33.502  7647  7647 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-07 10:33:33.505  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 10:33:33.624  1043  1863 V SIM_STK : Menu title from STK is T-Mobile
09-07 10:33:33.624  1043  1863 V SIM_STK : Menu title from STK is T-Mobile
,09-07 10:33:33.741  1043  1060 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-07 10:33:33.749  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 10:33:33.753  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 10:33:33.754  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 10:33:33.754  7647  7647 I BluetoothA2dpServiceJni: classInitNative
09-07 10:33:33.754  7647  7647 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 10:33:33.754  7647  7647 D A2dpStateMachine: make
09-07 10:33:33.759  7647  7647 I bluedroid-qcom: get_profile_interface a2dp
09-07 10:33:33.759  7647  7929 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 10:33:33.761  7647  7647 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-07 10:33:33.761  7647  7647 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-07 10:33:33.761  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.762  7647  7928 D A2dpStateMachine: Enter Disconnected: -2
09-07 10:33:33.762  7647  7647 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 10:33:33.763  7647  7647 D HidService: Received start request. Starting profile...
09-07 10:33:33.764  7647  7647 I bluedroid-qcom: get_profile_interface hidhost
09-07 10:33:33.764  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.764  7647  7647 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 10:33:33.765  7647  7647 D HealthService: Received start request. Starting profile...
09-07 10:33:33.769  7647  7647 I bluedroid-qcom: get_profile_interface health
09-07 10:33:33.769  7647  7647 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-07 10:33:33.769  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.770  7647  7647 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 10:33:33.772  7647  7647 D PanService: Received start request. Starting profile...
09-07 10:33:33.772  7647  7647 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 10:33:33.772  7647  7647 I bluedroid-qcom: get_profile_interface pan
,09-07 10:33:33.777  7647  7647 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-07 10:33:33.777  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.777  7647  7647 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-07 10:33:33.781  7647  7647 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 10:33:33.783  7647  7647 D BtGatt.GattService: Received start request. Starting profile...
09-07 10:33:33.783  7647  7647 D BtGatt.GattService: start()
09-07 10:33:33.783  7647  7647 I bluedroid-qcom: get_profile_interface gatt
09-07 10:33:33.783  7647  7647 D BtGatt.AdvertiseManager: advertise manager created
,09-07 10:33:33.788  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.789  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.790  7647  7647 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-07 10:33:33.790  7647  7647 V BluetoothMapService: BluetoothMapBinder()
09-07 10:33:33.791  7647  7647 D BluetoothMapService: Received start request. Starting profile...
09-07 10:33:33.791  7647  7647 D BluetoothMapService: start()
09-07 10:33:33.794  7647  7647 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-07 10:33:33.794  7647  7647 D BluetoothMapEmailAppObserver: createReceiver()
09-07 10:33:33.795  7647  7647 D BluetoothMapEmailAppObserver: initObservers()
09-07 10:33:33.795  7647  7647 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-07 10:33:33.803  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:33.804  7647  7647 D HeadsetStateMachine: Proxy object connected
09-07 10:33:33.804  7647  7647 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-07 10:33:33.804  7647  7647 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-07 10:33:33.806  7647  7920 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 10:33:33.806  7647  7920 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 10:33:33.806  7647  7920 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-07 10:33:33.809  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:33.810  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:33:33.816  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:33.818  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-07 10:33:33.821  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:33.823  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-07 10:33:33.824  7647  7647 V PanService: [BTUI] SIM Extra State :ABSENT
,09-07 10:33:33.826  7647  7647 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-07 10:33:33.826  7647  7647 V BluetoothMapService: Handler(): got msg=1
09-07 10:33:33.827  7647  7647 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 10:33:33.827  7647  7647 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:33.827  7647  7647 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 10:33:33.827  7647  7647 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:33.827  7647  7647 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-07 10:33:33.829  7647  7898 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-07 10:33:33.829  7647  7898 I bluedroid-qcom: enable
09-07 10:33:33.830  7647  7898 I bt_hci_bdroid: init
09-07 10:33:33.831  7647  7898 I bt_vendor: bt-vendor : init
09-07 10:33:33.831  7647  7898 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 10:33:33.831  7647  7898 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 10:33:33.831  7647  7898 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-07 10:33:33.831  7647  7898 D bt_userial_mct: userial_init
09-07 10:33:33.832  7647  7940 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 10:33:33.832  7647  7940 I bt-btu  : btu_task pending for preload complete event
09-07 10:33:33.832  7647  7898 D bt_hci_bdroid: set_power 1
09-07 10:33:33.832  7647  7898 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 10:33:33.832  7647  7898 I bt_vendor: Starting hciattach daemon
09-07 10:33:33.832  7647  7898 I bt_vendor: try to set true
09-07 10:33:33.823  7943  7943 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:33.823  7943  7943 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 10:33:33.853  7944  7944 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-07 10:33:33.896  7950  7950 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-07 10:33:33.904  7951  7951 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-07 10:33:33.920  7953  7953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 10:33:33.927  7954  7954 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-07 10:33:33.936  7955  7955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 10:33:33.943  7956  7956 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 10:33:33.978  7958  7958 I libmdmdetect: ESOC framework not supported
09-07 10:33:33.979  7958  7958 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-07 10:33:33.987  7958  7958 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-07 10:33:33.987  7958  7958 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-07 10:33:33.987  7958  7958 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-07 10:33:33.987  7958  7958 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-07 10:33:33.987  7958  7958 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-07 10:33:33.987  7958  7958 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-07 10:33:33.987  7958  7958 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-07 10:33:34.027  7958  7959 E QC-QMI  : qmi_client [7958] 15: failed to locate client data
09-07 10:33:34.028   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-07 10:33:34.028   444   444 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-07 10:33:34.079  7960  7960 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-07 10:33:34.097  7961  7961 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 10:33:34.137  7647  7898 I bt_vendor: bluetooth satus is on
09-07 10:33:34.137  7647  7898 D bt_hci_bdroid: preload
09-07 10:33:34.137  7647  7942 D bt_userial_mct: userial_open(port:0)
09-07 10:33:34.137  7647  7942 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 10:33:34.143  7647  7942 I bt_vendor: Done intiailizing UART
,09-07 10:33:34.148  7647  7942 I bt_vendor: Done intiailizing UART
,09-07 10:33:34.148  7647  7942 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-07 10:33:34.149  7647  7942 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 10:33:34.149  7647  7940 I bt-btu  : btu_task received preload complete event
09-07 10:33:34.150  7647  7963 D bt_userial_mct: Entering userial_read_thread()
09-07 10:33:34.152  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-07 10:33:34.152  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,09-07 10:33:34.159  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-07 10:33:34.168  7647  7940 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 10:33:34.168  7647  7940 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 10:33:34.168  7647  7940 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 10:33:34.168  7647  7940 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 10:33:34.169  7647  7940 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 10:33:34.248  7647  7940 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-07 10:33:34.248  7647  7940 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016b061 
09-07 10:33:34.248  7647  7940 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016b061 
,09-07 10:33:34.271  7647  7902 E bt-btif : Calling BTA_HhEnable
09-07 10:33:34.271  7647  7902 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-07 10:33:34.271  7647  7902 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-07 10:33:34.274  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-07 10:33:34.274  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-07 10:33:34.274  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-07 10:33:34.275  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-07 10:33:34.276  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
09-07 10:33:34.276  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-07 10:33:34.276  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-07 10:33:34.276  7647  7902 D BluetoothAdapterProperties: Name is: G3
09-07 10:33:34.277  7647  7902 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:33:34.278  7647  7902 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 10:33:34.278  7647  7902 D bt_hci_bdroid: postload
09-07 10:33:34.278  7647  7942 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:34.279  7647  7942 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:34.279  7647  7942 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:34.279  7647  7942 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:34.280  7647  7940 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-07 10:33:34.280  7647  7902 D bte_conf: Device ID record 1 : primary
09-07 10:33:34.280  7647  7902 D bte_conf:   vendorId            = 00c4
09-07 10:33:34.281  7647  7902 D bte_conf:   vendorIdSource      = 0001
09-07 10:33:34.281  7647  7902 D bte_conf:   product             = 13a1
09-07 10:33:34.281  7647  7902 D bte_conf:   version             = 1000
09-07 10:33:34.281  7647  7902 D bte_conf:   clientExecutableURL = 
09-07 10:33:34.281  7647  7902 D bte_conf:   serviceDescription  = 
09-07 10:33:34.281  7647  7902 D bte_conf:   documentationURL    = 
09-07 10:33:34.281  7647  7902 D bte_conf: bte_load_did_conf no section named DID2.
09-07 10:33:34.281  7647  7942 D bt_hci_bdroid: Used up Tx Cmd credits
09-07 10:33:34.284  7647  7963 E bt_mct  : hci lib postload completed
,09-07 10:33:34.290  7647  7940 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:34.290  7647  7940 W bt-smp  : Plain text(LSB ~ MSB) = cb 9d 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:34.290  7647  7940 W bt-smp  : Encrypted text(LSB ~ MSB) = 9c 52 13 60 85 a1 a2 e1 ca fa fd 8e a0 d0 d5 61 
09-07 10:33:34.290  7647  7940 W bt-btm  : Stopping oneshot timer
09-07 10:33:34.291  7647  7898 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 10:33:34.291  7647  7898 D BluetoothAdapterProperties: ScanMode =  20
09-07 10:33:34.291  7647  7898 D BluetoothAdapterProperties: State =  11
09-07 10:33:34.291  7647  7898 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-07 10:33:34.291  7647  7898 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-07 10:33:34.291  7647  7898 D BluetoothAdapterProperties: Setting state to 12
09-07 10:33:34.292  7647  7898 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 10:33:34.292  7647  7902 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 10:33:34.292  7647  7902 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 10:33:34.283  7968  7968 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:34.283  7968  7968 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:34.303  1043  1119 D BluetoothManagerService: Message: 60
09-07 10:33:34.303  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-07 10:33:34.303  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-07 10:33:34.312  7647  7898 I BluetoothAdapterState: Entering On State
09-07 10:33:34.318  7647  7898 D LGBluetoothServiceAdapter: [BTUI] OnState
09-07 10:33:34.318  7647  7898 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-07 10:33:34.318  7647  7898 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-07 10:33:34.320  7647  7898 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-07 10:33:34.339  7647  7940 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:34.339  7647  7940 W bt-smp  : Plain text(LSB ~ MSB) = ae dc 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:34.339  7647  7940 W bt-smp  : Encrypted text(LSB ~ MSB) = da e9 84 50 1a f5 5e 38 d0 4c 03 93 fb 69 b4 e2 
,09-07 10:33:34.341  7647  7940 W bt-btm  : Stopping oneshot timer
09-07 10:33:34.354  7647  7902 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 10:33:34.357  7647  7902 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:34.360  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:34.364  7647  7898 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-07 10:33:34.365  7647  7940 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:34.365  7647  7940 W bt-smp  : Plain text(LSB ~ MSB) = c5 59 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:34.365  7647  7940 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 2a 76 96 1d 1e 22 bd 24 04 2d a4 c0 55 b0 f7 
09-07 10:33:34.365  7647  7940 W bt-btm  : Stopping oneshot timer
09-07 10:33:34.368  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:33:34.379  7647  7940 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-07 10:33:34.380  7647  7940 W bt-smp  : Plain text(LSB ~ MSB) = 39 de 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:34.380  7647  7940 W bt-smp  : Encrypted text(LSB ~ MSB) = aa 82 83 2a 94 27 6f 73 09 3b bb 7e 4a e5 a9 e3 
09-07 10:33:34.383  7647  7940 W bt-btm  : Stopping oneshot timer
,09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:34.389  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:33:34.392  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:33:34.397  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:34.397  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14137163 added. We now have 8 listener(s)
09-07 10:33:34.397  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:33:34.402  1043  1059 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-07 10:33:34.402  1043  1059 D WifiService: setWifiEnabled: false pid=6729, uid=10118
,09-07 10:33:34.402  1043  1059 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 10:33:34.407  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:34.409  1043  1943 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-07 10:33:34.410  1043  1943 D WifiService: setWifiEnabled: true pid=6729, uid=10118
09-07 10:33:34.410  1043  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 10:33:34.415  6836  6854 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 10:33:34.416  7985  7985 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-07 10:33:34.417  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:34.419  6836  6852 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 10:33:34.423  1043  1043 D BluetoothHeadset: Proxy object connected
09-07 10:33:34.425  1043  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-07 10:33:34.425  1043  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-07 10:33:34.427  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 10:33:34.427  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-07 10:33:34.427  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-07 10:33:34.429  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:34.429  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-07 10:33:34.429  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 10:33:34.429  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-07 10:33:34.429  1043  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-07 10:33:34.429  1043  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-07 10:33:34.429  1043  1523 E WifiHW  : unknown target_country: EU , set to default
09-07 10:33:34.429  1043  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-07 10:33:34.429  1043  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-07 10:33:34.429  1043  1523 I WifiUtil: gEnableBmps=1
09-07 10:33:34.430  6836  6836 D BluetoothA2dp: Proxy object connected
09-07 10:33:34.430  6836  6836 D A2dpProfile: Bluetooth service connected
09-07 10:33:34.433  7647  7940 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-07 10:33:34.433  7647  7940 W bt-smp  : Plain text(LSB ~ MSB) = 20 db 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 10:33:34.433  7647  7940 W bt-smp  : Encrypted text(LSB ~ MSB) = 3c 76 12 72 a9 66 4c 91 80 81 a9 37 0f e9 e0 f2 
09-07 10:33:34.433  7647  7940 W bt-btm  : Stopping oneshot timer
09-07 10:33:34.435  1834  1834 D BluetoothHeadset: Proxy object connected
,09-07 10:33:34.436  6836  6854 D BluetoothMap: onBluetoothStateChange: up=true
09-07 10:33:34.442  6836  6836 D BluetoothMap: Proxy object connected
09-07 10:33:34.442  6836  6836 D MapProfile: Bluetooth service connected
,09-07 10:33:34.442  6836  6836 D BluetoothMap: getConnectedDevices()
09-07 10:33:34.444  6836  6852 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 10:33:34.444  7647  7666 V BluetoothMapService: getConnectedDevices()
09-07 10:33:34.448  1834  3538 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:34.449  6836  6836 D BluetoothInputDevice: Proxy object connected
09-07 10:33:34.450  6836  6836 D HidProfile: Bluetooth service connected
,09-07 10:33:34.453  1834  1834 D BluetoothHeadset: Proxy object connected
09-07 10:33:34.454  1834  1849 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:34.456  1834  1834 D BluetoothHeadset: Proxy object connected
09-07 10:33:34.456  6836  6854 D BluetoothPan: onBluetoothStateChange on: true
09-07 10:33:34.456  6836  6854 D BluetoothPan: onBluetoothStateChange call bindService
09-07 10:33:34.458  6836  6852 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 10:33:34.459  6836  6836 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 10:33:34.459  6836  6836 D PanProfile: Bluetooth service connected
09-07 10:33:34.460  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 10:33:34.461  1043  1043 D BluetoothA2dp: Proxy object connected
09-07 10:33:34.461  6836  6836 D BluetoothHeadset: Proxy object connected
09-07 10:33:34.461  6836  6836 D HeadsetProfile: Bluetooth service connected
,09-07 10:33:34.464  1043  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-07 10:33:34.464  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-07 10:33:34.464  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-07 10:33:34.465  1043  1119 D BluetoothManagerService: Message: 40
09-07 10:33:34.465  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-07 10:33:34.465  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.466  1925  2097 D LGBluetoothAPIService: Message: 1
09-07 10:33:34.466  1925  2097 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-07 10:33:34.466  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-07 10:33:34.473  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:34.476  7647  7647 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.477  7647  7647 D BluetoothMapService: STATE_ON
09-07 10:33:34.481  1925  2097 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-07 10:33:34.484  6836  6836 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-07 10:33:34.486  6836  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-07 10:33:34.493  6836  6836 D DockEventReceiver: finishStartingService: stopping service
09-07 10:33:34.494  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:34.494  7647  7647 V BluetoothPbapService: Pbap Service onCreate
09-07 10:33:34.494  7647  7647 V BluetoothPbapService: Starting PBAP service
09-07 10:33:34.496  7647  7647 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-07 10:33:34.496  7647  7647 V BluetoothPbapService: Pbap Service onBind
09-07 10:33:34.497  6836  6836 D BluetoothPbap: Proxy object connected
09-07 10:33:34.497  6836  6836 D PbapServerProfile: Bluetooth service connected
09-07 10:33:34.497  7647  7647 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.497  7647  7647 V BluetoothPbapService: state: 12
09-07 10:33:34.498  7647  7647 V BluetoothMapService: Handler(): got msg=1
09-07 10:33:34.498  7647  7647 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-07 10:33:34.500  7647  7995 D BluetoothMapMasInstance: MAS initSocket()
09-07 10:33:34.500  7647  7995 D BluetoothMapMasInstance:   masId = 00
09-07 10:33:34.500  7647  7995 D BluetoothMapMasInstance:   msgTypes = 0e
09-07 10:33:34.500  7647  7995 D BluetoothMapMasInstance:   masName = SMS/MMS
09-07 10:33:34.500  7647  7995 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-07 10:33:34.500  7647  7647 D LGBluetoothAPIServer: [BTUI] onCreate()
09-07 10:33:34.501  7647  7647 D LGBluetoothAPIServer: [BTUI] onBind()
,09-07 10:33:34.502  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:34.502  7647  7647 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-07 10:33:34.502  7647  7647 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.502  7647  7647 V BluetoothPbapReceiver: ***********state = 12
09-07 10:33:34.502  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-07 10:33:34.503  1925  2097 D LGBluetoothAPIService: Message: 100
09-07 10:33:34.503  1925  2097 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-07 10:33:34.504  7647  7647 V BluetoothPbapService: Handler(): got msg=1
09-07 10:33:34.504  7647  7647 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-07 10:33:34.505  7647  7995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:34.506  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:33:34.507  7647  7902 D BluetoothAdapterProperties: Scan Mode:21
09-07 10:33:34.507  7647  7902 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-07 10:33:34.507  7647  7996 V BluetoothPbapService: Pbap Service initSocket
09-07 10:33:34.507  7647  7995 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=74 mFd=0
09-07 10:33:34.507  7647  7995 V BluetoothMapMasInstance: Succeed to create listening socket 
09-07 10:33:34.507  2066  2066 D c       : Getting all permits...
09-07 10:33:34.507  2066  2066 D a       : Opening database...
09-07 10:33:34.507  7647  7995 D BluetoothMapMasInstance: Accepting socket connection...
09-07 10:33:34.509  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:34.510  1043  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:34.512  7647  7996 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:33:34.513  7647  7996 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=74
09-07 10:33:34.513  7647  7996 V BluetoothPbapService: Succeed to create listening socket 
09-07 10:33:34.513  7647  7996 V BluetoothPbapService: Accepting socket connection...
09-07 10:33:34.515  2066  2066 D a       : Opening database auth.proximity.permit_store...
09-07 10:33:34.516  2066  2066 D a       : Closing database...
09-07 10:33:34.527  6836  6836 D BluetoothPermissionRequest: onReceive
,09-07 10:33:34.528  6836  6836 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-07 10:33:34.530  6836  6836 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-07 10:33:34.534  7647  7647 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-07 10:33:34.535  7647  7647 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-07 10:33:34.542  7647  7647 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-07 10:33:34.565  7647  7647 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-07 10:33:34.566  7647  7647 V BtOppService: onCreate
09-07 10:33:34.570  7647  7647 V BluetoothOppNotification: send message
09-07 10:33:34.574  7647  7647 V BtOppService: Starting RfcommListener
09-07 10:33:34.580  7647  7647 D BluetoothOppPreference: Dumping Names:  
09-07 10:33:34.580  7647  7647 D BluetoothOppPreference: {}
09-07 10:33:34.580  7647  7647 D BluetoothOppPreference: Dumping Channels:  
,09-07 10:33:34.580  7647  7647 D BluetoothOppPreference: {}
09-07 10:33:34.583  7647  7647 V BtOppService: onStartCommand
,09-07 10:33:34.590  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.590  7647  7647 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-07 10:33:34.595  7647  7647 V BluetoothOppNotification: new notify threadi!
09-07 10:33:34.596  7647  8000 V BtOppService: Deleted complete outbound shares, number =  0
,09-07 10:33:34.597  7647  7647 V BluetoothOppNotification: send delay message
09-07 10:33:34.599  7647  8003 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 10:33:34.599  7647  8004 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-07 10:33:34.599  7647  8003 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 10:33:34.600  7647  7647 V BtOppService: start RfcommListener
09-07 10:33:34.602  7647  8003 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37dfb69a on behalf of 
,09-07 10:33:34.604  7647  8004 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8ffdbcb on behalf of 
09-07 10:33:34.605  7647  8004 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 10:33:34.605  7647  8000 V BtOppService: Deleted complete inbound failed shares, number = 0
09-07 10:33:34.606  7647  8000 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-07 10:33:34.606  7647  8004 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:34.607  7647  8003 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 10:33:34.608  7647  8000 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13ea9fa8 on behalf of 
09-07 10:33:34.609  7647  8004 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b7b5ac1 on behalf of 
09-07 10:33:34.610  7647  8004 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 10:33:34.611  7647  7647 V BtOppService: RfcommListener started
09-07 10:33:34.612  7647  8004 V BluetoothOppNotification: outbound notification was removed.
09-07 10:33:34.612  7647  8004 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:34.612  7647  8005 V BtOppRfcommListener: Starting RFCOMM listener....
09-07 10:33:34.613  1043  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:34.614  7647  8005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:33:34.618  7647  8004 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b72a266 on behalf of 
,09-07 10:33:34.618  7647  8005 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-07 10:33:34.618  7647  8004 V BluetoothOppNotification: inbound: succ-0  fail-0
09-07 10:33:34.620  7647  8004 V BluetoothOppNotification: inbound notification was removed.
09-07 10:33:34.620  7647  8004 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 10:33:34.620  7647  8005 V BtOppRfcommListener: Started RFCOMM listener....
,09-07 10:33:34.621  7647  8005 I BtOppRfcommListener: Accept thread started.
09-07 10:33:34.621  7647  8005 V BtOppRfcommListener: Accepting connection...
09-07 10:33:34.629  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:34.629  7647  7647 V BluetoothFtpService: Ftp Service onCreate
09-07 10:33:34.629  7647  7647 I BluetoothFtpService: Ftp Service onCreate
09-07 10:33:34.629  7647  7647 V BluetoothFtpService: Ftp Service onStartCommand
09-07 10:33:34.629  7647  7647 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.630  7647  7647 V BluetoothFtpService: Starting Listening on sockets
,09-07 10:33:34.630  7647  7647 V BtOppService: ContentObserver received notification
09-07 10:33:34.631  7647  7647 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-07 10:33:34.631  7647  7647 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-07 10:33:34.631  7647  7647 V BluetoothSapReceiver: SapReceiver onReceive 
09-07 10:33:34.631  7647  7647 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.631  7647  7647 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-07 10:33:34.631  7647  7647 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-07 10:33:34.632  7647  8006 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 10:33:34.632  7647  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-07 10:33:34.756  1043  1980 I art     : Explicit concurrent mark sweep GC freed 25801(1273KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.721ms total 134.306ms
,09-07 10:33:34.757  7647  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c1e0e54 on behalf of 
09-07 10:33:34.757  7647  7647 V BtOppService: ContentObserver received notification
09-07 10:33:34.758  7647  7647 V BluetoothFtpService: Handler(): got msg=1
09-07 10:33:34.758  7647  7647 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-07 10:33:34.758  7647  7647 V BluetoothFtpService: Ftp Service initSocket
09-07 10:33:34.761  7647  8004 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a21e1fd on behalf of 
09-07 10:33:34.761  7647  8006 V BluetoothOppNotification: update too frequent, put in queue
09-07 10:33:34.762  1043  1708 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:34.763  7647  7647 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:34.763  7647  8006 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-07 10:33:34.763  7647  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-07 10:33:34.765  7647  7647 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-07 10:33:34.766  7647  7647 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-07 10:33:34.765  7647  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9f67ef2 on behalf of 
09-07 10:33:34.769  7647  8006 V BluetoothOppNotification: update too frequent, put in queue
,09-07 10:33:34.774  7647  8007 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-07 10:33:34.775  7647  8006 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-07 10:33:34.781  7647  7647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29179339
09-07 10:33:34.781  7647  7647 V BluetoothSapService: Sap Service onCreate
09-07 10:33:34.783  7647  7647 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:33:34.783  7647  7647 V BluetoothSapService: state: 12
09-07 10:33:34.783  7647  7647 V BluetoothSapService: Starting SAP server process
09-07 10:33:34.785  7647  7647 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-07 10:33:34.786  7647  8009 V BluetoothSapService: Sap Service initRfcommSocket
09-07 10:33:34.773  8008  8008 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:34.788  1043  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:34.788  7647  8009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 10:33:34.790  7647  8009 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-07 10:33:34.790  7647  8009 V BluetoothSapService: Succeed to create listening socket 
09-07 10:33:34.790  7647  8009 V BluetoothSapService: Accepting socket connection...
09-07 10:33:34.773  8008  8008 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:34.798  8008  8008 V BT_SAP  : Event pipe created
09-07 10:33:34.798  8008  8008 V BT_SAP  : create_server_socket qcom.sap.server
09-07 10:33:34.798  8008  8008 V BT_SAP  : created socket fd 6
,09-07 10:33:35.265  7678  7749 D UEI.SmartControl: Internal timer expired: 1
09-07 10:33:35.265  7678  7749 D UEI.SmartControl: unbind internal service
,09-07 10:33:35.292   315   903 D SoftapController: Softap fwReload - Ok
,09-07 10:33:35.298  1043  1523 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (866ms)
09-07 10:33:35.309   315   903 D CommandListener: Setting iface cfg
09-07 10:33:35.310   315   903 D CommandListener: Trying to bring down wlan0
,09-07 10:33:35.314  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:33:35.314  1043  1119 D Tethering: InitialState.processMessage what=4
09-07 10:33:35.333   315   903 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:33:35.337  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:33:35.341  1043  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-07 10:33:35.399  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-07 10:33:35.400  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 10:33:35.400  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 10:33:35.400  6836  6836 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 10:33:35.401  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 10:33:35.405  6836  6836 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 10:33:35.405  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 10:33:35.405  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 10:33:35.405  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 10:33:35.405  6836  6836 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 10:33:35.406  6836  6836 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 10:33:35.408  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:35.408  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:35.408  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-07 10:33:35.412  1043  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 10:33:35.412  1043  1523 D WifiMonitor: connecting to supplicant
09-07 10:33:35.413  1043  1523 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-07 10:33:35.414  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 10:33:35.414  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 10:33:35.414  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 10:33:35.414  6836  6836 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 10:33:35.403  8038  8038 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:35.403  8038  8038 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:35.419  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:35.420  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-07 10:33:35.421  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:35.421  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-07 10:33:35.422  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 10:33:35.423  6836  6836 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 10:33:35.423  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-07 10:33:35.423  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 10:33:35.423  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 10:33:35.423  6836  6836 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 10:33:35.423  6836  6836 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-07 10:33:35.449  8038  8038 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 10:33:35.473  1043  1979 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8044 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-07 10:33:35.478  7678  7678 D UEI.SmartControl: Service.onUnbind: IControl
09-07 10:33:35.479  7678  7678 D UEI.SmartControl: Service.onDestroy
09-07 10:33:35.479  7678  7678 D UEI.SmartControl: Lock is in USE false
09-07 10:33:35.479  7678  7678 D UEI.SmartControl: unbind internal service
09-07 10:33:35.481  8038  8038 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 10:33:35.481  8038  8038 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-07 10:33:35.484  7678  7678 D serial_port: close(fd = 25)
09-07 10:33:35.508  7678  7678 I UEI.SmartControl: Serial port is closed.
09-07 10:33:35.508  7678  7678 I UEI.SmartControl: Serial port is closed.
09-07 10:33:35.508  7678  7678 D UEI.SmartControl: Blaster closed
09-07 10:33:35.508  7678  7678 D UEI.SmartControl: Shut down QS...
09-07 10:33:35.508  7678  7678 D UEI.SmartControl: Stopping QS lib
09-07 10:33:35.509  7678  7678 D UEI.SmartControl: QS lib stop result = true
,09-07 10:33:35.509  7678  7678 D UEI.SmartControl: Stopped QS lib
09-07 10:33:35.509  7678  7678 D UEI.SmartControl: Stopped file observer...
09-07 10:33:35.509  7678  7678 D UEI.SmartControl: QS shutdown complete
,09-07 10:33:35.566  8038  8038 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 10:33:35.579  1043  1631 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8066 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 10:33:35.582  8044  8064 W FormManager: Network not available. Please check & try again.
09-07 10:33:35.587  8044  8065 V FormManager: Network unavailable.
09-07 10:33:35.588  8044  8065 V FormManager: Network unavailable.
09-07 10:33:35.598  7647  7647 V BluetoothOppNotification: new notify threadi!
09-07 10:33:35.598  7647  7647 V BluetoothOppNotification: send delay message
09-07 10:33:35.599  7647  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-07 10:33:35.599  7647  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e69983e on behalf of 
09-07 10:33:35.600  7647  8084 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-07 10:33:35.603  8038  8038 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-07 10:33:35.607  7647  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:35.608  7647  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d4ce69f on behalf of 
09-07 10:33:35.608  7647  8084 V BluetoothOppNotification: outbound: succ-0  fail-0
09-07 10:33:35.609  7647  8084 V BluetoothOppNotification: outbound notification was removed.
09-07 10:33:35.609  7647  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-07 10:33:35.611  8038  8038 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 10:33:35.612  7647  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5fcd3ec on behalf of 
09-07 10:33:35.612  7647  8084 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-07 10:33:35.614  7647  8084 V BluetoothOppNotification: inbound notification was removed.
,09-07 10:33:35.614  7647  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-07 10:33:35.615  7647  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29c053b5 on behalf of 
09-07 10:33:35.631  8066  8066 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-07 10:33:35.632  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 10:33:35.637  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:35.638  1043  1863 I ActivityManager: Killing 7157:com.lge.drmservice/u0a62 (adj 15): empty #17
09-07 10:33:35.663  1043  1060 W libprocessgroup: failed to open /acct/uid_10062/pid_7157/cgroup.procs: No such file or directory
,09-07 10:33:36.329  8038  8038 E wpa_supplicant: USIM:  scard_init function
,09-07 10:33:36.330  8038  8038 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-07 10:33:36.432  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-07 10:33:36.436  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-07 10:33:36.437  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-07 10:33:36.437  1043  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-07 10:33:36.437  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.438  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.438  1043  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.439  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.439  1043  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-07 10:33:36.439  1043  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-07 10:33:36.442  1043  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-07 10:33:36.442  1043  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-07 10:33:36.442  1043  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-07 10:33:36.443  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.444  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.444  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.444  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.444  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-07 10:33:36.444  1043  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-07 10:33:36.444  1043  1523 E WifiStateMachine: useWiFiOffloading() : false
09-07 10:33:36.444  1043  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-07 10:33:36.452  1925  1925 D WfdService: Waiting for WifiP2p enabling
09-07 10:33:36.453  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:33:36.461  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:33:36.467  8038  8038 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-07 10:33:36.476  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:33:36.480  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-07 10:33:36.480  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,09-07 10:33:36.480  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-07 10:33:36.480  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-07 10:33:36.488  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-07 10:33:36.488  1043  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-07 10:33:36.493  8038  8038 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 10:33:36.493  8038  8038 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 10:33:36.497  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 10:33:36.497  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:36.497  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:36.498  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:36.498  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:36.498  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-07 10:33:36.498  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 10:33:36.498  1043  8096 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 10:33:36.498  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-07 10:33:36.498  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 10:33:36.498  1043  8096 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-07 10:33:36.498  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:36.498  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-07 10:33:36.511  1043  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
09-07 10:33:36.511  1043  1523 D WifiNative-wlan0: SET update_config 1: returned true
09-07 10:33:36.511  1043  1523 D WifiConfigStore: Loading config and enabling all networks 
09-07 10:33:36.511  1043  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-07 10:33:36.512  1043  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
09-07 10:33:36.523  1043  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-07 10:33:36.534  1043  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-07 10:33:36.534  1043  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-07 10:33:36.536  1043  1523 D WifiStateMachine: enableVerboseLogging : level 2
09-07 10:33:36.536  1043  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-07 10:33:36.536  1043  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-07 10:33:36.537  1043  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-07 10:33:36.537  1043  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-07 10:33:36.537  1043  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-07 10:33:36.537  1043  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-07 10:33:36.537  1043  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-07 10:33:36.538  1043  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-07 10:33:36.538  1043  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-07 10:33:36.538  1043  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-07 10:33:36.538  1043  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-07 10:33:36.539  1043  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-07 10:33:36.539  1043  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-07 10:33:36.539  1043  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-07 10:33:36.541  1925  1925 D WfdsService: Supplicant Connection state is changed : true
09-07 10:33:36.541  1925  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-07 10:33:36.541  1925  2279 D WfdsService: Set the WFDS Monitor: true
09-07 10:33:36.541  1925  2279 D WfdsMonitor: WfdsMonitorThread create
09-07 10:33:36.542  1925  2279 D WfdsMonitor: WFDS Monitor is created and started
09-07 10:33:36.542  1925  2279 D WfdsService: WiFi: Supplicant connection re-established
09-07 10:33:36.542  1043  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 10:33:36.542  1043  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-07 10:33:36.547  1043  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-07 10:33:36.547  1043  1523 D WifiNative-HAL: Setting external_sim to 1
09-07 10:33:36.547  1043  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-07 10:33:36.548  1043  1523 D WifiNative-wlan0: SET external_sim 1: returned true
09-07 10:33:36.548  1043  1523 I WifiNative-HAL: startHal
09-07 10:33:36.548  1043  1523 D wifi    : setting scan oui 0xaf75cf40
09-07 10:33:36.548  1043  1523 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 10:33:36.548  1043  1523 I WifiNative-HAL: startHal
09-07 10:33:36.548  1043  1523 D wifi    : setting scan oui 0xaf75cf40
09-07 10:33:36.549  1043  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-07 10:33:36.549  1925  8097 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-07 10:33:36.550  1925  8097 E CtrlSupplicant: Succeed to open control connection
09-07 10:33:36.550  1925  8097 E CtrlSupplicant: Succeed to open monitor connection
09-07 10:33:36.551  1925  8097 D WfdsMonitor: Supplicant connection established
09-07 10:33:36.552  1043  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-07 10:33:36.552  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-07 10:33:36.552  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-07 10:33:36.552  1925  2279 D WfdsService: Connected to the supplicant for wfds
09-07 10:33:36.553  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-07 10:33:36.553  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 10:33:36.553  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-07 10:33:36.553  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 10:33:36.553  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-07 10:33:36.554  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-07 10:33:36.554  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-07 10:33:36.554  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 10:33:36.554  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 10:33:36.556  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 10:33:36.556  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-07 10:33:36.556  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-07 10:33:36.559  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-07 10:33:36.559  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-07 10:33:36.559  8038  8038 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-07 10:33:36.560  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-07 10:33:36.560  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-07 10:33:36.560  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-07 10:33:36.560  1043  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-07 10:33:36.561  1043  1523 E WifiNative: : [200,625,130 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-07 10:33:36.561  1043  1523 D WifiNative-wlan0: doBoolean: RECONNECT
09-07 10:33:36.562  1043  1523 D WifiNative-wlan0: RECONNECT: returned true
09-07 10:33:36.562  1043  1523 D WifiNative-wlan0: doString: [STATUS]
09-07 10:33:36.563  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:36.563  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:36.563  1043  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 10:33:36.563  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:36.564  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
09-07 10:33:36.564  1043  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.566   315   903 D CommandListener: Setting iface cfg
09-07 10:33:36.566   315   903 D CommandListener: Trying to bring up p2p0
09-07 10:33:36.567  1043  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 10:33:36.567  1043  1521 D LGWifiP2pService: P2pEnablingState
09-07 10:33:36.567  1043  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.567  1043  1521 D LGWifiP2pService: P2p socket connection successful
09-07 10:33:36.568  1043  1521 D LGWifiP2pService: P2pEnabledState
,09-07 10:33:36.572  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-07 10:33:36.572  1925  1925 D WfdsService: WifiP2pState is changed : true
09-07 10:33:36.573  1925  2279 D WfdsService: Receive the WFDS_ENABLE Method
09-07 10:33:36.573  1925  2279 D WfdsService: Set the WFDS Monitor: true
09-07 10:33:36.573  1925  2279 D WfdsService: Connected to the supplicant for wfds
09-07 10:33:36.573  1925  2279 D WfdsJNI : doCommand: WFDS_SET TRUE
09-07 10:33:36.573  8038  8038 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-07 10:33:36.573  1925  2279 D WfdsService: selectPreferredScanChannel [36]
09-07 10:33:36.573  1925  2279 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-07 10:33:36.577  1043  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-07 10:33:36.579  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-07 10:33:36.580  1925  1925 D WfdsService: isConnected: false
,09-07 10:33:36.583  1043  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-07 10:33:36.584  1043  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-07 10:33:36.584  1043  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-07 10:33:36.584  1043  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-07 10:33:36.585  1043  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-07 10:33:36.585  1043  1521 D LGWifiP2pService: before postfix = G3
09-07 10:33:36.585  1043  1521 D WifiServerServiceExt: postfix byte check : 2
09-07 10:33:36.585  1043  1521 D LGWifiP2pService: after postfix = G3
09-07 10:33:36.585  1043  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-07 10:33:36.586  1043  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-07 10:33:36.586  1043  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-07 10:33:36.586  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 10:33:36.587  1043  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.587  1043  1540 I WifiNative-HAL: startHal
09-07 10:33:36.587  1043  1043 D RttService: SCAN_AVAILABLE : 3
09-07 10:33:36.587  1043  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.588  1043  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-07 10:33:36.589  1043  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-07 10:33:36.589  1043  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-07 10:33:36.589  1043  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-07 10:33:36.590  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=200654  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 10:33:36.591  1043  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-07 10:33:36.591  1043  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf75cf40
09-07 10:33:36.591  1043  1540 D wifi    : failed to get capabilities : -3
09-07 10:33:36.591  1043  1540 E WifiScanningService: could not get scan capabilities
09-07 10:33:36.591  1043  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-07 10:33:36.593  1043  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-07 10:33:36.593  1043  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,09-07 10:33:36.596  1043  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-07 10:33:36.596  1043  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-07 10:33:36.596  1043  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-07 10:33:36.603  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.603  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.604  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 10:33:36.608  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:36.608  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:36.609  1043  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-07 10:33:36.610  1043  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-07 10:33:36.612  1043  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
,09-07 10:33:36.612  1043  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-07 10:33:36.615  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
09-07 10:33:36.615  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-07 10:33:36.615  1925  1925 D WfdsService: Update P2p Interface State: 3
09-07 10:33:36.617  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:36.617  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=200681  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-07 10:33:36.619  1043  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200683
09-07 10:33:36.620  1043  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200684
09-07 10:33:36.621  1043  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-07 10:33:36.621  1043  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,09-07 10:33:36.622  1043  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200686
09-07 10:33:36.622  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200686
09-07 10:33:36.622  1043  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200687
09-07 10:33:36.623  1043  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-07 10:33:36.623  1043  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-07 10:33:36.624  1043  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-07 10:33:36.624  1043  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-07 10:33:36.624  8038  8038 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-07 10:33:36.625  1043  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-07 10:33:36.625  1043  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-07 10:33:36.626  1043  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-07 10:33:36.626  1043  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-07 10:33:36.626  8038  8038 E wpa_supplicant: disconnect_rssi_lvl: -100
09-07 10:33:36.627  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=200690  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 10:33:36.628  7716  7716 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.628  1043  1521 D WifiNative-p2p0:    returned OK
09-07 10:33:36.628  1043  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-07 10:33:36.638  1043  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-07 10:33:36.638  1043  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-07 10:33:36.638  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.638  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.638  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-07 10:33:36.641  1043  1521 D LGWifiP2pService: InactiveState
09-07 10:33:36.641  1043  1521 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.641  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.641  1043  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-07 10:33:36.642  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=200706  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-07 10:33:36.643  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-07 10:33:36.644  1043  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=200708  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 10:33:36.644  8038  8038 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:36.644  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=200708  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-07 10:33:36.645  8038  8038 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-07 10:33:36.645  8038  8038 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.646  8038  8038 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.647  1925  8097 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 10:33:36.647  1925  8097 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:36.647  1925  8097 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:36.647  1043  8096 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-07 10:33:36.647  1043  8096 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:36.647  1043  8096 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:36.647  1043  8096 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-07 10:33:36.648  1043  8096 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:36.648  1043  8096 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.648  1043  8096 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.648  1043  8096 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.648  1043  8096 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-07 10:33:36.648  1043  8096 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.648  1043  8096 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.648  1043  8096 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-07 10:33:36.649  1043  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-07 10:33:36.649  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:36.649  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:36.650  1043  1521 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.650  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.650  1043  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=200714
09-07 10:33:36.650  1043  1521 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.650  1043  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.650  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.650  1043  1521 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.652  1043  1521 D ,LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.652  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.652  1043  1521 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.653  1925  2279 W WfdsService: DefaultState - msg [9441285] is not handled
09-07 10:33:36.653  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.653  1043  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=200717
09-07 10:33:36.653  1043  1521 D LGWifiP2pService: InactiveState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.653  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.653  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.653  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-07 10:33:36.653  1043  1521 D LGWifiP2pService: DefaultState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.653  1043  1043 E WifiServerServiceExt: No p2p device connected
09-07 10:33:36.654  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:36.655  1043  1523 D WifiNative-wlan0: doString: [STATUS]
09-07 10:33:36.656  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-07 10:33:36.656  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-07 10:33:36.656  1043  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-07 10:33:36.659  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:36.659  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:36.661  1043  1523 I WifiServiceExtension: setVHTCapabilityType  : false
,09-07 10:33:36.662  8066  8066 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:36.663  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:36.666  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-07 10:33:36.668  8044  8116 V FormManager: Network unavailable.
,09-07 10:33:36.671  1043  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-07 10:33:36.671  1043  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-07 10:33:36.674  8044  8115 W FormManager: Network not available. Please check & try again.
09-07 10:33:36.677  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.677  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.677  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-07 10:33:36.678  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:36.678  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:36.679  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:36.685  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.685  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:36.685  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-07 10:33:36.686  8044  8116 V FormManager: Network unavailable.
09-07 10:33:36.687  1043  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-07 10:33:36.687  1043  1529 D ConnectivityService: Got NetworkAgent Messenger
09-07 10:33:36.687  1043  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:33:36.687  1043  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 10:33:36.687  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 10:33:36.687  1043  1529 D ConnectivityService: NetworkAgent connected
09-07 10:33:36.687  1043  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 10:33:36.687  1043  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-07 10:33:36.688  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:36.692  1043  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 10:33:36.693  1043  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 10:33:36.693  1043  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-07 10:33:36.693  1043  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-07 10:33:36.693  1043  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-07 10:33:36.699  1043  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-07 10:33:36.700   315   903 D CommandListener: Setting iface cfg
09-07 10:33:36.701  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:36.701  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:36.702  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:36.703  1043  1523 E WifiStateMachine: Start Dhcp Watchdog 3
09-07 10:33:36.703  1043  8119 D DhcpStateMachine: StoppedState
09-07 10:33:36.703  1043  8119 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.703  1043  8119 D DhcpStateMachine: WaitBeforeStartState
09-07 10:33:36.703  1043  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=200767  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.704  1043  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=200768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.704  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=200768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.705  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.705  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.705  1043  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.706  1043  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.706  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.707  1043  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-07 10:33:36.707  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 10:33:36.707  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 10:33:36.708  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
09-07 10:33:36.708  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
,09-07 10:33:36.709  1043  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-07 10:33:36.709  1043  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-07 10:33:36.709  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-07 10:33:36.709  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-07 10:33:36.709  8038  8038 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 10:33:36.709  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-07 10:33:36.709  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 10:33:36.710  1043  8096 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 10:33:36.710  1043  8096 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-07 10:33:36.711  1043  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-07 10:33:36.711  1043  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-07 10:33:36.711  1043  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-07 10:33:36.711  1043  1523 D WifiNative-wlan0: doBoolean: SCAN
09-07 10:33:36.711  8038  8038 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-07 10:33:36.712  1043  1523 D WifiNative-wlan0: SCAN: returned true
09-07 10:33:36.712  1043  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=200776  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.712  1043  8096 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-07 10:33:36.712  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-07 10:33:36.712  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-07 10:33:36.712  1043  8096 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-07 10:33:36.712  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-07 10:33:36.713  1043  8096 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-07 10:33:36.713  1043  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=200777  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.713  6836  6836 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-07 10:33:36.713  6836  6836 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-07 10:33:36.713  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=200777  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.713  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-07 10:33:36.713  1043  1523 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:36.713  6836  6836 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-07 10:33:36.713  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-07 10:33:36.713  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-07 10:33:36.713  1043  1523 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:36.714  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-07 10:33:36.714  6836  6836 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-07 10:33:36.714  6836  6836 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-07 10:33:36.714  1043  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:36.714  6836  6836 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-07 10:33:36.714  1043  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:36.714  ,1043  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:36.715  1043  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-07 10:33:36.716  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 10:33:36.716  4278  4278 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-07 10:33:36.717  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:36.717  1043  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=200781  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.718  1043  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=200782  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.718  1043  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=200782  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-07 10:33:36.719  4278  4278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-07 10:33:36.719  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:36.719  1043  1043 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-07 10:33:36.719  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13930] from screen [on:0 period:63434191] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 10:33:36.720  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:63434192] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 10:33:36.720  1043  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-07 10:33:36.725  4278  8121 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-07 10:33:36.726  4278  8122 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-07 10:33:36.726  4278  8122 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-07 10:33:36.760  1043  1943 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8123 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-07 10:33:36.876  8123  8123 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 10:33:36.876  8123  8123 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-07 10:33:36.877  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:36.879  1043  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-07 10:33:36.880  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-07 10:33:36.881  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:36.883  1043  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:36.884  1043  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:36.885  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:36.886  8123  8123 V [BNRBootReceiver]: Boot Receiver Return
09-07 10:33:36.886  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:36.887  1043  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-07 10:33:36.888  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=111,0,0
09-07 10:33:36.889  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=111,0,0
09-07 10:33:36.889  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,09-07 10:33:36.890  8123  8123 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 10:33:36.891  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-07 10:33:36.891  1043  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,09-07 10:33:36.891  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 0
09-07 10:33:36.892  1043  1523 D WifiNative-wlan0: SET ps 0: returned true
09-07 10:33:36.892  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-07 10:33:36.892  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-07 10:33:36.894  1925  8097 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
,09-07 10:33:36.894  1925  8097 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
,09-07 10:33:36.894  1043  8096 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-07 10:33:36.894  1043  8096 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 10:33:36.894  1043  8096 E WifiMonitor: WifiMonitor:p2p0 cnt=59 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-07 10:33:36.894  1043  8096 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-07 10:33:36.894  1043  8096 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
09-07 10:33:36.895  1043  8096 E WifiMonitor: WifiMonitor:p2p0 cnt=60 dispatchEvent: WPS-AP-AVAILABLE 
09-07 10:33:36.895  1043  8096 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-07 10:33:36.895  1043  1521 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.895  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.895  1043  1521 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.896  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-07 10:33:36.896  1043  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d6bdf9c target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.896  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d6bdf9c target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.896  1043  8119 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:36.896  1043  8119 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-07 10:33:36.897  1043  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-07 10:33:36.897  1043  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 10:33:36.897  1043  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 10:33:36.898   315   903 D CommandListener: Setting iface cfg
09-07 10:33:36.899   315   903 D CommandListener: Trying to bring up wlan0
09-07 10:33:36.900  1043  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-07 10:33:36.940  1043  1980 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-07 10:33:36.941  1043  1980 I ActivityManager: Killing 7181:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-07 10:33:37.005  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:37.006  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 10:33:37.006  1043  1870 W libprocessgroup: failed to open /acct/uid_10085/pid_7181/cgroup.procs: No such file or directory
,09-07 10:33:37.009  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-07 10:33:37.009  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-07 10:33:37.009  1043  1523 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 10:33:37.009  1043  1523 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 10:33:37.010  1043  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 10:33:37.010  1043  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 10:33:37.011  1043  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-07 10:33:37.011  1043  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-07 10:33:37.016  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:37.017  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:37.017  1043  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:37.018  1043  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:37.018  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:37.018  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-07 10:33:37.019  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 10:33:37.019  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-07 10:33:37.019  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-07 10:33:37.020  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-07 10:33:37.021  1043  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-07 10:33:37.021  1043  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:37.021  1043  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:37.022  1043  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-07 10:33:37.022  1043  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-07 10:33:37.022  8038  8038 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-07 10:33:37.023  1043  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-07 10:33:37.023  1043  1523 D WifiNative-wlan0: doBoolean: SET ps 1
09-07 10:33:37.035  8141  8141 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 10:33:37.040  1043  1523 D WifiNative-wlan0: SET ps 1: returned true
09-07 10:33:37.041  1043  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-07 10:33:37.041  1043  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 10:33:37.042  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-07 10:33:37.042  1043  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 10:33:37.043  1043  1529 D ConnectivityService: ignoring duplicate network state non-change
09-07 10:33:37.046  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:37.046  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:37.048  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:37.049  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.050  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.050  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 10:33:37.054  1043  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 10:33:37.055  1043  1529 D ConnectivityService: Adding iface wlan0 to network 102
09-07 10:33:37.063  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.063  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.063  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-07 10:33:37.065  1043  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 10:33:37.067  8141  8141 D PluginManager: init()
,09-07 10:33:37.075  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:37.075  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-07 10:33:37.076  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-07 10:33:37.081  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-07 10:33:37.083  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.083  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.084  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 10:33:37.084  1043  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 10:33:37.084  1043  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-07 10:33:37.085  1043  1523 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 10:33:37.085  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-07 10:33:37.086  1043  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-07 10:33:37.086  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-07 10:33:37.087   315   903 E Netd    : netlink response contains error (File exists)
09-07 10:33:37.087  1043  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-07 10:33:37.088  1043  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-07 10:33:37.088  1043  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-07 10:33:37.088  1043  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-07 10:33:37.091  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:37.093  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.093  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 10:33:37.093  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-07 10:33:37.093  1043  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,09-07 10:33:37.093  1043  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 10:33:37.093  1043  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 10:33:37.093  1043  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-07 10:33:37.093  1043  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:37.093  1043  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-07 10:33:37.093  1043  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:33:37.093  1043  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:37.093  1043  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:37.094  1043  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-07 10:33:37.094  1043  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 10:33:37.094  1043  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.094  1043  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-07 10:33:37.094  1043  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-07 10:33:37.094  1043  1529 D ConnectivityService:    accepting network in place of null
09-07 10:33:37.094  1043  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.095  1834  1834 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.096  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-07 10:33:37.098  1043  8119 D DhcpStateMachine: DHCPV4 request on wlan0
09-07 10:33:37.099  1043  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.099  1043  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:37.099  1043  8119 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-07 10:33:37.099  1043  8119 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-07 10:33:37.100   315  8164 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-07 10:33:37.102  1043  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 10:33:37.102  1043  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 10:33:37.103  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 10:33:37.105  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:37.105  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 10:33:37.106  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:37.109  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:37.109  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-07 10:33:37.109  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:37.093  8165  8165 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:37.093  8165  8165 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 10:33:37.111  8165  8165 I dhcpcd  : version 5.5.6 starting
09-07 10:33:37.113  8165  8165 E dhcpcd  : get_duid: m
09-07 10:33:37.113  8165  8165 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-07 10:33:37.113  8165  8165 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-07 10:33:37.152  1043  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:37.152  1043  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-07 10:33:37.152  1043  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,09-07 10:33:37.153   315  8164 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-07 10:33:37.154  1043  1529 D ConnectivityService: validation of new default Network = false
09-07 10:33:37.154  1043  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-07 10:33:37.154  1043  1529 D DSQN    : enableDataServiceNotify 
09-07 10:33:37.154  1043  1529 D DSQN    : start dsqn bin
09-07 10:33:37.158  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-07 10:33:37.158  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-07 10:33:37.158  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-07 10:33:37.158  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-07 10:33:37.163  1043  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-07 10:33:37.163  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.163  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:37.164  1043  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:37.153  8177  8177 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-07 10:33:37.153  8177  8177 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-07 10:33:37.173  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 10:33:37.178  1043  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-07 10:33:37.184  8165  8165 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 10:33:37.184  8165  8165 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 10:33:37.184  8165  8165 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 10:33:37.184  8165  8165 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-07 10:33:37.184  8177  8177 E DSQN    : DSQN ssw
09-07 10:33:37.184  8165  8165 D dhcpcd  : wlan0: sending REQUEST (xid 0xcd9c7018), next in 3.04 seconds
,09-07 10:33:37.187   315  8164 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-07 10:33:37.195  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:37.196  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:37.197  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:37.212  8165  8165 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-07 10:33:37.214   315   902 D LGDataListener: argv[0]=dsqncommand
09-07 10:33:37.214   315   902 D LGDataListener: argv[1]=wlan0
09-07 10:33:37.214   315   902 D LGDataListener: argv[2]=1
09-07 10:33:37.214   315   902 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-07 10:33:37.215  1043  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-07 10:33:37.215  1043  1117 D DSQN    : start to monitor internet connection
09-07 10:33:37.230  8165  8165 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-07 10:33:37.230  8165  8165 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-07 10:33:37.231  8165  8165 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-07 10:33:37.231  8165  8165 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-07 10:33:37.231  8165  8165 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-07 10:33:37.231  8165  8165 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-07 10:33:37.231  8165  8165 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-07 10:33:37.231  8165  8165 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-07 10:33:37.238  1043  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 08:33:37 GMT], X-Android-Received-Millis=[1473237217238], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473237217214]}
09-07 10:33:37.238  1043  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-07 10:33:37.238  1043  8117 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-07 10:33:37.238  1043  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-07 10:33:37.238  1043  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-07 10:33:37.238  1043  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:33:37.239  1043  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:37.239  1043  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-07 10:33:37.239  1043  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-07 10:33:37.239  1043  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-07 10:33:37.239  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.239  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:37.239  1043  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:37.240  1043  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.240  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 10:33:37.240  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 10:33:37.240  1834  1834 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.240  1043  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:37.240  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-07 10:33:37.240  1043  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-07 10:33:37.262  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-07 10:33:37.263  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:37.264  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:37.438  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:33:37.441  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:37.445  6729  6807 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 10:33:37.446  6729  6807 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 10:33:37.447  6729  6807 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f25a2ad Bundle[{}]
09-07 10:33:37.447  6729  6807 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 10:33:37.447  6729  6807 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 10:33:37.448  6729  6807 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 10:33:37.448  6729  6807 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 10:33:37.449  6729  6807 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 10:33:37.449  6729  6807 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 10:33:37.454  6729  6807 I System.out: Running OutgoingSocketThread
09-07 10:33:37.458  6729  8200 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 871)
09-07 10:33:37.462  6729  8200 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43068
09-07 10:33:37.462  6729  8200 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-07 10:33:37.503  1043  8119 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-07 10:33:37.505  1043  8119 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-07 10:33:37.506  1043  8119 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-07 10:33:37.506  1043  8119 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-07 10:33:37.506  1043  8119 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-07 10:33:37.506  1043  8119 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-07 10:33:37.506  1043  8119 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-07 10:33:37.506  1043  8119 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-07 10:33:37.507  1043  8119 D DhcpStateMachine: RunningState
09-07 10:33:37.571  8141  8141 W ExternalStrings: load override strings
09-07 10:33:37.571  8141  8141 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 10:33:37.571  8141  8141 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 10:33:37.575  8141  8141 D StatusProvider: onCreate
,09-07 10:33:37.652  8141  8141 V Signer  : override build config not found
,09-07 10:33:37.652  8141  8141 D Signer  : value of property debug is false
09-07 10:33:37.695  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-07 10:33:37.695  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-07 10:33:37.695  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-07 10:33:37.696  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-07 10:33:37.696  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-07 10:33:37.696  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-07 10:33:37.696  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,09-07 10:33:37.697  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-07 10:33:37.697  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-07 10:33:37.697  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-07 10:33:37.698  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-07 10:33:37.698  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-07 10:33:37.698  8141  8141 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-07 10:33:37.713  8141  8141 V LGMDMManager: Create singleton instance
09-07 10:33:37.805  8141  8141 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-07 10:33:37.861  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:37.869  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:37.880  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:37.887  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:37.925  1043  1943 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8216 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-07 10:33:37.928  1043  1943 I ActivityManager: Killing 7218:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-07 10:33:38.008  8141  8212 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-07 10:33:38.142  1043  1059 W libprocessgroup: failed to open /acct/uid_10093/pid_7218/cgroup.procs: No such file or directory
,09-07 10:33:38.166  1043  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-07 10:33:38.172  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 10:33:38.174  1043  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 10:33:38.175  1043  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 10:33:38.176  1043  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 10:33:38.178  1043  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-07 10:33:38.179  1043  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-07 10:33:38.179  1043  1529 D ConnectivityService: identical MTU - not setting
09-07 10:33:38.179  1043  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-07 10:33:38.179  1043  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 10:33:38.179  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:33:38.180  1043  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-07 10:33:38.180  1043  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-07 10:33:38.181  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-07 10:33:38.202  8216  8216 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-07 10:33:38.229  8216  8216 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-07 10:33:38.263  8216  8216 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-07 10:33:38.264  8216  8216 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-07 10:33:38.264  8216  8216 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-07 10:33:38.264  8216  8216 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-07 10:33:38.265  8216  8216 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-07 10:33:38.267  8216  8216 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-07 10:33:38.272  8216  8216 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-07 10:33:38.279  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:38.284  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:38.286  8141  8212 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:38.286  8141  8212 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 10:33:38.294  8216  8216 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 10:33:38.298  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.300  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:38.303  8216  8216 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-07 10:33:38.308  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:38.312  8216  8216 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-07 10:33:38.317  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.323  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:38.324  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:38.324  8216  8216 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:38.327  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.330  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:38.334  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:38.341  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.347  1043  1362 V AlarmManager: RTC_WAKEUP set : Alarm{3153d1a0 type 0 when 1473237211447 com.google.android.gms} when 1473237211447
09-07 10:33:38.348  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:38.348  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:38.349  1043  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{c4f3159 type 2 when 202411 com.google.android.gms} when 202411
09-07 10:33:38.349  8216  8216 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:38.352  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.352  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:38.359  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:38.365  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.371  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:38.372  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:38.374  8216  8216 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:38.377  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.379  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:38.382  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:38.396  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.403  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:38.403  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-07 10:33:38.404  8216  8216 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:38.406  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-07 10:33:38.410  6836  6836 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-07 10:33:38.422  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-07 10:33:38.424  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:38.438  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:38.442  8141  8212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-07 10:33:38.446  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.454  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-07 10:33:38.456  6729  6807 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 872)
09-07 10:33:38.456  6729  6807 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 872)
09-07 10:33:38.458  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:38.461  6729  6807 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 877)
09-07 10:33:38.462  6729  6807 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 10:33:38.462  6729  6807 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
09-07 10:33:38.465  8141  8212 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-07 10:33:38.467  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.467  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e65a160 added. We now have 2 listener(s)
09-07 10:33:38.467  8216  8216 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-07 10:33:38.474  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:38.476  1043  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.478  8141  8212 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-07 10:33:38.479  8141  8212 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 10:33:38.480  8141  8212 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-07 10:33:38.481  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.481  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.481  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.482  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.482  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b12619 added. We now have 9 listener(s)
09-07 10:33:38.482  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.482  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:33:38.483  8141  8212 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-07 10:33:38.483  8141  8212 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-07 10:33:38.484  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:38.485  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:38.487  8141  8212 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-07 10:33:38.489  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:38.492  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:38.493  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.494  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:38.494  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.494  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@341c0bf added. We now have 3 listener(s)
,09-07 10:33:38.494  1043  1863 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.495  8141  8212 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-07 10:33:38.497  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.497  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.497  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.497  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.497  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e73738c added. We now have 10 listener(s)
09-07 10:33:38.497  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.498  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:38.498  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:38.498  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:38.498  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.498  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.498  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:38.498  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.498  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e65a160 removed from the list
09-07 10:33:38.498  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.498  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b12619 removed from the list
09-07 10:33:38.498  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.501  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.501  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:38.502  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.502  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:33:38.502  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.502  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.505  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.505  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.505  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.506  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b12619 not in the list
09-07 10:33:38.506  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.506  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.507  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.507  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.507  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.507  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e73738c removed from the list
09-07 10:33:38.507  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.507  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.507  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.507  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.507  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@341c0bf removed from the list
09-07 10:33:38.508  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.508  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ea50ad5 added. We now have 2 listener(s)
09-07 10:33:38.512  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:38.512  1043  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.512  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:38.513  8216  8216 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-07 10:33:38.515  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.515  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.515  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.515  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.515  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b50b2ea added. We no,w have 9 listener(s)
09-07 10:33:38.515  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.516  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:33:38.516  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.519  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:38.521  8066  8066 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-07 10:33:38.522  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:38.526  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:38.527  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.528  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:38.528  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.528  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1faa3c78 added. We now have 3 listener(s)
,09-07 10:33:38.529  1043  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.531  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.533  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.533  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.533  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.533  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.533  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.534  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b87f51 added. We now have 10 listener(s)
,09-07 10:33:38.534  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.534  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:38.534  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:33:38.534  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:33:38.534  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:38.534  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:33:38.534  8066  8066 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:38.538  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-07 10:33:38.546  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:33:38.546  1043  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.547  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.556  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:38.556  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 10:33:38.557  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:33:38.557  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:38.558  8216  8216 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-07 10:33:38.559  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:33:38.559  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:38.561  6729  6807 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 10:33:38.561  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:38.561  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:38.563  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:38.563  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:38.563  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:38.563  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.563  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.563  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:38.563  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.563  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ea50ad5 removed from the list
09-07 10:33:38.563  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.563  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b50b2ea removed from the list
09-07 10:33:38.563  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:38.563  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.566  8216  8216 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 10:33:38.567  8216  8216 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 10:33:38.569  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.570  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.571  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.571  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:33:38.571  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.571  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b50b2ea not in the list
09-07 10:33:38.571  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.571  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.571  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.572  8141  8213 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-07 10:33:38.572  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.573  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:38.573  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:38.573  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.573  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.573  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b87f51 removed from the list
09-07 10:33:38.573  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.573  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.573  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.573  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.573  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1faa3c78 removed from the list
,09-07 10:33:38.575  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.575  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f82a824 added. We now have 2 listener(s)
09-07 10:33:38.575  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.575  8066  8066 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-07 10:33:38.576  8066  8066 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-07 10:33:38.578  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.578  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.578  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.578  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.578  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29b4bf8d added. We now have 9 listener(s)
09-07 10:33:38.579  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.579  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:33:38.580  6836  6836 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-07 10:33:38.582  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:38.588  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:38.591  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.591  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:38.592  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.592  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b737953 added. We now have 3 listener(s)
09-07 10:33:38.592  1043  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.593  6836  6836 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-07 10:33:38.593  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.596  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.596  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.596  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.596  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.597  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.596  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28542290 added. We now have 10 listener(s)
09-07 10:33:38.598  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.598  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:38.599  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:38.599  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:33:38.599  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:33:38.599  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:38.599  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wif,i.WifiDirectManager: bind: Binding a new listener
09-07 10:33:38.599  8216  8216 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-07 10:33:38.600  8216  8216 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-07 10:33:38.601  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:33:38.602  1043  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.602  8216  8216 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-07 10:33:38.603  8216  8216 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-07 10:33:38.604  8216  8216 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-07 10:33:38.609  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:33:38.609  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:33:38.611  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:33:38.611  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-07 10:33:38.613  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:33:38.616  6729  6807 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 10:33:38.616  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:38.616  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:38.616  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:38.616  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.616  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.616  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:38.616  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.616  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f82a824 removed from the list
09-07 10:33:38.616  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.616  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29b4bf8d removed from the list
09-07 10:33:38.616  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:38.616  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.617  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.617  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.618  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.618  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.618  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.618  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29b4bf8d not in the list
09-07 10:33:38.618  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.618  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.619  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.619  8216  8216 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-07 10:33:38.619  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:38.619  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:38.619  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.619  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.619  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28542290 removed from the list
09-07 10:33:38.619  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.619  6729  6807 W org.,thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.620  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.620  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.620  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b737953 removed from the list
09-07 10:33:38.621  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.622  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@143257af added. We now have 2 listener(s)
09-07 10:33:38.622  1043  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.623  8216  8216 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-07 10:33:38.623  8216  8216 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-07 10:33:38.625  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.625  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.625  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.625  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.626  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3080d7bc added. We now have 9 listener(s)
09-07 10:33:38.626  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.626  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:33:38.629  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:38.638  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:33:38.639  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.640  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:38.640  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.640  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3773aa9a added. We now have 3 listener(s)
09-07 10:33:38.640  1043  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.643  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.643  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.643  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.643  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.643  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2756bfcb added. We now have 10 listener(s)
09-07 10:33:38.643  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.643  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:38.643  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:33:38.643  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.643  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:33:38.643  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:38.643  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:33:38.645  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.647  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:33:38.647  1043  1861 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.651  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:33:38.652  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:33:38.653  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 10:33:38.654  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:38.655  6729  6807 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 10:33:38.657  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:38.657  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:38.657  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:38.658  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.658  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.658  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:38.658  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.658  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@143257af removed from the list
09-07 10:33:38.658  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.658  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3080d7bc removed from the list
09-07 10:33:38.658  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:38.658  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.659  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.659  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.660  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.660  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.660  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.660  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3080d7bc not in the list
09-07 10:33:38.660  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.660  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.661  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.661  6729  6807 D BluetoothLeScanner: could not find callback wrapper
09-07 10:33:38.661  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:33:38.661  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.661  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.662  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2756bfcb removed from the list
09-07 10:33:38.662  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.662  6729  6807 W org.thaliproject.p2p.bt,connectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.662  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.662  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.662  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3773aa9a removed from the list
09-07 10:33:38.663  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.664  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251d666 added. We now have 2 listener(s)
,09-07 10:33:38.666  1043  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.668  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.668  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.668  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.668  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.668  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350f8da7 added. We now have 9 listener(s)
09-07 10:33:38.668  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.669  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:33:38.671  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:33:38.674  6729  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:33:38.675  8216  8216 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:38.675  8216  8216 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 10:33:38.676  6729  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:33:38.676  6729  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:33:38.676  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:33:38.676  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2421a5fd added. We now have 3 listener(s)
09-07 10:33:38.676  1043  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 10:33:38.678  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:33:38.681  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:33:38.681  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-07 10:33:38.681  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:33:38.681  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:33:38.681  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:33:38.681  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194f2f2 added. We now have 10 listener(s)
09-07 10:33:38.681  6729  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:33:38.682  6729  6807 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:33:38.682  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:38.682  6729  6807 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:33:38.682  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.682  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.682  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:33:38.682  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.682  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251d666 removed from the list
09-07 10:33:38.682  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.683  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350f8da7 removed from the list
09-07 10:33:38.683  6729  6807 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:33:38.683  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.683  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.683  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.684  8216  8216 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-07 10:33:38.685  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.685  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.685  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.685  6729  6807 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350f8da7 not in the list
09-07 10:33:38.685  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given l,istener does not exist in the list - probably already removed
09-07 10:33:38.685  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.686  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:33:38.686  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:33:38.686  6729  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:33:38.686  6729  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@194f2f2 removed from the list
09-07 10:33:38.686  6729  6807 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:33:38.686  6729  6807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:33:38.686  6729  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:33:38.686  6729  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:33:38.686  6729  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2421a5fd removed from the list
09-07 10:33:38.686  8216  8216 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-07 10:33:38.686  8216  8216 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-07 10:33:38.686  8216  8216 V SoundPool: doLoad: loading sample sampleID=1
09-07 10:33:38.687  8216  8263 V SoundPool: Start decode
09-07 10:33:38.687  8216  8263 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-07 10:33:38.687  8216  8216 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-07 10:33:38.687  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 10:33:38.687  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 10:33:38.687  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 10:33:38.688   320   320 V MediaPlayerService: decode(23, 10857164, 17813)
09-07 10:33:38.688   320   320 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,09-07 10:33:38.688   320   320 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-07 10:33:38.688   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-07 10:33:38.688   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-07 10:33:38.688   320   320 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-07 10:33:38.688   320   320 V MediaPlayerService: player type = 3
09-07 10:33:38.688  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:33:38.688   320   320 V AwesomePlayer: AwesomePlayer create()
,09-07 10:33:38.688  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 10:33:38.688  6729  6807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 10:33:38.688   320   320 V AwesomePlayer: reset_l() 
09-07 10:33:38.688   320   320 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:38.688   320   320 V AwesomePlayer: setAudioSink() 
09-07 10:33:38.688   320   320 V AwesomePlayer: reset_l() 
09-07 10:33:38.688   320   320 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
,09-07 10:33:38.688   320   320 V AudioCache: ignored
09-07 10:33:38.688   320   320 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:38.688   320   320 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-07 10:33:38.688   320   320 V AwesomePlayer: setDataSource_l dataSource
09-07 10:33:38.689   320   320 V LGParserOSAL: SniffLGParser start
09-07 10:33:38.689   320   320 V LGParserOSAL: MainType:5, SubType=0
09-07 10:33:38.689   320   320 V LGParserOSAL: #### check Mime : application/ogg
,09-07 10:33:38.689   320   320 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-07 10:33:38.689   320   320 E MediaExtractor: Use LGExtractor :application/ogg 
09-07 10:33:38.691  7678  7678 D UEI.SmartControl: QS Service created
,09-07 10:33:38.701  8216  8216 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-07 10:33:38.702  6729  8264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: My test thread name)
09-07 10:33:38.702  6729  8264 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: My test thread name)
09-07 10:33:38.702  6729  8264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 10:33:38.702  8216  8216 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-07 10:33:38.703  8216  8216 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-07 10:33:38.712  6729  8265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
09-07 10:33:38.712  6729  8265 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: My test thread name)
09-07 10:33:38.712  6729  8265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-07 10:33:38.715  6729  6807 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 10:33:38.715  6729  6807 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 10:33:38.715  6729  6807 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 10:33:38.715  6729  6807 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 10:33:38.715  6729  6807 D com.test.thalitest.ThaliTestRunner: Total duration: 24113 ms
09-07 10:33:38.716  8216  8216 V LGMDMManager: Create singleton instance
09-07 10:33:38.717  6729  6807 I jxcore-log: *Native tests were executed*
09-07 10:33:38.717  6729  6807 I jxcore-log: 
09-07 10:33:38.717  6729  6807 I jxcore-log: Total number of executed tests:  80
09-07 10:33:38.717  6729  6807 I jxcore-log: 
09-07 10:33:38.717  6729  6807 I jxcore-log: Number of passed tests:  80
09-07 10:33:38.717  6729  6807 I jxcore-log: 
09-07 10:33:38.718  6729  6807 I jxcore-log: Number of failed tests:  0
09-07 10:33:38.718  6729  6807 I jxcore-log: 
09-07 10:33:38.718  6729  6807 I jxcore-log: Number of ignored tests:  0
09-07 10:33:38.718  6729  6807 I jxcore-log: 
09-07 10:33:38.718  7678  7678 I UEI.SmartControl: Service initServices...
09-07 10:33:38.718  7678  7678 D UEI.SmartControl: QS start get config
09-07 10:33:38.718  6729  6807 I jxcore-log: Total duration:  24113
09-07 10:33:38.718  6729  6807 I jxcore-log: 
09-07 10:33:38.719  6729  6807 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 10:33:38.719  6729  6807 I jxcore-log: 
,09-07 10:33:38.727  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.727  6729  6807 I jxcore-log: 
09-07 10:33:38.731  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.731  6729  6807 I jxcore-log: 
09-07 10:33:38.732  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.732  6729  6807 I jxcore-log: 
09-07 10:33:38.733  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.733  6729  6807 I jxcore-log: 
09-07 10:33:38.735  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.735  6729  6807 I jxcore-log: 
09-07 10:33:38.735  6729  6729 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 10:33:38.736   320   320 V LGParserOSAL: supported mime: application/ogg
09-07 10:33:38.736   320   320 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-07 10:33:38.736   320   320 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-07 10:33:38.736   320   320 V AwesomePlayer: mBitrate = -1 bits/sec
09-07 10:33:38.736   320   320 V AwesomePlayer: AudioTrack Setting
09-07 10:33:38.736   320   320 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-07 10:33:38.736   320   320 V AwesomePlayer: setAudioSource() 
09-07 10:33:38.736   320   320 V MediaPlayerService: prepare
09-07 10:33:38.736   320   320 V AwesomePlayer: prepareAsync_l() 
09-07 10:33:38.736   320   320 V MediaPlayerService: wait for prepare
,09-07 10:33:38.736   320  8266 V AwesomePlayer: onPrepareAsyncEvent() 
09-07 10:33:38.736   320  8266 V AwesomePlayer: initAudioDecoder() 
09-07 10:33:38.736   320  8266 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 10:33:38.737   320  8266 V AudioSystem: isOffloadSupported()
09-07 10:33:38.737   320  8266 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 10:33:38.737   320  8266 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 10:33:38.737   320  8266 I AudioFlinger: isAudioPlaybackHookOn() false
09-07 10:33:38.737   320  8266 V AwesomePlayer: getUseOffload() = 0 
09-07 10:33:38.737   320  8266 V OMXCodec: OMXCodec::Create
09-07 10:33:38.737   320  8266 V OMXCodec: findMatchingCodecs()
09-07 10:33:38.737  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:33:38.737  6729  6807 I jxcore-log: 
09-07 10:33:38.737   320  8266 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-07 10:33:38.737   320  8266 V OMXCodec: matchingCodecs.size()=1
09-07 10:33:38.737   320  8266 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-07 10:33:38.739   320  8266 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-07 10:33:38.739   320  8266 V LGCodecAdapter: LG Codec Adapter start
09-07 10:33:38.739   320  8266 V OMXCodec: OMXCodec Createtor
09-07 10:33:38.739   320  8266 V OMXCodec: setComponentRole
09-07 10:33:38.739   320  8266 V OMXCodec: configureCodec protected=0
09-07 10:33:38.739   320  8266 V LGCodecAdapter: called getLGCodecSpecificData
09-07 10:33:38.739   320  8266 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-07 10:33:38.739   320  8266 V LGCodecOSAL: Called LGconfigureCodecMETA
09-07 10:33:38.739   320  8266 V LGCodecOSAL: Called LGconfigureCodecMSG
09-07 10:33:38.739   320  8266 V LGCodecOSAL: Not support LGCodec
09-07 10:33:38.739   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 10:33:38.739   320  8266 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-07 10:33:38.739   320  8266 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-07 10:33:38.739   320  8266 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-07 10:33:38.739   320  8266 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-07 10:33:38.739   320  8266 V AudioSystem: isOffloadSupported()
09-07 10:33:38.739   320  8266 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-07 10:33:38.739   320  8266 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-07 10:33:38.739   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-07 10:33:38.739   320  8266 V OMXCodec: init()
09-07 10:33:38.739   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-07 10:33:38.739   320  8266 V OMXCodec: allocateBuffers
09-07 10:33:38.739   320  8266 V OMXCodec: allocateBuffersOnPort portIndex=0
09-07 10:33:38.739   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-07 10:33:38.740   320,  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-07 10:33:38.740   320  8266 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-07 10:33:38.740   320  8266 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
09-07 10:33:38.740   320  8266 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 10:33:38.740  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:33:38.740  6729  6807 I jxcore-log: 
09-07 10:33:38.741   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 10:33:38.741   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 10:33:38.741   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-07 10:33:38.741   320  8266 V OMXCodec: init() mAsyncCompletion wait!!! 
09-07 10:33:38.741   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-07 10:33:38.741   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-07 10:33:38.741   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-07 10:33:38.741   320  8266 V OMXCodec: init() mAsyncCompletion wait free! 
09-07 10:33:38.741   320  8266 V AwesomePlayer: finishAsyncPrepare_l() 
09-07 10:33:38.741   320  8266 V AudioCache: notify(0xb16a67c0, 5, 0, 0)
09-07 10:33:38.741   320  8266 V AudioCache: ignored
09-07 10:33:38.741   320  8266 V AudioCache: notify(0xb16a67c0, 1, 0, 0)
09-07 10:33:38.741   320  8266 V AudioCache: prepared
09-07 10:33:38.742   320   320 V AudioCache: wait - success
09-07 10:33:38.742   320   320 V MediaPlayerService: start
09-07 10:33:38.742   320   320 V AwesomePlayer: play_l() 
09-07 10:33:38.742   320   320 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-07 10:33:38.742   320   320 V AwesomePlayer: createAudioPlayer_l
09-07 10:33:38.742   320   320 V AwesomePlayer: seekAudioIfNecessary_l() 
09-07 10:33:38.742   320   320 V AwesomePlayer: startAudioPlayer_l() 
09-07 10:33:38.742   320   320 D AudioPlayer: start of Playback, useOffload 0
09-07 10:33:38.742   320   320 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 10:33:38.742   320   320 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-07 10:33:38.744   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-07 10:33:38.745   320  8268 V OMXCodec: allocateBuffersOnPort portIndex=1
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-07 10:33:38.745  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.745  6729  6807 I jxcore-log: 
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-07 10:33:38.745   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-07 10:33:38.746   320   320 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-07 10:33:38.746   320   320 V AudioCache: notify(0xb16a67c0, 6, 0, 0)
09-07 10:33:38.746   320   320 V AudioCache: ignored
09-07 10:33:38.747   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.747   320  8269 V AudioCache: memcpy(0xaf006000, 0xb16de000, 4096)
09-07 10:33:38.748   320   320 V MediaPlayerService: wait for playback complete
09-07 10:33:38.748   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.748   320  8269 V AudioCache: memcpy(0xaf007000, 0xb16de000, 4096)
09-07 10:33:38.748   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.748   320  8269 V AudioCache: memcpy(0xaf008000, 0xb16de000, 4096)
,09-07 10:33:38.750   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.750   320  8269 V AudioCache: memcpy(0xaf009000, 0xb16de000, 4096)
09-07 10:33:38.750   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.750   320  8269 V AudioCache: memcpy(0xaf00a000, 0xb16de000, 4096)
09-07 10:33:38.750   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.750   320  8269 V AudioCache: memcpy(0xaf00b000, 0xb16de000, 4096)
09-07 10:33:38.750   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.750   320  8269 V AudioCache: memcpy(0xaf00c000, 0xb16de000, 4096)
09-07 10:33:38.751  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.751  6729  6807 I jxcore-log: 
09-07 10:33:38.752  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.752  6729  6807 I jxcore-log: 
09-07 10:33:38.753   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.753   320  8269 V AudioCache: memcpy(0xaf00d000, 0xb16de000, 4096)
09-07 10:33:38.753   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.753   320  8269 V AudioCache: memcpy(0xaf00e000, 0xb16de000, 4096)
09-07 10:33:38.753   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.753   320  8269 V AudioCache: memcpy(0xaf00f000, 0xb16de000, 4096)
09-07 10:33:38.753  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:33:38.753  6729  6807 I jxcore-log: 
09-07 10:33:38.753   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.753   320  8269 V AudioCache: memcpy(0xaf010000, 0xb16de000, 4096)
09-07 10:33:38.754   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.754   320  8269 V AudioCache: memcpy(0xaf011000, 0xb16de000, 4096)
09-07 10:33:38.754  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:33:38.754  6729  6807 I jxcore-log: 
09-07 10:33:38.755   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.755   320  8269 V AudioCache: memcpy(0xaf012000, 0xb16de000, 4096)
09-07 10:33:38.755  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:33:38.755  6729  6807 I jxcore-log: 
09-07 10:33:38.756   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.756   320  8269 V AudioCache: memcpy(0xaf013000, 0xb16de000, 4096)
09-07 10:33:38.756  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.756  6729  6807 I jxcore-log: 
09-07 10:33:38.756   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.756   320  8269 V AudioCache: memcpy(0xaf014000, 0xb16de000, 4096)
09-07 10:33:38.757   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.757   320  8269 V AudioCache: memcpy(0xaf015000, 0xb16de000, 4096)
09-07 10:33:38.757  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.757  6729  6807 I jxcore-log: 
09-07 10:33:38.758   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.758   320  8269 V AudioCache: memcpy(0xaf016000, 0xb16de000, 4096)
09-07 10:33:38.758  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.758  6729  6807 I jxcore-log: 
09-07 10:33:38.758   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.758   320  8269 V AudioCache: memcpy(0xaf017000, 0xb16de000,, 4096)
09-07 10:33:38.759  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.759  6729  6807 I jxcore-log: 
09-07 10:33:38.759   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.759   320  8269 V AudioCache: memcpy(0xaf018000, 0xb16de000, 4096)
09-07 10:33:38.759  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.759  6729  6807 I jxcore-log: 
09-07 10:33:38.760   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.760   320  8269 V AudioCache: memcpy(0xaf019000, 0xb16de000, 4096)
09-07 10:33:38.760  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.760  6729  6807 I jxcore-log: 
09-07 10:33:38.760   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.760   320  8269 V AudioCache: memcpy(0xaf01a000, 0xb16de000, 4096)
09-07 10:33:38.761   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.761   320  8269 V AudioCache: memcpy(0xaf01b000, 0xb16de000, 4096)
09-07 10:33:38.761  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.761  6729  6807 I jxcore-log: 
09-07 10:33:38.762   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.762   320  8269 V AudioCache: memcpy(0xaf01c000, 0xb16de000, 4096)
09-07 10:33:38.762  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:33:38.762  6729  6807 I jxcore-log: 
09-07 10:33:38.762   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.762   320  8269 V AudioCache: memcpy(0xaf01d000, 0xb16de000, 4096)
09-07 10:33:38.763  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:33:38.763  6729  6807 I jxcore-log: 
09-07 10:33:38.763   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.763   320  8269 V AudioCache: memcpy(0xaf01e000, 0xb16de000, 4096)
09-07 10:33:38.764   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.764  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.764  6729  6807 I jxcore-log: 
09-07 10:33:38.764   320  8269 V AudioCache: memcpy(0xaf01f000, 0xb16de000, 4096)
09-07 10:33:38.764   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.764   320  8269 V AudioCache: memcpy(0xaf020000, 0xb16de000, 4096)
09-07 10:33:38.764  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.764  6729  6807 I jxcore-log: 
09-07 10:33:38.765   320  8269 V AudioCache: write(0xb16de000, 4096)
,09-07 10:33:38.765   320  8269 V AudioCache: memcpy(0xaf021000, 0xb16de000, 4096)
09-07 10:33:38.765  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.765  6729  6807 I jxcore-log: 
09-07 10:33:38.765   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.765   320  8269 V AudioCache: memcpy(0xaf022000, 0xb16de000, 4096)
09-07 10:33:38.766  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.766  6729  6807 I jxcore-log: 
09-07 10:33:38.766   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.766   320  8269 V AudioCache: memcpy(0xaf023000, 0xb16de000, 4096)
09-07 10:33:38.766  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.766  6729  6807 I jxcore-log: 
09-07 10:33:38.767   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.767   320  8269 V AudioCache: memcpy(0xaf024000, 0xb16de000, 4096)
09-07 10:33:38.767   320  8269 V AudioCache: write(0xb16de000, 4096)
,09-07 10:33:38.767   320  8269 V AudioCache: memcpy(0xaf025000, 0xb16de000, 4096)
09-07 10:33:38.767  6729  6807 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:33:38.767  6729  6807 I jxcore-log: 
09-07 10:33:38.768   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.768   320  8269 V AudioCache: memcpy(0xaf026000, 0xb16de000, 4096)
09-07 10:33:38.768   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.768   320  8269 V AudioCache: memcpy(0xaf027000, 0xb16de000, 4096)
09-07 10:33:38.769   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.769   320  8269 V AudioCache: memcpy(0xaf028000, 0xb16de000, 4096)
09-07 10:33:38.770   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.770   320  8269 V AudioCache: memcpy(0xaf029000, 0xb16de000, 4096)
,09-07 10:33:38.770   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.770   320  8269 V AudioCache: memcpy(0xaf02a000, 0xb16de000, 4096)
09-07 10:33:38.771   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.771   320  8269 V AudioCache: memcpy(0xaf02b000, 0xb16de000, 4096)
09-07 10:33:38.772   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.772   320  8269 V AudioCache: memcpy(0xaf02c000, 0xb16de000, 4096)
09-07 10:33:38.772   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.772   320  8269 V AudioCache: memcpy(0xaf02d000, 0xb16de000, 4096)
09-07 10:33:38.773   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.773   320  8269 V AudioCache: memcpy(0xaf02e000, 0xb16de000, 4096)
09-07 10:33:38.773   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.773   320  8269 V AudioCache: memcpy(0xaf02f000, 0xb16de000, 4096)
09-07 10:33:38.774   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.774   320  8269 V AudioCache: memcpy(0xaf030000, 0xb16de000, 4096)
09-07 10:33:38.775   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.775   320  8269 V AudioCache: memcpy(0xaf031000, 0xb16de000, 4096)
09-07 10:33:38.775   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.775   320  8269 V AudioCache: memcpy(0xaf032000, 0xb16de000, 4096)
09-07 10:33:38.776   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.776   320  8269 V AudioCache: memcpy(0xaf033000, 0xb16de000, 4096)
09-07 10:33:38.776   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.776   320  8269 V AudioCache: memcpy(0xaf034000, 0xb16de000, 4096)
09-07 10:33:38.777   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.777   320  8269 V AudioCache: memcpy(0xaf035000, 0xb16de000, 4096)
09-07 10:33:38.777   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.777   320  8269 V AudioCache: memcpy(0xaf036000, 0xb16de000, 4096)
09-07 10:33:38.778   320  8269 V AudioCache: write(0xb16de000, 4096)
09-07 10:33:38.778   320  8269 V AudioCache: memcpy(0xaf037000, 0xb16de000, 4096)
09-07 10:33:38.778   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-07 10:33:38.778   320  8269 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-07 10:33:38.778   320  8269 V AwesomePlayer: postAudioEOS() 
09-07 10:33:38.778   320  8269 V AudioCache: write(0xb16de000, 280)
09-07 10:33:38.778   320  8269 V AudioCache: memcpy(0xaf038000, 0xb16de000, 280)
09-07 10:33:38.780   320  8266 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-07 10:33:38.780   320  8266 V AwesomePlayer: onStreamDone
09-07 10:33:38.780   320  8266 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-07 10:33:38.780   320  8266 V AudioCache: notify(0xb16a67c0, 2, 0, 0)
09-07 10:33:38.780   320  8266 V AudioCache: playback complete
09-07 10:33:38.780   320  8266 V AwesomePlayer: pause_l() 
09-07 10:33:38.780   320  8266 V AudioCache: notify(0xb16a67c0, 7, 0, 0)
09-07 10:33:38.780   320  8266 V AudioCache: ignored
09-07 10:33:38.780   320  8266 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:38.780   320  8266 D AudioPlayer: Pause Playback at 1068125
09-07 10:33:38.780   320   320 V AudioCache: wait - success
09-07 10:33:38.780   320   320 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-07 10:33:38.780   320   320 V AwesomePlayer: reset_l() 
09-07 10:33:38.780   320   320 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
09-07 10:33:38.780   320   320 V AudioCache: ignored
09-07 10:33:38.780   320   320 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:38.780   320   320 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-07 10:33:38.780   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-07 10:33:38.780   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-07 10:33:38.780   320   320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newSt,ate=5
09-07 10:33:38.780   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 10:33:38.790   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-07 10:33:38.790   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-07 10:33:38.790   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-07 10:33:38.790   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-07 10:33:38.790   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-07 10:33:38.791   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 10:33:38.791   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-07 10:33:38.791   320  8268 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-07 10:33:38.791   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-07 10:33:38.791   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-07 10:33:38.791   320   320 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-07 10:33:38.792   320   320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-07 10:33:38.792   320   320 D AudioPlayer: AudioPlayer releasing audio source
09-07 10:33:38.792   320   320 D AudioPlayer: AudioPlayer done releasing audio source
09-07 10:33:38.792   320   320 V AwesomePlayer: reset_l() 
09-07 10:33:38.792   320   320 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:38.793   320   320 V AwesomePlayer: ~AwesomePlayer call
09-07 10:33:38.793   320   320 V AwesomePlayer: reset_l() 
09-07 10:33:38.793   320   320 V AwesomePlayer: cancelPlayerEvents
09-07 10:33:38.793  8216  8263 V SoundPool: close(31)
09-07 10:33:38.793  8216  8263 V SoundPool: pointer = 0x9fe55000, size = 205080, sampleRate = 48000, numChannels = 2
09-07 10:33:38.815  8216  8216 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-07 10:33:38.816  8216  8216 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-07 10:33:38.817  8216  8216 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4953
09-07 10:33:38.820  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:38.843  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:38.857  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:38.860   315  8275 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-07 10:33:38.861   315  8275 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-07 10:33:38.863  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.866  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.869  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-07 10:33:38.875  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.878  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-07 10:33:38.882  1799  8274 I CheckinService: active receiver: enabled
,09-07 10:33:38.903   315  8275 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-07 10:33:38.904  1799  8274 I CheckinService: Preparing to send checkin request
09-07 10:33:38.904  1799  8274 I EventLogService: Accumulating logs since 1473237200046
09-07 10:33:38.935  1799  8274 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-07 10:33:38.983  8270  8270 D AndroidRuntime: 
09-07 10:33:38.983  8270  8270 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 10:33:38.985  8270  8270 D AndroidRuntime: CheckJNI is OFF
,09-07 10:33:39.088  8270  8270 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 10:33:39.097  1043  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-07 10:33:39.098  1043  1115 I ActivityManager: Killing 6729:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-07 10:33:39.129  7678  7678 I UEI.SmartControl: Supports setup maps: true
,09-07 10:33:39.134  7678  7678 D UEI.SmartControl: QS start statue = true Error code = 0
09-07 10:33:39.134  7678  7678 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-07 10:33:39.134  7678  7678 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-07 10:33:39.134  7678  7678 I UEI.SmartControl: ### init IR Blaster...
09-07 10:33:39.138  7678  7678 D serial_port: Configuring serial port
09-07 10:33:39.138  7678  7678 E UEI.SmartControl: UEIBLaster setting for 616
09-07 10:33:39.138  7678  7678 I UEI.SmartControl: Setting serial record hearder size = 2
09-07 10:33:39.138  7678  7678 I UEI.SmartControl: configuring settings for MAXQ616
09-07 10:33:39.138  7678  7678 I UEI.SmartControl: Get version...
09-07 10:33:39.153  1043  1631 I WindowState: WIN DEATH: Window{150b34e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 10:33:39.153  1043  1528 D WifiService: Client connection lost with reason: 4
09-07 10:33:39.157  7678  8291 D UEI.SmartControl: serial port data available: 21
09-07 10:33:39.160  1043  1631 D InputDispatcher: Window went away: Window{150b34e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 10:33:39.183  7678  7678 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-07 10:33:39.183  7678  7678 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-07 10:33:39.183  7678  7678 I UEI.SmartControl: QS saving settings...
09-07 10:33:39.184  7678  7678 D UEI.SmartControl: IR Blaster version: 25672567
,09-07 10:33:39.193  2066  8288 D GCM     : Connected
,09-07 10:33:39.201  7678  8291 D UEI.SmartControl: serial port data available: 4
09-07 10:33:39.202  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:39.202  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:39.202  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:39.202  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:39.202  7252  7270 I Adreno-EGL: Remote Branch: 
09-07 10:33:39.202  7252  7270 I Adreno-EGL: Local Patches: 
09-07 10:33:39.202  7252  7270 I Adreno-EGL: Reconstruct Branch: 
09-07 10:33:39.229  7678  8294 I UEI.SmartControl: Device manager: loading config....
,09-07 10:33:39.231  7678  7678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-07 10:33:39.232  7678  8294 D UEI.SmartControl: ----------- loading internal config...
09-07 10:33:39.235  7678  8294 E UEI.SmartControl: Loading SETTINGS...
09-07 10:33:39.239  7678  8294 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-07 10:33:39.248  7678  8293 I UEI.SmartControl: Notify AllClients services are ready: 0
09-07 10:33:39.248  7678  8293 D UEI.SmartControl: -----service ready thread exits
,09-07 10:33:39.257  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:39.257  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:39.257  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:39.257  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:39.257  7252  7270 I Adreno-EGL: Remote Branch: 
09-07 10:33:39.257  7252  7270 I Adreno-EGL: Local Patches: 
09-07 10:33:39.257  7252  7270 I Adreno-EGL: Reconstruct Branch: 
,09-07 10:33:39.310  7252  7270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 10:33:39.310  7252  7270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 10:33:39.310  7252  7270 I Adreno-EGL: Build Date: 12/12/14 금
09-07 10:33:39.310  7252  7270 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-07 10:33:39.310  7252  7270 I Adreno-EGL: Remote Branch: 
09-07 10:33:39.310  7252  7270 I Adreno-EGL: Local Patches: 
09-07 10:33:39.310  7252  7270 I Adreno-EGL: Reconstruct Branch: 
09-07 10:33:39.344  1043  1115 I ActivityManager:   Force finishing activity ActivityRecord{36a5c4ac u0 com.test.thalitest/.MainActivity t6}
,09-07 10:33:39.373   343   358 E GBMv2   : DFP En is all cleared set to be enabled
09-07 10:33:39.374  1043  1961 W ActivityManager: Spurious death for ProcessRecord{1ab81756 6729:com.test.thalitest/u0a118}, curProc for 6729: null
09-07 10:33:39.376  1043  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-07 10:33:39.381  1043  1125 I ActivityManager:   Force finishing activity ActivityRecord{36a5c4ac u0 com.test.thalitest/.MainActivity t6 f}
,09-07 10:33:39.381  1043  1125 W ActivityManager: Duplicate finish request for ActivityRecord{36a5c4ac u0 com.test.thalitest/.MainActivity t6 f}
,09-07 10:33:39.412  1925  2775 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-07 10:33:39.412  1925  2775 D SplitWindowPolicy: topRunningActivity=ActivityInfo{42a276f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-07 10:33:39.413  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-07 10:33:39.414  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-07 10:33:39.415  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{cd0cc7c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-07 10:33:39.417  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-07 10:33:39.418  7678  7678 E UEI.SmartControl: Services init done
09-07 10:33:39.418  7678  7678 D UEI.SmartControl: QS Service init finished
09-07 10:33:39.419  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-07 10:33:39.433  3793  3793 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-07 10:33:39.433  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,09-07 10:33:39.434  7647  7647 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-07 10:33:39.434  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-07 10:33:39.443  7678  7678 D UEI.SmartControl: QS Service version name: 2.1.91
09-07 10:33:39.443  4459  4459 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-07 10:33:39.443  7678  7678 D UEI.SmartControl: QS Service version code: 201091
09-07 10:33:39.444  7678  7678 D UEI.SmartControl: Service requested: Control
09-07 10:33:39.444  4459  4459 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-07 10:33:39.444  4459  4459 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-07 10:33:39.444  4459  4459 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-07 10:33:39.444  4459  4459 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 10:33:39.444  4459  4459 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 10:33:39.444  4459  4459 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 10:33:39.444  4459  4459 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-07 10:33:39.444  4459  4459 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:33:39.444  4459  4459 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:33:39.444  4459  4459 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-07 10:33:39.444  4459  4459 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-07 10:33:39.447  1043  1410 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 10:33:39.450  2066  8288 D GCM     : Message class com.google.e.a.a.q
09-07 10:33:39.452  8141  8141 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-07 10:33:39.453  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-07 10:33:39.453  2017  2057 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-07 10:33:39.459  4560  4560 I art     : Explicit concurrent mark sweep GC freed 8193(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 303us total 61.463ms
09-07 10:33:39.498  1043  1943 V SIM_STK : Menu title from STK is T-Mobile
09-07 10:33:39.496  1043  1114 W InputMethodInfo: Duplicated subtype definition found: , voice
09-07 10:33:39.499  1043  1043 D administrator: Handling package changes for user 0
,09-07 10:33:39.502  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-07 10:33:39.502  8216  8216 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-07 10:33:39.504  2471  2655 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 10:33:39.506  7678  7693 I UEI.SmartControl: ------ IControl API: 11
09-07 10:33:39.506  7678  7693 D UEI.SmartControl: File observer start...
09-07 10:33:39.507  7678  7693 E UEI.SmartControl: IR Port is disabled: false
09-07 10:33:39.507  7678  7693 D UEI.SmartControl: Starting file observer...
09-07 10:33:39.507  7678  7693 I UEI.SmartControl: Registering callback...
09-07 10:33:39.508  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-07 10:33:39.508  1889  1889 D ActionManagerService: notifyUserLog: 1000003
09-07 10:33:39.509  3793  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-07 10:33:39.510  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-07 10:33:39.512  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-07 10:33:39.513  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-07 10:33:39.515  1799  1799 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-07 10:33:39.531  7678  7694 I UEI.SmartControl: ------ IControl API: 19
09-07 10:33:39.532  7678  7694 I UEI.SmartControl: Registering Services Ready callback...
09-07 10:33:39.533  7678  7694 I UEI.SmartControl: Notify client services are ready...
09-07 10:33:39.533  8216  8235 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,09-07 10:33:39.534  1889  1889 D ActionManagerService: notifyUserLog: 1000004
09-07 10:33:39.535  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-07 10:33:39.535  3793  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-07 10:33:39.537  1586  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 10:33:39.537  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.541  8216  8261 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-07 10:33:39.541  8216  8261 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-07 10:33:39.556  7678  7678 D UEI.SmartControl: Internal service binding...
,09-07 10:33:39.557  3793  4155 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 10:33:39.558  8216  8216 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-07 10:33:39.558  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-07 10:33:39.558  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-07 10:33:39.558  8216  8216 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-07 10:33:39.559  7678  7693 I UEI.SmartControl: ------ IControl API: 8
09-07 10:33:39.566  1586  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 10:33:39.566  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.566  1043  2015 V SIM_STK : Menu title from STK is T-Mobile
09-07 10:33:39.566  1043  2015 V SIM_STK : Menu title from STK is T-Mobile
09-07 10:33:39.570  8216  8216 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-07 10:33:39.570  8216  8216 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,09-07 10:33:39.570  8216  8216 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-07 10:33:39.571  8216  8216 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-07 10:33:39.574  2066  2066 I ConfigService: onCreate
09-07 10:33:39.574  2066  2066 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , display: false
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , animation: false }
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , display: false
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , animation: false }
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , create_time: 1472828323917
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , display: false
09-07 10:33:39.575  2017  2017 I GBoardWebViewUtils: , animation: false }
09-07 10:33:39.576  1799  1799 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-07 10:33:39.577  8216  8216 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-07 10:33:39.577  8216  8216 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-07 10:33:39.582  1586  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 10:33:39.582  1586  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:39.583  1586  1648 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-07 10:33:39.584  1586  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 10:33:39.590  1586  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 10:33:39.590  1586  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 10:33:39.592  2017  8297 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-07 10:33:39.593  1851  1851 D SplitUIManager: split_name #11 / not available #0
09-07 10:33:39.593  1851  1851 D SplitUIService: removed split : 
09-07 10:33:39.595  1586  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 10:33:39.595  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.596  2066  2066 I ConfigService: onBind returning update interface
,09-07 10:33:39.597  2066  2066 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-07 10:33:39.597  2066  2066 I ConfigService: onBind returning config service
09-07 10:33:39.600  1586  1648 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-07 10:33:39.600  1586  1648 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 10:33:39.603  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 10:33:39.603  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-07 10:33:39.619  1043  1863 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-07 10:33:39.620  7647  7647 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-07 10:33:39.621  2066  2066 I ConfigService: onDestroy
09-07 10:33:39.627  1799  8300 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-07 10:33:39.642  1586  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 10:33:39.642  1586  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-07 10:33:39.647  1586  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 10:33:39.647  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.655  1586  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:39.655  1586  1648 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 10:33:39.656  1586  1648 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 10:33:39.656  1586  1648 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-07 10:33:39.658  1586  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 10:33:39.658  1586  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 10:33:39.659  1586  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 10:33:39.659  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.660  1851  1851 D SplitUIManager: split_name #11 / not available #0
09-07 10:33:39.660  1851  1851 I SplitUIService: split app #11
09-07 10:33:39.669  5927  8306 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-07 10:33:39.672  1043  1906 V SIM_STK : Menu title from STK is T-Mobile
09-07 10:33:39.673  8216  8216 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-07 10:33:39.675  8216  8216 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-07 10:33:39.679  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-07 10:33:39.679  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 10:33:39.679  1043  1043 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 10:33:39.679  1586  1586 D KeyguardModel: handleShortcutListChanged...
09-07 10:33:39.680  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-07 10:33:39.687  1586  1648 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 10:33:39.687  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.688  1586  1648 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 10:33:39.688  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.689  1586  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 10:33:39.689  1586  1648 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 10:33:39.690  1586  1648 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 10:33:39.690  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.691  1586  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 10:33:39.691  1586  1648 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 10:33:39.693  1586  1648 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 10:33:39.693  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.694  1586  1648 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 10:33:39.694  1586  1648 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 10:33:39.695  1586  1648 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 10:33:39.695  1586  1648 D KeyguardModel: createShortcutInfo...
09-07 10:33:39.698  1043  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-07 10:33:39.706  1799  8307 I PeopleContactsSync: CP2 sync disabled
09-07 10:33:39.708  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-07 10:33:39.710  7043  7043 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-07 10:33:39.717  1799  8305 W GmsApplication: Using Auth Proxy for data requests.
09-07 10:33:39.724   329   435 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-07 10:33:39.725  3190  8308 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-07 10:33:39.737  2066  4042 I art     : Explicit concurrent mark sweep GC freed 8721(531KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 927us total 18.071ms
,09-07 10:33:39.739  1586  1586 D KeyguardModel: handleShortcutListChanged...
09-07 10:33:39.739  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-07 10:33:39.742  1799  4732 I Icing   : doRemovePackageData com.test.thalitest
09-07 10:33:39.749  2353  8310 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-07 10:33:39.775  1043  1631 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8312 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-07 10:33:39.779  1799  8305 W GmsApplication: Using Auth Proxy for data requests.
,09-07 10:33:39.811   315  8330 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-07 10:33:39.812   315  8330 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-07 10:33:39.824  8312  8312 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:39.825  8312  8312 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 10:33:39.831  8312  8312 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-07 10:33:39.832  8312  8312 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 10:33:39.845  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-07 10:33:39.851  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 10:33:39.853  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-07 10:33:39.854  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-07 10:33:39.855  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-07 10:33:39.856   315  8330 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-07 10:33:39.857  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-07 10:33:39.878  1043  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2fe76a02 u0 com.lge.launcher2/.Launcher t5} time:203957
09-07 10:33:39.879  1043  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=55.5, 0.0, 0.0  rx=66.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:63437351] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 10:33:39.880  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-07 10:33:39.880  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 10:33:39.882  2017  2109 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-07 10:33:39.882  2017  2109 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-07 10:33:39.883  1043  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=55.5, 0.0, 0.0  rx=66.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:63437355] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-07 10:33:39.883  1043  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-07 10:33:39.886  1043  1125 I art     : Explicit concurrent mark sweep GC freed 87071(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 2.700ms total 470.862ms
09-07 10:33:39.886  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-07 10:33:39.898  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-07 10:33:39.899  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-07 10:33:39.899  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 10:33:39.909  8312  8312 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-07 10:33:39.911  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-07 10:33:39.912  2565  2565 D [Concierge]Service: onStartCommand(). Type : 8
09-07 10:33:39.912  2565  2565 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-07 10:33:39.913  2565  2565 D [Concierge]Service: Update widget ID : 11
09-07 10:33:39.914  2017  2017 D [Concierge]WidgetView: change position of spinner
09-07 10:33:39.915  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1473237219915
09-07 10:33:39.915  2565  2565 D [Concierge]Service: onStartCommand(). Type : 0
09-07 10:33:39.918  8312  8312 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-07 10:33:39.927  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 309112980
09-07 10:33:39.927  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-07 10:33:39.927  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-07 10:33:39.930  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3cab6f7c
09-07 10:33:39.930  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-07 10:33:39.931  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-07 10:33:39.931  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-07 10:33:39.937  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-07 10:33:39.937  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-07 10:33:39.937  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-07 10:33:39.938  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473237043367, New one : 1473237219915
09-07 10:33:39.938  2017  2017 D [Concierge]WidgetView: Unregister all receivers
09-07 10:33:39.938  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-07 10:33:39.938  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 10:33:39.941  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-07 10:33:39.942  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-07 10:33:39.943  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-07 10:33:39.944  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-07 10:33:39.945  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-07 10:33:39.948  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 10:33:39.948  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 10:33:39.949  1799  8274 I CheckinTask: Sending checkin request (7893 bytes)
09-07 10:33:39.966  8312  8312 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 10:33:39.986  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-07 10:33:39.989  8312  8312 D LgDataFeature: LgDataFeature() Constructor: none
09-07 10:33:39.989  8312  8312 D LgDataFeature: LgDataFeature() Constructor Done, null
09-07 10:33:39.991  8270  8270 D AndroidRuntime: Shutting down VM
09-07 10:33:39.994  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-07 10:33:39.994  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-07 10:33:39.995  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-07 10:33:40.005  1043  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 10:33:40.009  1043  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 10:33:40.014  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a4fb933 time:204093
09-07 10:33:40.022  1043  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8336 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-07 10:33:40.023  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-07 10:33:40.062  1043  1559 I ActivityManager: Killing 7716:com.google.android.talk/u0a72 (adj 15): empty #17
09-07 10:33:40.064  8312  8312 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-07 10:33:40.070  1043  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
09-07 10:33:40.154  1043  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:33:40.173  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-07 10:33:40.181  1043  1631 W libprocessgroup: failed to open /acct/uid_10072/pid_7716/cgroup.procs: No such file or directory
09-07 10:33:40.183  1043  1631 I ActivityManager: Killing 7790:com.android.gallery3d/u0a27 (adj 15): empty #17
09-07 10:33:40.217  2017  2858 I GBoardtInterface: onReloaded()
,09-07 10:33:40.219  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-07 10:33:40.232  1043  1119 D Tethering: MasterInitialState.processMessage what=3
,09-07 10:33:40.233  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-07 10:33:40.234  5741  5741 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-07 10:33:40.235  1043  1559 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.gallery3d/com.android.gallery3d.app.PackagesMonitor}
09-07 10:33:40.235  1043  1559 W BroadcastQueue: android.os.DeadObjectException
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
09-07 10:33:40.235  1043  1559 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 10:33:40.235  1043  1559 W libprocessgroup: failed to open /acct/uid_10027/pid_7790/cgroup.procs: No such file or directory
09-07 10:33:40.235  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:33:40.267  1043  1559 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8357 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-07 10:33:40.268  1043  1708 W ActivityManager: Spurious death for ProcessRecord{3b7c0a0a 8357:com.android.gallery3d/u0a27}, curProc for 7790: null
09-07 10:33:40.269  3793  4155 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 10:33:40.273  3793  3809 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 10:33:40.285  1889  1889 D ActionManagerService: notifyUserLog: 1000001
,09-07 10:33:40.289  1889  1889 D ActionManagerService: notifyUserLog: 1000001
09-07 10:33:40.289  3793  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-07 10:33:40.289  3793  4453 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-07 10:33:40.290  3793  4453 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-07 10:33:40.290  3793  4453 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-07 10:33:40.290  3793  4453 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-07 10:33:40.290  3793  4453 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-07 10:33:40.291  3793  4155 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-07 10:33:40.293  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-07 10:33:40.293  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-07 10:33:40.295  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-07 10:33:40.295  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-07 10:33:40.297  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-07 10:33:40.297  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-07 10:33:40.303  8357  8357 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:33:40.303  8357  8357 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 10:33:40.303  8357  8357 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-07 10:33:40.303  8357  8357 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-07 10:33:40.324  1799  3941 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gsf/shared_prefs/CheckinService.xml to backup file /data/data/com.google.android.gsf/shared_prefs/CheckinService.xml.bak
09-07 10:33:40.324  1799  8274 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
09-07 10:33:40.324  1799  3941 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
,09-07 10:33:40.327  1799  3941 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
,09-07 10:33:40.342  1799  8274 I CheckinService: active receiver: disabled
09-07 10:33:40.345  1043  1979 F PackageManager: Unable to backup user packages state file, current changes will be lost at reboot
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: Can't write: system_server_wtf
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop19.tmp: open failed: EROFS (Read-only file system)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12444)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12257)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:12229)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:135)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 10:33:40.350  1043  1115 E DropBoxManagerService: 	... 13 more
09-07 10:33:40.360  8357  8357 I AppConfig: Total System Memory = 2995761152
,09-07 10:33:40.365  8357  8357 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-07 10:33:40.378  8357  8357 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
