#### Test 79426650471aed9_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-17 10:43:00.130  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-17 10:43:33.492  6720  6720 D AndroidRuntime: 
08-17 10:43:33.492  6720  6720 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 10:43:33.499  6720  6720 D AndroidRuntime: CheckJNI is OFF
08-17 10:43:33.700  6720  6720 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 10:43:33.711  1035  1954 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 10:43:33.728  1942  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 10:43:33.734  1035  1954 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 10:43:33.736  1035  1954 D ActivityManager: setTaskToReturnTo : TaskRecord{2629583b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 10:43:33.736  1035  1954 D ActivityManager: setTaskToReturnTo : TaskRecord{2629583b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 10:43:33.738  1035  1954 D WindowStateEx: AppWindowTokenEx init.. 
08-17 10:43:33.739   341   349 E GBMv2   : DFP En is all cleared set to be enabled
08-17 10:43:33.767  1035  1954 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6735 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 10:43:33.769  6720  6720 D AndroidRuntime: Shutting down VM
08-17 10:43:33.825  1942  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 10:43:33.826  1942  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d6b1ca4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 10:43:33.826  1942  2568 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 10:43:33.827  1942  2568 D SplitWindowPolicy: topRunningActivity=ActivityInfo{342d5a0d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 10:43:33.895  6735  6735 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-17 10:43:33.980  6735  6735 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 10:43:33.987  6735  6735 I LibraryLoader: Loading: webviewchromium
08-17 10:43:33.990  6735  6735 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4141-4145)
,08-17 10:43:33.990  6735  6735 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:43:34.015  6735  6735 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2bdc3df2}
,08-17 10:43:34.016  6735  6735 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:43:34.017  6735  6735 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 10:43:34.029  6735  6735 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 10:43:34.031  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 10:43:34.047  6735  6735 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 10:43:34.048  6735  6735 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-17 10:43:34.049  6735  6735 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-17 10:43:34.053   324   324 V AudioPolicyService: registerClient() client 0xb558aea0, uid 10118
,08-17 10:43:34.067  1035  1111 D BluetoothManagerService: Message: 20
08-17 10:43:34.068  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2105faed:true
08-17 10:43:34.068  6735  6735 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 10:43:34.068  6735  6735 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 10:43:34.068  6735  6735 I Adreno-EGL: Build Date: 12/12/14 금
08-17 10:43:34.068  6735  6735 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 10:43:34.068  6735  6735 I Adreno-EGL: Remote Branch: 
08-17 10:43:34.068  6735  6735 I Adreno-EGL: Local Patches: 
08-17 10:43:34.068  6735  6735 I Adreno-EGL: Reconstruct Branch: 
,08-17 10:43:34.186  6735  6782 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-17 10:43:34.189  6735  6735 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-17 10:43:34.209  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 10:43:34.215  6735  6735 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 10:43:34.218  6735  6735 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 10:43:34.222  6735  6735 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-17 10:43:34.222  6735  6735 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-17 10:43:34.238  6735  6735 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-17 10:43:34.245  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 10:43:34.245  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 10:43:34.275  6735  6800 D OpenGLRenderer: Render dirty regions requested: true
08-17 10:43:34.275  6735  6800 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 10:43:34.281  6735  6800 D OpenGLRenderer: Enabling debug mode 0
08-17 10:43:34.294  6735  6735 D Atlas   : Validating map...
,08-17 10:43:34.303  1035  1974 D SplitWindow: check instance of lgWin Window{1ae7c2ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 10:43:34.345  6735  6798 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 10:43:34.345  6735  6798 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 10:43:34.460  6735  6735 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@158a8569 time:284615
,08-17 10:43:34.465  1035  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +641ms (total +724ms)
08-17 10:43:34.466  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{111ebb58 u0 com.test.thalitest/.MainActivity t6} time:284620
08-17 10:43:34.576  6735  6735 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 10:43:34.576  6735  6735 I chromium: 
,08-17 10:43:34.620  6735  6735 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 10:43:34.797  6735  6811 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435177984
,08-17 10:43:34.812  6735  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 10:43:34.812  6735  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 10:43:34.812  6735  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 10:43:34.812  6735  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 10:43:34.812  6735  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 10:43:34.812  6735  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1efddd added. We now have 1 listener(s)
08-17 10:43:34.818  1035  1657 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 10:43:34.821  6735  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 10:43:34.825  6735  6811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 10:43:34.828  6735  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:43:34.828  6735  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 10:43:34.838  6735  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a44f120 added. We now have 1 listener(s)
08-17 10:43:34.839  6735  6811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:43:34.844  1035  1544 D WifiService: New client listening to asynchronous messages
08-17 10:43:34.849  6735  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:43:34.849  6735  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 10:43:34.851  6735  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 10:43:34.852  6735  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 10:43:34.852  6735  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 10:43:34.864  6735  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:43:34.865  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 10:43:34.866  6735  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 10:43:34.881  6735  6811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:43:34.882  6735  6811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:43:34.883  6735  6811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 10:43:34.883  6735  6811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:43:34.887  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:43:34.890  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:43:34.891  6735  6811 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 10:43:34.940  6735  6798 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 10:43:34.940  6735  6798 I chromium: 
,08-17 10:43:35.000  6735  6735 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 10:43:35.697   341   351 E GBMv2   : DFP En is all cleared set to be enabled
,08-17 10:43:35.697   341   351 E GBMv2   : Set value is all cleared set the max
08-17 10:43:35.697   341   351 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 10:43:36.266  6735  6814 W jxcore-log: Initializing JXcore engine
08-17 10:43:36.266  6735  6814 W jxcore-log: JXcore engine is ready
,08-17 10:43:36.332  6814  6814 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8454]" dev="sockfs" ino=8454 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-17 10:43:36.342  6814  6814 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-17 10:43:36.342  6814  6814 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9957]" dev="sockfs" ino=9957 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 10:43:36.342  6814  6814 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-17 10:43:36.342  6814  6814 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32905]" dev="sockfs" ino=32905 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-17 10:43:36.370  6735  6814 W jxcore-log: Starting JXcore engine
,08-17 10:43:36.523  6735  6814 W jxcore-log: Platform android
08-17 10:43:36.523  6735  6814 W jxcore-log: 
08-17 10:43:36.524  6735  6814 W jxcore-log: Process ARCH arm
08-17 10:43:36.524  6735  6814 W jxcore-log: 

```
