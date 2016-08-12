#### Test 79751015007586f_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-12 22:30:02.261  1035  1566 W libprocessgroup: failed to open /acct/uid_10014/pid_6241/cgroup.procs: No such file or directory
,--------- beginning of main
08-12 22:30:37.995  6886  6886 D AndroidRuntime: 
08-12 22:30:37.995  6886  6886 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 22:30:38.000  6886  6886 D AndroidRuntime: CheckJNI is OFF
08-12 22:30:38.125  6886  6886 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 22:30:38.130  1035  1720 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 22:30:38.141  1953  1969 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 22:30:38.144  1035  1720 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 22:30:38.145  1035  1720 D ActivityManager: setTaskToReturnTo : TaskRecord{3655f571 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 22:30:38.146  1035  1720 D ActivityManager: setTaskToReturnTo : TaskRecord{3655f571 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 22:30:38.146  1035  1720 D WindowStateEx: AppWindowTokenEx init.. 
08-12 22:30:38.147   335   350 E GBMv2   : DFP En is all cleared set to be enabled
08-12 22:30:38.182  1035  1720 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6905 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 22:30:38.183  6886  6886 D AndroidRuntime: Shutting down VM
08-12 22:30:38.255  1953  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 22:30:38.258  1953  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{50604b8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 22:30:38.260  1953  1968 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 22:30:38.260  1953  1968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17504291 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 22:30:38.331  6905  6905 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 22:30:38.432  6905  6905 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 22:30:38.441  6905  6905 I LibraryLoader: Loading: webviewchromium
08-12 22:30:38.445  6905  6905 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4323-4327)
,08-12 22:30:38.445  6905  6905 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 22:30:38.463  6905  6905 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39594326}
08-12 22:30:38.465  6905  6905 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 22:30:38.465  6905  6905 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 22:30:38.475  6905  6905 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 22:30:38.476  6905  6905 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:30:38.498  6905  6905 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 22:30:38.500  6905  6905 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 22:30:38.500  6905  6905 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-12 22:30:38.503   314  2989 V AudioPolicyService: registerClient() client 0xb1024fe0, uid 10118
08-12 22:30:38.519  6905  6905 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 22:30:38.519  6905  6905 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 22:30:38.519  6905  6905 I Adreno-EGL: Build Date: 12/12/14 금
08-12 22:30:38.519  6905  6905 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 22:30:38.519  6905  6905 I Adreno-EGL: Remote Branch: 
08-12 22:30:38.519  6905  6905 I Adreno-EGL: Local Patches: 
08-12 22:30:38.519  6905  6905 I Adreno-EGL: Reconstruct Branch: 
,08-12 22:30:38.525  1035  1117 D BluetoothManagerService: Message: 20
08-12 22:30:38.525  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22403e73:true
08-12 22:30:38.622  6905  6942 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 22:30:38.625  6905  6905 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 22:30:38.648  6905  6905 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 22:30:38.655  6905  6905 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 22:30:38.659  6905  6905 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-12 22:30:38.662  6905  6905 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 22:30:38.662  6905  6905 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 22:30:38.679  6905  6905 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 22:30:38.688  6905  6905 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:30:38.688  6905  6905 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 22:30:38.727  6905  6954 D OpenGLRenderer: Render dirty regions requested: true
08-12 22:30:38.727  6905  6954 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 22:30:38.744  6905  6954 D OpenGLRenderer: Enabling debug mode 0
,08-12 22:30:38.752  1035  1101 W ActivityManager: Activity pause timeout for ActivityRecord{19c81f56 u0 com.test.thalitest/.MainActivity t6}
08-12 22:30:38.754  6905  6905 D Atlas   : Validating map...
08-12 22:30:38.759  1035  1050 D SplitWindow: check instance of lgWin Window{294d7bd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:30:38.839  6905  6952 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 22:30:38.839  6905  6952 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 22:30:38.876  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +623ms (total +727ms)
08-12 22:30:38.877  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19c81f56 u0 com.test.thalitest/.MainActivity t6} time:304760
,08-12 22:30:38.878  6905  6905 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d4a5c2d time:304761
08-12 22:30:39.048  6905  6905 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 22:30:39.048  6905  6905 I chromium: 
,08-12 22:30:39.114  6905  6905 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 22:30:39.182  6905  6952 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 22:30:39.182  6905  6952 I chromium: 
,08-12 22:30:39.335  6905  6967 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-12 22:30:39.351  6905  6967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 22:30:39.351  6905  6967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 22:30:39.351  6905  6967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 22:30:39.351  6905  6967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 22:30:39.351  6905  6967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 22:30:39.351  6905  6967 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b27d961 added. We now have 1 listener(s)
,08-12 22:30:39.357  1035  1566 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 22:30:39.360  6905  6967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 22:30:39.361  6905  6967 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 22:30:39.368  6905  6967 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 22:30:39.368  6905  6967 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 22:30:39.377  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 22:30:39.378  6905  6967 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2311574 added. We now have 1 listener(s)
08-12 22:30:39.378  6905  6967 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 22:30:39.383  1035  1528 D WifiService: New client listening to asynchronous messages
,08-12 22:30:39.389  6905  6967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 22:30:39.389  6905  6967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 22:30:39.391  6905  6967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 22:30:39.392  6905  6967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 22:30:39.392  6905  6967 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 22:30:39.397  6905  6967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 22:30:39.398  1035  1751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-12 22:30:39.401  6905  6967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 22:30:39.412  6905  6967 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:30:39.412  6905  6967 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 22:30:39.413  6905  6967 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 22:30:39.413  6905  6967 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 22:30:39.414  6905  6967 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 22:30:39.415  6905  6905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 22:30:39.417  6905  6905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 22:30:39.451  6905  6905 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 22:30:39.991   335   353 E GBMv2   : DFP En is all cleared set to be enabled
08-12 22:30:39.991   335   353 E GBMv2   : Set value is all cleared set the max
08-12 22:30:39.991   335   353 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 22:30:40.347  6905  6970 W jxcore-log: Initializing JXcore engine
08-12 22:30:40.347  6905  6970 W jxcore-log: JXcore engine is ready
,08-12 22:30:40.371  6970  6970 W Thread-817: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10257]" dev="sockfs" ino=10257 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 22:30:40.371  6970  6970 W Thread-817: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-12 22:30:40.371  6970  6970 W Thread-817: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10405]" dev="sockfs" ino=10405 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 22:30:40.371  6970  6970 W Thread-817: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 22:30:40.371  6970  6970 W Thread-817: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32532]" dev="sockfs" ino=32532 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 22:30:40.423  6905  6970 W jxcore-log: Starting JXcore engine
,08-12 22:30:40.570  6905  6970 W jxcore-log: Platform android
08-12 22:30:40.570  6905  6970 W jxcore-log: 
08-12 22:30:40.570  6905  6970 W jxcore-log: Process ARCH arm
08-12 22:30:40.570  6905  6970 W jxcore-log: 
,08-12 22:30:40.961  6905  6970 I jxcore-log: JXcore Cordova bridge is ready!
08-12 22:30:40.961  6905  6970 I jxcore-log: 
08-12 22:30:40.962  6905  6970 W jxcore-log: JXcore engine is started
,08-12 22:30:40.970  6905  6967 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 22:30:40.977  6905  6905 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 22:30:56.735  6905  6970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 22:30:56.735  6905  6970 I jxcore-log: 
,08-12 22:30:56.738  6905  6970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 22:30:56.738  6905  6970 I jxcore-log: 
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:30:56.742  6905  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 22:30:56.744  6905  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 22:30:56.747  6905  6970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 22:30:56.747  6905  6970 I jxcore-log: 
08-12 22:30:56.748  6905  6970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 22:30:56.748  6905  6970 I jxcore-log: 
,08-12 22:30:57.087  6905  6970 I jxcore-log: Unit Test app is loaded
08-12 22:30:57.087  6905  6970 I jxcore-log: 
,08-12 22:30:57.096  6905  6905 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 22:30:57.104  6905  6970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 22:30:57.104  6905  6970 I jxcore-log: 
08-12 22:30:57.110  6905  6970 I jxcore-log: My device name is: LGE-LG-D855
08-12 22:30:57.110  6905  6970 I jxcore-log: 
,08-12 22:30:59.379  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 22:30:59.379  6905  6970 I jxcore-log: 
,08-12 22:31:00.023  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 22:31:00.023  6905  6970 I jxcore-log: 
,08-12 22:31:00.051  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 22:31:00.051  6905  6970 I jxcore-log: 
,08-12 22:31:00.067  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-12 22:31:00.067  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-12 22:31:00.067  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 22:31:00.067  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
08-12 22:31:00.068  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
,08-12 22:31:00.068  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-12 22:31:00.069  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,08-12 22:31:00.070  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 22:31:01.400  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 22:31:01.400  6905  6970 I jxcore-log: 
,08-12 22:31:01.628  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 22:31:01.628  6905  6970 I jxcore-log: 
,08-12 22:31:01.633  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 22:31:01.633  6905  6970 I jxcore-log: 
,08-12 22:31:01.639  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 22:31:01.639  6905  6970 I jxcore-log: 
,08-12 22:31:01.656  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 22:31:01.656  6905  6970 I jxcore-log: 
,08-12 22:31:01.660  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 22:31:01.660  6905  6970 I jxcore-log: 
08-12 22:31:02.322  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 22:31:02.322  6905  6970 I jxcore-log: 
,08-12 22:31:02.335  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 22:31:02.335  6905  6970 I jxcore-log: 
,08-12 22:31:02.344  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 22:31:02.344  6905  6970 I jxcore-log: 
,08-12 22:31:02.351  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 22:31:02.351  6905  6970 I jxcore-log: 
,08-12 22:31:02.399  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 22:31:02.399  6905  6970 I jxcore-log: 
,08-12 22:31:02.455  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 22:31:02.455  6905  6970 I jxcore-log: 
,08-12 22:31:02.464  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 22:31:02.464  6905  6970 I jxcore-log: 
,08-12 22:31:02.630  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 22:31:02.630  6905  6970 I jxcore-log: 
,08-12 22:31:02.660  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 22:31:02.660  6905  6970 I jxcore-log: 
,08-12 22:31:02.664  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 22:31:02.664  6905  6970 I jxcore-log: 
,08-12 22:31:02.670  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 22:31:02.670  6905  6970 I jxcore-log: 
,08-12 22:31:02.688  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 22:31:02.688  6905  6970 I jxcore-log: 
,08-12 22:31:02.771  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 22:31:02.771  6905  6970 I jxcore-log: 
,08-12 22:31:02.785  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 22:31:02.785  6905  6970 I jxcore-log: 
,08-12 22:31:02.814  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 22:31:02.814  6905  6970 I jxcore-log: 
,08-12 22:31:02.826  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 22:31:02.826  6905  6970 I jxcore-log: 
,08-12 22:31:02.845  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 22:31:02.845  6905  6970 I jxcore-log: 
,08-12 22:31:02.880  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 22:31:02.880  6905  6970 I jxcore-log: 
,08-12 22:31:02.886  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 22:31:02.886  6905  6970 I jxcore-log: 
,08-12 22:31:03.092  6905  6970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 22:31:03.092  6905  6970 I jxcore-log: 
,08-12 22:31:03.101  6905  6970 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-12 22:31:03.103  6905  6970 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 22:31:03.103  6905  6970 I jxcore-log: 
08-12 22:31:08.750  1035  3490 I LocationManagerService: remove 34594dd6
,08-12 22:31:08.756  1035  3490 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 22:31:08.758  1035  3490 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 22:31:08.759  1035  3490 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 22:31:08.762  1035  3490 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 22:31:08.765  1035  3490 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 22:31:16.914  6905  6970 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 22:31:16.914  6905  6970 I jxcore-log: 
,08-12 22:31:17.270  6982  6982 D AndroidRuntime: 
08-12 22:31:17.270  6982  6982 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 22:31:17.274  6982  6982 D AndroidRuntime: CheckJNI is OFF
08-12 22:31:17.447  6982  6982 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 22:31:17.465  1035  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 22:31:17.465  1035  1101 I ActivityManager: Killing 6905:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 22:31:17.504  1035  2333 I WindowState: WIN DEATH: Window{294d7bd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:31:17.506  1035  1528 D WifiService: Client connection lost with reason: 4
08-12 22:31:17.513  1035  2333 D InputDispatcher: Window went away: Window{294d7bd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:31:17.581  1035  1101 I ActivityManager:   Force finishing activity ActivityRecord{19c81f56 u0 com.test.thalitest/.MainActivity t6}
,08-12 22:31:17.613   335   350 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 22:31:17.616  1035  2069 W ActivityManager: Spurious death for ProcessRecord{1515f253 6905:com.test.thalitest/u0a118}, curProc for 6905: null
08-12 22:31:17.616  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 22:31:17.622  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{19c81f56 u0 com.test.thalitest/.MainActivity t6 f}
08-12 22:31:17.622  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{19c81f56 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 22:31:17.653  1953  4038 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 22:31:17.653  1953  4038 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e9ab5f6 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 22:31:17.654  2081  2081 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 22:31:17.654  1953  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 22:31:17.655  1953  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d949df7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 22:31:17.655  2081  2081 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-12 22:31:17.658  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 22:31:17.659  2081  2181 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-12 22:31:17.663  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 22:31:17.670  1035  1419 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 22:31:17.682  5066  5066 I art     : Explicit concurrent mark sweep GC freed 475(32KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 532us total 52.937ms
08-12 22:31:17.685  3800  3800 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-12 22:31:17.686  4311  4311 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 22:31:17.686  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 22:31:17.687  2493  2615 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 22:31:17.687  2026  2026 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 22:31:17.722  1035  1099 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-12 22:31:17.744  4974  4974 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 22:31:17.744  4974  4974 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 22:31:17.744  4974  4974 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 22:31:17.744  4974  4974 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 22:31:17.745  4974  4974 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 22:31:17.745  4974  4974 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 22:31:17.745  4974  4974 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:31:17.745  4974  4974 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 22:31:17.745  4974  4974 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:31:17.745  4974  4974 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 22:31:17.745  4974  4974 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 22:31:17.745  4974  4974 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-12 22:31:17.750  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 22:31:17.752  1917  1917 D ActionManagerService: notifyUserLog: 1000003
08-12 22:31:17.754  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 22:31:17.754  3800  4949 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 22:31:17.755  2081  2081 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 22:31:17.757  2081  2081 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 22:31:17.759  2081  2081 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-12 22:31:17.765  1588  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 22:31:17.765  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.767  6395  6395 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 22:31:17.768  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 22:31:17.768  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 22:31:17.771  1917  1917 D ActionManagerService: notifyUserLog: 1000004
08-12 22:31:17.773  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 22:31:17.775  3800  4949 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 22:31:17.776  1588  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 22:31:17.776  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.777  3800  3815 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-12 22:31:17.782  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 22:31:17.782  1588  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 22:31:17.782  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 22:31:17.783  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 22:31:17.786  1827  1827 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-12 22:31:17.790  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.790  1588  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , display: false
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , animation: false }
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , display: false
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , animation: false }
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , create_time: 1471007226523
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , display: false
08-12 22:31:17.790  2081  2081 I GBoardWebViewUtils: , animation: false }
,08-12 22:31:17.794  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-12 22:31:17.795  1883  1883 D SplitUIService: removed split : 
08-12 22:31:17.804  2209  2209 I ConfigService: onCreate
,08-12 22:31:17.804  2209  2209 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 22:31:17.805  1588  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 22:31:17.805  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.805  2081  7015 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 22:31:17.812  1035  2009 V SIM_STK : Menu title from STK is T-Mobile
08-12 22:31:17.815  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 22:31:17.815  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 22:31:17.815  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 22:31:17.815  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 22:31:17.818  1827  1827 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 22:31:17.819  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.819  1588  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-12 22:31:17.833  2209  2209 I ConfigService: onBind returning update interface
08-12 22:31:17.840  1588  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 22:31:17.840  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.848  2209  2209 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 22:31:17.848  2209  2209 I ConfigService: onBind returning config service
,08-12 22:31:17.851  2209  2209 I ConfigService: onDestroy
08-12 22:31:17.854  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-12 22:31:17.854  1883  1883 I SplitUIService: split app #11
08-12 22:31:17.855  1588  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 22:31:17.855  1588  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 22:31:17.855  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 22:31:17.855  1588  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 22:31:17.867  1827  7020 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-12 22:31:17.869  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.869  1588  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 22:31:17.871  1588  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 22:31:17.871  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.878  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-12 22:31:17.878  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 22:31:17.885  1588  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 22:31:17.885  1588  1641 D KeyguardModel: createShortcutInfo...
,08-12 22:31:17.887  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
08-12 22:31:17.887  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
08-12 22:31:17.889  2081  2081 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 22:31:17.890  1588  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 22:31:17.890  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.892  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.892  1588  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 22:31:17.902  1588  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 22:31:17.902  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.903  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.903  1588  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 22:31:17.904  1588  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 22:31:17.904  1588  1641 D KeyguardModel: createShortcutInfo...
,08-12 22:31:17.906  1035  1035 I art     : Explicit concurrent mark sweep GC freed 29953(1925KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.707ms total 265.560ms
08-12 22:31:17.910  1588  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.910  1588  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 22:31:17.911  1588  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 22:31:17.911  1588  1641 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.913  1035  1123 I art     : WaitForGcToComplete blocked for 260.963ms for cause Explicit
08-12 22:31:17.913  5838  7025 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-12 22:31:17.943  1827  7028 I PeopleContactsSync: CP2 sync disabled
,08-12 22:31:17.946   329   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-12 22:31:17.947  6486  6486 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 22:31:17.947  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-12 22:31:17.947  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 22:31:17.948  3237  7030 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-12 22:31:17.948  1035  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 22:31:17.949  1827  5238 I Icing   : doRemovePackageData com.test.thalitest
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 22:31:17.950  4311  4311 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-12 22:31:17.972  1827  7027 W GmsApplication: Using Auth Proxy for data requests.
,08-12 22:31:17.975  1035  1035 D administrator: Handling package changes for user 0
08-12 22:31:17.978  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
08-12 22:31:17.991  1827  7027 W GmsApplication: Using Auth Proxy for data requests.
,08-12 22:31:17.993  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-12 22:31:17.996  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:31:17.998  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 22:31:17.999  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 22:31:18.000  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 22:31:18.001  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-12 22:31:18.002  6512  6512 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 22:31:18.021  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 22:31:18.021  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 22:31:18.027  2081  2308 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 22:31:18.028  2081  2308 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 22:31:18.028  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{13c2e01d u0 com.lge.launcher2/.Launcher t5} time:343911
08-12 22:31:18.028  2026  2026 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 22:31:18.029  2026  2026 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 22:31:18.029  2026  2026 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 22:31:18.033  6395  6395 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 22:31:18.036  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 22:31:18.037  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-12 22:31:18.037  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:31:18.041  2187  7032 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 22:31:18.044  2081  2081 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 22:31:18.065  1035  1720 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7036 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 22:31:18.068  2654  2654 D [Concierge]Service: onStartCommand(). Type : 8
08-12 22:31:18.068  2654  2654 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 22:31:18.069  2654  2654 D [Concierge]Service: Update widget ID : 11
08-12 22:31:18.070  2081  2081 D [Concierge]WidgetView: change position of spinner
08-12 22:31:18.071  2654  2654 D [Concierge]Service: onStartCommand(). Type : 0
08-12 22:31:18.071  2081  2081 I [Concierge]WidgetView: initWebView(). Time : 1471033878071
08-12 22:31:18.073  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 22:31:18.073  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 22:31:18.073  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 22:31:18.075  1035  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 22:31:18.084  2081  2081 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 200533509
08-12 22:31:18.084  2081  2081 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-12 22:31:18.084  2081  2081 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-12 22:31:18.087  2081  2081 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@e3f1985
,08-12 22:31:18.087  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 22:31:18.088  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 22:31:18.088  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:31:18.093  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 22:31:18.093  2081  2081 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 22:31:18.094  2081  2081 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471033562253, New one : 1471033878071
08-12 22:31:18.094  2081  2081 D [Concierge]WidgetView: Unregister all receivers
08-12 22:31:18.094  2081  2081 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 22:31:18.094  2081  2081 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 22:31:18.095  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:31:18.096  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 22:31:18.097  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 22:31:18.098  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-12 22:31:18.099  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 22:31:18.101  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 22:31:18.107  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:31:18.107  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:31:18.144  2081  2081 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 22:31:18.152  2081  2081 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 22:31:18.152  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 22:31:18.154  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 22:31:18.163  7036  7036 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-12 22:31:18.163  7036  7036 W LG Account v2.2: No ProfileInfo entries
08-12 22:31:18.163  7036  7036 I LG Account v2.2: isEnabled: false
08-12 22:31:18.163  7036  7036 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 22:31:18.163  7036  7036 I Feature : [Lifetracker]Country: EU
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Operator: OPEN
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Ranking support: false
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Comfort support: false
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Accessory: true
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Health device: true
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Extra Pedometer: false
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Blood glucose device: false
08-12 22:31:18.164  7036  7036 I Feature : [Lifetracker]Device Number: 3
08-12 22:31:18.165  7036  7036 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-12 22:31:18.173  2081  2081 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1ac53496 time:344056
08-12 22:31:18.193  1035  1970 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7055 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 22:31:18.193  1035  1970 I ActivityManager: Killing 6328:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-12 22:31:18.210  1035  1099 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 22:31:18.217  1035  1099 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 22:31:18.221  1035  1123 I art     : Explicit concurrent mark sweep GC freed 11755(685KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.494ms total 308.421ms
08-12 22:31:18.274  2081  2081 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 22:31:18.286  6982  6982 D AndroidRuntime: Shutting down VM
,08-12 22:31:18.307  1035  1991 W libprocessgroup: failed to open /acct/uid_10004/pid_6328/cgroup.procs: No such file or directory
,08-12 22:31:18.311  2081  2919 I GBoardtInterface: onReloaded()
08-12 22:31:18.312  2081  2081 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 22:31:18.314  3800  3815 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 22:31:18.316  3800  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 22:31:18.321  1917  1917 D ActionManagerService: notifyUserLog: 1000001
,08-12 22:31:18.322  3800  4949 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 22:31:18.323  3800  4949 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 22:31:18.324  7055  7055 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 22:31:18.324  7055  7055 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 22:31:18.325  7055  7055 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 22:31:18.325  7055  7055 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 22:31:18.325  1917  1917 D ActionManagerService: notifyUserLog: 1000001
08-12 22:31:18.326  3800  4949 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 22:31:18.326  3800  4949 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 22:31:18.326  3800  4949 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 22:31:18.326  3800  4949 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 22:31:18.326  3800  3815 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 22:31:18.326  7055  7055 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 22:31:18.327  7055  7055 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 22:31:18.328  2081  2081 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 22:31:18.328  2081  2081 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 22:31:18.330  2081  2081 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 22:31:18.330  2081  2081 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 22:31:18.331  2081  2081 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 22:31:18.331  2081  2081 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 22:31:18.333  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 22:31:18.400  7055  7055 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-12 22:31:18.406  7055  7055 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-12 22:31:18.406  7055  7055 D HideNavigationAppsReceiver: replacing : false
08-12 22:31:18.408  7055  7055 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-12 22:31:18.410  7055  7055 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 22:31:18.410  7055  7055 D ButtonCombinationReceiver: replacing : false
,08-12 22:31:18.414  1035  1970 I ActivityManager: Killing 6436:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-12 22:31:18.488  1035  1751 W libprocessgroup: failed to open /acct/uid_10008/pid_6436/cgroup.procs: No such file or directory
,08-12 22:31:18.495  5066  7072 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 22:31:18.518  1035  2098 V SIM_STK : Menu title from STK is T-Mobile
,08-12 22:31:18.526  1035  1991 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7076 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-12 22:31:18.557  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7094 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
--------- beginning of crash
08-12 22:31:18.576  5066  7072 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 22:31:18.576  5066  7072 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 5066
08-12 22:31:18.576  5066  7072 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:525)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at csx.d(PG:192)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at cun.g(PG:594)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at cuy.ub(PG:301)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:31:18.576  5066  7072 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 22:31:18.580  5066  7072 I Process : Sending signal. PID: 5066 SIG: 9
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 22:31:18.582  1035  7111 E DropBoxManagerService: 	... 5 more
08-12 22:31:18.592  1035  1528 D WifiService: Client connection lost with reason: 4
,08-12 22:31:18.613  7076  7076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-12 22:31:18.614  2081  2919 I GBoardtInterface: exportHTML()
08-12 22:31:18.641  2081  2919 I GBoardtInterface: exportHTML()
,08-12 22:31:18.642  1035  1991 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 5066) has died
08-12 22:31:18.642  1035  1991 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
08-12 22:31:18.642  1035  1991 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:31:18.658  7076  7119 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-12 22:31:18.659  7076  7119 E AndroidRuntime: Process: com.android.keychain, PID: 7076
08-12 22:31:18.659  7076  7119 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool,.java:463)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:31:18.659  7076  7119 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
