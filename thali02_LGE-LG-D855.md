#### Test 823372352b31b5a_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 13:19:00.087  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-25 13:19:00.096  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 13:19:00.096  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 13:19:00.099  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 13:19:00.101  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 13:19:12.924  6751  6751 D AndroidRuntime: 
08-25 13:19:12.924  6751  6751 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 13:19:12.929  6751  6751 D AndroidRuntime: CheckJNI is OFF
08-25 13:19:13.050  6751  6751 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 13:19:13.055  1035  1772 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 13:19:13.065  1927  1942 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 13:19:13.068  1035  1772 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 13:19:13.069  1035  1772 D ActivityManager: setTaskToReturnTo : TaskRecord{2aafe117 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 13:19:13.069  1035  1772 D ActivityManager: setTaskToReturnTo : TaskRecord{2aafe117 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 13:19:13.071  1035  1772 D WindowStateEx: AppWindowTokenEx init.. 
08-25 13:19:13.071   349   357 E GBMv2   : DFP En is all cleared set to be enabled
08-25 13:19:13.091  1035  1772 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6766 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 13:19:13.092  6751  6751 D AndroidRuntime: Shutting down VM
08-25 13:19:13.130   354   354 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 35.353ms
08-25 13:19:13.153   354   354 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 20.485ms
08-25 13:19:13.155  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 13:19:13.155  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2041151f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 13:19:13.156  1927  2924 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 13:19:13.156  1927  2924 D SplitWindowPolicy: topRunningActivity=ActivityInfo{51fa06c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 13:19:13.177   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 629us total 22.988ms
08-25 13:19:13.189  6766  6766 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-25 13:19:13.251  6766  6766 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-25 13:19:13.258  6766  6766 I LibraryLoader: Loading: webviewchromium
08-25 13:19:13.260  6766  6766 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9512-9515)
08-25 13:19:13.260  6766  6766 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 13:19:13.275  6766  6766 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1108d325}
,08-25 13:19:13.276  6766  6766 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 13:19:13.277  6766  6766 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 13:19:13.285  6766  6766 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 13:19:13.286  6766  6766 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 13:19:13.317  6766  6766 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 13:19:13.317   327   327 V AudioPolicyService: registerClient() client 0xb14e9e80, uid 10118
,08-25 13:19:13.320  6766  6766 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-25 13:19:13.321  6766  6766 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-25 13:19:13.329  1035  1117 D BluetoothManagerService: Message: 20
,08-25 13:19:13.329  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3173dce9:true
08-25 13:19:13.352  6766  6766 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 13:19:13.352  6766  6766 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 13:19:13.352  6766  6766 I Adreno-EGL: Build Date: 12/12/14 금
08-25 13:19:13.352  6766  6766 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 13:19:13.352  6766  6766 I Adreno-EGL: Remote Branch: 
08-25 13:19:13.352  6766  6766 I Adreno-EGL: Local Patches: 
08-25 13:19:13.352  6766  6766 I Adreno-EGL: Reconstruct Branch: 
,08-25 13:19:13.466  6766  6811 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 13:19:13.470  6766  6766 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 13:19:13.490  6766  6766 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 13:19:13.495  6766  6766 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 13:19:13.499  6766  6766 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-25 13:19:13.506  6766  6766 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 13:19:13.506  6766  6766 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-25 13:19:13.524  6766  6766 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 13:19:13.531  6766  6766 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 13:19:13.531  6766  6766 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 13:19:13.578  6766  6828 D OpenGLRenderer: Render dirty regions requested: true
08-25 13:19:13.578  6766  6828 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 13:19:13.583  6766  6828 D OpenGLRenderer: Enabling debug mode 0
08-25 13:19:13.590  6766  6766 D Atlas   : Validating map...
08-25 13:19:13.596  1035  1997 D SplitWindow: check instance of lgWin Window{3223f41b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 13:19:13.666  6766  6826 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:13.667  6766  6826 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:13.710  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +558ms (total +637ms)
08-25 13:19:13.710  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{32420904 u0 com.test.thalitest/.MainActivity t6} time:159965
,08-25 13:19:13.711  6766  6766 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@353a5838 time:159966
08-25 13:19:13.851  6766  6766 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 13:19:13.931  6766  6826 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 13:19:13.931  6766  6826 I chromium: 
,08-25 13:19:14.077  6766  6842 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435177984
,08-25 13:19:14.095  6766  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 13:19:14.095  6766  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 13:19:14.095  6766  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 13:19:14.095  6766  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 13:19:14.095  6766  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 13:19:14.095  6766  6842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d8a277c added. We now have 1 listener(s)
08-25 13:19:14.098  6766  6766 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 13:19:14.098  6766  6766 I chromium: 
08-25 13:19:14.102  1035  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:14.104  6766  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-25 13:19:14.107  6766  6842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 13:19:14.111  6766  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:14.112  6766  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 13:19:14.120  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 13:19:14.121  6766  6842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63d228b added. We now have 1 listener(s)
08-25 13:19:14.121  6766  6842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:19:14.130  1035  1388 D WifiService: New client listening to asynchronous messages
08-25 13:19:14.134  6766  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 13:19:14.134  6766  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 13:19:14.135  6766  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 13:19:14.135  6766  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 13:19:14.135  6766  6842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 13:19:14.141  6766  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:14.141  1035  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:14.143  6766  6842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 13:19:14.158  6766  6842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:14.159  6766  6842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:14.159  6766  6842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 13:19:14.159  6766  6842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:14.161  6766  6842 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 13:19:14.162  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:14.164  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:14.203  6766  6766 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 13:19:14.555   349   359 E GBMv2   : DFP En is all cleared set to be enabled
,08-25 13:19:14.556   349   359 E GBMv2   : Set value is all cleared set the max
08-25 13:19:14.556   349   359 I GBMv2   : DFP Enabled. Ignore VFP set
08-25 13:19:15.032  6766  6845 W jxcore-log: Initializing JXcore engine
08-25 13:19:15.032  6766  6845 W jxcore-log: JXcore engine is ready
,08-25 13:19:15.078  6845  6845 W Thread-792: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9809]" dev="sockfs" ino=9809 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-25 13:19:15.078  6845  6845 W Thread-792: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-25 13:19:15.078  6845  6845 W Thread-792: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10485]" dev="sockfs" ino=10485 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 13:19:15.078  6845  6845 W Thread-792: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 13:19:15.078  6845  6845 W Thread-792: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33554]" dev="sockfs" ino=33554 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 13:19:15.100  6766  6845 W jxcore-log: Starting JXcore engine
,08-25 13:19:15.172  6766  6845 W jxcore-log: Platform android
08-25 13:19:15.172  6766  6845 W jxcore-log: 
08-25 13:19:15.172  6766  6845 W jxcore-log: Process ARCH arm
08-25 13:19:15.172  6766  6845 W jxcore-log: 
,08-25 13:19:15.371  6766  6845 I jxcore-log: JXcore Cordova bridge is ready!
08-25 13:19:15.371  6766  6845 I jxcore-log: 
08-25 13:19:15.371  6766  6845 W jxcore-log: JXcore engine is started
,08-25 13:19:15.379  6766  6842 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 13:19:15.382  6766  6766 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 13:19:25.962  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-25 13:19:25.962  6766  6845 I jxcore-log: 
,08-25 13:19:27.733  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-25 13:19:27.733  6766  6845 I jxcore-log: 
,08-25 13:19:27.764  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-25 13:19:27.764  6766  6845 I jxcore-log: 
,08-25 13:19:27.781  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-25 13:19:27.781  6766  6845 I jxcore-log: 
,08-25 13:19:27.804  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-25 13:19:27.804  6766  6845 I jxcore-log: 
,08-25 13:19:27.809  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-25 13:19:27.809  6766  6845 I jxcore-log: 
08-25 13:19:30.581  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 13:19:30.581  6766  6845 I jxcore-log: 
,08-25 13:19:30.585  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 13:19:30.585  6766  6845 I jxcore-log: 
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:30.591  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:30.593  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:30.595  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 13:19:30.595  6766  6845 I jxcore-log: 
08-25 13:19:30.597  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 13:19:30.597  6766  6845 I jxcore-log: 
,08-25 13:19:34.229  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-25 13:19:34.229  6766  6845 I jxcore-log: 
,08-25 13:19:34.243  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-25 13:19:34.243  6766  6845 I jxcore-log: 
,08-25 13:19:34.254  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-25 13:19:34.254  6766  6845 I jxcore-log: 
08-25 13:19:34.407  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-25 13:19:34.407  6766  6845 I jxcore-log: 
,08-25 13:19:35.190  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-25 13:19:35.190  6766  6845 I jxcore-log: 
,08-25 13:19:35.251  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-25 13:19:35.251  6766  6845 I jxcore-log: 
,08-25 13:19:35.260  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-25 13:19:35.260  6766  6845 I jxcore-log: 
08-25 13:19:35.454  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-25 13:19:35.454  6766  6845 I jxcore-log: 
,08-25 13:19:35.479  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-25 13:19:35.479  6766  6845 I jxcore-log: 
,08-25 13:19:35.484  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-25 13:19:35.484  6766  6845 I jxcore-log: 
,08-25 13:19:35.489  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-25 13:19:35.489  6766  6845 I jxcore-log: 
,08-25 13:19:35.505  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-25 13:19:35.505  6766  6845 I jxcore-log: 
,08-25 13:19:35.524  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-25 13:19:35.524  6766  6845 I jxcore-log: 
,08-25 13:19:35.610  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-25 13:19:35.610  6766  6845 I jxcore-log: 
,08-25 13:19:35.617  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-25 13:19:35.617  6766  6845 I jxcore-log: 
,08-25 13:19:35.643  6766  6845 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-25 13:19:35.643  6766  6845 I jxcore-log: 
,08-25 13:19:35.659  6766  6845 D ExecuteNativeTests: Running unit tests
,08-25 13:19:35.740  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 13:19:35.740  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c added. We now have 2 listener(s)
,08-25 13:19:35.741  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:35.743  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:35.743  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:35.743  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:35.743  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:35.743  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 added. We now have 2 listener(s)
08-25 13:19:35.743  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:35.744  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 13:19:35.746  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:35.748  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:35.749  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:19:35.749  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:35.750  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:35.751  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.754  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
,08-25 13:19:35.757  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-25 13:19:35.757  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:19:35.759  6766  6845 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 13:19:35.760  6766  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 13:19:35.760  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 13:19:35.761  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:19:35.761  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:19:35.761  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.762  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:19:35.762  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.762  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.763  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.763  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:35.763  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 13:19:35.763  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c removed from the list,
08-25 13:19:35.763  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.763  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 removed from the list
08-25 13:19:35.763  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.763  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.764  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:19:35.764  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.764  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.764  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.764  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.764  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list,
08-25 13:19:35.766  6766  6845 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 13:19:35.766  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.766  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.766  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.766  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-25 13:19:35.766  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.766  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.766  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.766  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:19:35.766  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.766  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.766  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:19:35.766  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.766  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.766  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.767  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.767  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-25 13:19:35.767  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.767  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
,08-25 13:19:35.770  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 13:19:35.771  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 13:19:35.771  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.771  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.771  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.772  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.772  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.772  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.772  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.772  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.772  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.772  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.772  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.772  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.772  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.772  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.773  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.773  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.773  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.773  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.774  6766  6845 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 13:19:35.775  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:35.777  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:35.778  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.778  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:35.779  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.779  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:35.780  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:35.780  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.785  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:19:35.785  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.785  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:19:35.788  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 13:19:35.788  1035  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:35.791  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 13:19:35.795  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 13:19:35.797  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 13:19:35.798  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:35.798  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:35.799  6766  6845 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 13:19:35.799  6766  6845 I io.jxcore.node.ConnectionHelper: start: OK
08-25 13:19:35.801  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.801  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.801  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.801  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.801  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.801  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:35.801  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.801  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.801  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.801  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.801  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.802  6766  6845 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 13:19:35.803  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:35.805  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:35.806  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.806  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:35.807  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.808  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.809  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:35.809  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:35.809  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:19:35.809  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.809  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:19:35.811  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:35.812  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:35.812  6766  6845 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 13:19:35.813  6766  6845 I io.jxcore.node.ConnectionHelper: start: OK
08-25 13:19:35.814  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.814  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.814  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.814  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.814  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 13:19:35.814  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:35.814  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.814  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.814  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.814  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.814  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.814  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.814  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.815  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.815  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.816  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.816  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.816  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.816  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.817  6766  6845 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 13:19:35.818  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:35.820  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:35.821  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.821  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:35.822  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.823  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.823  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:35.823  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:35.823  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:19:35.823  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.823  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:19:35.826  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:35.826  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:35.827  6766  6845 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 13:19:35.827  6766  6845 I io.jxcore.node.ConnectionHelper: start: OK
08-25 13:19:35.827  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.827  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.827  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.828  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.828  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.828  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.828  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.828  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.828  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:35.828  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.828  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.828  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.828  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.828  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.829  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.829  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.829  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.829  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.830  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.830  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.830  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.830  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.830  6766  6845 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 13:19:35.831  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.831  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.831  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.831  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.831  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.831  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.831  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.831  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.831  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.831  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.831  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.831  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.831  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.831  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.832  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.832  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.832  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.832  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.832  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.832  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.833  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 13:19:35.833  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.833  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.833  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.833  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.833  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.833  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.833  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.833  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.833  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.833  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.833  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.833  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.833  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.833  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.834  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.834  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.835  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.835  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.835  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.835  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.835  6766  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 13:19:35.835  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.835  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.835  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.836  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.836  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.836  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.836  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.836  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.836  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.836  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.836  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.836  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.836  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.836  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.837  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.837  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.837  6766  6845 D BluetoothLeScanner: could not find callback wrapper
,08-25 13:19:35.837  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.837  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.837  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.837  6766  6845 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 13:19:35.837  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.838  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.838  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.838  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.838  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.838  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.838  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.838  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.838  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.838  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.838  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.838  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.838  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.838  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.839  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.839  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.839  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.839  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.839  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.839  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.840  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 13:19:35.841  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:19:35.841  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:19:35.841  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:19:35.841  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 13:19:35.841  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:19:35.841  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.841  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.841  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.842  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.842  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.842  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.842  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.842  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.842  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.842  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.842  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.842  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.842  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.842  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.843  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.843  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.843  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.843  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.843  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.843  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.843  6766  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:19:35.843  6766  6845 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 13:19:35.844  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 13:19:35.846  6766  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:19:35.846  6766  6845 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 13:19:35.846  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 13:19:35.847  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 13:19:35.847  6766  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 13:19:35.848  6766  6845 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 13:19:35.849  6766  6845 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 13:19:35.849  6766  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:19:35.849  6766  6845 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 13:19:35.849  6766  6845 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 13:19:35.849  6766  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:19:35.849  6766  6845 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 13:19:35.849  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 13:19:35.851  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 13:19:35.852  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 13:19:35.852  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 13:19:35.854  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 13:19:35.854  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 13:19:35.854  6766  6845 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 13:19:35.854  6766  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:19:35.854  6766  6845 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 13:19:35.854  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.854  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.854  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.855  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.855  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.855  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.855  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 13:19:35.855  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.855  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.855  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.855  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.855  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.855  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.855  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.855  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.856  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.856  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.857  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.857  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.857  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.857  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.857  6766  6845 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 13:19:35.857  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.857  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.857  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.858  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.858  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.858  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.858  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.858  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.858  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.858  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.858  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.858  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.858  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.858  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.859  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.859  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.859  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.859  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.859  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.859  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.859  6766  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 13:19:35.860  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.860  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.860  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.861  6766  6854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 856)
08-25 13:19:35.865  6766  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 856
08-25 13:19:35.866  6766  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 856)
08-25 13:19:35.866  6766  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 856)
08-25 13:19:35.866  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.866  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.866  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.866  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.867  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.867  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.867  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.867  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.867  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.867  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.867  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.867  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.867  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.868  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.868  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.868  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.868  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.868  6766  6845 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 13:19:35.868  6766  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 13:19:35.869  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:19:35.869  6766  6845 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 13:19:35.869  6766  6845 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 13:19:35.869  6766  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 13:19:35.869  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:19:35.869  6766  6845 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 13:19:35.869  6766  6845 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 13:19:35.869  6766  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 13:19:35.869  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:19:35.869  6766  6845 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 13:19:35.869  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.869  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.869  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.870  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.870  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.870  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.870  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.870  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.870  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.870  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.870  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.870  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.870  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.870  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.871  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.871  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.871  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.871  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.871  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.871  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.871  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.871  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.871  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.872  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.872  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.872  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.872  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.872  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.872  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.872  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.872  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.872  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.872  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.872  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.872  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.872  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.872  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.872  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.872  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.873  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.873  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.873  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.873  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.873  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.873  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.873  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.873  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.873  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.873  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.873  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.873  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.874  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.874  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.874  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.874  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.876  6766  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 13:19:35.876  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.877  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 13:19:35.877  6766  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 13:19:35.877  6766  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 13:19:35.880  6766  6766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 13:19:35.881  1035  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:35.882  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 13:19:35.882  6766  6856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:35.882  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:19:35.884  4275  4412 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-25 13:19:35.886  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.886  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 13:19:35.886  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 13:19:35.886  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 13:19:35.888  6766  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-25 13:19:35.889  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.889  6766  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 13:19:35.889  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.889  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.889  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:19:35.889  6766  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:19:35.889  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:19:35.889  6766  6766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 13:19:35.889  6766  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 13:19:35.889  6766  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 13:19:35.890  6766  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 13:19:35.895  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 13:19:35.898  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:35.898  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:35.898  6766  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:19:35.898  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.898  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.898  6766  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:19:35.899  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.899  6766  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:19:35.899  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.899  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.899  6766  6766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 13:19:35.899  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.899  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.899  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.899  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.899  6766  6766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:19:35.899  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.899  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.899  6766  6766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:19:35.899  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.899  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.899  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.899  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.899  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.899  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.900  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.900  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.900  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.900  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.900  6766  6845 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 13:19:35.900  6766  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 13:19:35.901  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:19:35.902  6766  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:19:35.902  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.902  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.902  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.902  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.902  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.902  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.903  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.903  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.903  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.903  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.903  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.903  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.903  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.903  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.903  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.903  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.904  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.904  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.904  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:35.905  1035  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:35.906  1035  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:35.906  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.906  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.906  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.906  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.906  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.906  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.906  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.906  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.906  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.906  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.906  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.906  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.906  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.906  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.907  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.907  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.907  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.907  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.908  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:35.908  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:35.908  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:35.908  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:35.908  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.908  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.908  6766  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393a274c not in the list
08-25 13:19:35.908  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.908  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.908  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:35.908  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.908  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.908  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:35.908  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:35.909  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:35.909  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:35.909  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:35.909  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6841395 not in the list
08-25 13:19:35.910  6766  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 13:19:35.910  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:19:35.910  6766  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 13:19:35.910  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:19:35.910  6766  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 13:19:35.910  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:19:35.912  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 13:19:35.912  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 13:19:35.912  6766  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 13:19:35.912  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 13:19:35.912  6766  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 13:19:35.912  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 13:19:35.912  6766  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 13:19:35.912  6766  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 13:19:35.913  6766  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 13:19:35.913  6766  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 13:19:35.913  6766  6845 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 13:19:35.913  6766  6845 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 13:19:35.914  6766  6845 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 13:19:35.914  6766  6845 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 13:19:35.914  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:35.914  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bb76702 added. We now have 2 listener(s)
08-25 13:19:35.914  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:35.916  6766  6845 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 13:19:35.917  1035  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6766, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 13:19:35.917  1035  1051 D WifiService: setWifiEnabled: true pid=6766, uid=10118
08-25 13:19:35.917  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 13:19:35.918  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:35.918  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c05a813 added. We now have 3 listener(s)
08-25 13:19:35.918  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:35.921  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:35.921  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39508a50 added. We now have 4 listener(s)
08-25 13:19:35.921  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:35.922  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:35.922  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b4f7449 added. We now have 5 listener(s)
08-25 13:19:35.922  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:35.924  1035  2018 D WifiServiceImplEx: setWifiEnabled: false pid=6766, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 13:19:35.924  1035  2018 D WifiService: setWifiEnabled: false pid=6766, uid=10118
08-25 13:19:35.924  1035  2018 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 13:19:35.933  1035  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:35.933  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:35.934  1035  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:35.934  1035  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:35.934  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:35.936  1035  1375 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 13:19:35.936  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 13:19:35.937  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:35.937  1035  1962 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2b30998a mBinding = false
08-25 13:19:35.938  1035  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:19:35.938  1035  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 13:19:35.938  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:35.938  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-25 13:19:35.945  1035  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 13:19:35.945  1035  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 13:19:35.946  1035  1117 D BluetoothManagerService: Message: 2
08-25 13:19:35.946  1035  1117 D BluetoothManagerService: Sending off request.
08-25 13:19:35.947  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 13:19:35.948  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:35.948  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-25 13:19:35.949  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:35.950  4275  4291 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 13:19:35.950  1035  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 13:19:35.950  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 13:19:35.950  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:35.950  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:35.950  2606  2606 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:35.952  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:35.952  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.953  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:35.954  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.954  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:35.955  4275  4346 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 13:19:35.955  4275  4346 D BluetoothAdapterProperties: Setting state to 13
08-25 13:19:35.956  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 13:19:35.956  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 13:19:35.956  4275  4346 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 13:19:35.956  4275  4346 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 13:19:35.956  4275  4346 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 13:19:35.957  1035  1375 D WifiNative-wlan0: SET ps 1: returned true
08-25 13:19:35.959  4275  4349 D BluetoothAdapterProperties: Scan Mode:20
08-25 13:19:35.960  4275  4346 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 13:19:35.960  4275  4582 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 13:19:35.960  4275  4582 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:35.960  4275  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 13:19:35.960  ,4275  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 13:19:35.960  4275  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 13:19:35.960  4275  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 13:19:35.960  4275  4582 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 13:19:35.960  4275  4582 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 13:19:35.961  1035  2773 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:35.961  4275  4583 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:35.961  4275  4346 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 13:19:35.961  4275  4662 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:35.961  4275  4660 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:35.962  4275  4664 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 13:19:35.963  4275  4481 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 13:19:35.963  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 13:19:35.963  4275  4481 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 13:19:35.967   323   889 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:19:35.968  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:35.968  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:35.968  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:35.968  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.984  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:35.984  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:35.986  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:35.986  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:35.992  1035  1106 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6865 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-25 13:19:35.997  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 13:19:35.997  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-25 13:19:36.001  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:36.001  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:36.002  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-25 13:19:36.002  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.002  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.002  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:36.003  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:36.003  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 13:19:36.003  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 13:19:36.003  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 13:19:36.004  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:36.005  1035  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.005  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.005  1035  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:36.005  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:36.005  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:36.006  1035  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:36.006  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:36.006  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:36.007  1035  1375 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 13:19:36.007  1035  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ac8384b
08-25 13:19:36.007  1035  1374 D LGWifiP2pService: P2pDisablingState
08-25 13:19:36.007  1035  1374 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.007  1035  1374 D LGWifiP2pService: p2p socket connection lost
08-25 13:19:36.007  1035  1374 D LGWifiP2pService: P2pDisabledState
08-25 13:19:36.008  1035  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 13:19:36.008  1035  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.008  1035  1374 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.008  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 13:19:36.008  2606  2606 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-25 13:19:36.008  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 13:19:36.008  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 13:19:36.009  1035  1375 D WifiNative-wlan0: SET ps 1: returned true
08-25 13:19:36.016  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-25 13:19:36.038  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:36.038  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 13:19:36.040  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.040  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.040  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:36.040  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 13:19:36.040  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-25 13:19:36.040  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.040  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:36.041  1035  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.042  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 13:19:36.042  1927  1927 D WfdsService: WifiP2pState is changed : false
08-25 13:19:36.042  1927  2207 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 13:19:36.042  1927  2207 D WfdsService: Set the WFDS Monitor: false
08-25 13:19:36.043  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
08-25 13:19:36.043  1927  2207 D WfdsService: STATE : WfdsDisabledState - enter
08-25 13:19:36.043  1927  2696 D CtrlSupplicant: Received on exit socket, terminate
08-25 13:19:36.043  1927  2696 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 13:19:36.043  1927  2696 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 13:19:36.043  1927  2696 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 13:19:36.044  1927  2209 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 13:19:36.044  4275  4275 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:36.044  1927  2207 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 13:19:36.044  4275  4275 D BluetoothMapService: STATE_TURNING_OFF
08-25 13:19:36.044  4275  4275 V BluetoothMapService: Handler(): got msg=4
08-25 13:19:36.044  4275  4275 D BluetoothMapService: MAP Service closeService in
08-25 13:19:36.044  4275  4275 D BluetoothMapMasInstance: MAP Service shutdown
08-25 13:19:36.045  4275  4275 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 13:19:36.045  4275  4275 V BluetoothMapService: MAP Service closeService out
08-25 13:19:36.045  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:36.046  4275  4275 V BtOppService: Receiver DISABLED_ACTION 
08-25 13:19:36.046  4275  4275 I BtOppRfcommListener: stopping Accept Thread
08-25 13:19:36.046  4275  4275 V BtOppRfcommListener: close mBtServerSocket
08-25 13:19:36.046  4275  4275 V BtOppRfcommListener: waiting for thread to terminate
08-25 13:19:36.046  4275  4660 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 13:19:36.047  4275  4275 V BtOppRfcommListener: done waiting for thread to terminate
08-25 13:19:36.049  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.049  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:36.049  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:36.049  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:36.049  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:36.049  6766  6766 V io.jxco,re.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:36.049  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:36.049  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:36.049  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:36.052  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.052  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:36.056  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:36.056  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:36.057  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.057  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:36.058   323   889 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:19:36.058  1035  1405 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 13:19:36.058  1035  1405 D DSQN    : disableDataServiceNotify
08-25 13:19:36.058  1035  1405 D DSQN    : stop dsqn bin
08-25 13:19:36.059  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 13:19:36.063  1035  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-25 13:19:36.063  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.063  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.064  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 13:19:36.065  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.065  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-25 13:19:36.069  1035  1405 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 13:19:36.069  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:36.069  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:36.070  1035  1405 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:36.070  1035  1405 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 13:19:36.070  1035  1405 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 13:19:36.071  1035  1405 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 13:19:36.071  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:19:36.071  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 13:19:36.074   323  6896 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 13:19:36.075  1035  1106 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6892 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 13:19:36.076  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-25 13:19:36.076  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.076  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:36.076  1035  2771 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 13:19:36.076  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 13:19:36.081  1035  1375 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 13:19:36.082  1035  1375 D WifiNative-p2p0: TERMINATE: returned true
,08-25 13:19:36.082  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:36.082  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:36.082  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 13:19:36.085  1035  1405 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:36.085  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:19:36.085  4275  4275 V BtOppService: onDestroy
08-25 13:19:36.085  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-25 13:19:36.090  6766  6854 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-25 13:19:36.090  6766  6854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 856)
08-25 13:19:36.091  1035  1405 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:36.091  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.091  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.091  1035  1405 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:36.091  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:36.092  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 13:19:36.092  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 13:19:36.092  1035  1405 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:36.092  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 13:19:36.092  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 13:19:36.092  1035  1405 D NetworkManagementService: Removing idletimer
08-25 13:19:36.092  1035  1405 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.093  1035  1405 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 13:19:36.093  1035  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 13:19:36.093  1035  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 13:19:36.093  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 13:19:36.093  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 13:19:36.093  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 13:19:36.093  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 13:19:36.093  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:36.093  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 13:19:36.095  4275  4275 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAda,pter cleanup
08-25 13:19:36.095  1035  1375 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:36.095  1035  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:36.097  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 13:19:36.097  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:36.097  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 13:19:36.098  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 13:19:36.101  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:36.101  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:36.102  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.102  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:19:36.104  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:36.104  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:36.104  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:36.104  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:36.107  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 13:19:36.108  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:36.108  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 13:19:36.130  6892  6892 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:36.130  6892  6892 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 13:19:36.130  6892  6892 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 13:19:36.130  6892  6892 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 13:19:36.131  6892  6892 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 13:19:36.131  6892  6892 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 13:19:36.148  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:36.149  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:36.149  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 13:19:36.157  6865  6865 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 13:19:36.157  6865  6865 W LG Account v2.2: No ProfileInfo entries
08-25 13:19:36.157  6865  6865 I LG Account v2.2: isEnabled: false
08-25 13:19:36.157  6865  6865 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 13:19:36.157  6865  6865 I Feature : [Lifetracker]Country: EU
08-25 13:19:36.157  6865  6865 I Feature : [Lifetracker]Operator: OPEN
08-25 13:19:36.157  6865  6865 I Feature : [Lifetracker]Ranking support: false
08-25 13:19:36.158  6865  6865 I Feature : [Lifetracker]Comfort support: false
08-25 13:19:36.158  6865  6865 I Feature : [Lifetracker]Accessory: true
08-25 13:19:36.158  6865  6865 I Feature : [Lifetracker]Health device: true
08-25 13:19:36.158  6865  6865 I Feature : [Lifetracker]Extra Pedometer: false
08-25 13:19:36.158  6865  6865 I Feature : [Lifetracker]Blood glucose device: false
08-25 13:19:36.158  6865  6865 I Feature : [Lifetracker]Device Number: 3
,08-25 13:19:36.161  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:36.162  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:36.162  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:36.162  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:36.164  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:36.195  1035  1772 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6914 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 13:19:36.196  1035  1772 I ActivityManager: Killing 6277:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-25 13:19:36.206  2606  2606 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 13:19:36.207  2606  2606 I wpa_supplicant: monitor socket send errors count : 1
08-25 13:19:36.207  2606  2606 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
08-25 13:19:36.207  1035  2683 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 13:19:36.207  1035  2683 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-25 13:19:36.236  1035  1962 W libprocessgroup: failed to open /acct/uid_10014/pid_6277/cgroup.procs: No such file or directory
,08-25 13:19:36.246  2606  2606 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 13:19:36.247  1035  1117 D Tethering: InitialState.processMessage what=4
08-25 13:19:36.247  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:19:36.247  1035  2683 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 13:19:36.248  1035  2683 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 13:19:36.248  1035  2683 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 13:19:36.248  2606  2606 W wpa_supplicant: USIM:  scard_deinit function
08-25 13:19:36.248  1035  2683 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 13:19:36.248  1035  2683 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:36.248  1035  1375 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:36.249  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:36.249  1035  1375 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=182489
08-25 13:19:36.249  1035  1375 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=182490
08-25 13:19:36.249  1035  2683 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:36.250  1035  1375 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=182490  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 13:19:36.251  1035  1375 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=182491  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-25 13:19:36.268  1035  2773 D DhcpStateMachine: StoppedState
,08-25 13:19:36.268  1035  2773 D DhcpStateMachine: StoppedState{ when=-260ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:19:36.270  1035  1375 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 13:19:36.270  1035  1375 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 13:19:36.294  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 13:19:36.309  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:36.309  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:36.311  1035  1980 I ActivityManager: Killing 6478:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-25 13:19:36.321  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 13:19:36.342  2606  2606 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 13:19:36.343  1035  2683 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 13:19:36.343  1035  2683 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 13:19:36.343  1035  2683 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-25 13:19:36.344  1035  1375 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-25 13:19:36.369  1035  1560 W libprocessgroup: failed to open /acct/uid_10008/pid_6478/cgroup.procs: No such file or directory
,08-25 13:19:36.378  4275  4275 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 13:19:36.378  4275  4275 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:36.378  4275  4275 V BluetoothPbapReceiver: ***********state = 13
08-25 13:19:36.381  4275  4275 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 13:19:36.383  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:36.383  4275  4275 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:36.383  4275  4275 V BluetoothPbapService: state: 13
08-25 13:19:36.383  4275  4275 V BluetoothPbapService: Pbap Service closeService in
08-25 13:19:36.388  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:19:36.392  4275  4275 V BluetoothPbapService: successfully stopped pbap service
08-25 13:19:36.392  4275  4275 V BluetoothPbapService: Pbap Service closeService out
08-25 13:19:36.393  4275  4275 V BluetoothPbapService: Pbap Service onDestroy
08-25 13:19:36.393  4275  4275 V BluetoothPbapService: Pbap Service closeService in
08-25 13:19:36.393  4275  4275 V BluetoothPbapService: Pbap Service closeService out
08-25 13:19:36.393  4275  4275 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-25 13:19:36.400  6766  6766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 13:19:36.425  6892  6892 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:36.425  6892  6892 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:36.438  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:36.449  1927  1927 D WfdsService: Supplicant Connection state is changed : false
,08-25 13:19:36.450  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 13:19:36.450  1927  2207 D WfdsService: Set the WFDS Monitor: false
08-25 13:19:36.450  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
08-25 13:19:36.451  1035  1375 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 13:19:36.451  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:36.451  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:36.451  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 13:19:36.453  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:36.454  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 13:19:36.459  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 13:19:36.460  1035  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 13:19:36.460  1035  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 13:19:36.461  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:36.462  2495  2495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:36.467  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:36.470  1035  1117 D BluetoothManagerService: Message: 20
08-25 13:19:36.470  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ffa20ad:true
08-25 13:19:36.482  1035  1117 D BluetoothManagerService: Message: 30
,08-25 13:19:36.487  1035  1117 D BluetoothManagerService: Message: 30
08-25 13:19:36.489  6892  6892 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 13:19:36.491  6892  6892 D BluetoothMap: Create BluetoothMap proxy object
08-25 13:19:36.492  1035  1117 D BluetoothManagerService: Message: 30
08-25 13:19:36.496  1035  1117 D BluetoothManagerService: Message: 30
,08-25 13:19:36.498  6892  6892 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 13:19:36.499  6892  6892 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 13:19:36.512  6892  6892 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 13:19:36.515  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 13:19:36.718  1035  1560 I art     : Explicit concurrent mark sweep GC freed 57333(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.560ms total 201.178ms
,08-25 13:19:36.730  6892  6892 D DockEventReceiver: finishStartingService: stopping service
08-25 13:19:36.746  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 13:19:36.751  6892  6892 D BluetoothInputDevice: Proxy object connected
,08-25 13:19:36.752  6892  6892 D HidProfile: Bluetooth service connected
08-25 13:19:36.753  6892  6892 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:19:36.753  6892  6892 D PanProfile: Bluetooth service connected
08-25 13:19:36.754  6892  6892 D BluetoothMap: Proxy object connected
08-25 13:19:36.755  6892  6892 D MapProfile: Bluetooth service connected
08-25 13:19:36.755  6892  6892 D BluetoothMap: getConnectedDevices()
08-25 13:19:36.756  6892  6892 D BluetoothMap: Bluetooth is Not enabled
08-25 13:19:36.756  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 13:19:36.759  6892  6892 D BluetoothPermissionRequest: onReceive
,08-25 13:19:36.765  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 13:19:36.775  1035  1980 I ActivityManager: Killing 6011:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-25 13:19:36.777  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 13:19:36.807  4275  4275 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-25 13:19:36.807  4275  4275 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 13:19:36.808  4275  4275 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 13:19:36.810  1035  1560 W libprocessgroup: failed to open /acct/uid_10011/pid_6011/cgroup.procs: No such file or directory
08-25 13:19:36.820  4275  4275 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:36.820  4275  4275 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 13:19:36.822  4275  4275 V BluetoothFtpService: Ftp Service onStartCommand
08-25 13:19:36.822  4275  4275 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:19:36.823  4275  4275 V BluetoothFtpService: Ftp Service closeService
08-25 13:19:36.823  4275  4275 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 13:19:36.828  4275  4275 V BluetoothFtpService: successfully stopped ftp service
08-25 13:19:36.829  4275  4275 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 13:19:36.829  4275  4275 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 13:19:36.829  4275  4275 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:36.829  4275  4275 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:36.829  4275  4275 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 13:19:36.829  4275  4275 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 13:19:36.831  4275  4275 V BluetoothFtpService: Ftp Service onDestroy
08-25 13:19:36.831  4275  4275 V BluetoothFtpService: Ftp Service closeService
08-25 13:19:36.832  4275  4275 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:36.832  4275  4275 V BluetoothSapService: state: 13
08-25 13:19:36.832  4275  4275 V BluetoothSapService: Stopping SAP server process
08-25 13:19:36.834  4275  4275 V BluetoothSapService: Sap Service closeSapService in
08-25 13:19:36.834  4275  4275 V BluetoothSapService: Close listen Socket : 
08-25 13:19:36.834  4275  4275 V BluetoothSapService: Close rfcomm Socket : 
08-25 13:19:36.835  4275  4275 V BluetoothSapService: Close sapd  Socket : 
,08-25 13:19:36.922  1035  2015 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6946 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 13:19:36.930  4275  4275 V BluetoothSapService: Sap Service closeSapService out
08-25 13:19:36.930  4275  4275 V BluetoothSapService: Sap Service onDestroy
08-25 13:19:36.930  4275  4275 V BluetoothSapService: Sap Service closeSapService in
08-25 13:19:36.930  4275  4275 V BluetoothSapService: Close listen Socket : 
08-25 13:19:36.930  4275  4275 V BluetoothSapService: Close rfcomm Socket : 
08-25 13:19:36.930  4275  4275 V BluetoothSapService: Close sapd  Socket : 
08-25 13:19:36.967  4275  4349 D bt_hci_bdroid: cleanup
08-25 13:19:36.967  4275  4488 I bt_lpm  : LPM is already off!!!
,08-25 13:19:36.968  4275  4569 I bt_userial_mct: exiting userial_read_thread
08-25 13:19:36.968  4275  4569 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 13:19:36.968  4275  4481 W bt-btif : ag scb idx 1 not allocated
08-25 13:19:36.968  4275  4481 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 13:19:36.968  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:36.968  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:36.968  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:36.968  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:36.968  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:36.969  4275  4481 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:36.969  4275  4481 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 13:19:36.970  4275  4349 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 13:19:36.970  4275  4488 I bt_vendor: hw_epilog_process
08-25 13:19:36.971  4275  4349 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 13:19:36.971  4275  4349 D bt_userial_mct: userial_close
08-25 13:19:36.971  4275  4349 E bt_userial_mct: pthread_join() FAILED result:3
08-25 13:19:36.971  4275  4349 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 13:19:36.994  1035  2015 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6964 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 13:19:36.995  4275  4275 V BluetoothSapService: Sap Service closeSapService out
08-25 13:19:37.029  6946  6946 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 13:19:37.050  4275  4349 D bt_hci_bdroid: set_power 0
,08-25 13:19:37.051  4275  4349 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 13:19:37.051  4275  4349 I bt_vendor: bluetooth satus is on
08-25 13:19:37.051  4275  4349 I bt_vendor: bt-vendor : resetting BT status
08-25 13:19:37.051  4275  4349 I bt_vendor: Starting hciattach daemon
08-25 13:19:37.051  4275  4349 I bt_vendor: try to set false
08-25 13:19:37.052  4275  4349 I bt_vendor: Starting hciattach daemon
08-25 13:19:37.052  4275  4349 I bt_vendor: try to set false
08-25 13:19:37.052  4275  4349 I bt_vendor: cleanup
08-25 13:19:37.053  4275  4481 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 13:19:37.053  4275  4349 I GKI_LINUX: GKI_exit_task 0 done
08-25 13:19:37.053  4275  4349 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 13:19:37.054  4275  4346 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 13:19:37.057  4275  4275 D HeadsetService: Received stop request...Stopping profile...
,08-25 13:19:37.058  4275  4275 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 13:19:37.058  4275  4275 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 13:19:37.058  4275  4275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b55cfa
08-25 13:19:37.059  4275  4411 D HeadsetStateMachine: Exit Disconnected: -1
08-25 13:19:37.060  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:37.060  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:37.060  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 13:19:37.060  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:37.060  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:37.061  4275  4275 D A2dpService: Received stop request...Stopping profile...
08-25 13:19:37.062  4275  4457 D A2dpStateMachine: Exit Disconnected: -1
08-25 13:19:37.063  6946  6946 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 13:19:37.063  4275  4346 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 13:19:37.064  4275  4275 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 13:19:37.067  6964  6964 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 13:19:37.068  4275  4275 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 13:19:37.068  4275  4275 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 13:19:37.068  4275  4275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b55cfa
08-25 13:19:37.069  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-25 13:19:37.069  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 13:19:37.071  4275  4275 D HidService: Received stop request...Stopping profile...
08-25 13:19:37.071  4275  4275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b55cfa
08-25 13:19:37.073  4275  4275 D HealthService: Received stop request...Stopping profile...
08-25 13:19:37.073  4275  4275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b55cfa
08-25 13:19:37.076  6892  6892 D BluetoothInputDevice: Proxy object disconnected
08-25 13:19:37.076  6892  6892 D HidProfile: Bluetooth service disconnected
08-25 13:19:37.077  4275  4275 D PanService: Received stop request...Stopping profile...
08-25 13:19:37.077  4275  4275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b55cfa
08-25 13:19:37.078  4275  4275 D HeadsetStateMachine: Unbinding service...
,08-25 13:19:37.081  4275  4275 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 13:19:37.081  4275  4275 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 13:19:37.081  4275  4275 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 13:19:37.081  4275  4275 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 13:19:37.081  4275  4275 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 13:19:37.081  4275  4275 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 13:19:37.081  4275  4275 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 13:19:37.082  4275  4275 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 13:19:37.082  4275  4275 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 13:19:37.082  4275  4275 D BtGatt.GattService: stop()
08-25 13:19:37.082  4275  4275 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 13:19:37.083  4275  4275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b55cfa
08-25 13:19:37.083  6892  6892 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 13:19:37.083  6892  6892 D PanProfile: Bluetooth service disconnected
08-25 13:19:37.084  4275  4275 D BluetoothMapService: Received stop request...Stopping profile...
08-25 13:19:37.084  4275  4275 D BluetoothMapService: stop()
08-25 13:19:37.085  4275  4275 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 13:19:37.085  4275  4275 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 13:19:37.086  4275  4275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24b55cfa
08-25 13:19:37.087  4275  4275 I BluetoothA2dpServiceJni: cleanupNative
08-25 13:19:37.087  4275  4461 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 13:19:37.087  4275  4275 I GKI_LINUX: GKI_exit_task 2 done
08-25 13:19:37.087  4275  4275 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 13:19:37.088  4275  4275 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 13:19:37.088  4275  4275 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 13:19:37.088  4275  4275 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 13:19:37.088  4275  4275 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 13:19:37.088  4275  4275 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 13:19:37.088  4275  4275 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 13:19:37.088  4275  4275 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 13:19:37.090  4275  4275 V BluetoothMapService: Handler(): got msg=4
08-25 13:19:37.090  4275  4275 D BluetoothMapService: MAP Service closeService in
08-25 13:19:37.090  4275  4275 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 13:19:37.090  4275  4275 V BluetoothMapService: MAP Service closeService out
08-25 13:19:37.090  4275  4275 D BluetoothMapService: cleanup()
08-25 13:19:37.090  4275  4275 D BluetoothMapService: MAP Service closeService in
08-25 13:19:37.090  4275  4275 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 13:19:37.090  4275  4275 V BluetoothMapService: MAP Service closeService out
08-25 13:19:37.090  4275  4346 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 13:19:37.090  4275  4346 D BluetoothAdapterProperties: Setting state to 10
08-25 13:19:37.090  4275  4346 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 13:19:37.091  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:37.091  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 13:19:37.091  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStat,eChange(false) to 9 receivers.
,08-25 13:19:37.092  4275  4346 I BluetoothAdapterState: Entering OffState
08-25 13:19:37.092  6892  6910 D BluetoothMap: onBluetoothStateChange: up=false
08-25 13:19:37.094  1035  1997 I ActivityManager: Killing 6033:com.android.contacts/u0a19 (adj 15): empty #17
08-25 13:19:37.109  6946  6946 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-25 13:19:37.110  6946  6946 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 13:19:37.110  6946  6946 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 13:19:37.111  6946  6946 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 13:19:37.111  6946  6946 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 13:19:37.113  6946  6946 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 13:19:37.118  6946  6946 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-25 13:19:37.137  1035  1050 W libprocessgroup: failed to open /acct/uid_10019/pid_6033/cgroup.procs: No such file or directory
,08-25 13:19:37.139  1839  2446 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:37.141  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:37.143  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 13:19:37.143  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:37.144  6892  6908 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 13:19:37.145  6892  6910 D BluetoothPan: onBluetoothStateChange on: false
08-25 13:19:37.146  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:37.147  6892  6908 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 13:19:37.148  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:37.150  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:37.150  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 13:19:37.150  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 13:19:37.154  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-25 13:19:37.154  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 13:19:37.154  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2b30998a mBinding = false
08-25 13:19:37.155  1035  1117 D BluetoothManagerService: Sending unbind request.
08-25 13:19:37.156  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 13:19:37.161  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:37.161  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 13:19:37.162  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:37.163  1927  2086 D LGBluetoothAPIService: Message: 2
08-25 13:19:37.163  1927  2086 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@10e06635 mBinding = false
08-25 13:19:37.163  1927  2086 D LGBluetoothAPIService: Sending unbind request.
08-25 13:19:37.163  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:37.165  4275  4349 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 13:19:37.165  4275  4275 I GKI_LINUX: GKI_exit_task 1 done
08-25 13:19:37.165  4275  4275 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 13:19:37.166  4275  4275 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 13:19:37.166  4275  4275 I art     : --- WEIRD: removing null entry 246
08-25 13:19:37.166  4275  4275 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 13:19:37.166  4275  4275 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-25 13:19:37.168  6892  6892 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 13:19:37.169  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 13:19:37.169  6892  6892 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 13:19:37.173  4275  4275 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 13:19:37.176  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 13:19:37.177  1586  1586 D BluetoothAdapter: 313502162: getState() :  mService = null. Returning STATE_OFF
08-25 13:19:37.177  1586  1586 D BluetoothAdapter: 313502162: getState() :  mService = null. Returning STATE_OFF
08-25 13:19:37.180  4275  4275 I art     : System.exit called, status: 0
08-25 13:19:37.180  4275  4275 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 13:19:37.183  6892  6892 D DockEventReceiver: finishStartingService: stopping service
08-25 13:19:37.191  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 13:19:37.193  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:37.195  6946  6946 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 13:19:37.198  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 13:19:37.198  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:37.198  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:37.200  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:37.201   327  1385 V AudioFlinger: 4275 died, releasing its sessions
08-25 13:19:37.201   327  1385 V AudioFlinger:  pid 1839 @ 0
08-25 13:19:37.201   327  1385 V AudioFlinger:  pid 3424 @ 1
08-25 13:19:37.201   327  1385 V AudioFlinger:  pid 3424 @ 2
08-25 13:19:37.204  6946  6946 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-25 13:19:37.207  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:37.207  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 13:19:37.225  1035  1889 I ActivityManager: Process com.android.bluetooth (pid 4275) has died
08-25 13:19:37.226  1035  1889 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-25 13:19:37.236  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:19:37.242  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:37.243  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:37.247  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 13:19:37.259  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:37.265  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 13:19:37.266  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:37.266  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:37.270  6892  6892 D BluetoothPermissionRequest: onReceive
08-25 13:19:37.277  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:37.288  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:37.290  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 13:19:37.291  6892  6892 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-25 13:19:37.292  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 13:19:37.377  1035  1703 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6986 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 13:19:37.391  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:37.391  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 13:19:37.395  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 13:19:37.451  1035  1772 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7003 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 13:19:37.478  6986  6986 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 13:19:37.478  6986  6986 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 13:19:37.479  6986  6986 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-25 13:19:37.479  6986  6986 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 13:19:37.499  6986  6986 D BluetoothAdapterApp: Loading JNI Library
,08-25 13:19:37.533  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:37.539  6986  6986 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3611b033 Instance Count = 1
08-25 13:19:37.539  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 13:19:37.544  6986  6986 D BluetoothAdapterApp: onCreate
08-25 13:19:37.548  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:37.570  6986  6986 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-25 13:19:37.571  6986  6986 D ProfileConfigQcom: Adding HeadsetService
08-25 13:19:37.571  6986  6986 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 13:19:37.571  6986  6986 D ProfileConfigQcom: Adding A2dpService
08-25 13:19:37.571  6986  6986 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 13:19:37.571  6986  6986 D ProfileConfigQcom: Adding HidService
08-25 13:19:37.572  6986  6986 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 13:19:37.572  6986  6986 D ProfileConfigQcom: Adding HealthService
08-25 13:19:37.572  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 13:19:37.572  6986  6986 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 13:19:37.572  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 13:19:37.572  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 13:19:37.573  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 13:19:37.573  7003  7022 W FormManager: Network not available. Please check & try again.
08-25 13:19:37.574  6986  6986 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 13:19:37.574  6986  6986 D ProfileConfigQcom: Adding PanService
08-25 13:19:37.574  6986  6986 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 13:19:37.574  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 13:19:37.575  6986  6986 D ProfileConfigQcom: Adding GattService
08-25 13:19:37.575  6986  6986 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 13:19:37.575  6986  6986 D ProfileConfigQcom: Adding BluetoothMapService
08-25 13:19:37.576  6986  6986 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 13:19:37.577  6986  6986 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 13:19:37.584  6986  6986 V LGMDMManagerInternal: Create singleton instance
,08-25 13:19:37.591  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 13:19:37.592  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 13:19:37.592  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 13:19:37.592  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 13:19:37.592  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 13:19:37.592  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 13:19:37.595  7003  7024 V FormManager: Network unavailable.
08-25 13:19:37.596  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 13:19:37.598  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:37.599  7003  7024 V FormManager: Network unavailable.
08-25 13:19:37.599  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 13:19:37.601  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 13:19:37.606  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:37.612  6914  6914 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 13:19:37.612  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:37.612  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:37.615  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:19:37.624  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:37.624  4735  7027 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 13:19:37.639  7003  7028 W FormManager: Network not available. Please check & try again.
08-25 13:19:37.642  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-25 13:19:37.643  4735  7031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:37.643  4735  7031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 13:19:37.644  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 13:19:37.645  7003  7030 V FormManager: Network unavailable.
08-25 13:19:37.645  6946  6946 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 13:19:37.647  7003  7030 V FormManager: Network unavailable.
08-25 13:19:37.660  1035  1771 I ActivityManager: Killing 6510:com.lge.email/u0a23 (adj 15): empty #17
,08-25 13:19:37.690  6946  6946 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 13:19:37.690  6946  6946 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:37.697  6946  6946 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 13:19:37.698  6946  6946 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 13:19:37.698  6946  6946 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-25 13:19:37.698  6946  6946 V SoundPool: doLoad: loading sample sampleID=1
08-25 13:19:37.699  6946  6946 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 13:19:37.700  6946  7040 V SoundPool: Start decode
08-25 13:19:37.700  6946  7040 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-25 13:19:37.701   327  1385 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 13:19:37.701   327  1385 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 13:19:37.701   327  1385 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 13:19:37.701   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 13:19:37.701   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
,08-25 13:19:37.701   327  1385 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 13:19:37.701   327  1385 V MediaPlayerService: player type = 3
08-25 13:19:37.701   327  1385 V AwesomePlayer: AwesomePlayer create()
08-25 13:19:37.702   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:37.702   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:37.702   327  1385 V AwesomePlayer: setAudioSink() 
08-25 13:19:37.702   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:37.702   327  1385 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-25 13:19:37.702   327  1385 V AudioCache: ignored
08-25 13:19:37.702   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:37.702   327  1385 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 13:19:37.702   327  1385 V AwesomePlayer: setDataSource_l dataSource
08-25 13:19:37.702   327  1385 V LGParserOSAL: SniffLGParser start
08-25 13:19:37.702   327  1385 V LGParserOSAL: MainType:5, SubType=0
08-25 13:19:37.702   327  1385 V LGParserOSAL: #### check Mime : application/ogg
08-25 13:19:37.702   327  1385 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 13:19:37.702   327  1385 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 13:19:37.717  1035  1944 W libprocessgroup: failed to open /acct/uid_10023/pid_6510/cgroup.procs: No such file or directory
,08-25 13:19:37.718  6986  6986 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:37.724  6665  6665 D UEI.SmartControl: QS Service created
08-25 13:19:37.726  6946  6946 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-25 13:19:37.738  6665  6665 I UEI.SmartControl: Service initServices...
08-25 13:19:37.738  6665  6665 D UEI.SmartControl: QS start get config
08-25 13:19:37.738  6946  6946 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 13:19:37.739  6986  6986 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 13:19:37.739  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 13:19:37.740  6986  6986 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 13:19:37.740  6986  6986 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:37.744  6986  6986 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:37.744  6986  6986 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 13:19:37.753   327  1385 V LGParserOSAL: supported mime: application/ogg
08-25 13:19:37.753   327  1385 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 13:19:37.753   327  1385 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 13:19:37.753   327  1385 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 13:19:37.753   327  1385 V AwesomePlayer: AudioTrack Setting
08-25 13:19:37.753   327  1385 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 13:19:37.753   327  1385 V AwesomePlayer: setAudioSource() 
08-25 13:19:37.753   327  1385 V MediaPlayerService: prepare
08-25 13:19:37.753   327  1385 V AwesomePlayer: prepareAsync_l() 
08-25 13:19:37.753   327  1385 V MediaPlayerService: wait for prepare
08-25 13:19:37.754   327  7042 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 13:19:37.754   327  7042 V AwesomePlayer: initAudioDecoder() 
08-25 13:19:37.754   327  7042 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 13:19:37.754   327  7042 V AudioSystem: isOffloadSupported()
08-25 13:19:37.754   327  7042 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 13:19:37.754   327  7042 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 13:19:37.754   327  7042 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 13:19:37.754   327  7042 V AwesomePlayer: getUseOffload() = 0 
08-25 13:19:37.755   327  7042 V OMXCodec: OMXCodec::Create
08-25 13:19:37.755   327  7042 V OMXCodec: findMatchingCodecs()
08-25 13:19:37.755   327  7042 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 13:19:37.755   327  7042 V OMXCodec: matchingCodecs.size()=1
08-25 13:19:37.755   327  7042 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-25 13:19:37.762  6964  6964 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 13:19:37.762   327  7042 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 13:19:37.762   327  7042 V LGCodecAdapter: LG Codec Adapter start
08-25 13:19:37.763   327  7042 V OMXCodec: OMXCodec Createtor
08-25 13:19:37.763   327  7042 V OMXCodec: setComponentRole
08-25 13:19:37.763   327  7042 V OMXCodec: configureCodec protected=0
08-25 13:19:37.763   327  7042 V LGCodecAdapter: called getLGCodecSpecificData
08-25 13:19:37.763   327  7042 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 13:19:37.763   327  7042 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 13:19:37.763   327  7042 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 13:19:37.763   327  7042 V LGCodecOSAL: Not support LGCodec
08-25 13:19:37.763   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 13:19:37.763   327  7042 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 13:19:37.763   327  7042 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 13:19:37.764   327  7042 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 13:19:37.764   327  7042 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 13:19:37.764   327  7042 V AudioSystem: isOffloadSupported()
08-25 13:19:37.764   327  7042 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 13:19:37.764   327  7042 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 13:19:37.764   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 13:19:37.764   327  7042 V OMXCodec: init()
08-25 13:19:37.764   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 13:19:37.764   327  7042 V OMXCodec: allocateBuffers
08-25 13:19:37.764   327  7042 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 13:19:37.764   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 13:19:37.764  6946  6946 V LGMDMManager: Create singleton instance
08-25 13:19:37.765   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010920 on input port
08-25 13:19:37.765   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010970 on input port
08-25 13:19:37.765   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb00109c0 on input port
08-25 13:19:37.765   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010a10 on input port
08-25 13:19:37.765   327  7042 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 13:19:37.765   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-25 13:19:37.766   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010a60 on output port
08-25 13:19:37.766   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010b50 on output port
08-25 13:19:37.766   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010d30 on output port
08-25 13:19:37.766   327  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010d80 on output port
08-25 13:19:37.766   327  7042 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 13:19:37.766   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 13:19:37.766   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 13:19:37.766   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 13:19:37.766   327  7042 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-25 13:19:37.766   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 13:19:37.766   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 13:19:37.766   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 13:19:37.766   327  7042 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 13:19:37.766   327  7042 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 13:19:37.766   327  7042 V AudioCache: notify(0xb54749c0, 5, 0, 0)
08-25 13:19:37.766   327  7042 V AudioCache: ignored
08-25 13:19:37.766   327  7042 V AudioCache: notify(0xb54749c0, 1, 0, 0)
,08-25 13:19:37.766   327  7042 V AudioCache: prepared
08-25 13:19:37.766   327  1385 V AudioCache: wait - success
08-25 13:19:37.766   327  1385 V MediaPlayerService: start
08-25 13:19:37.766   327  1385 V AwesomePlayer: play_l() 
08-25 13:19:37.766   327  1385 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 13:19:37.766   327  1385 V AwesomePlayer: createAudioPlayer_l
08-25 13:19:37.766   327  1385 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 13:19:37.766   327  1385 V AwesomePlayer: startAudioPlayer_l() 
,08-25 13:19:37.766   327  1385 D AudioPlayer: start of Playback, useOffload 0
08-25 13:19:37.766   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 13:19:37.766   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
,08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952858208
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952858448
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952858928
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952859008
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat(),
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 13:19:37.769   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 13:19:37.769   327  7044 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 13:19:37.770   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 13:19:37.770   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010d30 on output port
,08-25 13:19:37.770   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010b50 on output port
08-25 13:19:37.770   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010a60 on output port
08-25 13:19:37.770   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-25 13:19:37.770   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 13:19:37.770   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 13:19:37.771   327  1385 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 13:19:37.771   327  1385 V AudioCache: notify(0xb54749c0, 6, 0, 0)
08-25 13:19:37.771   327  1385 V AudioCache: ignored
08-25 13:19:37.771   327  1385 V MediaPlayerService: wait for playback complete
,08-25 13:19:37.772   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.772   327  7045 V AudioCache: memcpy(0xb0417000, 0xb57c3000, 4096)
08-25 13:19:37.774   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.774   327  7045 V AudioCache: memcpy(0xb0418000, 0xb57c3000, 4096)
08-25 13:19:37.775   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.775   327  7045 V AudioCache: memcpy(0xb0419000, 0xb57c3000, 4096)
08-25 13:19:37.775   327  7045 V AudioCache: write(0xb57c3000, 4096)
,08-25 13:19:37.776   327  7045 V AudioCache: memcpy(0xb041a000, 0xb57c3000, 4096)
08-25 13:19:37.776   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.776   327  7045 V AudioCache: memcpy(0xb041b000, 0xb57c3000, 4096)
08-25 13:19:37.777   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.777   327  7045 V AudioCache: memcpy(0xb041c000, 0xb57c3000, 4096)
08-25 13:19:37.777   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.777   327  7045 V AudioCache: memcpy(0xb041d000, 0xb57c3000, 4096)
08-25 13:19:37.778   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.778   327  7045 V AudioCache: memcpy(0xb041e000, 0xb57c3000, 4096)
08-25 13:19:37.779   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.779   327  7045 V AudioCache: memcpy(0xb041f000, 0xb57c3000, 4096)
08-25 13:19:37.779   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.779   327  7045 V AudioCache: memcpy(0xb0420000, 0xb57c3000, 4096)
08-25 13:19:37.780   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.780   327  7045 V AudioCache: memcpy(0xb0421000, 0xb57c3000, 4096)
08-25 13:19:37.780   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.781   327  7045 V AudioCache: memcpy(0xb0422000, 0xb57c3000, 4096)
08-25 13:19:37.781   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.781   327  7045 V AudioCache: memcpy(0xb0423000, 0xb57c3000, 4096)
08-25 13:19:37.782   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.782   327  7045 V AudioCache: memcpy(0xb0424000, 0xb57c3000, 4096)
08-25 13:19:37.782   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.782   327  7045 V AudioCache: memcpy(0xb0425000, 0xb57c3000, 4096)
08-25 13:19:37.783   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.783   327  7045 V AudioCache: memcpy(0xb0426000, 0xb57c3000, 4096)
08-25 13:19:37.783   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.783   327  7045 V AudioCache: memcpy(0xb0427000, 0xb57c3000, 4096)
08-25 13:19:37.784   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.784   327  7045 V AudioCache: memcpy(0xb0428000, 0xb57c3000, 4096)
08-25 13:19:37.785   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.785   327  7045 V AudioCache: memcpy(0xb0429000, 0xb57c3000, 4096)
08-25 13:19:37.785   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.785   327  7045 V AudioCache: memcpy(0xb042a000, 0xb57c3000, 4096)
08-25 13:19:37.786   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.786   327  7045 V AudioCache: memcpy(0xb042b000, 0xb57c3000, 4096)
08-25 13:19:37.787   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.787   327  7045 V AudioCache: memcpy(0xb042c000, 0xb57c3000, 4096)
08-25 13:19:37.787   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.787   327  7045 V AudioCache: memcpy(0xb042d000, 0xb57c3000, 4096)
08-25 13:19:37.788   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.788   327  7045 V AudioCache: memcpy(0xb042e000, 0xb57c3000, 4096)
08-25 13:19:37.788   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.788   327  7045 V AudioCache: memcpy(0xb042f000, 0xb57c3000, 4096)
08-25 13:19:37.789   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.789   327  7045 V AudioCache: memcpy(0xb0430000, 0xb57c3000, 4096)
08-25 13:19:37.789   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.789   327  7045 V AudioCache: memcpy(0xb0431000, 0xb57c3000, 4096)
08-25 13:19:37.789   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.789   327  7045 V AudioCache: memcpy(0xb0432000, 0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V AudioCache: memcpy(0xb0433000, 0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V AudioCache: memcpy(0xb0434000, 0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V Au,dioCache: write(0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V AudioCache: memcpy(0xb0435000, 0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.791   327  7045 V AudioCache: memcpy(0xb0436000, 0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: memcpy(0xb0437000, 0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: memcpy(0xb0438000, 0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: memcpy(0xb0439000, 0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.793   327  7045 V AudioCache: memcpy(0xb043a000, 0xb57c3000, 4096)
08-25 13:19:37.794   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.794   327  7045 V AudioCache: memcpy(0xb043b000, 0xb57c3000, 4096)
08-25 13:19:37.795   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.795   327  7045 V AudioCache: memcpy(0xb043c000, 0xb57c3000, 4096)
08-25 13:19:37.795   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.795   327  7045 V AudioCache: memcpy(0xb043d000, 0xb57c3000, 4096)
08-25 13:19:37.796   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.796   327  7045 V AudioCache: memcpy(0xb043e000, 0xb57c3000, 4096)
08-25 13:19:37.797   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.797   327  7045 V AudioCache: memcpy(0xb043f000, 0xb57c3000, 4096)
08-25 13:19:37.797   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.797   327  7045 V AudioCache: memcpy(0xb0440000, 0xb57c3000, 4096)
08-25 13:19:37.798   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.798   327  7045 V AudioCache: memcpy(0xb0441000, 0xb57c3000, 4096)
08-25 13:19:37.798   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.798   327  7045 V AudioCache: memcpy(0xb0442000, 0xb57c3000, 4096)
,08-25 13:19:37.799   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.799   327  7045 V AudioCache: memcpy(0xb0443000, 0xb57c3000, 4096)
08-25 13:19:37.799   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.799   327  7045 V AudioCache: memcpy(0xb0444000, 0xb57c3000, 4096)
08-25 13:19:37.800   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.800   327  7045 V AudioCache: memcpy(0xb0445000, 0xb57c3000, 4096)
08-25 13:19:37.800   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.800   327  7045 V AudioCache: memcpy(0xb0446000, 0xb57c3000, 4096)
08-25 13:19:37.801   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.801   327  7045 V AudioCache: memcpy(0xb0447000, 0xb57c3000, 4096)
08-25 13:19:37.801   327  7045 V AudioCache: write(0xb57c3000, 4096)
08-25 13:19:37.801   327  7045 V AudioCache: memcpy(0xb0448000, 0xb57c3000, 4096)
08-25 13:19:37.802   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 13:19:37.802   327  7045 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 13:19:37.802   327  7045 V AwesomePlayer: postAudioEOS() 
08-25 13:19:37.802   327  7045 V AudioCache: write(0xb57c3000, 280)
08-25 13:19:37.802   327  7045 V AudioCache: memcpy(0xb0449000, 0xb57c3000, 280)
08-25 13:19:37.803   327  7042 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 13:19:37.803   327  7042 V AwesomePlayer: onStreamDone
08-25 13:19:37.803   327  7042 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 13:19:37.803   327  7042 V AudioCache: notify(0xb54749c0, 2, 0, 0)
08-25 13:19:37.803   327  7042 V AudioCache: playback complete
08-25 13:19:37.803   327  7042 V AwesomePlayer: pause_l() 
08-25 13:19:37.803   327  7042 V AudioCache: notify(0xb54749c0, 7, 0, 0)
08-25 13:19:37.803   327  7042 V AudioCache: ignored
08-25 13:19:37.803   327  7042 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:37.804   327  7042 D AudioPlayer: Pause Playback at 1068125
08-25 13:19:37.804   327  1385 V AudioCache: wait - success
08-25 13:19:37.804   327  1385 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 13:19:37.804   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:37.804   327  1385 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-25 13:19:37.804   327  1385 V AudioCache: ignored
08-25 13:19:37.804   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:37.804   327  1385 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 13:19:37.804   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 13:19:37.804   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 13:19:37.804   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 13:19:37.804   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010a10 on port 0
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb00109c0 on port 0
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010970 on port 0
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010920 on port 0
08-25 13:19:37.804   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,,bufIndex=0
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010a60 on port 1
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010b50 on port 1
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010d30 on port 1
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 13:19:37.805   327  7044 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 13:19:37.805   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 13:19:37.805   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 13:19:37.805   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 13:19:37.806   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 13:19:37.806   327  1385 D AudioPlayer: AudioPlayer releasing audio source
08-25 13:19:37.806   327  1385 D AudioPlayer: AudioPlayer done releasing audio source
08-25 13:19:37.806   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:37.806   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:37.806   327  1385 V AwesomePlayer: ~AwesomePlayer call
08-25 13:19:37.808   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:37.808   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:37.808  6946  7040 V SoundPool: close(32)
08-25 13:19:37.808  6946  7040 V SoundPool: pointer = 0x9ffe6000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 13:19:37.849  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-25 13:19:37.851  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 13:19:37.857  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:945
08-25 13:19:38.076  6665  6665 I UEI.SmartControl: Supports setup maps: true
08-25 13:19:38.078  6665  6665 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 13:19:38.078  6665  6665 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 13:19:38.078  6665  6665 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 13:19:38.079  6665  6665 I UEI.SmartControl: ### init IR Blaster...
08-25 13:19:38.082  6665  6665 D serial_port: Configuring serial port
,08-25 13:19:38.083  6665  6665 E UEI.SmartControl: UEIBLaster setting for 616
08-25 13:19:38.083  6665  6665 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 13:19:38.083  6665  6665 I UEI.SmartControl: configuring settings for MAXQ616
08-25 13:19:38.083  6665  6665 I UEI.SmartControl: Get version...
08-25 13:19:38.098  6665  7049 D UEI.SmartControl: serial port data available: 21
,08-25 13:19:38.125  6665  6665 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 13:19:38.126  6665  6665 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 13:19:38.126  6665  6665 I UEI.SmartControl: QS saving settings...
08-25 13:19:38.128  6665  6665 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 13:19:38.146  6665  7049 D UEI.SmartControl: serial port data available: 4
,08-25 13:19:38.196  6665  6665 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 13:19:38.201  6665  6665 E UEI.SmartControl: Services init done
08-25 13:19:38.201  6665  6665 D UEI.SmartControl: QS Service init finished
08-25 13:19:38.201  6665  7058 I UEI.SmartControl: Device manager: loading config....
08-25 13:19:38.202  6665  7058 D UEI.SmartControl: ----------- loading internal config...
08-25 13:19:38.204  6665  6665 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 13:19:38.204  6665  6665 D UEI.SmartControl: QS Service version code: 201091
08-25 13:19:38.205  6665  6665 D UEI.SmartControl: Service requested: Control
08-25 13:19:38.208  6665  7058 E UEI.SmartControl: Loading SETTINGS...
08-25 13:19:38.210  6665  6665 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-25 13:19:38.217  6946  6946 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 13:19:38.218  6665  6680 I UEI.SmartControl: ------ IControl API: 11
08-25 13:19:38.218  6665  6680 D UEI.SmartControl: File observer start...
08-25 13:19:38.219  6665  6680 E UEI.SmartControl: IR Port is disabled: false
08-25 13:19:38.219  6665  6680 D UEI.SmartControl: Starting file observer...
08-25 13:19:38.220  6665  6680 I UEI.SmartControl: Registering callback...
08-25 13:19:38.220  6665  6665 D UEI.SmartControl: Internal service binding...
08-25 13:19:38.221  6665  6681 I UEI.SmartControl: ------ IControl API: 19
08-25 13:19:38.222  6665  6681 I UEI.SmartControl: Registering Services Ready callback...
08-25 13:19:38.225  6665  7058 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 13:19:38.236  6665  7057 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 13:19:38.237  6946  6962 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 13:19:38.238  6946  7038 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 13:19:38.238  6946  7038 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 13:19:38.239  6946  6946 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 13:19:38.239  6946  6946 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 13:19:38.239  6665  6680 I UEI.SmartControl: ------ IControl API: 8
08-25 13:19:38.240  6665  7057 D UEI.SmartControl: -----service ready thread exits
08-25 13:19:38.242  6946  6946 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 13:19:38.242  6946  6946 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 13:19:38.242  6946  6946 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 13:19:38.243  6946  6946 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 13:19:38.245  6946  6946 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 13:19:38.246  6946  6946 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-25 13:19:38.252  6946  6946 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 13:19:38.254  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 13:19:38.254  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 13:19:38.257  6946  6946 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 13:19:38.257  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-25 13:19:38.260  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 13:19:38.261  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 13:19:38.261  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 13:19:38.262  6946  6946 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472123978262]
08-25 13:19:38.266  6946  6946 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 13:19:38.269  1035  1997 I ActivityManager: Killing 6061:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-25 13:19:38.308  6946  7060 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 13:19:38.312  1035  1997 I ActivityManager: Killing 6344:com.android.defcontainer/u0a4 (adj 15): empty #18
08-25 13:19:38.336  1035  1944 W libprocessgroup: failed to open /acct/uid_10027/pid_6061/cgroup.procs: No such file or directory
,08-25 13:19:38.342  1035  1772 W libprocessgroup: failed to open /acct/uid_10004/pid_6344/cgroup.procs: No such file or directory
08-25 13:19:38.348  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-25 13:19:38.350  6946  6946 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 13:19:38.350  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 13:19:38.351  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 13:19:38.351  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 13:19:38.351  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 13:19:38.352  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-25 13:19:38.362  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-25 13:19:38.960  1035  1771 D WifiServiceImplEx: setWifiEnabled: true pid=6766, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 13:19:38.961  1035  1771 D WifiService: setWifiEnabled: true pid=6766, uid=10118
08-25 13:19:38.961  1035  1771 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 13:19:38.995  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 13:19:38.995  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:38.995  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-25 13:19:38.997  1035  1375 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 13:19:38.997  1035  1375 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 13:19:39.000  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-25 13:19:39.000  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 13:19:39.000  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 13:19:39.000  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 13:19:39.000  1035  1375 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-25 13:19:39.000  1035  1375 E WifiHW  : unknown target_country: EU , set to default
08-25 13:19:39.000  1035  1375 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-25 13:19:39.000  1035  1375 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 13:19:39.000  1035  1375 I WifiUtil: gEnableBmps=1
08-25 13:19:39.088  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:39.108  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:19:39.127  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:39.131  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:39.134  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:39.142  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:19:39.153  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:39.155  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:39.158  1035  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:39.159  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 13:19:39.162  4809  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 13:19:39.173  5866  5866 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 13:19:39.189  5866  5866 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 13:19:39.210  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:39.236  1035  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:39.291  1035  1944 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7075 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 13:19:39.295  1035  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:39.295  1035  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 13:19:39.388  7075  7075 I AppUp4:AppBoxCP: onCreate
,08-25 13:19:39.389  7075  7075 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-25 13:19:39.400  7075  7075 I AppUp4:DB:  setFingerPrint start
,08-25 13:19:39.400  7075  7075 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 13:19:39.409  7075  7075 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 13:19:39.409  7075  7075 I AppUp4:DB:  SDK version = 21
08-25 13:19:39.409  7075  7075 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-25 13:19:39.412  7075  7075 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-25 13:19:39.413  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 13:19:39.413  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:39.416  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 13:19:39.417  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 13:19:39.426  7075  7075 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 13:19:39.477  7075  7075 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:39.478  7075  7075 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:39.487  7075  7075 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1108d325
08-25 13:19:39.487  7075  7075 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 13:19:39.487  7075  7075 D AppUp4:CustFacade: isPhone : true
08-25 13:19:39.488  7075  7075 D AppUp4:CustModeStarterReceiver: begin check event
08-25 13:19:39.488  7075  7075 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 13:19:39.489  7075  7075 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 13:19:39.490  7075  7096 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 13:19:39.490  7075  7096 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 13:19:39.490  7075  7096 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 13:19:39.492  1035  1560 I ActivityManager: Killing 6534:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-25 13:19:39.537  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:39.538  1035  2015 W libprocessgroup: failed to open /acct/uid_10061/pid_6534/cgroup.procs: No such file or directory
08-25 13:19:39.538  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 13:19:39.540  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 13:19:39.543  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:39.552  4735  7105 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 13:19:39.556  4735  7106 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:39.557  4735  7106 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 13:19:39.608  1035  1772 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7107 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 13:19:39.668  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:19:39.668  1035  1117 D Tethering: InitialState.processMessage what=4
08-25 13:19:39.671  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:19:39.673   323   889 D SoftapController: Softap fwReload - Ok
08-25 13:19:39.675  1035  1375 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (668ms)
,08-25 13:19:39.679   323   889 D CommandListener: Setting iface cfg
08-25 13:19:39.679   323   889 D CommandListener: Trying to bring down wlan0
08-25 13:19:39.681   323   889 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:19:39.683  1035  1375 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 13:19:39.685  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:39.685  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:39.685  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 13:19:39.678  7125  7125 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:39.678  7125  7125 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:39.695  1035  1375 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 13:19:39.695  1035  1375 D WifiMonitor: connecting to supplicant
08-25 13:19:39.698  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:39.701  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-25 13:19:39.702  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 13:19:39.702  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:39.703  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:39.718  7125  7125 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 13:19:39.721  7107  7107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:39.721  7107  7107 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 13:19:39.723  7107  7107 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 13:19:39.723  7107  7107 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 13:19:39.754  7125  7125 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 13:19:39.755  7125  7125 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 13:19:39.800  7107  7107 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 13:19:39.811  7107  7107 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-25 13:19:39.837  7107  7107 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 13:19:39.859  7107  7107 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:39.860  7107  7107 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:39.879  7125  7125 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 13:19:39.916  7125  7125 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-25 13:19:39.919  7125  7125 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 13:19:39.919  7125  7125 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 13:19:39.922  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 13:19:39.922  1035  7130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-25 13:19:39.922  1035  7130 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 13:19:39.922  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 13:19:39.923  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 13:19:39.923  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 13:19:39.923  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 13:19:39.923  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 13:19:39.925  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 13:19:39.926  1035  1375 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-25 13:19:39.927  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:39.929  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:39.931  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:39.932  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:39.933  1035  1375 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 13:19:39.933  1035  1375 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 13:19:39.935  1035  1375 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 13:19:39.935  1035  1375 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 13:19:39.935  1035  1375 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 13:19:39.936  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:39.936  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:39.936  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:39.936  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:39.936  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:39.936  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:39.936  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:39.936  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 13:19:39.937  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 13:19:39.938  1035  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 13:19:39.938  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:39.939  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-25 13:19:39.939  1035  1375 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 13:19:39.940  1035  1375 D WifiNative-wlan0: SET update_config 1: returned true
08-25 13:19:39.940  1035  1375 D WifiConfigStore: Loading config and enabling all networks 
08-25 13:19:39.940  1035  1375 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 13:19:39.940  1035  1375 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 13:19:39.943  1035  1375 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 13:19:39.944  7107  7107 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 13:19:39.945  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:39.945  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:39.945  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:39.945  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:39.948  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:39.948  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:39.948  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:39.948  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSS,ID name: null
08-25 13:19:39.949  1035  1375 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 13:19:39.949  1035  1375 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 13:19:39.950  1035  1375 D WifiStateMachine: enableVerboseLogging : level 2
08-25 13:19:39.950  1035  1375 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 13:19:39.950  1035  1375 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 13:19:39.950  1035  1375 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 13:19:39.950  1035  1375 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 13:19:39.950  1035  1375 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 13:19:39.950  1035  1375 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 13:19:39.950  1035  1375 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 13:19:39.951  1035  1375 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 13:19:39.951  1035  1375 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-25 13:19:39.951  1035  1375 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 13:19:39.951  1035  1375 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 13:19:39.951  1035  1375 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 13:19:39.951  1035  1375 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 13:19:39.951  1035  1375 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 13:19:39.952  1035  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 13:19:39.952  1035  1375 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 13:19:39.952  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-25 13:19:39.952  1035  1375 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 13:19:39.953  1035  1375 D WifiNative-HAL: Setting external_sim to 1
08-25 13:19:39.953  1035  1375 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 13:19:39.953  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 13:19:39.953  1927  2207 D WfdsService: Set the WFDS Monitor: true
08-25 13:19:39.953  1927  2207 D WfdsMonitor: WfdsMonitorThread create
08-25 13:19:39.953  1035  1375 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 13:19:39.953  1035  1375 I WifiNative-HAL: startHal
08-25 13:19:39.953  1035  1375 D wifi    : setting scan oui 0x95774b20
08-25 13:19:39.953  1035  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 13:19:39.953  1035  1375 I WifiNative-HAL: startHal
08-25 13:19:39.953  1035  1375 D wifi    : setting scan oui 0x95774b20
08-25 13:19:39.953  1035  1375 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 13:19:39.953  1927  2207 D WfdsMonitor: WFDS Monitor is created and started
08-25 13:19:39.953  1927  2207 D WfdsService: WiFi: Supplicant connection re-established
08-25 13:19:39.954  1035  1375 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 13:19:39.954  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 13:19:39.954  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 13:19:39.954  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 13:19:39.954  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 13:19:39.954  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 13:19:39.955  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 13:19:39.955  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 13:19:39.955  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 13:19:39.955  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 13:19:39.955  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 13:19:39.955  1927  7131 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 13:19:39.955  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 13:19:39.955  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 13:19:39.955  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 13:19:39.955  1927  7131 E CtrlSupplicant: Succeed to open control connection
08-25 13:19:39.955  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 13:19:39.956  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 13:19:39.956  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 13:19:39.956  7125  7125 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 13:19:39.956  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 13:19:39.956  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 13:19:39.956  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 13:19:39.957  1035  1375 D WifiNative-wlan0: DRIVER RXFILTE,R-START: returned true
08-25 13:19:39.957  1035  1375 E WifiNative: : [186,197,348 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 13:19:39.957  1035  1375 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 13:19:39.957  1035  1375 D WifiNative-wlan0: RECONNECT: returned true
08-25 13:19:39.957  1035  1375 D WifiNative-wlan0: doString: [STATUS]
08-25 13:19:39.958  1035  1375 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 13:19:39.958  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 13:19:39.958  1035  1375 D WifiNative-wlan0: SET ps 1: returned true
08-25 13:19:39.958  1035  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.959  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 13:19:39.959  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 13:19:39.959  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 13:19:39.959  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-25 13:19:39.959  1035  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.959  1035  1541 I WifiNative-HAL: startHal
08-25 13:19:39.959  1035  1541 D wifi    : getting scan capabilities on interface[1] = 0x95774b20
08-25 13:19:39.959  1035  1541 D wifi    : failed to get capabilities : -3
08-25 13:19:39.959  1035  1541 E WifiScanningService: could not get scan capabilities
08-25 13:19:39.959  1035  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.959  1927  7131 E CtrlSupplicant: Succeed to open monitor connection
08-25 13:19:39.959  1035  1375 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 13:19:39.960  1035  1375 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 13:19:39.960  1035  1375 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 13:19:39.960  1035  1375 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 13:19:39.960  1035  1375 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 13:19:39.960  1035  1375 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 13:19:39.961  1035  1375 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 13:19:39.961  1035  1375 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 13:19:39.961  7125  7125 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 13:19:39.961  1927  7131 D WfdsMonitor: Supplicant connection established
08-25 13:19:39.961  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-25 13:19:39.961  1035  1375 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 13:19:39.961  1035  1375 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 13:19:39.962  1035  1375 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 13:19:39.962  1035  1375 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 13:19:39.962  7125  7125 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 13:19:39.962  1035  1375 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 13:19:39.962  1035  1375 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 13:19:39.962  1035  1375 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 13:19:39.962   323   889 D CommandListener: Setting iface cfg
08-25 13:19:39.962  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 13:19:39.963  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 13:19:39.963  7125  7125 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.963 ,  323   889 D CommandListener: Trying to bring up p2p0
08-25 13:19:39.964  7125  7125 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 13:19:39.964  7125  7125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.964  1035  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 13:19:39.964  1035  1374 D LGWifiP2pService: P2pEnablingState
08-25 13:19:39.964  7125  7125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.964  1035  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.964  1035  1374 D LGWifiP2pService: P2p socket connection successful
08-25 13:19:39.964  1035  1374 D LGWifiP2pService: P2pEnabledState
08-25 13:19:39.964  1927  7131 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.964  1927  7131 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.965  1035  1375 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 13:19:39.965  1035  1375 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 13:19:39.965  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 13:19:39.965  1035  1375 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 13:19:39.965  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.965  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.965  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.966  1035  7130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.966  1035  1375 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 13:19:39.966  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 13:19:39.966  1035  7130 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.966  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.966  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 13:19:39.966  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.966  7125  7125 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:39.966  1035  7130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.966  1035  7130 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.966  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.966  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.966  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 13:19:39.966  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:39.966  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:39.966  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:39.966  1035  1375 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 13:19:39.966  1035  1375 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 13:19:39.966  1035  1375 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 13:19:39.966  1035  1375 D WifiNative-wlan0: doBoolean: SCAN
08-25 13:19:39.967  1035  1375 D WifiNative-wlan0: SCAN: returned false
08-25 13:19:39.967  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=186207  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 13:19:39.969  1035  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 13:19:39.969  1035  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 13:19:39.970  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=186210  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 13:19:39.970  1035  1375 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:39.970  1035  1375 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:39.970  1035  1375 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:39.971  1035  1375 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:39.971  1035  1375 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:39.973  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:39.973  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:39.973  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 13:19:39.973  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:39.973  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 13:19:39.974  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 13:19:39.974  1927  1927 D WfdsService: WifiP2pState is changed : true
08-25 13:19:39.975  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 13:19:39.975  1927  2207 D WfdsService: Receive the WFDS_ENABLE Method
08-25 13:19:39.975  1927  2207 D WfdsService: Set the WFDS Monitor: true
08-25 13:19:39.975  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-25 13:19:39.975  1927  2207 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 13:19:39.975  7125  7125 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 13:19:39.975  1035  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 13:19:39.976  1927  1927 D WfdsService: isConnected: false
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-25 13:19:39.976  1035  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 13:19:39.976  1035  1374 D LGWifiP2pService: before postfix = G3
08-25 13:19:39.976  1035  1374 D WifiServerServiceExt: postfix byte check : 2
08-25 13:19:39.976  1035  1374 D LGWifiP2pService: after postfix = G3
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 13:19:39.976  1927  2207 D WfdsService: selectPreferredScanChannel [36]
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 13:19:39.976  1927  2207 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 13:19:39.976  1035  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 13:19:39.977  1035  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 13:19:39.977  1035  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-25 13:19:39.977  1035  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 13:19:39.977  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:39.977  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:39.977  1035  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 13:19:39.977  1035  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 13:19:39.978  1035  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 13:19:39.978  1035  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 13:19:39.978  1035  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 13:19:39.978  1035  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 13:19:39.978  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:39.978  1035  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 13:19:39.978  1035  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 13:19:39.979  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 13:19:39.980  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 13:19:39.980  1927  1927 D WfdsService: Update P2p Interface State: 3
08-25 13:19:39.988  7107  7107 I HubEmail: JNI_OnLoad()
08-25 13:19:39.988  7107  7107 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 13:19:39.988  7107  7107 I HubEmail: registerNatives()
08-25 13:19:39.988  7107  7107 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 13:19:39.988  7107  7107 I HubEmail: registerNativeMethods()
08-25 13:19:39.988  7107  7107 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 13:19:39.989  7107  7107 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-25 13:19:39.991  1035  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 13:19:39.991  1035  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 13:19:39.992  1035  1374 D LGWifiP2pService: InactiveState
08-25 13:19:39.992  1035  1374 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.992  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.992  1035  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 13:19:39.993  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 13:19:39.994  7125  7125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.994  1035  7130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 13:19:39.994  1035  7130 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.994  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.994  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:39.995  7125  7125 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 13:19:39.995  7125  7125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.995  1927  7131 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 13:19:39.995  1927  7131 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.995  7125  7125 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.995  1035  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 13:19:39.995  1035  1374 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.995  1035  7130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.995  1035  7130 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.996  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.996  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.996  1927  7131 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.996  1035  7130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:39.996  1035  7130 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 13:19:39.996  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:19:39.996  1035  7130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.996  1035  7130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.996  1035  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.998  1927  2207 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 13:19:39.998  1035  1374 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.998  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.998  1035  1374 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:39.998  1035  1035 E WifiServerServiceExt: No p2p device connected
08-25 13:19:40.000  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 13:19:40.000  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:40.001  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 13:19:40.053  1035  1771 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7137 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-25 13:19:40.057  7003  7133 W FormManager: Network not available. Please check & try again.
,08-25 13:19:40.059  7107  7134 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.061  7003  7136 V FormManager: Network unavailable.
08-25 13:19:40.068  7003  7136 V FormManager: Network unavailable.
08-25 13:19:40.080  1035  1703 I ActivityManager: Killing 6583:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-25 13:19:40.126  1035  1771 W libprocessgroup: failed to open /acct/uid_10080/pid_6583/cgroup.procs: No such file or directory
,08-25 13:19:40.219  7137  7137 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:40.220  7137  7137 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:40.223  7137  7137 D PhoneMonitor: Register our PhoneStateListener
08-25 13:19:40.251  7137  7137 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 13:19:40.258  7137  7137 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 13:19:40.305  7137  7137 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-25 13:19:40.307  7137  7137 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 13:19:40.309  7137  7137 D TelephonyAutoProfiling: [parse] Load xml
08-25 13:19:40.316  7137  7137 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 13:19:40.316  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 13:19:40.317  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 13:19:40.317  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 13:19:40.317  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 13:19:40.317  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 13:19:40.317  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 13:19:40.317  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 13:19:40.317  7137  7137 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-25 13:19:40.324  7137  7137 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-25 13:19:40.325  1035  1908 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7159 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 13:19:40.326  1035  1908 I ActivityManager: Killing 6604:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 13:19:40.351   354   354 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 23.606ms
,08-25 13:19:40.374   354   354 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 21.708ms
,08-25 13:19:40.396   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 20.576ms
,08-25 13:19:40.406  1035  2018 W libprocessgroup: failed to open /acct/uid_10097/pid_6604/cgroup.procs: No such file or directory
,08-25 13:19:40.511  7125  7125 E wpa_supplicant: USIM:  scard_init function
08-25 13:19:40.512  7125  7125 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-25 13:19:40.515  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 13:19:40.516  1035  7130 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 13:19:40.516  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 13:19:40.516  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-25 13:19:40.516  1035  7130 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 13:19:40.516  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 13:19:40.516  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 13:19:40.518  1035  1375 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
08-25 13:19:40.519  1035  1375 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
08-25 13:19:40.520  1035  1375 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
08-25 13:19:40.521  1035  1375 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=5 bcn=0
08-25 13:19:40.521  1035  1375 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 13:19:40.535  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=186775  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 13:19:40.542  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:40.542  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:40.542  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:19:40.543  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.543  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 13:19:40.543  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:40.586  1035  1560 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7177 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-25 13:19:40.587  1035  1560 I ActivityManager: Killing 6633:com.lge.eula/1000 (adj 15): empty #17
08-25 13:19:40.618  1035  1772 W libprocessgroup: failed to open /acct/uid_1000/pid_6633/cgroup.procs: No such file or directory
,08-25 13:19:40.626  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.626  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:40.626  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:40.626  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.626  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 13:19:40.626  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=186865  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 13:19:40.627  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:40.627  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 13:19:40.628  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:40.636  7125  7125 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 13:19:40.636  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 13:19:40.636  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 13:19:40.637  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 13:19:40.637  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 13:19:40.637  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:40.637  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:40.637  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=186877  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-25 13:19:40.638  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=186878  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-25 13:19:40.638  1035  1375 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186878
08-25 13:19:40.639  1035  1375 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186879
08-25 13:19:40.639  1035  1375 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186879
08-25 13:19:40.640  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186880
08-25 13:19:40.640  1035  1375 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186880
08-25 13:19:40.641  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=186881  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 13:19:40.643  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 13:19:40.644  7125  7125 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:19:40.644  7125  7125 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 13:19:40.646  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.647  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.647  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 13:19:40.650  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:40.650  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:40.650  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-25 13:19:40.650  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:19:40.651  1035  7130 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:19:40.651  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 13:19:40.651  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 13:19:40.651  1035  7130 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 13:19:40.651  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:40.651  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:40.653  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=186894  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 13:19:40.655  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:40.655  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:40.656  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:40.659  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:40.659  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:40.659  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.659  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.659  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 13:19:40.660  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:40.660  1035  1375 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:40.660  1035  1375 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:40.661  1035  1375 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:40.661  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-25 13:19:40.662  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:40.663  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=186903  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 13:19:40.663  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=186903  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 13:19:40.664  1035  1375 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=186904
08-25 13:19:40.664  1035  1375 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=186904
08-25 13:19:40.667  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:40.667  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 13:19:40.668  1035  1375 D WifiNative-wlan0: doString: [STATUS]
08-25 13:19:40.668  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:40.668  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:40.668  1035  1375 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 13:19:40.670  1035  1375 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 13:19:40.685  1035  1375 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 13:19:40.685  1035  1375 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 13:19:40.693  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.693  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.693  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 13:19:40.697  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:40.697  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:40.702  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.702  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:40.702  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-25 13:19:40.705  1035  1375 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 13:19:40.705  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:40.705  1035  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:19:40.705  1035  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 13:19:40.705  1035  1405 D ConnectivityService: Got NetworkAgent Messenger
08-25 13:19:40.705  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 13:19:40.706  1035  1405 D ConnectivityService: NetworkAgent connected
08-25 13:19:40.706  1035  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 13:19:40.706  1035  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 13:19:40.707  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:40.707  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:40.709  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:40.712  1035  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 13:19:40.712  1035  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:19:40.712  1035  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 13:19:40.714  1035  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 13:19:40.714  1035  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 13:19:40.719  1035  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 13:19:40.721   323   889 D CommandListener: Setting iface cfg
,08-25 13:19:40.772  1035  1944 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7201 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:19:40.774  1035  1944 I ActivityManager: Killing 5620:com.lge.bnr/1000 (adj 15): empty #17
08-25 13:19:40.867  1035  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_5620/cgroup.procs: No such file or directory
,08-25 13:19:40.887  1035  1375 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 13:19:40.887  1035  7195 D DhcpStateMachine: StoppedState
08-25 13:19:40.887  1035  7195 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:40.887  1035  7195 D DhcpStateMachine: WaitBeforeStartState
,08-25 13:19:40.889  1035  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=187128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:40.891  1035  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=187130  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:40.892  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=187132  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:40.895  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:40.895  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 13:19:40.897  1035  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=187136  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-25 13:19:40.898  1035  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=187138  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:40.900  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=187140  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:40.904  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:141069] from screen [on:0 period:-1049801625] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 13:19:40.906  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1049801622] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 13:19:40.906  1035  1375 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 13:19:40.915  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:40.919  1035  1405 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 13:19:40.920  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.921  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.922  1035  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 13:19:40.923  1035  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.924  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.925  7201  7201 I art     : Almond Protected OAT
08-25 13:19:40.926  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.927  1035  1405 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 13:19:40.928  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-25 13:19:40.929  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-25 13:19:40.929  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 13:19:40.930  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 13:19:40.931  1035  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 13:19:40.931  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 13:19:40.932  1035  1375 D WifiNative-wlan0: SET ps 0: returned true
08-25 13:19:40.933  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 13:19:40.933  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 13:19:40.934  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 13:19:40.934  1035  1375 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 13:19:40.934  1035  1375 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 13:19:40.935  1035  1375 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 13:19:40.936  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4a84705 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:40.936  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4a84705 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:40.936  1035  7195 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:40.936  1035  7195 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-25 13:19:40.936   323   889 D CommandListener: Setting iface cfg
08-25 13:19:40.937   323   889 D CommandListener: Trying to bring up wlan0
08-25 13:19:40.938  1035  1375 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 13:19:40.940  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:40.940  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 13:19:40.941  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:40.941  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 13:19:40.942  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.943  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.943  1035  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.944  1035  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.944  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 13:19:40.944  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:40.945  1035  1405 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 13:19:40.945  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 13:19:40.946  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 13:19:40.946  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:40.946  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:40.946  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 13:19:40.947  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 13:19:40.948  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 13:19:40.948  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-25 13:19:40.948  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 13:19:40.949  1035  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 13:19:40.949  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
,08-25 13:19:40.966  1035  1375 D WifiNative-wlan0: SET ps 1: returned true,
08-25 13:19:40.967  1035  1405 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-25 13:19:40.967  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-25 13:19:40.968  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 13:19:40.968  1035  1375 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-25 13:19:40.971  1035  1405 D ConnectivityService: ignoring duplicate network state non-change
,08-25 13:19:40.974  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 13:19:40.975  1035  1405 D ConnectivityService: Adding iface wlan0 to network 101
08-25 13:19:40.981  7201  7201 D WeatherApplication: removeAccount
08-25 13:19:40.981  1035  1375 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 13:19:40.982  7201  7201 D WeatherApplication: Account.length = 0
08-25 13:19:40.983  7201  7201 E WeatherApplication: OPERATOR:OPEN
08-25 13:19:40.988  7201  7201 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:40
,08-25 13:19:40.991  7201  7201 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 13:19:40.992  7201  7201 D Weather.Utils: 2 : All the weather widget is gone.
08-25 13:19:40.998  7201  7201 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 13:19:41.001  7201  7201 D WeatherAncestor: connectivity changed - connection : true
08-25 13:19:41.002  7201  7201 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-25 13:19:41.004  1035  1405 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 13:19:41.004  1035  1405 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 13:19:41.005  1035  1405 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 13:19:41.006   323   889 E Netd    : netlink response contains error (File exists)
08-25 13:19:41.006  1035  1405 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 13:19:41.007  1035  1405 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 13:19:41.007  1035  1405 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 13:19:41.007  1035  1405 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 13:19:41.008  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:41.008  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:41.008  1035  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:41.008  1035  1405 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 13:19:41.008  1035  1405 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 13:19:41.008  1035  1405 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 13:19:41.008  1035  1405 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 13:19:41.008  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:41.009  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 13:19:41.009  1035  1405 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:41.009  1035  1405 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:41.009  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:41.009  1035  1405 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 13:19:41.009  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 13:19:41.009  1035  1405 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.009  1035  1405 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 13:19:41.009  1035  1405 D ConnectivityService: currentScore = 0, newScore = 20
08-25 13:19:41.009  1035  1405 D ConnectivityService:    accepting network in place of null
08-25 13:19:41.009  1035  1405 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.009  1035  1375 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.009  1035  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:41.010  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.010  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS,&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 13:19:41.011  1035  1405 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 13:19:41.011  1035  1405 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 13:19:41.011  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:19:41.012  1035  1405 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:41.012  1035  1405 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 13:19:41.012  1035  1405 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 13:19:41.014   323  7222 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 13:19:41.014  1035  1405 D ConnectivityService: validation of new default Network = false
08-25 13:19:41.014  1035  1405 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 13:19:41.014  1035  1405 D DSQN    : enableDataServiceNotify 
08-25 13:19:41.014  1035  1405 D DSQN    : start dsqn bin
08-25 13:19:41.015  7201  7201 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 13:19:41.015  7201  7201 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 13:19:41.015  7201  7201 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-25 13:19:41.026  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:41.026  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 13:19:41.027  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:41.034  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:41.034  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:41.034  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-25 13:19:41.036  7201  7201 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 13:19:41.037  7201  7201 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:41
08-25 13:19:41.038  1035  1405 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 13:19:41.038  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.038  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:41.038  1035  1405 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:41.039  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 13:19:41.028  7224  7224 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 13:19:41.028  7224  7224 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:41.041  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:41.041  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:41.041  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 13:19:41.041  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 13:19:41.043  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 13:19:41.047  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:19:41.055  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:41.055  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 13:19:41.055  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 13:19:41.056  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:41.056  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:41.056  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 13:19:41.059  7224  7224 E DSQN    : DSQN ssw
08-25 13:19:41.059  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 13:19:41.060  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:41.060  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:41.061  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 13:19:41.061  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 13:19:41.061  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 13:19:41.061  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 13:19:41.070  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:41.070  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 13:19:41.070  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:41.075  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:41.075  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 13:19:41.075  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:41.076   323  7222 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 13:19:41.083  1035  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 13:19:41.084  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 13:19:41.084  1035  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 13:19:41.084  1035  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 13:19:41.085  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 13:19:41.088  1035  1375 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-25 13:19:41.101  1035  1560 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7228 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 13:19:41.102  1035  1560 I ActivityManager: Killing 2179:com.lge.music/u0a34 (adj 15): empty #17
,08-25 13:19:41.111   323  7222 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-25 13:19:41.124   327   327 V AudioFlinger: 2179 died, releasing its sessions
08-25 13:19:41.124   327   327 V AudioFlinger:  pid 1839 @ 0
08-25 13:19:41.124   327   327 V AudioFlinger:  pid 3424 @ 1
08-25 13:19:41.124   327   327 V AudioFlinger:  pid 3424 @ 2
,08-25 13:19:41.138  1035  7195 D DhcpStateMachine: DHCPV4 request on wlan0
,08-25 13:19:41.138  1035  7195 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 13:19:41.138  1035  7195 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 13:19:41.128  7245  7245 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:41.128  7245  7245 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:41.148   323   888 D LGDataListener: argv[0]=dsqncommand
08-25 13:19:41.148   323   888 D LGDataListener: argv[1]=wlan0
08-25 13:19:41.148   323   888 D LGDataListener: argv[2]=1
08-25 13:19:41.148   323   888 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 13:19:41.148  7245  7245 I dhcpcd  : version 5.5.6 starting
,08-25 13:19:41.149  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 13:19:41.149  1035  1115 D DSQN    : start to monitor internet connection
08-25 13:19:41.150  7245  7245 E dhcpcd  : get_duid: m
08-25 13:19:41.150  7245  7245 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 13:19:41.150  7245  7245 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 13:19:41.168  1035  1106 W ActivityManager: Failed to clear dns cache for: com.lge.music
,08-25 13:19:41.173  1035  2018 W libprocessgroup: failed to open /acct/uid_10034/pid_2179/cgroup.procs: No such file or directory
,08-25 13:19:41.183  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 11:19:41 GMT], X-Android-Received-Millis=[1472123981183], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472123981148]}
08-25 13:19:41.183  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 13:19:41.184  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 13:19:41.184  1035  1405 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 13:19:41.184  1035  1405 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 13:19:41.184  1035  1405 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:41.184  1035  1405 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:41.184  1035  1405 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 13:19:41.184  1035  1405 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 13:19:41.184  1035  1405 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 13:19:41.184  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.184  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:41.185  1035  1405 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:41.185  1035  1405 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.185  1035  1375 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.185  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 13:19:41.185  1035  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:41.186  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 13:19:41.186  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:41.186  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 13:19:41.201  1035  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-25 13:19:41.211  7245  7245 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-25 13:19:41.211  7245  7245 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 13:19:41.211  7245  7245 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 13:19:41.211  7245  7245 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 13:19:41.211  7245  7245 D dhcpcd  : wlan0: sending REQUEST (xid 0x42db0109), next in 3.72 seconds
,08-25 13:19:41.217  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:41.218  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:41.219  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 13:19:41.230  1804  7254 I CheckinService: active receiver: enabled
08-25 13:19:41.240  1804  7254 I CheckinService: Preparing to send checkin request
,08-25 13:19:41.240  1804  7254 I EventLogService: Accumulating logs since 1472123837089
,08-25 13:19:41.246  7245  7245 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 13:19:41.250  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:41.251  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:41.252  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:41.265  7245  7245 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 13:19:41.265  7245  7245 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-25 13:19:41.265  7245  7245 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 13:19:41.265  7245  7245 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 13:19:41.265  7245  7245 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 13:19:41.266  7245  7245 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 13:19:41.266  7245  7245 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 13:19:41.266  7245  7245 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 13:19:41.287   281   355 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 13:19:41.287   281   355 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 13:19:41.287   281   355 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 13:19:41.288  7228  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-25 13:19:41.290   281   355 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 13:19:41.290   281   355 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 13:19:41.290   281   355 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 13:19:41.291  7228  7259 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 13:19:41.295  1804  7254 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-25 13:19:41.301   281   355 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 13:19:41.301   281   355 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 13:19:41.301   281   355 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:19:41.304  7228  7265 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 13:19:41.305   281   355 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 13:19:41.306   281   355 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 13:19:41.306   281   355 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 13:19:41.306  7228  7265 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-25 13:19:41.401  1035  1889 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7276 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 13:19:41.452  7276  7276 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 13:19:41.453  7276  7276 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-25 13:19:41.485  7276  7276 I MultiDex: VM with version 2.1.0 has multidex support
08-25 13:19:41.485  7276  7276 I MultiDex: install
08-25 13:19:41.486  7276  7276 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 13:19:41.497  7276  7276 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-25 13:19:41.527  7228  7228 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 13:19:41.535  7228  7228 I LibraryLoader: Loading: webviewchromium
08-25 13:19:41.537  7228  7228 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7789-7792)
08-25 13:19:41.537  7228  7228 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 13:19:41.541  1035  7195 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-25 13:19:41.541  1035  7195 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 13:19:41.542  1035  7195 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 13:19:41.542  1035  7195 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 13:19:41.542  1035  7195 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 13:19:41.542  1035  7195 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 13:19:41.542  1035  7195 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 13:19:41.542  1035  7195 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 13:19:41.542  1035  7195 D DhcpStateMachine: RunningState
08-25 13:19:41.543  7228  7228 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3258bfe4}
08-25 13:19:41.547  7228  7228 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 13:19:41.548  7228  7228 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 13:19:41.570  7228  7228 I BrowserStartupController: Initializing chromium process, renderers=0
,08-25 13:19:41.571  7228  7228 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 13:19:41.590  7228  7228 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 13:19:41.591  7228  7228 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 13:19:41.591  7228  7228 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 13:19:41.599   327  2234 V AudioPolicyService: registerClient() client 0xb1427640, uid 10093
08-25 13:19:41.600  7228  7319 W AudioManagerAndroid: Requires BLUETOOTH permission
08-25 13:19:41.612  7228  7228 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 13:19:41.612  7228  7228 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 13:19:41.612  7228  7228 I Adreno-EGL: Build Date: 12/12/14 금
08-25 13:19:41.612  7228  7228 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 13:19:41.612  7228  7228 I Adreno-EGL: Remote Branch: 
08-25 13:19:41.612  7228  7228 I Adreno-EGL: Local Patches: 
08-25 13:19:41.612  7228  7228 I Adreno-EGL: Reconstruct Branch: 
,08-25 13:19:41.686  7228  7228 I NSApplication: Starting up...
,08-25 13:19:41.767  1035  1980 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7332 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-25 13:19:41.768  1035  1980 I ActivityManager: Killing 6097:com.android.vending/u0a44 (adj 15): empty #17
,08-25 13:19:41.920  1035  1944 W libprocessgroup: failed to open /acct/uid_10044/pid_6097/cgroup.procs: No such file or directory
,08-25 13:19:41.966  7332  7332 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 13:19:41.999  1035  1889 D WifiServiceImplEx: setWifiEnabled: false pid=6766, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 13:19:42.000  1035  1889 D WifiService: setWifiEnabled: false pid=6766, uid=10118
08-25 13:19:42.000  1035  1889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 13:19:42.024  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 13:19:42.030  1035  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:42.030  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:42.030  1035  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:42.031  1035  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:42.031  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 13:19:42.031  1035  1375 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 13:19:42.031  1035  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:19:42.031  1035  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 13:19:42.031  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:42.031  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-25 13:19:42.032  1035  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 13:19:42.032  1035  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 13:19:42.038  1035  1405 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-25 13:19:42.046  1035  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 13:19:42.046  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 13:19:42.046  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.046  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.046  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 13:19:42.047  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 13:19:42.047  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 13:19:42.047  1035  1375 D WifiNative-wlan0: SET ps 1: returned true
08-25 13:19:42.048   323   889 D CommandListener: Clearing all IP addresses on wlan0
,08-25 13:19:42.048  1035  7195 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.072  7276  7294 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:42.072  7276  7294 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:42.084  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 13:19:42.084  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-25 13:19:42.087  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-25 13:19:42.088  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:42.088  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:42.090  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 13:19:42.090  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.093  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.093  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.093  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:42.094  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.094  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.094  1035  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ac8384b
,08-25 13:19:42.095  1035  1374 D LGWifiP2pService: P2pDisablingState
08-25 13:19:42.095  1035  1374 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.095  1035  1374 D LGWifiP2pService: p2p socket connection lost
08-25 13:19:42.095  1035  1374 D LGWifiP2pService: P2pDisabledState
08-25 13:19:42.094  1035  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.096  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.096  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.096  1035  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.097  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.097  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.098  1035  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.098  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.098  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:42.098  1035  1375 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 13:19:42.098  1035  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 13:19:42.099  1035  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.099  1035  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.099  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 13:19:42.099  7125  7125 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 13:19:42.099  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 13:19:42.100  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 13:19:42.100  1035  1375 D WifiNative-wlan0: SET ps 1: returned true
08-25 13:19:42.100  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-25 13:19:42.102  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.102  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.102  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:42.102  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 13:19:42.102  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-25 13:19:42.103  1035  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.103  1035  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.106  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-25 13:19:42.108  1927  1927 D WfdsService: WifiP2pState is changed : false
08-25 13:19:42.109  1927  2207 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 13:19:42.109  1927  2207 D WfdsService: Set the WFDS Monitor: false
08-25 13:19:42.109  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
08-25 13:19:42.109  1927  2207 D WfdsService: STATE : WfdsDisabledState - enter
08-25 13:19:42.110  1927  7131 D CtrlSupplicant: Received on exit socket, terminate
08-25 13:19:42.110  1927  7131 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 13:19:42.110  1927  7131 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 13:19:42.110  1927  7131 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 13:19:42.110  1927  2209 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 13:19:42.110  1927  2207 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 13:19:42.112  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:42.112  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:42.113  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.126   323   889 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:19:42.126  1035  1405 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 13:19:42.126  1035  1405 D DSQN    : disableDataServiceNotify
08-25 13:19:42.126  1035  1405 D DSQN    : stop dsqn bin
08-25 13:19:42.128  1035  1375 D WifiNative-p2p0: doBoolean: TERMINATE
,08-25 13:19:42.129  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-25 13:19:42.129  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.129  1035  1375 D WifiNative-p2p0: TERMINATE: returned true
08-25 13:19:42.129  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.129  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:42.129  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:42.129  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 13:19:42.129  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:42.130  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 13:19:42.130  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:42.131  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 13:19:42.131  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.132  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 13:19:42.132  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:42.132  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 13:19:42.133  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.133  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:42.133  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:42.133  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:42.133  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:42.134  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:42.134  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:42.134  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:42.134  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:42.134  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:42.134  6,766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:42.134  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:42.134  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:42.134  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:42.134  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:42.134  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:42.143  1035  1405 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 13:19:42.143  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:42.143  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 13:19:42.143  1035  1405 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:42.143  1035  1405 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 13:19:42.144  1035  1405 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 13:19:42.144  1035  1405 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 13:19:42.144  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:19:42.144  1035  1405 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:42.144  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:19:42.144  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 13:19:42.144  1035  1405 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:42.145  1035  1405 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:42.145  1035  1405 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:42.145  1035  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 13:19:42.146  1035  1375 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:42.146  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:42.146  1035  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:42.146  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.146  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.146  1035  7194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 13:19:42.146  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 13:19:42.147  1035  1405 D NetworkManagementService: Removing idletimer
08-25 13:19:42.147  1035  1405 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.147  1035  1405 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 13:19:42.147  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 13:19:42.1,48  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 13:19:42.148  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 13:19:42.148  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 13:19:42.148  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 13:19:42.148  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 13:19:42.149  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 13:19:42.149  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 13:19:42.149  1035  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 13:19:42.154  7365  7365 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 13:19:42.167  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:42.168  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.168  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.188  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:42.189  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.189  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 13:19:42.203  7365  7365 I dex2oat : dex2oat took 49.243ms (threads: 4)
,08-25 13:19:42.215  7276  7294 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 13:19:42.215  7276  7294 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 13:19:42.215  7276  7294 I Adreno-EGL: Build Date: 12/12/14 금
08-25 13:19:42.215  7276  7294 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 13:19:42.215  7276  7294 I Adreno-EGL: Remote Branch: 
08-25 13:19:42.215  7276  7294 I Adreno-EGL: Local Patches: 
08-25 13:19:42.215  7276  7294 I Adreno-EGL: Reconstruct Branch: 
,08-25 13:19:42.216  7125  7125 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 13:19:42.216  7125  7125 I wpa_supplicant: monitor socket send errors count : 1
08-25 13:19:42.216  7125  7125 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
08-25 13:19:42.218  1035  7130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 13:19:42.218  1035  7130 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 13:19:42.238  7125  7125 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 13:19:42.238  7125  7125 W wpa_supplicant: USIM:  scard_deinit function
,08-25 13:19:42.240  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 13:19:42.240  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 13:19:42.240  1035  7130 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 13:19:42.240  1035  7130 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 13:19:42.240  1035  1117 D Tethering: InitialState.processMessage what=4
08-25 13:19:42.240  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:42.240  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:42.240  1035  1375 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188481
08-25 13:19:42.241  1035  1375 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188481
08-25 13:19:42.241  1035  1375 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=188481  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 13:19:42.241  1035  1375 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=188482  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 13:19:42.242  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:19:42.244  1035  1375 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:42.244  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:42.255  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 13:19:42.255  4809  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 13:19:42.257  1035  7195 D DhcpStateMachine: StoppedState
08-25 13:19:42.257  1035  7195 D DhcpStateMachine: StoppedState{ when=-157ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:42.263  1035  1375 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 13:19:42.263  1035  1375 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 13:19:42.268  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:42.275  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 13:19:42.275  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:42.275  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 13:19:42.275  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 13:19:42.276  7075  7075 I AppUp4:CustModeStarterReceiver: onReceive
08-25 13:19:42.278  7075  7075 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1108d325
08-25 13:19:42.278  7075  7075 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 13:19:42.278  7075  7075 D AppUp4:CustFacade: isPhone : true
08-25 13:19:42.278  7075  7075 D AppUp4:CustModeStarterReceiver: begin check event
08-25 13:19:42.279  7075  7075 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 13:19:42.281  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:42.281  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 13:19:42.282  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 13:19:42.285  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:42.287  4735  7382 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 13:19:42.289  7107  7107 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 13:19:42.292  4735  7384 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:42.292  4735  7384 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 13:19:42.309  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 13:19:42.309  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:42.310  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 13:19:42.312  7276  7294 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 13:19:42.312  7276  7294 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 13:19:42.312  7276  7294 I Adreno-EGL: Build Date: 12/12/14 금
08-25 13:19:42.312  7276  7294 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 13:19:42.312  7276  7294 I Adreno-EGL: Remote Branch: 
08-25 13:19:42.312  7276  7294 I Adreno-EGL: Local Patches: 
08-25 13:19:42.312  7276  7294 I Adreno-EGL: Reconstruct Branch: 
08-25 13:19:42.313  7137  7137 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 13:19:42.313  7137  7137 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 13:19:42.315  7107  7386 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.316  7003  7388 W FormManager: Network not available. Please check & try again.
,08-25 13:19:42.322  7201  7201 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:42
08-25 13:19:42.322  7201  7201 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 13:19:42.322  7003  7389 V FormManager: Network unavailable.
08-25 13:19:42.323  7201  7201 D Weather.Utils: 2 : All the weather widget is gone.
08-25 13:19:42.323  7201  7201 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 13:19:42.323  7201  7201 D WeatherAncestor: connectivity changed - connection : true
08-25 13:19:42.323  7201  7201 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6e8f2ab
08-25 13:19:42.324  7201  7201 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 13:19:42.324  7201  7201 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 13:19:42.324  7201  7201 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 13:19:42.324  7201  7201 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 13:19:42.324  7201  7201 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:42
08-25 13:19:42.328  7003  7389 V FormManager: Network unavailable.
,08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 13:19:42.342  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 13:19:42.342  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 13:19:42.342  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 13:19:42.343  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 13:19:42.345  7125  7125 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 13:19:42.346  1035  7130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 13:19:42.346  1035  7130 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 13:19:42.346  1035  7130 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 13:19:42.346  1035  1375 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-25 13:19:42.348  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:42.350  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 13:19:42.355  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:42.361  7003  7392 W FormManager: Network not available. Please check & try again.
08-25 13:19:42.364  7003  7393 V FormManager: Network unavailable.
08-25 13:19:42.366  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:42.368  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:19:42.372  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:42.374  7003  7393 V FormManager: Network unavailable.
08-25 13:19:42.381  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:42.381  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 13:19:42.382  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 13:19:42.386  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:42.387  7003  7394 W FormManager: Network not available. Please check & try again.
08-25 13:19:42.391  4735  7396 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 13:19:42.391  4735  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:42.391  4735  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 13:19:42.397  1035  2018 I art     : Explicit concurrent mark sweep GC freed 121233(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.460ms total 94.572ms
08-25 13:19:42.419  1035  1560 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7398 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 13:19:42.426  7003  7395 V FormManager: Network unavailable.
08-25 13:19:42.430  7003  7395 V FormManager: Network unavailable.
08-25 13:19:42.439  7276  7294 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 13:19:42.439  7276  7294 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 13:19:42.439  7276  7294 I Adreno-EGL: Build Date: 12/12/14 금
08-25 13:19:42.439  7276  7294 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 13:19:42.439  7276  7294 I Adreno-EGL: Remote Branch: 
08-25 13:19:42.439  7276  7294 I Adreno-EGL: Local Patches: 
08-25 13:19:42.439  7276  7294 I Adreno-EGL: Reconstruct Branch: 
,08-25 13:19:42.447  1927  1927 D WfdsService: Supplicant Connection state is changed : false
08-25 13:19:42.447  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 13:19:42.447  1927  2207 D WfdsService: Set the WFDS Monitor: false
08-25 13:19:42.448  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
,08-25 13:19:42.448  1035  1375 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 13:19:42.448  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:42.448  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:42.448  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 13:19:42.449  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 13:19:42.449  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:42.450  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 13:19:42.450  1035  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 13:19:42.450  1035  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 13:19:42.452  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:42.452  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:42.453  2495  2495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:42.453  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:42.453  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:42.512   323  7416 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 13:19:42.512  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-25 13:19:42.512  1804  7254 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-25 13:19:42.519  1804  7254 I CheckinService: active receiver: disabled
,08-25 13:19:42.542  7398  7398 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 13:19:42.543  7398  7398 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-25 13:19:42.547  7398  7398 V [BNRBootReceiver]: Boot Receiver Return
08-25 13:19:42.548  7398  7398 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-25 13:19:42.551  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:42.556  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:42.561  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:42.569  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:42.569  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:42.571  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 13:19:42.574  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 13:19:42.576  6892  6892 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 13:19:42.580  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:42.586  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.590  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:42.598  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:42.598  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:42.600  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 13:19:42.606  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 13:19:42.617  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.628  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:42.643  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:42.644  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:42.646  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 13:19:42.653  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:42.665  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.675  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:42.682  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 13:19:42.682  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 13:19:42.683  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:42.687  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:42.695  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.703  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:42.712  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:42.713  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:42.713  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 13:19:42.721  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:42.740  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.748  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:42.759  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:42.760  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:42.761  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 13:19:42.767  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:42.782  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.796  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:42.811  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:42.812  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 13:19:42.813  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:42.832  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 13:19:42.865  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.870  1035  1363 D PowerManagerServiceEx: acquireWakeLockInternal: lock=707425239, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-25 13:19:42.884  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:42.902  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:42.903  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 13:19:42.912  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 13:19:42.919  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:42.921  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 13:19:42.948  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:42.960  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:42.968  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 13:19:42.969  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:42.970  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:42.975  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 13:19:42.981  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 13:19:42.990  1035  1388 D WifiService: New client listening to asynchronous messages
,08-25 13:19:42.991  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:42.996  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:43.002  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:43.013  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:43.014  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:43.015  6946  6946 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-25 13:19:43.016  6946  6946 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 13:19:43.017  6946  6946 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 13:19:43.027  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:43.035  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 13:19:43.038  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:43.044  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:43.062  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:43.078  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:43.078  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:43.080  6946  6946 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 13:19:43.082  6946  6946 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 13:19:43.082  6946  6946 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-25 13:19:43.088  1035  1944 I ActivityManager: Killing 6865:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-25 13:19:43.149  1035  1908 W libprocessgroup: failed to open /acct/uid_10037/pid_6865/cgroup.procs: No such file or directory
,08-25 13:19:43.156  2066  2066 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 13:19:43.177  2066  2066 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-25 13:19:43.179  2066  2066 D c       : Getting all permits...
08-25 13:19:43.179  2066  2066 D a       : Opening database...
,08-25 13:19:43.184  6665  7059 D UEI.SmartControl: Internal timer expired: 2
08-25 13:19:43.184  6665  7059 D UEI.SmartControl: unbind internal service
08-25 13:19:43.187  2066  2066 D a       : Opening database auth.proximity.permit_store...
08-25 13:19:43.188  2066  2066 D a       : Closing database...
08-25 13:19:43.203  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 13:19:43.209  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 13:19:43.209  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:43.209  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:43.214  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:43.220  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:43.228  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:43.229  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:43.230  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 13:19:43.234  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:43.241  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 13:19:43.241  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:43.241  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:43.241  6665  7053 D serial_port: close(fd = 24)
08-25 13:19:43.245  6665  7053 I UEI.SmartControl: Serial port is closed.
08-25 13:19:43.247  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:43.256  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:43.264  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:43.265  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:43.268  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 13:19:43.274  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:43.282  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 13:19:43.282  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:43.282  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:43.288  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:43.293  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:43.299  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:43.299  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:43.301  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 13:19:43.309  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:43.313  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:19:43.321  7003  7423 V FormManager: Network unavailable.
08-25 13:19:43.323  7003  7423 V FormManager: Network unavailable.
08-25 13:19:43.323  7003  7422 W FormManager: Network not available. Please check & try again.
,08-25 13:19:43.326  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:43.347  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:43.347  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 13:19:43.350  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:43.354  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:43.362  4735  7424 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 13:19:43.364  6914  6914 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 13:19:43.365  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 13:19:43.365  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:43.366  4735  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:43.366  4735  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 13:19:43.370  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:19:43.374  7003  7427 W FormManager: Network not available. Please check & try again.
08-25 13:19:43.381  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:43.381  7003  7428 V FormManager: Network unavailable.
08-25 13:19:43.388  7003  7428 V FormManager: Network unavailable.
,08-25 13:19:43.400  2066  2066 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-25 13:19:43.416  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-25 13:19:43.417  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:945
,08-25 13:19:43.418  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=707425239 [*alarm*], flags=0x0
,08-25 13:19:43.920  1035  1375 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1049798608] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 13:19:43.923  1035  1375 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1049798606] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 13:19:44.014  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:44.032  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:19:44.039  1035  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:44.042  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:44.043  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:44.050  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 13:19:44.062  5866  5866 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 13:19:44.073  4809  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 13:19:44.086  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:44.118  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 13:19:44.118  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:44.118  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 13:19:44.118  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 13:19:44.123  7075  7075 I AppUp4:CustModeStarterReceiver: onReceive
08-25 13:19:44.127  7075  7075 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1108d325
08-25 13:19:44.127  7075  7075 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 13:19:44.127  7075  7075 D AppUp4:CustFacade: isPhone : true
08-25 13:19:44.127  7075  7075 D AppUp4:CustModeStarterReceiver: begin check event
08-25 13:19:44.127  7075  7075 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 13:19:44.132  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:44.132  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 13:19:44.133  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 13:19:44.140  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:44.148  7107  7107 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 13:19:44.174  4735  7445 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 13:19:44.180  1035  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 13:19:44.188  4735  7446 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:44.188  4735  7446 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 13:19:44.189  7107  7439 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:44.201  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 13:19:44.201  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:44.201  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 13:19:44.201  3424  3424 D PhoneState: setPdpRejectCasuse : false
,08-25 13:19:44.204  7003  7454 W FormManager: Network not available. Please check & try again.
08-25 13:19:44.208  7137  7137 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 13:19:44.208  7137  7137 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 13:19:44.209  7003  7455 V FormManager: Network unavailable.
08-25 13:19:44.214  7003  7455 V FormManager: Network unavailable.
,08-25 13:19:44.224  7201  7201 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:44
,08-25 13:19:44.227  7201  7201 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 13:19:44.227  7201  7201 D Weather.Utils: 2 : All the weather widget is gone.
08-25 13:19:44.228  7201  7201 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 13:19:44.228  7201  7201 D WeatherAncestor: connectivity changed - connection : true
08-25 13:19:44.228  7201  7201 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6e8f2ab
,08-25 13:19:44.229  7201  7201 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 13:19:44.229  7201  7201 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 13:19:44.229  7201  7201 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 13:19:44.229  7201  7201 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 13:19:44.229  7201  7201 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:44
08-25 13:19:45.029  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:45.030  1035  1051 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 13:19:45.063  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 13:19:45.063  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:45.064  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-25 13:19:45.064  1035  1117 D BluetoothManagerService: Message: 1
08-25 13:19:45.064  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 13:19:45.090  1035  1117 D BluetoothManagerService: Message: 20
08-25 13:19:45.091  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30ff00c5:true
,08-25 13:19:45.096  6986  6986 D BluetoothAdapterState: make
08-25 13:19:45.101  6986  6986 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 13:19:45.101  6986  6986 I bluedroid-qcom: init
08-25 13:19:45.103  6986  7472 I BluetoothAdapterState: Entering OffState
08-25 13:19:45.103  6986  6986 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 13:19:45.103  6986  6986 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 13:19:45.103  6986  6986 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 13:19:45.103  6986  6986 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 13:19:45.104  6986  6986 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 13:19:45.106  6986  6986 I bluedroid-qcom: get_profile_interface socket
08-25 13:19:45.106  6986  6986 I bluedroid-qcom: get_profile_interface map_client
,08-25 13:19:45.111  6986  7476 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 13:19:45.098  7475  7475 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:45.108  7475  7475 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:45.120  6986  7476 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 13:19:45.129  7475  7475 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 13:19:45.129  7475  7475 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 13:19:45.129  7475  7475 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-25 13:19:45.133  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 13:19:45.135  1035  1117 D BluetoothManagerService: Message: 40
08-25 13:19:45.145  7475  7475 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-25 13:19:45.149  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.152  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.152  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 13:19:45.159  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:45.163  7475  7475 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 13:19:45.163  7475  7475 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 13:19:45.166  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:45.166  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 13:19:45.166  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 13:19:45.167  6986  7002 I bluedroid-qcom: config_hci_snoop_log
08-25 13:19:45.169  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 13:19:45.169  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 13:19:45.189  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 13:19:45.191  6986  7472 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-25 13:19:45.196  1035  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.196  6986  7476 D BluetoothAdapterProperties: Name is: G3
08-25 13:19:45.197  6986  7472 D BluetoothAdapterProperties: Setting state to 11
08-25 13:19:45.197  6986  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 13:19:45.197  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-25 13:19:45.197  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-25 13:19:45.198  4809  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 13:19:45.200  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:45.200  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 13:19:45.200  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 13:19:45.204  6986  7472 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 13:19:45.206  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:45.207  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:45.211  5866  5866 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 13:19:45.230  5866  5866 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 13:19:45.230  1035  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.231  6986  7472 D BluetoothBondStateMachine: make
08-25 13:19:45.231  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:45.232  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 13:19:45.234  1035  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 13:19:45.234  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:45.234  1035  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:45.235  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 13:19:45.236  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:45.238  6986  7472 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.238  6986  7472 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 13:19:45.238  6986  7472 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.238  6986  7472 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 13:19:45.239  6986  7472 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 13:19:45.240  6986  6986 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 13:19:45.241  6986  6986 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:45.241  6986  6986 V BluetoothPbapReceiver: ***********state = 11
08-25 13:19:45.242  6986  7487 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 13:19:45.244  6986  7472 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:45.245  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:19:45.304  1035  1889 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7489 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 13:19:45.311  6986  6986 D HeadsetService: Received start request. Starting profile...
08-25 13:19:45.311  6986  7472 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:45.311  6986  6986 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 13:19:45.311  6986  6986 D LGBluetoothHfpAdapter: Version 1.6
08-25 13:19:45.315  6986  6986 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 13:19:45.316  6986  6986 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 13:19:45.317  6986  6986 D HeadsetStateMachine: make
,08-25 13:19:45.325  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:45.339  6986  7472 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:45.352  6986  7472 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 13:19:45.358  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 13:19:45.358  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.358  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 13:19:45.358  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 13:19:45.359  6986  6986 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:45.359  6986  6986 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 13:19:45.361  6986  7472 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:45.372  6986  6986 D HeadsetStateMachine: max_hf_connections = 1
08-25 13:19:45.372  6986  6986 I bluedroid-qcom: get_profile_interface handsfree
,08-25 13:19:45.375  6986  6986 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 13:19:45.376   327   327 V AudioPolicyService: registerClient() client 0xb1508560, uid 1002
08-25 13:19:45.377   327  2234 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 13:19:45.377   327  2234 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 13:19:45.377   327  2234 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 13:19:45.378  6986  6986 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 13:19:45.379   327  1386 V AudioFlinger: registerClient() client 0xb1433130, pid 6986
08-25 13:19:45.380   327  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:45.380   327  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:45.380  1035  1962 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:45.380  1035  1962 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:45.380  1586  3118 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:45.381  1586  3118 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:45.381  1839  2446 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:45.381  1839  2446 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:45.381  3424  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:45.381  3424  3440 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:45.381   327  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:45.381   327  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:45.381  1035  1926 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:45.381  1035  1926 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:45.382  1586  2146 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:45.382  1586  2146 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:45.382  1839  1854 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:45.382  1839  1854 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:45.382  6986  7001 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:45.382  6986  7001 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 13:19:45.382  3424  3441 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:45.382  3424  3441 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:45.383  6986  7001 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:45.383  6986  7001 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 13:19:45.383  6986  6986 V ToneGenerator: Create Track: 0xb4928080
08-25 13:19:45.383  6986  6986 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 13:19:45.383  6986  6986 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 13:19:45.383   327   327 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 13:19:45.383   327   327 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 13:19:45.383   327   327 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 13:19:45.383   327   327 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 13:19:45.384   327  2234 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 13:19:45.384   327  1386 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 13:19:45.384   327  1386 V AudioPolicyManager: ,getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 13:19:45.384   327  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 13:19:45.384   327  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 13:19:45.384  6986  6986 V AudioSystem: getLatency() output 2, latency 50
08-25 13:19:45.384  6986  6986 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 13:19:45.384  6986  6986 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 13:19:45.384  6986  7472 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:45.385   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 13:19:45.385   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 13:19:45.386   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 13:19:45.386   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 13:19:45.386   327  1385 V AudioFlinger: createTrack() lSessionId: 20
08-25 13:19:45.387  6986  6986 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 13:19:45.388   327   327 V AudioFlinger: acquiring 20 from 6986, for 6986
08-25 13:19:45.388   327   327 V AudioFlinger:  added new entry for 20
08-25 13:19:45.388  6986  6986 V ToneGenerator: ToneGenerator INIT OK, time: 191643
08-25 13:19:45.388  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
,08-25 13:19:45.390  6986  7504 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 13:19:45.391  6986  7504 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 13:19:45.391  6986  7504 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 13:19:45.392  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.392  6986  7504 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 13:19:45.397  6986  6986 D A2dpService: Received start request. Starting profile...
08-25 13:19:45.398  6986  6986 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 13:19:45.399  6986  6986 V Avrcp   : make
08-25 13:19:45.400  6986  6986 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 13:19:45.400  6986  6986 I bluedroid-qcom: get_profile_interface avrcp
08-25 13:19:45.401  7075  7075 I AppUp4:CustModeStarterReceiver: onReceive
08-25 13:19:45.401   327  2234 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6986
08-25 13:19:45.402   327  2234 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 13:19:45.402   327  2234 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 13:19:45.402   327  2234 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 13:19:45.402   327  2234 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 13:19:45.402   327  2234 V voice   : voice_set_parameters: exit with code(0)
08-25 13:19:45.402   327  2234 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 13:19:45.402   327  2234 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 13:19:45.402   327  2234 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 13:19:45.402   327  2234 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 13:19:45.402   327  2234 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 13:19:45.402   327  2234 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 13:19:45.402  6986  7504 V ToneGenerator: ToneGenerator destructor
08-25 13:19:45.402  6986  7504 V ToneGenerator: stopTone
08-25 13:19:45.402  6986  7504 V ToneGenerator: Delete Track: 0xb4928080
08-25 13:19:45.403  6986  7504 V AudioTrack: ~AudioTrack, releasing session id from 6986 on behalf of 6986
08-25 13:19:45.403   327  1386 V AudioFlinger: releasing 20 from 6986 for 6986
08-25 13:19:45.403   327  1386 V AudioFlinger:  decremented refcount to 0
08-25 13:19:45.403   327  1386 V AudioFlinger: purging stale effects
08-25 13:19:45.403   327  1386 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 13:19:45.403   327  1386 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 13:19:45.403   327  1274 V AudioPolicyService: AudioCommandThread() waking up
08-25 13:19:45.403   327  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 13:19:45.403   327  1274 V AudioPolicyManager: releaseOutput() 2
08-25 13:19:45.403   327  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 13:19:45.404   327  1386 V AudioFlinger: PlaybackThread::Track destructor
08-25 13:19:45.404   327  1386 V AudioFlinger: removeClient_l() pid 6986, calling pid 327
08-25 13:19:45.407  7075  7075 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1108d325
08-25 13:19:45.407  7075  7075 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 13:19:45.407  7075  7075 D AppUp4:CustFacade: isPhone : true
08-25 13:19:45.414  7075  7075 D AppUp4:CustModeStarterReceiver: begin check event
08-25 13:19:45.414  7075  7075 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 13:19:45.417  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Rec,eiver android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.417  6986  7472 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:45.418  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 13:19:45.418  6986  6986 V AudioManager: registerRemoteController: size of Media player list: 0
08-25 13:19:45.419  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 13:19:45.426  6986  6986 E AudioManager: No RCC entry present to update
08-25 13:19:45.426  6986  6986 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 13:19:45.427  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:45.430  6986  6986 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 13:19:45.431  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 13:19:45.431  6986  6986 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-25 13:19:45.440  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 13:19:45.449  6986  7472 V LGMDMManager: Create singleton instance
,08-25 13:19:45.450  6986  7472 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 13:19:45.466  4735  7516 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 13:19:45.471  4735  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.471  4735  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 13:19:45.499  7107  7107 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 13:19:45.517  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 13:19:45.518  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.518  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 13:19:45.519  7107  7519 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:19:45.521  7137  7137 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 13:19:45.521  7137  7137 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 13:19:45.529  7003  7522 W FormManager: Network not available. Please check & try again.
08-25 13:19:45.533  7201  7201 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:45
,08-25 13:19:45.539  7201  7201 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 13:19:45.539  7201  7201 D Weather.Utils: 2 : All the weather widget is gone.
08-25 13:19:45.539  7489  7489 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 13:19:45.539  7003  7523 V FormManager: Network unavailable.
08-25 13:19:45.540  7489  7489 W LG Account v2.2: No ProfileInfo entries
08-25 13:19:45.540  7489  7489 I LG Account v2.2: isEnabled: false
08-25 13:19:45.540  7201  7201 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Country: EU
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Operator: OPEN
08-25 13:19:45.540  7201  7201 D WeatherAncestor: connectivity changed - connection : true
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Ranking support: false
08-25 13:19:45.540  7201  7201 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6e8f2ab
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Comfort support: false
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Accessory: true
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Health device: true
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Extra Pedometer: false
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Blood glucose device: false
08-25 13:19:45.540  7489  7489 I Feature : [Lifetracker]Device Number: 3
08-25 13:19:45.542  7201  7201 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 13:19:45.542  7201  7201 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 13:19:45.542  7201  7201 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 13:19:45.542  7201  7201 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 13:19:45.542  7201  7201 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:45
08-25 13:19:45.545  7003  7523 V FormManager: Network unavailable.
,08-25 13:19:45.552  6892  6892 D BluetoothPermissionRequest: onReceive
08-25 13:19:45.560  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 13:19:45.562  1035  1997 V SIM_STK : Menu title from STK is T-Mobile
,08-25 13:19:45.562  1035  1997 V SIM_STK : Menu title from STK is T-Mobile
08-25 13:19:45.572  4809  4809 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 13:19:45.572  4809  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 13:19:45.584  2066  2066 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.592  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 13:19:45.592  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.592  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 13:19:45.592  7075  7075 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 13:19:45.594  7075  7075 I AppUp4:CustModeStarterReceiver: onReceive
08-25 13:19:45.596  7075  7075 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1108d325
08-25 13:19:45.596  7075  7075 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 13:19:45.596  7075  7075 D AppUp4:CustFacade: isPhone : true
08-25 13:19:45.596  7075  7075 D AppUp4:CustModeStarterReceiver: begin check event
08-25 13:19:45.596  7075  7075 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 13:19:45.598  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.599  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 13:19:45.600  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:45.601  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:45.604  4735  7526 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 13:19:45.606  7107  7107 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 13:19:45.608  4735  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.608  4735  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 13:19:45.618  1035  1944 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 13:19:45.622  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 13:19:45.622  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:45.623  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 13:19:45.625  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 13:19:45.625  7107  7529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:45.626  7003  7530 W FormManager: Network not available. Please check & try again.
08-25 13:19:45.628  7137  7137 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 13:19:45.628  7137  7137 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 13:19:45.629  7003  7531 V FormManager: Network unavailable.
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 13:19:45.629  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 13:19:45.630  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 13:19:45.630  6986  6986 I BluetoothA2dpServiceJni: classInitNative
08-25 13:19:45.630  6986  6986 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 13:19:45.630  6986  6986 D A2dpStateMachine: make
08-25 13:19:45.631  6986  6986 I bluedroid-qcom: get_profile_interface a2dp
08-25 13:19:45.631  6986  7534 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 13:19:45.632  6986  6986 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 13:19:45.633  6986  6986 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 13:19:45.633  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.633  6986  7533 D A2dpStateMachine: Enter Disconnected: -2
08-25 13:19:45.634  6986  6986 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 13:19:45.635  6986  6986 D HidService: Received start request. Starting profile...
08-25 13:19:45.635  6986  6986 I bluedroid-qcom: get_profile_interface hidhost
08-25 13:19:45.635  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.635  6986  6986 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 13:19:45.638  7201  7201 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:45
08-25 13:19:45.638  6986  6986 D HealthService: Received start request. Starting profile...
08-25 13:19:45.639  7003  7531 V FormManager: Network unavailable.
08-25 13:19:45.639  7201  7201 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 13:19:45.639  7201  7201 D Weather.Utils: 2 : All the weather widget is gone.
08-25 13:19:45.639  7201  7201 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 13:19:45.639  7201  7201 D WeatherAncestor: connectivity changed - connection : true
08-25 13:19:45.639  7201  7201 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6e8f2ab
08-25 13:19:45.639  6986  6986 I bluedroid-qcom: get_profile_interface health
08-25 13:19:45.640  6986  6986 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 13:19:45.640  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.640  7201  7201 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 13:19:45.640  7201  7201 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 13:19:45.640  7201  7201 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 13:19:45.640  7201  7201 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 13:19:45.640  7201  7201 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:19:45
08-25 13:19:45.640  6986  6986 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 13:19:45.642  6986  6986 D PanService: Received start request. Starting profile...
08-25 13:19:45.642  6986  6986 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 13:19:45.642  6986  6986 I bluedroid-qcom: get_profile_interface pan
,08-25 13:19:45.646  6986  6986 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 13:19:45.646  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.646  6986  6986 D HeadsetStateMachine: Proxy object connected
08-25 13:19:45.646  6986  6986 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 13:19:45.646  6986  6986 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 13:19:45.649  6986  6986 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:45.650  6986  6986 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 13:19:45.650  6986  7504 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 13:19:45.650  6986  7504 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 13:19:45.650  6986  7504 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 13:19:45.653  6986  6986 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 13:19:45.653  6986  6986 D BtGatt.GattService: Received start request. Starting profile...
08-25 13:19:45.653  6986  6986 D BtGatt.GattService: start()
08-25 13:19:45.653  6986  6986 I bluedroid-qcom: get_profile_interface gatt
08-25 13:19:45.653  6986  6986 D BtGatt.AdvertiseManager: advertise manager created
,08-25 13:19:45.657  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.658  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.658  6986  6986 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 13:19:45.659  6986  6986 V BluetoothMapService: BluetoothMapBinder()
08-25 13:19:45.659  6986  6986 D BluetoothMapService: Received start request. Starting profile...
08-25 13:19:45.659  6986  6986 D BluetoothMapService: start()
08-25 13:19:45.661  6986  6986 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 13:19:45.661  6986  6986 D BluetoothMapEmailAppObserver: createReceiver()
08-25 13:19:45.662  6986  6986 D BluetoothMapEmailAppObserver: initObservers()
08-25 13:19:45.662  6986  6986 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-25 13:19:45.667  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:45.670  6986  6986 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:45.673  6986  6986 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:45.675  6986  6986 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:45.675  6986  6986 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 13:19:45.677  6986  6986 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 13:19:45.680  6986  6986 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-25 13:19:45.680  6986  6986 V BluetoothMapService: Handler(): got msg=1
08-25 13:19:45.681  6986  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 13:19:45.681  6986  7472 I bluedroid-qcom: enable
08-25 13:19:45.681  6986  7541 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 13:19:45.681  6986  7541 I bt-btu  : btu_task pending for preload complete event
08-25 13:19:45.681  6986  7472 I bt_hci_bdroid: init
08-25 13:19:45.682  6986  6986 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:45.684  6986  7472 I bt_vendor: bt-vendor : init
08-25 13:19:45.684  6986  7472 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 13:19:45.684  6986  7472 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 13:19:45.684  6986  7472 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 13:19:45.684  6986  7472 D bt_userial_mct: userial_init
08-25 13:19:45.684  6986  7472 D bt_hci_bdroid: set_power 1
08-25 13:19:45.684  6986  7472 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 13:19:45.684  6986  7472 I bt_vendor: Starting hciattach daemon
08-25 13:19:45.684  6986  7472 I bt_vendor: try to set true
08-25 13:19:45.685  6986  6986 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 13:19:45.685  6986  6986 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 13:19:45.685  6986  6986 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:45.685  6986  6986 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:45.685  6986  6986 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 13:19:45.678  7544  7544 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:45.678  7544  7544 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:45.702  7545  7545 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 13:19:45.766  7551  7551 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 13:19:45.781  7552  7552 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 13:19:45.827  7554  7554 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 13:19:45.844  7555  7555 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 13:19:45.867  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 13:19:45.884  7557  7557 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 13:19:45.923  7559  7559 I libmdmdetect: ESOC framework not supported
08-25 13:19:45.924  7559  7559 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 13:19:45.933  7559  7559 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 13:19:45.933  7559  7559 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 13:19:45.933  7559  7559 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 13:19:45.933  7559  7559 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 13:19:45.933  7559  7559 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 13:19:45.933  7559  7559 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 13:19:45.933  7559  7559 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 13:19:45.976  7559  7560 E QC-QMI  : qmi_client [7559] 14: failed to locate client data
08-25 13:19:45.977   463   463 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-25 13:19:45.977   463   463 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-25 13:19:46.035  7567  7567 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 13:19:46.052  7568  7568 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 13:19:46.086  6986  7472 I bt_vendor: bluetooth satus is on
08-25 13:19:46.086  6986  7472 D bt_hci_bdroid: preload
08-25 13:19:46.086  6986  7543 D bt_userial_mct: userial_open(port:0)
08-25 13:19:46.086  6986  7543 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 13:19:46.089  6986  7543 I bt_vendor: Done intiailizing UART
08-25 13:19:46.090  6986  7543 I bt_vendor: Done intiailizing UART
08-25 13:19:46.090  6986  7543 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 13:19:46.091  6986  7543 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 13:19:46.091  6986  7570 D bt_userial_mct: Entering userial_read_thread()
08-25 13:19:46.091  6986  7541 I bt-btu  : btu_task received preload complete event
08-25 13:19:46.092  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 13:19:46.092  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 13:19:46.094  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 13:19:46.097  6986  7541 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 13:19:46.105  1035  1106 W ProcessCpuTracker: Skipping unknown process pid 7482
,08-25 13:19:46.106  1035  1106 W ProcessCpuTracker: Skipping unknown process pid 7483
,08-25 13:19:46.107  1035  1106 W ProcessCpuTracker: Skipping unknown process pid 7486
,08-25 13:19:46.107  1035  1106 W ProcessCpuTracker: Skipping unknown process pid 7488
08-25 13:19:46.108  1035  1106 W ProcessCpuTracker: Skipping unknown process pid 7544
08-25 13:19:46.109  1035  1106 W ProcessCpuTracker: Skipping unknown process pid 7564
08-25 13:19:46.109  1035  1106 W ProcessCpuTracker: Skipping unknown process pid 7569
08-25 13:19:46.201  6986  7541 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 13:19:46.201  6986  7541 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f4061 
,08-25 13:19:46.202  6986  7541 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f4061 
,08-25 13:19:46.233  6986  7476 E bt-btif : Calling BTA_HhEnable
08-25 13:19:46.234  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 13:19:46.234  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 13:19:46.234  6986  7541 W bt-l2cap: btif_storage_get_adapter_property service_mask
08-25 13:19:46.234  6986  7476 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 13:19:46.234  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 13:19:46.234  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 13:19:46.235  6986  7476 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 13:19:46.246  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-25 13:19:46.246  6986  7476 D BluetoothAdapterProperties: Name is: G3
08-25 13:19:46.246  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 13:19:46.249  6986  7476 D BluetoothAdapterProperties: Scan Mode:20
08-25 13:19:46.249  6986  7476 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 13:19:46.249  6986  7476 D bt_hci_bdroid: postload
08-25 13:19:46.250  6986  7543 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:46.250  6986  7541 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 13:19:46.251  6986  7476 D bte_conf: Device ID record 1 : primary
08-25 13:19:46.251  6986  7476 D bte_conf:   vendorId            = 00c4
08-25 13:19:46.251  6986  7476 D bte_conf:   vendorIdSource      = 0001
08-25 13:19:46.251  6986  7476 D bte_conf:   product             = 13a1
08-25 13:19:46.251  6986  7476 D bte_conf:   version             = 1000
08-25 13:19:46.251  6986  7476 D bte_conf:   clientExecutableURL = 
08-25 13:19:46.251  6986  7476 D bte_conf:   serviceDescription  = 
08-25 13:19:46.251  6986  7476 D bte_conf:   documentationURL    = 
08-25 13:19:46.251  6986  7476 D bte_conf: bte_load_did_conf no section named DID2.
08-25 13:19:46.254  6986  7541 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:46.254  6986  7541 W bt-smp  : Plain text(LSB ~ MSB) = 17 df 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:46.254  6986  7541 W bt-smp  : Encrypted text(LSB ~ MSB) = d3 6d 76 d6 cb 3b 37 8d aa a7 99 1c 83 b0 82 30 
08-25 13:19:46.254  6986  7541 W bt-btm  : Stopping oneshot timer
08-25 13:19:46.254  6986  7543 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:46.258  6986  7543 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:46.258  6986  7543 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 13:19:46.262  6986  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 13:19:46.262  6986  7472 D BluetoothAdapterProperties: ScanMode =  20
08-25 13:19:46.262  6986  7472 D BluetoothAdapterProperties: State =  11
08-25 13:19:46.262  6986  7472 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 13:19:46.263  6986  7472 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 13:19:46.263  6986  7472 D BluetoothAdapterProperties: Setting state to 12
08-25 13:19:46.263  6986  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 13:19:46.264  6986  7543 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:46.248  7572  7572 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:46.264  6986  7476 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 13:19:46.264  6986  7476 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 13:19:46.248  7572  7572 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:46.267  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:46.267  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 13:19:46.267  6986  7570 E bt_mct  : hci lib postload completed
08-25 13:19:46.268  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:46.272  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:46.278  6986  7472 I BluetoothAdapterState: Entering On State
08-25 13:19:46.280  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:46.283  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:46.285  6986  7541 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:46.285  6986  7541 W bt-smp  : Plain text(LSB ~ MSB) = 17 bd 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:46.285  6986  7541 W bt-smp  : Encrypted text(LSB ~ MSB) = 0d 3c 36 85 18 18 dc 04 b4 f7 c2 cb 42 16 7d 9b 
08-25 13:19:46.286  6986  7541 W bt-btm  : Stopping oneshot timer
,08-25 13:19:46.289  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:46.290  6892  6908 D BluetoothMap: onBluetoothStateChange: up=true
08-25 13:19:46.301  6986  7541 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:46.301  6986  7541 W bt-smp  : Plain text(LSB ~ MSB) = 23 47 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:46.301  6986  7541 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 96 b3 4f 63 e9 6e 38 9b ca 22 1e 9b dd 7e 88 
08-25 13:19:46.301  6986  7541 W bt-btm  : Stopping oneshot timer
,08-25 13:19:46.304  6986  7472 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-25 13:19:46.305  6986  7472 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 13:19:46.306  6986  7472 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 13:19:46.306  6986  7476 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 13:19:46.306  6986  7476 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 13:19:46.307  6986  7472 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 13:19:46.310  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:46.311  6986  7541 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:46.311  6986  7541 W bt-smp  : Plain text(LSB ~ MSB) = 68 7c 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:46.311  6986  7541 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 8a ae bb ec b8 28 42 85 3b 46 26 56 3a f5 c7 
08-25 13:19:46.311  6986  7541 W bt-btm  : Stopping oneshot timer
08-25 13:19:46.317  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:46.318  1839  1839 D BluetoothHeadset: Proxy object connected
,08-25 13:19:46.321  1839  1839 D BluetoothHeadset: Proxy object connected
08-25 13:19:46.321  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 13:19:46.323  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:46.323  1035  1035 D BluetoothHeadset: Proxy object connected
08-25 13:19:46.325  6986  7541 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:46.325  6986  7541 W bt-smp  : Plain text(LSB ~ MSB) = de f0 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:46.325  6986  7541 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b 43 53 eb 79 30 0b be 4c 20 a3 13 7b 57 96 0f 
08-25 13:19:46.325  6986  7541 W bt-btm  : Stopping oneshot timer
08-25 13:19:46.326  1035  1035 D BluetoothA2dp: Proxy object connected
08-25 13:19:46.326  6892  6910 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 13:19:46.331  6986  7472 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 13:19:46.332  6892  6908 D BluetoothPan: onBluetoothStateChange on: true
08-25 13:19:46.332  6892  6908 D BluetoothPan: onBluetoothStateChange call bindService
,08-25 13:19:46.337  6892  6910 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 13:19:46.339  1839  2446 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:46.341  1839  1839 D BluetoothHeadset: Proxy object connected
08-25 13:19:46.342  7579  7579 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 13:19:46.344  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-25 13:19:46.347  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 13:19:46.347  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 13:19:46.349  6892  6892 D BluetoothMap: Proxy object connected
08-25 13:19:46.349  6892  6892 D MapProfile: Bluetooth service connected
08-25 13:19:46.349  6892  6892 D BluetoothMap: getConnectedDevices()
08-25 13:19:46.352  6986  7001 V BluetoothMapService: getConnectedDevices()
08-25 13:19:46.354  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:46.354  1927  2086 D LGBluetoothAPIService: Message: 1
08-25 13:19:46.354  1927  2086 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 13:19:46.355  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 13:19:46.355  1035  1117 D BluetoothManagerService: Message: 40
08-25 13:19:46.361  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-25 13:19:46.363  6892  6892 D BluetoothInputDevice: Proxy object connected
08-25 13:19:46.363  6892  6892 D HidProfile: Bluetooth service connected
08-25 13:19:46.365  1927  2086 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 13:19:46.367  6766  6766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 13:19:46.368  6986  6986 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:46.369  6986  6986 D BluetoothMapService: STATE_ON
08-25 13:19:46.371  6892  6892 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:19:46.371  6892  6892 D PanProfile: Bluetooth service connected
08-25 13:19:46.371  6986  6986 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 13:19:46.371  6986  6986 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 13:19:46.372  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:46.373  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 13:19:46.374  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:46.374  1927  2086 D LGBluetoothAPIService: Message: 100
08-25 13:19:46.374  1927  2086 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 13:19:46.378  6892  6892 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 13:19:46.381  1035  1117 D BluetoothManagerService: Message: 30
08-25 13:19:46.383  7228  7262 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-25 13:19:46.386  6892  6892 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 13:19:46.388  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:46.388  6986  6986 V BluetoothPbapService: Pbap Service onCreate
08-25 13:19:46.388  6986  6986 V BluetoothPbapService: Starting PBAP service
,08-25 13:19:46.389  1035  1117 D BluetoothManagerService: Message: 30
08-25 13:19:46.390  6986  6986 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 13:19:46.390  6986  6986 V BluetoothMapService: Handler(): got msg=1
08-25 13:19:46.391  6986  6986 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 13:19:46.391  6986  6986 V BluetoothPbapService: Pbap Service onBind
08-25 13:19:46.392  6986  7595 D BluetoothMapMasInstance: MAS initSocket()
08-25 13:19:46.393  6986  6986 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:46.393  6986  6986 V BluetoothPbapService: state: 12
08-25 13:19:46.393  6986  6986 V BluetoothPbapService: Handler(): got msg=1
08-25 13:19:46.394  6986  7595 D BluetoothMapMasInstance:   masId = 00
08-25 13:19:46.394  6986  7595 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 13:19:46.394  6986  7595 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 13:19:46.394  6986  7595 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 13:19:46.394  6986  6986 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 13:19:46.395  6986  7596 V BluetoothPbapService: Pbap Service initSocket
08-25 13:19:46.396  1035  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:46.396  1035  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:46.396  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 13:19:46.398  6986  7595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:46.398  6986  7596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:46.399  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 13:19:46.401  6986  7596 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 13:19:46.402  6986  7596 V BluetoothPbapService: Succeed to create listening socket 
08-25 13:19:46.402  6986  7596 V BluetoothPbapService: Accepting socket connection...
,08-25 13:19:46.404  6986  7595 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 13:19:46.406  6986  7595 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 13:19:46.406  6986  7595 D BluetoothMapMasInstance: Accepting socket connection...
08-25 13:19:46.406  6892  6892 D BluetoothA2dp: Proxy object connected
08-25 13:19:46.406  6986  7476 D BluetoothAdapterProperties: Scan Mode:21
08-25 13:19:46.407  6986  7476 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 13:19:46.407  6892  6892 D A2dpProfile: Bluetooth service connected
08-25 13:19:46.407  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:46.408  6986  6986 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 13:19:46.408  6986  6986 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:46.408  6986  6986 V BluetoothPbapReceiver: ***********state = 12
08-25 13:19:46.409  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:46.409  6892  6892 D BluetoothHeadset: Proxy object connected
08-25 13:19:46.410  6892  6892 D HeadsetProfile: Bluetooth service connected
08-25 13:19:46.411  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:19:46.412  6892  6892 D BluetoothPbap: Proxy object connected
08-25 13:19:46.412  6892  6892 D PbapServerProfile: Bluetooth service connected
08-25 13:19:46.413  2066  2066 D c       : Getting all permits...
08-25 13:19:46.413  2066  2066 D a       : Opening database...
08-25 13:19:46.417  2066  2066 D a       : Opening database auth.proximity.permit_store...
08-25 13:19:46.417  6892  6892 D DockEventReceiver: finishStartingService: stopping service
08-25 13:19:46.418  2066  2066 D a       : Closing database...
,08-25 13:19:46.429  6892  6892 D BluetoothPermissionRequest: onReceive
08-25 13:19:46.430  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-25 13:19:46.432  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 13:19:46.435  6986  6986 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 13:19:46.436  6986  6986 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 13:19:46.441  6986  6986 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 13:19:46.460  6986  6986 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 13:19:46.461  6986  6986 V BtOppService: onCreate
,08-25 13:19:46.466  6986  6986 V BluetoothOppNotification: send message
08-25 13:19:46.469  6986  6986 V BtOppService: Starting RfcommListener
08-25 13:19:46.478  6986  6986 D BluetoothOppPreference: Dumping Names:  
08-25 13:19:46.478  6986  6986 D BluetoothOppPreference: {}
08-25 13:19:46.478  6986  6986 D BluetoothOppPreference: Dumping Channels:  
08-25 13:19:46.479  6986  6986 D BluetoothOppPreference: {}
08-25 13:19:46.480  6986  6986 V BtOppService: onStartCommand
08-25 13:19:46.481  6986  7604 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-25 13:19:46.486  6986  6986 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:19:46.486  6986  6986 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 13:19:46.487  6986  7604 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 13:19:46.487  6986  7601 V BtOppService: Deleted complete outbound shares, number =  0
08-25 13:19:46.489  6986  7601 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 13:19:46.489  6986  7601 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 13:19:46.490  6986  6986 V BluetoothOppNotification: new notify threadi!
08-25 13:19:46.491  6986  6986 V BluetoothOppNotification: send delay message
08-25 13:19:46.492  6986  6986 V BtOppService: start RfcommListener
08-25 13:19:46.492  6986  7601 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38da0044 on behalf of 
,08-25 13:19:46.496  6986  7604 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@197f052d on behalf of 
08-25 13:19:46.499  6986  6986 V BtOppService: RfcommListener started
08-25 13:19:46.499  6986  7605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 13:19:46.499  6986  6986 V BtOppService: ContentObserver received notification
08-25 13:19:46.499  6986  6986 V BtOppService: ContentObserver received notification
08-25 13:19:46.501  6986  7606 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 13:19:46.502  1035  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:46.503  6986  7604 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 13:19:46.503  6986  7604 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 13:19:46.505  6986  7606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:19:46.507  6986  7604 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c771a62 on behalf of 
08-25 13:19:46.508  6986  7605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@128c47f3 on behalf of 
,08-25 13:19:46.508  6986  7606 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,08-25 13:19:46.509  6986  7604 V BluetoothOppNotification: update too frequent, put in queue
08-25 13:19:46.509  6986  7605 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 13:19:46.509  6986  7606 V BtOppRfcommListener: Started RFCOMM listener....
08-25 13:19:46.509  6986  7606 I BtOppRfcommListener: Accept thread started.
08-25 13:19:46.509  6986  7606 V BtOppRfcommListener: Accepting connection...
08-25 13:19:46.510  6986  7605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:46.512  6986  7605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c98dcb0 on behalf of 
08-25 13:19:46.513  6986  7605 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 13:19:46.513  6986  7604 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 13:19:46.514  6986  7605 V BluetoothOppNotification: outbound notification was removed.
08-25 13:19:46.514  6986  7605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:46.516  6986  7605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@73c729 on behalf of 
08-25 13:19:46.517  6986  7605 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 13:19:46.518  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:46.518  6986  6986 V BluetoothFtpService: Ftp Service onCreate
08-25 13:19:46.518  6986  6986 I BluetoothFtpService: Ftp Service onCreate
08-25 13:19:46.519  6986  6986 V BluetoothFtpService: Ftp Service onStartCommand
08-25 13:19:46.519  6986  6986 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:46.519  6986  6986 V BluetoothFtpService: Starting Listening on sockets
08-25 13:19:46.519  6986  7605 V BluetoothOppNotification: inbound notification was removed.
08-25 13:19:46.519  6986  7605 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 13:19:46.519  6986  6986 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 13:19:46.519  6986  6986 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 13:19:46.519  6986  6986 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:46.519  6986  6986 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:46.519  6986  6986 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 13:19:46.519  6986  6986 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-25 13:19:46.525  6986  6986 V BluetoothFtpService: Handler(): got msg=1
,08-25 13:19:46.526  6986  7605 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@319704f on behalf of 
08-25 13:19:46.526  6986  6986 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 13:19:46.526  6986  6986 V BluetoothFtpService: Ftp Service initSocket
08-25 13:19:46.535  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 13:19:46.536  6986  6986 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:19:46.539  6986  6986 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-25 13:19:46.540  6986  6986 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 13:19:46.543  6986  7607 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 13:19:46.559  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:46.559  6986  6986 V BluetoothSapService: Sap Service onCreate
,08-25 13:19:46.561  6986  6986 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:46.561  6986  6986 V BluetoothSapService: state: 12
08-25 13:19:46.561  6986  6986 V BluetoothSapService: Starting SAP server process
08-25 13:19:46.563  6986  6986 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 13:19:46.548  7608  7608 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:46.548  7608  7608 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:46.567  6986  7609 V BluetoothSapService: Sap Service initRfcommSocket
08-25 13:19:46.568  1035  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:46.570  6986  7609 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:46.572  6986  7609 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-25 13:19:46.573  6986  7609 V BluetoothSapService: Succeed to create listening socket 
08-25 13:19:46.573  6986  7609 V BluetoothSapService: Accepting socket connection...
08-25 13:19:46.589  7608  7608 V BT_SAP  : Event pipe created
08-25 13:19:46.589  7608  7608 V BT_SAP  : create_server_socket qcom.sap.server
08-25 13:19:46.589  7608  7608 V BT_SAP  : created socket fd 6
,08-25 13:19:47.101  1035  1374 D LGWifiP2pService: P2pDisabledState{ when=-7ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:47.101  1035  1374 D LGWifiP2pService: DefaultState{ when=-7ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:19:47.132  1035  1375 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-25 13:19:47.133  1035  1375 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 13:19:47.260  1035  1771 I ActivityManager: Killing 7398:com.lge.bnr/1000 (adj 15): empty #17
,08-25 13:19:47.292  1035  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_7398/cgroup.procs: No such file or directory
,08-25 13:19:47.492  6986  6986 V BluetoothOppNotification: new notify threadi!
,08-25 13:19:47.493  6986  6986 V BluetoothOppNotification: send delay message
,08-25 13:19:47.512  1035  1926 I ActivityManager: Killing 6914:com.lge.sync/1000 (adj 15): empty #17
,08-25 13:19:47.521  6986  7619 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 13:19:47.534  1035  1388 D WifiService: Client connection lost with reason: 4
,08-25 13:19:47.537  6986  7619 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3da6c26b on behalf of 
08-25 13:19:47.538  6986  7619 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 13:19:47.539  6986  7619 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:47.540  6986  7619 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18ff91c8 on behalf of 
08-25 13:19:47.541  6986  7619 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 13:19:47.543  6986  7619 V BluetoothOppNotification: outbound notification was removed.
08-25 13:19:47.543  6986  7619 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:47.544  6986  7619 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bec3261 on behalf of 
08-25 13:19:47.544  6986  7619 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 13:19:47.550  6986  7619 V BluetoothOppNotification: inbound notification was removed.
,08-25 13:19:47.550  6986  7619 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-25 13:19:47.551  6986  7619 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22f13186 on behalf of 
08-25 13:19:47.555  1035  2018 W libprocessgroup: failed to open /acct/uid_1000/pid_6914/cgroup.procs: No such file or directory
08-25 13:19:48.078  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:48.079  1035  1908 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@f26cce1 mBinding = false
,08-25 13:19:48.123  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 13:19:48.124  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:48.124  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-25 13:19:48.124  1035  1117 D BluetoothManagerService: Message: 2
08-25 13:19:48.125  1035  1117 D BluetoothManagerService: Sending off request.
08-25 13:19:48.126  6986  7002 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 13:19:48.127  6986  7472 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 13:19:48.127  6986  7472 D BluetoothAdapterProperties: Setting state to 13
08-25 13:19:48.127  6986  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 13:19:48.128  6986  7472 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 13:19:48.128  6986  7472 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 13:19:48.130  6986  7476 D BluetoothAdapterProperties: Scan Mode:20
08-25 13:19:48.132  6986  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-25 13:19:48.136  6986  7596 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:48.137  6986  7472 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 13:19:48.139  6986  7606 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:48.139  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 13:19:48.139  6986  7541 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 13:19:48.140  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:48.140  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:48.140  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 13:19:48.141  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 13:19:48.141  6986  7541 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 13:19:48.142  6986  7595 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 13:19:48.145  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:48.145  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:48.153  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:48.154  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:48.158  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:48.158  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:48.161  6766  6766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:19:48.161  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:48.165  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:48.165  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 13:19:48.165  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 13:19:48.168  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:48.169  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 13:19:48.175  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:48.180  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:48.181  6986  6986 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:48.181  6986  6986 D BluetoothMapService: STATE_TURNING_OFF
08-25 13:19:48.181  6986  6986 V BluetoothMapService: Handler(): got msg=4
08-25 13:19:48.181  6986  6986 D BluetoothMapService: MAP Service closeService in
08-25 13:19:48.182  6986  6986 D BluetoothMapMasInstance: MAP Service shutdown
08-25 13:19:48.182  6986  6986 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 13:19:48.182  6986  6986 V BluetoothMapService: MAP Service closeService out
08-25 13:19:48.183  6986  6986 V BtOppService: Receiver DISABLED_ACTION 
08-25 13:19:48.183  6986  6986 I BtOppRfcommListener: stopping Accept Thread
08-25 13:19:48.183  6986  6986 V BtOppRfcommListener: close mBtServerSocket
08-25 13:19:48.184  6986  7606 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 13:19:48.184  6986  6986 V BtOppRfcommListener: waiting for thread to terminate
08-25 13:19:48.184  6986  6986 V BtOppRfcommListener: done waiting for thread to terminate
08-25 13:19:48.188  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-25 13:19:48.195  6986  7607 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:48.199  6986  7609 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:19:48.202  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 13:19:48.206  6986  6986 V BtOppService: onDestroy
08-25 13:19:48.207  6986  6986 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 13:19:48.212  6986  6986 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 13:19:48.212  6986  6986 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:48.212  6986  6986 V BluetoothPbapReceiver: ***********state = 13
08-25 13:19:48.214  6986  6986 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 13:19:48.219  6986  6986 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:48.219  6986  6986 V BluetoothPbapService: state: 13
08-25 13:19:48.219  6986  6986 V BluetoothPbapService: Pbap Service closeService in
08-25 13:19:48.222  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:19:48.224  6986  6986 V BluetoothPbapService: successfully stopped pbap service
08-25 13:19:48.224  6986  6986 V BluetoothPbapService: Pbap Service closeService out
08-25 13:19:48.225  6986  6986 V BluetoothPbapService: Pbap Service onDestroy
08-25 13:19:48.225  6986  6986 V BluetoothPbapService: Pbap Service closeService in
08-25 13:19:48.225  6986  6986 V BluetoothPbapService: Pbap Service closeService out
08-25 13:19:48.225  6986  6986 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 13:19:48.245  6892  6892 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:19:48.248  6892  6892 D BluetoothPbap: Proxy object disconnected
08-25 13:19:48.248  6892  6892 D PbapServerProfile: Bluetooth service disconnected
08-25 13:19:48.254  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 13:19:48.263  6892  6892 D BluetoothPermissionRequest: onReceive
08-25 13:19:48.263  6892  6892 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 13:19:48.273  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 13:19:48.281  6986  6986 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 13:19:48.281  6986  6986 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 13:19:48.282  6986  6986 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 13:19:48.287  6986  6986 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:19:48.287  6986  6986 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 13:19:48.288  6986  6986 V BluetoothFtpService: Ftp Service onStartCommand
08-25 13:19:48.288  6986  6986 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:48.289  6986  6986 V BluetoothFtpService: Ftp Service closeService
08-25 13:19:48.289  6986  6986 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 13:19:48.291  6986  6986 V BluetoothFtpService: successfully stopped ftp service
08-25 13:19:48.291  6986  6986 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 13:19:48.291  6986  6986 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 13:19:48.291  6986  6986 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:48.291  6986  6986 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:48.291  6986  6986 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 13:19:48.291  6986  6986 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 13:19:48.293  6986  6986 V BluetoothFtpService: Ftp Service onDestroy
08-25 13:19:48.293  6986  6986 V BluetoothFtpService: Ftp Service closeService
08-25 13:19:48.298  6986  6986 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:48.298  6986  6986 V BluetoothSapService: state: 13
08-25 13:19:48.298  6986  6986 V BluetoothSapService: Stopping SAP server process
08-25 13:19:48.299  6986  6986 V BluetoothSapService: Sap Service closeSapService in
08-25 13:19:48.299  6986  6986 V BluetoothSapService: Close listen Socket : 
08-25 13:19:48.299  6986  6986 V BluetoothSapService: Close rfcomm Socket : 
08-25 13:19:48.299  6986  6986 V BluetoothSapService: Close sapd  Socket : 
08-25 13:19:48.304  6986  6986 V BluetoothSapService: Sap Service closeSapService out
08-25 13:19:48.304  6986  6986 V BluetoothSapService: Sap Service onDestroy
08-25 13:19:48.304  6986  6986 V BluetoothSapService: Sap Service closeSapService in
08-25 13:19:48.304  6986  6986 V BluetoothSapService: Close listen Socket : 
08-25 13:19:48.305  6986  6986 V BluetoothSapService: Close rfcomm Socket : 
08-25 13:19:48.305  6986  6986 V BluetoothSapService: Close sapd  Socket : 
08-25 13:19:48.306  6986  6986 V BluetoothSapService: Sap Service closeSapService out
,08-25 13:19:49.102  6986  7476 D bt_hci_bdroid: cleanup
,08-25 13:19:49.109  6986  7543 I bt_lpm  : LPM is already off!!!
08-25 13:19:49.109  6986  7570 I bt_userial_mct: exiting userial_read_thread
08-25 13:19:49.109  6986  7570 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 13:19:49.111  6986  7541 W bt-btif : ag scb idx 1 not allocated
08-25 13:19:49.111  6986  7541 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:49.111  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 13:19:49.112  6986  7541 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:19:49.112  6986  7541 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 13:19:49.116  6986  7476 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 13:19:49.116  6986  7543 I bt_vendor: hw_epilog_process
08-25 13:19:49.118  6986  7476 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-25 13:19:49.118  6986  7476 D bt_userial_mct: userial_close
08-25 13:19:49.118  6986  7476 E bt_userial_mct: pthread_join() FAILED result:3
,08-25 13:19:49.118  6986  7476 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 13:19:49.126  6986  7476 D bt_hci_bdroid: set_power 0
08-25 13:19:49.126  6986  7476 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 13:19:49.126  6986  7476 I bt_vendor: bluetooth satus is on
08-25 13:19:49.126  6986  7476 I bt_vendor: bt-vendor : resetting BT status
08-25 13:19:49.126  6986  7476 I bt_vendor: Starting hciattach daemon
08-25 13:19:49.126  6986  7476 I bt_vendor: try to set false
,08-25 13:19:49.134  6986  7476 I bt_vendor: Starting hciattach daemon
08-25 13:19:49.134  6986  7476 I bt_vendor: try to set false
08-25 13:19:49.136  6986  7476 I bt_vendor: cleanup
08-25 13:19:49.136  6986  7541 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 13:19:49.137  6986  7476 I GKI_LINUX: GKI_exit_task 0 done
08-25 13:19:49.137  6986  7476 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 13:19:49.138  6986  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 13:19:49.144  6986  6986 D HeadsetService: Received stop request...Stopping profile...
,08-25 13:19:49.149  6986  6986 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 13:19:49.149  6986  6986 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 13:19:49.149  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:49.152  6986  7504 D HeadsetStateMachine: Exit Disconnected: -1
08-25 13:19:49.153  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:49.153  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 13:19:49.154  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:49.154  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:49.154  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-25 13:19:49.158  6986  6986 D A2dpService: Received stop request...Stopping profile...
,08-25 13:19:49.160  6986  7533 D A2dpStateMachine: Exit Disconnected: -1
08-25 13:19:49.163  6986  7472 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 13:19:49.164  6986  6986 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 13:19:49.166  6986  6986 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 13:19:49.166  6986  6986 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 13:19:49.166  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:49.168  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-25 13:19:49.168  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 13:19:49.168  6986  6986 D HidService: Received stop request...Stopping profile...
08-25 13:19:49.169  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:49.171  6986  6986 D HealthService: Received stop request...Stopping profile...
08-25 13:19:49.171  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
,08-25 13:19:49.174  6986  6986 D HeadsetStateMachine: Unbinding service...
08-25 13:19:49.177  6986  6986 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 13:19:49.177  6986  6986 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 13:19:49.177  6986  6986 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 13:19:49.177  6986  6986 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 13:19:49.177  6986  6986 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 13:19:49.177  6986  6986 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 13:19:49.177  6986  6986 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 13:19:49.179  6986  6986 D PanService: Received stop request...Stopping profile...
08-25 13:19:49.179  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:49.180  6986  6986 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 13:19:49.181  6986  6986 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 13:19:49.181  6986  6986 D BtGatt.GattService: stop()
08-25 13:19:49.181  6986  6986 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 13:19:49.182  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
,08-25 13:19:49.186  6986  6986 D BluetoothMapService: Received stop request...Stopping profile...
08-25 13:19:49.186  6986  6986 D BluetoothMapService: stop()
08-25 13:19:49.188  6986  6986 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 13:19:49.188  6986  6986 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 13:19:49.189  6986  6986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e8f2ab
08-25 13:19:49.190  6986  6986 I BluetoothA2dpServiceJni: cleanupNative
08-25 13:19:49.190  6986  7534 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 13:19:49.191  6986  6986 I GKI_LINUX: GKI_exit_task 2 done
08-25 13:19:49.191  6986  6986 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 13:19:49.191  6986  6986 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 13:19:49.191  6986  6986 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 13:19:49.191  6986  6986 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 13:19:49.192  6986  6986 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 13:19:49.192  6986  6986 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 13:19:49.192  6986  6986 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 13:19:49.192  6986  6986 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 13:19:49.196  6986  6986 V BluetoothMapService: Handler(): got msg=4
08-25 13:19:49.196  6986  6986 D BluetoothMapService: MAP Service closeService in
08-25 13:19:49.196  6986  6986 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 13:19:49.196  6986  6986 V BluetoothMapService: MAP Service closeService out
,08-25 13:19:49.199  6986  7472 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 13:19:49.199  6986  7472 D BluetoothAdapterProperties: Setting state to 10
08-25 13:19:49.199  6986  7472 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 13:19:49.201  6986  6986 D BluetoothMapService: cleanup()
08-25 13:19:49.201  6986  6986 D BluetoothMapService: MAP Service closeService in
08-25 13:19:49.201  6986  6986 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 13:19:49.201  6986  6986 V BluetoothMapService: MAP Service closeService out
08-25 13:19:49.202  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:49.203  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 13:19:49.203  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 13:19:49.204  6986  7472 I BluetoothAdapterState: Entering OffState
08-25 13:19:49.204  6892  6908 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 13:19:49.206  6892  6908 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:49.206  6892  6908 D BluetoothMap: onBluetoothStateChange: up=false
08-25 13:19:49.207  1839  2721 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:49.207  1839  2446 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 13:19:49.210  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 13:19:49.210  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:49.211  6892  6908 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 13:19:49.212  6892  6908 D BluetoothPan: onBluetoothStateChange on: false
08-25 13:19:49.213  6892  6908 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 13:19:49.213  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:19:49.214  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 13:19:49.214  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 13:19:49.216  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 13:19:49.216  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 13:19:49.216  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@f26cce1 mBinding = false
08-25 13:19:49.217  1035  1117 D BluetoothManagerService: Sending unbind request.
08-25 13:19:49.221  6986  7476 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 13:19:49.224  6986  6986 I GKI_LINUX: GKI_exit_task 1 done
08-25 13:19:49.225  6986  6986 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 13:19:49.225  6986  6986 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 13:19:49.225  6986  6986 I art     : --- WEIRD: removing null entry 248
08-25 13:19:49.225  6986  6986 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 13:19:49.225  6986  6986 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 13:19:49.226  6986  6986 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 13:19:49.228  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 13:19:49.230  6986  6986 I art     : System.exit called, status: 0
08-25 13:19:49.230  6986  6986 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 13:19:49.249   327  1385 V AudioFlinger: 6986 died, releasing its sessions
08-25 13:19:49.249   327  1385 V AudioFlinger:  pid 1839 @ 0
08-25 13:19:49.249   327  1385 V AudioFlinger:  pid 3424 @ 1
08-25 13:19:49.249   327  1385 V AudioFlinger:  pid 3424 @ 2
,08-25 13:19:49.253  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 13:19:49.253  1927  2086 D LGBluetoothAPIService: Message: 101
08-25 13:19:49.253  1927  2086 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-25 13:19:49.254  1927  2086 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 13:19:49.254  1927  2086 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,08-25 13:19:49.257  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 13:19:49.295  1035  1771 I ActivityManager: Process com.android.bluetooth (pid 6986) has died
08-25 13:19:49.295  1035  1771 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-25 13:19:49.296  1035  1771 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-25 13:19:49.301  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 13:19:49.303  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:49.304  1927  2086 D LGBluetoothAPIService: Message: 2
08-25 13:19:49.304  1927  2086 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-25 13:19:49.306  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:49.307  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:49.310  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 13:19:49.310  6892  6892 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 13:19:49.315  1586  1586 D BluetoothAdapter: 313502162: getState() :  mService = null. Returning STATE_OFF
08-25 13:19:49.315  1586  1586 D BluetoothAdapter: 313502162: getState() :  mService = null. Returning STATE_OFF
08-25 13:19:49.316  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 13:19:49.370  1035  1560 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7665 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 13:19:49.372  6892  6892 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:19:49.425  7665  7665 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 13:19:49.425  7665  7665 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 13:19:49.425  7665  7665 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 13:19:49.426  7665  7665 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 13:19:49.445  7665  7665 D BluetoothAdapterApp: Loading JNI Library
,08-25 13:19:49.477  7665  7665 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3611b033 Instance Count = 1
,08-25 13:19:49.482  7665  7665 D BluetoothAdapterApp: onCreate
08-25 13:19:49.506  7665  7665 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 13:19:49.506  7665  7665 D ProfileConfigQcom: Adding HeadsetService
08-25 13:19:49.506  7665  7665 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 13:19:49.506  7665  7665 D ProfileConfigQcom: Adding A2dpService
08-25 13:19:49.506  7665  7665 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 13:19:49.507  7665  7665 D ProfileConfigQcom: Adding HidService
08-25 13:19:49.507  7665  7665 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-25 13:19:49.507  7665  7665 D ProfileConfigQcom: Adding HealthService
08-25 13:19:49.507  7665  7665 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 13:19:49.508  7665  7665 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 13:19:49.508  7665  7665 D ProfileConfigQcom: Adding PanService
08-25 13:19:49.509  7665  7665 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 13:19:49.509  7665  7665 D ProfileConfigQcom: Adding GattService
08-25 13:19:49.509  7665  7665 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 13:19:49.509  7665  7665 D ProfileConfigQcom: Adding BluetoothMapService
08-25 13:19:49.510  7665  7665 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 13:19:49.511  7665  7665 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 13:19:49.512  7665  7665 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:49.512  7665  7665 V BluetoothPbapReceiver: ***********state = 10
08-25 13:19:49.514  7665  7665 V LGMDMManagerInternal: Create singleton instance
08-25 13:19:49.594  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:19:49.600  7665  7665 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-25 13:19:49.600  7665  7665 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 13:19:49.601  6892  6892 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 13:19:49.604  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 13:19:49.604  1927  2086 D LGBluetoothAPIService: Message: 100
08-25 13:19:49.604  1927  2086 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 13:19:49.623  6892  6892 D BluetoothPermissionRequest: onReceive
,08-25 13:19:49.627  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 13:19:49.627  6892  6892 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 13:19:49.630  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 13:19:49.635  7665  7665 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 13:19:49.639  7665  7665 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:19:49.643  7665  7665 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-25 13:19:49.643  7665  7665 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-25 13:19:49.643  7665  7665 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:49.645  7665  7665 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:49.645  7665  7665 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 13:19:49.648  6964  6964 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 13:19:50.758   314   314 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-25 13:19:50.758   314   314 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-25 13:19:50.758   314   314 I rmt_storage: wakelock acquired: 1, error no: 42
08-25 13:19:50.759   314   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,08-25 13:19:50.934   314   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
08-25 13:19:50.934   314   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-25 13:19:50.934   314   913 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-25 13:19:50.934   314   913 I rmt_storage: 
,08-25 13:19:50.937   314   314 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,08-25 13:19:50.938   901   910 E Diag_Lib: [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
08-25 13:19:51.200  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:51.201  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:51.318  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-25 13:19:51.375  1035  1365 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 13:19:51.418  1035  1106 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7695 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 13:19:51.425  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 13:19:51.426  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-25 13:19:51.461  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 13:19:51.480  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 13:19:51.500  1035  1035 D administrator: Handling package changes for user 0
,08-25 13:19:51.511  7695  7695 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 13:19:51.576  7695  7695 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:51.576  7695  7695 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:51.601  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 13:19:51.601  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 13:19:51.635  1035  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:51.642  1035  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-25 13:19:51.652  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 13:19:51.653  2495  2495 V GmsNetworkLocationProvi: DISABLE
08-25 13:19:51.658  7695  7738 I Babel   : MmsConfig: mnc/mcc: 0/0
08-25 13:19:51.658  7695  7738 I Babel   : MmsConfig.loadMmsSettings
,08-25 13:19:51.664  7695  7738 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 13:19:51.664  7695  7738 I Babel   : MmsConfig.loadFromDatabase
,08-25 13:19:51.673  7695  7738 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-25 13:19:51.673  7695  7738 I Babel   : MmsConfig.loadFromResources
08-25 13:19:51.674  7695  7738 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 13:19:51.675  7695  7738 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 13:19:51.690  1035  1104 D LocationProviderProxy: applying state to connected service
,08-25 13:19:51.691  2495  2495 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-25 13:19:51.704  7695  7695 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:19:51.727  7695  7736 W AudioCapabilities: Unsupported mime audio/evrc
08-25 13:19:51.728  7695  7736 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 13:19:51.729  7695  7736 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:19:51.739  7695  7736 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-25 13:19:51.740  7695  7736 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 13:19:51.741  7695  7736 W AudioCapabilities: Unsupported mime audio/evrc
08-25 13:19:51.750  7695  7736 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 13:19:51.753  7695  7736 W VideoCapabilities: Unsupported mime video/divx
08-25 13:19:51.756  7695  7736 W VideoCapabilities: Unsupported mime video/divx311
08-25 13:19:51.758  7695  7736 W VideoCapabilities: Unsupported mime video/divx4
08-25 13:19:51.764  7695  7736 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 13:19:51.781  7695  7736 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 13:19:51.785  7695  7736 W AudioCapabilities: Unsupported mime audio/eac3
08-25 13:19:51.787  7695  7736 W AudioCapabilities: Unsupported mime audio/ac3
08-25 13:19:51.788  7695  7736 W AudioCapabilities: Unsupported mime audio/g726
08-25 13:19:51.789  7695  7736 W AudioCapabilities: Unsupported mime audio/wma-voice
08-25 13:19:51.790  7695  7736 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 13:19:51.791  7695  7736 W AudioCapabilities: Unsupported mime audio/adpcm
08-25 13:19:51.792  1035  1962 I art     : Explicit concurrent mark sweep GC freed 61819(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.591ms total 75.178ms
08-25 13:19:51.800  7695  7736 W VideoCapabilities: Unsupported mime video/theora
,08-25 13:19:51.804  7075  7075 I AppUp4:CustModeStarterReceiver: onReceive
08-25 13:19:51.806  1804  7742 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-25 13:19:51.806  1804  7742 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-25 13:19:51.818  7695  7736 W VideoCapabilities: Unsupported mime video/mjpg
08-25 13:19:51.821  7075  7075 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1108d325
08-25 13:19:51.821  7075  7075 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 13:19:51.821  7075  7075 D AppUp4:CustFacade: isPhone : true
08-25 13:19:51.822  7075  7075 D AppUp4:CustModeStarterReceiver: begin check event
08-25 13:19:51.822  7075  7075 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-25 13:19:51.822  1804  5258 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-25 13:19:51.852  1035  1926 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7745 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-25 13:19:51.893  1035  1703 I ActivityManager: Killing 6665:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-25 13:19:51.902  7745  7745 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:51.902  7745  7745 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 13:19:51.902  7745  7745 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 13:19:51.903  7745  7745 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-25 13:19:51.904  6946  6946 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-25 13:19:51.904  7745  7745 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 13:19:51.904  6946  6946 W System.err: android.os.DeadObjectException
08-25 13:19:51.904  6946  6946 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 13:19:51.904  6946  6946 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 13:19:51.904  6946  6946 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 13:19:51.904  6946  6946 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 13:19:51.904  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 13:19:51.904  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 13:19:51.904  6946  6946 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 13:19:51.904  6946  6946 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 13:19:51.904  6946  6946 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 13:19:51.904  6946  6946 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 13:19:51.904  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:19:51.904  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:19:51.904  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 13:19:51.904  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 13:19:51.904  6946  6946 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 13:19:51.905  6946  6946 W System.err: android.os.DeadObjectException
08-25 13:19:51.905  6946  6946 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 13:19:51.905  6946  6946 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 13:19:51.905  6946  6946 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 13:19:51.905  6946  6946 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 13:19:51.905  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 13:19:51.905  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 13:19:51.905  6946  6946 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 13:19:51.905  6946  6946 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 13:19:51.905  6946  6946 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 13:19:51.905  6946  6946 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 13:19:51.905  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:19:51.905  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:19:51.905  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 13:19:51.905  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 13:19:51.905  6946  6946 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 13:19:51.906  6946  6946 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-25 13:19:52.103  1035  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_6665/cgroup.procs: No such file or directory
08-25 13:19:52.104  1035  1944 W ActivityManager:, Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-25 13:19:52.109  6946  6946 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 13:19:52.110  6946  6946 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 13:19:52.133  7745  7745 I SystemConfig: BUILD Country: EU
,08-25 13:19:52.133  7745  7745 I SystemConfig: BUILD Operator: OPEN
08-25 13:19:52.151  1035  1405 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-25 13:19:52.175  1035  2018 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 13:19:52.176  6946  6946 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-25 13:19:52.179  1035  1772 I ActivityManager: Killing 6946:com.lge.qremote/u0a112 (adj 15): empty #17
08-25 13:19:52.199   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 19.440ms
,08-25 13:19:52.218   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 18.141ms
,08-25 13:19:52.236   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 16.373ms
,08-25 13:19:52.247  1035  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_6946/cgroup.procs: No such file or directory
,08-25 13:19:52.281  7767  7767 D UEI.SmartControl: Quickset Services start...
08-25 13:19:52.282  1035  1772 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7786 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-25 13:19:52.283  7767  7767 I UEI.SmartControl: Manufacture = LGE
08-25 13:19:52.283  7767  7767 D UEI.SmartControl: Id = LGNevo
,08-25 13:19:52.287  7745  7773 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 13:19:52.287  7745  7773 I SystemConfig: existFile = false
08-25 13:19:52.287  7745  7773 I SystemConfig: canReadFile = false
08-25 13:19:52.287  7745  7773 I SystemConfig: systemFeature RCS result false
08-25 13:19:52.287  7745  7773 D SystemConfig: refreshRcsSupport() :false
08-25 13:19:52.289  7767  7767 D UEI.SmartControl: File observer start...
08-25 13:19:52.289  7767  7767 E UEI.SmartControl: IR Port is disabled: false
08-25 13:19:52.290  7767  7767 D UEI.SmartControl: Starting file observer...
08-25 13:19:52.290  7767  7767 D UEI.SmartControl: Extracting JNI libs...
08-25 13:19:52.290  7767  7767 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-25 13:19:52.346  7786  7786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:52.347  7786  7786 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 13:19:52.347  7786  7786 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 13:19:52.347  7786  7786 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 13:19:52.357  7767  7767 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-25 13:19:52.357  7767  7767 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 13:19:52.357  7767  7767 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-25 13:19:52.380  7767  7767 I UEI.SmartControl: --- Selecting new region: 6
,08-25 13:19:52.381  7767  7767 I UEI.SmartControl: Model = LG-D855
08-25 13:19:52.382  7767  7767 D UEI.SmartControl: QS Service created
08-25 13:19:52.392  7767  7767 I UEI.SmartControl: Service initServices...
,08-25 13:19:52.395  7767  7767 D UEI.SmartControl: QS start get config
08-25 13:19:52.434  7767  7767 D UEI.SmartControl: Loading JNI Libs...
,08-25 13:19:52.453  7786  7786 I AppConfig: Total System Memory = 2995761152
,08-25 13:19:52.462  7786  7786 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-25 13:19:52.545  1035  1980 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7806 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 13:19:52.546  1035  1980 I ActivityManager: Killing 7107:com.lge.email/u0a23 (adj 15): empty #17
,08-25 13:19:52.679  1035  1703 W libprocessgroup: failed to open /acct/uid_10023/pid_7107/cgroup.procs: No such file or directory
,08-25 13:19:52.776  7767  7767 I UEI.SmartControl: Supports setup maps: true
,08-25 13:19:52.781  7767  7767 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 13:19:52.781  7767  7767 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 13:19:52.781  7767  7767 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 13:19:52.781  7767  7767 I UEI.SmartControl: ### init IR Blaster...
08-25 13:19:52.787  7767  7767 D serial_port: Configuring serial port
08-25 13:19:52.796  7767  7767 E UEI.SmartControl: UEIBLaster setting for 616
08-25 13:19:52.796  7767  7767 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 13:19:52.796  7767  7767 I UEI.SmartControl: configuring settings for MAXQ616
08-25 13:19:52.797  7767  7767 I UEI.SmartControl: Get version...
,08-25 13:19:52.814  7767  7833 D UEI.SmartControl: serial port data available: 21
,08-25 13:19:52.822  7806  7806 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 13:19:52.842  7767  7767 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 13:19:52.843  7767  7767 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 13:19:52.843  7767  7767 I UEI.SmartControl: QS saving settings...
,08-25 13:19:52.844  7767  7767 D UEI.SmartControl: IR Blaster version: 25672567
08-25 13:19:52.860  7767  7833 D UEI.SmartControl: serial port data available: 4
08-25 13:19:52.892  7767  7850 I UEI.SmartControl: Device manager: loading config....
08-25 13:19:52.893  7767  7850 D UEI.SmartControl: ----------- loading internal config...
,08-25 13:19:52.904  7767  7850 E UEI.SmartControl: Loading SETTINGS...
08-25 13:19:52.905  7767  7767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 13:19:52.908  7767  7767 E UEI.SmartControl: Services init done
08-25 13:19:52.908  7767  7767 D UEI.SmartControl: QS Service init finished
,08-25 13:19:52.910  7767  7767 D UEI.SmartControl: QS Service version name: 2.1.91
,08-25 13:19:52.910  7767  7767 D UEI.SmartControl: QS Service version code: 201091
08-25 13:19:52.911  7767  7767 D UEI.SmartControl: Service requested: Control
08-25 13:19:52.914  7767  7850 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 13:19:52.916  1035  1560 I ActivityManager: Killing 7003:com.lge.formmanager/u0a26 (adj 15): empty #17
08-25 13:19:52.918  7767  7849 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 13:19:52.918  7767  7849 D UEI.SmartControl: -----service ready thread exits
08-25 13:19:52.946  7806  7806 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:52.946  7806  7806 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 13:19:52.987  1035  1908 W libprocessgroup: failed to open /acct/uid_10026/pid_7003/cgroup.procs: No such file or directory
08-25 13:19:52.987  7767  7767 D UEI.SmartControl: Internal service binding...
08-25 13:19:53.001  7806  7806 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 13:19:53.038  7806  7806 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 13:19:53.040  7806  7806 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 13:19:53.055  1035  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{19299a7b type 2 when 199295 com.google.android.gms} when 199295
,08-25 13:19:53.061  7806  7806 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-25 13:19:53.062  7806  7806 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-25 13:19:53.098  1035  1703 I ActivityManager: Killing 4809:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-25 13:19:53.167  1035  1997 W libprocessgroup: failed to open /acct/uid_1000/pid_4809/cgroup.procs: No such file or directory
,08-25 13:19:53.178  2835  2850 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-25 13:19:53.180  2835  2850 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@36399380 on behalf of 7806
08-25 13:19:53.186  5055  7860 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-25 13:19:53.220  1035  1051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7861 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 13:19:53.258  7806  7806 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-25 13:19:53.287  7806  7806 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-25 13:19:53.330  7861  7861 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 13:19:53.354  7861  7861 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-25 13:19:53.354  7861  7861 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 13:19:53.354  7861  7861 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-25 13:19:53.354  7861  7861 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 13:19:53.354  7861  7861 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-25 13:19:53.354  7861  7861 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-25 13:19:53.372   323  7883 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-25 13:19:53.374  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 13:19:53.380  1035  1703 I ActivityManager: Killing 7137:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-25 13:19:53.446  1035  1771 W libprocessgroup: failed to open /acct/uid_10046/pid_7137/cgroup.procs: No such file or directory
,08-25 13:19:53.617  1035  1560 V SIM_STK : Menu title from STK is T-Mobile
,08-25 13:19:53.645  5055  7860 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 459 ms] updated apps [took 459 ms] 
,08-25 13:19:54.217  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:19:54.217  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b98b26f added. We now have 6 listener(s)
08-25 13:19:54.218  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:19:54.230  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:54.230  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@373bfb7c added. We now have 7 listener(s)
08-25 13:19:54.230  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:54.231  6766  6845 I System.out: IsBluetoothEnabled
08-25 13:19:54.232  1035  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:54.232  1035  1944 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 13:19:54.233  1035  1117 D BluetoothManagerService: Message: 2
08-25 13:19:54.237  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:54.239  1035  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:54.239  1035  1703 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 13:19:54.266  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 13:19:54.266  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:54.275  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-25 13:19:54.286  1035  1117 D BluetoothManagerService: Message: 1
08-25 13:19:54.286  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 13:19:54.326  1035  1117 D BluetoothManagerService: Message: 20
08-25 13:19:54.326  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b9399d:true
,08-25 13:19:54.330  7665  7665 D BluetoothAdapterState: make
08-25 13:19:54.337  7665  7665 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 13:19:54.337  7665  7665 I bluedroid-qcom: init
08-25 13:19:54.338  7665  7890 I BluetoothAdapterState: Entering OffState
,08-25 13:19:54.341  7665  7665 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 13:19:54.342  7665  7665 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 13:19:54.342  7665  7665 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 13:19:54.342  7665  7665 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 13:19:54.342  7665  7665 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 13:19:54.344  7665  7665 I bluedroid-qcom: get_profile_interface socket
08-25 13:19:54.344  7665  7665 I bluedroid-qcom: get_profile_interface map_client
08-25 13:19:54.345  7665  7894 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 13:19:54.338  7893  7893 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:54.338  7893  7893 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:54.357  7665  7894 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 13:19:54.361  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-25 13:19:54.361  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 13:19:54.369  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 13:19:54.370  1035  1117 D BluetoothManagerService: Message: 40
,08-25 13:19:54.371  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 13:19:54.371  7665  7894 D BluetoothAdapterProperties: Name is: G3
08-25 13:19:54.371  7893  7893 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 13:19:54.371  7893  7893 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 13:19:54.371  7893  7893 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 13:19:54.372  7665  7681 I bluedroid-qcom: config_hci_snoop_log
08-25 13:19:54.373  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 13:19:54.373  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 13:19:54.374  7893  7893 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-25 13:19:54.381  7893  7893 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
,08-25 13:19:54.381  7893  7893 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 13:19:54.382  7665  7890 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 13:19:54.382  7665  7890 D BluetoothAdapterProperties: Setting state to 11
,08-25 13:19:54.382  7665  7890 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 13:19:54.383  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:54.384  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 13:19:54.384  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-25 13:19:54.385  7665  7890 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 13:19:54.387  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:54.388  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 13:19:54.392  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:54.396  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 13:19:54.399  7665  7890 D BluetoothBondStateMachine: make
08-25 13:19:54.400  7665  7665 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 13:19:54.400  7665  7665 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:54.401  7665  7665 V BluetoothPbapReceiver: ***********state = 11
08-25 13:19:54.403  7665  7911 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 13:19:54.403  7665  7890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
,08-25 13:19:54.403  7665  7890 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 13:19:54.404  7665  7890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:54.404  7665  7890 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 13:19:54.404  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:19:54.404  7665  7890 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 13:19:54.409  7665  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:54.420  6892  6892 D BluetoothPermissionRequest: onReceive
,08-25 13:19:54.422  7665  7665 D HeadsetService: Received start request. Starting profile...
08-25 13:19:54.422  7665  7665 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 13:19:54.423  7665  7665 D LGBluetoothHfpAdapter: Version 1.6
08-25 13:19:54.425  7665  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:54.426  7665  7665 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 13:19:54.427  7665  7665 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 13:19:54.427  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 13:19:54.428  7665  7665 D HeadsetStateMachine: make
08-25 13:19:54.432  7665  7890 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 13:19:54.437  7665  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:54.441  7665  7890 E BluetoothAdapterService: File transfer profiles supported!!
08-25 13:19:54.446  7665  7890 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 13:19:54.450  7665  7890 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 13:19:54.465  7665  7665 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 13:19:54.465  7665  7665 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 13:19:54.466  7665  7890 V LGMDMManager: Create singleton instance
08-25 13:19:54.468  7665  7890 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 13:19:54.470  7665  7665 D HeadsetStateMachine: max_hf_connections = 1
08-25 13:19:54.470  7665  7665 I bluedroid-qcom: get_profile_interface handsfree
08-25 13:19:54.473  7665  7665 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 13:19:54.473   327  1385 V AudioPolicyService: registerClient() client 0xb15081c0, uid 1002
,08-25 13:19:54.473   327   327 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 13:19:54.473   327   327 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 13:19:54.473   327   327 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 13:19:54.474  7665  7665 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 13:19:54.474   327  2234 V AudioFlinger: registerClient() client 0xb14330a0, pid 7665
08-25 13:19:54.474   327  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:54.474   327  1380 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:54.475  1586  2146 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:54.475  1586  2146 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:54.475   327  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:54.475   327  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:54.475  1586  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:54.475  1586  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-25 13:19:54.475  1035  1771 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:54.475  1035  1771 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:54.475  1035  1771 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:54.475  1035  1771 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:54.475  7665  7909 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:54.475  3424  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:54.475  3424  3440 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:54.475  3424  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:54.475  3424  3440 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:54.476  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 13:19:54.476  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 13:19:54.476  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:54.476  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 13:19:54.476  7665  7909 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 13:19:54.476  7665  7909 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 13:19:54.476  7665  7909 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 13:19:54.476  7665  7665 V ToneGenerator: Create Track: 0xb4928080
08-25 13:19:54.476  7665  7665 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 13:19:54.476  7665  7665 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 13:19:54.476   327  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 13:19:54.476   327  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 13:19:54.476   327  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 13:19:54.476   327  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 13:19:54.477   327   327 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 13:19:54.477   327  2234 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 13:19:54.477   327  2234 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 13:19:54.477   327  2234 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 13:19:54.477   327  2234 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 13:19:54.477  7665  7665 V AudioSystem: getLatency() output 2, latency 50
08-25 13:19:54.477  7665  7665 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 13:19:54.477  7665  7665 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 13:19:54.478   327  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 13:19:54.478   327  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 13:19:54.478   327  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 13:19:54.478   327  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 13:19:54.478   327  1386 V AudioFlinger: createTrack() lSessionId: 21
08-25 13:19:54.479  7665  7665 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,08-25 13:19:54.481   327  1385 V AudioFlinger: acquiring 21 from 7665, for 7665
,08-25 13:19:54.481   327  1385 V AudioFlinger:  added new entry for 21
08-25 13:19:54.481  7665  7665 V ToneGenerator: ToneGenerator INIT OK, time: 200736
08-25 13:19:54.481  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:54.482  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:54.483  7665  7915 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 13:19:54.483  7665  7915 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 13:19:54.484  7665  7915 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 13:19:54.484  7665  7915 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 13:19:54.484   327   327 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7665
08-25 13:19:54.484  7665  7665 D A2dpService: Received start request. Starting profile...
08-25 13:19:54.484   327   327 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 13:19:54.484   327   327 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 13:19:54.484   327   327 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 13:19:54.484   327   327 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 13:19:54.484   327   327 V voice   : voice_set_parameters: exit with code(0)
08-25 13:19:54.484   327   327 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 13:19:54.484   327   327 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 13:19:54.485   327   327 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 13:19:54.485   327   327 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 13:19:54.485   327   327 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 13:19:54.485   327   327 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 13:19:54.485  7665  7915 V ToneGenerator: ToneGenerator destructor
08-25 13:19:54.485  7665  7665 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 13:19:54.485  7665  7915 V ToneGenerator: stopTone
08-25 13:19:54.485  7665  7915 V ToneGenerator: Delete Track: 0xb4928080
08-25 13:19:54.486  7665  7665 V Avrcp   : make
08-25 13:19:54.487  7665  7665 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 13:19:54.487  7665  7665 I bluedroid-qcom: get_profile_interface avrcp
08-25 13:19:54.487  7665  7915 V AudioTrack: ~AudioTrack, releasing session id from 7665 on behalf of 7665
08-25 13:19:54.488   327  1385 V AudioFlinger: releasing 21 from 7665 for 7665
08-25 13:19:54.488   327  1385 V AudioFlinger:  decremented refcount to 0
08-25 13:19:54.488   327  1385 V AudioFlinger: purging stale effects
08-25 13:19:54.488   327  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 13:19:54.488   327  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 13:19:54.488   327  1385 V AudioFlinger: PlaybackThread::Track destructor
08-25 13:19:54.488   327  1385 V AudioFlinger: removeClient_l() pid 7665, calling pid 327
08-25 13:19:54.488   327  1274 V AudioPolicyService: AudioCommandThread() waking up
08-25 13:19:54.488   327  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 13:19:54.488   327  1274 V AudioPolicyManager: releaseOutput() 2
08-25 13:19:54.488   327  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 13:19:54.497  7665  7665 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 13:19:54.498  7665  7665 E AudioManager: No RCC entry present to update
08-25 13:19:54.499  7665  7665 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 13:19:54.502  7665  7665 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-25 13:19:54.504  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 13:19:54.504  7665  7665 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 13:19:54.508  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 13:19:54.634  1035  1772 V SIM_STK : Menu title from STK is T-Mobile
08-25 13:19:54.634  1035  1772 V SIM_STK : Menu title from STK is T-Mobile
,08-25 13:19:54.707  1035  1997 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 13:19:54.716  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-25 13:19:54.720  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 13:19:54.720  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 13:19:54.721  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 13:19:54.721  7665  7665 I BluetoothA2dpServiceJni: classInitNative
08-25 13:19:54.721  7665  7665 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 13:19:54.721  7665  7665 D A2dpStateMachine: make
08-25 13:19:54.725  7665  7665 I bluedroid-qcom: get_profile_interface a2dp
08-25 13:19:54.726  7665  7920 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 13:19:54.735  7665  7665 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 13:19:54.735  7665  7665 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-25 13:19:54.739  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
,08-25 13:19:54.739  7665  7919 D A2dpStateMachine: Enter Disconnected: -2
,08-25 13:19:54.743  7665  7665 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 13:19:54.746  7665  7665 D HidService: Received start request. Starting profile...
08-25 13:19:54.746  7665  7665 I bluedroid-qcom: get_profile_interface hidhost
08-25 13:19:54.747  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:54.748  7665  7665 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 13:19:54.750  7665  7665 D HealthService: Received start request. Starting profile...
08-25 13:19:54.752  7665  7665 I bluedroid-qcom: get_profile_interface health
08-25 13:19:54.753  7665  7665 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 13:19:54.753  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:54.754  7665  7665 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 13:19:54.757  7665  7665 D PanService: Received start request. Starting profile...
,08-25 13:19:54.757  7665  7665 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 13:19:54.757  7665  7665 I bluedroid-qcom: get_profile_interface pan
08-25 13:19:54.766  7665  7665 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 13:19:54.766  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:54.773  7665  7665 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-25 13:19:54.781  7665  7665 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 13:19:54.781  7665  7665 D BtGatt.GattService: Received start request. Starting profile...
08-25 13:19:54.781  7665  7665 D BtGatt.GattService: start()
08-25 13:19:54.781  7665  7665 I bluedroid-qcom: get_profile_interface gatt
08-25 13:19:54.782  7665  7665 D BtGatt.AdvertiseManager: advertise manager created
08-25 13:19:54.791  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
,08-25 13:19:54.793  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
,08-25 13:19:54.793  7665  7665 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 13:19:54.794  7665  7665 V BluetoothMapService: BluetoothMapBinder()
08-25 13:19:54.795  7665  7665 D BluetoothMapService: Received start request. Starting profile...
08-25 13:19:54.795  7665  7665 D BluetoothMapService: start()
08-25 13:19:54.799  7665  7665 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 13:19:54.799  7665  7665 D BluetoothMapEmailAppObserver: createReceiver()
08-25 13:19:54.800  7665  7665 D BluetoothMapEmailAppObserver: initObservers()
08-25 13:19:54.800  7665  7665 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 13:19:54.810  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:54.810  7665  7665 D HeadsetStateMachine: Proxy object connected
08-25 13:19:54.811  7665  7665 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 13:19:54.811  7665  7665 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-25 13:19:54.818  7665  7665 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:54.819  7665  7915 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 13:19:54.820  7665  7915 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 13:19:54.821  7665  7915 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 13:19:54.824  7665  7665 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 13:19:54.827  7665  7665 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:19:54.836  7665  7665 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:54.842  7665  7665 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:54.843  7665  7665 V PanService: [BTUI] SIM Extra State :ABSENT
,08-25 13:19:54.850  7665  7665 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 13:19:54.855  7665  7665 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 13:19:54.856  7665  7665 V BluetoothMapService: Handler(): got msg=1
,08-25 13:19:54.857  7665  7665 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 13:19:54.857  7665  7890 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 13:19:54.858  7665  7665 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 13:19:54.858  7665  7890 I bluedroid-qcom: enable
08-25 13:19:54.858  7665  7665 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:54.858  7665  7665 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:54.858  7665  7665 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 13:19:54.858  7665  7890 I bt_hci_bdroid: init
08-25 13:19:54.858  7665  7930 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 13:19:54.858  7665  7930 I bt-btu  : btu_task pending for preload complete event
08-25 13:19:54.865  7665  7890 I bt_vendor: bt-vendor : init
08-25 13:19:54.866  7665  7890 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 13:19:54.866  7665  7890 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 13:19:54.866  7665  7890 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 13:19:54.866  7665  7890 D bt_userial_mct: userial_init
08-25 13:19:54.868  7665  7890 D bt_hci_bdroid: set_power 1
08-25 13:19:54.868  7665  7890 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 13:19:54.868  7665  7890 I bt_vendor: Starting hciattach daemon
,08-25 13:19:54.868  7665  7890 I bt_vendor: try to set true
08-25 13:19:54.868  7933  7933 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:54.868  7933  7933 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:54.908  7934  7934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 13:19:55.042  7943  7943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 13:19:55.057  7944  7944 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 13:19:55.083  7946  7946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 13:19:55.108  7947  7947 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 13:19:55.122  7948  7948 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-25 13:19:55.133  7949  7949 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 13:19:55.156  7951  7951 I libmdmdetect: ESOC framework not supported
,08-25 13:19:55.157  7951  7951 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-25 13:19:55.164  7951  7951 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 13:19:55.164  7951  7951 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 13:19:55.164  7951  7951 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 13:19:55.164  7951  7951 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 13:19:55.164  7951  7951 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 13:19:55.164  7951  7951 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 13:19:55.164  7951  7951 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 13:19:55.204  7951  7952 E QC-QMI  : qmi_client [7951] 15: failed to locate client data
08-25 13:19:55.205   463   463 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 13:19:55.205   463   463 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-25 13:19:55.258  7953  7953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 13:19:55.286  7954  7954 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 13:19:55.326  7665  7890 I bt_vendor: bluetooth satus is on
08-25 13:19:55.326  7665  7890 D bt_hci_bdroid: preload
08-25 13:19:55.327  7665  7932 D bt_userial_mct: userial_open(port:0)
08-25 13:19:55.327  7665  7932 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 13:19:55.332  7665  7932 I bt_vendor: Done intiailizing UART
,08-25 13:19:55.336  7665  7932 I bt_vendor: Done intiailizing UART
,08-25 13:19:55.336  7665  7932 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-25 13:19:55.337  7665  7932 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 13:19:55.337  7665  7956 D bt_userial_mct: Entering userial_read_thread()
,08-25 13:19:55.338  7665  7930 I bt-btu  : btu_task received preload complete event
08-25 13:19:55.339  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 13:19:55.339  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 13:19:55.343  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 13:19:55.350  7665  7930 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 13:19:55.350  7665  7930 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 13:19:55.350  7665  7930 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-25 13:19:55.350  7665  7930 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 13:19:55.351  7665  7930 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 13:19:55.447  7665  7930 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 13:19:55.447  7665  7930 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f4061 
,08-25 13:19:55.447  7665  7930 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f4061 
,08-25 13:19:55.472  7665  7894 E bt-btif : Calling BTA_HhEnable
08-25 13:19:55.472  7665  7894 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 13:19:55.472  7665  7894 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 13:19:55.475  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 13:19:55.475  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 13:19:55.475  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 13:19:55.477  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 13:19:55.477  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 13:19:55.478  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 13:19:55.478  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 13:19:55.478  7665  7894 D BluetoothAdapterProperties: Name is: G3
08-25 13:19:55.479  7665  7894 D BluetoothAdapterProperties: Scan Mode:20
08-25 13:19:55.480  7665  7894 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 13:19:55.480  7665  7894 D bt_hci_bdroid: postload
08-25 13:19:55.481  7665  7932 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:55.481  7665  7932 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:55.482  7665  7894 D bte_conf: Device ID record 1 : primary
08-25 13:19:55.482  7665  7894 D bte_conf:   vendorId            = 00c4
08-25 13:19:55.482  7665  7894 D bte_conf:   vendorIdSource      = 0001
08-25 13:19:55.482  7665  7894 D bte_conf:   product             = 13a1
08-25 13:19:55.482  7665  7894 D bte_conf:   version             = 1000
08-25 13:19:55.482  7665  7894 D bte_conf:   clientExecutableURL = 
08-25 13:19:55.482  7665  7894 D bte_conf:   serviceDescription  = 
08-25 13:19:55.482  7665  7894 D bte_conf:   documentationURL    = 
08-25 13:19:55.482  7665  7894 D bte_conf: bte_load_did_conf no section named DID2.
08-25 13:19:55.483  7665  7930 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 13:19:55.483  7665  7932 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:55.487  7665  7890 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 13:19:55.487  7665  7890 D BluetoothAdapterProperties: ScanMode =  20
08-25 13:19:55.487  7665  7890 D BluetoothAdapterProperties: State =  11
08-25 13:19:55.487  7665  7890 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 13:19:55.487  7665  7890 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 13:19:55.488  7665  7890 D BluetoothAdapterProperties: Setting state to 12
08-25 13:19:55.488  7665  7890 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 13:19:55.493  7665  7894 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 13:19:55.494  7665  7894 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 13:19:55.488  7961  7961 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:55.488  7961  7961 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:55.497  1035  1117 D BluetoothManagerService: Message: 60
08-25 13:19:55.497  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 13:19:55.497  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 13:19:55.498  7665  7930 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:55.498  7665  7930 W bt-smp  : Plain text(LSB ~ MSB) = da 0f 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:55.498  7665  7930 W bt-smp  : Encrypted text(LSB ~ MSB) = 33 ff 06 69 39 bc 4c 3d b4 72 d5 c0 79 f5 8f a0 
08-25 13:19:55.498  7665  7932 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 13:19:55.498  7665  7930 W bt-btm  : Stopping oneshot timer
08-25 13:19:55.508  7665  7956 E bt_mct  : hci lib postload completed
,08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:55.536  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:55.546  7665  7930 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:55.546  7665  7930 W bt-smp  : Plain text(LSB ~ MSB) = 82 5c 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:55.546  7665  7930 W bt-smp  : Encrypted text(LSB ~ MSB) = 67 4e 3b c2 ba 3a b0 f6 dc 53 3e cf a0 ed e4 f0 
08-25 13:19:55.546  7665  7930 W bt-btm  : Stopping oneshot timer
08-25 13:19:55.546  7665  7890 I BluetoothAdapterState: Entering On State
08-25 13:19:55.549  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:19:55.566  7665  7930 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:55.566  7665  7930 W bt-smp  : Plain text(LSB ~ MSB) = 0d 77 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:55.566  7665  7930 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f d9 cb 11 74 21 06 36 36 c5 d2 72 30 e5 a0 3a 
,08-25 13:19:55.569  7665  7930 W bt-btm  : Stopping oneshot timer
08-25 13:19:55.570  7665  7890 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 13:19:55.570  7665  7890 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 13:19:55.570  7665  7890 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 13:19:55.572  7665  7890 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 13:19:55.576  6892  6908 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 13:19:55.599  7966  7966 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-25 13:19:55.603  7665  7890 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 13:19:55.604  7665  7930 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:55.604  7665  7930 W bt-smp  : Plain text(LSB ~ MSB) = df 77 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 13:19:55.604  7665  7930 W bt-smp  : Encrypted text(LSB ~ MSB) = f9 7e c6 73 26 11 fa 5c 69 e1 13 c5 d9 08 fe 55 
08-25 13:19:55.604  7665  7930 W bt-btm  : Stopping oneshot timer
08-25 13:19:55.608  6892  6908 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:55.612  6892  7577 D BluetoothMap: onBluetoothStateChange: up=true
08-25 13:19:55.615  1839  2721 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 13:19:55.618  7665  7930 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 13:19:55.618  7665  7930 W bt-smp  : Plain text(LSB ~ MSB) = 42 90 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-25 13:19:55.618  7665  7930 W bt-smp  : Encrypted text(LSB ~ MSB) = 0f 55 08 18 d0 04 3e fb 76 0e 00 2a c6 cb fd 4c 
08-25 13:19:55.618  7665  7930 W bt-btm  : Stopping oneshot timer
08-25 13:19:55.621  1839  1839 D BluetoothHeadset: Proxy object connected
08-25 13:19:55.622  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:55.630  1839  1839 D BluetoothHeadset: Proxy object connected
,08-25 13:19:55.637  6892  6892 D BluetoothA2dp: Proxy object connected
08-25 13:19:55.637  6892  6892 D A2dpProfile: Bluetooth service connected
08-25 13:19:55.644  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 13:19:55.647  6892  6892 D BluetoothHeadset: Proxy object connected
08-25 13:19:55.647  6892  6892 D HeadsetProfile: Bluetooth service connected
08-25 13:19:55.648  1035  1035 D BluetoothA2dp: Proxy object connected
,08-25 13:19:55.649  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:55.651  6892  6892 D BluetoothMap: Proxy object connected
08-25 13:19:55.651  6892  6892 D MapProfile: Bluetooth service connected
08-25 13:19:55.651  6892  6892 D BluetoothMap: getConnectedDevices()
08-25 13:19:55.651  1035  1035 D BluetoothHeadset: Proxy object connected
08-25 13:19:55.651  6892  6908 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 13:19:55.654  7665  7909 V BluetoothMapService: getConnectedDevices()
08-25 13:19:55.656  6892  6892 D BluetoothInputDevice: Proxy object connected
08-25 13:19:55.656  6892  6892 D HidProfile: Bluetooth service connected
08-25 13:19:55.657  6892  6910 D BluetoothPan: onBluetoothStateChange on: true
08-25 13:19:55.657  6892  6910 D BluetoothPan: onBluetoothStateChange call bindService
08-25 13:19:55.662  6892  6892 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:19:55.663  6892  6892 D PanProfile: Bluetooth service connected
08-25 13:19:55.663  6892  6908 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 13:19:55.666  1839  2446 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:55.669  1839  1839 D BluetoothHeadset: Proxy object connected
08-25 13:19:55.671  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 13:19:55.671  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 13:19:55.672  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 13:19:55.674  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.674  1927  2086 D LGBluetoothAPIService: Message: 1
,08-25 13:19:55.674  1927  2086 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 13:19:55.675  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 13:19:55.674  1927  2086 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
,08-25 13:19:55.675  1927  2086 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 13:19:55.678  1035  1117 D BluetoothManagerService: Message: 40
08-25 13:19:55.678  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 13:19:55.682  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:55.687  7665  7665 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.687  7665  7665 D BluetoothMapService: STATE_ON
08-25 13:19:55.695  6892  6892 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-25 13:19:55.697  6892  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 13:19:55.703  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:55.703  7665  7665 V BluetoothPbapService: Pbap Service onCreate
08-25 13:19:55.703  7665  7665 V BluetoothPbapService: Starting PBAP service
08-25 13:19:55.704  7665  7665 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 13:19:55.704  7665  7665 V BluetoothPbapService: Pbap Service onBind
08-25 13:19:55.707  7665  7665 V BluetoothMapService: Handler(): got msg=1
,08-25 13:19:55.708  7665  7665 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 13:19:55.708  6892  6892 D DockEventReceiver: finishStartingService: stopping service
08-25 13:19:55.708  7665  7665 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.708  7665  7665 V BluetoothPbapService: state: 12
,08-25 13:19:55.708  7665  7665 V BluetoothPbapService: Handler(): got msg=1
08-25 13:19:55.709  7665  7665 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 13:19:55.710  6892  6892 D BluetoothPbap: Proxy object connected
08-25 13:19:55.710  6892  6892 D PbapServerProfile: Bluetooth service connected
08-25 13:19:55.711  7665  7665 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 13:19:55.711  7665  7665 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.711  7665  7665 V BluetoothPbapReceiver: ***********state = 12
08-25 13:19:55.713  7665  7987 D BluetoothMapMasInstance: MAS initSocket()
08-25 13:19:55.713  7665  7987 D BluetoothMapMasInstance:   masId = 00
08-25 13:19:55.713  7665  7987 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 13:19:55.713  7665  7987 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 13:19:55.713  7665  7987 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 13:19:55.714  2066  2066 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:19:55.714  1035  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:55.715  2066  2066 D c       : Getting all permits...
08-25 13:19:55.715  2066  2066 D a       : Opening database...
08-25 13:19:55.715  7665  7988 V BluetoothPbapService: Pbap Service initSocket
08-25 13:19:55.716  1035  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:55.716  7665  7987 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:55.717  7665  7987 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 13:19:55.717  7665  7987 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 13:19:55.717  7665  7987 D BluetoothMapMasInstance: Accepting socket connection...
08-25 13:19:55.718  7665  7988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:55.718  7665  7894 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 13:19:55.719  2066  2066 D a       : Opening database auth.proximity.permit_store...
08-25 13:19:55.719  7665  7894 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 13:19:55.719  2066  2066 D a       : Closing database...
08-25 13:19:55.719  7665  7894 D BluetoothAdapterProperties: Scan Mode:21
08-25 13:19:55.719  7665  7894 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 13:19:55.721  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:55.721  7665  7988 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 13:19:55.721  7665  7988 V BluetoothPbapService: Succeed to create listening socket 
08-25 13:19:55.721  7665  7988 V BluetoothPbapService: Accepting socket connection...
,08-25 13:19:55.730  6892  6892 D BluetoothPermissionRequest: onReceive
08-25 13:19:55.731  6892  6892 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 13:19:55.732  6892  6892 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 13:19:55.735  7665  7665 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-25 13:19:55.737  7665  7665 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-25 13:19:55.742  7665  7665 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 13:19:55.759  7665  7665 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 13:19:55.760  7665  7665 V BtOppService: onCreate
,08-25 13:19:55.764  7665  7665 V BluetoothOppNotification: send message
,08-25 13:19:55.768  7665  7665 V BtOppService: Starting RfcommListener
08-25 13:19:55.773  7665  7665 D BluetoothOppPreference: Dumping Names:  
08-25 13:19:55.773  7665  7665 D BluetoothOppPreference: {}
08-25 13:19:55.773  7665  7665 D BluetoothOppPreference: Dumping Channels:  
08-25 13:19:55.773  7665  7665 D BluetoothOppPreference: {}
08-25 13:19:55.774  7665  7665 V BtOppService: onStartCommand
,08-25 13:19:55.778  7665  7665 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.778  7665  7665 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 13:19:55.782  7665  7991 V BtOppService: Deleted complete outbound shares, number =  0
08-25 13:19:55.782  7665  7665 V BluetoothOppNotification: new notify threadi!
08-25 13:19:55.783  7665  7665 V BluetoothOppNotification: send delay message
08-25 13:19:55.784  7665  7665 V BtOppService: start RfcommListener
08-25 13:19:55.784  7665  7994 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 13:19:55.786  7665  7991 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-25 13:19:55.787  7665  7991 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 13:19:55.787  7665  7665 V BtOppService: RfcommListener started
08-25 13:19:55.788  7665  7994 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 13:19:55.791  7665  7991 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38da0044 on behalf of 
08-25 13:19:55.792  7665  7996 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 13:19:55.794  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:55.796  7665  7996 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:55.796  7665  7995 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 13:19:55.798  7665  7996 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-25 13:19:55.799  7665  7996 V BtOppRfcommListener: Started RFCOMM listener....
08-25 13:19:55.799  7665  7996 I BtOppRfcommListener: Accept thread started.
08-25 13:19:55.799  7665  7996 V BtOppRfcommListener: Accepting connection...
08-25 13:19:55.800  7665  7994 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@197f052d on behalf of 
,08-25 13:19:55.802  7665  7995 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c771a62 on behalf of 
,08-25 13:19:55.803  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:55.803  7665  7665 V BluetoothFtpService: Ftp Service onCreate
08-25 13:19:55.803  7665  7665 I BluetoothFtpService: Ftp Service onCreate
08-25 13:19:55.803  7665  7995 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 13:19:55.803  7665  7665 V BluetoothFtpService: Ftp Service onStartCommand
08-25 13:19:55.803  7665  7665 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.804  7665  7665 V BluetoothFtpService: Starting Listening on sockets
08-25 13:19:55.804  7665  7665 V BtOppService: ContentObserver received notification
08-25 13:19:55.804  7665  7665 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 13:19:55.804  7665  7665 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 13:19:55.804  7665  7665 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 13:19:55.805  7665  7665 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.805  7665  7665 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 13:19:55.805  7665  7665 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 13:19:55.805  7665  7994 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 13:19:55.805  7665  7994 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 13:19:55.806  7665  7995 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:55.806  7665  7665 V BtOppService: ContentObserver received notification
08-25 13:19:55.807  7665  7665 V BluetoothFtpService: Handler(): got msg=1
08-25 13:19:55.807  7665  7994 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c98dcb0 on behalf of 
08-25 13:19:55.807  7665  7665 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 13:19:55.807  7665  7665 V BluetoothFtpService: Ftp Service initSocket
08-25 13:19:55.808  7665  7994 V BluetoothOppNotification: update too frequent, put in queue
08-25 13:19:55.810  1035  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:55.811  7665  7994 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 13:19:55.811  7665  7994 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 13:19:55.811  7665  7665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:55.814  7665  7995 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@73c729 on behalf of 
08-25 13:19:55.815  7665  7994 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ab07aae on behalf of 
08-25 13:19:55.816  7665  7665 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-25 13:19:55.817  7665  7665 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-25 13:19:55.819  7665  7997 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 13:19:55.822  7665  7995 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 13:19:55.822  7665  7994 V BluetoothOppNotification: update too frequent, put in queue
,08-25 13:19:55.823  7665  7994 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 13:19:55.823  7665  7995 V BluetoothOppNotification: outbound notification was removed.
08-25 13:19:55.823  7665  7995 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:55.825  7665  7995 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@319704f on behalf of 
08-25 13:19:55.834  7665  7665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6619d08
08-25 13:19:55.835  7665  7665 V BluetoothSapService: Sap Service onCreate
08-25 13:19:55.835  7665  7995 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 13:19:55.836  7665  7665 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:55.836  7665  7665 V BluetoothSapService: state: 12
08-25 13:19:55.837  7665  7665 V BluetoothSapService: Starting SAP server process
,08-25 13:19:55.839  7665  7995 V BluetoothOppNotification: inbound notification was removed.
08-25 13:19:55.839  7665  7665 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 13:19:55.828  7998  7998 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:55.828  7998  7998 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:55.840  7665  7999 V BluetoothSapService: Sap Service initRfcommSocket
08-25 13:19:55.841  7665  7995 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 13:19:55.841  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:55.841  7665  7999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:55.842  7665  7995 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3da6c26b on behalf of 
08-25 13:19:55.843  7665  7999 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=82
08-25 13:19:55.843  7665  7999 V BluetoothSapService: Succeed to create listening socket 
08-25 13:19:55.843  7665  7999 V BluetoothSapService: Accepting socket connection...
08-25 13:19:55.848  7998  7998 V BT_SAP  : Event pipe created
08-25 13:19:55.849  7998  7998 V BT_SAP  : create_server_socket qcom.sap.server
08-25 13:19:55.849  7998  7998 V BT_SAP  : created socket fd 6
,08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:56.317  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:56.330  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:56.334  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:19:56.338  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9120c05 added. We now have 8 listener(s)
08-25 13:19:56.338  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:56.342  1035  1926 D WifiServiceImplEx: setWifiEnabled: false pid=6766, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 13:19:56.342  1035  1926 D WifiService: setWifiEnabled: false pid=6766, uid=10118
08-25 13:19:56.342  1035  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 13:19:56.348  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:56.354  1035  1980 D WifiServiceImplEx: setWifiEnabled: true pid=6766, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 13:19:56.354  1035  1980 D WifiService: setWifiEnabled: true pid=6766, uid=10118
08-25 13:19:56.354  1035  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 13:19:56.372  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 13:19:56.372  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 13:19:56.372  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-25 13:19:56.377  1035  1375 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-25 13:19:56.377  1035  1375 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 13:19:56.380  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 13:19:56.380  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 13:19:56.380  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 13:19:56.380  1035  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 13:19:56.380  1035  1375 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 13:19:56.380  1035  1375 E WifiHW  : unknown target_country: EU , set to default
08-25 13:19:56.380  1035  1375 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 13:19:56.380  1035  1375 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 13:19:56.380  1035  1375 I WifiUtil: gEnableBmps=1
08-25 13:19:56.787  7665  7665 V BluetoothOppNotification: new notify threadi!
08-25 13:19:56.787  7665  7665 V BluetoothOppNotification: send delay message
,08-25 13:19:56.814  7665  8012 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-25 13:19:56.820  7665  8012 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18ff91c8 on behalf of 
08-25 13:19:56.821  7665  8012 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 13:19:56.823  7665  8012 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:56.824  7665  8012 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bec3261 on behalf of 
08-25 13:19:56.824  7665  8012 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 13:19:56.826  7665  8012 V BluetoothOppNotification: outbound notification was removed.
08-25 13:19:56.826  7665  8012 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 13:19:56.827  7665  8012 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22f13186 on behalf of 
08-25 13:19:56.828  7665  8012 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 13:19:56.832  7665  8012 V BluetoothOppNotification: inbound notification was removed.
08-25 13:19:56.833  7665  8012 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 13:19:56.834  7665  8012 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@316d1a47 on behalf of 
08-25 13:19:57.052   323   889 D SoftapController: Softap fwReload - Ok
,08-25 13:19:57.061  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:19:57.061  1035  1117 D Tethering: InitialState.processMessage what=4
08-25 13:19:57.066  1035  1375 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (682ms)
,08-25 13:19:57.085  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 13:19:57.098   323   889 D CommandListener: Setting iface cfg
08-25 13:19:57.098   323   889 D CommandListener: Trying to bring down wlan0
,08-25 13:19:57.101   323   889 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:19:57.104  1035  1375 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 13:19:57.121  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 13:19:57.121  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 13:19:57.121  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 13:19:57.121  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 13:19:57.130  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 13:19:57.118  8032  8032 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:57.131  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 13:19:57.131  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 13:19:57.132  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 13:19:57.132  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 13:19:57.132  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 13:19:57.132  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:57.132  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:57.132  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 13:19:57.136  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:57.136  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 13:19:57.138  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 13:19:57.118  8032  8032 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 13:19:57.141  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:57.142  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 13:19:57.144  1035  1375 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 13:19:57.144  1035  1375 D WifiMonitor: connecting to supplicant
08-25 13:19:57.146  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 13:19:57.146  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 13:19:57.146  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 13:19:57.146  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 13:19:57.147  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 13:19:57.148  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 13:19:57.148  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 13:19:57.148  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 13:19:57.148  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 13:19:57.148  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 13:19:57.148  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 13:19:57.183  8032  8032 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 13:19:57.189  1035  1997 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8038 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-25 13:19:57.221  8032  8032 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 13:19:57.221  8032  8032 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 13:19:57.293  8032  8032 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 13:19:57.302  1035  1560 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8059 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 13:19:57.311  8038  8057 W FormManager: Network not available. Please check & try again.
,08-25 13:19:57.318  8038  8058 V FormManager: Network unavailable.
08-25 13:19:57.320  8038  8058 V FormManager: Network unavailable.
,08-25 13:19:57.337  1035  1908 I ActivityManager: Killing 7159:com.android.chrome/u0a57 (adj 15): empty #17
,08-25 13:19:57.357  8032  8032 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 13:19:57.362  8032  8032 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 13:19:57.362  8032  8032 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 13:19:57.363  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 13:19:57.363  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 13:19:57.364  1035  8078 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 13:19:57.364  1035  8078 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 13:19:57.364  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 13:19:57.364  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 13:19:57.364  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 13:19:57.364  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 13:19:57.364  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 13:19:57.364  1035  1375 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 13:19:57.365  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:57.365  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:57.366  1035  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:57.366  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:57.366  1035  1375 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 13:19:57.366  1035  1375 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 13:19:57.367  1035  1375 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 13:19:57.367  1035  1375 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 13:19:57.367  1035  1375 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 13:19:57.376  1035  1772 W libprocessgroup: failed to open /acct/uid_10057/pid_7159/cgroup.procs: No such file or directory
08-25 13:19:57.375  8059  8059 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:57.379  1035  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 13:19:57.379  1035  1375 E WifiStateMachine: useWiFiOffloading() : false
08-25 13:19:57.379  1035  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 13:19:57.379  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:19:57.379  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:57.379  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:57.379  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:57.379  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 13:19:57.382  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 13:19:57.383  1035  1375 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 13:19:57.384  1035  1375 D WifiNative-wlan0: SET update_config 1: returned true
08-25 13:19:57.384  1035  1375 D WifiConfigStore: Loading config and enabling all networks 
08-25 13:19:57.384  1035  1375 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 13:19:57.384  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-25 13:19:57.384  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:57.386  1035  1375 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 13:19:57.386  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 13:19:57.386  1035  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:57.392  6766  6766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:57.392  1035  1375 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:57.395  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:57.396  6766  6766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:57.396  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:57.399  1035  1772 I ActivityManager: Killing 7177:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 13:19:57.399  1035  1375 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 13:19:57.399  1035  1375 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 13:19:57.400  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:19:57.405  6766  6845 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 13:19:57.406  6766  6845 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 13:19:57.409  6766  6845 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@19d4477f Bundle[{}]
08-25 13:19:57.410  6766  6845 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 13:19:57.410  6766  6845 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 13:19:57.410  6766  6845 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 13:19:57.411  6766  6845 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 13:19:57.412  6766  6845 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 13:19:57.412  6766  6845 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 13:19:57.418  6766  6845 I System.out: Running OutgoingSocketThread
,08-25 13:19:57.420  6766  8081 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 886)
08-25 13:19:57.421  6766  8081 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43202
08-25 13:19:57.421  6766  8081 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 13:19:57.438  1035  1703 W libprocessgroup: failed to open /acct/uid_10062/pid_7177/cgroup.procs: No such file or directory
,08-25 13:19:57.438  1035  1375 D WifiStateMachine: enableVerboseLogging : level 2
08-25 13:19:57.438  1035  1375 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 13:19:57.439  1035  1375 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-25 13:19:57.439  1035  1375 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 13:19:57.440  1035  1375 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 13:19:57.441  1035  1375 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 13:19:57.442  1035  1375 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 13:19:57.442  1035  1375 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 13:19:57.443  1035  1375 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 13:19:57.443  1035  1375 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 13:19:57.444  1035  1375 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 13:19:57.444  1035  1375 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 13:19:57.445  1035  1375 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 13:19:57.445  1035  1375 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 13:19:57.446  1035  1375 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 13:19:57.448  1035  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 13:19:57.448  1035  1375 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 13:19:57.448  1035  1375 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 13:19:57.449  1035  1375 D WifiNative-HAL: Setting external_sim to 1
08-25 13:19:57.449  1035  1375 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 13:19:57.449  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-25 13:19:57.449  7695  7695 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:57.449  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 13:19:57.450  1927  2207 D WfdsService: Set the WFDS Monitor: true
08-25 13:19:57.450  1927  2207 D WfdsMonitor: WfdsMonitorThread create
08-25 13:19:57.450  1927  2207 D WfdsMonitor: WFDS Monitor is created and started
08-25 13:19:57.450  1927  2207 D WfdsService: WiFi: Supplicant connection re-established
08-25 13:19:57.451  1927  8082 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-25 13:19:57.452  1927  8082 E CtrlSupplicant: Succeed to open control connection
08-25 13:19:57.452  1927  8082 E CtrlSupplicant: Succeed to open monitor connection
08-25 13:19:57.453  1927  8082 D WfdsMonitor: Supplicant connection established
08-25 13:19:57.453  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-25 13:19:57.454  1035  1375 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 13:19:57.454  1035  1375 I WifiNative-HAL: startHal
08-25 13:19:57.454  1035  1375 D wifi    : setting scan oui 0x95774b20
08-25 13:19:57.454  1035  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 13:19:57.454  1035  1375 I WifiNative-HAL: startHal
08-25 13:19:57.454  1035  1375 D wifi    : setting scan oui 0x95774b20
08-25 13:19:57.454  1035  1375 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 13:19:57.455  1035  1375 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 13:19:57.455  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 13:19:57.455  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 13:19:57.456  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 13:19:57.456  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 13:19:57.456  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 13:19:57.457  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 13:19:57.457  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 13:19:57.457  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 13:19:57.457  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 13:19:57.457  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 13:19:57.457  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 13:19:57.459  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 13:19:57.459  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 13:19:57.460  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 13:19:57.460  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 13:19:57.460  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 13:19:57.460  8059  8059 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:57.460  8032  8032 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 13:19:57.460  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 13:19:57.461  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 13:19:57.461  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 13:19:57.461  1035  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 13:19:57.462  1035  1375 E WifiNative: : [203,701,913 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 13:19:57.462  1035  1375 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 13:19:57.463  1035  1375 D WifiNative-wlan0: RECONNECT: returned true
08-25 13:19:57.463  1035  1375 D WifiNative-wlan0: doString: [STATUS]
08-25 13:19:57.463  1035  1375 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 13:19:57.464  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 13:19:57.464  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 13:19:57.464  1035  1375 D WifiNative-wlan0: SET ps 1: returned true
08-25 13:19:57.464  1035  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.465  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=],
08-25 13:19:57.465  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-25 13:19:57.467  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 13:19:57.467   323   889 D CommandListener: Setting iface cfg
,08-25 13:19:57.467   323   889 D CommandListener: Trying to bring up p2p0
08-25 13:19:57.467  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-25 13:19:57.467  1035  1375 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 13:19:57.467  1035  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 13:19:57.467  1035  1374 D LGWifiP2pService: P2pEnablingState
08-25 13:19:57.467  1035  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.467  1035  1541 I WifiNative-HAL: startHal
08-25 13:19:57.467  1035  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.467  1035  1374 D LGWifiP2pService: P2p socket connection successful
08-25 13:19:57.467  1035  1374 D LGWifiP2pService: P2pEnabledState
08-25 13:19:57.467  1035  1541 D wifi    : getting scan capabilities on interface[1] = 0x95774b20
08-25 13:19:57.467  1035  1541 D wifi    : failed to get capabilities : -3
08-25 13:19:57.467  1035  1541 E WifiScanningService: could not get scan capabilities
08-25 13:19:57.467  1035  1375 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 13:19:57.468  1035  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 13:19:57.468  1035  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.468  1035  1375 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 13:19:57.468  1035  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 13:19:57.468  1035  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 13:19:57.469  1035  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 13:19:57.469  1035  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-25 13:19:57.469  1035  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 13:19:57.469  1035  1374 D LGWifiP2pService: before postfix = G3
08-25 13:19:57.469  1035  1374 D WifiServerServiceExt: postfix byte check : 2
08-25 13:19:57.469  1035  1374 D LGWifiP2pService: after postfix = G3
08-25 13:19:57.469  1035  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 13:19:57.469  1035  1375 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 13:19:57.470  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 13:19:57.470  1035  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 13:19:57.470  1035  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 13:19:57.470  1927  1927 D WfdsService: WifiP2pState is changed : true
08-25 13:19:57.470  1927  2207 D WfdsService: Receive the WFDS_ENABLE Method
08-25 13:19:57.470  1927  2207 D WfdsService: Set the WFDS Monitor: true
08-25 13:19:57.470  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-25 13:19:57.470  1927  2207 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 13:19:57.470  8032  8032 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 13:19:57.471  1035  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 13:19:57.471  1035  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 13:19:57.471  1927  2207 D WfdsService: selectPreferredScanChannel [36]
08-25 13:19:57.471  1927  2207 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 13:19:57.471  1035  1375 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 13:19:57.472  1035  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 13:19:57.472  1035  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 13:19:57.472  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 13:19:57.472  1035  1375 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 13,:19:57.472  1035  1375 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 13:19:57.472  1035  1375 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 13:19:57.472  8032  8032 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 13:19:57.473  1035  1375 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 13:19:57.473  1035  1375 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 13:19:57.474  1035  1375 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 13:19:57.474  1035  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 13:19:57.474  1035  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-25 13:19:57.474  1035  1375 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 13:19:57.474  8032  8032 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 13:19:57.474  1035  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 13:19:57.474  1035  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 13:19:57.474  1035  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 13:19:57.475  1035  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-25 13:19:57.475  1035  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 13:19:57.476  1035  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 13:19:57.476  1035  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 13:19:57.476  1927  1927 D WfdsService: isConnected: false
08-25 13:19:57.476  1035  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-25 13:19:57.476  1035  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 13:19:57.476  1035  1375 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 13:19:57.477  1035  1375 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 13:19:57.477  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 13:19:57.478  1035  1375 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 13:19:57.478  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 13:19:57.478  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 13:19:57.478  1927  1927 D WfdsService: Update P2p Interface State: 3
,08-25 13:19:57.486  1035  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 13:19:57.486  1035  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 13:19:57.486  1035  1374 D LGWifiP2pService: InactiveState
08-25 13:19:57.486  1035  1374 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.486  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.486  1035  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 13:19:57.486  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:57.487  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 13:19:57.488  8032  8032 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.488  1035  8078 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 13:19:57.488  1035  8078 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.488  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.488  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.488  1927  8082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 13:19:57.488  8032  8032 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 13:19:57.488  8032  8032 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.489  1927  8082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:57.489  8032  8032 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.489  1927  8082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:57.489  1035  8078 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:57.489  1035  8078 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.490  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.490  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.490  1035  8078 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:57.490  1035  8078 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.490  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.490  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.490  1035  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 13:19:57.490  1035  1374 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.490  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.490  1035  1374 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.491  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-25 13:19:57.492  1035  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:19:57.492  1035  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  1035  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  1035  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  1035  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  1035  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.492  8032  8032 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.493  1927  2207 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 13:19:57.493  1035  1035 E WifiServerServiceExt: No p2p device connected
08-25 13:19:57.493  8032  8032 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 13:19:57.493  8032  8032 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.494  8032  8032 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.495  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 13:19:57.495  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.495  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.495  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 13:19:57.495  1035  8078 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:57.496  1035  8078 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.496  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.496  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.496  1035  8078 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:57.496  1035  8078 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.496  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.496  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 13:19:57.496  1035  1375 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 13:19:57.497  1035  1375 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 13:19:57.497  1035  1375 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 13:19:57.497  1035  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.497  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:57.497  1035  1375 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 13:19:57.497  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 13:19:57.498  1927  8082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 13:19:57.498  1927  8082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=,DRIVER type=WORLD]
08-25 13:19:57.498  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 13:19:57.498  8032  8032 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:57.498  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 13:19:57.498  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:57.498  1035  8078 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:57.498  1035  8078 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 13:19:57.499  1035  1375 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 13:19:57.499  1035  1375 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 13:19:57.499  1035  1375 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 13:19:57.499  1035  1375 D WifiNative-wlan0: doBoolean: SCAN
08-25 13:19:57.500  1035  1375 D WifiNative-wlan0: SCAN: returned false
08-25 13:19:57.500  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=203740  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 13:19:57.501  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=203741  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 13:19:57.502  1035  1375 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:57.502  1035  1375 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:57.502  1035  1375 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:57.503  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:57.503  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:57.503  1035  1375 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:57.503  1035  1375 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 13:19:57.504  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:57.504  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:57.504  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 13:19:57.505  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:57.506  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-25 13:19:57.507  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:57.511  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:57.511  4735  4735 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 13:19:57.512  8038  8084 W FormManager: Network not available. Please check & try again.
08-25 13:19:57.514  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:57.514  8038  8085 V FormManager: Network unavailable.
08-25 13:19:57.517  4735  4735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 13:19:57.521  4735  8086 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 13:19:57.529  4735  8087 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 13:19:57.529  4735  8087 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 13:19:57.573  1035  1908 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8088 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 13:19:57.579  8038  8085 V FormManager: Network unavailable.
,08-25 13:19:57.668  8088  8088 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 13:19:57.668  8088  8088 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 13:19:57.680  8088  8088 V [BNRBootReceiver]: Boot Receiver Return
,08-25 13:19:57.685  8088  8088 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-25 13:19:57.767  1035  1771 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8106 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 13:19:57.772  1035  1771 I ActivityManager: Killing 7201:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-25 13:19:57.874  1035  2015 W libprocessgroup: failed to open /acct/uid_10085/pid_7201/cgroup.procs: No such file or directory
,08-25 13:19:57.896  7767  7852 D UEI.SmartControl: Internal timer expired: 1
08-25 13:19:57.896  7767  7852 D UEI.SmartControl: unbind internal service
,08-25 13:19:57.905  7767  7767 D UEI.SmartControl: Service.onUnbind: IControl
08-25 13:19:57.905  7767  7767 D UEI.SmartControl: Service.onDestroy
08-25 13:19:57.906  7767  7767 D UEI.SmartControl: Lock is in USE false
08-25 13:19:57.906  7767  7767 D UEI.SmartControl: unbind internal service
08-25 13:19:57.906  7767  7767 D serial_port: close(fd = 25)
08-25 13:19:57.912  7767  7767 I UEI.SmartControl: Serial port is closed.
08-25 13:19:57.912  7767  7767 I UEI.SmartControl: Serial port is closed.
08-25 13:19:57.912  7767  7767 D UEI.SmartControl: Blaster closed
08-25 13:19:57.912  7767  7767 D UEI.SmartControl: Shut down QS...
08-25 13:19:57.913  7767  7767 D UEI.SmartControl: Stopping QS lib
08-25 13:19:57.913  7767  7767 D UEI.SmartControl: QS lib stop result = true
08-25 13:19:57.913  7767  7767 D UEI.SmartControl: Stopped QS lib
08-25 13:19:57.914  8106  8106 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 13:19:57.915  7767  7767 D UEI.SmartControl: Stopped file observer...
,08-25 13:19:57.915  7767  7767 D UEI.SmartControl: QS shutdown complete
08-25 13:19:57.939  8106  8106 D PluginManager: init()
,08-25 13:19:58.002  8032  8032 E wpa_supplicant: USIM:  scard_init function
08-25 13:19:58.002  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 13:19:58.002  1035  8078 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 13:19:58.002  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 13:19:58.002  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-25 13:19:58.003  1035  8078 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 13:19:58.003  8032  8032 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 13:19:58.004  1035  1375 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 13:19:58.007  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 13:19:58.008  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 13:19:58.008  1035  1375 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-25 13:19:58.009  1035  1375 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 13:19:58.011  1035  1375 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 13:19:58.011  1035  1375 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 13:19:58.019  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=204259  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 13:19:58.021  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=204261  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 13:19:58.026  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.026  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.028  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.028  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.028  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 13:19:58.028  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.029  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.029  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 13:19:58.029  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:58.029  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 13:19:58.031  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.033  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.033  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.034  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.122  8032  8032 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 13:19:58.123  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 13:19:58.123  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 13:19:58.124  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 13:19:58.124  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 13:19:58.125  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:58.125  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 13:19:58.129  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=204368  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 13:19:58.135  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 13:19:58.135  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=204375  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 13:19:58.136  1035  1375 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204376
08-25 13:19:58.136  1035  1375 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204376
08-25 13:19:58.137  1035  1375 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204377
08-25 13:19:58.137  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204377
08-25 13:19:58.137  1035  1375 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204377
08-25 13:19:58.137  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=204377  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 13:19:58.141  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.141  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.141  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:58.141  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:58.141  8032  8032 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:19:58.142  8032  8032 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 13:19:58.142  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 13:19:58.142  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:19:58.142  1035  8078 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:19:58.142  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 13:19:58.143  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 13:19:58.143  1035  8078 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-25 13:19:58.147  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.147  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.147  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 13:19:58.147  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:58.147  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:58.147  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.150  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=204390  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 13:19:58.151  1035  1375 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:58.151  1035  1375 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:58.151  1035  1375 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:58.151  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:58.151  1035  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 13:19:58.153  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.153  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.153  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 13:19:58.154  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:58.154  1035  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=204394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 13:19:58.154  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 13:19:58.155  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=204395  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-25 13:19:58.155  1035  1375 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=204395
08-25 13:19:58.156  1035  1375 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=204396
08-25 13:19:58.156  1035  1375 D WifiNative-wlan0: doString: [STATUS]
08-25 13:19:58.157  1035  8078 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 13:19:58.157  1035  8078 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 13:19:58.157  1035  1375 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-25 13:19:58.159  1035  1375 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 13:19:58.163  1035  1375 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 13:19:58.163  1035  1375 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 13:19:58.167  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.167  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.168  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 13:19:58.169  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.169  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.169  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 13:19:58.171  1035  1375 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 13:19:58.171  1035  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:19:58.171  1035  1405 D ConnectivityService: Got NetworkAgent Messenger
08-25 13:19:58.171  1035  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 13:19:58.171  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 13:19:58.171  1035  1405 D ConnectivityService: NetworkAgent connected
08-25 13:19:58.171  1035  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 13:19:58.171  1035  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 13:19:58.174  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.174  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.175  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.175  1035  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 13:19:58.175  1035  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:19:58.175  1035  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 13:19:58.176  1035  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 13:19:58.176  1035  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 13:19:58.177  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.177  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.178  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.179  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.179  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.180  1586  1586 D StatusBar.NetworkCon,troller: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.180  1035  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 13:19:58.181   323   889 D CommandListener: Setting iface cfg
,08-25 13:19:58.184  1035  1375 E WifiStateMachine: Start Dhcp Watchdog 3
08-25 13:19:58.184  1035  8127 D DhcpStateMachine: StoppedState
08-25 13:19:58.184  1035  8127 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.184  1035  8127 D DhcpStateMachine: WaitBeforeStartState
08-25 13:19:58.185  1035  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=204425  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:58.185  1035  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=204426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-25 13:19:58.186  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=204426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:58.187  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:58.187  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 13:19:58.187  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:58.187  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 13:19:58.188  1035  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=204428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:58.188  1035  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=204429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:58.189  1035  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=204429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 13:19:58.190  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14266] from screen [on:0 period:-1049784338] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 13:19:58.191  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1049784337] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 13:19:58.191  1035  1375 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 13:19:58.194  1035  1405 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-25 13:19:58.194  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.194  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.194  1035  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.194  1035  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.195  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.196  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 13:19:58.197  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 13:19:58.197  1035  1405 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 13:19:58.198  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
08-25 13:19:58.198  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
08-25 13:19:58.198  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 13:19:58.198  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 13:19:58.198  1035  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 13:19:58.198  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 13:19:58.199  1035  1375 D WifiNative-wlan0: SET ps 0: returned true
08-25 13:19:58.199  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 13:19:58.199  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 13:19:58.199  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 13:19:58.199  1035  1375 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 13:19:58.199  1035  1375 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 13:19:58.199  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10232f3a target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.199  1035  1375 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 13:19:58.199  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10232f3a target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.199  1035  8127 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.199  1035  8127 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 13:19:58.199   323   889 D CommandListener: Setting iface cfg
08-25 13:19:58.200   323   889 D CommandListener: Trying to bring up wlan0
08-25 13:19:58.200  1035  1375 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 13:19:58.201  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.201  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 13:19:58.201  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.201  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 13:19:58.201  1035  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.202  1035  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.202  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.202  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 13:19:58.202  1035  1405 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 13:19:58.202  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 13:19:58.203  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 13:19:58.203  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 13:19:58.203  1035  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.203  1035  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.203  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 13:19:58.203  1035  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned t,rue
08-25 13:19:58.203  1035  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 13:19:58.203  8032  8032 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 13:19:58.204  1035  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 13:19:58.204  1035  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 13:19:58.204  1035  1375 D WifiNative-wlan0: SET ps 1: returned true
08-25 13:19:58.206  1035  1405 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 13:19:58.206  1035  1375 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 13:19:58.207  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 13:19:58.207  1035  1375 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 13:19:58.207  1035  1405 D ConnectivityService: ignoring duplicate network state non-change
,08-25 13:19:58.210  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.210  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.212  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.213  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.213  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.213  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 13:19:58.214  1035  1405 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 13:19:58.215  1035  1405 D ConnectivityService: Adding iface wlan0 to network 102
08-25 13:19:58.220  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.220  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:19:58.220  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 13:19:58.220  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 13:19:58.221  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 13:19:58.223  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.223  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.223  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 13:19:58.224  1035  1375 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 13:19:58.227  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 13:19:58.234  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.234  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 13:19:58.235  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.248  1035  1405 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 13:19:58.248  1035  1405 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 13:19:58.249  1035  1405 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 13:19:58.249   323   889 E Netd    : netlink response contains error (File exists)
08-25 13:19:58.249  1035  1405 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 13:19:58.250  1035  1405 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 13:19:58.250  1035  1405 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-25 13:19:58.250  1035  1405 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-25 13:19:58.253  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.253  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:19:58.253  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 13:19:58.254  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.254  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 13:19:58.257  1035  1405 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 13:19:58.257  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.257  1035  1405 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 13:19:58.257  1035  1405 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 13:19:58.258  1035  1405 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 13:19:58.258  1035  8126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.258  1035  1405 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:58.258  1035  8126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 13:19:58.258  1035  1405 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:58.258  1035  8126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:19:58.258  1035  1405 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 13:19:58.258  1035  8126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 13:19:58.258  1035  1405 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.258  1035  1405 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 13:19:58.258  1035  1405 D ConnectivityService: currentScore = 0, newScore = 20
08-25 13:19:58.258  1035  1405 D ConnectivityService:    accepting network in place of null
08-25 13:19:58.258  1035  1405 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.258  1035  1375 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.258  1035  1375 D WIFI    :  , my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:58.259  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.259  1035  1405 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 13:19:58.259  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 13:19:58.259  1035  1405 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 13:19:58.260  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:19:58.261   323  8135 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-25 13:19:58.263  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:19:58.263  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 13:19:58.264  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.266  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 13:19:58.266  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 13:19:58.266  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 13:19:58.266  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 13:19:58.267  1035  1405 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:58.267  1035  1405 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 13:19:58.267  1035  1405 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-25 13:19:58.268  1035  1405 D ConnectivityService: validation of new default Network = false
08-25 13:19:58.268  1035  1405 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 13:19:58.268  1035  1405 D DSQN    : enableDataServiceNotify 
08-25 13:19:58.268  1035  1405 D DSQN    : start dsqn bin
,08-25 13:19:58.277  1035  1405 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 13:19:58.277  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.277  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:58.277  1035  1405 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:58.277  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 13:19:58.278  1035  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 13:19:58.268  8137  8137 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:58.268  8137  8137 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:58.289  8137  8137 E DSQN    : DSQN ssw
,08-25 13:19:58.299  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:58.300  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.300  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 13:19:58.304   323  8135 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 13:19:58.336   323  8135 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 13:19:58.368   323   888 D LGDataListener: argv[0]=dsqncommand
08-25 13:19:58.368   323   888 D LGDataListener: argv[1]=wlan0
,08-25 13:19:58.368   323   888 D LGDataListener: argv[2]=1
08-25 13:19:58.368   323   888 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 13:19:58.370  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 13:19:58.370  1035  1115 D DSQN    : start to monitor internet connection
08-25 13:19:58.396  1035  8126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 11:19:58 GMT], X-Android-Received-Millis=[1472123998395], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472123998367]}
,08-25 13:19:58.396  1035  8126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 13:19:58.396  1035  8126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 13:19:58.397  1035  1405 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-25 13:19:58.397  1035  1405 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 13:19:58.398  1035  1405 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:58.398  1035  1405 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:58.398  1035  1405 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 13:19:58.398  1035  1405 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-25 13:19:58.398  1035  1405 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 13:19:58.398  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.399  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:58.400  1035  1405 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:58.401  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 13:19:58.403  1035  8127 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 13:19:58.403  1035  1405 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.404  1035  1375 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.404  1035  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:19:58.404  1035  8127 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 13:19:58.404  1035  1405 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 13:19:58.405  1035  8127 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 13:19:58.405  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:58.406  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 13:19:58.398  8143  8143 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 13:19:58.398  8143  8143 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 13:19:58.420  6766  6845 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 887)
08-25 13:19:58.420  6766  6845 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 887)
08-25 13:19:58.422  6766  6845 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 892)
08-25 13:19:58.423  6766  6845 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 13:19:58.423  6766  6845 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 893)
08-25 13:19:58.425  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.425  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d36d45a added. We now have 2 listener(s)
08-25 13:19:58.425  1035  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 13:19:58.430  8143  8143 I dhcpcd  : version 5.5.6 starting
08-25 13:19:58.432  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.432  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.432  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.432  8143  8143 E dhcpcd  : get_duid: m
08-25 13:19:58.432  8143  8143 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 13:19:58.432  8143  8143 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-25 13:19:58.432  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.432  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca8068b added. We now have 9 listener(s)
08-25 13:19:58.432  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.434  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 13:19:58.436  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 13:19:58.436  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.437  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.437  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:58.440  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:58.440  8106  8106 W ExternalStrings: load override strings
08-25 13:19:58.440  8106  8106 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 13:19:58.440  8106  8106 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704,)
08-25 13:19:58.441  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.441  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:58.442  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.442  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ac6381 added. We now have 3 listener(s)
08-25 13:19:58.442  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 13:19:58.443  8106  8106 D StatusProvider: onCreate
08-25 13:19:58.443  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.445  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.447  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.447  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.447  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.447  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.447  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307ddc26 added. We now have 10 listener(s)
08-25 13:19:58.447  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.447  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:58.448  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:58.448  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:58.448  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.448  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.448  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:58.448  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.448  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d36d45a removed from the list
08-25 13:19:58.448  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.448  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca8068b removed from the list
08-25 13:19:58.448  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:58.448  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.449  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.449  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.450  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.450  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.450  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.450  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca8068b not in the list
08-25 13:19:58.450  6766  6845 W org.thaliproject.p2p.btconnectorlib.inte,rnal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.450  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.451  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.451  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.451  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.451  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307ddc26 removed from the list
08-25 13:19:58.451  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.451  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.451  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.451  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.451  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12ac6381 removed from the list
08-25 13:19:58.452  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.452  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0e8067 added. We now have 2 listener(s)
08-25 13:19:58.452  1035  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.455  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.455  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.455  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.456  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.456  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f63e14 added. We now have 9 listener(s)
08-25 13:19:58.456  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.456  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:19:58.461  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:58.465  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:58.467  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.467  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:58.467  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.467  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bdb94b2 added. We now have 3 listener(s)
,08-25 13:19:58.467  1035  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.469  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.471  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.473  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.473  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.473  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.473  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.473  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1778bc03 added. We now have 10 listener(s)
08-25 13:19:58.473  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.473  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:58.473  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:58.473  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:19:58.473  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.473  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:19:58.476  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 13:19:58.476  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.480  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:19:58.482  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 13:19:58.483  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:58.483  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:58.484  6766  6845 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 13:19:58.484  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:58.484  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:58.486  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:58.486  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:58.486  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:58.486  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.486  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.486  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:58.486  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.486  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0e8067 removed from the list
08-25 13:19:58.486  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.486  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f63e14 removed from the list
08-25 13:19:58.486  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:58.486  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.487  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.487  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.488  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.488  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.488  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.488  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f63e14 not in the list
08-25 13:19:58.488  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.488  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.488  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.4,89  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:58.489  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:58.489  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.489  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.489  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1778bc03 removed from the list
08-25 13:19:58.489  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.489  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.489  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.489  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.489  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bdb94b2 removed from the list
08-25 13:19:58.490  8106  8106 V Signer  : override build config not found
08-25 13:19:58.490  8106  8106 D Signer  : value of property debug is false
08-25 13:19:58.490  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.490  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ea49fe added. We now have 2 listener(s)
08-25 13:19:58.490  1035  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.493  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.493  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.493  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.493  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.493  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cc1155f added. We now have 9 listener(s)
08-25 13:19:58.493  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.493  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:19:58.496  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:58.499  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:58.500  8143  8143 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 13:19:58.500  8143  8143 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 13:19:58.500  8143  8143 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 13:19:58.500  8143  8143 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 13:19:58.500  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.500  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:58.500  8143  8143 D dhcpcd  : wlan0: sending REQUEST (xid 0x841ced6b), next in 4.53 seconds
08-25 13:19:58.501  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.501  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a070075 added. We now have 3 listener(s)
08-25 13:19:58.501  1035  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.502  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.504  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.506  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.506  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.506  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.506  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.506  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169d080a added. We now have 10 listener(s)
08-25 13:19:58.506  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.506  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 13:19:58.507  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:58.507  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:58.507  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:19:58.507  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.507  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:19:58.517  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 13:19:58.517  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-25 13:19:58.517  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 13:19:58.517  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 13:19:58.517  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 13:19:58.517  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 13:19:58.518  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 13:19:58.518  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 13:19:58.518  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-25 13:19:58.518  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 13:19:58.518  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 13:19:58.518  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-25 13:19:58.518  8106  8106 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-25 13:19:58.525  8143  8143 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 13:19:58.526  8106  8106 V LGMDMManager: Create singleton instance
,08-25 13:19:58.555  8143  8143 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds,
08-25 13:19:58.555  8143  8143 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 13:19:58.556  8143  8143 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-25 13:19:58.556  8143  8143 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 13:19:58.556  8143  8143 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 13:19:58.557  8143  8143 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 13:19:58.557  8143  8143 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 13:19:58.557  8143  8143 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 13:19:58.565  8106  8106 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-25 13:19:58.606  1035  1703 I art     : Explicit concurrent mark sweep GC freed 78596(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.415ms total 97.929ms
,08-25 13:19:58.612  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:58.614  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:58.615  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 13:19:58.616  1035  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.620  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:58.629  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:58.632  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 13:19:58.632  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:19:58.634  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:58.664  1035  1962 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8168 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-25 13:19:58.665  1035  1962 I ActivityManager: Killing 7228:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-25 13:19:58.718  8106  8157 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 13:19:58.816  1035  8127 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 13:19:58.818  1035  8127 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 13:19:58.819  1035  8127 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 13:19:58.819  1035  8127 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 13:19:58.819  1035  8127 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 13:19:58.819  1035  8127 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 13:19:58.819  1035  8127 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 13:19:58.819  1035  8127 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 13:19:58.821  1035  8127 D DhcpStateMachine: RunningState
08-25 13:19:58.876  1035  1980 W libprocessgroup: failed to open /acct/uid_10093/pid_7228/cgroup.procs: No such file or directory
08-25 13:19:58.876  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:19:58.882  6766  6845 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-25 13:19:58.882  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:19:58.883  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:58.883  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:58.883  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.883  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.883  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:58.883  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.883  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ea49fe removed from the list
08-25 13:19:58.884  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.884  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cc1155f removed from the list
08-25 13:19:58.884  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:58.884  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.898  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.898  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.903  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.903  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.903  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.903  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cc1155f not in the list
08-25 13:19:58.903  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.903  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.904  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.905  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:58.905  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:58.905  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:19:58.905  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.905  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169d080a removed from the list
08-25 13:19:58.905  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.905  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.905  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.905  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.905  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a070075 removed from the list
08-25 13:19:58.906  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.906  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22d42ef1 added. We now have 2 listener(s)
08-25 13:19:58.906  1035  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.909  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.909  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.909  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.909  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.909  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a0b9ad6 added. We now have 9 listener(s)
08-25 13:19:58.909  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.910  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 13:19:58.913  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:58.920  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:58.923  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.923  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:19:58.924  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.924  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52f5444 added. We now have 3 listener(s)
08-25 13:19:58.925  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.926  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.929  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.930  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.930  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.930  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.930  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.930  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@116bc92d added. We now have 10 listener(s)
08-25 13:19:58.930  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.930  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:58.930  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:58.930  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:19:58.930  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.930  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:19:58.933  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 13:19:58.933  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.937  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 13:19:58.938  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 13:19:58.938  8168  8168 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 13:19:58.940  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:58.940  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:58.942  6766  6845 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 13:19:58.944  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:58.944  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:58.944  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:58.944  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.944  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.944  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:58.944  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.944  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22d42ef1 removed from the list
08-25 13:19:58.944  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.945  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a0b9ad6 removed from the list
08-25 13:19:58.945  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:58.945  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.945  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.945  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.946  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.946  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.946  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.946  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a0b9ad6 not in the list
08-25 13:19:58.946  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.946  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.947  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.948  6766  6845 D BluetoothLeScanner: could not find callback wrapper
08-25 13:19:58.948  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:58.948  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.948  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.948  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@116bc92d removed from the list
08-,25 13:19:58.948  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.948  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.948  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.948  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.948  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52f5444 removed from the list
08-25 13:19:58.949  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.949  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aef70b0 added. We now have 2 listener(s)
,08-25 13:19:58.949  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 13:19:58.952  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.952  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.952  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.952  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.952  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@468cb29 added. We now have 9 listener(s)
08-25 13:19:58.952  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.953  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 13:19:58.955  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:58.958  6766  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:58.960  6766  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:58.960  6766  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:58.960  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:58.960  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f00144f added. We now have 3 listener(s)
08-25 13:19:58.961  1035  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 13:19:58.962  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.964  6766  6766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:58.965  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 13:19:58.965  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:58.965  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:58.966  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:58.966  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d52e7dc added. We now have 10 listener(s)
08-25 13:19:58.966  6766  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:58.966  6766  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:58.966  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:58.966  6766  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:58.966  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.966  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.966  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:58.966  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.967  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aef70b0 removed from the list
08-25 13:19:58.967  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.967  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@468cb29 removed from the list
08-25 13:19:58.967  6766  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:58.967  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.968  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.968  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.969  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.969  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.969  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.969  6766  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@468cb29 not in the list
08-25 13:19:58.969  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listene,r does not exist in the list - probably already removed
08-25 13:19:58.969  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.970  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:58.970  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:58.970  8168  8168 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 13:19:58.970  6766  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:58.970  6766  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d52e7dc removed from the list
08-25 13:19:58.970  6766  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:58.970  6766  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:58.970  6766  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:58.970  6766  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:58.970  6766  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f00144f removed from the list
08-25 13:19:58.971  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 13:19:58.971  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 13:19:58.971  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 13:19:58.971  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:58.972  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 13:19:58.972  6766  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:19:58.983  6766  8199 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 900, name: My test thread name)
08-25 13:19:58.983  6766  8199 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 900, thread name: My test thread name)
08-25 13:19:58.983  6766  8199 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 900, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 13:19:58.985  6766  8200 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 902, name: My test thread name)
08-25 13:19:58.985  6766  8200 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 902, thread name: My test thread name)
08-25 13:19:58.986  6766  8200 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 902, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 13:19:58.987  6766  6845 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 13:19:58.987  6766  6845 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 13:19:58.987  6766  6845 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 13:19:58.988  6766  6845 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 13:19:58.988  6766  6845 D com.test.thalitest.ThaliTestRunner: Total duration: 23250 ms
08-25 13:19:58.989  6766  6845 I jxcore-log: Total number of executed tests:  80
08-25 13:19:58.989  6766  6845 I jxcore-log: 
08-25 13:19:58.989  6766  6845 I jxcore-log: Number of passed tests:  80
08-25 13:19:58.989  6766  6845 I jxcore-log: 
08-25 13:19:58.989  6766  6845 I jxcore-log: Number of failed tests:  0
08-25 13:19:58.989  6766  6845 I jxcore-log: 
08-25 13:19:58.989  6766  6845 I jxcore-log: Number of ignored tests:  0
08-25 13:19:58.989  6766  6845 I jxcore-log: 
08-25 13:19:58.989  6766  6845 I jxcore-log: Total duration:  23250
08-25 13:19:58.989  6766  6845 I jxcore-log: 
08-25 13:19:58.990  6766  6845 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 13:19:58.990  6766  6845 I jxcore-log: 
08-25 13:19:58.992  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:58.992  6766  6845 I jxcore-log: 
08-25 13:19:58.995  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:58.995  6766  6845 I jxcore-log: 
08-25 13:19:58.996  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:58.996  6766  6845 I jxcore-log: 
08-25 13:19:58.996  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:58.996  6766  6845 I jxcore-log: 
08-25 13:19:58.997  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:58.997  6766  6845 I jxcore-log: 
08-25 13:19:58.999  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:58.999  6766  6845 I jxcore-log: 
,08-25 13:19:59.001  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:59.001  6766  6845 I jxcore-log: 
08-25 13:19:59.003  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:59.003  6766  6845 I jxcore-log: 
08-25 13:19:59.005  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:59.005  6766  6845 I jxcore-log: 
08-25 13:19:59.006  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:59.006  6766  6845 I jxcore-log: 
08-25 13:19:59.006  8168  8168 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 13:19:59.007  8168  8168 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 13:19:59.007  8168  8168 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 13:19:59.007  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.007  6766  6845 I jxcore-log: 
08-25 13:19:59.007  8168  8168 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 13:19:59.007  8168  8168 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 13:19:59.008  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.008  6766  6845 I jxcore-log: 
08-25 13:19:59.009  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:19:59.009  6766  6845 I jxcore-log: 
08-25 13:19:59.009  8168  8168 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 13:19:59.009  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:59.009  6766  6845 I jxcore-log: 
08-25 13:19:59.010  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:59.010  6766  6845 I jxcore-log: 
08-25 13:19:59.010  6766  6766 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 13:19:59.011  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.011  6766  6845 I jxcore-log: 
08-25 13:19:59.011  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.011  6766  6845 I jxcore-log: 
08-25 13:19:59.012  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.012  6766  6845 I jxcore-log: 
08-25 13:19:59.012  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.012  6766  6845 I jxcore-log: 
08-25 13:19:59.013  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.013  6766  6845 I jxcore-log: 
08-25 13:19:59.013  8168  8168 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 13:19:59.013  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.013  6766  6845 I jxcore-log: 
08-25 13:19:59.014  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.014  6766  6845 I jxcore-log: 
08-25 13:19:59.015  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:59.015  6766  6845 I jxcore-log: 
08-25 13:19:59.015  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:19:59.015  6766  6845 I jxcore-log: 
,08-25 13:19:59.016  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:19:59.016  6766  6845 I jxcore-log: 
,08-25 13:19:59.016  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:59.016  6766  6845 I jxcore-log: 
08-25 13:19:59.017  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:59.017  6766  6845 I jxcore-log: 
08-25 13:19:59.018  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.018  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:59.018  6766  6845 I jxcore-log: 
08-25 13:19:59.018  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:59.018  6766  6845 I jxcore-log: 
08-25 13:19:59.019  6766  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:59.019  6766  6845 I jxcore-log: 
08-25 13:19:59.019  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.028  8168  8168 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 13:19:59.030  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 13:19:59.031  8168  8168 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 13:19:59.032  6892  6892 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 13:19:59.033  8168  8168 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 13:19:59.035  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.035  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.039  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:59.042  8106  8157 D LgDataFeature: LgDataFeature() Constructor: none
08-25 13:19:59.042  8106  8157 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 13:19:59.043  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.048  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.049  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.050  8168  8168 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 13:19:59.052  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.053  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.056  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:59.060  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.065  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.065  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 13:19:59.066  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:59.069  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 13:19:59.069  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 13:19:59.069  6892  6892 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 13:19:59.069  6892  6892 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 13:19:59.070  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 13:19:59.070  6892  6892 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 13:19:59.070  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 13:19:59.070  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 13:19:59.070  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 13:19:59.070  6892  6892 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 13:19:59.070  6892  6892 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 13:19:59.071  6892  6892 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 13:19:59.073  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.075  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.079  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:59.084  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.088  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.088  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.088  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:59.090  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.090  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.094  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:59.102  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.107  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.107  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.107  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:59.109  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.109  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 13:19:59.116  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:59.119  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.123  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.123  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.124  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 13:19:59.125  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.126  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.130  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:59.134  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.138  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.138  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.139  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 13:19:59.146  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.147  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.154  8106  8157 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-25 13:19:59.157  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:59.167  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.171  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.171  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.176  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:59.179  8106  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-25 13:19:59.181  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.182  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.186  8106  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-25 13:19:59.187  8106  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 13:19:59.188  8106  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 13:19:59.189  8106  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-25 13:19:59.189  8106  8157 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-25 13:19:59.191  8106  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-25 13:19:59.192  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:59.196  8106  8157 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-25 13:19:59.199  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.206  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 13:19:59.207  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.209  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 13:19:59.212  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.213  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.216  8059  8059 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 13:19:59.223  8059  8059 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 13:19:59.227  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 13:19:59.233  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 13:19:59.242  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.242  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.243  8168  8168 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 13:19:59.244  8168  8168 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-25 13:19:59.244  8168  8168 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 13:19:59.248  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.248  8106  8158 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 13:19:59.255  8059  8059 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 13:19:59.256  8059  8059 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 13:19:59.260  6892  6892 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 13:19:59.260  8205  8205 D AndroidRuntime: 
08-25 13:19:59.260  8205  8205 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 13:19:59.263  8205  8205 D AndroidRuntime: CheckJNI is OFF
08-25 13:19:59.266  6892  6892 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 13:19:59.272  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 13:19:59.273  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 13:19:59.274  8168  8168 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 13:19:59.274  8168  8168 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-25 13:19:59.277  8168  8168 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-25 13:19:59.281  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-25 13:19:59.286  8168  8168 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 13:19:59.287  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 13:19:59.288  8168  8168 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-25 13:19:59.322  8168  8168 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 13:19:59.322  8168  8168 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 13:19:59.328  8168  8168 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 13:19:59.330  8168  8168 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 13:19:59.330  8168  8168 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 13:19:59.330  8168  8168 V SoundPool: doLoad: loading sample sampleID=1
08-25 13:19:59.331  8168  8168 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 13:19:59.332  8168  8224 V SoundPool: Start decode
08-25 13:19:59.332  8168  8224 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 13:19:59.333   327  1385 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 13:19:59.333   327  1385 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 13:19:59.333   327  1385 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 13:19:59.333   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 13:19:59.333   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 13:19:59.333   327  1385 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 13:19:59.333   327  1385 V MediaPlayerService: player type = 3
08-25 13:19:59.333   327  1385 V AwesomePlayer: AwesomePlayer create()
08-25 13:19:59.334   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:59.334   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:59.334   327  1385 V AwesomePlayer: setAudioSink() 
08-25 13:19:59.334   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:59.334   327  1385 V AudioCache: notify(0xb16a6900, 8, 0, 0)
08-25 13:19:59.334   327  1385 V AudioCache: ignored
08-25 13:19:59.334   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:59.334   327  1385 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 13:19:59.334   327  1385 V AwesomePlayer: setDataSource_l dataSource
08-25 13:19:59.334   327  1385 V LGParserOSAL: SniffLGParser start
08-25 13:19:59.334   327  1385 V LGParserOSAL: MainType:5, SubType=0
08-25 13:19:59.334   327  1385 V LGParserOSAL: #### check Mime : application/ogg
08-25 13:19:59.334   327  1385 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 13:19:59.334   327  1385 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 13:19:59.337  7767  7767 D UEI.SmartControl: QS Service created
08-25 13:19:59.337  8168  8168 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 13:19:59.339  8168  8168 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-25 13:19:59.339  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 13:19:59.358  8168  8168 V LGMDMManager: Create singleton instance
08-25 13:19:59.366  7767  7767 I UEI.SmartControl: Service initServices...
08-25 13:19:59.366  7767  7767 D UEI.SmartControl: QS start get config
08-25 13:19:59.372   327  1385 V LGParserOSAL: supported mime: application/ogg
08-25 13:19:59.372   327  1385 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 13:19:59.372   327  1385 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 13:19:59.372   327  1385 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 13:19:59.372   327  1385 V AwesomePlayer: AudioTrack Setting
08-25 13:19:59.372   327  1385 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 13:19:59.372   327  1385 V AwesomePlayer: setAudioSource() 
08-25 13:19:59.372   327  1385 V MediaPlayerService: prepare
08-25 13:19:59.372   327  1385 V AwesomePlayer: prepareAsync_l() 
08-25 13:19:59.372   327  1385 V MediaPlayerService: wait for prepare
08-25 13:19:59.372   327  8225 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 13:19:59.372   327  8225 V AwesomePlayer: initAudioDecoder() 
08-25 13:19:59.372   327  8225 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 13:19:59.372   327  8225 V AudioSystem: isOffloadSupported()
08-25 13:19:59.372   327  8225 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 13:19:59.372   327  8225 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 13:19:59.372   327  8225 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 13:19:59.372   327  8225 V AwesomePlayer: getUseOffload() = 0 
08-25 13:19:59.372   327  8225 V OMXCodec: OMXCodec::Create
08-25 13:19:59.372   327  8225 V OMXCodec: findMatchingCodecs()
08-25 13:19:59.372   327  8225 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 13:19:59.372   327  8225 V OMXCodec: matchingCodecs.size()=1
08-25 13:19:59.373   327  8225 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-25 13:19:59.374   327  8225 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 13:19:59.374   327  8225 V LGCodecAdapter: LG Codec Adapter start
08-25 13:19:59.374   327  8225 V OMXCodec: OMXCodec Createtor
08-25 13:19:59.374   327  8225 V OMXCodec: setComponentRole
08-25 13:19:59.374   327  8225 V OMXCodec: configureCodec protected=0
08-25 13:19:59.374   327  8225 V LGCodecAdapter: called getLGCodecSpecificData
08-25 13:19:59.374   327  8225 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 13:19:59.374   327  8225 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 13:19:59.374   327  8225 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 13:19:59.375   327  8225 V LGCodecOSAL: Not support LGCodec
08-25 13:19:59.375   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 13:19:59.375   327  8225 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 13:19:59.375   327  8225 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 13:19:59.375   327  8225 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 13:19:59.375   327  8225 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 13:19:59.375   327  8225 V AudioSystem: isOffloadSupported()
08-25 13:19:59.376   327  8225 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 13:19:59.376   327  8225 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 13:19:59.376   327  8225 V OMXCodec: init()
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 13:19:59.376   327  8225 V OMXCodec: allocateBuffers
08-25 13:19:59.376   327  8225 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb00101f0 on input port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010240 on input port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010920 on input port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010970 on input port
08-25 13:19:59.376   327  8225 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb00109c0 on output port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010a60 on output port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010ab0 on output port
08-25 13:19:59.376   327  8225 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010b50 on output port
08-25 13:19:59.376   327  8225 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 13:19:59.376   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 13:19:59.376   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 13:19:59.376   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 13:19:59.377   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 13:19:59.377   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 13:19:59.377   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-25 13:19:59.377   327  8225 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 13:19:59.377   327  8225 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 13:19:59.377   327  8225 V AudioCache: notify(0xb16a6900, 5, 0, 0)
08-25 13:19:59.377   327  8225 V AudioCache: ignored
08-25 13:19:59.377   327  8225 V AudioCache: notify(0xb16a6900, 1, 0, 0)
08-25 13:19:59.377   327  8225 V AudioCache: prepared
08-25 13:19:59.377   327  1385 V AudioCache: wait - success
08-25 13:19:59.377   327  1385 V MediaPlayerService: start
08-25 13:19:59.377   327  1385 V AwesomePlayer: play_l() 
08-25 13:19:59.377   327  1385 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 13:19:59.377   327  1385 V AwesomePlayer: createAudioPlayer_l
08-25 13:19:59.377   327  1385 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 13:19:59.377   327  1385 V AwesomePlayer: startAudioPlayer_l() 
08-25 13:19:59.377   327  1385 D AudioPlayer: start of Playback, useOffload 0
08-25 13:19:59.377   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 13:19:59.377   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 13:19:59.378  8205  8205 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-25 13:19:59.379   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 13:19:59.379   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,08-25 13:19:59.379   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 13:19:59.379   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 13:19:59.379   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 13:19:59.379   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 13:19:59.379   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952858048
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952858208
,08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952858288
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2952858448
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 13:19:59.380   327  8227 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010ab0 on output port
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0010a60 on output port
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb00109c0 on output port
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on output port
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 13:19:59.380   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 13:19:59.381   327  1385 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 13:19:59.382   327  1385 V AudioCache: notify(0xb16a6900, 6, 0, 0)
,08-25 13:19:59.382   327  1385 V AudioCache: ignored
08-25 13:19:59.382   327  1385 V MediaPlayerService: wait for playback complete
08-25 13:19:59.383   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.383   327  8230 V AudioCache: memcpy(0xac000000, 0xb57c5000, 4096)
08-25 13:19:59.385   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.385   327  8230 V AudioCache: memcpy(0xac001000, 0xb57c5000, 4096)
08-25 13:19:59.385   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.385   327  8230 V AudioCache: memcpy(0xac002000, 0xb57c5000, 4096)
08-25 13:19:59.385   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.385   327  8230 V AudioCache: memcpy(0xac003000, 0xb57c5000, 4096)
08-25 13:19:59.387   327  8230 V AudioCache: write(0xb57c5000, 4096)
,08-25 13:19:59.387   327  8230 V AudioCache: memcpy(0xac004000, 0xb57c5000, 4096)
08-25 13:19:59.387   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.387   327  8230 V AudioCache: memcpy(0xac005000, 0xb57c5000, 4096)
08-25 13:19:59.387   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.387   327  8230 V AudioCache: memcpy(0xac006000, 0xb57c5000, 4096)
08-25 13:19:59.387   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.387   327  8230 V AudioCache: memcpy(0xac007000, 0xb57c5000, 4096)
08-25 13:19:59.388   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.388   327  8230 V AudioCache: memcpy(0xac008000, 0xb57c5000, 4096)
08-25 13:19:59.388  1035  1106 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 13:19:59.388   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.388   327  8230 V AudioCache: memcpy(0xac009000, 0xb57c5000, 4096)
08-25 13:19:59.388  1035  1106 I ActivityManager: Killing 6766:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-25 13:19:59.389   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.389   327  8230 V AudioCache: memcpy(0xac00a000, 0xb57c5000, 4096)
08-25 13:19:59.390   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.390   327  8230 V AudioCache: memcpy(0xac00b000, 0xb57c5000, 4096)
08-25 13:19:59.391   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.391   327  8230 V AudioCache: memcpy(0xac00c000, 0xb57c5000, 4096)
08-25 13:19:59.392   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.392   327  8230 V AudioCache: memcpy(0xac00d000, 0xb57c5000, 4096)
08-25 13:19:59.392   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.392   327  8230 V AudioCache: memcpy(0xac00e000, 0xb57c5000, 4096)
08-25 13:19:59.393   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.393   327  8230 V AudioCache: memcpy(0xac00f000, 0xb57c5000, 4096)
08-25 13:19:59.394   327  8230 V AudioCache: write(0xb57c5000, 4096)
,08-25 13:19:59.394   327  8230 V AudioCache: memcpy(0xac010000, 0xb57c5000, 4096)
08-25 13:19:59.395   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.395   327  8230 V AudioCache: memcpy(0xac011000, 0xb57c5000, 4096)
08-25 13:19:59.395   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.395   327  8230 V AudioCache: memcpy(0xac012000, 0xb57c5000, 4096)
08-25 13:19:59.396   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.396   327  8230 V AudioCache: memcpy(0xac013000, 0xb57c5000, 4096)
08-25 13:19:59.397   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.397   327  8230 V AudioCache: memcpy(0xac014000, 0xb57c5000, 4096)
,08-25 13:19:59.397   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.397   327  8230 V AudioCache: memcpy(0xac015000, 0xb57c5000, 4096)
08-25 13:19:59.398   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.398   327  8230 V AudioCache: memcpy(0xac016000, 0xb57c5000, 4096)
08-25 13:19:59.399   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.399   327  8230 V AudioCache: memcpy(0xac017000, 0xb57c5000, 4096)
08-25 13:19:59.399   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.399   327  8230 V AudioCache: memcpy(0xac018000, 0xb57c5000, 4096)
08-25 13:19:59.400   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.400   327  8230 V AudioCache: memcpy(0xac019000, 0xb57c5000, 4096)
08-25 13:19:59.401   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.401   327  8230 V AudioCache: memcpy(0xac01a000, 0xb57c5000, 4096)
08-25 13:19:59.401   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.401   327  8230 V AudioCache: memcpy(0xac01b000, 0xb57c5000, 4096)
08-25 13:19:59.404   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.404   327  8230 V AudioCache: memcpy(0xac01c000, 0xb57c5000, 4096)
,08-25 13:19:59.405   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.405   327  8230 V AudioCache: memcpy(0xac01d000, 0xb57c5000, 4096)
08-25 13:19:59.406   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.406   327  8230 V AudioCache: memcpy(0xac01e000, 0xb57c5000, 4096)
08-25 13:19:59.407   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.407   327  8230 V AudioCache: memcpy(0xac01f000, 0xb57c5000, 4096)
08-25 13:19:59.408   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.408   327  8230 V AudioCache: memcpy(0xac020000, 0xb57c5000, 4096)
08-25 13:19:59.408   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.408   327  8230 V AudioCache: memcpy(0xac021000, 0xb57c5000, 4096)
08-25 13:19:59.409   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.409   327  8230 V AudioCache: memcpy(0xac022000, 0xb57c5000, 4096)
08-25 13:19:59.410   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.410   327  8230 V AudioCache: memcpy(0xac023000, 0xb57c5000, 4096)
08-25 13:19:59.410   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.410   327  8230 V AudioCache: memcpy(0xac024000, 0xb57c5000, 4096)
08-25 13:19:59.411   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.411   327  8230 V AudioCache: memcpy(0xac025000, 0xb57c5000, 4096)
08-25 13:19:59.411   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.411   327  8230 V AudioCache: memcpy(0xac026000, 0xb57c5000, 4096)
08-25 13:19:59.412   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.412   327  8230 V AudioCache: memcpy(0xac027000, 0xb57c5000, 4096)
08-25 13:19:59.412   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.412   327  8230 V AudioCache: memcpy(0xac028000, 0xb57c5000, 4096)
08-25 13:19:59.413   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.413   327  8230 V AudioCache: memcpy(0xac029000, 0xb57c5000, 4096)
08-25 13:19:59.413   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.413   327  8230 V AudioCache: memcpy(0xac02a000, 0xb57c5000, 4096)
08-25 13:19:59.414   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.414   327  8230 V AudioCache: memcpy(0xac02b000, 0xb57c5000, 4096)
08-25 13:19:59.415   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.415   327  8230 V AudioCache: memcpy(0xac02c000, 0xb57c5000, 4096)
08-25 13:19:59.415   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.415   327  8230 V AudioCache: memcpy(0xac02d000, 0xb57c5000, 4096)
08-25 13:19:59.416   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.416   327  8230 V AudioCache: memcpy(0xac02e000, 0xb57c5000, 4096)
08-25 13:19:59.416   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.416   327  8230 V AudioCache: memcpy(0xac02f000, 0xb57c5000, 4096)
08-25 13:19:59.417   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.417   327  8230 V AudioCache: memcpy(0xac030000, 0xb57c5000, 4096)
08-25 13:19:59.417   327  8230 V AudioCache: write(0xb57c5000, 4096)
08-25 13:19:59.417   327  8230 V AudioCache: memcpy(0xac031000, 0xb57c5000, 4096)
08-25 13:19:59.418   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 13:19:59.418   327  8230 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 13:19:59.418   327  8230 V AwesomePlayer: postAudioEOS() 
08-25 13:19:59.418   327  8230 V AudioCache: write(0xb57c5000, 280)
08-25 13:19:59.418   327  8230 V AudioCache: memcpy(0xac032000, 0xb57c5000, 280)
08-25 13:19:59.425   327  8225 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 13:19:59.425   327  8225 V AwesomePlayer: onStreamDone
08-25 13:19:59.425   327  8225 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 13:19:59.425   327  8225 V AudioCache: notify(0xb16a6900, 2, 0, 0)
08-25 13:19:59.425   327  8225 V AudioCache: playback complete
08-25 13:19:59.425   327  8225 V AwesomePlayer: pause_l() 
08-25 13:1,9:59.425   327  8225 V AudioCache: notify(0xb16a6900, 7, 0, 0)
08-25 13:19:59.425   327  8225 V AudioCache: ignored
08-25 13:19:59.425   327  8225 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:59.425   327  1385 V AudioCache: wait - success
08-25 13:19:59.425   327  1385 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 13:19:59.425   327  8225 D AudioPlayer: Pause Playback at 1068125
08-25 13:19:59.426   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:59.426   327  1385 V AudioCache: notify(0xb16a6900, 8, 0, 0)
08-25 13:19:59.426   327  1385 V AudioCache: ignored
08-25 13:19:59.426   327  1385 V AwesomePlayer: cancelPlayerEvents
,08-25 13:19:59.426   327  1385 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 13:19:59.426   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 13:19:59.426   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 13:19:59.426   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 13:19:59.426   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010970 on port 0
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010920 on port 0
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010240 on port 0
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb00101f0 on port 0
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 1
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb00109c0 on port 1
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010a60 on port 1
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 13:19:59.426   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0010ab0 on port 1
08-25 13:19:59.427   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 13:19:59.427   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 13:19:59.427   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 13:19:59.427   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 13:19:59.427   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 13:19:59.427   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 13:19:59.427   327  8227 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 13:19:59.427   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 13:19:59.427   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 13:19:59.427   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 13:19:59.428   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 13:19:59.428   327  1385 D AudioPlayer: AudioPlayer releasing audio source
08-25 13:19:59.428   327  1385 D AudioPlayer: AudioPlayer done releasing audio source
08-25 13:19:59.428   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:59.428   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:59.428   327  1385 V AwesomePlayer: ~AwesomePlayer call
08-25 13:19:59.428   327  1385 V AwesomePlayer: reset_l() 
08-25 13:19:59.428   327  1385 V AwesomePlayer: cancelPlayerEvents
08-25 13:19:59.428  8168  8224 V SoundPool: close(31)
08-25 13:19:,59.428  8168  8224 V SoundPool: pointer = 0x9ffe6000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 13:19:59.444  1035  1997 I WindowState: WIN DEATH: Window{3223f41b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 13:19:59.444  1035  1388 D WifiService: Client connection lost with reason: 4
08-25 13:19:59.445  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 13:19:59.448  1035  1997 D InputDispatcher: Window went away: Window{3223f41b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 13:19:59.531  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 13:19:59.546  1035  1375 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 13:19:59.546  1035  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 13:19:59.547  1035  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 13:19:59.547  1035  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 13:19:59.548  1035  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 13:19:59.548  1035  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 13:19:59.548  1035  1405 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-25 13:19:59.548  1035  1405 D ConnectivityService: identical MTU - not setting
08-25 13:19:59.549  1035  1405 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 13:19:59.549  1035  1405 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 13:19:59.549  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:19:59.549  1035  1405 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:59.549  1035  1405 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 13:19:59.549  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 13:19:59.601  1035  1106 E libprocessgroup: failed to kill 1 processes for processgroup 6766
08-25 13:19:59.606  1035  1106 I ActivityManager:   Force finishing activity ActivityRecord{32420904 u0 com.test.thalitest/.MainActivity t6}
,08-25 13:19:59.655   349   357 E GBMv2   : DFP En is all cleared set to be enabled
,08-25 13:19:59.659  1035  1560 W ActivityManager: Spurious death for ProcessRecord{1a328fec 6766:com.test.thalitest/u0a118}, curProc for 6766: null
08-25 13:19:59.660  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 13:19:59.661  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9914
08-25 13:19:59.662  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{32420904 u0 com.test.thalitest/.MainActivity t6 f}
08-25 13:19:59.662  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{32420904 u0 com.test.thalitest/.MainActivity t6 f}
08-25 13:19:59.676  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-25 13:19:59.681  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 13:19:59.683  1035  1365 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 13:19:59.684  3795  3795 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 13:19:59.684  7665  7665 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 13:19:59.684  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 13:19:59.684  4962  4962 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 13:19:59.685  4962  4962 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 13:19:59.685  4962  4962 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 13:19:59.685  4962  4962 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 13:19:59.685  4962  4962 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 13:19:59.685  4962  4962 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 13:19:59.685  4962  4962 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 13:19:59.685  4962  4962 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 13:19:59.685  4962  4962 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:19:59.685  4962  4962 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:19:59.685  4962  4962 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 13:19:59.685  4962  4962 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 13:19:59.687  2495  2670 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 13:19:59.692  8088  8088 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 13:19:59.693  1927  2060 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-25 13:19:59.693  1927  2060 D LEDHandler: Battery Level Remaining: 100%
08-25 13:19:59.693  1927  2060 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
,08-25 13:19:59.727  5055  5055 I art     : Explicit concurrent mark sweep GC freed 8253(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 688us total 58.992ms
,08-25 13:19:59.735  1035  1104 W InputMethodInfo: Duplicated subtype definition found: , voice
08-25 13:19:59.735  7767  7767 I UEI.SmartControl: Supports setup maps: true
08-25 13:19:59.738  7767  7767 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 13:19:59.738  7767  7767 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 13:19:59.738  7767  7767 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 13:19:59.738  7767  7767 I UEI.SmartControl: ### init IR Blaster...
08-25 13:19:59.741  1035  1889 V SIM_STK : Menu title from STK is T-Mobile
08-25 13:19:59.741  7767  7767 D serial_port: Configuring serial port
08-25 13:19:59.742  7767  7767 E UEI.SmartControl: UEIBLaster setting for 616
08-25 13:19:59.742  7767  7767 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 13:19:59.742  7767  7767 I UEI.SmartControl: configuring settings for MAXQ616
08-25 13:19:59.742  7767  7767 I UEI.SmartControl: Get version...
,08-25 13:19:59.752  1035  1035 D administrator: Handling package changes for user 0
08-25 13:19:59.762  7767  8231 D UEI.SmartControl: serial port data available: 21
,08-25 13:19:59.765  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.770  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 13:19:59.771  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{89c5758 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 13:19:59.772  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 13:19:59.772  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{333e30b1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 13:19:59.776  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 13:19:59.777  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-25 13:19:59.777  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-25 13:19:59.782  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 13:19:59.783  1586  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 13:19:59.783  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.784  2019  2059 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-25 13:19:59.786  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-25 13:19:59.787  7767  7767 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 13:19:59.787  7767  7767 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 13:19:59.787  7767  7767 I UEI.SmartControl: QS saving settings...
08-25 13:19:59.788  1586  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 13:19:59.788  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.788  7767  7767 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 13:19:59.788  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-25 13:19:59.788  1891  1891 D ActionManagerService: notifyUserLog: 1000003
08-25 13:19:59.789  3795  4854 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 13:19:59.789  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-25 13:19:59.790  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-25 13:19:59.794  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 13:19:59.794  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-25 13:19:59.795  3795  4854 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 13:19:59.796  3795  3810 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 13:19:59.799  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 13:19:59.799  1586  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:59.799  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 13:19:59.800  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 13:19:59.801  7767  8231 D UEI.SmartControl: serial port data available: 4
,08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , display: false
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , animation: false }
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , display: false
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , animation: false }
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , display: false
08-25 13:19:59.810  2019  2019 I GBoardWebViewUtils: , animation: false }
08-25 13:19:59.809  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 13:19:59.810  1586  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 13:19:59.812  1035  1771 V SIM_STK : Menu title from STK is T-Mobile
08-25 13:19:59.812  1035  1771 V SIM_STK : Menu title from STK is T-Mobile
08-25 13:19:59.814  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 13:19:59.814  1586  1586 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-25 13:19:59.815  1586  1586 I [SystemUI]LGPowerUI: On Skip Timer : true
08-25 13:19:59.815  1586  1586 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
,08-25 13:19:59.815  1586  1586 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-25 13:19:59.821  1586  1586 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-25 13:19:59.821  2019  8234 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 13:19:59.822  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-25 13:19:59.822  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.823  1586  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 13:19:59.823  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.827  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 13:19:59.827  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 13:19:59.828  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 13:19:59.828  1586  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 13:19:59.830  7767  7767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 13:19:59.831  7767  7767 E UEI.SmartControl: Services init done
08-25 13:19:59.831  7767  7767 D UEI.SmartControl: QS Service init finished
08-25 13:19:59.834  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 13:19:59.835  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-25 13:19:59.837  1586  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 13:19:59.837  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.844  1586  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:59.844  1586  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 13:19:59.844  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 13:19:59.844  1586  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 13:19:59.849  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-25 13:19:59.849  1856  1856 D SplitUIService: removed split : 
08-25 13:19:59.864  1035  2018 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 13:19:59.864  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 13:19:59.864  1586  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-25 13:19:59.864  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 13:19:59.865  7665  7665 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 13:19:59.865  7665  7915 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 13:19:59.866  1586  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 13:19:59.866  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.869  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-25 13:19:59.869  1856  1856 I SplitUIService: split app #11
08-25 13:19:59.871  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-25 13:19:59.871  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 13:19:59.877  1586  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 13:19:59.877  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.878  1586  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 13:19:59.878  1586  1651 D KeyguardModel: createShortcutInfo...
,08-25 13:19:59.880  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 13:19:59.880  1586  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 13:19:59.881  1586  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 13:19:59.881  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.883  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 13:19:59.883  1586  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 13:19:59.884  1586  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 13:19:59.884  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.887  7767  7767 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 13:19:59.887  7767  7767 D UEI.SmartControl: QS Service version code: 201091
,08-25 13:19:59.887  7767  7767 D UEI.SmartControl: Service requested: Control
08-25 13:19:59.888  8168  8168 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 13:19:59.889  7767  7784 I UEI.SmartControl: ------ IControl API: 11
08-25 13:19:59.889  7767  7784 D UEI.SmartControl: File observer start...
08-25 13:19:59.889  7767  7784 E UEI.SmartControl: IR Port is disabled: false
08-25 13:19:59.889  7767  7784 D UEI.SmartControl: Starting file observer...
08-25 13:19:59.889  1586  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 13:19:59.889  1586  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 13:19:59.890  7767  7784 I UEI.SmartControl: Registering callback...
08-25 13:19:59.892  1586  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 13:19:59.892  1586  1651 D KeyguardModel: createShortcutInfo...
08-25 13:19:59.894  7767  7767 D UEI.SmartControl: Internal service binding...
08-25 13:19:59.894  7767  7785 I UEI.SmartControl: ------ IControl API: 19
08-25 13:19:59.895  7767  7785 I UEI.SmartControl: Registering Services Ready callback...
,08-25 13:19:59.895  1035  2015 V SIM_STK : Menu title from STK is T-Mobile
08-25 13:19:59.899  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 13:19:59.903  7767  8237 I UEI.SmartControl: Device manager: loading config....
08-25 13:19:59.903  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.904  7767  8237 D UEI.SmartControl: ----------- loading internal config...
08-25 13:19:59.907  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.909  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 13:19:59.911  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.914  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.915  7767  8237 E UEI.SmartControl: Loading SETTINGS...
08-25 13:19:59.918  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.921  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 13:19:59.924  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 13:19:59.924  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-25 13:19:59.924  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 13:19:59.927  8106  8106 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 13:19:59.929  7767  8237 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 13:19:59.932  1804  1804 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-25 13:19:59.943  1804  1804 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-25 13:19:59.943  7767  8236 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 13:19:59.944  7767  8236 D UEI.SmartControl: -----service ready thread exits
08-25 13:19:59.944  8168  8186 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 13:19:59.945  2066  2066 I ConfigService: onCreate
08-25 13:19:59.945  8168  8222 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 13:19:59.945  8168  8222 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 13:19:59.946  2066  2066 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 13:19:59.946  8168  8168 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 13:19:59.946  8168  8168 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 13:19:59.946  7767  7784 I UEI.SmartControl: ------ IControl API: 8
08-25 13:19:59.947  8168  8168 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 13:19:59.948  8168  8168 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 13:19:59.948  8168  8168 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 13:19:59.948   338   451 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-25 13:19:59.948  8168  8168 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 13:19:59.948  8168  8168 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 13:19:59.949  8168  8168 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 13:19:59.949  3205  8241 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-25 13:19:59.952  8168  8168 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 13:19:59.953  8168  8168 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 13:19:59.954  1035  1703 I ActivityManager: Killing 7276:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-25 13:19:59.957  2066  2066 I ConfigService: onBind returning update interface
,08-25 13:19:59.978  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 13:19:59.978  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 13:19:59.978  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 13:19:59.986  1035  1123 I art     : Explicit concurrent mark sweep GC freed 22560(1555KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.765ms total 177.827ms
08-25 13:20:00.018  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-25 13:20:00.021  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 13:20:00.023  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 13:20:00.024  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 13:20:00.025  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 13:20:00.026  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 13:20:00.040  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 13:20:00.040  2019  2114 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 13:20:00.040  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 13:20:00.040  2019  2114 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-25 13:20:00.047  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:20:00.047  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:20:00.048  1035  1962 W libprocessgroup: failed to open /acct/uid_10005/pid_7276/cgroup.procs: No such file or directory
08-25 13:20:00.048  1035  1388 D WifiController: battery changed pluggedType: 2
08-25 13:20:00.048  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-25 13:20:00.048  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-25 13:20:00.048  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-25 13:20:00.048  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-25 13:20:00.049  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 13:20:00.049  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 13:20:00.050  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 13:20:00.050  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
08-25 13:20:00.054  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-25 13:20:00.055  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 13:20:00.055  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 13:20:00.056  2066  2066 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 13:20:00.056  2066  2066 I ConfigService: onBind returning config service
08-25 13:20:00.057  1035  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 13:20:00.057  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d44f8ed u0 com.lge.launcher2/.Launcher t5} time:206312
08-25 13:20:00.061  2066  2066 I ConfigService: onDestroy
08-25 13:20:00.063  8205  8205 D AndroidRuntime: Shutting down VM
08-25 13:20:00.064  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 13:20:00.064  1804  8244 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 13:20:00.065  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
08-25 13:20:00.065  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-25 13:20:00.068  2019  2019 D [Concierge]WidgetView: change position of spinner
08-25 13:20:00.068  2583  2583 D [Concierge]Service: Update widget ID : 11
08-25 13:20:00.071  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
08-25 13:20:00.071  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1472124000071
08-25 13:20:00.086  5901  8250 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-25 13:20:00.092  1804  8251 I PeopleContactsSync: CP2 sync disabled
08-25 13:20:00.096  1804  5258 I Icing   : doRemovePackageData com.test.thalitest
08-25 13:20:00.106  1804  8249 W GmsApplication: Using Auth Proxy for data requests.
,08-25 13:20:00.110  1804  8249 W GmsApplication: Using Auth Proxy for data requests.
08-25 13:20:00.128  2066  3878 I art     : Explicit concurrent mark sweep GC freed 6266(361KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 588us total 15.893ms
,08-25 13:20:00.139  1035  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 13:20:00.143  7075  7075 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-25 13:20:00.143  1035  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 13:20:00.148  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 57803956
08-25 13:20:00.149  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-25 13:20:00.149  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 13:20:00.151  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@225ac70
08-25 13:20:00.152  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-25 13:20:00.152  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 13:20:00.153  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 13:20:00.154  2387  8254 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-25 13:20:00.158  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 13:20:00.158  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 13:20:00.159  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-25 13:20:00.182  1035  1889 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8255 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-25 13:20:00.184  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472123821605, New one : 1472124000071
08-25 13:20:00.184  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-25 13:20:00.184  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 13:20:00.185  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 13:20:00.186  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 13:20:00.187  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 13:20:00.189  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 13:20:00.190  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-25 13:20:00.191  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 13:20:00.192  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 13:20:00.193  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 13:20:00.193  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 13:20:00.234  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-25 13:20:00.242  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 13:20:00.243  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-25 13:20:00.244  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 13:20:00.250  8255  8255 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:20:00.250  8255  8255 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 13:20:00.253  8255  8255 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-25 13:20:00.254  8255  8255 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 13:20:00.272  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ca79955 time:206527
,08-25 13:20:00.303  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8273 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-25 13:20:00.307  8255  8255 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-25 13:20:00.316  8255  8255 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 13:20:00.343  1035  2015 I ActivityManager: Killing 7695:com.google.android.talk/u0a72 (adj 15): empty #17
,08-25 13:20:00.347  8255  8255 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 13:20:00.389  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-25 13:20:00.424  2019  2901 I GBoardtInterface: onReloaded()
,08-25 13:20:00.426  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-25 13:20:00.477  1035  1772 W libprocessgroup: failed to open /acct/uid_10072/pid_7695/cgroup.procs: No such file or directory

```
