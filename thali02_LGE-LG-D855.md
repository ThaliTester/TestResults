#### Test 8251899684424f3_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-24 17:08:26.355  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-24 17:08:26.362  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-24 17:08:54.467  6847  6847 D AndroidRuntime: 
08-24 17:08:54.467  6847  6847 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 17:08:54.475  6847  6847 D AndroidRuntime: CheckJNI is OFF
08-24 17:08:54.678  6847  6847 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 17:08:54.688  1038  1726 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 17:08:54.703  1928  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 17:08:54.709  1038  1726 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 17:08:54.710  1038  1726 D ActivityManager: setTaskToReturnTo : TaskRecord{37ebd1e5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 17:08:54.711  1038  1726 D ActivityManager: setTaskToReturnTo : TaskRecord{37ebd1e5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 17:08:54.712  1038  1726 D WindowStateEx: AppWindowTokenEx init.. 
08-24 17:08:54.713   331   347 E GBMv2   : DFP En is all cleared set to be enabled
08-24 17:08:54.741  1038  1726 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6862 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 17:08:54.743  6847  6847 D AndroidRuntime: Shutting down VM
08-24 17:08:54.810  1928  2662 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 17:08:54.812  1928  2662 D SplitWindowPolicy: topRunningActivity=ActivityInfo{173d3c81 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 17:08:54.813  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 17:08:54.813  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a484126 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,08-24 17:08:54.874  6862  6862 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-24 17:08:54.962  6862  6862 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 17:08:54.969  6862  6862 I LibraryLoader: Loading: webviewchromium
08-24 17:08:54.972  6862  6862 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1558-1562)
08-24 17:08:54.972  6862  6862 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 17:08:54.991  6862  6862 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31461ad7}
,08-24 17:08:54.992  6862  6862 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 17:08:54.992  6862  6862 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 17:08:55.002  6862  6862 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 17:08:55.002  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:08:55.021  6862  6862 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-24 17:08:55.021   316  1386 V AudioPolicyService: registerClient() client 0xb558a2a0, uid 10118
08-24 17:08:55.021  6862  6862 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-24 17:08:55.021  6862  6862 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-24 17:08:55.025  1038  1120 D BluetoothManagerService: Message: 20
08-24 17:08:55.025  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a9f1747:true
08-24 17:08:55.042  6862  6862 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 17:08:55.042  6862  6862 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 17:08:55.042  6862  6862 I Adreno-EGL: Build Date: 12/12/14 금
08-24 17:08:55.042  6862  6862 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 17:08:55.042  6862  6862 I Adreno-EGL: Remote Branch: 
08-24 17:08:55.042  6862  6862 I Adreno-EGL: Local Patches: 
08-24 17:08:55.042  6862  6862 I Adreno-EGL: Reconstruct Branch: 
,08-24 17:08:55.165  6862  6906 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 17:08:55.168  6862  6862 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-24 17:08:55.189  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:08:55.195  6862  6862 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 17:08:55.198  6862  6862 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 17:08:55.202  6862  6862 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 17:08:55.202  6862  6862 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-24 17:08:55.219  6862  6862 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 17:08:55.228  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 17:08:55.228  6862  6862 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:08:55.262  6862  6924 D OpenGLRenderer: Render dirty regions requested: true
,08-24 17:08:55.262  6862  6924 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 17:08:55.270  6862  6924 D OpenGLRenderer: Enabling debug mode 0
,08-24 17:08:55.280  6862  6862 D Atlas   : Validating map...
08-24 17:08:55.284  1038  2039 D SplitWindow: check instance of lgWin Window{2a396309 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 17:08:55.335  6862  6921 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 17:08:55.335  6862  6921 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 17:08:55.481  1038  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +676ms (total +767ms)
,08-24 17:08:55.483  6862  6862 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@223fab92 time:172073
08-24 17:08:55.485  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{257a54ba u0 com.test.thalitest/.MainActivity t6} time:172074
08-24 17:08:55.622  6862  6862 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 17:08:55.622  6862  6862 I chromium: 
,08-24 17:08:55.646  6862  6862 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 17:08:55.808  6862  6938 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435173888
,08-24 17:08:55.824  6862  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 17:08:55.824  6862  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 17:08:55.824  6862  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 17:08:55.824  6862  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 17:08:55.824  6862  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 17:08:55.825  6862  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@261dfbb6 added. We now have 1 listener(s)
,08-24 17:08:55.831  1038  2039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:08:55.834  6862  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-24 17:08:55.836  6862  6938 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-24 17:08:55.838  6862  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:55.838  6862  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 17:08:55.846  6862  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6eec78d added. We now have 1 listener(s)
08-24 17:08:55.847  6862  6938 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:55.856  1038  1432 D WifiService: New client listening to asynchronous messages
,08-24 17:08:55.864  6862  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:55.864  6862  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 17:08:55.866  6862  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 17:08:55.866  6862  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 17:08:55.866  6862  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 17:08:55.870  6862  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:55.870  1038  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:08:55.872  6862  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-24 17:08:55.883  6862  6938 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:55.884  6862  6938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:55.884  6862  6938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 17:08:55.885  6862  6938 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:55.888  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:55.890  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:55.891  6862  6938 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 17:08:55.924  6862  6921 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 17:08:55.924  6862  6921 I chromium: 
,08-24 17:08:55.988  6862  6862 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 17:08:56.164   331   349 E GBMv2   : DFP En is all cleared set to be enabled
08-24 17:08:56.164   331   349 E GBMv2   : Set value is all cleared set the max
08-24 17:08:56.164   331   349 I GBMv2   : DFP Enabled. Ignore VFP set
,08-24 17:08:56.759  6862  6941 W jxcore-log: Initializing JXcore engine
08-24 17:08:56.759  6862  6941 W jxcore-log: JXcore engine is ready
,08-24 17:08:56.829  6941  6941 W Thread-802: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7508]" dev="sockfs" ino=7508 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-24 17:08:56.829  6941  6941 W Thread-802: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-24 17:08:56.829  6941  6941 W Thread-802: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7637]" dev="sockfs" ino=7637 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 17:08:56.829  6941  6941 W Thread-802: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-24 17:08:56.839  6941  6941 W Thread-802: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33392]" dev="sockfs" ino=33392 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-24 17:08:56.877  6862  6941 W jxcore-log: Starting JXcore engine
,08-24 17:08:57.034  6862  6941 W jxcore-log: Platform android
08-24 17:08:57.034  6862  6941 W jxcore-log: 
08-24 17:08:57.034  6862  6941 W jxcore-log: Process ARCH arm
08-24 17:08:57.034  6862  6941 W jxcore-log: 
,08-24 17:08:57.263  6862  6941 I jxcore-log: JXcore Cordova bridge is ready!
08-24 17:08:57.263  6862  6941 I jxcore-log: 
08-24 17:08:57.264  6862  6941 W jxcore-log: JXcore engine is started
,08-24 17:08:57.275  6862  6938 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 17:08:57.277  6862  6862 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 17:09:00.056  1592  1592 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-24 17:09:00.056  1592  1592 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 17:09:00.060  1592  1592 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 17:09:00.060  1592  1592 I [SystemUI]Clock: called onTimeUpdated()
08-24 17:09:00.062  1592  1592 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 17:09:00.062  1592  1592 I [SystemUI]DateView: called onTimeUpdated()
08-24 17:09:00.063  1592  1592 I [SystemUI]DateView: called onTimeUpdated()
08-24 17:09:00.063  1592  1592 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 17:09:09.423  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 17:09:09.423  6862  6941 I jxcore-log: 
,08-24 17:09:09.426  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 17:09:09.426  6862  6941 I jxcore-log: 
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:09.431  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:09.434  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:09.437  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 17:09:09.437  6862  6941 I jxcore-log: 
,08-24 17:09:09.439  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 17:09:09.439  6862  6941 I jxcore-log: 
08-24 17:09:09.945  6862  6941 D executeNativeTests: Running unit tests
,08-24 17:09:10.028  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:09:10.028  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 added. We now have 2 listener(s)
,08-24 17:09:10.029  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:10.031  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:10.031  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:10.031  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:10.031  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:10.031  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 added. We now have 2 listener(s)
08-24 17:09:10.031  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:10.031  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:09:10.034  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:10.036  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:10.038  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.038  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:10.040  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.041  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.044  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:09:10.047  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 17:09:10.047  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:09:10.052  6862  6941 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-24 17:09:10.053  6862  6941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 17:09:10.053  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:09:10.056  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 17:09:10.056  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:09:10.057  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.059  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.059  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:09:10.061  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.061  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.061  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:10.062  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:10.062  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 removed from the list
08-24 17:09:10.062  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.062  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 removed from the list
08-24 17:09:10.062  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.062  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.062  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.062  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.063  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.063  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:09:10.063  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.063  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.065  6862  6941 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 17:09:10.065  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.065  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.065  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.065  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.065  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.065  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.066  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.066  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.066  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.066  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.066  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.066  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.066  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.066  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.066  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.066  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.067  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.067  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.070  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 17:09:10.070  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:09:10.070  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 17:09:10.070  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgo,ingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:09:10.071  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 17:09:10.071  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.071  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/st,op everything
08-24 17:09:10.071  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.072  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.072  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.072  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.072  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.072  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.072  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.072  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.072  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.072  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.073  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.073  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:09:10.074  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.075  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.075  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.075  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.076  6862  6941 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 17:09:10.078  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:10.079  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:10.080  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.080  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:10.081  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:10.081  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:09:10.081  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:09:10.081  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.081  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:09:10.082  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.084  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:10.085  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 17:09:10.085  1038  2021 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:10.090  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 17:09:10.093  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 17:09:10.095  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 17:09:10.096  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:09:10.098  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:10.099  6862  6941 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 17:09:10.099  6862  6941 I io.jxcore.node.ConnectionHelper: start: OK
08-24 17:09:10.102  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.102  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.102  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.102  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.102  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.102  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:10.102  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.102  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.102  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.102  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.102  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.103  6862  6941 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 17:09:10.104  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:10.106  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:10.107  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.107  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:10.107  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:10.107  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:09:10.107  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:09:10.107  6862  6941 I org.thaliproject.p2p.btconnectorlib.inter,nal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.107  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:09:10.109  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.110  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.113  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:09:10.113  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:10.114  6862  6941 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 17:09:10.114  6862  6941 I io.jxcore.node.ConnectionHelper: start: OK
08-24 17:09:10.115  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.115  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.115  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.115  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.115  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.115  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:10.115  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.115  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.116  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.116  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.116  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.116  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.116  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.116  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.116  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.118  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.118  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.118  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.118  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.118  6862  6941 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 17:09:10.120  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:10.121  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:10.122  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:10.122  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:10.123  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:10.123  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:09:10.123  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:09:10.123  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.123  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:09:10.124  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.126  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.127  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:09:10.127  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:10.128  6862  6941 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 17:09:10.128  6862  6941 I io.jxcore.node.ConnectionHelper: start: OK
08-24 17:09:10.128  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.128  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.128  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.128  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.129  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.129  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.129  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.129  6862  6941 W ,org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.129  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:10.129  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.129  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.129  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.129  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.129  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.129  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.129  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.129  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.129  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.130  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.130  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.130  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.130  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.130  6862  6941 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 17:09:10.131  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.131  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.131  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.131  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.131  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.131  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.131  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.131  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.131  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.131  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.131  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.131  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.131  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.131  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.132  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.132  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.132  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.132  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.132  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.132  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.133  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 17:09:10.133  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.133  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.133  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.133  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.133  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.133  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.133  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.133  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.133  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.133  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.134  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.134  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.134  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.134  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.134  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.134  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.135  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.135  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.135  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.135  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.135  6862  6941 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 17:09:10.135  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.135  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.135  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.136  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.136  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.136  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.136  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.136  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.136  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.136  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.136  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.136  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.136  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.136  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.137  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.137  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.137  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.137  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.137  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.137  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.138  6862  6941 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 17:09:10.138  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.138  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.138  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.138  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.138  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.138  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.138  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.138  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.138  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.138  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.138  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.138  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.138  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.138  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.139  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.139  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.139  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.139  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.139  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.139  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.140  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:09:10.141  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:09:10.141  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:09:10.141  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:09:10.141  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:09:10.141  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:09:10.141  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.141  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.141  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.141  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.141  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.141  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.141  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.141  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.141  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.141  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.141  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.141  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.141  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.141  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.142  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.142  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.142  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.142  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.142  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.142  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.143  6862  6941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:09:10.143  6862  6941 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 17:09:10.143  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 17:09:10.145  6862  6941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:09:10.145  6862  6941 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:09:10.145  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 17:09:10.146  6862  6941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 17:09:10.146  6862  6941 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:09:10.146  6862  6941 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 17:09:10.146  6862  6941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:09:10.146  6862  6941 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:09:10.146  6862  6941 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 17:09:10.146  6862  6941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:09:10.146  6862  6941 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:09:10.146  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 17:09:10.148  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 17:09:10.149  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 17:09:10.149  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 17:09:10.150  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 17:09:10.150  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 17:09:10.150  6862  6941 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 17:09:10.150  6862  6941 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:09:10.150  6862  6941 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 17:09:10.150  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.150  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.150  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.151  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.151  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.151  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.151  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 17:09:10.151  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.151  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.151  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.151  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.151  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.151  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.151  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.151  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.152  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.152  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.152  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.152  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.152  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.153  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.153  6862  6941 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 17:09:10.155  6862  6952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 866
08-24 17:09:10.156  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.156  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.156  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.156  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.156  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.156  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.156  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.156  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.156  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.156  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.156  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.156  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.156  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.156  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.157  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.157  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.157  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.157  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.157  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.157  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.158  6862  6941 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 17:09:10.158  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:09:10.161  6862  6951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 866)
08-24 17:09:10.161  6862  6951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 866)
08-24 17:09:10.162  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.162  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.162  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.162  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.162  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.162  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.162  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.162  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.162  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.162  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.162  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.162  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.162  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.163  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.163  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.163  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.163  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.163  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.163  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.164  6862  6941 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 17:09:10.164  6862  6941 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 17:09:10.164  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:09:10.164  6862  6941 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 17:09:10.165  6862  6941 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:09:10.165  6862  6941 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 17:09:10.165  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:09:10.165  6862  6941 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 17:09:10.165  6862  6941 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:09:10.165  6862  6941 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 17:09:10.165  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:09:10.165  6862  6941 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 17:09:10.165  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.165  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.165  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.166  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.166  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.166  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.166  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.166  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.166  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.166  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.166  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.166  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.166  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.166  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.167  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.167  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.167  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.167  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.168  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.168  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.168  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.168  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.168  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.168  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.168  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.168  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.168  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.168  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.168  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.168  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.168  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.168  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.168  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.168  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.168  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.168  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.168  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.168  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.169  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.169  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.169  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.169  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.169  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.169  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.169  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.169  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.169  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.169  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.169  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.170  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.170  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.170  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.170  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.170  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.170  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.171  6862  6941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 17:09:10.172  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:10.172  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 17:09:10.173  6862  6941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 17:09:10.173  6862  6941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 17:09:10.173  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 17:09:10.173  6862  6862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 17:09:10.173  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:09:10.174  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.174  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 17:09:10.174  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 17:09:10.174  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 17:09:10.174  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.174  6862  6941 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 17:09:10.174  6862  6958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 17:09:10.175  6862  6958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 17:09:10.175  6862  6862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 17:09:10.176  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.176  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.176  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:09:10.176  6862  6941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:09:10.176  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:09:10.177  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:09:10.177  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:10.177  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:10.177  6862  6941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:09:10.177  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.177  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.178  6862  6941 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:09:10.178  6862  6862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:09:10.178  6862  6862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 17:09:10.178  6862  6862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:09:10.178  6862  6862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:09:10.179  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.179  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.179  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.179  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.179  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.179  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.179  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.179  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.179  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.179  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.179  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.179  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.179  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.179  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.179  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.180  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.180  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.180  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.180  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.181  6862  6941 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 17:09:10.181  6862  6941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 17:09:10.181  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:09:10.182  6862  6941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:09:10.182  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.182  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.182  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.182  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.182  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.182  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.182  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.182  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.183  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.183  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.183  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.183  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.183  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.183  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.183  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.183  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.183  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.183  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.184  1038  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:10.185  1038  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:10.185  1038  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:10.186  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.186  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.186  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.186  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.186  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.186  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.186  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.186  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.186  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.186  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.186  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.186  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.186  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.186  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.187  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.187  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.187  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.187  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.188  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:10.188  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:10.188  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:10.188  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:10.188  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.188  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.188  6862  6941 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aa97906 not in the list
08-24 17:09:10.188  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.188  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.188  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:10.188  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.188  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.188  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:10.189  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:10.189  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:10.189  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:10.189  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:10.189  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dac8bc7 not in the list
08-24 17:09:10.190  6862  6941 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 17:09:10.191  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:09:10.191  6862  6941 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 17:09:10.191  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:09:10.191  6862  6941 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 17:09:10.191  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:09:10.192  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 17:09:10.192  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 17:09:10.193  6862  6941 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 17:09:10.193  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:09:10.194  6862  6941 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 17:09:10.194  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:09:10.194  6862  6941 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 17:09:10.194  6862  6941 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-24 17:09:10.194  6862  6941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-24 17:09:10.194  6862  6941 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 17:09:10.195  6862  6941 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 17:09:10.195  6862  6941 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 17:09:10.195  6862  6941 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 17:09:10.195  6862  6941 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 17:09:10.195  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:09:10.196  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a46f8c added. We now have 2 listener(s)
08-24 17:09:10.196  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:10.197  6862  6941 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 17:09:10.197  1038  1726 D WifiServiceImplEx: setWifiEnabled: true pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 17:09:10.198  1038  1726 D WifiService: setWifiEnabled: true pid=6862, uid=10118
08-24 17:09:10.198  1038  1726 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 17:09:10.199  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:10.199  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4856d5 added. We now have 3 listener(s)
08-24 17:09:10.199  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:10.202  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:10.202  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27000eea added. We now have 4 listener(s)
08-24 17:09:10.202  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:10.203  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:10.203  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@128dd5db added. We now have 5 listener(s)
08-24 17:09:10.203  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:09:10.204  1038  1726 D WifiServiceImplEx: setWifiEnabled: false pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 17:09:10.204  1038  1726 D WifiService: setWifiEnabled: false pid=6862, uid=10118
08-24 17:09:10.204  1038  1726 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 17:09:10.223  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:10.224  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 17:09:10.224  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-24 17:09:10.225  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:10.225  1038  1909 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1c40c270 mBinding = false
08-24 17:09:10.225  1038  1379 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:10.226  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:10.226  1038  1379 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:10.227  1038  1379 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:10.227  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:10.227  1038  1379 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 17:09:10.227  1038  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:09:10.227  1038  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 17:09:10.228  1038  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 17:09:10.228  1038  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 17:09:10.238  1038  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 17:09:10.238  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.238  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.239  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 17:09:10.239  2697  2697 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-24 17:09:10.239  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 17:09:10.239  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 17:09:10.240  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:10.241  1038  2853 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.247   312   896 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:09:10.290  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-24 17:09:10.291  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-24 17:09:10.293  1038  1984 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-24 17:09:10.293  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.293  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.293  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 17:09:10.293  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.293  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-24 17:09:10.298  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-24 17:09:10.298  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.298  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.298  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:10.299  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:10.299  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:10.301  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-24 17:09:10.304  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:10.314  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:10.315  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:10.316  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 17:09:10.320  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-24 17:09:10.321  1038  1120 D BluetoothManagerService: Message: 2
08-24 17:09:10.321  1038  1120 D BluetoothManagerService: Sending off request.
08-24 17:09:10.323  4240  4263 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-24 17:09:10.324  4240  4315 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 17:09:10.324  4240  4315 D BluetoothAdapterProperties: Setting state to 13
08-24 17:09:10.324  4240  4315 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:09:10.324  4240  4315 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 17:09:10.324  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:10.324  4240  4315 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 17:09:10.324  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-24 17:09:10.324  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-24 17:09:10.356  1038  1591 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6974 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 17:09:10.358  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.358  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.359  1038  1377 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@33ecff4d
08-24 17:09:10.359  1038  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:10.359  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:10.360  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:10.360  4240  4320 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:09:10.360  1038  1377 D LGWifiP2pService: P2pDisablingState
08-24 17:09:10.360  1038  1377 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.360  1038  1377 D LGWifiP2pService: p2p socket connection lost
08-24 17:09:10.360  1038  1377 D LGWifiP2pService: P2pDisabledState
,08-24 17:09:10.361  1038  1433 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-24 17:09:10.361  4240  4315 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 17:09:10.361  1038  1433 D DSQN    : disableDataServiceNotify
08-24 17:09:10.361  1038  1433 D DSQN    : stop dsqn bin
08-24 17:09:10.362  4240  4315 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 17:09:10.362  4240  4667 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:10.362   312  6983 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 17:09:10.363  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-24 17:09:10.363  4240  4439 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-24 17:09:10.364  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 17:09:10.365  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-24 17:09:10.365  4240  4695 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:10.365  1038  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:10.366  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:10.366  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:10.366  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:10.366  4240  4694 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:10.366  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:10.366  4240  4708 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 17:09:10.367  4240  4663 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-24 17:09:10.367  1038  1379 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 17:09:10.367  1038  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 17:09:10.368  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 17:09:10.368  2697  2697 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 17:09:10.368  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.368  1038  1377 D LGWifiP2pService: D,efaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.368  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:10.368  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 17:09:10.369  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 17:09:10.369  4240  4439 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 17:09:10.369  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:10.370  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-24 17:09:10.370  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.371  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.371  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:10.373  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 17:09:10.373  1038  1038 D RttService: SCAN_AVAILABLE : 1
08-24 17:09:10.373  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:09:10.373  1038  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.373  1038  1433 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 17:09:10.373  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:10.373  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:10.374  1038  1433 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:10.374  1038  1433 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 17:09:10.375  1038  1433 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 17:09:10.375  1038  1433 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-24 17:09:10.375  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.375  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 17:09:10.375  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.375  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 17:09:10.375  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 17:09:10.375  1038  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 17:09:10.375  1038  1433 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:10.376  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 17:09:10.376  1038  1433 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:10.376  1038  1433 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:10.376  1038  1433 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:10.377  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:10.377   312   896 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:09:10.377  1038  1544 D RttService: EnabledState got{ when=-5ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:10.378  1038  1433 D NetworkManagementService: Removing idletimer
08-24 17:09:10.378  1038  1433 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.378  1928  1928 D WfdsService: WifiP2pState is changed : false
08-24 17:09:10.378  1038  1433 E ConnectivityService: EVENT_NETWORK_INFO_CHA,NGED from unknown NetworkAgent
08-24 17:09:10.378  1928  2205 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 17:09:10.379  1928  2205 D WfdsService: Set the WFDS Monitor: false
08-24 17:09:10.379  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:10.379  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:10.380  1841  1841 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:10.380  1592  1819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 17:09:10.380  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 17:09:10.381  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.381  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:10.382  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:10.382  1928  2205 D WfdsMonitor: WFDS Monitor is stopped
08-24 17:09:10.383  1928  2205 D WfdsService: STATE : WfdsDisabledState - enter
08-24 17:09:10.383  1928  2768 D CtrlSupplicant: Received on exit socket, terminate
08-24 17:09:10.383  1928  2768 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
,08-24 17:09:10.383  1928  2768 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 17:09:10.383  1928  2768 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 17:09:10.383  1928  2205 W WfdsService: DefaultState - msg [9445378] is not handled
08-24 17:09:10.383  1928  2206 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 17:09:10.386  4240  4240 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:10.386  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:10.386  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:09:10.386  4240  4240 D BluetoothMapService: STATE_TURNING_OFF
08-24 17:09:10.386  4240  4240 V BtOppService: Receiver DISABLED_ACTION 
08-24 17:09:10.387  4240  4240 V BluetoothMapService: Handler(): got msg=4
08-24 17:09:10.387  4240  4240 D BluetoothMapService: MAP Service closeService in
08-24 17:09:10.387  4240  4240 D BluetoothMapMasInstance: MAP Service shutdown
08-24 17:09:10.387  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.387  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:10.387  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:09:10.387  4240  4240 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 17:09:10.387  4240  4240 V BluetoothMapService: MAP Service closeService out
08-24 17:09:10.388  4240  4240 I BtOppRfcommListener: stopping Accept Thread
08-24 17:09:10.388  4240  4240 V BtOppRfcommListener: close mBtServerSocket
08-24 17:09:10.388  4240  4240 V BtOppRfcommListener: waiting for thread to terminate
08-24 17:09:10.388  4240  4694 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 17:09:10.389  4240  4240 V BtOppRfcommListener: done waiting for thread to terminate
,08-24 17:09:10.391  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:10.391  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:10.393  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:10.393  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:10.395  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 17:09:10.427  1038  1101 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6992 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 17:09:10.429  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:10.431  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.431  1038  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 17:09:10.431  1038  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 17:09:10.434  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 17:09:10.434  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 17:09:10.434  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 17:09:10.434  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 17:09:10.434  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 17:09:10.434  4240  4240 V BtOppService: onDestroy
08-24 17:09:10.434  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 17:09:10.434  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 17:09:10.434  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 17:09:10.438  4240  4240 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-24 17:09:10.439  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-24 17:09:10.439  1038  1379 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 17:09:10.440  1038  1379 D WifiNative-p2p0: TERMINATE: returned true
08-24 17:09:10.440  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:10.440  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:10.440  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 17:09:10.441  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.441  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.441  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:10.448  1038  2853 D DhcpStateMachine: StoppedState
08-24 17:09:10.448  1038  2853 D DhcpStateMachine: StoppedState{ when=-72ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:09:10.451  1038  1379 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:10.451  1038  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:10.451  1038  1379 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-24 17:09:10.451  1038  1379 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-24 17:09:10.452  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-24 17:09:10.452  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 17:09:10.453  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:10.453  1038  1038 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 17:09:10.454  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:10.454  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:10.456  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.456  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:10.457  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:10.457  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:10.458  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:10.458  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:10.464  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 17:09:10.465  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 17:09:10.466  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:10.486  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 17:09:10.487  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:10.487  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:10.489  6992  6992 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:10.489  6992  6992 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-24 17:09:10.489  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-24 17:09:10.489  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:10.489  6992  6992 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:10.489  6992  6992 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-24 17:09:10.491  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:10.494  6992  6992 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 17:09:10.495  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 17:09:10.495  6992  6992 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 17:09:10.505  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:10.506  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:10.507  1038  1983 I ActivityManager: Killing 6232:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-24 17:09:10.509  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:10.541  2697  2697 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 17:09:10.541  2697  2697 I wpa_supplicant: monitor socket send errors count : 1
08-24 17:09:10.541  2697  2697 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
,08-24 17:09:10.542  1038  2765 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 17:09:10.542  1038  2765 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 17:09:10.543  1038  1964 W libprocessgroup: failed to open /acct/uid_10014/pid_6232/cgroup.procs: No such file or directory
08-24 17:09:10.579  2697  2697 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 17:09:10.580  2697  2697 W wpa_supplicant: USIM:  scard_deinit function
08-24 17:09:10.581  1038  2765 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-24 17:09:10.582  1038  2765 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 17:09:10.582  1038  2765 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 17:09:10.582  1038  1120 D Tethering: InitialState.processMessage what=4
08-24 17:09:10.583  1038  2765 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 17:09:10.584  1038  2765 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:10.584  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:09:10.584  1038  2765 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:10.585  1038  1379 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=187163
08-24 17:09:10.586  1038  1379 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=187164
08-24 17:09:10.588  1038  1379 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:10.588  6992  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 17:09:10.589  1038  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:10.590  1038  1379 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=187168  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 17:09:10.592  1038  1379 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=187169  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-24 17:09:10.595  4240  4240 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 17:09:10.595  4240  4240 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:10.595  4240  4240 V BluetoothPbapReceiver: ***********state = 13
08-24 17:09:10.597  4240  4240 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-24 17:09:10.600  4240  4240 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:10.600  4240  4240 V BluetoothPbapService: state: 13
08-24 17:09:10.600  4240  4240 V BluetoothPbapService: Pbap Service closeService in
08-24 17:09:10.601  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:10.601  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 17:09:10.602  4240  4240 V BluetoothPbapService: successfully stopped pbap service
08-24 17:09:10.602  4240  4240 V BluetoothPbapService: Pbap Service closeService out
08-24 17:09:10.602  4240  4240 V BluetoothPbapService: Pbap Service onDestroy
08-24 17:09:10.602  4240  4240 V BluetoothPbapService: Pbap Service closeService in
08-24 17:09:10.602  4240  4240 V BluetoothPbapService: Pbap Service closeService out
08-24 17:09:10.603  4240  4240 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-24 17:09:10.646  6992  6992 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:10.646  6992  6992 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 17:09:10.658  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:10.667  1038  1120 D BluetoothManagerService: Message: 20
08-24 17:09:10.667  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c2b7f2b:true
08-24 17:09:10.672  1038  1946 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7013 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 17:09:10.679  6862  6862 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-24 17:09:10.683  1038  1120 D BluetoothManagerService: Message: 30
08-24 17:09:10.688  1038  1120 D BluetoothManagerService: Message: 30
,08-24 17:09:10.691  6992  6992 D LocalBluetoothProfileManager: Adding local MAP profile
08-24 17:09:10.693  2697  2697 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-24 17:09:10.693  1038  2765 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-24 17:09:10.693  1038  2765 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 17:09:10.693  1038  2765 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 17:09:10.694  6992  6992 D BluetoothMap: Create BluetoothMap proxy object
08-24 17:09:10.695  1038  1379 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-24 17:09:10.695  1038  1120 D BluetoothManagerService: Message: 30
08-24 17:09:10.700  1038  1120 D BluetoothManagerService: Message: 30
,08-24 17:09:10.703  6992  6992 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-24 17:09:10.705  6992  6992 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-24 17:09:10.726  6992  6992 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-24 17:09:10.730  6992  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-24 17:09:10.745  6992  6992 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:09:10.770  6992  6992 D BluetoothInputDevice: Proxy object connected
,08-24 17:09:10.771  6992  6992 D HidProfile: Bluetooth service connected
08-24 17:09:10.773  6992  6992 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:09:10.774  6992  6992 D PanProfile: Bluetooth service connected
08-24 17:09:10.775  6992  6992 D BluetoothMap: Proxy object connected
08-24 17:09:10.775  6992  6992 D MapProfile: Bluetooth service connected
08-24 17:09:10.776  6992  6992 D BluetoothMap: getConnectedDevices()
08-24 17:09:10.776  6992  6992 D BluetoothMap: Bluetooth is Not enabled
08-24 17:09:10.776  6992  6992 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 17:09:10.843  1038  1945 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7037 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-24 17:09:10.849  1038  1379 D WifiOffDelayIfNotUsed: stopMonitoring
08-24 17:09:10.849  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:10.849  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:10.849  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 17:09:10.853  1038  1945 I ActivityManager: Killing 6303:com.android.defcontainer/u0a4 (adj 15): empty #17
08-24 17:09:10.907  7013  7013 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-24 17:09:10.907  7013  7013 W LG Account v2.2: No ProfileInfo entries
08-24 17:09:10.907  7013  7013 I LG Account v2.2: isEnabled: false
,08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Country: EU
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Operator: OPEN
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Ranking support: false
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Comfort support: false
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Accessory: true
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Health device: true
08-24 17:09:10.908  1928  1928 D WfdsService: Supplicant Connection state is changed : false
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Extra Pedometer: false
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Blood glucose device: false
08-24 17:09:10.908  7013  7013 I Feature : [Lifetracker]Device Number: 3
08-24 17:09:10.908  1928  2205 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 17:09:10.909  1928  2205 D WfdsService: Set the WFDS Monitor: false
08-24 17:09:10.909  1928  2205 D WfdsMonitor: WFDS Monitor is stopped
08-24 17:09:10.911  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 17:09:10.911  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:10.911  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 17:09:10.915  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.916  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:10.926  1038  2020 W libprocessgroup: failed to open /acct/uid_10004/pid_6303/cgroup.procs: No such file or directory
,08-24 17:09:10.929  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-24 17:09:10.930  1038  1423 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 17:09:10.930  1038  1423 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-24 17:09:10.934  6992  6992 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-24 17:09:10.939  6992  6992 D BluetoothPermissionRequest: onReceive
,08-24 17:09:10.941  7037  7037 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:10.942  6992  6992 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-24 17:09:10.951  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 17:09:10.954  1038  2039 I ActivityManager: Killing 6467:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-24 17:09:11.015  4240  4240 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-24 17:09:11.016  4240  4240 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-24 17:09:11.017  4240  4240 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-24 17:09:11.018  1038  1726 W libprocessgroup: failed to open /acct/uid_10008/pid_6467/cgroup.procs: No such file or directory
08-24 17:09:11.027  7037  7037 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-24 17:09:11.036  4240  4240 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:11.036  4240  4240 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-24 17:09:11.048  4240  4240 V BluetoothFtpService: Ftp Service onStartCommand
08-24 17:09:11.048  4240  4240 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:11.049  4240  4240 V BluetoothFtpService: Ftp Service closeService
08-24 17:09:11.049  4240  4240 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-24 17:09:11.056  4240  4240 V BluetoothFtpService: successfully stopped ftp service
08-24 17:09:11.057  4240  4240 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:11.057  4240  4240 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 17:09:11.057  4240  4240 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 17:09:11.058  4240  4240 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:11.058  4240  4240 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-24 17:09:11.058  4240  4240 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 17:09:11.062  4240  4240 V BluetoothFtpService: Ftp Service onDestroy
08-24 17:09:11.062  4240  4240 V BluetoothFtpService: Ftp Service closeService
08-24 17:09:11.090  7037  7037 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-24 17:09:11.091  7037  7037 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-24 17:09:11.091  7037  7037 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-24 17:09:11.092  7037  7037 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-24 17:09:11.092  7037  7037 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-24 17:09:11.094  7037  7037 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-24 17:09:11.104  7037  7037 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-24 17:09:11.125  1038  1591 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7056 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 17:09:11.129  4240  4240 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:11.130  4240  4240 V BluetoothSapService: state: 13
08-24 17:09:11.130  4240  4240 V BluetoothSapService: Stopping SAP server process
08-24 17:09:11.135  4240  4240 V BluetoothSapService: Sap Service closeSapService in
08-24 17:09:11.135  4240  4240 V BluetoothSapService: Close listen Socket : 
08-24 17:09:11.135  4240  4240 V BluetoothSapService: Close rfcomm Socket : 
08-24 17:09:11.135  4240  4240 V BluetoothSapService: Close sapd  Socket : 
08-24 17:09:11.136  4240  4240 V BluetoothSapService: Sap Service closeSapService out
08-24 17:09:11.137  4240  4240 V BluetoothSapService: Sap Service onDestroy
08-24 17:09:11.137  4240  4240 V BluetoothSapService: Sap Service closeSapService in
08-24 17:09:11.137  4240  4240 V BluetoothSapService: Close listen Socket : 
08-24 17:09:11.137  4240  4240 V BluetoothSapService: Close rfcomm Socket : 
08-24 17:09:11.137  4240  4240 V BluetoothSapService: Close sapd  Socket : 
08-24 17:09:11.139  4240  4240 V BluetoothSapService: Sap Service closeSapService out
,08-24 17:09:11.145  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:11.147  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:11.163  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:11.166  7037  7037 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-24 17:09:11.169  7037  7037 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-24 17:09:11.170  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:11.175  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 17:09:11.175  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:11.175  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:11.179  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:11.186  7056  7056 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 17:09:11.202  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:11.209  1038  2021 I ActivityManager: Killing 6508:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-24 17:09:11.243  1038  1053 W libprocessgroup: failed to open /acct/uid_10011/pid_6508/cgroup.procs: No such file or directory
08-24 17:09:11.243  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:11.244  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:11.249  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:11.260  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:11.268  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 17:09:11.268  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:11.269  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:11.274  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:11.286  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:11.299  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 17:09:11.300  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:11.303  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:11.374  4240  4320 D bt_hci_bdroid: cleanup
,08-24 17:09:11.375  4240  4441 I bt_lpm  : LPM is already off!!!
08-24 17:09:11.376  4240  4655 I bt_userial_mct: exiting userial_read_thread
08-24 17:09:11.376  4240  4655 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 17:09:11.376  4240  4439 W bt-btif : ag scb idx 1 not allocated
08-24 17:09:11.377  4240  4439 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 17:09:11.377  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:11.377  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:09:11.377  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:11.377  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:09:11.377  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:11.377  4240  4439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:11.378  4240  4320 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-24 17:09:11.378  4240  4441 I bt_vendor: hw_epilog_process
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:11.378  4240  4320 D bt_hci_bdroid: cleanup Finalizing cleanup
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:09:11.378  4240  4320 D bt_userial_mct: userial_close
08-24 17:09:11.378  4240  4320 E bt_userial_mct: pthread_join() FAILED result:3
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:11.378  4240  4320 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:09:11.378  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:11.379  4240  4439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:09:11.379  4240  4439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:11.379  4240  4439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:11.379  4240  4439 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 17:09:11.387  1038  1726 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7076 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-24 17:09:11.450  4240  4320 D bt_hci_bdroid: set_power 0
08-24 17:09:11.450  4240  4320 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 17:09:11.450  4240  4320 I bt_vendor: bluetooth satus is on
08-24 17:09:11.450  4240  4320 I bt_vendor: bt-vendor : resetting BT status
08-24 17:09:11.451  4240  4320 I bt_vendor: Starting hciattach daemon
08-24 17:09:11.451  4240  4320 I bt_vendor: try to set false
,08-24 17:09:11.454  4240  4320 I bt_vendor: Starting hciattach daemon
08-24 17:09:11.455  4240  4320 I bt_vendor: try to set false
08-24 17:09:11.456  4240  4320 I bt_vendor: cleanup
08-24 17:09:11.457  4240  4439 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 17:09:11.457  4240  4320 I GKI_LINUX: GKI_exit_task 0 done
08-24 17:09:11.458  4240  4320 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 17:09:11.460  4240  4315 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 17:09:11.463  4240  4240 D HeadsetService: Received stop request...Stopping profile...
08-24 17:09:11.464  4240  4240 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 17:09:11.464  4240  4240 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 17:09:11.464  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30511fc4
,08-24 17:09:11.464  4240  4390 D HeadsetStateMachine: Exit Disconnected: -1
,08-24 17:09:11.466  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:11.471  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:11.472  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:11.473  1038  1038 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:11.473  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 17:09:11.475  4240  4240 D A2dpService: Received stop request...Stopping profile...
08-24 17:09:11.475  4240  4427 D A2dpStateMachine: Exit Disconnected: -1
08-24 17:09:11.476  4240  4240 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 17:09:11.478  4240  4315 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-24 17:09:11.480  4240  4240 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 17:09:11.480  4240  4240 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 17:09:11.480  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30511fc4
08-24 17:09:11.482  4240  4240 D HeadsetStateMachine: Unbinding service...
08-24 17:09:11.484  1038  1038 D BluetoothA2dp: Proxy object disconnected
08-24 17:09:11.484  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 17:09:11.484  4240  4240 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 17:09:11.484  4240  4240 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 17:09:11.484  4240  4240 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 17:09:11.484  4240  4240 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 17:09:11.484  4240  4240 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 17:09:11.484  4240  4240 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 17:09:11.484  4240  4240 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 17:09:11.485  4240  4240 D HidService: Received stop request...Stopping profile...
08-24 17:09:11.485  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30511fc4
08-24 17:09:11.487  4240  4240 D HealthService: Received stop request...Stopping profile...
08-24 17:09:11.487  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30511fc4
08-24 17:09:11.487  6992  6992 D BluetoothInputDevice: Proxy object disconnected
08-24 17:09:11.488  6992  6992 D HidProfile: Bluetooth service disconnected
08-24 17:09:11.488  4240  4240 D PanService: Received stop request...Stopping profile...
08-24 17:09:11.489  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30511fc4
08-24 17:09:11.490  6992  6992 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 17:09:11.490  6992  6992 D PanProfile: Bluetooth service disconnected
08-24 17:09:11.490  4240  4240 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 17:09:11.491  4240  4240 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 17:09:11.491  4240  4240 D BtGatt.GattService: stop()
08-24 17:09:11.491  4240  4240 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 17:09:11.492  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30511fc4
,08-24 17:09:11.493  4240  4240 D BluetoothMapService: Received stop request...Stopping profile...
08-24 17:09:11.493  4240  4240 D BluetoothMapService: stop()
08-24 17:09:11.494  4240  4240 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 17:09:11.494  4240  4240 D BluetoothMapEmailAppObserver: removeReceiver()
08-24 17:09:11.494  4240  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30511fc4
08-24 17:09:11.496  4240  4240 I BluetoothA2dpServiceJni: cleanupNative
08-24 17:09:11.496  4240  4428 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 17:09:11.497  4240  4240 I GKI_LINUX: GKI_exit_task 2 done
08-24 17:09:11.497  4240  4240 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 17:09:11.497  4240  4240 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 17:09:11.497  4240  4240 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 17:09:11.497  4240  4240 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 17:09:11.497  6992  6992 D BluetoothMap: Proxy object disconnected
08-24 17:09:11.497  6992  6992 D MapProfile: Bluetooth service disconnected
08-24 17:09:11.498  4240  4240 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:09:11.498  4240  4240 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:09:11.498  4240  4240 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 17:09:11.498  4240  4240 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 17:09:11.499  4240  4240 V BluetoothMapService: Handler(): got msg=4
08-24 17:09:11.499  4240  4240 D BluetoothMapService: MAP Service closeService in
08-24 17:09:11.499  4240  4240 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 17:09:11.499  4240  4240 V BluetoothMapService: MAP Service closeService out
08-24 17:09:11.500  4240  4315 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 17:09:11.500  4240  4315 D BluetoothAdapterProperties: Setting state to 10
08-24 17:09:11.500  4240  4315 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 17:09:11.500  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:11.500  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 17:09:11.500  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-24 17:09:11.501  4240  4240 D BluetoothMapService: cleanup()
08-24 17:09:11.501  4240  4240 D BluetoothMapService: MAP Service closeService in
08-24 17:09:11.501  4240  4240 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 17:09:11.501  4240  4240 V BluetoothMapService: MAP Service closeService out
08-24 17:09:11.501  4240  4315 I BluetoothAdapterState: Entering OffState
08-24 17:09:11.501  1841  2703 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:11.502  1841  2427 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:11.502  6992  7007 D BluetoothMap: onBluetoothStateChange: up=false
08-24 17:09:11.503  1841  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:11.503  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:11.503  6992  7008 D BluetoothPan: onBluetoothStateChange on: false
08-24 17:09:11.504  6992  7007 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 17:09:11.504  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:09:11.505  6992  7008 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 17:09:11.506  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 17:09:11.506  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-24 17:09:11.508  1038  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 17:09:11.509  1038  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 17:09:11.509  1038  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1c40c270 mBinding = false
08-24 17:09:11.509  1038  1120 D BluetoothManagerService: Sending unbind request.
08-24 17:09:11.511  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-24 17:09:11.512  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:11.512  1928  2091 D LGBluetoothAPIService: Message: 2
08-24 17:09:11.513  1928  2091 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3e018167 mBinding = false
08-24 17:09:11.513  1928  2091 D LGBluetoothAPIService: Sending unbind request.
,08-24 17:09:11.517  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 17:09:11.518  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:11.519  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:11.520  4240  4320 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-24 17:09:11.520  4240  4240 I GKI_LINUX: GKI_exit_task 1 done
08-24 17:09:11.520  4240  4240 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 17:09:11.521  4240  4240 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 17:09:11.521  4240  4240 I art     : --- WEIRD: removing null entry 246
08-24 17:09:11.521  4240  4240 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-24 17:09:11.521  4240  4240 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-24 17:09:11.522  6992  6992 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 17:09:11.522  6992  6992 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 17:09:11.522  6992  6992 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 17:09:11.523  4240  4240 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-24 17:09:11.525  1592  1592 D BluetoothAdapter: 274941007: getState() :  mService = null. Returning STATE_OFF
08-24 17:09:11.525  1592  1592 D BluetoothAdapter: 274941007: getState() :  mService = null. Returning STATE_OFF
08-24 17:09:11.526  6992  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-24 17:09:11.526  4240  4240 I art     : System.exit called, status: 0
08-24 17:09:11.526  4240  4240 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-24 17:09:11.534  6992  6992 D DockEventReceiver: finishStartingService: stopping service
08-24 17:09:11.538  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:11.545   316  1386 V AudioFlinger: 4240 died, releasing its sessions
08-24 17:09:11.545   316  1386 V AudioFlinger:  pid 1841 @ 0
08-24 17:09:11.545   316  1386 V AudioFlinger:  pid 3285 @ 1
08-24 17:09:11.545   316  1386 V AudioFlinger:  pid 3285 @ 2
,08-24 17:09:11.546  6992  6992 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-24 17:09:11.547  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:09:11.554  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:11.563  1038  1053 I ActivityManager: Process com.android.bluetooth (pid 4240) has died
08-24 17:09:11.563  1038  1053 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-24 17:09:11.571  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:09:11.582  7076  7101 W FormManager: Network not available. Please check & try again.
08-24 17:09:11.598  6992  6992 D BluetoothPermissionRequest: onReceive
,08-24 17:09:11.605  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-24 17:09:11.605  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 17:09:11.605  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 17:09:11.606  6992  6992 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 17:09:11.607  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 17:09:11.610  7076  7102 V FormManager: Network unavailable.
,08-24 17:09:11.614  7076  7102 V FormManager: Network unavailable.
08-24 17:09:11.619  6992  6992 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 17:09:11.619  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 17:09:11.619  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 17:09:11.619  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 17:09:11.619  6992  6992 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 17:09:11.619  6992  6992 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 17:09:11.621  6992  6992 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 17:09:11.621  6992  6992 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-24 17:09:11.622  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-24 17:09:11.689  1038  1983 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7111 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-24 17:09:11.696  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:11.697  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:11.699  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:11.701  1038  2039 I ActivityManager: Killing 6024:com.android.contacts/u0a19 (adj 15): empty #17
08-24 17:09:11.787  1038  1054 W libprocessgroup: failed to open /acct/uid_10019/pid_6024/cgroup.procs: No such file or directory
,08-24 17:09:11.787  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:11.803  1592  1592 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 17:09:11.804  1592  1592 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 17:09:11.807  1038  1432 D WifiController: battery changed pluggedType: 2
08-24 17:09:11.809  1592  1592 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
08-24 17:09:11.809  1592  1592 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 17:09:11.812  1592  1592 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 17:09:11.813  1928  2079 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 17:09:11.813  1928  2079 D LEDHandler: Battery Level Remaining: 100%
08-24 17:09:11.813  1928  2079 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
08-24 17:09:11.822  5607  5607 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 17:09:11.831  4779  7128 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:11.832  4779  7129 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:11.832  6974  6974 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-24 17:09:11.832  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:11.832  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:11.834  4779  7129 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 17:09:11.837  7111  7111 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-24 17:09:11.837  7111  7111 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:11.838  7111  7111 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 17:09:11.838  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 17:09:11.839  7111  7111 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 17:09:11.845  7076  7132 W FormManager: Network not available. Please check & try again.
,08-24 17:09:11.851  7076  7133 V FormManager: Network unavailable.
,08-24 17:09:11.854  7076  7133 V FormManager: Network unavailable.
08-24 17:09:11.858  7111  7111 D BluetoothAdapterApp: Loading JNI Library
08-24 17:09:11.860  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:11.876  7037  7037 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 17:09:11.877  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-24 17:09:11.877  7037  7037 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-24 17:09:11.892  7111  7111 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a2275f5 Instance Count = 1
,08-24 17:09:11.896  7111  7111 D BluetoothAdapterApp: onCreate
08-24 17:09:11.912  7111  7111 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-24 17:09:11.912  7111  7111 D ProfileConfigQcom: Adding HeadsetService
08-24 17:09:11.912  7111  7111 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-24 17:09:11.912  7111  7111 D ProfileConfigQcom: Adding A2dpService
08-24 17:09:11.912  7111  7111 D ProfileConfigQcom: [BTUI] HidService is supported
08-24 17:09:11.912  7111  7111 D ProfileConfigQcom: Adding HidService
08-24 17:09:11.913  7111  7111 D ProfileConfigQcom: [BTUI] HealthService is supported
08-24 17:09:11.913  7111  7111 D ProfileConfigQcom: Adding HealthService
08-24 17:09:11.913  7111  7111 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-24 17:09:11.913  7111  7111 D ProfileConfigQcom: [BTUI] PanService is supported
08-24 17:09:11.913  7111  7111 D ProfileConfigQcom: Adding PanService
08-24 17:09:11.914  7111  7111 D ProfileConfigQcom: [BTUI] GattService is supported
08-24 17:09:11.914  7111  7111 D ProfileConfigQcom: Adding GattService
08-24 17:09:11.914  7111  7111 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 17:09:11.914  7111  7111 D ProfileConfigQcom: Adding BluetoothMapService
08-24 17:09:11.914  7111  7111 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-24 17:09:11.915  7111  7111 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-24 17:09:11.917  7037  7037 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:11.917  7037  7037 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 17:09:11.918  6992  6992 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 17:09:11.919  7111  7111 V LGMDMManagerInternal: Create singleton instance
08-24 17:09:11.925  7037  7037 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-24 17:09:11.928  7037  7037 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-24 17:09:11.928  7037  7037 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-24 17:09:11.928  7037  7037 V SoundPool: doLoad: loading sample sampleID=1
08-24 17:09:11.928  7037  7137 V SoundPool: Start decode
08-24 17:09:11.928  7037  7137 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-24 17:09:11.929   316   316 V MediaPlayerService: decode(22, 10857164, 17813)
08-24 17:09:11.929   316   316 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-24 17:09:11.929   316   316 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-24 17:09:11.929   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-24 17:09:11.929   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-24 17:09:11.929   316   316 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-24 17:09:11.929   316   316 V MediaPlayerService: player type = 3
08-24 17:09:11.929   316   316 V AwesomePlayer: AwesomePlayer create()
08-24 17:09:11.930   316   316 V AwesomePlayer: reset_l() 
08-24 17:09:11.930   316   316 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:11.930   316   316 V AwesomePlayer: setAudioSink() 
08-24 17:09:11.930   316   316 V AwesomePlayer: reset_l() 
08-24 17:09:11.930   316   316 V AudioCache: notify(0xb16a6680, 8, 0, 0)
08-24 17:09:11.930   316   316 V AudioCache: ignored
08-24 17:09:11.930  7037  7037 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 17:09:11.930   316   316 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:11.930   316   316 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-24 17:09:11.930   316   316 V AwesomePlayer: setDataSource_l dataSource
08-24 17:09:11.930   316   316 V LGParserOSAL: SniffLGParser start
08-24 17:09:11.930   316   316 V LGParserOSAL: MainType:5, SubType=0
08-24 17:09:11.930   316   316 V LGParserOSAL: #### check Mime : application/ogg
08-24 17:09:11.930   316   316 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-24 17:09:11.931   316   316 E MediaExtractor: Use LGExtractor :application/ogg 
08-24 17:09:11.935  7037  7037 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-24 17:09:11.940  6774  6774 D UEI.SmartControl: QS Service created
,08-24 17:09:11.949  7037  7037 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 17:09:11.950  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-24 17:09:11.961  6774  6774 I UEI.SmartControl: Service initServices...
08-24 17:09:11.961  6774  6774 D UEI.SmartControl: QS start get config
08-24 17:09:11.968   316   316 V LGParserOSAL: supported mime: application/ogg
08-24 17:09:11.968   316   316 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-24 17:09:11.968   316   316 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-24 17:09:11.968   316   316 V AwesomePlayer: mBitrate = -1 bits/sec
08-24 17:09:11.968   316   316 V AwesomePlayer: AudioTrack Setting
08-24 17:09:11.968   316   316 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-24 17:09:11.968   316   316 V AwesomePlayer: setAudioSource() 
08-24 17:09:11.968   316   316 V MediaPlayerService: prepare
08-24 17:09:11.968   316   316 V AwesomePlayer: prepareAsync_l() 
08-24 17:09:11.968   316   316 V MediaPlayerService: wait for prepare
08-24 17:09:11.968   316  7138 V AwesomePlayer: onPrepareAsyncEvent() 
08-24 17:09:11.968   316  7138 V AwesomePlayer: initAudioDecoder() 
08-24 17:09:11.968   316  7138 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 17:09:11.968   316  7138 V AudioSystem: isOffloadSupported()
08-24 17:09:11.968   316  7138 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 17:09:11.968   316  7138 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 17:09:11.968   316  7138 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 17:09:11.968   316  7138 V AwesomePlayer: getUseOffload() = 0 
08-24 17:09:11.968   316  7138 V OMXCodec: OMXCodec::Create
08-24 17:09:11.968   316  7138 V OMXCodec: findMatchingCodecs()
08-24 17:09:11.968   316  7138 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-24 17:09:11.968   316  7138 V OMXCodec: matchingCodecs.size()=1
08-24 17:09:11.968   316  7138 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-24 17:09:11.970   316  7138 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-24 17:09:11.970   316  7138 V LGCodecAdapter: LG Codec Adapter start
08-24 17:09:11.970   316  7138 V OMXCodec: OMXCodec Createtor
08-24 17:09:11.970   316  7138 V OMXCodec: setComponentRole
08-24 17:09:11.970   316  7138 V OMXCodec: configureCodec protected=0
08-24 17:09:11.970   316  7138 V LGCodecAdapter: called getLGCodecSpecificData
,08-24 17:09:11.970   316  7138 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-24 17:09:11.970   316  7138 V LGCodecOSAL: Called LGconfigureCodecMETA
08-24 17:09:11.970   316  7138 V LGCodecOSAL: Called LGconfigureCodecMSG
08-24 17:09:11.970   316  7138 V LGCodecOSAL: Not support LGCodec
08-24 17:09:11.970   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 17:09:11.970   316  7138 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
,08-24 17:09:11.970   316  7138 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-24 17:09:11.970   316  7138 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-24 17:09:11.970   316  7138 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 17:09:11.971   316  7138 V AudioSystem: isOffloadSupported()
08-24 17:09:11.971   316  7138 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 17:09:11.971   316  7138 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-24 17:09:11.971   316  7138 V OMXCodec: init()
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-24 17:09:11.971   316  7138 V OMXCodec: allocateBuffers
08-24 17:09:11.971   316  7138 V OMXCodec: allocateBuffersOnPort portIndex=0
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-24 17:09:11.971   316  7138 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-24 17:09:11.971   316  7138 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb0b0 on output port
08-24 17:09:11.971   316  7138 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 17:09:11.971   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-24 17:09:11.971   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 17:09:11.971  7111  7111 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:11.971   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-24 17:09:11.972   316  7138 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 17:09:11.973  7037  7037 V LGMDMManager: Create singleton instance
08-24 17:09:11.973  7111  7111 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:11.974  7111  7111 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 17:09:11.974  7111  7111 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 17:09:11.974  7111  7111 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:11.974  7111  7111 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-24 17:09:11.977   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-24 17:09:11.977   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-24 17:09:11.977   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-24 17:09:11.978   316  7138 V OMXCodec: init() mAsyncCompletion wait free! 
08-24 17:09:11.978   316  7138 V AwesomePlayer: finishAsyncPrepare_l() 
08-24 17:09:11.978   316  7138 V AudioCache: notify(0xb16a6680, 5, 0, 0)
08-24 17:09:11.978   316  7138 V AudioCache: ignored
08-24 17:09:11.978   316  7138 V AudioCache: notify(0xb16a6680, 1, 0, 0)
08-24 17:09:11.978   316  7138 V AudioCache: prepared
08-24 17:09:11.978   316   316 V AudioCache: wait - success
08-24 17:09:11.978   316   316 V MediaPlayerService: start
08-24 17:09:11.978   316   316 V AwesomePlayer: play_l() 
08-24 17:09:11.978   316   316 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-24 17:09:11.978   316   316 V AwesomePlayer: createAudioPlayer_l
08-24 17:09:11.978   316   316 V AwesomePlayer: seekAudioIfNecessary_l() 
08-24 17:09:11.978   316   316 V AwesomePlayer: startAudioPlayer_l() 
08-24 17:09:11.978   316   316 D AudioPlayer: start of Playback, useOffload 0
08-24 17:09:11.978   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 17:09:11.978   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782256
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat,()
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-24 17:09:11.979   316  7140 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 17:09:11.979   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 17:09:11.980   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-24 17:09:11.980   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-24 17:09:11.980   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-24 17:09:11.980   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on output port
08-24 17:09:11.980   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-24 17:09:11.980   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-24 17:09:11.980   316   316 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-24 17:09:11.980   316   316 V AudioCache: notify(0xb16a6680, 6, 0, 0)
08-24 17:09:11.980   316   316 V AudioCache: ignored
08-24 17:09:11.981   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.981   316  7142 V AudioCache: memcpy(0xaf0f9000, 0xb16f3000, 4096)
08-24 17:09:11.981   316   316 V MediaPlayerService: wait for playback complete
08-24 17:09:11.981  7056  7056 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-24 17:09:11.982   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.982   316  7142 V AudioCache: memcpy(0xaf0fa000, 0xb16f3000, 4096)
08-24 17:09:11.982   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.982   316  7142 V AudioCache: memcpy(0xaf0fb000, 0xb16f3000, 4096)
08-24 17:09:11.982   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.982   316  7142 V AudioCache: memcpy(0xaf0fc000, 0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: memcpy(0xaf0fd000, 0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: memcpy(0xaf0fe000, 0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: memcpy(0xaf0ff000, 0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.983   316  7142 V AudioCache: memcpy(0xaf100000, 0xb16f3000, 4096)
08-24 17:09:11.984   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.984   316  7142 V AudioCache: memcpy(0xaf101000, 0xb16f3000, 4096)
,08-24 17:09:11.984   316  7142 V AudioCache: write(0xb16f3000, 4096),
,08-24 17:09:11.984   316  7142 V AudioCache: memcpy(0xaf102000, 0xb16f3000, 4096)
08-24 17:09:11.984   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.984   316  7142 V AudioCache: memcpy(0xaf103000, 0xb16f3000, 4096)
08-24 17:09:11.985   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.985   316  7142 V AudioCache: memcpy(0xaf104000, 0xb16f3000, 4096)
08-24 17:09:11.985   316  7142 V AudioCache: write(0xb16f3000, 4096)
,08-24 17:09:11.985   316  7142 V AudioCache: memcpy(0xaf105000, 0xb16f3000, 4096)
08-24 17:09:11.985   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.985   316  7142 V AudioCache: memcpy(0xaf106000, 0xb16f3000, 4096)
08-24 17:09:11.985   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.985   316  7142 V AudioCache: memcpy(0xaf107000, 0xb16f3000, 4096)
08-24 17:09:11.986   316  7142 V AudioCache: write(0xb16f3000, 4096)
,08-24 17:09:11.986   316  7142 V AudioCache: memcpy(0xaf108000, 0xb16f3000, 4096)
08-24 17:09:11.986   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.986   316  7142 V AudioCache: memcpy(0xaf109000, 0xb16f3000, 4096)
08-24 17:09:11.986   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.986   316  7142 V AudioCache: memcpy(0xaf10a000, 0xb16f3000, 4096)
,08-24 17:09:11.987   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.987   316  7142 V AudioCache: memcpy(0xaf10b000, 0xb16f3000, 4096)
08-24 17:09:11.987   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.987   316  7142 V AudioCache: memcpy(0xaf10c000, 0xb16f3000, 4096)
08-24 17:09:11.987   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.987   316  7142 V AudioCache: memcpy(0xaf10d000, 0xb16f3000, 4096)
,08-24 17:09:11.987   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.988   316  7142 V AudioCache: memcpy(0xaf10e000, 0xb16f3000, 4096)
08-24 17:09:11.988   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.988   316  7142 V AudioCache: memcpy(0xaf10f000, 0xb16f3000, 4096)
08-24 17:09:11.988   316  7142 V AudioCache: write(0xb16f3000, 4096)
,08-24 17:09:11.988   316  7142 V AudioCache: memcpy(0xaf110000, 0xb16f3000, 4096)
08-24 17:09:11.988   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.988   316  7142 V AudioCache: memcpy(0xaf111000, 0xb16f3000, 4096)
08-24 17:09:11.989   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.989   316  7142 V AudioCache: memcpy(0xaf112000, 0xb16f3000, 4096)
,08-24 17:09:11.989   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.989   316  7142 V AudioCache: memcpy(0xaf113000, 0xb16f3000, 4096)
08-24 17:09:11.989   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.989   316  7142 V AudioCache: memcpy(0xaf114000, 0xb16f3000, 4096)
08-24 17:09:11.990   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.990   316  7142 V AudioCache: memcpy(0xaf115000, 0xb16f3000, 4096)
,08-24 17:09:11.990   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.990   316  7142 V AudioCache: memcpy(0xaf116000, 0xb16f3000, 4096)
08-24 17:09:11.990   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.990   316  7142 V AudioCache: memcpy(0xaf117000, 0xb16f3000, 4096)
08-24 17:09:11.991   316  7142 V AudioCache: write(0xb16f3000, 4096)
,08-24 17:09:11.991   316  7142 V AudioCache: memcpy(0xaf118000, 0xb16f3000, 4096)
08-24 17:09:11.991   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.991   316  7142 V AudioCache: memcpy(0xaf119000, 0xb16f3000, 4096)
08-24 17:09:11.991   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.991   316  7142 V AudioCache: memcpy(0xaf11a000, 0xb16f3000, 4096)
08-24 17:09:11.992   316  7142 V AudioCache: write(0xb16f3000, 4096)
,08-24 17:09:11.992   316  7142 V AudioCache: memcpy(0xaf11b000, 0xb16f3000, 4096)
08-24 17:09:11.992   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.992   316  7142 V AudioCache: memcpy(0xaf11c000, 0xb16f3000, 4096)
08-24 17:09:11.992   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.992   316  7142 V AudioCache: memcpy(0xaf11d000, 0xb16f3000, 4096)
,08-24 17:09:11.993   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.993   316  7142 V AudioCache: memcpy(0xaf11e000, 0xb16f3000, 4096)
08-24 17:09:11.993   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.993   316  7142 V AudioCache: memcpy(0xaf11f000, 0xb16f3000, 4096)
08-24 17:09:11.993   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.993   316  7142 V AudioCache: memcpy(0xaf120000, 0xb16f3000, 4096)
,08-24 17:09:11.993   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.993   316  7142 V AudioCache: memcpy(0xaf121000, 0xb16f3000, 4096)
08-24 17:09:11.994   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.994   316  7142 V AudioCache: memcpy(0xaf122000, 0xb16f3000, 4096)
08-24 17:09:11.994   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.994   316  7142 V AudioCache: memcpy(0xaf123000, 0xb16f3000, 4096),
08-24 17:09:11.994   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.994   316  7142 V AudioCache: memcpy(0xaf124000, 0xb16f3000, 4096)
08-24 17:09:11.995   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.995   316  7142 V AudioCache: memcpy(0xaf125000, 0xb16f3000, 4096)
08-24 17:09:11.995   316  7142 V AudioCache: write(0xb16f3000, 4096)
,08-24 17:09:11.995   316  7142 V AudioCache: memcpy(0xaf126000, 0xb16f3000, 4096)
08-24 17:09:11.995   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.995   316  7142 V AudioCache: memcpy(0xaf127000, 0xb16f3000, 4096)
08-24 17:09:11.996   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.996   316  7142 V AudioCache: memcpy(0xaf128000, 0xb16f3000, 4096)
08-24 17:09:11.996   316  7142 V AudioCache: write(0xb16f3000, 4096),
08-24 17:09:11.996   316  7142 V AudioCache: memcpy(0xaf129000, 0xb16f3000, 4096)
08-24 17:09:11.996   316  7142 V AudioCache: write(0xb16f3000, 4096)
08-24 17:09:11.996   316  7142 V AudioCache: memcpy(0xaf12a000, 0xb16f3000, 4096)
,08-24 17:09:11.996   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-24 17:09:11.996   316  7142 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-24 17:09:11.996   316  7142 V AwesomePlayer: postAudioEOS() 
08-24 17:09:11.996   316  7142 V AudioCache: write(0xb16f3000, 280)
08-24 17:09:11.996   316  7142 V AudioCache: memcpy(0xaf12b000, 0xb16f3000, 280)
08-24 17:09:11.998   316  7138 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 ,
08-24 17:09:11.998   316  7138 V AwesomePlayer: onStreamDone
08-24 17:09:11.998   316  7138 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-24 17:09:11.998   316  7138 V AudioCache: notify(0xb16a6680, 2, 0, 0)
08-24 17:09:11.998   316  7138 V AudioCache: playback complete
,08-24 17:09:11.998   316  7138 V AwesomePlayer: pause_l() 
,08-24 17:09:11.998   316  7138 V AudioCache: notify(0xb16a6680, 7, 0, 0)
,08-24 17:09:11.998   316  7138 V AudioCache: ignored
08-24 17:09:11.998   316  7138 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:11.998   316  7138 D AudioPlayer: Pause Playback at 1068125
08-24 17:09:11.998   316   316 V AudioCache: wait - success
08-24 17:09:11.998   316   316 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-24 17:09:11.999   316   316 V AwesomePlayer: reset_l() 
08-24 17:09:11.999   316   316 V AudioCache: notify(0xb16a6680, 8, 0, 0)
08-24 17:09:11.999   316   316 V AudioCache: ignored
08-24 17:09:11.999   316   316 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:11.999   316   316 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-24 17:09:11.999   316  7140 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-24 17:09:11.999   316   316 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-24 17:09:12.000   316   316 ,V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-24 17:09:12.000   316   316 D AudioPlayer: AudioPlayer releasing audio source
08-24 17:09:12.000   316   316 D AudioPlayer: AudioPlayer done releasing audio source
08-24 17:09:12.000   316   316 V AwesomePlayer: reset_l() 
08-24 17:09:12.000   316   316 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:12.000   316   316 V AwesomePlayer: ~AwesomePlayer call
08-24 17:09:12.000   316   316 V AwesomePlayer: reset_l() 
08-24 17:09:12.000   316   316 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:12.000  7037  7137 V SoundPool: close(31)
08-24 17:09:12.000  7037  7137 V SoundPool: pointer = 0x9fe48000, size = 205080, sampleRate = 48000, numChannels = 2
08-24 17:09:12.035  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 17:09:12.035  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-24 17:09:12.037  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1961
,08-24 17:09:12.240  6774  6774 I UEI.SmartControl: Supports setup maps: true
,08-24 17:09:12.243  6774  6774 D UEI.SmartControl: QS start statue = true Error code = 0
08-24 17:09:12.243  6774  6774 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-24 17:09:12.243  6774  6774 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-24 17:09:12.243  6774  6774 I UEI.SmartControl: ### init IR Blaster...
08-24 17:09:12.246  6774  6774 D serial_port: Configuring serial port
08-24 17:09:12.247  6774  6774 E UEI.SmartControl: UEIBLaster setting for 616
08-24 17:09:12.247  6774  6774 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 17:09:12.247  6774  6774 I UEI.SmartControl: configuring settings for MAXQ616
08-24 17:09:12.247  6774  6774 I UEI.SmartControl: Get version...
08-24 17:09:12.266  6774  7143 D UEI.SmartControl: serial port data available: 21
,08-24 17:09:12.292  6774  6774 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 17:09:12.292  6774  6774 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 17:09:12.292  6774  6774 I UEI.SmartControl: QS saving settings...
,08-24 17:09:12.295  6774  6774 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 17:09:12.312  6774  7143 D UEI.SmartControl: serial port data available: 4
,08-24 17:09:12.348  6774  6774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-24 17:09:12.353  6774  6774 E UEI.SmartControl: Services init done
08-24 17:09:12.353  6774  6774 D UEI.SmartControl: QS Service init finished
08-24 17:09:12.355  6774  6774 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 17:09:12.355  6774  6774 D UEI.SmartControl: QS Service version code: 201091
08-24 17:09:12.357  6774  6774 D UEI.SmartControl: Service requested: Control
08-24 17:09:12.363  6774  7152 I UEI.SmartControl: Device manager: loading config....
08-24 17:09:12.363  7037  7037 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-24 17:09:12.364  6774  7152 D UEI.SmartControl: ----------- loading internal config...
,08-24 17:09:12.366  6774  6789 I UEI.SmartControl: ------ IControl API: 11
08-24 17:09:12.366  6774  6789 D UEI.SmartControl: File observer start...
,08-24 17:09:12.369  6774  7152 E UEI.SmartControl: Loading SETTINGS...
08-24 17:09:12.371  6774  6789 E UEI.SmartControl: IR Port is disabled: false
08-24 17:09:12.371  6774  6789 D UEI.SmartControl: Starting file observer...
08-24 17:09:12.372  6774  6789 I UEI.SmartControl: Registering callback...
08-24 17:09:12.373  6774  6790 I UEI.SmartControl: ------ IControl API: 19
08-24 17:09:12.374  6774  6790 I UEI.SmartControl: Registering Services Ready callback...
08-24 17:09:12.374  6774  7152 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 17:09:12.374  6774  6774 D UEI.SmartControl: Internal service binding...
08-24 17:09:12.383  6774  7151 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 17:09:12.383  6774  7151 D UEI.SmartControl: -----service ready thread exits
08-24 17:09:12.384  7037  7052 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-24 17:09:12.385  7037  7135 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-24 17:09:12.385  7037  7135 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-24 17:09:12.386  7037  7037 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-24 17:09:12.386  7037  7037 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-24 17:09:12.387  6774  6789 I UEI.SmartControl: ------ IControl API: 8
08-24 17:09:12.388  7037  7037 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-24 17:09:12.389  7037  7037 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-24 17:09:12.389  7037  7037 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-24 17:09:12.389  7037  7037 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-24 17:09:12.390  7037  7037 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-24 17:09:12.390  7037  7037 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-24 17:09:12.392  7037  7037 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-24 17:09:12.394  7037  7037 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 17:09:12.395  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-24 17:09:12.398  7037  7037 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 17:09:12.398  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-24 17:09:12.399  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-24 17:09:12.400  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-24 17:09:12.400  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-24 17:09:12.401  7037  7037 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472051352401]
08-24 17:09:12.404  7037  7037 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-24 17:09:12.407  1038  1591 I ActivityManager: Killing 6561:com.android.gallery3d/u0a27 (adj 15): empty #17
08-24 17:09:12.424  7037  7154 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-24 17:09:12.491  1038  1591 I ActivityManager: Killing 6530:com.lge.email/u0a23 (adj 15): empty #18
,08-24 17:09:12.549  1038  2020 W libprocessgroup: failed to open /acct/uid_10027/pid_6561/cgroup.procs: No such file or directory
,08-24 17:09:12.560  1038  1762 W libprocessgroup: failed to open /acct/uid_10023/pid_6530/cgroup.procs: No such file or directory
08-24 17:09:12.562  7037  7037 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-24 17:09:12.564  7037  7037 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-24 17:09:12.565  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-24 17:09:12.566  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-24 17:09:12.567  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-24 17:09:12.568  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-24 17:09:12.569  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-24 17:09:12.580  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-24 17:09:13.379  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:13.399  1038  1563 D WifiServiceImplEx: setWifiEnabled: true pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-24 17:09:13.405  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-24 17:09:13.412  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:13.414  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:13.424  1038  1563 D WifiService: setWifiEnabled: true pid=6862, uid=10118
08-24 17:09:13.424  1038  1563 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 17:09:13.427  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:13.435  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-24 17:09:13.444  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:13.448  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:13.450  1038  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:13.451  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 17:09:13.457  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:13.457  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 17:09:13.457  1038  1038 D Ulp_jni : JNI:system_update. Event-4
,08-24 17:09:13.461  1038  1379 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 17:09:13.461  1038  1379 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 17:09:13.464  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 17:09:13.464  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 17:09:13.464  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-24 17:09:13.464  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 17:09:13.464  1038  1379 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-24 17:09:13.464  1038  1379 E WifiHW  : unknown target_country: EU , set to default
08-24 17:09:13.464  1038  1379 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 17:09:13.464  1038  1379 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 17:09:13.464  1038  1379 I WifiUtil: gEnableBmps=1
08-24 17:09:13.476  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 17:09:13.486  6418  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 17:09:13.488  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 17:09:13.521  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:13.580  1038  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:13.603  1038  1563 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7173 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-24 17:09:13.607  1038  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:13.608  1038  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 17:09:13.684  7173  7173 I AppUp4:AppBoxCP: onCreate
,08-24 17:09:13.685  7173  7173 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-24 17:09:13.695  7173  7173 I AppUp4:DB:  setFingerPrint start
08-24 17:09:13.695  7173  7173 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-24 17:09:13.704  7173  7173 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-24 17:09:13.704  7173  7173 I AppUp4:DB:  SDK version = 21
08-24 17:09:13.704  7173  7173 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-24 17:09:13.706  7173  7173 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-24 17:09:13.709  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 17:09:13.709  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:13.712  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 17:09:13.712  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 17:09:13.721  7173  7173 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 17:09:13.763  7173  7173 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:13.763  7173  7173 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 17:09:13.773  7173  7173 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31461ad7
08-24 17:09:13.773  7173  7173 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 17:09:13.773  7173  7173 D AppUp4:CustFacade: isPhone : true
08-24 17:09:13.775  7173  7173 D AppUp4:CustModeStarterReceiver: begin check event
08-24 17:09:13.776  7173  7173 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-24 17:09:13.777  7173  7173 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-24 17:09:13.778  7173  7193 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-24 17:09:13.778  7173  7193 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-24 17:09:13.778  7173  7193 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-24 17:09:13.781  1038  1910 I ActivityManager: Killing 6620:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-24 17:09:13.823  1038  1726 W libprocessgroup: failed to open /acct/uid_10061/pid_6620/cgroup.procs: No such file or directory
08-24 17:09:13.823  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:13.823  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-24 17:09:13.826  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:13.828  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:13.840  4779  7196 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:13.843  4779  7197 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:13.843  4779  7197 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 17:09:13.931  1038  1909 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7201 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 17:09:13.957   352   352 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 26.735ms
,08-24 17:09:13.981   352   352 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.875ms
08-24 17:09:14.001   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 19.322ms
,08-24 17:09:14.009  7201  7201 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:14.010  7201  7201 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:14.012  7201  7201 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 17:09:14.012  7201  7201 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 17:09:14.106  7201  7201 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-24 17:09:14.121  7201  7201 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-24 17:09:14.167  7201  7201 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 17:09:14.223  7201  7201 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 17:09:14.223  7201  7201 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 17:09:14.241  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:09:14.241  1038  1120 D Tethering: InitialState.processMessage what=4
08-24 17:09:14.241  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-24 17:09:14.250   312   896 D SoftapController: Softap fwReload - Ok
08-24 17:09:14.251  1038  1379 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (781ms)
,08-24 17:09:14.261   312   896 D CommandListener: Setting iface cfg
08-24 17:09:14.261   312   896 D CommandListener: Trying to bring down wlan0
08-24 17:09:14.262   312   896 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:09:14.263  1038  1379 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-24 17:09:14.272  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:14.272  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:14.272  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-24 17:09:14.269  7230  7230 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:14.269  7230  7230 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 17:09:14.284  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:14.285  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-24 17:09:14.287  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:14.288  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:14.288  1038  1379 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-24 17:09:14.288  1038  1379 D WifiMonitor: connecting to supplicant
08-24 17:09:14.313  7230  7230 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 17:09:14.355  7230  7230 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 17:09:14.355  7230  7230 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-24 17:09:14.425  7201  7201 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-24 17:09:14.458  3285  3285 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 17:09:14.458  3285  3285 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:14.458  3285  3285 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-24 17:09:14.459  7230  7230 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 17:09:14.465  7201  7201 I HubEmail: JNI_OnLoad()
08-24 17:09:14.465  7201  7201 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 17:09:14.465  7201  7201 I HubEmail: registerNatives()
08-24 17:09:14.465  7201  7201 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 17:09:14.465  7201  7201 I HubEmail: registerNativeMethods()
08-24 17:09:14.465  7201  7201 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-24 17:09:14.465  7201  7201 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-24 17:09:14.483  7230  7230 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-24 17:09:14.489  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-24 17:09:14.491  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-24 17:09:14.491  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-24 17:09:14.491  1038  7248 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-24 17:09:14.492  1038  7248 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 17:09:14.492  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-24 17:09:14.492  1038  1379 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-24 17:09:14.493  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:14.493  1038  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:14.493  1038  1379 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-24 17:09:14.493  1038  1379 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-24 17:09:14.494  1038  1379 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-24 17:09:14.494  1038  1379 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-24 17:09:14.494  1038  1379 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-24 17:09:14.503  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-24 17:09:14.503  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 17:09:14.503  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 17:09:14.503  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-24 17:09:14.503  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 17:09:14.503  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 17:09:14.503  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-24 17:09:14.533  1038  1726 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7250 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-24 17:09:14.540  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:14.540  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:14.540  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 17:09:14.542  1038  1379 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 17:09:14.542  1038  1379 D WifiNative-wlan0: SET update_config 1: returned true
08-24 17:09:14.542  1038  1379 D WifiConfigStore: Loading config and enabling all networks 
08-24 17:09:14.542  1038  1379 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-24 17:09:14.543  1038  1379 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-24 17:09:14.546  1928  1928 D WfdService: Waiting for WifiP2p enabling
08-24 17:09:14.549  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:09:14.549  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:14.549  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:14.549  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:09:14.549  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:14.549  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:09:14.549  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:14.550  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:14.550  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:14.550  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-24 17:09:14.551  1038  1423 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-24 17:09:14.551  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:14.551  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:14.551  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:14.552  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:14.553  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:14.555  7076  7244 W FormManager: Network not available. Please check & try again.
08-24 17:09:14.556  7201  7247 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:14.558  7076  7246 V FormManager: Network unavailable.
08-24 17:09:14.561  7076  7246 V FormManager: Network unavailable.
08-24 17:09:14.562  1038  1379 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-24 17:09:14.572  1038  1054 I ActivityManager: Killing 6674:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-24 17:09:14.581  1038  1379 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 17:09:14.582  1038  1379 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 17:09:14.601  1038  1379 D WifiStateMachine: enableVerboseLogging : level 2
08-24 17:09:14.601  1038  1379 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 17:09:14.603  1038  1379 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-24 17:09:14.603  1038  1379 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-24 17:09:14.603  1038  1379 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 17:09:14.604  1038  1379 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 17:09:14.604  1038  1379 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 17:09:14.604  1038  1379 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-24 17:09:14.605  1038  1379 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 17:09:14.605  1038  1379 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-24 17:09:14.605  1038  1910 W libprocessgroup: failed to open /acct/uid_10080/pid_6674/cgroup.procs: No such file or directory
08-24 17:09:14.605  1038  1379 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 17:09:14.605  1038  1379 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 17:09:14.606  1038  1379 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-24 17:09:14.606  1038  1379 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 17:09:14.606  1038  1379 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 17:09:14.608  1038  1379 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 17:09:14.608  1038  1379 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 17:09:14.608  1038  1379 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 17:09:14.608  1038  1379 D WifiNative-HAL: Setting external_sim to 1
08-24 17:09:14.608  1038  1379 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-24 17:09:14.609  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-24 17:09:14.609  1928  2205 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 17:09:14.609  1928  2205 D WfdsService: Set the WFDS Monitor: true
08-24 17:09:14.609  1038  1379 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 17:09:14.609  1928  2205 D WfdsMonitor: WfdsMonitorThread create
08-24 17:09:14.609  1038  1379 I WifiNative-HAL: startHal
08-24 17:09:14.609  1038  1379 D wifi    : setting scan oui 0x9536c4c0
08-24 17:09:14.609  1928  2205 D WfdsMonitor: WFDS Monitor is created and started
08-24 17:09:14.609  1928  2205 D WfdsService: WiFi: Supplicant connection re-established
08-24 17:09:14.609  1038  1379 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 17:09:14.609  1038  1379 I WifiNative-HAL: startHal
08-24 17:09:14.609  1038  1379 D wifi    : setting scan oui 0x9536c4c0
08-24 17:09:14.610  1038  1379 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-24 17:09:14.610  1038  1379 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 17:09:14.610  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 17:09:14.611  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-24 17:09:14.611  1928  7268 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 17:09:14.611  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 17:09:14.611  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 17:09:14.611  1928  7268 E CtrlSupplicant: Succeed to open control connection
08-24 17:09:14.611  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 17:09:14.611  1928  7268 E CtrlSupplicant: Succeed to open monitor connection
08-24 17:09:14.612  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 17:09:14.612  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 17:09:14.612  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 17:09:14.612  1928  7268 D WfdsMonitor: Supplicant connection established
08-24 17:09:14.612  1928  2205 D WfdsService: Connected to the supplicant for wfds
08-24 17:09:14.612  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 17:09:14.612  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 17:09:14.612  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_dr,iver_cmd RXFILTER-START
08-24 17:09:14.613  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 17:09:14.613  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 17:09:14.613  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 17:09:14.615  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 17:09:14.615  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-24 17:09:14.615  7230  7230 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 17:09:14.615  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-24 17:09:14.616  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 17:09:14.616  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 17:09:14.616  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-24 17:09:14.617  1038  1379 E WifiNative: : [191,194,414 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 17:09:14.617  1038  1379 D WifiNative-wlan0: doBoolean: RECONNECT
08-24 17:09:14.618  1038  1379 D WifiNative-wlan0: RECONNECT: returned true
,08-24 17:09:14.618  1038  1379 D WifiNative-wlan0: doString: [STATUS]
08-24 17:09:14.618  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 17:09:14.618  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 17:09:14.619  1038  1379 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 17:09:14.619  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 17:09:14.619  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:14.620  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.620  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 17:09:14.620  1038  1038 D RttService: SCAN_AVAILABLE : 3
08-24 17:09:14.621  1038  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.621  1038  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.621  1038  1543 I WifiNative-HAL: startHal
08-24 17:09:14.621  1038  1543 D wifi    : getting scan capabilities on interface[1] = 0x9536c4c0
08-24 17:09:14.621  1038  1543 D wifi    : failed to get capabilities : -3
08-24 17:09:14.621  1038  1379 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-24 17:09:14.621  1038  1543 E WifiScanningService: could not get scan capabilities
08-24 17:09:14.622  1038  1379 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 17:09:14.622  1038  1379 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 17:09:14.622   312   896 D CommandListener: Setting iface cfg
08-24 17:09:14.622   312   896 D CommandListener: Trying to bring up p2p0
08-24 17:09:14.623  1038  1379 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 17:09:14.623  1038  1377 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 17:09:14.623  1038  1377 D LGWifiP2pService: P2pEnablingState
08-24 17:09:14.623  1038  1377 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.623  1038  1377 D LGWifiP2pService: P2p socket connection successful
08-24 17:09:14.623  1038  1377 D LGWifiP2pService: P2pEnabledState
08-24 17:09:14.623  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=191201  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 17:09:14.623  1038  1377 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 17:09:14.625  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 17:09:14.625  1928  1928 D WfdsService: WifiP2pState is changed : true
08-24 17:09:14.625  1928  2205 D WfdsService: Receive the WFDS_ENABLE Method
08-24 17:09:14.625  1928  2205 D WfdsService: Set the WFDS Monitor: true
08-24 17:09:14.625  1928  2205 D WfdsService: Connected to the supplicant for wfds
08-24 17:09:14.625  1928  2205 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 17:09:14.625  7230  7230 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 17:09:14.625  1928  2205 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-24 17:09:14.625  7230  7230 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-24 17:09:14.626  1038  1377 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 17:09:14.626  1928  2205 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-24 17:09:14.626  1928  2205 D WfdsService: selectPreferredScanChannel [36]
08-24 17:09:14.626  1928  2205 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-24 17:09:14.626  1038  1377 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 17:09:14.627 , 1038  1377 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 17:09:14.627  1038  1377 D WifiNative-p2p0: SET device_name G3: returned true
08-24 17:09:14.627  1038  1377 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 17:09:14.627  1038  1377 D LGWifiP2pService: before postfix = G3
08-24 17:09:14.627  1038  1377 D WifiServerServiceExt: postfix byte check : 2
08-24 17:09:14.627  1038  1377 D LGWifiP2pService: after postfix = G3
08-24 17:09:14.627  1038  1377 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 17:09:14.628  1038  1377 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 17:09:14.628  1038  1377 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 17:09:14.628  1038  1377 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 17:09:14.628  1038  1377 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-24 17:09:14.629  1038  1377 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 17:09:14.629  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-24 17:09:14.630  1038  1377 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 17:09:14.630  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 17:09:14.630  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-24 17:09:14.632  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-24 17:09:14.632  1928  1928 D WfdsService: isConnected: false
08-24 17:09:14.633  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:14.633  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:14.634  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:14.634  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:14.634  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 17:09:14.634  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:14.635  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=191212  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-24 17:09:14.635  1038  1379 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 17:09:14.636  1038  1379 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-24 17:09:14.637  1038  1379 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 17:09:14.637  1038  1379 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 17:09:14.637  7230  7230 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 17:09:14.637  1038  1377 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-24 17:09:14.637  1038  1377 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 17:09:14.638  1038  1377 D WifiNative-p2p0: P2P_FLUSH: returned true
08-24 17:09:14.638  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 17:09:14.638  1038  1377 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-24 17:09:14.638  1038  1377 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 17:09:14.638  1038  1377 D WifiNative-p2p0:    returned OK
08-24 17:09:14.639  1038  1377 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-24 17:09:14.639  1038  1377 D WifiNative-p2p0: SAVE_CONFIG: returned false
08-24 17:09:14.639  1038  1377 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 17:09:14.640  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 17:09:14.640  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 17:09:14.640  1038  1377 D LGWifiP2pService: InactiveState
08-24 17:09:14.640  1928  1928 D WfdsService: Update P2p Interface State: 3
08-24 17:09:14.640  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.640  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.640  1038  1377 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-24 17:09:14.650  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 17:09:14.650  1038  1379 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 17:09:14.651  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.651  1038  7248 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 17:09:14.651  1038  7248 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.651  1038  1379 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-24 17:09:14.651  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.651  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.651  1928  7268 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 17:09:14.651  7230  7230 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 17:09:14.651  1038  1379 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 17:09:14.651  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-24 17:09:14.652  1038  1379 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 17:09:14.652  1038  1379 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 17:09:14.652  7230  7230 E wpa_supplicant: disconnect_rssi_lvl: -100
08-24 17:09:14.652  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.653  1038  7248 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.653  1038  1379 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 17:09:14.653  1038  7248 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.653  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.653  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.653  1038  7248 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.653  1038  7248 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.653  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.653  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.653  1038  1379 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-24 17:09:14.653  1038  1377 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 17:09:14.653  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-24 17:09:14.653  1038  1377 D LGWifiP2pService: InactiveState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.653  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: DefaultState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1928  7268 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: InactiveState{ when=-14ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1928  7268 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: DefaultState{ when=-15ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  1038  1377 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.654  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.655  7230  7230 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 17:09:14.656  1038  7248 D WifiMonitor: Event [IFNAME=w,lan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 17:09:14.656  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.656  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.656  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.656  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:14.656  1038  7248 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.656  1038  7248 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.656  1038  1379 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 17:09:14.656  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.656  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.656  1928  7268 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.656  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.656  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:14.656  1038  1038 E WifiServerServiceExt: No p2p device connected
08-24 17:09:14.657  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.657  1928  2205 W WfdsService: DefaultState - msg [9441285] is not handled
08-24 17:09:14.657  1928  7268 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.657  1038  1379 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 17:09:14.657  1038  1379 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 17:09:14.658  1038  7248 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:14.658  1038  7248 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.658  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:14.658  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-24 17:09:14.658  1038  1379 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 17:09:14.658  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-24 17:09:14.658  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 17:09:14.658  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:14.659  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 17:09:14.659  1038  1379 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 17:09:14.659  1038  1379 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-24 17:09:14.659  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:14.660  1038  7248 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:14.660  1038  1379 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 17:09:14.660  1038  1379 D WifiNative-wlan0: doBoolean: SCAN
08-24 17:09:14.660  1038  7248 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:14.660  1038  1379 D WifiNative-wlan0: SCAN: returned false
,08-24 17:09:14.661  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=191239  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 17:09:14.662  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=191240  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 17:09:14.663  1038  1379 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:14.664  1038  1379 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-24 17:09:14.665  1038  1379 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:14.666  1038  1379 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:14.666  1038  1379 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:14.669  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:14.669  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:14.669  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 17:09:14.669  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:14.669  1038  1038 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 17:09:14.670  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:14.670  1038  1038 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 17:09:14.670  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:14.670  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:14.673  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:14.693  7250  7250 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:14.693  7250  7250 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 17:09:14.695  7250  7250 D PhoneMonitor: Register our PhoneStateListener
08-24 17:09:14.787  1038  1762 I art     : Explicit concurrent mark sweep GC freed 77353(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.365ms total 84.674ms
,08-24 17:09:14.793  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 17:09:14.795  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-24 17:09:14.828  7250  7250 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-24 17:09:14.829  1038  1591 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7272 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:09:14.829  7250  7250 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-24 17:09:14.830  1038  1591 I ActivityManager: Killing 6702:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-24 17:09:14.831  7250  7250 D TelephonyAutoProfiling: [parse] Load xml
08-24 17:09:14.834  7250  7250 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-24 17:09:14.834  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-24 17:09:14.834  7250  7250 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-24 17:09:14.842  7250  7250 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-24 17:09:14.891  1038  1910 W libprocessgroup: failed to open /acct/uid_10097/pid_6702/cgroup.procs: No such file or directory
,08-24 17:09:15.122  1038  1591 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7293 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-24 17:09:15.123  1038  1591 I ActivityManager: Killing 6732:com.lge.eula/1000 (adj 15): empty #17
08-24 17:09:15.140  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-24 17:09:15.141  1038  7248 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 17:09:15.141  7230  7230 E wpa_supplicant: USIM:  scard_init function
08-24 17:09:15.141  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 17:09:15.141  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-24 17:09:15.141  1038  7248 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 17:09:15.141  7230  7230 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-24 17:09:15.142  1038  1379 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 17:09:15.142  1038  1379 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 17:09:15.143  1038  1379 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 17:09:15.143  1038  1379 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-24 17:09:15.143  1038  1379 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 17:09:15.144  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 17:09:15.144  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-24 17:09:15.182  1038  1964 W libprocessgroup: failed to open /acct/uid_1000/pid_6732/cgroup.procs: No such file or directory
08-24 17:09:15.182  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=191760  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-24 17:09:15.193  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.194  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:15.194  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.194  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.194  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 17:09:15.194  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=191772  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-24 17:09:15.197  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:15.197  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-24 17:09:15.198  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.287  7230  7230 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 17:09:15.292  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 17:09:15.292  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 17:09:15.293  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 17:09:15.293  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 17:09:15.293  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:15.293  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:15.294  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=191872  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-24 17:09:15.295  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=191872  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-24 17:09:15.295  1038  1379 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191873
08-24 17:09:15.296  1038  1379 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191874
08-24 17:09:15.296  1038  1379 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191874
08-24 17:09:15.297  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191875
08-24 17:09:15.297  1038  1379 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=191875
08-24 17:09:15.298  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=191875  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 17:09:15.298   352   352 I art     : Background concurrent mark sweep GC freed 792(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 5.040ms total 41.662ms
08-24 17:09:15.308  7230  7230 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:09:15.309  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 17:09:15.314  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:15.314  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-24 17:09:15.315  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 17:09:15.315  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:09:15.315  1038  7248 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:09:15.315  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 17:09:15.315  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 17:09:15.315  1038  7248 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 17:09:15.316  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:15.316  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:15.320  1038  2021 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7310 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:09:15.321  1038  2021 I ActivityManager: Killing 5607:com.lge.bnr/1000 (adj 15): empty #17
08-24 17:09:15.361  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.361  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.362  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:09:15.484  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 17:09:15.485  1038  2039 W libprocessgroup: failed to open /acct/uid_1000/pid_5607/cgroup.procs: No such file or directory
08-24 17:09:15.505  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=192082  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-24 17:09:15.508  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.508  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:15.508  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.508  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.508  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 17:09:15.512  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.520  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.520  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.520  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-24 17:09:15.522  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:15.522  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-24 17:09:15.522  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=192100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 17:09:15.523  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=192100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-24 17:09:15.523  1038  1379 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=192101
08-24 17:09:15.524  1038  1379 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=192102
08-24 17:09:15.524  1038  1379 D WifiNative-wlan0: doString: [STATUS]
08-24 17:09:15.525  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:15.525  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:15.525  1038  1379 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 17:09:15.527  1038  1379 I WifiServiceExtension: setVHTCapabilityType  : false
08-24 17:09:15.535  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 17:09:15.535  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:15.536  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.539  7310  7310 I art     : Almond Protected OAT
08-24 17:09:15.540  1038  1379 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-24 17:09:15.540  1038  1379 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-24 17:09:15.544  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.544  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.544  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-24 17:09:15.548  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.548  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.548  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 17:09:15.557  1038  1379 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 17:09:15.557  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.557  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:15.557  1038  1433 D ConnectivityService: Got NetworkAgent Messenger
08-24 17:09:15.557  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 17:09:15.557  1038  1433 D ConnectivityService: NetworkAgent connected
08-24 17:09:15.557  1038  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:09:15.557  1038  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 17:09:15.558  1038  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 17:09:15.558  1038  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-24 17:09:15.559  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.562  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.562  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:15.563  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.564  1038  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 17:09:15.564  1038  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:09:15.564  1038  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 17:09:15.565  1038  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 17:09:15.565  1038  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 17:09:15.569  1038  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 17:09:15.570   312   896 D CommandListener: Setting iface cfg
08-24 17:09:15.573  1038  1379 E WifiStateMachine: Start Dhcp Watchdog 2
08-24 17:09:15.573  1038  7334 D DhcpStateMachine: StoppedState
08-24 17:09:15.573  1038  7334 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.573  1038  7334 D DhcpStateMachine: WaitBeforeStartState
08-24 17:09:15.574  1038  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192151  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-24 17:09:15.574  1038  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192152  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:15.575  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=192152  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:15.576  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 17:09:15.576  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 17:09:15.577  1038  1379 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 17:09:15.577  1038  1379 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 17:09:15.578  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 17:09:15.578  1038  1379 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-24 17:09:15.579  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:15.579  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:15.579  1038  1038 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-24 17:09:15.579  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:15.580  1038  1379 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:15.581  1038  1379 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:15.581  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:15.581  1038  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:15.582  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:15.582  1038  1038 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 17:09:15.583  1038  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=192161  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:15.583  1038  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=192161  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:15.584  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=192162  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:15.585  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:146123] from screen [on:0 period:-1122426943] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-24 17:09:15.586  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1122426942] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-24 17:09:15.586  1038  1379 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 17:09:15.591  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.592  1038  1433 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-24 17:09:15.593  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:15.593  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:15.594  1038  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:15.594  1038  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:15.594  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:15.595  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:15.595  1038  1433 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 17:09:15.596  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
08-24 17:09:15.597  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
08-24 17:09:15.597  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-24 17:09:15.597  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-24 17:09:15.597  1038  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-24 17:09:15.597  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 17:09:15.599  7310  7310 D WeatherApplication: removeAccount
08-24 17:09:15.598  1038  1379 D WifiNative-wlan0: SET ps 0: returned true
08-24 17:09:15.599  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 17:09:15.599  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 17:09:15.600  7310  7310 D WeatherApplication: Account.length = 0
08-24 17:09:15.600  7310  7310 E WeatherApplication: OPERATOR:OPEN
08-24 17:09:15.600  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 17:09:15.600  1038  1379 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 17:09:15.600  1038  1379 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 17:09:15.600  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e7522c0 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.600  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2e7522c0 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.600  1038  1379 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 17:09:15.601  1038  7334 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.601  1038  7334 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-24 17:09:15.602   312   896 D CommandListener: Setting iface cfg
08-24 17:09:15.602   312   896 D CommandListener: Trying to bring up wlan0
08-24 17:09:15.602  1038  1379 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 17:09:15.603  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:15.603  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 17:09:15.604  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:15.604  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 17:09:15.605  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-24 17:09:15.605  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-24 17:09:15.606  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 17:09:15.606  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.606  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.606  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 17:09:15.606  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 17:09:15.606  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 17:09:15.606  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-24 17:09:15.607  1038  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 17:09:15.607  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 17:09:15.609  7310  7310 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:15
,08-24 17:09:15.612  7310  7310 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 17:09:15.612  7310  7310 D Weather.Utils: 2 : All the weather widget is gone.
08-24 17:09:15.614  7310  7310 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 17:09:15.617  7310  7310 D WeatherAncestor: connectivity changed - connection : true
08-24 17:09:15.618  7310  7310 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-24 17:09:15.624  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:15.625  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:15.625  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:15.626  1038  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:15.626  1038  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:15.627  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:15.627  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:15.628  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 17:09:15.629  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 17:09:15.629  1038  1379 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 17:09:15.630  1038  1433 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 17:09:15.630  1038  1433 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-24 17:09:15.630  1038  1433 D ConnectivityService: ignoring duplicate network state non-change
,08-24 17:09:15.631  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.631  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:15.633  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.633  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.633  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.633  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 17:09:15.634  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 17:09:15.635  1038  1433 D ConnectivityService: Adding iface wlan0 to network 101
,08-24 17:09:15.637  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.637  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.637  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 17:09:15.640  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 17:09:15.641  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-24 17:09:15.644  7310  7310 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 17:09:15.644  7310  7310 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 17:09:15.644  7310  7310 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-24 17:09:15.645  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.645  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.645  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 17:09:15.646  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 17:09:15.646  1038  1379 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 17:09:15.652  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.652  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:15.652  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 17:09:15.657  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.657  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:15.658  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.660  1038  1433 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 17:09:15.660  1038  1433 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-24 17:09:15.662  1038  1433 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-24 17:09:15.662  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.662  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 17:09:15.662   312   896 E Netd    : netlink response contains error (File exists)
08-24 17:09:15.663  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.663  1038  1433 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-24 17:09:15.664  1038  1433 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 17:09:15.664  1038  1433 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-24 17:09:15.664  1038  1433 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-24 17:09:15.665  1038  1433 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 17:09:15.665  1038  1433 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 17:09:15.665  1038  1433 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-24 17:09:15.665  1038  1433 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 17:09:15.665  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.665  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 17:09:15.665  1038  1433 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:15.665  1038  1433 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:15.665  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:15.665  1038  1433 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 17:09:15.666  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 17:09:15.666  1038  1433 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.666  1038  1433 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-24 17:09:15.666  1038  1433 D ConnectivityService: currentScore = 0, newScore = 20
08-24 17:09:15.666  1038  1433 D ConnectivityService:    accepting network in place of null
08-24 17:09:15.666  1038  1433 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.666  1038  1379 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.666  1038  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:15.667  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: tru,e, isConnectedToProvisioningNetwork: false]
08-24 17:09:15.667  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 17:09:15.667  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.670   312  7339 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-24 17:09:15.671  1841  1841 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.671  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 17:09:15.674  1038  1433 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 17:09:15.675  1038  1433 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 17:09:15.675  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-24 17:09:15.680  1038  1038 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-24 17:09:15.681  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 17:09:15.681  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 17:09:15.681  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 17:09:15.682  1038  1433 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:15.682  1038  1433 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 17:09:15.683  1038  1433 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 17:09:15.684  1038  1433 D ConnectivityService: validation of new default Network = false
08-24 17:09:15.684  1038  1433 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 17:09:15.684  1038  1433 D DSQN    : enableDataServiceNotify 
08-24 17:09:15.684  1038  1433 D DSQN    : start dsqn bin
,08-24 17:09:15.689  1038  1433 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 17:09:15.689  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.690  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:15.679  7340  7340 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:15.691  1038  1433 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:15.691  7310  7310 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 17:09:15.691  1592  1819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 17:09:15.691  7310  7310 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:15
08-24 17:09:15.679  7340  7340 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:15.710  7340  7340 E DSQN    : DSQN ssw
,08-24 17:09:15.739   312  7339 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-24 17:09:15.743  1038  2021 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7344 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:09:15.744  1038  2021 I ActivityManager: Killing 2168:com.lge.music/u0a34 (adj 15): empty #17
08-24 17:09:15.763   316  1385 V AudioFlinger: 2168 died, releasing its sessions
08-24 17:09:15.763   316  1385 V AudioFlinger:  pid 1841 @ 0
08-24 17:09:15.763   316  1385 V AudioFlinger:  pid 3285 @ 1
08-24 17:09:15.763   316  1385 V AudioFlinger:  pid 3285 @ 2
,08-24 17:09:15.775   312  7339 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-24 17:09:15.794  1038  1945 W libprocessgroup: failed to open /acct/uid_10034/pid_2168/cgroup.procs: No such file or directory
,08-24 17:09:15.802  1038  7334 D DhcpStateMachine: DHCPV4 request on wlan0
08-24 17:09:15.802  1038  7334 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-24 17:09:15.803  1038  7334 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 17:09:15.803   312   895 D LGDataListener: argv[0]=dsqncommand
08-24 17:09:15.803   312   895 D LGDataListener: argv[1]=wlan0
,08-24 17:09:15.803   312   895 D LGDataListener: argv[2]=1
08-24 17:09:15.803   312   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-24 17:09:15.805  1038  1118 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 17:09:15.805  1038  1118 D DSQN    : start to monitor internet connection
08-24 17:09:15.799  7364  7364 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:15.799  7364  7364 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 17:09:15.813  7364  7364 I dhcpcd  : version 5.5.6 starting
08-24 17:09:15.815  7364  7364 E dhcpcd  : get_duid: m
08-24 17:09:15.815  7364  7364 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 17:09:15.815  7364  7364 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-24 17:09:15.826  1038  1376 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-24 17:09:15.828  1805  7361 I CheckinService: active receiver: enabled
08-24 17:09:15.832  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 15:09:15 GMT], X-Android-Received-Millis=[1472051355832], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472051355803]}
08-24 17:09:15.832  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 17:09:15.832  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 17:09:15.833  1038  1433 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-24 17:09:15.833  1038  1433 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-24 17:09:15.833  1038  1433 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:15.833  1038  1433 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:15.833  1038  1433 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 17:09:15.833  1038  1433 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-24 17:09:15.833  1038  1433 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-24 17:09:15.833  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.833  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:15.833  1038  1433 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:15.834  1038  1433 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.834  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 17:09:15.834  1592  1819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 17:09:15.835  1038  1379 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.835  1038  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:15.836  1841  1841 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:15.836  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-24 17:09:15.856  1805  7361 I CheckinService: Preparing to send checkin request
08-24 17:09:15.856  1805  7361 I EventLogService: Accumulating logs since 1472051206629
,08-24 17:09:15.863  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-24 17:09:15.864  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.865  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.878  7364  7364 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 17:09:15.879  7364  7364 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 17:09:15.879  7364  7364 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 17:09:15.879  7364  7364 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-24 17:09:15.879  7364  7364 D dhcpcd  : wlan0: sending REQUEST (xid 0x2537f2e1), next in 3.93 seconds
,08-24 17:09:15.887  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 17:09:15.888  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.889  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:15.904  1805  7361 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 17:09:15.909  7364  7364 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-24 17:09:15.920  7364  7364 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-24 17:09:15.920  7364  7364 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-24 17:09:15.920  7364  7364 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-24 17:09:15.920  7364  7364 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 17:09:15.921  7364  7364 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 17:09:15.922  7364  7364 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 17:09:15.922  7364  7364 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 17:09:15.922  7364  7364 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-24 17:09:15.933   279   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 17:09:15.933   279   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-24 17:09:15.933   279   447 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 17:09:15.936  7344  7374 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-24 17:09:15.943   279   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 17:09:15.943   279   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 17:09:15.943   279   447 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 17:09:15.945  7344  7374 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 17:09:15.953   279   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 17:09:15.953   279   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-24 17:09:15.953   279   447 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 17:09:15.956  7344  7381 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-24 17:09:15.961   279   447 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-24 17:09:15.961   279   447 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-24 17:09:15.961   279   447 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 17:09:15.961  7344  7381 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-24 17:09:16.008  1038  1945 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7389 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-24 17:09:16.045  7389  7389 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 17:09:16.045  7389  7389 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-24 17:09:16.060  7389  7389 I MultiDex: VM with version 2.1.0 has multidex support
08-24 17:09:16.060  7389  7389 I MultiDex: install
08-24 17:09:16.060  7389  7389 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 17:09:16.066  7389  7389 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-24 17:09:16.150  7344  7344 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 17:09:16.158  7344  7344 I LibraryLoader: Loading: webviewchromium
08-24 17:09:16.161  7344  7344 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2747-2750)
08-24 17:09:16.161  7344  7344 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 17:09:16.165  7344  7344 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3428eede}
,08-24 17:09:16.166  7344  7344 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 17:09:16.166  7344  7344 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 17:09:16.176  7344  7344 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 17:09:16.177  7344  7344 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 17:09:16.191   316  2190 V AudioPolicyService: registerClient() client 0xb558a2e0, uid 10093
08-24 17:09:16.192  7344  7344 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-24 17:09:16.192  7344  7344 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-24 17:09:16.193  7344  7344 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-24 17:09:16.198  7344  7436 W AudioManagerAndroid: Requires BLUETOOTH permission
08-24 17:09:16.204  1038  7334 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-24 17:09:16.207  1038  7334 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-24 17:09:16.207  1038  7334 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 17:09:16.207  1038  7334 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 17:09:16.207  1038  7334 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 17:09:16.207  1038  7334 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 17:09:16.207  1038  7334 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 17:09:16.207  1038  7334 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-24 17:09:16.209  1038  7334 D DhcpStateMachine: RunningState
08-24 17:09:16.214  7344  7344 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 17:09:16.214  7344  7344 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 17:09:16.214  7344  7344 I Adreno-EGL: Build Date: 12/12/14 금
08-24 17:09:16.214  7344  7344 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 17:09:16.214  7344  7344 I Adreno-EGL: Remote Branch: 
08-24 17:09:16.214  7344  7344 I Adreno-EGL: Local Patches: 
08-24 17:09:16.214  7344  7344 I Adreno-EGL: Reconstruct Branch: 
08-24 17:09:16.291  7389  7407 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:16.291  7389  7407 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 17:09:16.306  7344  7344 I NSApplication: Starting up...
,08-24 17:09:16.352  1038  1563 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7449 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-24 17:09:16.353  1038  1563 I ActivityManager: Killing 6581:com.android.vending/u0a44 (adj 15): empty #17
,08-24 17:09:16.412  1038  1946 W libprocessgroup: failed to open /acct/uid_10044/pid_6581/cgroup.procs: No such file or directory
,08-24 17:09:16.453  7449  7449 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 17:09:16.469  1038  1983 D WifiServiceImplEx: setWifiEnabled: false pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 17:09:16.469  1038  1983 D WifiService: setWifiEnabled: false pid=6862, uid=10118
08-24 17:09:16.469  1038  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 17:09:16.489  1038  1379 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:16.489  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:16.490  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-24 17:09:16.490  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:16.491  1038  1379 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:16.491  1038  1379 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:16.492  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-24 17:09:16.492  1038  1379 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 17:09:16.492  1038  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:09:16.492  1038  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 17:09:16.493  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-24 17:09:16.493  1038  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 17:09:16.493  1038  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 17:09:16.495  7469  7469 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-24 17:09:16.510  1038  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 17:09:16.510  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 17:09:16.510  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.510  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.510  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-24 17:09:16.511  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 17:09:16.511  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 17:09:16.511  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:16.511   312   896 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:09:16.518  1038  7334 D DhcpStateMachine: RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.541  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.541  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.541  1038  1377 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@33ecff4d
08-24 17:09:16.541  1038  1377 D LGWifiP2pService: P2pDisablingState
08-24 17:09:16.541  1038  1377 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.542  1038  1377 D LGWifiP2pService: p2p socket connection lost
08-24 17:09:16.542  1038  1377 D LGWifiP2pService: P2pDisabledState
08-24 17:09:16.542  1038  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-24 17:09:16.542  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:16.542  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:16.543  1038  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:16.543  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:16.543  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:16.544  1038  1379 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-24 17:09:16.544  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 17:09:16.544  1038  1433 D ConnectivityService: ignoring duplicate network state non-change
08-24 17:09:16.545  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-24 17:09:16.550  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-24 17:09:16.550  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-24 17:09:16.550  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.550  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.551  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:16.554  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:16.554  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:16.556  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-24 17:09:16.559  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.560  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 17:09:16.560  1928  1928 D WfdsService: WifiP2pState is changed : false
08-24 17:09:16.561  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=-16ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.561  1038  1377 D LGWifiP2pService: DefaultState{ when=-16ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.561  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 17:09:16.561  7230  7230 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 17:09:16.562  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 17:09:16.562  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
,08-24 17:09:16.562  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:16.564  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:16.564  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:16.565  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.565  1928  2205 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-24 17:09:16.565  1928  2205 D WfdsService: Set the WFDS Monitor: false
08-24 17:09:16.570  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.570  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.570  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:16.570  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 17:09:16.570  1038  1038 D RttService: SCAN_AVAILABLE : 1
08-24 17:09:16.570  1038  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.571  1038  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.573  1928  2205 D WfdsMonitor: WFDS Monitor is stopped
08-24 17:09:16.573  1928  2205 D WfdsService: STATE : WfdsDisabledState - enter
08-24 17:09:16.574  1928  2206 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-24 17:09:16.574  1928  7268 D CtrlSupplicant: Received on exit socket, terminate
08-24 17:09:16.574  1928  7268 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-24 17:09:16.574  1928  7268 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-24 17:09:16.574  1928  7268 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-24 17:09:16.574  1928  2205 W WfdsService: DefaultState - msg [9445378] is not handled
,08-24 17:09:16.580  7469  7469 I dex2oat : dex2oat took 84.540ms (threads: 4)
08-24 17:09:16.586   312   896 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:09:16.586  1038  1433 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-24 17:09:16.586  1038  1433 D DSQN    : disableDataServiceNotify
08-24 17:09:16.586  1038  1433 D DSQN    : stop dsqn bin
,08-24 17:09:16.588  7389  7407 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 17:09:16.588  7389  7407 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 17:09:16.588  7389  7407 I Adreno-EGL: Build Date: 12/12/14 금
08-24 17:09:16.588  7389  7407 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 17:09:16.588  7389  7407 I Adreno-EGL: Remote Branch: 
08-24 17:09:16.588  7389  7407 I Adreno-EGL: Local Patches: 
08-24 17:09:16.588  7389  7407 I Adreno-EGL: Reconstruct Branch: 
08-24 17:09:16.589  1038  1379 D WifiNative-p2p0: doBoolean: TERMINATE
08-24 17:09:16.589  1038  1379 D WifiNative-p2p0: TERMINATE: returned true
08-24 17:09:16.589  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:16.589  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:16.589  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 17:09:16.590  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-24 17:09:16.591  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 17:09:16.591  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:16.592  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.592  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.592  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:16.593  1038  1379 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 17:09:16.593  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.593  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-24 17:09:16.595  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-24 17:09:16.595  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:16.595  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:16.595  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:16.595  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:16.596  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:16.596  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth, is disabled - will return stored value
08-24 17:09:16.596  1038  1038 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:16.596  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:16.596  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:16.596  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:16.600  1038  1433 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-24 17:09:16.600  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:16.600  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:16.600  1038  1433 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:16.600  1038  1433 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-24 17:09:16.601  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.601  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:16.601  1038  7333 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 17:09:16.601  1038  1433 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-24 17:09:16.601  1038  1433 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 17:09:16.601  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 17:09:16.601  1592  1819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 17:09:16.601  1038  1433 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:16.601  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 17:09:16.602  1038  1433 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:16.602  1038  1433 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:16.602  1038  1433 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:16.603  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 17:09:16.603  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 17:09:16.603  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 17:09:16.603  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 17:09:16.603  1038  1379 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:16.603  1038  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 17:09:16.603  1038  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:16.603  1841  1841 D TelephonyNe,tworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:16.604  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 17:09:16.604  1038  1376 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-24 17:09:16.610  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-24 17:09:16.610  1038  1433 D NetworkManagementService: Removing idletimer
08-24 17:09:16.610  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 17:09:16.610  1038  1433 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.611  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 17:09:16.611  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-24 17:09:16.615  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.634  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 17:09:16.635  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.636  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 17:09:16.653  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 17:09:16.654  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.654  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.664  7230  7230 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-24 17:09:16.664  7230  7230 I wpa_supplicant: monitor socket send errors count : 1
08-24 17:09:16.664  7230  7230 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-4\x00 that cannot receive messages
,08-24 17:09:16.666  1038  7248 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-24 17:09:16.666  1038  7248 D WifiMonitor: Dropping event because (p2p0) is stopped
08-24 17:09:16.686  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 17:09:16.687  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-24 17:09:16.687  7230  7230 W wpa_supplicant: USIM:  scard_deinit function
,08-24 17:09:16.688  1038  1120 D Tethering: InitialState.processMessage what=4
08-24 17:09:16.689  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 17:09:16.689  1038  7248 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 17:09:16.689  1038  7248 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-24 17:09:16.689  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:16.690  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:16.690  1038  1379 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193268
08-24 17:09:16.691  1038  1379 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193268
08-24 17:09:16.691  1038  1379 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=193269  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 17:09:16.691  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:09:16.691  1038  1379 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=193269  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-24 17:09:16.692  1038  1433 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-24 17:09:16.694  1038  1379 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:16.694  1038  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:16.722  1038  7334 D DhcpStateMachine: StoppedState
08-24 17:09:16.722  1038  7334 D DhcpStateMachine: StoppedState{ when=-160ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:09:16.725  1038  1379 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-24 17:09:16.726  1038  1379 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-24 17:09:16.758  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-24 17:09:16.761  6418  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 17:09:16.777  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:16.790  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 17:09:16.790  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:16.790  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 17:09:16.790  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 17:09:16.792  7173  7173 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 17:09:16.795  7173  7173 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31461ad7
08-24 17:09:16.795  7173  7173 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 17:09:16.795  7173  7173 D AppUp4:CustFacade: isPhone : true
08-24 17:09:16.795  7173  7173 D AppUp4:CustModeStarterReceiver: begin check event
08-24 17:09:16.796  7173  7173 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 17:09:16.799  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:16.799  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:16.801  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:16.802  7230  7230 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-24 17:09:16.803  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:16.803  1038  7248 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-24 17:09:16.803  1038  7248 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-24 17:09:16.804  1038  7248 D WifiMonitor: Disconnecting from the supplicant, no more events
08-24 17:09:16.804  1038  1379 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-24 17:09:16.810  4779  7494 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:16.812  7201  7201 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 17:09:16.814  4779  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:16.815  4779  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 17:09:16.831  3285  3285 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 17:09:16.831  3285  3285 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:16.831  3285  3285 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-24 17:09:16.835  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 17:09:16.835  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 17:09:16.837  7201  7498 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.838  7076  7500 W FormManager: Network not available. Please check & try again.
08-24 17:09:16.839  7076  7501 V FormManager: Network unavailable.
08-24 17:09:16.848  7076  7501 V FormManager: Network unavailable.
,08-24 17:09:16.854  7310  7310 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:16
,08-24 17:09:16.856  7310  7310 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 17:09:16.856  7310  7310 D Weather.Utils: 2 : All the weather widget is gone.
08-24 17:09:16.856  7310  7310 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 17:09:16.857  7310  7310 D WeatherAncestor: connectivity changed - connection : true
08-24 17:09:16.857  7310  7310 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1fd06ead
08-24 17:09:16.857  7310  7310 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 17:09:16.857  7310  7310 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 17:09:16.857  7310  7310 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 17:09:16.857  7310  7310 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 17:09:16.857  7310  7310 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:16
08-24 17:09:16.865  7389  7407 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 17:09:16.865  7389  7407 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 17:09:16.865  7389  7407 I Adreno-EGL: Build Date: 12/12/14 금
08-24 17:09:16.865  7389  7407 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 17:09:16.865  7389  7407 I Adreno-EGL: Remote Branch: 
08-24 17:09:16.865  7389  7407 I Adreno-EGL: Local Patches: 
08-24 17:09:16.865  7389  7407 I Adreno-EGL: Reconstruct Branch: 
,08-24 17:09:16.878  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 17:09:16.878  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 17:09:16.878  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 17:09:16.878  6992  6992 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 17:09:16.879  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 17:09:16.879  6992  6992 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 17:09:16.879  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 17:09:16.879  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 17:09:16.879  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 17:09:16.879  6992  6992 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 17:09:16.879  6992  6992 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-24 17:09:16.886  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:16.888  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 17:09:16.891  7076  7507 W FormManager: Network not available. Please check & try again.
,08-24 17:09:16.895  7076  7508 V FormManager: Network unavailable.
,08-24 17:09:16.898  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:16.901  7076  7508 V FormManager: Network unavailable.
08-24 17:09:16.907  1038  1379 D WifiOffDelayIfNotUsed: stopMonitoring
08-24 17:09:16.907  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:16.907  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:16.907  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 17:09:16.908  1928  1928 D WfdsService: Supplicant Connection state is changed : false
,08-24 17:09:16.908  1928  2205 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-24 17:09:16.908  1928  2205 D WfdsService: Set the WFDS Monitor: false
08-24 17:09:16.908  1928  2205 D WfdsMonitor: WFDS Monitor is stopped
08-24 17:09:16.910  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:16.910  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-24 17:09:16.911  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-24 17:09:16.911  1038  1423 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-24 17:09:16.911  1038  1423 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-24 17:09:16.912  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:16.912  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:16.912  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:16.914  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:16.914  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:16.917  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:16.919  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:09:16.926  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:16.932  7076  7510 W FormManager: Network not available. Please check & try again.
,08-24 17:09:16.935  7076  7511 V FormManager: Network unavailable.
08-24 17:09:16.937  7076  7511 V FormManager: Network unavailable.
08-24 17:09:16.937  7389  7407 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 17:09:16.937  7389  7407 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 17:09:16.937  7389  7407 I Adreno-EGL: Build Date: 12/12/14 금
08-24 17:09:16.937  7389  7407 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 17:09:16.937  7389  7407 I Adreno-EGL: Remote Branch: 
08-24 17:09:16.937  7389  7407 I Adreno-EGL: Local Patches: 
08-24 17:09:16.937  7389  7407 I Adreno-EGL: Reconstruct Branch: 
08-24 17:09:16.940  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:16.940  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:16.941  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:16.947  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 17:09:16.952  4779  7512 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:16.955  4779  7513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:16.955  4779  7513 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 17:09:16.996  1038  1054 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7514 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-24 17:09:17.012   312  7532 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-24 17:09:17.012  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 17:09:17.012  1805  7361 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-24 17:09:17.023  1805  7361 I CheckinService: active receiver: disabled
,08-24 17:09:17.037  1038  1366 D PowerManagerServiceEx: acquireWakeLockInternal: lock=270740398, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,08-24 17:09:17.075  2597  2597 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 17:09:17.087  7514  7514 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 17:09:17.087  7514  7514 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-24 17:09:17.092  7514  7514 V [BNRBootReceiver]: Boot Receiver Return
08-24 17:09:17.093  7514  7514 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 17:09:17.095  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:17.100  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.106  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.116  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 17:09:17.116  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.117  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:17.120  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:17.128  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.134  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.142  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.143  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.146  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-24 17:09:17.151  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-24 17:09:17.156  6992  6992 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-24 17:09:17.162  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:17.172  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.179  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.188  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.189  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.190  7037  7037 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:17.196  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:17.205  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:17.213  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.221  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.222  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.223  7037  7037 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:17.229  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:17.241  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.251  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.261  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.262  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.263  7037  7037 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:17.268  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:17.281  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.291  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.302  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.302  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.303  7037  7037 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 17:09:17.312  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:17.329  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.338  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.345  6774  7153 D UEI.SmartControl: Internal timer expired: 2
08-24 17:09:17.346  6774  7153 D UEI.SmartControl: unbind internal service
08-24 17:09:17.346  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.347  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.347  7037  7037 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 17:09:17.356  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:17.371  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.380  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.389  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.389  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:17.395  7037  7037 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:17.402  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:17.415  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.424  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.433  6774  7147 D serial_port: close(fd = 24)
08-24 17:09:17.438  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.439  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:17.440  7037  7037 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:17.443  6774  7147 I UEI.SmartControl: Serial port is closed.
08-24 17:09:17.449  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:17.456  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-24 17:09:17.472  1038  1432 D WifiService: New client listening to asynchronous messages
08-24 17:09:17.473  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:17.480  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:17.492  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.507  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 17:09:17.507  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.509  7037  7037 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 17:09:17.512  7037  7037 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 17:09:17.513  7037  7037 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 17:09:17.523  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:17.530  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 17:09:17.533  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:17.539  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.551  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.565  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.566  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:17.569  7037  7037 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 17:09:17.572  7037  7037 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-24 17:09:17.573  7037  7037 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 17:09:17.578  1038  1591 I ActivityManager: Killing 7013:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-24 17:09:17.636  1038  1726 W libprocessgroup: failed to open /acct/uid_10037/pid_7013/cgroup.procs: No such file or directory
08-24 17:09:17.642  2146  2146 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-24 17:09:17.657  2146  2146 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-24 17:09:17.657  2146  2146 D c       : Getting all permits...
08-24 17:09:17.657  2146  2146 D a       : Opening database...
,08-24 17:09:17.662  2146  2146 D a       : Opening database auth.proximity.permit_store...
08-24 17:09:17.663  2146  2146 D a       : Closing database...
08-24 17:09:17.678  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:17.681  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 17:09:17.681  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:17.682  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:17.684  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:17.690  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.698  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 17:09:17.699  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:17.703  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:17.706  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:17.708  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 17:09:17.709  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:17.709  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:17.712  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.720  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.733  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:17.734  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:17.737  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:17.746  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:17.756  6974  6974 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-24 17:09:17.756  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:17.756  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:17.768  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:17.780  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:17.789  7037  7037 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-24 17:09:17.789  7037  7037 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:17.793  7037  7037 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:17.803  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:17.809  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:09:17.815  7076  7541 W FormManager: Network not available. Please check & try again.
08-24 17:09:17.817  7076  7542 V FormManager: Network unavailable.
,08-24 17:09:17.821  7076  7542 V FormManager: Network unavailable.
08-24 17:09:17.826  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.854  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:17.854  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:17.856  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:17.859  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 17:09:17.869  6974  6974 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-24 17:09:17.869  4779  7543 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:17.870  6974  6974 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-24 17:09:17.870  6974  6974 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:17.875  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 17:09:17.879  4779  7545 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:17.879  4779  7545 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 17:09:17.887  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:17.888  7076  7546 W FormManager: Network not available. Please check & try again.
08-24 17:09:17.896  7076  7547 V FormManager: Network unavailable.
,08-24 17:09:17.900  7076  7547 V FormManager: Network unavailable.
08-24 17:09:17.906  7037  7037 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-24 17:09:17.906  7037  7037 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1961
08-24 17:09:17.908  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=270740398 [*alarm*], flags=0x0
08-24 17:09:17.914  2146  2146 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-24 17:09:18.595  1038  1379 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1122423933] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 17:09:18.597  1038  1379 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1122423931] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 17:09:18.684  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:18.692  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-24 17:09:18.714  1038  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:18.720  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:18.721  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:18.724  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 17:09:18.725  6418  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 17:09:18.738  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-24 17:09:18.760  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:18.781  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 17:09:18.781  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:18.781  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 17:09:18.781  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 17:09:18.787  7173  7173 I AppUp4:CustModeStarterReceiver: onReceive
08-24 17:09:18.791  7173  7173 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31461ad7
08-24 17:09:18.792  7173  7173 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 17:09:18.792  7173  7173 D AppUp4:CustFacade: isPhone : true
08-24 17:09:18.793  7173  7173 D AppUp4:CustModeStarterReceiver: begin check event
08-24 17:09:18.793  7173  7173 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 17:09:18.798  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:18.798  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:18.800  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-24 17:09:18.806  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:18.819  4779  7559 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:18.824  1038  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 17:09:18.831  7201  7201 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 17:09:18.839  4779  7560 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:18.840  4779  7560 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-24 17:09:18.857  7201  7571 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:09:18.863  3285  3285 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-24 17:09:18.863  3285  3285 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:18.864  3285  3285 I LgeMiscReceiver: networkInfo.isConnected() = true
08-24 17:09:18.864  3285  3285 D PhoneState: setPdpRejectCasuse : false
08-24 17:09:18.869  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 17:09:18.869  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 17:09:18.871  7076  7574 W FormManager: Network not available. Please check & try again.
,08-24 17:09:18.881  7310  7310 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:18
08-24 17:09:18.883  7310  7310 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 17:09:18.883  7310  7310 D Weather.Utils: 2 : All the weather widget is gone.
08-24 17:09:18.883  7310  7310 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-24 17:09:18.883  7310  7310 D WeatherAncestor: connectivity changed - connection : true
,08-24 17:09:18.884  7310  7310 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1fd06ead
,08-24 17:09:18.884  7076  7575 V FormManager: Network unavailable.
08-24 17:09:18.885  7310  7310 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 17:09:18.885  7310  7310 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 17:09:18.885  7310  7310 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 17:09:18.885  7310  7310 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 17:09:18.885  7310  7310 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:18
08-24 17:09:18.887  7076  7575 V FormManager: Network unavailable.
08-24 17:09:19.490  1038  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:19.503  1038  1053 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-24 17:09:19.530  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:19.531  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 17:09:19.531  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-24 17:09:19.532  1038  1120 D BluetoothManagerService: Message: 1
08-24 17:09:19.532  1038  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-24 17:09:19.559  1038  1120 D BluetoothManagerService: Message: 20
08-24 17:09:19.559  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@110549b9:true
,08-24 17:09:19.565  7111  7111 D BluetoothAdapterState: make
08-24 17:09:19.569  7111  7111 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 17:09:19.570  7111  7111 I bluedroid-qcom: init
08-24 17:09:19.570  7111  7588 I BluetoothAdapterState: Entering OffState
08-24 17:09:19.571  7111  7111 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 17:09:19.571  7111  7111 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 17:09:19.572  7111  7111 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 17:09:19.572  7111  7111 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 17:09:19.572  7111  7111 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 17:09:19.574  7111  7111 I bluedroid-qcom: get_profile_interface socket
08-24 17:09:19.574  7111  7111 I bluedroid-qcom: get_profile_interface map_client
,08-24 17:09:19.579  7111  7592 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 17:09:19.579  7591  7591 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:19.579  7591  7591 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:19.592  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-24 17:09:19.596  1038  1120 D BluetoothManagerService: Message: 40
08-24 17:09:19.596  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 17:09:19.597  7111  7127 I bluedroid-qcom: config_hci_snoop_log
08-24 17:09:19.598  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 17:09:19.598  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-24 17:09:19.603  7591  7591 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 17:09:19.603  7591  7591 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 17:09:19.603  7591  7591 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-24 17:09:19.603  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.606  7591  7591 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-24 17:09:19.611  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.612  1038  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.619  7591  7591 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 17:09:19.619  7591  7591 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-24 17:09:19.623  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:19.628  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:19.631  7111  7588 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-24 17:09:19.631  7111  7588 D BluetoothAdapterProperties: Setting state to 11
08-24 17:09:19.631  7111  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 17:09:19.633  7111  7588 I LGBluetoothServiceJni: classInitNative: succeeds
08-24 17:09:19.638  7111  7592 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-24 17:09:19.645  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-24 17:09:19.645  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:19.645  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 17:09:19.645  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 17:09:19.656  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-24 17:09:19.660  6418  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-24 17:09:19.664  7111  7588 D BluetoothBondStateMachine: make
08-24 17:09:19.665  7111  7592 D BluetoothAdapterProperties: Name is: G3
08-24 17:09:19.669  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 17:09:19.669  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 17:09:19.670  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-24 17:09:19.671  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 17:09:19.672  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:19.672  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:19.674  6992  6992 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-24 17:09:19.674  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:19.676  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:19.678  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:19.680  7111  7607 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 17:09:19.681  7111  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:19.681  7111  7588 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 17:09:19.681  7111  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:19.681  7111  7588 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 17:09:19.681  7111  7588 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 17:09:19.683  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 17:09:19.687  7111  7111 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 17:09:19.688  7111  7111 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:19.688  7111  7111 V BluetoothPbapReceiver: ***********state = 11
08-24 17:09:19.688  7111  7588 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 17:09:19.694  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 17:09:19.745  1038  1946 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7611 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-24 17:09:19.747  1038  1100 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:09:19.751  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-24 17:09:19.752  7111  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:19.754  1038  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:19.754  1038  1100 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:19.754  7111  7111 D HeadsetService: Received start request. Starting profile...
08-24 17:09:19.755  7111  7111 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 17:09:19.755  7111  7111 D LGBluetoothHfpAdapter: Version 1.6
08-24 17:09:19.758  7111  7111 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 17:09:19.759  7111  7111 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 17:09:19.760  7111  7111 D HeadsetStateMachine: make
08-24 17:09:19.764  7111  7588 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 17:09:19.772  7111  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:19.773  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.782  7111  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:19.783  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 17:09:19.783  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.783  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 17:09:19.783  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-24 17:09:19.786  7173  7173 I AppUp4:CustModeStarterReceiver: onReceive
08-24 17:09:19.793  7111  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:19.794  7173  7173 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31461ad7
08-24 17:09:19.794  7173  7173 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 17:09:19.794  7173  7173 D AppUp4:CustFacade: isPhone : true
08-24 17:09:19.795  7173  7173 D AppUp4:CustModeStarterReceiver: begin check event
08-24 17:09:19.796  7173  7173 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-24 17:09:19.801  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.801  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:19.802  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:19.803  7111  7111 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:19.804  7111  7111 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 17:09:19.806  7111  7588 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:19.809  7111  7111 D HeadsetStateMachine: max_hf_connections = 1
,08-24 17:09:19.809  7111  7111 I bluedroid-qcom: get_profile_interface handsfree
,08-24 17:09:19.810  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:19.812  7111  7111 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-24 17:09:19.813   316   316 V AudioPolicyService: registerClient() client 0xb558a5e0, uid 1002
08-24 17:09:19.813   316  1385 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 17:09:19.813   316  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 17:09:19.813   316  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 17:09:19.814  7111  7111 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 17:09:19.814   316  2190 V AudioFlinger: registerClient() client 0xb10190e8, pid 7111
08-24 17:09:19.814   316  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-24 17:09:19.814   316  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:19.815  7111  7111 V ToneGenerator: Create Track: 0xb4928080
08-24 17:09:19.815  7111  7111 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 17:09:19.815  7111  7111 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 17:09:19.815   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 17:09:19.815  1038  1945 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:19.815   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-24 17:09:19.815  1038  1945 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:19.815   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 17:09:19.815   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 17:09:19.815  1592  1609 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:19.815  1592  1609 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:19.815   316  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:19.815   316  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:19.817  7111  7111 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 17:09:19.817  7111  7126 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:19.817  7111  7126 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 17:09:19.817   316  2190 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 17:09:19.818   316  2189 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 17:09:19.818   316  2189 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 17:09:19.818   316  2189 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 17:09:19.818   316  2189 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 17:09:19.818  7111  7111 V AudioSystem: getLatency() output 2, latency 50
08-24 17:09:19.818  7111  7111 V AudioSystem: getFrameCount() output 2, frameCount 960
08-24 17:09:19.818  7111  7111 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 17:09:19.818  1841  1857 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:19.818  1841  1857 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:19.818  3285  3301 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:19.818  3285  3301 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:19.818  1592  2523 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:19.818  1592  2523 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:19.818  1841  2703 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:19.819  1841  2703 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:19.819  3285  3300 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:19.819  3285  3300 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:19.819  7111  7127 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:19.819   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 17:09:19.819  7111  7127 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 17:09:19.819   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 17:09:19.819   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 17:09:19.819   316  , 316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 17:09:19.819   316   316 V AudioFlinger: createTrack() lSessionId: 20
08-24 17:09:19.824  1038  1762 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:19.824  1038  1762 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:19.825  7111  7111 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 17:09:19.826   316   316 V AudioFlinger: acquiring 20 from 7111, for 7111
08-24 17:09:19.826   316   316 V AudioFlinger:  added new entry for 20
08-24 17:09:19.826  7111  7111 V ToneGenerator: ToneGenerator INIT OK, time: 196415
08-24 17:09:19.826  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:19.826  7111  7588 V LGMDMManager: Create singleton instance
08-24 17:09:19.826  7111  7629 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 17:09:19.827  7111  7629 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 17:09:19.827  7111  7629 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 17:09:19.827  7111  7629 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 17:09:19.827   316  2189 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7111
08-24 17:09:19.830  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:19.830   316  2189 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 17:09:19.830   316  2189 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 17:09:19.830   316  2189 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 17:09:19.830   316  2189 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 17:09:19.830   316  2189 V voice   : voice_set_parameters: exit with code(0)
08-24 17:09:19.830   316  2189 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 17:09:19.830   316  2189 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 17:09:19.830   316  2189 V msm8974_platform: platform_set_parameters: exit with code(0)
08-24 17:09:19.830   316  2189 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 17:09:19.830   316  2189 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-24 17:09:19.830   316  2189 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 17:09:19.831  7111  7629 V ToneGenerator: ToneGenerator destructor
08-24 17:09:19.831  7111  7629 V ToneGenerator: stopTone
08-24 17:09:19.831  7111  7629 V ToneGenerator: Delete Track: 0xb4928080
,08-24 17:09:19.831  7111  7629 V AudioTrack: ~AudioTrack, releasing session id from 7111 on behalf of 7111
,08-24 17:09:19.832   316  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 17:09:19.832   316  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 17:09:19.832   316  2190 V AudioFlinger: releasing 20 from 7111 for 7111
08-24 17:09:19.832   316  2190 V AudioFlinger:  decremented refcount to 0
08-24 17:09:19.832   316  2190 V AudioFlinger: purging stale effects
08-24 17:09:19.832  7111  7111 D A2dpService: Received start request. Starting profile...
08-24 17:09:19.833  7111  7111 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 17:09:19.834  7111  7111 V Avrcp   : make
08-24 17:09:19.834   316  1385 V AudioFlinger: PlaybackThread::Track destructor
08-24 17:09:19.834   316  1385 V AudioFlinger: removeClient_l() pid 7111, calling pid 316
08-24 17:09:19.834   316  1259 V AudioPolicyService: AudioCommandThread() waking up
08-24 17:09:19.834   316  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 17:09:19.834   316  1259 V AudioPolicyManager: releaseOutput() 2
08-24 17:09:19.834   316  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 17:09:19.834  7111  7111 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 17:09:19.834  7111  7111 I bluedroid-qcom: get_profile_interface avrcp
08-24 17:09:19.837  7111  7588 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 17:09:19.841  7201  7201 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 17:09:19.845  7111  7111 V AudioManager: registerRemoteController: size of Media player list: 0
08-24 17:09:19.847  7111  7111 E AudioManager: No RCC entry present to update
08-24 17:09:19.847  7111  7111 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 17:09:19.851  7111  7111 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 17:09:19.852  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 17:09:19.852  7111  7111 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-24 17:09:19.862  4779  7631 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:19.863  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-24 17:09:19.884  4779  7635 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.885  4779  7635 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 17:09:19.922  7076  7637 W FormManager: Network not available. Please check & try again.
,08-24 17:09:19.927  7201  7641 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:19.929  7076  7638 V FormManager: Network unavailable.
08-24 17:09:19.931  7076  7638 V FormManager: Network unavailable.
08-24 17:09:19.965  1038  1964 I art     : Explicit concurrent mark sweep GC freed 117761(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.246ms total 86.628ms
,08-24 17:09:19.971  7611  7611 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-24 17:09:19.972  7611  7611 W LG Account v2.2: No ProfileInfo entries
08-24 17:09:19.972  7611  7611 I LG Account v2.2: isEnabled: false
08-24 17:09:19.972  7611  7611 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 17:09:19.972  7611  7611 I Feature : [Lifetracker]Country: EU
08-24 17:09:19.972  7611  7611 I Feature : [Lifetracker]Operator: OPEN
08-24 17:09:19.972  7611  7611 I Feature : [Lifetracker]Ranking support: false
08-24 17:09:19.972  7611  7611 I Feature : [Lifetracker]Comfort support: false
08-24 17:09:19.972  7611  7611 I Feature : [Lifetracker]Accessory: true
08-24 17:09:19.972  7611  7611 I Feature : [Lifetracker]Health device: true
08-24 17:09:19.973  7611  7611 I Feature : [Lifetracker]Extra Pedometer: false
08-24 17:09:19.973  7611  7611 I Feature : [Lifetracker]Blood glucose device: false
08-24 17:09:19.973  7611  7611 I Feature : [Lifetracker]Device Number: 3
08-24 17:09:19.975  3285  3285 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 17:09:19.975  3285  3285 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:19.975  3285  3285 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 17:09:19.980  1038  1945 V SIM_STK : Menu title from STK is T-Mobile
08-24 17:09:19.980  1038  1945 V SIM_STK : Menu title from STK is T-Mobile
,08-24 17:09:19.980  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 17:09:19.980  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 17:09:19.986  6992  6992 D BluetoothPermissionRequest: onReceive
08-24 17:09:19.990  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 17:09:19.993  7310  7310 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:19
,08-24 17:09:19.994  7310  7310 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 17:09:19.994  7310  7310 D Weather.Utils: 2 : All the weather widget is gone.
08-24 17:09:19.994  7310  7310 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 17:09:19.994  7310  7310 D WeatherAncestor: connectivity changed - connection : true
08-24 17:09:19.994  7310  7310 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1fd06ead
08-24 17:09:19.995  7310  7310 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 17:09:19.995  7310  7310 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 17:09:19.995  7310  7310 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 17:09:19.995  7310  7310 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 17:09:19.995  7310  7310 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:19
08-24 17:09:20.014  6418  6418 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-24 17:09:20.015  6418  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-24 17:09:20.025  2146  2146 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:20.033  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-24 17:09:20.033  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:20.033  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-24 17:09:20.033  7173  7173 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-24 17:09:20.034  1038  1563 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 17:09:20.035  7173  7173 I AppUp4:CustModeStarterReceiver: onReceive
08-24 17:09:20.037  7173  7173 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31461ad7
08-24 17:09:20.037  7173  7173 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 17:09:20.037  7173  7173 D AppUp4:CustFacade: isPhone : true
08-24 17:09:20.037  7173  7173 D AppUp4:CustModeStarterReceiver: begin check event
08-24 17:09:20.037  7173  7173 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-24 17:09:20.039  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 17:09:20.040  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:20.040  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:20.041  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:20.041  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 17:09:20.042  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 17:09:20.042  7111  7111 I BluetoothA2dpServiceJni: classInitNative
08-24 17:09:20.042  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:20.042  7111  7111 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:09:20.042  7111  7111 D A2dpStateMachine: make
08-24 17:09:20.043  7111  7111 I bluedroid-qcom: get_profile_interface a2dp
08-24 17:09:20.044  7111  7644 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-24 17:09:20.045  7111  7111 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:09:20.045  4779  7646 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:20.045  7111  7111 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-24 17:09:20.046  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.047  7111  7111 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 17:09:20.048  7111  7643 D A2dpStateMachine: Enter Disconnected: -2
08-24 17:09:20.048  7111  7111 D HidService: Received start request. Starting profile...
08-24 17:09:20.048  7111  7111 I bluedroid-qcom: get_profile_interface hidhost
08-24 17:09:20.048  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.048  7201  7201 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-24 17:09:20.048  7111  7111 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 17:09:20.049  4779  7647 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:20.049  4779  7647 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 17:09:20.050  7111  7111 D HealthService: Received start request. Starting profile...
08-24 17:09:20.051  7111  7111 I bluedroid-qcom: get_profile_interface health
08-24 17:09:20.051  7111  7111 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 17:09:20.051  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.052  7111  7111 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 17:09:20.054  7111  7111 D PanService: Received start request. Starting profile...
08-24 17:09:20.054  7111  7111 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:09:20.054  7111  7111 I bluedroid-qcom: get_profile_interface pan
08-24 17:09:20.061  7111  7111 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-24 17:09:20.061  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.062  7111  7111 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-24 17:09:20.062  7076  7653 W FormManager: Network not available. Please check & try again.
08-24 17:09:20.063  7201  7651 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:09:20.065  7111  7111 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 17:09:20.066  7111  7111 D BtGatt.GattService: Received start request. Starting profile...
08-24 17:09:20.066  7111  7111 D BtGatt.GattService: start()
08-24 17:09:20.066  7111  7111 I bluedroid-qcom: get_profile_interface gatt
08-24 17:09:20.066  7111  7111 D BtGatt.AdvertiseManager: advertise manager created
08-24 17:09:20.069  3285  3285 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-24 17:09:20.069  3285  3285 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:20.069  3285  3285 I LgeMiscReceiver: networkInfo.isConnected() = false
08-24 17:09:20.071  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.071  7111  7111 D HeadsetStateMachine: Proxy object connected
08-24 17:09:20.071  7111  7111 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 17:09:20.071  7111  7111 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-24 17:09:20.072  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-24 17:09:20.072  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-24 17:09:20.073  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.073  7111  7111 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-24 17:09:20.074  7111  7111 V BluetoothMapService: BluetoothMapBinder()
08-24 17:09:20.074  7111  7111 D BluetoothMapService: Received start request. Starting profile...
08-24 17:09:20.075  7111  7111 D BluetoothMapService: start()
,08-24 17:09:20.077  7076  7654 V FormManager: Network unavailable.
08-24 17:09:20.078  7111  7111 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-24 17:09:20.078  7111  7111 D BluetoothMapEmailAppObserver: createReceiver()
08-24 17:09:20.080  7310  7310 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:20
08-24 17:09:20.081  7111  7111 D BluetoothMapEmailAppObserver: initObservers()
08-24 17:09:20.082  7111  7111 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-24 17:09:20.082  7310  7310 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 17:09:20.082  7310  7310 D Weather.Utils: 2 : All the weather widget is gone.
08-24 17:09:20.082  7310  7310 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 17:09:20.082  7076  7654 V FormManager: Network unavailable.
08-24 17:09:20.082  7310  7310 D WeatherAncestor: connectivity changed - connection : true
08-24 17:09:20.082  7310  7310 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1fd06ead
08-24 17:09:20.083  7310  7310 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-24 17:09:20.083  7310  7310 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-24 17:09:20.083  7310  7310 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-24 17:09:20.083  7310  7310 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-24 17:09:20.083  7310  7310 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:20
08-24 17:09:20.086  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
,08-24 17:09:20.089  7111  7111 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:20.090  7111  7629 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 17:09:20.090  7111  7629 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 17:09:20.091  7111  7629 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 17:09:20.092  7111  7111 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:20.094  7111  7111 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:20.096  7111  7111 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:20.099  7111  7111 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:20.099  7111  7111 V PanService: [BTUI] SIM Extra State :ABSENT
,08-24 17:09:20.101  7111  7111 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 17:09:20.101  7111  7111 V BluetoothMapService: Handler(): got msg=1
08-24 17:09:20.102  7111  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-24 17:09:20.102  7111  7588 I bluedroid-qcom: enable
08-24 17:09:20.102  7111  7658 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 17:09:20.102  7111  7658 I bt-btu  : btu_task pending for preload complete event
08-24 17:09:20.102  7111  7588 I bt_hci_bdroid: init
08-24 17:09:20.103  7111  7111 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.104  7111  7588 I bt_vendor: bt-vendor : init
08-24 17:09:20.104  7111  7588 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 17:09:20.104  7111  7588 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 17:09:20.104  7111  7588 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 17:09:20.104  7111  7588 D bt_userial_mct: userial_init
08-24 17:09:20.104  7111  7588 D bt_hci_bdroid: set_power 1
08-24 17:09:20.104  7111  7588 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 17:09:20.104  7111  7588 I bt_vendor: Starting hciattach daemon
08-24 17:09:20.104  7111  7588 I bt_vendor: try to set true
08-24 17:09:20.105  7111  7111 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:20.105  7111  7111 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 17:09:20.105  7111  7111 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 17:09:20.105  7111  7111 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.105  7111  7111 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 17:09:20.099  7661  7661 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:20.099  7661  7661 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:20.117  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 17:09:20.177  7668  7668 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-24 17:09:20.190  7669  7669 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 17:09:20.230  7671  7671 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 17:09:20.243  7672  7672 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-24 17:09:20.256  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-24 17:09:20.270  7674  7674 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-24 17:09:20.307  7676  7676 I libmdmdetect: ESOC framework not supported
08-24 17:09:20.309  7676  7676 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-24 17:09:20.318  7676  7676 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-24 17:09:20.318  7676  7676 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-24 17:09:20.318  7676  7676 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 17:09:20.318  7676  7676 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 17:09:20.318  7676  7676 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-24 17:09:20.318  7676  7676 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-24 17:09:20.318  7676  7676 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 17:09:20.361  7676  7677 E QC-QMI  : qmi_client [7676] 14: failed to locate client data
08-24 17:09:20.362   466   466 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 17:09:20.362   466   466 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-24 17:09:20.411  7678  7678 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 17:09:20.432  7682  7682 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-24 17:09:20.457  7111  7588 I bt_vendor: bluetooth satus is on
08-24 17:09:20.457  7111  7588 D bt_hci_bdroid: preload
08-24 17:09:20.457  7111  7660 D bt_userial_mct: userial_open(port:0)
08-24 17:09:20.457  7111  7660 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-24 17:09:20.461  7111  7660 I bt_vendor: Done intiailizing UART
08-24 17:09:20.462  7111  7660 I bt_vendor: Done intiailizing UART
08-24 17:09:20.462  7111  7660 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 17:09:20.462  7111  7660 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 17:09:20.462  7111  7687 D bt_userial_mct: Entering userial_read_thread()
08-24 17:09:20.462  7111  7658 I bt-btu  : btu_task received preload complete event
08-24 17:09:20.463  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-24 17:09:20.463  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-24 17:09:20.465  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 17:09:20.468  7111  7658 I         : BTE_InitTraceLevels -- TRC_BTIF
08-24 17:09:20.531  7111  7658 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-24 17:09:20.531  7111  7658 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0154061 
08-24 17:09:20.531  7111  7658 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0154061 
,08-24 17:09:20.550  7111  7592 E bt-btif : Calling BTA_HhEnable
08-24 17:09:20.550  7111  7592 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-24 17:09:20.553  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-24 17:09:20.553  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-24 17:09:20.553  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 17:09:20.553  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-24 17:09:20.553  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 17:09:20.553  7111  7592 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 17:09:20.554  7111  7592 D BluetoothAdapterProperties: Name is: G3
08-24 17:09:20.555  7111  7592 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:09:20.556  7111  7592 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:09:20.556  7111  7592 D bt_hci_bdroid: postload
08-24 17:09:20.556  7111  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:20.556  7111  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:20.557  7111  7658 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-24 17:09:20.557  7111  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:20.557  7111  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:20.558  7111  7592 D bte_conf: Device ID record 1 : primary
08-24 17:09:20.558  7111  7592 D bte_conf:   vendorId            = 00c4
08-24 17:09:20.558  7111  7592 D bte_conf:   vendorIdSource      = 0001
08-24 17:09:20.558  7111  7592 D bte_conf:   product             = 13a1
08-24 17:09:20.558  7111  7592 D bte_conf:   version             = 1000
08-24 17:09:20.558  7111  7592 D bte_conf:   clientExecutableURL = 
08-24 17:09:20.558  7111  7592 D bte_conf:   serviceDescription  = 
08-24 17:09:20.558  7111  7592 D bte_conf:   documentationURL    = 
08-24 17:09:20.558  7111  7592 D bte_conf: bte_load_did_conf no section named DID2.
08-24 17:09:20.559  7111  7660 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:20.562  7111  7687 E bt_mct  : hci lib postload completed
,08-24 17:09:20.567  7111  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 17:09:20.567  7111  7588 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:09:20.567  7111  7588 D BluetoothAdapterProperties: State =  11
08-24 17:09:20.567  7111  7588 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 17:09:20.567  7111  7588 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-24 17:09:20.568  7111  7588 D BluetoothAdapterProperties: Setting state to 12
08-24 17:09:20.568  7111  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 17:09:20.568  7111  7592 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 17:09:20.569  7111  7592 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 17:09:20.569  7692  7692 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:20.569  7692  7692 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:20.574  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:20.575  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 17:09:20.575  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-24 17:09:20.578  7111  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:20.578  7111  7658 W bt-smp  : Plain text(LSB ~ MSB) = b6 0c 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:20.578  7111  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = ef 99 a7 12 53 77 9b 87 5e e4 aa a5 1c be 79 91 
08-24 17:09:20.579  7111  7658 W bt-btm  : Stopping oneshot timer
08-24 17:09:20.581  7111  7588 I BluetoothAdapterState: Entering On State
08-24 17:09:20.582  1841  2703 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:09:20.589  7111  7588 D LGBluetoothServiceAdapter: [BTUI] OnState
08-24 17:09:20.589  7111  7588 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 17:09:20.589  7111  7588 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-24 17:09:20.593  7111  7588 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 17:09:20.604  7111  7592 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:09:20.604  7111  7592 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-24 17:09:20.616  7111  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:20.616  7111  7658 W bt-smp  : Plain text(LSB ~ MSB) = bc 86 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:20.616  7111  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = 6f 0b 21 d1 24 71 d5 b8 d1 09 ba 1c 12 57 b5 7d 
08-24 17:09:20.616  7111  7658 W bt-btm  : Stopping oneshot timer
08-24 17:09:20.618  1841  1841 D BluetoothHeadset: Proxy object connected
,08-24 17:09:20.623  1841  4392 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:09:20.628  1841  1841 D BluetoothHeadset: Proxy object connected
08-24 17:09:20.631  7111  7588 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-24 17:09:20.638  7111  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:20.638  7111  7658 W bt-smp  : Plain text(LSB ~ MSB) = 98 48 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:20.638  7111  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = 31 8c 70 b0 56 79 51 36 53 6c 86 54 50 e0 00 78 
08-24 17:09:20.639  7111  7658 W bt-btm  : Stopping oneshot timer
08-24 17:09:20.678  7697  7697 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-24 17:09:20.686  6992  7270 D BluetoothMap: onBluetoothStateChange: up=true
08-24 17:09:20.689  1841  1856 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:09:20.696  1841  1841 D BluetoothHeadset: Proxy object connected
08-24 17:09:20.697  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:09:20.698  1038  1038 D BluetoothHeadset: Proxy object connected
,08-24 17:09:20.702  7111  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:20.702  7111  7658 W bt-smp  : Plain text(LSB ~ MSB) = 9b 3c 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:20.702  7111  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = 92 a3 40 f0 44 39 45 bf d1 c6 ed 34 6e 0e dc 83 
08-24 17:09:20.702  7111  7658 W bt-btm  : Stopping oneshot timer
08-24 17:09:20.702  6992  7270 D BluetoothPan: onBluetoothStateChange on: true
08-24 17:09:20.702  6992  7270 D BluetoothPan: onBluetoothStateChange call bindService
08-24 17:09:20.702  6992  6992 D BluetoothMap: Proxy object connected
08-24 17:09:20.702  6992  6992 D MapProfile: Bluetooth service connected
08-24 17:09:20.702  6992  6992 D BluetoothMap: getConnectedDevices()
08-24 17:09:20.709  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7595
08-24 17:09:20.710  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7596
08-24 17:09:20.710  6992  7008 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 17:09:20.711  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7599
08-24 17:09:20.711  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7600
08-24 17:09:20.712  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7606
08-24 17:09:20.712  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7609
08-24 17:09:20.712  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:09:20.712  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7610
08-24 17:09:20.713  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7623
08-24 17:09:20.714  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7684
08-24 17:09:20.714  1038  1101 W ProcessCpuTracker: Skipping unknown process pid 7688
08-24 17:09:20.715  1038  1038 D BluetoothA2dp: Proxy object connected
08-24 17:09:20.722  6992  7007 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 17:09:20.723  7111  7126 V BluetoothMapService: getConnectedDevices()
08-24 17:09:20.726  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 17:09:20.726  7111  7658 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:20.727  7111  7658 W bt-smp  : Plain text(LSB ~ MSB) = f1 07 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:20.727  7111  7658 W bt-smp  : Encrypted text(LSB ~ MSB) = d0 dd 13 35 72 93 d9 70 af a6 71 fd 1b 31 2c 9b 
08-24 17:09:20.727  7111  7658 W bt-btm  : Stopping oneshot timer
08-24 17:09:20.727  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
,08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:20.733  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:20.739  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:20.742  1038  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 17:09:20.742  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-24 17:09:20.745  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-24 17:09:20.745  1038  1120 D BluetoothManagerService: Message: 40
08-24 17:09:20.745  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-24 17:09:20.746  6992  6992 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:09:20.746  6992  6992 D PanProfile: Bluetooth service connected
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:20.747  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:20.749  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:20.750  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 17:09:20.755  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.755  1928  2091 D LGBluetoothAPIService: Message: 1
08-24 17:09:20.755  1928  2091 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-24 17:09:20.758  6862  6862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 17:09:20.761  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:20.763  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:20.765  7111  7111 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.765  7111  7111 D BluetoothMapService: STATE_ON
08-24 17:09:20.767  1928  2091 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-24 17:09:20.767  6992  6992 D BluetoothInputDevice: Proxy object connected
08-24 17:09:20.767  6992  6992 D HidProfile: Bluetooth service connected
08-24 17:09:20.770  6992  6992 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-24 17:09:20.776  1038  1120 D BluetoothManagerService: Message: 30
08-24 17:09:20.779  6992  6992 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-24 17:09:20.782  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.782  7111  7111 V BluetoothPbapService: Pbap Service onCreate
08-24 17:09:20.782  1038  1120 D BluetoothManagerService: Message: 30
08-24 17:09:20.782  7111  7111 V BluetoothPbapService: Starting PBAP service
,08-24 17:09:20.784  7111  7111 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 17:09:20.785  7111  7111 V BluetoothMapService: Handler(): got msg=1
08-24 17:09:20.785  7111  7111 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 17:09:20.786  7111  7111 V BluetoothPbapService: Pbap Service onBind
08-24 17:09:20.786  7111  7111 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.787  7111  7111 V BluetoothPbapService: state: 12
08-24 17:09:20.788  6992  6992 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-24 17:09:20.788  7111  7111 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 17:09:20.788  7111  7111 D LGBluetoothAPIServer: [BTUI] onBind()
08-24 17:09:20.789  7111  7716 D BluetoothMapMasInstance: MAS initSocket()
08-24 17:09:20.789  7111  7716 D BluetoothMapMasInstance:   masId = 00
08-24 17:09:20.789  7111  7716 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 17:09:20.789  7111  7716 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 17:09:20.789  7111  7716 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 17:09:20.790  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-24 17:09:20.790  1928  2091 D LGBluetoothAPIService: Message: 100
08-24 17:09:20.790  1928  2091 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-24 17:09:20.791  7111  7111 V BluetoothPbapService: Handler(): got msg=1
08-24 17:09:20.791  6992  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 17:09:20.791  1038  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:20.791  7111  7111 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 17:09:20.792  7111  7716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:20.796  7111  7111 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 17:09:20.796  7111  7111 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.796  7111  7111 V BluetoothPbapReceiver: ***********state = 12
08-24 17:09:20.796  7111  7592 D BluetoothAdapterProperties: Scan Mode:21
,08-24 17:09:20.796  7111  7592 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-24 17:09:20.798  6992  6992 D BluetoothA2dp: Proxy object connected
08-24 17:09:20.799  7111  7716 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 17:09:20.799  7111  7716 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 17:09:20.799  7111  7716 D BluetoothMapMasInstance: Accepting socket connection...
08-24 17:09:20.800  7111  7717 V BluetoothPbapService: Pbap Service initSocket
08-24 17:09:20.800  6992  6992 D A2dpProfile: Bluetooth service connected
08-24 17:09:20.803  1038  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:20.803  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 17:09:20.803  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:20.804  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:20.804  2146  2146 D c       : Getting all permits...
08-24 17:09:20.805  2146  2146 D a       : Opening database...
08-24 17:09:20.805  7111  7717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:20.807  7111  7717 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 17:09:20.807  7111  7717 V BluetoothPbapService: Succeed to create listening socket 
08-24 17:09:20.807  7111  7717 V BluetoothPbapService: Accepting socket connection...
08-24 17:09:20.807  6992  6992 D BluetoothHeadset: Proxy object connected
08-24 17:09:20.809  6992  6992 D HeadsetProfile: Bluetooth service connected
,08-24 17:09:20.812  6992  6992 D BluetoothPbap: Proxy object connected
08-24 17:09:20.813  6992  6992 D PbapServerProfile: Bluetooth service connected
08-24 17:09:20.813  2146  2146 D a       : Opening database auth.proximity.permit_store...
08-24 17:09:20.814  2146  2146 D a       : Closing database...
08-24 17:09:20.819  6992  6992 D DockEventReceiver: finishStartingService: stopping service
08-24 17:09:20.827  6992  6992 D BluetoothPermissionRequest: onReceive
,08-24 17:09:20.829  6992  6992 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 17:09:20.831  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 17:09:20.835  7111  7111 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-24 17:09:20.837  7111  7111 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-24 17:09:20.844  7111  7111 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-24 17:09:20.864  7111  7111 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-24 17:09:20.865  7111  7111 V BtOppService: onCreate
,08-24 17:09:20.869  7111  7111 V BluetoothOppNotification: send message
08-24 17:09:20.873  7111  7111 V BtOppService: Starting RfcommListener
08-24 17:09:20.879  7111  7111 D BluetoothOppPreference: Dumping Names:  
,08-24 17:09:20.879  7111  7111 D BluetoothOppPreference: {}
08-24 17:09:20.879  7111  7111 D BluetoothOppPreference: Dumping Channels:  
08-24 17:09:20.879  7111  7111 D BluetoothOppPreference: {}
08-24 17:09:20.881  7111  7111 V BtOppService: onStartCommand
08-24 17:09:20.881  7111  7725 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 17:09:20.883  7111  7725 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 17:09:20.886  7111  7725 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1559343e on behalf of 
08-24 17:09:20.886  7111  7722 V BtOppService: Deleted complete outbound shares, number =  0
,08-24 17:09:20.887  7111  7725 V BluetoothOppNotification: update too frequent, put in queue
08-24 17:09:20.889  7111  7111 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.889  7111  7111 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 17:09:20.889  7111  7722 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 17:09:20.889  7111  7725 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 17:09:20.890  7111  7722 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-24 17:09:20.890  7111  7725 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 17:09:20.891  7111  7722 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ada529f on behalf of 
08-24 17:09:20.893  7111  7111 V BluetoothOppNotification: new notify threadi!
08-24 17:09:20.894  7111  7725 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a1bcfec on behalf of 
08-24 17:09:20.895  7111  7111 V BluetoothOppNotification: send delay message
,08-24 17:09:20.896  7111  7725 V BluetoothOppNotification: update too frequent, put in queue
08-24 17:09:20.896  7111  7111 V BtOppService: start RfcommListener
08-24 17:09:20.899  7111  7726 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 17:09:20.900  7111  7725 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 17:09:20.901  7111  7111 V BtOppService: RfcommListener started
08-24 17:09:20.901  7111  7111 V BtOppService: ContentObserver received notification
08-24 17:09:20.902  7111  7111 V BtOppService: ContentObserver received notification
08-24 17:09:20.902  7111  7726 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b99fb5 on behalf of 
08-24 17:09:20.903  7111  7728 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 17:09:20.904  7111  7728 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 17:09:20.904  7111  7726 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 17:09:20.905  7111  7726 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 17:09:20.906  7111  7728 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fb0564a on behalf of 
08-24 17:09:20.907  7111  7728 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 17:09:20.908  7111  7726 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f9b79bb on behalf of 
08-24 17:09:20.909  7111  7726 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-24 17:09:20.911  7111  7727 V BtOppRfcommListener: Starting RFCOMM listener....
08-24 17:09:20.912  1038  1591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:20.912  7111  7726 V BluetoothOppNotification: outbound notification was removed.
08-24 17:09:20.913  7111  7726 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 17:09:20.913  7111  7727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:20.915  7111  7727 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-24 17:09:20.915  7111  7727 V BtOppRfcommListener: Started RFCOMM listener....
08-24 17:09:20.915  7111  7727 I BtOppRfcommListener: Accept thread started.
08-24 17:09:20.915  7111  7727 V BtOppRfcommListener: Accepting connection...
08-24 17:09:20.916  7111  7726 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15ebfed8 on behalf of 
08-24 17:09:20.917  7111  7726 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 17:09:20.920  7111  7726 V BluetoothOppNotification: inbound notification was removed.
08-24 17:09:20.920  7111  7726 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-24 17:09:20.922  7111  7726 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30318231 on behalf of 
08-24 17:09:20.929  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.929  7111  7111 V BluetoothFtpService: Ftp Service onCreate
08-24 17:09:20.929  7111  7111 I BluetoothFtpService: Ftp Service onCreate
08-24 17:09:20.929  7111  7111 V BluetoothFtpService: Ftp Service onStartCommand
08-24 17:09:20.929  7111  7111 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.929  7111  7111 V BluetoothFtpService: Starting Listening on sockets
08-24 17:09:20.930  7111  7111 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:20.930  7111  7111 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 17:09:20.930  7111  7111 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 17:09:20.930  7111  7111 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.930  7111  7111 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 17:09:20.930  7111  7111 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 17:09:20.932  7111  7111 V BluetoothFtpService: Handler(): got msg=1
,08-24 17:09:20.933  7111  7111 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,08-24 17:09:20.933  7111  7111 V BluetoothFtpService: Ftp Service initSocket
08-24 17:09:20.937  1038  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:20.938  7111  7111 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:20.942  7111  7111 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-24 17:09:20.942  7111  7111 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 17:09:20.944  7111  7730 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 17:09:20.946  7344  7377 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-24 17:09:20.967  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:20.968  7111  7111 V BluetoothSapService: Sap Service onCreate
,08-24 17:09:20.970  7111  7111 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:20.970  7111  7111 V BluetoothSapService: state: 12
08-24 17:09:20.970  7111  7111 V BluetoothSapService: Starting SAP server process
08-24 17:09:20.972  7111  7111 V BluetoothSapService: SAP Service startRfcommListenerThread
08-24 17:09:20.969  7732  7732 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:20.974  7111  7733 V BluetoothSapService: Sap Service initRfcommSocket
08-24 17:09:20.969  7732  7732 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:20.974  1038  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:20.975  7111  7733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:20.977  7111  7733 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-24 17:09:20.977  7111  7733 V BluetoothSapService: Succeed to create listening socket 
08-24 17:09:20.977  7111  7733 V BluetoothSapService: Accepting socket connection...
08-24 17:09:20.985  7732  7732 V BT_SAP  : Event pipe created
08-24 17:09:20.985  7732  7732 V BT_SAP  : create_server_socket qcom.sap.server
08-24 17:09:20.986  7732  7732 V BT_SAP  : created socket fd 6
,08-24 17:09:21.543  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:09:21.543  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:09:21.594  1038  1379 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-24 17:09:21.596  1038  1379 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-24 17:09:21.773  1038  1726 I ActivityManager: Killing 7514:com.lge.bnr/1000 (adj 15): empty #17
,08-24 17:09:21.805  1038  2020 W libprocessgroup: failed to open /acct/uid_1000/pid_7514/cgroup.procs: No such file or directory
,08-24 17:09:21.897  7111  7111 V BluetoothOppNotification: new notify threadi!
,08-24 17:09:21.897  7111  7111 V BluetoothOppNotification: send delay message
,08-24 17:09:21.911  7111  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 17:09:21.913  7111  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11e564a2 on behalf of 
08-24 17:09:21.914  7111  7743 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 17:09:21.915  7111  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-24 17:09:21.919  7111  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa16533 on behalf of 
08-24 17:09:21.919  7111  7743 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 17:09:21.922  7111  7743 V BluetoothOppNotification: outbound notification was removed.
08-24 17:09:21.923  7111  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 17:09:21.924  7111  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bffd0f0 on behalf of 
08-24 17:09:21.925  7111  7743 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 17:09:21.927  7111  7743 V BluetoothOppNotification: inbound notification was removed.
08-24 17:09:21.927  7111  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 17:09:21.928  7111  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27354669 on behalf of 
,08-24 17:09:22.017  1038  1910 I ActivityManager: Killing 6974:com.lge.sync/1000 (adj 15): empty #17
,08-24 17:09:22.049  1038  1432 D WifiService: Client connection lost with reason: 4
,08-24 17:09:22.061  1038  2020 W libprocessgroup: failed to open /acct/uid_1000/pid_6974/cgroup.procs: No such file or directory
,08-24 17:09:22.543  1038  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:22.544  1038  1563 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@106c2f15 mBinding = false
,08-24 17:09:22.574  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:22.575  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 17:09:22.575  1038  1038 D Ulp_jni : JNI:system_update. Event-4
,08-24 17:09:22.578  1038  1120 D BluetoothManagerService: Message: 2
08-24 17:09:22.579  1038  1120 D BluetoothManagerService: Sending off request.
08-24 17:09:22.580  7111  7127 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-24 17:09:22.581  7111  7588 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-24 17:09:22.581  7111  7588 D BluetoothAdapterProperties: Setting state to 13
08-24 17:09:22.581  7111  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:09:22.582  7111  7588 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 17:09:22.582  7111  7588 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 17:09:22.584  7111  7592 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:09:22.585  7111  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-24 17:09:22.587  7111  7716 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-24 17:09:22.590  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-24 17:09:22.590  7111  7658 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-24 17:09:22.594  7111  7717 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:22.595  7111  7727 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:22.595  7111  7733 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:22.595  7111  7730 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:09:22.596  7111  7588 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 17:09:22.600  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-24 17:09:22.602  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-24 17:09:22.602  7111  7658 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 17:09:22.611  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:22.611  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:09:22.615  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:22.615  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:22.621  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:22.621  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:22.621  6862  6862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:09:22.621  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:22.623  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:22.623  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-24 17:09:22.623  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-24 17:09:22.627  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.629  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 17:09:22.633  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:22.635  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:22.639  7111  7111 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.639  7111  7111 D BluetoothMapService: STATE_TURNING_OFF
08-24 17:09:22.639  7111  7111 V BluetoothMapService: Handler(): got msg=4
08-24 17:09:22.639  7111  7111 D BluetoothMapService: MAP Service closeService in
08-24 17:09:22.639  7111  7111 D BluetoothMapMasInstance: MAP Service shutdown
08-24 17:09:22.639  7111  7111 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 17:09:22.639  7111  7111 V BluetoothMapService: MAP Service closeService out
08-24 17:09:22.642  7111  7111 V BtOppService: Receiver DISABLED_ACTION 
08-24 17:09:22.642  7111  7111 I BtOppRfcommListener: stopping Accept Thread
08-24 17:09:22.642  7111  7111 V BtOppRfcommListener: close mBtServerSocket
08-24 17:09:22.643  7111  7727 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 17:09:22.643  7111  7111 V BtOppRfcommListener: waiting for thread to terminate
08-24 17:09:22.643  7111  7111 V BtOppRfcommListener: done waiting for thread to terminate
08-24 17:09:22.647  6992  6992 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-24 17:09:22.658  6992  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-24 17:09:22.661  7111  7111 V BtOppService: onDestroy
08-24 17:09:22.663  7111  7111 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-24 17:09:22.667  7111  7111 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 17:09:22.667  7111  7111 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.667  7111  7111 V BluetoothPbapReceiver: ***********state = 13
08-24 17:09:22.670  7111  7111 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-24 17:09:22.674  7111  7111 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.674  7111  7111 V BluetoothPbapService: state: 13
08-24 17:09:22.674  7111  7111 V BluetoothPbapService: Pbap Service closeService in
08-24 17:09:22.676  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 17:09:22.678  7111  7111 V BluetoothPbapService: successfully stopped pbap service
08-24 17:09:22.678  7111  7111 V BluetoothPbapService: Pbap Service closeService out
08-24 17:09:22.679  7111  7111 V BluetoothPbapService: Pbap Service onDestroy
08-24 17:09:22.679  7111  7111 V BluetoothPbapService: Pbap Service closeService in
08-24 17:09:22.679  7111  7111 V BluetoothPbapService: Pbap Service closeService out
08-24 17:09:22.679  7111  7111 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-24 17:09:22.698  6992  6992 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:09:22.716  6992  6992 D BluetoothPbap: Proxy object disconnected
08-24 17:09:22.716  6992  6992 D PbapServerProfile: Bluetooth service disconnected
,08-24 17:09:22.722  6992  6992 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-24 17:09:22.728  6992  6992 D BluetoothPermissionRequest: onReceive
,08-24 17:09:22.728  6992  6992 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-24 17:09:22.737  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 17:09:22.741  7111  7111 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-24 17:09:22.741  7111  7111 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-24 17:09:22.742  7111  7111 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-24 17:09:22.749  7111  7111 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.749  7111  7111 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 17:09:22.750  7111  7111 V BluetoothFtpService: Ftp Service onStartCommand
08-24 17:09:22.750  7111  7111 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.751  7111  7111 V BluetoothFtpService: Ftp Service closeService
08-24 17:09:22.751  7111  7111 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-24 17:09:22.754  7111  7111 V BluetoothFtpService: successfully stopped ftp service
08-24 17:09:22.755  7111  7111 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:22.755  7111  7111 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-24 17:09:22.755  7111  7111 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 17:09:22.755  7111  7111 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.755  7111  7111 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-24 17:09:22.755  7111  7111 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 17:09:22.757  7111  7111 V BluetoothFtpService: Ftp Service onDestroy
08-24 17:09:22.757  7111  7111 V BluetoothFtpService: Ftp Service closeService
08-24 17:09:22.762  7111  7111 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:22.762  7111  7111 V BluetoothSapService: state: 13
08-24 17:09:22.762  7111  7111 V BluetoothSapService: Stopping SAP server process
08-24 17:09:22.764  7111  7111 V BluetoothSapService: Sap Service closeSapService in
08-24 17:09:22.764  7111  7111 V BluetoothSapService: Close listen Socket : 
08-24 17:09:22.764  7111  7111 V BluetoothSapService: Close rfcomm Socket : 
08-24 17:09:22.764  7111  7111 V BluetoothSapService: Close sapd  Socket : 
08-24 17:09:22.765  7111  7111 V BluetoothSapService: Sap Service closeSapService out
08-24 17:09:22.766  7111  7111 V BluetoothSapService: Sap Service onDestroy
08-24 17:09:22.766  7111  7111 V BluetoothSapService: Sap Service closeSapService in
08-24 17:09:22.766  7111  7111 V BluetoothSapService: Close listen Socket : 
08-24 17:09:22.766  7111  7111 V BluetoothSapService: Close rfcomm Socket : 
08-24 17:09:22.766  7111  7111 V BluetoothSapService: Close sapd  Socket : 
08-24 17:09:22.767  7111  7111 V BluetoothSapService: Sap Service closeSapService out
,08-24 17:09:23.498  7111  7592 D bt_hci_bdroid: cleanup
,08-24 17:09:23.505  7111  7660 I bt_lpm  : LPM is already off!!!
,08-24 17:09:23.506  7111  7687 I bt_userial_mct: exiting userial_read_thread
08-24 17:09:23.506  7111  7687 D bt_userial_mct: Leaving userial_evt_read_thread()
08-24 17:09:23.507  7111  7658 W bt-btif : ag scb idx 1 not allocated
08-24 17:09:23.507  7111  7658 E bt-btif : BTA AG is already disabled, ignoring ...
08-24 17:09:23.507  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017,
,08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
,08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b,
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-24 17:09:23.508  7111  7658 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-24 17:09:23.509  7111  7658 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-24 17:09:23.509  7111  7658 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:09:23.509  7111  7658 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-24 17:09:23.512  7111  7592 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-24 17:09:23.512  7111  7660 I bt_vendor: hw_epilog_process
08-24 17:09:23.516  7111  7592 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-24 17:09:23.516  7111  7592 D bt_userial_mct: userial_close
08-24 17:09:23.516  7111  7592 E bt_userial_mct: pthread_join() FAILED result:3
08-24 17:09:23.516  7111  7592 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-24 17:09:23.540  7111  7592 D bt_hci_bdroid: set_power 0,
08-24 17:09:23.540  7111  7592 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-24 17:09:23.540  7111  7592 I bt_vendor: bluetooth satus is on
08-24 17:09:23.540  7111  7592 I bt_vendor: bt-vendor : resetting BT status
08-24 17:09:23.540  7111  7592 I bt_vendor: Starting hciattach daemon
,08-24 17:09:23.540  7111  7592 I bt_vendor: try to set false
08-24 17:09:23.543  7111  7592 I bt_vendor: Starting hciattach daemon
08-24 17:09:23.543  7111  7592 I bt_vendor: try to set false
,08-24 17:09:23.546  7111  7592 I bt_vendor: cleanup
08-24 17:09:23.547  7111  7658 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-24 17:09:23.547  7111  7592 I GKI_LINUX: GKI_exit_task 0 done
08-24 17:09:23.547  7111  7592 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-24 17:09:23.549  7111  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 17:09:23.553  7111  7111 D HeadsetService: Received stop request...Stopping profile...
08-24 17:09:23.556  7111  7111 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-24 17:09:23.556  7111  7111 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 17:09:23.556  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
,08-24 17:09:23.558  7111  7629 D HeadsetStateMachine: Exit Disconnected: -1
08-24 17:09:23.563  7111  7588 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 17:09:23.564  1038  1038 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:23.564  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 17:09:23.565  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:23.565  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:23.565  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-24 17:09:23.567  7111  7111 D A2dpService: Received stop request...Stopping profile...
08-24 17:09:23.567  7111  7643 D A2dpStateMachine: Exit Disconnected: -1
,08-24 17:09:23.571  7111  7111 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-24 17:09:23.573  7111  7111 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-24 17:09:23.573  7111  7111 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 17:09:23.573  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:23.575  1038  1038 D BluetoothA2dp: Proxy object disconnected
08-24 17:09:23.575  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 17:09:23.575  7111  7111 D HidService: Received stop request...Stopping profile...
08-24 17:09:23.575  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:23.577  7111  7111 D HeadsetStateMachine: Unbinding service...
08-24 17:09:23.581  7111  7111 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 17:09:23.581  7111  7111 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 17:09:23.581  7111  7111 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 17:09:23.581  7111  7111 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 17:09:23.581  7111  7111 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 17:09:23.581  7111  7111 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 17:09:23.581  7111  7111 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-24 17:09:23.585  7111  7111 D HealthService: Received stop request...Stopping profile...
08-24 17:09:23.585  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:23.587  7111  7111 D PanService: Received stop request...Stopping profile...
08-24 17:09:23.587  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:23.588  7111  7111 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 17:09:23.589  7111  7111 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 17:09:23.589  7111  7111 D BtGatt.GattService: stop()
08-24 17:09:23.589  7111  7111 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 17:09:23.591  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:23.593  7111  7111 D BluetoothMapService: Received stop request...Stopping profile...
08-24 17:09:23.593  7111  7111 D BluetoothMapService: stop()
,08-24 17:09:23.598  7111  7111 D BluetoothMapEmailAppObserver: deinitObservers()
08-24 17:09:23.598  7111  7111 D BluetoothMapEmailAppObserver: removeReceiver()
08-24 17:09:23.599  7111  7111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fd06ead
08-24 17:09:23.600  7111  7111 I BluetoothA2dpServiceJni: cleanupNative
08-24 17:09:23.601  7111  7644 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 17:09:23.601  7111  7111 I GKI_LINUX: GKI_exit_task 2 done
08-24 17:09:23.601  7111  7111 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 17:09:23.601  7111  7111 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 17:09:23.601  7111  7111 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 17:09:23.602  7111  7111 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 17:09:23.603  7111  7111 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:09:23.603  7111  7111 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:09:23.604  7111  7111 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 17:09:23.604  7111  7111 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 17:09:23.607  7111  7111 V BluetoothMapService: Handler(): got msg=4
08-24 17:09:23.607  7111  7111 D BluetoothMapService: MAP Service closeService in
08-24 17:09:23.607  7111  7111 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 17:09:23.607  7111  7111 V BluetoothMapService: MAP Service closeService out
,08-24 17:09:23.610  7111  7588 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-24 17:09:23.610  7111  7588 D BluetoothAdapterProperties: Setting state to 10
08-24 17:09:23.610  7111  7588 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 17:09:23.611  7111  7111 D BluetoothMapService: cleanup()
08-24 17:09:23.611  7111  7111 D BluetoothMapService: MAP Service closeService in
08-24 17:09:23.611  7111  7111 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-24 17:09:23.611  7111  7111 V BluetoothMapService: MAP Service closeService out
08-24 17:09:23.612  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:23.612  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-24 17:09:23.612  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-24 17:09:23.613  7111  7588 I BluetoothAdapterState: Entering OffState
08-24 17:09:23.613  6992  7008 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:09:23.614  1841  4394 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:23.615  1841  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:23.616  6992  7008 D BluetoothMap: onBluetoothStateChange: up=false
08-24 17:09:23.617  1841  2427 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:23.617  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:09:23.618  6992  7008 D BluetoothPan: onBluetoothStateChange on: false
08-24 17:09:23.618  6992  7008 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 17:09:23.622  6992  7008 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 17:09:23.622  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:09:23.622  6992  7008 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 17:09:23.623  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-24 17:09:23.623  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-24 17:09:23.626  1038  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-24 17:09:23.626  1038  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-24 17:09:23.626  1038  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@106c2f15 mBinding = false
08-24 17:09:23.627  1038  1120 D BluetoothManagerService: Sending unbind request.
08-24 17:09:23.632  7111  7592 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-24 17:09:23.634  7111  7111 I GKI_LINUX: GKI_exit_task 1 done
08-24 17:09:23.634  7111  7111 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-24 17:09:23.635  7111  7111 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 17:09:23.635  7111  7111 I art     : --- WEIRD: removing null entry 248
08-24 17:09:23.636  7111  7111 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-24 17:09:23.636  7111  7111 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-24 17:09:23.636  7111  7111 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-24 17:09:23.638  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-24 17:09:23.641  7111  7111 I art     : System.exit called, status: 0
08-24 17:09:23.641  7111  7111 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-24 17:09:23.660   316  2190 V AudioFlinger: 7111 died, releasing its sessions
08-24 17:09:23.660   316  2190 V AudioFlinger:  pid 1841 @ 0
08-24 17:09:23.660   316  2190 V AudioFlinger:  pid 3285 @ 1
08-24 17:09:23.660   316  2190 V AudioFlinger:  pid 3285 @ 2
,08-24 17:09:23.664  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-24 17:09:23.665  1928  2091 D LGBluetoothAPIService: Message: 101
08-24 17:09:23.665  1928  2091 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-24 17:09:23.665  1928  2091 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-24 17:09:23.665  1928  2091 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-24 17:09:23.667  6992  6992 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-24 17:09:23.669  1038  1946 I ActivityManager: Process com.android.bluetooth (pid 7111) has died
08-24 17:09:23.670  1038  1946 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-24 17:09:23.675  1038  1946 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13998ms
,08-24 17:09:23.681  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:23.682  1928  2091 D LGBluetoothAPIService: Message: 2
08-24 17:09:23.682  1928  2091 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,08-24 17:09:23.684  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:23.685  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:23.686  6992  6992 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-24 17:09:23.686  6992  6992 D LGBluetoothEventManager: [BTUI] clear device connection state
08-24 17:09:23.687  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-24 17:09:23.692  6992  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 17:09:23.700  1592  1592 D BluetoothAdapter: 274941007: getState() :  mService = null. Returning STATE_OFF
08-24 17:09:23.700  1592  1592 D BluetoothAdapter: 274941007: getState() :  mService = null. Returning STATE_OFF
,08-24 17:09:23.746  1038  1945 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7789 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-24 17:09:23.749  6992  6992 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:09:23.811  7789  7789 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-24 17:09:23.811  7789  7789 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:23.811  7789  7789 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-24 17:09:23.812  7789  7789 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 17:09:23.830  7789  7789 D BluetoothAdapterApp: Loading JNI Library
,08-24 17:09:23.858  7789  7789 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a2275f5 Instance Count = 1
,08-24 17:09:23.862  7789  7789 D BluetoothAdapterApp: onCreate
08-24 17:09:23.883  7789  7789 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-24 17:09:23.883  7789  7789 D ProfileConfigQcom: Adding HeadsetService
08-24 17:09:23.884  7789  7789 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-24 17:09:23.884  7789  7789 D ProfileConfigQcom: Adding A2dpService
08-24 17:09:23.885  7789  7789 D ProfileConfigQcom: [BTUI] HidService is supported
08-24 17:09:23.885  7789  7789 D ProfileConfigQcom: Adding HidService
08-24 17:09:23.886  7789  7789 D ProfileConfigQcom: [BTUI] HealthService is supported
08-24 17:09:23.886  7789  7789 D ProfileConfigQcom: Adding HealthService
08-24 17:09:23.887  7789  7789 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-24 17:09:23.888  7789  7789 D ProfileConfigQcom: [BTUI] PanService is supported
08-24 17:09:23.889  7789  7789 D ProfileConfigQcom: Adding PanService
08-24 17:09:23.890  7789  7789 D ProfileConfigQcom: [BTUI] GattService is supported
08-24 17:09:23.890  7789  7789 D ProfileConfigQcom: Adding GattService
08-24 17:09:23.891  7789  7789 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-24 17:09:23.891  7789  7789 D ProfileConfigQcom: Adding BluetoothMapService
08-24 17:09:23.892  7789  7789 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-24 17:09:23.894  7789  7789 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 17:09:23.896  7789  7789 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:23.897  7789  7789 V BluetoothPbapReceiver: ***********state = 10
,08-24 17:09:23.901  7789  7789 V LGMDMManagerInternal: Create singleton instance
,08-24 17:09:23.958  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:09:23.968  6992  6992 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-24 17:09:23.969  7789  7789 D LGBluetoothAPIServer: [BTUI] onCreate()
08-24 17:09:23.970  7789  7789 D LGBluetoothAPIServer: [BTUI] onBind()
08-24 17:09:23.977  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-24 17:09:23.978  1928  2091 D LGBluetoothAPIService: Message: 100
08-24 17:09:23.978  1928  2091 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-24 17:09:23.985  6992  6992 D BluetoothPermissionRequest: onReceive
08-24 17:09:23.988  6992  6992 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 17:09:23.988  6992  6992 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-24 17:09:23.990  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 17:09:23.998  7789  7789 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-24 17:09:24.007  7789  7789 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:09:24.018  7789  7789 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:24.019  7789  7789 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 17:09:24.020  7789  7789 V BluetoothSapReceiver: SapReceiver onReceive 
,08-24 17:09:24.024  7789  7789 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:24.026  7789  7789 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-24 17:09:24.033  7056  7056 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-24 17:09:25.654  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:09:25.655  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:09:25.943  1038  1368 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 17:09:25.956  1592  1592 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-24 17:09:25.990  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 17:09:26.039  1038  1038 D administrator: Handling package changes for user 0
,08-24 17:09:26.065  1038  1101 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7818 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-24 17:09:26.082  1592  1592 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-24 17:09:26.084  1592  1592 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-24 17:09:26.102   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 481us total 42.603ms
08-24 17:09:26.123   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 20.705ms
,08-24 17:09:26.142  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:26.142   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 490us total 18.902ms
08-24 17:09:26.162  7818  7818 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 17:09:26.181  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-24 17:09:26.181  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-24 17:09:26.241  1038  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 17:09:26.248  1038  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 17:09:26.257  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 17:09:26.257  2493  2493 V GmsNetworkLocationProvi: DISABLE
,08-24 17:09:26.267  7818  7818 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:26.268  7818  7818 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 17:09:26.287  2493  2493 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-24 17:09:26.377  7818  7863 I Babel   : MmsConfig: mnc/mcc: 0/0
08-24 17:09:26.377  7818  7863 I Babel   : MmsConfig.loadMmsSettings
08-24 17:09:26.382  7818  7863 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-24 17:09:26.382  7818  7863 I Babel   : MmsConfig.loadFromDatabase
,08-24 17:09:26.397  1038  1100 D LocationProviderProxy: applying state to connected service
08-24 17:09:26.398  7818  7863 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-24 17:09:26.398  7818  7863 I Babel   : MmsConfig.loadFromResources
08-24 17:09:26.401  7818  7863 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-24 17:09:26.404  7818  7863 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-24 17:09:26.410  7818  7861 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 17:09:26.412  7818  7818 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:26.412  7818  7861 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 17:09:26.414  7818  7861 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-24 17:09:26.422  7818  7861 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-24 17:09:26.425  7818  7861 W AudioCapabilities: Unsupported mime audio/qcelp
08-24 17:09:26.426  7818  7861 W AudioCapabilities: Unsupported mime audio/evrc
08-24 17:09:26.431  1805  7865 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-24 17:09:26.431  1805  7865 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-24 17:09:26.435  7173  7173 I AppUp4:CustModeStarterReceiver: onReceive
,08-24 17:09:26.439  7173  7173 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31461ad7
08-24 17:09:26.439  7173  7173 D AppUp4:CustFacade: isCustomizationCompleted : false
08-24 17:09:26.439  7173  7173 D AppUp4:CustFacade: isPhone : true
08-24 17:09:26.440  7173  7173 D AppUp4:CustModeStarterReceiver: begin check event
08-24 17:09:26.440  7173  7173 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-24 17:09:26.445  7818  7861 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-24 17:09:26.446  1805  5187 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-24 17:09:26.448  7818  7861 W VideoCapabilities: Unsupported mime video/divx
08-24 17:09:26.450  7818  7861 W VideoCapabilities: Unsupported mime video/divx311
,08-24 17:09:26.456  7818  7861 W VideoCapabilities: Unsupported mime video/divx4
08-24 17:09:26.461  7818  7861 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-24 17:09:26.469  1038  1054 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7868 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-24 17:09:26.473  1038  1053 I ActivityManager: Killing 6774:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-24 17:09:26.487  7037  7037 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-24 17:09:26.487  7037  7037 W System.err: android.os.DeadObjectException
08-24 17:09:26.487  7037  7037 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 17:09:26.487  7037  7037 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 17:09:26.487  7037  7037 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-24 17:09:26.487  7037  7037 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-24 17:09:26.487  7037  7037 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 17:09:26.487  7037  7037 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 17:09:26.487  7037  7037 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 17:09:26.487  7037  7037 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 17:09:26.487  7037  7037 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 17:09:26.487  7037  7037 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 17:09:26.488  7037  7037 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:09:26.488  7037  7037 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:09:26.488  7037  7037 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 17:09:26.488  7037  7037 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 17:09:26.488  7037  7037 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-24 17:09:26.488  7037  7037 W System.err: android.os.DeadObjectException
08-24 17:09:26.488  7037  7037 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 17:09:26.488  7037  7037 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 17:09:26.488  7037  7037 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-24 17:09:26.488  7037  7037 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-24 17:09:26.488  7037  7037 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-24 17:09:26.488  7037  7037 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-24 17:09:26.489  7037  7037 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 17:09:26.489  7037  7037 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 17:09:26.489  7037  7037 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 17:09:26.489  7037  7037 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 17:09:26.489  7037  7037 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:09:26.489  7037  7037 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:09:26.489  7037  7037 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 17:09:26.489  7037  7037 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 17:09:26.489  7037  7037 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-24 17:09:26.489  7037  7037 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()], oooooo Control unbind before rebinding.
,08-24 17:09:26.493  7818  7861 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-24 17:09:26.498  7818  7861 W AudioCapabilities: Unsupported mime audio/eac3
08-24 17:09:26.498  7818  7861 W AudioCapabilities: Unsupported mime audio/ac3
08-24 17:09:26.499  7818  7861 W AudioCapabilities: Unsupported mime audio/g726
08-24 17:09:26.500  7818  7861 W AudioCapabilities: Unsupported mime audio/wma-voice
08-24 17:09:26.501  7818  7861 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-24 17:09:26.502  7818  7861 W AudioCapabilities: Unsupported mime audio/adpcm
08-24 17:09:26.504  7818  7861 W VideoCapabilities: Unsupported mime video/theora
,08-24 17:09:26.505  7818  7861 W VideoCapabilities: Unsupported mime video/mjpg
08-24 17:09:26.680  1038  1053 E libprocessgroup: failed to kill 1 processes for processgroup 6774
,08-24 17:09:26.791  1038  1984 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-24 17:09:26.800  7037  7037 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-24 17:09:26.801  7037  7037 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 17:09:26.845  7868  7868 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:26.845  7868  7868 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:26.846  7868  7868 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-24 17:09:26.851  7868  7868 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-24 17:09:26.851  7868  7868 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 17:09:26.858  1038  1591 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7890 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 17:09:26.859  7037  7037 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-24 17:09:26.960  7890  7890 D UEI.SmartControl: Quickset Services start...
,08-24 17:09:26.961  7868  7868 I SystemConfig: BUILD Country: EU
08-24 17:09:26.961  7868  7868 I SystemConfig: BUILD Operator: OPEN
08-24 17:09:26.962  7890  7890 I UEI.SmartControl: Manufacture = LGE
08-24 17:09:26.962  7890  7890 D UEI.SmartControl: Id = LGNevo
08-24 17:09:26.963  7890  7890 D UEI.SmartControl: File observer start...
08-24 17:09:26.964  7890  7890 E UEI.SmartControl: IR Port is disabled: false
08-24 17:09:26.964  7890  7890 D UEI.SmartControl: Starting file observer...
08-24 17:09:26.965  7890  7890 D UEI.SmartControl: Extracting JNI libs...
08-24 17:09:26.965  7890  7890 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-24 17:09:27.031  1038  2021 I ActivityManager: Killing 7037:com.lge.qremote/u0a112 (adj 15): empty #17
,08-24 17:09:27.065  7890  7890 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-24 17:09:27.066  7890  7890 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-24 17:09:27.066  7890  7890 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-24 17:09:27.107  7890  7890 I UEI.SmartControl: --- Selecting new region: 6
,08-24 17:09:27.109  7890  7890 I UEI.SmartControl: Model = LG-D855
08-24 17:09:27.114  7890  7890 D UEI.SmartControl: QS Service created
08-24 17:09:27.118  1038  1762 W libprocessgroup: failed to open /acct/uid_10112/pid_7037/cgroup.procs: No such file or directory
08-24 17:09:27.134  7890  7890 I UEI.SmartControl: Service initServices...
,08-24 17:09:27.137  7868  7909 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-24 17:09:27.137  7868  7909 I SystemConfig: existFile = false
08-24 17:09:27.137  7868  7909 I SystemConfig: canReadFile = false
08-24 17:09:27.137  7890  7890 D UEI.SmartControl: QS start get config
08-24 17:09:27.137  7868  7909 I SystemConfig: systemFeature RCS result false
08-24 17:09:27.138  7868  7909 D SystemConfig: refreshRcsSupport() :false
08-24 17:09:27.172  7890  7890 D UEI.SmartControl: Loading JNI Libs...
,08-24 17:09:27.174  1038  2021 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7915 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-24 17:09:27.207  7915  7915 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:27.207  7915  7915 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 17:09:27.207  7915  7915 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 17:09:27.207  7915  7915 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-24 17:09:27.290  7915  7915 I AppConfig: Total System Memory = 2995761152
,08-24 17:09:27.300  7915  7915 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-24 17:09:27.381  1038  1984 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7936 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:09:27.382  1038  1984 I ActivityManager: Killing 7201:com.lge.email/u0a23 (adj 15): empty #17
,08-24 17:09:27.464  7890  7890 I UEI.SmartControl: Supports setup maps: true
,08-24 17:09:27.470  7890  7890 D UEI.SmartControl: QS start statue = true Error code = 0
,08-24 17:09:27.470  7890  7890 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 17:09:27.470  7890  7890 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 17:09:27.470  7890  7890 I UEI.SmartControl: ### init IR Blaster...
,08-24 17:09:27.477  7890  7890 D serial_port: Configuring serial port
,08-24 17:09:27.484  7890  7890 E UEI.SmartControl: UEIBLaster setting for 616
08-24 17:09:27.484  7890  7890 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 17:09:27.484  7890  7890 I UEI.SmartControl: configuring settings for MAXQ616
08-24 17:09:27.484  7890  7890 I UEI.SmartControl: Get version...
08-24 17:09:27.492  1038  1591 W libprocessgroup: failed to open /acct/uid_10023/pid_7201/cgroup.procs: No such file or directory
,08-24 17:09:27.504  7890  7956 D UEI.SmartControl: serial port data available: 21
08-24 17:09:27.533  7890  7890 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 17:09:27.533  7890  7890 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 17:09:27.533  7890  7890 I UEI.SmartControl: QS saving settings...
08-24 17:09:27.535  7890  7890 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 17:09:27.552  7890  7956 D UEI.SmartControl: serial port data available: 4
,08-24 17:09:27.590  7890  7890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-24 17:09:27.599  7890  7890 E UEI.SmartControl: Services init done
08-24 17:09:27.599  7890  7890 D UEI.SmartControl: QS Service init finished
08-24 17:09:27.603  7890  7961 I UEI.SmartControl: Device manager: loading config....
08-24 17:09:27.604  7890  7961 D UEI.SmartControl: ----------- loading internal config...
08-24 17:09:27.605  7890  7890 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 17:09:27.605  7890  7890 D UEI.SmartControl: QS Service version code: 201091
,08-24 17:09:27.608  7890  7890 D UEI.SmartControl: Service requested: Control
08-24 17:09:27.623  7890  7961 E UEI.SmartControl: Loading SETTINGS...
08-24 17:09:27.625  7890  7890 D UEI.SmartControl: Request IControl service: devices are loaded...
08-24 17:09:27.631  7890  7890 D UEI.SmartControl: Service.onUnbind: IControl
,08-24 17:09:27.632  7890  7890 D UEI.SmartControl: Service.onDestroy
08-24 17:09:27.632  7890  7890 D UEI.SmartControl: Lock is in USE false
08-24 17:09:27.633  7890  7890 D UEI.SmartControl: unbind internal service
08-24 17:09:27.633  7890  7890 D serial_port: close(fd = 25)
08-24 17:09:27.637  7890  7961 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 17:09:27.639  7890  7890 I UEI.SmartControl: Serial port is closed.
08-24 17:09:27.640  7890  7890 I UEI.SmartControl: Serial port is closed.
08-24 17:09:27.642  7890  7890 D UEI.SmartControl: Blaster closed
08-24 17:09:27.643  7890  7890 D UEI.SmartControl: Shut down QS...
08-24 17:09:27.643  7890  7890 D UEI.SmartControl: Stopping QS lib
08-24 17:09:27.643  7890  7890 D UEI.SmartControl: QS lib stop result = true
08-24 17:09:27.643  7890  7890 D UEI.SmartControl: Stopped QS lib
08-24 17:09:27.643  7890  7890 D UEI.SmartControl: Stopped file observer...
,08-24 17:09:27.643  7890  7890 D UEI.SmartControl: QS shutdown complete
,08-24 17:09:27.644  7890  7890 D UEI.SmartControl: QS Service created
08-24 17:09:27.647  7890  7959 I UEI.SmartControl: Notify AllClients services are ready: 11
08-24 17:09:27.647  7890  7959 D UEI.SmartControl: -----service ready thread exits
08-24 17:09:27.658  7890  7890 I UEI.SmartControl: Service initServices...
08-24 17:09:27.658  7890  7890 D UEI.SmartControl: QS start get config
08-24 17:09:27.659  7936  7936 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-24 17:09:27.736  7936  7936 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 17:09:27.736  7936  7936 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 17:09:27.774  7936  7936 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-24 17:09:27.789  7936  7936 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-24 17:09:27.789  7936  7936 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 17:09:27.822  7936  7936 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:09:27.822  7936  7936 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-24 17:09:27.832  1038  2039 I ActivityManager: Killing 7076:com.lge.formmanager/u0a26 (adj 15): empty #17
08-24 17:09:27.967  1038  1591 W libprocessgroup: failed to open /acct/uid_10026/pid_7076/cgroup.procs: No such file or directory
,08-24 17:09:27.979  5047  7987 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-24 17:09:28.037  1038  1762 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7991 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-24 17:09:28.048  2826  2843 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-24 17:09:28.052  2826  2843 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@10965ba8 on behalf of 7936
,08-24 17:09:28.073  7936  7936 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-24 17:09:28.093  7936  7936 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-24 17:09:28.118  7890  7890 I UEI.SmartControl: Supports setup maps: true
,08-24 17:09:28.132  7890  7890 D UEI.SmartControl: QS start statue = true Error code = 0
08-24 17:09:28.132  7890  7890 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 17:09:28.132  7890  7890 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 17:09:28.132  7890  7890 I UEI.SmartControl: ### init IR Blaster...
,08-24 17:09:28.135  7890  7890 D serial_port: Configuring serial port
08-24 17:09:28.136  7890  7890 E UEI.SmartControl: UEIBLaster setting for 616
08-24 17:09:28.136  7890  7890 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 17:09:28.136  7890  7890 I UEI.SmartControl: configuring settings for MAXQ616
08-24 17:09:28.136  7890  7890 I UEI.SmartControl: Get version...
08-24 17:09:28.136  7991  7991 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-24 17:09:28.152  7890  8016 D UEI.SmartControl: serial port data available: 21
,08-24 17:09:28.158  7991  7991 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-24 17:09:28.158  7991  7991 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-24 17:09:28.158  7991  7991 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-24 17:09:28.158  7991  7991 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-24 17:09:28.158  7991  7991 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-24 17:09:28.158  7991  7991 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-24 17:09:28.178  7890  7890 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 17:09:28.178  7890  7890 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 17:09:28.178  7890  7890 I UEI.SmartControl: QS saving settings...
,08-24 17:09:28.178  7890  7890 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 17:09:28.195  7890  8016 D UEI.SmartControl: serial port data available: 4
,08-24 17:09:28.226  7890  7890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-24 17:09:28.226  7890  8020 I UEI.SmartControl: Device manager: loading config....
08-24 17:09:28.227  7890  8020 D UEI.SmartControl: ----------- loading internal config...
08-24 17:09:28.236  7890  8020 E UEI.SmartControl: Loading SETTINGS...
,08-24 17:09:28.247  7890  8020 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 17:09:28.268  7890  8019 I UEI.SmartControl: Notify AllClients services are ready: 0
08-24 17:09:28.268  7890  8019 D UEI.SmartControl: -----service ready thread exits
,08-24 17:09:28.278  1038  1945 I art     : Explicit concurrent mark sweep GC freed 40241(1903KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.809ms total 121.837ms
08-24 17:09:28.283  7890  7890 E UEI.SmartControl: Services init done
08-24 17:09:28.283  7890  7890 D UEI.SmartControl: QS Service init finished
,08-24 17:09:28.284  1038  1366 V AlarmManager: ELAPSED_WAKEUP set : Alarm{379379e type 2 when 204784 com.google.android.gms} when 204784
08-24 17:09:28.286  7890  7890 D UEI.SmartControl: QS Service version name: 2.1.91
08-24 17:09:28.287  7890  7890 D UEI.SmartControl: QS Service version code: 201091
08-24 17:09:28.287  7890  7890 D UEI.SmartControl: Service requested: Control
08-24 17:09:28.293  1038  2021 I ActivityManager: Killing 6418:com.wsandroid.suite.lge/1000 (adj 15): empty #17,
08-24 17:09:28.346  1038  1563 I ActivityManager: Killing 7250:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-24 17:09:28.351  7890  7890 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26678d73 that was originally bound here
08-24 17:09:28.351  7890  7890 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26678d73 that was originally bound here
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 17:09:28.351  7890  7890 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 17:09:28.354   312  8024 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-24 17:09:28.354  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-24 17:09:28.375  1038  1983 W libprocessgroup: failed to open /acct/uid_1000/pid_6418/cgroup.procs: No such file or directory
,08-24 17:09:28.382  1038  1984 W libprocessgroup: failed to open /acct/uid_10046/pid_7250/cgroup.procs: No such file or directory
08-24 17:09:28.382  7890  7890 D UEI.SmartControl: Internal service binding...
08-24 17:09:28.590  1038  1984 V SIM_STK : Menu title from STK is T-Mobile
,08-24 17:09:28.618  5047  7987 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 639 ms] updated apps [took 639 ms] 
,08-24 17:09:28.633  7890  7965 D UEI.SmartControl: Internal timer expired: 2
,08-24 17:09:28.674  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:28.674  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d448b51 added. We now have 6 listener(s)
08-24 17:09:28.674  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:28.678  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:28.678  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a482fb6 added. We now have 7 listener(s)
,08-24 17:09:28.679  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:09:28.681  6862  6941 I System.out: IsBluetoothEnabled
,08-24 17:09:28.683  1038  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:28.683  1038  1762 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-24 17:09:28.684  1038  1120 D BluetoothManagerService: Message: 2
08-24 17:09:28.688  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:28.688  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:28.688  1038  1909 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-24 17:09:28.702  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:28.702  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 17:09:28.702  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-24 17:09:28.704  1038  1120 D BluetoothManagerService: Message: 1
08-24 17:09:28.704  1038  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-24 17:09:28.725  1038  1120 D BluetoothManagerService: Message: 20
08-24 17:09:28.725  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e056f4d:true
08-24 17:09:28.726  7789  7789 D BluetoothAdapterState: make
,08-24 17:09:28.732  7789  7789 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-24 17:09:28.732  7789  7789 I bluedroid-qcom: init
08-24 17:09:28.733  7789  8034 I BluetoothAdapterState: Entering OffState
08-24 17:09:28.735  7789  7789 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-24 17:09:28.735  7789  7789 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 17:09:28.736  7789  7789 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 17:09:28.736  7789  7789 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 17:09:28.736  7789  7789 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-24 17:09:28.729  8037  8037 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:28.729  8037  8037 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:28.737  7789  7789 I bluedroid-qcom: get_profile_interface socket
08-24 17:09:28.737  7789  7789 I bluedroid-qcom: get_profile_interface map_client
08-24 17:09:28.741  7789  8038 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-24 17:09:28.746  7789  8038 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-24 17:09:28.747  8037  8037 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-24 17:09:28.747  8037  8037 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-24 17:09:28.747  8037  8037 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-24 17:09:28.749  8037  8037 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-24 17:09:28.752  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 17:09:28.753  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 17:09:28.754  7789  8038 D BluetoothAdapterProperties: Name is: G3
08-24 17:09:28.758  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-24 17:09:28.758  1038  1120 D BluetoothManagerService: Message: 40
08-24 17:09:28.758  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-24 17:09:28.759  7789  7804 I bluedroid-qcom: config_hci_snoop_log
08-24 17:09:28.761  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-24 17:09:28.761  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-24 17:09:28.780  7789  8034 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-24 17:09:28.780  7789  8034 D BluetoothAdapterProperties: Setting state to 11
08-24 17:09:28.781  7789  8034 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-24 17:09:28.783  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:28.783  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-24 17:09:28.784  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-24 17:09:28.784  7789  8034 I LGBluetoothServiceJni: classInitNative: succeeds
08-24 17:09:28.788  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:28.789  8037  8037 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-24 17:09:28.789  8037  8037 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-24 17:09:28.791  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 17:09:28.794  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:28.799  6992  6992 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-24 17:09:28.804  7789  8034 D BluetoothBondStateMachine: make
08-24 17:09:28.807  7789  8034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:28.807  7789  8034 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-24 17:09:28.807  7789  8034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:28.807  7789  8034 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-24 17:09:28.808  7789  7789 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 17:09:28.808  7789  7789 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:28.808  7789  7789 V BluetoothPbapReceiver: ***********state = 11
08-24 17:09:28.808  7789  8043 I BluetoothBondStateMachine: StableState(): Entering Off State
08-24 17:09:28.810  7789  8034 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-24 17:09:28.813  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:09:28.818  7789  8034 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:28.835  6992  6992 D BluetoothPermissionRequest: onReceive
08-24 17:09:28.836  7789  8034 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 17:09:28.837  7789  7789 D HeadsetService: Received start request. Starting profile...
08-24 17:09:28.839  7789  7789 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 17:09:28.839  7789  7789 D LGBluetoothHfpAdapter: Version 1.6
08-24 17:09:28.842  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 17:09:28.843  7789  8034 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:28.843  7789  7789 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 17:09:28.845  7789  7789 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 17:09:28.845  7789  7789 D HeadsetStateMachine: make
08-24 17:09:28.852  7789  8034 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 17:09:28.858  7789  8034 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:28.863  7789  8034 E BluetoothAdapterService: File transfer profiles supported!!
,08-24 17:09:28.870  7789  8034 E BluetoothAdapterService: File transfer profiles supported!!
08-24 17:09:28.886  7789  8034 V LGMDMManager: Create singleton instance
,08-24 17:09:28.886  7789  7789 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:28.886  7789  7789 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 17:09:28.888  7789  8034 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 17:09:28.892  7789  7789 D HeadsetStateMachine: max_hf_connections = 1
08-24 17:09:28.892  7789  7789 I bluedroid-qcom: get_profile_interface handsfree
08-24 17:09:28.894  7789  7789 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-24 17:09:28.894   316  2189 V AudioPolicyService: registerClient() client 0xb558a520, uid 1002
08-24 17:09:28.895   316  1385 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-24 17:09:28.895   316  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-24 17:09:28.895   316  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 17:09:28.895  7789  7789 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-24 17:09:28.896   316  2190 V AudioFlinger: registerClient() client 0xb5581610, pid 7789
08-24 17:09:28.896   316  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:28.896   316  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:28.896  7789  7789 V ToneGenerator: Create Track: 0xb4928080
08-24 17:09:28.896  7789  7789 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-24 17:09:28.896  7789  7789 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-24 17:09:28.897   316  2190 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 17:09:28.897   316  2190 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-24 17:09:28.897  3285  3301 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-24 17:09:28.897   316  2190 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 17:09:28.897  3285  3301 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:28.897   316  2190 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 17:09:28.897   316  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:28.897   316  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:28.897  7789  7804 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:28.897  7789  7804 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-24 17:09:28.897  1592  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:28.897  1592  1613 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:28.898  1038  1910 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:28.898  1038  1910 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:28.898  1038  1910 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:28.898  1038  1910 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-24 17:09:28.898  1592  1609 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:28.898  1592  1609 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:28.898   316  1386 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 17:09:28.898  3285  3300 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:28.898  3285  3300 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:28.899   316  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-24 17:09:28.899   316  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-24 17:09:28.899   316  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-24 17:09:28.899   316  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-24 17:09:28.900  1841  4392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-24 17:09:28.900  1841  4392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-24 17:09:28.900  7789  7789 V AudioSystem: getLatency() output 2, latency 50
08-24 17:09:28.900  7789  7789 V AudioSystem: getFrameCount() output 2, frameCount 960
08-24 17:09:28.900  7789  7789 V AudioTrack: createTrack_l() output 2 afLatency 50
08-24 17:09:28.901   316  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 17:09:28.901   316  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 17:09:28.901   316  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-24 17:09:28.901   316  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-24 17:09:28.901   316  2189 V AudioFlinger: createTrack() lSessionId: 21
08-24 17:09:28.903  7789  7804 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-24 17:09:28.903  7789  7804 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-24 17:09:28.903  7789  7789 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-24 17:09:28.904   316  2189 V AudioFlinger: acquiring 21 from 7789, for 7789
08-24 17:09:28.904   316  2189 V AudioFlinger:  added new entry for 21
08-24 17:09:28.904  7789  7789 V ToneGenerator: ToneGenerator INIT OK, time: 205494
08-24 17:09:28.904  1841  4392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-24 17:09:28.904  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:28.904  1841  4392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-24 17:09:28.906  7789  8051 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-24 17:09:28.906  7789  8051 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-24 17:09:28.906  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:28.907  7789  8051 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-24 17:09:28.907  7789  8051 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-24 17:09:28.908   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7789
08-24 17:09:28.908  7789  7789 D A2dpService: Received start request. Starting profile...
08-24 17:09:28.909   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-24 17:09:28.909   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-24 17:09:28.909   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-24 17:09:28.909   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-24 17:09:28.909   316   316 V voice   : voice_set_parameters: exit with code(0)
08-24 17:09:28.909   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-24 17:09:28.909  7789  7789 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 17:09:28.909   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-24 17:09:28.910   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
08-24 17:09:28.910   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-24 17:09:28.910   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-24 17:09:28.910   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-24 17:09:28.910  7789  7789 V Avrcp   : make
08-24 17:09:28.910  7789  8051 V ToneGenerator: ToneGenerator destructor
08-24 17:09:28.910  7789  8051 V ToneGenerator: stopTone
08-24 17:09:28.910  7789  8051 V ToneGenerator: Delete Track: 0xb4928080
08-24 17:09:28.911  7789  7789 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-24 17:09:28.911  7789  7789 I bluedroid-qcom: get_profile_interface avrcp
08-24 17:09:28.911  7789  8051 V AudioTrack: ~AudioTrack, releasing session id from 7789 on behalf of 7789
08-24 17:09:28.912   316  2189 V AudioFlinger: releasing 21 from 7789 for 7789
08-24 17:09:28.912   316  2189 V AudioFlinger:  decremented refcount to 0
08-24 17:09:28.912   316  2189 V AudioFlinger: purging stale effects
08-24 17:09:28.912   316  2189 V AudioPolicyService: AudioCommandThread() adding release output 2
08-24 17:09:28.912   316  2189 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-24 17:09:28.912   316  2189 V AudioFlinger: PlaybackThread::Track destructor
08-24 17:09:28.912   316  1259 V AudioPolicyService: AudioCommandThread() waking up
08-24 17:09:28.912   316  2189 V AudioFlinger: removeClient_l() pid 7789, calling pid 316
08-24 17:09:28.912   316  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-24 17:09:28,.912   316  1259 V AudioPolicyManager: releaseOutput() 2
08-24 17:09:28.912   316  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-24 17:09:28.927  7789  7789 V AudioManager: registerRemoteController: size of Media player list: 0
08-24 17:09:28.929  7789  7789 E AudioManager: No RCC entry present to update
08-24 17:09:28.930  7789  7789 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 17:09:28.938  7789  7789 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-24 17:09:28.940  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-24 17:09:28.940  7789  7789 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-24 17:09:28.947  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-24 17:09:29.104  1038  1054 V SIM_STK : Menu title from STK is T-Mobile
,08-24 17:09:29.104  1038  1054 V SIM_STK : Menu title from STK is T-Mobile
,08-24 17:09:29.240  1038  1762 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-24 17:09:29.250  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 17:09:29.255  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 17:09:29.256  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 17:09:29.256  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 17:09:29.256  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 17:09:29.256  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 17:09:29.257  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 17:09:29.257  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 17:09:29.257  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 17:09:29.257  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 17:09:29.257  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 17:09:29.257  7789  7789 I BluetoothA2dpServiceJni: classInitNative
08-24 17:09:29.257  7789  7789 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:09:29.258  7789  7789 D A2dpStateMachine: make
,08-24 17:09:29.261  7789  7789 I bluedroid-qcom: get_profile_interface a2dp
08-24 17:09:29.262  7789  8063 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-24 17:09:29.265  7789  7789 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:09:29.265  7789  7789 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-24 17:09:29.266  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:29.267  7789  7789 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 17:09:29.269  7789  8062 D A2dpStateMachine: Enter Disconnected: -2
08-24 17:09:29.270  7789  7789 D HidService: Received start request. Starting profile...
08-24 17:09:29.270  7789  7789 I bluedroid-qcom: get_profile_interface hidhost
08-24 17:09:29.270  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:29.271  7789  7789 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 17:09:29.275  7789  7789 D HealthService: Received start request. Starting profile...
08-24 17:09:29.280  7789  7789 I bluedroid-qcom: get_profile_interface health
08-24 17:09:29.280  7789  7789 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-24 17:09:29.280  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:29.281  7789  7789 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 17:09:29.283  7789  7789 D PanService: Received start request. Starting profile...
08-24 17:09:29.283  7789  7789 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:09:29.283  7789  7789 I bluedroid-qcom: get_profile_interface pan
,08-24 17:09:29.293  7789  7789 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-24 17:09:29.293  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:29.295  7789  7789 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-24 17:09:29.300  7789  7789 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 17:09:29.300  7789  7789 D BtGatt.GattService: Received start request. Starting profile...
08-24 17:09:29.300  7789  7789 D BtGatt.GattService: start()
08-24 17:09:29.301  7789  7789 I bluedroid-qcom: get_profile_interface gatt
08-24 17:09:29.301  7789  7789 D BtGatt.AdvertiseManager: advertise manager created
08-24 17:09:29.312  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
,08-24 17:09:29.316  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:29.318  7789  7789 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-24 17:09:29.321  7789  7789 V BluetoothMapService: BluetoothMapBinder()
08-24 17:09:29.321  7789  7789 D BluetoothMapService: Received start request. Starting profile...
08-24 17:09:29.322  7789  7789 D BluetoothMapService: start()
08-24 17:09:29.325  7789  7789 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-24 17:09:29.325  7789  7789 D BluetoothMapEmailAppObserver: createReceiver()
08-24 17:09:29.326  7789  7789 D BluetoothMapEmailAppObserver: initObservers()
08-24 17:09:29.327  7789  7789 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-24 17:09:29.336  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:29.337  7789  7789 D HeadsetStateMachine: Proxy object connected
08-24 17:09:29.337  7789  7789 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-24 17:09:29.338  7789  7789 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-24 17:09:29.343  7789  7789 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:29.344  7789  8051 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 17:09:29.345  7789  8051 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 17:09:29.345  7789  8051 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-24 17:09:29.348  7789  7789 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:29.351  7789  7789 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-24 17:09:29.353  7789  7789 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:29.361  7789  7789 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:29.362  7789  7789 V PanService: [BTUI] SIM Extra State :ABSENT
08-24 17:09:29.365  7789  7789 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-24 17:09:29.368  7789  7789 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-24 17:09:29.368  7789  7789 V BluetoothMapService: Handler(): got msg=1
,08-24 17:09:29.369  7789  7789 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:29.370  7789  7789 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 17:09:29.370  7789  7789 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 17:09:29.370  7789  7789 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:29.370  7789  7789 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-24 17:09:29.372  7789  8034 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-24 17:09:29.372  7789  8034 I bluedroid-qcom: enable
08-24 17:09:29.372  7789  8034 I bt_hci_bdroid: init
08-24 17:09:29.374  7789  8034 I bt_vendor: bt-vendor : init
08-24 17:09:29.374  7789  8034 I bt_vendor: bt-vendor : get_bt_soc_type
08-24 17:09:29.374  7789  8034 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-24 17:09:29.374  7789  8034 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-24 17:09:29.374  7789  8034 D bt_userial_mct: userial_init
08-24 17:09:29.374  7789  8070 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-24 17:09:29.374  7789  8070 I bt-btu  : btu_task pending for preload complete event
08-24 17:09:29.374  7789  8034 D bt_hci_bdroid: set_power 1
08-24 17:09:29.374  7789  8034 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-24 17:09:29.374  7789  8034 I bt_vendor: Starting hciattach daemon
08-24 17:09:29.374  7789  8034 I bt_vendor: try to set true
08-24 17:09:29.369  8073  8073 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:29.369  8073  8073 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:29.402  8074  8074 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-24 17:09:29.468  8080  8080 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-24 17:09:29.481  8081  8081 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-24 17:09:29.507  8083  8083 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 17:09:29.533  8084  8084 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-24 17:09:29.546  8085  8085 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-24 17:09:29.558  8086  8086 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-24 17:09:29.578  8088  8088 I libmdmdetect: ESOC framework not supported
08-24 17:09:29.579  8088  8088 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-24 17:09:29.587  8088  8088 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-24 17:09:29.587  8088  8088 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-24 17:09:29.587  8088  8088 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-24 17:09:29.587  8088  8088 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-24 17:09:29.587  8088  8088 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-24 17:09:29.587  8088  8088 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-24 17:09:29.587  8088  8088 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-24 17:09:29.626  8088  8089 E QC-QMI  : qmi_client [8088] 15: failed to locate client data
08-24 17:09:29.627   466   466 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-24 17:09:29.628   466   466 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-24 17:09:29.663  8090  8090 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-24 17:09:29.677  8091  8091 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-24 17:09:29.732  7789  8034 I bt_vendor: bluetooth satus is on
08-24 17:09:29.732  7789  8034 D bt_hci_bdroid: preload
08-24 17:09:29.732  7789  8072 D bt_userial_mct: userial_open(port:0)
08-24 17:09:29.732  7789  8072 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-24 17:09:29.738  7789  8072 I bt_vendor: Done intiailizing UART
,08-24 17:09:29.743  7789  8072 I bt_vendor: Done intiailizing UART
08-24 17:09:29.743  7789  8072 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-24 17:09:29.743  7789  8072 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-24 17:09:29.744  7789  8070 I bt-btu  : btu_task received preload complete event
08-24 17:09:29.744  7789  8093 D bt_userial_mct: Entering userial_read_thread()
08-24 17:09:29.745  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-24 17:09:29.746  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-24 17:09:29.754  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_HCI
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 17:09:29.765  7789  8070 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 17:09:29.766  7789  8070 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 17:09:29.766  7789  8070 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 17:09:29.873  7789  8070 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-24 17:09:29.873  7789  8070 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0154061 
08-24 17:09:29.873  7789  8070 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0154061 
,08-24 17:09:29.890  7789  8038 E bt-btif : Calling BTA_HhEnable
08-24 17:09:29.890  7789  8038 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-24 17:09:29.891  7789  8038 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-24 17:09:29.894  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-24 17:09:29.894  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-24 17:09:29.894  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-24 17:09:29.894  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-24 17:09:29.894  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-24 17:09:29.895  7789  8038 D BluetoothAdapterProperties: Name is: G3
08-24 17:09:29.896  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-24 17:09:29.896  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
08-24 17:09:29.897  7789  8038 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:09:29.897  7789  8038 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:09:29.897  7789  8038 D bt_hci_bdroid: postload
08-24 17:09:29.898  7789  8072 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:29.898  7789  8072 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:29.899  7789  8072 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:29.900  7789  8072 D bt_hci_bdroid: Used up Tx Cmd credits
08-24 17:09:29.900  7789  8070 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-24 17:09:29.901  7789  8038 D bte_conf: Device ID record 1 : primary
08-24 17:09:29.901  7789  8093 E bt_mct  : hci lib postload completed
08-24 17:09:29.901  7789  8038 D bte_conf:   vendorId            = 00c4
08-24 17:09:29.901  7789  8038 D bte_conf:   vendorIdSource      = 0001
08-24 17:09:29.901  7789  8038 D bte_conf:   product             = 13a1
08-24 17:09:29.901  7789  8038 D bte_conf:   version             = 1000
08-24 17:09:29.901  7789  8038 D bte_conf:   clientExecutableURL = 
08-24 17:09:29.901  7789  8038 D bte_conf:   serviceDescription  = 
08-24 17:09:29.901  7789  8038 D bte_conf:   documentationURL    = 
08-24 17:09:29.901  7789  8038 D bte_conf: bte_load_did_conf no section named DID2.
08-24 17:09:29.905  7789  8034 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 17:09:29.905  7789  8034 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:09:29.905  7789  8034 D BluetoothAdapterProperties: State =  11
08-24 17:09:29.905  7789  8034 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-24 17:09:29.905  7789  8034 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-24 17:09:29.906  7789  8034 D BluetoothAdapterProperties: Setting state to 12
08-24 17:09:29.906  7789  8034 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 17:09:29.911  7789  8038 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 17:09:29.912  7789  8038 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 17:09:29.909  8098  8098 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:29.915  1038  1120 D BluetoothManagerService: Message: 60
08-24 17:09:29.909  8098  8098 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:29.921  7789  8034 I BluetoothAdapterState: Entering On State
,08-24 17:09:29.925  7789  8070 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:29.925  7789  8070 W bt-smp  : Plain text(LSB ~ MSB) = b5 b8 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:29.925  7789  8070 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f 25 2b 55 b2 44 37 eb ec a5 2c f1 99 bb 2d 92 
08-24 17:09:29.925  7789  8070 W bt-btm  : Stopping oneshot timer
08-24 17:09:29.925  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-24 17:09:29.925  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-24 17:09:29.956  7789  8070 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:29.956  7789  8070 W bt-smp  : Plain text(LSB ~ MSB) = 23 9f 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:29.956  7789  8070 W bt-smp  : Encrypted text(LSB ~ MSB) = be b0 07 64 73 7f 31 e2 41 37 79 72 9b da 2f 53 
,08-24 17:09:29.959  7789  8070 W bt-btm  : Stopping oneshot timer
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:29.959  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:29.962  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:29.973  7789  8070 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:29.973  7789  8070 W bt-smp  : Plain text(LSB ~ MSB) = 1b 95 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:29.973  7789  8070 W bt-smp  : Encrypted text(LSB ~ MSB) = 61 2c 46 e4 94 7c 18 b5 4c 59 f1 03 79 39 7d cd 
,08-24 17:09:29.976  7789  8070 W bt-btm  : Stopping oneshot timer
08-24 17:09:29.977  7789  8034 D LGBluetoothServiceAdapter: [BTUI] OnState
08-24 17:09:29.979  7789  8034 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-24 17:09:29.979  7789  8034 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-24 17:09:29.981  7789  8034 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-24 17:09:29.981  7789  8034 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-24 17:09:29.982  6992  7007 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:09:30.031  1841  4394 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:09:30.035  8103  8103 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-24 17:09:30.039  7789  8070 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:30.039  7789  8070 W bt-smp  : Plain text(LSB ~ MSB) = 06 90 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:30.039  7789  8070 W bt-smp  : Encrypted text(LSB ~ MSB) = 15 2b ac a6 a9 ef 6a 68 55 96 13 06 52 3d d2 90 
08-24 17:09:30.039  7789  8070 W bt-btm  : Stopping oneshot timer
08-24 17:09:30.042  6992  6992 D BluetoothA2dp: Proxy object connected
08-24 17:09:30.042  6992  6992 D A2dpProfile: Bluetooth service connected
08-24 17:09:30.045  1841  1841 D BluetoothHeadset: Proxy object connected
08-24 17:09:30.049  1841  2427 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:09:30.053  1841  1841 D BluetoothHeadset: Proxy object connected
08-24 17:09:30.054  6992  7270 D BluetoothMap: onBluetoothStateChange: up=true
08-24 17:09:30.056  1841  4392 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:09:30.059  1841  1841 D BluetoothHeadset: Proxy object connected
08-24 17:09:30.060  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:09:30.063  1038  1038 D BluetoothHeadset: Proxy object connected
08-24 17:09:30.064  7789  8070 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 17:09:30.064  7789  8070 W bt-smp  : Plain text(LSB ~ MSB) = 8c 22 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 17:09:30.064  7789  8070 W bt-smp  : Encrypted text(LSB ~ MSB) = 7f 94 31 98 dc 85 04 33 76 1d 61 a8 0a 75 eb ee 
08-24 17:09:30.065  6992  7270 D BluetoothPan: onBluetoothStateChange on: true
08-24 17:09:30.065  6992  7270 D BluetoothPan: onBluetoothStateChange call bindService
08-24 17:09:30.065  7789  8070 W bt-btm  : Stopping oneshot timer
08-24 17:09:30.066  6992  6992 D BluetoothMap: Proxy object connected
08-24 17:09:30.066  6992  6992 D MapProfile: Bluetooth service connected
08-24 17:09:30.066  6992  6992 D BluetoothMap: getConnectedDevices()
08-24 17:09:30.070  6992  7007 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:09:30.072  7789  7804 V BluetoothMapService: getConnectedDevices()
,08-24 17:09:30.073  6992  7008 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 17:09:30.074  6992  6992 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:09:30.074  6992  6992 D PanProfile: Bluetooth service connected
08-24 17:09:30.078  6992  6992 D BluetoothHeadset: Proxy object connected
08-24 17:09:30.078  6992  6992 D HeadsetProfile: Bluetooth service connected
08-24 17:09:30.081  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:09:30.082  1038  1038 D BluetoothA2dp: Proxy object connected
08-24 17:09:30.082  6992  7007 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 17:09:30.085  7789  8038 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:09:30.085  7789  8038 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-24 17:09:30.089  1038  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-24 17:09:30.089  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-24 17:09:30.089  6992  6992 D BluetoothInputDevice: Proxy object connected
08-24 17:09:30.089  6992  6992 D HidProfile: Bluetooth service connected
08-24 17:09:30.091  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-24 17:09:30.093  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.094  1928  2091 D LGBluetoothAPIService: Message: 1
08-24 17:09:30.094  1928  2091 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-24 17:09:30.094  1928  2091 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-24 17:09:30.094  1928  2091 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-24 17:09:30.097  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:30.097  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-24 17:09:30.098  1038  1120 D BluetoothManagerService: Message: 40
08-24 17:09:30.098  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-24 17:09:30.101  7789  7789 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.101  7789  7789 D BluetoothMapService: STATE_ON
08-24 17:09:30.102  7789  7789 V BluetoothMapService: Handler(): got msg=1
08-24 17:09:30.102  7789  7789 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-24 17:09:30.104  7789  8122 D BluetoothMapMasInstance: MAS initSocket()
08-24 17:09:30.104  6992  6992 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-24 17:09:30.104  7789  8122 D BluetoothMapMasInstance:   masId = 00
08-24 17:09:30.104  7789  8122 D BluetoothMapMasInstance:   msgTypes = 0e
08-24 17:09:30.104  7789  8122 D BluetoothMapMasInstance:   masName = SMS/MMS
08-24 17:09:30.104  7789  8122 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-24 17:09:30.105  6992  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-24 17:09:30.106  1038  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:30.109  7789  8122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:09:30.112  7789  8122 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-24 17:09:30.113  7789  8122 V BluetoothMapMasInstance: Succeed to create listening socket 
08-24 17:09:30.113  7789  8122 D BluetoothMapMasInstance: Accepting socket connection...
08-24 17:09:30.114  7789  8038 D BluetoothAdapterProperties: Scan Mode:21
08-24 17:09:30.114  7789  8038 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-24 17:09:30.117  6992  6992 D DockEventReceiver: finishStartingService: stopping service
08-24 17:09:30.118  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:30.124  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:30.124  7789  7789 V BluetoothPbapService: Pbap Service onCreate
08-24 17:09:30.124  7789  7789 V BluetoothPbapService: Starting PBAP service
,08-24 17:09:30.127  7789  7789 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-24 17:09:30.128  7789  7789 V BluetoothPbapService: Pbap Service onBind
08-24 17:09:30.128  7789  7789 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.129  6992  6992 D BluetoothPbap: Proxy object connected
08-24 17:09:30.129  6992  6992 D PbapServerProfile: Bluetooth service connected
08-24 17:09:30.129  7789  7789 V BluetoothPbapService: state: 12
08-24 17:09:30.129  7789  7789 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-24 17:09:30.129  7789  7789 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.129  7789  7789 V BluetoothPbapReceiver: ***********state = 12
08-24 17:09:30.130  7789  7789 V BluetoothPbapService: Handler(): got msg=1
08-24 17:09:30.131  7789  7789 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-24 17:09:30.132  2146  2146 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 17:09:30.132  7789  8126 V BluetoothPbapService: Pbap Service initSocket
08-24 17:09:30.133  2146  2146 D c       : Getting all permits...
08-24 17:09:30.133  2146  2146 D a       : Opening database...
08-24 17:09:30.133  1038  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:30.133  7789  8126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:30.134  7789  8126 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-24 17:09:30.134  7789  8126 V BluetoothPbapService: Succeed to create listening socket 
08-24 17:09:30.135  7789  8126 V BluetoothPbapService: Accepting socket connection...
08-24 17:09:30.136  2146  2146 D a       : Opening database auth.proximity.permit_store...
08-24 17:09:30.137  2146  2146 D a       : Closing database...
08-24 17:09:30.146  6992  6992 D BluetoothPermissionRequest: onReceive
,08-24 17:09:30.149  6992  6992 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-24 17:09:30.151  6992  6992 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-24 17:09:30.153  7789  7789 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-24 17:09:30.155  7789  7789 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-24 17:09:30.160  7789  7789 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-24 17:09:30.185  7789  7789 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-24 17:09:30.186  7789  7789 V BtOppService: onCreate
,08-24 17:09:30.191  7789  7789 V BluetoothOppNotification: send message
08-24 17:09:30.197  7789  7789 V BtOppService: Starting RfcommListener
08-24 17:09:30.206  7789  7789 D BluetoothOppPreference: Dumping Names:  
08-24 17:09:30.207  7789  7789 D BluetoothOppPreference: {}
08-24 17:09:30.207  7789  7789 D BluetoothOppPreference: Dumping Channels:  
08-24 17:09:30.207  7789  7789 D BluetoothOppPreference: {}
,08-24 17:09:30.210  7789  7789 V BtOppService: onStartCommand
08-24 17:09:30.215  7789  8129 V BtOppService: Deleted complete outbound shares, number =  0
08-24 17:09:30.215  7789  8132 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 17:09:30.216  7789  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 17:09:30.217  7789  7789 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.218  7789  7789 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-24 17:09:30.218  7789  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1559343e on behalf of 
08-24 17:09:30.222  7789  8129 V BtOppService: Deleted complete inbound failed shares, number = 0
08-24 17:09:30.222  7789  8129 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-24 17:09:30.223  7789  7789 V BluetoothOppNotification: new notify threadi!
08-24 17:09:30.226  7789  8129 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ada529f on behalf of 
,08-24 17:09:30.227  7789  7789 V BluetoothOppNotification: send delay message
08-24 17:09:30.228  7789  8132 V BluetoothOppNotification: update too frequent, put in queue
08-24 17:09:30.229  7789  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 17:09:30.229  7789  7789 V BtOppService: start RfcommListener
08-24 17:09:30.231  7789  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a1bcfec on behalf of 
08-24 17:09:30.232  7789  8133 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-24 17:09:30.233  7789  8132 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 17:09:30.233  7789  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-24 17:09:30.235  7789  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b99fb5 on behalf of 
08-24 17:09:30.236  7789  8133 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-24 17:09:30.239  7789  7789 V BtOppService: RfcommListener started
08-24 17:09:30.239  7789  7789 V BtOppService: ContentObserver received notification
08-24 17:09:30.241  7789  7789 V BtOppService: ContentObserver received notification
08-24 17:09:30.242  7789  8135 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-24 17:09:30.242  7789  8135 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-24 17:09:30.242  7789  8133 V BluetoothOppNotification: outbound notification was removed.
08-24 17:09:30.242  7789  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-24 17:09:30.243  7789  8135 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fb0564a on behalf of 
08-24 17:09:30.245  7789  8135 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-24 17:09:30.245  7789  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f9b79bb on behalf of 
08-24 17:09:30.245  7789  8134 V BtOppRfcommListener: Starting RFCOMM listener....
08-24 17:09:30.247  1038  1563 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:30.247  7789  8133 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 17:09:30.249  7789  8134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:30.249  7789  8133 V BluetoothOppNotification: inbound notification was removed.
08-24 17:09:30.249  7789  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-24 17:09:30.252  7789  8134 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-24 17:09:30.252  7789  8134 V BtOppRfcommListener: Started RFCOMM listener....
08-24 17:09:30.252  7789  8134 I BtOppRfcommListener: Accept thread started.
08-24 17:09:30.252  7789  8134 V BtOppRfcommListener: Accepting connection...
,08-24 17:09:30.254  7789  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15ebfed8 on behalf of 
08-24 17:09:30.259  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:30.259  7789  7789 V BluetoothFtpService: Ftp Service onCreate
08-24 17:09:30.259  7789  7789 I BluetoothFtpService: Ftp Service onCreate
08-24 17:09:30.259  7789  7789 V BluetoothFtpService: Ftp Service onStartCommand
08-24 17:09:30.259  7789  7789 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.259  7789  7789 V BluetoothFtpService: Starting Listening on sockets
08-24 17:09:30.260  7789  7789 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-24 17:09:30.260  7789  7789 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-24 17:09:30.260  7789  7789 V BluetoothSapReceiver: SapReceiver onReceive 
08-24 17:09:30.260  7789  7789 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.260  7789  7789 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-24 17:09:30.260  7789  7789 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-24 17:09:30.264  7789  7789 V BluetoothFtpService: Handler(): got msg=1
,08-24 17:09:30.265  7789  7789 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-24 17:09:30.265  7789  7789 V BluetoothFtpService: Ftp Service initSocket
08-24 17:09:30.269  1038  1591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:30.271  7789  7789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:09:30.272  7789  7789 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-24 17:09:30.273  7789  7789 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-24 17:09:30.276  7789  8136 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-24 17:09:30.306  7789  7789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144605e2
08-24 17:09:30.306  7789  7789 V BluetoothSapService: Sap Service onCreate
08-24 17:09:30.309  7789  7789 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:09:30.309  7789  7789 V BluetoothSapService: state: 12
08-24 17:09:30.309  7789  7789 V BluetoothSapService: Starting SAP server process
,08-24 17:09:30.312  7789  7789 V BluetoothSapService: SAP Service startRfcommListenerThread
08-24 17:09:30.309  8137  8137 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:30.309  8137  8137 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:30.317  7789  8138 V BluetoothSapService: Sap Service initRfcommSocket
08-24 17:09:30.318  1038  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:30.322  7789  8138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:09:30.328  7789  8138 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-24 17:09:30.328  7789  8138 V BluetoothSapService: Succeed to create listening socket 
08-24 17:09:30.328  7789  8138 V BluetoothSapService: Accepting socket connection...
,08-24 17:09:30.338  8137  8137 V BT_SAP  : Event pipe created
08-24 17:09:30.339  8137  8137 V BT_SAP  : create_server_socket qcom.sap.server
08-24 17:09:30.339  8137  8137 V BT_SAP  : created socket fd 6
,08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:30.731  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:09:30.749  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:09:30.755  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:30.755  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c09f4b7 added. We now have 8 listener(s)
08-24 17:09:30.755  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:30.758  1038  1964 D WifiServiceImplEx: setWifiEnabled: false pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 17:09:30.759  1038  1964 D WifiService: setWifiEnabled: false pid=6862, uid=10118
08-24 17:09:30.759  1038  1964 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 17:09:30.764  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:09:30.771  1038  1053 D WifiServiceImplEx: setWifiEnabled: true pid=6862, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-24 17:09:30.772  1038  1053 D WifiService: setWifiEnabled: true pid=6862, uid=10118
08-24 17:09:30.772  1038  1053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 17:09:30.792  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 17:09:30.792  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-24 17:09:30.792  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-24 17:09:30.793  1038  1379 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-24 17:09:30.794  1038  1379 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-24 17:09:30.796  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-24 17:09:30.796  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 17:09:30.796  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-24 17:09:30.796  1038  1379 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-24 17:09:30.797  1038  1379 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-24 17:09:30.797  1038  1379 E WifiHW  : unknown target_country: EU , set to default
08-24 17:09:30.797  1038  1379 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-24 17:09:30.797  1038  1379 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-24 17:09:30.797  1038  1379 I WifiUtil: gEnableBmps=1
08-24 17:09:31.229  7789  7789 V BluetoothOppNotification: new notify threadi!
08-24 17:09:31.229  7789  7789 V BluetoothOppNotification: send delay message
,08-24 17:09:31.238  7789  8157 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-24 17:09:31.248  7789  8157 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@346b106d on behalf of 
08-24 17:09:31.249  7789  8157 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-24 17:09:31.269  7789  8157 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-24 17:09:31.273  7789  8157 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11e564a2 on behalf of 
08-24 17:09:31.273  7789  8157 V BluetoothOppNotification: outbound: succ-0  fail-0
08-24 17:09:31.339  7789  8157 V BluetoothOppNotification: outbound notification was removed.
08-24 17:09:31.340  7789  8157 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-24 17:09:31.354  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 17:09:31.355  1038  1120 D Tethering: InitialState.processMessage what=4
08-24 17:09:31.356  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-24 17:09:31.361   312   896 D SoftapController: Softap fwReload - Ok
,08-24 17:09:31.369  1038  1379 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (568ms)
08-24 17:09:31.373  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 17:09:31.374  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 17:09:31.374  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 17:09:31.374  6992  6992 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 17:09:31.375   312   896 D CommandListener: Setting iface cfg
08-24 17:09:31.375   312   896 D CommandListener: Trying to bring down wlan0
08-24 17:09:31.375   312   896 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:09:31.377  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-24 17:09:31.378  1038  1379 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-24 17:09:31.379  6992  6992 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 17:09:31.380  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 17:09:31.380  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 17:09:31.381  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:31.381  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:31.381  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 17:09:31.382  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 17:09:31.382  6992  6992 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 17:09:31.382  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 17:09:31.383  6992  6992 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 17:09:31.379  8169  8169 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 17:09:31.379  8169  8169 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:31.385  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-24 17:09:31.386  1038  1379 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-24 17:09:31.386  1038  1379 D WifiMonitor: connecting to supplicant
08-24 17:09:31.389  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:31.390  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-24 17:09:31.393  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:31.394  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 17:09:31.395  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 17:09:31.395  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 17:09:31.395  6992  6992 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 17:09:31.395  7789  8157 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa16533 on behalf of 
08-24 17:09:31.395  7789  8157 V BluetoothOppNotification: inbound: succ-0  fail-0
08-24 17:09:31.396  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 17:09:31.397  6992  6992 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 17:09:31.397  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-24 17:09:31.397  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 17:09:31.397  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 17:09:31.397  6992  6992 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 17:09:31.397  6992  6992 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 17:09:31.423  8169  8169 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 17:09:31.444  1038  1983 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8176 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-24 17:09:31.451  7789  8157 V BluetoothOppNotification: inbound notification was removed.
08-24 17:09:31.451  7789  8157 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-24 17:09:31.458  7789  8157 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bffd0f0 on behalf of 
,08-24 17:09:31.461  8169  8169 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 17:09:31.461  8169  8169 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-24 17:09:31.565  8169  8169 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 17:09:31.570  1038  1591 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8199 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 17:09:31.578  8176  8197 W FormManager: Network not available. Please check & try again.
,08-24 17:09:31.594  8176  8198 V FormManager: Network unavailable.
,08-24 17:09:31.596  8176  8198 V FormManager: Network unavailable.
,08-24 17:09:31.608  8169  8169 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-24 17:09:31.614  1038  1591 I ActivityManager: Killing 7272:com.android.chrome/u0a57 (adj 15): empty #17
,08-24 17:09:31.614  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-24 17:09:31.616  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-24 17:09:31.616  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-24 17:09:31.616  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-24 17:09:31.616  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-24 17:09:31.617  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-24 17:09:31.617  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-24 17:09:31.618  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-24 17:09:31.619  1038  1379 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-24 17:09:31.619  1038  1379 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:31.620  1038  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:31.621  1038  1379 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-24 17:09:31.621  1038  1379 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-24 17:09:31.622  1038  1379 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-24 17:09:31.622  1038  1379 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-24 17:09:31.622  1038  1379 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-24 17:09:31.659  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:31.664  1038  1983 W libprocessgroup: failed to open /acct/uid_10057/pid_7272/cgroup.procs: No such file or directory
08-24 17:09:31.664  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 17:09:31.667  1038  1379 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-24 17:09:31.667  1038  1379 E WifiStateMachine: useWiFiOffloading() : false
08-24 17:09:31.667  1038  1379 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-24 17:09:31.667  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:31.667  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:31.667  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:31.667  1038  1379 D WifiNative-wlan0: doBoolean: SET update_config 1
08-24 17:09:31.667  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:31.667  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-24 17:09:31.669  1928  1928 D WfdService: Waiting for WifiP2p enabling
08-24 17:09:31.669  1038  1379 D WifiNative-wlan0: SET update_config 1: returned true
08-24 17:09:31.669  1038  1379 D WifiConfigStore: Loading config and enabling all networks 
08-24 17:09:31.669  1038  1379 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-24 17:09:31.669  1038  1379 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-24 17:09:31.669  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:31.671  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-24 17:09:31.673  1038  1423 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-24 17:09:31.676  1038  1379 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-24 17:09:31.681  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:31.682  1038  1984 I ActivityManager: Killing 7293:com.lge.drmservice/u0a62 (adj 15): empty #17
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:31.683  6862  6862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:09:31.686  6862  6862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:09:31.694  1038  1379 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-24 17:09:31.695  1038  1379 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-24 17:09:31.722  1038  1945 W libprocessgroup: failed to open /acct/uid_10062/pid_7293/cgroup.procs: No such file or directory
,08-24 17:09:31.725  1038  1379 D WifiStateMachine: enableVerboseLogging : level 2
08-24 17:09:31.725  1038  1379 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-24 17:09:31.725  1038  1379 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-24 17:09:31.725  1038  1379 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-24 17:09:31.726  1038  1379 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-24 17:09:31.726  1038  1379 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-24 17:09:31.726  1038  1379 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-24 17:09:31.726  1038  1379 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-24 17:09:31.726  1038  1379 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-24 17:09:31.726  1038  1379 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-24 17:09:31.726  1038  1379 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-24 17:09:31.727  1038  1379 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-24 17:09:31.727  1038  1379 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-24 17:09:31.727  1038  1379 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-24 17:09:31.727  1038  1379 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-24 17:09:31.728  1038  1379 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 17:09:31.728  1038  1379 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-24 17:09:31.728  1038  1379 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-24 17:09:31.728  1038  1379 D WifiNative-HAL: Setting external_sim to 1
08-24 17:09:31.728  1038  1379 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-24 17:09:31.729  1038  1379 D WifiNative-wlan0: SET external_sim 1: returned true
08-24 17:09:31.729  1038  1379 I WifiNative-HAL: startHal
08-24 17:09:31.729  1038  1379 D wifi    : setting scan oui 0x9536c4c0
08-24 17:09:31.729  1038  1379 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 17:09:31.729  1038  1379 I WifiNative-HAL: startHal
08-24 17:09:31.729  1038  1379 D wifi    : setting scan oui 0x9536c4c0
08-24 17:09:31.729  1038  1379 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-24 17:09:31.730  1038  1379 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-24 17:09:31.730  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-24 17:09:31.730  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-24 17:09:31.730  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-24 17:09:31.731  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 17:09:31.731  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 17:09:31.731  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 17:09:31.731  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-24 17:09:31.731  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-24 17:09:31.731  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-24 17:09:31.732  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-24 17:09:31.732  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 17:09:31.732  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 17:09:31.732  7818  7818 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:31.732  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 17:09:31.732  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-24 17:09:31.732  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-24 17:09:31.732  1928  2205 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-24 17:09:31.732  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-24 17:09:31.732  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-24 17:09:31.732  1928  2205 D WfdsService: Set the WFDS Monitor: true
08-24 17:09:31.732  1928  2205 D WfdsMonitor: WfdsMonit,orThread create
08-24 17:09:31.732  8169  8169 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-24 17:09:31.733  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-24 17:09:31.733  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-24 17:09:31.733  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-24 17:09:31.733  1928  2205 D WfdsMonitor: WFDS Monitor is created and started
08-24 17:09:31.733  1928  2205 D WfdsService: WiFi: Supplicant connection re-established
08-24 17:09:31.733  1038  1379 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-24 17:09:31.734  1928  8220 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-24 17:09:31.734  1038  1379 E WifiNative: : [208,311,948 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-24 17:09:31.734  1038  1379 D WifiNative-wlan0: doBoolean: RECONNECT
08-24 17:09:31.734  1928  8220 E CtrlSupplicant: Succeed to open control connection
08-24 17:09:31.735  1928  8220 E CtrlSupplicant: Succeed to open monitor connection
08-24 17:09:31.735  1038  1379 D WifiNative-wlan0: RECONNECT: returned true
08-24 17:09:31.735  1038  1379 D WifiNative-wlan0: doString: [STATUS]
08-24 17:09:31.735  1038  1379 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 17:09:31.735  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-24 17:09:31.735  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 17:09:31.736  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-24 17:09:31.736  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:31.736  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:09:31.740  1928  8220 D WfdsMonitor: Supplicant connection established
08-24 17:09:31.740  1928  2205 D WfdsService: Connected to the supplicant for wfds
08-24 17:09:31.742   312   896 D CommandListener: Setting iface cfg
08-24 17:09:31.742   312   896 D CommandListener: Trying to bring up p2p0
08-24 17:09:31.742  1038  1377 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 17:09:31.742  1038  1377 D LGWifiP2pService: P2pEnablingState
08-24 17:09:31.742  1038  1377 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.742  1038  1377 D LGWifiP2pService: P2p socket connection successful
08-24 17:09:31.742  1038  1377 D LGWifiP2pService: P2pEnabledState
08-24 17:09:31.743  1038  1377 D LGWifiP2pService: sending p2p connection changed broadcast
08-24 17:09:31.744  1038  1377 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-24 17:09:31.744  1038  1377 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-24 17:09:31.744  1038  1377 D WifiNative-p2p0: doBoolean: SET device_name G3
08-24 17:09:31.745  1038  1377 D WifiNative-p2p0: SET device_name G3: returned true
08-24 17:09:31.745  1038  1377 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-24 17:09:31.745  1038  1377 D LGWifiP2pService: before postfix = G3
08-24 17:09:31.745  1038  1377 D WifiServerServiceExt: postfix byte check : 2
08-24 17:09:31.745  1038  1377 D LGWifiP2pService: after postfix = G3
08-24 17:09:31.745  1038  1377 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-24 17:09:31.745  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-24 17:09:31.745  1038  1377 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-24 17:09:31.745  1038  1377 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-24 17:09:31.745  1928  1928 D WfdsService: WifiP2pState is changed : true
08-24 17:09:31.745  1038  1377 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-24 17:09:31.745  1038  1377 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-24 17:09:31.746  1038  1377 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-24 17:09:31.746  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-24 17:09:31.746  1038  1377 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-24 17:09:31.746  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress
08-24 17:09:31.746  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-24 17:09:31.747  1928  2205 D WfdsService: Receive the WFDS_ENABLE Method
08-24 17:09:31.747  1928  2205 D WfdsService: Set the WFDS Monitor: true
08-24 17:09:31.747  1928  2205 D WfdsService: Connected to the supplicant for wfds
08-24 17:09:31.748  1928  2205 D WfdsJNI : doCommand: WFDS_SET TRUE
08-24 17:09:31.748  8169  8169 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-24 17:09:31.748  1928  2205 D WfdsService: selectPreferredScanChannel [36]
08-24 17:09:31.748  1928  2205 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-24 17:09:31.749  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-24 17:09:31.750  1928  1928 D WfdsService: isConnected: false
,08-24 17:09:31.751  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 17:09:31.751  1038  1038 D RttService: SCAN_AVAILABLE : 3
08-24 17:09:31.751  1038  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.751  1038  1543 I WifiNative-HAL: startHal
08-24 17:09:31.751  1038  1543 D wifi    : getting scan capabilities on interface[1] = 0x9536c4c0
08-24 17:09:31.751  1038  1543 D wifi    : failed to get capabilities : -3
08-24 17:09:31.751  1038  1543 E WifiScanningService: could not get scan capabilities
08-24 17:09:31.752  1038  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.753  1038  1379 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-24 17:09:31.754  1038  1379 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-24 17:09:31.754  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:31.755  1038  1379 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-24 17:09:31.756  1038  1379 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-24 17:09:31.757  1038  1379 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-24 17:09:31.758  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-24 17:09:31.758  1038  1379 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-24 17:09:31.759  1038  1377 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-24 17:09:31.759  1038  1377 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-24 17:09:31.759  1038  1377 D WifiNative-p2p0: P2P_FLUSH: returned true
08-24 17:09:31.759  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-24 17:09:31.759  1038  1377 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-24 17:09:31.759  1038  1377 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-24 17:09:31.760  1038  1377 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-24 17:09:31.760  1038  1377 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-24 17:09:31.760  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
08-24 17:09:31.760  1038  1379 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-24 17:09:31.761  1038  1379 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-24 17:09:31.761  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-24 17:09:31.761  1928  1928 D WfdsService: Update P2p Interface State: 3
,08-24 17:09:31.767  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:31.769  8169  8169 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-24 17:09:31.769  1038  1377 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-24 17:09:31.769  1038  1377 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-24 17:09:31.769  1038  1379 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-24 17:09:31.770  1038  1379 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-24 17:09:31.771  1038  1379 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-24 17:09:31.771  1038  1379 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-24 17:09:31.771  8169  8169 E wpa_supplicant: disconnect_rssi_lvl: -100
08-24 17:09:31.771  1038  1377 D LGWifiP2pService: InactiveState
08-24 17:09:31.771  1038  1377 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.771  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.771  1038  1377 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-24 17:09:31.771  1038  1379 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 17:09:31.772  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 17:09:31.772  1038  1379 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 17:09:31.772  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.772  8169  8169 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 17:09:31.773  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.773  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.774  1928  8220 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 17:09:31.774  1928  8220 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.774  1928  8220 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.774  1038  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 17:09:31.774  1038  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.774  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.774  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.774  1038  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.774  1038  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.774  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.774  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.774  1038  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.774  1038  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.774  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.774  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.774  1038  1377 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-24 17:09:31.774  1038  1377 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.774  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal,.util.StateMachine$SmHandler }
08-24 17:09:31.775  1038  1377 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.775  1038  1377 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.775  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.775  1038  1377 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.775  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.775  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.775  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.775  1928  2205 W WfdsService: DefaultState - msg [9441285] is not handled
,08-24 17:09:31.776  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.776  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.776  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.776  1038  1038 E WifiServerServiceExt: No p2p device connected
08-24 17:09:31.776  1038  1379 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-24 17:09:31.776  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-24 17:09:31.779  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-24 17:09:31.779  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.779  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-24 17:09:31.779  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.780  8169  8169 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-24 17:09:31.780  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.780  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-24 17:09:31.780  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  1038  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.780  1038  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  1038  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.780  1038  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-24 17:09:31.780  1038  1379 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-24 17:09:31.781  1928  8220 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.781  1928  8220 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-24 17:09:31.781  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.781  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:31.781  1038  1379 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-24 17:09:31.782  1038  1379 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-24 17:09:31.782  1038  1379 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-24 17:09:31.782  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-24 17:09:31.782  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-24 17:09:31.782  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:31.783  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-24 17:09:31.783  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatch,Event: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:31.783  1038  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:31.783  1038  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-24 17:09:31.783  1038  1379 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-24 17:09:31.783  1038  1379 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-24 17:09:31.783  1038  1379 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-24 17:09:31.784  1038  1379 D WifiNative-wlan0: doBoolean: SCAN
08-24 17:09:31.784  1038  1379 D WifiNative-wlan0: SCAN: returned false
08-24 17:09:31.784  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=208362  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 17:09:31.785  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:31.786  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=208363  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-24 17:09:31.786  4779  4779 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-24 17:09:31.786  8176  8223 V FormManager: Network unavailable.
08-24 17:09:31.786  1038  1379 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:31.787  1038  1379 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:31.787  1038  1379 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:31.787  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:31.787  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:31.787  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:31.787  1038  1379 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:31.788  1038  1379 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-24 17:09:31.788  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:31.788  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:31.789  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:31.789  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 17:09:31.790  8176  8222 W FormManager: Network not available. Please check & try again.
,08-24 17:09:31.792  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:31.792  1038  1038 D WifiServerServiceExt: setSupplicantStateSCANNING
08-24 17:09:31.794  4779  4779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-24 17:09:31.799  4779  8224 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-24 17:09:31.801  4779  8225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-24 17:09:31.801  4779  8225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:09:31.807  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:09:31.809  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:09:31.814  6862  6941 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-24 17:09:31.815  6862  6941 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 17:09:31.817  6862  6941 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9c963e1 Bundle[{}]
08-24 17:09:31.818  6862  6941 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 17:09:31.818  6862  6941 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 17:09:31.819  6862  6941 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 17:09:31.820  6862  6941 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 17:09:31.820  6862  6941 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 17:09:31.821  6862  6941 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-24 17:09:31.829  6862  6941 I System.out: Running OutgoingSocketThread
08-24 17:09:31.830  6862  8226 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 896)
08-24 17:09:31.831  6862  8226 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60864
08-24 17:09:31.831  6862  8226 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 17:09:31.843  1038  1945 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8227 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 17:09:31.848  8176  8223 V FormManager: Network unavailable.
,08-24 17:09:31.961  8227  8227 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 17:09:31.962  8227  8227 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-24 17:09:31.966  7890  7901 E UEI.SmartControl: file observer is disposed!
08-24 17:09:31.975  8227  8227 V [BNRBootReceiver]: Boot Receiver Return
08-24 17:09:31.980  8227  8227 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 17:09:32.050  1038  1984 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8245 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-24 17:09:32.052  1038  1984 I ActivityManager: Killing 7310:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-24 17:09:32.111  1038  1910 W libprocessgroup: failed to open /acct/uid_10085/pid_7310/cgroup.procs: No such file or directory
,08-24 17:09:32.144  8245  8245 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 17:09:32.168  8245  8245 D PluginManager: init()
,08-24 17:09:32.235  8169  8169 E wpa_supplicant: USIM:  scard_init function
08-24 17:09:32.236  8169  8169 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-24 17:09:32.241  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-24 17:09:32.241  1038  8217 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-24 17:09:32.241  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-24 17:09:32.242  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-24 17:09:32.242  1038  8217 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-24 17:09:32.242  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-24 17:09:32.242  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-24 17:09:32.247  1038  1379 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-24 17:09:32.249  1038  1379 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-24 17:09:32.250  1038  1379 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-24 17:09:32.251  1038  1379 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-24 17:09:32.251  1038  1379 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-24 17:09:32.255  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=208833  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-24 17:09:32.257  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=208835  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-24 17:09:32.260  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.260  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:32.261  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.261  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.261  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-24 17:09:32.262  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.263  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.263  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.263  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 17:09:32.263  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:32.263  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-24 17:09:32.281  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.281  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-24 17:09:32.285  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.361  8169  8169 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 17:09:32.363  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-24 17:09:32.363  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-24 17:09:32.363  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-24 17:09:32.363  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-24 17:09:32.363  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:32.363  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:32.364  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=208941  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 17:09:32.364  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=208942  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-24 17:09:32.364  1038  1379 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=208942
08-24 17:09:32.365  1038  1379 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=208943
08-24 17:09:32.365  1038  1379 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=208943
08-24 17:09:32.365  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=208943
08-24 17:09:32.365  1038  1379 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=208943
08-24 17:09:32.366  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=208944  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 17:09:32.368  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.368  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:32.369  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.369  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.370  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-24 17:09:32.371  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 17:09:32.371  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=208948  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-24 17:09:32.372  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.372  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.373  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.373  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-24 17:09:32.375  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.375  1592  1592 ,I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:32.376  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 17:09:32.381  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:32.381  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-24 17:09:32.382  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:32.382  1038  1038 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-24 17:09:32.382  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:32.382  1038  1379 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:32.382  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:32.383  8169  8169 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:09:32.383  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-24 17:09:32.383  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:09:32.383  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 17:09:32.383  1038  8217 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:09:32.383  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-24 17:09:32.383  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 17:09:32.383  1038  8217 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-24 17:09:32.384  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:32.384  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:32.388  1038  1379 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-24 17:09:32.389  1038  1379 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:32.389  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:32.389  1038  1379 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-24 17:09:32.391  1038  1379 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=208968  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 17:09:32.391  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=208969  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-24 17:09:32.392  1038  1379 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=208970
08-24 17:09:32.392  1038  1379 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=208970
08-24 17:09:32.393  1038  1379 D WifiNative-wlan0: doString: [STATUS]
08-24 17:09:32.393  1038  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-24 17:09:32.393  1038  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-24 17:09:32.394  1038  1379 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-24 17:09:32.395  1038  1379 I WifiServiceExtension: setVHTCapabilityType  : false
,08-24 17:09:32.402  1038  1379 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-24 17:09:32.402  1038  1379 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-24 17:09:32.405  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.405  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.405  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-24 17:09:32.411  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.411  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.411  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-24 17:09:32.412  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.412  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:32.415  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.416  1038  1379 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-24 17:09:32.416  1038  1433 D ConnectivityService: Got NetworkAgent Messenger
08-24 17:09:32.416  1038  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:09:32.416  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 17:09:32.416  1038  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 17:09:32.416  1038  1433 D ConnectivityService: NetworkAgent connected
,08-24 17:09:32.417  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.417  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:32.417  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.419  1038  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 17:09:32.419  1038  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-24 17:09:32.424  1038  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 17:09:32.424  1038  1379 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:09:32.425  1038  1379 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-24 17:09:32.425  1038  1379 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-24 17:09:32.425  1038  1379 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-24 17:09:32.429  1038  1379 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-24 17:09:32.430   312   896 D CommandListener: Setting iface cfg
08-24 17:09:32.435  1038  1379 E WifiStateMachine: Start Dhcp Watchdog 3
08-24 17:09:32.435  1038  8266 D DhcpStateMachine: StoppedState
08-24 17:09:32.436  1038  8266 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.436  1038  8266 D DhcpStateMachine: WaitBeforeStartState
08-24 17:09:32.436  1038  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=209014  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:32.436  1038  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=209014  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:32.437  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=209015  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:32.438  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:32.438  1038  1038 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-24 17:09:32.438  1038  1379 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=209016  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:32.438  1038  1379 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=209016  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:32.439  1038  1379 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=209017  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-24 17:09:32.440  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13842] from screen [on:0 period:-1122410088] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-24 17:09:32.441  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1122410087] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-24 17:09:32.441  1038  1379 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-24 17:09:32.445  1038  1433 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-24 17:09:32.444  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.445  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.446  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.446  1038  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.447  1038  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.447  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.447  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.448  1038  1433 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 17:09:32.448  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-24 17:09:32.449  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-24 17:09:32.449  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-24 17:09:32.449  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-24 17:09:32.450  1038  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-24 17:09:32.450  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 0
08-24 17:09:32.450  1038  1379 D WifiNative-wlan0: SET ps 0: returned true
08-24 17:09:32.450  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-24 17:09:32.450  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-24 17:09:32.451  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-24 17:09:32.451  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d66bd2a target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.451  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d66bd2a target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.451  1038  8266 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.451  1038  8266 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-24 17:09:32.452  1038  1379 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-24 17:09:32.452  1038  1379 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 17:09:32.453  1038  1379 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-24 17:09:32.454   312   896 D CommandListener: Setting iface cfg
08-24 17:09:32.454   312   896 D CommandListener: Trying to bring up wlan0
08-24 17:09:32.455  1038  1379 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-24 17:09:32.456  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:32.456  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 17:09:32.457  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-24 17:09:32.457  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-24 17:09:32.457  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.457  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.458  1038  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.458  1038  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.459  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.459  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-24 17:09:32.460  1038  1433 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 17:09:32.460  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 17:09:32.461  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-24 17:09:32.461  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.461  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.461  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-24 17:09:32.462  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-24 17:09:32.462  1038  1379 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-24 17:09:32.462  1038  1379 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-24 17:09:32.462  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-24 17:09:32.463  1038  1379 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-24 17:09:32.463  1038  1379 D WifiNative-wlan0: doBoolean: SET ps 1
08-24 17:09:32.481  1038  1379 D WifiNative-wlan0: SET ps 1: returned true
08-24 17:09:32.481  1038  1433 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-24 17:09:32.482  1038  1379 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 17:09:32.482  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-24 17:09:32.482  1038  1379 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 17:09:32.483  1038  1433 D ConnectivityService: ignoring duplicate network state non-change
,08-24 17:09:32.485  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.485  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:32.486  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.486  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.486  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 17:09:32.486  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.487  1038  1433 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 17:09:32.488  1038  1433 D ConnectivityService: Adding iface wlan0 to network 102
,08-24 17:09:32.490  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.493  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-24 17:09:32.490  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.495  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-24 17:09:32.495  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-24 17:09:32.497  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.497  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.497  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 17:09:32.498  1038  1379 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 17:09:32.500  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-24 17:09:32.507  1038  1433 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 17:09:32.507  1038  1433 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-24 17:09:32.509  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.509  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-24 17:09:32.509  1038  1433 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-24 17:09:32.509   312   896 E Netd    : netlink response contains error (File exists)
08-24 17:09:32.510  1038  1433 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-24 17:09:32.511  1038  1433 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-24 17:09:32.511  1038  1433 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-24 17:09:32.511  1038  1433 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-24 17:09:32.512  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.513  1038  1433 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 17:09:32.513  1038  1433 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 17:09:32.513  1038  1433 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-24 17:09:32.513  1038  1433 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 17:09:32.513  1038  1433 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:32.513  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.513  1038  1433 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:32.513  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:32.513  1038  1433 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 17:09:32.513  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-24 17:09:32.513  1038  1433 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.513  1038  1433 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-24 17:09:32.513  1038  1433 D ConnectivityService: currentScore = 0, newScore = 20
08-24 17:09:32.513  1038  1433 D ConnectivityService:    accepting network in place of null
08-24 17:09:32.513  1038  1433 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.514  1038  8265 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.514  1038  8265 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-24 17:09:32.514  1038  8265 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:09:32.514  1038  8265 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-24 17:09:32.514  1038  1379 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.514  1038  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:32.516   312  8276 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-24 17:09:32.516  1841  1841 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17,:09:32.517  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 17:09:32.518  1038  1433 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 17:09:32.518  1038  1433 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-24 17:09:32.518  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 17:09:32.519  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:09:32.519  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 17:09:32.520  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.522  1038  1433 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:09:32.522  1038  1433 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-24 17:09:32.522  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 17:09:32.522  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-24 17:09:32.523  1038  1433 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-24 17:09:32.523  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.525  1038  1433 D ConnectivityService: validation of new default Network = false
08-24 17:09:32.525  1038  1433 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-24 17:09:32.525  1038  1433 D DSQN    : enableDataServiceNotify 
08-24 17:09:32.525  1038  1433 D DSQN    : start dsqn bin
08-24 17:09:32.529  1038  1038 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-24 17:09:32.529  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-24 17:09:32.529  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-24 17:09:32.529  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-24 17:09:32.532  1038  1433 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 17:09:32.532  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.532  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:32.532  1038  1433 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:32.529  8277  8277 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:32.529  8277  8277 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:32.534  1592  1819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 17:09:32.541  8277  8277 E DSQN    : DSQN ssw
,08-24 17:09:32.546  1038  1376 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-24 17:09:32.561  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 17:09:32.562  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.563  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.565   312  8276 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-24 17:09:32.581  8245  8245 W ExternalStrings: load override strings
08-24 17:09:32.581  8245  8245 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 17:09:32.581  8245  8245 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-24 17:09:32.583  8245  8245 D StatusProvider: onCreate
08-24 17:09:32.600   312  8276 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-24 17:09:32.634   312   895 D LGDataListener: argv[0]=dsqncommand
08-24 17:09:32.635   312   895 D LGDataListener: argv[1]=wlan0
08-24 17:09:32.635   312   895 D LGDataListener: argv[2]=1
,08-24 17:09:32.635   312   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-24 17:09:32.636  1038  1118 D DSQN    : DSQM DsqnNotification wlan0  1
08-24 17:09:32.636  1038  1118 D DSQN    : start to monitor internet connection
,08-24 17:09:32.641  8245  8245 V Signer  : override build config not found
,08-24 17:09:32.642  8245  8245 D Signer  : value of property debug is false
08-24 17:09:32.653  1038  8266 D DhcpStateMachine: DHCPV4 request on wlan0
08-24 17:09:32.654  1038  8266 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-24 17:09:32.654  1038  8266 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-24 17:09:32.649  8283  8283 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-24 17:09:32.649  8283  8283 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-24 17:09:32.668  1038  8265 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 15:09:32 GMT], X-Android-Received-Millis=[1472051372667], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472051372634]}
08-24 17:09:32.669  1038  8265 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-24 17:09:32.669  1038  8265 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-24 17:09:32.669  1038  1433 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-24 17:09:32.669  1038  1433 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-24 17:09:32.669  1038  1433 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:32.670  1038  1433 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:32.670  1038  1433 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-24 17:09:32.670  1038  1433 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-24 17:09:32.670  1038  1433 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-24 17:09:32.670  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.671  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:32.672  1038  1433 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:32.672  1038  1433 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.672  1592  1819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-24 17:09:32.673  1038  1433 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 17:09:32.673  1038  1379 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.673  1038  1379 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:09:32.674  1841  1841 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:32.675  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-24 17:09:32.677  8283  8283 I dhcpcd  : version 5.5.6 starting
08-24 17:09:32.679  8283  8283 E dhcpcd  : get_duid: m
08-24 17:09:32.679  8283  8283 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-24 17:09:32.679  8283  8283 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-24 17:09:32.693  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-24 17:09:32.693  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-24 17:09:32.693  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-24 17:09:32.694  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-24 17:09:32.694  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-24 17:09:32.694  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-24 17:09:32.695  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-24 17:09:32.695  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-24 17:09:32.695  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-24 17:09:32.696  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-24 17:09:32.696  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,08-24 17:09:32.696  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-24 17:09:32.696  8245  8245 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-24 17:09:32.705  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-24 17:09:32.708  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-24 17:09:32.710  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-24 17:09:32.713  8245  8245 V LGMDMManager: Create singleton instance
08-24 17:09:32.754  8283  8283 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-24 17:09:32.755  8283  8283 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-24 17:09:32.755  8283  8283 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-24 17:09:32.755  8283  8283 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-24 17:09:32.756  8283  8283 D dhcpcd  : wlan0: sending REQUEST (xid 0x428ba249), next in 3.02 seconds
08-24 17:09:32.780  8245  8245 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-24 17:09:32.789  8283  8283 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-24 17:09:32.820  8283  8283 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-24 17:09:32.820  8283  8283 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-24 17:09:32.821  8283  8283 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-24 17:09:32.821  8283  8283 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-24 17:09:32.821  8283  8283 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-24 17:09:32.821  8283  8283 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-24 17:09:32.821  8283  8283 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2,
08-24 17:09:32.821  8283  8283 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT,
,08-24 17:09:32.832  6862  6941 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 897)
08-24 17:09:32.832  6862  6941 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 897)
08-24 17:09:32.834  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:32.840  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-24 17:09:32.845  6862  6941 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 902)
08-24 17:09:32.846  6862  6941 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 17:09:32.846  6862  6941 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 903)
08-24 17:09:32.849  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:32.850  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25572424 added. We now have 2 listener(s)
08-24 17:09:32.851  1038  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:32.854  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:32.854  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:32.854  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:32.854  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:32.854  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af58b8d added. We now have 9 listener(s)
08-24 17:09:32.854  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:09:32.858  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:09:32.860  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:32.862  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:32.866  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:09:32.868  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:32.868  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:32.868  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:32.868  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31bf2553 added. We now have 3 listener(s)
08-24 17:09:32.869  1038  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:32.871  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:32.871  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:32.871  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:32.871  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:32.871  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf45e90 added. We now have 10 listener(s)
08-24 17:09:32.871  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:32.871  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:32.871  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:32.871  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:32.871  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:32.871  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:32.872  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:32.872  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:32.872  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:32.872  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25572424 removed from the list
08-24 17:09:32.872  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:32.872  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af58b8d removed from the list
08-24 17:09:32.873  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:32.874  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:32.875  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:32.875  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:32.875  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exi,st in the list - probably already removed
08-24 17:09:32.875  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:32.876  1592  1592 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-24 17:09:32.876  1592  1592 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 17:09:32.876  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:32.876  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:32.876  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:32.876  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af58b8d not in the list
08-24 17:09:32.876  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:32.876  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:32.877  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:32.877  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:32.877  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:32.877  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf45e90 removed from the list
08-24 17:09:32.877  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:32.877  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:32.877  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:32.877  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:32.877  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31bf2553 removed from the list
08-24 17:09:32.878  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:32.878  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3c5389 added. We now have 2 listener(s)
08-24 17:09:32.878  1038  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:32.880  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:32.880  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:32.880  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:32.880  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:32.880  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c197f8e added. We now have 9 listener(s)
08-24 17:09:32.880  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:32.881  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:09:32.883  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:32.885  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:32.887  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:32.887  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:32.887  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:32.887  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14e8d3bc added. We now have 3 listener(s)
08-24 17:09:32.889  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:32.890  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:32.933  1038  1591 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8305 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-24 17:09:32.935  1038  1591 I ActivityManager: Killing 7344:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-24 17:09:33.014  8245  8292 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 17:09:33.057  1038  8266 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-24 17:09:33.057  1038  8266 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-24 17:09:33.058  1038  8266 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-24 17:09:33.058  1038  8266 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-24 17:09:33.058  1038  8266 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-24 17:09:33.058  1038  8266 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-24 17:09:33.058  1038  8266 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-24 17:09:33.058  1038  8266 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-24 17:09:33.058  1038  8266 D DhcpStateMachine: RunningState
08-24 17:09:33.146  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:33.151  1038  1432 D WifiController: battery changed pluggedType: 2
08-24 17:09:33.152  1592  1592 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
08-24 17:09:33.152  1592  1592 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 17:09:33.154  1928  2079 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 17:09:33.154  1928  2079 D LEDHandler: Battery Level Remaining: 100%
08-24 17:09:33.154  1928  2079 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
08-24 17:09:33.154  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:33.155  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:33.155  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:33.155  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:33.155  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@170d9f45 added. We now have 10 listener(s)
08-24 17:09:33.155  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:33.156  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:33.156  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:09:33.156  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 17:09:33.156  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:33.156  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:09:33.158  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:33.160  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:09:33.162  1592  1592 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 17:09:33.163  7789  8051 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 17:09:33.166  8227  8227 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 17:09:33.170  1038  1910 W libprocessgroup: failed to open /acct/uid_10093/pid_7344/cgroup.procs: No such file or directory
08-24 17:09:33.174  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 17:09:33.181  1038  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:33.186  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 17:09:33.187  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 17:09:33.188  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:09:33.189  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:33.190  6862  6941 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 17:09:33.191  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:33.191  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:33.192  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:33.193  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:33.193  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:33.193  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.193  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.193  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:33.193  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:33.193  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c3c5389 removed from the list
08-24 17:09:33.193  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.193  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c197f8e removed from the list
08-24 17:09:33.193  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:33.193  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.193  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.193  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.194  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.194  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:33.194  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.194  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c197f8e not in the list
08-24 17:09:33.194  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.194  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.195  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:33.196  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:33.196  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:33.196  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.196  6862  6941 I org.thal,iproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.196  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@170d9f45 removed from the list
08-24 17:09:33.196  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.196  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.196  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.196  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:33.196  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14e8d3bc removed from the list
08-24 17:09:33.197  8305  8305 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:33.197  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:33.197  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@394d6fa8 added. We now have 2 listener(s)
08-24 17:09:33.198  1038  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:33.203  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:33.203  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:33.203  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:33.203  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:33.203  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1edeac1 added. We now have 9 listener(s)
08-24 17:09:33.203  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:33.203  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:09:33.205  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:33.209  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:33.210  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:33.210  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:09:33.211  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:09:33.211  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcb79a7 added. We now have 3 listener(s)
08-24 17:09:33.211  1038  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:33.212  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:33.214  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:33.215  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:33.215  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:33.215  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:33.215  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:33.215  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cddde54 added. We now have 10 listener(s)
08-24 17:09:33.215  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:33.215  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:33.216  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:33.216  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:09:33.216  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:09:33.216  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:33.216  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:09:33.218  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 17:09:33.219  1038  1591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:33.223  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 17:09:33.223  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:09:33.226  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:09:33.226  7890  8021 D UEI.SmartControl: Internal timer expired: 3
08-24 17:09:33.226  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:33.226  7890  8021 D UEI.SmartControl: unbind internal service
08-24 17:09:33.229  7890  7890 D UEI.SmartControl: Service.onUnbind: IControl
08-24 17:09:33.229  6862  6941 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 17:09:33.230  7890  7890 D UEI.SmartControl: Service.onDestroy
08-24 17:09:33.230  7890  7890 D UEI.SmartControl: Lock is in USE false
08-24 17:09:33.230  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:33.230  7890  7890 D UEI.SmartControl: unbind internal service
08-24 17:09:33.230  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:33.230  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:33.230  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.230  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.230  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:33.230  7890  7890 D serial_port: close(fd = 24)
08-24 17:09:33.230  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:33.230  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@394d6fa8 removed from the list
08-24 17:09:33.230  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.230  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1edeac1 removed from the list
08-24 17:09:33.230  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:33.230  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.231  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.231  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.231  8305  8305 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-24 17:09:33.232  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.232  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:33.232  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.232  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1edeac1 not in the list
08-24 17:09:33.232  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.232  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.233  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager:, stopDiscovery
08-24 17:09:33.234  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:33.234  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:33.234  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.234  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.234  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cddde54 removed from the list
08-24 17:09:33.234  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.234  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.234  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.234  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:33.234  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcb79a7 removed from the list
08-24 17:09:33.235  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:33.235  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2c0943 added. We now have 2 listener(s)
08-24 17:09:33.235  7890  7890 I UEI.SmartControl: Serial port is closed.
08-24 17:09:33.235  7890  7890 I UEI.SmartControl: Serial port is closed.
08-24 17:09:33.235  7890  7890 D UEI.SmartControl: Blaster closed
08-24 17:09:33.236  7890  7890 D UEI.SmartControl: Shut down QS...
08-24 17:09:33.236  7890  7890 D UEI.SmartControl: Stopping QS lib
08-24 17:09:33.236  1038  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:33.238  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:33.238  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:33.238  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:09:33.238  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:33.238  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20648bc0 added. We now have 9 listener(s)
08-24 17:09:33.238  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:33.239  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:09:33.241  7890  7890 D UEI.SmartControl: QS lib stop result = true
08-24 17:09:33.241  7890  7890 D UEI.SmartControl: Stopped QS lib
08-24 17:09:33.241  7890  7890 D UEI.SmartControl: QS shutdown complete
,08-24 17:09:33.244  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:33.247  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:09:33.248  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:33.248  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:33.249  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:33.249  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8aae83e added. We now have 3 listener(s)
08-24 17:09:33.249  1038  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:33.251  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:33.251  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:33.251  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:33.251  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:33.252  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217bf69f added. We now have 10 listener(s)
08-24 17:09:33.252  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:33.252  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:33.252  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:09:33.252  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:09:33.252  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:33.252  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:09:33.252  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:33.254  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:09:33.255  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 17:09:33.255  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:33.258  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 17:09:33.259  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 17:09:33.260  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:09:33.261  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:33.262  6862  6941 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-24 17:09:33.264  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:33.264  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:33.264  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:33.264  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.264  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.264  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:33.264  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:33.264  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2c0943 removed from the list
08-24 17:09:33.264  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.265  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20648bc0 removed from the list
08-24 17:09:33.265  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:33.265  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.265  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.265  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.266  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.266  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:33.266  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.266  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20648bc0 not in the list
08-24 17:09:33.266  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.266  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.267  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:09:33.267  6862  6941 D BluetoothLeScanner: could not find callback wrapper
08-24 17:09:33.267  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:09:33.267  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.267  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.267  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217bf69f removed from the list
08-24 17:09:33.267  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.267  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.267  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.267  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:33.268  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8aae83e removed from the list
08-24 17:09:33.268  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:33.268  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8694a4a added. We now have 2 listener(s)
08-24 17:09:33.269  1038  1591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:33.271  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:33.272  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:33.272  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:33.272  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:33.272  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28b35dbb added. We now have 9 listener(s)
08-24 17:09:33.272  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:33.272  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:09:33.274  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:09:33.277  6862  6941 V io.jxcore.node.ConnectivityMonitor:     - active network ty,pe is Wi-Fi: true
08-24 17:09:33.277  8305  8305 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-24 17:09:33.277  8305  8305 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-24 17:09:33.278  8305  8305 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-24 17:09:33.278  8305  8305 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-24 17:09:33.278  8305  8305 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-24 17:09:33.280  8305  8305 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-24 17:09:33.285  6862  6941 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:09:33.285  6862  6941 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:09:33.285  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:09:33.285  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32260631 added. We now have 3 listener(s)
08-24 17:09:33.285  1038  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 17:09:33.286  8305  8305 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-24 17:09:33.287  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 17:09:33.287  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:09:33.287  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:09:33.288  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:09:33.288  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af9c116 added. We now have 10 listener(s)
08-24 17:09:33.288  6862  6941 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:09:33.288  6862  6941 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:09:33.288  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:33.288  6862  6941 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:09:33.288  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.288  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.288  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:09:33.288  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 17:09:33.288  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8694a4a removed from the list
08-24 17:09:33.288  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.289  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28b35dbb removed from the list
08-24 17:09:33.291  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:33.293  6862  6862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:09:33.293  6862  6941 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:09:33.293  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.293  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.293  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.293  8245  8292 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:33.293  8245  8292 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 17:09:33.294  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.294  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:33.294  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.294  6862  6941 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28b35dbb not in the list
08-24 17:09:33.294  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.294  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.295  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:09:33.295  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:09:33.295  6862  6941 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:09:33.295  6862  6941 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2af9c116 removed from the list
08-24 17:09:33.295  6862  6941 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:09:33.295  6862  6941 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:09:33.295  6862  6941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:09:33.295  6862  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:09:33.295  6862  6941 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32260631 removed from the list
08-24 17:09:33.296  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.296  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 17:09:33.296  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start o,peration: Should start/stop everything
08-24 17:09:33.296  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 17:09:33.296  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:09:33.296  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 17:09:33.297  6862  6941 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:09:33.297  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:33.308  6862  8342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 910, name: My test thread name)
08-24 17:09:33.308  6862  8342 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 910, thread name: My test thread name)
08-24 17:09:33.309  6862  8342 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 910, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 17:09:33.310  8305  8305 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:33.311  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-24 17:09:33.312  6862  8343 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 912, name: My test thread name)
08-24 17:09:33.312  6862  8343 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 912, thread name: My test thread name)
08-24 17:09:33.312  6862  8343 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 912, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 17:09:33.313  8305  8305 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-24 17:09:33.314  6862  6941 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-24 17:09:33.314  6862  6941 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 17:09:33.314  6862  6941 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 17:09:33.315  6862  6941 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 17:09:33.315  6862  6941 D com.test.thalitest.ThaliTestRunner: Total duration: 23289 ms
08-24 17:09:33.315  6992  6992 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-24 17:09:33.315  8305  8305 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-24 17:09:33.317  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.317  6862  6941 I jxcore-log: Total number of executed tests:  80
08-24 17:09:33.317  6862  6941 I jxcore-log: 
08-24 17:09:33.317  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.318  6862  6941 I jxcore-log: Number of passed tests:  80
08-24 17:09:33.318  6862  6941 I jxcore-log: 
08-24 17:09:33.318  6862  6941 I jxcore-log: Number of failed tests:  0
08-24 17:09:33.318  6862  6941 I jxcore-log: 
08-24 17:09:33.319  6862  6941 I jxcore-log: Number of ignored tests:  0
08-24 17:09:33.319  6862  6941 I jxcore-log: 
,08-24 17:09:33.319  6862  6941 I jxcore-log: Total duration:  23289
08-24 17:09:33.319  6862  6941 I jxcore-log: 
08-24 17:09:33.319  6862  6941 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 17:09:33.319  6862  6941 I jxcore-log: 
08-24 17:09:33.322  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:33.324  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.324  6862  6941 I jxcore-log: 
08-24 17:09:33.326  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.327  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.327  6862  6941 I jxcore-log: 
,08-24 17:09:33.328  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.328  6862  6941 I jxcore-log: 
08-24 17:09:33.330  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.330  6862  6941 I jxcore-log: 
08-24 17:09:33.331  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.331  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.331  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.331  6862  6941 I jxcore-log: 
08-24 17:09:33.332  8305  8305 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-24 17:09:33.333  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:09:33.333  6862  6941 I jxcore-log: 
08-24 17:09:33.334  6862  6862 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 17:09:33.335  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.335  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.341  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:33.342  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:09:33.342  6862  6941 I jxcore-log: 
08-24 17:09:33.344  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.344  6862  6941 I jxcore-log: 
08-24 17:09:33.345  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.345  6862  6941 I jxcore-log: 
,08-24 17:09:33.346  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:09:33.346  6862  6941 I jxcore-log: 
08-24 17:09:33.346  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.347  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:09:33.347  6862  6941 I jxcore-log: 
08-24 17:09:33.349  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:09:33.349  6862  6941 I jxcore-log: 
08-24 17:09:33.351  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.351  6862  6941 I jxcore-log: 
08-24 17:09:33.351  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.351  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.352  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.352  6862  6941 I jxcore-log: 
08-24 17:09:33.352  8305  8305 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:33.352  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.352  6862  6941 I jxcore-log: 
08-24 17:09:33.354  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.354  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.354  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.354  6862  6941 I jxcore-log: 
08-24 17:09:33.355  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.355  6862  6941 I jxcore-log: 
08-24 17:09:33.356  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.356  6862  6941 I jxcore-log: 
08-24 17:09:33.356  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.356  6862  6941 I jxcore-log: 
08-24 17:09:33.357  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:09:33.357  6862  6941 I jxcore-log: 
08-24 17:09:33.358  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:09:33.358  6862  6941 I jxcore-log: 
,08-24 17:09:33.359  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:09:33.359  6862  6941 I jxcore-log: 
08-24 17:09:33.360  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.360  6862  6941 I jxcore-log: 
08-24 17:09:33.360  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:33.361  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.361  6862  6941 I jxcore-log: 
08-24 17:09:33.362  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.362  6862  6941 I jxcore-log: 
08-24 17:09:33.363  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.363  6862  6941 I jxcore-log: 
08-24 17:09:33.364  6862  6941 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:09:33.364  6862  6941 I jxcore-log: 
08-24 17:09:33.366  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.372  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.372  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.373  8305  8305 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 17:09:33.375  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.375  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.380  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:33.385  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.390  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.391  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.391  8305  8305 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:33.393  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-24 17:09:33.393  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-24 17:09:33.393  6992  6992 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-24 17:09:33.393  6992  6992 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-24 17:09:33.393  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-24 17:09:33.394  6992  6992 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-24 17:09:33.394  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-24 17:09:33.394  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-24 17:09:33.394  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-24 17:09:33.394  6992  6992 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-24 17:09:33.394  6992  6992 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-24 17:09:33.394  6992  6992 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-24 17:09:33.397  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:33.400  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.400  8245  8292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-24 17:09:33.403  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:33.415  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.420  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.421  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.421  8305  8305 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:33.423  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.424  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.424  8245  8292 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-24 17:09:33.430  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:33.434  8245  8292 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-24 17:09:33.435  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.435  8245  8292 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 17:09:33.436  8245  8292 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-24 17:09:33.436  8245  8292 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-24 17:09:33.437  8245  8292 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-24 17:09:33.441  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.441  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.441  8305  8305 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-24 17:09:33.445  8245  8292 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-24 17:09:33.447  8245  8292 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-24 17:09:33.453  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.453  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-24 17:09:33.466  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:33.471  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.477  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.477  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:33.481  8305  8305 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:33.485  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.485  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.491  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:33.497  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:33.505  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.506  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.507  8305  8305 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-24 17:09:33.510  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.510  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.515  8199  8199 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 17:09:33.519  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-24 17:09:33.521  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-24 17:09:33.525  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-24 17:09:33.532  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.532  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-24 17:09:33.534  8305  8305 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-24 17:09:33.534  8305  8305 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 17:09:33.535  8305  8305 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 17:09:33.539  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.539  8245  8293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-24 17:09:33.541  8199  8199 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-24 17:09:33.542  8199  8199 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-24 17:09:33.545  6992  6992 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-24 17:09:33.549  6992  6992 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-24 17:09:33.555  8305  8305 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-24 17:09:33.555  8305  8305 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-24 17:09:33.556  8305  8305 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-24 17:09:33.556  8305  8305 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-24 17:09:33.556  8305  8305 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-24 17:09:33.559  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:33.581  8346  8346 D AndroidRuntime: 
08-24 17:09:33.581  8346  8346 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 17:09:33.584  8346  8346 D AndroidRuntime: CheckJNI is OFF
08-24 17:09:33.591  8305  8305 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-24 17:09:33.592  8305  8305 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-24 17:09:33.592  8305  8305 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-24 17:09:33.626  8305  8305 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:33.626  8305  8305 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 17:09:33.636  8305  8305 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-24 17:09:33.638  8305  8305 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-24 17:09:33.638  8305  8305 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-24 17:09:33.638  8305  8305 V SoundPool: doLoad: loading sample sampleID=1
08-24 17:09:33.638  8305  8361 V SoundPool: Start decode
08-24 17:09:33.638  8305  8361 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-24 17:09:33.638  8305  8305 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-24 17:09:33.641   316  1386 V MediaPlayerService: decode(22, 10857164, 17813)
,08-24 17:09:33.641   316  1386 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-24 17:09:33.642   316  1386 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-24 17:09:33.642   316  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-24 17:09:33.642   316  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-24 17:09:33.642   316  1386 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-24 17:09:33.642   316  1386 V MediaPlayerService: player type = 3
08-24 17:09:33.642   316  1386 V AwesomePlayer: AwesomePlayer create()
08-24 17:09:33.643   316  1386 V AwesomePlayer: reset_l() 
08-24 17:09:33.643   316  1386 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:33.643   316  1386 V AwesomePlayer: setAudioSink() 
08-24 17:09:33.643   316  1386 V AwesomePlayer: reset_l() 
08-24 17:09:33.643   316  1386 V AudioCache: notify(0xb100d440, 8, 0, 0)
08-24 17:09:33.643   316  1386 V AudioCache: ignored
08-24 17:09:33.643   316  1386 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:33.643   316  1386 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-24 17:09:33.643   316  1386 V AwesomePlayer: setDataSource_l dataSource
08-24 17:09:33.643   316  1386 V LGParserOSAL: SniffLGParser start
08-24 17:09:33.643   316  1386 V LGParserOSAL: MainType:5, SubType=0
08-24 17:09:33.643   316  1386 V LGParserOSAL: #### check Mime : application/ogg
08-24 17:09:33.643   316  1386 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-24 17:09:33.643   316  1386 E MediaExtractor: Use LGExtractor :application/ogg 
08-24 17:09:33.645  8305  8305 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-24 17:09:33.649  8305  8305 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-24 17:09:33.649  7890  7890 D UEI.SmartControl: QS Service created
08-24 17:09:33.649  8305  8305 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-24 17:09:33.663  8305  8305 V LGMDMManager: Create singleton instance
08-24 17:09:33.672  7890  7890 I UEI.SmartControl: Service initServices...
08-24 17:09:33.672  7890  7890 D UEI.SmartControl: QS start get config
,08-24 17:09:33.689   316  1386 V LGParserOSAL: supported mime: application/ogg
08-24 17:09:33.690   316  1386 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-24 17:09:33.690   316  1386 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-24 17:09:33.690   316  1386 V AwesomePlayer: mBitrate = -1 bits/sec
08-24 17:09:33.690   316  1386 V AwesomePlayer: AudioTrack Setting
08-24 17:09:33.690   316  1386 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-24 17:09:33.690   316  1386 V AwesomePlayer: setAudioSource() 
08-24 17:09:33.690   316  1386 V MediaPlayerService: prepare
08-24 17:09:33.690   316  1386 V AwesomePlayer: prepareAsync_l() 
08-24 17:09:33.690   316  1386 V MediaPlayerService: wait for prepare
08-24 17:09:33.690   316  8366 V AwesomePlayer: onPrepareAsyncEvent() 
08-24 17:09:33.690   316  8366 V AwesomePlayer: initAudioDecoder() 
08-24 17:09:33.690   316  8366 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 17:09:33.690   316  8366 V AudioSystem: isOffloadSupported()
08-24 17:09:33.690   316  8366 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 17:09:33.690   316  8366 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 17:09:33.690   316  8366 I AudioFlinger: isAudioPlaybackHookOn() false
08-24 17:09:33.690   316  8366 V AwesomePlayer: getUseOffload() = 0 
08-24 17:09:33.690   316  8366 V OMXCodec: OMXCodec::Create
08-24 17:09:33.690   316  8366 V OMXCodec: findMatchingCodecs()
08-24 17:09:33.690   316  8366 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-24 17:09:33.691   316  8366 V OMXCodec: matchingCodecs.size()=1
08-24 17:09:33.691   316  8366 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-24 17:09:33.692   316  8366 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-24 17:09:33.692   316  8366 V LGCodecAdapter: LG Codec Adapter start
08-24 17:09:33.692   316  8366 V OMXCodec: OMXCodec Createtor
08-24 17:09:33.692   316  8366 V OMXCodec: setComponentRole
08-24 17:09:33.692   316  8366 V OMXCodec: configureCodec protected=0
08-24 17:09:33.692   316  8366 V LGCodecAdapter: called getLGCodecSpecificData
08-24 17:09:33.692   316  8366 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-24 17:09:33.692   316  8366 V LGCodecOSAL: Called LGconfigureCodecMETA
08-24 17:09:33.693   316  8366 V LGCodecOSAL: Called LGconfigureCodecMSG
08-24 17:09:33.693   316  8366 V LGCodecOSAL: Not support LGCodec
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-24 17:09:33.693   316  8366 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-24 17:09:33.693   316  8366 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-24 17:09:33.693   316  8366 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-24 17:09:33.693   316  8366 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-24 17:09:33.693   316  8366 V AudioSystem: isOffloadSupported()
08-24 17:09:33.693   316  8366 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-24 17:09:33.693   316  8366 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-24 17:09:33.693   316  8366 V OMXCodec: init()
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-24 17:09:33.693   316  8366 V OMXCodec: allocateBuffers
08-24 17:09:33.693   316  8366 V OMXCodec: allocateBuffersOnPort portIndex=0
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
,08-24 17:09:33.693   316  8366 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 17:09:33.693   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 17:09:33.694   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-24 17:09:33.694   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-24 17:09:33.694   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-24 17:09:33.694   316  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb240 on output port
08-24 17:09:33.694   316  8366 V OMXCodec: init() mAsyncCompletion wait!!! 
08-24 17:09:33.694   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-24 17:09:33.694   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 17:09:33.694   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-24 17:09:33.694   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-24 17:09:33.694   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-24 17:09:33.694   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-24 17:09:33.695   316  8366 V OMXCodec: init() mAsyncCompletion wait free! 
08-24 17:09:33.695   316  8366 V AwesomePlayer: finishAsyncPrepare_l() 
08-24 17:09:33.695   316  8366 V AudioCache: notify(0xb100d440, 5, 0, 0)
08-24 17:09:33.695   316  8366 V AudioCache: ignored
08-24 17:09:33.695   316  8366 V AudioCache: notify(0xb100d440, 1, 0, 0)
,08-24 17:09:33.695   316  8366 V AudioCache: prepared
08-24 17:09:33.696   316  1386 V AudioCache: wait - success
08-24 17:09:33.696   316  1386 V MediaPlayerService: start
08-24 17:09:33.696   316  1386 V AwesomePlayer: play_l() 
08-24 17:09:33.696   316  1386 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-24 17:09:33.696   316  1386 V AwesomePlayer: createAudioPlayer_l
08-24 17:09:33.696   316  1386 V AwesomePlayer: seekAudioIfNecessary_l() 
08-24 17:09:33.696   316  1386 V AwesomePlayer: startAudioPlayer_l() 
08-24 17:09:33.696   316  1386 D AudioPlayer: start of Playback, useOffload 0
,08-24 17:09:33.696   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 17:09:33.696   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-24 17:09:33.699   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-24 17:09:33.699   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-24 17:09:33.699   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-24 17:09:33.699   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-24 17:09:33.699   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-24 17:09:33.699   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 17:09:33.700   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
,08-24 17:09:33.700   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:33.700   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-24 17:09:33.700   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:33.700   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-24 17:09:33.700   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:33.700   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782656
08-24 17:09:33.701   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:33.701   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-24 17:09:33.701   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-24 17:09:33.701   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-24 17:09:33.701   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-24 17:09:33.701   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-24 17:09:33.701   316  8368 V OMXCodec: allocateBuffersOnPort portIndex=1
08-24 17:09:33.701   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-24 17:09:33.702   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-24 17:09:33.702   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-24 17:09:33.702   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-24 17:09:33.702   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on output port
,08-24 17:09:33.702   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-24 17:09:33.702   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-24 17:09:33.703   316  1386 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-24 17:09:33.705   316  1386 V AudioCache: notify(0xb100d440, 6, 0, 0)
08-24 17:09:33.705   316  1386 V AudioCache: ignored
,08-24 17:09:33.705   316  1386 V MediaPlayerService: wait for playback complete
08-24 17:09:33.708   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.708   316  8369 V AudioCache: memcpy(0xaf0f9000, 0xb16f4000, 4096)
08-24 17:09:33.712   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.713   316  8369 V AudioCache: memcpy(0xaf0fa000, 0xb16f4000, 4096)
08-24 17:09:33.713   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.713   316  8369 V AudioCache: memcpy(0xaf0fb000, 0xb16f4000, 4096)
08-24 17:09:33.714   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.714   316  8369 V AudioCache: memcpy(0xaf0fc000, 0xb16f4000, 4096)
08-24 17:09:33.715   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.715   316  8369 V AudioCache: memcpy(0xaf0fd000, 0xb16f4000, 4096)
08-24 17:09:33.716   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.716   316  8369 V AudioCache: memcpy(0xaf0fe000, 0xb16f4000, 4096)
08-24 17:09:33.717   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.717   316  8369 V AudioCache: memcpy(0xaf0ff000, 0xb16f4000, 4096)
08-24 17:09:33.718   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.718   316  8369 V AudioCache: memcpy(0xaf100000, 0xb16f4000, 4096)
08-24 17:09:33.719   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.719   316  8369 V AudioCache: memcpy(0xaf101000, 0xb16f4000, 4096)
08-24 17:09:33.719   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.720   316  8369 V AudioCache: memcpy(0xaf102000, 0xb16f4000, 4096)
08-24 17:09:33.721   316  8369 V AudioCache: write(0xb16f4000, 4096)
,08-24 17:09:33.721   316  8369 V AudioCache: memcpy(0xaf103000, 0xb16f4000, 4096)
08-24 17:09:33.722   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.722   316  8369 V AudioCache: memcpy(0xaf104000, 0xb16f4000, 4096)
,08-24 17:09:33.723   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.723   316  8369 V AudioCache: memcpy(0xaf105000, 0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: memcpy(0xaf106000, 0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: memcpy(0xaf107000, 0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: memcpy(0xaf108000, 0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.725   316  8369 V AudioCache: memcpy(0xaf109000, 0xb16f4000, 4096)
08-24 17:09:33.727   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.727   316  8369 V AudioCache: memcpy(0xaf10a000, 0xb16f4000, 4096)
08-24 17:09:33.728   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.728   316  8369 V AudioCache: memcpy(0xaf10b000, 0xb16f4000, 4096)
08-24 17:09:33.728   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.728   316  8369 V AudioCache: memcpy(0xaf10c000, 0xb16f4000, 4096)
08-24 17:09:33.728   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.728   316  8369 V AudioCache: memcpy(0xaf10d000, 0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: memcpy(0xaf10e000, 0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: memcpy(0xaf10f000, 0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: memcpy(0xaf110000, 0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.734   316  8369 V AudioCache: memcpy(0xaf111000, 0xb16f4000, 4096)
08-24 17:09:33.736   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.736   316  8369 V AudioCache: memcpy(0xaf112000, 0xb16f4000, 4096)
08-24 17:09:33.736   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.736   316  8369 V AudioCache: memcpy(0xaf113000, 0xb16f4000, 4096)
08-24 17:09:33.736   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.737   316  8369 V AudioCache: memcpy(0xaf114000, 0xb16f4000, 4096)
08-24 17:09:33.737   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.737   316  8369 V AudioCache: memcpy(0xaf115000, 0xb16f4000, 4096)
08-24 17:09:33.739   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.739   316  8369 V AudioCache: memcpy(0xaf116000, 0xb16f4000, 4096)
08-24 17:09:33.739   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.739   316  8369 V AudioCache: memcpy(0xaf117000, 0xb16f4000, 4096)
08-24 17:09:33.739   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.739   316  8369 V AudioCache: memcpy(0xaf118000, 0xb16f4000, 4096)
08-24 17:09:33.739   316  8369 V AudioCache: write(0xb16f4000, 4096)
,08-24 17:09:33.739   316  8369 V AudioCache: memcpy(0xaf119000, 0xb16f4000, 4096)
08-24 17:09:33.740   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.740   316  8369 V AudioCache: memcpy(0xaf11a000, 0xb16f4000, 4096)
08-24 17:09:33.741   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.741   316  8369 V AudioCache: memcpy(0xaf11b000, 0xb16f4000, 4096)
08-24 17:09:33.742   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.742   316  8369 V AudioCache: memcpy(0xaf11c000, 0xb16f4000, 4096)
08-24 17:09:33.744   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.744   316  8369 V AudioCache: memcpy(0xaf11d000, 0xb16f4000, 4096)
08-24 17:09:33.745   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.745   316  8369 V AudioCache: memcpy(0xaf11e000, 0xb16f4000, 4096)
08-24 17:09:33.746   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.746   316  8369 V AudioCache: memcpy(0xaf11f000, 0xb16f4000, 4096)
08-24 17:09:33.746   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.746   316  8369 V AudioCache: memcpy(0xaf120000, 0xb16f4000, 4096)
08-24 17:09:33.747   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.747   316  8369 V AudioCache: memcpy(0xaf121000, 0xb16f4000, 4096)
08-24 17:09:33.748   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.748   316  8369 V AudioCache: memcpy(0xaf122000, 0xb16f4000, 4096)
08-24 17:09:33.749   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.749   316  8369 V AudioCache: memcpy(0xaf123000, 0xb16f4000, 4096)
08-24 17:09:33.749   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.749   316  8369 V AudioCache: memcpy(0xaf124000, 0xb16f4000, 4096)
08-24 17:09:33.750  8305  8305 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-24 17:09:33.750   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.750   316  8369 V AudioCache: memcpy(0xaf125000, 0xb16f4000, 4096)
08-24 17:09:33.750  8305  8305 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-24 17:09:33.751   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.751   316  8369 V AudioCache: memcpy(0xaf126000, 0xb16f4000, 4096)
08-24 17:09:33.751   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.751   316  8369 V AudioCache: memcpy(0xaf127000, 0xb16f4000, 4096)
08-24 17:09:33.752   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.752   316  8369 V AudioCache: memcpy(0xaf128000, 0xb16f4000, 4096)
08-24 17:09:33.753   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.753   316  8369 V AudioCache: memcpy(0xaf129000, 0xb16f4000, 4096)
08-24 17:09:33.753   316  8369 V AudioCache: write(0xb16f4000, 4096)
08-24 17:09:33.753   316  8369 V AudioCache: memcpy(0xaf12a000, 0xb16f4000, 4096)
08-24 17:09:33.754   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-24 17:09:33.754   316  8369 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-24 17:09:33.754   316  8369 V AwesomePlayer: postAudioEOS() 
08-24 17:09:33.755   316  8369 V AudioCache: write(0xb16f4000, 280)
08-24 17:09:33.755   316  8369 V AudioCache: memcpy(0xaf12b000, 0xb16f4000, 280)
08-24 17:09:33.755   316  8366 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-24 17:09:33.756   316  8366 V AwesomePlayer: onStreamDone
08-24 17:09:33.756   316  8366 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-24 17:09:33.756   316  8366 V AudioCache: notify(0xb100d440, 2, 0, 0)
08-24 17:09:33.756   316  8366 V AudioCache: playback complete
08-24 17:09:33.756   316  8366 V AwesomePlayer: pause_l() 
08-24 17:09:33.756   316  8366 V AudioCache: notify(0xb100d440, 7, 0, 0)
08-24 17:09:33.756   316  8366 V AudioCache: ignored
08-24 17:09:33.756   316  8366 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:33.756   316  1386 V AudioCache: wait - success
08-24 17:09:33.756   316  1386 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-24 17:09:33.756   316  8366 D AudioPlayer: Pause Playback at 1068125
08-24 17:09:33.756   316  1386 V AwesomePlayer: reset_l() 
08-24 17:09:33.756   316  1386 V AudioCache: notify(0xb100d440, 8, 0, 0)
08-24 17:09:33.756   316  1386 V AudioCache: ignored
08-24 17:09:33.756   316  1386 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:33.756   316  1386 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-24 17:09:33.756   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-24 17:09:33.756   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-24 17:09:33.756   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-24 17:09:33.756   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-24 17:09:33.757   316  8368 V OMXCod,ec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 1
08-24 17:09:33.757  8305  8305 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3828
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-24 17:09:33.757   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-24 17:09:33.757   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 17:09:33.757   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-24 17:09:33.758   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-24 17:09:33.758   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-24 17:09:33.758   316  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-24 17:09:33.758   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-24 17:09:33.758   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-24 17:09:33.758   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-24 17:09:33.758   316  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-24 17:09:33.759   316  1386 D AudioPlayer: AudioPlayer releasing audio source
08-24 17:09:33.759   316  1386 D AudioPlayer: AudioPlayer done releasing audio source
08-24 17:09:33.759   316  1386 V AwesomePlayer: reset_l() 
08-24 17:09:33.759   316  1386 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:33.759   316  1386 V AwesomePlayer: ~AwesomePlayer call
08-24 17:09:33.759   316  1386 V AwesomePlayer: reset_l() 
08-24 17:09:33.759   316  1386 V AwesomePlayer: cancelPlayerEvents
08-24 17:09:33.759  8305  8361 V SoundPool: close(31)
08-24 17:09:33.759  8305  8361 V SoundPool: pointer = 0x9fe48000, size = 205080, sampleRate = 48000, numChannels = 2
08-24 17:09:33.759  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.762  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:33.763  8346  8346 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 17:09:33.765  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.770  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.772  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.773  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:33.775  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:33.777  1038  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-24 17:09:33.777  1038  1101 I ActivityManager: Killing 6862:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-24 17:09:33.778  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:33.830  1038  1984 I WindowState: WIN DEATH: Window{2a396309 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 17:09:33.831  1038  1432 D WifiService: Client connection lost with reason: 4
,08-24 17:09:33.836  1038  1984 D InputDispatcher: Window went away: Window{2a396309 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 17:09:34.024  1038  1101 I ActivityManager:   Force finishing activity ActivityRecord{257a54ba u0 com.test.thalitest/.MainActivity t6}
,08-24 17:09:34.050   331   347 E GBMv2   : DFP En is all cleared set to be enabled
08-24 17:09:34.057  1038  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-24 17:09:34.061  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-24 17:09:34.064  1038  1126 I ActivityManager:   Force finishing activity ActivityRecord{257a54ba u0 com.test.thalitest/.MainActivity t6 f}
08-24 17:09:34.064  1038  1126 W ActivityManager: Duplicate finish request for ActivityRecord{257a54ba u0 com.test.thalitest/.MainActivity t6 f}
,08-24 17:09:34.085  7890  7890 I UEI.SmartControl: Supports setup maps: true
08-24 17:09:34.094  7890  7890 D UEI.SmartControl: QS start statue = true Error code = 0
08-24 17:09:34.094  7890  7890 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-24 17:09:34.094  7890  7890 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-24 17:09:34.094  7890  7890 I UEI.SmartControl: ### init IR Blaster...
,08-24 17:09:34.100  7890  7890 D serial_port: Configuring serial port
08-24 17:09:34.100  1038  1983 W ActivityManager: Spurious death for ProcessRecord{22a2845c 6862:com.test.thalitest/u0a118}, curProc for 6862: null
08-24 17:09:34.100  7890  7890 E UEI.SmartControl: UEIBLaster setting for 616
08-24 17:09:34.100  7890  7890 I UEI.SmartControl: Setting serial record hearder size = 2
08-24 17:09:34.100  7890  7890 I UEI.SmartControl: configuring settings for MAXQ616
08-24 17:09:34.100  7890  7890 I UEI.SmartControl: Get version...
08-24 17:09:34.102  1928  2662 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-24 17:09:34.102  1928  2662 D SplitWindowPolicy: topRunningActivity=ActivityInfo{86749b2 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 17:09:34.104  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-24 17:09:34.105  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3e1acd03 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-24 17:09:34.112  2022  2022 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-24 17:09:34.115  1592  1592 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-24 17:09:34.116  7890  8372 D UEI.SmartControl: serial port data available: 21
08-24 17:09:34.116  2022  2022 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-24 17:09:34.124  3760  3760 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-24 17:09:34.125  1985  1985 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-24 17:09:34.126  7789  7789 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-24 17:09:34.126  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 17:09:34.128  2493  2610 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 17:09:34.136  1038  1368 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 17:09:34.137  4939  4939 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 17:09:34.137  4939  4939 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 17:09:34.137  4939  4939 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 17:09:34.137  4939  4939 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-24 17:09:34.137  4939  4939 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 17:09:34.137  4939  4939 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 17:09:34.138  4939  4939 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 17:09:34.138  4939  4939 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 17:09:34.138  4939  4939 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:09:34.138  4939  4939 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:09:34.138  4939  4939 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 17:09:34.138  4939  4939 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-24 17:09:34.145  7890  7890 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-24 17:09:34.145  7890  7890 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-24 17:09:34.145  7890  7890 I UEI.SmartControl: QS saving settings...
08-24 17:09:34.147  7890  7890 D UEI.SmartControl: IR Blaster version: 25672567
,08-24 17:09:34.169  5047  5047 I art     : Explicit concurrent mark sweep GC freed 8196(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 547us total 94.262ms
,08-24 17:09:34.170  7890  8372 D UEI.SmartControl: serial port data available: 4
08-24 17:09:34.203  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-24 17:09:34.204  2022  2116 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-24 17:09:34.204  1592  1592 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-24 17:09:34.209  2022  2022 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-24 17:09:34.210  2022  2022 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-24 17:09:34.210  2022  2022 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-24 17:09:34.212  1592  1639 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 17:09:34.212  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.212  2022  2022 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-24 17:09:34.213  1892  1892 D ActionManagerService: notifyUserLog: 1000003
08-24 17:09:34.214  3760  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-24 17:09:34.215  1592  1639 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-24 17:09:34.215  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.222  1892  1892 D ActionManagerService: notifyUserLog: 1000004
08-24 17:09:34.222  3760  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-24 17:09:34.223  2022  2022 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-24 17:09:34.225  7890  7890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-24 17:09:34.225  3760  3776 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 17:09:34.225  7890  7890 E UEI.SmartControl: Services init done
08-24 17:09:34.225  7890  7890 D UEI.SmartControl: QS Service init finished
,08-24 17:09:34.227  7890  8375 I UEI.SmartControl: Device manager: loading config....
08-24 17:09:34.227  7890  8375 D UEI.SmartControl: ----------- loading internal config...
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , create_time: 1430832262123
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , expire_time: 0
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , display: false
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , animation: false }
,08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , create_time: 1430832262287
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , expire_time: 0
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , display: false
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , animation: false }
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , create_time: 1471602816196
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , expire_time: 0
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , display: false
08-24 17:09:34.227  2022  2022 I GBoardWebViewUtils: , animation: false }
08-24 17:09:34.227  1592  1639 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 17:09:34.228  1592  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:34.228  1592  1639 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 17:09:34.230  1592  1639 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 17:09:34.233  1592  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 17:09:34.233  1592  1639 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 17:09:34.240  7890  7890 D UEI.SmartControl: QS Service version name: 2.1.91
,08-24 17:09:34.240  7890  7890 D UEI.SmartControl: QS Service version code: 201091
08-24 17:09:34.242  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-24 17:09:34.243  1592  1639 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 17:09:34.243  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.244  2022  8377 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-24 17:09:34.246  1592  1592 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 17:09:34.246  1592  1592 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 17:09:34.252  1858  1858 D SplitUIManager: split_name #11 / not available #0
08-24 17:09:34.252  1858  1858 D SplitUIService: removed split : 
08-24 17:09:34.252  1038  1945 V SIM_STK : Menu title from STK is T-Mobile
08-24 17:09:34.253  1592  1639 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 17:09:34.253  1592  1639 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:34.254  1592  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 17:09:34.254  1592  1639 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-24 17:09:34.259  1592  1639 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 17:09:34.259  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.263  1592  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:34.263  1592  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 17:09:34.263  1592  1639 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 17:09:34.263  1592  1639 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 17:09:34.264  1592  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 17:09:34.264  1592  1639 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 17:09:34.267  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 17:09:34.267  2022  2022 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-24 17:09:34.267  7890  7890 D UEI.SmartControl: Service requested: Control
08-24 17:09:34.268  1592  1639 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 17:09:34.268  1592  1639 D KeyguardModel: createShortcutInfo...
,08-24 17:09:34.271  8245  8245 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 17:09:34.273  7890  8375 E UEI.SmartControl: Loading SETTINGS...
08-24 17:09:34.283  1805  1805 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-24 17:09:34.292  1592  1592 D KeyguardModel: handleShortcutListChanged...
08-24 17:09:34.292  1592  1592 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-24 17:09:34.295  1592  1639 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 17:09:34.295  1592  1639 D KeyguardModel: createShortcutInfo...
,08-24 17:09:34.303  2146  2146 I ConfigService: onCreate
08-24 17:09:34.303  7890  7890 D UEI.SmartControl: Request IControl service: devices are loaded...
08-24 17:09:34.313  1592  1639 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 17:09:34.313  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.317  1858  1858 D SplitUIManager: split_name #11 / not available #0
08-24 17:09:34.317  1858  1858 I SplitUIService: split app #11
,08-24 17:09:34.317  1592  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 17:09:34.317  1592  1639 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-24 17:09:34.319  2146  2146 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 17:09:34.319  2146  2146 I ConfigService: onBind returning update interface
08-24 17:09:34.324  1038  1379 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:34.324  1038  1379 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:34.325  1038  1379 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:34.325  1038  1379 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:34.325  1038  1379 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:34.326  1038  1379 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-24 17:09:34.326  1592  1639 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 17:09:34.326  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.326  1038  1433 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-24 17:09:34.326  1038  1433 D ConnectivityService: identical MTU - not setting
08-24 17:09:34.326  1038  1433 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-24 17:09:34.327  1038  1433 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 17:09:34.327  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:09:34.327  1038  1433 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:34.327  1038  1433 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-24 17:09:34.328  1805  1805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 17:09:34.328  1592  1819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-24 17:09:34.328  2146  2146 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 17:09:34.328  2146  2146 I ConfigService: onBind returning config service
08-24 17:09:34.328  7890  7890 D UEI.SmartControl: Internal service binding...
08-24 17:09:34.329  1592  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 17:09:34.329  1592  1639 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-24 17:09:34.331  1592  1639 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 17:09:34.331  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.334  8305  8305 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-24 17:09:34.337  1038  1100 W InputMethodInfo: Duplicated subtype definition found: , voice
08-24 17:09:34.343  7890  7905 I UEI.SmartControl: ------ IControl API: 11
08-24 17:09:34.343  7890  7905 D UEI.SmartControl: File observer start...
,08-24 17:09:34.343  7890  7905 E UEI.SmartControl: IR Port is disabled: false
08-24 17:09:34.344  7890  7905 D UEI.SmartControl: Starting file observer...
08-24 17:09:34.344  7890  8375 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-24 17:09:34.344  7890  7905 I UEI.SmartControl: Registering callback...
08-24 17:09:34.345  7890  7907 I UEI.SmartControl: ------ IControl API: 19
08-24 17:09:34.346  7890  7907 I UEI.SmartControl: Registering Services Ready callback...
08-24 17:09:34.348  1805  1805 I ConfigFetchService: service connected
08-24 17:09:34.350  1038  1038 I art     : Explicit concurrent mark sweep GC freed 82548(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.925ms total 252.060ms
08-24 17:09:34.350  2022  2022 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-24 17:09:34.351  1038  1126 I art     : WaitForGcToComplete blocked for 238.789ms for cause Explicit
08-24 17:09:34.363  7890  8374 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-24 17:09:34.363  7890  8374 D UEI.SmartControl: -----service ready thread exits
08-24 17:09:34.364  8305  8323 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-24 17:09:34.365  8305  8357 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-24 17:09:34.366  8305  8357 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-24 17:09:34.366  8305  8305 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-24 17:09:34.366  8305  8305 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-24 17:09:34.366  7890  7905 I UEI.SmartControl: ------ IControl API: 8
08-24 17:09:34.367  1592  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 17:09:34.367  1592  1639 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 17:09:34.369  1592  1639 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 17:09:34.369  1592  1639 D KeyguardModel: createShortcutInfo...
08-24 17:09:34.371  8305  8305 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-24 17:09:34.371  8305  8305 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-24 17:09:34.371  8305  8305 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-24 17:09:34.371  2146  2146 I ConfigService: onDestroy
08-24 17:09:34.371  8305  8305 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-24 17:09:34.372  8305  8305 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-24 17:09:34.372  8305  8305 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-24 17:09:34.373  8305  8305 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-24 17:09:34.375  1592  1592 D KeyguardModel: handleShortcutListChanged...
08-24 17:09:34.375  1592  1592 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-24 17:09:34.379  1805  8381 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 17:09:34.387  8305  8305 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-24 17:09:34.399  1038  1053 V SIM_STK : Menu title from STK is T-Mobile
08-24 17:09:34.399  1038  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-24 17:09:34.408  5846  8386 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-24 17:09:34.430  1805  8387 W GmsApplication: Using Auth Proxy for data requests.
,08-24 17:09:34.434  1805  8387 W GmsApplication: Using Auth Proxy for data requests.
08-24 17:09:34.447  1805  8388 I PeopleContactsSync: CP2 sync disabled
,08-24 17:09:34.455  1038  1563 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 17:09:34.456  1805  5187 I Icing   : doRemovePackageData com.test.thalitest
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 17:09:34.456  7789  7789 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 17:09:34.475  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-24 17:09:34.478  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:34.479  1038  1038 D administrator: Handling package changes for user 0
,08-24 17:09:34.480  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-24 17:09:34.481  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-24 17:09:34.482  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-24 17:09:34.483  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-24 17:09:34.484  7173  7173 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-24 17:09:34.498  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-24 17:09:34.499  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:34.501  2022  2202 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-24 17:09:34.501  2022  2202 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-24 17:09:34.505   325   425 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-24 17:09:34.506  3237  8391 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-24 17:09:34.513  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c85ae5e u0 com.lge.launcher2/.Launcher t5} time:211103
08-24 17:09:34.513  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-24 17:09:34.514  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 17:09:34.514  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:34.516  1038  2021 I ActivityManager: Killing 7389:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-24 17:09:34.522  2022  2022 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-24 17:09:34.529  1038  1126 I art     : Explicit concurrent mark sweep GC freed 7294(380KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.222ms total 178.373ms
08-24 17:09:34.531  1038  1726 I art     : WaitForGcToComplete blocked for 157.866ms for cause Explicit
08-24 17:09:34.570  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-24 17:09:34.570  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 17:09:34.570  1038  1038 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 17:09:34.582  1038  1964 W libprocessgroup: failed to open /acct/uid_10005/pid_7389/cgroup.procs: No such file or directory
08-24 17:09:34.585  1038  1565 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-24 17:09:34.585  2022  2022 D [Concierge]WidgetView: change position of spinner
08-24 17:09:34.586  2597  2597 D [Concierge]Service: onStartCommand(). Type : 8
08-24 17:09:34.586  2597  2597 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-24 17:09:34.586  2022  2022 I [Concierge]WidgetView: initWebView(). Time : 1472051374586
08-24 17:09:34.587  2597  2597 D [Concierge]Service: Update widget ID : 11
08-24 17:09:34.588  2597  2597 D [Concierge]Service: onStartCommand(). Type : 0
,08-24 17:09:34.593  2385  8394 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 17:09:34.600  2146  2303 I art     : Explicit concurrent mark sweep GC freed 6274(373KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.378ms total 16.680ms
08-24 17:09:34.602  8346  8346 D AndroidRuntime: Shutting down VM
,08-24 17:09:34.618  1038  1726 I art     : Explicit concurrent mark sweep GC freed 4566(268KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.734ms total 85.668ms
,08-24 17:09:34.626  1038  2021 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8395 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-24 17:09:34.635   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.734ms
,08-24 17:09:34.644   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.990ms
08-24 17:09:34.654   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.008ms
,08-24 17:09:34.663  1038  1762 V SIM_STK : Menu title from STK is T-Mobile
08-24 17:09:34.684  1038  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8412 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 17:09:34.685  2022  2022 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 848079498
08-24 17:09:34.686  2022  2022 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-24 17:09:34.686  2022  2022 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 17:09:34.688  2022  2022 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@29f8455f
08-24 17:09:34.688  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-24 17:09:34.690  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 17:09:34.690  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:34.695  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-24 17:09:34.696  2022  2022 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-24 17:09:34.696  2022  2022 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-24 17:09:34.697  2022  2022 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472051191353, New one : 1472051374586
08-24 17:09:34.697  2022  2022 D [Concierge]WidgetView: Unregister all receivers
08-24 17:09:34.697  2022  2022 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 17:09:34.698  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:34.701  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-24 17:09:34.702  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-24 17:09:34.703  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-24 17:09:34.704  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-24 17:09:34.705  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-24 17:09:34.708  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:34.709  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 17:09:34.753  2022  2022 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-24 17:09:34.761  2022  2022 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-24 17:09:34.761  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-24 17:09:34.763  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 17:09:34.773  1038  1983 I ActivityManager: Killing 7818:com.google.android.talk/u0a72 (adj 15): empty #17
08-24 17:09:34.779  8395  8395 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:34.780  8395  8395 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 17:09:34.780  8395  8395 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 17:09:34.781  8395  8395 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 17:09:34.783  2022  2022 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26b3b387 time:211372
,08-24 17:09:34.786  1038  1100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:09:34.797  1038  1100 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-24 17:09:34.871  1038  1762 W libprocessgroup: failed to open /acct/uid_10072/pid_7818/cgroup.procs: No such file or directory
,08-24 17:09:34.875  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 17:09:34.879  8395  8395 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-24 17:09:34.887  8395  8395 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-24 17:09:34.912  8395  8395 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 17:09:34.927  2022  2022 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-24 17:09:34.932  8395  8395 D LgDataFeature: LgDataFeature() Constructor: none
08-24 17:09:34.932  8395  8395 D LgDataFeature: LgDataFeature() Constructor Done, null
08-24 17:09:34.965  2022  2873 I GBoardtInterface: onReloaded()
,08-24 17:09:34.967  2022  2022 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-24 17:09:34.968  3760  3776 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 17:09:34.971  3760  4932 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 17:09:34.979  1892  1892 D ActionManagerService: notifyUserLog: 1000001
,08-24 17:09:34.980  3760  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 17:09:34.980  3760  4936 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 17:09:34.982  1892  1892 D ActionManagerService: notifyUserLog: 1000001
08-24 17:09:34.984  3760  3776 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 17:09:34.984  3760  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 17:09:34.984  3760  4936 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 17:09:34.984  3760  4936 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-24 17:09:34.984  3760  4936 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-24 17:09:34.986  2022  2022 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-24 17:09:34.986  2022  2022 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-24 17:09:34.987  8395  8395 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-24 17:09:34.988  2022  2022 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-24 17:09:34.988  2022  2022 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 17:09:34.989  2022  2022 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-24 17:09:34.989  2022  2022 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 17:09:34.991  7915  7915 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
08-24 17:09:34.992  1038  1983 I ActivityManager: Killing 7936:com.android.vending/u0a44 (adj 15): empty #17

```
