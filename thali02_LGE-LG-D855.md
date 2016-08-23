#### Test 81095569cb9dee4_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 18:36:00.094  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
08-23 18:36:00.104  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 18:36:00.104  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-23 18:36:00.106  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-23 18:36:00.108  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 18:36:09.128  6965  6965 D AndroidRuntime: 
08-23 18:36:09.128  6965  6965 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 18:36:09.136  6965  6965 D AndroidRuntime: CheckJNI is OFF
08-23 18:36:09.338  6965  6965 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 18:36:09.348  1033  1967 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 18:36:09.364  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 18:36:09.369  1033  1967 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 18:36:09.371  1033  1967 D ActivityManager: setTaskToReturnTo : TaskRecord{8c819cc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 18:36:09.371  1033  1967 D ActivityManager: setTaskToReturnTo : TaskRecord{8c819cc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 18:36:09.373  1033  1967 D WindowStateEx: AppWindowTokenEx init.. 
08-23 18:36:09.373   338   347 E GBMv2   : DFP En is all cleared set to be enabled
08-23 18:36:09.402  1033  1967 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6980 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 18:36:09.404  6965  6965 D AndroidRuntime: Shutting down VM
08-23 18:36:09.472  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 18:36:09.473  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ab259b1 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 18:36:09.474  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 18:36:09.474  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{252a4e96 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 18:36:09.586  1033  2013 I art     : Explicit concurrent mark sweep GC freed 40489(1885KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.605ms total 105.467ms
,08-23 18:36:09.652  6980  6980 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-23 18:36:09.753  6980  6980 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 18:36:09.763  6980  6980 I LibraryLoader: Loading: webviewchromium
,08-23 18:36:09.767  6980  6980 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5142-5146)
08-23 18:36:09.767  6980  6980 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 18:36:09.784  6980  6980 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30751f87}
08-23 18:36:09.786  6980  6980 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 18:36:09.786  6980  6980 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 18:36:09.797  6980  6980 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 18:36:09.798  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 18:36:09.809  6980  6980 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-23 18:36:09.809   318  1383 V AudioPolicyService: registerClient() client 0xb0410920, uid 10118
08-23 18:36:09.809  6980  6980 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 18:36:09.810  6980  6980 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-23 18:36:09.815  1033  1109 D BluetoothManagerService: Message: 20
,08-23 18:36:09.815  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cd487f6:true
08-23 18:36:09.828  6980  6980 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 18:36:09.828  6980  6980 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 18:36:09.828  6980  6980 I Adreno-EGL: Build Date: 12/12/14 금
08-23 18:36:09.828  6980  6980 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 18:36:09.828  6980  6980 I Adreno-EGL: Remote Branch: 
08-23 18:36:09.828  6980  6980 I Adreno-EGL: Local Patches: 
08-23 18:36:09.828  6980  6980 I Adreno-EGL: Reconstruct Branch: 
,08-23 18:36:09.901  6980  7014 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-23 18:36:09.908  6980  6980 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-23 18:36:09.923  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 18:36:09.928  6980  6980 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 18:36:09.933  6980  6980 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 18:36:09.935  6980  6980 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 18:36:09.935  6980  6980 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-23 18:36:09.947  6980  6980 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-23 18:36:09.953  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 18:36:09.953  6980  6980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 18:36:09.970  1033  1090 W ActivityManager: Activity pause timeout for ActivityRecord{34d75415 u0 com.test.thalitest/.MainActivity t6}
,08-23 18:36:09.991  6980  7027 D OpenGLRenderer: Render dirty regions requested: true
08-23 18:36:09.991  6980  7027 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 18:36:09.998  6980  7027 D OpenGLRenderer: Enabling debug mode 0
,08-23 18:36:10.004  6980  6980 D Atlas   : Validating map...
08-23 18:36:10.007  1033  1939 D SplitWindow: check instance of lgWin Window{23163200 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 18:36:10.039  6980  7025 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:10.039  6980  7025 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:10.110  1033  1110 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +640ms (total +736ms)
08-23 18:36:10.111  1033  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34d75415 u0 com.test.thalitest/.MainActivity t6} time:175491
08-23 18:36:10.111  6980  6980 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11dc3802 time:175491
,08-23 18:36:10.227  6980  6980 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 18:36:10.264  6980  6980 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 18:36:10.264  6980  6980 I chromium: 
,08-23 18:36:10.284  6980  7025 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 18:36:10.284  6980  7025 I chromium: 
,08-23 18:36:10.386  6980  7037 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-23 18:36:10.398  6980  7037 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 18:36:10.398  6980  7037 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 18:36:10.398  6980  7037 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 18:36:10.398  6980  7037 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 18:36:10.398  6980  7037 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 18:36:10.399  6980  7037 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17b9dd26 added. We now have 1 listener(s)
08-23 18:36:10.402  1033  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 18:36:10.404  6980  7037 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 18:36:10.407  6980  7037 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:10.408  6980  7037 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:10.408  6980  7037 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 18:36:10.413  6980  7037 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27636bbd added. We now have 1 listener(s)
08-23 18:36:10.414  6980  7037 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:10.419  1033  1542 D WifiService: New client listening to asynchronous messages
,08-23 18:36:10.423  6980  7037 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 18:36:10.424  6980  7037 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 18:36:10.424  6980  7037 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 18:36:10.424  6980  7037 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 18:36:10.424  6980  7037 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 18:36:10.427  6980  7037 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:10.428  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:10.428  6980  7037 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 18:36:10.435  6980  7037 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:10.435  6980  7037 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:10.435  6980  7037 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 18:36:10.435  6980  7037 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 18:36:10.438  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:10.439  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:10.439  6980  7037 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 18:36:10.465  6980  6980 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 18:36:11.344   338   349 E GBMv2   : DFP En is all cleared set to be enabled
08-23 18:36:11.344   338   349 E GBMv2   : Set value is all cleared set the max
08-23 18:36:11.344   338   349 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 18:36:11.373  6980  7040 W jxcore-log: Initializing JXcore engine
,08-23 18:36:11.373  6980  7040 W jxcore-log: JXcore engine is ready
,08-23 18:36:11.439  7040  7040 W Thread-817: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7509]" dev="sockfs" ino=7509 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-23 18:36:11.449  7040  7040 W Thread-817: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 18:36:11.449  7040  7040 W Thread-817: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8571]" dev="sockfs" ino=8571 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 18:36:11.449  7040  7040 W Thread-817: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 18:36:11.449  7040  7040 W Thread-817: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32740]" dev="sockfs" ino=32740 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-23 18:36:11.494  6980  7040 W jxcore-log: Starting JXcore engine
,08-23 18:36:11.643  6980  7040 W jxcore-log: Platform android
08-23 18:36:11.643  6980  7040 W jxcore-log: 
08-23 18:36:11.643  6980  7040 W jxcore-log: Process ARCH arm
08-23 18:36:11.643  6980  7040 W jxcore-log: 
,08-23 18:36:11.862  6980  7040 I jxcore-log: JXcore Cordova bridge is ready!
08-23 18:36:11.862  6980  7040 I jxcore-log: 
08-23 18:36:11.863  6980  7040 W jxcore-log: JXcore engine is started
,08-23 18:36:11.876  6980  7037 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 18:36:11.884  6980  6980 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 18:36:30.363  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 18:36:30.363  6980  7040 I jxcore-log: 
08-23 18:36:30.367  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 18:36:30.367  6980  7040 I jxcore-log: 
,08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:30.375  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:30.378  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:30.382  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 18:36:30.382  6980  7040 I jxcore-log: 
08-23 18:36:30.385  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 18:36:30.385  6980  7040 I jxcore-log: 
,08-23 18:36:31.351  6980  7040 D ExecuteNativeTests: Running unit tests
,08-23 18:36:31.487  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:31.487  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 added. We now have 2 listener(s)
,08-23 18:36:31.490  1033  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:31.493  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:31.493  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 18:36:31.493  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:31.493  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:31.493  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 added. We now have 2 listener(s)
08-23 18:36:31.493  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:31.494  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:36:31.497  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:31.501  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:36:31.506  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 18:36:31.506  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:31.508  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:31.510  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:31.513  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 18:36:31.516  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:36:31.516  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 18:36:31.522  6980  7040 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-23 18:36:31.524  6980  7040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 18:36:31.524  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:36:31.524  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:36:31.524  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:36:31.525  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.528  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.528  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.530  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:36:31.532  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.532  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:31.533  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:31.533  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 removed from the list
08-23 18:36:31.533  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.533  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 removed from the list
08-23 18:36:31.533  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.533  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.534  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.534  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.535  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.535  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.535  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.535  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.538  6980  7040 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-23 18:36:31.538  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.538  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.538  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.539  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.539  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.539  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.539  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.539  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.539  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.539  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.539  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.539  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.539  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMa,nager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.539  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.540  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.540  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.541  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.541  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
08-23 18:36:31.547  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 18:36:31.548  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-23 18:36:31.549  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.549  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.549  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.551  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-23 18:36:31.551  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.551  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.551  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
,08-23 18:36:31.551  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.551  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.552  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:36:31.552  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.552  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-23 18:36:31.552  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.552  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:36:31.564  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-23 18:36:31.564  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.564  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.564  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list,
08-23 18:36:31.565  6980  7040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 18:36:31.570  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:31.573  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:31.575  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.575  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:31.577  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:31.581  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:31.582  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:31.582  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:36:31.582  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:36:31.582  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.582  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:36:31.588  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:36:31.588  1033  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:31.595  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 18:36:31.604  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 18:36:31.607  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 18:36:31.609  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:36:31.609  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:31.612  6980  7040 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-23 18:36:31.613  6980  7040 I io.jxcore.node.ConnectionHelper: start: OK
08-23 18:36:31.618  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.618  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.618  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.619  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.619  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.619  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:31.619  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.619  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.619  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.619  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.619  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.620  6980  7040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 18:36:31.622  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:31.626  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:36:31.629  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.629  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:31.632  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:31.634  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:31.634  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:31.634  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:36:31.634  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:36:31.634  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.634  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:36:31.639  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:36:31.641  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:31.643  6980  7040 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 18:36:31.643  6980  7040 I io.jxcore.node.ConnectionHelper: start: OK
08-23 18:36:31.645  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.645  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.645  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.646  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.646  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.646  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:31.646  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.646  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.646  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.646  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.646  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.647  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.647  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.648  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.648  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.650  6980  7040 D BluetoothLeScanner: could not find callback wrapper
,08-23 18:36:31.652  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.652  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.652  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.654  6980  7040 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 18:36:31.656  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:31.659  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:31.661  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.661  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:31.663  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:31.666  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:31.667  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:31.667  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:36:31.667  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:36:31.667  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.667  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:36:31.672  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:36:31.672  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:31.674  6980  7040 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-23 18:36:31.676  6980  7040 I io.jxcore.node.ConnectionHelper: start: OK
08-23 18:36:31.676  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.676  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.676  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.677  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.677  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.677  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.678  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.678  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.678  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:31.678  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.678  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.678  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.678  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.678  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.679  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.679  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.681  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.681  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.681  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.681  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.681  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.681  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.682  6980  7040 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-23 18:36:31.682  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.682  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.682  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.683  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 18:36:31.683  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.683  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.683  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.683  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.683  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list,
08-23 18:36:31.683  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.683  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.683  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.683  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-23 18:36:31.683  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.685  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.685  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:36:31.685  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.685  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.685  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.685  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list,
08-23 18:36:31.687  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 18:36:31.687  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.687  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 18:36:31.687  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 18:36:31.694  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.694  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.694  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.694  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.694  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.694  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.694  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.694  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.694  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.695  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.695  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.696  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.696  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.697  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.697  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.697  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.697  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.698  6980  7040 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-23 18:36:31.698  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.698  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.699  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.699  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.699  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.699  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.699  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.699  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.699  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.699  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.699  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The g,iven listener does not exist in the list - probably already removed
08-23 18:36:31.699  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.699  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.699  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.704  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.704  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.705  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.705  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.705  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.705  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.706  6980  7040 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-23 18:36:31.706  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.706  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.706  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.707  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.707  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.707  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.707  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.707  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.707  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.707  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.707  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.707  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.707  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.707  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.709  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.709  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.709  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.709  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.709  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.710  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.710  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 18:36:31.712  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:36:31.712  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:36:31.712  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:36:31.713  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 18:36:31.713  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 18:36:31.713  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.713  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.713  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.718  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.718  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.718  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.718  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.718  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.718  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.718  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.718  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.718  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.718  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.718  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.722  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.722  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.724  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.724  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.724  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.726  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
,08-23 18:36:31.730  6980  7040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:36:31.730  6980  7040 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 18:36:31.731  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 18:36:31.734  6980  7040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:36:31.734  6980  7040 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 18:36:31.734  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 18:36:31.735  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 18:36:31.735  6980  7040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 18:36:31.735  6980  7040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:36:31.736  6980  7040 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 18:36:31.736  6980  7040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:36:31.736  6980  7040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:36:31.736  6980  7040 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 18:36:31.736  6980  7040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:36:31.736  6980  7040 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 18:36:31.736  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-23 18:36:31.739  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 18:36:31.747  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 18:36:31.747  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-23 18:36:31.748  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 18:36:31.748  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 18:36:31.749  6980  7040 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 18:36:31.749  6980  7040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 18:36:31.749  6980  7040 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 18:36:31.749  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.749  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.749  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.751  6980  7077 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 881)
08-23 18:36:31.761  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.761  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.761  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.761  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-23 18:36:31.762  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.762  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.762  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.762  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.762  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.762  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.762  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.762  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:36:31.766  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.766  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.767  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.767  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.767  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.767  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.768  6980  7040 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 18:36:31.768  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.768  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.768  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.770  6980  7078 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 881
08-23 18:36:31.770  6980  7078 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 881)
08-23 18:36:31.770  6980  7078 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 881)
08-23 18:36:31.771  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.771  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.771  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.771  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.771  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.771  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.771  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.771  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.771  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.771  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.771  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.772  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.772  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.774  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.774  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.774  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.774  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.775  6980  7040 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 18:36:31.775  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.775  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.775  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.779  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.780  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.780  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.780  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.780  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.783  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.783  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.783  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.783  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.787  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.787  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.788  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.788  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.791  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.791  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.791  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.791  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.792  6980  7040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 18:36:31.792  6980  7040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 18:36:31.792  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:36:31.792  6980  7040 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 18:36:31.792  6980  7040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 18:36:31.792  6980  7040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 18:36:31.792  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:36:31.792  6980  7040 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 18:36:31.792  6980  7040 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 18:36:31.792  6980  7040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 18:36:31.792  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:36:31.793  6980  7040 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 18:36:31.793  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.793  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.793  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.794  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.794  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.794  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.794  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.794  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.794  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.794  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.794  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.794  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.794  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.794  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.795  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.795  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.796  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.796  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.796  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.796  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.796  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.796  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.796  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.797  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.797  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.797  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.797  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.797  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.797  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.797  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.797  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.797  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.797  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.797  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.797  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.797  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.797  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.797  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.798  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.798  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.798  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.798  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.798  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.798  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.798  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.798  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.798  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.798  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.798  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.800  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.800  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 18:36:31.804  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.804  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.804  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.805  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.806  6980  7040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 18:36:31.806  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.810  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-23 18:36:31.811  6980  7040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 18:36:31.811  6980  7040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 18:36:31.811  6980  6980 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 18:36:31.812  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 18:36:31.812  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 18:36:31.813  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.813  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 18:36:31.813  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 18:36:31.813  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 18:36:31.813  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.813  6980  7040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 18:36:31.813  6980  6980 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 18:36:31.813  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.813  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.813  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 18:36:31.813  6980  7040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 18:36:31.813  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 18:36:31.814  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 18:36:31.815  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:31.815  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:31.815  6980  7040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 18:36:31.815  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.815  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.816  6980  7087 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 18:36:31.817  6980  7040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:36:31.817  6980  6980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:36:31.817  6980  6980 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 18:36:31.817  6980  6980 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 18:36:31.818  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.818  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.818  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.818  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.818  6980  7087 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 18:36:31.818  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.818  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.819  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.819  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.819  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.819  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.819  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.819  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.819  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.819  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.819  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.820  6980  6980 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 18:36:31.820  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.820  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.820  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.820  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.821  6980  7040 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 18:36:31.830  6980  7040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 18:36:31.830  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 18:36:31.834  6980  7040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 18:36:31.835  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.835  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.835  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.835  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.836  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.836  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.836  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.836  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.836  6980  7077 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-23 18:36:31.836  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.836  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.836  6980  7077 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 881)
08-23 18:36:31.836  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.836  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.836  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.836  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.839  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.839  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.839  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.839  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.843  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:31.844  1033  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:31.844  1033  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:31.845  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.845  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.845  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:31.845  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.845  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.845  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.845  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.845  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.845  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.845  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.845  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.845  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.845  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.845  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.846  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.846  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.846  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.846  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.847  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:31.847  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:31.847  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 18:36:31.847  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:31.847  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.847  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.847  6980  7040 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e21e76 not in the list
08-23 18:36:31.847  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.847  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.847  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:31.847  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.847  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.847  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:31.847  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:31.848  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:31.848  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:31.848  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:31.849  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d31c77 not in the list
08-23 18:36:31.850  6980  7040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 18:36:31.850  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:36:31.850  6980  7040 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 18:36:31.850  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 18:36:31.850  6980  7040 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 18:36:31.850  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 18:36:31.852  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 18:36:31.852  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-23 18:36:31.853  6980  7040 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 18:36:31.853  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 18:36:31.853  6980  7040 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 18:36:31.853  6980  7040 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 18:36:31.853  6980  7040 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 18:36:31.853  6980  7040 D io.jxcore.node.Connecti,onModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 18:36:31.854  6980  7040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 18:36:31.854  6980  7040 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 18:36:31.854  6980  7040 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 18:36:31.854  6980  7040 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 18:36:31.854  6980  7040 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 18:36:31.854  6980  7040 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-23 18:36:31.855  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:31.855  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35f4187c added. We now have 2 listener(s)
08-23 18:36:31.855  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:31.856  6980  7040 D BluetoothAdapter: enable(): BT is already enabled..!
08-23 18:36:31.858  1033  1970 D WifiServiceImplEx: setWifiEnabled: true pid=6980, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 18:36:31.859  1033  1970 D WifiService: setWifiEnabled: true pid=6980, uid=10118
08-23 18:36:31.859  1033  1970 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 18:36:31.860  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:31.860  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44c6505 added. We now have 3 listener(s)
08-23 18:36:31.860  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:36:31.865  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:31.865  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22cb95a added. We now have 4 listener(s)
08-23 18:36:31.865  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:31.866  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:31.866  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@320878b added. We now have 5 listener(s)
08-23 18:36:31.866  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:31.868  1033  1939 D WifiServiceImplEx: setWifiEnabled: false pid=6980, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 18:36:31.869  1033  1939 D WifiService: setWifiEnabled: false pid=6980, uid=10118
08-23 18:36:31.869  1033  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 18:36:31.884  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:31.884  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-23 18:36:31.884  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-23 18:36:31.885  1033  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:31.885  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:31.885  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:31.885  1033  1938 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@360f5c63 mBinding = false
08-23 18:36:31.886  1033  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:31.886  1033  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:31.886  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:31.886  1033  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 18:36:31.887  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:36:31.887  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 18:36:31.888  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 18:36:31.888  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 18:36:31.896  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 18:36:31.896  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:36:31.897  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:31.897  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 18:36:31.897  2687  2687 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 18:36:31.897  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 18:36:31.898  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:31.898  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
08-23 18:36:31.898  1033  2818 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:31.899   311   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:36:31.901  1033  1109 D BluetoothManagerService: Message: 2
08-23 18:36:31.902  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:31.902  1033  1109 D BluetoothManagerService: Sending off request.
08-23 18:36:31.903  4362  4383 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-23 18:36:31.903  4362  4437 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-23 18:36:31.903  4362  4437 D BluetoothAdapterProperties: Setting state to 13
08-23 18:36:31.903  4362  4437 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 18:36:31.904  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:31.904  4362  4437 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 18:36:31.904  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-23 18:36:31.904  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-23 18:36:31.904  4362  4437 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-23 18:36:31.905  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 18:36:31.905  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-23 18:36:31.908  4362  4362 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:31.908  4362  4362 D BluetoothMapService: STATE_TURNING_OFF
08-23 18:36:31.908  4362  4362 V BluetoothMapService: Handler(): got msg=4
08-23 18:36:31.908  4362  4362 D BluetoothMapService: MAP Service closeService in
08-23 18:36:31.908  4362  4362 D BluetoothMapMasInstance: MAP Service shutdown
08-23 18:36:31.908  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-23 18:36:31.910  4362  4760 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-23 18:36:31.910  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-23 18:36:31.910  4362  4362 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 18:36:31.910  4362  4362 V BluetoothMapService: MAP Service closeService out
08-23 18:36:31.912  4362  4362 V BtOppService: Receiver DISABLED_ACTION ,
08-23 18:36:31.912  4362  4362 I BtOppRfcommListener: stopping Accept Thread
08-23 18:36:31.912  4362  4362 V BtOppRfcommListener: close mBtServerSocket
08-23 18:36:31.912  4362  4799 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:31.913  4362  4362 V BtOppRfcommListener: waiting for thread to terminate
08-23 18:36:31.913  4362  4799 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 18:36:31.914  4362  4362 V BtOppRfcommListener: done waiting for thread to terminate
,08-23 18:36:31.916  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:31.916  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:31.919  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:31.919  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:31.940  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 18:36:31.941  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-23 18:36:31.949  1033  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7102 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 18:36:31.951  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:31.953  4362  4441 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:36:31.956  4362  4362 V BtOppService: onDestroy
08-23 18:36:31.956  4362  4437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 18:36:31.957  4362  4437 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 18:36:31.958  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-23 18:36:31.958  4362  4524 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-23 18:36:31.959  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-23 18:36:31.959  4362  4524 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 18:36:31.960  4362  4800 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:31.961  4362  4802 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:31.961  4362  4762 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:31.965  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:31.965  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:31.966  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:31.966  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:31.966  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:31.969  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:31.969  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:31.969  698,0  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:31.969  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:31.969  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:31.969  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:31.969  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:31.969  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:31.969  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:36:31.970  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:31.970  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:31.978  1033  1049 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-23 18:36:31.979  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:31.979  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:31.979  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-23 18:36:31.980  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:31.980  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-23 18:36:31.981  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:31.986  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:31.989  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:31.991  1033  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-23 18:36:31.991  1033  1543 D DSQN    : disableDataServiceNotify
08-23 18:36:31.991   311  7116 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-23 18:36:31.991  1033  1543 D DSQN    : stop dsqn bin
08-23 18:36:31.992  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-23 18:36:31.992  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-23 18:36:31.997  1033  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-23 18:36:31.997  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:31.997  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:31.997  1033  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:31.997  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-23 18:36:31.998  1033  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-23 18:36:31.998  1033  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-23 18:36:31.998  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 18:36:31.999  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:31.999  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:31.999  1601  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-23 18:36:31.999  1033  2816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-23 18:36:32.002  1033  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7122 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-23 18:36:32.003  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:32.003  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 18:36:32.004  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:32.004  1033  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:32.004  1033  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 18:36:32.005  4362  4362 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-23 18:36:32.006  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.006  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.007  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.007  1033  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 18:36:32.007  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.008  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.008  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.008  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-23 18:36:32.009  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.009  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.009  1033  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.009  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.009  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:32.009  1033  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1318d37d
08-23 18:36:32.009  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-23 18:36:32.009  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.009  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.010  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.010  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.011  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-23 18:36:32.011  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:32.011  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:32.012  1033  1543 D NetworkManagementService: Removing idletimer
08-23 18:36:32.012  1033  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.012  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 18:36:32.013  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 18:36:32.013  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 18:36:32.014  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 18:36:32.014  1033  1535 D LGWifiP2pService: P2pDisablingState
08-23 18:36:32.014  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 18:36:32.014  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-23 18:36:32.014  1033  1535 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.014  1033  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.014  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 18:36:32.014  1033  1535 D LGWifiP2pService: p2p socket connection lost
08-23 18:36:32.014  1033  1535 D LGWifiP2pService: P2pDisabledState
08-23 18:36:32.014  1033  ,1555 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.014  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:32.015  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 18:36:32.015  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 18:36:32.015  1941  1941 D WfdsService: WifiP2pState is changed : false
08-23 18:36:32.015  1941  2256 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-23 18:36:32.015  1941  2256 D WfdsService: Set the WFDS Monitor: false
08-23 18:36:32.016  1941  2256 D WfdsMonitor: WFDS Monitor is stopped
08-23 18:36:32.016  1941  2256 D WfdsService: STATE : WfdsDisabledState - enter
08-23 18:36:32.016  1941  2744 D CtrlSupplicant: Received on exit socket, terminate
08-23 18:36:32.016  1941  2744 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-23 18:36:32.016  1941  2257 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-23 18:36:32.016  1941  2744 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-23 18:36:32.016  1941  2744 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-23 18:36:32.016  1941  2256 W WfdsService: DefaultState - msg [9445378] is not handled
08-23 18:36:32.018  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 18:36:32.018  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 18:36:32.018  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 18:36:32.018  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 18:36:32.018  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-23 18:36:32.019  1033  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 18:36:32.020  1033  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:32.020  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:32.020  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-23 18:36:32.020  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.020  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.021  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 18:36:32.021  2687  2687 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 18:36:32.024  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 18:36:32.024  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:32.025  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
08-23 18:36:32.025   311   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:36:32.026  1033  1536 D WifiNative-p2p0: doBoolean: TERMINATE
08-23 18:36:32.027  1033  1536 D WifiNative-p2p0: TERMINATE: returned true
08-23 18:36:32.027  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:32.027  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:32.027  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-23 18:36:32.032  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:32.032  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:32.033  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.034  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-23 18:36:32.038  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-23 18:36:32.038  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.038  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.039  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:32.041  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-23 18:36:32.041  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:32.041  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-23 18:36:32.042  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:32.042  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:32.043  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:32.043  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:32.044  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:32.044  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:32.044  6980  6980 W org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:32.045  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:36:32.056  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:32.056  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:32.056  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.058  7102  7102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:36:32.058  7102  7102 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 18:36:32.058  7102  7102 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 18:36:32.059  7102  7102 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-23 18:36:32.060  7102  7102 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 18:36:32.060  7102  7102 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 18:36:32.071  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:32.072  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.072  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.085  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:32.086  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:32.086  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.089  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 18:36:32.089  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:32.090  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.092  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.120  7122  7122 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 18:36:32.120  7122  7122 W LG Account v2.2: No ProfileInfo entries
08-23 18:36:32.120  7122  7122 I LG Account v2.2: isEnabled: false
,08-23 18:36:32.120  7122  7122 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-23 18:36:32.120  7122  7122 I Feature : [Lifetracker]Country: EU
08-23 18:36:32.120  7122  7122 I Feature : [Lifetracker]Operator: OPEN
08-23 18:36:32.120  7122  7122 I Feature : [Lifetracker]Ranking support: false
08-23 18:36:32.120  7122  7122 I Feature : [Lifetracker]Comfort support: false
08-23 18:36:32.120  7122  7122 I Feature : [Lifetracker]Accessory: true
08-23 18:36:32.120  7122  7122 I Feature : [Lifetracker]Health device: true
08-23 18:36:32.121  7122  7122 I Feature : [Lifetracker]Extra Pedometer: false
08-23 18:36:32.121  7122  7122 I Feature : [Lifetracker]Blood glucose device: false
08-23 18:36:32.121  7122  7122 I Feature : [Lifetracker]Device Number: 3
08-23 18:36:32.123  1033  2818 D DhcpStateMachine: StoppedState
08-23 18:36:32.123  1033  2818 D DhcpStateMachine: StoppedState{ when=-99ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:32.125  1033  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-23 18:36:32.125  1033  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-23 18:36:32.128  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:32.131  2687  2687 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 18:36:32.131  2687  2687 I wpa_supplicant: monitor socket send errors count : 1
,08-23 18:36:32.131  2687  2687 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
08-23 18:36:32.133  1033  2736 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-23 18:36:32.133  1033  2736 D WifiMonitor: Dropping event because (p2p0) is stopped
08-23 18:36:32.141  7102  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 18:36:32.166  1033  1574 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 18:36:32.166  1033  1574 I ActivityManager: Killing 6361:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-23 18:36:32.171  2687  2687 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 18:36:32.173  1033  1109 D Tethering: InitialState.processMessage what=4
08-23 18:36:32.174  1033  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-23 18:36:32.174  1033  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 18:36:32.174  1033  2736 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 18:36:32.174  2687  2687 W wpa_supplicant: USIM:  scard_deinit function
08-23 18:36:32.174  1033  2736 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-23 18:36:32.174  1033  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:32.174  1033  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:32.175  1033  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197540
08-23 18:36:32.176  1033  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=197541
08-23 18:36:32.177  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=197542  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 18:36:32.177  1033  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=197542  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 18:36:32.213  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-23 18:36:32.213  1033  1939 W libprocessgroup: failed to open /acct/uid_10014/pid_6361/cgroup.procs: No such file or directory
08-23 18:36:32.225  1033  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:32.225  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-23 18:36:32.227  1033  1109 D BluetoothManagerService: Message: 20
08-23 18:36:32.227  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@196d49ea:true
08-23 18:36:32.229  4362  4362 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 18:36:32.229  4362  4362 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:32.229  4362  4362 V BluetoothPbapReceiver: ***********state = 13
08-23 18:36:32.231  4362  4362 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-23 18:36:32.232  4362  4362 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:32.232  4362  4362 V BluetoothPbapService: state: 13
08-23 18:36:32.232  4362  4362 V BluetoothPbapService: Pbap Service closeService in
08-23 18:36:32.235  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:36:32.236  4362  4362 V BluetoothPbapService: successfully stopped pbap service
08-23 18:36:32.236  4362  4362 V BluetoothPbapService: Pbap Service closeService out
08-23 18:36:32.236  4362  4362 V BluetoothPbapService: Pbap Service onDestroy
08-23 18:36:32.236  4362  4362 V BluetoothPbapService: Pbap Service closeService in
08-23 18:36:32.236  4362  4362 V BluetoothPbapService: Pbap Service closeService out
08-23 18:36:32.236  4362  4362 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-23 18:36:32.242  1033  1109 D BluetoothManagerService: Message: 30
,08-23 18:36:32.247  1033  1109 D BluetoothManagerService: Message: 30
08-23 18:36:32.249  7102  7102 D LocalBluetoothProfileManager: Adding local MAP profile
08-23 18:36:32.251  7102  7102 D BluetoothMap: Create BluetoothMap proxy object
08-23 18:36:32.251  1033  1109 D BluetoothManagerService: Message: 30
08-23 18:36:32.255  1033  1109 D BluetoothManagerService: Message: 30
,08-23 18:36:32.258  7102  7102 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-23 18:36:32.259  7102  7102 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-23 18:36:32.262  2687  2687 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-23 18:36:32.263  1033  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-23 18:36:32.263  1033  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-23 18:36:32.263  1033  2736 D WifiMonitor: Disconnecting from the supplicant, no more events
08-23 18:36:32.263  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-23 18:36:32.271  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-23 18:36:32.274  7102  7102 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-23 18:36:32.277  7102  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-23 18:36:32.279  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:32.279  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:32.281  1033  1049 I ActivityManager: Killing 6432:com.android.defcontainer/u0a4 (adj 15): empty #17
08-23 18:36:32.312  1033  1653 W libprocessgroup: failed to open /acct/uid_10004/pid_6432/cgroup.procs: No such file or directory
08-23 18:36:32.313  7102  7102 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:36:32.318  6980  6980 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 18:36:32.334  7102  7102 D BluetoothInputDevice: Proxy object connected
,08-23 18:36:32.335  7102  7102 D HidProfile: Bluetooth service connected
,08-23 18:36:32.336  7102  7102 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 18:36:32.337  7102  7102 D PanProfile: Bluetooth service connected
08-23 18:36:32.338  7102  7102 D BluetoothMap: Proxy object connected
08-23 18:36:32.339  7102  7102 D MapProfile: Bluetooth service connected
08-23 18:36:32.339  7102  7102 D BluetoothMap: getConnectedDevices()
08-23 18:36:32.340  7102  7102 D BluetoothMap: Bluetooth is Not enabled
08-23 18:36:32.340  7102  7102 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-23 18:36:32.354  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:32.365  1033  1536 D WifiOffDelayIfNotUsed: stopMonitoring
08-23 18:36:32.365  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:32.365  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:32.365  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 18:36:32.366  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-23 18:36:32.367  1941  2256 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-23 18:36:32.367  1941  2256 D WfdsService: Set the WFDS Monitor: false
08-23 18:36:32.367  1941  2256 D WfdsMonitor: WFDS Monitor is stopped
08-23 18:36:32.369  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-23 18:36:32.369  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:32.370  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 18:36:32.371  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-23 18:36:32.371  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-23 18:36:32.373  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:32.374  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:32.377  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:32.412  7102  7102 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:32.412  7102  7102 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:32.422  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 18:36:32.426  7102  7102 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-23 18:36:32.431  7102  7102 D BluetoothPermissionRequest: onReceive
08-23 18:36:32.434  7102  7102 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 18:36:32.444  1033  1977 I ActivityManager: Killing 6609:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-23 18:36:32.447  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 18:36:32.534  1033  1938 W libprocessgroup: failed to open /acct/uid_10008/pid_6609/cgroup.procs: No such file or directory
08-23 18:36:32.536  4362  4362 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-23 18:36:32.536  4362  4362 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-23 18:36:32.539  4362  4362 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-23 18:36:32.644  1033  1967 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7172 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-23 18:36:32.646  4362  4362 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:32.647  4362  4362 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-23 18:36:32.654  4362  4362 V BluetoothFtpService: Ftp Service onStartCommand
08-23 18:36:32.654  4362  4362 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:32.655  4362  4362 V BluetoothFtpService: Ftp Service closeService
08-23 18:36:32.655  4362  4362 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-23 18:36:32.656  4362  4362 V BluetoothFtpService: successfully stopped ftp service
08-23 18:36:32.657  4362  4362 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:32.657  4362  4362 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:32.657  4362  4362 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:32.657  4362  4362 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:32.657  4362  4362 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-23 18:36:32.657  4362  4362 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 18:36:32.659  4362  4362 V BluetoothFtpService: Ftp Service onDestroy
08-23 18:36:32.659  4362  4362 V BluetoothFtpService: Ftp Service closeService
08-23 18:36:32.706  1033  1574 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7192 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 18:36:32.706  4362  4362 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:32.706  4362  4362 V BluetoothSapService: state: 13
08-23 18:36:32.707  4362  4362 V BluetoothSapService: Stopping SAP server process
08-23 18:36:32.709  4362  4362 V BluetoothSapService: Sap Service closeSapService in
08-23 18:36:32.709  4362  4362 V BluetoothSapService: Close listen Socket : 
08-23 18:36:32.709  4362  4362 V BluetoothSapService: Close rfcomm Socket : 
08-23 18:36:32.710  4362  4362 V BluetoothSapService: Close sapd  Socket : 
,08-23 18:36:32.711  4362  4362 V BluetoothSapService: Sap Service closeSapService out
08-23 18:36:32.711  4362  4362 V BluetoothSapService: Sap Service onDestroy
08-23 18:36:32.711  4362  4362 V BluetoothSapService: Sap Service closeSapService in
08-23 18:36:32.711  4362  4362 V BluetoothSapService: Close listen Socket : 
08-23 18:36:32.711  4362  4362 V BluetoothSapService: Close rfcomm Socket : 
08-23 18:36:32.712  4362  4362 V BluetoothSapService: Close sapd  Socket : 
08-23 18:36:32.712  4362  4362 V BluetoothSapService: Sap Service closeSapService out
,08-23 18:36:32.744  7172  7172 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 18:36:32.771  7172  7172 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-23 18:36:32.777  7192  7192 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 18:36:32.793  1033  1920 I ActivityManager: Killing 6653:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-23 18:36:32.805  7172  7172 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-23 18:36:32.805  7172  7172 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-23 18:36:32.805  7172  7172 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-23 18:36:32.805  7172  7172 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-23 18:36:32.806  7172  7172 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-23 18:36:32.807  7172  7172 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-23 18:36:32.812  7172  7172 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-23 18:36:32.846  1033  1782 W libprocessgroup: failed to open /acct/uid_10011/pid_6653/cgroup.procs: No such file or directory
,08-23 18:36:32.865  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:32.874  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 18:36:32.919  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:32.925  7172  7172 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-23 18:36:32.927  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:32.931  7172  7172 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-23 18:36:32.935  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 18:36:32.935  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:32.935  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:32.943  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:32.952  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 18:36:32.964  4362  4441 D bt_hci_bdroid: cleanup
08-23 18:36:32.965  4362  4526 I bt_lpm  : LPM is already off!!!
08-23 18:36:32.965  4362  4726 I bt_userial_mct: exiting userial_read_thread
08-23 18:36:32.965  4362  4726 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 18:36:32.965  4362  4524 W bt-btif : ag scb idx 1 not allocated
08-23 18:36:32.965  4362  4524 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:32.965  4362  4524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:32.966  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:32.966  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 18:36:32.966  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:32.966  4362  4524 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:32.966  4362  4524 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:32.966  4362  4524 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:32.966  4362  4524 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 18:36:32.966  4362  4441 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 18:36:32.966  4362  4526 I bt_vendor: hw_epilog_process
08-23 18:36:32.967  4362  4441 D bt_hci_bdroid: cleanup Finalizing cleanup
08-23 18:36:32.967  4362  4441 D bt_userial_mct: userial_close
08-23 18:36:32.967  4362  4441 E bt_userial_mct: pthread_join() FAILED result:3
08-23 18:36:32.967  4362  4441 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-23 18:36:32.969  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:32.971  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:32.974  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:32.977  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:32.982  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 18:36:32.982  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:32.982  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:32.987  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:32.997  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 18:36:33.008  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:33.009  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:33.013  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:33.022  4362  4441 D bt_hci_bdroid: set_power 0
,08-23 18:36:33.022  4362  4441 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 18:36:33.022  4362  4441 I bt_vendor: bluetooth satus is on
08-23 18:36:33.022  4362  4441 I bt_vendor: bt-vendor : resetting BT status
08-23 18:36:33.022  4362  4441 I bt_vendor: Starting hciattach daemon
08-23 18:36:33.022  4362  4441 I bt_vendor: try to set false
08-23 18:36:33.024  4362  4441 I bt_vendor: Starting hciattach daemon
08-23 18:36:33.024  4362  4441 I bt_vendor: try to set false
08-23 18:36:33.027  4362  4441 I bt_vendor: cleanup
08-23 18:36:33.028  4362  4524 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 18:36:33.028  4362  4441 I GKI_LINUX: GKI_exit_task 0 done
08-23 18:36:33.028  4362  4441 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 18:36:33.030  4362  4437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 18:36:33.081  1033  1970 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7213 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-23 18:36:33.091  4362  4362 D HeadsetService: Received stop request...Stopping profile...
08-23 18:36:33.092  4362  4362 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 18:36:33.092  4362  4362 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:36:33.092  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ae3beb4
08-23 18:36:33.093  4362  4480 D HeadsetStateMachine: Exit Disconnected: -1
08-23 18:36:33.095  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-23 18:36:33.096  1852  1852 D BluetoothHeadset: Proxy object disconnected
,08-23 18:36:33.096  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-23 18:36:33.097  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-23 18:36:33.097  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-23 18:36:33.097  4362  4362 D A2dpService: Received stop request...Stopping profile...
08-23 18:36:33.098  4362  4501 D A2dpStateMachine: Exit Disconnected: -1
08-23 18:36:33.100  4362  4362 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-23 18:36:33.104  4362  4362 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-23 18:36:33.104  4362  4362 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:36:33.104  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ae3beb4
08-23 18:36:33.104  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-23 18:36:33.105  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 18:36:33.106   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 510us total 25.031ms
08-23 18:36:33.106  4362  4362 D HidService: Received stop request...Stopping profile...
08-23 18:36:33.106  4362  4437 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 18:36:33.106  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ae3beb4
08-23 18:36:33.107  7102  7102 D BluetoothInputDevice: Proxy object disconnected
08-23 18:36:33.107  4362  4362 D HealthService: Received stop request...Stopping profile...
08-23 18:36:33.107  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ae3beb4
08-23 18:36:33.107  7102  7102 D HidProfile: Bluetooth service disconnected
08-23 18:36:33.109  4362  4362 D PanService: Received stop request...Stopping profile...
,08-23 18:36:33.110  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ae3beb4
08-23 18:36:33.112  4362  4362 D HeadsetStateMachine: Unbinding service...
08-23 18:36:33.112  7102  7102 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 18:36:33.112  7102  7102 D PanProfile: Bluetooth service disconnected
08-23 18:36:33.112  4362  4362 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 18:36:33.113  4362  4362 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 18:36:33.113  4362  4362 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 18:36:33.113  4362  4362 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 18:36:33.113  4362  4362 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 18:36:33.113  4362  4362 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:36:33.113  4362  4362 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 18:36:33.113  4362  4362 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 18:36:33.114  4362  4362 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 18:36:33.114  4362  4362 D BtGatt.GattService: stop()
08-23 18:36:33.114  4362  4362 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 18:36:33.115  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ae3beb4
08-23 18:36:33.116  4362  4362 D BluetoothMapService: Received stop request...Stopping profile...
08-23 18:36:33.116  4362  4362 D BluetoothMapService: stop()
08-23 18:36:33.117  4362  4362 D BluetoothMapEmailAppObserver: deinitObservers()
08-23 18:36:33.117  4362  4362 D BluetoothMapEmailAppObserver: removeReceiver()
08-23 18:36:33.117  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ae3beb4
08-23 18:36:33.118  4362  4362 I BluetoothA2dpServiceJni: cleanupNative
08-23 18:36:33.119  4362  4502 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 18:36:33.119  7102  7102 D BluetoothMap: Proxy object disconnected
08-23 18:36:33.119  4362  4362 I GKI_LINUX: GKI_exit_task 2 done
08-23 18:36:33.119  7102  7102 D MapProfile: Bluetooth service disconnected
08-23 18:36:33.119  4362  4362 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 18:36:33.119  4362  4362 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 18:36:33.119  4362  4362 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 18:36:33.119  4362  4362 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 18:36:33.119  4362  4362 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 18:36:33.119  4362  4362 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 18:36:33.120  4362  4362 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 18:36:33.120  4362  4362 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 18:36:33.122  4362  4362 V BluetoothMapService: Handler(): got msg=4
08-23 18:36:33.122  4362  4362 D BluetoothMapService: MAP Service closeService in
08-23 18:36:33.122  4362  4362 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 18:36:33.122  4362  4362 V BluetoothMapService: MAP Service closeService out
08-23 18:36:33.123  4362  4437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-23 18:36:33.123  4362  4437 D BluetoothAdapterProperties: Setting state to 10
08-23 18:36:33.123  4362  4437 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-23 18:36:33.123  4362  4362 D BluetoothMapService: cleanup()
08-23 18:36:33.123  4362  4362 D BluetoothMapService: MAP Service closeService in
08-23 18:36:33.123  4362  4362 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 18:36:33.123  4362  4362 V BluetoothMapService: MAP Service closeService out
,08-23 18:36:33.124  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:33.124  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-23 18:36:33.124  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-23 18:36:33.124  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:36:33.125  4362  4437 I BluetoothAdapterState: Entering OffState
08-23 18:36:33.125  7102  7128 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 18:36:33.125  7102  7138 D BluetoothPan: onBluetoothStateChange on: false
,08-23 18:36:33.126  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:36:33.127  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:36:33.127  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:36:33.127   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 21.196ms
08-23 18:36:33.128  1852  2445 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:36:33.128  7102  7128 D BluetoothMap: onBluetoothStateChange: up=false
08-23 18:36:33.129  7102  7138 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 18:36:33.132  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-23 18:36:33.132  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-23 18:36:33.135  1033  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-23 18:36:33.135  1033  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-23 18:36:33.136  1033  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@360f5c63 mBinding = false
08-23 18:36:33.136  1033  1109 D BluetoothManagerService: Sending unbind request.
08-23 18:36:33.145  4362  4441 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-23 18:36:33.146  4362  4362 I GKI_LINUX: GKI_exit_task 1 done
08-23 18:36:33.146  4362  4362 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-23 18:36:33.146  4362  4362 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 18:36:33.146  4362  4362 I art     : --- WEIRD: removing null entry 246
08-23 18:36:33.146  4362  4362 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-23 18:36:33.147  4362  4362 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-23 18:36:33.148  4362  4362 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-23 18:36:33.139  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-23 18:36:33.149   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.100ms
,08-23 18:36:33.153  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:33.153  1941  2100 D LGBluetoothAPIService: Message: 2
08-23 18:36:33.153  1941  2100 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@14f95a17 mBinding = false
08-23 18:36:33.153  1941  2100 D LGBluetoothAPIService: Sending unbind request.
08-23 18:36:33.154  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 18:36:33.155  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:33.155  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:33.157  7102  7102 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 18:36:33.158  7102  7102 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-23 18:36:33.158  7102  7102 D LGBluetoothEventManager: [BTUI] clear device connection state
08-23 18:36:33.159  1601  1601 D BluetoothAdapter: 894783231: getState() :  mService = null. Returning STATE_OFF
08-23 18:36:33.159  1601  1601 D BluetoothAdapter: 894783231: getState() :  mService = null. Returning STATE_OFF
08-23 18:36:33.162  4362  4362 I art     : System.exit called, status: 0
08-23 18:36:33.162  4362  4362 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 18:36:33.166  7102  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 18:36:33.178  7102  7102 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:36:33.184   318   318 V AudioFlinger: 4362 died, releasing its sessions
08-23 18:36:33.184   318   318 V AudioFlinger:  pid 1852 @ 0
08-23 18:36:33.184   318   318 V AudioFlinger:  pid 3201 @ 1
08-23 18:36:33.184   318   318 V AudioFlinger:  pid 3201 @ 2
08-23 18:36:33.184  1033  1048 I ActivityManager: Process com.android.bluetooth (pid 4362) has died
08-23 18:36:33.185  1033  1048 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-23 18:36:33.185  7102  7102 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-23 18:36:33.189  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:36:33.199  7102  7102 D BluetoothPermissionRequest: onReceive
,08-23 18:36:33.202  7102  7102 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 18:36:33.203  7102  7102 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-23 18:36:33.205  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 18:36:33.261  1033  1048 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7237 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-23 18:36:33.276  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:33.283  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:36:33.292  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 18:36:33.324  7213  7257 W FormManager: Network not available. Please check & try again.
,08-23 18:36:33.328  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 18:36:33.328  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 18:36:33.329  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 18:36:33.329  7102  7102 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 18:36:33.330  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 18:36:33.332  7237  7237 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-23 18:36:33.332  7237  7237 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 18:36:33.333  7237  7237 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-23 18:36:33.333  7213  7258 V FormManager: Network unavailable.
08-23 18:36:33.334  7237  7237 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 18:36:33.335  7213  7258 V FormManager: Network unavailable.
,08-23 18:36:33.345  7102  7102 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 18:36:33.345  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 18:36:33.346  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 18:36:33.346  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 18:36:33.346  7102  7102 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 18:36:33.346  7102  7102 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 18:36:33.351  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-23 18:36:33.351  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:33.354  1033  2012 I ActivityManager: Killing 6162:com.android.contacts/u0a19 (adj 15): empty #17
08-23 18:36:33.355  7237  7237 D BluetoothAdapterApp: Loading JNI Library
08-23 18:36:33.356  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:33.390  7237  7237 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@33f2ac25 Instance Count = 1
,08-23 18:36:33.416  1033  1970 W libprocessgroup: failed to open /acct/uid_10019/pid_6162/cgroup.procs: No such file or directory
,08-23 18:36:33.418  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:33.422  7237  7237 D BluetoothAdapterApp: onCreate
08-23 18:36:33.432  7144  7144 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-23 18:36:33.432  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:33.432  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:33.436  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 18:36:33.438  4834  7261 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 18:36:33.441  4834  7263 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 18:36:33.442  4834  7263 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-23 18:36:33.450  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:33.456  7237  7237 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-23 18:36:33.457  7237  7237 D ProfileConfigQcom: Adding HeadsetService
08-23 18:36:33.457  7237  7237 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-23 18:36:33.457  7237  7237 D ProfileConfigQcom: Adding A2dpService
08-23 18:36:33.457  7237  7237 D ProfileConfigQcom: [BTUI] HidService is supported
08-23 18:36:33.458  7213  7265 W FormManager: Network not available. Please check & try again.
08-23 18:36:33.458  7237  7237 D ProfileConfigQcom: Adding HidService
08-23 18:36:33.458  7237  7237 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-23 18:36:33.458  7237  7237 D ProfileConfigQcom: Adding HealthService
08-23 18:36:33.458  7237  7237 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-23 18:36:33.459  7237  7237 D ProfileConfigQcom: [BTUI] PanService is supported
08-23 18:36:33.459  7237  7237 D ProfileConfigQcom: Adding PanService
08-23 18:36:33.460  7237  7237 D ProfileConfigQcom: [BTUI] GattService is supported
08-23 18:36:33.460  7237  7237 D ProfileConfigQcom: Adding GattService
08-23 18:36:33.460  7237  7237 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-23 18:36:33.460  7237  7237 D ProfileConfigQcom: Adding BluetoothMapService
08-23 18:36:33.461  7237  7237 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-23 18:36:33.463  7237  7237 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-23 18:36:33.467  7102  7102 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-23 18:36:33.469  7213  7266 V FormManager: Network unavailable.
08-23 18:36:33.470  7237  7237 V LGMDMManagerInternal: Create singleton instance
,08-23 18:36:33.474  7172  7172 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-23 18:36:33.475  7213  7266 V FormManager: Network unavailable.
08-23 18:36:33.475  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-23 18:36:33.476  7172  7172 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-23 18:36:33.513  7172  7172 D LgDataFeature: LgDataFeature() Constructor: none
,08-23 18:36:33.513  7172  7172 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 18:36:33.521  7172  7172 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-23 18:36:33.522  7172  7172 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-23 18:36:33.522  7172  7172 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-23 18:36:33.522  7172  7172 V SoundPool: doLoad: loading sample sampleID=1
08-23 18:36:33.523  7172  7172 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 18:36:33.524  7172  7270 V SoundPool: Start decode
08-23 18:36:33.524  7172  7270 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-23 18:36:33.525   318  1384 V MediaPlayerService: decode(22, 10857164, 17813)
08-23 18:36:33.525   318  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-23 18:36:33.526   318  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-23 18:36:33.526   318  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-23 18:36:33.526   318  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-23 18:36:33.526   318  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-23 18:36:33.526   318  1384 V MediaPlayerService: player type = 3
08-23 18:36:33.526   318  1384 V AwesomePlayer: AwesomePlayer create()
08-23 18:36:33.527   318  1384 V AwesomePlayer: reset_l() 
08-23 18:36:33.527   318  1384 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:33.527   318  1384 V AwesomePlayer: setAudioSink() 
08-23 18:36:33.527   318  1384 V AwesomePlayer: reset_l() 
08-23 18:36:33.527   318  1384 V AudioCache: notify(0xb5474980, 8, 0, 0)
08-23 18:36:33.527   318  1384 V AudioCache: ignored
08-23 18:36:33.527   318  1384 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:33.527   318  1384 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-23 18:36:33.527   318  1384 V AwesomePlayer: setDataSource_l dataSource
08-23 18:36:33.528   318  1384 V LGParserOSAL: SniffLGParser start
08-23 18:36:33.528   318  1384 V LGParserOSAL: MainType:5, SubType=0
08-23 18:36:33.528   318  1384 V LGParserOSAL: #### check Mime : application/ogg
08-23 18:36:33.528   318  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-23 18:36:33.528   318  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-23 18:36:33.530  6878  6878 D UEI.SmartControl: QS Service created
08-23 18:36:33.532  7172  7172 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-23 18:36:33.535  7172  7172 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 18:36:33.537  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-23 18:36:33.546  6878  6878 I UEI.SmartControl: Service initServices...
,08-23 18:36:33.546  6878  6878 D UEI.SmartControl: QS start get config
08-23 18:36:33.556  7237  7237 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:33.557  7172  7172 V LGMDMManager: Create singleton instance
08-23 18:36:33.559  7237  7237 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:33.560  7237  7237 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:33.560  7237  7237 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:33.561  7237  7237 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:33.561  7237  7237 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-23 18:36:33.569  7192  7192 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-23 18:36:33.598   318  1384 V LGParserOSAL: supported mime: application/ogg
08-23 18:36:33.598   318  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-23 18:36:33.598   318  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-23 18:36:33.598   318  1384 V AwesomePlayer: mBitrate = -1 bits/sec
08-23 18:36:33.598   318  1384 V AwesomePlayer: AudioTrack Setting
08-23 18:36:33.598   318  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-23 18:36:33.598   318  1384 V AwesomePlayer: setAudioSource() 
08-23 18:36:33.598   318  1384 V MediaPlayerService: prepare
08-23 18:36:33.598   318  1384 V AwesomePlayer: prepareAsync_l() 
08-23 18:36:33.599   318  1384 V MediaPlayerService: wait for prepare
,08-23 18:36:33.599   318  7272 V AwesomePlayer: onPrepareAsyncEvent() 
08-23 18:36:33.599   318  7272 V AwesomePlayer: initAudioDecoder() 
08-23 18:36:33.599   318  7272 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 18:36:33.599   318  7272 V AudioSystem: isOffloadSupported()
08-23 18:36:33.599   318  7272 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 18:36:33.599   318  7272 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 18:36:33.599   318  7272 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 18:36:33.599   318  7272 V AwesomePlayer: getUseOffload() = 0 
08-23 18:36:33.599   318  7272 V OMXCodec: OMXCodec::Create
08-23 18:36:33.599   318  7272 V OMXCodec: findMatchingCodecs()
08-23 18:36:33.599   318  7272 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-23 18:36:33.599   318  7272 V OMXCodec: matchingCodecs.size()=1
08-23 18:36:33.599   318  7272 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-23 18:36:33.601   318  7272 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-23 18:36:33.601   318  7272 V LGCodecAdapter: LG Codec Adapter start
08-23 18:36:33.601   318  7272 V OMXCodec: OMXCodec Createtor
08-23 18:36:33.601   318  7272 V OMXCodec: setComponentRole
08-23 18:36:33.601   318  7272 V OMXCodec: configureCodec protected=0
08-23 18:36:33.601   318  7272 V LGCodecAdapter: called getLGCodecSpecificData
08-23 18:36:33.601   318  7272 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-23 18:36:33.601   318  7272 V LGCodecOSAL: Called LGconfigureCodecMETA
08-23 18:36:33.601   318  7272 V LGCodecOSAL: Called LGconfigureCodecMSG
08-23 18:36:33.602   318  7272 V LGCodecOSAL: Not support LGCodec
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 18:36:33.602   318  7272 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-23 18:36:33.602   318  7272 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-23 18:36:33.602   318  7272 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-23 18:36:33.602   318  7272 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 18:36:33.602   318  7272 V AudioSystem: isOffloadSupported()
08-23 18:36:33.602   318  7272 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 18:36:33.602   318  7272 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-23 18:36:33.602   318  7272 V OMXCodec: init()
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-23 18:36:33.602   318  7272 V OMXCodec: allocateBuffers
08-23 18:36:33.602   318  7272 V OMXCodec: allocateBuffersOnPort portIndex=0
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-23 18:36:33.602   31,8  7272 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-23 18:36:33.602   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-23 18:36:33.603   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-23 18:36:33.603   318  7272 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-23 18:36:33.603   318  7272 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 18:36:33.603   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 18:36:33.603   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 18:36:33.603   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-23 18:36:33.603   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-23 18:36:33.603   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-23 18:36:33.603   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-23 18:36:33.603   318  7272 V OMXCodec: init() mAsyncCompletion wait free! 
08-23 18:36:33.603   318  7272 V AwesomePlayer: finishAsyncPrepare_l() 
08-23 18:36:33.603   318  7272 V AudioCache: notify(0xb5474980, 5, 0, 0)
08-23 18:36:33.603   318  7272 V AudioCache: ignored
08-23 18:36:33.603   318  7272 V AudioCache: notify(0xb5474980, 1, 0, 0)
08-23 18:36:33.603   318  7272 V AudioCache: prepared
08-23 18:36:33.603   318  1384 V AudioCache: wait - success
08-23 18:36:33.603   318  1384 V MediaPlayerService: start
08-23 18:36:33.603   318  1384 V AwesomePlayer: play_l() 
08-23 18:36:33.603   318  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-23 18:36:33.603   318  1384 V AwesomePlayer: createAudioPlayer_l
08-23 18:36:33.603   318  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
08-23 18:36:33.603   318  1384 V AwesomePlayer: startAudioPlayer_l() 
08-23 18:36:33.603   318  1384 D AudioPlayer: start of Playback, useOffload 0
08-23 18:36:33.603   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 18:36:33.603   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 18:36:33.605   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,08-23 18:36:33.605   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-23 18:36:33.605   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-23 18:36:33.605   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-23 18:36:33.605   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-23 18:36:33.605   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-23 18:36:33.606   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-23 18:36:33.607   318  7274 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 18:36:33.607   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 18:36:33.607   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-23 18:36:33.607   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,08-23 18:36:33.607   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-23 18:36:33.607   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb470 on output port
08-23 18:36:33.607   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-23 18:36:33.607   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-23 18:36:33.609   318  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-23 18:36:33.609   318  1384 V AudioCache: notify(0xb5474980, 6, 0, 0),
08-23 18:36:33.609   318  1384 V AudioCache: ignored
08-23 18:36:33.609   318  1384 V MediaPlayerService: wait for playback complete
08-23 18:36:33.610   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.610   318  7275 V AudioCache: memcpy(0xac300000, 0xb040b000, 4096)
08-23 18:36:33.612   318  7275 V AudioCache: write(0xb040b000, 4096),
08-23 18:36:33.612   318  7275 V AudioCache: memcpy(0xac301000, 0xb040b000, 4096)
08-23 18:36:33.613   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.613   318  7275 V AudioCache: memcpy(0xac302000, 0xb040b000, 4096),
08-23 18:36:33.613   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.613   318  7275 V AudioCache: memcpy(0xac303000, 0xb040b000, 4096)
08-23 18:36:33.614   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.614   318  7275 V AudioCache: memcpy(0xac304000, 0xb040b000, 4096)
08-23 18:36:33.614   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.614   318  7275 V AudioCache: memcpy(0xac305000, 0xb040b000, 4096)
08-23 18:36:33.615   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.615   318  7275 V AudioCache: memcpy(0xac306000, 0xb040b000, 4096)
08-23 18:36:33.615   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.616   318  7275 V AudioCache: memcpy(0xac307000, 0xb040b000, 4096)
,08-23 18:36:33.616   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.616   318  7275 V AudioCache: memcpy(0xac308000, 0xb040b000, 4096)
08-23 18:36:33.617   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.617   318  7275 V AudioCache: memcpy(0xac309000, 0xb040b000, 4096)
08-23 18:36:33.617   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.617   318  7275 V AudioCache: memcpy(0xac30a000, 0xb040b000, 4096)
08-23 18:36:33.618   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.618   318  7275 V AudioCache: memcpy(0xac30b000, 0xb040b000, 4096)
08-23 18:36:33.618   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.618   318  7275 V AudioCache: memcpy(0xac30c000, 0xb040b000, 4096)
,08-23 18:36:33.619   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.619   318  7275 V AudioCache: memcpy(0xac30d000, 0xb040b000, 4096)
08-23 18:36:33.619   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.619   318  7275 V AudioCache: memcpy(0xac30e000, 0xb040b000, 4096)
08-23 18:36:33.620   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.620   318  7275 V AudioCache: memcpy(0xac30f000, 0xb040b000, 4096)
08-23 18:36:33.621   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.621   318  7275 V AudioCache: memcpy(0xac310000, 0xb040b000, 4096)
08-23 18:36:33.621   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.621   318  7275 V AudioCache: memcpy(0xac311000, 0xb040b000, 4096)
,08-23 18:36:33.622   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.622   318  7275 V AudioCache: memcpy(0xac312000, 0xb040b000, 4096)
08-23 18:36:33.622   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.622   318  7275 V AudioCache: memcpy(0xac313000, 0xb040b000, 4096)
,08-23 18:36:33.623   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.623   318  7275 V AudioCache: memcpy(0xac314000, 0xb040b000, 4096)
08-23 18:36:33.624   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.624   318  7275 V AudioCache: memcpy(0xac315000, 0xb040b000, 4096)
08-23 18:36:33.624   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.624   318  7275 V AudioCache: memcpy(0xac316000, 0xb040b000, 4096)
08-23 18:36:33.625   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.625   318  7275 V AudioCache: memcpy(0xac317000, 0xb040b000, 4096)
,08-23 18:36:33.625   318  7275 V AudioCache: write(0xb040b000, 4096),
08-23 18:36:33.625   318  7275 V AudioCache: memcpy(0xac318000, 0xb040b000, 4096)
08-23 18:36:33.626   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.626   318  7275 V AudioCache: memcpy(0xac319000, 0xb040b000, 4096)
08-23 18:36:33.626   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.627   318  7275 V AudioCache: memcpy(0xac31a000, 0xb040b000, 4096)
08-23 18:36:33.627   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.627   318  7275 V AudioCache: memcpy(0xac31b000, 0xb040b000, 4096)
,08-23 18:36:33.628   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.628   318  7275 V AudioCache: memcpy(0xac31c000, 0xb040b000, 4096)
08-23 18:36:33.628   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.628   318  7275 V AudioCache: memcpy(0xac31d000, 0xb040b000, 4096)
08-23 18:36:33.629   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.629   318  7275 V AudioCache: memcpy(0xac31e000, 0xb040b000, 4096)
08-23 18:36:33.629   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.629   318  7275 V AudioCache: memcpy(0xac31f000, 0xb040b000, 4096)
08-23 18:36:33.630   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.630   318  7275 V AudioCache: memcpy(0xac320000, 0xb040b000, 4096)
08-23 18:36:33.631   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.631   318  7275 V AudioCache: memcpy(0xac321000, 0xb040b000, 4096)
,08-23 18:36:33.631   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.631   318  7275 V AudioCache: memcpy(0xac322000, 0xb040b000, 4096)
08-23 18:36:33.632   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.632   318  7275 V AudioCache: memcpy(0xac323000, 0xb040b000, 4096)
08-23 18:36:33.632   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.632   318  7275 V AudioCache: memcpy(0xac324000, 0xb040b000, 4096),
08-23 18:36:33.633   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.633   318  7275 V AudioCache: memcpy(0xac325000, 0xb040b000, 4096)
08-23 18:36:33.633   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.633   318  7275 V AudioCache: memcpy(0xac326000, 0xb040b000, 4096)
,08-23 18:36:33.634   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.634   318  7275 V AudioCache: memcpy(0xac327000, 0xb040b000, 4096)
08-23 18:36:33.634   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.634   318  7275 V AudioCache: memcpy(0xac328000, 0xb040b000, 4096)
08-23 18:36:33.635   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.635   318  7275 V AudioCache: memcpy(0xac329000, 0xb040b000, 4096)
08-23 18:36:33.635  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-23 18:36:33.636   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.636   318  7275 V AudioCache: memcpy(0xac32a000, 0xb040b000, 4096)
08-23 18:36:33.636   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.636   318  7275 V AudioCache: memcpy(0xac32b000, 0xb040b000, 4096)
08-23 18:36:33.637  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-23 18:36:33.637   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.637   318  7275 V AudioCache: memcpy(0xac32c000, 0xb040b000, 4096)
,08-23 18:36:33.637   318  7275 V AudioCache: write(0xb040b000, 4096),
,08-23 18:36:33.637   318  7275 V AudioCache: memcpy(0xac32d000, 0xb040b000, 4096),
,08-23 18:36:33.638   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.638   318  7275 V AudioCache: memcpy(0xac32e000, 0xb040b000, 4096)
08-23 18:36:33.638   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.,
08-23 18:36:33.638   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.638   318  7275 V AudioCache: memcpy(0xac32f000, 0xb040b000, 4096)
08-23 18:36:33.638   318  7275 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer,
08-23 18:36:33.638   318  7275 V AudioCache: write(0xb040b000, 4096)
,08-23 18:36:33.638   318  7275 V AudioCache: memcpy(0xac330000, 0xb040b000, 4096)
08-23 18:36:33.638   318  7275 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-23 18:36:33.638   318  7275 V AudioCache: write(0xb040b000, 4096)
08-23 18:36:33.638   318  7275 V AudioCache: memcpy(0xac331000, 0xb040b000, 4096)
,08-23 18:36:33.638   318  7275 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-23 18:36:33.638   318  7275 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer,
08-23 18:36:33.639   318  7275 V AwesomePlayer: postAudioEOS() 
08-23 18:36:33.639  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:956
,08-23 18:36:33.639   318  7275 V AudioCache: write(0xb040b000, 280)
08-23 18:36:33.639   318  7275 V AudioCache: memcpy(0xac332000, 0xb040b000, 280)
,08-23 18:36:33.640   318  7272 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-23 18:36:33.640   318  7272 V AwesomePlayer: onStreamDone,
08-23 18:36:33.640   318  7272 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
,08-23 18:36:33.640   318  7272 V AudioCache: notify(0xb5474980, 2, 0, 0)
08-23 18:36:33.640   318  7272 V AudioCache: playback complete
,08-23 18:36:33.640   318  7272 V AwesomePlayer: pause_l() 
08-23 18:36:33.640   318  7272 V AudioCache: notify(0xb5474980, 7, 0, 0)
,08-23 18:36:33.640   318  7272 V AudioCache: ignored
,08-23 18:36:33.640   318  7272 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:33.640   318  1384 V AudioCache: wait - success
,08-23 18:36:33.640   318  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-23 18:36:33.641   318  7272 D AudioPlayer: Pause Playback at 1068125
08-23 18:36:33.641   318  1384 V AwesomePlayer: reset_l() 
08-23 18:36:33.641   318  1384 V AudioCache: notify(0xb5474980, 8, 0, 0)
08-23 18:36:33.641   318  1384 V AudioCache: ignored
,08-23 18:36:33.641   318  1384 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:33.641   318  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-23 18:36:33.641   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-23 18:36:33.641   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-23 18:36:33.641   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
,08-23 18:36:33.641   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
,08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
,08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb470 on port 1
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-23 18:36:33.641   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-23 18:36:33.642   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
,08-23 18:36:33.642   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 18:36:33.642   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-23 18:36:33.642   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-23 18:36:33.642   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-23 18:36:33.642   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-23 18:36:33.642   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,08-23 18:36:33.642   318  7274 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-23 18:36:33.642   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-23 18:36:33.642   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-23 18:36:33.642   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-23 18:36:33.642   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-23 18:36:33.643   318  1384 D AudioPlayer: AudioPlayer releasing audio source
08-23 18:36:33.643   318  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-23 18:36:33.643   318  1384 V AwesomePlayer: reset_l() 
08-23 18:36:33.643   318  1384 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:33.643   318  1384 V AwesomePlayer: ~AwesomePlayer call
,08-23 18:36:33.643   318  1384 V AwesomePlayer: reset_l() 
08-23 18:36:33.643   318  1384 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:33.643  7172  7270 V SoundPool: close(31)
08-23 18:36:33.643  7172  7270 V SoundPool: pointer = 0x9fff4000, size = 205080, sampleRate = 48000, numChannels = 2
08-23 18:36:33.837  6878  6878 I UEI.SmartControl: Supports setup maps: true
,08-23 18:36:33.840  6878  6878 D UEI.SmartControl: QS start statue = true Error code = 0
08-23 18:36:33.840  6878  6878 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-23 18:36:33.840  6878  6878 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-23 18:36:33.840  6878  6878 I UEI.SmartControl: ### init IR Blaster...
08-23 18:36:33.844  6878  6878 D serial_port: Configuring serial port
08-23 18:36:33.844  6878  6878 E UEI.SmartControl: UEIBLaster setting for 616
08-23 18:36:33.845  6878  6878 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 18:36:33.845  6878  6878 I UEI.SmartControl: configuring settings for MAXQ616
08-23 18:36:33.845  6878  6878 I UEI.SmartControl: Get version...
08-23 18:36:33.864  6878  7276 D UEI.SmartControl: serial port data available: 21
,08-23 18:36:33.891  6878  6878 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-23 18:36:33.891  6878  6878 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-23 18:36:33.891  6878  6878 I UEI.SmartControl: QS saving settings...
,08-23 18:36:33.893  6878  6878 D UEI.SmartControl: IR Blaster version: 25672567
08-23 18:36:33.910  6878  7276 D UEI.SmartControl: serial port data available: 4
,08-23 18:36:33.940  6878  7282 I UEI.SmartControl: Device manager: loading config....
,08-23 18:36:33.941  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-23 18:36:33.943  6878  6878 E UEI.SmartControl: Services init done
08-23 18:36:33.943  6878  6878 D UEI.SmartControl: QS Service init finished
08-23 18:36:33.945  6878  7282 D UEI.SmartControl: ----------- loading internal config...
,08-23 18:36:33.946  6878  6878 D UEI.SmartControl: QS Service version name: 2.1.91
08-23 18:36:33.946  6878  6878 D UEI.SmartControl: QS Service version code: 201091
08-23 18:36:33.947  6878  6878 D UEI.SmartControl: Service requested: Control
08-23 18:36:33.952  6878  7282 E UEI.SmartControl: Loading SETTINGS...
08-23 18:36:33.952  6878  6878 D UEI.SmartControl: Request IControl service: devices are loaded...
08-23 18:36:33.954  6878  6878 D UEI.SmartControl: Internal service binding...
08-23 18:36:33.954  7172  7172 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-23 18:36:33.956  6878  6893 I UEI.SmartControl: ------ IControl API: 11
08-23 18:36:33.956  6878  6893 D UEI.SmartControl: File observer start...
08-23 18:36:33.957  6878  6893 E UEI.SmartControl: IR Port is disabled: false
08-23 18:36:33.957  6878  6893 D UEI.SmartControl: Starting file observer...
08-23 18:36:33.958  6878  6893 I UEI.SmartControl: Registering callback...
,08-23 18:36:33.967  6878  6894 I UEI.SmartControl: ------ IControl API: 19
,08-23 18:36:33.968  6878  6894 I UEI.SmartControl: Registering Services Ready callback...
08-23 18:36:33.971  6878  7282 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-23 18:36:33.979  6878  7281 I UEI.SmartControl: Notify AllClients services are ready: 0
08-23 18:36:33.980  6878  7281 D UEI.SmartControl: -----service ready thread exits
08-23 18:36:33.980  7172  7191 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-23 18:36:33.981  7172  7268 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-23 18:36:33.981  7172  7268 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-23 18:36:33.982  7172  7172 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-23 18:36:33.982  7172  7172 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-23 18:36:33.982  6878  6893 I UEI.SmartControl: ------ IControl API: 8
08-23 18:36:33.984  7172  7172 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-23 18:36:33.984  7172  7172 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-23 18:36:33.985  7172  7172 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-23 18:36:33.985  7172  7172 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-23 18:36:33.986  7172  7172 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-23 18:36:33.986  7172  7172 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-23 18:36:33.988  7172  7172 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-23 18:36:33.991  7172  7172 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-23 18:36:33.992  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-23 18:36:33.992  7172  7172 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 18:36:33.993  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-23 18:36:33.996  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-23 18:36:33.997  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-23 18:36:33.997  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-23 18:36:33.999  7172  7172 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471970193998]
08-23 18:36:34.000  7172  7172 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-23 18:36:34.003  1033  1977 I ActivityManager: Killing 6705:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-23 18:36:34.029  7172  7287 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-23 18:36:34.042  1033  1977 I ActivityManager: Killing 6674:com.lge.email/u0a23 (adj 15): empty #18
,08-23 18:36:34.081  1033  1782 W libprocessgroup: failed to open /acct/uid_10027/pid_6705/cgroup.procs: No such file or directory
,08-23 18:36:34.085  1033  1938 W libprocessgroup: failed to open /acct/uid_10023/pid_6674/cgroup.procs: No such file or directory
08-23 18:36:34.090  7172  7172 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-23 18:36:34.091  7172  7172 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 18:36:34.092  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-23 18:36:34.092  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-23 18:36:34.093  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-23 18:36:34.093  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-23 18:36:34.094  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-23 18:36:34.108  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-23 18:36:34.971  1033  1939 D WifiServiceImplEx: setWifiEnabled: true pid=6980, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 18:36:34.973  1033  1939 D WifiService: setWifiEnabled: true pid=6980, uid=10118
08-23 18:36:34.973  1033  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 18:36:34.990  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:34.991  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 18:36:34.991  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-23 18:36:34.992  1033  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-23 18:36:34.992  1033  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-23 18:36:34.994  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-23 18:36:34.994  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 18:36:34.994  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-23 18:36:34.994  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 18:36:34.994  1033  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-23 18:36:34.994  1033  1536 E WifiHW  : unknown target_country: EU , set to default
08-23 18:36:34.994  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-23 18:36:34.994  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-23 18:36:34.994  1033  1536 I WifiUtil: gEnableBmps=1
,08-23 18:36:35.006  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:35.011  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,08-23 18:36:35.021  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:35.026  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:35.029  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:35.034  1033  1109 D Tethering: MasterInitialState.processMessage what=3
08-23 18:36:35.035  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:35.045  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:35.048  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:35.050  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-23 18:36:35.058  6554  7143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-23 18:36:35.063  5994  5994 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-23 18:36:35.077  5994  5994 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-23 18:36:35.102  2164  2164 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:36:35.132  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:36:35.180  1033  1782 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7307 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-23 18:36:35.190  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:35.190  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 18:36:35.254  7307  7307 I AppUp4:AppBoxCP: onCreate
08-23 18:36:35.255  7307  7307 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-23 18:36:35.264  7307  7307 I AppUp4:DB:  setFingerPrint start
,08-23 18:36:35.265  7307  7307 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-23 18:36:35.274  7307  7307 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-23 18:36:35.274  7307  7307 I AppUp4:DB:  SDK version = 21
08-23 18:36:35.274  7307  7307 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-23 18:36:35.276  7307  7307 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-23 18:36:35.279  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-23 18:36:35.279  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:35.281  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 18:36:35.282  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 18:36:35.289  7307  7307 I AppUp4:CustModeStarterReceiver: onReceive
,08-23 18:36:35.333  7307  7307 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:35.333  7307  7307 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:35.341  7307  7307 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30751f87
08-23 18:36:35.341  7307  7307 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 18:36:35.342  7307  7307 D AppUp4:CustFacade: isPhone : true
08-23 18:36:35.343  7307  7307 D AppUp4:CustModeStarterReceiver: begin check event
08-23 18:36:35.344  7307  7307 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-23 18:36:35.345  7307  7307 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-23 18:36:35.346  7307  7325 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-23 18:36:35.346  7307  7325 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-23 18:36:35.346  7307  7325 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-23 18:36:35.349  1033  1967 I ActivityManager: Killing 6768:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-23 18:36:35.408  1033  1048 W libprocessgroup: failed to open /acct/uid_10061/pid_6768/cgroup.procs: No such file or directory
,08-23 18:36:35.410  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:35.411  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-23 18:36:35.417  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:35.422  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:35.431  4834  7328 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 18:36:35.440  4834  7329 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:35.440  4834  7329 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:35.490  1033  1938 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7330 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-23 18:36:35.597  7330  7330 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:36:35.598  7330  7330 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 18:36:35.599  7330  7330 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 18:36:35.600  7330  7330 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 18:36:35.696  7330  7330 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-23 18:36:35.710  7330  7330 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-23 18:36:35.769  7330  7330 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-23 18:36:35.812  7330  7330 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:35.812  7330  7330 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:35.844   311   893 D SoftapController: Softap fwReload - Ok
,08-23 18:36:35.853  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 18:36:35.853  1033  1109 D Tethering: InitialState.processMessage what=4
08-23 18:36:35.857  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:36:35.858  1033  1536 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (856ms)
08-23 18:36:35.860   311   893 D CommandListener: Setting iface cfg
08-23 18:36:35.860   311   893 D CommandListener: Trying to bring down wlan0
08-23 18:36:35.861   311   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:36:35.863  1033  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-23 18:36:35.867  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:35.867  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:35.867  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-23 18:36:35.869  7360  7360 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:35.869  7360  7360 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:35.871  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:35.873  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-23 18:36:35.876  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:35.877  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-23 18:36:35.877  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:35.878  1033  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-23 18:36:35.878  1033  1536 D WifiMonitor: connecting to supplicant
,08-23 18:36:35.896  7360  7360 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-23 18:36:35.929  7360  7360 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 18:36:35.930  7360  7360 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-23 18:36:35.978  7360  7360 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 18:36:35.984  7330  7330 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-23 18:36:36.014  7330  7330 I HubEmail: JNI_OnLoad()
08-23 18:36:36.014  7330  7330 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 18:36:36.014  7330  7330 I HubEmail: registerNatives()
08-23 18:36:36.014  7330  7330 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 18:36:36.014  7330  7330 I HubEmail: registerNativeMethods()
08-23 18:36:36.014  7330  7330 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 18:36:36.015  7330  7330 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-23 18:36:36.025  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 18:36:36.025  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:36.026  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 18:36:36.041  7360  7360 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-23 18:36:36.049  7360  7360 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-23 18:36:36.050  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-23 18:36:36.051  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-23 18:36:36.051  1033  7373 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-23 18:36:36.051  1033  7373 D WifiMonitor: Dropping event because (p2p0) is stopped
08-23 18:36:36.051  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-23 18:36:36.052  1033  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-23 18:36:36.052  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.052  7360  7360 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-23 18:36:36.052  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-23 18:36:36.052  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-23 18:36:36.052  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.053  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-23 18:36:36.053  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-23 18:36:36.053  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-23 18:36:36.053  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-23 18:36:36.053  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.053  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.054  1033  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-23 18:36:36.054  1033  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-23 18:36:36.055  1033  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-23 18:36:36.055  1033  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-23 18:36:36.055  1033  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-23 18:36:36.078  1033  1049 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7374 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-23 18:36:36.081  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:36.081  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:36.081  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 18:36:36.082  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.082  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.082  7330  7368 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.082  1033  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
08-23 18:36:36.082  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.082  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.082  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:36.083  1033  1536 D WifiNative-wlan0: SET update_config 1: returned true
08-23 18:36:36.084  1033  1536 D WifiConfigStore: Loading config and enabling all networks 
08-23 18:36:36.084  1033  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-23 18:36:36.085  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-23 18:36:36.086  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-23 18:36:36.087  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-23 18:36:36.087  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:36.087  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:36.087  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:36.087  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:36.088  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36,:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:36.088  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:36.088  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:36.088  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:36.089  1033  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-23 18:36:36.089  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.094  7213  7371 W FormManager: Network not available. Please check & try again.
,08-23 18:36:36.094  1033  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-23 18:36:36.100  7213  7372 V FormManager: Network unavailable.
08-23 18:36:36.102  7213  7372 V FormManager: Network unavailable.
08-23 18:36:36.103  1033  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-23 18:36:36.103  1033  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-23 18:36:36.105  1033  1536 D WifiStateMachine: enableVerboseLogging : level 2
08-23 18:36:36.105  1033  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-23 18:36:36.105  1033  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-23 18:36:36.105  1033  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-23 18:36:36.106  1033  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-23 18:36:36.106  1033  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-23 18:36:36.106  1033  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-23 18:36:36.106  1033  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-23 18:36:36.107  1033  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-23 18:36:36.107  1033  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-23 18:36:36.107  1033  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-23 18:36:36.107  1033  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-23 18:36:36.107  1033  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-23 18:36:36.108  1033  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-23 18:36:36.108  1033  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-23 18:36:36.109  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 18:36:36.109  1033  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-23 18:36:36.109  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-23 18:36:36.109  1941  2256 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-23 18:36:36.110  1941  2256 D WfdsService: Set the WFDS Monitor: true
08-23 18:36:36.110  1941  2256 D WfdsMonitor: WfdsMonitorThread create
08-23 18:36:36.110  1941  2256 D WfdsMonitor: WFDS Monitor is created and started
08-23 18:36:36.110  1941  2256 D WfdsService: WiFi: Supplicant connection re-established
08-23 18:36:36.110  1033  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-23 18:36:36.110  1033  1536 D WifiNative-HAL: Setting external_sim to 1
08-23 18:36:36.110  1033  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-23 18:36:36.110  1941  7390 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-23 18:36:36.111  1033  1536 D WifiNative-wlan0: SET external_sim 1: returned true
08-23 18:36:36.111  1033  1536 I WifiNative-HAL: startHal
08-23 18:36:36.111  1033  1536 D wifi    : setting scan oui 0xaf6c3080
08-23 18:36:36.111  1941  7390 E CtrlSupplicant: Succeed to open control connection
08-23 18:36:36.111  1941  7390 E CtrlSupplicant: Succeed to open monitor connection
08-23 18:36:36.111  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 18:36:36.111  1033  1536 I WifiNative-HAL: startHal
08-23 18:36:36.111  1033  1536 D wifi    : setting scan oui 0xaf6c3080
08-23 18:36:36.111  1033  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-23 18:36:36.112  1033  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-23 18:36:36.112  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-23 18:36:36.112  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-23 18:36:36.112  1033  2012 I ActivityManager: Killing 6812:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-23 18:36:36.112  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-23 18:36:36.113  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 18:36:36.113  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 18:36:36.114  1941  7390 D WfdsMonitor: Supplicant connection established
08-23 18:36:36.114  1941  2256 D WfdsService: Connected to the supplicant for wfds
08-23 18:36:36.117  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 18:36:36.117  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-23 18:36:36.117  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-23 18:36:36.119  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-23 18:36:36.119  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 18:36:36.119  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-23 18:36:36.121  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 18:36:36.121  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 18:36:36.121  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 18:36:36.128  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 18:36:36.128  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-23 18:36:36.128  7360  7360 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-23 18:36:36.128  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-23 18:36:36.128  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 18:36:36.128  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 18:36:36.129  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 18:36:36.129  1033  1536 E WifiNative: : [201,494,687 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-23 18:36:36.130  1033  1536 D WifiNative-wlan0: doBoolean: RECONNECT
,08-23 18:36:36.131  1033  1536 D WifiNative-wlan0: RECONNECT: returned true
08-23 18:36:36.131  1033  1536 D WifiNative-wlan0: doString: [STATUS]
08-23 18:36:36.131  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-23 18:36:36.131  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-23 18:36:36.131  1033  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 18:36:36.131  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:36.132  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
08-23 18:36:36.132  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.133   311   893 D CommandListener: Setting iface cfg
08-23 18:36:36.133   311   893 D CommandListener: Trying to bring up p2p0
08-23 18:36:36.133  1033  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 18:36:36.133  1033  1535 D LGWifiP2pService: P2pEnablingState
08-23 18:36:36.133  1033  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.133  1033  1535 D LGWifiP2pService: P2p socket connection successful
08-23 18:36:36.134  1033  1535 D LGWifiP2pService: P2pEnabledState
08-23 18:36:36.152  1033  1967 W libprocessgroup: failed to open /acct/uid_10080/pid_6812/cgroup.procs: No such file or directory
,08-23 18:36:36.159  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-23 18:36:36.160  1033  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-23 18:36:36.161  1033  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-23 18:36:36.161  1033  1535 D LGWifiP2pService: sending p2p connection changed broadcast
08-23 18:36:36.162  1033  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-23 18:36:36.162  1033  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-23 18:36:36.163  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 18:36:36.163  1033  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.163  1033  1554 I WifiNative-HAL: startHal
08-23 18:36:36.163  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-23 18:36:36.163  1033  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-23 18:36:36.163  1033  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.164  1033  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf6c3080
08-23 18:36:36.164  1033  1554 D wifi    : failed to get capabilities : -3
08-23 18:36:36.164  1033  1554 E WifiScanningService: could not get scan capabilities
08-23 18:36:36.164  1033  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
08-23 18:36:36.164  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-23 18:36:36.164  1941  1941 D WfdsService: WifiP2pState is changed : true
08-23 18:36:36.165  1941  2256 D WfdsService: Receive the WFDS_ENABLE Method
08-23 18:36:36.165  1941  2256 D WfdsService: Set the WFDS Monitor: true
08-23 18:36:36.165  1941  2256 D WfdsService: Connected to the supplicant for wfds
08-23 18:36:36.165  1941  2256 D WfdsJNI : doCommand: WFDS_SET TRUE
08-23 18:36:36.166  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-23 18:36:36.166  7360  7360 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-23 18:36:36.166  1941  2256 D WfdsService: selectPreferredScanChannel [36]
08-23 18:36:36.166  1941  2256 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-23 18:36:36.166  1941  1941 D WfdsService: isConnected: false
08-23 18:36:36.167  1033  1535 D WifiNative-p2p0: SET device_name G3: returned true
08-23 18:36:36.167  1033  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-23 18:36:36.167  1033  1535 D LGWifiP2pService: before postfix = G3
08-23 18:36:36.167  1033  1535 D WifiServerServiceExt: postfix byte check : 2
08-23 18:36:36.167  1033  1535 D LGWifiP2pService: after postfix = G3
08-23 18:36:36.167  1033  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-23 18:36:36.168  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=201532  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 18:36:36.170  1033  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-23 18:36:36.171  1033  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-23 18:36:36.171  1033  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-23 18:36:36.171  1033  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-23 18:36:36.172  1033  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-23 18:36:36.172  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-23 18:36:36.173  1033  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-23 18:36:36.173  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress
08-23 18:36:36.173  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-23 18:36:36.175  1033  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-23 18:36:36.175  1033  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-23 18:36:36.175  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=201540  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 18:36:36.176  1033  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
08-23 18:36:36.176  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-23 18:36:36.176  1033  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-23 18:36:36.176  1033  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-23 18:36:36.176  1033  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-23 18:36:36.177  1033  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-23 18:36:36.177  1033  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-23 18:36:36.177  1033  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-23 18:36:36.177  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.177  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.178  1033  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-23 18:36:36.178  1033  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-23 18:36:36.179  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.179  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.179  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.179  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 18:36:36.181  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-23 18:36:36.181  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-23 18:36:36.182  1941  1941 D WfdsService: Update P2p Interface State: 3
08-23 18:36:36.187  7360  7360 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-23 18:36:36.188  1033  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-23 18:36:36.188  1033  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-23 18:36:36.189  1033  1535 D LGWifiP2pService: InactiveState
08-23 18:36:36.189  1033  1535 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.189  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.189  1033  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-23 18:36:36.190  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 18:36:36.190  1033  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-23 18:36:36.190  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:36:36.190  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.191  7360  7360 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.191  1941  7390 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 18:36:36.191  1033  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.191  1033  7373 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 18:36:36.191  1033  7373 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.191  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.191  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.192  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  7360  7360 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 18:36:36.192  7360  7360 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  1033  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.192  1033  1033 E WifiServerServiceExt: No p2p device connected
08-23 18:36:36.192  7360  7360 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.193  1941  2256 W WfdsService: DefaultState - msg [9441285] is not handled
08-23 18:36:36.193  1941  7390 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:36.193  1941  7390 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:36.193  1033  7373 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:36.193  1033  7373 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.193  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.193  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.194  1033  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-23 18:36:36.194  1033  7373 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:36.194  1033  7373 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.194  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-23 18:36:36.194  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.194  1033  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-23 18:36:36.194  1033  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-23 18:36:36.194  1033  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-23 18:36:36.195  7360  7360 E wpa_supplicant: disconnect_rssi_lvl: -100
08-23 18:36:36.195  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 18:36:36.196  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 18:36:36.196  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 18:36:36.196  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-23 18:36:36.197  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-23 18:36:36.197  7360  7360 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.198  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 18:36:36.198  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.198  7360  7360 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 18:36:36.198  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.198  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:36.198  7360  7360 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.198  1941  7390 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:36.199  1033  7373 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-23 18:36:36.199  1033  7373 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.199  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.199  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.199  7360  7360 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.199  1033  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-23 18:36:36.199  1941  7390 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:36.199  1033  7373 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:36.199  1033  7373 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.199  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-23 18:36:36.200  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:36.200  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.200  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.200  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-23 18:36:36.201  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-23 18:36:36.202  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-23 18:36:36.202  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-23 18:36:36.202  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-23 18:36:36.202  7360  7360 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 18:36:36.203  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-23 18:36:36.203  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-23 18:36:36.204  1033  7373 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 18:36:36.204  1033  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-23 18:36:36.204  1033  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-23 18:36:36.204  1033  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-23 18:36:36.204  1033  1536 D WifiNative-wlan0: doBoolean: SCAN
08-23 18:36:36.204  1033  7373 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-23 18:36:36.205  1033  1536 D WifiNative-wlan0: SCAN: returned false
08-23 18:36:36.205  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=201571  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 18:36:36.207  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=201572  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 18:36:36.208  1033  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:36.208  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.208  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.208  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 18:36:36.209  1033  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:36.209  1033  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:36.209  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.209  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.210  1033  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:36.211  1033  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:36.211  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.212  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:36.212  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-23 18:36:36.213  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:36.213  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-23 18:36:36.266  7374  7374 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:36.267  7374  7374 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 18:36:36.271  7374  7374 D PhoneMonitor: Register our PhoneStateListener
,08-23 18:36:36.291  7374  7374 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-23 18:36:36.295  7374  7374 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-23 18:36:36.313  7374  7374 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-23 18:36:36.315  7374  7374 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-23 18:36:36.316  7374  7374 D TelephonyAutoProfiling: [parse] Load xml
08-23 18:36:36.323  7374  7374 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-23 18:36:36.324  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-23 18:36:36.325  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-23 18:36:36.325  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-23 18:36:36.325  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
,08-23 18:36:36.325  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-23 18:36:36.325  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-23 18:36:36.325  7374  7374 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-23 18:36:36.325  7374  7374 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-23 18:36:36.336  7374  7374 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-23 18:36:36.361  1033  1653 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7396 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:36:36.362  1033  1653 I ActivityManager: Killing 6276:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-23 18:36:36.421  1033  1970 W libprocessgroup: failed to open /acct/uid_10097/pid_6276/cgroup.procs: No such file or directory
,08-23 18:36:36.630  1033  1049 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7420 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-23 18:36:36.634  1033  1049 I ActivityManager: Killing 6835:com.lge.eula/1000 (adj 15): empty #17
08-23 18:36:36.692  7360  7360 E wpa_supplicant: USIM:  scard_init function
08-23 18:36:36.692  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-23 18:36:36.692  1033  7373 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-23 18:36:36.692  7360  7360 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-23 18:36:36.692  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-23 18:36:36.692  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-23 18:36:36.692  1033  7373 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-23 18:36:36.692  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-23 18:36:36.692  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-23 18:36:36.694  1033  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_6835/cgroup.procs: No such file or directory
08-23 18:36:36.695  1033  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 18:36:36.695  1033  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 18:36:36.696  1033  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 18:36:36.696  1033  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 18:36:36.696  1033  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-23 18:36:36.704  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=202069  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-23 18:36:36.706  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.706  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.706  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-23 18:36:36.706  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.706  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.708  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=202073  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-23 18:36:36.709  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:36.709  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-23 18:36:36.710  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.790  1033  1970 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7437 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 18:36:36.794  1033  1970 I ActivityManager: Killing 6856:com.lge.bnr/1000 (adj 15): empty #17
08-23 18:36:36.801  7360  7360 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-23 18:36:36.802  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-23 18:36:36.802  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-23 18:36:36.802  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,08-23 18:36:36.802  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-23 18:36:36.808  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=202173  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 18:36:36.808  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=202174  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 18:36:36.811  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:36.811  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:36.811  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:36.811  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:36.811  7360  7360 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:36:36.812  7360  7360 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 18:36:36.814  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-23 18:36:36.814  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:36:36.814  1033  7373 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:36:36.814  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-23 18:36:36.814  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 18:36:36.814  1033  7373 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 18:36:36.814  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:36.814  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-23 18:36:36.852  1033  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202217
08-23 18:36:36.852  1033  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202218
08-23 18:36:36.853  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-23 18:36:36.854  1033  1977 W libprocessgroup: failed to open /acct/uid_1000/pid_6856/cgroup.procs: No such file or directory
,08-23 18:36:36.858  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:36.858  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-23 18:36:36.859  1033  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202224
08-23 18:36:36.860  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202226
08-23 18:36:36.862  1033  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202227
08-23 18:36:36.863  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=202228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 18:36:36.871  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.871  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.872  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.872  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.872  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-23 18:36:36.874  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=202239  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 18:36:36.875  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=202240  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 18:36:36.875  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.876  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=202241  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 18:36:36.876  1033  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=202242
08-23 18:36:36.877  1033  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=202242
08-23 18:36:36.877  1033  1536 D WifiNative-wlan0: doString: [STATUS]
,08-23 18:36:36.878  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:36.878  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:36.878  1033  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 18:36:36.881  1033  1536 I WifiServiceExtension: setVHTCapabilityType  : false
08-23 18:36:36.883  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.883  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.883  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-23 18:36:36.888  1033  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-23 18:36:36.888  1033  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-23 18:36:36.896  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.896  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.896  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 18:36:36.904  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.904  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.904  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.904  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.904  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-23 18:36:36.908  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.909  1033  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-23 18:36:36.909  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:36:36.909  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 18:36:36.909  1033  1543 D ConnectivityService: Got NetworkAgent Messenger
08-23 18:36:36.909  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-23 18:36:36.909  1033  1543 D ConnectivityService: NetworkAgent connected
08-23 18:36:36.910  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 18:36:36.910  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 18:36:36.911  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.911  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.913  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.913  7437  7437 I art     : Almond Protected OAT
08-23 18:36:36.914  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.914  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.915  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 18:36:36.915  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:36:36.915  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 18:36:36.916  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 18:36:36.916  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 18:36:36.921  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 18:36:36.922   311   893 D CommandListener: Setting iface cfg
08-23 18:36:36.922  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:36.925  1033  7467 D DhcpStateMachine: StoppedState
08-23 18:36:36.925  1033  1536 E WifiStateMachine: Start Dhcp Watchdog 2
08-23 18:36:36.925  1033  7467 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.925  1033  7467 D DhcpStateMachine: WaitBeforeStartState
08-23 18:36:36.926  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=202291  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:36.926  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=202292  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:36.927  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=202292  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:36.927  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.928  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.928  1033  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.929  1033  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.929  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.929  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:36.931  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=202296  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:36.931  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=202297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:36.932  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=202297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:36.933  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:155950] from screen [on:0 period:-1203585595] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-23 18:36:36.934  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1203585594] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-23 18:36:36.934  1033  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-23 18:36:36.942  1033  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-23 18:36:36.943  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:36.943  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:36.943  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:36.944  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:36.944  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:36.945  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:36.945  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 18:36:36.946  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=120,0,0
08-23 18:36:36.946  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=120,0,0
08-23 18:36:36.946  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-23 18:36:36.946  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-23 18:36:36.947  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,08-23 18:36:36.947  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 0
08-23 18:36:36.948  1033  1536 D WifiNative-wlan0: SET ps 0: returned true
08-23 18:36:36.948  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-23 18:36:36.948  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-23 18:36:36.949  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-23 18:36:36.949  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b90dff3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.949  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b90dff3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.949  1033  7467 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.949  1033  7467 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-23 18:36:36.950  1033  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-23 18:36:36.950  1033  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 18:36:36.950  1033  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 18:36:36.951   311   893 D CommandListener: Setting iface cfg
08-23 18:36:36.952   311   893 D CommandListener: Trying to bring up wlan0
08-23 18:36:36.952  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:36.952  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-23 18:36:36.953  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.953  1033  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-23 18:36:36.954  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:36.954  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 18:36:36.954  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-23 18:36:36.954  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-23 18:36:36.954  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.954  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:36.954  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 18:36:36.955  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 18:36:36.955  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 18:36:36.955  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-23 18:36:36.955  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-23 18:36:36.955  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-23 18:36:36.955  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:36.969  7437  7437 D WeatherApplication: removeAccount
,08-23 18:36:36.971  7437  7437 D WeatherApplication: Account.length = 0
08-23 18:36:36.971  7437  7437 E WeatherApplication: OPERATOR:OPEN
08-23 18:36:36.973  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
08-23 18:36:36.974  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 18:36:36.974  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:36.974  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:36.975  7437  7437 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:36
08-23 18:36:36.975  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:36.975  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:36.976  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:36.976  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:36.976  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 18:36:36.977  7437  7437 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 18:36:36.977  7437  7437 D Weather.Utils: 2 : All the weather widget is gone.
08-23 18:36:36.977  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 18:36:36.977  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 18:36:36.977  1033  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 18:36:36.978  7437  7437 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 18:36:36.978  1033  1543 D ConnectivityService: ignoring duplicate network state non-change
08-23 18:36:36.980  7437  7437 D WeatherAncestor: connectivity changed - connection : true
08-23 18:36:36.980  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:36.980  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:36.981  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:36.981  7437  7437 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-23 18:36:36.985  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.985  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.985  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 18:36:36.986  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-23 18:36:36.987  1033  1543 D ConnectivityService: Adding iface wlan0 to network 101
08-23 18:36:36.990  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.990  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.990  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 18:36:36.992  1033  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 18:36:36.993  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 18:36:36.994  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.994  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.994  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 18:36:36.994  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 18:36:36.996  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-23 18:36:36.998  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:36:36.998  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:36.998  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 18:36:36.999  7437  7437 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 18:36:36.999  7437  7437 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 18:36:36.999  7437  7437 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-23 18:36:37.004  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:37.004  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:37.005  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:37.006  1033  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 18:36:37.006  1033  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-23 18:36:37.008  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:37.008  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 18:36:37.008  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:37.009  1033  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-23 18:36:37.010   311   893 E Netd    : netlink response contains error (File exists)
,08-23 18:36:37.010  1033  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-23 18:36:37.011  1033  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-23 18:36:37.011  1033  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-23 18:36:37.011  1033  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-23 18:36:37.012  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-23 18:36:37.012  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-23 18:36:37.012  1033  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-23 18:36:37.012  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-23 18:36:37.012  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:37.012  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:37.012  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 18:36:37.012  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:37.012  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.012  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-23 18:36:37.012  1033  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-23 18:36:37.012  1033  1543 D ConnectivityService:    accepting network in place of null
08-23 18:36:37.012  1033  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.013  1033  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.013  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:37.013  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:37.013  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-23 18:36:37.013  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:36:37.013  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.013  1033  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-23 18:36:37.013  1033  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-23 18:36:37.013  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-23 18:36:37.013  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 18:36:37.013  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 18:36:37.013  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 18:36:37.014  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:37.014  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:37.014  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:37.014  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:37.018  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:37.018  1033  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-23 18:36:37.018  1033  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-23 18:36:37.019  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-23 18:36:37.019   311  7472 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-23 18:36:37.020  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 18:36:37.020  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 18:36:37.020  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 18:36:37.021  1033  1543 D ConnectivityService: validation of new default Network = false
08-23 18:36:37.021  1033  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-23 18:36:37.021  1033  1543 D DSQN    : enableDataServiceNotify 
08-23 18:36:37.021  1033  1543 D DSQN    : start dsqn bin
08-23 18:36:37.026  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-23 18:36:37.019  7473  7473 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file,
08-23 18:36:37.019  7473  7473 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:37.026  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.026  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:37.026  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:37.028  1033  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-23 18:36:37.029  1601  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 18:36:37.029  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 18:36:37.031  1033  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 18:36:37.031  1033  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 18:36:37.032  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 18:36:37.033  1033  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 18:36:37.034  1033  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-23 18:36:37.042  7473  7473 E DSQN    : DSQN ssw
08-23 18:36:37.043  7437  7437 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 18:36:37.043  7437  7437 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:37
08-23 18:36:37.075   311  7472 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-23 18:36:37.084  1033  1938 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7478 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 18:36:37.085  1033  1938 I ActivityManager: Killing 2207:com.lge.music/u0a34 (adj 15): empty #17
08-23 18:36:37.100   318   318 V AudioFlinger: 2207 died, releasing its sessions
08-23 18:36:37.100   318   318 V AudioFlinger:  pid 1852 @ 0
08-23 18:36:37.100   318   318 V AudioFlinger:  pid 3201 @ 1
08-23 18:36:37.100   318   318 V AudioFlinger:  pid 3201 @ 2
,08-23 18:36:37.114   311  7472 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-23 18:36:37.152  1033  7467 D DhcpStateMachine: DHCPV4 request on wlan0
,08-23 18:36:37.153   311   892 D LGDataListener: argv[0]=dsqncommand
08-23 18:36:37.153   311   892 D LGDataListener: argv[1]=wlan0
08-23 18:36:37.153   311   892 D LGDataListener: argv[2]=1
08-23 18:36:37.153   311   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-23 18:36:37.153  1033  7467 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-23 18:36:37.153  1033  7467 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-23 18:36:37.154  1033  1107 D DSQN    : DSQM DsqnNotification wlan0  1
08-23 18:36:37.154  1033  1107 D DSQN    : start to monitor internet connection
08-23 18:36:37.159  7497  7497 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:37.159  7497  7497 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:37.163  1817  7475 I CheckinService: active receiver: enabled
08-23 18:36:37.164  1033  1048 W libprocessgroup: failed to open /acct/uid_10034/pid_2207/cgroup.procs: No such file or directory
,08-23 18:36:37.178  7497  7497 I dhcpcd  : version 5.5.6 starting
08-23 18:36:37.182  7497  7497 E dhcpcd  : get_duid: m
08-23 18:36:37.182  7497  7497 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-23 18:36:37.182  7497  7497 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-23 18:36:37.183  1817  7475 I CheckinService: Preparing to send checkin request
08-23 18:36:37.184  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 16:36:37 GMT], X-Android-Received-Millis=[1471970197184], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471970197152]}
08-23 18:36:37.184  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 18:36:37.185  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-23 18:36:37.185  1033  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-23 18:36:37.185  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-23 18:36:37.185  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:37.185  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:37.185  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 18:36:37.186  1033  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-23 18:36:37.186  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-23 18:36:37.186  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.186  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:37.187  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:37.187  1033  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.187  1601  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 18:36:37.188  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 18:36:37.189  1033  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.189  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 18:36:37.183  1817  7475 I EventLogService: Accumulating logs since 1471970037214
08-23 18:36:37.193  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:37.194  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-23 18:36:37.214  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:37.215  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:37.216  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:37.239  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:37.240  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:37.241  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:37.254  7497  7497 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-23 18:36:37.254  7497  7497 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 18:36:37.255  7497  7497 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 18:36:37.255  7497  7497 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-23 18:36:37.255  7497  7497 D dhcpcd  : wlan0: sending REQUEST (xid 0xb83eb783), next in 4.23 seconds
08-23 18:36:37.276  1817  7475 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-23 18:36:37.280  7497  7497 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-23 18:36:37.330  7497  7497 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-23 18:36:37.330  7497  7497 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-23 18:36:37.330  7497  7497 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-23 18:36:37.330  7497  7497 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-23 18:36:37.330  7497  7497 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 18:36:37.331  7497  7497 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 18:36:37.331  7497  7497 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 18:36:37.331  7497  7497 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-23 18:36:37.382  1033  1977 I art     : Explicit concurrent mark sweep GC freed 103575(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 1.845ms total 100.652ms
,08-23 18:36:37.410   279   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 18:36:37.411   279   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-23 18:36:37.411   279   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 18:36:37.412  7478  7512 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-23 18:36:37.414   279   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 18:36:37.414   279   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-23 18:36:37.414   279   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 18:36:37.417  7478  7512 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-23 18:36:37.434   279   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 18:36:37.434   279   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-23 18:36:37.434   279   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 18:36:37.434  7478  7518 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-23 18:36:37.441   279   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 18:36:37.441   279   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-23 18:36:37.441   279   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 18:36:37.441  7478  7518 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-23 18:36:37.498  1033  1049 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7527 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-23 18:36:37.531  7527  7527 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 18:36:37.531  7527  7527 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 18:36:37.546  7527  7527 I MultiDex: VM with version 2.1.0 has multidex support
08-23 18:36:37.546  7527  7527 I MultiDex: install
08-23 18:36:37.546  7527  7527 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 18:36:37.553  7527  7527 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-23 18:36:37.559  1033  7467 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-23 18:36:37.560  1033  7467 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-23 18:36:37.560  1033  7467 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 18:36:37.560  1033  7467 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-23 18:36:37.560  1033  7467 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-23 18:36:37.560  1033  7467 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 18:36:37.560  1033  7467 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-23 18:36:37.560  1033  7467 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-23 18:36:37.561  1033  7467 D DhcpStateMachine: RunningState
08-23 18:36:37.611  7478  7478 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-23 18:36:37.618  7478  7478 I LibraryLoader: Loading: webviewchromium
08-23 18:36:37.621  7478  7478 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2997-3000)
08-23 18:36:37.621  7478  7478 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 18:36:37.628  7478  7478 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31d9d24e}
08-23 18:36:37.631  7478  7478 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 18:36:37.632  7478  7478 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 18:36:37.655  7478  7478 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 18:36:37.656  7478  7478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 18:36:37.674  7478  7478 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-23 18:36:37.675  7478  7478 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-23 18:36:37.675  7478  7478 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-23 18:36:37.678   318  1700 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
,08-23 18:36:37.680  7478  7568 W AudioManagerAndroid: Requires BLUETOOTH permission
08-23 18:36:37.694  7478  7478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 18:36:37.694  7478  7478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 18:36:37.694  7478  7478 I Adreno-EGL: Build Date: 12/12/14 금
08-23 18:36:37.694  7478  7478 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 18:36:37.694  7478  7478 I Adreno-EGL: Remote Branch: 
08-23 18:36:37.694  7478  7478 I Adreno-EGL: Local Patches: 
08-23 18:36:37.694  7478  7478 I Adreno-EGL: Reconstruct Branch: 
,08-23 18:36:37.789  7478  7478 I NSApplication: Starting up...
,08-23 18:36:37.790  7576  7576 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-23 18:36:37.831  7576  7576 I dex2oat : dex2oat took 40.745ms (threads: 4)
,08-23 18:36:37.844  7527  7545 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 18:36:37.844  7527  7545 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 18:36:37.844  7527  7545 I Adreno-EGL: Build Date: 12/12/14 금
08-23 18:36:37.844  7527  7545 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 18:36:37.844  7527  7545 I Adreno-EGL: Remote Branch: 
08-23 18:36:37.844  7527  7545 I Adreno-EGL: Local Patches: 
08-23 18:36:37.844  7527  7545 I Adreno-EGL: Reconstruct Branch: 
,08-23 18:36:37.853  1033  1781 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7587 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-23 18:36:37.855  1033  1781 I ActivityManager: Killing 6725:com.android.vending/u0a44 (adj 15): empty #17
08-23 18:36:37.959  7527  7545 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 18:36:37.959  7527  7545 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 18:36:37.959  7527  7545 I Adreno-EGL: Build Date: 12/12/14 금
08-23 18:36:37.959  7527  7545 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 18:36:37.959  7527  7545 I Adreno-EGL: Remote Branch: 
08-23 18:36:37.959  7527  7545 I Adreno-EGL: Local Patches: 
08-23 18:36:37.959  7527  7545 I Adreno-EGL: Reconstruct Branch: 
,08-23 18:36:37.966  1033  1939 W libprocessgroup: failed to open /acct/uid_10044/pid_6725/cgroup.procs: No such file or directory
08-23 18:36:37.996  1033  1781 D WifiServiceImplEx: setWifiEnabled: false pid=6980, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 18:36:37.996  1033  1781 D WifiService: setWifiEnabled: false pid=6980, uid=10118
08-23 18:36:37.996  1033  1781 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 18:36:38.016  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:38.016  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-23 18:36:38.017  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-23 18:36:38.018  1033  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:38.019  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:38.021  1033  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:38.022  1033  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:38.023  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-23 18:36:38.023  1033  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 18:36:38.023  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:36:38.024  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 18:36:38.024  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 18:36:38.024  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 18:36:38.027  1033  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-23 18:36:38.031  7587  7587 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:36:38.035  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 18:36:38.035  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 18:36:38.036  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 18:36:38.037  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 18:36:38.037  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:38.037  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.037  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.038  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
08-23 18:36:38.038  1033  7467 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.041   311   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:36:38.045  7527  7545 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:38.045  7527  7545 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:38.067  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 18:36:38.067  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-23 18:36:38.070  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-23 18:36:38.070  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:38.070  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:38.071  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:38.073  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:38.073  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:38.073  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:38.073  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:38.073  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:38.073  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:38.074  1033  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 18:36:38.074  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-23 18:36:38.075  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.075  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.075  1033  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1318d37d
08-23 18:36:38.075  1033  1535 D LGWifiP2pService: P2pDisablingState
08-23 18:36:38.075  1033  1535 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.075  1033  1535 D LGWifiP2pService: p2p socket connection lost
08-23 18:36:38.075  1033  1535 D LGWifiP2pService: P2pDisabledState
08-23 18:36:38.075  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-23 18:36:38.076  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:38.076  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:38.076  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:38.076  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 18:36:38.076  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-23 18:36:38.076  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-23 18:36:38.076  1033  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.076  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 18:36:38.076  1033  1555 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.076  7360  7360 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 18:36:38.076  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.076  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.077  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 18:36:38.077  1941  1941 D WfdsService: WifiP2pState is changed : false
08-23 18:36:38.0,77  1941  2256 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-23 18:36:38.077  1941  2256 D WfdsService: Set the WFDS Monitor: false
08-23 18:36:38.078  1941  2256 D WfdsMonitor: WFDS Monitor is stopped
08-23 18:36:38.078  1941  2256 D WfdsService: STATE : WfdsDisabledState - enter
08-23 18:36:38.078  1941  7390 D CtrlSupplicant: Received on exit socket, terminate
08-23 18:36:38.078  1941  7390 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-23 18:36:38.078  1941  7390 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-23 18:36:38.078  1941  7390 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-23 18:36:38.078  1941  2257 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-23 18:36:38.078  1941  2256 W WfdsService: DefaultState - msg [9445378] is not handled
08-23 18:36:38.081  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 18:36:38.081  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:38.082  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
,08-23 18:36:38.092  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:38.092  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:38.093  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:38.121  1033  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-23 18:36:38.121  1033  1543 D DSQN    : disableDataServiceNotify
08-23 18:36:38.121  1033  1543 D DSQN    : stop dsqn bin
08-23 18:36:38.121   311   893 D CommandListener: Clearing all IP addresses on wlan0
08-23 18:36:38.123  1033  1536 D WifiNative-p2p0: doBoolean: TERMINATE
08-23 18:36:38.123  1033  1536 D WifiNative-p2p0: TERMINATE: returned true
08-23 18:36:38.123  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:38.123  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:38.123  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-23 18:36:38.123  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-23 18:36:38.123  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:38.124  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-23 18:36:38.125  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:38.126  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:38.126  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:38.126  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:38.128  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-23 18:36:38.129  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-23 18:36:38.129  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:38.129  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-23 18:36:38.130  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:38.130  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:38.130  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:38.130  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:38.131  1033  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-23 18:36:38.131  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:38.131  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:38.131  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:38.131  1033  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 1,8:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:38.131  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:38.131  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:38.131  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:38.131  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-23 18:36:38.132  1033  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-23 18:36:38.132  1033  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-23 18:36:38.132  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 18:36:38.132  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:38.132  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 18:36:38.132  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 18:36:38.132  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.132  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.132  1033  7464 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-23 18:36:38.133  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 18:36:38.133  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 18:36:38.133  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 18:36:38.133  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 18:36:38.133  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:38.133  1033  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:38.133  1033  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:38.133  1601  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-23 18:36:38.133  1033  1543 D NetworkManagementService: Removing idletimer
08-23 18:36:38.133  1033  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider,.Settings.Global, returning read-only value.
08-23 18:36:38.134  1033  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:38.134  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:38.134  1033  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 18:36:38.134  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:38.134  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 18:36:38.134  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 18:36:38.135  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 18:36:38.135  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 18:36:38.135  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 18:36:38.135  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 18:36:38.144  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:38.162  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:38.163  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:38.163  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:38.175  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:38.176  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:38.176  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:38.222  7527  7545 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 18:36:38.222  7527  7545 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 18:36:38.222  7527  7545 I Adreno-EGL: Build Date: 12/12/14 금
08-23 18:36:38.222  7527  7545 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 18:36:38.222  7527  7545 I Adreno-EGL: Remote Branch: 
08-23 18:36:38.222  7527  7545 I Adreno-EGL: Local Patches: 
08-23 18:36:38.222  7527  7545 I Adreno-EGL: Reconstruct Branch: 
,08-23 18:36:38.241  7360  7360 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 18:36:38.241  7360  7360 I wpa_supplicant: monitor socket send errors count : 1
08-23 18:36:38.241  7360  7360 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-23 18:36:38.242  1033  7373 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-23 18:36:38.242  1033  7373 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-23 18:36:38.252  1033  7467 D DhcpStateMachine: StoppedState
08-23 18:36:38.252  1033  7467 D DhcpStateMachine: StoppedState{ when=-171ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:38.253  1033  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-23 18:36:38.253  1033  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-23 18:36:38.256  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-23 18:36:38.257  6554  7143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-23 18:36:38.262  7360  7360 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-23 18:36:38.263  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-23 18:36:38.263  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 18:36:38.263  1033  7373 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 18:36:38.263  7360  7360 W wpa_supplicant: USIM:  scard_deinit function
08-23 18:36:38.264  1033  7373 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-23 18:36:38.264  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:38.264  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:38.264  1033  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=203630
08-23 18:36:38.264  1033  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=203630
08-23 18:36:38.265  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=203630  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 18:36:38.265  1033  1109 D Tethering: InitialState.processMessage what=4
08-23 18:36:38.265  1033  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=203630  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 18:36:38.266  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:36:38.267  1033  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:38.267  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-23 18:36:38.277  2164  2164 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:38.284  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 18:36:38.284  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:38.285  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-23 18:36:38.285  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 18:36:38.286  7307  7307 I AppUp4:CustModeStarterReceiver: onReceive
08-23 18:36:38.292  7307  7307 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30751f87
08-23 18:36:38.292  7307  7307 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 18:36:38.292  7307  7307 D AppUp4:CustFacade: isPhone : true
08-23 18:36:38.293  7307  7307 D AppUp4:CustModeStarterReceiver: begin check event
08-23 18:36:38.293  7307  7307 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-23 18:36:38.295  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:38.295  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:38.296  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 18:36:38.299  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:38.303  7330  7330 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-23 18:36:38.304  4834  7621 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 18:36:38.305  4834  7622 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:38.306  4834  7622 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:38.320  7330  7624 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:36:38.327  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-23 18:36:38.327  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:38.328  7213  7627 W FormManager: Network not available. Please check & try again.
08-23 18:36:38.328  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 18:36:38.336  7213  7628 V FormManager: Network unavailable.
,08-23 18:36:38.338  7213  7628 V FormManager: Network unavailable.
08-23 18:36:38.340  7374  7374 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 18:36:38.340  7374  7374 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 18:36:38.347  7437  7437 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:38
08-23 18:36:38.348  7437  7437 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 18:36:38.348  7437  7437 D Weather.Utils: 2 : All the weather widget is gone.
,08-23 18:36:38.350  7437  7437 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-23 18:36:38.350  7437  7437 D WeatherAncestor: connectivity changed - connection : true
08-23 18:36:38.350  7437  7437 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a4b3add
08-23 18:36:38.352  7437  7437 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 18:36:38.352  7437  7437 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 18:36:38.352  7437  7437 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 18:36:38.352  7437  7437 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 18:36:38.352  7437  7437 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:38
08-23 18:36:38.369  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 18:36:38.369  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 18:36:38.369  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 18:36:38.369  7102  7102 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 18:36:38.369  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 18:36:38.370  7102  7102 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 18:36:38.370  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 18:36:38.370  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-23 18:36:38.370  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 18:36:38.370  7102  7102 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 18:36:38.370  7102  7102 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-23 18:36:38.377  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:38.382  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 18:36:38.384  7213  7631 W FormManager: Network not available. Please check & try again.
,08-23 18:36:38.386  7213  7632 V FormManager: Network unavailable.
08-23 18:36:38.388  7213  7632 V FormManager: Network unavailable.
08-23 18:36:38.389  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.401  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:38.402  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 18:36:38.404  7213  7634 W FormManager: Network not available. Please check & try again.
08-23 18:36:38.407  7213  7635 V FormManager: Network unavailable.
08-23 18:36:38.407  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.411  7360  7360 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-23 18:36:38.414  1033  7373 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-23 18:36:38.414  1033  7373 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-23 18:36:38.414  1033  7373 D WifiMonitor: Disconnecting from the supplicant, no more events
08-23 18:36:38.414  7213  7635 V FormManager: Network unavailable.
,08-23 18:36:38.416  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-23 18:36:38.416  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 18:36:38.417  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:38.417  1033  1536 D WifiOffDelayIfNotUsed: stopMonitoring
08-23 18:36:38.417  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:38.417  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:38.417  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 18:36:38.417  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:38.418  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-23 18:36:38.418  1941  2256 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-23 18:36:38.418  1941  2256 D WfdsService: Set the WFDS Monitor: false
08-23 18:36:38.418  1941  2256 D WfdsMonitor: WFDS Monitor is stopped
08-23 18:36:38.419  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 18:36:38.419  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:38.420  2504  2504 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:38.421  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:38.421  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:38.421  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
0,8-23 18:36:38.422  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-23 18:36:38.422  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-23 18:36:38.422  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-23 18:36:38.423  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:38.427  4834  7636 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 18:36:38.429  4834  7637 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 18:36:38.429  4834  7637 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:38.447  1033  1574 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-23 18:36:38.458   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 9.431ms
,08-23 18:36:38.468   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.488ms
08-23 18:36:38.478   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 200us total 8.904ms
,08-23 18:36:38.496   311  7656 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-23 18:36:38.496  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-23 18:36:38.496  1817  7475 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-23 18:36:38.499  7638  7638 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-23 18:36:38.500  7638  7638 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-23 18:36:38.502  1817  7475 I CheckinService: active receiver: disabled
08-23 18:36:38.505  7638  7638 V [BNRBootReceiver]: Boot Receiver Return
08-23 18:36:38.505  7638  7638 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 18:36:38.510  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.519  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.524  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.533  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:38.533  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.534  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:38.537  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.542  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.547  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 18:36:38.552  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:38.552  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.554  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:38.557  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-23 18:36:38.561  7102  7102 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-23 18:36:38.564  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.570  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.578  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 18:36:38.584  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:38.585  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.586  7172  7172 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 18:36:38.593  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 18:36:38.605  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.618  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.633  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:38.634  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.635  7172  7172 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 18:36:38.643  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 18:36:38.645  1033  1390 D PowerManagerServiceEx: acquireWakeLockInternal: lock=951409497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
08-23 18:36:38.665  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.674  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.686  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:38.687  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.688  7172  7172 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 18:36:38.693  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.708  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:38.709  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 18:36:38.725  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.739  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:38.740  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 18:36:38.741  7172  7172 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 18:36:38.746  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 18:36:38.754  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.761  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.768  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:38.768  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.769  7172  7172 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 18:36:38.776  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.788  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.795  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.804  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:38.805  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 18:36:38.811  7172  7172 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 18:36:38.819  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.833  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.844  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.857  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:38.857  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.859  7172  7172 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 18:36:38.867  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.874  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-23 18:36:38.885  1033  1542 D WifiService: New client listening to asynchronous messages
08-23 18:36:38.885  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:38.892  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.901  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:38.912  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:38.913  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.915  7172  7172 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-23 18:36:38.917  7172  7172 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 18:36:38.918  7172  7172 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-23 18:36:38.925  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:38.930  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-23 18:36:38.937  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:38.941  6878  7283 D UEI.SmartControl: Internal timer expired: 2
08-23 18:36:38.941  6878  7283 D UEI.SmartControl: unbind internal service
08-23 18:36:38.943  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:38.955  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 18:36:38.969  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:38.970  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:38.972  7172  7172 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-23 18:36:38.973  7172  7172 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 18:36:38.974  7172  7172 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 18:36:38.980  1033  1049 I ActivityManager: Killing 7122:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-23 18:36:39.015  6878  7277 D serial_port: close(fd = 24)
,08-23 18:36:39.019  6878  7277 I UEI.SmartControl: Serial port is closed.
08-23 18:36:39.054  1033  1977 W libprocessgroup: failed to open /acct/uid_10037/pid_7122/cgroup.procs: No such file or directory
,08-23 18:36:39.069  2164  2164 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-23 18:36:39.096  2164  2164 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-23 18:36:39.097  2164  2164 D c       : Getting all permits...
08-23 18:36:39.097  2164  2164 D a       : Opening database...
08-23 18:36:39.102  2164  2164 D a       : Opening database auth.proximity.permit_store...
08-23 18:36:39.103  2164  2164 D a       : Closing database...
,08-23 18:36:39.119  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 18:36:39.124  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 18:36:39.124  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:39.124  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:39.129  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:39.141  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:39.150  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:39.150  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 18:36:39.154  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:39.158  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:39.163  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 18:36:39.163  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:39.163  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:39.170  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:39.176  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:39.183  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:39.183  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 18:36:39.185  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:39.188  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:39.191  7144  7144 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 18:36:39.191  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:39.191  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:39.195  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:39.201  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:39.209  7172  7172 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:39.209  7172  7172 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:39.211  7172  7172 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 18:36:39.220  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:39.224  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:36:39.229  7213  7668 W FormManager: Network not available. Please check & try again.
08-23 18:36:39.232  7213  7669 V FormManager: Network unavailable.
08-23 18:36:39.234  7213  7669 V FormManager: Network unavailable.
08-23 18:36:39.236  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:39.253  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-23 18:36:39.253  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:39.255  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:39.258  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:39.265  4834  7670 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 18:36:39.267  7144  7144 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-23 18:36:39.267  7144  7144 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 18:36:39.267  7144  7144 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:39.271  4834  7671 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 18:36:39.271  4834  7671 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:39.274  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:36:39.284  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:39.294  7213  7673 W FormManager: Network not available. Please check & try again.
,08-23 18:36:39.303  7213  7674 V FormManager: Network unavailable.
08-23 18:36:39.307  2164  2164 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-23 18:36:39.320  7213  7674 V FormManager: Network unavailable.
,08-23 18:36:39.325  7172  7172 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-23 18:36:39.326  7172  7172 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:956
08-23 18:36:39.328  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=951409497 [*alarm*], flags=0x0
08-23 18:36:39.944  1033  1536 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1203582584] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-23 18:36:39.946  1033  1536 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1203582582] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-23 18:36:40.021  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:36:40.027  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:40.027  1033  1109 D Tethering: MasterInitialState.processMessage what=3
08-23 18:36:40.035  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:40.041  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:40.046  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-23 18:36:40.048  6554  7143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 18:36:40.061  5994  5994 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-23 18:36:40.087  2164  2164 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:36:40.116  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 18:36:40.116  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:40.116  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 18:36:40.116  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-23 18:36:40.123  7307  7307 I AppUp4:CustModeStarterReceiver: onReceive
08-23 18:36:40.127  7307  7307 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30751f87
08-23 18:36:40.127  7307  7307 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 18:36:40.127  7307  7307 D AppUp4:CustFacade: isPhone : true
08-23 18:36:40.127  7307  7307 D AppUp4:CustModeStarterReceiver: begin check event
08-23 18:36:40.127  7307  7307 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-23 18:36:40.133  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:40.133  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:40.135  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 18:36:40.142  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:40.157  7330  7330 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-23 18:36:40.164  4834  7699 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 18:36:40.167  4834  7701 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:40.168  4834  7701 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:40.185  7330  7703 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:36:40.192  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 18:36:40.192  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:40.192  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = true
08-23 18:36:40.192  3201  3201 D PhoneState: setPdpRejectCasuse : false
08-23 18:36:40.196  7374  7374 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 18:36:40.196  7374  7374 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 18:36:40.201  7213  7708 W FormManager: Network not available. Please check & try again.
,08-23 18:36:40.204  7213  7709 V FormManager: Network unavailable.
08-23 18:36:40.212  7437  7437 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:40
08-23 18:36:40.213  7437  7437 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 18:36:40.214  7437  7437 D Weather.Utils: 2 : All the weather widget is gone.
,08-23 18:36:40.214  7213  7709 V FormManager: Network unavailable.
08-23 18:36:40.216  7437  7437 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 18:36:40.216  7437  7437 D WeatherAncestor: connectivity changed - connection : true
08-23 18:36:40.216  7437  7437 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a4b3add
08-23 18:36:40.219  7437  7437 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 18:36:40.219  7437  7437 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 18:36:40.219  7437  7437 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 18:36:40.219  7437  7437 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 18:36:40.220  7437  7437 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:40
08-23 18:36:40.296  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 18:36:41.016  1033  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 18:36:41.017  1033  1977 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-23 18:36:41.069  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:41.070  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 18:36:41.071  1033  1109 D BluetoothManagerService: Message: 1
08-23 18:36:41.071  1033  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-23 18:36:41.073  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-23 18:36:41.112  1033  1109 D BluetoothManagerService: Message: 20
08-23 18:36:41.112  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@150f7170:true
,08-23 18:36:41.117  7237  7237 D BluetoothAdapterState: make
08-23 18:36:41.128  7237  7237 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-23 18:36:41.128  7237  7237 I bluedroid-qcom: init
,08-23 18:36:41.132  7237  7720 I BluetoothAdapterState: Entering OffState
08-23 18:36:41.132  7237  7237 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 18:36:41.133  7237  7237 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 18:36:41.133  7237  7237 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 18:36:41.133  7237  7237 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 18:36:41.133  7237  7237 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-23 18:36:41.134  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.129  7723  7723 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:41.129  7723  7723 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:41.144  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,08-23 18:36:41.148  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.152  7237  7237 I bluedroid-qcom: get_profile_interface socket
08-23 18:36:41.152  7237  7237 I bluedroid-qcom: get_profile_interface map_client
08-23 18:36:41.156  7723  7723 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-23 18:36:41.156  7723  7723 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-23 18:36:41.156  7723  7723 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-23 18:36:41.157  7237  7724 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-23 18:36:41.163  7723  7723 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-23 18:36:41.165  7237  7724 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-23 18:36:41.189  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,08-23 18:36:41.190  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:41.192  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:41.196  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-23 18:36:41.200  6554  7143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 18:36:41.201  7237  7724 D BluetoothAdapterProperties: Name is: G3
08-23 18:36:41.202  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:36:41.207  7723  7723 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-23 18:36:41.207  7723  7723 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-23 18:36:41.215  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:41.218  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:41.218  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 18:36:41.219  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 18:36:41.222  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-23 18:36:41.222  1033  1109 D BluetoothManagerService: Message: 40
08-23 18:36:41.222  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-23 18:36:41.222  5994  5994 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-23 18:36:41.223  7237  7256 I bluedroid-qcom: config_hci_snoop_log
08-23 18:36:41.228  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
,08-23 18:36:41.228  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-23 18:36:41.229  5994  5994 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-23 18:36:41.236  7237  7720 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-23 18:36:41.237  7237  7720 D BluetoothAdapterProperties: Setting state to 11
08-23 18:36:41.237  7237  7720 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 18:36:41.237  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:41.238  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-23 18:36:41.238  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-23 18:36:41.239  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.240  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:36:41.241  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 18:36:41.245  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:41.246  7102  7102 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-23 18:36:41.247  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:41.248  7237  7720 I LGBluetoothServiceJni: classInitNative: succeeds
08-23 18:36:41.252  7237  7237 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 18:36:41.253  7237  7237 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:41.253  7237  7237 V BluetoothPbapReceiver: ***********state = 11
,08-23 18:36:41.254  7237  7720 D BluetoothBondStateMachine: make
08-23 18:36:41.257  7237  7720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.257  7237  7720 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-23 18:36:41.257  7237  7720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.257  7237  7720 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-23 18:36:41.258  7237  7720 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-23 18:36:41.259  7237  7736 I BluetoothBondStateMachine: StableState(): Entering Off State
08-23 18:36:41.261  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:36:41.262  7237  7720 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:41.264  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:41.264  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:41.271  7237  7720 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 18:36:41.276  7237  7237 D HeadsetService: Received start request. Starting profile...
08-23 18:36:41.277  7237  7237 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 18:36:41.277  7237  7237 D LGBluetoothHfpAdapter: Version 1.6
08-23 18:36:41.280  7237  7237 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 18:36:41.281  7237  7237 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 18:36:41.282  7237  7237 D HeadsetStateMachine: make
,08-23 18:36:41.320  7237  7237 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:41.320  7237  7237 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 18:36:41.320  1033  1782 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7744 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-23 18:36:41.326  2164  2164 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.328  7237  7237 D HeadsetStateMachine: max_hf_connections = 1
08-23 18:36:41.328  7237  7237 I bluedroid-qcom: get_profile_interface handsfree
08-23 18:36:41.329  7237  7720 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:41.331  7237  7237 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-23 18:36:41.332   318  1384 V AudioPolicyService: registerClient() client 0xb0410c20, uid 1002
08-23 18:36:41.332   318   318 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-23 18:36:41.332   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 18:36:41.332   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 18:36:41.332  7237  7237 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-23 18:36:41.333   318  1383 V AudioFlinger: registerClient() client 0xb14332b0, pid 7237
08-23 18:36:41.333   318  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:41.333   318  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-23 18:36:41.334  3201  3222 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:41.334  3201  3222 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:41.334   318  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:41.334   318  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:41.334  1033  1653 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:41.334  7237  7254 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:41.334  1033  1653 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:41.334  1033  1653 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:41.334  1033  1653 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:41.335  3201  3225 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:41.335  3201  3225 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:41.335  7237  7237 V ToneGenerator: Create Track: 0xb4928a80
08-23 18:36:41.335  7237  7237 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-23 18:36:41.335  7237  7237 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-23 18:36:41.335   318  4487 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 18:36:41.335   318  4487 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-23 18:36:41.335   318  4487 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 18:36:41.336   318  4487 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 18:36:41.336  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:41.336  7237  7254 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-23 18:36:41.336  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:41.336  7237  7254 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:41.336  7237  7254 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-23 18:36:41.336  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:41.336  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:41.336  1852  2445 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:41.337  1852  2445 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:41.337  1852  2445 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:41.337  1852  2445 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:41.337  7237  7720 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:41.340   318  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 18:36:41.341   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 18:36:41.341   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-23 18:36:41.341   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 18:36:41.341   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 18:36:41.341  7237  7237 V AudioSystem: getLatency() output 2, latency 50
08-23 18:36:41.341  7237  7237 V AudioSystem: getFrameCount() output 2, frameCount 960
08-23 18:36:41.341  7237  7237 V AudioTrack: createTrack_l() output 2 afLatency 50
08-23 18:36:41.342   318  1700 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 18:36:41.342   318  1700 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 18:36:41.342   318  1700 V AudioFlinger: [MABL_AudioFlinger] PlaybackTh,read::setMABLEnable(), enable = 0 
08-23 18:36:41.342   318  1700 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 18:36:41.342   318  1700 V AudioFlinger: createTrack() lSessionId: 22
08-23 18:36:41.343  7237  7237 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-23 18:36:41.343   318  1700 V AudioFlinger: acquiring 22 from 7237, for 7237
08-23 18:36:41.343   318  1700 V AudioFlinger:  added new entry for 22
08-23 18:36:41.344  7237  7237 V ToneGenerator: ToneGenerator INIT OK, time: 206723
08-23 18:36:41.344  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.344  7237  7742 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-23 18:36:41.344  7237  7742 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 18:36:41.345  7237  7742 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 18:36:41.345  7237  7742 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-23 18:36:41.345   318  4487 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7237
08-23 18:36:41.345  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.345  7237  7720 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:41.345   318  4487 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-23 18:36:41.345   318  4487 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-23 18:36:41.345   318  4487 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-23 18:36:41.345   318  4487 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-23 18:36:41.345   318  4487 V voice   : voice_set_parameters: exit with code(0)
08-23 18:36:41.346   318  4487 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-23 18:36:41.346   318  4487 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-23 18:36:41.346   318  4487 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 18:36:41.346   318  4487 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 18:36:41.346   318  4487 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-23 18:36:41.346   318  4487 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-23 18:36:41.346  7237  7742 V ToneGenerator: ToneGenerator destructor
08-23 18:36:41.346  7237  7742 V ToneGenerator: stopTone
08-23 18:36:41.346  7237  7742 V ToneGenerator: Delete Track: 0xb4928a80
08-23 18:36:41.346  7237  7742 V AudioTrack: ~AudioTrack, releasing session id from 7237 on behalf of 7237
08-23 18:36:41.347   318  1384 V AudioFlinger: releasing 22 from 7237 for 7237
08-23 18:36:41.347   318  1384 V AudioFlinger:  decremented refcount to 0
08-23 18:36:41.347   318  1384 V AudioFlinger: purging stale effects
08-23 18:36:41.347   318  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-23 18:36:41.347   318  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-23 18:36:41.347   318  1384 V AudioFlinger: PlaybackThread::Track destructor
08-23 18:36:41.347   318  1257 V AudioPolicyService: AudioCommandThread() waking up
08-23 18:36:41.347   318  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
08-23 18:36:41.347   318  1384 V AudioFlinger: removeClient_l() pid 7237, calling pid 318
08-23 18:36:41.347   318  1257 V AudioPolicyManager: releaseOutput() 2
08-23 18:36:41.347   318  1257 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 18:36:41.347  7237  7237 D A2dpService: Received start request. Starting profile...
08-23 18:36:41.348  7237  7237 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 18:36:41.348  7237  7237 V Avrcp   : make
08-23 18:36:41.349  7237  7237 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-23 18:36:41.349  7237  7237 I bluedroid-qcom: get_profile_interface avrcp
08-23 18:36:41.351  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 18:36:41.353  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.353  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 18:36:41.353  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 18:36:41.359  7237  7237 V AudioManager: registerRemoteController: size of Media player list: 0
08-23 18:36:41.359  7237  7720 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:41.360  7237  7237 E AudioManager: No RCC entry present to update
08-23 18:36:41.360  7237  7237 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-23 18:36:41.364  7237  7237 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-23 18:36:41.365  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-23 18:36:41.365  7237  7237 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-23 18:36:41.365  7307  7307 I AppUp4:CustModeStarterReceiver: onReceive
08-23 18:36:41.366  7237  7720 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:41.369  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 18:36:41.372  7307  7307 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30751f87
08-23 18:36:41.372  7307  7307 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 18:36:41.372  7307  7307 D AppUp4:CustFacade: isPhone : true
08-23 18:36:41.382  7237  7720 V LGMDMManager: Create singleton instance
,08-23 18:36:41.389  7237  7720 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 18:36:41.407  7307  7307 D AppUp4:CustModeStarterReceiver: begin check event
08-23 18:36:41.408  7307  7307 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-23 18:36:41.422  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-23 18:36:41.422  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:41.424  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:41.426  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:41.442  4834  7764 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 18:36:41.449  4834  7765 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.449  7330  7330 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-23 18:36:41.450  4834  7765 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:41.455  1033  1939 V SIM_STK : Menu title from STK is T-Mobile
08-23 18:36:41.455  1033  1939 V SIM_STK : Menu title from STK is T-Mobile
08-23 18:36:41.467  7330  7766 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:41.468  7213  7768 W FormManager: Network not available. Please check & try again.
,08-23 18:36:41.475  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 18:36:41.475  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.475  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 18:36:41.478  7374  7374 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 18:36:41.478  7374  7374 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 18:36:41.483  7744  7744 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 18:36:41.483  7744  7744 W LG Account v2.2: No ProfileInfo entries
08-23 18:36:41.483  7744  7744 I LG Account v2.2: isEnabled: false
,08-23 18:36:41.483  7744  7744 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Country: EU
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Operator: OPEN
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Ranking support: false
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Comfort support: false
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Accessory: true
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Health device: true
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Extra Pedometer: false
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Blood glucose device: false
08-23 18:36:41.484  7744  7744 I Feature : [Lifetracker]Device Number: 3
08-23 18:36:41.485  7213  7769 V FormManager: Network unavailable.
08-23 18:36:41.492  7437  7437 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:41
08-23 18:36:41.495  7102  7102 D BluetoothPermissionRequest: onReceive
08-23 18:36:41.495  7437  7437 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 18:36:41.496  7437  7437 D Weather.Utils: 2 : All the weather widget is gone.
,08-23 18:36:41.498  7437  7437 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 18:36:41.499  7437  7437 D WeatherAncestor: connectivity changed - connection : true
08-23 18:36:41.499  7437  7437 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a4b3add
08-23 18:36:41.499  7213  7769 V FormManager: Network unavailable.
08-23 18:36:41.499  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 18:36:41.499  7437  7437 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 18:36:41.499  7437  7437 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 18:36:41.499  7437  7437 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 18:36:41.499  7437  7437 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 18:36:41.499  7437  7437 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:41
08-23 18:36:41.516  6554  6554 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-23 18:36:41.516  1033  1048 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 18:36:41.517  6554  7143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 18:36:41.521  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 18:36:41.524  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 18:36:41.525  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 18:36:41.525  7237  7237 I BluetoothA2dpServiceJni: classInitNative
08-23 18:36:41.526  7237  7237 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 18:36:41.526  7237  7237 D A2dpStateMachine: make
08-23 18:36:41.526  7237  7237 I bluedroid-qcom: get_profile_interface a2dp
08-23 18:36:41.527  7237  7774 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 18:36:41.528  7237  7237 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-23 18:36:41.528  7237  7237 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-23 18:36:41.529  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.529  7237  7237 D HeadsetStateMachine: Proxy object connected
,08-23 18:36:41.529  7237  7237 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-23 18:36:41.529  2164  2164 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.529  7237  7237 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-23 18:36:41.530  7237  7237 I BluetoothHidServiceJni: classInitNative: succeeds
08-23 18:36:41.531  7237  7773 D A2dpStateMachine: Enter Disconnected: -2
08-23 18:36:41.531  7237  7237 D HidService: Received start request. Starting profile...
08-23 18:36:41.531  7237  7237 I bluedroid-qcom: get_profile_interface hidhost
08-23 18:36:41.531  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.532  7237  7237 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 18:36:41.533  7237  7237 D HealthService: Received start request. Starting profile...
08-23 18:36:41.534  7237  7237 I bluedroid-qcom: get_profile_interface health
08-23 18:36:41.534  7237  7237 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-23 18:36:41.534  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.536  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 18:36:41.536  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.537  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 18:36:41.537  7307  7307 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 18:36:41.537  7237  7237 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:41.537  7237  7237 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 18:36:41.538  7237  7742 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 18:36:41.538  7237  7742 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 18:36:41.538  7237  7742 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-23 18:36:41.538  7307  7307 I AppUp4:CustModeStarterReceiver: onReceive
08-23 18:36:41.538  7237  7237 D PanService: Received start request. Starting profile...
08-23 18:36:41.539  7237  7237 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 18:36:41.539  7237  7237 I bluedroid-qcom: get_profile_interface pan
08-23 18:36:41.540  7307  7307 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30751f87
08-23 18:36:41.540  7307  7307 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-23 18:36:41.540  7307  7307 D AppUp4:CustFacade: isPhone : true
08-23 18:36:41.540  7307  7307 D AppUp4:CustModeStarterReceiver: begin check event
08-23 18:36:41.540  7307  7307 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-23 18:36:41.544  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.544  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:41.544  7237  7237 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-23 18:36:41.544  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.545  7237  7237 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-23 18:36:41.545  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:41.547  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:41.548  7237  7237 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 18:36:41.548  7237  7237 D BtGatt.GattService: Received start request. Starting profile...
08-23 18:36:41.548  7237  7237 D BtGatt.GattService: start()
08-23 18:36:41.548  7237  7237 I bluedroid-qcom: get_profile_interface gatt
08-23 18:36:41.549  7237  7237 D BtGatt.AdvertiseManager: advertise manager created
08-23 18:36:41.550  4834  7779 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 18:36:41.552  7330  7330 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-23 18:36:41.552  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.553  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:41.553  7237  7237 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-23 18:36:41.554  7237  7237 V BluetoothMapService: BluetoothMapBinder()
08-23 18:36:41.555  7237  7237 D BluetoothMapService: Received start request. Starting profile...
08-23 18:36:41.555  7237  7237 D BluetoothMapService: start()
08-23 18:36:41.556  4834  7781 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.556  4834  7781 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:41.558  7237  7237 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-23 18:36:41.558  7237  7237 D BluetoothMapEmailAppObserver: createReceiver()
08-23 18:36:41.559  7237  7237 D BluetoothMapEmailAppObserver: initObservers()
08-23 18:36:41.560  7237  7237 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-23 18:36:41.564  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
,08-23 18:36:41.568  7237  7237 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:41.570  7330  7783 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:41.570  7237  7237 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:41.572  7237  7237 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:41.572  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 18:36:41.572  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:41.573  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 18:36:41.573  7237  7237 V PanService: [BTUI] SIM Extra State :ABSENT
08-23 18:36:41.575  7237  7237 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:41.576  7213  7785 W FormManager: Network not available. Please check & try again.
,08-23 18:36:41.577  7237  7237 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-23 18:36:41.577  7237  7237 V BluetoothMapService: Handler(): got msg=1
08-23 18:36:41.578  7237  7720 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-23 18:36:41.578  7237  7720 I bluedroid-qcom: enable
08-23 18:36:41.578  7237  7720 I bt_hci_bdroid: init
08-23 18:36:41.578  7237  7788 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 18:36:41.578  7237  7788 I bt-btu  : btu_task pending for preload complete event
08-23 18:36:41.579  7237  7237 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:41.579  7237  7720 I bt_vendor: bt-vendor : init
08-23 18:36:41.579  7237  7720 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 18:36:41.579  7237  7720 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 18:36:41.579  7237  7720 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-23 18:36:41.579  7237  7720 D bt_userial_mct: userial_init
08-23 18:36:41.580  7237  7720 D bt_hci_bdroid: set_power 1
08-23 18:36:41.580  7237  7720 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 18:36:41.580  7237  7720 I bt_vendor: Starting hciattach daemon
08-23 18:36:41.580  7237  7720 I bt_vendor: try to set true
08-23 18:36:41.581  7213  7787 V FormManager: Network unavailable.
08-23 18:36:41.579  7791  7791 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:41.581  7237  7237 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:41.581  7237  7237 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:41.581  7237  7237 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:41.579  7791  7791 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:41.581  7237  7237 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:41.582  7237  7237 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-23 18:36:41.582  7374  7374 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 18:36:41.582  7374  7374 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 18:36:41.589  7213  7787 V FormManager: Network unavailable.
,08-23 18:36:41.595  7437  7437 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:41
,08-23 18:36:41.596  7437  7437 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 18:36:41.596  7437  7437 D Weather.Utils: 2 : All the weather widget is gone.
08-23 18:36:41.596  7792  7792 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-23 18:36:41.596  7437  7437 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 18:36:41.597  7437  7437 D WeatherAncestor: connectivity changed - connection : true
08-23 18:36:41.597  7437  7437 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a4b3add
08-23 18:36:41.597  7437  7437 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 18:36:41.597  7437  7437 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 18:36:41.597  7437  7437 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 18:36:41.597  7437  7437 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 18:36:41.597  7437  7437 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:41
08-23 18:36:41.635  7798  7798 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-23 18:36:41.643  7799  7799 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-23 18:36:41.671  7801  7801 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 18:36:41.678  7802  7802 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-23 18:36:41.688  7803  7803 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 18:36:41.697  7804  7804 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-23 18:36:41.735  7806  7806 I libmdmdetect: ESOC framework not supported
08-23 18:36:41.735  7806  7806 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-23 18:36:41.746  7806  7806 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-23 18:36:41.746  7806  7806 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-23 18:36:41.746  7806  7806 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-23 18:36:41.746  7806  7806 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-23 18:36:41.746  7806  7806 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-23 18:36:41.746  7806  7806 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-23 18:36:41.746  7806  7806 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-23 18:36:41.786  7806  7807 E QC-QMI  : qmi_client [7806] 14: failed to locate client data
,08-23 18:36:41.786   471   471 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-23 18:36:41.786   471   471 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-23 18:36:41.822  7808  7808 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-23 18:36:41.832  7809  7809 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-23 18:36:41.882  7237  7720 I bt_vendor: bluetooth satus is on
08-23 18:36:41.882  7237  7720 D bt_hci_bdroid: preload
08-23 18:36:41.882  7237  7790 D bt_userial_mct: userial_open(port:0)
08-23 18:36:41.882  7237  7790 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-23 18:36:41.886  7237  7790 I bt_vendor: Done intiailizing UART
08-23 18:36:41.886  7237  7790 I bt_vendor: Done intiailizing UART
08-23 18:36:41.886  7237  7790 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-23 18:36:41.887  7237  7790 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-23 18:36:41.887  7237  7788 I bt-btu  : btu_task received preload complete event
08-23 18:36:41.887  7237  7814 D bt_userial_mct: Entering userial_read_thread()
08-23 18:36:41.888  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-23 18:36:41.888  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-23 18:36:41.893  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 18:36:41.898  7237  7788 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 18:36:41.980  7237  7788 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-23 18:36:41.981  7237  7788 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0202061 
08-23 18:36:41.981  7237  7788 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0202061 
,08-23 18:36:41.998  7237  7724 E bt-btif : Calling BTA_HhEnable
08-23 18:36:41.998  7237  7724 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-23 18:36:41.999  7237  7724 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-23 18:36:42.003  7237  7724 D BluetoothAdapterProperties: Name is: G3
08-23 18:36:42.004  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-23 18:36:42.004  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-23 18:36:42.004  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-23 18:36:42.004  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-23 18:36:42.004  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-23 18:36:42.005  7237  7724 D BluetoothAdapterProperties: Scan Mode:20
08-23 18:36:42.005  7237  7724 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 18:36:42.006  7237  7724 D bt_hci_bdroid: postload
08-23 18:36:42.006  7237  7790 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 18:36:42.006  7237  7788 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-23 18:36:42.006  7237  7724 D bte_conf: Device ID record 1 : primary
08-23 18:36:42.006  7237  7724 D bte_conf:   vendorId            = 00c4
,08-23 18:36:42.006  7237  7724 D bte_conf:   vendorIdSource      = 0001
08-23 18:36:42.006  7237  7724 D bte_conf:   product             = 13a1
08-23 18:36:42.006  7237  7724 D bte_conf:   version             = 1000
08-23 18:36:42.006  7237  7724 D bte_conf:   clientExecutableURL = 
08-23 18:36:42.006  7237  7724 D bte_conf:   serviceDescription  = 
08-23 18:36:42.006  7237  7724 D bte_conf:   documentationURL    = 
08-23 18:36:42.006  7237  7724 D bte_conf: bte_load_did_conf no section named DID2.
08-23 18:36:42.008  7237  7790 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 18:36:42.009  7237  7724 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 18:36:42.009  7237  7720 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-23 18:36:42.010  7237  7720 D BluetoothAdapterProperties: ScanMode =  20
08-23 18:36:42.011  7237  7720 D BluetoothAdapterProperties: State =  11
08-23 18:36:42.011  7237  7720 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-23 18:36:42.011  7237  7720 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-23 18:36:42.011  7237  7720 D BluetoothAdapterProperties: Setting state to 12
08-23 18:36:42.011  7237  7720 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 18:36:42.012  7237  7790 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 18:36:42.012  7237  7790 D bt_hci_bdroid: Used up Tx Cmd credits
,08-23 18:36:42.013  7237  7724 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 18:36:42.009  7819  7819 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:42.009  7819  7819 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:42.019  7237  7814 E bt_mct  : hci lib postload completed
08-23 18:36:42.019  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:42.019  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,08-23 18:36:42.020  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-23 18:36:42.020  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 18:36:42.022  7237  7720 I BluetoothAdapterState: Entering On State
,08-23 18:36:42.028  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7730
08-23 18:36:42.028  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7731
08-23 18:36:42.029  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7734
08-23 18:36:42.030  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7735
08-23 18:36:42.033  7237  7788 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:42.033  7237  7788 W bt-smp  : Plain text(LSB ~ MSB) = a7 9e 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:42.033  7237  7788 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 31 e6 1c b6 d4 b2 99 e3 34 e7 cb 94 cf 3b 7d 
08-23 18:36:42.033  7237  7788 W bt-btm  : Stopping oneshot timer
,08-23 18:36:42.038  7237  7720 D LGBluetoothServiceAdapter: [BTUI] OnState
08-23 18:36:42.038  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7738
08-23 18:36:42.038  7237  7720 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-23 18:36:42.038  7237  7720 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-23 18:36:42.038  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7739
08-23 18:36:42.041  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7743
08-23 18:36:42.042  7237  7724 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 18:36:42.043  7237  7724 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-23 18:36:42.043  7237  7720 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-23 18:36:42.044  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7811
08-23 18:36:42.045  7102  7128 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 18:36:42.048  7102  7138 D BluetoothPan: onBluetoothStateChange on: true
08-23 18:36:42.048  7102  7138 D BluetoothPan: onBluetoothStateChange call bindService
,08-23 18:36:42.052  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7815
08-23 18:36:42.054  7237  7788 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:42.054  7237  7788 W bt-smp  : Plain text(LSB ~ MSB) = 76 f0 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:42.054  7237  7788 W bt-smp  : Encrypted text(LSB ~ MSB) = 00 bf 0b f3 6c 14 d6 b7 eb 2e 0d 35 99 1f 2c 83 
08-23 18:36:42.054  7237  7788 W bt-btm  : Stopping oneshot timer
08-23 18:36:42.060  1033  1033 D BluetoothHeadset: Proxy object connected
,08-23 18:36:42.067  7102  7102 D BluetoothInputDevice: Proxy object connected
08-23 18:36:42.067  7102  7102 D HidProfile: Bluetooth service connected
08-23 18:36:42.071  7237  7788 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:42.071  7237  7788 W bt-smp  : Plain text(LSB ~ MSB) = f9 77 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:42.071  7237  7788 W bt-smp  : Encrypted text(LSB ~ MSB) = 41 c1 74 39 6b a4 9a d0 e7 48 9b df 2f 93 ae 35 
08-23 18:36:42.071  7237  7788 W bt-btm  : Stopping oneshot timer
08-23 18:36:42.071  7237  7720 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-23 18:36:42.076  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 18:36:42.076  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:42.079  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:42.080  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:36:42.082  7237  7788 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:42.083  7237  7788 W bt-smp  : Plain text(LSB ~ MSB) = 7e a6 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:42.083  7237  7788 W bt-smp  : Encrypted text(LSB ~ MSB) = 2e b7 b6 8b f3 9a 76 64 3c 47 3e 2f 29 5c 5e 93 
08-23 18:36:42.083  7237  7788 W bt-btm  : Stopping oneshot timer
08-23 18:36:42.085  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:42.090  1852  1852 D BluetoothHeadset: Proxy object connected
08-23 18:36:42.091  7102  7102 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 18:36:42.091  7102  7102 D PanProfile: Bluetooth service connected
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:42.092  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:36:42.094  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 18:36:42.095  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:42.100  1852  2445 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:36:42.100  7237  7788 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:42.100  7237  7788 W bt-smp  : Plain text(LSB ~ MSB) = 61 f1 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:42.100  7237  7788 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 57 24 92 f0 4d 3c eb d6 50 f3 78 56 64 06 e2 
08-23 18:36:42.100  7237  7788 W bt-btm  : Stopping oneshot timer
08-23 18:36:42.100  1033  1033 D BluetoothA2dp: Proxy object connected
08-23 18:36:42.103  1852  1852 D BluetoothHeadset: Proxy object connected
,08-23 18:36:42.103  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:36:42.106  1852  1852 D BluetoothHeadset: Proxy object connected
08-23 18:36:42.107  7102  7128 D BluetoothMap: onBluetoothStateChange: up=true
08-23 18:36:42.110  7102  7138 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 18:36:42.111  7102  7102 D BluetoothMap: Proxy object connected
08-23 18:36:42.111  7102  7102 D MapProfile: Bluetooth service connected
08-23 18:36:42.111  7102  7102 D BluetoothMap: getConnectedDevices()
08-23 18:36:42.111  7237  7254 V BluetoothMapService: getConnectedDevices()
08-23 18:36:42.114  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-23 18:36:42.114  1033  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-23 18:36:42.114  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-23 18:36:42.116  7835  7835 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-23 18:36:42.117  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 18:36:42.121  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.121  1941  2100 D LGBluetoothAPIService: Message: 1
08-23 18:36:42.121  1941  2100 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-23 18:36:42.126  6980  6980 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 18:36:42.127  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:42.131  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:42.132  1033  1109 D BluetoothManagerService: Message: 40
08-23 18:36:42.132  1941  2100 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-23 18:36:42.132  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-23 18:36:42.135  7237  7237 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.135  7237  7237 D BluetoothMapService: STATE_ON
08-23 18:36:42.136  7102  7102 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 18:36:42.136  7237  7237 D LGBluetoothAPIServer: [BTUI] onCreate()
08-23 18:36:42.137  7237  7237 D LGBluetoothAPIServer: [BTUI] onBind()
08-23 18:36:42.138  1033  1109 D BluetoothManagerService: Message: 30
08-23 18:36:42.139  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-23 18:36:42.139  1941  2100 D LGBluetoothAPIService: Message: 100
08-23 18:36:42.139  1941  2100 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-23 18:36:42.141  7102  7102 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-23 18:36:42.143  1033  1109 D BluetoothManagerService: Message: 30
08-23 18:36:42.155  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:42.155  7237  7237 V BluetoothPbapService: Pbap Service onCreate
,08-23 18:36:42.155  7237  7237 V BluetoothPbapService: Starting PBAP service
08-23 18:36:42.156  7237  7237 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-23 18:36:42.156  7237  7237 V BluetoothPbapService: Pbap Service onBind
08-23 18:36:42.281  1033  2013 I art     : Explicit concurrent mark sweep GC freed 95587(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.609ms total 135.842ms
,08-23 18:36:42.282  7237  7237 V BluetoothMapService: Handler(): got msg=1
08-23 18:36:42.282  7237  7237 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-23 18:36:42.283  7237  7237 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.283  7237  7237 V BluetoothPbapService: state: 12
08-23 18:36:42.283  7237  7237 V BluetoothPbapService: Handler(): got msg=1
08-23 18:36:42.285  7237  7237 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-23 18:36:42.288  7102  7102 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-23 18:36:42.289  7237  7839 D BluetoothMapMasInstance: MAS initSocket()
08-23 18:36:42.290  7237  7839 D BluetoothMapMasInstance:   masId = 00
08-23 18:36:42.290  7237  7839 D BluetoothMapMasInstance:   msgTypes = 0e
08-23 18:36:42.290  7237  7839 D BluetoothMapMasInstance:   masName = SMS/MMS
08-23 18:36:42.290  7237  7839 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-23 18:36:42.290  7102  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 18:36:42.292  7237  7841 V BluetoothPbapService: Pbap Service initSocket
08-23 18:36:42.294  1033  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:42.296  1033  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 18:36:42.298  7237  7237 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 18:36:42.298  7237  7237 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.298  7237  7237 V BluetoothPbapReceiver: ***********state = 12
08-23 18:36:42.302  7102  7102 D BluetoothA2dp: Proxy object connected
08-23 18:36:42.302  7237  7841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:42.303  7102  7102 D A2dpProfile: Bluetooth service connected
08-23 18:36:42.303  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:36:42.304  2164  2164 D c       : Getting all permits...
08-23 18:36:42.304  2164  2164 D a       : Opening database...
08-23 18:36:42.304  7237  7841 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-23 18:36:42.305  7237  7841 V BluetoothPbapService: Succeed to create listening socket 
08-23 18:36:42.305  7237  7841 V BluetoothPbapService: Accepting socket connection...
08-23 18:36:42.305  7237  7724 D BluetoothAdapterProperties: Scan Mode:21
08-23 18:36:42.305  7237  7724 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-23 18:36:42.306  7237  7839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:42.308  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:42.308  7237  7839 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-23 18:36:42.308  7237  7839 V BluetoothMapMasInstance: Succeed to create listening socket 
08-23 18:36:42.308  7237  7839 D BluetoothMapMasInstance: Accepting socket connection...
,08-23 18:36:42.309  7102  7102 D BluetoothHeadset: Proxy object connected
08-23 18:36:42.310  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:42.311  2164  2164 D a       : Opening database auth.proximity.permit_store...
08-23 18:36:42.312  2164  2164 D a       : Closing database...
08-23 18:36:42.312  7102  7102 D HeadsetProfile: Bluetooth service connected
08-23 18:36:42.320  7102  7102 D BluetoothPbap: Proxy object connected
08-23 18:36:42.320  7102  7102 D PbapServerProfile: Bluetooth service connected
,08-23 18:36:42.325  7102  7102 D DockEventReceiver: finishStartingService: stopping service
08-23 18:36:42.330  7102  7102 D BluetoothPermissionRequest: onReceive
08-23 18:36:42.332  7102  7102 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 18:36:42.334  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-23 18:36:42.338  7237  7237 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-23 18:36:42.339  7237  7237 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-23 18:36:42.347  7237  7237 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-23 18:36:42.369  7237  7237 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 18:36:42.369  7237  7237 V BtOppService: onCreate
,08-23 18:36:42.373  7237  7237 V BluetoothOppNotification: send message
08-23 18:36:42.377  7237  7237 V BtOppService: Starting RfcommListener
08-23 18:36:42.387  7237  7237 D BluetoothOppPreference: Dumping Names:  
,08-23 18:36:42.387  7237  7237 D BluetoothOppPreference: {}
,08-23 18:36:42.387  7237  7237 D BluetoothOppPreference: Dumping Channels:  
08-23 18:36:42.387  7237  7237 D BluetoothOppPreference: {}
08-23 18:36:42.387  7237  7237 V BtOppService: onStartCommand
08-23 18:36:42.390  7237  7848 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 18:36:42.391  7237  7848 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 18:36:42.392  7237  7845 V BtOppService: Deleted complete outbound shares, number =  0
08-23 18:36:42.392  7237  7848 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b608fae on behalf of 
08-23 18:36:42.393  7237  7237 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.393  7237  7237 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 18:36:42.394  7237  7848 V BluetoothOppNotification: update too frequent, put in queue
08-23 18:36:42.395  7237  7848 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 18:36:42.395  7237  7848 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 18:36:42.397  7237  7845 V BtOppService: Deleted complete inbound failed shares, number = 0
08-23 18:36:42.397  7237  7237 V BluetoothOppNotification: new notify threadi!
08-23 18:36:42.397  7237  7848 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3278614f on behalf of 
08-23 18:36:42.397  7237  7845 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-23 18:36:42.398  7237  7237 V BluetoothOppNotification: send delay message
08-23 18:36:42.398  7237  7237 V BtOppService: start RfcommListener
08-23 18:36:42.399  7237  7845 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d01b0dc on behalf of 
08-23 18:36:42.400  7237  7848 V BluetoothOppNotification: update too frequent, put in queue
,08-23 18:36:42.403  7237  7237 V BtOppService: RfcommListener started
,08-23 18:36:42.403  7237  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 18:36:42.404  7237  7237 V BtOppService: ContentObserver received notification
08-23 18:36:42.406  7237  7848 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 18:36:42.406  7237  7848 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 18:36:42.408  7237  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23c385e5 on behalf of 
08-23 18:36:42.409  7237  7848 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129f8ba on behalf of 
08-23 18:36:42.411  7237  7850 V BtOppRfcommListener: Starting RFCOMM listener....
08-23 18:36:42.412  1033  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:42.414  7237  7850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:42.412  7237  7849 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-23 18:36:42.417  7237  7850 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-23 18:36:42.418  7237  7850 V BtOppRfcommListener: Started RFCOMM listener....
08-23 18:36:42.418  7237  7848 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 18:36:42.418  7237  7850 I BtOppRfcommListener: Accept thread started.
08-23 18:36:42.418  7237  7850 V BtOppRfcommListener: Accepting connection...
08-23 18:36:42.419  7237  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 18:36:42.420  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:42.421  7237  7237 V BluetoothFtpService: Ftp Service onCreate
08-23 18:36:42.421  7237  7237 I BluetoothFtpService: Ftp Service onCreate
08-23 18:36:42.421  7237  7237 V BluetoothFtpService: Ftp Service onStartCommand
08-23 18:36:42.421  7237  7237 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.421  7237  7237 V BluetoothFtpService: Starting Listening on sockets
08-23 18:36:42.421  7237  7237 V BtOppService: ContentObserver received notification
08-23 18:36:42.422  7237  7237 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:42.422  7237  7237 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:42.422  7237  7237 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:42.422  7237  7237 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.422  7237  7237 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-23 18:36:42.422  7237  7237 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 18:36:42.423  7237  7851 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 18:36:42.423  7237  7851 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 18:36:42.423  7237  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2766fec8 on behalf of 
08-23 18:36:42.425  7237  7237 V BluetoothFtpService: Handler(): got msg=1
08-23 18:36:42.429  7237  7851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f2b9b61 on behalf of 
,08-23 18:36:42.430  7237  7237 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-23 18:36:42.430  7237  7237 V BluetoothFtpService: Ftp Service initSocket
08-23 18:36:42.430  7237  7849 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 18:36:42.432  7237  7851 V BluetoothOppNotification: update too frequent, put in queue
08-23 18:36:42.435  7478  7514 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-23 18:36:42.435  7237  7851 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 18:36:42.437  7237  7849 V BluetoothOppNotification: outbound notification was removed.
08-23 18:36:42.437  7237  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 18:36:42.440  7237  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ceee686 on behalf of 
08-23 18:36:42.441  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:42.441  7237  7237 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:42.442  7237  7849 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-23 18:36:42.443  7237  7237 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-23 18:36:42.443  7237  7237 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-23 18:36:42.445  7237  7849 V BluetoothOppNotification: inbound notification was removed.
08-23 18:36:42.445  7237  7849 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 18:36:42.447  7237  7849 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d992b47 on behalf of 
08-23 18:36:42.449  7237  7854 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-23 18:36:42.458  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
,08-23 18:36:42.459  7237  7237 V BluetoothSapService: Sap Service onCreate
08-23 18:36:42.461  7237  7237 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:42.461  7237  7237 V BluetoothSapService: state: 12
08-23 18:36:42.461  7237  7237 V BluetoothSapService: Starting SAP server process
08-23 18:36:42.463  7237  7237 V BluetoothSapService: SAP Service startRfcommListenerThread
08-23 18:36:42.459  7855  7855 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:42.464  7237  7856 V BluetoothSapService: Sap Service initRfcommSocket
08-23 18:36:42.465  1033  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:42.465  7237  7856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:42.466  7237  7856 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-23 18:36:42.467  7237  7856 V BluetoothSapService: Succeed to create listening socket 
08-23 18:36:42.467  7237  7856 V BluetoothSapService: Accepting socket connection...
08-23 18:36:42.459  7855  7855 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:42.475  7855  7855 V BT_SAP  : Event pipe created
08-23 18:36:42.475  7855  7855 V BT_SAP  : create_server_socket qcom.sap.server
08-23 18:36:42.475  7855  7855 V BT_SAP  : created socket fd 6
,08-23 18:36:43.078  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:36:43.078  1033  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:36:43.127  1033  1536 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-23 18:36:43.128  1033  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-23 18:36:43.274  1033  1048 I ActivityManager: Killing 7638:com.lge.bnr/1000 (adj 15): empty #17
,08-23 18:36:43.305  1033  1920 W libprocessgroup: failed to open /acct/uid_1000/pid_7638/cgroup.procs: No such file or directory
,08-23 18:36:43.399  7237  7237 V BluetoothOppNotification: new notify threadi!
,08-23 18:36:43.407  7237  7237 V BluetoothOppNotification: send delay message
,08-23 18:36:43.413  7237  7866 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 18:36:43.420  7237  7866 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fb334e3 on behalf of 
,08-23 18:36:43.428  7237  7866 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 18:36:43.432  7237  7866 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 18:36:43.434  7237  7866 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fcdee0 on behalf of 
08-23 18:36:43.434  7237  7866 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 18:36:43.436  7237  7866 V BluetoothOppNotification: outbound notification was removed.
08-23 18:36:43.436  7237  7866 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 18:36:43.437  7237  7866 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fd35599 on behalf of 
,08-23 18:36:43.440  7237  7866 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 18:36:43.443  7237  7866 V BluetoothOppNotification: inbound notification was removed.
08-23 18:36:43.443  7237  7866 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 18:36:43.444  7237  7866 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e66405e on behalf of 
08-23 18:36:43.484  1033  1920 I ActivityManager: Killing 7144:com.lge.sync/1000 (adj 15): empty #17
,08-23 18:36:43.511  1033  1542 D WifiService: Client connection lost with reason: 4
,08-23 18:36:43.518  1033  1967 W libprocessgroup: failed to open /acct/uid_1000/pid_7144/cgroup.procs: No such file or directory
,08-23 18:36:44.076  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:44.076  1033  1938 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@10939bc mBinding = false
,08-23 18:36:44.106  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:44.107  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 18:36:44.107  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-23 18:36:44.108  1033  1109 D BluetoothManagerService: Message: 2
08-23 18:36:44.108  1033  1109 D BluetoothManagerService: Sending off request.
08-23 18:36:44.109  7237  7826 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-23 18:36:44.110  7237  7720 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-23 18:36:44.110  7237  7720 D BluetoothAdapterProperties: Setting state to 13
08-23 18:36:44.110  7237  7720 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 18:36:44.111  7237  7720 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 18:36:44.111  7237  7720 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-23 18:36:44.113  7237  7724 D BluetoothAdapterProperties: Scan Mode:20
08-23 18:36:44.117  7237  7720 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-23 18:36:44.122  7237  7841 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-23 18:36:44.123  7237  7839 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-23 18:36:44.124  7237  7850 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:44.124  7237  7854 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 18:36:44.125  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-23 18:36:44.125  7237  7788 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-23 18:36:44.127  7237  7720 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-23 18:36:44.133  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-23 18:36:44.133  7237  7788 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-23 18:36:44.145  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:44.145  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:44.150  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:44.150  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 18:36:44.155  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:44.155  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:44.156  6980  6980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 18:36:44.156  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:44.160  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:44.160  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-23 18:36:44.163  7237  7856 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-23 18:36:44.166  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-23 18:36:44.171  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.173  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 18:36:44.177  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:44.180  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:44.182  7237  7237 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.182  7237  7237 D BluetoothMapService: STATE_TURNING_OFF
08-23 18:36:44.182  7237  7237 V BluetoothMapService: Handler(): got msg=4
08-23 18:36:44.182  7237  7237 D BluetoothMapService: MAP Service closeService in
08-23 18:36:44.182  7237  7237 D BluetoothMapMasInstance: MAP Service shutdown
08-23 18:36:44.182  7237  7237 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 18:36:44.182  7237  7237 V BluetoothMapService: MAP Service closeService out
08-23 18:36:44.191  7237  7237 V BtOppService: Receiver DISABLED_ACTION 
08-23 18:36:44.191  7237  7237 I BtOppRfcommListener: stopping Accept Thread
08-23 18:36:44.191  7237  7237 V BtOppRfcommListener: close mBtServerSocket
,08-23 18:36:44.194  7237  7850 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 18:36:44.195  7237  7237 V BtOppRfcommListener: waiting for thread to terminate
08-23 18:36:44.195  7237  7237 V BtOppRfcommListener: done waiting for thread to terminate
08-23 18:36:44.202  7102  7102 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-23 18:36:44.208  7102  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-23 18:36:44.212  7237  7237 V BtOppService: onDestroy
08-23 18:36:44.213  7237  7237 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-23 18:36:44.218  7237  7237 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 18:36:44.218  7237  7237 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.218  7237  7237 V BluetoothPbapReceiver: ***********state = 13
08-23 18:36:44.220  7237  7237 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-23 18:36:44.225  7237  7237 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.225  7237  7237 V BluetoothPbapService: state: 13
08-23 18:36:44.225  7237  7237 V BluetoothPbapService: Pbap Service closeService in
08-23 18:36:44.229  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:36:44.230  7237  7237 V BluetoothPbapService: successfully stopped pbap service
08-23 18:36:44.230  7237  7237 V BluetoothPbapService: Pbap Service closeService out
08-23 18:36:44.238  7237  7237 V BluetoothPbapService: Pbap Service onDestroy
08-23 18:36:44.238  7237  7237 V BluetoothPbapService: Pbap Service closeService in
,08-23 18:36:44.238  7237  7237 V BluetoothPbapService: Pbap Service closeService out
08-23 18:36:44.238  7237  7237 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-23 18:36:44.246  7102  7102 D DockEventReceiver: finishStartingService: stopping service
08-23 18:36:44.247  7102  7102 D BluetoothPbap: Proxy object disconnected
08-23 18:36:44.247  7102  7102 D PbapServerProfile: Bluetooth service disconnected
08-23 18:36:44.258  7102  7102 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-23 18:36:44.263  7102  7102 D BluetoothPermissionRequest: onReceive
08-23 18:36:44.263  7102  7102 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 18:36:44.269  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 18:36:44.273  7237  7237 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-23 18:36:44.273  7237  7237 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-23 18:36:44.274  7237  7237 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-23 18:36:44.278  7237  7237 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.278  7237  7237 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 18:36:44.279  7237  7237 V BluetoothFtpService: Ftp Service onStartCommand
,08-23 18:36:44.279  7237  7237 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.279  7237  7237 V BluetoothFtpService: Ftp Service closeService
08-23 18:36:44.279  7237  7237 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-23 18:36:44.281  7237  7237 V BluetoothFtpService: successfully stopped ftp service
08-23 18:36:44.281  7237  7237 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:44.282  7237  7237 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:44.282  7237  7237 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:44.282  7237  7237 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.282  7237  7237 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-23 18:36:44.282  7237  7237 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 18:36:44.283  7237  7237 V BluetoothFtpService: Ftp Service onDestroy
08-23 18:36:44.283  7237  7237 V BluetoothFtpService: Ftp Service closeService
08-23 18:36:44.287  7237  7237 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:44.287  7237  7237 V BluetoothSapService: state: 13
08-23 18:36:44.287  7237  7237 V BluetoothSapService: Stopping SAP server process
08-23 18:36:44.288  7237  7237 V BluetoothSapService: Sap Service closeSapService in
08-23 18:36:44.288  7237  7237 V BluetoothSapService: Close listen Socket : 
08-23 18:36:44.288  7237  7237 V BluetoothSapService: Close rfcomm Socket : 
08-23 18:36:44.288  7237  7237 V BluetoothSapService: Close sapd  Socket : 
,08-23 18:36:44.293  7237  7237 V BluetoothSapService: Sap Service closeSapService out
08-23 18:36:44.294  7237  7237 V BluetoothSapService: Sap Service onDestroy
08-23 18:36:44.294  7237  7237 V BluetoothSapService: Sap Service closeSapService in
08-23 18:36:44.294  7237  7237 V BluetoothSapService: Close listen Socket : 
08-23 18:36:44.294  7237  7237 V BluetoothSapService: Close rfcomm Socket : 
08-23 18:36:44.294  7237  7237 V BluetoothSapService: Close sapd  Socket : 
08-23 18:36:44.294  7237  7237 V BluetoothSapService: Sap Service closeSapService out
08-23 18:36:44.324  1033  1390 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e57dc9a type 2 when 209689 com.google.android.gms} when 209689
,08-23 18:36:44.338   311  7887 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-23 18:36:44.340  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-23 18:36:45.032  7237  7724 D bt_hci_bdroid: cleanup
,08-23 18:36:45.038  7237  7790 I bt_lpm  : LPM is already off!!!
08-23 18:36:45.040  7237  7814 I bt_userial_mct: exiting userial_read_thread
08-23 18:36:45.040  7237  7814 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 18:36:45.042  7237  7788 W bt-btif : ag scb idx 1 not allocated
08-23 18:36:45.042  7237  7788 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 18:36:45.042  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 18:36:45.043  7237  7788 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 18:36:45.043  7237  7788 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 18:36:45.044  7237  7724 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 18:36:45.044  7237  7790 I bt_vendor: hw_epilog_process
08-23 18:36:45.044  7237  7724 D bt_hci_bdroid: cleanup Finalizing cleanup
08-23 18:36:45.044  7237  7724 D bt_userial_mct: userial_close
08-23 18:36:45.044  7237  7724 E bt_userial_mct: pthread_join() FAILED result:3
08-23 18:36:45.044  7237  7724 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-23 18:36:45.050  7237  7724 D bt_hci_bdroid: set_power 0
08-23 18:36:45.050  7237  7724 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 18:36:45.050  7237  7724 I bt_vendor: bluetooth satus is on
08-23 18:36:45.050  7237  7724 I bt_vendor: bt-vendor : resetting BT status
08-23 18:36:45.050  7237  7724 I bt_vendor: Starting hciattach daemon
08-23 18:36:45.050  7237  7724 I bt_vendor: try to set false
,08-23 18:36:45.056  7237  7724 I bt_vendor: Starting hciattach daemon
08-23 18:36:45.057  7237  7724 I bt_vendor: try to set false
08-23 18:36:45.057  7237  7724 I bt_vendor: cleanup
08-23 18:36:45.058  7237  7788 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 18:36:45.058  7237  7724 I GKI_LINUX: GKI_exit_task 0 done
08-23 18:36:45.058  7237  7724 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 18:36:45.060  7237  7720 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 18:36:45.064  7237  7237 D HeadsetService: Received stop request...Stopping profile...
,08-23 18:36:45.069  7237  7237 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 18:36:45.069  7237  7237 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:36:45.069  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:45.069  7237  7742 D HeadsetStateMachine: Exit Disconnected: -1
08-23 18:36:45.074  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-23 18:36:45.074  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-23 18:36:45.074  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-23 18:36:45.074  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-23 18:36:45.074  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-23 18:36:45.077  7237  7237 D A2dpService: Received stop request...Stopping profile...
,08-23 18:36:45.081  7237  7773 D A2dpStateMachine: Exit Disconnected: -1
08-23 18:36:45.083  7237  7720 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 18:36:45.083  7237  7237 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-23 18:36:45.085  7237  7237 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-23 18:36:45.085  7237  7237 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:36:45.085  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:45.087  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-23 18:36:45.087  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 18:36:45.088  7237  7237 D HidService: Received stop request...Stopping profile...
08-23 18:36:45.088  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:45.090  7237  7237 D HealthService: Received stop request...Stopping profile...
,08-23 18:36:45.094  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:45.096  7237  7237 D HeadsetStateMachine: Unbinding service...
08-23 18:36:45.097  7237  7237 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 18:36:45.097  7237  7237 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 18:36:45.097  7237  7237 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 18:36:45.097  7237  7237 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 18:36:45.098  7237  7237 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 18:36:45.098  7237  7237 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 18:36:45.098  7237  7237 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 18:36:45.099  7237  7237 D PanService: Received stop request...Stopping profile...
08-23 18:36:45.099  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:45.100  7237  7237 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 18:36:45.101  7237  7237 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 18:36:45.102  7237  7237 D BtGatt.GattService: stop()
08-23 18:36:45.102  7237  7237 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 18:36:45.103  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
,08-23 18:36:45.108  7237  7237 D BluetoothMapService: Received stop request...Stopping profile...
08-23 18:36:45.108  7237  7237 D BluetoothMapService: stop()
08-23 18:36:45.108  7237  7237 D BluetoothMapEmailAppObserver: deinitObservers()
08-23 18:36:45.108  7237  7237 D BluetoothMapEmailAppObserver: removeReceiver()
08-23 18:36:45.109  7237  7237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:45.110  7237  7237 I BluetoothA2dpServiceJni: cleanupNative
08-23 18:36:45.111  7237  7774 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 18:36:45.111  7237  7237 I GKI_LINUX: GKI_exit_task 2 done
08-23 18:36:45.111  7237  7237 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 18:36:45.112  7237  7237 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 18:36:45.112  7237  7237 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 18:36:45.112  7237  7237 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 18:36:45.112  7237  7237 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 18:36:45.112  7237  7237 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 18:36:45.113  7237  7237 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 18:36:45.113  7237  7237 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 18:36:45.114  7237  7237 V BluetoothMapService: Handler(): got msg=4
08-23 18:36:45.114  7237  7237 D BluetoothMapService: MAP Service closeService in
08-23 18:36:45.114  7237  7237 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 18:36:45.114  7237  7237 V BluetoothMapService: MAP Service closeService out
08-23 18:36:45.115  7237  7720 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-23 18:36:45.115  7237  7720 D BluetoothAdapterProperties: Setting state to 10
08-23 18:36:45.115  7237  7720 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 18:36:45.117  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:45.117  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-23 18:36:45.117  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-23 18:36:45.117  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 18:36:45.121  7237  7720 I BluetoothAdapterState: Entering OffState
08-23 18:36:45.122  7102  7128 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 18:36:45.123  7237  7237 D BluetoothMapService: cleanup()
08-23 18:36:45.123  7237  7237 D BluetoothMapService: MAP Service closeService in
08-23 18:36:45.123  7237  7237 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 18:36:45.123  7237  7237 V BluetoothMapService: MAP Service closeService out
08-23 18:36:45.125  7102  7128 D BluetoothPan: onBluetoothStateChange on: false
08-23 18:36:45.126  1852  2452 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:36:45.126  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:36:45.127  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:36:45.131  1852  2445 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 18:36:45.134  7102  7128 D BluetoothMap: onBluetoothStateChange: up=false
08-23 18:36:45.135  7102  7128 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 18:36:45.137  7102  7824 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 18:36:45.138  7102  7138 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 18:36:45.139  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-23 18:36:45.139  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-23 18:36:45.142  1033  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-23 18:36:45.142  1033  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-23 18:36:45.142  1033  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@10939bc mBinding = false
08-23 18:36:45.143  1033  1109 D BluetoothManagerService: Sending unbind request.
,08-23 18:36:45.149  7237  7724 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-23 18:36:45.149  7237  7237 I GKI_LINUX: GKI_exit_task 1 done
08-23 18:36:45.149  7237  7237 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-23 18:36:45.150  7237  7237 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 18:36:45.150  7237  7237 I art     : --- WEIRD: removing null entry 248
08-23 18:36:45.150  7237  7237 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-23 18:36:45.150  7237  7237 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-23 18:36:45.151  7237  7237 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-23 18:36:45.154  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-23 18:36:45.158  7237  7237 I art     : System.exit called, status: 0
08-23 18:36:45.158  7237  7237 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 18:36:45.173  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:36:45.176  1941  2100 D LGBluetoothAPIService: Message: 2
,08-23 18:36:45.176  1941  2100 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2c688e04 mBinding = false
08-23 18:36:45.176  1941  2100 D LGBluetoothAPIService: Sending unbind request.
08-23 18:36:45.178  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:45.179  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:45.179  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 18:36:45.186  7102  7102 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-23 18:36:45.186  7102  7102 D LGBluetoothEventManager: [BTUI] clear device connection state
08-23 18:36:45.199  1601  1601 D BluetoothAdapter: 894783231: getState() :  mService = null. Returning STATE_OFF
,08-23 18:36:45.199  1601  1601 D BluetoothAdapter: 894783231: getState() :  mService = null. Returning STATE_OFF
08-23 18:36:45.202  7102  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 18:36:45.208   318  4487 V AudioFlinger: 7237 died, releasing its sessions
08-23 18:36:45.208   318  4487 V AudioFlinger:  pid 1852 @ 0
08-23 18:36:45.208   318  4487 V AudioFlinger:  pid 3201 @ 1
08-23 18:36:45.208   318  4487 V AudioFlinger:  pid 3201 @ 2
08-23 18:36:45.208  7102  7102 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-23 18:36:45.300  1033  1920 I ActivityManager: Process com.android.bluetooth (pid 7237) has died
08-23 18:36:45.301  1033  1920 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-23 18:36:45.387  1033  1938 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7917 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-23 18:36:45.391  7102  7102 D DockEventReceiver: finishStartingService: stopping service
,08-23 18:36:45.492  7917  7917 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-23 18:36:45.492  7917  7917 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 18:36:45.493  7917  7917 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-23 18:36:45.494  7917  7917 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 18:36:45.514  7917  7917 D BluetoothAdapterApp: Loading JNI Library
,08-23 18:36:45.554  7917  7917 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@33f2ac25 Instance Count = 1
,08-23 18:36:45.560  7917  7917 D BluetoothAdapterApp: onCreate
08-23 18:36:45.585  7917  7917 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-23 18:36:45.585  7917  7917 D ProfileConfigQcom: Adding HeadsetService
08-23 18:36:45.586  7917  7917 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-23 18:36:45.586  7917  7917 D ProfileConfigQcom: Adding A2dpService
08-23 18:36:45.586  7917  7917 D ProfileConfigQcom: [BTUI] HidService is supported
08-23 18:36:45.586  7917  7917 D ProfileConfigQcom: Adding HidService
08-23 18:36:45.587  7917  7917 D ProfileConfigQcom: [BTUI] HealthService is supported
08-23 18:36:45.587  7917  7917 D ProfileConfigQcom: Adding HealthService
08-23 18:36:45.587  7917  7917 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-23 18:36:45.589  7917  7917 D ProfileConfigQcom: [BTUI] PanService is supported
08-23 18:36:45.589  7917  7917 D ProfileConfigQcom: Adding PanService
08-23 18:36:45.590  7917  7917 D ProfileConfigQcom: [BTUI] GattService is supported
08-23 18:36:45.590  7917  7917 D ProfileConfigQcom: Adding GattService
08-23 18:36:45.591  7917  7917 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-23 18:36:45.592  7917  7917 D ProfileConfigQcom: Adding BluetoothMapService
08-23 18:36:45.593  7917  7917 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-23 18:36:45.594  7917  7917 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 18:36:45.598  7917  7917 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:45.598  7917  7917 V BluetoothPbapReceiver: ***********state = 10
,08-23 18:36:45.603  7917  7917 V LGMDMManagerInternal: Create singleton instance
08-23 18:36:45.714  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 18:36:45.717  7102  7102 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-23 18:36:45.719  1033  1967 I ActivityManager: Killing 6878:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-23 18:36:45.740  7172  7172 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-23 18:36:45.741  7172  7172 W System.err: android.os.DeadObjectException
08-23 18:36:45.741  7172  7172 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 18:36:45.741  7172  7172 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 18:36:45.741  7172  7172 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-23 18:36:45.741  7172  7172 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-23 18:36:45.741  7172  7172 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-23 18:36:45.741  7172  7172 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-23 18:36:45.741  7172  7172 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 18:36:45.741  7172  7172 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 18:36:45.741  7172  7172 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:45.741  7172  7172 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:45.741  7172  7172 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:45.741  7172  7172 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:45.741  7172  7172 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:45.741  7172  7172 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:45.742  7172  7172 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-23 18:36:45.742  7172  7172 W System.err: android.os.DeadObjectException
08-23 18:36:45.743  7172  7172 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 18:36:45.743  7172  7172 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 18:36:45.743  7172  7172 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-23 18:36:45.743  7172  7172 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-23 18:36:45.743  7172  7172 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-23 18:36:45.743  7172  7172 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-23 18:36:45.745  7172  7172 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 18:36:45.745  7172  7172 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 18:36:45.745  7172  7172 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:45.745  7172  7172 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:45.745  7172  7172 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:45.745  7172  7172 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:45.745  7172  7172 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:45.745  7172  7172 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:45.745  7172  7172 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-23 18:36:45.746  7172  7172 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-23 18:36:45.775  1033  1977 W libprocessgroup: failed to open /acct/uid_1000/pid_6878/cgroup.procs: No such file or directory
08-23 18:36:45.775  1033  1977 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-23 18:36:45.782  7172  7172 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-23 18:36:45.782  7172  7172 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 18:36:45.835  1033  1049 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 18:36:45.836  7172  7172 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-23 18:36:45.853  7102  7102 D BluetoothPermissionRequest: onReceive
,08-23 18:36:45.855  7102  7102 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 18:36:45.856  7102  7102 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-23 18:36:45.859  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 18:36:45.863  7917  7917 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-23 18:36:45.869  7917  7917 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:45.872  7917  7917 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:45.873  7917  7917 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:45.873  7917  7917 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:45.874  7917  7917 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:36:45.874  7917  7917 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-23 18:36:45.881  7192  7192 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-23 18:36:45.948  7942  7942 D UEI.SmartControl: Quickset Services start...
,08-23 18:36:45.951  7942  7942 I UEI.SmartControl: Manufacture = LGE
,08-23 18:36:45.951  7942  7942 D UEI.SmartControl: Id = LGNevo
08-23 18:36:45.953  7942  7942 D UEI.SmartControl: File observer start...
08-23 18:36:45.954  7942  7942 E UEI.SmartControl: IR Port is disabled: false
,08-23 18:36:45.954  7942  7942 D UEI.SmartControl: Starting file observer...
08-23 18:36:45.954  7942  7942 D UEI.SmartControl: Extracting JNI libs...
08-23 18:36:45.954  7942  7942 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-23 18:36:46.048  7942  7942 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-23 18:36:46.048  7942  7942 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-23 18:36:46.048  7942  7942 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-23 18:36:46.090  7942  7942 I UEI.SmartControl: --- Selecting new region: 6
,08-23 18:36:46.092  7942  7942 I UEI.SmartControl: Model = LG-D855
,08-23 18:36:46.095  7942  7942 D UEI.SmartControl: QS Service created
,08-23 18:36:46.117  7942  7942 I UEI.SmartControl: Service initServices...
,08-23 18:36:46.123  7942  7942 D UEI.SmartControl: QS start get config
08-23 18:36:46.194  7942  7942 D UEI.SmartControl: Loading JNI Libs...
,08-23 18:36:46.535  7942  7942 I UEI.SmartControl: Supports setup maps: true
,08-23 18:36:46.538  7942  7942 D UEI.SmartControl: QS start statue = true Error code = 0
,08-23 18:36:46.538  7942  7942 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-23 18:36:46.538  7942  7942 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-23 18:36:46.538  7942  7942 I UEI.SmartControl: ### init IR Blaster...
08-23 18:36:46.543  7942  7942 D serial_port: Configuring serial port
08-23 18:36:46.546  7942  7942 E UEI.SmartControl: UEIBLaster setting for 616
08-23 18:36:46.546  7942  7942 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 18:36:46.547  7942  7942 I UEI.SmartControl: configuring settings for MAXQ616
08-23 18:36:46.547  7942  7942 I UEI.SmartControl: Get version...
08-23 18:36:46.563  7942  7969 D UEI.SmartControl: serial port data available: 21
,08-23 18:36:46.591  7942  7942 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-23 18:36:46.591  7942  7942 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-23 18:36:46.592  7942  7942 I UEI.SmartControl: QS saving settings...
,08-23 18:36:46.594  7942  7942 D UEI.SmartControl: IR Blaster version: 25672567
08-23 18:36:46.612  7942  7969 D UEI.SmartControl: serial port data available: 4
,08-23 18:36:46.655  7942  7972 I UEI.SmartControl: Device manager: loading config....
,08-23 18:36:46.657  7942  7972 D UEI.SmartControl: ----------- loading internal config...
08-23 18:36:46.661  7942  7942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-23 18:36:46.667  7942  7942 E UEI.SmartControl: Services init done
08-23 18:36:46.667  7942  7942 D UEI.SmartControl: QS Service init finished
08-23 18:36:46.673  7942  7942 D UEI.SmartControl: QS Service version name: 2.1.91
08-23 18:36:46.673  7942  7942 D UEI.SmartControl: QS Service version code: 201091
08-23 18:36:46.674  7942  7942 D UEI.SmartControl: Service requested: Control
,08-23 18:36:46.676  7942  7972 E UEI.SmartControl: Loading SETTINGS...
,08-23 18:36:46.679  7942  7942 D UEI.SmartControl: Request IControl service: devices are loaded...
08-23 18:36:46.683  7172  7172 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-23 18:36:46.683  7942  7958 I UEI.SmartControl: ------ IControl API: 11
08-23 18:36:46.684  7942  7958 I UEI.SmartControl: Registering callback...
08-23 18:36:46.685  7942  7957 I UEI.SmartControl: ------ IControl API: 19
08-23 18:36:46.686  7942  7957 I UEI.SmartControl: Registering Services Ready callback...
08-23 18:36:46.687  1033  1970 I ActivityManager: Killing 7172:com.lge.qremote/u0a112 (adj 15): empty #17
08-23 18:36:46.690  7942  7972 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-23 18:36:46.709  7942  7971 I UEI.SmartControl: Notify AllClients services are ready: 0
08-23 18:36:46.710  7942  7971 D UEI.SmartControl: -----service ready thread exits
,08-23 18:36:46.732  1033  1653 W libprocessgroup: failed to open /acct/uid_10112/pid_7172/cgroup.procs: No such file or directory
08-23 18:36:46.732  7942  7942 D UEI.SmartControl: Internal service binding...
,08-23 18:36:47.205  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 18:36:47.205  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 18:36:47.238  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-23 18:36:47.273  1033  1453 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 18:36:47.349  1033  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7977 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-23 18:36:47.356  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-23 18:36:47.357  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-23 18:36:47.381  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-23 18:36:47.417  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:47.419  1033  1033 D administrator: Handling package changes for user 0
,08-23 18:36:47.451  7977  7977 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 18:36:47.526  7977  7977 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:47.526  7977  7977 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 18:36:47.527  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-23 18:36:47.527  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-23 18:36:47.569  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:36:47.576  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-23 18:36:47.582  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-23 18:36:47.584  2504  2504 V GmsNetworkLocationProvi: DISABLE
,08-23 18:36:47.621  1033  1089 D LocationProviderProxy: applying state to connected service
08-23 18:36:47.623  2504  2504 E GCoreFlp: Bound FusedProviderService with LocationManager
08-23 18:36:47.625  7977  8020 I Babel   : MmsConfig: mnc/mcc: 0/0
08-23 18:36:47.627  7977  8020 I Babel   : MmsConfig.loadMmsSettings
08-23 18:36:47.634  7977  8020 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-23 18:36:47.634  7977  8020 I Babel   : MmsConfig.loadFromDatabase
,08-23 18:36:47.644  7977  8020 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-23 18:36:47.644  7977  8020 I Babel   : MmsConfig.loadFromResources
08-23 18:36:47.647  7977  8020 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-23 18:36:47.647  7977  8020 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-23 18:36:47.653  7977  8019 W AudioCapabilities: Unsupported mime audio/evrc
08-23 18:36:47.654  7977  8019 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 18:36:47.657  7977  8019 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 18:36:47.658  7977  7977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:36:47.668  7977  8019 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-23 18:36:47.669  7977  8019 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 18:36:47.670  7977  8019 W AudioCapabilities: Unsupported mime audio/evrc
08-23 18:36:47.675  1817  8024 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-23 18:36:47.675  1817  8024 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-23 18:36:47.680  7307  7307 I AppUp4:CustModeStarterReceiver: onReceive
,08-23 18:36:47.689  7307  7307 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@30751f87
08-23 18:36:47.689  7307  7307 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 18:36:47.689  7307  7307 D AppUp4:CustFacade: isPhone : true
08-23 18:36:47.689  7307  7307 D AppUp4:CustModeStarterReceiver: begin check event
08-23 18:36:47.689  7307  7307 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-23 18:36:47.691  7977  8019 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-23 18:36:47.695  7977  8019 W VideoCapabilities: Unsupported mime video/divx
08-23 18:36:47.698  1817  5322 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-23 18:36:47.701  7977  8019 W VideoCapabilities: Unsupported mime video/divx311
08-23 18:36:47.703  7977  8019 W VideoCapabilities: Unsupported mime video/divx4
,08-23 18:36:47.712  7977  8019 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-23 18:36:47.714  1033  1781 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8027 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-23 18:36:47.719  1033  1967 I ActivityManager: Killing 7330:com.lge.email/u0a23 (adj 15): empty #17
,08-23 18:36:47.747  7977  8019 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-23 18:36:47.750  7977  8019 W AudioCapabilities: Unsupported mime audio/eac3
08-23 18:36:47.751  7977  8019 W AudioCapabilities: Unsupported mime audio/ac3
08-23 18:36:47.752  7977  8019 W AudioCapabilities: Unsupported mime audio/g726
08-23 18:36:47.753  7977  8019 W AudioCapabilities: Unsupported mime audio/wma-voice
08-23 18:36:47.753  7977  8019 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-23 18:36:47.754  7977  8019 W AudioCapabilities: Unsupported mime audio/adpcm
08-23 18:36:47.756  7977  8019 W VideoCapabilities: Unsupported mime video/theora
08-23 18:36:47.761  7977  8019 W VideoCapabilities: Unsupported mime video/mjpg
,08-23 18:36:47.794  1033  1653 W libprocessgroup: failed to open /acct/uid_10023/pid_7330/cgroup.procs: No such file or directory
,08-23 18:36:47.822  8027  8027 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 18:36:47.823  8027  8027 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 18:36:47.823  8027  8027 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 18:36:47.825  8027  8027 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-23 18:36:47.825  8027  8027 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 18:36:47.897  8027  8027 I SystemConfig: BUILD Country: EU
08-23 18:36:47.897  8027  8027 I SystemConfig: BUILD Operator: OPEN
,08-23 18:36:47.942  1033  1049 I ActivityManager: Killing 7213:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-23 18:36:48.054  1033  1977 W libprocessgroup: failed to open /acct/uid_10026/pid_7213/cgroup.procs: No such file or directory
,08-23 18:36:48.066  8027  8046 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-23 18:36:48.066  8027  8046 I SystemConfig: existFile = false
08-23 18:36:48.067  8027  8046 I SystemConfig: canReadFile = false
08-23 18:36:48.067  8027  8046 I SystemConfig: systemFeature RCS result false
08-23 18:36:48.067  8027  8046 D SystemConfig: refreshRcsSupport() :false
08-23 18:36:48.105  1033  1049 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8051 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-23 18:36:48.140  1033  1543 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-23 18:36:48.164  8051  8051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:36:48.164  8051  8051 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 18:36:48.164  8051  8051 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 18:36:48.165  8051  8051 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-23 18:36:48.294  8051  8051 I AppConfig: Total System Memory = 2995761152
,08-23 18:36:48.305  8051  8051 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-23 18:36:48.395  1033  1781 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8070 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 18:36:48.397  1033  1781 I ActivityManager: Killing 6554:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-23 18:36:48.582  1033  1782 W libprocessgroup: failed to open /acct/uid_1000/pid_6554/cgroup.procs: No such file or directory
08-23 18:36:48.762  8070  8070 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-23 18:36:48.874  8070  8070 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:48.874  8070  8070 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:48.949  8070  8070 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-23 18:36:48.972  8070  8070 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 18:36:48.973  8070  8070 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 18:36:49.007  8070  8070 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 18:36:49.008  8070  8070 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-23 18:36:49.028  1033  1967 I ActivityManager: Killing 7374:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-23 18:36:49.068  1033  1977 W libprocessgroup: failed to open /acct/uid_10046/pid_7374/cgroup.procs: No such file or directory
,08-23 18:36:49.087  5146  8110 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-23 18:36:49.145  1033  2013 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8111 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-23 18:36:49.172  3424  4248 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-23 18:36:49.176  3424  4248 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16887f98 on behalf of 8070
08-23 18:36:49.200  8070  8070 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-23 18:36:49.242  8070  8070 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-23 18:36:49.248  8111  8111 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-23 18:36:49.269  8111  8111 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-23 18:36:49.270  8111  8111 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-23 18:36:49.270  8111  8111 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-23 18:36:49.270  8111  8111 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-23 18:36:49.270  8111  8111 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-23 18:36:49.270  8111  8111 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-23 18:36:49.286  1033  1574 I ActivityManager: Killing 7396:com.android.chrome/u0a57 (adj 15): empty #17
,08-23 18:36:49.363  1033  1977 W libprocessgroup: failed to open /acct/uid_10057/pid_7396/cgroup.procs: No such file or directory
,08-23 18:36:49.656  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-23 18:36:49.698  5146  8110 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 611 ms] updated apps [took 611 ms] 
,08-23 18:36:49.934  1033  1390 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23aac0c5 type 2 when 215285 com.google.android.gms} when 215285
,08-23 18:36:49.948   311  8153 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-23 18:36:49.957  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-23 18:36:50.220  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:36:50.229  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b34c81 added. We now have 6 listener(s)
08-23 18:36:50.229  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:50.235  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:50.235  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f6d1126 added. We now have 7 listener(s)
08-23 18:36:50.235  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:50.237  6980  7040 I System.out: IsBluetoothEnabled
08-23 18:36:50.238  1033  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:50.238  1033  1782 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-23 18:36:50.240  1033  1109 D BluetoothManagerService: Message: 2
08-23 18:36:50.244  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:50.244  1033  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:50.244  1033  2012 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-23 18:36:50.262  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:50.263  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 18:36:50.263  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-23 18:36:50.266  1033  1109 D BluetoothManagerService: Message: 1
08-23 18:36:50.266  1033  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-23 18:36:50.295  1033  1109 D BluetoothManagerService: Message: 20
08-23 18:36:50.296  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2676ede6:true
,08-23 18:36:50.299  7917  7917 D BluetoothAdapterState: make
08-23 18:36:50.303  7917  7917 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-23 18:36:50.304  7917  7917 I bluedroid-qcom: init
08-23 18:36:50.305  7917  8157 I BluetoothAdapterState: Entering OffState
08-23 18:36:50.305  7917  7917 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 18:36:50.305  7917  7917 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 18:36:50.305  7917  7917 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 18:36:50.306  7917  7917 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 18:36:50.306  7917  7917 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-23 18:36:50.307  7917  7917 I bluedroid-qcom: get_profile_interface socket
08-23 18:36:50.307  7917  7917 I bluedroid-qcom: get_profile_interface map_client
,08-23 18:36:50.312  7917  8161 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-23 18:36:50.314  7917  8161 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-23 18:36:50.309  8160  8160 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:50.309  8160  8160 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:50.323  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 18:36:50.323  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-23 18:36:50.331  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-23 18:36:50.331  1033  1109 D BluetoothManagerService: Message: 40
08-23 18:36:50.332  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-23 18:36:50.332  7917  7933 I bluedroid-qcom: config_hci_snoop_log
08-23 18:36:50.334  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-23 18:36:50.334  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-23 18:36:50.334  8160  8160 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-23 18:36:50.334  8160  8160 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-23 18:36:50.335  8160  8160 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-23 18:36:50.336  7917  8161 D BluetoothAdapterProperties: Name is: G3
,08-23 18:36:50.339  8160  8160 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-23 18:36:50.344  8160  8160 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-23 18:36:50.344  8160  8160 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-23 18:36:50.348  7917  8157 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-23 18:36:50.351  7917  8157 D BluetoothAdapterProperties: Setting state to 11
08-23 18:36:50.351  7917  8157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 18:36:50.352  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:50.352  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-23 18:36:50.352  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-23 18:36:50.354  7917  8157 I LGBluetoothServiceJni: classInitNative: succeeds
08-23 18:36:50.360  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 18:36:50.363  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 18:36:50.366  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:50.370  7102  7102 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-23 18:36:50.387  7917  8157 D BluetoothBondStateMachine: make
,08-23 18:36:50.394  7917  7917 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 18:36:50.394  7917  7917 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:50.394  7917  7917 V BluetoothPbapReceiver: ***********state = 11
08-23 18:36:50.395  7917  8175 I BluetoothBondStateMachine: StableState(): Entering Off State
08-23 18:36:50.396  7917  8157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.396  7917  8157 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-23 18:36:50.397  7917  8157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.397  7917  8157 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-23 18:36:50.398  7917  8157 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-23 18:36:50.401  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 18:36:50.405  7917  8157 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:50.415  7917  8157 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 18:36:50.417  7917  7917 D HeadsetService: Received start request. Starting profile...
,08-23 18:36:50.417  7917  7917 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 18:36:50.417  7102  7102 D BluetoothPermissionRequest: onReceive
08-23 18:36:50.418  7917  7917 D LGBluetoothHfpAdapter: Version 1.6
08-23 18:36:50.421  7917  7917 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 18:36:50.422  7917  7917 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 18:36:50.423  7917  7917 D HeadsetStateMachine: make
08-23 18:36:50.424  7917  8157 E BluetoothAdapterService: File transfer profiles supported!!
08-23 18:36:50.426  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 18:36:50.441  7917  8157 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 18:36:50.448  7917  8157 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 18:36:50.452  7917  8157 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 18:36:50.459  7917  8157 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 18:36:50.463  7917  7917 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:50.463  7917  7917 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 18:36:50.468  7917  7917 D HeadsetStateMachine: max_hf_connections = 1
08-23 18:36:50.468  7917  7917 I bluedroid-qcom: get_profile_interface handsfree
08-23 18:36:50.470  7917  7917 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-23 18:36:50.471   318  1384 V AudioPolicyService: registerClient() client 0xb558a280, uid 1002
08-23 18:36:50.471   318  4487 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-23 18:36:50.471   318  4487 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 18:36:50.471   318  4487 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 18:36:50.472  7917  7917 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-23 18:36:50.472   318   318 V AudioFlinger: registerClient() client 0xb55818c8, pid 7917
,08-23 18:36:50.473   318  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:50.473   318  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:50.473  1601  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:50.473  1601  1618 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:50.473  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-23 18:36:50.473   318  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:50.473  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:50.473   318  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:50.473  1601  3200 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:50.473  1601  3200 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:50.474  7917  7933 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:50.474  7917  7933 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-23 18:36:50.474  7917  7933 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:50.474  7917  7933 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-23 18:36:50.474  7917  7917 V ToneGenerator: Create Track: 0xb4928a80
08-23 18:36:50.474  1033  1920 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:50.474  1033  1920 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:50.474  7917  7917 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-23 18:36:50.474  7917  7917 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-23 18:36:50.474  1033  1920 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:50.474  1033  1920 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:50.474  3201  3222 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 18:36:50.474  3201  3222 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 18:36:50.474   318  4487 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 18:36:50.474   318  4487 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-23 18:36:50.474  1852  2445 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:50.474  1852  2445 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-23 18:36:50.474   318  4487 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 18:36:50.474  3201  3222 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 18:36:50.474  3201  3222 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 18:36:50.474   318  4487 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 18:36:50.475   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 18:36:50.475   318  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 18:36:50.475   318  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-23 18:36:50.475   318  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 18:36:50.475   318  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 18:36:50.476  7917  7917 V AudioSystem: getLatency() output 2, latency 50
08-23 18:36:50.476  7917  7917 V AudioSystem: getFrameCount() output 2, frameCount 960
08-23 18:36:50.476  7917  7917 V AudioTrack: createTrack_l() output 2 afLatency 50
08-23 18:36:50.476   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 18:36:50.476   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 18:36:50.476   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 18:36:50.476   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 18:36:50.476   318  1383 V AudioFlinger: createTrack() lSessionId: 23
08-23 18:36:50.477  7917  8157 V LGMDMManager: Create singleton instance
08-23 18:36:50.477  7917  7917 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-23 18:36:50.478   318  1383 V AudioFlinger: acquiring 23 from 7917, for 7917
08-23 18:36:50.478   318  1383 V AudioFlinger:  added new entry for 23
,08-23 18:36:50.478  7917  7917 V ToneGenerator: ToneGenerator INIT OK, time: 215858
08-23 18:36:50.478  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.479  7917  8181 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-23 18:36:50.479  7917  8157 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 18:36:50.479  7917  8181 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 18:36:50.479  7917  8181 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 18:36:50.480  7917  8181 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-23 18:36:50.480   318  1700 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7917
08-23 18:36:50.480   318  1700 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-23 18:36:50.480   318  1700 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-23 18:36:50.480   318  1700 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-23 18:36:50.480   318  1700 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-23 18:36:50.480   318  1700 V voice   : voice_set_parameters: exit with code(0)
08-23 18:36:50.480   318  1700 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
,08-23 18:36:50.480   318  1700 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-23 18:36:50.480   318  1700 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 18:36:50.480   318  1700 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 18:36:50.481   318  1700 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-23 18:36:50.481   318  1700 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-23 18:36:50.481  7917  8181 V ToneGenerator: ToneGenerator destructor
08-23 18:36:50.481  7917  8181 V ToneGenerator: stopTone
,08-23 18:36:50.481  7917  8181 V ToneGenerator: Delete Track: 0xb4928a80
08-23 18:36:50.481  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.482   318  4487 V AudioPolicyService: AudioCommandThread() adding release output 2
08-23 18:36:50.482   318  4487 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-23 18:36:50.482   318  4487 V AudioFlinger: PlaybackThread::Track destructor
08-23 18:36:50.482   318  1257 V AudioPolicyService: AudioCommandThread() waking up
08-23 18:36:50.482   318  4487 V AudioFlinger: removeClient_l() pid 7917, calling pid 318
,08-23 18:36:50.482   318  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
08-23 18:36:50.482   318  1257 V AudioPolicyManager: releaseOutput() 2
08-23 18:36:50.482   318  1257 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 18:36:50.482  7917  8181 V AudioTrack: ~AudioTrack, releasing session id from 7917 on behalf of 7917
08-23 18:36:50.482   318  1383 V AudioFlinger: releasing 23 from 7917 for 7917
08-23 18:36:50.482   318  1383 V AudioFlinger:  decremented refcount to 0
,08-23 18:36:50.482   318  1383 V AudioFlinger: purging stale effects
08-23 18:36:50.484  1033  1977 W Process : Unable to open /proc/8183/status
08-23 18:36:50.484  7917  7917 D A2dpService: Received start request. Starting profile...
08-23 18:36:50.485  7917  7917 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 18:36:50.486  7917  7917 V Avrcp   : make
08-23 18:36:50.486  7917  7917 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-23 18:36:50.486  7917  7917 I bluedroid-qcom: get_profile_interface avrcp
,08-23 18:36:50.499  7917  7917 V AudioManager: registerRemoteController: size of Media player list: 0
08-23 18:36:50.501  7917  7917 E AudioManager: No RCC entry present to update
08-23 18:36:50.501  7917  7917 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 18:36:50.506  7917  7917 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-23 18:36:50.507  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-23 18:36:50.507  7917  7917 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-23 18:36:50.512  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 18:36:50.640  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
08-23 18:36:50.640  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-23 18:36:50.734  1033  1970 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-23 18:36:50.741  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 18:36:50.744  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 18:36:50.745  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 18:36:50.746  7917  7917 I BluetoothA2dpServiceJni: classInitNative
08-23 18:36:50.746  7917  7917 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 18:36:50.746  7917  7917 D A2dpStateMachine: make
08-23 18:36:50.748  7917  7917 I bluedroid-qcom: get_profile_interface a2dp
08-23 18:36:50.748  7917  8193 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 18:36:50.752  7917  7917 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-23 18:36:50.752  7917  7917 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-23 18:36:50.753  7917  8192 D A2dpStateMachine: Enter Disconnected: -2
08-23 18:36:50.753  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
,08-23 18:36:50.755  7917  7917 I BluetoothHidServiceJni: classInitNative: succeeds
08-23 18:36:50.760  7917  7917 D HidService: Received start request. Starting profile...
08-23 18:36:50.760  7917  7917 I bluedroid-qcom: get_profile_interface hidhost
08-23 18:36:50.760  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.761  7917  7917 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 18:36:50.765  7917  7917 D HealthService: Received start request. Starting profile...
,08-23 18:36:50.767  7917  7917 I bluedroid-qcom: get_profile_interface health
08-23 18:36:50.768  7917  7917 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-23 18:36:50.768  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.768  7917  7917 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 18:36:50.770  7917  7917 D PanService: Received start request. Starting profile...
08-23 18:36:50.770  7917  7917 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 18:36:50.770  7917  7917 I bluedroid-qcom: get_profile_interface pan
08-23 18:36:50.867  1033  1574 I art     : Explicit concurrent mark sweep GC freed 27444(1350KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.568ms total 92.350ms
,08-23 18:36:50.868  7917  7917 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-23 18:36:50.868  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.869  7917  7917 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-23 18:36:50.873  7917  7917 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 18:36:50.874  7917  7917 D BtGatt.GattService: Received start request. Starting profile...
08-23 18:36:50.874  7917  7917 D BtGatt.GattService: start()
08-23 18:36:50.874  7917  7917 I bluedroid-qcom: get_profile_interface gatt
08-23 18:36:50.874  7917  7917 D BtGatt.AdvertiseManager: advertise manager created
08-23 18:36:50.879  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.880  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.880  7917  7917 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-23 18:36:50.881  7917  7917 V BluetoothMapService: BluetoothMapBinder()
08-23 18:36:50.881  7917  7917 D BluetoothMapService: Received start request. Starting profile...
08-23 18:36:50.881  7917  7917 D BluetoothMapService: start()
08-23 18:36:50.891  7917  7917 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-23 18:36:50.891  7917  7917 D BluetoothMapEmailAppObserver: createReceiver()
08-23 18:36:50.892  7917  7917 D BluetoothMapEmailAppObserver: initObservers()
08-23 18:36:50.892  7917  7917 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-23 18:36:50.897  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:50.897  7917  7917 D HeadsetStateMachine: Proxy object connected
08-23 18:36:50.898  7917  7917 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-23 18:36:50.898  7917  7917 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-23 18:36:50.899  7917  8181 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 18:36:50.899  7917  8181 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 18:36:50.900  7917  8181 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-23 18:36:50.902  7917  7917 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:50.904  7917  7917 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:50.906  7917  7917 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:50.907  7917  7917 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:50.910  7917  7917 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:50.910  7917  7917 V PanService: [BTUI] SIM Extra State :ABSENT
,08-23 18:36:50.915  7917  7917 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 18:36:50.917  7917  7917 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-23 18:36:50.917  7917  7917 V BluetoothMapService: Handler(): got msg=1
08-23 18:36:50.918  7917  7917 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:50.918  7917  7917 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:50.918  7917  7917 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:50.918  7917  7917 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:50.918  7917  7917 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-23 18:36:50.918  7917  8157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-23 18:36:50.918  7917  8157 I bluedroid-qcom: enable
08-23 18:36:50.918  7917  8157 I bt_hci_bdroid: init
08-23 18:36:50.919  7917  8157 I bt_vendor: bt-vendor : init
08-23 18:36:50.919  7917  8157 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 18:36:50.919  7917  8157 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 18:36:50.919  7917  8157 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-23 18:36:50.919  7917  8157 D bt_userial_mct: userial_init
08-23 18:36:50.922  7917  8157 D bt_hci_bdroid: set_power 1
08-23 18:36:50.922  7917  8157 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 18:36:50.922  7917  8157 I bt_vendor: Starting hciattach daemon
08-23 18:36:50.922  7917  8157 I bt_vendor: try to set true
08-23 18:36:50.923  7917  8200 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 18:36:50.923  7917  8200 I bt-btu  : btu_task pending for preload complete event
,08-23 18:36:50.919  8203  8203 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:50.919  8203  8203 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:50.939  8204  8204 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-23 18:36:51.018  8219  8219 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-23 18:36:51.033  8221  8221 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 18:36:51.067  8224  8224 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 18:36:51.092  8225  8225 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-23 18:36:51.110  8226  8226 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 18:36:51.124  8227  8227 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-23 18:36:51.148  8229  8229 I libmdmdetect: ESOC framework not supported
,08-23 18:36:51.149  8229  8229 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-23 18:36:51.160  8229  8229 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-23 18:36:51.160  8229  8229 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-23 18:36:51.160  8229  8229 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-23 18:36:51.160  8229  8229 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-23 18:36:51.160  8229  8229 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-23 18:36:51.160  8229  8229 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-23 18:36:51.160  8229  8229 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-23 18:36:51.204  8229  8231 E QC-QMI  : qmi_client [8229] 15: failed to locate client data
08-23 18:36:51.205   471   471 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-23 18:36:51.205   471   471 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-23 18:36:51.264  8233  8233 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-23 18:36:51.278  8237  8237 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 18:36:51.324  7917  8157 I bt_vendor: bluetooth satus is on
08-23 18:36:51.324  7917  8157 D bt_hci_bdroid: preload
08-23 18:36:51.324  7917  8202 D bt_userial_mct: userial_open(port:0)
08-23 18:36:51.324  7917  8202 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-23 18:36:51.329  7917  8202 I bt_vendor: Done intiailizing UART
08-23 18:36:51.332  7917  8202 I bt_vendor: Done intiailizing UART
08-23 18:36:51.332  7917  8202 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-23 18:36:51.332  7917  8202 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-23 18:36:51.332  7917  8242 D bt_userial_mct: Entering userial_read_thread()
08-23 18:36:51.333  7917  8200 I bt-btu  : btu_task received preload complete event
08-23 18:36:51.334  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-23 18:36:51.334  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-23 18:36:51.340  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 18:36:51.348  7917  8200 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 18:36:51.349  7917  8200 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 18:36:51.349  7917  8200 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 18:36:51.349  7917  8200 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 18:36:51.349  7917  8200 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 18:36:51.421  7917  8200 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-23 18:36:51.422  7917  8200 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0202061 ,
,08-23 18:36:51.422  7917  8200 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0202061 ,
,08-23 18:36:51.469  7917  8161 E bt-btif : Calling BTA_HhEnable
08-23 18:36:51.470  7917  8161 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-23 18:36:51.475  7917  8161 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-23 18:36:51.478  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 18:36:51.478  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 18:36:51.480  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-23 18:36:51.480  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-23 18:36:51.480  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-23 18:36:51.481  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-23 18:36:51.481  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-23 18:36:51.482  7917  8161 D BluetoothAdapterProperties: Name is: G3
08-23 18:36:51.484  7917  8161 D BluetoothAdapterProperties: Scan Mode:20
,08-23 18:36:51.491  7917  8161 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 18:36:51.491  7917  8161 D bt_hci_bdroid: postload
08-23 18:36:51.492  7917  8202 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 18:36:51.492  7917  8161 D bte_conf: Device ID record 1 : primary
08-23 18:36:51.492  7917  8161 D bte_conf:   vendorId            = 00c4
08-23 18:36:51.492  7917  8161 D bte_conf:   vendorIdSource      = 0001
08-23 18:36:51.492  7917  8161 D bte_conf:   product             = 13a1
08-23 18:36:51.492  7917  8161 D bte_conf:   version             = 1000
08-23 18:36:51.492  7917  8161 D bte_conf:   clientExecutableURL = 
08-23 18:36:51.492  7917  8161 D bte_conf:   serviceDescription  = 
08-23 18:36:51.492  7917  8161 D bte_conf:   documentationURL    = 
08-23 18:36:51.493  7917  8161 D bte_conf: bte_load_did_conf no section named DID2.
08-23 18:36:51.493  7917  8200 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-23 18:36:51.494  7917  8202 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 18:36:51.497  7917  8202 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 18:36:51.497  7917  8157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-23 18:36:51.498  7917  8157 D BluetoothAdapterProperties: ScanMode =  20
08-23 18:36:51.498  7917  8157 D BluetoothAdapterProperties: State =  11
08-23 18:36:51.498  7917  8157 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-23 18:36:51.498  7917  8157 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-23 18:36:51.499  7917  8157 D BluetoothAdapterProperties: Setting state to 12
08-23 18:36:51.499  7917  8157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 18:36:51.502  7917  8202 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 18:36:51.504  7917  8161 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 18:36:51.504  7917  8161 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 18:36:51.499  8247  8247 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:51.499  8247  8247 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:51.510  7917  8242 E bt_mct  : hci lib postload completed
,08-23 18:36:51.519  7917  8200 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:51.519  7917  8200 W bt-smp  : Plain text(LSB ~ MSB) = a3 e2 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:51.519  7917  8200 W bt-smp  : Encrypted text(LSB ~ MSB) = c2 c4 2b 63 cf 50 03 9e a4 c9 d9 8e ba 0f 41 52 
08-23 18:36:51.520  7917  8200 W bt-btm  : Stopping oneshot timer
08-23 18:36:51.529  1033  1109 D BluetoothManagerService: Message: 60
08-23 18:36:51.530  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-23 18:36:51.530  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-23 18:36:51.530  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 18:36:51.533  7917  8161 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 18:36:51.533  7917  8161 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-23 18:36:51.535  7917  8157 I BluetoothAdapterState: Entering On State
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:51.552  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:36:51.556  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:51.563  7917  8157 D LGBluetoothServiceAdapter: [BTUI] OnState
08-23 18:36:51.563  7917  8157 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-23 18:36:51.563  7917  8157 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-23 18:36:51.567  7917  8157 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-23 18:36:51.575  7917  8200 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:51.575  7917  8200 W bt-smp  : Plain text(LSB ~ MSB) = 19 f6 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:51.575  7917  8200 W bt-smp  : Encrypted text(LSB ~ MSB) = a5 d4 1f ce cf 0a b3 7e a6 8c be 96 78 0a da f4 
08-23 18:36:51.576  7917  8200 W bt-btm  : Stopping oneshot timer
08-23 18:36:51.570  7102  7824 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 18:36:51.578  1033  1033 D BluetoothHeadset: Proxy object connected
08-23 18:36:51.585  7917  8157 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-23 18:36:51.593  7102  7824 D BluetoothPan: onBluetoothStateChange on: true
08-23 18:36:51.593  7102  7824 D BluetoothPan: onBluetoothStateChange call bindService
08-23 18:36:51.602  7917  8200 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:51.602  7917  8200 W bt-smp  : Plain text(LSB ~ MSB) = ab a2 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:51.602  7917  8200 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 d0 bd 6b ed 26 e7 70 1d 39 30 54 53 b9 de 9d 
08-23 18:36:51.602  7917  8200 W bt-btm  : Stopping oneshot timer
,08-23 18:36:51.610  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:36:51.624  7917  8200 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 18:36:51.624  7917  8200 W bt-smp  : Plain text(LSB ~ MSB) = a7 22 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:51.624  7917  8200 W bt-smp  : Encrypted text(LSB ~ MSB) = 36 b0 47 60 72 8e 94 a1 9b 15 a2 66 f3 12 20 ec 
08-23 18:36:51.624  7917  8200 W bt-btm  : Stopping oneshot timer
,08-23 18:36:51.628  1852  1852 D BluetoothHeadset: Proxy object connected
08-23 18:36:51.628  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 18:36:51.642  8252  8252 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-23 18:36:51.648  1852  4485 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:36:51.650  1033  1033 D BluetoothA2dp: Proxy object connected
08-23 18:36:51.655  7942  7973 D UEI.SmartControl: Internal timer expired: 1
08-23 18:36:51.655  7942  7973 D UEI.SmartControl: unbind internal service
08-23 18:36:51.659  7917  8200 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-23 18:36:51.659  7917  8200 W bt-smp  : Plain text(LSB ~ MSB) = d0 e7 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 18:36:51.659  7917  8200 W bt-smp  : Encrypted text(LSB ~ MSB) = e6 7f 68 41 71 40 54 52 6c 59 ad 41 be 94 aa 68 
08-23 18:36:51.659  7917  8200 W bt-btm  : Stopping oneshot timer
08-23 18:36:51.661  7102  7102 D BluetoothInputDevice: Proxy object connected
08-23 18:36:51.661  7102  7102 D HidProfile: Bluetooth service connected
08-23 18:36:51.663  1852  1852 D BluetoothHeadset: Proxy object connected
,08-23 18:36:51.665  7942  7942 D UEI.SmartControl: Service.onUnbind: IControl
08-23 18:36:51.665  1852  2452 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:36:51.665  7942  7942 D UEI.SmartControl: Service.onDestroy
08-23 18:36:51.666  7942  7942 D UEI.SmartControl: Lock is in USE false
08-23 18:36:51.666  7942  7942 D UEI.SmartControl: unbind internal service
08-23 18:36:51.667  7942  7942 D serial_port: close(fd = 25)
08-23 18:36:51.669  7102  7102 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 18:36:51.669  7102  7102 D PanProfile: Bluetooth service connected
08-23 18:36:51.671  7942  7942 I UEI.SmartControl: Serial port is closed.
08-23 18:36:51.671  7942  7942 I UEI.SmartControl: Serial port is closed.
08-23 18:36:51.671  7942  7942 D UEI.SmartControl: Blaster closed
08-23 18:36:51.672  7942  7942 D UEI.SmartControl: Shut down QS...
,08-23 18:36:51.672  7942  7942 D UEI.SmartControl: Stopping QS lib
,08-23 18:36:51.674  1852  1852 D BluetoothHeadset: Proxy object connected
08-23 18:36:51.675  7942  7942 D UEI.SmartControl: QS lib stop result = true
08-23 18:36:51.675  7942  7942 D UEI.SmartControl: Stopped QS lib
08-23 18:36:51.675  7102  7128 D BluetoothMap: onBluetoothStateChange: up=true
08-23 18:36:51.676  7942  7942 D UEI.SmartControl: Stopped file observer...
08-23 18:36:51.676  7942  7942 D UEI.SmartControl: QS shutdown complete
08-23 18:36:51.681  7102  7102 D BluetoothMap: Proxy object connected
08-23 18:36:51.681  7102  7102 D MapProfile: Bluetooth service connected
08-23 18:36:51.681  7102  7102 D BluetoothMap: getConnectedDevices()
08-23 18:36:51.681  7102  7824 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 18:36:51.683  7917  7933 V BluetoothMapService: getConnectedDevices()
08-23 18:36:51.685  7102  7102 D BluetoothHeadset: Proxy object connected
08-23 18:36:51.685  7102  7102 D HeadsetProfile: Bluetooth service connected
,08-23 18:36:51.688  7102  7138 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 18:36:51.691  7102  7824 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 18:36:51.691  7102  7102 D BluetoothA2dp: Proxy object connected
08-23 18:36:51.691  7102  7102 D A2dpProfile: Bluetooth service connected
08-23 18:36:51.694  1033  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-23 18:36:51.694  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-23 18:36:51.695  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-23 18:36:51.698  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.699  1941  2100 D LGBluetoothAPIService: Message: 1
08-23 18:36:51.699  1941  2100 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-23 18:36:51.699  1033  1109 D BluetoothManagerService: Message: 40
08-23 18:36:51.699  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-23 18:36:51.700  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:51.701  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 18:36:51.703  7917  7917 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.703  7917  7917 D BluetoothMapService: STATE_ON
08-23 18:36:51.707  1941  2100 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-23 18:36:51.711  7102  7102 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-23 18:36:51.713  7102  7102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 18:36:51.718  7102  7102 D DockEventReceiver: finishStartingService: stopping service
08-23 18:36:51.721  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:51.721  7917  7917 V BluetoothPbapService: Pbap Service onCreate
08-23 18:36:51.721  7917  7917 V BluetoothPbapService: Starting PBAP service
08-23 18:36:51.723  7917  7917 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-23 18:36:51.723  7917  7917 V BluetoothMapService: Handler(): got msg=1
08-23 18:36:51.724  7917  7917 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-23 18:36:51.724  7917  7917 V BluetoothPbapService: Pbap Service onBind
08-23 18:36:51.725  7917  8271 D BluetoothMapMasInstance: MAS initSocket()
08-23 18:36:51.725  7917  7917 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.726  7917  7917 V BluetoothPbapService: state: 12
08-23 18:36:51.727  7917  7917 D LGBluetoothAPIServer: [BTUI] onCreate()
08-23 18:36:51.727  7917  7917 D LGBluetoothAPIServer: [BTUI] onBind()
08-23 18:36:51.728  7917  8271 D BluetoothMapMasInstance:   masId = 00
08-23 18:36:51.728  7917  8271 D BluetoothMapMasInstance:   msgTypes = 0e
08-23 18:36:51.728  7917  8271 D BluetoothMapMasInstance:   masName = SMS/MMS
08-23 18:36:51.728  7917  8271 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-23 18:36:51.729  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-23 18:36:51.729  1941  2100 D LGBluetoothAPIService: Message: 100
08-23 18:36:51.729  1941  2100 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-23 18:36:51.729  7917  7917 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 18:36:51.729  7917  7917 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.729  7917  7917 V BluetoothPbapReceiver: ***********state = 12
08-23 18:36:51.729  1033  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:51.731  7917  7917 V BluetoothPbapService: Handler(): got msg=1
08-23 18:36:51.731  7917  7917 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-23 18:36:51.731  7917  8271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:51.733  7917  8272 V BluetoothPbapService: Pbap Service initSocket
08-23 18:36:51.733  2164  2164 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 18:36:51.733  1033  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:51.733  7102  7102 D BluetoothPbap: Proxy object connected
08-23 18:36:51.733  7102  7102 D PbapServerProfile: Bluetooth service connected
08-23 18:36:51.734  2164  2164 D c       : Getting all permits...
08-23 18:36:51.734  2164  2164 D a       : Opening database...
08-23 18:36:51.737  2164  2164 D a       : Opening database auth.proximity.permit_store...
08-23 18:36:51.738  7917  8271 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-23 18:36:51.738  7917  8271 V BluetoothMapMasInstance: Succeed to create listening socket 
08-23 18:36:51.738  2164  2164 D a       : Closing database...
08-23 18:36:51.738  7917  8271 D BluetoothMapMasInstance: Accepting socket connection...
08-23 18:36:51.739  7917  8161 D BluetoothAdapterProperties: Scan Mode:21
08-23 18:36:51.739  7917  8161 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-23 18:36:51.742  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:51.743  7917  8272 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:51.744  7917  8272 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-23 18:36:51.744  7917  8272 V BluetoothPbapService: Succeed to create listening socket 
08-23 18:36:51.744  7917  8272 V BluetoothPbapService: Accepting socket connection...
08-23 18:36:51.753  7102  7102 D BluetoothPermissionRequest: onReceive
,08-23 18:36:51.754  7102  7102 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 18:36:51.756  7102  7102 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 18:36:51.758  7917  7917 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-23 18:36:51.760  7917  7917 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-23 18:36:51.765  7917  7917 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-23 18:36:51.787  7917  7917 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 18:36:51.787  7917  7917 V BtOppService: onCreate
,08-23 18:36:51.792  7917  7917 V BluetoothOppNotification: send message
08-23 18:36:51.796  7917  7917 V BtOppService: Starting RfcommListener
08-23 18:36:51.811  7917  7917 D BluetoothOppPreference: Dumping Names:  
08-23 18:36:51.811  7917  7917 D BluetoothOppPreference: {}
08-23 18:36:51.811  7917  7917 D BluetoothOppPreference: Dumping Channels:  
08-23 18:36:51.811  7917  7917 D BluetoothOppPreference: {}
,08-23 18:36:51.812  7917  7917 V BtOppService: onStartCommand
08-23 18:36:51.819  7917  8279 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 18:36:51.821  7917  8276 V BtOppService: Deleted complete outbound shares, number =  0
08-23 18:36:51.823  7917  7917 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.824  7917  7917 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 18:36:51.824  7917  8279 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 18:36:51.825  7917  8276 V BtOppService: Deleted complete inbound failed shares, number = 0
08-23 18:36:51.826  7917  8276 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-23 18:36:51.827  7917  8276 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3278614f on behalf of 
08-23 18:36:51.827  7917  8279 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b608fae on behalf of 
08-23 18:36:51.829  7917  7917 V BluetoothOppNotification: new notify threadi!
,08-23 18:36:51.831  7917  7917 V BluetoothOppNotification: send delay message
08-23 18:36:51.832  7917  8279 V BluetoothOppNotification: update too frequent, put in queue
08-23 18:36:51.832  7917  7917 V BtOppService: start RfcommListener
08-23 18:36:51.833  7917  8279 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 18:36:51.833  7917  8280 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 18:36:51.835  7917  8280 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d01b0dc on behalf of 
,08-23 18:36:51.836  7917  8280 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 18:36:51.837  7917  8280 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 18:36:51.838  7917  8280 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23c385e5 on behalf of 
08-23 18:36:51.839  7917  7917 V BtOppService: RfcommListener started
08-23 18:36:51.839  7917  7917 V BtOppService: ContentObserver received notification
08-23 18:36:51.840  7917  8280 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 18:36:51.841  7917  7917 V BtOppService: ContentObserver received notification
08-23 18:36:51.841  7917  8281 V BtOppRfcommListener: Starting RFCOMM listener....
08-23 18:36:51.842  1033  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:51.843  7917  8282 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 18:36:51.843  7917  8282 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 18:36:51.843  7917  8281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 18:36:51.848  7917  8281 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-23 18:36:51.848  7917  8281 V BtOppRfcommListener: Started RFCOMM listener....
08-23 18:36:51.848  7917  8282 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129f8ba on behalf of 
08-23 18:36:51.848  7917  8281 I BtOppRfcommListener: Accept thread started.
08-23 18:36:51.848  7917  8281 V BtOppRfcommListener: Accepting connection...
08-23 18:36:51.849  7917  8280 V BluetoothOppNotification: outbound notification was removed.
08-23 18:36:51.849  7917  8280 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 18:36:51.851  7917  8282 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 18:36:51.851  7917  8280 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2283c36b on behalf of 
08-23 18:36:51.854  7917  8280 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 18:36:51.855  7917  8280 V BluetoothOppNotification: inbound notification was removed.
08-23 18:36:51.855  7917  8280 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 18:36:51.857  7917  8280 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2766fec8 on behalf of 
08-23 18:36:51.859  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:51.859  7917  7917 V BluetoothFtpService: Ftp Service onCreate
08-23 18:36:51.859  7917  7917 I BluetoothFtpService: Ftp Service onCreate
08-23 18:36:51.859  7917  7917 V BluetoothFtpService: Ftp Service onStartCommand
08-23 18:36:51.860  7917  7917 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.860  7917  7917 V BluetoothFtpService: Starting Listening on sockets
08-23 18:36:51.860  7917  7917 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 18:36:51.860  7917  7917 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 18:36:51.860  7917  7917 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 18:36:51.860  7917  7917 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.860  7917  7917 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-23 18:36:51.860  7917  7917 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-23 18:36:51.862  7917  7917 V BluetoothFtpService: Handler(): got msg=1
08-23 18:36:51.864  7917  7917 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-23 18:36:51.864  7917  7917 V BluetoothFtpService: Ftp Service initSocket
08-23 18:36:51.868  1033  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:51.869  7917  7917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:51.873  7917  7917 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-23 18:36:51.873  7917  7917 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-23 18:36:51.875  7917  8284 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-23 18:36:51.889  7917  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a4b3add
08-23 18:36:51.889  7917  7917 V BluetoothSapService: Sap Service onCreate
08-23 18:36:51.892  7917  7917 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 18:36:51.892  7917  7917 V BluetoothSapService: state: 12
08-23 18:36:51.892  7917  7917 V BluetoothSapService: Starting SAP server process
,08-23 18:36:51.894  7917  7917 V BluetoothSapService: SAP Service startRfcommListenerThread
08-23 18:36:51.889  8285  8285 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:51.889  8285  8285 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 18:36:51.897  7917  8286 V BluetoothSapService: Sap Service initRfcommSocket
08-23 18:36:51.898  1033  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:51.900  7917  8286 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 18:36:51.902  7917  8286 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-23 18:36:51.902  7917  8286 V BluetoothSapService: Succeed to create listening socket 
08-23 18:36:51.902  7917  8286 V BluetoothSapService: Accepting socket connection...
08-23 18:36:51.906  8285  8285 V BT_SAP  : Event pipe created
08-23 18:36:51.906  8285  8285 V BT_SAP  : create_server_socket qcom.sap.server
08-23 18:36:51.906  8285  8285 V BT_SAP  : created socket fd 6
,08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:52.306  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 18:36:52.319  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:52.325  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:52.325  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@160e1167 added. We now have 8 listener(s)
08-23 18:36:52.325  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 18:36:52.331  1033  1977 D WifiServiceImplEx: setWifiEnabled: false pid=6980, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-23 18:36:52.331  1033  1977 D WifiService: setWifiEnabled: false pid=6980, uid=10118
,08-23 18:36:52.331  1033  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 18:36:52.336  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:52.337  1033  2012 D WifiServiceImplEx: setWifiEnabled: true pid=6980, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 18:36:52.337  1033  2012 D WifiService: setWifiEnabled: true pid=6980, uid=10118
08-23 18:36:52.337  1033  2012 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 18:36:52.360  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 18:36:52.360  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 18:36:52.360  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-23 18:36:52.362  1033  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-23 18:36:52.362  1033  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-23 18:36:52.365  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-23 18:36:52.365  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 18:36:52.365  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-23 18:36:52.365  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 18:36:52.365  1033  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-23 18:36:52.365  1033  1536 E WifiHW  : unknown target_country: EU , set to default
08-23 18:36:52.365  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-23 18:36:52.365  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-23 18:36:52.365  1033  1536 I WifiUtil: gEnableBmps=1
08-23 18:36:52.837  7917  7917 V BluetoothOppNotification: new notify threadi!
,08-23 18:36:52.850  7917  7917 V BluetoothOppNotification: send delay message
08-23 18:36:52.865  7917  8304 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-23 18:36:52.874  7917  8304 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ca58c9d on behalf of 
08-23 18:36:52.874  7917  8304 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 18:36:52.886  7917  8304 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-23 18:36:52.890  7917  8304 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21c2e512 on behalf of 
08-23 18:36:52.891  7917  8304 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 18:36:52.892  7917  8304 V BluetoothOppNotification: outbound notification was removed.
08-23 18:36:52.892  7917  8304 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 18:36:52.893  7917  8304 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fb334e3 on behalf of 
08-23 18:36:52.894  7917  8304 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 18:36:52.895  7917  8304 V BluetoothOppNotification: inbound notification was removed.
08-23 18:36:52.896  7917  8304 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 18:36:52.896  7917  8304 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fcdee0 on behalf of 
08-23 18:36:53.039   311   893 D SoftapController: Softap fwReload - Ok
,08-23 18:36:53.049  1033  1536 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (680ms)
08-23 18:36:53.060  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:36:53.060  1033  1109 D Tethering: InitialState.processMessage what=4
,08-23 18:36:53.071   311   893 D CommandListener: Setting iface cfg
08-23 18:36:53.071   311   893 D CommandListener: Trying to bring down wlan0
08-23 18:36:53.073   311   893 D CommandListener: Clearing all IP addresses on wlan0
,08-23 18:36:53.082  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 18:36:53.090  1033  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-23 18:36:53.089  8307  8307 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:53.102  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:53.102  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:53.102  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 18:36:53.109  8307  8307 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 18:36:53.121  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:53.124  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-23 18:36:53.147  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 18:36:53.149  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-23 18:36:53.150  1033  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-23 18:36:53.160  1033  1536 D WifiMonitor: connecting to supplicant
,08-23 18:36:53.165  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 18:36:53.165  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 18:36:53.166  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 18:36:53.166  7102  7102 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 18:36:53.167  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 18:36:53.168  7102  7102 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 18:36:53.168  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 18:36:53.168  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 18:36:53.168  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 18:36:53.168  7102  7102 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 18:36:53.168  7102  7102 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 18:36:53.171  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 18:36:53.171  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 18:36:53.171  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 18:36:53.171  7102  7102 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 18:36:53.171  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 18:36:53.174  7102  7102 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 18:36:53.174  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 18:36:53.174  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 18:36:53.174  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 18:36:53.174  7102  7102 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 18:36:53.174  7102  7102 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 18:36:53.177  8307  8307 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-23 18:36:53.215  8307  8307 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 18:36:53.215  8307  8307 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-23 18:36:53.225  1033  1967 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8324 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-23 18:36:53.278  8307  8307 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 18:36:53.330  1033  1782 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8346 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 18:36:53.339  8324  8344 W FormManager: Network not available. Please check & try again.
08-23 18:36:53.345  8324  8345 V FormManager: Network unavailable.
,08-23 18:36:53.349  8307  8307 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-23 18:36:53.351  8324  8345 V FormManager: Network unavailable.
08-23 18:36:53.356  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-23 18:36:53.359  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-23 18:36:53.359  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-23 18:36:53.360  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-23 18:36:53.360  1033  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-23 18:36:53.361  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:53.361  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:53.362  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:53.362  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:53.363  1033  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-23 18:36:53.363  1033  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-23 18:36:53.363  1033  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-23 18:36:53.364  1033  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-23 18:36:53.364  1033  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-23 18:36:53.364  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 18:36:53.364  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
08-23 18:36:53.364  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 18:36:53.364  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.364  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.365  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.365  1033  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
08-23 18:36:53.365  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.365  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 18:36:53.365  1033  1536 D WifiNative-wlan0: SET update_config 1: returned true
08-23 18:36:53.365  1033  1536 D WifiConfigStore: Loading config and enabling all networks 
08-23 18:36:53.365  1033  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-23 18:36:53.366  1033  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-23 18:36:53.366  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-23 18:36:53.367  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:53.373  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-23 18:36:53.373  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-23 18:36:53.373  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-23 18:36:53.373  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-23 18:36:53.373  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-23 18:36:53.374  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-23 18:36:53.374  1033  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:53.377  6980  6980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:53.379  6980  6980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:53.382  1033  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-23 18:36:53.382  1033  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-23 18:36:53.383  1033  1536 D WifiStateMachine: enableVerboseLogging : level 2
08-23 18:36:53.383  1033  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-23 18:36:53.383  1033  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-23 18:36:53.383  1033  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-23 18:36:53.384  1033  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
,08-23 18:36:53.384  1033  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-23 18:36:53.384  1033  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-23 18:36:53.384  1033  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 18:36:53.384  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 18:36:53.385  1033  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-23 18:36:53.385  1033  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-23 18:36:53.385  1033  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-23 18:36:53.385  1033  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-23 18:36:53.386  1033  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-23 18:36:53.386  1033  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-23 18:36:53.386  1033  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-23 18:36:53.387  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 18:36:53.387  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 18:36:53.387  1033  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-23 18:36:53.388  1033  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-23 18:36:53.388  1033  1536 D WifiNative-HAL: Setting external_sim to 1
08-23 18:36:53.388  1033  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-23 18:36:53.388  1033  1536 D WifiNative-wlan0: SET external_sim 1: returned true
08-23 18:36:53.388  1033  1536 I WifiNative-HAL: startHal
08-23 18:36:53.388  1033  1536 D wifi    : setting scan oui 0xaf6c3080
08-23 18:36:53.388  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-23 18:36:53.389  1941  2256 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-23 18:36:53.389  1941  2256 D WfdsService: Set the WFDS Monitor: true
08-23 18:36:53.389  1941  2256 D WfdsMonitor: WfdsMonitorThread create
08-23 18:36:53.389  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 18:36:53.389  1033  1536 I WifiNative-HAL: startHal
08-23 18:36:53.389  1033  1536 D wifi    : setting scan oui 0xaf6c3080
08-23 18:36:53.389  1941  2256 D WfdsMonitor: WFDS Monitor is created and started
08-23 18:36:53.389  1941  2256 D WfdsService: WiFi: Supplicant connection re-established
08-23 18:36:53.389  1033  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-23 18:36:53.390  1941  8366 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-23 18:36:53.390  1033  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-23 18:36:53.390  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-23 18:36:53.390  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-23 18:36:53.391  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-23 18:36:53.391  7977  7977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.391  1033  ,1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 18:36:53.391  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 18:36:53.392  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 18:36:53.392  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-23 18:36:53.392  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-23 18:36:53.392  1941  8366 E CtrlSupplicant: Succeed to open control connection
08-23 18:36:53.392  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-23 18:36:53.392  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 18:36:53.392  1941  8366 E CtrlSupplicant: Succeed to open monitor connection
08-23 18:36:53.392  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-23 18:36:53.393  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true,
08-23 18:36:53.393  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 18:36:53.393  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 18:36:53.393  6980  7040 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-23 18:36:53.393  1941  8366 D WfdsMonitor: Supplicant connection established
08-23 18:36:53.393  1941  2256 D WfdsService: Connected to the supplicant for wfds
08-23 18:36:53.393  6980  7040 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
08-23 18:36:53.394  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 18:36:53.394  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-23 18:36:53.394  8307  8307 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-23 18:36:53.394  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-23 18:36:53.394  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 18:36:53.394  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 18:36:53.394  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-23 18:36:53.395  1033  1536 E WifiNative: : [218,760,502 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-23 18:36:53.395  1033  1536 D WifiNative-wlan0: doBoolean: RECONNECT
08-23 18:36:53.396  1033  1536 D WifiNative-wlan0: RECONNECT: returned true
08-23 18:36:53.396  1033  1536 D WifiNative-wlan0: doString: [STATUS]
08-23 18:36:53.396  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-23 18:36:53.396  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-23 18:36:53.397  1033  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 18:36:53.397  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:53.395  6980  7040 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3f237911 Bundle[{}]
08-23 18:36:53.397  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
08-23 18:36:53.398  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.398  6980  7040 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 18:36:53.398  6980  7040 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 18:36:53.399  6980  7040 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-23 18:36:53.399  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 18:36:53.399  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-23 18:36:53.399  1033  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.399  1033  1554 I WifiNative-HAL: startHal
08-23 18:36:53.399  1033  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf6c3080
08-23 18:36:53.399  1033  1554 D wifi    : failed to get capabilities : -3
08-23 18:36:53.399  1033  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:36:53.399  1033  1554 E WifiScanningService: could not get scan capabilities
08-23 18:36:53.399  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-23 18:36:53.400  1033  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-23 18:36:53.400   311   893 D CommandListener: Setting iface cfg
08-23 18:36:53.401   311   893 D CommandListener: Trying to bring up p2p0
08-23 18:36:53.401  1033  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-23 18:36:53.401  1033  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 18:36:53.401  1033  1535 D LGWifiP2pService: P2pEnablingState
08-23 18:36:53.401  1033  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.401  1033  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-23 18:36:53.401  1033  1535 D LGWifiP2pService: P2p socket connection successful
08-23 18:36:53.401  1033  1535 D LGWifiP2pService: P2pEnabledState
08-23 18:36:53.401  1033  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-23 18:36:53.402  1033  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-23 18:36:53.402  1033  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-23 18:36:53.402  1033  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-23 18:36:53.402  8307  8307 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-23 18:36:53.403  1033  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-23 18:36:53.403  1033  1535 D LGWifiP2pService: sending p2p connection changed broadcast
08-23 18:36:53.403  1033  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-23 18:36:53.404  1033  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-23 18:36:53.404  1033  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-23 18:36:53.404  1033  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-23 18:36:53.404  8307  8307 E wpa_supplicant: disconnect_rssi_lvl: -100
08-23 18:36:53.404  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 18:36:53.405  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 18:36:53.405  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 18:36:53.405  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-23 18:36:53.406  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-23 18:36:53.406  1941  1941 D WfdsService: WifiP2pState is changed : true
08-23 18:36:53.406  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-23 18:36:53.407  6980  7040 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 18:36:53.407  1941  1941 D WfdsService: isConnected: false
08-23 18:36:53.407  1941  2256 D WfdsService: Receive the WFDS_ENABLE Method
08-23 18:36:53.407  1941  2256 D WfdsService: Set the WFDS Monitor: true
08-23 18:36:53.407  6980  7040 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 18:36:53.407  1941  2256 D WfdsService: Connected to the supplicant for wfds
08-23 18:36:53.407  1941  2256 D WfdsJNI : doCommand: WFDS_SET TRUE
08-23 18:36:53.407  8307  8307 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-23 18:36:53.408  1941  2256 D WfdsService: selectPreferredScanChannel [36]
08-23 18:36:53.408  1941  2256 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-23 18:36:53.408  6980  7040 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 18:36:53.408  1033  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-23 18:36:53.408  1033  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
08-23 18:36:53.409  1033  1535 D WifiNative-p2p0: SET device_name G3: returned true
08-23 18:36:53.409  1033  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-23 18:36:53.409  1033  1535 D LGWifiP2pService: before postfix = G3
08-23 18:36:53.409  1033  1535 D WifiServerServiceExt: postfix byte check : 2
08-23 18:36:53.409  1033  1535 D LGWifiP2pService: after postfix = G3
08-23 18:36:53.409  1033  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-23 18:36:53.409  1033  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-23 18:36:53.409  1033  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-23 18:36:53.410  1033  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-23 18:36:53.410  1033  1535 D WifiNative-p2p0: doBoolean: SET config_methods, virtual_push_button physical_display keypad
08-23 18:36:53.411  1033  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-23 18:36:53.411  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-23 18:36:53.411  1033  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-23 18:36:53.411  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress
08-23 18:36:53.412  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-23 18:36:53.412  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 18:36:53.413  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:53.413  8307  8307 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 18:36:53.413  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.414  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.415  6980  7040 I System.out: Running OutgoingSocketThread
08-23 18:36:53.415  1033  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-23 18:36:53.415  1941  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.415  1941  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.415  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-23 18:36:53.416  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 18:36:53.416  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-23 18:36:53.416  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:53.416  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:53.416  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:53.416  1033  8364 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.416  1033  8364 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.416  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-23 18:36:53.416  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.416  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-23 18:36:53.416  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.416  1033  8364 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.416  1033  8364 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.416  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-23 18:36:53.416  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 18:36:53.416  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.416  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.417  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-23 18:36:53.417  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 18:36:53.417  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 18:36:53.417  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 18:36:53.417  1033  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-23 18:36:53.417  1033  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-23 18:36:53.417  1033  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-23 18:36:53.417  1033  1536 D WifiNative-wlan0: doBoolean: SCAN
08-23 18:36:53.418  1033  1536 D WifiNative-wlan0: SCAN: returned false
08-23 18:36:53.418  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=218783  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 18:36:53.419  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:53.420  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-23 18:36:53.420  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-23 18:36:53.420  1941  1941 D WfdsService: Update P2p Interface State: 3
08-23 18:36:53.420  1033  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-23 18:36:53.420  1033  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-23 18:36:53.421  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:53.421  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.421  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.421  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 18:36:53.422  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=218787  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 18:36:53.422  1033  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:53.422  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:53.422  1033  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:53.423  1033  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
08-23 18:36:53.423  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-23 18:36:53.424  1033  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:53.424  1033  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:53.424  1033  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 18:36:53.425  1033  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-23 18:36:53.425  1033  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-23 18:36:53.425  1033  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-23 18:36:53.425  1033  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-23 18:36:53.426  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:53.426  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-23 18:36:53.426  6980  8367 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 911)
08-23 18:36:53.427  6980  8367 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43284
08-23 18:36:53.427  6980  8367 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-23 18:36:53.433  1033  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-23 18:36:53.433  1033  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-23 18:36:53.433  1033  1535 D LGWifiP2pService: InactiveState
08-23 18:36:53.433  1033  1535 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.434  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.434  1033  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-23 18:36:53.434  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 18:36:53.434  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:53.434  1033  8364 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 18:36:53.435  1033  8364 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:53.435  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-23 18:36:53.435  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 18:36:53.435  8307  8307 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 18:36:53.435  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.435  1033  8364 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.435  1033  8364 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.435  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.435  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.435  8307  8307 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.435  1033  8364 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.435  1033  8364 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.435  1033  8364 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-23 18:36:53.436  1033  8364 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 18:36:53.436  1941  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 18:36:53.436  1941  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.436  1941  8366 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 18:36:53.436  1033  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.436  1033  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.437  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.437  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.437  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.437  1033  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.437  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:53.437  1033  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 18:36:53.437  1033  1033 E WifiServerServiceExt: No p2p device connected
,08-23 18:36:53.438  1941  2256 W WfdsService: DefaultState - msg [9441285] is not handled
08-23 18:36:53.444  8346  8346 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:53.446  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:36:53.451  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:53.453  1033  1967 I ActivityManager: Killing 7420:com.lge.drmservice/u0a62 (adj 15): empty #17
08-23 18:36:53.482  1033  1049 W libprocessgroup: failed to open /acct/uid_10062/pid_7420/cgroup.procs: No such file or directory
,08-23 18:36:53.504  8346  8346 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 18:36:53.506  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 18:36:53.519  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:53.529  8324  8371 W FormManager: Network not available. Please check & try again.
08-23 18:36:53.531  8324  8372 V FormManager: Network unavailable.
08-23 18:36:53.536  8324  8372 V FormManager: Network unavailable.
,08-23 18:36:53.557  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-23 18:36:53.558  4834  4834 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 18:36:53.560  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 18:36:53.565  4834  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 18:36:53.577  4834  8373 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 18:36:53.585  4834  8374 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 18:36:53.586  4834  8374 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 18:36:53.653  1033  1049 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8375 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-23 18:36:53.676   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 21.276ms
,08-23 18:36:53.697   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 19.815ms
,08-23 18:36:53.717   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 19.523ms
,08-23 18:36:53.803  8375  8375 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 18:36:53.804  8375  8375 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-23 18:36:53.813  8375  8375 V [BNRBootReceiver]: Boot Receiver Return
08-23 18:36:53.814  8375  8375 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-23 18:36:53.870  1033  1782 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8393 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 18:36:53.873  1033  1782 I ActivityManager: Killing 7437:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-23 18:36:53.932  1033  1781 W libprocessgroup: failed to open /acct/uid_10085/pid_7437/cgroup.procs: No such file or directory
,08-23 18:36:53.935  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-23 18:36:53.935  1033  8364 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-23 18:36:53.935  8307  8307 E wpa_supplicant: USIM:  scard_init function
08-23 18:36:53.935  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-23 18:36:53.935  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-23 18:36:53.935  1033  8364 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-23 18:36:53.935  8307  8307 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-23 18:36:53.936  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-23 18:36:53.936  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-23 18:36:53.936  1033  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-23 18:36:53.937  1033  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-23 18:36:53.937  1033  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-23 18:36:53.938  1033  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-23 18:36:53.938  1033  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-23 18:36:53.948  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=219314  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-23 18:36:53.954  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:53.954  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:53.954  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.954  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.954  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 18:36:53.955  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=219321  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-23 18:36:53.957  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.957  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:53.957  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-23 18:36:53.958  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:53.958  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-23 18:36:53.958  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:53.959  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:53.960  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:53.960  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:53.969  8393  8393 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 18:36:53.991  8393  8393 D PluginManager: init()
,08-23 18:36:54.056  8307  8307 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 18:36:54.061  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-23 18:36:54.061  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-23 18:36:54.062  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-23 18:36:54.062  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-23 18:36:54.062  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=219428  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 18:36:54.063  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=219428  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 18:36:54.063  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:54.063  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:54.063  1033  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219429
08-23 18:36:54.063  1033  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219429
08-23 18:36:54.064  1033  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219429
08-23 18:36:54.064  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219429
08-23 18:36:54.064  1033  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219429
08-23 18:36:54.065  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 18:36:54.065  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=219431  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 18:36:54.066  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=219432  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 18:36:54.067  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:54.068  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-23 18:36:54.069  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.069  1033  1536 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:54.069  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.069  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-23 18:36:54.069  1033  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:54.070  1033  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:54.070  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:54.070  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 18:36:54.071  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 18:36:54.071  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.071  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.071  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:54.071  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-23 18:36:54.073  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.074  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:54.074  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:54.075  8307  8307 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:36:54.075  8307  8307 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 18:36:54.076  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-23 18:36:54.076  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:36:54.076  1033  8364 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 18:36:54.076  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-23 18:36:54.076  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 18:36:54.076  1033  8364 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 18:36:54.077  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:54.077  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:54.078  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.078  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:54.079  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.079  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=219444  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 18:36:54.079  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=219445  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 18:36:54.080  1033  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=219445
08-23 18:36:54.080  1033  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=219446
08-23 18:36:54.080  1033  1536 D WifiNative-wlan0: doString: [STATUS]
08-23 18:36:54.081  1033  8364 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 18:36:54.081  1033  8364 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 18:36:54.081  1033  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 m,ode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 18:36:54.082  1033  1536 I WifiServiceExtension: setVHTCapabilityType  : false
08-23 18:36:54.086  1033  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-23 18:36:54.086  1033  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-23 18:36:54.089  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.089  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.089  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 18:36:54.092  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.092  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.092  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 18:36:54.093  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.093  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:54.094  1033  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-23 18:36:54.094  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:36:54.094  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.095  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 18:36:54.095  1033  1543 D ConnectivityService: Got NetworkAgent Messenger
08-23 18:36:54.095  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-23 18:36:54.095  1033  1543 D ConnectivityService: NetworkAgent connected
08-23 18:36:54.095  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 18:36:54.095  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 18:36:54.096  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.096  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:54.097  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.101  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 18:36:54.101  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 18:36:54.101  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 18:36:54.101  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 18:36:54.101  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-23 18:36:54.105  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 18:36:54.106   311   893 D CommandListener: Setting iface cfg
08-23 18:36:54.108  1033  1536 E WifiStateMachine: Start Dhcp Watchdog 3
08-23 18:36:54.108  1033  8412 D DhcpStateMachine: StoppedState
08-23 18:36:54.108  1033  8412 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.108  1033  8412 D DhcpStateMachine: WaitBeforeStartState
08-23 18:36:54.108  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=219474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:54.109  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=219474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:54.109  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=219474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:54.109  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=219475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:54.110  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=219475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:54.110  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:54.110  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-23 18:36:54.110  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=219475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 18:36:54.111  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14164] from screen [on:0 period:-1203568417] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-23 18:36:54.111  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1203568417] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-23 18:36:54.111  1033  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-23 18:36:54.114  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:54.115  1033  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-23 18:36:54.115  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.115  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.115  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.116  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.116  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.117  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.117  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-23 18:36:54.117  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
08-23 18:36:54.117  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
08-23 18:36:54.117  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-23 18:36:54.118  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-23 18:36:54.118  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-23 18:36:54.118  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 0
08-23 18:36:54.118  1033  1536 D WifiNative-wlan0: SET ps 0: returned true
08-23 18:36:54.118  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-23 18:36:54.118  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-23 18:36:54.118  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-23 18:36:54.118  1033  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-23 18:36:54.118  1033  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 18:36:54.118  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@497b79a target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.118  1033  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 18:36:54.118  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@497b79a target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.119  1033  8412 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.119  1033  8412 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-23 18:36:54.119   311   893 D CommandListener: Setting iface cfg
08-23 18:36:54.119   311   893 D CommandListener: Trying to bring up wlan0
08-23 18:36:54.120  1033  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-23 18:36:54.120  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:54.120  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 18:36:54.121  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 18:36:54.121  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 18:36:54.122  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.122  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.122  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.122  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.122  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 18:36:54.123  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 ,0
08-23 18:36:54.123  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-23 18:36:54.123  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-23 18:36:54.123  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-23 18:36:54.123  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 18:36:54.123  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.123  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.123  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 18:36:54.124  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 18:36:54.124  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-23 18:36:54.124  8307  8307 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-23 18:36:54.124  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-23 18:36:54.124  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 18:36:54.143  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
08-23 18:36:54.144  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-23 18:36:54.144  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 18:36:54.144  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 18:36:54.144  1033  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 18:36:54.145  1033  1543 D ConnectivityService: ignoring duplicate network state non-change
,08-23 18:36:54.147  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.147  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.147  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 18:36:54.148  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.149  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:54.151  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-23 18:36:54.151  1033  1543 D ConnectivityService: Adding iface wlan0 to network 102
08-23 18:36:54.152  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.155  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.155  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 18:36:54.157  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.157  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.157  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 18:36:54.158  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:54.163  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-23 18:36:54.165  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 18:36:54.167  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.167  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.167  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 18:36:54.168  1033  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 18:36:54.169  1033  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 18:36:54.169  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 18:36:54.169  1033  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-23 18:36:54.170  1033  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-23 18:36:54.171   311   893 E Netd    : netlink response contains error (File exists)
08-23 18:36:54.171  1033  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-23 18:36:54.172  1033  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-23 18:36:54.172  1033  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-23 18:36:54.172  1033  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-23 18:36:54.173  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.173  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 18:36:54.174  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 18:36:54.174  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-23 18:36:54.174  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-23 18:36:54.174  1033  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-23 18:36:54.174  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-23 18:36:54.175  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:54.175  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:54.175  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 18:36:54.175  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.175  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-23 18:36:54.175  1033  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-23 18:36:54.175  1033  1543 D ConnectivityService:    accepting network in place of null
08-23 18:36:54.175  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.175  1033  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.175  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-23 18:36:54.175  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.175  1033  8411 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.175  1033  8411 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-23 18:36:54.175  1033  8411 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 18:36:54.175  1033  8411 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-23 18:36:54.176  1033  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.176  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:54.177  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.177  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 18:36:54.178  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 18:36:54.178  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 18:36:54.178  1033  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-23 18:36:54.179  1033  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-23 18:36:54.179  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 18:36:54.179  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.180   311  8416 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-23 18:36:54.182  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 18:36:54.182  1033  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-23 18:36:54.183  1033  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN Link,UpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-23 18:36:54.184  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-23 18:36:54.185  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 18:36:54.185  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 18:36:54.185  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 18:36:54.185  1033  1543 D ConnectivityService: validation of new default Network = false
08-23 18:36:54.185  1033  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-23 18:36:54.185  1033  1543 D DSQN    : enableDataServiceNotify 
08-23 18:36:54.185  1033  1543 D DSQN    : start dsqn bin
08-23 18:36:54.189  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-23 18:36:54.189  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.189  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:54.189  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:54.190  1601  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 18:36:54.189  8417  8417 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:54.189  8417  8417 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:54.196  1033  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-23 18:36:54.201  8417  8417 E DSQN    : DSQN ssw
08-23 18:36:54.215  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:54.217  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.218  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 18:36:54.227   311  8416 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-23 18:36:54.261   311  8416 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-23 18:36:54.295   311   892 D LGDataListener: argv[0]=dsqncommand
08-23 18:36:54.295   311   892 D LGDataListener: argv[1]=wlan0
08-23 18:36:54.295   311   892 D LGDataListener: argv[2]=1
08-23 18:36:54.295   311   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-23 18:36:54.296  1033  1107 D DSQN    : DSQM DsqnNotification wlan0  1
08-23 18:36:54.296  1033  1107 D DSQN    : start to monitor internet connection
,08-23 18:36:54.322  1033  8412 D DhcpStateMachine: DHCPV4 request on wlan0
,08-23 18:36:54.324  1033  8412 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-23 18:36:54.324  1033  8412 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-23 18:36:54.319  8423  8423 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:54.319  8423  8423 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 18:36:54.332  1033  8411 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 16:36:54 GMT], X-Android-Received-Millis=[1471970214331], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471970214294]}
08-23 18:36:54.332  1033  8411 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 18:36:54.332  1033  8411 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-23 18:36:54.332  1033  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-23 18:36:54.332  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-23 18:36:54.333  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:54.333  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:54.333  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 18:36:54.333  1033  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-23 18:36:54.333  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-23 18:36:54.333  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.333  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:54.333  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:54.334  1033  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.334  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 18:36:54.335  1033  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.335  1601  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 18:36:54.335  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 18:36:54.335  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:54.336  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 18:36:54.341  8423  8423 I dhcpcd  : version 5.5.6 starting
08-23 18:36:54.345  8423  8423 E dhcpcd  : get_duid: m
08-23 18:36:54.345  8423  8423 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-23 18:36:54.345  8423  8423 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-23 18:36:54.364  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 18:36:54.365  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.366  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 18:36:54.418  8423  8423 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 18:36:54.419  8423  8423 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 18:36:54.419  8423  8423 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 18:36:54.419  8423  8423 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-23 18:36:54.419  8423  8423 D dhcpcd  : wlan0: sending REQUEST (xid 0xda79798f), next in 3.98 seconds
,08-23 18:36:54.428  6980  7040 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 912)
08-23 18:36:54.428  6980  7040 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 912)
08-23 18:36:54.437  6980  7040 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 917)
08-23 18:36:54.440  6980  7040 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-23 18:36:54.441  6980  7040 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 918)
,08-23 18:36:54.443  8393  8393 W ExternalStrings: load override strings
08-23 18:36:54.443  8393  8393 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:54.443  8393  8393 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:54.445  8393  8393 D StatusProvider: onCreate
,08-23 18:36:54.450  8423  8423 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-23 18:36:54.450  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.451  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f4fb14 added. We now have 2 listener(s)
08-23 18:36:54.451  1033  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 18:36:54.458  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-23 18:36:54.458  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.458  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.458  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 18:36:54.458  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27472fbd added. We now have 9 listener(s)
08-23 18:36:54.459  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.459  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:36:54.462  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:54.465  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:36:54.466  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.467  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:54.467  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 18:36:54.467  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32605d03 added. We now have 3 listener(s)
08-23 18:36:54.467  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.468  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.469  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.469  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 18:36:54.470  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.470  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.470  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0b480 added. We now have 10 listener(s)
08-23 18:36:54.470  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.470  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 18:36:54.470  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-23 18:36:54.470  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:54.470  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.470  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.470  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.470  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.471  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f4fb14 removed from the list
08-23 18:36:54.471  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 18:36:54.471  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27472fbd removed from the list
08-23 18:36:54.471  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.472  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:54.472  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.472  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.472  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.473  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.473  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.473  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.473  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27472fbd not in the list
,08-23 18:36:54.473  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.473  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.473  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.474  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.474  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.474  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0b480 removed from the list
08-23 18:36:54.474  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.474  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.474  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.474  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.474  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32605d03 removed from the list
08-23 18:36:54.474  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.474  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173c0ab9 added. We now have 2 listener(s)
,08-23 18:36:54.475  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.477  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.477  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.477  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.477  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.477  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33eb1efe added. We now have 9 listener(s)
08-23 18:36:54.477  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.478  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:36:54.481  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:54.484  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 18:36:54.485  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.485  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:54.485  8423  8423 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-23 18:36:54.485  8423  8423 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-23 18:36:54.486  8423  8423 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-23 18:36:54.486  8423  8423 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-23 18:36:54.487  8423  8423 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 18:36:54.487  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.487  8423  8423 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 18:36:54.488  8423  8423 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 18:36:54.488  8423  8423 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-23 18:36:54.488  8393  8393 V Signer  : override build config not found
08-23 18:36:54.488  8393  8393 D Signer  : value of property debug is false
08-23 18:36:54.490  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.490  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ac98ac added. We now have 3 listener(s)
08-23 18:36:54.490  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.491  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.493  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.493  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.493  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.493  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.493  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29099975 added. We now have 10 listener(s)
08-23 18:36:54.494  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.494  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:54.494  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:36:54.494  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:36:54.494  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.494  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:36:54.498  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 18:36:54.498  1033  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.504  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 18:36:54.505  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 18:36:54.506  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 18:36:54.507  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.508  6980  7040 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 18:36:54.508  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:54.508  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:54.510  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:54.510  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:54.510  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:54.512  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.512  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.512  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.512  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.513  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173c0ab9 removed from the list
08-23 18:36:54.513  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.513  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33eb1efe removed from the list
08-23 18:36:54.513  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:54.513  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.513  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.513  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.514  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-23 18:36:54.514  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-23 18:36:54.514  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.514  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-23 18:36:54.514  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.514  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.514  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33eb1efe not in the list
08-23 18:36:54.514  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.514  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.514  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-23 18:36:54.514  8393  8393, D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-23 18:36:54.515  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-23 18:36:54.515  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:54.515  8393  8393 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-23 18:36:54.515  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:54.516  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.516  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.516  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29099975 removed from the list
08-23 18:36:54.516  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.516  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.516  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.516  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.516  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ac98ac removed from the list
08-23 18:36:54.517  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.517  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a09398 added. We now have 2 listener(s)
08-23 18:36:54.517  1033  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.519  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.519  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.519  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.519  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.519  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31e757f1 added. We now have 9 listener(s)
08-23 18:36:54.519  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.520  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery, mode BLE is supported
08-23 18:36:54.522  8393  8393 V LGMDMManager: Create singleton instance
08-23 18:36:54.522  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:54.534  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:54.539  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.539  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:54.540  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.540  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f282257 added. We now have 3 listener(s)
08-23 18:36:54.540  1033  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.551  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.553  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.556  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.556  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.556  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.556  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.556  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d75144 added. We now have 10 listener(s)
08-23 18:36:54.556  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.556  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:54.557  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:54.557  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:36:54.557  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:36:54.557  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.557  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:36:54.560  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:36:54.561  1033  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.566  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 18:36:54.567  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 18:36:54.568  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:36:54.569  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.571  6980  7040 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 18:36:54.571  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:54.571  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:54.571  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:54.571  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.571  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.571  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.571  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.571  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a09398 removed from the list
08-23 18:36:54.571  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.572  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31e757f1 removed from the list
08-23 18:36:54.572  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:54.572  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.572  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.572  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.573  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.573  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.573  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.573  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31e757f1 not in the list
08-23 18:36:54.573  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.573  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.574  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.575  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:54.575  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:54.575  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.575  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.575  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d75144 removed from the list
08-2,3 18:36:54.575  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.575  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.575  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.575  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.575  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f282257 removed from the list
08-23 18:36:54.576  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.577  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21228cf3 added. We now have 2 listener(s)
08-23 18:36:54.577  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.579  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.580  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.580  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.580  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.580  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199a3db0 added. We now have 9 listener(s)
08-23 18:36:54.580  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.580  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:36:54.583  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:54.586  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:54.588  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.588  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:54.588  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.588  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69b43ae added. We now have 3 listener(s)
08-23 18:36:54.589  1033  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.590  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.592  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.593  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.593  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.593  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.593  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.593  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254f054f added. We now have 10 listener(s)
08-23 18:36:54.593  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.593  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:54.594  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 18:36:54.594  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 18:36:54.594  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.594  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 18:36:54.596  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 18:36:54.597  1033  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.600  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 18:36:54.601  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 18:36:54.602  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 18:36:54.602  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.604  6980  7040 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 18:36:54.605  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:54.605  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:54.605  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:54.605  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.605  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.605  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.605  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.605  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21228cf3 removed from the list
08-23 18:36:54.605  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.605  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199a3db0 removed from the list
08-23 18:36:54.605  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:54.605  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.606  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.606  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.606  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.606  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.606  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.606  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@199a3db0 not in the list
08-23 18:36:54.606  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.606  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.607  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.607  6980  7040 D BluetoothLeScanner: could not find callback wrapper
08-23 18:36:54.607  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 18:36:54.607  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.607  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.608  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254f054f removed from the list
08-23 18:36:54.608  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.608  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.608  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.608  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.608  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69b43ae removed from the list
08-23 18:36:54.608  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.608  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275becba added. We now have 2 listener(s)
,08-23 18:36:54.608  1033  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.610  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.610  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.610  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.610  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.610  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1620a76b added. We now have 9 listener(s)
08-23 18:36:54.610  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.611  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 18:36:54.613  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 18:36:54.615  6980  7040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 18:36:54.616  6980  7040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 18:36:54.617  6980  7040 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 18:36:54.617  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 18:36:54.617  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13ad1f61 added. We now have 3 listener(s)
08-23 18:36:54.617  1033  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 18:36:54.618  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.620  6980  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 18:36:54.620  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 18:36:54.620  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 18:36:54.620  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 18:36:54.620  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 18:36:54.620  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64c1a86 added. We now have 10 listener(s)
08-23 18:36:54.620  6980  7040 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 18:36:54.621  6980  7040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 18:36:54.621  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:54.621  6980  7040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 18:36:54.621  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.621  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.621  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 18:36:54.621  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.621  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275becba removed from the list
08-23 18:36:54.622  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.622  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1620a76b removed from the list
08-23 18:36:54.622  6980  7040 D io.jxcore.node.ConnectivityMonitor: stop
08-23 18:36:54.622  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.622  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.622  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.623  6980  7040 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1620a76b not in the list
08-23 18:36:54.623  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.623  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 18:36:54.623  6980  7040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64c1a86 removed from the list
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 18:36:54.623  6980  7040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 18:36:54.623  6980  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 18:36:54.623  6980  7040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 18:36:54.623  6980  7040 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13ad1f61 removed from the list
08-23 18:36:54.624  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 18:36:54.624  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 18:36:54.624  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 18:36:54.625  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 18:36:54.625  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 18:36:54.625  6980  7040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 18:36:54.631  8393  8393 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-23 18:36:54.632  6980  8444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 925, name: My test thread name)
08-23 18:36:54.632  6980  8444 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 925, thread name: My test thread name)
08-23 18:36:54.632  6980  8444 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 925, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 18:36:54.634  6980  8445 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 927, name: My test thread name)
08-23 18:36:54.634  6980  8445 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 927, thread name: My test thread name)
08-23 18:36:54.634  6980  8445 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 927, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 18:36:54.635  6980  7040 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-23 18:36:54.635  6980  7040 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 18:36:54.636  6980  7040 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-23 18:36:54.636  6980  7040 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-23 18:36:54.636  6980  7040 D com.test.thalitest.ThaliTestRunner: Total duration: 23152 ms
08-23 18:36:54.637  6980  7040 I jxcore-log: Total number of executed tests:  80
08-23 18:36:54.637  6980  7040 I jxcore-log: 
08-23 18:36:54.637  6980  7040 I jxcore-log: Number of passed tests:  80
08-23 18:36:54.637  6980  7040 I jxcore-log: 
08-23 18:36:54.637  6980  7040 I jxcore-log: Number of failed tests:  0
08-23 18:36:54.637  6980  7040 I jxcore-log: 
08-23 18:36:54.637  6980  7040 I jxcore-log: Number of ignored tests:  0
08-23 18:36:54.637  6980  7040 I jxcore-log: 
08-23 18:36:54.637  6980  7040 I jxcore-log: Total duration:  23152
08-23 18:36:54.637  6980  7040 I jxcore-log: 
08-23 18:36:54.637  6980  7040 I jxcore-log: Is Android:  true
08-23 18:36:54.637  6980  7040 I jxcore-log: 
08-23 18:36:54.638  6980  7040 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 18:36:54.638  6980  7040 I jxcore-log: 
08-23 18:36:54.641  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.641  6980  7040 I jxcore-log: 
08-23 18:36:54.644  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.644  6980  7040 I jxcore-log: 
08-23 18:36:54.644  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.644  6980  7040 I jxcore-log: 
08-23 18:36:54.645  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.645  6980  7040 I jxcore-log: 
08-23 18:36:54.646  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.646  6980  7040 I jxcore-log: 
08-23 18:36:54.647  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.647  6980  7040 I jxcore-log: 
08-23 18:36:54.649  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:36:54.649  6980  7040 I jxcore-log: 
08-23 18:36:54.650  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:36:54.650  6980  7040 I jxcore-log: 
08-23 18:36:54.651  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.651  6980  7040 I jxcore-log: 
08-23 18:36:54.652  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.652  6980  7040 I jxcore-log: 
08-23 18:36:54.652  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 18:36:54.652  6980  7040 I jxcore-log: 
,08-23 18:36:54.653  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:36:54.653  6980  7040 I jxcore-log: 
08-23 18:36:54.654  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 18:36:54.654  6980  7040 I jxcore-log: 
08-23 18:36:54.655  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.655  6980  7040 I jxcore-log: 
08-23 18:36:54.655  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.655  6980  7040 I jxcore-log: 
08-23 18:36:54.656  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.656  6980  7040 I jxcore-log: 
08-23 18:36:54.656  6980  6980 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 18:36:54.657  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.657  6980  7040 I jxcore-log: 
08-23 18:36:54.657  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.657  6980  7040 I jxcore-log: 
08-23 18:36:54.658  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.658  6980  7040 I jxcore-log: 
08-23 18:36:54.658  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.658  6980  7040 I jxcore-log: 
08-23 18:36:54.659  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 18:36:54.659  6980  7040 I jxcore-log: 
08-23 18:36:54.659  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 18:36:54.659  6980  7040 I jxcore-log: 
08-23 18:36:54.660  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 18:36:54.660  6980  7040 I jxcore-log: 
08-23 18:36:54.661  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.661  6980  7040 I jxcore-log: 
08-23 18:36:54.661  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.661  6980  7040 I jxcore-log: 
08-23 18:36:54.662  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.662  6980  7040 I jxcore-log: 
08-23 18:36:54.662  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 18:36:54.662  6980  7040 I jxcore-log: 
08-23 18:36:54.663  6980  7040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName",:"f4:f2:6d:22:99:3e"}
08-23 18:36:54.663  6980  7040 I jxcore-log: 
08-23 18:36:54.697  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 18:36:54.698  8393  8454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 18:36:54.706  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:54.710  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:54.726  1033  8412 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-23 18:36:54.728  1033  8412 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-23 18:36:54.728  1033  8412 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 18:36:54.728  1033  8412 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-23 18:36:54.728  1033  8412 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-23 18:36:54.728  1033  8412 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 18:36:54.728  1033  8412 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-23 18:36:54.728  1033  8412 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-23 18:36:54.728  1033  8412 D DhcpStateMachine: RunningState
08-23 18:36:54.742  1033  1970 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8459 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-23 18:36:54.743  1033  1970 I ActivityManager: Killing 7478:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-23 18:36:54.871  8393  8453 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 18:36:54.978  8457  8457 D AndroidRuntime: 
08-23 18:36:54.978  8457  8457 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 18:36:54.981  8457  8457 D AndroidRuntime: CheckJNI is OFF
08-23 18:36:55.011  1033  1048 W libprocessgroup: failed to open /acct/uid_10093/pid_7478/cgroup.procs: No such file or directory
,08-23 18:36:55.051  8459  8459 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 18:36:55.082  8459  8459 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-23 18:36:55.118  8459  8459 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-23 18:36:55.118  8459  8459 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-23 18:36:55.119  8459  8459 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-23 18:36:55.119  8457  8457 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-23 18:36:55.120  8459  8459 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-23 18:36:55.120  8459  8459 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-23 18:36:55.122  8459  8459 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-23 18:36:55.127  8459  8459 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-23 18:36:55.129  1033  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-23 18:36:55.130  1033  1090 I ActivityManager: Killing 6980:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-23 18:36:55.136  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:55.141  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:55.168  8393  8453 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:55.168  8393  8453 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:55.185  1033  2013 I WindowState: WIN DEATH: Window{23163200 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 18:36:55.186  1033  1542 D WifiService: Client connection lost with reason: 4
08-23 18:36:55.191  1033  2013 D InputDispatcher: Window went away: Window{23163200 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 18:36:55.285  8393  8453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-23 18:36:55.346  1033  1090 I ActivityManager:   Force finishing activity ActivityRecord{34d75415 u0 com.test.thalitest/.MainActivity t6}
,08-23 18:36:55.389   338   347 E GBMv2   : DFP En is all cleared set to be enabled
,08-23 18:36:55.393  1033  1967 W ActivityManager: Spurious death for ProcessRecord{3b86dcc6 6980:com.test.thalitest/u0a118}, curProc for 6980: null
08-23 18:36:55.394  1033  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-23 18:36:55.395  8459  8459 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 18:36:55.398  8459  8459 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-23 18:36:55.401  1033  1122 I ActivityManager:   Force finishing activity ActivityRecord{34d75415 u0 com.test.thalitest/.MainActivity t6 f}
08-23 18:36:55.401  1033  1122 W ActivityManager: Duplicate finish request for ActivityRecord{34d75415 u0 com.test.thalitest/.MainActivity t6 f}
08-23 18:36:55.405  8459  8459 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-23 18:36:55.429  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-23 18:36:55.443  1033  1453 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 18:36:55.451  2504  2609 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 18:36:55.453  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 18:36:55.454  3825  3825 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 18:36:55.458  5043  5043 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 18:36:55.459  5043  5043 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 18:36:55.459  5043  5043 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 18:36:55.459  5043  5043 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 18:36:55.459  5043  5043 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 18:36:55.459  5043  5043 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 18:36:55.459  5043  5043 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-23 18:36:55.459  5043  5043 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:55.459  5043  5043 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:55.459  5043  5043 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:55.460  5043  5043 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:55.460  5043  5043 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:55.466  7917  7917 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 18:36:55.466  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 18:36:55.478  1033  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-23 18:36:55.497  5146  5146 I art     : Explicit concurrent mark sweep GC freed 8253(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 684us total 86.653ms
08-23 18:36:55.499  1033  1938 V SIM_STK : Menu title from STK is T-Mobile
,08-23 18:36:55.542  1033  1033 D administrator: Handling package changes for user 0
,08-23 18:36:55.549  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-23 18:36:55.553  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-23 18:36:55.554  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-23 18:36:55.563  7102  7102 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-23 18:36:55.568  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-23 18:36:55.569  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-23 18:36:55.569  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d2f80b3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 18:36:55.570  2032  2112 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-23 18:36:55.581  1033  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:55.581  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:55.582  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:55.582  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:55.582  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:55.583  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 18:36:55.584  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-23 18:36:55.584  1033  1543 D ConnectivityService: identical MTU - not setting
08-23 18:36:55.584  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-23 18:36:55.584  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-23 18:36:55.584  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 18:36:55.584  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:55.585  1033  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 18:36:55.586  1601  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-23 18:36:55.587  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-23 18:36:55.590  1941  2630 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-23 18:36:55.591  1941  2630 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33e28670 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 18:36:55.594  1601  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-23 18:36:55.594  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.602  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-23 18:36:55.603  1869  1869 D SplitUIService: removed split : 
08-23 18:36:55.603  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:55.604  8393  8454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-23 18:36:55.605  8393  8453 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-23 18:36:55.605  1601  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 18:36:55.605  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.609  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 18:36:55.609  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 18:36:55.619  1601  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-23 18:36:55.620  1601  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:36:55.621  1601  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 18:36:55.622  1601  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 18:36:55.622  1601  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 18:36:55.622  8393  8453 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-23 18:36:55.622  1601  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 18:36:55.623  8393  8453 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-23 18:36:55.624  8393  8453 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-23 18:36:55.623  1601  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 18:36:55.627  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.627  8393  8453 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-23 18:36:55.628  8393  8453 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-23 18:36:55.629  1903  1903 D ActionManagerService: notifyUserLog: 1000003
08-23 18:36:55.629  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-23 18:36:55.630  3825  5012 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-23 18:36:55.633  8393  8453 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-23 18:36:55.635  1601  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 18:36:55.635  1601  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 18:36:55.639  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:55.639  1601  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 18:36:55.640  1601  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 18:36:55.642  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 18:36:55.642  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-23 18:36:55.643  8393  8453 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-23 18:36:55.643  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-23 18:36:55.643  1601  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 18:36:55.643  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.647  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-23 18:36:55.647  1869  1869 I SplitUIService: split app #11
,08-23 18:36:55.651  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-23 18:36:55.652  3825  5007 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 18:36:55.654  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-23 18:36:55.654  3825  5012 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-23 18:36:55.656  1601  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:36:55.657  1601  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 18:36:55.657  1601  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 18:36:55.657  1601  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , display: false
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , animation: false }
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , display: false
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , animation: false }
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , display: false
08-23 18:36:55.657  2032  2032 I GBoardWebViewUtils: , animation: false }
08-23 18:36:55.659  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:55.661  1601  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 18:36:55.661  1601  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-23 18:36:55.663  1601  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 18:36:55.663  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.667  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-23 18:36:55.667  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 18:36:55.670  1601  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 18:36:55.670  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.672  1601  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 18:36:55.672  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.673  1033  1781 V SIM_STK : Menu title from STK is T-Mobile
08-23 18:36:55.673  1033  1781 V SIM_STK : Menu title from STK is T-Mobile
08-23 18:36:55.674  1601  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 18:36:55.674  1601  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-23 18:36:55.676  1601  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 18:36:55.676  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.678  2032  8511 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-23 18:36:55.679  1601  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 18:36:55.679  1601  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 18:36:55.682  1601  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 18:36:55.682  1601  1656 D KeyguardModel: createShortcutInfo...
08-23 18:36:55.684  1601  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 18:36:55.684  1601  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 18:36:55.685  1601  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 18:36:55.686  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 18:36:55.686  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-23 18:36:55.695  1601  1656 D KeyguardModel: createShortcutInfo...
,08-23 18:36:55.714  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:55.714  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 18:36:55.724  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-23 18:36:55.724  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 18:36:55.733  8459  8459 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 18:36:55.743  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:55.744  8393  8454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 18:36:55.749  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-23 18:36:55.751  2032  2047 I art     : Background sticky concurrent mark sweep GC freed 2772(151KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 9.897ms total 14.811ms
08-23 18:36:55.762  1033  2012 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-23 18:36:55.763  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 18:36:55.763  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 18:36:55.763  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 18:36:55.763  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 18:36:55.763  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 18:36:55.763  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 18:36:55.764  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 18:36:55.764  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 18:36:55.764  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 18:36:55.764  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 18:36:55.764  7917  7917 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 18:36:55.765  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-23 18:36:55.766  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:55.780  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:55.781  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 18:36:55.781  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 18:36:55.781  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 18:36:55.783  1033  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-23 18:36:55.785  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:55.785  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:55.785  8459  8459 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 18:36:55.787  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 18:36:55.790  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 18:36:55.790  7102  7102 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 18:36:55.790  7102  7102 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 18:36:55.790  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 18:36:55.791  7102  7102 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 18:36:55.791  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-23 18:36:55.791  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 18:36:55.791  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 18:36:55.791  7102  7102 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 18:36:55.791  7102  7102 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-23 18:36:55.791  7102  7102 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-23 18:36:55.794  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:55.794  8393  8454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 18:36:55.798  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:55.802  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:55.807  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:55.809  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:55.809  8459  8459 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 18:36:55.811  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:55.812  8393  8454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 18:36:55.817  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:55.823  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:55.835  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:55.835  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:55.836  8459  8459 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 18:36:55.839  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:55.840  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-23 18:36:55.840  8393  8454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 18:36:55.845  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:55.848  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:55.849  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 18:36:55.851  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 18:36:55.852  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 18:36:55.853  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 18:36:55.854  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:55.860  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:55.862  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:55.862  8459  8459 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 18:36:55.869  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-23 18:36:55.869  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:55.870  1033  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b2ece15 u0 com.lge.launcher2/.Launcher t5} time:221250
08-23 18:36:55.875  2032  2208 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 18:36:55.875  2032  2208 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-23 18:36:55.881  1033  1122 I art     : Explicit concurrent mark sweep GC freed 84812(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.864ms total 313.146ms
08-23 18:36:55.884  1033  1046 I art     : WaitForGcToComplete blocked for 16.429ms for cause HeapTrim
08-23 18:36:55.885  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-23 18:36:55.885  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 18:36:55.885  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:55.888  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:55.890  8393  8454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 18:36:55.894  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-23 18:36:55.898  2631  2631 D [Concierge]Service: onStartCommand(). Type : 8
08-23 18:36:55.898  2631  2631 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-23 18:36:55.899  2631  2631 D [Concierge]Service: Update widget ID : 11
08-23 18:36:55.900  2032  2032 D [Concierge]WidgetView: change position of spinner
08-23 18:36:55.901  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 18:36:55.907  2631  2631 D [Concierge]Service: onStartCommand(). Type : 0
08-23 18:36:55.908  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1471970215908
,08-23 18:36:55.916  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:55.917  8457  8457 D AndroidRuntime: Shutting down VM
08-23 18:36:55.934  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 440742046
08-23 18:36:55.935  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 18:36:55.935  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 18:36:55.937  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@17db4a7a
08-23 18:36:55.937  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-23 18:36:55.943  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 18:36:55.943  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:55.949  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 18:36:55.949  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:55.950  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 18:36:55.950  8459  8459 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 18:36:55.951  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 18:36:55.951  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 18:36:55.955  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471970023053, New one : 1471970215908
08-23 18:36:55.955  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-23 18:36:55.955  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 18:36:55.955  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:55.957  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-23 18:36:55.958  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:55.958  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 18:36:55.960  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-23 18:36:55.961  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,08-23 18:36:55.962  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 18:36:55.964  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:55.964  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 18:36:55.981  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:36:55.986  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-23 18:36:55.990  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:55.993  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:55.998  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:55.999  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 18:36:56.003  8459  8459 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 18:36:56.005  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:56.010  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:56.012  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 18:36:56.015  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:56.019  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:56.020  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:56.020  8459  8459 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 18:36:56.023  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 18:36:56.023  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:56.026  8346  8346 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-23 18:36:56.026  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 18:36:56.030  8346  8346 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:56.030  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-23 18:36:56.032  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:56.033  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 18:36:56.036  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:56.044  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:56.044  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:56.045  8459  8459 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-23 18:36:56.045  8459  8459 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 18:36:56.045  8459  8459 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 18:36:56.048  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:56.051  8346  8346 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-23 18:36:56.051  8346  8346 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-23 18:36:56.054  7102  7102 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 18:36:56.055  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@161d7437 time:221435
,08-23 18:36:56.058  7102  7102 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 18:36:56.062  8459  8459 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 18:36:56.062  8459  8459 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 18:36:56.062  8459  8459 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-23 18:36:56.063  8459  8459 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 18:36:56.063  8459  8459 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 18:36:56.067  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 18:36:56.070  8459  8459 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-23 18:36:56.071  8459  8459 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-23 18:36:56.071  8459  8459 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-23 18:36:56.090  8459  8459 D LgDataFeature: LgDataFeature() Constructor: none
08-23 18:36:56.090  8459  8459 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 18:36:56.094  8459  8459 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-23 18:36:56.094  8459  8459 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-23 18:36:56.094  8459  8459 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-23 18:36:56.094  8459  8459 V SoundPool: doLoad: loading sample sampleID=1
08-23 18:36:56.095  8459  8459 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 18:36:56.095  8459  8523 V SoundPool: Start decode
08-23 18:36:56.095  8459  8523 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-23 18:36:56.096   318  4487 V MediaPlayerService: decode(22, 10857164, 17813)
08-23 18:36:56.096   318  4487 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-23 18:36:56.096   318  4487 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-23 18:36:56.096   318  4487 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-23 18:36:56.096   318  4487 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-23 18:36:56.096   318  4487 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-23 18:36:56.096   318  4487 V MediaPlayerService: player type = 3
08-23 18:36:56.096   318  4487 V AwesomePlayer: AwesomePlayer create()
08-23 18:36:56.096   318  4487 V AwesomePlayer: reset_l() 
08-23 18:36:56.096   318  4487 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:56.096   318  4487 V AwesomePlayer: setAudioSink() 
08-23 18:36:56.096   318  4487 V AwesomePlayer: reset_l() 
08-23 18:36:56.096   318  4487 V AudioCache: notify(0xb5474bc0, 8, 0, 0)
08-23 18:36:56.096   318  4487 V AudioCache: ignored
08-23 18:36:56.096   318  4487 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:56.096   318  4487 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-23 18:36:56.096   318  4487 V AwesomePlayer: setDataSource_l dataSource
08-23 18:36:56.096   318  4487 V LGParserOSAL: SniffLGParser start
08-23 18:36:56.096   318  4487 V LGParserOSAL: MainType:5, SubType=0
08-23 18:36:56.096   318  4487 V LGParserOSAL: #### check Mime : application/ogg
08-23 18:36:56.096   318  4487 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-23 18:36:56.096   318  4487 E MediaExtractor: Use LGExtractor :application/ogg 
08-23 18:36:56.097  7942  7942 D UEI.SmartControl: QS Service created
08-23 18:36:56.100  8459  8459 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-23 18:36:56.101  8459  8459 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-23 18:36:56.101  8459  8459 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-23 18:36:56.107  8459  8459 V LGMDMManager: Create singleton instance
08-23 18:36:56.115  7942  7942 I UEI.SmartControl: Service initServices...
08-23 18:36:56.115  7942  7942 D UEI.SmartControl: QS start get config
,08-23 18:36:56.140   318  4487 V LGParserOSAL: supported mime: application/ogg
08-23 18:36:56.140   318  4487 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-23 18:36:56.140   318  4487 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-23 18:36:56.140   318  4487 V AwesomePlayer: mBitrate = -1 bits/sec
08-23 18:36:56.140   318  4487 V AwesomePlayer: AudioTrack Setting
08-23 18:36:56.140   318  4487 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-23 18:36:56.140   318  4487 V AwesomePlayer: setAudioSource() 
08-23 18:36:56.140   318  4487 V MediaPlayerService: prepare
08-23 18:36:56.141   318  4487 V AwesomePlayer: prepareAsync_l() 
08-23 18:36:56.141   318  4487 V MediaPlayerService: wait for prepare
08-23 18:36:56.141   318  8524 V AwesomePlayer: onPrepareAsyncEvent() 
08-23 18:36:56.141   318  8524 V AwesomePlayer: initAudioDecoder() 
08-23 18:36:56.141   318  8524 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,08-23 18:36:56.142   318  8524 V AudioSystem: isOffloadSupported()
08-23 18:36:56.142   318  8524 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 18:36:56.142   318  8524 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 18:36:56.142   318  8524 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 18:36:56.142   318  8524 V AwesomePlayer: getUseOffload() = 0 
08-23 18:36:56.142   318  8524 V OMXCodec: OMXCodec::Create
08-23 18:36:56.142   318  8524 V OMXCodec: findMatchingCodecs()
08-23 18:36:56.142   318  8524 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-23 18:36:56.142   318  8524 V OMXCodec: matchingCodecs.size()=1
08-23 18:36:56.142   318  8524 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-23 18:36:56.143   318  8524 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-23 18:36:56.143   318  8524 V LGCodecAdapter: LG Codec Adapter start
08-23 18:36:56.143   318  8524 V OMXCodec: OMXCodec Createtor
08-23 18:36:56.143   318  8524 V OMXCodec: setComponentRole
08-23 18:36:56.143   318  8524 V OMXCodec: configureCodec protected=0
08-23 18:36:56.143   318  8524 V LGCodecAdapter: called getLGCodecSpecificData
08-23 18:36:56.143   318  8524 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-23 18:36:56.143   318  8524 V LGCodecOSAL: Called LGconfigureCodecMETA
08-23 18:36:56.143   318  8524 V LGCodecOSAL: Called LGconfigureCodecMSG
08-23 18:36:56.143   318  8524 V LGCodecOSAL: Not support LGCodec
08-23 18:36:56.143   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 18:36:56.143   318  8524 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-23 18:36:56.143   318  8524 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-23 18:36:56.143   318  8524 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-23 18:36:56.144   318  8524 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 18:36:56.144   318  8524 V AudioSystem: isOffloadSupported()
08-23 18:36:56.144   318  8524 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 18:36:56.144   318  8524 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-23 18:36:56.144   318  8524 V OMXCodec: init()
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-23 18:36:56.144   318  8524 V OMXCodec: allocateBuffers
08-23 18:36:56.144   318  8524 V OMXCodec: allocateBuffersOnPort portIndex=0
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-23 18:36:56.144   318  8524 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decod,er] allocated buffer 0xb54f7bf0 on output port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-23 18:36:56.144   318  8524 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-23 18:36:56.144   318  8524 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 18:36:56.144   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 18:36:56.144   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 18:36:56.144   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-23 18:36:56.144   318  8524 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 18:36:56.144   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-23 18:36:56.144   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-23 18:36:56.144   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-23 18:36:56.144   318  8524 V OMXCodec: init() mAsyncCompletion wait free! 
08-23 18:36:56.144   318  8524 V AwesomePlayer: finishAsyncPrepare_l() 
08-23 18:36:56.144   318  8524 V AudioCache: notify(0xb5474bc0, 5, 0, 0)
08-23 18:36:56.144   318  8524 V AudioCache: ignored
08-23 18:36:56.144   318  8524 V AudioCache: notify(0xb5474bc0, 1, 0, 0)
08-23 18:36:56.144   318  8524 V AudioCache: prepared
08-23 18:36:56.144   318  4487 V AudioCache: wait - success
08-23 18:36:56.144   318  4487 V MediaPlayerService: start
08-23 18:36:56.144   318  4487 V AwesomePlayer: play_l() 
08-23 18:36:56.144   318  4487 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-23 18:36:56.144   318  4487 V AwesomePlayer: createAudioPlayer_l
08-23 18:36:56.144   318  4487 V AwesomePlayer: seekAudioIfNecessary_l() 
08-23 18:36:56.144   318  4487 V AwesomePlayer: startAudioPlayer_l() 
08-23 18:36:56.144   318  4487 D AudioPlayer: start of Playback, useOffload 0
08-23 18:36:56.144   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 18:36:56.145   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1,
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-23 18:36:56.147   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1,
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-23 18:36:56.148   318  8526 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-23 18:36:56.148   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-23 18:36:56.149   318  4487 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-23 18:36:56.149   318  4487 V AudioCache: notify(0xb5474bc0, 6, 0, 0)
08-23 18:36:56.149   318  4487 V AudioCache: ignored
08-23 18:36:56.149   318  4487 V MediaPlayerService: wait for playback complete
08-23 18:36:56.150   318  8527 V AudioCache: write(0xb0408000, 4096)
,08-23 18:36:56.150   318  8527 V AudioCache: memcpy(0xac300000, 0xb0408000, 4096)
08-23 18:36:56.151   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.151   318  8527 V AudioCache: memcpy(0xac301000, 0xb0408000, 4096)
08-23 18:36:56.152   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.152   318  8527 V AudioCache: memcpy(0xac302000, 0xb0408000, 4096)
,08-23 18:36:56.153   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.153   318  8527 V AudioCache: memcpy(0xac303000, 0xb0408000, 4096)
08-23 18:36:56.153   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.153   318  8527 V AudioCache: memcpy(0xac304000, 0xb0408000, 4096)
08-23 18:36:56.154   318  8527 V AudioCache: write(0xb0408000, 4096)
,08-23 18:36:56.154   318  8527 V AudioCache: memcpy(0xac305000, 0xb0408000, 4096)
08-23 18:36:56.154   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.154   318  8527 V AudioCache: memcpy(0xac306000, 0xb0408000, 4096)
08-23 18:36:56.155   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.155   318  8527 V AudioCache: memcpy(0xac307000, 0xb0408000, 4096)
,08-23 18:36:56.156   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.156   318  8527 V AudioCache: memcpy(0xac308000, 0xb0408000, 4096)
08-23 18:36:56.156   318  8527 V AudioCache: write(0xb0408000, 4096)
,08-23 18:36:56.156   318  8527 V AudioCache: memcpy(0xac309000, 0xb0408000, 4096)
,08-23 18:36:56.157   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.157   318  8527 V AudioCache: memcpy(0xac30a000, 0xb0408000, 4096)
08-23 18:36:56.158   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.158   318  8527 V AudioCache: memcpy(0xac30b000, 0xb0408000, 4096)
08-23 18:36:56.158   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.158   318  8527 V AudioCache: memcpy(0xac30c000, 0xb0408000, 4096)
08-23 18:36:56.159   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.159   318  8527 V AudioCache: memcpy(0xac30d000, 0xb0408000, 4096)
08-23 18:36:56.160   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.160   318  8527 V AudioCache: memcpy(0xac30e000, 0xb0408000, 4096)
08-23 18:36:56.160   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.160   318  8527 V AudioCache: memcpy(0xac30f000, 0xb0408000, 4096)
08-23 18:36:56.161   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.161   318  8527 V AudioCache: memcpy(0xac310000, 0xb0408000, 4096)
08-23 18:36:56.161   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.161   318  8527 V AudioCache: memcpy(0xac311000, 0xb0408000, 4096)
08-23 18:36:56.162   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.162   318  8527 V AudioCache: memcpy(0xac312000, 0xb0408000, 4096)
08-23 18:36:56.163   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.163   318  8527 V AudioCache: memcpy(0xac313000, 0xb0408000, 4096)
08-23 18:36:56.163   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.163   318  8527 V AudioCache: memcpy(0xac314000, 0xb0408000, 4096)
08-23 18:36:56.164   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.164   318  8527 V AudioCache: memcpy(0xac315000, 0xb0408000, 4096)
08-23 18:36:56.164   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.164   318  8527 V AudioCache: memcpy(0xac316000, 0xb0408000, 4096)
08-23 18:36:56.165   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.165   318  8527 V AudioCache: memcpy(0xac317000, 0xb0408000, 4096)
08-23 18:36:56.165   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.165   318  8527 V AudioCache: memcpy(0xac318000, 0xb0408000, 4096)
08-23 18:36:56.166   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.166   318  8527 V AudioCache: memcpy(0xac319000, 0xb0408000, 4096)
08-23 18:36:56.166   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.166   318  8527 V AudioCache: memcpy(0xac31a000, 0xb0408000, 4096)
08-23 18:36:56.167   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.167   318  8527 V AudioCache: memcpy(0xac31b000, 0xb0408000, 4096)
08-23 18:36:56.168   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.168   318  8527 V AudioCache: memcpy(0xac31c000, 0xb0408000, 4096)
08-23 18:36:56.168   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.168   318  8527 V AudioCache: memcpy(0xac31d000, 0xb0408000, 4096)
08-23 18:36:56.169   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.169   318  8527 V AudioCache: memcpy(0xac31e000, 0xb0408000, 4096)
08-23 18:36:56.169   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.169   318  8527 V AudioCache: memcpy(0xac31f000, 0xb0408000, 4096)
08-23 18:36:56.170   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.170   318  8527 V AudioCache: memcpy(0xac320000, 0xb0408000, 4096)
08-23 18:36:56.177  8459  8459 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-23 18:36:56.178  8459  8459 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting,
08-23 18:36:56.179   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.179   318  8527 V AudioCache: memcpy(0xac321000, 0xb0408000, 4096)
08-23 18:36:56.179   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.179   318  8527 V AudioCache: memcpy(0xac322000, 0xb0408000, 4096)
08-23 18:36:56.180   318  8527 V AudioCache: write(0xb0408000, 4096)
,08-23 18:36:56.180   318  8527 V AudioCache: memcpy(0xac323000, 0xb0408000, 4096)
,08-23 18:36:56.181   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.181   318  8527 V AudioCache: memcpy(0xac324000, 0xb0408000, 4096)
08-23 18:36:56.181   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.181   318  8527 V AudioCache: memcpy(0xac325000, 0xb0408000, 4096)
08-23 18:36:56.181  1033  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8529 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-23 18:36:56.182   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.182   318  8527 V AudioCache: memcpy(0xac326000, 0xb0408000, 4096)
08-23 18:36:56.183  8459  8459 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4824
08-23 18:36:56.183   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.183   318  8527 V AudioCache: memcpy(0xac327000, 0xb0408000, 4096)
08-23 18:36:56.184   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.184   318  8527 V AudioCache: memcpy(0xac328000, 0xb0408000, 4096)
08-23 18:36:56.184   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.184   318  8527 V AudioCache: memcpy(0xac329000, 0xb0408000, 4096)
08-23 18:36:56.185   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.185   318  8527 V AudioCache: memcpy(0xac32a000, 0xb0408000, 4096)
08-23 18:36:56.185   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.185   318  8527 V AudioCache: memcpy(0xac32b000, 0xb0408000, 4096)
08-23 18:36:56.186   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.186   318  8527 V AudioCache: memcpy(0xac32c000, 0xb0408000, 4096)
08-23 18:36:56.186   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.186   318  8527 V AudioCache: memcpy(0xac32d000, 0xb0408000, 4096)
08-23 18:36:56.186  8393  8393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 18:36:56.186   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.187   318  8527 V AudioCache: memcpy(0xac32e000, 0xb0408000, 4096)
08-23 18:36:56.187   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.187   318  8527 V AudioCache: memcpy(0xac32f000, 0xb0408000, 4096)
08-23 18:36:56.187   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.187   318  8527 V AudioCache: memcpy(0xac330000, 0xb0408000, 4096)
08-23 18:36:56.188   318  8527 V AudioCache: write(0xb0408000, 4096)
08-23 18:36:56.188   318  8527 V AudioCache: memcpy(0xac331000, 0xb0408000, 4096)
08-23 18:36:56.188   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-23 18:36:56.188   318  8527 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-23 18:36:56.188   318  8527 V AwesomePlayer: postAudioEOS() 
08-23 18:36:56.188   318  8527 V AudioCache: write(0xb0408000, 280)
08-23 18:36:56.188   318  8527 V AudioCache: memcpy(0xac332000, 0xb0408000, 280)
08-23 18:36:56.188  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 18:36:56.192   318  8524 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-23 18:36:56.192   318  8524 V AwesomePlayer: onStreamDone
08-23 18:36:56.192   318  8524 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-23 18:36:56.192   318  8524 V AudioCache: notify(0xb5474bc0, 2, 0, 0)
08-23 18:36:56.192   318  8524 V AudioCache: playback complete
08-23 18:36:56.192   318  8524 V AwesomePlayer: pause_l() 
08-23 18:36:56.192   318  8524 V AudioCache: notify(0xb5474bc0, 7, 0, 0)
08-23 18:36:56.192   318  8524 V AudioCache: ignored
08-23 18:36:56.192   318  8524 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:56.192   318  4487 V AudioCache: wait - success
08-23 18:36:56.192   318  4487 V MediaPlayerS,ervice: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-23 18:36:56.192   318  8524 D AudioPlayer: Pause Playback at 1068125
,08-23 18:36:56.194   318  4487 V AwesomePlayer: reset_l() 
08-23 18:36:56.194   318  4487 V AudioCache: notify(0xb5474bc0, 8, 0, 0)
08-23 18:36:56.194   318  4487 V AudioCache: ignored
08-23 18:36:56.194   318  4487 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:56.194   318  4487 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-23 18:36:56.194   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-23 18:36:56.194   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-23 18:36:56.194   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-23 18:36:56.194   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-23 18:36:56.194   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 18:36:56.194   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 18:36:56.194   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-23 18:36:56.194   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-23 18:36:56.194   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-23 18:36:56.195   318  8526 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-23 18:36:56.197  2164  2164 I ConfigService: onCreate
08-23 18:36:56.198  2164  2164 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 18:36:56.199   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-23 18:36:56.199   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-23 18:36:56.199   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-23 18:36:56.199   318  4487 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-23 18:36:56.200   318  4487 D AudioPlayer: AudioPlayer releasing audio source
08-23 18:36:56.200   318  4487 D AudioPlayer: AudioPlayer done releasing audio source
08-23 18:36:56.200   318  4487 V AwesomePlayer: reset_l() 
08-23 18:36:56.200   318  4487 V Awes,omePlayer: cancelPlayerEvents
08-23 18:36:56.200   318  4487 V AwesomePlayer: ~AwesomePlayer call
08-23 18:36:56.200   318  4487 V AwesomePlayer: reset_l() 
08-23 18:36:56.200   318  4487 V AwesomePlayer: cancelPlayerEvents
08-23 18:36:56.200  8459  8523 V SoundPool: close(31)
08-23 18:36:56.200  8459  8523 V SoundPool: pointer = 0x9fff4000, size = 205080, sampleRate = 48000, numChannels = 2
08-23 18:36:56.201  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 18:36:56.213  2164  2164 I ConfigService: onBind returning update interface
,08-23 18:36:56.215  2164  2164 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 18:36:56.215  2164  2164 I ConfigService: onBind returning config service
08-23 18:36:56.258  2164  2164 I ConfigService: onDestroy
,08-23 18:36:56.260  1817  8549 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 18:36:56.261  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-23 18:36:56.300  2032  2926 I GBoardtInterface: onReloaded()
,08-23 18:36:56.302  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-23 18:36:56.303  3825  3841 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 18:36:56.306  3825  5007 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 18:36:56.313  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-23 18:36:56.315  3825  5012 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 18:36:56.315  3825  5012 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-23 18:36:56.318  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-23 18:36:56.319  3825  5012 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 18:36:56.319  3825  5012 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 18:36:56.319  3825  5012 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-23 18:36:56.319  3825  5012 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-23 18:36:56.320  3825  3841 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 18:36:56.323  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-23 18:36:56.323  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-23 18:36:56.325  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-23 18:36:56.325  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 18:36:56.327  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
,08-23 18:36:56.327  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 18:36:56.356  6023  8554 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-23 18:36:56.359  1817  8556 I PeopleContactsSync: CP2 sync disabled
08-23 18:36:56.366  1817  5322 I Icing   : doRemovePackageData com.test.thalitest
08-23 18:36:56.376  1817  8555 W GmsApplication: Using Auth Proxy for data requests.
,08-23 18:36:56.379  1817  8555 W GmsApplication: Using Auth Proxy for data requests.
08-23 18:36:56.400  7307  7307 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-23 18:36:56.411  2370  8558 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 18:36:56.439  1033  1977 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8560 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-23 18:36:56.454  7942  7942 E UEI.SmartControl: unzip: java.io.IOException: write failed: EBADF (Bad file number)
08-23 18:36:56.455  7942  7942 I UEI.SmartControl: Specific region DB is not found, use default...
,08-23 18:36:56.465  2370  8558 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
--------- beginning of crash
08-23 18:36:56.466  2370  8558 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-23 18:36:56.466  2370  8558 E AndroidRuntime: Process: android.process.acore, PID: 2370
08-23 18:36:56.466  2370  8558 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailStatusTable.delete(VoicemailStatusTable.java:100)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.466  2370  8558 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: Can't write: system_app_crash
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:36:56.4,69  1033  8577 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 18:36:56.469  1033  8577 E DropBoxManagerService: 	... 5 more
08-23 18:36:56.469  2164  2195 I art     : Explicit concurrent mark sweep GC freed 6286(375KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.131ms total 26.286ms
08-23 18:36:56.469  2370  8558 I Process : Sending signal. PID: 2370 SIG: 9
,08-23 18:36:56.505  7942  7942 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
,08-23 18:36:56.508  7942  7942 I UEI.SmartControl: Supports setup maps: true
08-23 18:36:56.508  7942  7942 W System.err: java.lang.NullPointerException: Attempt to get length of null array
08-23 18:36:56.509  7942  7942 W System.err: 	at com.uei.control.core.ab.b(Unknown Source)
08-23 18:36:56.509  7942  7942 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-23 18:36:56.509  7942  7942 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-23 18:36:56.509  7942  7942 W System.err: 	at com.uei.control.Service.a(Unknown Source)
08-23 18:36:56.509  7942  7942 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 18:36:56.509  7942  7942 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 18:36:56.509  7942  7942 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 18:36:56.509  7942  7942 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 18:36:56.509  7942  7942 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.509  7942  7942 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.509  7942  7942 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.509  7942  7942 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.509  7942  7942 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.509  7942  7942 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.509  7942  7942 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.510  8560  8560 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: ,	at com.uei.control.core.ab.a(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.510  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.511  8560  8560 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 18:36:56.511  7942  7942 I UEI.SmartControl: ### init IR Blaster...
08-23 18:36:56.511  8560  8560 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 18:36:56.512  8560  8560 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 18:36:56.521  7942  7942 D serial_port: Configuring serial port
08-23 18:36:56.521  7942  7942 E UEI.SmartControl: UEIBLaster setting for 616
08-23 18:36:56.521  7942  7942 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 18:36:56.521  7942  7942 I UEI.SmartControl: configuring settings for MAXQ616
08-23 18:36:56.521  7942  7942 I UEI.SmartControl: Get version...
,08-23 18:36:56.538  7942  8580 D UEI.SmartControl: serial port data available: 21
,08-23 18:36:56.552  8560  8560 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.552  8560  8560 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.552  8560  8560 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:36:56.552  8560  8560 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:36:56.552  8560  8560 W System.err: 	at a,ndroid.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-23 18:36:56.552  8560  8560 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-23 18:36:56.552  8560  8560 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:36:56.553  8560  8560 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.553  8560  8560 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.553  8560  8560 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.553  8560  8560 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.553  8560  8560 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.553  8560  8560 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.554  1033  1574 I ActivityManager: Process android.process.acore (pid 2370) has died
08-23 18:36:56.554  1033  1574 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
08-23 18:36:56.555  1033  1574 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
,08-23 18:36:56.564  7942  7942 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-23 18:36:56.564  7942  7942 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-23 18:36:56.564  7942  7942 I UEI.SmartControl: QS saving settings...
08-23 18:36:56.565  7942  7942 W FileUtils: Failed to chmod(/data/data/com.uei.lg.quicksetsdk.maxq616/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-23 18:36:56.565  7942  7942 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-23 18:36:56.565  7942  7942 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,08-23 18:36:56.565  7942  7942 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:36:56.565  7942  7942 W System.err: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-23 18:36:56.565  7942  7942 W System.err: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-23 18:36:56.565  7942  7942 W System.err: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-23 18:36:56.565  7942  7942 W System.err: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-23 18:36:56.565  7942  7942 W System.err: 	at com.uei.control.core.a.a(Unknown Source)
08-23 18:36:56.565  7942  7942 W System.err: 	at com.uei.control.core.a.<init>(Unknown Source)
08-23 18:36:56.565  7942  7942 W System.err: 	at com.uei.control.Service.a(Unknown Source)
08-23 18:36:56.566  7942  7942 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 18:36:56.566  7942  7942 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 18:36:56.566  7942  7942 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 18:36:56.566  7942  7942 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 18:36:56.566  7942  7942 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.566  7942  7942 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.566  7942  7942 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.566  7942  7942 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.566  7942  7942 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.566  7942  7942 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.566  7942  7942 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.566  7942  7942 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:36:56.566  7942  7942 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 18:36:56.566  7942  7942 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:36:56.566  7942  7942 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 18:36:56.566  7942  7942 W System.err: 	... 19 more
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366),
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	... 19 more
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:36:56.567  ,7942  7942 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 18:36:56.567  7942  7942 E UEI.SmartControl: 	... 19 more
08-23 18:36:56.567  7942  7942 D UEI.SmartControl: IR Blaster version: 25672567
08-23 18:36:56.568  1817  8551 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 18:36:56.569  1817  8551 E DriveAsyncService: disk I/O error (code 3850)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.569  1817  8551 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.569  8560  8560 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.569  8560  8560 D AndroidRuntime: Shutting down VM
08-23 18:36:56.570  8560  8560 E AndroidRuntime: FATAL EXCEPTION: main
08-23 18:36:56.570  8560  8560 E AndroidRuntime: Process: com.lge.email, PID: 8560
08-23 18:36:56.570  8560  8560 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-23 18:36:56.570  8560  8560 E AndroidRuntime: 	... 11 more
08-23 18:36:56.573  8560  8560 I Process : Sending signal. PID: 8560 SIG: 9
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: Can't write: system_app_crash
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 18:36:56.579  1033  8582 E DropBoxManagerService: 	... 5 more
08-23 18:36:56.583  7942  8580 D UEI.SmartControl: serial port data available: 4
,08-23 18:36:56.590  5043  5074 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: Error inserting f004=20 f005=2370 f002=1471970216481 f003= f006=-1
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-23 18:36:56.592  5043  5074 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-23 18:36:56.612  7942  8584 I UEI.SmartControl: Device manager: loading config....
08-23 18:36:56.614  7942  7942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 

```
