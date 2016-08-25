#### Test 82728424d2195a9_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 20:54:00.113  1593  1593 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 20:54:07.431  6839  6839 D AndroidRuntime: 
08-25 20:54:07.431  6839  6839 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 20:54:07.434  6839  6839 D AndroidRuntime: CheckJNI is OFF
08-25 20:54:07.560  6839  6839 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 20:54:07.565  1027  2004 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 20:54:07.574  1933  1948 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 20:54:07.577  1027  2004 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 20:54:07.578  1027  2004 D ActivityManager: setTaskToReturnTo : TaskRecord{36a1106 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 20:54:07.578  1027  2004 D ActivityManager: setTaskToReturnTo : TaskRecord{36a1106 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 20:54:07.579  1027  2004 D WindowStateEx: AppWindowTokenEx init.. 
08-25 20:54:07.580   335   353 E GBMv2   : DFP En is all cleared set to be enabled
08-25 20:54:07.599  1027  2004 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6854 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 20:54:07.600  6839  6839 D AndroidRuntime: Shutting down VM
08-25 20:54:07.663  1933  4487 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 20:54:07.663  1933  4487 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c4fb035 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 20:54:07.665  1933  1949 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 20:54:07.666  1933  1949 D SplitWindowPolicy: topRunningActivity=ActivityInfo{339c5cca co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 20:54:07.729  6854  6854 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-25 20:54:07.796  6854  6854 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 20:54:07.804  6854  6854 I LibraryLoader: Loading: webviewchromium
08-25 20:54:07.806  6854  6854 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6093-6096)
08-25 20:54:07.806  6854  6854 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 20:54:07.840  6854  6854 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1548ccab}
,08-25 20:54:07.842  6854  6854 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 20:54:07.842  6854  6854 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 20:54:07.851  6854  6854 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 20:54:07.852  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 20:54:07.866  6854  6854 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 20:54:07.867  6854  6854 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-25 20:54:07.867  6854  6854 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-25 20:54:07.872   316  2159 V AudioPolicyService: registerClient() client 0xb0010360, uid 10118
08-25 20:54:07.879  1027  1115 D BluetoothManagerService: Message: 20
08-25 20:54:07.879  1027  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@333ab560:true
,08-25 20:54:07.904  6854  6854 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 20:54:07.904  6854  6854 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 20:54:07.904  6854  6854 I Adreno-EGL: Build Date: 12/12/14 금
08-25 20:54:07.904  6854  6854 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 20:54:07.904  6854  6854 I Adreno-EGL: Remote Branch: 
08-25 20:54:07.904  6854  6854 I Adreno-EGL: Local Patches: 
08-25 20:54:07.904  6854  6854 I Adreno-EGL: Reconstruct Branch: 
,08-25 20:54:08.000  6854  6900 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 20:54:08.002  6854  6854 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 20:54:08.023  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 20:54:08.029  6854  6854 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 20:54:08.033  6854  6854 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-25 20:54:08.036  6854  6854 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 20:54:08.036  6854  6854 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-25 20:54:08.054  6854  6854 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 20:54:08.063  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 20:54:08.063  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 20:54:08.102  6854  6915 D OpenGLRenderer: Render dirty regions requested: true
08-25 20:54:08.103  6854  6915 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 20:54:08.107  6854  6915 D OpenGLRenderer: Enabling debug mode 0
,08-25 20:54:08.135  6854  6854 D Atlas   : Validating map...
,08-25 20:54:08.141  1027  1042 D SplitWindow: check instance of lgWin Window{a851e9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 20:54:08.196  6854  6913 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:08.196  6854  6913 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 20:54:08.300  1027  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +639ms (total +720ms)
08-25 20:54:08.302  1027  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35fd43c7 u0 com.test.thalitest/.MainActivity t6} time:176591
08-25 20:54:08.302  6854  6854 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2fb59776 time:176592
08-25 20:54:08.434  6854  6854 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 20:54:08.434  6854  6854 I chromium: 
,08-25 20:54:08.479  6854  6854 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 20:54:08.570  6854  6913 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 20:54:08.570  6854  6913 I chromium: 
,08-25 20:54:08.712  6854  6929 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435147776
,08-25 20:54:08.721   335   355 E GBMv2   : DFP En is all cleared set to be enabled
08-25 20:54:08.721   335   355 E GBMv2   : Set value is all cleared set the max
08-25 20:54:08.721   335   355 I GBMv2   : DFP Enabled. Ignore VFP set
08-25 20:54:08.729  6854  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 20:54:08.729  6854  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 20:54:08.729  6854  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 20:54:08.729  6854  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 20:54:08.729  6854  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 20:54:08.729  6854  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3456e25a added. We now have 1 listener(s)
08-25 20:54:08.743  1027  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 20:54:08.751  6854  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-25 20:54:08.753  6854  6929 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:08.754  6854  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:08.754  6854  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 20:54:08.763  6854  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c9e4981 added. We now have 1 listener(s)
08-25 20:54:08.763  6854  6929 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:08.768  1027  1533 D WifiService: New client listening to asynchronous messages
08-25 20:54:08.772  6854  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:54:08.772  6854  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 20:54:08.774  6854  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 20:54:08.774  6854  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 20:54:08.774  6854  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 20:54:08.778  6854  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:08.782  1027  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:08.783  6854  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-25 20:54:08.795  6854  6929 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:08.795  6854  6929 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:08.795  6854  6929 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 20:54:08.795  6854  6929 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 20:54:08.799  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:08.802  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:08.802  6854  6929 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 20:54:08.840  6854  6854 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 20:54:09.693  6854  6932 W jxcore-log: Initializing JXcore engine
08-25 20:54:09.693  6854  6932 W jxcore-log: JXcore engine is ready
,08-25 20:54:09.729  6932  6932 W Thread-797: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7532]" dev="sockfs" ino=7532 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 20:54:09.729  6932  6932 W Thread-797: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-25 20:54:09.729  6932  6932 W Thread-797: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9986]" dev="sockfs" ino=9986 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 20:54:09.729  6932  6932 W Thread-797: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 20:54:09.729  6932  6932 W Thread-797: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30574]" dev="sockfs" ino=30574 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 20:54:09.743  6854  6932 W jxcore-log: Starting JXcore engine
,08-25 20:54:09.822  6854  6932 W jxcore-log: Platform android
08-25 20:54:09.822  6854  6932 W jxcore-log: 
08-25 20:54:09.822  6854  6932 W jxcore-log: Process ARCH arm
08-25 20:54:09.822  6854  6932 W jxcore-log: 
,08-25 20:54:10.014  6854  6932 I jxcore-log: JXcore Cordova bridge is ready!
08-25 20:54:10.014  6854  6932 I jxcore-log: 
08-25 20:54:10.014  6854  6932 W jxcore-log: JXcore engine is started
,08-25 20:54:10.027  6854  6929 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 20:54:10.031  6854  6854 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 20:54:19.534  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 20:54:19.534  6854  6932 I jxcore-log: 
,08-25 20:54:19.536  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 20:54:19.536  6854  6932 I jxcore-log: 
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:19.544  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:19.547  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 20:54:19.550  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 20:54:19.550  6854  6932 I jxcore-log: 
08-25 20:54:19.553  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 20:54:19.553  6854  6932 I jxcore-log: 
08-25 20:54:20.044  6854  6932 D executeNativeTests: Running unit tests
,08-25 20:54:20.112  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:20.112  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa added. We now have 2 listener(s)
,08-25 20:54:20.113  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:20.116  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:20.116  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:20.116  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:20.116  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:20.117  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b added. We now have 2 listener(s)
08-25 20:54:20.117  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:20.117  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:54:20.120  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:20.123  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:54:20.125  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.125  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:20.127  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.128  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.129  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 20:54:20.131  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 20:54:20.131  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 20:54:20.132  6854  6932 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 20:54:20.133  6854  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 20:54:20.133  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 20:54:20.133  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 20:54:20.133  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 20:54:20.133  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.134  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.134  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.134  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.134  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.134  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:20.135  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:20.135  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa removed from the list
08-25 20:54:20.135  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.135  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b removed from the list
08-25 20:54:20.135  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.135  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:54:20.137  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.137  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.139  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.139  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.139  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.139  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.141  6854  6932 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 20:54:20.141  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.141  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.141  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.141  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.141  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.141  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.141  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.141  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.141  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.142  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.142  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.142  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.142  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:54:20.142  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.142  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.142  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.142  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.142  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
,08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
,08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 20:54:20.146  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
08-25 20:54:20.147  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.147  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-25 20:54:20.147  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.147  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.147  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.147  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:54:20.147  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.147  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.147  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.147  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.148  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 20:54:20.148  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.148  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.148  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.150  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.150  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.150  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.150  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.151  6854  6932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 20:54:20.152  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:20.154  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.154  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.155  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:20.156  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.156  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.157  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:20.157  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:54:20.157  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:54:20.157  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.157  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 20:54:20.160  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 20:54:20.160  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:20.164  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 20:54:20.167  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 20:54:20.169  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 20:54:20.169  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:54:20.169  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:20.170  6854  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 20:54:20.171  6854  6932 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 20:54:20.173  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.173  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.173  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.174  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.174  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.174  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:20.174  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.174  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.174  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.174  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.174  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.174  6854  6932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 20:54:20.176  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:20.177  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.178  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.178  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:20.179  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.180  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:20.180  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:54:20.180  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:54:20.180  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.180  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 20:54:20.181  6854  6854 V io.j,xcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.183  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:54:20.183  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:20.184  6854  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 20:54:20.184  6854  6932 I io.jxcore.node.ConnectionHelper: start: OK
08-25 20:54:20.185  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.185  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.185  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.186  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.186  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.186  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:20.186  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.186  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.186  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.186  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.186  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.186  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.186  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.187  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.187  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.188  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.188  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.188  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.188  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.188  6854  6932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 20:54:20.189  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:20.191  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.192  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.192  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:20.193  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.194  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.195  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:20.195  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:54:20.195  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:54:20.195  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.195  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 20:54:20.198  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:54:20.199  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:20.200  6854  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 20:54:20.200  6854  6932 I io.jxcore.node.ConnectionHelper: start: OK
08-25 20:54:20.200  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.200  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.200  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.201  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.201  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.201  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.201  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.201  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.201  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:20.201  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.201  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.201  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.201  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.201  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.201  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.201  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.202  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.202  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.202  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.202  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.202  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.202  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.203  6854  6932 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 20:54:20.203  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.203  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.203  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.203  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.203  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.203  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.203  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.203  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.203  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.203  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.203  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.203  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.204  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.204  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.204  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.204  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.205  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.205  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.205  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.205  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.205  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 20:54:20.206  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.206  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.206  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.206  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.206  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.206  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.206  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.206  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.206  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.206  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.206  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.206  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.206  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.206  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.213  1593  1593 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-25 20:54:20.213  1593  1593 I [SystemUI]LGPowerUI: On Skip Timer : true
08-25 20:54:20.213  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.213  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.214  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.214  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.214  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.214  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.215  6854  6932 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 20:54:20.219  1593  1593 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
08-25 20:54:20.219  1593  1593 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-25 20:54:20.220  5616  5616 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 20:54:20.221  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.221  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.221  1027  1533 D WifiController: battery changed pluggedType: 2
08-25 20:54:20.222  4317  4456 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 20:54:20.223  1593  1593 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-25 20:54:20.223  1933  2092 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-25 20:54:20.224  1933  2092 D LEDHandler: Battery Level Remaining: 100%
08-25 20:54:20.224  1933  2092 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
08-25 20:54:20.225  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.225  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.225  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.225  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.225  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.225  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.225  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.225  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.225  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.225  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.225  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.225  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.225  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.225  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.226  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.226  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.226  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.226  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.226  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.226  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.227  6854  6932 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 20:54:20.227  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.227  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.227  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.227  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.227  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.227  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.228  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.228  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.228  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.228  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.228  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.228  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.228  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.228  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.228  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.228  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.229  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.229  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.229  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.229  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.229  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 20:54:20.229  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 20:54:20.229  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 20:54:20.230  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 20:54:20.230  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 20:54:20.230  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 20:54:20.230  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.230  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.230  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.230  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.230  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.230  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.230  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.230  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.230  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.230  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.230  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.230  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.230  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.230  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.233  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.233  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.234  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.234  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.234  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.234  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.234  6854  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:54:20.234  6854  6932 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 20:54:20.234  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 20:54:20.236  6854  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:54:20.236  6854  6932 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 20:54:20.236  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 20:54:20.237  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 20:54:20.237  6854  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 20:54:20.237  6854  6932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 20:54:20.237  6854  6932 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 20:54:20.237  6854  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:54:20.237  6854  6932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 20:54:20.237  6854  6932 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 20:54:20.237  6854  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:54:20.237  6854  6932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 20:54:20.237  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 20:54:20.239  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 20:54:20.240  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 20:54:20.240  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 20:54:20.240  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 20:54:20.240  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 20:54:20.240  6854  6932 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 20:54:20.240  6854  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 20:54:20.240  6854  6932 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 20:54:20.241  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.241  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.241  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.241  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.241  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.241  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.241  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 20:54:20.241  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.241  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.241  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.241  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.241  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.241  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.241  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.241  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.242  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.242  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.242  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.242  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.242  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.242  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.243  6854  6932 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 20:54:20.243  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.243  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.243  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.246  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.246  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.246  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.246  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.246  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.246  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.246  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.247  6854  6942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 861)
08-25 20:54:20.247  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.247  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.247  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.247  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.248  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.248  6854  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 861
08-25 20:54:20.248  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.248  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.248  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.249  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.249  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.249  6854  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 20:54:20.249  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.250  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.250  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.250  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.250  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.250  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.250  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.250  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.250  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.250  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.250  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.250  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.250  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.250  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.251  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.251  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.252  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.252  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.252  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.252  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.252  6854  6932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 20:54:20.252  6854  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 20:54:20.252  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 20:54:20.252  6854  6932 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 20:54:20.253  6854  6932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 20:54:20.253  6854  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 20:54:20.253  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 20:54:20.253  6854  6932 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 20:54:20.253  6854  6932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 20:54:20.253  6854  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 20:54:20.253  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 20:54:20.253  6854  6932 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 20:54:20.253  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.253  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.253  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.253  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.253  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.254  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.254  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.254  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.254  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.254  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.254  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.254  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.254  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.254  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.255  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.255  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 20:54:20.258  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.258  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.258  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.258  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.258  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.258  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.258  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.258  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.259  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.259  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.259  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.259  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.259  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.259  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.259  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.259  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.259  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.259  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.259  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.259  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.259  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.259  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.260  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.260  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.260  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.260  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.260  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.260  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.260  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.260  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.260  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.260  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.260  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.261  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.261  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.261  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.261  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.261  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.261  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.271  6854  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 20:54:20.271  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.272  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 20:54:20.272  6854  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 20:54:20.273  6854  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 20:54:20.273  6854  6854 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 20:54:20.273  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 20:54:20.273  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 20:54:20.275  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.275  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 20:54:20.276  1027  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:20.277  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 20:54:20.277  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 20:54:20.277  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.277  6854  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 20:54:20.277  6854  6854 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 20:54:20.277  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.277  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.277  6854  6944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:20.277  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 20:54:20.277  6854  6932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 20:54:20.278  4317  4340 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-25 20:54:20.278  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 20:54:20.279  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 20:54:20.279  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:20.279  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:20.279  6854  6932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 20:54:20.279  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.280  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.280  6854  6944 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 20:54:20.281  6854  6944 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 20:54:20.281  6854  6932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:54:20.281  6854  6944 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 20:54:20.281  6854  6854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:54:20.281  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.281  6854  6854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 20:54:20.281  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.281  6854  6854 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 20:54:20.281  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.281  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.281  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.281  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.281  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.281  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.281  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.281  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.281  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.282  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.282  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.282  6854  6854 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 20:54:20.282  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.282  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.283  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.283  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.283  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.283  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.284  6854  6932 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 20:54:20.284  6854  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 20:54:20.284  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 20:54:20.286  6854  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 20:54:20.286  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.286  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.286  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.287  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.287  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.287  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.287  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.287  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.287  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.287  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.287  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.287  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.287  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.287  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.290  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.290  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.290  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.290  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.291  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:20.291  1027  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:20.292  1027  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:20.293  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.293  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.293  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.293  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.293  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.293  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.293  6854  6932 E org.thaliproject.p2p.btconnectorlib.C,onnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.293  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.293  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.293  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.293  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.293  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.293  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.293  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.294  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.294  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.294  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.294  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.294  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:20.294  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:20.294  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:20.295  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:20.295  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.295  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.295  6854  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28056eaa not in the list
08-25 20:54:20.295  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.295  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.295  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:20.295  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.295  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.295  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:20.295  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:20.295  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:20.295  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:20.295  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:20.295  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33841a9b not in the list
08-25 20:54:20.296  6854  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 20:54:20.296  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 20:54:20.297  6854  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 20:54:20.297  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 20:54:20.297  6854  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 20:54:20.297  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
,08-25 20:54:20.298  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 20:54:20.298  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 20:54:20.299  6854  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-25 20:54:20.299  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 20:54:20.299  6854  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 20:54:20.299  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-25 20:54:20.299  6854  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 20:54:20.299  6854  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 20:54:20.300  6854  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 20:54:20.300  6854  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed,
08-25 20:54:20.300  6854  6932 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 20:54:20.300  6854  6932 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 20:54:20.300  6854  6932 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-25 20:54:20.300  6854  6932 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 20:54:20.301  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:20.301  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1afd1c50 added. We now have 2 listener(s)
,08-25 20:54:20.301  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:20.302  6854  6932 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 20:54:20.303  1027  1968 D WifiServiceImplEx: setWifiEnabled: true pid=6854, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-25 20:54:20.303  1027  1968 D WifiService: setWifiEnabled: true pid=6854, uid=10118
08-25 20:54:20.303  1027  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 20:54:20.304  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:20.304  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12459e49 added. We now have 3 listener(s)
08-25 20:54:20.304  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:54:20.308  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:20.309  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3354d34e added. We now have 4 listener(s)
08-25 20:54:20.309  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:20.310  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:20.310  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fd3ec6f added. We now have 5 listener(s)
08-25 20:54:20.310  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:20.312  1027  1968 D WifiServiceImplEx: setWifiEnabled: false pid=6854, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 20:54:20.312  1027  1968 D WifiService: setWifiEnabled: false pid=6854, uid=10118
08-25 20:54:20.312  1027  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 20:54:20.321  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 20:54:20.321  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:20.321  1027  1027 D Ulp_jni : JNI:system_update. Event-4
,08-25 20:54:20.322  1027  1477 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:20.322  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:20.323  1027  1477 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:20.323  1027  1477 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:20.323  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:20.323  1027  1477 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 20:54:20.323  1027  1477 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 20:54:20.323  1027  1477 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 20:54:20.324  1027  1567 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:20.324  1027  1567 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@31cc9c25 mBinding = false
08-25 20:54:20.324  1027  1477 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 20:54:20.324  1027  1477 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 20:54:20.331  6854  6942 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-25 20:54:20.331  6854  6942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:20.332  4317  4337 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:20.332  4317  4538 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,08-25 20:54:20.335  1027  1477 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 20:54:20.335  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 20:54:20.335  2681  2681 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 20:54:20.335  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.335  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.335  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 20:54:20.336  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:20.336  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:20.336  1027  2811 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.336   312   885 D CommandListener: Clearing all IP addresses on wlan0
08-25 20:54:20.343  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 20:54:20.344  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:20.344  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 20:54:20.344  1027  1115 D BluetoothManagerService: Message: 2
,08-25 20:54:20.345  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:20.346  1027  1115 D BluetoothManagerService: Sending off request.
08-25 20:54:20.346  4317  4337 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 20:54:20.347  4317  4401 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 20:54:20.347  4317  4401 D BluetoothAdapterProperties: Setting state to 13
08-25 20:54:20.347  4317  4401 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 20:54:20.348  4317  4401 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 20:54:20.348  4317  4401 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:20.348  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.348  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.348  4317  4404 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:54:20.348  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.349  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:20.349  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:20.349  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 20:54:20.349  4317  4401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 20:54:20.349  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 20:54:20.349  4317  4401 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 20:54:20.350  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 20:54:20.350  4317  4686 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:20.350  4317  4538 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 20:54:20.350  4317  4685 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 20:54:20.350  4317  4685 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:20.350  4317  4685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 20:54:20.350  4317  4685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 20:54:20.350  4317  4685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 20:54:20.350  4317  4685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 20:54:20.350  4317  4685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 20:54,:20.350  4317  4685 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 20:54:20.351  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:20.351  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.351  4317  4717 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:20.351  4317  4732 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:20.351  4317  4728 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:20.352  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.352  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.353  6854  6942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 861)
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 20:54:20.353  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 20:54:20.354  4317  4538 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 20:54:20.355  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:20.359  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:20.359  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.359  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.359  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:20.361  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:20.367  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 20:54:20.368  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-25 20:54:20.377  1027  2024 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-25 20:54:20.380  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.380  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.380  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 20:54:20.380  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.380  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-25 20:54:20.387  1027  1105 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6954 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-25 20:54:20.390  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 20:54:20.390  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:20.390  4317  4317 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:20.390  4317  4317 D BluetoothMapService: STATE_TURNING_OFF
08-25 20:54:20.390  4317  4317 V BluetoothMapService: Handler(): got msg=4
08-25 20:54:20.390  4317  4317 D BluetoothMapService: MAP Service closeService in
08-25 20:54:20.390  4317  4317 D BluetoothMapMasInstance: MAP Service shutdown
08-25 20:54:20.391  4317  4317 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 20:54:20.391  4317  4317 V BluetoothMapService: MAP Service closeService out
08-25 20:54:20.391  4317  4317 V BtOppService: Receiver DISABLED_ACTION 
08-25 20:54:20.391  4317  4317 I BtOppRfcommListener: stopping Accept Thread
08-25 20:54:20.391  4317  4317 V BtOppRfcommListener: close mBtServerSocket
08-25 20:54:20.391  4317  4317 V BtOppRfcommListener: waiting for thread to terminate
08-25 20:54:20.391  4317  4717 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 20:54:20.391  4317  4317 V BtOppRfcommListener: done waiting for thread to terminate
08-25 20:54:20.399  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:20.399  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:54:20.401  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.401  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:20.409  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:20.409  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.409  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.409  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:20.410  1027  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6972 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 20:54:20.411  1027  1027 D WifiHS20: hidePasspointNotification off =false
,08-25 20:54:20.416  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.416  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.416  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:20.418  1933  1933 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 20:54:20.418  4317  4317 V BtOppService: onDestroy
08-25 20:54:20.419  1027  1477 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.419  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.419  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.419  4317  4317 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 20:54:20.419  1027  1477 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.420  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.420  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.421  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 20:54:20.421  1027  1477 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 20:54:20.421  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.421  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.421  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:20.421  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 20:54:20.421  1027  1477 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.421  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-25 20:54:20.421  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.421  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:20.422  1027  1548 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.422  1027  1549 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 20:54:20.429  1027  1428 D LGWifiP2pService: InactiveState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.429  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.429  1027  1428 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@649b541
08-25 20:54:20.429  1027  1428 D LGWifiP2pService: P2pDisablingState
08-25 20:54:20.429  1027  1428 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.429  1027  1428 D LGWifiP2pService: p2p socket connection lost
08-25 20:54:20.430  1027  1428 D LGWifiP2pService: P2pDisabledState
08-25 20:54:20.430  1027  1477 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-25 20:54:20.431  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 20:54:20.431  2681  2681 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 20:54:20.431  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 20:54:20.431  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:20.431  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:20.431  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 20:54:20.432  1933  1933 D WfdsService: WifiP2pState is changed : false
08-25 20:54:20.432  1933  2293 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 20:54:20.432  1933  2293 D WfdsService: Set the WFDS Monitor: false
08-25 20:54:20.432   312   885 D CommandListener: Clearing all IP addresses on wlan0
08-25 20:54:20.432  1933  2293 D WfdsMonitor: WFDS Monitor is stopped
08-25 20:54:20.432  1933  2293 D WfdsService: STATE : WfdsDisabledState - enter
08-25 20:54:20.432  1933  2296 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 20:54:20.433  1027  1535 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 20:54:20.433  1027  1535 D DSQN    : disableDataServiceNotify
08-25 20:54:20.433  1027  1535 D DSQN    : stop dsqn bin
08-25 20:54:20.433  1027  1428 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.433  1027  1428 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.434  1933  2716 D CtrlSupplicant: Received on exit socket, terminate
08-25 20:54:20.434  1933  2716 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 20:54:20.434  1933  2716 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 20:54:20.435  1933  2293 W WfdsService: DefaultState - msg [9445378] is not handled
,08-25 20:54:20.435  1933  2716 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 20:54:20.436   312  6990 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 20:54:20.436  1027  1477 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 20:54:20.436  1027  1477 D WifiNative-p2p0: TERMINATE: returned true
08-25 20:54:20.436  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:20.436  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:20.436  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:20.436  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-25 20:54:20.437  1027  1112 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 20:54:20.437  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 20:54:20.437  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.437  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.437  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:20.437  1027  1535 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 20:54:20.438  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:20.438  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:20.438  1027  1535 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:20.438  1027  1535 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 20:54:20.438  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.439  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.439  1593  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 20:54:20.439  1027  2805 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 20:54:20.439  1027  1535 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 20:54:20.439  1027  1535 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 20:54:20.439  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 20:54:20.440  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-2,5 20:54:20.440  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:20.440  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 20:54:20.441  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 20:54:20.441  1027  1535 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:20.441  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 20:54:20.441  1027  1535 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:20.441  1027  1535 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:20.441  1027  1535 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:20.442  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.443  1027  1426 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 20:54:20.443  1845  1845 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:20.443  1845  1845 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 20:54:20.445  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 20:54:20.445  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 20:54:20.445  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:20.445  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.445  1027  1426 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 20:54:20.445  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 20:54:20.446  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 20:54:20.446  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 20:54:20.446  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 20:54:20.446  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 20:54:20.446  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 20:54:20.446  1,027  1535 D NetworkManagementService: Removing idletimer
08-25 20:54:20.446  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.446  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:20.446  1027  1535 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.447  1027  1535 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 20:54:20.451  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:20.451  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:20.452  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.452  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:20.458  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:20.458  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 20:54:20.458  1027  1477 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:20.458  1027  1477 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:20.465  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:20.465  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:20.470  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.471  6972  6972 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 20:54:20.472  6972  6972 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 20:54:20.472  6972  6972 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 20:54:20.472  6972  6972 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 20:54:20.473  6972  6972 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 20:54:20.473  6972  6972 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 20:54:20.478  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 20:54:20.478  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:20.478  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:20.480  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.493  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:20.494  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.494  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.502  6954  6954 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 20:54:20.502  6954  6954 W LG Account v2.2: No ProfileInfo entries
08-25 20:54:20.502  6954  6954 I LG Account v2.2: isEnabled: false
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Country: EU
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Operator: OPEN
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Ranking support: false
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Comfort support: false
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Accessory: true
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Health device: true
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Extra Pedometer: false
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Blood glucose device: false
08-25 20:54:20.502  6954  6954 I Feature : [Lifetracker]Device Number: 3
08-25 20:54:20.508  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:20.508  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:20.509  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.509  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.521  2681  2681 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 20:54:20.521  2681  2681 I wpa_supplicant: monitor socket send errors count : 1
08-25 20:54:20.521  2681  2681 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1933-2\x00 that cannot receive messages
08-25 20:54:20.522  1027  2714 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 20:54:20.522  1027  2714 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-25 20:54:20.538  1027  1969 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6995 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 20:54:20.539  1027  1969 I ActivityManager: Killing 6196:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-25 20:54:20.542  1027  2811 D DhcpStateMachine: StoppedState
08-25 20:54:20.542  1027  2811 D DhcpStateMachine: StoppedState{ when=-111ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:20.548  2681  2681 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 20:54:20.548  1027  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 20:54:20.548  1027  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 20:54:20.548  1027  2714 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 20:54:20.549  1027  2714 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 20:54:20.549  2681  2681 W wpa_supplicant: USIM:  scard_deinit function
08-25 20:54:20.549  1027  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:20.549  1027  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:20.550  1027  1477 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188830
08-25 20:54:20.550  1027  1477 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188831
08-25 20:54:20.550  1027  1477 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=188831  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-25 20:54:20.550  1027  1477 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=188831  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 20:54:20.551  1027  1115 D Tethering: InitialState.processMessage what=4
08-25 20:54:20.582  2681  2681 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 20:54:20.582  1027  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 20:54:20.582  1027  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 20:54:20.582  1027  2714 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-25 20:54:20.583  1027  1477 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-25 20:54:20.594  1027  1567 W libprocessgroup: failed to open /acct/uid_10014/pid_6196/cgroup.procs: No such file or directory
,08-25 20:54:20.600  1027  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 20:54:20.653  6972  6972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 20:54:20.657  4317  4317 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 20:54:20.657  4317  4317 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:20.657  4317  4317 V BluetoothPbapReceiver: ***********state = 13
08-25 20:54:20.660  4317  4317 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 20:54:20.662  1027  1115 D BluetoothManagerService: Message: 20
08-25 20:54:20.662  1027  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f56eb4:true
08-25 20:54:20.663  4317  4317 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:20.663  4317  4317 V BluetoothPbapService: state: 13
08-25 20:54:20.663  4317  4317 V BluetoothPbapService: Pbap Service closeService in
08-25 20:54:20.664  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:20.665  4317  4317 V BluetoothPbapService: successfully stopped pbap service
08-25 20:54:20.665  4317  4317 V BluetoothPbapService: Pbap Service closeService out
08-25 20:54:20.665  4317  4317 V BluetoothPbapService: Pbap Service onDestroy
08-25 20:54:20.665  4317  4317 V BluetoothPbapService: Pbap Service closeService in
08-25 20:54:20.665  4317  4317 V BluetoothPbapService: Pbap Service closeService out
08-25 20:54:20.666  4317  4317 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 20:54:20.671  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 20:54:20.675  1027  1115 D BluetoothManagerService: Message: 30
08-25 20:54:20.679  1027  1115 D BluetoothManagerService: Message: 30
,08-25 20:54:20.681  6972  6972 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 20:54:20.681  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 20:54:20.681  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:20.682  6972  6972 D BluetoothMap: Create BluetoothMap proxy object
08-25 20:54:20.682  1027  1115 D BluetoothManagerService: Message: 30
08-25 20:54:20.684  1027  1931 I ActivityManager: Killing 6430:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-25 20:54:20.751  1027  1477 D WifiOffDelayIfNotUsed: stopMonitoring
,08-25 20:54:20.751  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:20.751  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:20.751  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:20.754  1027  1932 W libprocessgroup: failed to open /acct/uid_10008/pid_6430/cgroup.procs: No such file or directory
08-25 20:54:20.764  1933  1933 D WfdsService: Supplicant Connection state is changed : false
,08-25 20:54:20.765  1933  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 20:54:20.765  1933  2293 D WfdsService: Set the WFDS Monitor: false
08-25 20:54:20.765  1933  2293 D WfdsMonitor: WFDS Monitor is stopped
08-25 20:54:20.765  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:20.766  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 20:54:20.770  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 20:54:20.771  1027  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 20:54:20.771  1027  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-25 20:54:20.774  2500  2500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:20.776  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:20.777  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:20.781  1027  1115 D BluetoothManagerService: Message: 30
08-25 20:54:20.783  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:20.783  6854  6854 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 20:54:20.786  6972  6972 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 20:54:20.788  6972  6972 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 20:54:20.805  6972  6972 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 20:54:20.809  6972  6972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 20:54:20.818  6972  6972 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:54:20.829  6972  6972 D BluetoothInputDevice: Proxy object connected
,08-25 20:54:20.830  6972  6972 D HidProfile: Bluetooth service connected
08-25 20:54:20.831  6972  6972 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 20:54:20.832  6972  6972 D PanProfile: Bluetooth service connected
08-25 20:54:20.845  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:20.901  6972  6972 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:20.901  6972  6972 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 20:54:20.922  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 20:54:20.923  6972  6972 D BluetoothMap: Proxy object connected
08-25 20:54:20.925  6972  6972 D MapProfile: Bluetooth service connected
08-25 20:54:20.925  6972  6972 D BluetoothMap: getConnectedDevices()
08-25 20:54:20.928  6972  6972 D BluetoothMap: Bluetooth is Not enabled
08-25 20:54:20.929  6972  6972 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 20:54:20.935  6972  6972 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 20:54:20.944  6972  6972 D BluetoothPermissionRequest: onReceive
,08-25 20:54:20.950  6972  6972 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 20:54:20.957  1027  1477 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,08-25 20:54:20.958  1027  1477 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 20:54:20.961  1027  1477 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:20.964  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:20.967  1027  2005 I ActivityManager: Killing 5979:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 20:54:20.973  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 20:54:21.013  1027  2043 W libprocessgroup: failed to open /acct/uid_10011/pid_5979/cgroup.procs: No such file or directory
08-25 20:54:21.013  4317  4317 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 20:54:21.013  4317  4317 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 20:54:21.015  4317  4317 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-25 20:54:21.096  1027  1042 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7026 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-25 20:54:21.097  4317  4317 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 20:54:21.097  4317  4317 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 20:54:21.107  4317  4317 V BluetoothFtpService: Ftp Service onStartCommand
08-25 20:54:21.107  4317  4317 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:21.108  4317  4317 V BluetoothFtpService: Ftp Service closeService
08-25 20:54:21.108  4317  4317 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 20:54:21.111  4317  4317 V BluetoothFtpService: successfully stopped ftp service
08-25 20:54:21.111  4317  4317 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:21.111  4317  4317 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:21.111  4317  4317 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:21.111  4317  4317 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:21.111  4317  4317 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 20:54:21.111  4317  4317 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 20:54:21.113  4317  4317 V BluetoothFtpService: Ftp Service onDestroy
08-25 20:54:21.113  4317  4317 V BluetoothFtpService: Ftp Service closeService
,08-25 20:54:21.117  4317  4317 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 20:54:21.117  4317  4317 V BluetoothSapService: state: 13
08-25 20:54:21.118  4317  4317 V BluetoothSapService: Stopping SAP server process
08-25 20:54:21.119  4317  4317 V BluetoothSapService: Sap Service closeSapService in
08-25 20:54:21.119  4317  4317 V BluetoothSapService: Close listen Socket : 
08-25 20:54:21.119  4317  4317 V BluetoothSapService: Close rfcomm Socket : 
08-25 20:54:21.119  4317  4317 V BluetoothSapService: Close sapd  Socket : 
08-25 20:54:21.181  1027  1969 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7043 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 20:54:21.194  4317  4317 V BluetoothSapService: Sap Service closeSapService out
08-25 20:54:21.194  4317  4317 V BluetoothSapService: Sap Service onDestroy
08-25 20:54:21.194  4317  4317 V BluetoothSapService: Sap Service closeSapService in
08-25 20:54:21.194  4317  4317 V BluetoothSapService: Close listen Socket : 
08-25 20:54:21.195  4317  4317 V BluetoothSapService: Close rfcomm Socket : 
08-25 20:54:21.195  4317  4317 V BluetoothSapService: Close sapd  Socket : 
08-25 20:54:21.196  4317  4317 V BluetoothSapService: Sap Service closeSapService out
08-25 20:54:21.219  7026  7026 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 20:54:21.241  7043  7043 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 20:54:21.253  7026  7026 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 20:54:21.258  1027  1567 I ActivityManager: Killing 6000:com.android.contacts/u0a19 (adj 15): empty #17
08-25 20:54:21.291  1027  1896 W libprocessgroup: failed to open /acct/uid_10019/pid_6000/cgroup.procs: No such file or directory
,08-25 20:54:21.328  7026  7026 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-25 20:54:21.328  7026  7026 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 20:54:21.329  7026  7026 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 20:54:21.329  7026  7026 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 20:54:21.329  7026  7026 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 20:54:21.332  7026  7026 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 20:54:21.338  7026  7026 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 20:54:21.346  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:21.352  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:21.362  4317  4404 D bt_hci_bdroid: cleanup
08-25 20:54:21.363  4317  4540 I bt_lpm  : LPM is already off!!!
08-25 20:54:21.363  4317  4661 I bt_userial_mct: exiting userial_read_thread
08-25 20:54:21.363  4317  4661 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 20:54:21.364  4317  4404 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 20:54:21.364  4317  4540 I bt_vendor: hw_epilog_process
08-25 20:54:21.365  4317  4404 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 20:54:21.365  4317  4404 D bt_userial_mct: userial_close
08-25 20:54:21.365  4317  4404 E bt_userial_mct: pthread_join() FAILED result:3
08-25 20:54:21.365  4317  4404 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 20:54:21.365  4317  4538 W bt-btif : ag scb idx 1 not allocated
08-25 20:54:21.365  4317  4538 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 20:54:21.365  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:21.365  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:21.365  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:21.366  4317  4538 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 20:54:21.366  4317  4538 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 20:54:21.368  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:21.371  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:21.375  7026  7026 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 20:54:21.379  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 20:54:21.379  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 20:54:21.380  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:21.387  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:21.390  7026  7026 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 20:54:21.396  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:21.407  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:21.407  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:21.409  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 20:54:21.412  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:21.418  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 20:54:21.418  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-25 20:54:21.418  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:21.423  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:21.431  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:21.443  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:21.444  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:21.446  4317  4404 D bt_hci_bdroid: set_power 0
08-25 20:54:21.446  4317  4404 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 20:54:21.446  4317  4404 I bt_vendor: bluetooth satus is on
08-25 20:54:21.446  4317  4404 I bt_vendor: bt-vendor : resetting BT status
08-25 20:54:21.446  4317  4404 I bt_vendor: Starting hciattach daemon
08-25 20:54:21.446  4317  4404 I bt_vendor: try to set false
08-25 20:54:21.446  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:21.447  4317  4404 I bt_vendor: Starting hciattach daemon
08-25 20:54:21.447  4317  4404 I bt_vendor: try to set false
08-25 20:54:21.448  4317  4404 I bt_vendor: cleanup
08-25 20:54:21.449  4317  4538 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 20:54:21.449  4317  4404 I GKI_LINUX: GKI_exit_task 0 done
08-25 20:54:21.449  4317  4404 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 20:54:21.453  4317  4401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 20:54:21.510  1027  1968 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7064 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 20:54:21.518  4317  4317 D HeadsetService: Received stop request...Stopping profile...
08-25 20:54:21.519  4317  4317 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 20:54:21.519  4317  4317 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:54:21.519  4317  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359d6f08
08-25 20:54:21.520  4317  4456 D HeadsetStateMachine: Exit Disconnected: -1
08-25 20:54:21.520  1845  1845 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:21.521  1845  1845 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:21.521  1845  1845 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:21.521  4317  4401 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 20:54:21.521  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:21.522  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 20:54:21.522  4317  4317 D A2dpService: Received stop request...Stopping profile...
08-25 20:54:21.523  4317  4501 D A2dpStateMachine: Exit Disconnected: -1
08-25 20:54:21.523  4317  4317 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-25 20:54:21.527  4317  4317 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 20:54:21.527  4317  4317 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:54:21.527  4317  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359d6f08
08-25 20:54:21.528  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-25 20:54:21.528  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 20:54:21.529  4317  4317 D HidService: Received stop request...Stopping profile...
08-25 20:54:21.529  4317  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359d6f08
08-25 20:54:21.530  4317  4317 D HealthService: Received stop request...Stopping profile...
08-25 20:54:21.531  4317  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359d6f08
08-25 20:54:21.531  6972  6972 D BluetoothInputDevice: Proxy object disconnected
08-25 20:54:21.531  6972  6972 D HidProfile: Bluetooth service disconnected
08-25 20:54:21.533  4317  4317 D PanService: Received stop request...Stopping profile...
08-25 20:54:21.533  4317  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359d6f08
08-25 20:54:21.535  6972  6972 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 20:54:21.535  4317  4317 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 20:54:21.535  6972  6972 D PanProfile: Bluetooth service disconnected
08-25 20:54:21.535  4317  4317 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 20:54:21.535  4317  4317 D BtGatt.GattService: stop()
08-25 20:54:21.535  4317  4317 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 20:54:21.537  4317  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359d6f08
08-25 20:54:21.539  4317  4317 D BluetoothMapService: Received stop request...Stopping profile...
08-25 20:54:21.539  4317  4317 D BluetoothMapService: stop()
08-25 20:54:21.539  4317  4317 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 20:54:21.540  4317  4317 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 20:54:21.541  4317  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359d6f08
08-25 20:54:21.542  4317  4317 D HeadsetStateMachine: Unbinding service...
08-25 20:54:21.542  6972  6972 D BluetoothMap: Proxy object disconnected
08-25 20:54:21.542  6972  6972 D MapProfile: Bluetooth service disconnected
08-25 20:54:21.543  4317  4317 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 20:54:21.543  4317  4317 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 20:54:21.543  4317  4317 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 20:54:21.543  4317  4317 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 20:54:21.543  4317  4317 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 20:54:21.543  4317  4317 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:54:21.543  4317  4317 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 20:54:21.543  4317  4317 I BluetoothA2dpServiceJni: cleanupNative
08-25 20:54:21.544  4317  4502 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 20:54:21.544  4317  4317 I GKI_LINUX: GKI_exit_task 2 done
08-25 20:54:21.544  4317  4317 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 20:54:21.544  4317  4317 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 20:54:21.544  4317  4317 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 20:54:21.545  4317  4317 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 20:54:21.545  4317  4317 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 20:54:21.545  4317  4317 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 20:54:21.545  4317  4317 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 20:54:21.545  4317  4317 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 20:54:21.547  4317  4317 V BluetoothMapService: Handler(): got msg=4
08-25 20:54:21.547  4317  4317 D BluetoothMapService: MAP Service closeService in
08-25 20:54:21.547  4317  4317 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 20:54:21.547  4317  4317 V BluetoothMapService: MAP Service closeService out
,08-25 20:54:21.548  4317  4401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 20:54:21.548  4317  4401 D BluetoothAdapterProperties: Setting state to 10
08-25 20:54:21.548  4317  4401 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 20:54:21.548  4317  4401 I BluetoothAdapterState: Entering OffState
08-25 20:54:21.549  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:21.549  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 20:54:21.549  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 20:54:21.549  1845  2442 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:21.549  1027  1115 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:21.550  1845  1861 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:21.550  4317  4317 D BluetoothMapService: cleanup()
08-25 20:54:21.550  4317  4317 D BluetoothMapService: MAP Service closeService in
08-25 20:54:21.550  4317  4317 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 20:54:21.550  4317  4317 V BluetoothMapService: MAP Service closeService out
08-25 20:54:21.552  1845  2624 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:21.553  1027  1115 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 20:54:21.553  6972  6991 D BluetoothPan: onBluetoothStateChange on: false
08-25 20:54:21.553  6972  6989 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 20:54:21.554  6972  6991 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 20:54:21.555  6972  6989 D BluetoothMap: onBluetoothStateChange: up=false
08-25 20:54:21.556  1027  1115 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 20:54:21.556  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 20:54:21.559  1027  1115 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 20:54:21.559  1027  1115 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 20:54:21.559  1027  1115 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@31cc9c25 mBinding = false
,08-25 20:54:21.560  1027  1115 D BluetoothManagerService: Sending unbind request.
08-25 20:54:21.562  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 20:54:21.569  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:21.569  1933  2124 D LGBluetoothAPIService: Message: 2
08-25 20:54:21.569  1933  2124 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2c153e3b mBinding = false
08-25 20:54:21.569  4317  4404 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 20:54:21.569  1933  2124 D LGBluetoothAPIService: Sending unbind request.
08-25 20:54:21.570  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 20:54:21.570  4317  4317 I GKI_LINUX: GKI_exit_task 1 done
08-25 20:54:21.570  4317  4317 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 20:54:21.571  4317  4317 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 20:54:21.571  4317  4317 I art     : --- WEIRD: removing null entry 246
08-25 20:54:21.571  4317  4317 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 20:54:21.571  4317  4317 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 20:54:21.576  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:21.578  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:21.579  6972  6972 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 20:54:21.580  6972  6972 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 20:54:21.580  6972  6972 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 20:54:21.581  4317  4317 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 20:54:21.583  1593  1593 D BluetoothAdapter: 204641443: getState() :  mService = null. Returning STATE_OFF
08-25 20:54:21.583  1593  1593 D BluetoothAdapter: 204641443: getState() :  mService = null. Returning STATE_OFF
,08-25 20:54:21.585  6972  6972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 20:54:21.586  4317  4317 I art     : System.exit called, status: 0
08-25 20:54:21.586  4317  4317 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 20:54:21.594  6972  6972 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:54:21.615   316  1385 V AudioFlinger: 4317 died, releasing its sessions
08-25 20:54:21.615   316  1385 V AudioFlinger:  pid 1845 @ 0
08-25 20:54:21.615   316  1385 V AudioFlinger:  pid 3313 @ 1
08-25 20:54:21.615   316  1385 V AudioFlinger:  pid 3313 @ 2
,08-25 20:54:21.615  6972  6972 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 20:54:21.670  1027  1567 I ActivityManager: Process com.android.bluetooth (pid 4317) has died
,08-25 20:54:21.671  1027  1567 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-25 20:54:21.684  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:21.704  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 20:54:21.729  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 20:54:21.741  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:21.741  7064  7091 W FormManager: Network not available. Please check & try again.
08-25 20:54:21.744  6972  6972 D BluetoothPermissionRequest: onReceive
08-25 20:54:21.746  6972  6972 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-25 20:54:21.746  6972  6972 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 20:54:21.748  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 20:54:21.809  1027  1727 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7093 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 20:54:21.839  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-25 20:54:21.844  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 20:54:21.844  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 20:54:21.845  6972  6972 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 20:54:21.847  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-25 20:54:21.851  7064  7092 V FormManager: Network unavailable.
08-25 20:54:21.854  7064  7092 V FormManager: Network unavailable.
08-25 20:54:21.858  6972  6972 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 20:54:21.858  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 20:54:21.858  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 20:54:21.858  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 20:54:21.858  6972  6972 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 20:54:21.859  6972  6972 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 20:54:21.864  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 20:54:21.865  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 20:54:21.867  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:21.869  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:21.879  4812  7113 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 20:54:21.879  6995  6995 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 20:54:21.879  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 20:54:21.879  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:21.883  4812  7112 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:21.888  4812  7113 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 20:54:21.891  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 20:54:21.898  7064  7116 W FormManager: Network not available. Please check & try again.
08-25 20:54:21.900  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:21.906  7093  7093 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 20:54:21.907  7093  7093 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 20:54:21.907  7093  7093 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-25 20:54:21.908  7093  7093 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 20:54:21.909  7064  7117 V FormManager: Network unavailable.
08-25 20:54:21.915  7064  7117 V FormManager: Network unavailable.
08-25 20:54:21.919  7026  7026 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-25 20:54:21.920  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 20:54:21.921  7026  7026 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 20:54:21.929  7093  7093 D BluetoothAdapterApp: Loading JNI Library
08-25 20:54:21.931  1027  2004 I ActivityManager: Killing 6483:com.lge.email/u0a23 (adj 15): empty #17
,08-25 20:54:21.960  7026  7026 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:21.960  7026  7026 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 20:54:21.964  7093  7093 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@91b3369 Instance Count = 1
08-25 20:54:21.968  7026  7026 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 20:54:21.970  7026  7026 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-25 20:54:21.970  7026  7026 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
08-25 20:54:21.970  7026  7026 V SoundPool: doLoad: loading sample sampleID=1
08-25 20:54:21.971  7026  7120 V SoundPool: Start decode
08-25 20:54:21.971  7026  7120 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-25 20:54:21.972   316  2159 V MediaPlayerService: decode(22, 10857164, 17813)
08-25 20:54:21.972   316  2159 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 20:54:21.972   316  2159 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 20:54:21.972   316  2159 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 20:54:21.972   316  2159 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 20:54:21.972   316  2159 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 20:54:21.972   316  2159 V MediaPlayerService: player type = 3
08-25 20:54:21.972   316  2159 V AwesomePlayer: AwesomePlayer create()
08-25 20:54:21.973  7026  7026 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 20:54:21.973   316  2159 V AwesomePlayer: reset_l() 
,08-25 20:54:21.973   316  2159 V AwesomePlayer: cancelPlayerEvents
08-25 20:54:21.973   316  2159 V AwesomePlayer: setAudioSink() 
08-25 20:54:21.973   316  2159 V AwesomePlayer: reset_l() 
08-25 20:54:21.973   316  2159 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-25 20:54:21.973   316  2159 V AudioCache: ignored
08-25 20:54:21.973   316  2159 V AwesomePlayer: cancelPlayerEvents
08-25 20:54:21.973   316  2159 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 20:54:21.973   316  2159 V AwesomePlayer: setDataSource_l dataSource
08-25 20:54:21.973   316  2159 V LGParserOSAL: SniffLGParser start
08-25 20:54:21.973   316  2159 V LGParserOSAL: MainType:5, SubType=0
08-25 20:54:21.973   316  2159 V LGParserOSAL: #### check Mime : application/ogg
08-25 20:54:21.973   316  2159 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 20:54:21.973   316  2159 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 20:54:21.992  1027  1767 W libprocessgroup: failed to open /acct/uid_10023/pid_6483/cgroup.procs: No such file or directory
,08-25 20:54:21.996  7093  7093 D BluetoothAdapterApp: onCreate
08-25 20:54:22.000  6768  6768 D UEI.SmartControl: QS Service created
08-25 20:54:22.006  7026  7026 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-25 20:54:22.013  7026  7026 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 20:54:22.014   316  2159 V LGParserOSAL: supported mime: application/ogg
08-25 20:54:22.014   316  2159 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 20:54:22.014   316  2159 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 20:54:22.014   316  2159 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 20:54:22.014   316  2159 V AwesomePlayer: AudioTrack Setting
08-25 20:54:22.014   316  2159 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 20:54:22.014   316  2159 V AwesomePlayer: setAudioSource() 
08-25 20:54:22.014   316  2159 V MediaPlayerService: prepare
08-25 20:54:22.014   316  2159 V AwesomePlayer: prepareAsync_l() 
08-25 20:54:22.014   316  2159 V MediaPlayerService: wait for prepare
08-25 20:54:22.014  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 20:54:22.014   316  7121 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 20:54:22.015   316  7121 V AwesomePlayer: initAudioDecoder() 
08-25 20:54:22.015   316  7121 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 20:54:22.015   316  7121 V AudioSystem: isOffloadSupported()
08-25 20:54:22.015   316  7121 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 20:54:22.015   316  7121 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 20:54:22.015   316  7121 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 20:54:22.015   316  7121 V AwesomePlayer: getUseOffload() = 0 
08-25 20:54:22.015   316  7121 V OMXCodec: OMXCodec::Create
08-25 20:54:22.015   316  7121 V OMXCodec: findMatchingCodecs()
08-25 20:54:22.015   316  7121 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 20:54:22.015   316  7121 V OMXCodec: matchingCodecs.size()=1
08-25 20:54:22.015   316  7121 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 20:54:22.017   316  7121 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 20:54:22.017   316  7121 V LGCodecAdapter: LG Codec Adapter start
08-25 20:54:22.017   316  7121 V OMXCodec: OMXCodec Createtor
08-25 20:54:22.017   316  7121 V OMXCodec: setComponentRole
08-25 20:54:22.017   316  7121 V OMXCodec: configureCodec protected=0
08-25 20:54:22.017   316  7121 V LGCodecAdapter: called getLGCodecSpecificData
08-25 20:54:22.017   316  7121 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 20:54:22.017   316  7121 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 20:54:22.018   316  7121 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 20:54:22.018   316  7121 V LGCodecOSAL: Not support LGCodec
08-25 20:54:22.018   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 20:54:22.018   316  7121 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 20:54:22.018   316  7121 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 20:54:22.018   316  7121 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 20:54:22.018   316  7121 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 20:54:22.018   316  7121 V AudioSystem: isOffloadSupported()
08-25 20:54:22.018   316  7121 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 20:54:22.018   316  7121 D AudioPolicyManager: isOffloadSupported: stream_typ,e != MUSIC, returning false
08-25 20:54:22.018   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 20:54:22.018   316  7121 V OMXCodec: init()
08-25 20:54:22.018   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 20:54:22.018   316  7121 V OMXCodec: allocateBuffers
08-25 20:54:22.018   316  7121 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 20:54:22.018   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f8d0 on input port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f920 on input port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f970 on input port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f9c0 on input port
08-25 20:54:22.019   316  7121 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa10 on output port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on output port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb00 on output port
08-25 20:54:22.019   316  7121 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000ffb0 on output port
08-25 20:54:22.019   316  7121 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 20:54:22.019   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 20:54:22.019   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 20:54:22.019   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 20:54:22.020   316  7121 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 20:54:22.020   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 20:54:22.020   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 20:54:22.020   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 20:54:22.020   316  7121 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 20:54:22.020   316  7121 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 20:54:22.020   316  7121 V AudioCache: notify(0xb1432480, 5, 0, 0)
08-25 20:54:22.020   316  7121 V AudioCache: ignored
08-25 20:54:22.020   316  7121 V AudioCache: notify(0xb1432480, 1, 0, 0)
08-25 20:54:22.020   316  7121 V AudioCache: prepared
08-25 20:54:22.020   316  2159 V AudioCache: wait - success
08-25 20:54:22.020   316  2159 V MediaPlayerService: start
08-25 20:54:22.020   316  2159 V AwesomePlayer: play_l() 
08-25 20:54:22.020   316  2159 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 20:54:22.020   316  2159 V AwesomePlayer: createAudioPlayer_l
08-25 20:54:22.020   316  2159 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 20:54:22.020   316  2159 V AwesomePlayer: startAudioPlayer_l() 
08-25 20:54:22.020   316  2159 D AudioPlayer: start of Playback, useOffload 0
08-25 20:54:22.020   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 20:54:22.020   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 20:54:22.023  7093  7093 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 20:54:22.024  7093  7093 D ProfileConfigQcom: Adding HeadsetService
08-25 20:54:22.024  6768  6768 I UEI.SmartControl: Service initServices...
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 20:54:22.024  6768  6768 D UEI.SmartControl: QS start get config
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 20:54:22.024  7093  7093 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854032
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854192
08-25 20:54:22.024   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952854272
08-25 20:54:,22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952855472
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 20:54:22.025   316  7124 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fb00 on output port
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fab0 on output port
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000fa10 on output port
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on output port
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 20:54:22.025   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 20:54:22.026   316  2159 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 20:54:22.026   316  2159 V AudioCache: notify(0xb1432480, 6, 0, 0)
08-25 20:54:22.026   316  2159 V AudioCache: ignored
08-25 20:54:22.027   316  2159 V MediaPlayerService: wait for playback complete
08-25 20:54:22.027   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.027   316  7125 V AudioCache: memcpy(0xb051d000, 0xb57be000, 4096)
08-25 20:54:22.028   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.028   316  7125 V AudioCache: memcpy(0xb051e000, 0xb57be000, 4096)
08-25 20:54:22.028   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.028   316  7125 V AudioCache: memcpy(0xb051f000, 0xb57be000, 4096)
08-25 20:54:22.029   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.029   316  7125 V AudioCache: memcpy(0xb0520000, 0xb57be000, 4096)
08-25 20:54:22.029   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.029   316  7125 V AudioCache: memcpy(0xb0521000, 0xb57be000, 4096)
08-25 20:54:22.029   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.029   316  7125 V AudioCache: memcpy(0xb0522000, 0xb57be000, 4096)
08-25 20:54:22.030   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.030   316  7125 V AudioCache: memcpy(0xb0523000, 0xb57be000, 4096)
08-25 20:54:22.030  7093  7093 D ProfileConfigQcom: Adding A2dpService
08-25 20:54:22.030   316  7125 V AudioCache: write(0xb57be000, 4096)
,08-25 20:54:22.030   316  7125 V AudioCache: memcpy(0xb0524000, 0xb57be000, 4096)
08-25 20:54:22.030  7093  7093 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 20:54:22.031   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.031   316  7125 V AudioCache: memcpy(0xb0525000, 0xb57be000, 4096)
08-25 20:54:22.031   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.031   316  7125 V AudioCache: memcpy(0xb0526000, 0xb57be000, 4096)
08-25 20:54:22.031  7093  7093 D ProfileConfigQcom: Adding HidService
08-25 20:54:22.031   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.031   316  7125 V AudioCache: memcpy(0xb0527000, 0xb57be000, 4096)
08-25 20:54:22.032  7093  7093 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 20:54:22.032   316  7125 V AudioCache: write(0xb57be000, 4096)
,08-25 20:54:22.032   316  7125 V AudioCache: memcpy(0xb0528000, 0xb57be000, 4096)
08-25 20:54:22.032   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.032   316  7125 V AudioCache: memcpy(0xb0529000, 0xb57be000, 4096)
08-25 20:54:22.032  7093  7093 D ProfileConfigQcom: Adding HealthService
08-25 20:54:22.033   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.033   316  7125 V AudioCache: memcpy(0xb052a000, 0xb57be000, 4096)
08-25 20:54:22.033   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.033  7093  7093 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 20:54:22.033   316  7125 V AudioCache: memcpy(0xb052b000, 0xb57be000, 4096)
08-25 20:54:22.033   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.033   316  7125 V AudioCache: memcpy(0xb052c000, 0xb57be000, 4096)
,08-25 20:54:22.035   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: memcpy(0xb052d000, 0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: memcpy(0xb052e000, 0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: memcpy(0xb052f000, 0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: memcpy(0xb0530000, 0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.035   316  7125 V AudioCache: memcpy(0xb0531000, 0xb57be000, 4096)
08-25 20:54:22.036   316  7125 V AudioCache: write(0xb57be000, 4096)
,08-25 20:54:22.036   316  7125 V AudioCache: memcpy(0xb0532000, 0xb57be000, 4096)
08-25 20:54:22.036   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.036   316  7125 V AudioCache: memcpy(0xb0533000, 0xb57be000, 4096)
08-25 20:54:22.037   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.037   316  7125 V AudioCache: memcpy(0xb0534000, 0xb57be000, 4096)
08-25 20:54:22.037   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.037   316  7125 V AudioCache: memcpy(0xb0535000, 0xb57be000, 4096)
08-25 20:54:22.037   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.037   316  7125 V AudioCache: memcpy(0xb0536000, 0xb57be000, 4096)
08-25 20:54:22.038   316  7125 V AudioCache: write(0xb57be000, 4096)
,08-25 20:54:22.038   316  7125 V AudioCache: memcpy(0xb0537000, 0xb57be000, 4096)
08-25 20:54:22.038   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.038   316  7125 V AudioCache: memcpy(0xb0538000, 0xb57be000, 4096)
08-25 20:54:22.038   316  7125 V AudioCache: write(0xb57be000, 4096)
,08-25 20:54:22.038   316  7125 V AudioCache: memcpy(0xb0539000, 0xb57be000, 4096)
,08-25 20:54:22.039   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.039   316  7125 V AudioCache: memcpy(0xb053a000, 0xb57be000, 4096)
08-25 20:54:22.039   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.039   316  7125 V AudioCache: memcpy(0xb053b000, 0xb57be000, 4096)
08-25 20:54:22.040   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.040   316  7125 V AudioCache: memcpy(0xb053c000, 0xb57be000, 4096)
08-25 20:54:22.040  7093  7093 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 20:54:22.040  7093  7093 D ProfileConfigQcom: Adding PanService
08-25 20:54:22.040  7093  7093 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 20:54:22.040  7093  7093 D ProfileConfigQcom: Adding GattService
08-25 20:54:22.041  7093  7093 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 20:54:22.041  7093  7093 D ProfileConfigQcom: Adding BluetoothMapService
,08-25 20:54:22.041  7093  7093 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 20:54:22.043  7093  7093 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 20:54:22.045   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.046  6972  6972 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 20:54:22.045   316  7125 V AudioCache: memcpy(0xb053d000, 0xb57be000, 4096)
08-25 20:54:22.047   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.047  7093  7093 V LGMDMManagerInternal: Create singleton instance
08-25 20:54:22.047   316  7125 V AudioCache: memcpy(0xb053e000, 0xb57be000, 4096)
08-25 20:54:22.048   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.048   316  7125 V AudioCache: memcpy(0xb053f000, 0xb57be000, 4096)
08-25 20:54:22.048   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.048   316  7125 V AudioCache: memcpy(0xb0540000, 0xb57be000, 4096)
08-25 20:54:22.048   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.048   316  7125 V AudioCache: memcpy(0xb0541000, 0xb57be000, 4096)
08-25 20:54:22.049   316  7125 V AudioCache: write(0xb57be000, 4096)
,08-25 20:54:22.049   316  7125 V AudioCache: memcpy(0xb0542000, 0xb57be000, 4096)
08-25 20:54:22.050   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.051   316  7125 V AudioCache: memcpy(0xb0543000, 0xb57be000, 4096)
08-25 20:54:22.051   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.051   316  7125 V AudioCache: memcpy(0xb0544000, 0xb57be000, 4096)
08-25 20:54:22.052   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.052   316  7125 V AudioCache: memcpy(0xb0545000, 0xb57be000, 4096)
08-25 20:54:22.053   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.053   316  7125 V AudioCache: memcpy(0xb0546000, 0xb57be000, 4096)
08-25 20:54:22.053   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.053   316  7125 V AudioCache: memcpy(0xb0547000, 0xb57be000, 4096)
08-25 20:54:22.053   316  7125 V AudioCache: write(0xb57be000, 4096)
,08-25 20:54:22.053   316  7125 V AudioCache: memcpy(0xb0548000, 0xb57be000, 4096)
08-25 20:54:22.054   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.054   316  7125 V AudioCache: memcpy(0xb0549000, 0xb57be000, 4096)
08-25 20:54:22.055   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.055   316  7125 V AudioCache: memcpy(0xb054a000, 0xb57be000, 4096)
08-25 20:54:22.055   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.055   316  7125 V AudioCache: memcpy(0xb054b000, 0xb57be000, 4096)
08-25 20:54:22.056   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.056   316  7125 V AudioCache: memcpy(0xb054c000, 0xb57be000, 4096)
08-25 20:54:22.057   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.057   316  7125 V AudioCache: memcpy(0xb054d000, 0xb57be000, 4096)
,08-25 20:54:22.057   316  7125 V AudioCache: write(0xb57be000, 4096)
08-25 20:54:22.057   316  7125 V AudioCache: memcpy(0xb054e000, 0xb57be000, 4096)
,08-25 20:54:22.059   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 20:54:22.059   316  7125 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 20:54:22.059   316  7125 V AwesomePlayer: postAudioEOS() 
08-25 20:54:22.059   316  7125 V AudioCache: write(0xb57be000, 280)
08-25 20:54:22.059   316  7125 V AudioCache: memcpy(0xb054f000, 0xb57be000, 280)
08-25 20:54:22.061   316  7121 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 20:54:22.061   316  7121 V AwesomePlayer: onStreamDone
08-25 20:54:22.061   316  7121 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 20:54:22.061   316  7121 V AudioCache: notify(0xb1432480, 2, 0, 0)
08-25 20:54:22.061   316  7121 V AudioCache: playback complete
08-25 20:54:22.061   316  7121 V AwesomePlayer: pause_l() 
08-25 20:54:22.061   316  7121 V AudioCache: notify(0xb1432480, 7, 0, 0)
08-25 20:54:22.061   316  7121 V AudioCache: ignored
08-25 20:54:22.061   316  7121 V AwesomePlayer: cancelPlayerEvents
08-25 20:54:22.061   316  2159 V AudioCache: wait - success
08-25 20:54:22.061   316  2159 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 20:54:22.061   316  7121 D AudioPlayer: Pause Playback at 1068125
08-25 20:54:22.061   316  2159 V AwesomePlayer: reset_l() 
08-25 20:54:22.061   316  2159 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-25 20:54:22.061   316  2159 V AudioCache: ignored
08-25 20:54:22.061   316  2159 V AwesomePlayer: cancelPlayerEvents
08-25 20:54:22.061   316  2159 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 20:54:22.061   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 20:54:22.061   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 20:54:22.061   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 20:54:22.061   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 20:54:22.061   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 20:54:22.061   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 20:54:22.061   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 20:54:22.061   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f9c0 on port 0
08-25 20:54:22.061   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f970 on port 0
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f920 on port 0
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f8d0 on port 0
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fa10 on port 1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fab0 on port 1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000fb00 on port 1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google,.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 20:54:22.062   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 20:54:22.062   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 20:54:22.062   316  7124 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 20:54:22.063   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 20:54:22.063   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 20:54:22.063  7026  7026 V LGMDMManager: Create singleton instance
08-25 20:54:22.063   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 20:54:22.064   316  2159 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 20:54:22.065   316  2159 D AudioPlayer: AudioPlayer releasing audio source
08-25 20:54:22.065   316  2159 D AudioPlayer: AudioPlayer done releasing audio source
08-25 20:54:22.065   316  2159 V AwesomePlayer: reset_l() 
08-25 20:54:22.065   316  2159 V AwesomePlayer: cancelPlayerEvents
08-25 20:54:22.065   316  2159 V AwesomePlayer: ~AwesomePlayer call
08-25 20:54:22.065   316  2159 V AwesomePlayer: reset_l() 
08-25 20:54:22.065   316  2159 V AwesomePlayer: cancelPlayerEvents
08-25 20:54:22.066  7026  7120 V SoundPool: close(30)
08-25 20:54:22.066  7026  7120 V SoundPool: pointer = 0xa0007000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 20:54:22.116  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 20:54:22.121  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:22.121  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:22.121  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:22.122  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:22.122  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-25 20:54:22.127  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-25 20:54:22.128  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-25 20:54:22.129  7043  7043 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 20:54:22.131  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1559
08-25 20:54:22.294  6768  6768 I UEI.SmartControl: Supports setup maps: true
08-25 20:54:22.297  6768  6768 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 20:54:22.297  6768  6768 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 20:54:22.297  6768  6768 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 20:54:22.297  6768  6768 I UEI.SmartControl: ### init IR Blaster...
,08-25 20:54:22.300  6768  6768 D serial_port: Configuring serial port
,08-25 20:54:22.301  6768  6768 E UEI.SmartControl: UEIBLaster setting for 616
08-25 20:54:22.301  6768  6768 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 20:54:22.301  6768  6768 I UEI.SmartControl: configuring settings for MAXQ616
08-25 20:54:22.301  6768  6768 I UEI.SmartControl: Get version...
08-25 20:54:22.321  6768  7127 D UEI.SmartControl: serial port data available: 21
,08-25 20:54:22.348  6768  6768 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 20:54:22.348  6768  6768 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-25 20:54:22.348  6768  6768 I UEI.SmartControl: QS saving settings...
08-25 20:54:22.351  6768  6768 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 20:54:22.370  6768  7127 D UEI.SmartControl: serial port data available: 4
,08-25 20:54:22.404  6768  7133 I UEI.SmartControl: Device manager: loading config....
,08-25 20:54:22.405  6768  7133 D UEI.SmartControl: ----------- loading internal config...
,08-25 20:54:22.406  6768  6768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 20:54:22.410  6768  6768 E UEI.SmartControl: Services init done
08-25 20:54:22.410  6768  6768 D UEI.SmartControl: QS Service init finished
08-25 20:54:22.412  6768  6768 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 20:54:22.412  6768  6768 D UEI.SmartControl: QS Service version code: 201091
08-25 20:54:22.413  6768  6768 D UEI.SmartControl: Service requested: Control
08-25 20:54:22.429  6768  7133 E UEI.SmartControl: Loading SETTINGS...
08-25 20:54:22.436  6768  6768 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-25 20:54:22.441  6768  6768 D UEI.SmartControl: Internal service binding...
08-25 20:54:22.442  7026  7026 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 20:54:22.447  6768  6784 I UEI.SmartControl: ------ IControl API: 11
08-25 20:54:22.447  6768  6784 D UEI.SmartControl: File observer start...
08-25 20:54:22.448  6768  6784 E UEI.SmartControl: IR Port is disabled: false
08-25 20:54:22.448  6768  6784 D UEI.SmartControl: Starting file observer...
08-25 20:54:22.448  6768  7133 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 20:54:22.452  6768  6784 I UEI.SmartControl: Registering callback...
08-25 20:54:22.452  6768  6783 I UEI.SmartControl: ------ IControl API: 19
,08-25 20:54:22.453  6768  6783 I UEI.SmartControl: Registering Services Ready callback...
08-25 20:54:22.466  6768  7132 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 20:54:22.466  6768  7132 D UEI.SmartControl: -----service ready thread exits
,08-25 20:54:22.467  7026  7042 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 20:54:22.468  7026  7118 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 20:54:22.468  7026  7118 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 20:54:22.469  7026  7026 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 20:54:22.469  7026  7026 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 20:54:22.469  6768  6784 I UEI.SmartControl: ------ IControl API: 8
08-25 20:54:22.471  7026  7026 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 20:54:22.471  7026  7026 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 20:54:22.471  7026  7026 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 20:54:22.472  7026  7026 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 20:54:22.473  7026  7026 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 20:54:22.473  7026  7026 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 20:54:22.474  7026  7026 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 20:54:22.478  7026  7026 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 20:54:22.480  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-25 20:54:22.484  7026  7026 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 20:54:22.484  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 20:54:22.486  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 20:54:22.487  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 20:54:22.488  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 20:54:22.489  7026  7026 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472151262488]
08-25 20:54:22.493  7026  7026 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-25 20:54:22.500  1027  1969 I ActivityManager: Killing 6336:com.android.defcontainer/u0a4 (adj 15): empty #17
08-25 20:54:22.520  7026  7138 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 20:54:22.530  1027  1969 I ActivityManager: Killing 6022:com.android.gallery3d/u0a27 (adj 15): empty #18
08-25 20:54:22.562  1027  1968 W libprocessgroup: failed to open /acct/uid_10004/pid_6336/cgroup.procs: No such file or directory
,08-25 20:54:22.568  1027  1931 W libprocessgroup: failed to open /acct/uid_10027/pid_6022/cgroup.procs: No such file or directory
08-25 20:54:22.576  7026  7026 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-25 20:54:22.579  7026  7026 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 20:54:22.580  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 20:54:22.581  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 20:54:22.582  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 20:54:22.582  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 20:54:22.583  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-25 20:54:22.604  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-25 20:54:23.355  1027  2004 D WifiServiceImplEx: setWifiEnabled: true pid=6854, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 20:54:23.357  1027  2004 D WifiService: setWifiEnabled: true pid=6854, uid=10118
08-25 20:54:23.357  1027  2004 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 20:54:23.387  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 20:54:23.387  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:23.387  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 20:54:23.389  1027  1477 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 20:54:23.389  1027  1477 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 20:54:23.392  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 20:54:23.392  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 20:54:23.392  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 20:54:23.392  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 20:54:23.392  1027  1477 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 20:54:23.392  1027  1477 E WifiHW  : unknown target_country: EU , set to default
08-25 20:54:23.392  1027  1477 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 20:54:23.392  1027  1477 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 20:54:23.392  1027  1477 I WifiUtil: gEnableBmps=1
08-25 20:54:23.444  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:23.459  1027  1115 D Tethering: MasterInitialState.processMessage what=3
08-25 20:54:23.463  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:23.472  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:23.476  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:23.479  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:23.483  1027  1115 D Tethering: MasterInitialState.processMessage what=3
08-25 20:54:23.491  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:23.495  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:23.496  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 20:54:23.499  6392  6994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 20:54:23.501  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 20:54:23.524  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 20:54:23.549  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:23.619  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:23.644  1027  1768 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7156 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 20:54:23.647  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:23.649  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 20:54:23.718  7156  7156 I AppUp4:AppBoxCP: onCreate
08-25 20:54:23.718  7156  7156 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-25 20:54:23.727  7156  7156 I AppUp4:DB:  setFingerPrint start
08-25 20:54:23.728  7156  7156 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 20:54:23.735  7156  7156 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 20:54:23.735  7156  7156 I AppUp4:DB:  SDK version = 21
08-25 20:54:23.735  7156  7156 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-25 20:54:23.736  7156  7156 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 20:54:23.737  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 20:54:23.737  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:23.739  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 20:54:23.739  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 20:54:23.746  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-25 20:54:23.775  7156  7156 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:23.775  7156  7156 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 20:54:23.779  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1548ccab
,08-25 20:54:23.779  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-25 20:54:23.780  7156  7156 D AppUp4:CustFacade: isPhone : true
08-25 20:54:23.780  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-25 20:54:23.780  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-25 20:54:23.780  7156  7156 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 20:54:23.781  7156  7177 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 20:54:23.781  7156  7177 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 20:54:23.782  7156  7177 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 20:54:23.784  1027  1727 I ActivityManager: Killing 6569:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-25 20:54:23.842  1027  1932 W libprocessgroup: failed to open /acct/uid_10061/pid_6569/cgroup.procs: No such file or directory
08-25 20:54:23.845  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:23.846  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 20:54:23.851  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 20:54:23.855  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:23.860  4812  7179 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:23.867  4812  7180 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:23.867  4812  7180 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 20:54:23.920  1027  2005 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7184 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 20:54:23.999  7184  7184 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 20:54:24.000  7184  7184 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 20:54:24.002  7184  7184 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 20:54:24.002  7184  7184 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 20:54:24.093  7184  7184 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 20:54:24.111  1027  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 20:54:24.111  1027  1115 D Tethering: InitialState.processMessage what=4
08-25 20:54:24.114  7184  7184 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-25 20:54:24.119  1027  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 20:54:24.122   312   885 D SoftapController: Softap fwReload - Ok
,08-25 20:54:24.124  1027  1477 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (726ms)
08-25 20:54:24.126   312   885 D CommandListener: Setting iface cfg
08-25 20:54:24.126   312   885 D CommandListener: Trying to bring down wlan0
08-25 20:54:24.128   312   885 D CommandListener: Clearing all IP addresses on wlan0
08-25 20:54:24.130  1027  1477 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 20:54:24.129  7210  7210 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 20:54:24.129  7210  7210 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:24.150  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:24.150  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:24.150  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:24.151  1027  1477 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 20:54:24.151  1027  1477 D WifiMonitor: connecting to supplicant
,08-25 20:54:24.156  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:24.157  7210  7210 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 20:54:24.158  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 20:54:24.162  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:24.163  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:24.163  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-25 20:54:24.192  7210  7210 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 20:54:24.192  7210  7210 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 20:54:24.197  7184  7184 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 20:54:24.231  7184  7184 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:24.232  7184  7184 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 20:54:24.267  7210  7210 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 20:54:24.293  7210  7210 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 20:54:24.299  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 20:54:24.299  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 20:54:24.300  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 20:54:24.300  1027  1477 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 20:54:24.301  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:24.301  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:24.301  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-25 20:54:24.302  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-25 20:54:24.302  1027  1477 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 20:54:24.302  1027  1477 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 20:54:24.303  1027  1477 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 20:54:24.303  1027  1477 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 20:54:24.303  1027  1477 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 20:54:24.304  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:24.304  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:24.304  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:24.304  1027  1477 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 20:54:24.305  1027  1477 D WifiNative-wlan0: SET update_config 1: returned true
08-25 20:54:24.305  1027  1477 D WifiConfigStore: Loading config and enabling all networks 
08-25 20:54:24.306  1027  1477 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 20:54:24.306  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.306  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.306  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.306  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.306  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:24.307  1027  1477 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-25 20:54:24.309  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:24.310  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:24.310  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:24.310  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:24.310  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:24.311  1933  1933 D WfdService: Waiting for WifiP2p enabling
08-25 20:54:24.312  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 20:54:24.312  1027  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 20:54:24.313  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:24.313  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:24.313  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:24.313  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:24.313  1027  1477 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 20:54:24.321  1027  1477 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 20:54:24.321  1027  1477 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 20:54:24.322  1027  1477 D WifiStateMachine: enableVerboseLogging : level 2
08-25 20:54:24.322  1027  1477 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 20:54:24.323  1027  1477 D WifiNative-wlan0: SET device_name g3_global_com: return,ed true
08-25 20:54:24.323  1027  1477 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 20:54:24.323  1027  1477 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 20:54:24.323  1027  1477 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 20:54:24.324  1027  1477 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 20:54:24.324  1027  1477 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 20:54:24.324  1027  1477 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 20:54:24.324  1027  1477 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 20:54:24.324  1027  1477 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 20:54:24.325  1027  1477 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 20:54:24.325  1027  1477 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 20:54:24.325  1027  1477 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 20:54:24.325  1027  1477 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-25 20:54:24.326  1027  1477 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 20:54:24.326  1027  1477 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 20:54:24.327  1933  1933 D WfdsService: Supplicant Connection state is changed : true
08-25 20:54:24.327  1933  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 20:54:24.327  1933  2293 D WfdsService: Set the WFDS Monitor: true
08-25 20:54:24.327  1933  2293 D WfdsMonitor: WfdsMonitorThread create
08-25 20:54:24.328  1027  1477 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 20:54:24.328  1933  2293 D WfdsMonitor: WFDS Monitor is created and started
08-25 20:54:24.328  1027  1477 D WifiNative-HAL: Setting external_sim to 1
08-25 20:54:24.328  1933  2293 D WfdsService: WiFi: Supplicant connection re-established
08-25 20:54:24.328  1027  1477 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 20:54:24.328  1027  1477 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 20:54:24.328  1027  1477 I WifiNative-HAL: startHal
08-25 20:54:24.328  1027  1477 D wifi    : setting scan oui 0xaf74f3e0
08-25 20:54:24.329  1027  1477 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 20:54:24.329  1027  1477 I WifiNative-HAL: startHal
08-25 20:54:24.329  1027  1477 D wifi    : setting scan oui 0xaf74f3e0
08-25 20:54:24.329  1933  7221 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 20:54:24.329  1027  1477 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 20:54:24.330  1027  1477 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 20:54:24.330  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 20:54:24.330  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 20:54:24.330  1933  7221 E CtrlSupplicant: Succeed to open control connection
08-25 20:54:24.331  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 20:54:24.331  1933  7221 E CtrlSupplicant: Succeed to open monitor connection
08-25 20:54:24.331  1933  7221 D WfdsMonitor: Supplicant connection established
08-25 20:54:24.331  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 20:54:24.331  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 20:54:24.331  1933  2293 D WfdsService: Connected to the supplicant for wfds
08-25 20:54:24.331  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 20:54:24.331  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 20:54:24.331  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 20:54:24.332  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 20:54:24.332  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 20:54:24.332  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 20:54:24.332  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 20:54:24.332  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 20:54:24.332  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 20:54:24.333  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 20:54:24.333  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 20:54:24.334  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 20:54:24.334  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 20:54:24.334  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 20:54:24.334  7210  7210 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 20:54:24.334  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 20:54:24.334  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 20:54:24.334  1027  1477 D WifiNative-w,lan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 20:54:24.334  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 20:54:24.334  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 20:54:24.334  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 20:54:24.334  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 20:54:24.334  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 20:54:24.335  1027  1477 E WifiNative: : [192,615,769 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 20:54:24.335  1027  1477 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 20:54:24.336  1027  1477 D WifiNative-wlan0: RECONNECT: returned true
08-25 20:54:24.336  1027  1477 D WifiNative-wlan0: doString: [STATUS]
08-25 20:54:24.336  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 20:54:24.336  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 20:54:24.336  1027  1477 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 20:54:24.336  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:24.337  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:24.337  1027  1428 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.337  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 20:54:24.338  1027  1027 D RttService: SCAN_AVAILABLE : 3
,08-25 20:54:24.338  1027  1477 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 20:54:24.339  1027  1548 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.339  1027  1548 I WifiNative-HAL: startHal
08-25 20:54:24.339  1027  1477 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 20:54:24.339  1027  1548 D wifi    : getting scan capabilities on interface[1] = 0xaf74f3e0
08-25 20:54:24.339  1027  1548 D wifi    : failed to get capabilities : -3
08-25 20:54:24.339  1027  1548 E WifiScanningService: could not get scan capabilities
08-25 20:54:24.339  1027  1477 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 20:54:24.339  1027  1549 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.340  1027  1477 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 20:54:24.340  1027  1477 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 20:54:24.341   312   885 D CommandListener: Setting iface cfg
08-25 20:54:24.341   312   885 D CommandListener: Trying to bring up p2p0
08-25 20:54:24.341  1027  1477 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 20:54:24.341  1027  1428 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 20:54:24.341  1027  1477 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 20:54:24.341  1027  1477 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 20:54:24.341  1027  1428 D LGWifiP2pService: P2pEnablingState
08-25 20:54:24.341  7210  7210 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 20:54:24.341  1027  1428 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.341  1027  1428 D LGWifiP2pService: P2p socket connection successful
08-25 20:54:24.341  1027  1428 D LGWifiP2pService: P2pEnabledState
08-25 20:54:24.342  1027  1428 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 20:54:24.344  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 20:54:24.345  1933  1933 D WfdsService: WifiP2pState is changed : true
08-25 20:54:24.345  1933  2293 D WfdsService: Receive the WFDS_ENABLE Method
08-25 20:54:24.345  1933  2293 D WfdsService: Set the WFDS Monitor: true
08-25 20:54:24.345  1933  2293 D WfdsService: Connected to the supplicant for wfds
08-25 20:54:24.345  1933  2293 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 20:54:24.345  7210  7210 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 20:54:24.345  1933  2293 D WfdsService: selectPreferredScanChannel [36]
08-25 20:54:24.345  1933  2293 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 20:54:24.346  1027  1477 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 20:54:24.346  1027  1477 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 20:54:24.346  1027  1477 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 20:54:24.346  1027  1477 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 20:54:24.347  7210  7210 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 20:54:24.349  1933  1933 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 20:54:24.349  1933  1933 D WfdsService: isConnected: false
,08-25 20:54:24.350  1027  1428 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 20:54:24.350  1027  1477 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 20:54:24.350  1027  1428 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 20:54:24.350  1027  1428 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 20:54:24.351  1027  1477 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 20:54:24.351  1027  1428 D WifiNative-p2p0: SET device_name G3: returned true
08-25 20:54:24.351  1027  1428 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 20:54:24.351  1027  1428 D LGWifiP2pService: before postfix = G3
08-25 20:54:24.351  1027  1428 D WifiServerServiceExt: postfix byte check : 2
08-25 20:54:24.351  1027  1428 D LGWifiP2pService: after postfix = G3
08-25 20:54:24.351  1027  1477 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 20:54:24.351  1027  1428 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,08-25 20:54:24.351  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 20:54:24.360  1027  1428 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 20:54:24.360  1027  1428 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 20:54:24.360  1027  1428 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 20:54:24.361  1027  1428 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 20:54:24.361  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 20:54:24.362  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.362  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-25 20:54:24.362  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.362  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.362  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.363  7210  7210 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 20:54:24.363  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.363  1027  7220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-25 20:54:24.363  1027  7220 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.363  1027  1477 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 20:54:24.363  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.363  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.363  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 20:54:24.364  1027  7220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:24.364  1027  7220 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.364  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.364  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.364  1027  1477 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,08-25 20:54:24.365  1027  1477 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 20:54:24.365  1933  7221 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:24.365  1933  7221 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:24.366  1027  1477 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 20:54:24.366  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-25 20:54:24.366  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 20:54:24.366  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 20:54:24.366  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 20:54:24.366  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 20:54:24.366  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 20:54:24.366  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-25 20:54:24.367  1027  1477 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 20:54:24.367  1027  1477 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 20:54:24.367  1027  1477 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 20:54:24.367  1027  1477 D WifiNative-wlan0: doBoolean: SCAN
08-25 20:54:24.368  1027  1477 D WifiNative-wlan0: SCAN: returned false
,08-25 20:54:24.368  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=192649  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-25 20:54:24.370  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:24.370  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:24.371  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.371  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.371  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:24.371  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 20:54:24.373  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=192654  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 20:54:24.374  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=192654  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 20:54:24.375  1027  1428 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 20:54:24.375  1027  1428 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 20:54:24.375  1027  1428 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 20:54:24.375  1027  1428 D WifiNative-HAL: p2pGetDeviceAddress
08-25 20:54:24.376  1027  1428 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 20:54:24.376  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=192657  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 20:54:24.377  1027  1477 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:24.377  1027  1428 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 20:54:24.377  1027  1428 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 20:54:24.378  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 20:54:24.377  1027  1477 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:24.379  1027  1428 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 20:54:24.379  1027  1428 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-25 20:54:24.380  1027  1477 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:24.380  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.380  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.380  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 20:54:24.381  1027  1477 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-25 20:54:24.381  1933  1933 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 20:54:24.381  1933  1933 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 20:54:24.381  1027  1428 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 20:54:24.381  1933  1933 D WfdsService: Update P2p Interface State: 3
08-25 20:54:24.381  1027  1428 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 20:54:24.382  1027  1428 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 20:54:24.382  1027  1428 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 20:54:24.383  1027  1477 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:24.384  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:24.384  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 20:54:24.391  1027  1428 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 20:54:24.391  1027  1428 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 20:54:24.391  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:24.391  1027  1428 D LGWifiP2pService: InactiveState
08-25 20:54:24.391  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:24.391  1027  1428 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.391  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.391  1027  1428 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 20:54:24.392  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 20:54:24.392  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:24.392  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.393  1933  7221 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 20:54:24.393  1027  7220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 20:54:24.393  1027  7220 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.393  7210  7210 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 20:54:24.393  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.393  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:24.393  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.393  1027  1428 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,08-25 20:54:24.394  1933  7221 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:24.394  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1027  7220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1027  7220 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.394  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.394  1027  7220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1027  7220 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1027  7220 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 20:54:24.394  1027  7220 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1933  7221 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.394  1027  1428 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.395  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.395  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.395  1027  1428 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:24.395  1933  2293 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 20:54:24.395  1027  1027 E WifiServerServiceExt: No p2p device connected
,08-25 20:54:24.419  3313  3313 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 20:54:24.419  3313  3313 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:24.419  3313  3313 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 20:54:24.460  1027  1727 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7226 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-25 20:54:24.469  7064  7224 W FormManager: Network not available. Please check & try again.
08-25 20:54:24.473  7064  7225 V FormManager: Network unavailable.
08-25 20:54:24.477  7064  7225 V FormManager: Network unavailable.
,08-25 20:54:24.492   349   349 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 656us total 28.931ms
,08-25 20:54:24.512   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 567us total 19.426ms
,08-25 20:54:24.516  1027  1932 I art     : Explicit concurrent mark sweep GC freed 79206(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 5.498ms total 101.762ms
08-25 20:54:24.525  7184  7184 I HubEmail: JNI_OnLoad()
08-25 20:54:24.525  7184  7184 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 20:54:24.525  7184  7184 I HubEmail: registerNatives()
08-25 20:54:24.525  7184  7184 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 20:54:24.526  7184  7184 I HubEmail: registerNativeMethods()
08-25 20:54:24.526  7184  7184 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 20:54:24.526  7184  7184 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-25 20:54:24.532   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 390us total 18.243ms
08-25 20:54:24.534  7184  7243 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:24.535  1027  1968 I ActivityManager: Killing 6619:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-25 20:54:24.594  7226  7226 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:24.594  7226  7226 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 20:54:24.596  7226  7226 D PhoneMonitor: Register our PhoneStateListener
,08-25 20:54:24.602  1027  2005 W libprocessgroup: failed to open /acct/uid_10080/pid_6619/cgroup.procs: No such file or directory
08-25 20:54:24.621  7226  7226 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 20:54:24.625  7226  7226 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 20:54:24.650  7226  7226 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-25 20:54:24.651  7226  7226 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 20:54:24.652  7226  7226 D TelephonyAutoProfiling: [parse] Load xml
08-25 20:54:24.655  7226  7226 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 20:54:24.656  7226  7226 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 20:54:24.656  7226  7226 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-25 20:54:24.668  7226  7226 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-25 20:54:24.710  1027  1896 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7246 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 20:54:24.712  1027  1896 I ActivityManager: Killing 6694:com.lge.eula/1000 (adj 15): empty #17
08-25 20:54:24.782  1027  2043 W libprocessgroup: failed to open /acct/uid_1000/pid_6694/cgroup.procs: No such file or directory
,08-25 20:54:24.982  7210  7210 E wpa_supplicant: USIM:  scard_init function
08-25 20:54:24.983  7210  7210 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 20:54:24.990  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 20:54:24.990  1027  7220 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 20:54:24.990  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 20:54:24.990  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-25 20:54:24.990  1027  7220 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 20:54:24.991  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 20:54:24.991  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-25 20:54:24.993  1027  1477 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:24.993  1027  1477 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:24.994  1027  1477 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:24.995  1027  1477 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:24.995  1027  1477 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 20:54:25.045  1027  1896 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7270 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-25 20:54:25.056  1027  1896 I ActivityManager: Killing 5616:com.lge.bnr/1000 (adj 15): empty #17
08-25 20:54:25.107  7210  7210 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 20:54:25.108  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 20:54:25.108  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 20:54:25.108  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,08-25 20:54:25.109  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 20:54:25.109  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:25.109  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:25.117  7210  7210 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 20:54:25.117  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 20:54:25.118  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=193398  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 20:54:25.118  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:25.119  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 20:54:25.119  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 20:54:25.119  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 20:54:25.119  1027  7220 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 20:54:25.119  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 20:54:25.119  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 20:54:25.119  1027  7220 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 20:54:25.119  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:25.120  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:25.125  1027  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 20:54:25.126  1027  2043 W libprocessgroup: failed to open /acct/uid_1000/pid_5616/cgroup.procs: No such file or directory
,08-25 20:54:25.134  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=193415  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 20:54:25.134  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=193415  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 20:54:25.135  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=193416  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 20:54:25.135  1027  1477 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193416
08-25 20:54:25.136  1027  1477 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193417
08-25 20:54:25.136  1027  1477 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193417
08-25 20:54:25.137  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193417
,08-25 20:54:25.137  1027  1477 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193418
08-25 20:54:25.137  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193418  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 20:54:25.143  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.143  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 20:54:25.143  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 20:54:25.149  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.150  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:25.153  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.153  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.153  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 20:54:25.156  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.157  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193437  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 20:54:25.157  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=193438  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 20:54:25.158  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=193439  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 20:54:25.159  1027  1477 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193440
08-25 20:54:25.159  1027  1477 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193440
,08-25 20:54:25.161  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.161  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:25.160  1027  1477 D WifiNative-wlan0: doString: [STATUS]
08-25 20:54:25.162  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.162  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:25.162  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:25.163  1027  1477 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 20:54:25.163  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.164  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.164  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 20:54:25.164  1027  1477 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 20:54:25.172  1027  1477 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 20:54:25.172  1027  1477 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 20:54:25.178  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.178  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.178  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.179  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 20:54:25.180  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:25.181  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.181  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.181  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 20:54:25.181  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.184  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.184  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 20:54:25.185  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.187  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.187  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:25.187  1027  1477 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 20:54:25.187  1027  1477 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 20:54:25.187  1027  1477 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 20:54:25.187  1027  1535 D ConnectivityService: Got NetworkAgent Messenger
08-25 20:54:25.187  1027  1477 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 20:54:25.187  1027  1477 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 20:54:25.188  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 20:54:25.188  1027  1535 D ConnectivityService: NetworkAgent connected
08-25 20:54:25.188  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.192  1027  1477 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 20:54:25.192  1027  1477 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 20:54:25.192  1027  1477 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 20:54:25.193  1027  1477 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 20:54:25.193  1027  1477 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 20:54:25.197  1027  1477 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 20:54:25.200   312   885 D CommandListener: Setting iface cfg
08-25 20:54:25.203  1027  1477 E WifiStateMachine: Start Dhcp Watchdog 2
08-25 20:54:25.203  1027  7299 D DhcpStateMachine: StoppedState
08-25 20:54:25.203  1027  7299 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.203  1027  7299 D DhcpStateMachine: WaitBeforeStartState
08-25 20:54:25.204  1027  1477 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193484  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:25.204  1027  1477 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193485  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:25.205  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193486  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:25.206  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:25.206  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 20:54:25.208  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:25.208  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 20:54:25.209  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:25.209  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:25.210  1027  1477 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:25.210  1027  1477 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:25.211  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:25.211  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:25.212  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:25.212  1027  1027 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-25 20:54:25.212  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:25.212  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 20:54:25.213  1027  1477 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=193494  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:25.214  1027  1477 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=193495  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:25.215  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=193495  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:25.216  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:146588] from screen [on:0 period:-1022517312] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 20:54:25.217  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1022517311] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 20:54:25.217  1027  1477 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 20:54:25.249  1027  1768 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7300 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 20:54:25.251  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.252  1027  1535 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 20:54:25.252  1027  1768 I ActivityManager: Killing 6651:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 20:54:25.252  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.252  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.253  1027  1477 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.253  1027  1477 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.254  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.254  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.255  1027  1535 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 20:54:25.255  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=166,0,0
08-25 20:54:25.256  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=166,0,0
08-25 20:54:25.256  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 20:54:25.256  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 20:54:25.257  1027  1477 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 20:54:25.257  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 20:54:25.257  1027  1477 D WifiNative-wlan0: SET ps 0: returned true
08-25 20:54:25.257  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 20:54:25.257  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 20:54:25.258  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 20:54:25.258  1027  1428 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d91ef35 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.258  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d91ef35 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.258  1027  1477 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 20:54:25.258  1027  7299 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.258  1027  1477 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 20:54:25.258  1027  7299 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 20:54:25.258  1027  1477 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 20:54:25.259   312   885 D CommandListener: Setting iface cfg
08-25 20:54:25.260   312   885 D CommandListener: Trying to bring up wlan0
08-25 20:54:25.260  1027  1477 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-25 20:54:25.312  1027  1950 W libprocessgroup: failed to open /acct/uid_10097/pid_6651/cgroup.procs: No such file or directory
08-25 20:54:25.314  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:25.314  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 20:54:25.316  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:25.316  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 20:54:25.317  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.318  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.319  1027  1477 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.321  1027  1477 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.322  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 20:54:25.323  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:25.325  1027  1535 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 20:54:25.326  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 20:54:25.327  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 20:54:25.328  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.328  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.328  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 20:54:25.329  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 20:54:25.329  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 20:54:25.329  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 20:54:25.330  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 20:54:25.330  1027  1477 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 20:54:25.330  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:25.340  7300  7300 I art     : Almond Protected OAT
08-25 20:54:25.346  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:25.347  1027  1535 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-25 20:54:25.347  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 20:54:25.348  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 20:54:25.348  1027  1477 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 20:54:25.348  1027  1535 D ConnectivityService: ignoring duplicate network state non-change
08-25 20:54:25.350  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 20:54:25.352  1027  1535 D ConnectivityService: Adding iface wlan0 to network 101
08-25 20:54:25.355  1027  1477 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 20:54:25.371  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.371  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:25.371  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:25.381  1933  1933 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 20:54:25.381  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.382  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.382  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 20:54:25.382  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.382  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.382  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 20:54:25.382  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 20:54:25.383  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.384  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.384  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 20:54:25.384  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 20:54:25.388  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.388  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:25.388  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 20:54:25.395  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.395  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 20:54:25.396  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.398  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.398  1593  1593 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 20:54:25.398  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.401  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:25.401  1593  1593 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 20:54:25.401  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.402  1027  1535 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 20:54:25.402  1027  1535 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 20:54:25.403  1027  1535 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 20:54:25.403   312   885 E Netd    : netlink response contains error (File exists)
08-25 20:54:25.404  1027  1535 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 20:54:25.405  1027  1535 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 20:54:25.405  1027  1535 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 20:54:25.405  1027  1535 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 20:54:25.406  1027  1535 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-25 20:54:25.406  1027  1535 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 20:54:25.406  1027  1535 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 20:54:25.406  1027  1535 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 20:54:25.406  1027  1535 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 20:54:25.406  1027  1535 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:25.406  1027  1535 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 20:54:25.406  1027  1535 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.406  1027  1535 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 20:54:25.406  1027  1535 D ConnectivityService: currentScore = 0, newScore = 20
,08-25 20:54:25.406  1027  1535 D ConnectivityService:    accepting network in place of null
08-25 20:54:25.406  1027  1535 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.407  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.407  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 20:54:25.407  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.407  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 20:54:25.409  1027  1535 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 20:54:25.409  1027  1535 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 20:54:25.409  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 20:54:25.410  1845  1845 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.410  1845  1845 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 20:54:25.411   312  7320 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 20:54:25.411  1027  1477 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.411  1027  1477 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:25.412  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 20:54:25.412  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 20:54:25.412  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 20:54:25.412  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 20:54:25.413  1027  1535 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:25.416  1027  1535 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 20:54:25.416  1027  1535 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> ,192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 20:54:25.417  1027  1535 D ConnectivityService: validation of new default Network = false
08-25 20:54:25.417  1027  1535 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 20:54:25.417  1027  1535 D DSQN    : enableDataServiceNotify 
08-25 20:54:25.417  1027  1535 D DSQN    : start dsqn bin
,08-25 20:54:25.423  1027  1535 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 20:54:25.423  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.423  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:25.424  1027  1535 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:25.425  1593  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 20:54:25.419  7321  7321 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:25.419  7321  7321 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:25.430  1027  1428 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.430  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.430  1027  1428 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:25.434  1027  1426 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 20:54:25.437  1027  1477 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 20:54:25.438  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 20:54:25.438  1027  1477 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 20:54:25.438  1027  1477 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 20:54:25.439  7321  7321 E DSQN    : DSQN ssw
08-25 20:54:25.439  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 20:54:25.440  1027  1477 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-25 20:54:25.442  7300  7300 D WeatherApplication: removeAccount
08-25 20:54:25.443  7300  7300 D WeatherApplication: Account.length = 0
08-25 20:54:25.443  7300  7300 E WeatherApplication: OPERATOR:OPEN
08-25 20:54:25.447  7300  7300 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:25
08-25 20:54:25.449  1809  7323 I CheckinService: active receiver: enabled
08-25 20:54:25.450  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:25.450  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.451  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:25.459  7300  7300 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 20:54:25.459  7300  7300 D Weather.Utils: 2 : All the weather widget is gone.
08-25 20:54:25.459  1809  7323 I CheckinService: Preparing to send checkin request
08-25 20:54:25.459  1809  7323 I EventLogService: Accumulating logs since 1472151118377
08-25 20:54:25.460  1027  7299 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 20:54:25.460  1027  7299 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 20:54:25.460  1027  7299 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 20:54:25.460  7300  7300 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 20:54:25.459  7327  7327 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:25.459  7327  7327 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:25.462  7300  7300 D WeatherAncestor: connectivity changed - connection : true
08-25 20:54:25.463  7300  7300 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-25 20:54:25.467   312  7320 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 20:54:25.467  7327  7327 I dhcpcd  : version 5.5.6 starting
,08-25 20:54:25.468  7327  7327 E dhcpcd  : get_duid: m
08-25 20:54:25.468  7327  7327 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 20:54:25.468  7327  7327 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 20:54:25.471  7300  7300 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 20:54:25.471  7300  7300 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 20:54:25.472  7300  7300 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-25 20:54:25.491  7300  7300 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-25 20:54:25.491  7300  7300 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:25
08-25 20:54:25.509   312  7320 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 20:54:25.526  1027  1931 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7336 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 20:54:25.526  1027  1931 I ActivityManager: Killing 2144:com.lge.music/u0a34 (adj 15): empty #17
,08-25 20:54:25.538  7327  7327 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 20:54:25.539  7327  7327 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 20:54:25.539  7327  7327 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 20:54:25.539  7327  7327 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 20:54:25.539  7327  7327 D dhcpcd  : wlan0: sending REQUEST (xid 0x107fcf9e), next in 3.22 seconds
08-25 20:54:25.540   316  1385 V AudioFlinger: 2144 died, releasing its sessions
08-25 20:54:25.540   316  1385 V AudioFlinger:  pid 1845 @ 0
08-25 20:54:25.540   316  1385 V AudioFlinger:  pid 3313 @ 1
08-25 20:54:25.540   316  1385 V AudioFlinger:  pid 3313 @ 2
08-25 20:54:25.545   312   884 D LGDataListener: argv[0]=dsqncommand
08-25 20:54:25.545   312   884 D LGDataListener: argv[1]=wlan0
08-25 20:54:25.545   312   884 D LGDataListener: argv[2]=1
08-25 20:54:25.545   312   884 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 20:54:25.546  1027  1112 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 20:54:25.546  1027  1112 D DSQN    : start to monitor internet connection
,08-25 20:54:25.562  1809  7323 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-25 20:54:25.562  1027  2024 W libprocessgroup: failed to open /acct/uid_10034/pid_2144/cgroup.procs: No such file or directory
08-25 20:54:25.573  7327  7327 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 20:54:25.583  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 18:54:25 GMT], X-Android-Received-Millis=[1472151265583], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472151265544]}
08-25 20:54:25.583  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 20:54:25.583  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 20:54:25.584  1027  1535 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 20:54:25.584  1027  1535 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 20:54:25.584  1027  1535 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:25.584  1027  1535 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:25.584  1027  1535 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 20:54:25.584  1027  1535 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 20:54:25.584  1027  1535 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 20:54:25.584  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.584  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:25.585  1027  1535 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:25.585  1027  1535 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.585  1593  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 20:54:25.585  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 20:54:25.586  1027  1477 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.586  1027  1477 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:25.586  1845  1845 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:25.587  1845  1845 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 20:54:25.590  7327  7327 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 20:54:25.590  7327  7327 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-25 20:54:25.590  7327  7327 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 20:54:25.590  7327  7327 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 20:54:25.591  7327  7327 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 20:54:25.591  7327  7327 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 20:54:25.591  7327  7327 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 20:54:25.591  7327  7327 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-25 20:54:25.616  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:25.617  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:25.620  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:25.676   278   463 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 20:54:25.676   278   463 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 20:54:25.676   278   463 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 20:54:25.677  7336  7363 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 20:54:25.681   278   463 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 20:54:25.681   278   463 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 20:54:25.681   278   463 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 20:54:25.681  7336  7363 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 20:54:25.698   278   463 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 20:54:25.698   278   463 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 20:54:25.698   278   463 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 20:54:25.699  7336  7366 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-25 20:54:25.702   278   463 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 20:54:25.702   278   463 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 20:54:25.702   278   463 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 20:54:25.703  7336  7366 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 20:54:25.722  1027  2005 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7372 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 20:54:25.773  7372  7372 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 20:54:25.774  7372  7372 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 20:54:25.793  7372  7372 I MultiDex: VM with version 2.1.0 has multidex support
08-25 20:54:25.793  7372  7372 I MultiDex: install
08-25 20:54:25.793  7372  7372 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 20:54:25.804  7372  7372 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-25 20:54:25.868  1027  7299 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-25 20:54:25.870  1027  7299 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 20:54:25.871  1027  7299 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 20:54:25.871  1027  7299 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 20:54:25.871  1027  7299 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 20:54:25.871  1027  7299 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 20:54:25.871  1027  7299 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 20:54:25.871  1027  7299 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 20:54:25.871  1027  7299 D DhcpStateMachine: RunningState
,08-25 20:54:25.944  7336  7336 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 20:54:25.953  7336  7336 I LibraryLoader: Loading: webviewchromium
,08-25 20:54:25.956  7336  7336 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4242-4245)
08-25 20:54:25.956  7336  7336 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 20:54:25.966  7336  7336 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {185bb502}
,08-25 20:54:25.968  7336  7336 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 20:54:25.968  7336  7336 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 20:54:25.979  7336  7336 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 20:54:25.980  7336  7336 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 20:54:26.000  7336  7336 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 20:54:26.004   316  1384 V AudioPolicyService: registerClient() client 0xb0010580, uid 10093
08-25 20:54:26.005  7336  7336 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 20:54:26.006  7336  7418 W AudioManagerAndroid: Requires BLUETOOTH permission
08-25 20:54:26.006  7336  7336 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 20:54:26.041  7336  7336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 20:54:26.041  7336  7336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 20:54:26.041  7336  7336 I Adreno-EGL: Build Date: 12/12/14 금
08-25 20:54:26.041  7336  7336 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 20:54:26.041  7336  7336 I Adreno-EGL: Remote Branch: 
08-25 20:54:26.041  7336  7336 I Adreno-EGL: Local Patches: 
08-25 20:54:26.041  7336  7336 I Adreno-EGL: Reconstruct Branch: 
,08-25 20:54:26.130  7336  7336 I NSApplication: Starting up...
,08-25 20:54:26.195  1027  1042 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7434 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 20:54:26.201  1027  1042 I ActivityManager: Killing 6520:com.android.vending/u0a44 (adj 15): empty #17
08-25 20:54:26.271  1027  1968 W libprocessgroup: failed to open /acct/uid_10044/pid_6520/cgroup.procs: No such file or directory
,08-25 20:54:26.291  7434  7434 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 20:54:26.295  7372  7391 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:26.295  7372  7391 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 20:54:26.393  1027  1969 D WifiServiceImplEx: setWifiEnabled: false pid=6854, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 20:54:26.393  1027  1969 D WifiService: setWifiEnabled: false pid=6854, uid=10118
08-25 20:54:26.393  1027  1969 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 20:54:26.405  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 20:54:26.406  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:26.406  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 20:54:26.407  1027  1477 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:26.407  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:26.407  1027  1477 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:26.408  1027  1477 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:26.408  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 20:54:26.408  1027  1477 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 20:54:26.408  1027  1477 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 20:54:26.408  1027  1477 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 20:54:26.409  1027  1477 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 20:54:26.409  1027  1477 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 20:54:26.417  1027  1477 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 20:54:26.417  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 20:54:26.417  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.417  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 20:54:26.417  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.417  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 20:54:26.417  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:26.418  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:26.418  1027  7299 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.418   312   885 D CommandListener: Clearing all IP addresses on wlan0
,08-25 20:54:26.426  1027  1535 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-25 20:54:26.437  7453  7453 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 20:54:26.461  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 20:54:26.461  1027  1535 D ConnectivityService: ignoring duplicate network state non-change
08-25 20:54:26.461  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-25 20:54:26.463  1027  1027 D WifiHS20: hidePasspointNotification off =false
,08-25 20:54:26.464  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:26.464  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:26.464  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:26.464  1933  1933 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 20:54:26.465  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:26.465  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:26.466  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:26.468  1027  1477 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:26.468  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:26.468  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:26.469  1027  1477 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:26.469  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:26.469  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:26.469  1027  1477 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 20:54:26.470  1027  1428 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.470  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.470  1027  1428 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@649b541
08-25 20:54:26.470  1027  1428 D LGWifiP2pService: P2pDisablingState
08-25 20:54:26.470  1027  1428 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.470  1027  1428 D LGWifiP2pService: p2p socket connection lost
08-25 20:54:26.470  1027  1428 D LGWifiP2pService: P2pDisabledState
,08-25 20:54:26.473  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 20:54:26.473  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:26.473  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:26.473  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:26.473  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 20:54:26.473  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-25 20:54:26.473  1027  1548 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.474  1027  1549 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.478  1027  1477 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 20:54:26.478  1027  1428 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.478  1027  1428 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.478  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 20:54:26.478  1933  1933 D WfdsService: WifiP2pState is changed : false
08-25 20:54:26.478  1933  2293 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 20:54:26.478  1933  2293 D WfdsService: Set the WFDS Monitor: false
08-25 20:54:26.479  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 20:54:26.479  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 20:54:26.479  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 20:54:26.479  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:26.480  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:26.480  1933  2293 D WfdsMonitor: WFDS Monitor is stopped
08-25 20:54:26.480  1933  2293 D WfdsService: STATE : WfdsDisabledState - enter
08-25 20:54:26.481  1933  2296 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-25 20:54:26.482  1933  7221 D CtrlSupplicant: Received on exit socket, terminate
08-25 20:54:26.482  1933  7221 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 20:54:26.483  1933  7221 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 20:54:26.483  1933  7221 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 20:54:26.483  1933  2293 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 20:54:26.489  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:26.490  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:26.511  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:26.516  7453  7453 I dex2oat : dex2oat took 79.184ms (threads: 4)
,08-25 20:54:26.529  7372  7391 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 20:54:26.529  7372  7391 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 20:54:26.529  7372  7391 I Adreno-EGL: Build Date: 12/12/14 금
08-25 20:54:26.529  7372  7391 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 20:54:26.529  7372  7391 I Adreno-EGL: Remote Branch: 
08-25 20:54:26.529  7372  7391 I Adreno-EGL: Local Patches: 
08-25 20:54:26.529  7372  7391 I Adreno-EGL: Reconstruct Branch: 
08-25 20:54:26.541   312   885 D CommandListener: Clearing all IP addresses on wlan0
08-25 20:54:26.541  1027  1535 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 20:54:26.541  1027  1535 D DSQN    : disableDataServiceNotify
08-25 20:54:26.541  1027  1535 D DSQN    : stop dsqn bin
,08-25 20:54:26.542  1027  1477 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 20:54:26.543  1027  1477 D WifiNative-p2p0: TERMINATE: returned true
08-25 20:54:26.543  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:26.543  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:26.543  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:26.544  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 20:54:26.545  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 20:54:26.545  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:26.545  1027  1535 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 20:54:26.546  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:26.546  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:26.546  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:26.546  1027  1535 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:26.546  1027  1535 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 20:54:26.546  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.546  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:26.546  1027  7297 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 20:54:26.547  1027  1535 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 20:54:26.547  1027  1535 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 20:54:26.547  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 20:54:26.547  1593  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 20:54:26.549  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:26.549  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:26.549  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:26.551  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 20:54:26.553  1027  1535 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:26.553  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_,ACTION [0]
08-25 20:54:26.553  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 20:54:26.553  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:26.553  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-25 20:54:26.555  1027  1535 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:26.555  1027  1535 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:26.555  1027  1535 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:26.555  1027  1426 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 20:54:26.556  1027  1535 D NetworkManagementService: Removing idletimer
08-25 20:54:26.556  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 20:54:26.556  1027  1535 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:26.556  1027  1477 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:26.556  1027  1477 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:26.556  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 20:54:26.556  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 20:54:26.556  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 20:54:26.557  1845  1845 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:26.557  1845  1845 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 20:54:26.557  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 20:54:26.557  1027  1426 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 20:54:26.558  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 20:54:26.558  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 20:54:26.558  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 20:54:26.560  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:26.560  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:26.560  6854  6854 W org.thaliproject.p2p.btconnectorlib.i,nternal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:26.560  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:26.561  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:26.561  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:26.561  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:26.561  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:26.567  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:26.595  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:26.597  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:26.597  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:26.614  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:26.615  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:26.616  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:26.627  1027  7299 D DhcpStateMachine: StoppedState
08-25 20:54:26.627  1027  7299 D DhcpStateMachine: StoppedState{ when=-148ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 20:54:26.628  1027  1477 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 20:54:26.628  1027  1477 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 20:54:26.635  7372  7391 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 20:54:26.635  7372  7391 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 20:54:26.635  7372  7391 I Adreno-EGL: Build Date: 12/12/14 금
08-25 20:54:26.635  7372  7391 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 20:54:26.635  7372  7391 I Adreno-EGL: Remote Branch: 
08-25 20:54:26.635  7372  7391 I Adreno-EGL: Local Patches: 
08-25 20:54:26.635  7372  7391 I Adreno-EGL: Reconstruct Branch: 
08-25 20:54:26.637  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 20:54:26.637  7210  7210 I wpa_supplicant: monitor socket send errors count : 1
08-25 20:54:26.637  7210  7210 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1933-4\x00 that cannot receive messages
08-25 20:54:26.638  1027  7220 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 20:54:26.638  1027  7220 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 20:54:26.663  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 20:54:26.665  6392  6994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 20:54:26.675  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:26.677  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 20:54:26.677  7210  7210 W wpa_supplicant: USIM:  scard_deinit function
08-25 20:54:26.678  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 20:54:26.678  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 20:54:26.678  1027  7220 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 20:54:26.678  1027  7220 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 20:54:26.678  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:26.678  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:26.678  1027  1115 D Tethering: InitialState.processMessage what=4
08-25 20:54:26.679  1027  1477 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194960
08-25 20:54:26.680  1027  1477 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194960
08-25 20:54:26.681  1027  1477 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=194961  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 20:54:26.681  1027  1477 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=194962  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 20:54:26.684  1027  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 20:54:26.684  1027  1477 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:26.684  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:26.687  7372  7391 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 20:54:26.687  7372  7391 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 20:54:26.687  7372  7391 I Adreno-EGL: Build Date: 12/12/14 금
08-25 20:54:26.687  7372  7391 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 20:54:26.687  7372  7391 I Adreno-EGL: Remote Branch: 
08-25 20:54:26.687  7372  7391 I Adreno-EGL: Local Patches: 
08-25 20:54:26.687  7372  7391 I Adreno-EGL: Reconstruct Branch: 
,08-25 20:54:26.694  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 20:54:26.694  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:26.694  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 20:54:26.694  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 20:54:26.696  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-25 20:54:26.698  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1548ccab
08-25 20:54:26.698  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 20:54:26.698  7156  7156 D AppUp4:CustFacade: isPhone : true
08-25 20:54:26.699  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-25 20:54:26.699  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 20:54:26.702  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:26.702  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 20:54:26.704  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 20:54:26.708  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:26.717  4812  7483 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:26.717  4812  7483 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 20:54:26.717  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 20:54:26.717  4812  7482 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 20:54:26.733  7184  7485 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 20:54:26.736  3313  3313 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 20:54:26.736  3313  3313 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:26.736  3313  3313 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 20:54:26.739  7226  7226 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 20:54:26.740  7226  7226 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 20:54:26.745  7064  7486 W FormManager: Network not available. Please check & try again.
08-25 20:54:26.746  7064  7488 V FormManager: Network unavailable.
,08-25 20:54:26.748  7064  7488 V FormManager: Network unavailable.
08-25 20:54:26.757  7300  7300 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:26
08-25 20:54:26.760  7300  7300 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 20:54:26.760  7300  7300 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 20:54:26.762  7300  7300 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 20:54:26.762  7300  7300 D WeatherAncestor: connectivity changed - connection : true
08-25 20:54:26.763  7300  7300 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@340ce6a1
08-25 20:54:26.764  7300  7300 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 20:54:26.764  7300  7300 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 20:54:26.764  7300  7300 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 20:54:26.764  7300  7300 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 20:54:26.764  7300  7300 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:26
08-25 20:54:26.788  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-25 20:54:26.788  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 20:54:26.789  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 20:54:26.789  6972  6972 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 20:54:26.789  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 20:54:26.791  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 20:54:26.791  1027  7220 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 20:54:26.791  1027  7220 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 20:54:26.791  6972  6972 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 20:54:26.791  1027  7220 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 20:54:26.791  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 20:54:26.791  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 20:54:26.791  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 20:54:26.791  6972  6972 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 20:54:26.791  1027  1477 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-25 20:54:26.791  6972  6972 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 20:54:26.797  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:26.799  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 20:54:26.800   312  7493 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 20:54:26.801  1027  1112 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-25 20:54:26.804  7064  7490 W FormManager: Network not available. Please check & try again.
08-25 20:54:26.804  1809  7323 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-25 20:54:26.809  7064  7491 V FormManager: Network unavailable.
08-25 20:54:26.812  7064  7491 V FormManager: Network unavailable.
08-25 20:54:26.814  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:26.818  1809  7323 I CheckinService: active receiver: disabled
,08-25 20:54:26.843  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:26.846  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 20:54:26.848  7064  7495 W FormManager: Network not available. Please check & try again.
,08-25 20:54:26.855  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:26.855  7064  7496 V FormManager: Network unavailable.
08-25 20:54:26.859  7064  7496 V FormManager: Network unavailable.
,08-25 20:54:26.867  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 20:54:26.867  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 20:54:26.869  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:26.871  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 20:54:26.875  4812  7497 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:26.880  4812  7498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 20:54:26.880  4812  7498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 20:54:26.921  1027  1968 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7499 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 20:54:26.923  1027  1477 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 20:54:26.923  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:26.923  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:26.923  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:26.927  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 20:54:26.927  1027  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 20:54:26.927  1027  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 20:54:26.927  1933  1933 D WfdsService: Supplicant Connection state is changed : false
08-25 20:54:26.927  1933  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-25 20:54:26.927  1933  2293 D WfdsService: Set the WFDS Monitor: false
08-25 20:54:26.927  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 20:54:26.927  1933  2293 D WfdsMonitor: WFDS Monitor is stopped
08-25 20:54:26.929  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:26.929  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:26.929  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:26.930  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:26.931  2500  2500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 20:54:27.042  7499  7499 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 20:54:27.043  7499  7499 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 20:54:27.056  7499  7499 V [BNRBootReceiver]: Boot Receiver Return
,08-25 20:54:27.057  7499  7499 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 20:54:27.062  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:27.076  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.089  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 20:54:27.123  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.124  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.131  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:27.133  1027  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=317573030, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
08-25 20:54:27.142  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:27.155  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.166  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.186  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:27.191  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:27.193  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:27.200  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 20:54:27.203  2582  2582 D [Concierge]Service: onStartCommand(). Type : 9
08-25 20:54:27.209  6972  6972 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 20:54:27.220  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:27.233  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.244  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.252  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.252  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.253  7026  7026 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:27.258  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.268  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.275  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.283  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.284  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.284  7026  7026 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:27.288  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.295  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.303  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.311  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.311  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:27.311  7026  7026 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 20:54:27.316  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.322  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.331  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.341  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.341  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.342  7026  7026 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:27.348  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.356  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.366  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.377  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:27.378  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:27.379  7026  7026 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:27.390  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:27.405  6768  7134 D UEI.SmartControl: Internal timer expired: 2
,08-25 20:54:27.405  6768  7134 D UEI.SmartControl: unbind internal service
08-25 20:54:27.415  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.427  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.441  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:27.442  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.450  7026  7026 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:27.460  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:27.476  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.492  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 20:54:27.506  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.506  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.508  7026  7026 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:27.512  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.515  6768  7128 D serial_port: close(fd = 24)
08-25 20:54:27.519  6768  7128 I UEI.SmartControl: Serial port is closed.
08-25 20:54:27.519  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 20:54:27.533  1027  1533 D WifiService: New client listening to asynchronous messages
,08-25 20:54:27.535  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:27.538  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.546  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.556  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.557  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.558  7026  7026 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 20:54:27.559  7026  7026 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 20:54:27.560  7026  7026 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 20:54:27.566  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.573  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 20:54:27.577  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:27.583  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.596  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.610  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:27.610  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:27.612  7026  7026 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 20:54:27.613  7026  7026 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 20:54:27.614  7026  7026 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 20:54:27.619  1027  2024 I ActivityManager: Killing 6954:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-25 20:54:27.680  1027  1043 W libprocessgroup: failed to open /acct/uid_10037/pid_6954/cgroup.procs: No such file or directory
,08-25 20:54:27.685  2185  2185 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 20:54:27.705  2185  2185 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-25 20:54:27.706  2185  2185 D c       : Getting all permits...
08-25 20:54:27.707  2185  2185 D a       : Opening database...
08-25 20:54:27.720  2185  2185 D a       : Opening database auth.proximity.permit_store...
,08-25 20:54:27.722  2185  2185 D a       : Closing database...
08-25 20:54:27.742  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:27.748  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 20:54:27.748  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 20:54:27.748  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:27.753  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 20:54:27.762  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 20:54:27.775  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.776  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.778  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:27.788  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.796  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 20:54:27.796  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 20:54:27.796  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 20:54:27.804  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.812  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.822  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.822  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:27.824  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 20:54:27.830  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:27.836  6995  6995 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 20:54:27.836  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 20:54:27.836  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 20:54:27.841  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:27.851  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.863  7026  7026 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:27.864  7026  7026 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 20:54:27.866  7026  7026 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:27.881  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 20:54:27.887  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 20:54:27.893  7064  7525 W FormManager: Network not available. Please check & try again.
,08-25 20:54:27.902  7064  7526 V FormManager: Network unavailable.
08-25 20:54:27.905  7064  7526 V FormManager: Network unavailable.
,08-25 20:54:27.907  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.930  2185  2185 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-25 20:54:27.946  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 20:54:27.946  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 20:54:27.948  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:27.951  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:27.960  6995  6995 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 20:54:27.961  6995  6995 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 20:54:27.961  6995  6995 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 20:54:27.963  4812  7527 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:27.966  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 20:54:27.975  4812  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 20:54:27.975  4812  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 20:54:27.980  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:27.988  7064  7530 W FormManager: Network not available. Please check & try again.
08-25 20:54:27.999  7064  7531 V FormManager: Network unavailable.
,08-25 20:54:28.001  7026  7026 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-25 20:54:28.002  7026  7026 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1559
08-25 20:54:28.004  7064  7531 V FormManager: Network unavailable.
08-25 20:54:28.005  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=317573030 [*alarm*], flags=0x0
08-25 20:54:28.264  1027  1477 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3013] from screen [on:0 period:-1022514264] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 20:54:28.265  1027  1477 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1022514263] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 20:54:28.418  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:28.435  1027  1115 D Tethering: MasterInitialState.processMessage what=3
08-25 20:54:28.440  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:28.444  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:28.449  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:28.451  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 20:54:28.453  6392  6994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 20:54:28.467  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 20:54:28.491  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:28.511  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 20:54:28.511  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:28.511  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 20:54:28.512  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 20:54:28.517  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-25 20:54:28.520  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1548ccab
08-25 20:54:28.521  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 20:54:28.521  7156  7156 D AppUp4:CustFacade: isPhone : true
08-25 20:54:28.521  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-25 20:54:28.521  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 20:54:28.526  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:28.526  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 20:54:28.528  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 20:54:28.534  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:28.542  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 20:54:28.575  3313  3313 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-25 20:54:28.575  3313  3313 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:28.576  3313  3313 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 20:54:28.576  3313  3313 D PhoneState: setPdpRejectCasuse : false
,08-25 20:54:28.585  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:28.591  7226  7226 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 20:54:28.591  7226  7226 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 20:54:28.592  4812  7540 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:28.595  7184  7539 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 20:54:28.598  4812  7556 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:28.599  4812  7556 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 20:54:28.606  7300  7300 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:28
08-25 20:54:28.608  7300  7300 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 20:54:28.608  7300  7300 D Weather.Utils: 2 : All the weather widget is gone.
08-25 20:54:28.609  7300  7300 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 20:54:28.610  7300  7300 D WeatherAncestor: connectivity changed - connection : true
08-25 20:54:28.610  7300  7300 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@340ce6a1
08-25 20:54:28.611  7300  7300 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 20:54:28.611  7300  7300 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 20:54:28.611  7300  7300 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-25 20:54:28.612  7300  7300 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-25 20:54:28.612  7300  7300 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:28
08-25 20:54:28.613  7064  7557 W FormManager: Network not available. Please check & try again.
08-25 20:54:28.616  7064  7558 V FormManager: Network unavailable.
08-25 20:54:28.621  7064  7558 V FormManager: Network unavailable.
08-25 20:54:29.413  1027  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 20:54:29.424  1027  1768 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 20:54:29.457  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 20:54:29.458  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:29.458  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 20:54:29.458  1027  1115 D BluetoothManagerService: Message: 1
08-25 20:54:29.458  1027  1115 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 20:54:29.485  1027  1115 D BluetoothManagerService: Message: 20
08-25 20:54:29.485  1027  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29d2b68a:true
,08-25 20:54:29.489   308   308 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-25 20:54:29.489   308   308 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-25 20:54:29.489   308   308 I rmt_storage: wakelock acquired: 1, error no: 42
08-25 20:54:29.489   308   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
08-25 20:54:29.501  7093  7093 D BluetoothAdapterState: make
,08-25 20:54:29.508  7093  7093 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 20:54:29.508  7093  7093 I bluedroid-qcom: init
08-25 20:54:29.518  7093  7571 I BluetoothAdapterState: Entering OffState
,08-25 20:54:29.519  7093  7093 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 20:54:29.520  7093  7093 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 20:54:29.520  7093  7093 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 20:54:29.520  7093  7093 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 20:54:29.520  7093  7093 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 20:54:29.539  7574  7574 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 20:54:29.539  7574  7574 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:29.551  7574  7574 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 20:54:29.551  7574  7574 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 20:54:29.551  7574  7574 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 20:54:29.552  7093  7093 I bluedroid-qcom: get_profile_interface socket
08-25 20:54:29.552  7093  7093 I bluedroid-qcom: get_profile_interface map_client
08-25 20:54:29.555  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:29.558  7574  7574 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 20:54:29.563  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.563  1027  1115 D Tethering: MasterInitialState.processMessage what=3
08-25 20:54:29.564  7574  7574 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 20:54:29.564  7574  7574 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 20:54:29.572  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:29.571  7093  7575 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-25 20:54:29.592  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:29.597  1027  1115 D Tethering: MasterInitialState.processMessage what=3
08-25 20:54:29.598  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:29.602  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 20:54:29.602  7093  7575 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 20:54:29.603  6392  6994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 20:54:29.609  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.609  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:29.610  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 20:54:29.611  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:29.611  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 20:54:29.612  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:29.614  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 20:54:29.614  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 20:54:29.616  7093  7575 D BluetoothAdapterProperties: Name is: G3
08-25 20:54:29.618  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 20:54:29.618  1027  1115 D BluetoothManagerService: Message: 40
08-25 20:54:29.618  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 20:54:29.619  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 20:54:29.619  7093  7109 I bluedroid-qcom: config_hci_snoop_log
08-25 20:54:29.621  1027  1115 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 20:54:29.621  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-25 20:54:29.626  7093  7571 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 20:54:29.626  7093  7571 D BluetoothAdapterProperties: Setting state to 11
08-25 20:54:29.626  7093  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 20:54:29.627  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:29.627  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 20:54:29.627  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 20:54:29.627  7093  7571 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 20:54:29.629  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 20:54:29.632  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:29.632  7093  7571 D BluetoothBondStateMachine: make
08-25 20:54:29.632  6972  6972 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 20:54:29.633  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:29.635  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 20:54:29.636  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:29.636  7093  7093 V BluetoothPbapReceiver: ***********state = 11
08-25 20:54:29.638  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:29.638  7093  7571 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.638  7093  7571 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 20:54:29.638  7093  7571 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.639  7093  7571 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 20:54:29.639  7093  7571 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 20:54:29.639  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:29.646  7093  7571 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 20:54:29.648  7093  7593 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 20:54:29.664  1027  1932 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7595 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 20:54:29.669  7093  7571 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:29.669  7093  7093 D HeadsetService: Received start request. Starting profile...
08-25 20:54:29.669  7093  7093 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 20:54:29.669  7093  7093 D LGBluetoothHfpAdapter: Version 1.6
08-25 20:54:29.672  7093  7093 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 20:54:29.672  7093  7093 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 20:54:29.673  7093  7093 D HeadsetStateMachine: make
08-25 20:54:29.676  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.677  7093  7571 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:29.684  7093  7571 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 20:54:29.687  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 20:54:29.687  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.688  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 20:54:29.688  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 20:54:29.690  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-25 20:54:29.692  7093  7571 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:29.697  7093  7571 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 20:54:29.698  7093  7093 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:29.698  7093  7093 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 20:54:29.705  7093  7093 D HeadsetStateMachine: max_hf_connections = 1
08-25 20:54:29.706  7093  7093 I bluedroid-qcom: get_profile_interface handsfree
08-25 20:54:29.706  7093  7571 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:29.707  7093  7093 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 20:54:29.707   316  1385 V AudioPolicyService: registerClient() client 0xb558af20, uid 1002
08-25 20:54:29.708  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1548ccab
08-25 20:54:29.708  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 20:54:29.708  7156  7156 D AppUp4:CustFacade: isPhone : true
08-25 20:54:29.708   316  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 20:54:29.708   316  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 20:54:29.708   316  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 20:54:29.708  7093  7093 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 20:54:29.709  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
,08-25 20:54:29.709  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-25 20:54:29.711   316   316 V AudioFlinger: registerClient() client 0xb57c03e8, pid 7093
08-25 20:54:29.711   316  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:29.711  7093  7093 V ToneGenerator: Create Track: 0xb4928a80
08-25 20:54:29.711  7093  7093 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 20:54:29.711  7093  7093 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 20:54:29.711   316  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:29.711  1027  1969 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:29.712  3313  3328 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:29.712  1027  1969 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:29.712  3313  3328 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:29.712   316  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:29.712   316  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:29.712  3313  3329 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:29.712  3313  3329 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:29.712   316  2159 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 20:54:29.712   316  2159 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 20:54:29.712   316  2159 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-25 20:54:29.712   316  2159 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 20:54:29.712  7093  7093 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 20:54:29.712  7093  7594 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:29.712  7093  7594 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 20:54:29.712  1593  2093 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:29.712  1593  2093 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:29.712  7093  7594 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:29.712  7093  7594 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 20:54:29.712  1593  2093 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:29.712  1593  2093 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:29.712  1027  1042 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:29.712  1845  2624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:29.712  1027  1042 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:29.712  1845  2624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:29.712  1845  2624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:29.712  1845  2624 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:29.713   316  2159 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 20:54:29.713   316  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 20:54:29.713   316  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 20:54:29.713   316  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 20:54:29.713   316  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 20:54:29.713  7093  7093 V AudioSystem: getLatency() output 2, latency 50
08-25 20:54:29.713  7093  7093 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 20:54:29.713  7093  7093 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 20:54:29.713   316  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 20:54:29.713   316  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 20:54:29.713   316  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 20:54:29.713   316  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 20:54:29.713   316  1384 V AudioFlinger: createTrack() lSessionId: 22
08-25 20:54:29.714  7093  7093 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 20:54:29.714   316  2159 V AudioFlinger: acquiring 22 from 7093, for 7093
08-25 20:54:29.714   316  2159 V AudioFlinger:  added new entry for 22
08-25 20:54:29.714  7093  7093 V ToneGenerator: ToneGenerator INIT OK, time: 198004
08-25 20:54:29.714  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.714  7093  7606 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 20:54:29.715  7093  7606 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 20:54:29.715  7093  7606 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 20:54:29.715  7093  7606 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 20:54:29.715   316  1385 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7093
08-25 20:54:29.715   316  1385 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 20:54:29.715   316  1385 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25, 20:54:29.715   316  1385 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 20:54:29.715   316  1385 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 20:54:29.715   316  1385 V voice   : voice_set_parameters: exit with code(0)
08-25 20:54:29.715   316  1385 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 20:54:29.715   316  1385 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 20:54:29.715   316  1385 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 20:54:29.715   316  1385 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 20:54:29.715   316  1385 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 20:54:29.715   316  1385 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 20:54:29.716  7093  7606 V ToneGenerator: ToneGenerator destructor
08-25 20:54:29.716  7093  7606 V ToneGenerator: stopTone
08-25 20:54:29.716  7093  7606 V ToneGenerator: Delete Track: 0xb4928a80
08-25 20:54:29.716  7093  7606 V AudioTrack: ~AudioTrack, releasing session id from 7093 on behalf of 7093
08-25 20:54:29.716   316  1384 V AudioFlinger: releasing 22 from 7093 for 7093
08-25 20:54:29.716   316  1384 V AudioFlinger:  decremented refcount to 0
08-25 20:54:29.716   316  1384 V AudioFlinger: purging stale effects
08-25 20:54:29.716   316  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 20:54:29.716   316  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 20:54:29.716   316  1263 V AudioPolicyService: AudioCommandThread() waking up
08-25 20:54:29.716   316  1263 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 20:54:29.716   316  1263 V AudioPolicyManager: releaseOutput() 2
08-25 20:54:29.716   316  1263 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 20:54:29.716   316  1384 V AudioFlinger: PlaybackThread::Track destructor
08-25 20:54:29.716   316  1384 V AudioFlinger: removeClient_l() pid 7093, calling pid 316
08-25 20:54:29.717  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.718  7093  7093 D A2dpService: Received start request. Starting profile...
08-25 20:54:29.718  7093  7093 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 20:54:29.719  7093  7093 V Avrcp   : make
08-25 20:54:29.719  7093  7093 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 20:54:29.719  7093  7093 I bluedroid-qcom: get_profile_interface avrcp
08-25 20:54:29.720  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.720  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 20:54:29.722  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:29.722  1027  1950 W Process : Unable to open /proc/7614/status
08-25 20:54:29.728  7093  7571 V LGMDMManager: Create singleton instance
08-25 20:54:29.729  7093  7571 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 20:54:29.731  7093  7093 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 20:54:29.733  7093  7093 E AudioManager: No RCC entry present to update
08-25 20:54:29.733  7093  7093 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 20:54:29.733   308   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
08-25 20:54:29.733   308   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-25 20:54:29.733   308   903 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-25 20:54:29.733   308   903 I rmt_storage: 
,08-25 20:54:29.735  7093  7093 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 20:54:29.736  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 20:54:29.736  7093  7093 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 20:54:29.736   308   308 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-25 20:54:29.736   892   901 E Diag_Lib: [IMS_FATAL]| 3347 | 901 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-25 20:54:29.737  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 20:54:29.741  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 20:54:29.744  4812  7617 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:29.746  4812  7618 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.746  4812  7618 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 20:54:29.784  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 20:54:29.833  1027  1042 V SIM_STK : Menu title from STK is T-Mobile
08-25 20:54:29.833  1027  1042 V SIM_STK : Menu title from STK is T-Mobile
,08-25 20:54:29.908  1027  1768 I art     : Explicit concurrent mark sweep GC freed 117170(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.528ms total 114.741ms
,08-25 20:54:29.910  1027  1896 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 20:54:29.923  3313  3313 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 20:54:29.923  3313  3313 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-25 20:54:29.923  3313  3313 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 20:54:29.925  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 20:54:29.927  7226  7226 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 20:54:29.927  7064  7622 W FormManager: Network not available. Please check & try again.
08-25 20:54:29.927  7226  7226 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 20:54:29.927  7595  7595 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 20:54:29.927  7595  7595 W LG Account v2.2: No ProfileInfo entries
08-25 20:54:29.928  7595  7595 I LG Account v2.2: isEnabled: false
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Country: EU
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Operator: OPEN
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Ranking support: false
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Comfort support: false
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Accessory: true
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Health device: true
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Extra Pedometer: false
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Blood glucose device: false
08-25 20:54:29.928  7064  7623 V FormManager: Network unavailable.
08-25 20:54:29.928  7595  7595 I Feature : [Lifetracker]Device Number: 3
08-25 20:54:29.929  7184  7624 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:29.930  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 20:54:29.931  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 20:54:29.931  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 20:54:29.931  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 20:54:29.931  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 20:54:29.931  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 20:54:29.931  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 20:54:29.931  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 20:54:29.932  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 20:54:29.932  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 20:54:29.932  7064  7623 V FormManager: Network unavailable.
08-25 20:54:29.932  7093  7093 I BluetoothA2dpServiceJni: classInitNative
08-25 20:54:29.932  7093  7093 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 20:54:29.932  7093  7093 D A2dpStateMachine: make
08-25 20:54:29.933  7093  7093 I bluedroid-qcom: get_profile_interface a2dp
08-25 20:54:29.934  7093  7628 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 20:54:29.937  7093  7093 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 20:54:29.937  7093  7093 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 20:54:29.937  6972  6972 D BluetoothPermissionRequest: onReceive
08-25 20:54:29.939  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.939  7093  7627 D A2dpStateMachine: Enter Disconnected: -2
08-25 20:54:29.939  7093  7093 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 20:54:29.940  7093  7093 D HidService: Received start request. Starting profile...
08-25 20:54:29.941  7093  7093 I bluedroid-qcom: get_profile_interface hidhost
08-25 20:54:29.941  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.941  7093  7093 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 20:54:29.942  7093  7093 D HealthService: Received start request. Starting profile...
08-25 20:54:29.942  7300  7300 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:29
08-25 20:54:29.943  7093  7093 I bluedroid-qcom: get_profile_interface health
08-25 20:54:29.943  7093  7093 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 20:54:29.943  7300  7300 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 20:54:29.943  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.943  7300  7300 D Weather.Utils: 2 : All the weather widget is gone.
08-25 20:54:29.944  7300  7300 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 20:54:29.944  7093  7093 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 20:54:29.944  7300  7300 D WeatherAncestor: connectivity changed - connection : true
08-25 20:54:29.944  7300  7300 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@340ce6a1
08-25 20:54:29.945  7093  7093 D PanService: Received start request. Starting profile...
08-25 20:54:29.945  7300  7300 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 20:54:29.945  7093  7093 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 20:54:29.945  7093  7093 I bluedroid-qcom: get_profile_interface pan
08-25 20:54:29.945  7300  7300 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-25 20:54:29.945  7300  7300 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 20:54:29.945  7300  7300 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 20:54:29.945  7300  7300 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:29
08-25 20:54:29.946  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 20:54:29.950  7093  7093 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 20:54:29.950  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.951  7093  7093 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 20:54:29.954  7093  7093 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 20:54:29.954  7093  7093 D BtGatt.GattService: Received start request. Starting profile...
08-25 20:54:29.954  7093  7093 D BtGatt.GattService: start()
08-25 20:54:29.955  7093  7093 I bluedroid-qcom: get_profile_interface gatt
08-25 20:54:29.955  7093  7093 D BtGatt.AdvertiseManager: advertise manager created
08-25 20:54:29.961  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.961  7093  7093 D HeadsetStateMachine: Proxy object connected
,08-25 20:54:29.961  7093  7093 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 20:54:29.961  7093  7093 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 20:54:29.963  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:29.964  7093  7093 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 20:54:29.964  7093  7093 V BluetoothMapService: BluetoothMapBinder()
08-25 20:54:29.965  7093  7093 D BluetoothMapService: Received start request. Starting profile...
08-25 20:54:29.965  7093  7093 D BluetoothMapService: start()
08-25 20:54:29.967  7093  7093 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 20:54:29.967  7093  7093 D BluetoothMapEmailAppObserver: createReceiver()
08-25 20:54:29.968  7093  7093 D BluetoothMapEmailAppObserver: initObservers()
08-25 20:54:29.968  7093  7093 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 20:54:29.971  6392  6392 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 20:54:29.973  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
,08-25 20:54:29.975  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 20:54:29.976  7093  7606 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 20:54:29.976  6392  6994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 20:54:29.976  7093  7606 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 20:54:29.976  7093  7606 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 20:54:29.979  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 20:54:29.982  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 20:54:29.984  2185  2185 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.985  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 20:54:29.988  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 20:54:29.988  7093  7093 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 20:54:29.992  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 20:54:29.992  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:29.992  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 20:54:29.992  7156  7156 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 20:54:29.993  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 20:54:29.993  7093  7093 V BluetoothMapService: Handler(): got msg=1
08-25 20:54:29.993  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
08-25 20:54:29.994  7093  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 20:54:29.994  7093  7571 I bluedroid-qcom: enable
08-25 20:54:29.994  7093  7571 I bt_hci_bdroid: init
08-25 20:54:29.994  7093  7635 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 20:54:29.994  7093  7635 I bt-btu  : btu_task pending for preload complete event
08-25 20:54:29.995  7093  7571 I bt_vendor: bt-vendor : init
08-25 20:54:29.995  7093  7571 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 20:54:29.995  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:29.995  7093  7571 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 20:54:29.995  7093  7571 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 20:54:29.995  7093  7571 D bt_userial_mct: userial_init
08-25 20:54:29.996  7093  7571 D bt_hci_bdroid: set_power 1
08-25 20:54:29.996  7093  7571 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 20:54:29.996  7093  7571 I bt_vendor: Starting hciattach daemon
08-25 20:54:29.996  7093  7571 I bt_vendor: try to set true
08-25 20:54:29.997  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:29.997  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:29.997  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:29.997  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:29.998  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-25 20:54:29.989  7638  7638 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:29.989  7638  7638 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:30.001  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1548ccab
08-25 20:54:30.001  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 20:54:30.001  7156  7156 D AppUp4:CustFacade: isPhone : true
08-25 20:54:30.001  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-25 20:54:30.001  7156  7156 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 20:54:30.005  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:30.006  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 20:54:30.007  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:30.008  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 20:54:30.013  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 20:54:30.014  4812  7640 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:30.015  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 20:54:30.020  4812  7641 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:30.020  4812  7641 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 20:54:30.035  3313  3313 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 20:54:30.035  3313  3313 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:30.035  3313  3313 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 20:54:30.035  7184  7643 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:30.036  7064  7646 W FormManager: Network not available. Please check & try again.
,08-25 20:54:30.039  7226  7226 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 20:54:30.039  7226  7226 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 20:54:30.049  7300  7300 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:30
08-25 20:54:30.050  7300  7300 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 20:54:30.050  7300  7300 D Weather.Utils: 2 : All the weather widget is gone.
08-25 20:54:30.051  7300  7300 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 20:54:30.051  7300  7300 D WeatherAncestor: connectivity changed - connection : true
08-25 20:54:30.051  7064  7647 V FormManager: Network unavailable.
,08-25 20:54:30.051  7300  7300 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@340ce6a1
08-25 20:54:30.053  7300  7300 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 20:54:30.053  7300  7300 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 20:54:30.053  7300  7300 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 20:54:30.053  7300  7300 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 20:54:30.053  7300  7300 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:54:30
,08-25 20:54:30.057  7064  7647 V FormManager: Network unavailable.
,08-25 20:54:30.062  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-25 20:54:30.069  7653  7653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 20:54:30.091  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 20:54:30.099  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 20:54:30.107  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 20:54:30.126  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 20:54:30.152  7660  7660 I libmdmdetect: ESOC framework not supported
,08-25 20:54:30.155  7660  7660 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-25 20:54:30.166  7660  7660 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 20:54:30.166  7660  7660 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 20:54:30.166  7660  7660 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-25 20:54:30.166  7660  7660 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 20:54:30.166  7660  7660 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 20:54:30.166  7660  7660 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 20:54:30.166  7660  7660 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 20:54:30.211  7660  7661 E QC-QMI  : qmi_client [7660] 14: failed to locate client data
08-25 20:54:30.213   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 20:54:30.214   483   483 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-25 20:54:30.271  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 20:54:30.298  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 20:54:30.348  7093  7571 I bt_vendor: bluetooth satus is on
,08-25 20:54:30.348  7093  7571 D bt_hci_bdroid: preload
08-25 20:54:30.349  7093  7637 D bt_userial_mct: userial_open(port:0)
08-25 20:54:30.349  7093  7637 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 20:54:30.353  7093  7637 I bt_vendor: Done intiailizing UART
08-25 20:54:30.356  7093  7637 I bt_vendor: Done intiailizing UART
08-25 20:54:30.356  7093  7637 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 20:54:30.357  7093  7637 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 20:54:30.357  7093  7635 I bt-btu  : btu_task received preload complete event
08-25 20:54:30.358  7093  7668 D bt_userial_mct: Entering userial_read_thread()
08-25 20:54:30.358  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 20:54:30.359  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 20:54:30.362  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 20:54:30.367  7093  7635 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 20:54:30.453  7093  7635 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 20:54:30.453  7093  7635 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0215061 
08-25 20:54:30.453  7093  7635 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0215061 
,08-25 20:54:30.470  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 7586
,08-25 20:54:30.470  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 7587
08-25 20:54:30.471  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 7590
08-25 20:54:30.472  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 7591
,08-25 20:54:30.473  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 7665
08-25 20:54:30.496  7093  7575 E bt-btif : Calling BTA_HhEnable
08-25 20:54:30.496  7093  7575 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 20:54:30.497  7093  7575 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 20:54:30.497  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 20:54:30.497  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 20:54:30.497  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 20:54:30.498  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 20:54:30.498  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 20:54:30.498  7093  7575 D BluetoothAdapterProperties: Name is: G3
,08-25 20:54:30.501  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 20:54:30.502  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 20:54:30.503  7093  7575 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:54:30.504  7093  7575 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 20:54:30.504  7093  7575 D bt_hci_bdroid: postload
08-25 20:54:30.505  7093  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 20:54:30.506  7093  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 20:54:30.506  7093  7575 D bte_conf: Device ID record 1 : primary
08-25 20:54:30.506  7093  7575 D bte_conf:   vendorId            = 00c4
08-25 20:54:30.506  7093  7575 D bte_conf:   vendorIdSource      = 0001
08-25 20:54:30.507  7093  7575 D bte_conf:   product             = 13a1
08-25 20:54:30.507  7093  7575 D bte_conf:   version             = 1000
08-25 20:54:30.507  7093  7575 D bte_conf:   clientExecutableURL = 
08-25 20:54:30.507  7093  7575 D bte_conf:   serviceDescription  = 
08-25 20:54:30.507  7093  7575 D bte_conf:   documentationURL    = 
08-25 20:54:30.507  7093  7575 D bte_conf: bte_load_did_conf no section named DID2.
08-25 20:54:30.510  7093  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 20:54:30.512  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:30.512  7093  7575 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 20:54:30.512  7093  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 20:54:30.513  7093  7571 D BluetoothAdapterProperties: ScanMode =  20
,08-25 20:54:30.513  7093  7571 D BluetoothAdapterProperties: State =  11
08-25 20:54:30.513  7093  7571 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 20:54:30.509  7670  7670 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:30.509  7670  7670 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:30.513  7093  7571 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 20:54:30.513  7093  7571 D BluetoothAdapterProperties: Setting state to 12
08-25 20:54:30.513  7093  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 20:54:30.514  7093  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 20:54:30.514  7093  7637 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 20:54:30.517  7093  7575 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 20:54:30.519  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:30.519  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 20:54:30.520  7093  7571 I BluetoothAdapterState: Entering On State
08-25 20:54:30.521  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 20:54:30.521  1845  2442 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:30.523  7093  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:30.523  7093  7635 W bt-smp  : Plain text(LSB ~ MSB) = c1 af 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:30.523  7093  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = 63 e7 aa 8c 3e c7 a2 6a df 45 22 cf 01 45 7a 64 
08-25 20:54:30.523  7093  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 20:54:30.523  7093  7635 W bt-btm  : Stopping oneshot timer
08-25 20:54:30.524  7093  7668 E bt_mct  : hci lib postload completed
08-25 20:54:30.529  7093  7575 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 20:54:30.529  7093  7575 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-25 20:54:30.533  7093  7571 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 20:54:30.534  7093  7571 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 20:54:30.534  7093  7571 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 20:54:30.535  7093  7571 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:30.535  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:30.539  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 20:54:30.539  1845  1845 D BluetoothHeadset: Proxy object connected
08-25 20:54:30.539  1027  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:30.540  1845  2624 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:30.540  1027  1027 D BluetoothHeadset: Proxy object connected
08-25 20:54:30.543  7093  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:30.543  7093  7635 W bt-smp  : Plain text(LSB ~ MSB) = 9e 85 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:30.543  7093  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = 89 c7 a8 f4 dd 50 5c bc d4 4c 7a 01 05 e9 81 03 
08-25 20:54:30.543  7093  7635 W bt-btm  : Stopping oneshot timer
,08-25 20:54:30.547  1845  1845 D BluetoothHeadset: Proxy object connected
08-25 20:54:30.547  1845  1860 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:30.550  1027  1115 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 20:54:30.550  1845  1845 D BluetoothHeadset: Proxy object connected
08-25 20:54:30.551  6972  6991 D BluetoothPan: onBluetoothStateChange on: true
08-25 20:54:30.551  6972  6991 D BluetoothPan: onBluetoothStateChange call bindService
08-25 20:54:30.552  1027  1027 D BluetoothA2dp: Proxy object connected
08-25 20:54:30.558  7093  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:30.558  7093  7635 W bt-smp  : Plain text(LSB ~ MSB) = 88 a0 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:30.558  6972  6972 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 20:54:30.558  7093  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = 60 c4 e1 22 f5 fc 18 63 ed 3e 37 d3 40 36 77 6e 
08-25 20:54:30.558  6972  6972 D PanProfile: Bluetooth service connected
08-25 20:54:30.558  7093  7635 W bt-btm  : Stopping oneshot timer
,08-25 20:54:30.560  6972  6989 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 20:54:30.565  6972  6972 D BluetoothInputDevice: Proxy object connected
08-25 20:54:30.565  6972  6972 D HidProfile: Bluetooth service connected
08-25 20:54:30.565  6972  6991 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 20:54:30.567  6972  6989 D BluetoothMap: onBluetoothStateChange: up=true
08-25 20:54:30.571  7093  7571 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 20:54:30.571  7093  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:30.571  7093  7635 W bt-smp  : Plain text(LSB ~ MSB) = d8 06 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:30.571  7093  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 fc a9 19 ae 3e d7 c0 14 69 c4 61 4c 4d 9d 42 
08-25 20:54:30.571  7093  7635 W bt-btm  : Stopping oneshot timer
,08-25 20:54:30.573  1027  1115 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 20:54:30.573  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 20:54:30.576  6972  6972 D BluetoothMap: Proxy object connected
08-25 20:54:30.576  6972  6972 D MapProfile: Bluetooth service connected
08-25 20:54:30.576  6972  6972 D BluetoothMap: getConnectedDevices()
08-25 20:54:30.579  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 20:54:30.580  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.580  1933  2124 D LGBluetoothAPIService: Message: 1
08-25 20:54:30.581  1933  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 20:54:30.585  6854  6854 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:30.592  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:30.594  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:30.595  7681  7681 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 20:54:30.596  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:30.597  7093  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:30.597  7093  7635 W bt-smp  : Plain text(LSB ~ MSB) = 6a e6 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:30.597  7093  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 53 15 69 7a f0 ac 68 14 ee c8 16 ee 3e b7 69 
08-25 20:54:30.597  7093  7635 W bt-btm  : Stopping oneshot timer
08-25 20:54:30.600  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-25 20:54:30.603  7093  7594 V BluetoothMapService: getConnectedDevices()
08-25 20:54:30.605  1933  2124 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 20:54:30.607  7093  7093 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.607  7093  7093 D BluetoothMapService: STATE_ON
08-25 20:54:30.607  7093  7093 V BluetoothMapService: Handler(): got msg=1
08-25 20:54:30.608  7093  7093 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 20:54:30.609  7093  7684 D BluetoothMapMasInstance: MAS initSocket()
08-25 20:54:30.610  1027  1115 D BluetoothManagerService: Message: 40
08-25 20:54:30.610  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 20:54:30.611  7093  7093 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 20:54:30.611  7093  7093 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 20:54:30.614  1933  1933 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-25 20:54:30.617  1933  2124 D LGBluetoothAPIService: Message: 100
08-25 20:54:30.617  1933  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 20:54:30.619  7093  7684 D BluetoothMapMasInstance:   masId = 00
08-25 20:54:30.619  7093  7684 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 20:54:30.619  7093  7684 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 20:54:30.619  7093  7684 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-25 20:54:30.620  6972  6972 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 20:54:30.623  1027  1115 D BluetoothManagerService: Message: 30
08-25 20:54:30.623  1027  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:30.624  7093  7684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:30.626  7093  7684 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 20:54:30.626  7093  7684 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 20:54:30.626  7093  7575 D BluetoothAdapterProperties: Scan Mode:21
08-25 20:54:30.627  7093  7684 D BluetoothMapMasInstance: Accepting socket connection...
08-25 20:54:30.627  7093  7575 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-25 20:54:30.630  6972  6972 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 20:54:30.631  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:30.634  1027  1115 D BluetoothManagerService: Message: 30
08-25 20:54:30.634  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:30.634  7093  7093 V BluetoothPbapService: Pbap Service onCreate
08-25 20:54:30.635  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:30.638  7093  7093 V BluetoothPbapService: Starting PBAP service
,08-25 20:54:30.639  7093  7093 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 20:54:30.639  7093  7093 V BluetoothPbapService: Pbap Service onBind
08-25 20:54:30.640  6972  6972 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 20:54:30.640  7093  7093 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.641  7093  7093 V BluetoothPbapService: state: 12
08-25 20:54:30.641  7093  7093 V BluetoothPbapService: Handler(): got msg=1
08-25 20:54:30.641  6972  6972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 20:54:30.641  7093  7093 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 20:54:30.643  7093  7685 V BluetoothPbapService: Pbap Service initSocket
08-25 20:54:30.644  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:30.644  6972  6972 D BluetoothA2dp: Proxy object connected
08-25 20:54:30.645  6972  6972 D A2dpProfile: Bluetooth service connected
08-25 20:54:30.645  7093  7685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:30.645  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 20:54:30.646  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.646  7093  7093 V BluetoothPbapReceiver: ***********state = 12
08-25 20:54:30.646  7093  7685 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 20:54:30.646  7093  7685 V BluetoothPbapService: Succeed to create listening socket 
08-25 20:54:30.646  7093  7685 V BluetoothPbapService: Accepting socket connection...
08-25 20:54:30.647  6972  6972 D BluetoothHeadset: Proxy object connected
08-25 20:54:30.648  6972  6972 D HeadsetProfile: Bluetooth service connected
08-25 20:54:30.648  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:30.649  2185  2185 D c       : Getting all permits...
08-25 20:54:30.649  2185  2185 D a       : Opening database...
,08-25 20:54:30.650  6972  6972 D BluetoothPbap: Proxy object connected
08-25 20:54:30.652  6972  6972 D PbapServerProfile: Bluetooth service connected
08-25 20:54:30.653  2185  2185 D a       : Opening database auth.proximity.permit_store...
08-25 20:54:30.654  2185  2185 D a       : Closing database...
08-25 20:54:30.661  6972  6972 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:54:30.667  6972  6972 D BluetoothPermissionRequest: onReceive
08-25 20:54:30.669  6972  6972 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 20:54:30.671  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 20:54:30.674  7093  7093 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-25 20:54:30.677  7093  7093 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 20:54:30.683  7093  7093 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 20:54:30.701  7093  7093 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 20:54:30.701  7093  7093 V BtOppService: onCreate
08-25 20:54:30.704  7336  7367 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-25 20:54:30.706  7093  7093 V BluetoothOppNotification: send message
08-25 20:54:30.710  7093  7093 V BtOppService: Starting RfcommListener
08-25 20:54:30.716  7093  7093 D BluetoothOppPreference: Dumping Names:  
08-25 20:54:30.717  7093  7093 D BluetoothOppPreference: {}
08-25 20:54:30.717  7093  7093 D BluetoothOppPreference: Dumping Channels:  
08-25 20:54:30.717  7093  7093 D BluetoothOppPreference: {}
08-25 20:54:30.719  7093  7093 V BtOppService: onStartCommand
,08-25 20:54:30.722  7093  7694 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 20:54:30.723  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.723  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 20:54:30.728  7093  7093 V BluetoothOppNotification: new notify threadi!
08-25 20:54:30.728  7093  7093 V BluetoothOppNotification: send delay message
08-25 20:54:30.729  7093  7093 V BtOppService: start RfcommListener
08-25 20:54:30.732  7093  7093 V BtOppService: RfcommListener started
,08-25 20:54:30.735  7093  7696 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 20:54:30.735  1027  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:30.736  7093  7696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:30.738  7093  7696 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-25 20:54:30.738  7093  7696 V BtOppRfcommListener: Started RFCOMM listener....
08-25 20:54:30.738  7093  7696 I BtOppRfcommListener: Accept thread started.
08-25 20:54:30.738  7093  7696 V BtOppRfcommListener: Accepting connection...
08-25 20:54:30.747  7093  7691 V BtOppService: Deleted complete outbound shares, number =  0
,08-25 20:54:30.747  7093  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 20:54:30.749  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 20:54:30.749  7093  7691 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 20:54:30.751  7093  7691 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 20:54:30.752  7093  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@371ce1f3 on behalf of 
08-25 20:54:30.752  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30e1dc62 on behalf of 
08-25 20:54:30.752  7093  7691 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39166eb0 on behalf of 
08-25 20:54:30.754  7093  7695 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 20:54:30.756  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:30.757  7093  7694 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 20:54:30.758  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3066f129 on behalf of 
,08-25 20:54:30.760  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:30.760  7093  7093 V BluetoothFtpService: Ftp Service onCreate
,08-25 20:54:30.760  7093  7093 I BluetoothFtpService: Ftp Service onCreate
08-25 20:54:30.760  7093  7093 V BluetoothFtpService: Ftp Service onStartCommand
08-25 20:54:30.760  7093  7093 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.761  7093  7093 V BluetoothFtpService: Starting Listening on sockets
08-25 20:54:30.762  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:30.762  7093  7695 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 20:54:30.762  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:30.762  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:30.762  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.762  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 20:54:30.763  7093  7093 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 20:54:30.765  7093  7695 V BluetoothOppNotification: outbound notification was removed.
08-25 20:54:30.765  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:30.766  7093  7093 V BtOppService: ContentObserver received notification
08-25 20:54:30.766  7093  7093 V BtOppService: ContentObserver received notification
08-25 20:54:30.766  7093  7093 V BluetoothFtpService: Handler(): got msg=1
08-25 20:54:30.766  7093  7093 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 20:54:30.766  7093  7093 V BluetoothFtpService: Ftp Service initSocket
08-25 20:54:30.767  7093  7697 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 20:54:30.767  7093  7697 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 20:54:30.769  1027  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:30.770  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@919aa4f on behalf of 
08-25 20:54:30.770  7093  7093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:30.771  7093  7695 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 20:54:30.773  7093  7093 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-25 20:54:30.773  7093  7093 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 20:54:30.773  7093  7697 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39ebc5dc on behalf of 
08-25 20:54:30.775  7093  7697 V BluetoothOppNotification: update too frequent, put in queue
08-25 20:54:30.776  7093  7695 V BluetoothOppNotification: inbound notification was removed.
08-25 20:54:30.776  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 20:54:30.777  7093  7697 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 20:54:30.778  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23d476e5 on behalf of 
08-25 20:54:30.779  7093  7698 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 20:54:30.789  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:30.789  7093  7093 V BluetoothSapService: Sap Service onCreate
,08-25 20:54:30.792  7093  7093 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:30.792  7093  7093 V BluetoothSapService: state: 12
08-25 20:54:30.792  7093  7093 V BluetoothSapService: Starting SAP server process
08-25 20:54:30.794  7093  7093 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 20:54:30.789  7699  7699 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:30.789  7699  7699 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:30.796  7093  7700 V BluetoothSapService: Sap Service initRfcommSocket
08-25 20:54:30.797  1027  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:30.798  7093  7700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:30.799  7093  7700 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-25 20:54:30.799  7093  7700 V BluetoothSapService: Succeed to create listening socket 
08-25 20:54:30.799  7093  7700 V BluetoothSapService: Accepting socket connection...
08-25 20:54:30.806  7699  7699 V BT_SAP  : Event pipe created
08-25 20:54:30.806  7699  7699 V BT_SAP  : create_server_socket qcom.sap.server
08-25 20:54:30.806  7699  7699 V BT_SAP  : created socket fd 6
,08-25 20:54:31.476  1027  1428 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 20:54:31.476  1027  1428 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 20:54:31.548  1027  1477 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 20:54:31.555  1027  1477 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-25 20:54:31.677  1027  2004 I ActivityManager: Killing 7499:com.lge.bnr/1000 (adj 15): empty #17
,08-25 20:54:31.711  1027  2005 W libprocessgroup: failed to open /acct/uid_1000/pid_7499/cgroup.procs: No such file or directory
,08-25 20:54:31.730  7093  7093 V BluetoothOppNotification: new notify threadi!
08-25 20:54:31.730  7093  7093 V BluetoothOppNotification: send delay message
,08-25 20:54:31.733  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 20:54:31.735  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dda9c61 on behalf of 
08-25 20:54:31.735  7093  7710 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 20:54:31.737  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:31.738  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15c05386 on behalf of 
08-25 20:54:31.738  7093  7710 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 20:54:31.740  7093  7710 V BluetoothOppNotification: outbound notification was removed.
08-25 20:54:31.740  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:31.742  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bfa9447 on behalf of 
08-25 20:54:31.742  7093  7710 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 20:54:31.749  7093  7710 V BluetoothOppNotification: inbound notification was removed.
08-25 20:54:31.749  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 20:54:31.751  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18c8f474 on behalf of 
08-25 20:54:31.799  1027  1768 I ActivityManager: Killing 6995:com.lge.sync/1000 (adj 15): empty #17
,08-25 20:54:31.822  1027  1533 D WifiService: Client connection lost with reason: 4
,08-25 20:54:31.832  1027  2004 W libprocessgroup: failed to open /acct/uid_1000/pid_6995/cgroup.procs: No such file or directory
,08-25 20:54:32.278  1027  1370 V AlarmManager: ELAPSED_WAKEUP set : Alarm{ee2e576 type 2 when 200551 com.google.android.gms} when 200551
,08-25 20:54:32.297   312  7712 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 20:54:32.298  1027  1112 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-25 20:54:32.474  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 20:54:32.474  1027  1042 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27c9d777 mBinding = false
,08-25 20:54:32.506  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 20:54:32.507  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:32.507  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 20:54:32.507  1027  1115 D BluetoothManagerService: Message: 2
08-25 20:54:32.508  1027  1115 D BluetoothManagerService: Sending off request.
08-25 20:54:32.509  7093  7109 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 20:54:32.510  7093  7571 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 20:54:32.510  7093  7571 D BluetoothAdapterProperties: Setting state to 13
08-25 20:54:32.510  7093  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 20:54:32.511  7093  7571 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 20:54:32.511  7093  7571 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 20:54:32.513  7093  7575 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:54:32.514  7093  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 20:54:32.518  7093  7571 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 20:54:32.522  7093  7685 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:32.523  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 20:54:32.524  7093  7696 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:32.524  7093  7635 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 20:54:32.525  7093  7684 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 20:54:32.528  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 20:54:32.528  7093  7635 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 20:54:32.538  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:32.538  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:54:32.543  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:32.544  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:32.547  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:32.547  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:32.549  6854  6854 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 20:54:32.549  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:32.552  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:32.552  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 20:54:32.552  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-25 20:54:32.556  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.558  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 20:54:32.564  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:32.567  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:32.570  7093  7093 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.570  7093  7093 D BluetoothMapService: STATE_TURNING_OFF
08-25 20:54:32.571  7093  7093 V BluetoothMapService: Handler(): got msg=4
08-25 20:54:32.571  7093  7093 D BluetoothMapService: MAP Service closeService in
08-25 20:54:32.571  7093  7093 D BluetoothMapMasInstance: MAP Service shutdown
08-25 20:54:32.571  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 20:54:32.571  7093  7093 V BluetoothMapService: MAP Service closeService out
08-25 20:54:32.572  7093  7093 V BtOppService: Receiver DISABLED_ACTION 
08-25 20:54:32.572  7093  7093 I BtOppRfcommListener: stopping Accept Thread
08-25 20:54:32.572  7093  7093 V BtOppRfcommListener: close mBtServerSocket
08-25 20:54:32.573  7093  7696 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 20:54:32.573  7093  7093 V BtOppRfcommListener: waiting for thread to terminate
08-25 20:54:32.573  7093  7093 V BtOppRfcommListener: done waiting for thread to terminate
08-25 20:54:32.577  6972  6972 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-25 20:54:32.583  7093  7698 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:32.587  7093  7700 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 20:54:32.592  6972  6972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 20:54:32.595  7093  7093 V BtOppService: onDestroy
08-25 20:54:32.597  7093  7093 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 20:54:32.602  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 20:54:32.602  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.602  7093  7093 V BluetoothPbapReceiver: ***********state = 13
08-25 20:54:32.604  7093  7093 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 20:54:32.607  7093  7093 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.607  7093  7093 V BluetoothPbapService: state: 13
08-25 20:54:32.607  7093  7093 V BluetoothPbapService: Pbap Service closeService in
08-25 20:54:32.611  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:32.612  7093  7093 V BluetoothPbapService: successfully stopped pbap service
08-25 20:54:32.612  7093  7093 V BluetoothPbapService: Pbap Service closeService out
08-25 20:54:32.613  7093  7093 V BluetoothPbapService: Pbap Service onDestroy
08-25 20:54:32.613  7093  7093 V BluetoothPbapService: Pbap Service closeService in
08-25 20:54:32.613  7093  7093 V BluetoothPbapService: Pbap Service closeService out
08-25 20:54:32.614  7093  7093 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 20:54:32.638  6972  6972 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:54:32.641  6972  6972 D BluetoothPbap: Proxy object disconnected
08-25 20:54:32.641  6972  6972 D PbapServerProfile: Bluetooth service disconnected
,08-25 20:54:32.647  6972  6972 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 20:54:32.655  6972  6972 D BluetoothPermissionRequest: onReceive
08-25 20:54:32.655  6972  6972 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 20:54:32.665  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 20:54:32.673  7093  7093 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 20:54:32.673  7093  7093 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 20:54:32.674  7093  7093 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 20:54:32.681  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.681  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-25 20:54:32.684  7093  7093 V BluetoothFtpService: Ftp Service onStartCommand
08-25 20:54:32.684  7093  7093 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.684  7093  7093 V BluetoothFtpService: Ftp Service closeService
08-25 20:54:32.685  7093  7093 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 20:54:32.690  7093  7093 V BluetoothFtpService: successfully stopped ftp service
08-25 20:54:32.690  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:32.690  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:32.690  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:32.691  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.691  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 20:54:32.691  7093  7093 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 20:54:32.693  7093  7093 V BluetoothFtpService: Ftp Service onDestroy
08-25 20:54:32.693  7093  7093 V BluetoothFtpService: Ftp Service closeService
08-25 20:54:32.699  7093  7093 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:32.699  7093  7093 V BluetoothSapService: state: 13
08-25 20:54:32.700  7093  7093 V BluetoothSapService: Stopping SAP server process
08-25 20:54:32.701  7093  7093 V BluetoothSapService: Sap Service closeSapService in
08-25 20:54:32.701  7093  7093 V BluetoothSapService: Close listen Socket : 
,08-25 20:54:32.702  7093  7093 V BluetoothSapService: Close rfcomm Socket : 
,08-25 20:54:32.702  7093  7093 V BluetoothSapService: Close sapd  Socket : 
08-25 20:54:32.707  7093  7093 V BluetoothSapService: Sap Service closeSapService out
08-25 20:54:32.707  7093  7093 V BluetoothSapService: Sap Service onDestroy
08-25 20:54:32.707  7093  7093 V BluetoothSapService: Sap Service closeSapService in
08-25 20:54:32.707  7093  7093 V BluetoothSapService: Close listen Socket : 
08-25 20:54:32.707  7093  7093 V BluetoothSapService: Close rfcomm Socket : 
08-25 20:54:32.707  7093  7093 V BluetoothSapService: Close sapd  Socket : 
08-25 20:54:32.708  7093  7093 V BluetoothSapService: Sap Service closeSapService out
08-25 20:54:33.433  7093  7575 D bt_hci_bdroid: cleanup
,08-25 20:54:33.443  7093  7637 I bt_lpm  : LPM is already off!!!
08-25 20:54:33.444  7093  7668 I bt_userial_mct: exiting userial_read_thread
08-25 20:54:33.444  7093  7668 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 20:54:33.445  7093  7635 W bt-btif : ag scb idx 1 not allocated
08-25 20:54:33.445  7093  7635 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b,
08-25 20:54:33.445  7093  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
,08-25 20:54:33.445  7093  7635 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 20:54:33.448  7093  7575 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 20:54:33.450  7093  7637 I bt_vendor: hw_epilog_process
,08-25 20:54:33.451  7093  7575 D bt_hci_bdroid: cleanup Finalizing cleanup,
,08-25 20:54:33.451  7093  7575 D bt_userial_mct: userial_close,
08-25 20:54:33.451  7093  7575 E bt_userial_mct: pthread_join() FAILED result:3
08-25 20:54:33.451  7093  7575 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
,08-25 20:54:33.462  7093  7575 D bt_hci_bdroid: set_power 0
08-25 20:54:33.462  7093  7575 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 20:54:33.462  7093  7575 I bt_vendor: bluetooth satus is on
08-25 20:54:33.462  7093  7575 I bt_vendor: bt-vendor : resetting BT status
08-25 20:54:33.462  7093  7575 I bt_vendor: Starting hciattach daemon
08-25 20:54:33.462  7093  7575 I bt_vendor: try to set false
08-25 20:54:33.480  7093  7575 I bt_vendor: Starting hciattach daemon
,08-25 20:54:33.481  7093  7575 I bt_vendor: try to set false
,08-25 20:54:33.483  7093  7575 I bt_vendor: cleanup
08-25 20:54:33.485  7093  7635 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 20:54:33.486  7093  7575 I GKI_LINUX: GKI_exit_task 0 done
08-25 20:54:33.486  7093  7575 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 20:54:33.488  7093  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 20:54:33.495  7093  7093 D HeadsetService: Received stop request...Stopping profile...
,08-25 20:54:33.500  7093  7093 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 20:54:33.500  7093  7093 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:54:33.500  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:33.501  7093  7606 D HeadsetStateMachine: Exit Disconnected: -1
08-25 20:54:33.503  1845  1845 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:33.504  7093  7571 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 20:54:33.504  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:33.505  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 20:54:33.505  1845  1845 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:33.505  1845  1845 D BluetoothHeadset: Proxy object disconnected
08-25 20:54:33.506  7093  7093 D A2dpService: Received stop request...Stopping profile...
08-25 20:54:33.507  7093  7627 D A2dpStateMachine: Exit Disconnected: -1
08-25 20:54:33.509  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-25 20:54:33.512  7093  7093 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 20:54:33.512  7093  7093 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:54:33.512  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:33.514  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-25 20:54:33.514  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 20:54:33.515  7093  7093 D HidService: Received stop request...Stopping profile...
08-25 20:54:33.515  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:33.517  7093  7093 D HealthService: Received stop request...Stopping profile...
08-25 20:54:33.518  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:33.521  7093  7093 D PanService: Received stop request...Stopping profile...
,08-25 20:54:33.524  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:33.525  7093  7093 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 20:54:33.526  7093  7093 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 20:54:33.527  7093  7093 D BtGatt.GattService: stop()
08-25 20:54:33.527  7093  7093 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 20:54:33.528  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:33.530  7093  7093 D BluetoothMapService: Received stop request...Stopping profile...
08-25 20:54:33.530  7093  7093 D BluetoothMapService: stop()
08-25 20:54:33.534  7093  7093 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 20:54:33.534  7093  7093 D BluetoothMapEmailAppObserver: removeReceiver()
,08-25 20:54:33.537  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@340ce6a1
08-25 20:54:33.539  7093  7093 D HeadsetStateMachine: Unbinding service...
08-25 20:54:33.540  7093  7093 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 20:54:33.540  7093  7093 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 20:54:33.541  7093  7093 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 20:54:33.541  7093  7093 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 20:54:33.541  7093  7093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 20:54:33.541  7093  7093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 20:54:33.541  7093  7093 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 20:54:33.541  7093  7093 I BluetoothA2dpServiceJni: cleanupNative
08-25 20:54:33.541  7093  7628 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 20:54:33.542  7093  7093 I GKI_LINUX: GKI_exit_task 2 done
08-25 20:54:33.542  7093  7093 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 20:54:33.542  7093  7093 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 20:54:33.542  7093  7093 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 20:54:33.543  7093  7093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 20:54:33.544  7093  7093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 20:54:33.544  7093  7093 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 20:54:33.544  7093  7093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 20:54:33.544  7093  7093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 20:54:33.545  7093  7093 V BluetoothMapService: Handler(): got msg=4
08-25 20:54:33.546  7093  7093 D BluetoothMapService: MAP Service closeService in
08-25 20:54:33.546  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 20:54:33.546  7093  7093 V BluetoothMapService: MAP Service closeService out
08-25 20:54:33.546  7093  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 20:54:33.546  7093  7571 D BluetoothAdapterProperties: Setting state to 10
08-25 20:54:33.546  7093  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-25 20:54:33.550  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:33.550  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 20:54:33.550  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 20:54:33.550  7093  7093 D BluetoothMapService: cleanup()
08-25 20:54:33.550  7093  7093 D BluetoothMapService: MAP Service closeService in
08-25 20:54:33.550  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 20:54:33.551  7093  7093 V BluetoothMapService: MAP Service closeService out
08-25 20:54:33.551  7093  7571 I BluetoothAdapterState: Entering OffState
08-25 20:54:33.551  1845  1860 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:33.553  1027  1115 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:33.553  1845  2442 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:33.554  6972  6989 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 20:54:33.556  1845  1861 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:33.556  1027  1115 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 20:54:33.557  6972  6989 D BluetoothPan: onBluetoothStateChange on: false
08-25 20:54:33.557  6972  6989 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 20:54:33.558  6972  6989 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 20:54:33.560  6972  6989 D BluetoothMap: onBluetoothStateChange: up=false
08-25 20:54:33.561  6972  6989 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 20:54:33.563  1027  1115 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 20:54:33.563  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 20:54:33.565  1027  1115 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 20:54:33.565  1027  1115 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 20:54:33.565  1027  1115 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@27c9d777 mBinding = false
08-25 20:54:33.565  1027  1115 D BluetoothManagerService: Sending unbind request.
08-25 20:54:33.570  7093  7575 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 20:54:33.573  7093  7093 I GKI_LINUX: GKI_exit_task 1 done
08-25 20:54:33.573  7093  7093 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 20:54:33.573  7093  7093 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 20:54:33.573  7093  7093 I art     : --- WEIRD: removing null entry 248
08-25 20:54:33.574  7093  7093 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 20:54:33.574  7093  7093 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 20:54:33.575  7093  7093 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 20:54:33.576  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 20:54:33.578  7093  7093 I art     : System.exit called, status: 0
08-25 20:54:33.578  7093  7093 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 20:54:33.598   316   316 V AudioFlinger: 7093 died, releasing its sessions
08-25 20:54:33.598   316   316 V AudioFlinger:  pid 1845 @ 0
08-25 20:54:33.598   316   316 V AudioFlinger:  pid 3313 @ 1
08-25 20:54:33.598   316   316 V AudioFlinger:  pid 3313 @ 2
,08-25 20:54:33.603  1933  1933 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 20:54:33.603  1933  2124 D LGBluetoothAPIService: Message: 101
08-25 20:54:33.603  1933  2124 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-25 20:54:33.603  1933  2124 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 20:54:33.603  1933  2124 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-25 20:54:33.605  6972  6972 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 20:54:33.607  1027  1567 I ActivityManager: Process com.android.bluetooth (pid 7093) has died
08-25 20:54:33.607  1027  1567 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-25 20:54:33.607  1027  1567 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-25 20:54:33.613  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 20:54:33.616  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 20:54:33.617  1933  2124 D LGBluetoothAPIService: Message: 2
08-25 20:54:33.617  1933  2124 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-25 20:54:33.617  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:33.618  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:33.625  6972  6972 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 20:54:33.625  6972  6972 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 20:54:33.636  1593  1593 D BluetoothAdapter: 204641443: getState() :  mService = null. Returning STATE_OFF
08-25 20:54:33.636  1593  1593 D BluetoothAdapter: 204641443: getState() :  mService = null. Returning STATE_OFF
,08-25 20:54:33.647  6972  6972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 20:54:33.694  1027  2024 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7759 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 20:54:33.696  6972  6972 D DockEventReceiver: finishStartingService: stopping service
,08-25 20:54:33.795  7759  7759 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 20:54:33.796  7759  7759 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 20:54:33.797  7759  7759 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 20:54:33.799  7759  7759 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 20:54:33.821  7759  7759 D BluetoothAdapterApp: Loading JNI Library
,08-25 20:54:33.857  7759  7759 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@91b3369 Instance Count = 1
,08-25 20:54:33.863  7759  7759 D BluetoothAdapterApp: onCreate
08-25 20:54:33.889  7759  7759 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 20:54:33.889  7759  7759 D ProfileConfigQcom: Adding HeadsetService
08-25 20:54:33.889  7759  7759 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 20:54:33.890  7759  7759 D ProfileConfigQcom: Adding A2dpService
,08-25 20:54:33.890  7759  7759 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 20:54:33.890  7759  7759 D ProfileConfigQcom: Adding HidService
08-25 20:54:33.890  7759  7759 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 20:54:33.891  7759  7759 D ProfileConfigQcom: Adding HealthService
08-25 20:54:33.891  7759  7759 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 20:54:33.892  7759  7759 D ProfileConfigQcom: [BTUI] PanService is supported
,08-25 20:54:33.892  7759  7759 D ProfileConfigQcom: Adding PanService
08-25 20:54:33.892  7759  7759 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 20:54:33.892  7759  7759 D ProfileConfigQcom: Adding GattService
08-25 20:54:33.893  7759  7759 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 20:54:33.893  7759  7759 D ProfileConfigQcom: Adding BluetoothMapService
,08-25 20:54:33.893  7759  7759 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 20:54:33.894  7759  7759 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-25 20:54:33.896  7759  7759 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:33.896  7759  7759 V BluetoothPbapReceiver: ***********state = 10
,08-25 20:54:33.898  7759  7759 V LGMDMManagerInternal: Create singleton instance
08-25 20:54:34.016  7759  7759 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-25 20:54:34.016  7759  7759 D LGBluetoothAPIServer: [BTUI] onBind()
,08-25 20:54:34.022  1933  1933 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 20:54:34.022  1933  2124 D LGBluetoothAPIService: Message: 100
08-25 20:54:34.022  1933  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 20:54:34.023  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:34.029  6972  6972 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 20:54:34.040  6972  6972 D BluetoothPermissionRequest: onReceive
,08-25 20:54:34.043  6972  6972 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 20:54:34.043  6972  6972 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-25 20:54:34.047  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 20:54:34.052  7759  7759 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 20:54:34.059  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 20:54:34.062  7759  7759 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:34.063  7759  7759 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:34.063  7759  7759 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:34.064  7759  7759 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:34.064  7759  7759 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 20:54:34.071  7043  7043 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 20:54:35.541  1593  1593 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-25 20:54:35.551  1027  1373 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 20:54:35.600  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:35.600  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:54:35.640  1027  1105 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7788 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 20:54:35.647  1593  1593 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 20:54:35.653  1593  1593 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-25 20:54:35.665  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 20:54:35.695  1027  1027 D administrator: Handling package changes for user 0
,08-25 20:54:35.724  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 20:54:35.738  7788  7788 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 20:54:35.818  7788  7788 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:35.818  7788  7788 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 20:54:35.822  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 20:54:35.822  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-25 20:54:35.857  1027  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 20:54:35.863  1027  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 20:54:35.871  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-25 20:54:35.875  2500  2500 V GmsNetworkLocationProvi: DISABLE
,08-25 20:54:35.918  1027  1104 D LocationProviderProxy: applying state to connected service
08-25 20:54:35.922  2500  2500 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-25 20:54:35.945  7788  7831 I Babel   : MmsConfig: mnc/mcc: 0/0
08-25 20:54:35.946  7788  7831 I Babel   : MmsConfig.loadMmsSettings
,08-25 20:54:35.953  7788  7831 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 20:54:35.953  7788  7831 I Babel   : MmsConfig.loadFromDatabase
08-25 20:54:35.986  7788  7829 W AudioCapabilities: Unsupported mime audio/evrc
08-25 20:54:35.986  7788  7829 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 20:54:35.988  7788  7831 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-25 20:54:35.988  7788  7831 I Babel   : MmsConfig.loadFromResources
08-25 20:54:35.989  7788  7831 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 20:54:35.990  7788  7831 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 20:54:35.993  7788  7829 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 20:54:36.007  7788  7788 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:36.009  7788  7829 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-25 20:54:36.011  7788  7829 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 20:54:36.013  7788  7829 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 20:54:36.025  7788  7829 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-25 20:54:36.028  7788  7829 W VideoCapabilities: Unsupported mime video/divx
08-25 20:54:36.030  7788  7829 W VideoCapabilities: Unsupported mime video/divx311
08-25 20:54:36.032  7788  7829 W VideoCapabilities: Unsupported mime video/divx4
08-25 20:54:36.034  1809  7835 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-25 20:54:36.034  1809  7835 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-25 20:54:36.034  7156  7156 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 20:54:36.042  7156  7156 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1548ccab
08-25 20:54:36.042  7156  7156 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 20:54:36.042  7156  7156 D AppUp4:CustFacade: isPhone : true
08-25 20:54:36.042  7156  7156 D AppUp4:CustModeStarterReceiver: begin check event
08-25 20:54:36.042  7156  7156 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-25 20:54:36.044  7788  7829 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-25 20:54:36.045  1809  5228 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-25 20:54:36.075  7788  7829 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 20:54:36.082  1027  1042 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7838 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-25 20:54:36.083  7788  7829 W AudioCapabilities: Unsupported mime audio/eac3
08-25 20:54:36.091  7788  7829 W AudioCapabilities: Unsupported mime audio/ac3
08-25 20:54:36.091  1027  1969 I ActivityManager: Killing 6768:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-25 20:54:36.093  7788  7829 W AudioCapabilities: Unsupported mime audio/g726
08-25 20:54:36.094  7788  7829 W AudioCapabilities: Unsupported mime audio/wma-voice
08-25 20:54:36.095  7788  7829 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 20:54:36.096  7788  7829 W AudioCapabilities: Unsupported mime audio/adpcm
08-25 20:54:36.099   349   349 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 17.797ms
08-25 20:54:36.109  7788  7829 W VideoCapabilities: Unsupported mime video/theora
,08-25 20:54:36.112  7788  7829 W VideoCapabilities: Unsupported mime video/mjpg
08-25 20:54:36.115   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 293us total 15.377ms
08-25 20:54:36.116  7026  7026 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-25 20:54:36.116  7026  7026 W System.err: android.os.DeadObjectException
08-25 20:54:36.116  7026  7026 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 20:54:36.116  7026  7026 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 20:54:36.116  7026  7026 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 20:54:36.116  7026  7026 W System.err: ,	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 20:54:36.116  7026  7026 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 20:54:36.116  7026  7026 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 20:54:36.116  7026  7026 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 20:54:36.116  7026  7026 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 20:54:36.116  7026  7026 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:36.116  7026  7026 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 20:54:36.116  7026  7026 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:54:36.116  7026  7026 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 20:54:36.116  7026  7026 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 20:54:36.117  7026  7026 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 20:54:36.117  7026  7026 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 20:54:36.117  7026  7026 W System.err: android.os.DeadObjectException
08-25 20:54:36.117  7026  7026 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 20:54:36.117  7026  7026 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 20:54:36.117  7026  7026 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 20:54:36.117  7026  7026 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 20:54:36.117  7026  7026 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 20:54:36.117  7026  7026 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 20:54:36.117  7026  7026 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 20:54:36.117  7026  7026 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 20:54:36.117  7026  7026 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:36.117  7026  7026 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 20:54:36.117  7026  7026 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:54:36.117  7026  7026 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 20:54:36.117  7026  7026 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 20:54:36.117  7026  7026 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 20:54:36.117  7026  7026 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 20:54:36.118  7026  7026 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-25 20:54:36.129   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 13.452ms
,08-25 20:54:36.302  1027  1969 E libprocessgroup: failed to kill 1 processes for processgroup 6768
,08-25 20:54:36.370  1027  2005 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-25 20:54:36.379  7026  7026 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 20:54:36.380  7026  7026 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 20:54:36.415  7838  7838 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 20:54:36.415  7838  7838 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 20:54:36.415  7838  7838 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 20:54:36.416  7838  7838 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 20:54:36.416  7838  7838 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-25 20:54:36.442  1027  1950 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7860 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 20:54:36.455  7026  7026 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-25 20:54:36.464  7838  7838 I SystemConfig: BUILD Country: EU
08-25 20:54:36.464  7838  7838 I SystemConfig: BUILD Operator: OPEN
,08-25 20:54:36.505  1027  1896 I ActivityManager: Killing 7026:com.lge.qremote/u0a112 (adj 15): empty #17
,08-25 20:54:36.512  7860  7860 D UEI.SmartControl: Quickset Services start...
08-25 20:54:36.513  7860  7860 I UEI.SmartControl: Manufacture = LGE
08-25 20:54:36.514  7860  7860 D UEI.SmartControl: Id = LGNevo
08-25 20:54:36.514  7860  7860 D UEI.SmartControl: File observer start...
08-25 20:54:36.516  7860  7860 E UEI.SmartControl: IR Port is disabled: false
08-25 20:54:36.516  7860  7860 D UEI.SmartControl: Starting file observer...
08-25 20:54:36.517  7860  7860 D UEI.SmartControl: Extracting JNI libs...
08-25 20:54:36.517  7860  7860 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-25 20:54:36.560  1027  1535 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-25 20:54:36.577  1027  2024 W libprocessgroup: failed to open /acct/uid_10112/pid_7026/cgroup.procs: No such file or directory
,08-25 20:54:36.593  7838  7878 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 20:54:36.593  7838  7878 I SystemConfig: existFile = false
08-25 20:54:36.593  7838  7878 I SystemConfig: canReadFile = false
08-25 20:54:36.593  7838  7878 I SystemConfig: systemFeature RCS result false
08-25 20:54:36.594  7838  7878 D SystemConfig: refreshRcsSupport() :false
,08-25 20:54:36.627  7860  7860 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-25 20:54:36.627  7860  7860 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 20:54:36.627  7860  7860 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-25 20:54:36.662  1027  1950 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7887 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-25 20:54:36.672  7860  7860 I UEI.SmartControl: --- Selecting new region: 6
08-25 20:54:36.678  7860  7860 I UEI.SmartControl: Model = LG-D855
,08-25 20:54:36.686  7860  7860 D UEI.SmartControl: QS Service created
08-25 20:54:36.706  7860  7860 I UEI.SmartControl: Service initServices...
,08-25 20:54:36.712  7860  7860 D UEI.SmartControl: QS start get config
08-25 20:54:36.755  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 20:54:36.755  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 20:54:36.755  7887  7887 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 20:54:36.756  7887  7887 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 20:54:36.764  7860  7860 D UEI.SmartControl: Loading JNI Libs...
08-25 20:54:36.864  1027  1370 V AlarmManager: ELAPSED_WAKEUP set : Alarm{24506c9c type 2 when 205144 com.google.android.gms} when 205144
,08-25 20:54:36.877  7887  7887 I AppConfig: Total System Memory = 2995761152
,08-25 20:54:36.893  7887  7887 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-25 20:54:36.963  1027  1932 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7906 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 20:54:36.964  1027  1932 I ActivityManager: Killing 7184:com.lge.email/u0a23 (adj 15): empty #17
08-25 20:54:37.042  1027  1896 W libprocessgroup: failed to open /acct/uid_10023/pid_7184/cgroup.procs: No such file or directory
,08-25 20:54:37.121  7860  7860 I UEI.SmartControl: Supports setup maps: true
,08-25 20:54:37.126  7860  7860 D UEI.SmartControl: QS start statue = true Error code = 0
,08-25 20:54:37.126  7860  7860 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 20:54:37.126  7860  7860 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 20:54:37.126  7860  7860 I UEI.SmartControl: ### init IR Blaster...
08-25 20:54:37.132  7860  7860 D serial_port: Configuring serial port
08-25 20:54:37.136  7860  7860 E UEI.SmartControl: UEIBLaster setting for 616
08-25 20:54:37.136  7860  7860 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 20:54:37.137  7860  7860 I UEI.SmartControl: configuring settings for MAXQ616
08-25 20:54:37.137  7860  7860 I UEI.SmartControl: Get version...
,08-25 20:54:37.153  7860  7926 D UEI.SmartControl: serial port data available: 21
,08-25 20:54:37.182  7860  7860 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 20:54:37.182  7860  7860 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 20:54:37.182  7860  7860 I UEI.SmartControl: QS saving settings...
08-25 20:54:37.183  7860  7860 D UEI.SmartControl: IR Blaster version: 25672567
08-25 20:54:37.201  7860  7926 D UEI.SmartControl: serial port data available: 4
,08-25 20:54:37.220  7906  7906 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 20:54:37.232  7860  7860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 20:54:37.235  7860  7860 E UEI.SmartControl: Services init done
08-25 20:54:37.235  7860  7860 D UEI.SmartControl: QS Service init finished
08-25 20:54:37.236  7860  7860 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 20:54:37.236  7860  7860 D UEI.SmartControl: QS Service version code: 201091
08-25 20:54:37.237  7860  7860 D UEI.SmartControl: Service requested: Control
08-25 20:54:37.237  7860  7934 I UEI.SmartControl: Device manager: loading config....
08-25 20:54:37.237  7860  7934 D UEI.SmartControl: ----------- loading internal config...
08-25 20:54:37.243  7860  7934 E UEI.SmartControl: Loading SETTINGS...
08-25 20:54:37.247  7860  7934 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 20:54:37.247  7860  7860 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-25 20:54:37.250  7860  7860 D UEI.SmartControl: Service.onUnbind: IControl
08-25 20:54:37.251  7860  7860 D UEI.SmartControl: Service.onDestroy
08-25 20:54:37.251  7860  7860 D UEI.SmartControl: Lock is in USE false
08-25 20:54:37.251  7860  7860 D UEI.SmartControl: unbind internal service
08-25 20:54:37.253  7860  7933 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 20:54:37.253  7860  7933 D UEI.SmartControl: -----service ready thread exits
,08-25 20:54:37.259  7860  7860 D serial_port: close(fd = 25)
08-25 20:54:37.263  7860  7860 I UEI.SmartControl: Serial port is closed.
08-25 20:54:37.263  7860  7860 I UEI.SmartControl: Serial port is closed.
08-25 20:54:37.264  7860  7860 D UEI.SmartControl: Blaster closed
08-25 20:54:37.264  7860  7860 D UEI.SmartControl: Shut down QS...
08-25 20:54:37.264  7860  7860 D UEI.SmartControl: Stopping QS lib
08-25 20:54:37.264  7860  7860 D UEI.SmartControl: QS lib stop result = true
08-25 20:54:37.264  7860  7860 D UEI.SmartControl: Stopped QS lib
08-25 20:54:37.264  7860  7860 D UEI.SmartControl: Stopped file observer...
08-25 20:54:37.264  7860  7860 D UEI.SmartControl: QS shutdown complete
,08-25 20:54:37.266  7860  7860 D UEI.SmartControl: QS Service created
08-25 20:54:37.280  7860  7860 I UEI.SmartControl: Service initServices...
08-25 20:54:37.280  7860  7860 D UEI.SmartControl: QS start get config
,08-25 20:54:37.306  7906  7906 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:37.306  7906  7906 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 20:54:37.371  7906  7906 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 20:54:37.393  7906  7906 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 20:54:37.400  7906  7906 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 20:54:37.423  7906  7906 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-25 20:54:37.423  7906  7906 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-25 20:54:37.447  1027  2024 I ActivityManager: Killing 7064:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-25 20:54:37.539  1027  1567 W libprocessgroup: failed to open /acct/uid_10026/pid_7064/cgroup.procs: No such file or directory
,08-25 20:54:37.563  5085  7952 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-25 20:54:37.596  7860  7860 I UEI.SmartControl: Supports setup maps: true
08-25 20:54:37.599  7860  7860 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 20:54:37.599  7860  7860 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 20:54:37.599  7860  7860 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 20:54:37.599  7860  7860 I UEI.SmartControl: ### init IR Blaster...
,08-25 20:54:37.603  7860  7860 D serial_port: Configuring serial port
08-25 20:54:37.603  7860  7860 E UEI.SmartControl: UEIBLaster setting for 616
08-25 20:54:37.604  7860  7860 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 20:54:37.604  7860  7860 I UEI.SmartControl: configuring settings for MAXQ616
08-25 20:54:37.604  7860  7860 I UEI.SmartControl: Get version...
08-25 20:54:37.609  1027  1932 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7954 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-25 20:54:37.620  7860  7953 D UEI.SmartControl: serial port data available: 21
08-25 20:54:37.621  3415  4242 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-25 20:54:37.622  3415  4242 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@32b899ac on behalf of 7906
,08-25 20:54:37.645  7906  7906 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-25 20:54:37.648  7860  7860 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 20:54:37.648  7860  7860 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 20:54:37.648  7860  7860 I UEI.SmartControl: QS saving settings...
08-25 20:54:37.648  7860  7860 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 20:54:37.655  7906  7906 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-25 20:54:37.665  7860  7953 D UEI.SmartControl: serial port data available: 4
,08-25 20:54:37.673  7954  7954 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 20:54:37.691  7860  7860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 20:54:37.693  7860  7860 E UEI.SmartControl: Services init done
08-25 20:54:37.693  7860  7860 D UEI.SmartControl: QS Service init finished
08-25 20:54:37.695  7860  7860 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 20:54:37.695  7860  7860 D UEI.SmartControl: QS Service version code: 201091
08-25 20:54:37.695  7860  7860 D UEI.SmartControl: Service requested: Control
08-25 20:54:37.697  1027  2043 I ActivityManager: Killing 6392:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-25 20:54:37.700  7860  7981 I UEI.SmartControl: Device manager: loading config....
08-25 20:54:37.700  7860  7981 D UEI.SmartControl: ----------- loading internal config...
08-25 20:54:37.708  7860  7981 E UEI.SmartControl: Loading SETTINGS...
,08-25 20:54:37.712  7860  7981 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 20:54:37.720  7860  7980 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 20:54:37.720  7860  7980 D UEI.SmartControl: -----service ready thread exits
,08-25 20:54:37.796  7860  7860 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@23c58887 that was originally bound here
08-25 20:54:37.796  7860  7860 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@23c58887 that was originally bound here
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 20:54:37.796  7860  7860 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 20:54:37.804  1027  1896 W libprocessgroup: failed to open /acct/uid_1000/pid_6392/cgroup.procs: No such file or directory
08-25 20:54:37.818  7860  7860 D UEI.SmartControl: Internal service binding...
,08-25 20:54:37.938  1027  2024 I art     : Explicit concurrent mark sweep GC freed 42274(1992KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.795ms total 133.313ms
,08-25 20:54:37.947  7954  7954 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-25 20:54:37.947  7954  7954 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 20:54:37.947  7954  7954 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-25 20:54:37.947  7954  7954 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 20:54:37.947  7954  7954 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-25 20:54:37.947  7954  7954 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-25 20:54:37.975   312  7986 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 20:54:37.976  1027  1112 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-25 20:54:37.993  1027  1932 I ActivityManager: Killing 7226:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-25 20:54:38.029  1027  1968 V SIM_STK : Menu title from STK is T-Mobile
,08-25 20:54:38.046  5085  7952 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 482 ms] updated apps [took 482 ms] 
,08-25 20:54:38.054  1027  1727 W libprocessgroup: failed to open /acct/uid_10046/pid_7226/cgroup.procs: No such file or directory
08-25 20:54:38.252  7860  7940 D UEI.SmartControl: Internal timer expired: 2
,08-25 20:54:38.652  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 20:54:38.653  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a40d605 added. We now have 6 listener(s)
08-25 20:54:38.653  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 20:54:38.663  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:38.663  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@baed65a added. We now have 7 listener(s)
08-25 20:54:38.664  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:38.664  6854  6932 I System.out: IsBluetoothEnabled
08-25 20:54:38.665  1027  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:38.665  1027  1767 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 20:54:38.666  1027  1115 D BluetoothManagerService: Message: 2
08-25 20:54:38.669  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:38.669  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:38.669  1027  1042 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 20:54:38.685  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 20:54:38.685  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:38.685  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 20:54:38.686  1027  1115 D BluetoothManagerService: Message: 1
08-25 20:54:38.686  1027  1115 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 20:54:38.709  1027  1115 D BluetoothManagerService: Message: 20
08-25 20:54:38.710  1027  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f6a65ef:true
,08-25 20:54:38.714  7759  7759 D BluetoothAdapterState: make
08-25 20:54:38.719  7759  7759 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 20:54:38.719  7759  7759 I bluedroid-qcom: init
08-25 20:54:38.720  7759  7999 I BluetoothAdapterState: Entering OffState
08-25 20:54:38.721  7759  7759 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 20:54:38.721  7759  7759 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 20:54:38.721  7759  7759 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 20:54:38.721  7759  7759 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 20:54:38.721  7759  7759 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 20:54:38.723  7759  7759 I bluedroid-qcom: get_profile_interface socket
08-25 20:54:38.723  7759  7759 I bluedroid-qcom: get_profile_interface map_client
,08-25 20:54:38.727  7759  8003 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 20:54:38.731  7759  8003 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 20:54:38.729  8002  8002 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:38.729  8002  8002 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:38.742  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-25 20:54:38.745  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 20:54:38.746  7759  8003 D BluetoothAdapterProperties: Name is: G3
08-25 20:54:38.746  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 20:54:38.747  1027  1115 D BluetoothManagerService: Message: 40
08-25 20:54:38.747  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 20:54:38.747  7759  7775 I bluedroid-qcom: config_hci_snoop_log
08-25 20:54:38.749  1027  1115 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 20:54:38.749  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 20:54:38.749  8002  8002 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 20:54:38.749  8002  8002 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 20:54:38.749  8002  8002 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 20:54:38.752  8002  8002 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 20:54:38.757  8002  8002 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 20:54:38.757  8002  8002 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-25 20:54:38.764  7759  7999 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 20:54:38.764  7759  7999 D BluetoothAdapterProperties: Setting state to 11
08-25 20:54:38.764  7759  7999 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 20:54:38.765  7759  7999 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 20:54:38.769  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:38.769  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 20:54:38.769  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 20:54:38.773  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 20:54:38.776  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 20:54:38.780  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:38.782  6972  6972 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 20:54:38.788  7759  7759 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 20:54:38.788  7759  7759 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:38.788  7759  7759 V BluetoothPbapReceiver: ***********state = 11
,08-25 20:54:38.794  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:38.814  7759  7999 D BluetoothBondStateMachine: make
,08-25 20:54:38.820  7759  7999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:38.821  7759  7999 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 20:54:38.821  7759  7999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:38.821  7759  7999 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 20:54:38.821  6972  6972 D BluetoothPermissionRequest: onReceive
08-25 20:54:38.821  7759  7999 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 20:54:38.823  7759  8016 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 20:54:38.825  7759  7999 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:38.827  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 20:54:38.838  7759  7999 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:38.838  7759  7759 D HeadsetService: Received start request. Starting profile...
08-25 20:54:38.839  7759  7759 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 20:54:38.839  7759  7759 D LGBluetoothHfpAdapter: Version 1.6
08-25 20:54:38.843  7759  7759 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 20:54:38.843  7759  7999 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:38.844  7759  7759 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 20:54:38.845  7759  7759 D HeadsetStateMachine: make
,08-25 20:54:38.849  7759  7999 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:38.855  7759  7999 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 20:54:38.861  7759  7999 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:38.867  7759  7999 E BluetoothAdapterService: File transfer profiles supported!!
08-25 20:54:38.881  7759  7999 V LGMDMManager: Create singleton instance
,08-25 20:54:38.894  7759  7999 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 20:54:38.894  7759  7759 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 20:54:38.894  7759  7759 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 20:54:38.903  7759  7759 D HeadsetStateMachine: max_hf_connections = 1
08-25 20:54:38.903  7759  7759 I bluedroid-qcom: get_profile_interface handsfree
08-25 20:54:38.907  7759  7759 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-25 20:54:38.908   316  1385 V AudioPolicyService: registerClient() client 0xb558a500, uid 1002
08-25 20:54:38.908   316  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-25 20:54:38.908   316  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 20:54:38.908   316  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 20:54:38.909  7759  7759 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 20:54:38.910   316   316 V AudioFlinger: registerClient() client 0xb5581610, pid 7759
08-25 20:54:38.910   316  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:38.910   316  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:38.910   316  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:38.910   316  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:38.911  1593  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:38.911  1593  1613 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:38.911  1027  1768 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:38.911  1027  1768 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:38.911  1593  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:38.911  1593  1613 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:38.911  7759  7776 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:38.911  1027  1768 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:38.911  1027  1768 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:38.911  1845  2442 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:38.911  1845  2442 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-25 20:54:38.911  1845  2442 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:38.911  1845  2442 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:38.911  3313  3328 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 20:54:38.911  3313  3328 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 20:54:38.911  3313  3328 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:38.911  3313  3328 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 20:54:38.911  7759  7776 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 20:54:38.912  7759  7776 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 20:54:38.912  7759  7776 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 20:54:38.912  7759  7759 V ToneGenerator: Create Track: 0xb4928a80
08-25 20:54:38.912  7759  7759 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 20:54:38.912  7759  7759 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 20:54:38.912   316  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 20:54:38.912   316  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 20:54:38.912   316  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 20:54:38.912   316  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 20:54:38.913   316  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 20:54:38.913   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 20:54:38.913   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 20:54:38.913   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 20:54:38.913   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 20:54:38.914  7759  7759 V AudioSystem: getLatency() output 2, latency 50
08-25 20:54:38.914  7759  7759 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 20:54:38.914  7759  7759 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 20:54:38.915   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 20:54:38.915   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 20:54:38.915   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 20:54:38.915   316  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 20:54:38.915   316  2159 V AudioFlinger: createTrack() lSessionId: 23
08-25 20:54:38.916  7759  7759 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 20:54:38.917   316  1385 V AudioFlinger: acquiring 23 from 7759, for 7759
08-25 20:54:38.917   316  1385 V AudioFlinger:  added new entry for 23
08-25 20:54:38.917  7759  7759 V ToneGenerator: ToneGenerator INIT OK, time: 207207
08-25 20:54:38.918  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:38.918  7759  8019 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 20:54:38.918  7759  8019 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 20:54:38.919  7759  8019 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 20:54:38.919  7759  8019 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 20:54:38.919   316  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7759
08-25 20:54:38.920   316  1384 D audio_hw_primary: ad,ev_set_parameters: enter: bt_samplerate=8000
08-25 20:54:38.920   316  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 20:54:38.920   316  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,08-25 20:54:38.921  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:38.921   316  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 20:54:38.921   316  1384 V voice   : voice_set_parameters: exit with code(0)
08-25 20:54:38.921   316  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 20:54:38.921   316  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 20:54:38.921   316  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 20:54:38.921   316  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 20:54:38.922   316  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 20:54:38.922   316  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 20:54:38.922  7759  8019 V ToneGenerator: ToneGenerator destructor
08-25 20:54:38.922  7759  8019 V ToneGenerator: stopTone
08-25 20:54:38.922  7759  8019 V ToneGenerator: Delete Track: 0xb4928a80
08-25 20:54:38.924   316   316 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 20:54:38.924   316   316 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 20:54:38.924   316  1263 V AudioPolicyService: AudioCommandThread() waking up
08-25 20:54:38.924   316   316 V AudioFlinger: PlaybackThread::Track destructor
08-25 20:54:38.924   316  1263 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 20:54:38.924   316  1263 V AudioPolicyManager: releaseOutput() 2
,08-25 20:54:38.924   316  1263 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 20:54:38.924   316   316 V AudioFlinger: removeClient_l() pid 7759, calling pid 316
08-25 20:54:38.925  7759  8019 V AudioTrack: ~AudioTrack, releasing session id from 7759 on behalf of 7759
08-25 20:54:38.925  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:38.925   316  1385 V AudioFlinger: releasing 23 from 7759 for 7759
08-25 20:54:38.925   316  1385 V AudioFlinger:  decremented refcount to 0
08-25 20:54:38.925   316  1385 V AudioFlinger: purging stale effects
08-25 20:54:38.929  7759  7759 D A2dpService: Received start request. Starting profile...
08-25 20:54:38.931  7759  7759 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 20:54:38.932  7759  7759 V Avrcp   : make
08-25 20:54:38.933  7759  7759 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 20:54:38.933  7759  7759 I bluedroid-qcom: get_profile_interface avrcp
,08-25 20:54:38.948  7759  7759 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 20:54:38.952  7759  7759 E AudioManager: No RCC entry present to update
08-25 20:54:38.952  7759  7759 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 20:54:38.957  7759  7759 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 20:54:38.959  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 20:54:38.959  7759  7759 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-25 20:54:38.965  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 20:54:39.081  1027  2004 V SIM_STK : Menu title from STK is T-Mobile
08-25 20:54:39.081  1027  2004 V SIM_STK : Menu title from STK is T-Mobile
,08-25 20:54:39.219  1027  2043 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 20:54:39.245  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-25 20:54:39.252  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 20:54:39.252  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 20:54:39.253  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 20:54:39.254  7759  7759 I BluetoothA2dpServiceJni: classInitNative
08-25 20:54:39.254  7759  7759 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 20:54:39.254  7759  7759 D A2dpStateMachine: make
08-25 20:54:39.256  7759  7759 I bluedroid-qcom: get_profile_interface a2dp
08-25 20:54:39.256  7759  8034 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 20:54:39.260  7759  7759 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 20:54:39.260  7759  7759 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-25 20:54:39.262  7759  8033 D A2dpStateMachine: Enter Disconnected: -2
08-25 20:54:39.262  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:39.264  7759  7759 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 20:54:39.267  7759  7759 D HidService: Received start request. Starting profile...
08-25 20:54:39.267  7759  7759 I bluedroid-qcom: get_profile_interface hidhost
08-25 20:54:39.267  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:39.268  7759  7759 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 20:54:39.270  7759  7759 D HealthService: Received start request. Starting profile...
08-25 20:54:39.273  7759  7759 I bluedroid-qcom: get_profile_interface health
,08-25 20:54:39.273  7759  7759 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 20:54:39.274  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:39.275  7759  7759 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 20:54:39.278  7759  7759 D PanService: Received start request. Starting profile...
08-25 20:54:39.278  7759  7759 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 20:54:39.278  7759  7759 I bluedroid-qcom: get_profile_interface pan
08-25 20:54:39.286  7759  7759 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 20:54:39.286  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
,08-25 20:54:39.287  7759  7759 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 20:54:39.294  7759  7759 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 20:54:39.295  7759  7759 D BtGatt.GattService: Received start request. Starting profile...
08-25 20:54:39.295  7759  7759 D BtGatt.GattService: start()
08-25 20:54:39.295  7759  7759 I bluedroid-qcom: get_profile_interface gatt
08-25 20:54:39.295  7759  7759 D BtGatt.AdvertiseManager: advertise manager created
08-25 20:54:39.306  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
,08-25 20:54:39.311  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:39.312  7759  7759 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 20:54:39.314  7759  7759 V BluetoothMapService: BluetoothMapBinder()
08-25 20:54:39.316  7759  7759 D BluetoothMapService: Received start request. Starting profile...
08-25 20:54:39.316  7759  7759 D BluetoothMapService: start()
08-25 20:54:39.323  7759  7759 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 20:54:39.323  7759  7759 D BluetoothMapEmailAppObserver: createReceiver()
,08-25 20:54:39.325  7759  7759 D BluetoothMapEmailAppObserver: initObservers()
08-25 20:54:39.326  7759  7759 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 20:54:39.337  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
,08-25 20:54:39.338  7759  7759 D HeadsetStateMachine: Proxy object connected
08-25 20:54:39.339  7759  7759 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 20:54:39.339  7759  7759 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 20:54:39.341  7759  8019 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 20:54:39.342  7759  8019 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 20:54:39.342  7759  8019 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 20:54:39.348  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 20:54:39.348  7759  7759 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:39.348  7759  7759 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:39.348  7759  7759 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:39.348  7759  7759 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:39.348  7759  7759 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 20:54:39.352  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 20:54:39.359  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 20:54:39.363  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 20:54:39.363  7759  7759 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 20:54:39.367  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 20:54:39.372  7759  7759 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 20:54:39.372  7759  7759 V BluetoothMapService: Handler(): got msg=1
08-25 20:54:39.374  7759  7999 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 20:54:39.374  7759  7999 I bluedroid-qcom: enable
08-25 20:54:39.374  7759  7999 I bt_hci_bdroid: init
08-25 20:54:39.374  7759  8041 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 20:54:39.376  7759  7999 I bt_vendor: bt-vendor : init
08-25 20:54:39.376  7759  7999 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 20:54:39.376  7759  7999 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 20:54:39.376  7759  7999 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 20:54:39.376  7759  7999 D bt_userial_mct: userial_init
08-25 20:54:39.376  7759  8041 I bt-btu  : btu_task pending for preload complete event
08-25 20:54:39.376  7759  7999 D bt_hci_bdroid: set_power 1
08-25 20:54:39.376  7759  7999 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 20:54:39.376  7759  7999 I bt_vendor: Starting hciattach daemon
08-25 20:54:39.376  7759  7999 I bt_vendor: try to set true
08-25 20:54:39.369  8044  8044 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:39.379  8044  8044 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 20:54:39.408  8045  8045 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 20:54:39.486  8051  8051 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 20:54:39.512  8052  8052 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 20:54:39.538  8054  8054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 20:54:39.551  8055  8055 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-25 20:54:39.563  8056  8056 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 20:54:39.577  8057  8057 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 20:54:39.613  8059  8059 I libmdmdetect: ESOC framework not supported
08-25 20:54:39.614  8059  8059 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 20:54:39.622  8059  8059 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-25 20:54:39.623  8059  8059 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-25 20:54:39.623  8059  8059 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 20:54:39.623  8059  8059 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-25 20:54:39.623  8059  8059 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 20:54:39.623  8059  8059 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 20:54:39.623  8059  8059 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 20:54:39.663  8059  8060 E QC-QMI  : qmi_client [8059] 15: failed to locate client data
08-25 20:54:39.666   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-25 20:54:39.667   483   483 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-25 20:54:39.701  8061  8061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 20:54:39.715  8062  8062 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 20:54:39.781  7759  7999 I bt_vendor: bluetooth satus is on
08-25 20:54:39.781  7759  7999 D bt_hci_bdroid: preload
,08-25 20:54:39.782  7759  8043 D bt_userial_mct: userial_open(port:0)
,08-25 20:54:39.782  7759  8043 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 20:54:39.786  7759  8043 I bt_vendor: Done intiailizing UART
,08-25 20:54:39.791  7759  8043 I bt_vendor: Done intiailizing UART
08-25 20:54:39.791  7759  8043 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 20:54:39.791  7759  8043 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 20:54:39.792  7759  8041 I bt-btu  : btu_task received preload complete event
08-25 20:54:39.793  7759  8064 D bt_userial_mct: Entering userial_read_thread()
08-25 20:54:39.794  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 20:54:39.795  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-25 20:54:39.801  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 20:54:39.809  7759  8041 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 20:54:39.809  7759  8041 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 20:54:39.809  7759  8041 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 20:54:39.809  7759  8041 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 20:54:39.810  7759  8041 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 20:54:39.810  7759  8041 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 20:54:39.810  7759  8041 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 20:54:39.810  7759  8041 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 20:54:39.810  7759  8041 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 20:54:39.810  7759  8041 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 20:54:39.811  7759  8041 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 20:54:39.811  7759  8041 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 20:54:39.811  7759  8041 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 20:54:39.811  7759  8041 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 20:54:39.811  7759  8041 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 20:54:39.811  7759  8041 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 20:54:39.883  7759  8041 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-25 20:54:39.883  7759  8041 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0215061 
08-25 20:54:39.883  7759  8041 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0215061 
,08-25 20:54:39.946  7759  8003 E bt-btif : Calling BTA_HhEnable
,08-25 20:54:39.947  7759  8003 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 20:54:39.947  7759  8003 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 20:54:39.959  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-25 20:54:39.961  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 20:54:39.961  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 20:54:39.961  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 20:54:39.962  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-25 20:54:39.962  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 20:54:39.964  7759  8003 D BluetoothAdapterProperties: Name is: G3
08-25 20:54:39.971  7759  8003 D BluetoothAdapterProperties: Scan Mode:20
08-25 20:54:39.972  7759  8003 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 20:54:39.972  7759  8003 D bt_hci_bdroid: postload
,08-25 20:54:39.975  7759  8043 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 20:54:39.976  7759  8041 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 20:54:39.977  7759  8003 D bte_conf: Device ID record 1 : primary
08-25 20:54:39.977  7759  8003 D bte_conf:   vendorId            = 00c4
08-25 20:54:39.977  7759  8003 D bte_conf:   vendorIdSource      = 0001
08-25 20:54:39.977  7759  8003 D bte_conf:   product             = 13a1
08-25 20:54:39.977  7759  8003 D bte_conf:   version             = 1000
08-25 20:54:39.977  7759  8003 D bte_conf:   clientExecutableURL = 
08-25 20:54:39.977  7759  8003 D bte_conf:   serviceDescription  = 
08-25 20:54:39.977  7759  8003 D bte_conf:   documentationURL    = 
08-25 20:54:39.977  7759  8003 D bte_conf: bte_load_did_conf no section named DID2.
08-25 20:54:39.980  7759  8041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:39.980  7759  8041 W bt-smp  : Plain text(LSB ~ MSB) = 27 2a 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:39.980  7759  8041 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 57 09 ca 37 93 33 ed 5a 91 da bb 40 59 40 48 
08-25 20:54:39.982  7759  8043 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 20:54:39.982  7759  8041 W bt-btm  : Stopping oneshot timer
08-25 20:54:39.979  8069  8069 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 20:54:39.987  7759  8043 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 20:54:39.988  7759  7999 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 20:54:39.988  7759  7999 D BluetoothAdapterProperties: ScanMode =  20
08-25 20:54:39.988  7759  7999 D BluetoothAdapterProperties: State =  11
08-25 20:54:39.988  7759  7999 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 20:54:39.989  7759  7999 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 20:54:39.989  7759  7999 D BluetoothAdapterProperties: Setting state to 12
08-25 20:54:39.989  7759  7999 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 20:54:39.989  7759  8003 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 20:54:39.989  8069  8069 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:39.993  1027  1115 D BluetoothManagerService: Message: 60
08-25 20:54:39.993  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 20:54:39.993  1027  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 20:54:39.996  7759  8043 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 20:54:40.000  7759  8064 E bt_mct  : hci lib postload completed
08-25 20:54:40.001  7759  8003 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 20:54:40.016  7759  7999 I BluetoothAdapterState: Entering On State
,08-25 20:54:40.019  1845  1860 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:40.022  7759  7999 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 20:54:40.022  7759  7999 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
,08-25 20:54:40.022  7759  7999 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 20:54:40.024  7759  7999 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 20:54:40.055  7759  8041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:40.055  7759  8041 W bt-smp  : Plain text(LSB ~ MSB) = f8 1b 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:40.055  7759  8041 W bt-smp  : Encrypted text(LSB ~ MSB) = 3f 63 46 35 8a 88 ec 69 22 cd 6e 4d 2f f2 51 88 
,08-25 20:54:40.058  7759  8041 W bt-btm  : Stopping oneshot timer
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:40.060  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:40.068  7759  7999 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-25 20:54:40.077  7759  8003 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 20:54:40.077  7759  8003 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 20:54:40.086  7759  8041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:40.086  7759  8041 W bt-smp  : Plain text(LSB ~ MSB) = ad 26 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:40.086  7759  8041 W bt-smp  : Encrypted text(LSB ~ MSB) = aa a2 45 23 25 93 ba fd ab d4 4b b5 b5 e1 85 5c 
,08-25 20:54:40.088  7759  8041 W bt-btm  : Stopping oneshot timer
08-25 20:54:40.089  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:40.092  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 20:54:40.110  7759  8041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:40.111  7759  8041 W bt-smp  : Plain text(LSB ~ MSB) = af b2 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:40.111  7759  8041 W bt-smp  : Encrypted text(LSB ~ MSB) = f2 da 04 14 0b a1 7e 81 80 ac dc 43 8e 3c 0e 04 
,08-25 20:54:40.112  7759  8041 W bt-btm  : Stopping oneshot timer
08-25 20:54:40.117  1027  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:40.118  8080  8080 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 20:54:40.118  1845  1861 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:40.125  1027  1027 D BluetoothHeadset: Proxy object connected
,08-25 20:54:40.126  1845  1845 D BluetoothHeadset: Proxy object connected
08-25 20:54:40.126  6972  7674 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 20:54:40.127  1845  1845 D BluetoothHeadset: Proxy object connected
,08-25 20:54:40.129  1845  1860 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:40.131  7759  8041 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 20:54:40.131  7759  8041 W bt-smp  : Plain text(LSB ~ MSB) = cb c8 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 20:54:40.131  7759  8041 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 b8 91 43 81 b2 b7 f0 68 e1 2b 96 40 19 bf 47 
08-25 20:54:40.131  7759  8041 W bt-btm  : Stopping oneshot timer
08-25 20:54:40.132  1027  1115 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 20:54:40.132  1845  1845 D BluetoothHeadset: Proxy object connected
08-25 20:54:40.132  6972  6972 D BluetoothA2dp: Proxy object connected
08-25 20:54:40.132  6972  6972 D A2dpProfile: Bluetooth service connected
08-25 20:54:40.132  1027  1027 D BluetoothA2dp: Proxy object connected
08-25 20:54:40.132  6972  6991 D BluetoothPan: onBluetoothStateChange on: true
08-25 20:54:40.133  6972  6991 D BluetoothPan: onBluetoothStateChange call bindService
08-25 20:54:40.136  6972  6972 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 20:54:40.136  6972  6972 D PanProfile: Bluetooth service connected
08-25 20:54:40.136  6972  6989 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 20:54:40.140  6972  6991 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 20:54:40.142  6972  6972 D BluetoothInputDevice: Proxy object connected
08-25 20:54:40.142  6972  6972 D HidProfile: Bluetooth service connected
,08-25 20:54:40.144  6972  6989 D BluetoothMap: onBluetoothStateChange: up=true
08-25 20:54:40.146  6972  7674 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 20:54:40.148  6972  6972 D BluetoothMap: Proxy object connected
08-25 20:54:40.148  6972  6972 D MapProfile: Bluetooth service connected
08-25 20:54:40.148  6972  6972 D BluetoothMap: getConnectedDevices()
08-25 20:54:40.149  7759  7775 V BluetoothMapService: getConnectedDevices()
08-25 20:54:40.150  1027  1115 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 20:54:40.150  1027  1115 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 20:54:40.151  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 20:54:40.151  6972  6972 D BluetoothHeadset: Proxy object connected
08-25 20:54:40.151  6972  6972 D HeadsetProfile: Bluetooth service connected
08-25 20:54:40.152  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.152  1933  2124 D LGBluetoothAPIService: Message: 1
08-25 20:54:40.152  1933  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 20:54:40.153  1933  2124 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-25 20:54:40.154  1933  2124 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 20:54:40.156  1593  1593 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 20:54:40.157  1027  1115 D BluetoothManagerService: Message: 40
08-25 20:54:40.158  1027  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 20:54:40.159  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:40.161  7759  7759 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.161  7759  7759 D BluetoothMapService: STATE_ON
08-25 20:54:40.163  6972  6972 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 20:54:40.166  6972  6972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 20:54:40.173  6972  6972 D DockEventReceiver: finishStartingService: stopping service
08-25 20:54:40.180  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
,08-25 20:54:40.180  7759  7759 V BluetoothPbapService: Pbap Service onCreate
08-25 20:54:40.180  7759  7759 V BluetoothPbapService: Starting PBAP service
08-25 20:54:40.182  7759  7759 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 20:54:40.183  7759  7759 V BluetoothPbapService: Pbap Service onBind
08-25 20:54:40.184  7759  7759 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.184  6972  6972 D BluetoothPbap: Proxy object connected
08-25 20:54:40.184  6972  6972 D PbapServerProfile: Bluetooth service connected
08-25 20:54:40.184  7759  7759 V BluetoothPbapService: state: 12
08-25 20:54:40.184  7759  7759 V BluetoothMapService: Handler(): got msg=1
08-25 20:54:40.185  7759  7759 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 20:54:40.185  7759  7759 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 20:54:40.186  7759  7759 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.186  7759  7759 V BluetoothPbapReceiver: ***********state = 12
08-25 20:54:40.186  7759  8094 D BluetoothMapMasInstance: MAS initSocket()
08-25 20:54:40.187  7759  8094 D BluetoothMapMasInstance:   masId = 00
08-25 20:54:40.187  7759  8094 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 20:54:40.187  7759  8094 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 20:54:40.187  7759  8094 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 20:54:40.187  7759  7759 V BluetoothPbapService: Handler(): got msg=1
08-25 20:54:40.188  7759  7759 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 20:54:40.189  7759  8095 V BluetoothPbapService: Pbap Service initSocket
08-25 20:54:40.190  1027  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:40.190  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:40.191  2185  2185 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 20:54:40.191  2185  2185 D c       : Getting all permits...
08-25 20:54:40.191  2185  2185 D a       : Opening database...
08-25 20:54:40.192  7759  8094 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:40.193  7759  8003 D BluetoothAdapterProperties: Scan Mode:21
08-25 20:54:40.193  7759  8003 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 20:54:40.194  7759  8094 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 20:54:40.194  7759  8094 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 20:54:40.194  2185  2185 D a       : Opening database auth.proximity.permit_store...
08-25 20:54:40.194  7759  8094 D BluetoothMapMasInstance: Accepting socket connection...
08-25 20:54:40.195  7759  8095 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:40.195  2185  2185 D a       : Closing database...
08-25 20:54:40.196  7759  8095 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 20:54:40.197  7759  8095 V BluetoothPbapService: Succeed to create listening socket 
08-25 20:54:40.197  7759  8095 V BluetoothPbapService: Accepting socket connection...
,08-25 20:54:40.199  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:40.209  6972  6972 D BluetoothPermissionRequest: onReceive
08-25 20:54:40.211  6972  6972 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-25 20:54:40.213  6972  6972 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 20:54:40.216  7759  7759 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 20:54:40.218  7759  7759 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 20:54:40.225  7759  7759 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 20:54:40.255  7759  7759 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 20:54:40.255  7759  7759 V BtOppService: onCreate
08-25 20:54:40.261  7759  7759 V BluetoothOppNotification: send message
08-25 20:54:40.264  7759  7759 V BtOppService: Starting RfcommListener
08-25 20:54:40.273  7759  7759 D BluetoothOppPreference: Dumping Names:  
08-25 20:54:40.273  7759  7759 D BluetoothOppPreference: {}
08-25 20:54:40.273  7759  7759 D BluetoothOppPreference: Dumping Channels:  
08-25 20:54:40.273  7759  7759 D BluetoothOppPreference: {}
08-25 20:54:40.276  7759  7759 V BtOppService: onStartCommand
,08-25 20:54:40.279  7759  8102 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 20:54:40.280  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.280  7759  7759 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 20:54:40.284  7759  7759 V BluetoothOppNotification: new notify threadi!
08-25 20:54:40.284  7759  8102 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 20:54:40.285  7759  8099 V BtOppService: Deleted complete outbound shares, number =  0
08-25 20:54:40.286  7759  7759 V BluetoothOppNotification: send delay message
08-25 20:54:40.287  7759  7759 V BtOppService: start RfcommListener
,08-25 20:54:40.288  7759  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 20:54:40.290  7759  8102 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30e1dc62 on behalf of 
08-25 20:54:40.293  7759  7759 V BtOppService: RfcommListener started
08-25 20:54:40.294  7759  8099 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 20:54:40.294  7759  8099 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 20:54:40.296  7759  8104 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 20:54:40.296  7759  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@371ce1f3 on behalf of 
08-25 20:54:40.297  1027  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:40.297  7759  8102 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 20:54:40.298  7759  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39166eb0 on behalf of 
08-25 20:54:40.299  7759  8104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:40.299  7759  8103 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 20:54:40.305  7759  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:40.305  7759  8104 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=77 mFd=75
08-25 20:54:40.305  7759  8104 V BtOppRfcommListener: Started RFCOMM listener....
08-25 20:54:40.306  7759  8104 I BtOppRfcommListener: Accept thread started.
08-25 20:54:40.306  7759  8104 V BtOppRfcommListener: Accepting connection...
08-25 20:54:40.306  7759  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3066f129 on behalf of 
08-25 20:54:40.307  7759  8103 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 20:54:40.310  7759  8103 V BluetoothOppNotification: outbound notification was removed.
08-25 20:54:40.310  7759  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:40.313  7759  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28055cae on behalf of 
08-25 20:54:40.314  7759  8103 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 20:54:40.317  7759  8103 V BluetoothOppNotification: inbound notification was removed.
08-25 20:54:40.317  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:40.317  7759  8103 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 20:54:40.318  7759  7759 V BluetoothFtpService: Ftp Service onCreate
08-25 20:54:40.318  7759  7759 I BluetoothFtpService: Ftp Service onCreate
08-25 20:54:40.318  7759  7759 V BluetoothFtpService: Ftp Service onStartCommand
08-25 20:54:40.318  7759  7759 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.318  7759  7759 V BluetoothFtpService: Starting Listening on sockets
08-25 20:54:40.318  7759  7759 V BtOppService: ContentObserver received notification
08-25 20:54:40.319  7759  7759 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 20:54:40.319  7759  7759 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 20:54:40.319  7759  7759 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 20:54:40.319  7759  7759 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.319  7759  7759 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 20:54:40.319  7759  7759 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 20:54:40.322  7759  8105 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 20:54:40.322  7759  8105 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 20:54:40.323  7759  7759 V BtOppService: ContentObserver received notification
08-25 20:54:40.323  7759  7759 V BluetoothFtpService: Handler(): got msg=1
08-25 20:54:40.324  7759  7759 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 20:54:40.324  7759  7759 V BluetoothFtpService: Ftp Service initSocket
08-25 20:54:40.324  7759  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39ebc5dc on behalf of 
08-25 20:54:40.327  7759  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23d476e5 on behalf of 
08-25 20:54:40.327  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:40.328  7759  7759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:40.328  7759  8105 V BluetoothOppNotification: update too frequent, put in queue
08-25 20:54:40.329  7759  8105 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 20:54:40.329  7759  8105 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-25 20:54:40.330  7759  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17ce95ba on behalf of 
08-25 20:54:40.331  7759  8105 V BluetoothOppNotification: update too frequent, put in queue
08-25 20:54:40.333  7759  8105 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 20:54:40.333  7759  7759 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=77
08-25 20:54:40.334  7759  7759 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 20:54:40.341  7759  8106 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 20:54:40.361  7759  7759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@194970c6
08-25 20:54:40.361  7759  7759 V BluetoothSapService: Sap Service onCreate
08-25 20:54:40.363  7759  7759 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 20:54:40.363  7759  7759 V BluetoothSapService: state: 12
08-25 20:54:40.363  7759  7759 V BluetoothSapService: Starting SAP server process
,08-25 20:54:40.365  7759  7759 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 20:54:40.367  7759  8108 V BluetoothSapService: Sap Service initRfcommSocket
08-25 20:54:40.359  8107  8107 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 20:54:40.367  1027  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:40.359  8107  8107 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:40.368  7759  8108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 20:54:40.370  7759  8108 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 20:54:40.372  7759  8108 V BluetoothSapService: Succeed to create listening socket 
08-25 20:54:40.372  7759  8108 V BluetoothSapService: Accepting socket connection...
08-25 20:54:40.379  8107  8107 V BT_SAP  : Event pipe created
08-25 20:54:40.379  8107  8107 V BT_SAP  : create_server_socket qcom.sap.server
08-25 20:54:40.379  8107  8107 V BT_SAP  : created socket fd 6
,08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:40.722  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:54:40.727  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:40.730  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:40.730  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@225ce08b added. We now have 8 listener(s)
08-25 20:54:40.730  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:40.733  1027  1968 D WifiServiceImplEx: setWifiEnabled: false pid=6854, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 20:54:40.733  1027  1968 D WifiService: setWifiEnabled: false pid=6854, uid=10118
08-25 20:54:40.733  1027  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 20:54:40.738  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:40.742  1027  2005 D WifiServiceImplEx: setWifiEnabled: true pid=6854, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 20:54:40.743  1027  2005 D WifiService: setWifiEnabled: true pid=6854, uid=10118
08-25 20:54:40.743  1027  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 20:54:40.761  1027  1477 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 20:54:40.761  1027  1477 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-25 20:54:40.765  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 20:54:40.765  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 20:54:40.765  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 20:54:40.766  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 20:54:40.766  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 20:54:40.766  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 20:54:40.766  1027  1477 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-25 20:54:40.766  1027  1477 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 20:54:40.766  1027  1477 E WifiHW  : unknown target_country: EU , set to default
,08-25 20:54:40.766  1027  1477 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 20:54:40.766  1027  1477 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-25 20:54:40.766  1027  1477 I WifiUtil: gEnableBmps=1
08-25 20:54:41.288  7759  7759 V BluetoothOppNotification: new notify threadi!
,08-25 20:54:41.289  7759  7759 V BluetoothOppNotification: send delay message
,08-25 20:54:41.309  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-25 20:54:41.316  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15c05386 on behalf of 
08-25 20:54:41.317  7759  8127 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 20:54:41.320  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:41.322  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bfa9447 on behalf of 
08-25 20:54:41.323  7759  8127 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-25 20:54:41.327  7759  8127 V BluetoothOppNotification: outbound notification was removed.,
08-25 20:54:41.327  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 20:54:41.329  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18c8f474 on behalf of 
08-25 20:54:41.330  7759  8127 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 20:54:41.331  7759  8127 V BluetoothOppNotification: inbound notification was removed.
08-25 20:54:41.332  7759  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 20:54:41.333  7759  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dc39d9d on behalf of 
08-25 20:54:41.408   312   885 D SoftapController: Softap fwReload - Ok
,08-25 20:54:41.421  1027  1477 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (651ms)
,08-25 20:54:41.426   312   885 D CommandListener: Setting iface cfg
08-25 20:54:41.426   312   885 D CommandListener: Trying to bring down wlan0
08-25 20:54:41.440  1027  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 20:54:41.440  1027  1115 D Tethering: InitialState.processMessage what=4
,08-25 20:54:41.449   312   885 D CommandListener: Clearing all IP addresses on wlan0
08-25 20:54:41.452  1027  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 20:54:41.458  1027  1477 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 20:54:41.469  8129  8129 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:41.475  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:41.475  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:41.475  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:41.469  8129  8129 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:41.483  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:41.496  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-25 20:54:41.502  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 20:54:41.519  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:41.522  1027  1477 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 20:54:41.523  1027  1477 D WifiMonitor: connecting to supplicant
,08-25 20:54:41.552  8129  8129 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 20:54:41.596  8129  8129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 20:54:41.596  8129  8129 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 20:54:41.628  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-25 20:54:41.628  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 20:54:41.628  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 20:54:41.629  6972  6972 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 20:54:41.636  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 20:54:41.638  6972  6972 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-25 20:54:41.638  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 20:54:41.638  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 20:54:41.638  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 20:54:41.638  6972  6972 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 20:54:41.639  6972  6972 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 20:54:41.643  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 20:54:41.643  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 20:54:41.643  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 20:54:41.643  6972  6972 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 20:54:41.643  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 20:54:41.644  6972  6972 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 20:54:41.644  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 20:54:41.644  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 20:54:41.644  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 20:54:41.644  6972  6972 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 20:54:41.644  6972  6972 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 20:54:41.659  8129  8129 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 20:54:41.677  7860  7871 E UEI.SmartControl: file observer is disposed!
,08-25 20:54:41.688  1027  1042 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8146 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 20:54:41.722  8129  8129 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-25 20:54:41.725  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 20:54:41.726  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 20:54:41.727  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 20:54:41.727  1027  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 20:54:41.727  1027  8164 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 20:54:41.727  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 20:54:41.727  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 20:54:41.727  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 20:54:41.727  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 20:54:41.727  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 20:54:41.727  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 20:54:41.728  1027  1477 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 20:54:41.728  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:41.729  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:41.729  1027  1477 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:41.730  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:41.731  1027  1477 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 20:54:41.731  1027  1477 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 20:54:41.731  1027  1477 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 20:54:41.731  1027  1477 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 20:54:41.732  1027  1477 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-25 20:54:41.732  1027  1477 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 20:54:41.732  1027  1477 E WifiStateMachine: useWiFiOffloading() : false
08-25 20:54:41.732  1027  1477 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 20:54:41.732  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:41.732  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:41.733  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:41.733  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:41.733  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 20:54:41.734  1933  1933 D WfdService: Waiting for WifiP2p enabling
08-25 20:54:41.735  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:41.735  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 20:54:41.736  1027  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 20:54:41.737  1027  1477 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 20:54:41.737  1027  1477 D WifiNative-wlan0: SET update_config 1: returned true
08-25 20:54:41.737  1027  1477 D WifiConfigStore: Loading config and enabling all networks 
08-25 20:54:41.738  1027  1477 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 20:54:41.738  1027  1477 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:41.738  6854  6854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 20:54:41.739  6854  6854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:41.744  1027  1477 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-25 20:54:41.753  1027  1477 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 20:54:41.753  1027  1477 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 20:54:41.755  1027  1477 D WifiStateMachine: enableVerboseLogging : level 2
08-25 20:54:41.755  1027  1477 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 20:54:41.755  1027  1477 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 20:54:41.755  1027  1477 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 20:54:41.755  1027  1477 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 20:54:41.755  1027  1477 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 20:54:41.756  1027  1477 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 20:54:41.756  1027  1477 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 20:54:41.756  1027  1477 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 20:54:41.756  1027  1477 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 20:54:41.756  1027  1477 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 20:54:41.756  1027  1477 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 20:54:41.757  1027  1477 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 20:54:41.757  1027  1477 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 20:54:41.758  1027  1477 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 20:54:41.777  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 20:54:41.779  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 20:54:41.783  6854  6932 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 20:54:41.784  6854  6932 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 20:54:41.785  6854  6932 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5761995 Bundle[{}]
08-25 20:54:41.785  6854  6932 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 20:54:41.785  6854  6932 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 20:54:41.786  6854  6932 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 20:54:41.786  6854  6932 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 20:54:41.787  6854  6932 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 20:54:41.787  6854  6932 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 20:54:41.792  6854  6932 I System.out: Running OutgoingSocketThread
,08-25 20:54:41.793  6854  8170 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 891)
08-25 20:54:41.794  6854  8170 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58186
08-25 20:54:41.795  6854  8170 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 20:54:41.808  1027  2043 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8171 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 20:54:41.812  1027  1477 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 20:54:41.812  1027  1477 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 20:54:41.812  1933  1933 D WfdsService: Supplicant Connection state is changed : true
08-25 20:54:41.813  1933  2293 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 20:54:41.813  1933  2293 D WfdsService: Set the WFDS Monitor: true
08-25 20:54:41.813  1933  2293 D WfdsMonitor: WfdsMonitorThread create
08-25 20:54:41.813  1933  2293 D WfdsMonitor: WFDS Monitor is created and started
08-25 20:54:41.813  1933  2293 D WfdsService: WiFi: Supplicant connection re-established
08-25 20:54:41.813  1027  1477 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 20:54:41.813  1027  1477 D WifiNative-HAL: Setting external_sim to 1
08-25 20:54:41.813  1027  1477 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 20:54:41.813  7788  7788 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:41.814  1027  1477 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 20:54:41.814  1027  1477 I WifiNative-HAL: startHal
08-25 20:54:41.814  1027  1477 D wifi    : setting scan oui 0xaf74f3e0
08-25 20:54:41.814  1027  1477 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 20:54:41.814  1027  1477 I WifiNative-HAL: startHal
08-25 20:54:41.814  1027  1477 D wifi    : setting scan oui 0xaf74f3e0
08-25 20:54:41.815  1027  1477 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 20:54:41.815  1027  1477 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 20:54:41.815  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 20:54:41.815  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 20:54:41.815  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 20:54:41.816  1933  8181 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-25 20:54:41.816  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 20:54:41.816  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 20:54:41.816  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 20:54:41.816  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 20:54:41.816  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 20:54:41.817  1933  8181 E CtrlSupplicant: Succeed to open control connection
08-25 20:54:41.817  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 20:54:41.817  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 20:54:41.817  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 20:54:41.817  1933  8181 E CtrlSupplicant: Succeed to open monitor connection
08-25 20:54:41.817  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 20:54:41.817  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 20:54:41.818  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 20:54:41.818  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 20:54:41.818  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 20:54:41.818  8129  8129 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 20:54:41.818  8146  8168 W FormManager: Network not available. Please check & try again.
08-25 20:54:41.819  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 20:54:41.819  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 20:54:41.819  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 20:54:41.819  1027  1477 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 20:54:41.819  1933  8181 D WfdsMonitor: Supplicant connection established
08-25 20:54:41.819  1933  2293 D WfdsService: Connected to the supplicant for wfds
08-25 20:54:41.820  1027  1477 E WifiNative: : [210,100,283 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 20:54:41.820  1027  1477 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 20:54:41.821  1027  1477 D WifiNative-wlan0: RECONNECT: returned true
08-25 20:54:41.821  1027  1477 D WifiNative-wlan0: doString: [STATUS]
08-25 20:54:41.821  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 20:54:41.821  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 20:54:41.821  1027  1477 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 20:54:41.821  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:41.822  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:41.822  1027  1428 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.824   312   885 D CommandListener: Setting iface cfg
08-25 20:54:41.824   312   885 D CommandListener: Trying to bring up p2p0
08-25 20:54:41.825  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 20:54:41.825  1027  1428 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 20:54:41.825  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-25 20:54:41.825  1027  1428 D LGWifiP2pService: P2pEnablingState
08-25 20:54:41.825  1027  1428 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.825  1027  1549 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.825  1027  1548 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.uti,l.StateMachine$SmHandler }
08-25 20:54:41.825  1027  1548 I WifiNative-HAL: startHal
08-25 20:54:41.825  1027  1477 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 20:54:41.826  1027  1548 D wifi    : getting scan capabilities on interface[1] = 0xaf74f3e0
08-25 20:54:41.826  1027  1548 D wifi    : failed to get capabilities : -3
,08-25 20:54:41.825  1027  1428 D LGWifiP2pService: P2p socket connection successful
08-25 20:54:41.826  1027  1428 D LGWifiP2pService: P2pEnabledState
08-25 20:54:41.826  1027  1548 E WifiScanningService: could not get scan capabilities
08-25 20:54:41.826  1027  1477 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 20:54:41.826  1027  1428 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 20:54:41.826  1027  1428 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 20:54:41.827  1027  1428 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 20:54:41.828  1027  1428 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 20:54:41.828  1027  1428 D WifiNative-p2p0: SET device_name G3: returned true
08-25 20:54:41.828  1027  1428 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 20:54:41.828  1027  1428 D LGWifiP2pService: before postfix = G3
08-25 20:54:41.828  1027  1428 D WifiServerServiceExt: postfix byte check : 2
08-25 20:54:41.828  1027  1428 D LGWifiP2pService: after postfix = G3
08-25 20:54:41.828  1027  1428 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 20:54:41.829  1027  1428 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 20:54:41.829  1027  1428 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 20:54:41.829  1027  1428 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 20:54:41.829  1027  1428 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 20:54:41.829  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 20:54:41.829  1933  1933 D WfdsService: WifiP2pState is changed : true
08-25 20:54:41.830  1933  1933 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 20:54:41.830  1933  1933 D WfdsService: isConnected: false
08-25 20:54:41.830  1933  2293 D WfdsService: Receive the WFDS_ENABLE Method
08-25 20:54:41.830  1933  2293 D WfdsService: Set the WFDS Monitor: true
08-25 20:54:41.831  1027  1428 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 20:54:41.831  1933  2293 D WfdsService: Connected to the supplicant for wfds
08-25 20:54:41.831  1027  1428 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 20:54:41.831  1933  2293 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 20:54:41.831  8129  8129 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 20:54:41.831  1027  1428 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 20:54:41.831  1027  1428 D WifiNative-HAL: p2pGetDeviceAddress
08-25 20:54:41.831  1933  2293 D WfdsService: selectPreferredScanChannel [36]
08-25 20:54:41.831  1027  1428 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 20:54:41.831  1933  2293 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 20:54:41.832  1027  1428 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 20:54:41.832  1027  1428 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 20:54:41.832  1027  1428 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 20:54:41.832  1027  1428 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 20:54:41.833  1027  1428 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 20:54:41.833  1027  1428 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 20:54:41.834  1027  1428 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 20:54:41.834  1027  1428 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 20:54:41.835  1027  1477 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 20:54:41.836  1027  1477 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 20:54:41.836  1027  1477 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 20:54:41.837  1933  1933 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 20:54:41.837  1933  1933 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 20:54:41.837  1027  1477 E WifiState,Machine:  ConnectModeState what:132106 1 0
08-25 20:54:41.837  1933  1933 D WfdsService: Update P2p Interface State: 3
08-25 20:54:41.838  1027  1477 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 20:54:41.838  1027  1477 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-25 20:54:41.842  8129  8129 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 20:54:41.843  1027  1428 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 20:54:41.843  1027  1428 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 20:54:41.843  1027  1477 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 20:54:41.843  1027  1428 D LGWifiP2pService: InactiveState
08-25 20:54:41.843  1027  1428 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.843  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.843  1027  1428 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 20:54:41.844  1027  1477 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 20:54:41.844  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 20:54:41.844  1027  1477 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 20:54:41.844  1027  1477 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 20:54:41.844  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:41.845  8129  8129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 20:54:41.845  1027  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 20:54:41.845  1027  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:41.845  8129  8129 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 20:54:41.845  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:41.845  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:41.845  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.845  1027  1428 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 20:54:41.845  1027  1428 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.845  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.845  1027  1428 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.846  1027  1428 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachin,e$SmHandler }
08-25 20:54:41.846  1933  8181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 20:54:41.847  1933  8181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.847  1933  8181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.847  1027  1027 E WifiServerServiceExt: No p2p device connected
08-25 20:54:41.847  1027  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.847  1027  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.847  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.847  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.847  1027  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.847  1027  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.847  1027  1477 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 20:54:41.847  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.847  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.848  1027  1477 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 20:54:41.848  1027  1477 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 20:54:41.848  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 20:54:41.849  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 20:54:41.849  1933  2293 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 20:54:41.849  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:41.849  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 20:54:41.849  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:41.849  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 20:54:41.849  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 20:54:41.850  8129  8129 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 20:54:41.850  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.851  1027  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.851  1027  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.851  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.851  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.851  8129  8129 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.852  1933  8181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.852  1933  8181 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.852  1027  1477 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 20:54:41.852  1027  1477 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 20:54:41.853  1027  1428 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.853  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:41.853  1027  1477 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 20:54:41.853  1027  1477 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 20:54:41.853  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 20:54:41.854  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 20:54:41.854  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 20:54:41.854  1027  8164 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 20:54:41.854  1027  8164 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.854  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.854  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 20:54:41.854  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 20:54:41.854  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 20:54:41.854  1027  8164 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 20:54:41.854  1027  8164 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 20:54:41.855  1027  1477 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 20:54:41.855  1027  1477 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 20:54:41.855  1027  1477 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 20:54:41.855  1027  1477 D WifiNative-wlan0: doBoolean: SCAN
08-25 20:54:41.856  1027  1477 D WifiNative-wlan0: SCAN: returned false
08-25 20:54:41.856  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=210137  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 20:54:41.858  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=210139  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 20:54:41.858  8146  8169 V FormManager: Network unavailable.
08-25 20:54:41.858  1027  1477 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:41.859  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwor,k: false]
08-25 20:54:41.859  1027  1477 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:41.859  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:41.859  1027  1477 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:41.860  1027  1477 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:41.860  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:41.860  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:41.860  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 20:54:41.860  1027  1477 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 20:54:41.861  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:41.862  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:41.862  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-25 20:54:41.864  8146  8169 V FormManager: Network unavailable.
08-25 20:54:41.878  1027  1042 I ActivityManager: Killing 7246:com.android.chrome/u0a57 (adj 15): empty #17
,08-25 20:54:41.892  8171  8171 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 20:54:41.934  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 20:54:41.935  1027  2004 W libprocessgroup: failed to open /acct/uid_10057/pid_7246/cgroup.procs: No such file or directory
,08-25 20:54:41.948  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 20:54:41.952  1027  1896 I ActivityManager: Killing 7270:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 20:54:42.061  1027  1567 W libprocessgroup: failed to open /acct/uid_10062/pid_7270/cgroup.procs: No such file or directory
,08-25 20:54:42.096  8171  8171 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 20:54:42.099  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 20:54:42.100  8146  8193 W FormManager: Network not available. Please check & try again.
,08-25 20:54:42.115  8146  8194 V FormManager: Network unavailable.
08-25 20:54:42.120  8146  8194 V FormManager: Network unavailable.
,08-25 20:54:42.129  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:42.145  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 20:54:42.145  4812  4812 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 20:54:42.147  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 20:54:42.149  4812  4812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 20:54:42.157  4812  8198 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 20:54:42.162  4812  8199 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 20:54:42.162  4812  8199 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 20:54:42.216  1027  2024 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8200 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 20:54:42.381  8200  8200 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 20:54:42.381  8200  8200 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 20:54:42.394  8200  8200 V [BNRBootReceiver]: Boot Receiver Return
08-25 20:54:42.395  8200  8200 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-25 20:54:42.406  8129  8129 E wpa_supplicant: USIM:  scard_init function
,08-25 20:54:42.406  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-25 20:54:42.406  1027  8164 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 20:54:42.406  8129  8129 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 20:54:42.406  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 20:54:42.406  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-25 20:54:42.406  1027  8164 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 20:54:42.407  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 20:54:42.407  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 20:54:42.407  1027  1477 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:42.408  1027  1477 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:42.408  1027  1477 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:42.409  1027  1477 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 20:54:42.409  1027  1477 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-25 20:54:42.463  1027  1896 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 20:54:42.466  1027  1896 I ActivityManager: Killing 7300:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-25 20:54:42.525  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=210805  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 20:54:42.531  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=210812  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 20:54:42.534  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 20:54:42.534  8129  8129 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 20:54:42.534  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 20:54:42.534  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 20:54:42.534  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 20:54:42.534  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:42.535  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:42.545  1027  1727 W libprocessgroup: failed to open /acct/uid_10085/pid_7300/cgroup.procs: No such file or directory
,08-25 20:54:42.549  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:42.549  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:42.549  8129  8129 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 20:54:42.549  8129  8129 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 20:54:42.550  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 20:54:42.551  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 20:54:42.551  1027  8164 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 20:54:42.551  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 20:54:42.551  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 20:54:42.551  1027  8164 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 20:54:42.552  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:42.552  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:42.556  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.556  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.556  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 20:54:42.556  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.557  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:42.558  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:42.562  1027  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 20:54:42.563  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210844  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 20:54:42.564  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210845  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 20:54:42.565  1027  1477 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210846
08-25 20:54:42.565  1027  1477 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210846
08-25 20:54:42.566  1027  1477 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210847
08-25 20:54:42.567  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210847
08-25 20:54:42.567  1027  1477 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210848
08-25 20:54:42.568  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.568  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.568  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 20:54:42.568  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:42.568  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 20:54:42.569  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=210850  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 20:54:42.571  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.572  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:42.572  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=210853  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 20:54:42.573  1027  1477 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210854  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-25 20:54:42.574  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210855  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 20:54:42.576  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.576  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.576  1027  1477 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210857
08-25 20:54:42.576  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-25 20:54:42.576  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.576  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.576  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 20:54:42.576  1027  1477 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210857
08-25 20:54:42.577  1027  1477 D WifiNative-wlan0: doString: [STATUS]
08-25 20:54:42.578  1027  1477 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 20:54:42.578  1027  8164 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 20:54:42.578  1027  8164 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 20:54:42.580  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.581  1027  1477 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 20:54:42.587  1027  1477 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 20:54:42.588  1027  1477 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 20:54:42.590  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.590  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:42.594  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.594  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.594  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 20:54:42.594  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.596  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 20:54:42.596  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:42.597  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.597  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.597  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 20:54:42.597  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.599  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.599  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:42.600  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.600  8218  8218 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 20:54:42.607  1027  1477 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 20:54:42.607  1027  1535 D ConnectivityService: Got NetworkAgent Messenger
08-25 20:54:42.607  1027  1477 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 20:54:42.607  1027  1477 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 20:54:42.607  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 20:54:42.607  1027  1535 D ConnectivityService: NetworkAgent connected
08-25 20:54:42.608  1027  1477 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 20:54:42.608  1027  1477 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 20:54:42.613  1027  1477 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 20:54:42.614  1027  1477 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 20:54:42.614  1027  1477 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 20:54:42.614  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.614  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:42.614  1027  1477 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 20:54:42.614  1027  1477 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 20:54:42.615  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.620  1027  1477 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 20:54:42.622   312   885 D CommandListener: Setting iface cfg
08-25 20:54:42.625  1027  1477 E WifiStateMachine: Start Dhcp Watchdog 3
08-25 20:54:42.625  1027  8236 D DhcpStateMachine: StoppedState
08-25 20:54:42.625  1027  8236 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.625  1027  8236 D DhcpStateMachine: WaitBeforeStartState
08-25 20:54:42.625  1027  1477 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210906  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:42.626  1027  1477 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210907  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:42.626  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210907  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:42.628  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:42.628  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-25 20:54:42.629  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:42.629  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:42.630  1027  1477 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:42.630  1027  1477 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:42.631  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:42.631  1027  1477 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 20:54:42.632  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:42.633  1027  1027 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 20:54:42.634  1027  1477 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210915  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:42.635  1027  1477 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210916  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:42.636  1027  1477 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210916  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 20:54:42.637  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14372] from screen [on:0 period:-1022499891] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 20:54:42.638  8218  8218 D PluginManager: init()
08-25 20:54:42.639  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1022499889] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 20:54:42.639  1027  1477 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 20:54:42.640  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:42.640  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-25 20:54:42.643  1027  1535 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-25 20:54:42.643  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.644  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.644  1027  1477 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.645  1027  1477 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.645  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.645  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.646  1027  1535 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 20:54:42.646  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=175,0,0
08-25 20:54:42.646  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=175,0,0
08-25 20:54:42.647  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 20:54:42.647  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 20:54:42.649  1027  1477 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 20:54:42.649  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 20:54:42.651  1027  1477 D WifiNative-wlan0: SET ps 0: returned true
08-25 20:54:42.651  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 20:54:42.651  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-25 20:54:42.652  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 20:54:42.652  1027  1477 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 20:54:42.652  1027  1477 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-25 20:54:42.652  1027  1477 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 20:54:42.652  1027  1428 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c0272e4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.652  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.652  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c0272e4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.652  1027  8236 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.652  1027  8236 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 20:54:42.653   312   885 D CommandListener: Setting iface cfg
08-25 20:54:42.653   312   885 D CommandListener: Trying to bring up wlan0
08-25 20:54:42.654  1027  1477 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 20:54:42.656  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:42.656  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 20:54:42.657  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 20:54:42.657  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 20:54:42.658  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.659  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.659  1027  1477 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.659  1027  1477 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.660  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.660  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 20:54:42.661  1027  1535 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 20:54:42.661  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 20:54:42.661  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 20:54:42.662  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 20:54:42.662  1027  1428 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.662  1027  1428 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.662  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 20:54:42.662  1027  1477 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 20:54:42.662  1027  1477 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 20:54:42.662  8129  8129 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 20:54:42.664  1027  1477 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 20:54:42.664  1027  1477 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 20:54:42.665  1027  1477 D WifiNative-wlan0: SET ps 1: returned true
08-25 20:54:42.665  1027  1535 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 20:54:42.665  1027  1477 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 20:54:42.666  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 20:54:42.666  1027  1477 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 20:54:42.666  1027  1535 D ConnectivityService:, ignoring duplicate network state non-change
08-25 20:54:42.669  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.669  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 20:54:42.672  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.672  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.672  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.672  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 20:54:42.674  1027  1535 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 20:54:42.674  1027  1535 D ConnectivityService: Adding iface wlan0 to network 102
08-25 20:54:42.676  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.677  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.677  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 20:54:42.678  1027  1477 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 20:54:42.680  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 20:54:42.687  1933  1933 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 20:54:42.687  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.687  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.687  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-25 20:54:42.689  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 20:54:42.691  7860  7982 D UEI.SmartControl: Internal timer expired: 3
08-25 20:54:42.691  7860  7982 D UEI.SmartControl: unbind internal service
08-25 20:54:42.694  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.694  1593  1593 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 20:54:42.695  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.695  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 20:54:42.695  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 20:54:42.696  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 20:54:42.696  7860  7860 D UEI.SmartControl: Service.onUnbind: IControl
08-25 20:54:42.696  7860  7860 D UEI.SmartControl: Service.onDestroy
08-25 20:54:42.696  7860  7860 D UEI.SmartControl: Lock is in USE false
08-25 20:54:42.696  7860  7860 D UEI.SmartControl: unbind internal service
08-25 20:54:42.697  7860  7860 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3dbfd29e
08-25 20:54:42.697  7860  7860 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,08-25 20:54:42.697  7860  7860 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-25 20:54:42.697  7860  7860 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:42.697  7860  7860 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 20:54:42.697  7860  7860 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:54:42.698  7860  7860 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 20:54:42.698  7860  7860 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 20:54:42.698  7860  7860 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 20:54:42.698  7860  7860 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3dbfd29e
08-25 20:54:42.698  7860  7860 D serial_port: close(fd = 24)
08-25 20:54:42.698  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.698  1593  1593 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 20:54:42.698  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.699  1027  1535 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 20:54:42.699  1027  1535 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 20:54:42.701  1027  1535 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 20:54:42.702   312   885 E Netd    : netlink response contains error (File exists)
08-25 20:54:42.702  1027  1535 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 20:54:42.702  1593  1593 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 20:54:42.702  1593  1593 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 20:54:42.702  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.703  1027  1535 D ConnectivityService: addLocalRoutetoDefaultNetwork
,08-25 20:54:42.703  1027  1535 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-25 20:54:42.703  1027  1535 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-25 20:54:42.704  7860  7860 I UEI.SmartControl: Serial port is closed.
08-25 20:54:42.704  7860  7860 I UEI.SmartControl: Serial port is closed.
08-25 20:54:42.704  7860  7860 D UEI.SmartControl: Blaster closed
08-25 20:54:42.704  7860  7860 D UEI.SmartControl: Shut down QS...
08-25 20:54:42.704  7860  7860 D UEI.SmartControl: Stopping QS lib
08-25 20:54:42.704  7860  7860 D UEI.SmartControl: QS lib stop result = true
08-25 20:54:42.704  7860  7860 D UEI.SmartControl: Stopped QS lib
08-25 20:54:42.704  7860  7860 D UEI.SmartControl: QS shutdown complete
08-25 20:54:42.707  1027  1535 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 20:54:42.708  1027  1535 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 20:54:42.708  1027  1535 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 20:54:42.708  1027  1535 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 20:54:42.708  1027  8235 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.708  1027  8235 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 20:54:42.708  1027  1535 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:42.708  1027  1535 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:42.708  1027  8235 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 20:54:42.708  1027  1535 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 20:54:42.708  1027  1535 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.708  1027  8235 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 20:54:42.708  1027  1535 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 20:54:42.708  1027  1535 D ConnectivityService: currentScore = 0, newScore = 20
08-25 20:54:42.708  1027  1535 D ConnectivityService:    accepting network in place of null
08-25 20:54:42.708  1027  1535 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.708  1027  1477 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.708  1027  1477 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:42.710  1027  1535 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NO,T_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 20:54:42.710  1027  1535 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 20:54:42.711  1845  1845 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.711  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 20:54:42.711   312  8246 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 20:54:42.711  1845  1845 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 20:54:42.712  1027  1535 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 20:54:42.712  1027  1535 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 20:54:42.713  1027  1535 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 20:54:42.713  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 20:54:42.713  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 20:54:42.713  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 20:54:42.713  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 20:54:42.714  1027  1535 D ConnectivityService: validation of new default Network = false
08-25 20:54:42.714  1027  1535 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 20:54:42.714  1027  1535 D DSQN    : enableDataServiceNotify 
08-25 20:54:42.714  1027  1535 D DSQN    : start dsqn bin
,08-25 20:54:42.719  8247  8247 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:42.719  8247  8247 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:42.726  1027  1535 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 20:54:42.726  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.726  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:42.726  1027  1535 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:42.727  1593  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 20:54:42.732  8247  8247 E DSQN    : DSQN ssw
,08-25 20:54:42.735  1027  1426 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 20:54:42.740  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:42.741  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.741  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.752   312  8246 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-25 20:54:42.784   312  8246 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 20:54:42.794  6854  6932 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 892)
08-25 20:54:42.794  6854  6932 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 892)
08-25 20:54:42.801  6854  6932 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 897)
08-25 20:54:42.802  6854  6932 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 20:54:42.802  6854  6932 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 898)
08-25 20:54:42.808  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.808  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24782568 added. We now have 2 listener(s)
08-25 20:54:42.812  1027  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 20:54:42.818  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:42.818  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.818  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.818   312   884 D LGDataListener: argv[0]=dsqncommand
08-25 20:54:42.818   312   884 D LGDataListener: argv[1]=wlan0
08-25 20:54:42.818   312   884 D LGDataListener: argv[2]=1
08-25 20:54:42.818  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.819   312   884 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 20:54:42.819  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38fdcd81 added. We now have 9 listener(s)
08-25 20:54:42.819  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.819  1027  1112 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 20:54:42.819  1027  1112 D DSQN    : start to monitor internet connection
08-25 20:54:42.819  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:54:42.824  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:42.829  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:54:42.833  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.833  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:42.833  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.834  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f36fa67 added. We now have 3 listener(s)
08-25 20:54:42.834  1027  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.836  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:42.836  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.836  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.836  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.836  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d5e3014 added. We now have 10 listener(s)
08-25 20:54:42.836  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.836  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:42.836  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:42.836  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:42.836  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:42.836  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.836  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:42.836  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:42.836  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24782568 removed from the list
08-25 20:54:42.836  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.836  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38fdcd81 removed from the list
08-25 20:54:42.837  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:42.839  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:42.839  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:42.840  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.840  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.840  6854  6932 D org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 20:54:42.844  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:42.844  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:42.844  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.844  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38fdcd81 not in the list
08-25 20:54:42.844  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.844  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.847  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:42.847  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:42.847  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 20:54:42.847  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d5e3014 removed from the list
08-25 20:54:42.847  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:42.848  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.848  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.848  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:42.848  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f36fa67 removed from the list
,08-25 20:54:42.849  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.850  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@738c0bd added. We now have 2 listener(s)
08-25 20:54:42.850  1027  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.853  1027  8235 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 18:54:42 GMT], X-Android-Received-Millis=[1472151282852], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472151282818]}
08-25 20:54:42.853  1027  8235 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 20:54:42.853  1027  8235 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 20:54:42.853  1027  1535 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-25 20:54:42.853  1027  1535 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 20:54:42.854  1027  1535 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:42.854  1027  1535 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:42.854  1027  1535 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 20:54:42.854  1027  1535 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-25 20:54:42.854  1027  1535 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 20:54:42.854  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.855  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:42.856  1027  1535 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 20:54:42.856  1593  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 20:54:42.857  1027  1535 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.857  1027  1477 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.858  1027  1477 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 20:54:42.859  1027  8236 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 20:54:42.859  1845  1845 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:42.860  1845  1845 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 20:54:42.860  1027  8236 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 20:54:42.860  1027  8236 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 20:54:42.860  1027  1535 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 20:54:42.859  8253  8253 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:42.859  8253  8253 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 20:54:42.869  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 20:54:42.870  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.870  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.870  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.871  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d11d6b2 added. We now have 9 listener(s)
08-25 20:54:42.871  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.871  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:54:42.876  8253  8253 I dhcpcd  : version 5.5.6 starting
08-25 20:54:42.878  8253  8253 E dhcpcd  : get_duid: m
08-25 20:54:42.878  8253  8253 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 20:54:42.878  8253  8253 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 20:54:42.880  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:42.890  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:54:42.894  1593  1593 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 20:54:42.895  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.896  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.896  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:42.896  1593  1593 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 20:54:42.897  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.897  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf83980 added. We now have 3 listener(s)
08-25 20:54:42.899  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.902  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:42.906  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:42.907  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:42.907  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.907  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.907  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.907  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3335abb9 added. We now have 10 listener(s)
08-25 20:54:42.907  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.907  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:42.907  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 20:54:42.908  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:54:42.908  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:42.908  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 20:54:42.911  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 20:54:42.911  1027  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.917  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 20:54:42.918  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 20:54:42.920  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:54:42.920  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:42.922  6854  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 20:54:42.922  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:42.922  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:42.925  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:42.925  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:42.925  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:42.925  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:54:42.925  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.925  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:42.925  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:42.925  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@738c0bd removed from the list
08-25 20:54:42.925  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.925  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d11d6b2 removed from the list
08-25 20:54:42.926  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:42.926  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.926  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.926  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.927  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:42.927  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:42.927  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.927  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d11d6b2 not in the list
08-25 20:54:42.927  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.927  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.928  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:42.929  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:42.929  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:42.929  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:42.929  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.929  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3335abb9 removed from the list
08-25 20:54:42.929  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:42.929  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.929  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.929  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:42.929  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf83980 removed from the list
08-25 20:54:42.930  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.930  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f676d,ac added. We now have 2 listener(s)
08-25 20:54:42.931  1027  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.933  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:42.933  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.934  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.934  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.934  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217c4a75 added. We now have 9 listener(s)
,08-25 20:54:42.934  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.934  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:54:42.938  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:42.941  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 20:54:42.943  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.943  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 20:54:42.945  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:42.947  8253  8253 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 20:54:42.947  8253  8253 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 20:54:42.947  8253  8253 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 20:54:42.947  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.947  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cab027b added. We now have 3 listener(s)
08-25 20:54:42.947  8253  8253 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 20:54:42.947  1027  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.947  8253  8253 D dhcpcd  : wlan0: sending REQUEST (xid 0xfe1f9e63), next in 4.66 seconds
08-25 20:54:42.948  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:42.951  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:42.951  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.951  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.951  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.951  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b3b898 added. We now have 10 listener(s)
08-25 20:54:42.951  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.951  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:42.952  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:42.952  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:54:42.952  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:54:42.952  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:42.952  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 20:54:42.956  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 20:54:42.956  1027  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.960  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 20:54:42.964  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 20:54:42.966  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:54:42.967  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:42.970  6854  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 20:54:42.970  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:42.970  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:42.970  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:42.970  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:54:42.970  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.970  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:42.970  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:42.970  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f676dac removed from the list
08-25 20:54:42.970  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.970  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217c4a75 removed from the list
08-25 20:54:42.970  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:42.971  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.971  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.971  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.972  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:42.972  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:42.972  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.972  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@217c4a75 not in the list
08-25 20:54:42.972  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.972  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.973  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 20:54:42.974  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:42.974  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:42.974  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:42.974  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:42.974  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b3b898 removed from the list
08-25 20:54:42.974  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:54:42.974  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:42.974  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:42.974  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:42.974  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cab027b removed from the list
08-25 20:54:42.975  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.975  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cdd4b57 added. We now have 2 listener(s)
08-25 20:54:42.976  1027  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.978  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:42.978  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.978  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.978  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.978  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3377c644 added. We now have 9 listener(s)
08-25 20:54:42.978  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.979  8253  8253 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 20:54:42.979  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:54:42.981  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:42.987  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 20:54:42.992  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:42.992  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:42.993  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:42.993  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c495062 added. We now have 3 listener(s)
08-25 20:54:42.993  1027  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:42.995  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:42.998  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:42.998  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:42.998  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:42.998  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:42.998  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:42.998  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8145f3 added. We now have 10 listener(s)
08-25 20:54:42.998  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:42.998  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:42.999  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 20:54:42.999  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 20:54:42.999  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:42.999  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 20:54:43.002  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 20:54:43.002  1027  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 20:54:43.006  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 20:54:43.006  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 20:54:43.009  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 20:54:43.009  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 20:54:43.010  8253  8253 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 20:54:43.010  8253  8253 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 20:54:43.011  8253  8253 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 20:54:43.011  8253  8253 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 20:54:43.011  8253  8253 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 20:54:43.012  8253  8253 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 20:54:43.012  6854  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 20:54:43.012  8253  8253 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 20:54:43.012  8253  8253 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 20:54:43.014  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:43.014  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:43.014  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:43.014  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:43.014  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.014  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:43.014  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:43.014  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cdd4b57 removed from the list
08-25 20:54:43.014  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:43.014  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3377c644 removed from the list
08-25 20:54:43.014  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:43.014  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.015  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.015  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.016  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:43.016  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 20:54:43.016  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:43.016  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3377c644 not in the list
08-25 20:54:43.016  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.016  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.017  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 20:54:43.017  6854  6932 D BluetoothLeScanner: could not find callback wrapper
08-25 20:54:43.018  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 20:54:43.018  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:43.018  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:43.018  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8145f3 removed from the list
08-25 20:54:43.018  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:43.018  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.018  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.018  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:43.018  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c495062 removed from the list
08-25 20:54:43.019  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:43.019  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@347010ae added. We now have 2 listener(s)
08-25 20:54:43.020  1027  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:43.024  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:43.024  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:43.024  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:43.024  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:43.024  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d604e4f added. We now have 9 listener(s)
08-25 20:54:43.024  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:43.025  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 20:54:43.027  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 20:54:43.032  6854  6932 V io.jxcore.node.ConnectivityMonitor:     - active network ty,pe is Wi-Fi: true
08-25 20:54:43.034  6854  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 20:54:43.034  6854  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 20:54:43.034  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 20:54:43.035  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75bae5 added. We now have 3 listener(s)
08-25 20:54:43.035  1027  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 20:54:43.036  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 20:54:43.038  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 20:54:43.040  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 20:54:43.041  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 20:54:43.041  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 20:54:43.041  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 20:54:43.041  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@123089ba added. We now have 10 listener(s)
08-25 20:54:43.041  6854  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 20:54:43.041  6854  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 20:54:43.041  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 20:54:43.041  6854  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 20:54:43.042  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 20:54:43.042  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.042  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 20:54:43.042  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:43.042  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@347010ae removed from the list
08-25 20:54:43.042  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:43.042  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d604e4f removed from the list
08-25 20:54:43.042  6854  6932 D io.jxcore.node.ConnectivityMonitor: stop
08-25 20:54:43.042  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.042  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.042  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.043  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:43.043  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:43.043  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:43.043  6854  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d604e4f not in the list
08-25 20:54:43.043  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.043  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.044  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 20:54:43.044  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 20:54:43.044  6854  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 20:54:43.044  6854  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@123089ba removed from the list
08-25 20:54:43.044  6854  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 20:54:43.044  6854  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 20:54:43.045  6854  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 20:54:43.045  6854  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 20:54:43.045  6854  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b75bae5 removed from the list
08-25 20:54:43.046  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 20:54:43.046  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 20:54:43.046  6854  6932 V io.jxcore.node,.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 20:54:43.046  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 20:54:43.046  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 20:54:43.047  6854  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 20:54:43.067  6854  8268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 905, name: My test thread name)
,08-25 20:54:43.067  6854  8268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 905, thread name: My test thread name)
08-25 20:54:43.068  6854  8268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 905, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 20:54:43.071  6854  8270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 907, name: My test thread name)
08-25 20:54:43.072  6854  8270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 907, thread name: My test thread name)
08-25 20:54:43.072  6854  8270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 907, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 20:54:43.074  6854  6932 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 20:54:43.074  6854  6932 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 20:54:43.074  6854  6932 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 20:54:43.074  6854  6932 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 20:54:43.074  6854  6932 D com.test.thalitest.ThaliTestRunner: Total duration: 22965 ms
08-25 20:54:43.076  6854  6932 I jxcore-log: *Native tests were executed*
08-25 20:54:43.076  6854  6932 I jxcore-log: 
08-25 20:54:43.076  6854  6932 I jxcore-log: Total number of executed tests:  80
08-25 20:54:43.076  6854  6932 I jxcore-log: 
08-25 20:54:43.076  6854  6932 I jxcore-log: Number of passed tests:  80
08-25 20:54:43.076  6854  6932 I jxcore-log: 
08-25 20:54:43.076  6854  6932 I jxcore-log: Number of failed tests:  0
08-25 20:54:43.076  6854  6932 I jxcore-log: 
08-25 20:54:43.077  6854  6932 I jxcore-log: Number of ignored tests:  0
08-25 20:54:43.077  6854  6932 I jxcore-log: 
08-25 20:54:43.077  6854  6932 I jxcore-log: Total duration:  22965
08-25 20:54:43.077  6854  6932 I jxcore-log: 
08-25 20:54:43.077  6854  6932 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 20:54:43.077  6854  6932 I jxcore-log: 
,08-25 20:54:43.082  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.082  6854  6932 I jxcore-log: 
08-25 20:54:43.085  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.085  6854  6932 I jxcore-log: 
08-25 20:54:43.086  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.086  6854  6932 I jxcore-log: 
08-25 20:54:43.087  6854  6854 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 20:54:43.087  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.087  6854  6932 I jxcore-log: 
08-25 20:54:43.088  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.088  6854  6932 I jxcore-log: 
08-25 20:54:43.090  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.090  6854  6932 I jxcore-log: 
08-25 20:54:43.093  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.093  6854  6932 I jxcore-log: 
08-25 20:54:43.095  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.095  6854  6932 I jxcore-log: 
08-25 20:54:43.096  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:54:43.096  6854  6932 I jxcore-log: 
08-25 20:54:43.096  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:54:43.096  6854  6932 I jxcore-log: 
08-25 20:54:43.097  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.097  6854  6932 I jxcore-log: 
08-25 20:54:43.098  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.098  6854  6932 I jxcore-log: 
08-25 20:54:43.099  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 20:54:43.099  6854  6932 I jxcore-log: 
08-25 20:54:43.101  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:54:43.101  6854  6932 I jxcore-log: 
08-25 20:54:43.101  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 20:54:43.101  6854  6932 I jxcore-log: 
08-25 20:54:43.102  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.102  6854  6932 I jxcore-log: 
08-25 20:54:43.103  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrap,per: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.103  6854  6932 I jxcore-log: 
08-25 20:54:43.104  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.104  6854  6932 I jxcore-log: 
08-25 20:54:43.104  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.104  6854  6932 I jxcore-log: 
08-25 20:54:43.105  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.105  6854  6932 I jxcore-log: 
08-25 20:54:43.106  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.106  6854  6932 I jxcore-log: 
08-25 20:54:43.107  8218  8218 W ExternalStrings: load override strings
08-25 20:54:43.107  8218  8218 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 20:54:43.107  8218  8218 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 20:54:43.107  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.107  6854  6932 I jxcore-log: 
08-25 20:54:43.107  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 20:54:43.107  6854  6932 I jxcore-log: 
08-25 20:54:43.108  8218  8218 D StatusProvider: onCreate
08-25 20:54:43.108  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 20:54:43.108  6854  6932 I jxcore-log: 
08-25 20:54:43.109  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 20:54:43.109  6854  6932 I jxcore-log: 
,08-25 20:54:43.110  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.110  6854  6932 I jxcore-log: 
08-25 20:54:43.111  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.111  6854  6932 I jxcore-log: 
08-25 20:54:43.111  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.111  6854  6932 I jxcore-log: 
08-25 20:54:43.112  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.112  6854  6932 I jxcore-log: 
08-25 20:54:43.113  6854  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 20:54:43.113  6854  6932 I jxcore-log: 
08-25 20:54:43.141  8218  8218 V Signer  : override build config not found
08-25 20:54:43.142  8218  8218 D Signer  : value of property debug is false
,08-25 20:54:43.163  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 20:54:43.163  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-25 20:54:43.163  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 20:54:43.163  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 20:54:43.163  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-25 20:54:43.164  8218  8218 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-25 20:54:43.176  8218  8218 V LGMDMManager: Create singleton instance
08-25 20:54:43.261  8218  8218 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-25 20:54:43.263  1027  8236 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-25 20:54:43.265  1027  8236 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 20:54:43.265  1027  8236 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 20:54:43.266  1027  8236 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 20:54:43.266  1027  8236 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 20:54:43.266  1027  8236 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 20:54:43.266  1027  8236 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 20:54:43.266  1027  8236 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 20:54:43.266  1027  8236 D DhcpStateMachine: RunningState
08-25 20:54:43.323  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:43.325  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 20:54:43.340  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:43.351  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:43.368  8281  8281 D AndroidRuntime: 
08-25 20:54:43.368  8281  8281 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 20:54:43.370  8281  8281 D AndroidRuntime: CheckJNI is OFF
08-25 20:54:43.401  1027  2005 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8289 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 20:54:43.403  1027  2005 I ActivityManager: Killing 7336:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-25 20:54:43.473  8281  8281 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 20:54:43.509  8218  8285 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 20:54:43.633  1027  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 20:54:43.634  1027  1105 I ActivityManager: Killing 6854:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-25 20:54:43.713  1027  1043 I WindowState: WIN DEATH: Window{a851e9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 20:54:43.714  1027  1533 D WifiService: Client connection lost with reason: 4
08-25 20:54:43.723  1027  1043 D InputDispatcher: Window went away: Window{a851e9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 20:54:43.848  1027  1105 I ActivityManager:   Force finishing activity ActivityRecord{35fd43c7 u0 com.test.thalitest/.MainActivity t6}
,08-25 20:54:43.887   335   353 E GBMv2   : DFP En is all cleared set to be enabled
,08-25 20:54:43.906  1027  1042 W libprocessgroup: failed to open /acct/uid_10093/pid_7336/cgroup.procs: No such file or directory
,08-25 20:54:43.912  1027  1932 W ActivityManager: Spurious death for ProcessRecord{3c10f1f1 6854:com.test.thalitest/u0a118}, curProc for 6854: null
08-25 20:54:43.912  2025  2025 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 20:54:43.914  2025  2025 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-25 20:54:43.918  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 20:54:43.921  2025  2096 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,08-25 20:54:43.927  1897  1897 D ActionManagerService: notifyUserLog: 1000003
08-25 20:54:43.928  3829  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 20:54:43.928  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-25 20:54:43.930  2025  2025 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-25 20:54:43.931  2025  2025 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 20:54:43.934  2025  2025 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-25 20:54:43.940  1897  1897 D ActionManagerService: notifyUserLog: 1000004
08-25 20:54:43.941  3829  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 20:54:43.942  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 20:54:43.944  3829  3844 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , display: false
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , animation: false }
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , display: false
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , animation: false }
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , display: false
08-25 20:54:43.949  2025  2025 I GBoardWebViewUtils: , animation: false }
,08-25 20:54:43.954  1933  4487 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 20:54:43.954  1933  4487 D SplitWindowPolicy: topRunningActivity=ActivityInfo{e8b7b96 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 20:54:43.962  1933  1948 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 20:54:43.963  1933  1948 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d0f8317 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-25 20:54:43.969  2025  8332 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-25 20:54:43.993  1027  1264 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 20:54:43.998  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-25 20:54:44.014  8289  8289 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 20:54:44.063  8289  8289 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 20:54:44.076  5085  5085 I art     : Explicit concurrent mark sweep GC freed 8209(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 491us total 34.106ms
08-25 20:54:44.081  1593  1593 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-25 20:54:44.084  1987  1987 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 20:54:44.084  7759  7759 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 20:54:44.084  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 20:54:44.085  3829  3829 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 20:54:44.089  1027  1373 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 20:54:44.093  2025  2025 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 20:54:44.093  1593  1593 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-25 20:54:44.100  1593  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 20:54:44.100  1593  1641 D KeyguardModel: createShortcutInfo...
,08-25 20:54:44.102  1593  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 20:54:44.102  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.106  1593  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 20:54:44.107  1593  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 20:54:44.107  1593  1641 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 20:54:44.107  2500  2676 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 20:54:44.108  1593  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 20:54:44.110  1593  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 20:54:44.110  1593  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 20:54:44.111  1593  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 20:54:44.111  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.114  1593  1593 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 20:54:44.114  1593  1593 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-25 20:54:44.121  4982  4982 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 20:54:44.121  4982  4982 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 20:54:44.121  4982  4982 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 20:54:44.121  4982  4982 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 20:54:44.121  4982  4982 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 20:54:44.121  4982  4982 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-25 20:54:44.121  4982  4982 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:44.122  4982  4982 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 20:54:44.122  4982  4982 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 20:54:44.122  4982  4982 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 20:54:44.122  4982  4982 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 20:54:44.122  4982  4982 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 20:54:44.130  1027  1950 V SIM_STK : Menu title from STK is T-Mobile
08-25 20:54:44.142  1027  1104 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-25 20:54:44.161  1593  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 20:54:44.161  1593  1641 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 20:54:44.163  1593  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 20:54:44.163  1593  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-25 20:54:44.170  1027  1477 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 20:54:44.170  1027  1477 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 20:54:44.171  1027  1477 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 20:54:44.171  1027  1477 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 20:54:44.171  1027  1477 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 20:54:44.172  1027  1477 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 20:54:44.175  1027  1535 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-25 20:54:44.175  1027  1535 D ConnectivityService: identical MTU - not setting
08-25 20:54:44.175  1027  1535 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 20:54:44.175  1027  1535 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 20:54:44.175  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 20:54:44.175  1027  1535 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:44.176  1027  1535 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 20:54:44.176  1027  1027 I art     : Explicit concurrent mark sweep GC freed 76840(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.025ms total 129.495ms
08-25 20:54:44.176  1593  1825 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-25 20:54:44.183  1593  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 20:54:44.183  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.187  1593  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 20:54:44.187  1593  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 20:54:44.188  1593  1641 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 20:54:44.188  1593  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 20:54:44.199  1593  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 20:54:44.199  1593  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 20:54:44.203  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-25 20:54:44.204  8289  8289 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 20:54:44.204  8289  8289 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 20:54:44.205  8289  8289 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-25 20:54:44.207  8289  8289 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 20:54:44.207  8289  8289 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 20:54:44.208  8289  8289 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 20:54:44.218  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 20:54:44.218  8289  8289 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 20:54:44.219  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 20:54:44.219  1593  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 20:54:44.219  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.220  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 20:54:44.221  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 20:54:44.223  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 20:54:44.226  1593  1593 D KeyguardModel: handleShortcutListChanged...
08-25 20:54:44.226  1593  1593 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 20:54:44.229  1027  1931 V SIM_STK : Menu title from STK is T-Mobile
08-25 20:54:44.229  1027  1931 V SIM_STK : Menu title from STK is T-Mobile
08-25 20:54:44.235  1593  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 20:54:44.235  1593  1641 D KeyguardModel: createShortcutInfo...
,08-25 20:54:44.242  8218  8285 D LgDataFeature: LgDataFeature() Constructor: none
08-25 20:54:44.242  8218  8285 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 20:54:44.250  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 20:54:44.250  1027  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e5f581b u0 com.lge.launcher2/.Launcher t5} time:212539
08-25 20:54:44.251  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.251  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 20:54:44.251  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 20:54:44.253  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.254  1593  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 20:54:44.254  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.258  1593  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 20:54:44.258  1593  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 20:54:44.260  2025  2171 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 20:54:44.260  2025  2171 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-25 20:54:44.262  1593  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 20:54:44.262  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.263  1862  1862 D SplitUIManager: split_name #11 / not available #0
08-25 20:54:44.264  1862  1862 D SplitUIService: removed split : 
08-25 20:54:44.267  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-25 20:54:44.268  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 20:54:44.268  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 20:54:44.273  1593  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 20:54:44.273  1593  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 20:54:44.274  1593  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 20:54:44.274  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.277  1593  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 20:54:44.277  1593  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 20:54:44.278  2025  2025 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 20:54:44.278   329   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-25 20:54:44.279  3247  8360 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-25 20:54:44.280  1027  1027 D administrator: Handling package changes for user 0
08-25 20:54:44.283  1027  1950 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 20:54:44.286  2025  2025 D [Concierge]WidgetView: change position of spinner
,08-25 20:54:44.287  2025  2025 I [Concierge]WidgetView: initWebView(). Time : 1472151284287
08-25 20:54:44.287  8289  8289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:44.288  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 20:54:44.288  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 20:54:44.288  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 20:54:44.288  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 20:54:44.288  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 20:54:44.288  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 20:54:44.288  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 20:54:44.289  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 20:54:44.289  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 20:54:44.289  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 20:54:44.289  7759  7759 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 20:54:44.289  8289  8289 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 20:54:44.290  1593  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 20:54:44.290  1593  1641 D KeyguardModel: createShortcutInfo...
08-25 20:54:44.292  8289  8289 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 20:54:44.292  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 20:54:44.293  2582  2582 D [Concierge]Service: onStartCommand(). Type : 8
08-25 20:54:44.293  2582  2582 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-25 20:54:44.295  2582  2582 D [Concierge]Service: Update widget ID : 11
08-25 20:54:44.295  2582  2582 D [Concierge]Service: onStartCommand(). Type : 0
,08-25 20:54:44.301  1593  1593 D KeyguardModel: handleShortcutListChanged...
08-25 20:54:44.301  1593  1593 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 20:54:44.303  6972  6972 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 20:54:44.305  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.307  1862  1862 D SplitUIManager: split_name #11 / not available #0
08-25 20:54:44.307  1862  1862 I SplitUIService: split app #11
08-25 20:54:44.308  2025  2025 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 20331934
08-25 20:54:44.309  2025  2025 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-25 20:54:44.309  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 20:54:44.309  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.312  2025  2025 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2ba126e
08-25 20:54:44.312  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-25 20:54:44.313  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 20:54:44.313  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 20:54:44.313  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 20:54:44.316  1027  1950 V SIM_STK : Menu title from STK is T-Mobile
08-25 20:54:44.319  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 20:54:44.320  2025  2025 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 20:54:44.320  2025  2025 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472151099910, New one : 1472151284287
08-25 20:54:44.320  2025  2025 D [Concierge]WidgetView: Unregister all receivers
08-25 20:54:44.320  2025  2025 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 20:54:44.321  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 20:54:44.323  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 20:54:44.324  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 20:54:44.325  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-25 20:54:44.326  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 20:54:44.328  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 20:54:44.333  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.339  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:44.339  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.340  8289  8289 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 20:54:44.341  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.341  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 20:54:44.343  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 20:54:44.343  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 20:54:44.356  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 20:54:44.356  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 20:54:44.356  1027  1027 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 20:54:44.358  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 20:54:44.361  1027  1569 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-25 20:54:44.375  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-25 20:54:44.383  2025  2025 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 20:54:44.383  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-25 20:54:44.384  2025  2025 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 20:54:44.385  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 20:54:44.391  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.405  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 20:54:44.405  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.405  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:44.407  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 20:54:44.407  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 20:54:44.407  6972  6972 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 20:54:44.407  6972  6972 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 20:54:44.409  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 20:54:44.410  6972  6972 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 20:54:44.410  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 20:54:44.410  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 20:54:44.410  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 20:54:44.410  6972  6972 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 20:54:44.410  6972  6972 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 20:54:44.410  6972  6972 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 20:54:44.411  2025  2025 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2295765b time:212701
08-25 20:54:44.413  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.413  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.418  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:44.424  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.429  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.429  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.430  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:44.431  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:44.432  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.437  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:44.444  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.450  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.450  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.451  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:44.452  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.452  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.455  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:44.460  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.462  8218  8285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-25 20:54:44.466  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.466  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.467  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 20:54:44.469  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.470  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.476  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 20:54:44.481  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.483  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-25 20:54:44.487  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.487  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.487  1027  1264 I art     : Explicit concurrent mark sweep GC freed 14114(892KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 5.572ms total 289.172ms
08-25 20:54:44.487  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:44.493  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-25 20:54:44.494  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 20:54:44.494  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.494  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.495  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 20:54:44.496  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-25 20:54:44.496  8218  8285 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-25 20:54:44.501  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-25 20:54:44.502  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 20:54:44.502  8218  8285 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-25 20:54:44.507  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.511  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.512  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.515  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 20:54:44.519  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.520  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.523  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:44.527  2025  2025 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-25 20:54:44.530  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.535  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.535  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.535  8289  8289 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 20:54:44.537  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 20:54:44.538  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.540  8171  8171 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 20:54:44.543  8171  8171 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:44.545  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 20:54:44.549  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 20:54:44.552  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.552  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.553  8289  8289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 20:54:44.553  8289  8289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 20:54:44.554  8289  8289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 20:54:44.556  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 20:54:44.556  8218  8286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 20:54:44.558  8171  8171 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 20:54:44.559  8171  8171 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 20:54:44.560  6972  6972 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 20:54:44.567  6972  6972 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 20:54:44.568  2025  2883 I GBoardtInterface: onReloaded()
08-25 20:54:44.570  2025  2025 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-25 20:54:44.572  8289  8289 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 20:54:44.572  8289  8289 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 20:54:44.573  3829  4967 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 20:54:44.574  8289  8289 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 20:54:44.575  8289  8289 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 20:54:44.575  8289  8289 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 20:54:44.576  3829  3845 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 20:54:44.579  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-25 20:54:44.587  1027  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 20:54:44.591  1027  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 20:54:44.599  1027  1042 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8367 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 20:54:44.600  8281  8281 D AndroidRuntime: Shutting down VM
,08-25 20:54:44.606  1897  1897 D ActionManagerService: notifyUserLog: 1000001
08-25 20:54:44.608  3829  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 20:54:44.608  3829  4956 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 20:54:44.611  1897  1897 D ActionManagerService: notifyUserLog: 1000001
,08-25 20:54:44.612  3829  4956 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 20:54:44.612  3829  4956 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 20:54:44.612  3829  4956 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-25 20:54:44.612  3829  4956 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-25 20:54:44.613  3829  4967 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 20:54:44.615  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-25 20:54:44.615  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-25 20:54:44.616  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-25 20:54:44.616  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 20:54:44.618  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-25 20:54:44.618  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 20:54:44.620  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-25 20:54:44.644  8367  8367 I art     : Almond Protected OAT
,08-25 20:54:44.670  8367  8367 D WeatherApplication: removeAccount
08-25 20:54:44.671  8367  8367 D WeatherApplication: Account.length = 0
08-25 20:54:44.671  8367  8367 E WeatherApplication: OPERATOR:OPEN
,08-25 20:54:44.680  8367  8367 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 20:54:44
08-25 20:54:44.683  8367  8367 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 20:54:44.683  8367  8367 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 20:54:44.684  8367  8367 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 20:54:44.685  8367  8367 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 20:54:44.685  8367  8367 D Weather.Utils: 2 : All the weather widget is gone.
08-25 20:54:44.686  8367  8367 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 20:54:44
08-25 20:54:44.688  8218  8218 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 20:54:44.702  1027  1042 I ActivityManager: Killing 7372:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-25 20:54:44.801  1809  1809 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-25 20:54:44.801  1027  2043 W libprocessgroup: failed to open /acct/uid_10005/pid_7372/cgroup.procs: No such file or directory
08-25 20:54:44.809  2185  2185 I ConfigService: onCreate
08-25 20:54:44.809  2185  2185 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 20:54:44.812  1809  1809 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-25 20:54:44.814  2185  2185 I ConfigService: onBind returning update interface
,08-25 20:54:44.842  1027  1264 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8386 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 20:54:44.851  2185  2185 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 20:54:44.851  2185  2185 I ConfigService: onBind returning config service
08-25 20:54:44.851   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 9.751ms
08-25 20:54:44.856  2185  2185 I ConfigService: onDestroy
08-25 20:54:44.856  1809  8404 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 20:54:44.860   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 8.953ms
,08-25 20:54:44.870   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.996ms
08-25 20:54:44.885  5793  8410 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-25 20:54:44.895  1809  8412 I PeopleContactsSync: CP2 sync disabled
,08-25 20:54:44.896  1809  5228 I Icing   : doRemovePackageData com.test.thalitest
08-25 20:54:44.903  2025  2883 I GBoardtInterface: exportHTML()
,08-25 20:54:44.929  2025  2883 I GBoardtInterface: exportHTML()
,08-25 20:54:44.956  2025  2883 I GBoardtInterface: exportHTML()
,08-25 20:54:44.991  1809  8411 W GmsApplication: Using Auth Proxy for data requests.
,08-25 20:54:44.994  1809  8411 W GmsApplication: Using Auth Proxy for data requests.
08-25 20:54:45.021  7156  7156 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-25 20:54:45.024  1027  1931 I ActivityManager: Killing 7788:com.google.android.talk/u0a72 (adj 15): empty #17
08-25 20:54:45.082  1027  2004 W libprocessgroup: failed to open /acct/uid_10072/pid_7788/cgroup.procs: No such file or directory
,08-25 20:54:45.086  2350  2494 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:45.087  2350  2494 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 20:54:45.088  2350  8416 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-25 20:54:45.093  2350  8416 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-25 20:54:45.094  2350  8416 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 20:54:45.094  2350  8416 E AndroidRuntime: Process: android.process.acore, PID: 2350
08-25 20:54:45.094  2350  8416 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at com.android.providers.c,ontacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-25 20:54:45.094  2350  8416 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 20:54:45.103  1027  2005 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8417 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-25 20:54:45.107  2350  8416 I Process : Sending signal. PID: 2350 SIG: 9
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: Can't write: system_app_crash
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 20:54:45.109  1027  8423 E DropBoxManagerService: 	... 5 more
08-25 20:54:45.127  2185  2201 I art     : Explicit concurrent mark sweep GC freed 6293(366KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 716us total 18.348ms

```
