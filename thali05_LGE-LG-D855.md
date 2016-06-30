#### Test 757892682551a10_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
06-30 13:55:03.399  2181  2181 I ConfigService: onDestroy
,06-30 13:55:17.756  6937  6937 D AndroidRuntime: 
06-30 13:55:17.756  6937  6937 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:55:17.760  6937  6937 D AndroidRuntime: CheckJNI is OFF
06-30 13:55:17.887  6937  6937 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 13:55:17.893  1036  2050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:55:17.903  1941  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
06-30 13:55:17.906  1036  2050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
06-30 13:55:17.908  1036  2050 D ActivityManager: setTaskToReturnTo : TaskRecord{35d1eb77 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 13:55:17.908  1036  2050 D ActivityManager: setTaskToReturnTo : TaskRecord{35d1eb77 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 13:55:17.909  1036  2050 D WindowStateEx: AppWindowTokenEx init.. 
06-30 13:55:17.909   345   363 E GBMv2   : DFP En is all cleared set to be enabled
06-30 13:55:17.948  1036  2050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6956 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:55:17.950  6937  6937 D AndroidRuntime: Shutting down VM
06-30 13:55:18.005  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
06-30 13:55:18.005  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f15eb71 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-30 13:55:18.006  1941  2566 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
06-30 13:55:18.006  1941  2566 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3477dd56 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-30 13:55:18.087  6956  6956 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,06-30 13:55:18.189  6956  6956 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,06-30 13:55:18.199  6956  6956 I LibraryLoader: Loading: webviewchromium
06-30 13:55:18.203  6956  6956 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3483-3488)
,06-30 13:55:18.204  6956  6956 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:55:18.225  6956  6956 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {197f5747}
,06-30 13:55:18.227  6956  6956 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 13:55:18.227  6956  6956 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:55:18.238  6956  6956 I BrowserStartupController: Initializing chromium process, renderers=0
,06-30 13:55:18.239  6956  6956 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:55:18.251  6956  6956 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
06-30 13:55:18.252  6956  6956 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
06-30 13:55:18.252  6956  6956 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,06-30 13:55:18.253   322  1386 V AudioPolicyService: registerClient() client 0xb558a680, uid 10118
06-30 13:55:18.258  1036  1118 D BluetoothManagerService: Message: 20
06-30 13:55:18.258  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21969449:true
06-30 13:55:18.269  6956  6956 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:55:18.269  6956  6956 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:55:18.269  6956  6956 I Adreno-EGL: Build Date: 12/12/14 금
06-30 13:55:18.269  6956  6956 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 13:55:18.269  6956  6956 I Adreno-EGL: Remote Branch: 
06-30 13:55:18.269  6956  6956 I Adreno-EGL: Local Patches: 
06-30 13:55:18.269  6956  6956 I Adreno-EGL: Reconstruct Branch: 
,06-30 13:55:18.356  6956  6992 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,06-30 13:55:18.361  6956  6956 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
06-30 13:55:18.379  6956  6956 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:55:18.383  6956  6956 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:55:18.387  6956  6956 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 13:55:18.390  6956  6956 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 13:55:18.390  6956  6956 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,06-30 13:55:18.404  6956  6956 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-30 13:55:18.411  6956  6956 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:55:18.411  6956  6956 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:55:18.455  6956  7008 D OpenGLRenderer: Render dirty regions requested: true
06-30 13:55:18.455  6956  7008 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:55:18.473  6956  7008 D OpenGLRenderer: Enabling debug mode 0
,06-30 13:55:18.488  6956  6956 D Atlas   : Validating map...
,06-30 13:55:18.493  1036  2032 D SplitWindow: check instance of lgWin Window{11e1c87b u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:55:18.503  1036  1092 W ActivityManager: Activity pause timeout for ActivityRecord{3529b3e4 u0 com.test.thalitest/.MainActivity t12}
,06-30 13:55:18.529  6956  7006 D LgDataFeature: LgDataFeature() Constructor: none
,06-30 13:55:18.529  6956  7006 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 13:55:18.621  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +618ms (total +711ms)
06-30 13:55:18.621  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3529b3e4 u0 com.test.thalitest/.MainActivity t12} time:283906
06-30 13:55:18.626  6956  6956 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3396d2c2 time:283912
,06-30 13:55:18.773  6956  6956 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 13:55:18.846  6956  7006 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
06-30 13:55:18.846  6956  7006 I chromium: 
,06-30 13:55:18.988  6956  7019 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,06-30 13:55:18.999  6956  6956 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
06-30 13:55:18.999  6956  6956 I chromium: 
06-30 13:55:19.004  6956  7019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:55:19.004  6956  7019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:55:19.004  6956  7019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:55:19.004  6956  7019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:55:19.004  6956  7019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:55:19.004  6956  7019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db57be6 added. We now have 1 listener(s)
,06-30 13:55:19.010  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:19.017  6956  7019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
06-30 13:55:19.020  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,06-30 13:55:19.022  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:55:19.022  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:55:19.031  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9fa97d added. We now have 1 listener(s)
06-30 13:55:19.031  6956  7019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:19.036  1036  1544 D WifiService: New client listening to asynchronous messages
06-30 13:55:19.038  6956  7019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-30 13:55:19.044  6956  7019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,06-30 13:55:19.044  6956  7019 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
06-30 13:55:19.050  6956  7019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:55:19.050  1036  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:19.051  6956  7019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:19.059  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:55:19.059  6956  7019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:55:19.059  6956  7019 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:55:19.060  6956  7019 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:55:19.061  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:19.063  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:19.098  6956  6956 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:55:19.491   345   365 E GBMv2   : DFP En is all cleared set to be enabled
06-30 13:55:19.491   345   365 E GBMv2   : Set value is all cleared set the max
06-30 13:55:19.491   345   365 I GBMv2   : DFP Enabled. Ignore VFP set
,06-30 13:55:19.888  6956  7023 W jxcore-log: Initializing JXcore engine
06-30 13:55:19.888  6956  7023 W jxcore-log: JXcore engine is ready
06-30 13:55:19.922  7023  7023 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7421]" dev="sockfs" ino=7421 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
06-30 13:55:19.922  7023  7023 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 13:55:19.922  7023  7023 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7599]" dev="sockfs" ino=7599 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
06-30 13:55:19.922  7023  7023 W Thread-812: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
06-30 13:55:19.922  7023  7023 W Thread-812: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33901]" dev="sockfs" ino=33901 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
06-30 13:55:19.941  6956  7023 W jxcore-log: Starting JXcore engine
06-30 13:55:20.017  6956  7023 W jxcore-log: Platform android
06-30 13:55:20.017  6956  7023 W jxcore-log: 
06-30 13:55:20.017  6956  7023 W jxcore-log: Process ARCH arm
06-30 13:55:20.017  6956  7023 W jxcore-log: 
06-30 13:55:20.213  6956  7023 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:55:20.213  6956  7023 I jxcore-log: 
06-30 13:55:20.214  6956  7023 W jxcore-log: JXcore engine is started
,06-30 13:55:20.218  6956  7019 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:55:20.224  6956  6956 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 13:55:30.285  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 13:55:30.285  6956  7023 I jxcore-log: 
,06-30 13:55:30.288  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 13:55:30.288  6956  7023 I jxcore-log: 
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:30.294  6956  7023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:55:30.298  6956  7023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:30.300  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 13:55:30.300  6956  7023 I jxcore-log: 
,06-30 13:55:30.301  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 13:55:30.301  6956  7023 I jxcore-log: 
06-30 13:55:30.628  6956  7023 I jxcore-log: Unit Test app is loaded
06-30 13:55:30.628  6956  7023 I jxcore-log: 
06-30 13:55:30.632  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:55:30.632  6956  7023 I jxcore-log: 
,06-30 13:55:30.637  6956  7023 I jxcore-log: My device name is: LGE-LG-D855
06-30 13:55:30.637  6956  7023 I jxcore-log: 
06-30 13:55:30.639  6956  7023 I jxcore-log: WARN testUtils: myNameCallback not set!
06-30 13:55:30.639  6956  7023 I jxcore-log: 
06-30 13:55:30.655  6956  6956 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-30 13:55:30.741  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:30.741  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@247bc5d7 added. We now have 2 listener(s)
06-30 13:55:30.741  6956  7019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:55:30.747  6956  7019 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:30.747  6956  7019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:30.747  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:30.747  6956  7019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:30.747  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@247bc5d7 removed from the list
06-30 13:55:30.748  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:30.748  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a44eec4 added. We now have 2 listener(s)
06-30 13:55:30.748  6956  7019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:55:30.750  6956  7019 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:30.750  6956  7019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:30.750  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:30.750  6956  7019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:30.750  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a44eec4 removed from the list
06-30 13:55:30.750  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:30.751  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fb191ad added. We now have 2 listener(s)
06-30 13:55:30.751  6956  7019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:55:30.753  1036  1940 D WifiServiceImplEx: setWifiEnabled: false pid=6956, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
06-30 13:55:30.753  1036  1940 D WifiService: setWifiEnabled: false pid=6956, uid=10118
06-30 13:55:30.753  1036  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,06-30 13:55:30.775  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:30.776  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:30.776  1036  1036 D Ulp_jni : JNI:system_update. Event-4
06-30 13:55:30.776  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:30.776  1036  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:30.776  1036  1994 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1cbfeb29 mBinding = false
06-30 13:55:30.776  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:30.776  1036  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:30.777  1036  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:30.777  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:30.777  1036  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
06-30 13:55:30.777  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 13:55:30.777  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-30 13:55:30.778  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-30 13:55:30.778  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-30 13:55:30.785  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-30 13:55:30.785  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
06-30 13:55:30.785  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.785  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.785  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
06-30 13:55:30.785  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
06-30 13:55:30.786  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
06-30 13:55:30.786  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
06-30 13:55:30.786  1036  2862 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.786   318   894 D CommandListener: Clearing all IP addresses on wlan0
,06-30 13:55:30.807  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:30.807  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:30.807  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,06-30 13:55:30.807  1036  1118 D BluetoothManagerService: Message: 2
06-30 13:55:30.812  1036  1958 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
06-30 13:55:30.813  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.813  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.813  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 13:55:30.813  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.813  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 13:55:30.815  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
06-30 13:55:30.816  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
06-30 13:55:30.816  1036  1118 D BluetoothManagerService: Sending off request.
06-30 13:55:30.817  4350  4374 D LGBluetoothServiceAdapter: [BTUI] Precleanup
06-30 13:55:30.822  4350  4437 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
06-30 13:55:30.822  4350  4437 D BluetoothAdapterProperties: Setting state to 13
06-30 13:55:30.822  4350  4437 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,06-30 13:55:30.823  1036  1036 D WifiHS20: hidePasspointNotification off =false
06-30 13:55:30.836  6956  7019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:55:30.838  4350  4437 D BluetoothAdapterProperties: onBluetoothDisable()
06-30 13:55:30.838  4350  4437 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
06-30 13:55:30.840  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:30.840  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:30.845  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:30.847  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:55:30.847  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:30.847  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
06-30 13:55:30.847  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
06-30 13:55:30.848  6956  7019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:30.852  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:30.855  6956  7019 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:55:30.865  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:30.865  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:30.865  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,06-30 13:55:30.867  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:30.868  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:30.874   318  7040 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-30 13:55:30.875  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
06-30 13:55:30.875  1036  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
06-30 13:55:30.875  1036  1545 D DSQN    : disableDataServiceNotify
06-30 13:55:30.876  1036  1545 D DSQN    : stop dsqn bin
06-30 13:55:30.876  1036  1116 D DSQN    : Dns fail occured do internet check.
06-30 13:55:30.876  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
06-30 13:55:30.876  1036  1036 D DSQN    : try Internet connection check
,06-30 13:55:30.878  4350  4440 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:55:30.878  4350  4437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
06-30 13:55:30.879  4350  4742 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,06-30 13:55:30.879  4350  4746 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-30 13:55:30.880  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
06-30 13:55:30.880  1036  1036 D WifiHS20: hidePasspointNotification off =false
06-30 13:55:30.880  4350  4557 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
06-30 13:55:30.880  4350  4786 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-30 13:55:30.880  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:30.880  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:30.880  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:30.881  4350  4787 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
06-30 13:55:30.881  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
06-30 13:55:30.881  4350  4557 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:55:30.881  4350  4437 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-30 13:55:30.881  4350  4789 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-30 13:55:30.883  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:30.884  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:30.884  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:30.885  1036  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.885  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.885  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:30.885  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f0a8cda
06-30 13:55:30.885  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:30.885  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:30.886  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:30.886  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:30.886  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:30.886  6956  6956 V io.jxcore.,node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:30.886  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:30.886  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:30.886  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:30.886  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:55:30.886  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:30.887  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:30.887  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:30.887  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
06-30 13:55:30.887  1036  1036 D RttService: SCAN_AVAILABLE : 1
06-30 13:55:30.887  1036  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.887  1036  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
06-30 13:55:30.888  1036  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.891  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:30.893  4350  4350 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:30.893  4350  4350 D BluetoothMapService: STATE_TURNING_OFF
06-30 13:55:30.893  4350  4350 V BluetoothMapService: Handler(): got msg=4
06-30 13:55:30.893  4350  4350 D BluetoothMapService: MAP Service closeService in
06-30 13:55:30.893  4350  4350 D BluetoothMapMasInstance: MAP Service shutdown
06-30 13:55:30.893  4350  4350 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:55:30.893  4350  4350 V BluetoothMapService: MAP Service closeService out
06-30 13:55:30.894  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:30.895  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:30.895  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 13:55:30.896  1036  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
06-30 13:55:30.897  4350  4350 V BtOppService: Receiver DISABLED_ACTION 
06-30 13:55:30.897  4350  4350 I BtOppRfcommListener: stopping Accept Thread
06-30 13:55:30.897  4350  4350 V BtOppRfcommListener: close mBtServerSocket
06-30 13:55:30.897  4350  4350 V BtOppRfcommListener: waiting for thread to terminate
06-30 13:55:30.897  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:55:30.897  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:30.897  4350  4786 I BtOppRfcommListener: BluetoothSocket listen thread finished
06-30 13:55:30.897  1036  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:30.897  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
06-30 13:55:30.898  1036  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
06-30 13:55:30.898  4350  4350 V BtOppRfcommListener: done waiting for thread to terminate
06-30 13:55:30.898  1036  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
06-30 13:55:30.898  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
06-30 13:55:30.899  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.899  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.899  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
06-30 13:55:30.899  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:30.900  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 13:55:30.902   318  7046 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-30 13:55:30.902  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 13:55:30.903  1036  7043 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
06-30 13:55:30.903  1036  7041 D DSQN    : ThreadInternetCheck internet check NOK 
06-30 13:55:30.903  1036  7041 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
06-30 13:55:30.904  1036  7041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
06-30 13:55:30.918  1036  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7047 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-30 13:55:30.918  1036  1537 D LGWifiP2pService: P2pDisablingState
06-30 13:55:30.919  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-34ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.919  1036  1537 D LGWifiP2pService: p2p socket connection lost
06-30 13:55:30.919  1036  1537 D LGWifiP2pService: P2pDisabledState
,06-30 13:55:30.920  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
06-30 13:55:30.920  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
06-30 13:55:30.920  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
06-30 13:55:30.921  4350  4350 V BtOppService: onDestroy
06-30 13:55:30.921  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.921  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:30.921  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
06-30 13:55:30.922  1941  1941 D WfdsService: WifiP2pState is changed : false
06-30 13:55:30.922  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
06-30 13:55:30.922  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
06-30 13:55:30.922  1941  2340 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
06-30 13:55:30.922  1941  2340 D WfdsService: Set the WFDS Monitor: false
06-30 13:55:30.922  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
06-30 13:55:30.922  1941  2340 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:55:30.922   318   894 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:55:30.922  1941  2340 D WfdsService: STATE : WfdsDisabledState - enter
06-30 13:55:30.922  1941  2773 D CtrlSupplicant: Received on exit socket, terminate
06-30 13:55:30.922  1941  2773 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
06-30 13:55:30.922  1941  2773 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
06-30 13:55:30.922  1941  2773 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
06-30 13:55:30.923  1941  2342 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
06-30 13:55:30.923  1941  2340 W WfdsService: DefaultState - msg [9445378] is not handled
06-30 13:55:30.955  1036  2032 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7065 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,06-30 13:55:30.957  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:30.957  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 13:55:30.957  4350  4350 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
06-30 13:55:30.957  1036  1538 D WifiNative-p2p0: doBoolean: TERMINATE
06-30 13:55:30.957  1036  1036 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
06-30 13:55:30.959  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
06-30 13:55:30.961  1036  1538 D WifiNative-p2p0: TERMINATE: returned true
06-30 13:55:30.961  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 13:55:30.961  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:30.961  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 13:55:30.963  1941  1956 D WifiServiceExtension: isInternetCheckAvailable return false
06-30 13:55:30.964  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
06-30 13:55:30.965  1036  1036 D WifiHS20: hidePasspointNotification off =false
06-30 13:55:30.965  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:30.965  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:30.965  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:55:30.965  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-30 13:55:30.965  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,06-30 13:55:30.965  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-30 13:55:30.968  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:30.968  1036  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:30.968  1036  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:30.969  1036  1545 D NetworkManagementService: Removing idletimer
,06-30 13:55:30.969  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
06-30 13:55:30.969  1036  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:30.969  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-30 13:55:30.969  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-30 13:55:30.969  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-30 13:55:30.969  1036  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
06-30 13:55:30.969  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
06-30 13:55:30.970  1036  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:30.970  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:30.970  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:30.971  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
06-30 13:55:30.975  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
06-30 13:55:30.975  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
06-30 13:55:30.975  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 13:55:30.975  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:30.979  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:55:30.985  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:30.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:30.987  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:30.996  7047  7047 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 13:55:30.996  7047  7047 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-30 13:55:30.996  7047  7047 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:55:30.997  7047  7047 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
06-30 13:55:30.998  7047  7047 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 13:55:30.998  7047  7047 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-30 13:55:30.999  1036  2862 D DhcpStateMachine: StoppedState
06-30 13:55:30.999  1036  2862 D DhcpStateMachine: StoppedState{ when=-77ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:31.001  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
06-30 13:55:31.001  1036  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
06-30 13:55:31.004  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 13:55:31.005  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:31.006  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:31.006  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:31.006  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:31.006  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:31.049  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 13:55:31.049  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:55:31.050  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:31.050  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:31.050  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 13:55:31.054  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:55:31.054  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:31.055  2720  2720 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
06-30 13:55:31.055  2720  2720 I wpa_supplicant: monitor socket send errors count : 1
06-30 13:55:31.055  2720  2720 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
06-30 13:55:31.056  1036  2757 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
06-30 13:55:31.056  1036  2757 D WifiMonitor: Dropping event because (p2p0) is stopped
06-30 13:55:31.056  1036  1667 I ActivityManager: Killing 6324:com.android.providers.calendar/u0a14 (adj 15): empty #17
06-30 13:55:31.093  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
06-30 13:55:31.093  1036  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
06-30 13:55:31.093  1036  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
06-30 13:55:31.093  1036  2757 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
06-30 13:55:31.093  7047  7047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:55:31.093  1036  2757 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,06-30 13:55:31.093  2720  2720 W wpa_supplicant: USIM:  scard_deinit function
06-30 13:55:31.094  1036  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=296365
06-30 13:55:31.094  1036  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=296365
06-30 13:55:31.094  1036  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 13:55:31.094  1036  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 13:55:31.095  1036  1118 D Tethering: InitialState.processMessage what=4
06-30 13:55:31.095  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296366  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
06-30 13:55:31.096  1036  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296367  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
06-30 13:55:31.148  1036  1777 W libprocessgroup: failed to open /acct/uid_10014/pid_6324/cgroup.procs: No such file or directory
,06-30 13:55:31.159  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 13:55:31.164  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,06-30 13:55:31.168  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:31.170  4350  4350 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:55:31.170  4350  4350 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:31.170  4350  4350 V BluetoothPbapReceiver: ***********state = 13
06-30 13:55:31.172  4350  4350 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
06-30 13:55:31.173  4350  4350 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:31.173  4350  4350 V BluetoothPbapService: state: 13
06-30 13:55:31.173  4350  4350 V BluetoothPbapService: Pbap Service closeService in
06-30 13:55:31.175  4350  4350 V BluetoothPbapService: successfully stopped pbap service
,06-30 13:55:31.175  4350  4350 V BluetoothPbapService: Pbap Service closeService out
06-30 13:55:31.176  4350  4350 V BluetoothPbapService: Pbap Service onDestroy
06-30 13:55:31.176  4350  4350 V BluetoothPbapService: Pbap Service closeService in
06-30 13:55:31.176  4350  4350 V BluetoothPbapService: Pbap Service closeService out
06-30 13:55:31.176  4350  4350 D LGBluetoothPbapAdapter: [BTUI] cleanup
06-30 13:55:31.176  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 13:55:31.180  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:31.225  7047  7047 D LgDataFeature: LgDataFeature() Constructor: none
,06-30 13:55:31.225  7047  7047 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 13:55:31.231  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
06-30 13:55:31.231  1036  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
06-30 13:55:31.231  1036  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
06-30 13:55:31.231  1036  2757 D WifiMonitor: Disconnecting from the supplicant, no more events
06-30 13:55:31.232  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,06-30 13:55:31.245  1036  1051 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7087 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:31.259  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:31.271  1036  1118 D BluetoothManagerService: Message: 20
06-30 13:55:31.271  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a2845c8:true
,06-30 13:55:31.285  1036  1118 D BluetoothManagerService: Message: 30
,06-30 13:55:31.290  1036  1118 D BluetoothManagerService: Message: 30
06-30 13:55:31.295  7047  7047 D LocalBluetoothProfileManager: Adding local MAP profile
06-30 13:55:31.296  7047  7047 D BluetoothMap: Create BluetoothMap proxy object
,06-30 13:55:31.297  1036  1118 D BluetoothManagerService: Message: 30
06-30 13:55:31.302  1036  1118 D BluetoothManagerService: Message: 30
06-30 13:55:31.304  7047  7047 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-30 13:55:31.305  7047  7047 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
06-30 13:55:31.316  7047  7047 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,06-30 13:55:31.320  7047  7047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
06-30 13:55:31.327  7047  7047 D DockEventReceiver: finishStartingService: stopping service
06-30 13:55:31.334  1036  1538 D WifiOffDelayIfNotUsed: stopMonitoring
06-30 13:55:31.334  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 13:55:31.334  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:31.334  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 13:55:31.335  1941  1941 D WfdsService: Supplicant Connection state is changed : false
06-30 13:55:31.335  1941  2340 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
06-30 13:55:31.335  1941  2340 D WfdsService: Set the WFDS Monitor: false
,06-30 13:55:31.335  1941  2340 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:55:31.335  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
06-30 13:55:31.336  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
06-30 13:55:31.337  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
06-30 13:55:31.337  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
06-30 13:55:31.337  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:31.337  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:31.338  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:31.341  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:31.343  7047  7047 D BluetoothInputDevice: Proxy object connected
06-30 13:55:31.343  7047  7047 D HidProfile: Bluetooth service connected
06-30 13:55:31.345  7047  7047 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 13:55:31.345  7047  7047 D PanProfile: Bluetooth service connected
,06-30 13:55:31.346  7047  7047 D BluetoothMap: Proxy object connected
06-30 13:55:31.347  7047  7047 D MapProfile: Bluetooth service connected
06-30 13:55:31.347  7047  7047 D BluetoothMap: getConnectedDevices()
06-30 13:55:31.347  7047  7047 D BluetoothMap: Bluetooth is Not enabled
06-30 13:55:31.347  7047  7047 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-30 13:55:31.390  1036  1903 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7111 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,06-30 13:55:31.393  1036  1903 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
06-30 13:55:31.414   322  1387 V AudioFlinger: 2127 died, releasing its sessions
06-30 13:55:31.414   322  1387 V AudioFlinger:  pid 1852 @ 0
,06-30 13:55:31.414   322  1387 V AudioFlinger:  pid 3192 @ 1
,06-30 13:55:31.414   322  1387 V AudioFlinger:  pid 3192 @ 2
06-30 13:55:31.547  1036  1052 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
06-30 13:55:31.547  7087  7087 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
06-30 13:55:31.549  7087  7087 W LG Account v2.2: No ProfileInfo entries
06-30 13:55:31.550  7087  7087 I LG Account v2.2: isEnabled: false
,06-30 13:55:31.551  7087  7087 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,06-30 13:55:31.551  7087  7087 I Feature : [Lifetracker]Country: EU
06-30 13:55:31.551  7087  7087 I Feature : [Lifetracker]Operator: OPEN
06-30 13:55:31.552  7087  7087 I Feature : [Lifetracker]Ranking support: false
06-30 13:55:31.552  7087  7087 I Feature : [Lifetracker]Comfort support: false
06-30 13:55:31.552  7087  7087 I Feature : [Lifetracker]Accessory: true
06-30 13:55:31.552  7087  7087 I Feature : [Lifetracker]Health device: true
06-30 13:55:31.552  7087  7087 I Feature : [Lifetracker]Extra Pedometer: false
06-30 13:55:31.553  7087  7087 I Feature : [Lifetracker]Blood glucose device: false
06-30 13:55:31.553  7087  7087 I Feature : [Lifetracker]Device Number: 3
,06-30 13:55:31.573  7047  7047 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,06-30 13:55:31.580  7047  7047 D BluetoothPermissionRequest: onReceive
06-30 13:55:31.582  7047  7047 D LGBluetoothAuthorization: [BTUI] cancel All Notification
06-30 13:55:31.590  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,06-30 13:55:31.591  1036  1976 I ActivityManager: Killing 6555:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,06-30 13:55:31.604  7111  7111 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 13:55:31.729  4350  4350 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,06-30 13:55:31.729  4350  4350 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,06-30 13:55:31.732  4350  4350 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,06-30 13:55:31.734  1036  2050 W libprocessgroup: failed to open /acct/uid_10008/pid_6555/cgroup.procs: No such file or directory
06-30 13:55:31.753  4350  4350 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:31.753  4350  4350 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
06-30 13:55:31.756  7111  7111 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,06-30 13:55:31.765  4350  4350 V BluetoothFtpService: Ftp Service onStartCommand
06-30 13:55:31.765  4350  4350 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:31.766  4350  4350 V BluetoothFtpService: Ftp Service closeService
06-30 13:55:31.766  4350  4350 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,06-30 13:55:31.771  4350  4350 V BluetoothFtpService: successfully stopped ftp service
06-30 13:55:31.772  4350  4350 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:31.772  4350  4350 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 13:55:31.772  4350  4350 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:31.773  4350  4350 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:31.773  4350  4350 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
06-30 13:55:31.773  4350  4350 V BluetoothSapReceiver: Calling SAP service start service with action = null
06-30 13:55:31.777  4350  4350 V BluetoothFtpService: Ftp Service onDestroy
06-30 13:55:31.777  4350  4350 V BluetoothFtpService: Ftp Service closeService
,06-30 13:55:31.811  7111  7111 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
06-30 13:55:31.812  7111  7111 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
06-30 13:55:31.812  7111  7111 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
06-30 13:55:31.812  7111  7111 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
06-30 13:55:31.813  7111  7111 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,06-30 13:55:31.816  7111  7111 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
06-30 13:55:31.820  1036  2022 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7134 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-30 13:55:31.822  4350  4350 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:31.822  4350  4350 V BluetoothSapService: state: 13
06-30 13:55:31.822  4350  4350 V BluetoothSapService: Stopping SAP server process
06-30 13:55:31.823  4350  4350 V BluetoothSapService: Sap Service closeSapService in
06-30 13:55:31.823  4350  4350 V BluetoothSapService: Close listen Socket : 
06-30 13:55:31.823  4350  4350 V BluetoothSapService: Close rfcomm Socket : 
06-30 13:55:31.823  4350  4350 V BluetoothSapService: Close sapd  Socket : 
06-30 13:55:31.824  4350  4350 V BluetoothSapService: Sap Service closeSapService out
06-30 13:55:31.825  4350  4350 V BluetoothSapService: Sap Service onDestroy
06-30 13:55:31.825  4350  4350 V BluetoothSapService: Sap Service closeSapService in
06-30 13:55:31.825  4350  4350 V BluetoothSapService: Close listen Socket : 
06-30 13:55:31.825  4350  4350 V BluetoothSapService: Close rfcomm Socket : 
06-30 13:55:31.825  4350  4350 V BluetoothSapService: Close sapd  Socket : 
06-30 13:55:31.825  4350  4350 V BluetoothSapService: Sap Service closeSapService out
06-30 13:55:31.833  7111  7111 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,06-30 13:55:31.847  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-30 13:55:31.850  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:31.857  1036  1667 D WifiServiceImplEx: setWifiEnabled: true pid=6956, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
06-30 13:55:31.857  1036  1667 D WifiService: setWifiEnabled: true pid=6956, uid=10118
06-30 13:55:31.857  1036  1667 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
06-30 13:55:31.867  7134  7134 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 13:55:31.872  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:31.872  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:31.872  1036  1036 D Ulp_jni : JNI:system_update. Event-4
06-30 13:55:31.873  1036  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
06-30 13:55:31.873  1036  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
06-30 13:55:31.874  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
06-30 13:55:31.874  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-30 13:55:31.874  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
06-30 13:55:31.875  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-30 13:55:31.875  1036  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
06-30 13:55:31.875  1036  1538 E WifiHW  : unknown target_country: EU , set to default
06-30 13:55:31.875  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
06-30 13:55:31.875  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
06-30 13:55:31.875  1036  1538 I WifiUtil: gEnableBmps=1
06-30 13:55:31.876  1036  1939 I ActivityManager: Killing 6119:com.lge.appbox.client/u0a11 (adj 15): empty #17
06-30 13:55:31.883  4350  4440 D bt_hci_bdroid: cleanup
06-30 13:55:31.883  4350  4561 I bt_lpm  : LPM is already off!!!
06-30 13:55:31.883  4350  4720 I bt_userial_mct: exiting userial_read_thread
06-30 13:55:31.883  4350  4720 D bt_userial_mct: Leaving userial_evt_read_thread()
06-30 13:55:31.883  4350  4557 W bt-btif : ag scb idx 1 not allocated
06-30 13:55:31.883  4350  4557 E bt-btif : BTA AG is already disabled, ignoring ...
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:31.883  4350  4557 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:31.883  4350  4557 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:55:31.884  4350  4440 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
06-30 13:55:31.884  4350  4561 I bt_vendor: hw_epilog_process
06-30 13:55:31.884,  4350  4440 D bt_hci_bdroid: cleanup Finalizing cleanup
06-30 13:55:31.884  4350  4440 D bt_userial_mct: userial_close
06-30 13:55:31.884  4350  4440 E bt_userial_mct: pthread_join() FAILED result:3
06-30 13:55:31.884  4350  4440 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,06-30 13:55:31.947  1036  1777 W libprocessgroup: failed to open /acct/uid_10011/pid_6119/cgroup.procs: No such file or directory
,06-30 13:55:31.947  7111  7111 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-30 13:55:31.953  7111  7111 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
06-30 13:55:31.957  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,06-30 13:55:31.960  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:31.965  7111  7111 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
06-30 13:55:31.970  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:55:31.971  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:55:31.971  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 13:55:31.980  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:55:31.985  4350  4440 D bt_hci_bdroid: set_power 0
06-30 13:55:31.985  4350  4440 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
06-30 13:55:31.985  4350  4440 I bt_vendor: bluetooth satus is on
06-30 13:55:31.985  4350  4440 I bt_vendor: bt-vendor : resetting BT status
06-30 13:55:31.985  4350  4440 I bt_vendor: Starting hciattach daemon
06-30 13:55:31.985  4350  4440 I bt_vendor: try to set false
06-30 13:55:31.986  4350  4440 I bt_vendor: Starting hciattach daemon
06-30 13:55:31.986  4350  4440 I bt_vendor: try to set false
06-30 13:55:31.987  4350  4440 I bt_vendor: cleanup
06-30 13:55:31.988  4350  4557 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
06-30 13:55:31.995  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 13:55:32.000  4350  4440 I GKI_LINUX: GKI_exit_task 0 done
06-30 13:55:32.000  4350  4440 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
06-30 13:55:32.001  4350  4437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
06-30 13:55:32.003  4350  4350 D HeadsetService: Received stop request...Stopping profile...
06-30 13:55:32.005  4350  4350 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:55:32.005  4350  4480 D HeadsetStateMachine: Exit Disconnected: -1
06-30 13:55:32.005  4350  4350 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:55:32.006  4350  4350 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb9fb74
06-30 13:55:32.012  1036  1036 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:32.012  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,06-30 13:55:32.012  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-30 13:55:32.013  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:32.015  1852  1852 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:32.015  1852  1852 D BluetoothHeadset: Proxy object disconnected
,06-30 13:55:32.016  7111  7111 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-30 13:55:32.016  1852  1852 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:32.017  4350  4350 D A2dpService: Received stop request...Stopping profile...
06-30 13:55:32.017  4350  4518 D A2dpStateMachine: Exit Disconnected: -1
06-30 13:55:32.019  4350  4350 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
06-30 13:55:32.023  4350  4437 D BluetoothAdapterState: Stopping profile services that were post enabled
06-30 13:55:32.027  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:32.027  4350  4350 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
06-30 13:55:32.027  4350  4350 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:55:32.027  4350  4350 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb9fb74
,06-30 13:55:32.032  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:55:32.032  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:55:32.032  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:32.037  1036  1036 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:32.037  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
06-30 13:55:32.037  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:32.039  4350  4350 D HidService: Received stop request...Stopping profile...
06-30 13:55:32.039  4350  4350 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb9fb74
,06-30 13:55:32.041  4350  4350 D HealthService: Received stop request...Stopping profile...
06-30 13:55:32.042  4350  4350 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb9fb74
06-30 13:55:32.043  4350  4350 D PanService: Received stop request...Stopping profile...
06-30 13:55:32.044  4350  4350 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb9fb74
,06-30 13:55:32.046  4350  4350 D HeadsetStateMachine: Unbinding service...
06-30 13:55:32.047  4350  4350 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:55:32.047  4350  4350 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,06-30 13:55:32.047  4350  4350 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:55:32.047  4350  4350 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:55:32.047  4350  4350 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
06-30 13:55:32.047  4350  4350 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:55:32.047  4350  4350 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:55:32.048  4350  4350 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 13:55:32.049  4350  4350 D BtGatt.GattService: Received stop request...Stopping profile...
06-30 13:55:32.049  4350  4350 D BtGatt.GattService: stop()
06-30 13:55:32.049  4350  4350 D BtGatt.AdvertiseManager: advertise clients cleared
06-30 13:55:32.050  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:32.050  4350  4350 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb9fb74
06-30 13:55:32.052  7047  7047 D BluetoothInputDevice: Proxy object disconnected
06-30 13:55:32.052  7047  7047 D HidProfile: Bluetooth service disconnected
06-30 13:55:32.052  7047  7047 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:55:32.052  7047  7047 D PanProfile: Bluetooth service disconnected
06-30 13:55:32.053  4350  4350 D BluetoothMapService: Received stop request...Stopping profile...
06-30 13:55:32.053  4350  4350 D BluetoothMapService: stop()
06-30 13:55:32.054  4350  4350 D BluetoothMapEmailAppObserver: deinitObservers()
06-30 13:55:32.055  4350  4350 D BluetoothMapEmailAppObserver: removeReceiver()
06-30 13:55:32.062  4350  4350 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb9fb74
06-30 13:55:32.062  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:32.062  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:32.065  4350  4350 I BluetoothA2dpServiceJni: cleanupNative
,06-30 13:55:32.065  7047  7047 D BluetoothMap: Proxy object disconnected
06-30 13:55:32.065  7047  7047 D MapProfile: Bluetooth service disconnected
06-30 13:55:32.066  4350  4520 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
06-30 13:55:32.066  4350  4350 I GKI_LINUX: GKI_exit_task 2 done
06-30 13:55:32.066  4350  4350 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
06-30 13:55:32.066  7111  7111 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-30 13:55:32.067  4350  4350 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
06-30 13:55:32.067  4350  4350 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-30 13:55:32.067  4350  4350 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
06-30 13:55:32.068  4350  4350 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:55:32.068  4350  4350 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:55:32.068  4350  4350 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-30 13:55:32.068  4350  4350 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
06-30 13:55:32.072  4350  4350 V BluetoothMapService: Handler(): got msg=4
06-30 13:55:32.072  4350  4350 D BluetoothMapService: MAP Service closeService in
06-30 13:55:32.073  4350  4350 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:55:32.073  4350  4350 V BluetoothMapService: MAP Service closeService out
06-30 13:55:32.073  4350  4437 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
06-30 13:55:32.073  4350  4437 D BluetoothAdapterProperties: Setting state to 10
06-30 13:55:32.073  4350  4437 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
06-30 13:55:32.073  4350  4350 D BluetoothMapService: cleanup()
06-30 13:55:32.073  4350  4350 D BluetoothMapService: MAP Service closeService in
06-30 13:55:32.073  4350  4350 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:55:32.073  4350  4350 V BluetoothMapService: MAP Service closeService out
06-30 13:55:32.074  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:32.074  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
06-30 13:55:32.074  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
06-30 13:55:32.074  4350  4437 I BluetoothAdapterState: Entering OffState
06-30 13:55:32.074  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
,06-30 13:55:32.129  1036  1939 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7162 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
06-30 13:55:32.130  1852  4478 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:32.131  7047  7064 D BluetoothInputDevice: onBluetoothStateChange: up=false
,06-30 13:55:32.132  1852  4486 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:32.133  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
06-30 13:55:32.134  7047  7063 D BluetoothPbap: onBluetoothStateChange: up=false
06-30 13:55:32.135  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:32.135  7047  7064 D BluetoothPan: onBluetoothStateChange on: false
06-30 13:55:32.137  7047  7063 D BluetoothMap: onBluetoothStateChange: up=false
06-30 13:55:32.139  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
06-30 13:55:32.139  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
06-30 13:55:32.141  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
06-30 13:55:32.141  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
,06-30 13:55:32.141  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1cbfeb29 mBinding = false
06-30 13:55:32.142  1036  1118 D BluetoothManagerService: Sending unbind request.
06-30 13:55:32.143  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,06-30 13:55:32.147  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:32.147  1941  2143 D LGBluetoothAPIService: Message: 2
06-30 13:55:32.147  1941  2143 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@22fda1d7 mBinding = false
06-30 13:55:32.147  1941  2143 D LGBluetoothAPIService: Sending unbind request.
06-30 13:55:32.148  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:32.153  1603  1603 D BluetoothAdapter: 808982924: getState() :  mService = null. Returning STATE_OFF
06-30 13:55:32.153  1603  1603 D BluetoothAdapter: 808982924: getState() :  mService = null. Returning STATE_OFF
06-30 13:55:32.153  7047  7047 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:55:32.154  7047  7047 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
06-30 13:55:32.154  7047  7047 D LGBluetoothEventManager: [BTUI] clear device connection state
06-30 13:55:32.156  7047  7047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,06-30 13:55:32.156  4350  4440 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,06-30 13:55:32.157  4350  4350 I GKI_LINUX: GKI_exit_task 1 done
06-30 13:55:32.157  4350  4350 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
06-30 13:55:32.157  4350  4350 I BluetoothServiceJni: cleanupNative: return from cleanup
06-30 13:55:32.157  4350  4350 I art     : --- WEIRD: removing null entry 246
06-30 13:55:32.157  4350  4350 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
06-30 13:55:32.158  4350  4350 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
06-30 13:55:32.159  4350  4350 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
06-30 13:55:32.162  4350  4350 I art     : System.exit called, status: 0
06-30 13:55:32.162  4350  4350 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
06-30 13:55:32.164  7047  7047 D DockEventReceiver: finishStartingService: stopping service
,06-30 13:55:32.181   322  1386 V AudioFlinger: 4350 died, releasing its sessions
06-30 13:55:32.182   322  1386 V AudioFlinger:  pid 1852 @ 0
06-30 13:55:32.182   322  1386 V AudioFlinger:  pid 3192 @ 1
06-30 13:55:32.182   322  1386 V AudioFlinger:  pid 3192 @ 2
06-30 13:55:32.182  7047  7047 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
06-30 13:55:32.215  1036  2050 I ActivityManager: Process com.android.bluetooth (pid 4350) has died
,06-30 13:55:32.215  1036  2050 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
06-30 13:55:32.217  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 13:55:32.229  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 13:55:32.231  7047  7047 D BluetoothPermissionRequest: onReceive
06-30 13:55:32.234  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.241  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:32.242  7047  7047 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-30 13:55:32.242  7047  7047 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
06-30 13:55:32.244  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-30 13:55:32.303  1036  1940 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7185 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,06-30 13:55:32.310  7162  7183 W FormManager: Network not available. Please check & try again.
06-30 13:55:32.326  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:32.326  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:32.327  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:32.327  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:32.328  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,06-30 13:55:32.331   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 28.619ms
06-30 13:55:32.338  7162  7184 V FormManager: Network unavailable.
06-30 13:55:32.340  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:32.340  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-30 13:55:32.340  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:32.340  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:32.340  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 13:55:32.340  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,06-30 13:55:32.347  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:32.348  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:55:32.350  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:32.351   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 19.326ms
06-30 13:55:32.355  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:32.355  7162  7184 V FormManager: Network unavailable.
06-30 13:55:32.359  7185  7185 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
06-30 13:55:32.360  7185  7185 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:55:32.360  7185  7185 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
06-30 13:55:32.361  7185  7185 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 13:55:32.372   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 19.377ms
06-30 13:55:32.375  7065  7065 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
06-30 13:55:32.375  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:55:32.375  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:32.378  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:32.379  4818  7204 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,06-30 13:55:32.381  7162  7205 W FormManager: Network not available. Please check & try again.
06-30 13:55:32.384  7185  7185 D BluetoothAdapterApp: Loading JNI Library
06-30 13:55:32.387  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:32.390  4818  7207 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:32.390  4818  7207 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,06-30 13:55:32.391  7162  7206 V FormManager: Network unavailable.
06-30 13:55:32.399  7111  7111 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
06-30 13:55:32.400  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-30 13:55:32.401  7111  7111 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
06-30 13:55:32.401  7162  7206 V FormManager: Network unavailable.
06-30 13:55:32.404  1036  1580 I ActivityManager: Killing 6140:com.android.contacts/u0a19 (adj 15): empty #17
,06-30 13:55:32.418  7185  7185 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@45e11e5 Instance Count = 1
06-30 13:55:32.433  7111  7111 D LgDataFeature: LgDataFeature() Constructor: none
,06-30 13:55:32.434  7111  7111 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 13:55:32.441  7111  7111 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
06-30 13:55:32.442  7111  7111 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
06-30 13:55:32.442  7111  7111 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
06-30 13:55:32.442  7111  7111 V SoundPool: doLoad: loading sample sampleID=1
06-30 13:55:32.443  7111  7111 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
06-30 13:55:32.446  7111  7211 V SoundPool: Start decode
06-30 13:55:32.446  7111  7211 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,06-30 13:55:32.455   322  1386 V MediaPlayerService: decode(22, 10857164, 17813)
06-30 13:55:32.455   322  1386 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
06-30 13:55:32.455   322  1386 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
06-30 13:55:32.455   322  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
06-30 13:55:32.455   322  1386 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
06-30 13:55:32.455   322  1386 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
06-30 13:55:32.455   322  1386 V MediaPlayerService: player type = 3
06-30 13:55:32.455   322  1386 V AwesomePlayer: AwesomePlayer create()
06-30 13:55:32.455   322  1386 V AwesomePlayer: reset_l() 
06-30 13:55:32.455   322  1386 V AwesomePlayer: cancelPlayerEvents
,06-30 13:55:32.455   322  1386 V AwesomePlayer: setAudioSink() ,
,06-30 13:55:32.455   322  1386 V AwesomePlayer: reset_l() 
,06-30 13:55:32.455   322  1386 V AudioCache: notify(0xb5474980, 8, 0, 0)
06-30 13:55:32.455   322  1386 V AudioCache: ignored
06-30 13:55:32.456   322  1386 V AwesomePlayer: cancelPlayerEvents
,06-30 13:55:32.456   322  1386 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
06-30 13:55:32.456   322  1386 V AwesomePlayer: setDataSource_l dataSource
06-30 13:55:32.456   322  1386 V LGParserOSAL: SniffLGParser start
,06-30 13:55:32.456   322  1386 V LGParserOSAL: MainType:5, SubType=0
06-30 13:55:32.456   322  1386 V LGParserOSAL: #### check Mime : application/ogg
06-30 13:55:32.456   322  1386 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
06-30 13:55:32.456   322  1386 E MediaExtractor: Use LGExtractor :application/ogg 
06-30 13:55:32.487  1036  1940 W libprocessgroup: failed to open /acct/uid_10019/pid_6140/cgroup.procs: No such file or directory
,06-30 13:55:32.495  7185  7185 D BluetoothAdapterApp: onCreate
06-30 13:55:32.496  6809  6809 D UEI.SmartControl: QS Service created
06-30 13:55:32.507   322  1386 V LGParserOSAL: supported mime: application/ogg
06-30 13:55:32.507   322  1386 V AwesomePlayer: setDataSource_l() extractor countTracks=1
06-30 13:55:32.507   322  1386 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
06-30 13:55:32.507   322  1386 V AwesomePlayer: mBitrate = -1 bits/sec
06-30 13:55:32.507   322  1386 V AwesomePlayer: AudioTrack Setting
06-30 13:55:32.507   322  1386 V AwesomePlayer: AudioTrack Setting channelCount = 2
06-30 13:55:32.507   322  1386 V AwesomePlayer: setAudioSource() 
06-30 13:55:32.507   322  1386 V MediaPlayerService: prepare
06-30 13:55:32.507   322  1386 V AwesomePlayer: prepareAsync_l() 
06-30 13:55:32.508   322  1386 V MediaPlayerService: wait for prepare
06-30 13:55:32.508   322  7212 V AwesomePlayer: onPrepareAsyncEvent() 
06-30 13:55:32.508   322  7212 V AwesomePlayer: initAudioDecoder() 
06-30 13:55:32.508   322  7212 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
06-30 13:55:32.508   322  7212 V AudioSystem: isOffloadSupported()
06-30 13:55:32.508   322  7212 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-30 13:55:32.508   322  7212 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-30 13:55:32.508   322  7212 I AudioFlinger: isAudioPlaybackHookOn() false
06-30 13:55:32.508   322  7212 V AwesomePlayer: getUseOffload() = 0 
06-30 13:55:32.508   322  7212 V OMXCodec: OMXCodec::Create
06-30 13:55:32.508   322  7212 V OMXCodec: findMatchingCodecs()
06-30 13:55:32.508   322  7212 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
06-30 13:55:32.508   322  7212 V OMXCodec: matchingCodecs.size()=1
06-30 13:55:32.508   322  7212 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
06-30 13:55:32.509   322  7212 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
06-30 13:55:32.509   322  7212 V LGCodecAdapter: LG Codec Adapter start
06-30 13:55:32.509   322  7212 V OMXCodec: OMXCodec Createtor
06-30 13:55:32.509   322  7212 V OMXCodec: setComponentRole
06-30 13:55:32.510   322  7212 V OMXCodec: configureCodec protected=0
06-30 13:55:32.510   322  7212 V LGCodecAdapter: called getLGCodecSpecificData
06-30 13:55:32.510   322  7212 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
06-30 13:55:32.510   322  7212 V LGCodecOSAL: Called LGconfigureCodecMETA
06-30 13:55:32.510   322  7212 V LGCodecOSAL: Called LGconfigureCodecMSG
06-30 13:55:32.510   322  7212 V LGCodecOSAL: Not support LGCodec
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-30 13:55:32.510   322  7212 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
06-30 13:55:32.510   322  7212 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
06-30 13:55:32.510   322  7212 I AwesomePlayer: Could not offload audio decode, try pcm offload
06-30 13:55:32.510   322  7212 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
06-30 13:55:32.510   322  7212 V AudioSystem: isOffloadSupported()
06-30 13:55:32.510   322  7212 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
06-30 13:55:32.510   322  7212 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] start ,mState=1
06-30 13:55:32.510   322  7212 V OMXCodec: init()
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
06-30 13:55:32.510   322  7212 V OMXCodec: allocateBuffers
06-30 13:55:32.510   322  7212 V OMXCodec: allocateBuffersOnPort portIndex=0
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
06-30 13:55:32.510   322  7212 V OMXCodec: allocateBuffersOnPort portIndex=1
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
06-30 13:55:32.510   322  7212 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fce0 on output port
06-30 13:55:32.510   322  7212 V OMXCodec: init() mAsyncCompletion wait!!! 
06-30 13:55:32.511  7111  7111 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
06-30 13:55:32.512  7111  7111 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-30 13:55:32.512  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-30 13:55:32.515   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-30 13:55:32.515   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
06-30 13:55:32.515   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
06-30 13:55:32.515   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
06-30 13:55:32.515   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
06-30 13:55:32.515   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
06-30 13:55:32.515   322  7212 V OMXCodec: init() mAsyncCompletion wait free! 
06-30 13:55:32.515   322  7212 V AwesomePlayer: finishAsyncPrepare_l() 
06-30 13:55:32.515   322  7212 V AudioCache: notify(0xb5474980, 5, 0, 0)
06-30 13:55:32.515   322  7212 V AudioCache: ignored
06-30 13:55:32.515   322  7212 V AudioCache: notify(0xb5474980, 1, 0, 0)
06-30 13:55:32.515   322  7212 V AudioCache: prepared
06-30 13:55:32.515   322  1386 V AudioCache: wait - success
06-30 13:55:32.515   322  1386 V MediaPlayerService: start
06-30 13:55:32.515   322  1386 V AwesomePlayer: play_l() 
06-30 13:55:32.515   322  1386 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
06-30 13:55:32.515   322  1386 V AwesomePlayer: createAudioPlayer_l
06-30 13:55:32.515   322  1386 V AwesomePlayer: seekAudioIfNecessary_l() 
06-30 13:55:32.515   322  1386 V AwesomePlayer: startAudioPlayer_l() 
06-30 13:55:32.515   322  1386 D AudioPlayer: start of Playback, useOffload 0
06-30 13:55:32.515   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-30 13:55:32.515   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
06-30 13:55:32.517   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
06-30 13:55:32.517   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
06-30 13:55:32.517   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
06-30 13:55:32.517   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
06-30 13:55:32.517   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
06-30 13:55:32.517   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049056
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
06-30 13:55:32.518   322  7214 V OMXCodec: allocateBuffersOnPort portIndex=1
06-30 13:55:32.518   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
06-30 13:55:32.519   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
06-30 13:55:32.519   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
06-30 13:55:32.519   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
06-30 13:55:32.519   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on output port
06-30 13:55:32.519   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
06-30 13:55:32.519   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
06-30 13:55:32.519   322  1386 V AudioCache: open(48000, 2, 0x0, 1, 4)
06-30 13:55:32.520   322  1386 V AudioCache: notify(0xb5474980, 6, 0, 0)
06-30 13:55:32.520   322  1386 V AudioCache: ignored
06-30 13:55:32.520   322  1386 V MediaPlayerService: wait for playback complete
06-30 13:55:32.521   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.521   322  7215 V AudioCache: memcpy(0xaf0f9000, 0xb100b000, 4096)
06-30 13:55:32.522   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.522   322  7215 V AudioCache: memcpy(0xaf0fa000, 0xb100b000, 4096)
06-30 13:55:32.523   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.523   322  7215 V AudioCache: memcpy(0xaf0fb000, 0xb100b000, 4096)
06-30 13:55:32.523   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.523   322  7215 V AudioCache: memcpy(0xaf0fc000, 0xb100b000, 4096)
06-30 13:55:32.523  7111  7111 V LGMDMManager: Create singleton instance
06-30 13:55:32.524   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.524   322  7215 V AudioCache: memcpy(0xaf0fd000, 0xb100b000, 4096)
06-30 13:55:32.524  7185  7185 D ProfileConfigQcom: [BTUI] HeadsetService is supported
06-30 13:55:32.524  7185  7185 D ProfileConfigQcom: Adding HeadsetService
06-30 13:55:32.524   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.524   322  7215 V AudioCache: memcpy(0xaf0fe000, 0xb100b000, 4096)
06-30 13:55:32.525  7185  7185 D ProfileConfigQcom: [BTUI] A2dpService is supported
06-30 13:55:32.525  7185  7185 D ProfileConfigQcom: Adding A2dpService
06-30 13:55:32.525  7185  7185 D ProfileConfigQcom: [BTUI] HidService is supported
06-30 13:55:32.525  7185  7185 D ProfileConfigQcom: Adding HidService
06-30 13:55:32.526  7185  7185 D ProfileConfigQcom: [BTUI] HealthService is supported
06-30 13:55:32.526  7185  7185 D ProfileConfigQcom: Adding HealthService
06-30 13:55:32.526  7185  7185 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
06-30 13:55:32.527  7185  7185 D ProfileConfigQcom: [BTUI] PanService is supported
06-30 13:55:32.527  7185  7185 D ProfileConfigQcom: Adding PanService
06-30 13:55:32.527  7185  7185 D ProfileConfigQcom: [BTUI] GattService is supported
06-30 13:55:32.528  7185  7185 D ProfileConfigQcom: Adding GattService
06-30 13:55:32.528  7185  7185 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
06-30 13:55:32.528  7185  7185 D ProfileConfigQcom: Adding BluetoothMapService
06-30 13:55:32.528  7185  7185 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
06-30 13:55:32.530  7185  7185 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
06-30 13:55:32.532   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.532   322  7215 V AudioCache: memcpy(0xaf0ff000, 0xb100b000, 4096)
06-30 13:55:32.532   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.532   322  7215 V AudioCache: memcpy(0xaf100000, 0xb100b000, 4096)
06-30 13:55:32.532   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.532   322  7215 V AudioCache: memcpy(0xaf101000, 0xb100b000, 4096)
06-30 13:55:32.533   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.533   322  7215 V AudioCache: memcpy(0xaf102000, 0xb100b000, 4096)
06-30 13:55:32.533   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.533   322  7215 V AudioCache: memcpy(0xaf103000, 0xb100b000, 4096)
06-30 13:55:32.534   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.534   322  7215 V AudioCache: memcpy(0xaf104000, 0xb100b000, 4096)
06-30 13:55:32.535   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.535   322  7215 V AudioCache: memcpy(0xaf105000, 0xb100b000, 4096)
06-30 13:55:32.538   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.538   322  7215 V AudioCache: memcpy(0xaf106000, 0xb100b000, 4096)
06-30 13:55:32.538  6809  6809 I UEI.SmartControl: Service initServices...
06-30 13:55:32.538   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.538   322  7215 V AudioCache: memcpy(0xaf107000, 0xb100b000, 4096)
06-30 13:55:32.539  6809  6809 D UEI.SmartControl: QS start get config
06-30 13:55:32.539   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.539   322  7215 V AudioCache: memcpy(0xaf108000, 0xb100b000, 4096)
06-30 13:55:32.539   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.539   322  7215 V AudioCache: memcpy(0xaf109000, 0xb100b000, 4096)
06-30 13:55:32.540   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.540   322  7215 V AudioCache: memcpy(0xaf10a000, 0xb100b000, 4096)
06-30 13:55:32.541   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.541   322  7215 V AudioCache: memcpy(0xaf10b000, 0xb100b000, 4096)
06-30 13:55:32.542   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.542   322  7215 V AudioCache: memcpy(0xaf10c000, 0xb100b000, 4096)
06-30 13:55:32.543   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.543   322  7215 V AudioCache: memcpy(0xaf10d000, 0xb100b000, 4096)
06-30 13:55:32.543  7047  7047 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-30 13:55:32.543   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.543   322  7215 V AudioCache: memcpy(0xaf10e000, 0xb100b000, 4096)
06-30 13:55:32.546  7185  7185 V LGMDMManagerInternal: Create singleton instance
06-30 13:55:32.552   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.552   322  7215 V AudioCache: memcpy(0xaf10f000, 0xb100b000, 4096)
06-30 13:55:32.552   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.552   322  7215 V AudioCache: memcpy(0xaf110000, 0xb100b000, 4096)
06-30 13:55:32.553   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.553   322  7215 V AudioCache: memcpy(0xaf111000, 0xb100b000, 4096)
06-30 13:55:32.554   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.554   322  7215 V AudioCache: memcpy(0xaf112000, 0xb100b000, 4096)
06-30 13:55:32.554   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.554   322  7215 V AudioCache: memcpy(0xaf113000, 0xb100b000, 4096)
06-30 13:55:32.555   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.555   322  7215 V AudioCache: memcpy(0xaf114000, 0xb100b000, 4096)
,06-30 13:55:32.555   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.555   322  7215 V AudioCache: memcpy(0xaf115000, 0xb100b000, 4096)
06-30 13:55:32.556   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.556   322  7215 V AudioCache: memcpy(0xaf116000, 0xb100b000, 4096)
06-30 13:55:32.557   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.557   322  7215 V AudioCache: memcpy(0xaf117000, 0xb100b000, 4096)
06-30 13:55:32.557   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.557   322  7215 V AudioCache: memcpy(0xaf118000, 0xb100b000, 4096)
06-30 13:55:32.558   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.558   322  7215 V AudioCache: memcpy(0xaf119000, 0xb100b000, 4096)
06-30 13:55:32.558   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.558   322  7215 V AudioCache: memcpy(0xaf11a000, 0xb100b000, 4096)
06-30 13:55:32.559   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.559   322  7215 V AudioCache: memcpy(0xaf11b000, 0xb100b000, 4096)
06-30 13:55:32.559   322  7215 V AudioCache: write(0xb100b000, 4096)
,06-30 13:55:32.560   322  7215 V AudioCache: memcpy(0xaf11c000, 0xb100b000, 4096)
06-30 13:55:32.560   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.560   322  7215 V AudioCache: memcpy(0xaf11d000, 0xb100b000, 4096)
06-30 13:55:32.561   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.561   322  7215 V AudioCache: memcpy(0xaf11e000, 0xb100b000, 4096)
06-30 13:55:32.561   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.561   322  7215 V AudioCache: memcpy(0xaf11f000, 0xb100b000, 4096)
06-30 13:55:32.562   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.562   322  7215 V AudioCache: memcpy(0xaf120000, 0xb100b000, 4096)
06-30 13:55:32.562   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.562   322  7215 V AudioCache: memcpy(0xaf121000, 0xb100b000, 4096)
06-30 13:55:32.563   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.563   322  7215 V AudioCache: memcpy(0xaf122000, 0xb100b000, 4096)
06-30 13:55:32.564   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.564   322  7215 V AudioCache: memcpy(0xaf123000, 0xb100b000, 4096)
06-30 13:55:32.564   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.564   322  7215 V AudioCache: memcpy(0xaf124000, 0xb100b000, 4096)
06-30 13:55:32.566   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.566   322  7215 V AudioCache: memcpy(0xaf125000, 0xb100b000, 4096)
06-30 13:55:32.566   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.566   322  7215 V AudioCache: memcpy(0xaf126000, 0xb100b000, 4096)
06-30 13:55:32.567   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.567   322  7215 V AudioCache: memcpy(0xaf127000, 0xb100b000, 4096)
06-30 13:55:32.567   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.567   322  7215 V AudioCache: memcpy(0xaf128000, 0xb100b000, 4096)
06-30 13:55:32.568   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.568   322  7215 V AudioCache: memcpy(0xaf129000, 0xb100b000, 4096)
06-30 13:55:32.568   322  7215 V AudioCache: write(0xb100b000, 4096)
06-30 13:55:32.568   322  7215 V AudioCache: memcpy(0xaf12a000, 0xb100b000, 4096)
06-30 13:55:32.568   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
06-30 13:55:32.568   322  7215 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
06-30 13:55:32.568   322  7215 V AwesomePlayer: postAudioEOS() 
06-30 13:55:32.568   322  7215 V AudioCache: write(0xb100b000, 280)
06-30 13:55:32.568   322  7215 V AudioCache: memcpy(0xaf12b000, 0xb100b000, 280)
06-30 13:55:32.570   322  7212 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
06-30 13:55:32.570   322  7212 V AwesomePlayer: onStreamDone
06-30 13:55:32.570   322  7212 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
06-30 13:55:32.570   322  7212 V AudioCache: notify(0xb5474980, 2, 0, 0)
06-30 13:55:32.570   322  7212 V AudioCache: playback complete
06-30 13:55:32.570   322  7212 V AwesomePlayer: pause_l() 
06-30 13:55:32.570   322  7212 V AudioCache: notify(0xb5474980, 7, 0, 0)
06-30 13:55:32.570   322  7212 V AudioCache: ignored
06-30 13:55:32.570   322  7212 V AwesomePlayer: cancelPlayerEvents
06-30 13:55:32.570   322  1386 V AudioCache: wait - success
06-30 13:55:32.570   322  1386 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
06-30 13:55:32.570   322  7212 D AudioPlayer: Pause Playback at 1068125
06-30 13:55:32.570   322  1386 V AwesomePlayer: reset_l() 
06-30 13:55:32.571   322  1386 V AudioCache: notify(0xb5474980, 8, 0, 0)
06-30 13:55:32.571   322  1386 V AudioCache: ignored
06-30 13:55:32.571   322  1386 V AwesomePlayer: cancelPlayerEvents
06-30 13:55:32.571   322  1386 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
06-30 13:55:32.571   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
06-30 13:55:32.571   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
06-30 13:55:3,2.571   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
06-30 13:55:32.571   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 1
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
06-30 13:55:32.571   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
06-30 13:55:32.572   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
06-30 13:55:32.572   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-30 13:55:32.572   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
06-30 13:55:32.572   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
06-30 13:55:32.572   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
06-30 13:55:32.572   322  7214 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
06-30 13:55:32.572   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
06-30 13:55:32.572   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
06-30 13:55:32.572   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
06-30 13:55:32.573   322  1386 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
06-30 13:55:32.573   322  1386 D AudioPlayer: AudioPlayer releasing audio source
06-30 13:55:32.573   322  1386 D AudioPlayer: AudioPlayer done releasing audio source
06-30 13:55:32.574   322  1386 V AwesomePlayer: reset_l() 
06-30 13:55:32.574   322  1386 V AwesomePlayer: cancelPlayerEvents
06-30 13:55:32.574   322  1386 V AwesomePlayer: ~AwesomePlayer call
06-30 13:55:32.574   322  1386 V AwesomePlayer: reset_l() 
06-30 13:55:32.574   322  1386 V AwesomePlayer: cancelPlayerEvents
06-30 13:55:32.575  7111  7211 V SoundPool: close(31)
06-30 13:55:32.575  7111  7211 V SoundPool: pointer = 0x9fe45000, size = 205080, sampleRate = 48000, numChannels = 2
06-30 13:55:32.613  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,06-30 13:55:32.614  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
06-30 13:55:32.616  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:434
06-30 13:55:32.635  7185  7185 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:32.637  7185  7185 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:32.638  7185  7185 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,06-30 13:55:32.638  7185  7185 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:32.639  7185  7185 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:32.639  7185  7185 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,06-30 13:55:32.644  7134  7134 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
06-30 13:55:32.692  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 13:55:32.692  1036  1118 D Tethering: InitialState.processMessage what=4
,06-30 13:55:32.695  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 13:55:32.695  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:32.695  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:32.695  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:32.695  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:32.696  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 13:55:32.699  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:32.699  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-30 13:55:32.699  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:32.699  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:32.699   318   894 D SoftapController: Softap fwReload - Ok
06-30 13:55:32.699  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 13:55:32.699  1036  1538 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (821ms)
06-30 13:55:32.702   318   894 D CommandListener: Setting iface cfg
06-30 13:55:32.702   318   894 D CommandListener: Trying to bring down wlan0
06-30 13:55:32.702   318   894 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:55:32.704  1036  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,06-30 13:55:32.708  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 13:55:32.708  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:32.708  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 13:55:32.710  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
06-30 13:55:32.711  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:32.712  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
06-30 13:55:32.712  1036  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
06-30 13:55:32.712  1036  1538 D WifiMonitor: connecting to supplicant
06-30 13:55:32.712  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:32.713  1036  1538 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
06-30 13:55:32.713  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:32.713  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 13:55:32.712  7225  7225 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:32.712  7225  7225 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:32.726  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:32.726  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:32.726  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:32.726  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:32.727  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 13:55:32.727  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:32.727  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-30 13:55:32.727  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:32.727  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:32.727  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 13:55:32.727  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,06-30 13:55:32.738  7225  7225 I wpa_supplicant: Successfully initialized wpa_supplicant
06-30 13:55:32.749  7162  7228 V FormManager: Network unavailable.
06-30 13:55:32.751  7162  7227 W FormManager: Network not available. Please check & try again.
06-30 13:55:32.751  7162  7228 V FormManager: Network unavailable.
,06-30 13:55:32.755  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:32.764  7225  7225 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 13:55:32.765  7225  7225 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,06-30 13:55:32.767  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:32.780  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:32.874  1036  1903 D WifiServiceImplEx: setWifiEnabled: false pid=6956, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
06-30 13:55:32.875  1036  1903 D WifiService: setWifiEnabled: false pid=6956, uid=10118
06-30 13:55:32.875  1036  1903 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,06-30 13:55:32.879  7225  7225 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 13:55:32.887  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:32.887  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:32.887  1036  1036 D Ulp_jni : JNI:system_update. Event-4
06-30 13:55:32.908  6809  6809 I UEI.SmartControl: Supports setup maps: true
,06-30 13:55:32.913  6809  6809 D UEI.SmartControl: QS start statue = true Error code = 0
,06-30 13:55:32.913  6809  6809 I UEI.SmartControl: QS version = v2.7.10.1_RC1
06-30 13:55:32.913  6809  6809 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
06-30 13:55:32.914  6809  6809 I UEI.SmartControl: ### init IR Blaster...
06-30 13:55:32.917  6809  6809 D serial_port: Configuring serial port
06-30 13:55:32.917  6809  6809 E UEI.SmartControl: UEIBLaster setting for 616
06-30 13:55:32.917  6809  6809 I UEI.SmartControl: Setting serial record hearder size = 2
06-30 13:55:32.917  6809  6809 I UEI.SmartControl: configuring settings for MAXQ616
06-30 13:55:32.917  6809  6809 I UEI.SmartControl: Get version...
06-30 13:55:32.933  6809  7230 D UEI.SmartControl: serial port data available: 21
,06-30 13:55:32.953  7225  7225 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,06-30 13:55:32.959  6809  6809 D UEI.SmartControl: MAXQ616 A2-X4 software.
06-30 13:55:32.959  6809  6809 I UEI.SmartControl: IR Blaster version: 256702256704300002
06-30 13:55:32.960  6809  6809 I UEI.SmartControl: QS saving settings...
06-30 13:55:32.961  6809  6809 D UEI.SmartControl: IR Blaster version: 25672567
06-30 13:55:32.970  7225  7225 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
06-30 13:55:32.970  7225  7225 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,06-30 13:55:32.978  6809  7230 D UEI.SmartControl: serial port data available: 4
06-30 13:55:33.008  6809  7233 I UEI.SmartControl: Device manager: loading config....
06-30 13:55:33.009  6809  6809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
06-30 13:55:33.009  6809  7233 D UEI.SmartControl: ----------- loading internal config...
06-30 13:55:33.011  6809  6809 E UEI.SmartControl: Services init done
06-30 13:55:33.011  6809  6809 D UEI.SmartControl: QS Service init finished
,06-30 13:55:33.017  6809  6809 D UEI.SmartControl: QS Service version name: 2.1.91
06-30 13:55:33.017  6809  6809 D UEI.SmartControl: QS Service version code: 201091
06-30 13:55:33.017  6809  6809 D UEI.SmartControl: Service requested: Control
06-30 13:55:33.021  6809  7233 E UEI.SmartControl: Loading SETTINGS...
06-30 13:55:33.023  6809  6809 D UEI.SmartControl: Request IControl service: devices are loaded...
06-30 13:55:33.027  7111  7111 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
06-30 13:55:33.028  6809  6809 D UEI.SmartControl: Internal service binding...
06-30 13:55:33.028  6809  6824 I UEI.SmartControl: ------ IControl API: 11
06-30 13:55:33.028  6809  6824 D UEI.SmartControl: File observer start...
06-30 13:55:33.029  6809  6824 E UEI.SmartControl: IR Port is disabled: false
06-30 13:55:33.029  6809  6824 D UEI.SmartControl: Starting file observer...
06-30 13:55:33.029  6809  6824 I UEI.SmartControl: Registering callback...
,06-30 13:55:33.030  6809  6825 I UEI.SmartControl: ------ IControl API: 19
06-30 13:55:33.031  6809  6825 I UEI.SmartControl: Registering Services Ready callback...
06-30 13:55:33.034  6809  7233 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
06-30 13:55:33.048  6809  7232 I UEI.SmartControl: Notify AllClients services are ready: 0
,06-30 13:55:33.050  7111  7127 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
06-30 13:55:33.050  6809  7232 D UEI.SmartControl: -----service ready thread exits
,06-30 13:55:33.052  7111  7209 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
06-30 13:55:33.053  7111  7209 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
06-30 13:55:33.053  7111  7111 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
06-30 13:55:33.053  7111  7111 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
06-30 13:55:33.054  6809  6824 I UEI.SmartControl: ------ IControl API: 8
06-30 13:55:33.055  7111  7111 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
06-30 13:55:33.056  7111  7111 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
06-30 13:55:33.056  7111  7111 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
06-30 13:55:33.056  7111  7111 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
06-30 13:55:33.058  7111  7111 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
06-30 13:55:33.058  7111  7111 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
06-30 13:55:33.061  7111  7111 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,06-30 13:55:33.064  7111  7111 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
06-30 13:55:33.065  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
06-30 13:55:33.066  7111  7111 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-30 13:55:33.066  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
06-30 13:55:33.067  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
06-30 13:55:33.068  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
06-30 13:55:33.069  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
06-30 13:55:33.070  7111  7111 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1467287733069]
06-30 13:55:33.074  7111  7111 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,06-30 13:55:33.078  1036  1051 I ActivityManager: Killing 6165:com.android.gallery3d/u0a27 (adj 15): empty #17
06-30 13:55:33.106  7111  7238 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,06-30 13:55:33.185  1036  1051 I ActivityManager: Killing 6608:com.lge.email/u0a23 (adj 15): empty #18
,06-30 13:55:33.305  1036  1667 W libprocessgroup: failed to open /acct/uid_10027/pid_6165/cgroup.procs: No such file or directory
,06-30 13:55:33.314  1036  1958 W libprocessgroup: failed to open /acct/uid_10023/pid_6608/cgroup.procs: No such file or directory
06-30 13:55:33.315  7111  7111 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
06-30 13:55:33.317  7111  7111 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
06-30 13:55:33.317  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
06-30 13:55:33.317  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
06-30 13:55:33.317  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
06-30 13:55:33.318  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
06-30 13:55:33.318  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
06-30 13:55:33.327  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,06-30 13:55:33.448  7225  7225 E wpa_supplicant: USIM:  scard_init function
06-30 13:55:33.449  7225  7225 I wpa_supplicant: Trying to associate with SSID 'NG700'
,06-30 13:55:33.587  7225  7225 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
06-30 13:55:33.588  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 13:55:33.596  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:33.596  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:33.596  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:33.596  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:33.597  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 13:55:33.597  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:33.597  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-30 13:55:33.597  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:33.597  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:33.597  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 13:55:33.597  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-30 13:55:33.598  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 13:55:33.603  7225  7225 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 13:55:33.603  7225  7225 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-30 13:55:33.718  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,06-30 13:55:33.719  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,06-30 13:55:33.720  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
06-30 13:55:33.721  1036  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
06-30 13:55:33.724  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,06-30 13:55:33.725  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,06-30 13:55:33.726  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:33.727  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:33.728  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT 0 0
,06-30 13:55:33.729  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:33.730  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:33.732  1036  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,06-30 13:55:33.732  1036  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,06-30 13:55:33.733  1036  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
06-30 13:55:33.735  1036  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
06-30 13:55:33.736  1036  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,06-30 13:55:33.737  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:33.738  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:33.738  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:55:33.738  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:33.738  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:55:33.739  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 13:55:33.739  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:33.739  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true,
,06-30 13:55:33.742  1036  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
06-30 13:55:33.743  1941  1941 D WfdService: Waiting for WifiP2p enabling
06-30 13:55:33.744  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:33.746  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:33.747  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:33.748  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-30 13:55:33.749  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:33.750  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:33.750  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:33.750  1036  1538 D WifiNative-wlan0: SET update_config 1: returned true
06-30 13:55:33.750  1036  1538 D WifiConfigStore: Loading config and enabling all networks 
06-30 13:55:33.750  1036  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
06-30 13:55:33.751  1036  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
,06-30 13:55:33.760  1036  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-30 13:55:33.761  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:33.766  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:33.772  1036  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
06-30 13:55:33.773  1036  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-30 13:55:33.775  1036  1538 D WifiStateMachine: enableVerboseLogging : level 2
06-30 13:55:33.775  1036  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
06-30 13:55:33.776  1036  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
06-30 13:55:33.776  1036  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
06-30 13:55:33.776  1036  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
06-30 13:55:33.776  1036  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
06-30 13:55:33.777  1036  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
06-30 13:55:33.777  1036  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
06-30 13:55:33.777  1036  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
06-30 13:55:33.777  1036  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,06-30 13:55:33.779  1036  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
06-30 13:55:33.779  1036  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
06-30 13:55:33.780  1036  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
06-30 13:55:33.780  1036  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
06-30 13:55:33.780  1036  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
06-30 13:55:33.781  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:55:33.781  1036  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
06-30 13:55:33.781  1941  1941 D WfdsService: Supplicant Connection state is changed : true
06-30 13:55:33.781  1941  2340 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-30 13:55:33.781  1941  2340 D WfdsService: Set the WFDS Monitor: true
06-30 13:55:33.781  1036  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
06-30 13:55:33.781  1941  2340 D WfdsMonitor: WfdsMonitorThread create
06-30 13:55:33.781  1036  1538 D WifiNative-HAL: Setting external_sim to 1
06-30 13:55:33.781  1036  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
06-30 13:55:33.781  1941  2340 D WfdsMonitor: WFDS Monitor is created and started
06-30 13:55:33.781  1941  2340 D WfdsService: WiFi: Supplicant connection re-established
06-30 13:55:33.782  1036  1538 D WifiNative-wlan0: SET external_sim 1: returned true
06-30 13:55:33.782  1036  1538 I WifiNative-HAL: startHal
06-30 13:55:33.782  1036  1538 D wifi    : setting scan oui 0xaf650160
06-30 13:55:33.782  1941  7243 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-30 13:55:33.782  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:55:33.782  1036  1538 I WifiNative-HAL: startHal
06-30 13:55:33.782  1036  1538 D wifi    : setting scan oui 0xaf650160
06-30 13:55:33.783  1941  7243 E CtrlSupplicant: Succeed to open control connection
06-30 13:55:33.783  1036  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
06-30 13:55:33.783  1941  7243 E CtrlSupplicant: Succeed to open monitor connection
06-30 13:55:33.783  1941  7243 D WfdsMonitor: Supplicant connection established
06-30 13:55:33.783  1941  2340 D WfdsService: Connected to the supplicant for wfds
06-30 13:55:33.784  1036  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
06-30 13:55:33.784  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
06-30 13:55:33.784  7225  7225 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
06-30 13:55:33.784  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:33.784  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
06-30 13:55:33.785  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-30 13:55:33.785  7225  7225 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
06-30 13:55:33.786  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-30 13:55:33.786  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
06-30 13:55:33.786  7225  7225 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
06-30 13:55:33.786  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
06-30 13:55:33.786  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-30 13:55:33.786  7225  7225 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-30 13:55:33.787  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-30 13:55:33.787  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-30 13:55:33.788  7225  7225 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
06-30 13:55:33.788  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-30 13:55:33.788  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
06-30 13:55:33.788  7225  7225 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
06-30 13,:55:33.788  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
06-30 13:55:33.788  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-30 13:55:33.788  7225  7225 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-30 13:55:33.789  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-30 13:55:33.789  1036  1538 E WifiNative: : [299,060,232 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
06-30 13:55:33.789  1036  1538 D WifiNative-wlan0: doBoolean: RECONNECT
,06-30 13:55:33.790  1036  1538 D WifiNative-wlan0: RECONNECT: returned true
06-30 13:55:33.790  1036  1538 D WifiNative-wlan0: doString: [STATUS]
06-30 13:55:33.791  1036  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
06-30 13:55:33.791  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
06-30 13:55:33.791  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
06-30 13:55:33.791  1036  7239 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 13:55:33.792  1036  7239 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 13:55:33.793  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.793  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
06-30 13:55:33.793  1036  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
06-30 13:55:33.794  1036  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
06-30 13:55:33.794  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 13:55:33.794  1036  1036 D RttService: SCAN_AVAILABLE : 3
06-30 13:55:33.794  1036  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
06-30 13:55:33.794  1036  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.794  1036  1556 I WifiNative-HAL: startHal
06-30 13:55:33.794  1036  1538 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:33.794  1036  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf650160
06-30 13:55:33.794  1036  1556 D wifi    : failed to get capabilities : -3
06-30 13:55:33.794  1036  1556 E WifiScanningService: could not get scan capabilities
06-30 13:55:33.795  1036  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.795  1036  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:33.796  1036  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:33.796   318   894 D CommandListener: Setting iface cfg
06-30 13:55:33.796   318   894 D CommandListener: Trying to bring up p2p0
06-30 13:55:33.796  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
06-30 13:55:33.796  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 13:55:33.796  1036  1537 D LGWifiP2pService: P2pEnablingState
06-30 13:55:33.796  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.796  1036  1537 D LGWifiP2pService: P2p socket connection successful
06-30 13:55:33.796  1036  1537 D LGWifiP2pService: P2pEnabledState
06-30 13:55:33.797  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
06-30 13:55:33.797  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
06-30 13:55:33.798  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
06-30 13:55:33.798  1941  1941 D WfdsService: WifiP2pState is changed : true
06-30 13:55:33.798  1941  2340 D WfdsService: Receive the WFDS_ENABLE Method
06-30 13:55:33.798  1941  2340 D WfdsService: Set the WFDS Monitor: true
06-30 13:55:33.798  1941  2340 D WfdsService: Connected to the supplicant for wfds
06-30 13:55:33.798  1941  2340 D WfdsJNI : doCommand: WFDS_SET TRUE
06-30 13:55:33.798  7225  7225 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
06-30 13:55:33.798  1941  2340 D WfdsService: selectPreferredScanChannel [36]
06-30 13:55:33.798  1941  2340 D WfdsService: STATE : WfdsEnabledState - enter: this device, mac 02:9a:02:7f:fb:5d
06-30 13:55:33.799  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-30 13:55:33.799  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
06-30 13:55:33.799  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
06-30 13:55:33.799  1941  1941 D WfdsService: isConnected: false
06-30 13:55:33.800  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
06-30 13:55:33.800  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-30 13:55:33.800  1036  1537 D LGWifiP2pService: before postfix = G3
06-30 13:55:33.800  1036  1537 D WifiServerServiceExt: postfix byte check : 2
06-30 13:55:33.800  1036  1537 D LGWifiP2pService: after postfix = G3
06-30 13:55:33.800  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
06-30 13:55:33.803  1036  1538 E WifiStateMachine:  WaitForP2pDisableState what:132106 1 0
06-30 13:55:33.803  1036  1538 E WifiStateMachine:  SupplicantStartedState what:132106 1 0
06-30 13:55:33.803  1036  1538 E WifiStateMachine:  DefaultState what:132106 1 0
06-30 13:55:33.804  1036  1538 E WifiStateMachine: Error! unhandled message{ when=-56ms what=132106 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.804  1036  1538 E WifiStateMachine:  WaitForP2pDisableState what:132096 -100 0
06-30 13:55:33.804  1036  1538 E WifiStateMachine:  SupplicantStartedState what:132096 -100 0
06-30 13:55:33.805  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
06-30 13:55:33.805  1036  1036 D RttService: SCAN_AVAILABLE : 1
06-30 13:55:33.805  1036  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.805  1036  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.806  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
06-30 13:55:33.806  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
06-30 13:55:33.807  1036  1538 E WifiStateMachine:  DefaultState what:132096 -100 0
06-30 13:55:33.807  1036  1538 E WifiStateMachine: Error! unhandled message{ when=-59ms what=132096 arg1=-100 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.807  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
06-30 13:55:33.807  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
06-30 13:55:33.807  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
06-30 13:55:33.807  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_FREQUENCY_BAND 0 0
06-30 13:55:33.808  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
06-30 13:55:33.808  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
06-30 13:55:33.808  1036  1538 E WifiStateMachine:  WaitForP2pDisableState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=299079  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:33.808  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,06-30 13:55:33.809  1036  1538 E WifiStateMachine:  WaitForP2pDisableState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:33.809  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
06-30 13:55:33.809  1036  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:33.809  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
06-30 13:55:33.809  1036  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:33.811  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
,06-30 13:55:33.812  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
06-30 13:55:33.813  1941  1941 D WfdsService: Update P2p Interface State: 3
06-30 13:55:33.813  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
06-30 13:55:33.813  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
06-30 13:55:33.814  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
06-30 13:55:33.814  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
06-30 13:55:33.815  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
06-30 13:55:33.815  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
06-30 13:55:33.816  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
06-30 13:55:33.816  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
06-30 13:55:33.816  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:33.817  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:55:33.818  7162  7241 W FormManager: Network not available. Please check & try again.
06-30 13:55:33.818  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:33.820  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:33.825  6778  6778 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-30 13:55:33.825  6778  6778 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
06-30 13:55:33.826  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
06-30 13:55:33.826  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
06-30 13:55:33.826  1036  1537 D LGWifiP2pService: InactiveState
06-30 13:55:33.826  1036  1537 D LGWifiP2pService: InactiveState{ when=-24ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.826  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.826  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f0a8cda
06-30 13:55:33.826  1036  1537 D LGWifiP2pService: P2pDisablingState
06-30 13:55:33.827  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.827  1036  1537 D LGWifiP2pService: DefaultState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.827  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.827  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:55:33.831  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-5ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: p2p socket connection lost
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: P2pDisabledState
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.831  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.831  1036  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:33.831  1941  1941 D WfdsService: WifiP2pState is changed : false
06-30 13:55:33.832  1941  2340 W WfdsService: DefaultState - msg [9441285] is not handled
06-30 13:55:33.832  1941  2340 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
06-30 13:55:33.832  1941  2340 D WfdsService: Set the WFDS Monitor: false
06-30 13:55:33.832  1941  2340 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:55:33.832  1941  2340 D WfdsService: STATE : WfdsDisabledState - enter
06-30 13:55:33.832  1941  2342 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
06-30 13:55:33.833  1036  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
06-30 13:55:33.833   318   894 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:55:33.833  1036  1036 E WifiServerServiceExt: No p2p device connected
06-30 13:55:33.834  1941  7243 D CtrlSupplicant: Received on exit socket, terminate
06-30 13:55:33.834  1941  7243 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
06-30 13:55:33.834  1941  7243 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
06-30 13:55:33.834  1941  7243 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
06-30 13:55:33.834  1941  2340 W WfdsService: DefaultState - msg [9445378] is not handled
06-30 13:55:33.835  6778  6778 V [BNRBootReceiver]: Boot Receiver Return
06-30 13:55:33.836  1036  1036 D WifiHS20: hidePasspointNotification off =false
06-30 13:55:33.836  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
06-30 13:55:33.836  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:33.837  1036  1538 D WifiNative-p2p0: doBoolean: TERMINATE
06-30 13:55:33.837  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:33.837  1036  1538 D WifiNative-p2p0: TERMINATE: returned true
06-30 13:55:33.837  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 13:55:33.837  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:33.837  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 13:55:33.837  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:33.837  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, retu,rning read-only value.
06-30 13:55:33.837  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:55:33.839  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:33.840  7162  7242 V FormManager: Network unavailable.
06-30 13:55:33.840  4818  7249 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:55:33.841  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
06-30 13:55:33.841  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_SET_FREQUENCY_BAND 0 0
,06-30 13:55:33.842  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=299113  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:33.842  1036  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=299113  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:33.844  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:33.845  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:33.845  7162  7242 V FormManager: Network unavailable.
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:33.845  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:33.845  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:33.845  4818  7251 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:33.846  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
06-30 13:55:33.848  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:55:33.848  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:55:33.848  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:33.848  4818  7251 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:55:33.850  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:55:33.856  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:33.858  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:33.865  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:33.865  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:33.866  7111  7111 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-30 13:55:33.872  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:33.874  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:33.879  7162  7253 W FormManager: Network not available. Please check & try again.
06-30 13:55:33.882  7162  7254 V FormManager: Network unavailable.
06-30 13:55:33.882  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:33.892  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:33.892  1036  1940 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,06-30 13:55:33.894  7162  7254 V FormManager: Network unavailable.
06-30 13:55:33.899  1036  1118 D BluetoothManagerService: Message: 1
06-30 13:55:33.899  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-30 13:55:33.899  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,06-30 13:55:33.900  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:33.900  1036  1036 D Ulp_jni : JNI:system_update. Event-4
06-30 13:55:33.911  1036  1118 D BluetoothManagerService: Message: 20
06-30 13:55:33.912  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2989562b:true
06-30 13:55:33.912  7185  7185 D BluetoothAdapterState: make
06-30 13:55:33.915  7185  7185 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
06-30 13:55:33.915  7185  7185 I bluedroid-qcom: init
06-30 13:55:33.916  7185  7256 I BluetoothAdapterState: Entering OffState
06-30 13:55:33.916  7185  7185 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,06-30 13:55:33.917  7185  7185 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
06-30 13:55:33.917  7185  7185 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
06-30 13:55:33.917  7185  7185 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
06-30 13:55:33.917  7185  7185 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
06-30 13:55:33.918  7185  7185 I bluedroid-qcom: get_profile_interface socket
06-30 13:55:33.918  7185  7185 I bluedroid-qcom: get_profile_interface map_client
06-30 13:55:33.919  7185  7260 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
06-30 13:55:33.921  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
06-30 13:55:33.921  1036  1118 D BluetoothManagerService: Message: 40
06-30 13:55:33.921  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-30 13:55:33.922  7185  7200 I bluedroid-qcom: config_hci_snoop_log
06-30 13:55:33.922  7185  7260 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-30 13:55:33.923  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-30 13:55:33.923  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
06-30 13:55:33.924  7185  7260 D BluetoothAdapterProperties: Name is: G3
06-30 13:55:33.924  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
06-30 13:55:33.924  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
06-30 13:55:33.922  7259  7259 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:33.922  7259  7259 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:33.927  7225  7225 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
06-30 13:55:33.927  7225  7225 I wpa_supplicant: monitor socket send errors count : 1
06-30 13:55:33.927  7225  7225 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
06-30 13:55:33.928  1036  7239 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
06-30 13:55:33.928  1036  7239 D WifiMonitor: Dropping event because (p2p0) is stopped
06-30 13:55:33.929  7185  7256 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-30 13:55:33.929  7185  7256 D BluetoothAdapterProperties: Setting state to 11
06-30 13:55:33.929  7185  7256 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-30 13:55:33.929  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:33.929  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-30 13:55:33.929  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,06-30 13:55:33.930  7259  7259 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
06-30 13:55:33.930  7259  7259 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
06-30 13:55:33.930  7259  7259 I LGFTMITEM: [GET_FTM][id=8], offset=16384
06-30 13:55:33.931  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:33.932  7185  7256 I LGBluetoothServiceJni: classInitNative: succeeds
06-30 13:55:33.933  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:33.933  7259  7259 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
06-30 13:55:33.936  7047  7047 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
06-30 13:55:33.937  7259  7259 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
06-30 13:55:33.937  7259  7259 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
06-30 13:55:33.942  7185  7256 D BluetoothBondStateMachine: make
,06-30 13:55:33.943  7185  7185 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:55:33.944  7185  7185 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:33.944  7185  7185 V BluetoothPbapReceiver: ***********state = 11
06-30 13:55:33.944  7185  7256 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:33.944  7185  7256 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
06-30 13:55:33.944  7185  7256 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:33.944  7185  7256 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
06-30 13:55:33.945  7185  7256 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
06-30 13:55:33.945  7185  7261 I BluetoothBondStateMachine: StableState(): Entering Off State
06-30 13:55:33.947  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 13:55:33.950  7185  7256 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:33.954  7225  7225 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
06-30 13:55:33.954  1036  7239 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
06-30 13:55:33.954  1036  7239 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
06-30 13:55:33.954  1036  7239 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,06-30 13:55:33.955  7225  7225 W wpa_supplicant: USIM:  scard_deinit function
06-30 13:55:33.956  1036  1118 D Tethering: InitialState.processMessage what=4
06-30 13:55:33.957  1036  7239 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
06-30 13:55:33.957  1036  7239 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 13:55:33.957  1036  7239 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 13:55:33.958  1036  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=299229
06-30 13:55:33.958  1036  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=299229
06-30 13:55:33.958  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=299229  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
06-30 13:55:33.959  1036  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=299230  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
06-30 13:55:33.960  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:33.963  7185  7185 D HeadsetService: Received start request. Starting profile...
06-30 13:55:33.964  7185  7185 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 13:55:33.964  7185  7185 D LGBluetoothHfpAdapter: Version 1.6
06-30 13:55:33.966  7185  7256 E BluetoothAdapterService: File transfer profiles supported!!
,06-30 13:55:33.968  7185  7185 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:55:33.968  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:33.968  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 13:55:33.970  7185  7185 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,06-30 13:55:33.970  7185  7185 D HeadsetStateMachine: make
06-30 13:55:33.970  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:33.973  1036  1118 D Tethering: MasterInitialState.processMessage what=3
06-30 13:55:33.974  1036  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:33.976  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:33.977  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:33.978  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:55:33.980  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:33.980  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:33.980  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:33.980  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:33.981  7185  7256 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:33.982  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 13:55:33.983  1036  1118 D Tethering: MasterInitialState.processMessage what=3
06-30 13:55:33.990  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:33.992  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:33.993  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:33.997  7185  7185 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:33.997  7185  7185 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 13:55:34.079  7225  7225 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
06-30 13:55:34.079  1036  7239 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
06-30 13:55:34.079  1036  7239 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
06-30 13:55:34.079  1036  7239 D WifiMonitor: Disconnecting from the supplicant, no more events
06-30 13:55:34.079  1036  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 25 0
,06-30 13:55:34.092  1036  1052 I art     : Explicit concurrent mark sweep GC freed 94896(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.098ms total 104.866ms
06-30 13:55:34.094  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:34.094  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-30 13:55:34.094  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:34.094  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:34.094  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 13:55:34.094  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 13:55:34.094  7185  7185 D HeadsetStateMachine: max_hf_connections = 1
06-30 13:55:34.095  7185  7185 I bluedroid-qcom: get_profile_interface handsfree
06-30 13:55:34.095  7047  7047 D BluetoothPermissionRequest: onReceive
06-30 13:55:34.095  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:34.095  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:34.097  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,06-30 13:55:34.097  7185  7185 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
06-30 13:55:34.098   322  2154 V AudioPolicyService: registerClient() client 0xb558a2e0, uid 1002
06-30 13:55:34.098   322   322 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-30 13:55:34.098   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:55:34.098   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:55:34.098  7185  7185 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-30 13:55:34.099   322  1387 V AudioFlinger: registerClient() client 0xb1433f10, pid 7185
06-30 13:55:34.099  7185  7185 V ToneGenerator: Create Track: 0xb4928080
06-30 13:55:34.099  7185  7185 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-30 13:55:34.099  7185  7185 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
06-30 13:55:34.099   322  2154 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 13:55:34.100   322  2154 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
06-30 13:55:34.100   322  2154 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:55:34.100   322  2154 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:55:34.100  7185  7185 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-30 13:55:34.101   322  1387 I AudioFlinger: isAudioPlaybackHookOn() false
06-30 13:55:34.101   322  1386 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 13:55:34.101   322  1386 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
06-30 13:55:34.101   322  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:55:34.101   322  1386 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:55:34.102  5963  5963 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
06-30 13:55:34.103   322  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:34.103   322  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
,06-30 13:55:34.103   322  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:34.103  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:34.103   322  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:34.103  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:34.103  1603  2072 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:34.103  1603  2072 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:34.103  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:34.104  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:34.104  1603  2072 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,06-30 13:55:34.104  1603  2072 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:34.104  3192  3214 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:34.104  3192  3214 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:34.104  3192  3214 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:34.104  3192  3214 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:34.104  7185  7185 V AudioSystem: getLatency() output 2, latency 50
06-30 13:55:34.104  1852  4478 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:34.104  1852  4478 V AudioSystem: ioConfigChanged() opening already existing output! 4
,06-30 13:55:34.104  1852  4478 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:34.104  1852  4478 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:34.104  7185  7185 V AudioSystem: getFrameCount() output 2, frameCount 960
06-30 13:55:34.104  7185  7185 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-30 13:55:34.105  7185  7185 V AudioTrack: createTrack_l() output 2 afLatency 50
06-30 13:55:34.105  7185  7202 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:34.105  7185  7256 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:34.105   322  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-30 13:55:34.105   322  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-30 13:55:34.105   322  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-30 13:55:34.105   322  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-30 13:55:34.105   322  1386 V AudioFlinger: createTrack() lSessionId: 22
06-30 13:55:34.105  7185  7202 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
,06-30 13:55:34.106  7185  7202 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:34.106  7185  7202 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-30 13:55:34.107  7185  7185 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-30 13:55:34.108   322  1386 V AudioFlinger: acquiring 22 from 7185, for 7185
06-30 13:55:34.108   322  1386 V AudioFlinger:  added new entry for 22
06-30 13:55:34.108  7185  7185 V ToneGenerator: ToneGenerator INIT OK, time: 299393
06-30 13:55:34.108  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.108  7185  7256 E BluetoothAdapterService: File transfer profiles supported!!
,06-30 13:55:34.109  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
,06-30 13:55:34.111  7185  7185 D A2dpService: Received start request. Starting profile...
06-30 13:55:34.111  7185  7256 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:34.111  7185  7185 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 13:55:34.112  7185  7185 V Avrcp   : make
06-30 13:55:34.113  7185  7185 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-30 13:55:34.113  7185  7185 I bluedroid-qcom: get_profile_interface avrcp
06-30 13:55:34.114  7185  7263 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-30 13:55:34.114  7185  7256 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:34.114  7185  7263 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:55:34.114  7185  7263 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:55:34.114  7185  7263 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-30 13:55:34.115   322   322 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7185
06-30 13:55:34.115   322   322 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-30 13:55:34.115   322   322 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-30 13:55:34.115   322   322 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-30 13:55:34.115   322   322 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 13:55:34.115   322   322 V voice   : voice_set_parameters: exit with code(0)
06-30 13:55:34.115   322   322 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-30 13:55:34.115   322   322 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-30 13:55:34.115   322   322 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 13:55:34.115   322   322 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 13:55:34.115   322   322 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 13:55:34.115   322   322 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
06-30 13:55:34.116  7185  7263 V ToneGenerator: ToneGenerator destructor
06-30 13:55:34.116  7185  7263 V ToneGenerator: stopTone
06-30 13:55:34.116  7185  7263 V ToneGenerator: Delete Track: 0xb4928080
06-30 13:55:34.117  7185  7263 V AudioTrack: ~AudioTrack, releasing session id from 7185 on behalf of 7185
06-30 13:55:34.117   322  1387 V AudioPolicyService: AudioCommandThread() adding release output 2
06-30 13:55:34.117   322   322 V AudioFlinger: releasing 22 from 7185 for 7185
06-30 13:55:34.117   322   322 V AudioFlinger:  decremented refcount to 0
06-30 13:55:34.117   322  1387 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-30 13:55:34.117   322   322 V AudioFlinger: purging stale effects
06-30 13:55:34.117   322  1270 V AudioPolicyService: AudioCommandThread() waking up
06-30 13:55:34.117   322  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
06-30 13:55:34.117   322  1270 V AudioPolicyManager: releaseOutput() 2
06-30 13:55:34.117   322  1270 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 13:55:34.117   322  1387 V AudioFlinger: PlaybackThread::Track destructor
06-30 13:55:34.117   322  1387 V AudioFlinger: removeClient_l() pid 7185, calling pid 322
06-30 13:55:34.119  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
06-30 13:55:34.121  6512  7044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
06-30 13:55:34.124  7185  7185 V AudioManager: registerRemoteController: size of Media player list: 0
,06-30 13:55:34.126  7185  7185 E AudioManager: No RCC entry present to update
06-30 13:55:34.126  7185  7185 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
06-30 13:55:34.128  7185  7185 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,06-30 13:55:34.128  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
06-30 13:55:34.128  7185  7185 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
06-30 13:55:34.134  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,06-30 13:55:34.144  7185  7256 V LGMDMManager: Create singleton instance
06-30 13:55:34.146  7185  7256 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-30 13:55:34.164  5963  5963 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,06-30 13:55:34.178  2181  2181 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:34.192  1036  1538 D WifiOffDelayIfNotUsed: stopMonitoring
06-30 13:55:34.192  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 13:55:34.192  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:34.192  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 13:55:34.194  1941  1941 D WfdsService: Supplicant Connection state is changed : false
06-30 13:55:34.194  1941  2340 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
06-30 13:55:34.195  1941  2340 D WfdsService: Set the WFDS Monitor: false
06-30 13:55:34.195  1941  2340 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:55:34.195  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 13:55:34.198  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
06-30 13:55:34.199  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,06-30 13:55:34.199  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
06-30 13:55:34.199  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
06-30 13:55:34.200  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:34.200  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:34.202  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:34.212  1036  1976 V SIM_STK : Menu title from STK is T-Mobile
06-30 13:55:34.212  1036  1976 V SIM_STK : Menu title from STK is T-Mobile
,06-30 13:55:34.234  1036  2050 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7268 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,06-30 13:55:34.291  7268  7268 I AppUp4:AppBoxCP: onCreate
06-30 13:55:34.291  7268  7268 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-30 13:55:34.298  7268  7268 I AppUp4:DB:  setFingerPrint start
06-30 13:55:34.298  7268  7268 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
06-30 13:55:34.299  1036  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
06-30 13:55:34.304  7268  7268 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
06-30 13:55:34.304  7268  7268 I AppUp4:DB:  SDK version = 21
06-30 13:55:34.304  7268  7268 I AppUp4:DB:  beforefinger == newfinger no write in DB
,06-30 13:55:34.306  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
06-30 13:55:34.306  7268  7268 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-30 13:55:34.307  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-30 13:55:34.307  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:34.308  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-30 13:55:34.308  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
06-30 13:55:34.310  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
06-30 13:55:34.310  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
06-30 13:55:34.310  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
06-30 13:55:34.310  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
06-30 13:55:34.311  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 13:55:34.311  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
06-30 13:55:34.311  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
06-30 13:55:34.311  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
06-30 13:55:34.311  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 13:55:34.311  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
06-30 13:55:34.311  7185  7185 I BluetoothA2dpServiceJni: classInitNative
06-30 13:55:34.311  7185  7185 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-30 13:55:34.311  7185  7185 D A2dpStateMachine: make
06-30 13:55:34.313  7185  7185 I bluedroid-qcom: get_profile_interface a2dp
06-30 13:55:34.313  7185  7287 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 13:55:34.315  7185  7185 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
06-30 13:55:34.315  7185  7185 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-30 13:55:34.316  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.316  7185  7185 I BluetoothHidServiceJni: classInitNative: succeeds
06-30 13:55:34.317  7185  7285 D A2dpStateMachine: Enter Disconnected: -2
06-30 13:55:34.318  7185  7185 D HidService: Received start request. Starting profile...
06-30 13:55:34.318  7185  7185 I bluedroid-qcom: get_profile_interface hidhost
06-30 13:55:34.318  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.318  7185  7185 D HeadsetStateMachine: Proxy object connected
06-30 13:55:34.318  7185  7185 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
06-30 13:55:34.318  7268  7268 I AppUp4:CustModeStarterReceiver: onReceive
06-30 13:55:34.318  7185  7185 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,06-30 13:55:34.320  7185  7185 I BluetoothHealthServiceJni: classInitNative: succeeds
06-30 13:55:34.321  7185  7185 D HealthService: Received start request. Starting profile...
06-30 13:55:34.322  7185  7185 I bluedroid-qcom: get_profile_interface health
06-30 13:55:34.323  7185  7185 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-30 13:55:34.323  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.325  7185  7185 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:34.325  7185  7263 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:55:34.326  7185  7263 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 13:55:34.326  7185  7263 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-30 13:55:34.326  7185  7185 I BluetoothPanServiceJni: classInitNative(L105): succeeds
06-30 13:55:34.328  7185  7185 D PanService: Received start request. Starting profile...
06-30 13:55:34.328  7185  7185 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 13:55:34.328  7185  7185 I bluedroid-qcom: get_profile_interface pan
06-30 13:55:34.332  7185  7185 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
06-30 13:55:34.332  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.333  7185  7185 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,06-30 13:55:34.336  7185  7185 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 13:55:34.336  7185  7185 D BtGatt.GattService: Received start request. Starting profile...
06-30 13:55:34.336  7185  7185 D BtGatt.GattService: start()
06-30 13:55:34.336  7185  7185 I bluedroid-qcom: get_profile_interface gatt
06-30 13:55:34.336  7185  7185 D BtGatt.AdvertiseManager: advertise manager created
06-30 13:55:34.339  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.340  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.340  7185  7185 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-30 13:55:34.341  7185  7185 V BluetoothMapService: BluetoothMapBinder()
06-30 13:55:34.342  7185  7185 D BluetoothMapService: Received start request. Starting profile...
06-30 13:55:34.342  7185  7185 D BluetoothMapService: start()
06-30 13:55:34.343  7185  7185 D BluetoothMapEmailSettingsLoader: Found 0 applications
06-30 13:55:34.344  7185  7185 D BluetoothMapEmailAppObserver: createReceiver()
06-30 13:55:34.344  7185  7185 D BluetoothMapEmailAppObserver: initObservers()
06-30 13:55:34.344  7185  7185 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
06-30 13:55:34.348  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
,06-30 13:55:34.351  7185  7185 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:34.352  7185  7185 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:34.353  7185  7185 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:34.356  7185  7185 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:34.356  7185  7185 V PanService: [BTUI] SIM Extra State :ABSENT
06-30 13:55:34.358  7185  7185 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:34.360  7185  7185 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,06-30 13:55:34.360  7185  7185 V BluetoothMapService: Handler(): got msg=1
06-30 13:55:34.361  7185  7185 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:34.361  7185  7185 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 13:55:34.361  7185  7185 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:34.361  7185  7185 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:34.361  7185  7185 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
06-30 13:55:34.361  7185  7256 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-30 13:55:34.361  7185  7256 I bluedroid-qcom: enable
,06-30 13:55:34.361  7185  7256 I bt_hci_bdroid: init
06-30 13:55:34.362  7185  7256 I bt_vendor: bt-vendor : init
06-30 13:55:34.362  7185  7256 I bt_vendor: bt-vendor : get_bt_soc_type
06-30 13:55:34.362  7185  7256 E bt_vendor: get_bt_soc_type: Failed to get soc type
06-30 13:55:34.362  7185  7256 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
06-30 13:55:34.362  7185  7256 D bt_userial_mct: userial_init
06-30 13:55:34.362  7185  7256 D bt_hci_bdroid: set_power 1
06-30 13:55:34.362  7185  7256 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
06-30 13:55:34.362  7185  7256 I bt_vendor: Starting hciattach daemon
06-30 13:55:34.362  7185  7256 I bt_vendor: try to set true
06-30 13:55:34.363  7185  7295 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
06-30 13:55:34.363  7185  7295 I bt-btu  : btu_task pending for preload complete event
06-30 13:55:34.352  7298  7298 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:34.352  7298  7298 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,06-30 13:55:34.366  7268  7268 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:34.367  7268  7268 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 13:55:34.373  7268  7268 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@197f5747
06-30 13:55:34.373  7268  7268 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 13:55:34.373  7268  7268 D AppUp4:CustFacade: isPhone : true
06-30 13:55:34.374  7268  7268 D AppUp4:CustModeStarterReceiver: begin check event
06-30 13:55:34.374  7268  7268 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-30 13:55:34.374  7299  7299 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
06-30 13:55:34.374  7268  7268 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,06-30 13:55:34.376  7268  7286 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-30 13:55:34.376  7268  7286 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-30 13:55:34.376  7268  7286 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
06-30 13:55:34.380  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:34.380  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:55:34.385  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:34.386  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,06-30 13:55:34.392  4818  7302 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:55:34.393  4818  7303 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:34.393  4818  7303 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:55:34.396  1036  1538 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
06-30 13:55:34.396  1036  1538 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
06-30 13:55:34.397  1036  1538 E WifiStateMachine:  InitialState CMD_SET_FREQUENCY_BAND 0 0
06-30 13:55:34.397  1036  1538 E WifiStateMachine:  DefaultState CMD_SET_FREQUENCY_BAND 0 0
06-30 13:55:34.411  1036  1903 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7306 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,06-30 13:55:34.422  7316  7316 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
06-30 13:55:34.428  7323  7323 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,06-30 13:55:34.443  7327  7327 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,06-30 13:55:34.449  7328  7328 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,06-30 13:55:34.457  7329  7329 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,06-30 13:55:34.463  7330  7330 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
06-30 13:55:34.464  7306  7306 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:55:34.464  7306  7306 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:55:34.465  7306  7306 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 13:55:34.466  7306  7306 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 13:55:34.480  7332  7332 I libmdmdetect: ESOC framework not supported
06-30 13:55:34.481  7332  7332 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,06-30 13:55:34.490  7332  7332 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
06-30 13:55:34.490  7332  7332 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
06-30 13:55:34.490  7332  7332 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
06-30 13:55:34.490  7332  7332 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
06-30 13:55:34.490  7332  7332 D bthci_qcomm_common: [BTUI]     LE: Class 2
06-30 13:55:34.490  7332  7332 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
06-30 13:55:34.490  7332  7332 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
06-30 13:55:34.514  7306  7306 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,06-30 13:55:34.523  7332  7333 E QC-QMI  : qmi_client [7332] 14: failed to locate client data
06-30 13:55:34.524   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
06-30 13:55:34.524   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
06-30 13:55:34.525  7306  7306 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
06-30 13:55:34.578  7306  7306 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-30 13:55:34.611  7306  7306 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:34.611  7306  7306 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 13:55:34.621  7335  7335 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
06-30 13:55:34.644  7337  7337 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,06-30 13:55:34.666  7185  7256 I bt_vendor: bluetooth satus is on
06-30 13:55:34.666  7185  7256 D bt_hci_bdroid: preload
06-30 13:55:34.666  7185  7297 D bt_userial_mct: userial_open(port:0)
06-30 13:55:34.666  7185  7297 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,06-30 13:55:34.670  7185  7297 I bt_vendor: Done intiailizing UART
06-30 13:55:34.671  7185  7297 I bt_vendor: Done intiailizing UART
06-30 13:55:34.671  7185  7297 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
06-30 13:55:34.671  7185  7297 I bt_vendor: Bluetooth Firmware and transport layer are initialized
06-30 13:55:34.671  7185  7295 I bt-btu  : btu_task received preload complete event
06-30 13:55:34.671  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
06-30 13:55:34.671  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
06-30 13:55:34.673  7185  7341 D bt_userial_mct: Entering userial_read_thread()
06-30 13:55:34.673  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_HCI
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_L2CAP
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_RFCOMM
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_AVDT
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_AVRC
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_A2D
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_BNEP
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_BTM
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_HID_HOST
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_GAP
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_PAN
06-30 13:55:34.674  7185  7295 I         : BTE_InitTraceLevels -- TRC_SDP
06-30 13:55:34.675  7185  7295 I         : BTE_InitTraceLevels -- TRC_GATT
06-30 13:55:34.675  7185  7295 I         : BTE_InitTraceLevels -- TRC_SMP
06-30 13:55:34.675  7185  7295 I         : BTE_InitTraceLevels -- TRC_BTAPP
06-30 13:55:34.675  7185  7295 I         : BTE_InitTraceLevels -- TRC_BTIF
,06-30 13:55:34.705  7306  7306 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,06-30 13:55:34.738  7185  7295 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
06-30 13:55:34.738  7185  7295 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0151061 
,06-30 13:55:34.738  7185  7295 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0151061 
06-30 13:55:34.749  3192  3192 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
06-30 13:55:34.750  3192  3192 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:34.750  3192  3192 I LgeMiscReceiver: networkInfo.isConnected() = false
,06-30 13:55:34.760  7185  7260 E bt-btif : Calling BTA_HhEnable
06-30 13:55:34.760  7185  7260 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
06-30 13:55:34.760  7185  7260 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-30 13:55:34.761  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
06-30 13:55:34.761  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
06-30 13:55:34.761  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
06-30 13:55:34.762  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
06-30 13:55:34.762  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
06-30 13:55:34.767  7306  7306 I HubEmail: JNI_OnLoad()
06-30 13:55:34.767  7306  7306 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:55:34.767  7306  7306 I HubEmail: registerNatives()
06-30 13:55:34.767  7306  7306 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:55:34.767  7306  7306 I HubEmail: registerNativeMethods()
,06-30 13:55:34.767  7306  7306 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:55:34.768  7306  7306 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
06-30 13:55:34.772  7185  7295 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 13:55:34.772  7185  7295 W bt-smp  : Plain text(LSB ~ MSB) = fd 50 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:55:34.772  7185  7295 W bt-smp  : Encrypted text(LSB ~ MSB) = 55 af 63 c5 ea 6f 6c c5 c3 02 f0 09 f8 77 37 90 
06-30 13:55:34.772  7185  7295 W bt-btm  : Stopping oneshot timer
06-30 13:55:34.778  1036  1052 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7346 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
06-30 13:55:34.781  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
06-30 13:55:34.781  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
06-30 13:55:34.781  7185  7260 D BluetoothAdapterProperties: Name is: G3
,06-30 13:55:34.785  7185  7260 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:55:34.785  7185  7260 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:34.785  7185  7260 D bt_hci_bdroid: postload
06-30 13:55:34.785  7185  7260 D bte_conf: Device ID record 1 : primary
06-30 13:55:34.785  7185  7260 D bte_conf:   vendorId            = 00c4
06-30 13:55:34.785  7185  7297 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:34.785  7185  7260 D bte_conf:   vendorIdSource      = 0001
06-30 13:55:34.785  7185  7260 D bte_conf:   product             = 13a1
06-30 13:55:34.785  7185  7260 D bte_conf:   version             = 1000
06-30 13:55:34.785  7185  7260 D bte_conf:   clientExecutableURL = 
06-30 13:55:34.785  7185  7260 D bte_conf:   serviceDescription  = 
06-30 13:55:34.785  7185  7295 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
06-30 13:55:34.785  7185  7260 D bte_conf:   documentationURL    = 
06-30 13:55:34.785  7185  7260 D bte_conf: bte_load_did_conf no section named DID2.
06-30 13:55:34.786  7185  7260 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-30 13:55:34.787  7185  7256 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,06-30 13:55:34.787  7185  7256 D BluetoothAdapterProperties: ScanMode =  20
06-30 13:55:34.787  7185  7256 D BluetoothAdapterProperties: State =  11
06-30 13:55:34.787  7185  7256 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-30 13:55:34.789  7185  7297 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:34.789  7185  7297 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:34.788  7185  7256 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
06-30 13:55:34.789  7185  7256 D BluetoothAdapterProperties: Setting state to 12
06-30 13:55:34.789  7185  7260 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-30 13:55:34.782  7357  7357 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:34.782  7357  7357 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:34.792  7185  7297 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:34.792  7185  7297 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:34.793  7185  7256 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,06-30 13:55:34.796  7185  7341 E bt_mct  : hci lib postload completed
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:34.798  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:34.800  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:34.800  7162  7344 W FormManager: Network not available. Please check & try again.
06-30 13:55:34.801  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:34.801  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-30 13:55:34.801  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
06-30 13:55:34.801  7185  7256 I BluetoothAdapterState: Entering On State
06-30 13:55:34.802  1852  4481 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:55:34.803  7185  7256 D LGBluetoothServiceAdapter: [BTUI] OnState
06-30 13:55:34.803  7185  7256 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
06-30 13:55:34.804  7185  7256 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
06-30 13:55:34.804  7185  7256 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-30 13:55:34.806  1852  1852 D BluetoothHeadset: Proxy object connected
06-30 13:55:34.806  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:34.807  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:34.808  1852  1852 D BluetoothHeadset: Proxy object connected
,06-30 13:55:34.812  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:34.813  7047  7063 D BluetoothInputDevice: onBluetoothStateChange: up=true
06-30 13:55:34.822  7185  7260 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:34.822  7185  7260 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
06-30 13:55:34.824  7371  7371 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,06-30 13:55:34.826  7162  7345 V FormManager: Network unavailable.
06-30 13:55:34.827  7306  7347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:34.829  7047  7047 D BluetoothInputDevice: Proxy object connected
06-30 13:55:34.829  1852  4493 D BluetoothHeadset: onBluetoothStateChange: up=true
,06-30 13:55:34.829  7047  7047 D HidProfile: Bluetooth service connected
06-30 13:55:34.829  7162  7345 V FormManager: Network unavailable.
06-30 13:55:34.832  1852  1852 D BluetoothHeadset: Proxy object connected
06-30 13:55:34.832  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 13:55:34.833  7047  7064 D BluetoothPbap: onBluetoothStateChange: up=true
06-30 13:55:34.834  1036  1036 D BluetoothA2dp: Proxy object connected
06-30 13:55:34.835  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:55:34.836  7047  7063 D BluetoothPan: onBluetoothStateChange on: true
06-30 13:55:34.836  7047  7063 D BluetoothPan: onBluetoothStateChange call bindService
,06-30 13:55:34.836  1036  1036 D BluetoothHeadset: Proxy object connected
06-30 13:55:34.838  7047  7372 D BluetoothMap: onBluetoothStateChange: up=true
06-30 13:55:34.839  7047  7047 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 13:55:34.839  7047  7047 D PanProfile: Bluetooth service connected
06-30 13:55:34.843  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-30 13:55:34.843  7047  7047 D BluetoothMap: Proxy object connected
06-30 13:55:34.843  7047  7047 D MapProfile: Bluetooth service connected
06-30 13:55:34.843  7047  7047 D BluetoothMap: getConnectedDevices()
06-30 13:55:34.844  7185  7365 V BluetoothMapService: getConnectedDevices()
06-30 13:55:34.844  1036  1580 I ActivityManager: Killing 6460:com.android.defcontainer/u0a4 (adj 15): empty #17
06-30 13:55:34.845  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
06-30 13:55:34.852  7185  7256 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,06-30 13:55:34.898  7346  7346 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:34.898  7346  7346 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 13:55:34.901  7346  7346 D PhoneMonitor: Register our PhoneStateListener
06-30 13:55:34.938  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-30 13:55:34.939  1036  1118 D BluetoothManagerService: Message: 40
06-30 13:55:34.939  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
06-30 13:55:34.939  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:34.939  1941  2143 D LGBluetoothAPIService: Message: 1
06-30 13:55:34.939  1941  2143 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,06-30 13:55:34.940  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:34.950  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:34.954  7185  7185 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:34.954  1036  1052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@22c641b6 mBinding = false
06-30 13:55:34.954  7185  7185 D BluetoothMapService: STATE_ON
,06-30 13:55:34.959  1941  2143 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
06-30 13:55:34.959  1036  2032 W libprocessgroup: failed to open /acct/uid_10004/pid_6460/cgroup.procs: No such file or directory
06-30 13:55:34.962  7047  7047 D LocalBluetoothProfileManager: Adding local A2DP profile
06-30 13:55:34.970  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:34.970  7185  7185 V BluetoothPbapService: Pbap Service onCreate
06-30 13:55:34.970  7185  7185 V BluetoothPbapService: Starting PBAP service
,06-30 13:55:34.972  1036  1118 D BluetoothManagerService: Message: 30
06-30 13:55:34.973  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:34.973  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:34.973  1036  1036 D Ulp_jni : JNI:system_update. Event-4
06-30 13:55:34.974  1036  1118 D BluetoothManagerService: Message: 2
06-30 13:55:34.974  7185  7185 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-30 13:55:34.974  1036  1118 D BluetoothManagerService: Sending off request.
06-30 13:55:34.975  7185  7365 D LGBluetoothServiceAdapter: [BTUI] Precleanup
06-30 13:55:34.975  7185  7185 V BluetoothMapService: Handler(): got msg=1
06-30 13:55:34.976  7185  7256 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
06-30 13:55:34.976  7185  7185 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
06-30 13:55:34.976  7185  7256 D BluetoothAdapterProperties: Setting state to 13
06-30 13:55:34.976  7185  7256 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
06-30 13:55:34.976  7185  7185 V BluetoothPbapService: Pbap Service onBind
06-30 13:55:34.976  7185  7256 D BluetoothAdapterProperties: onBluetoothDisable()
06-30 13:55:34.977  7185  7256 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
06-30 13:55:34.977  7047  7047 D LocalBluetoothProfileManager: Adding local HEADSET profile
06-30 13:55:34.977  7185  7260 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:55:34.977  7185  7256 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
06-30 13:55:34.977  7185  7185 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:34.977  7185  7185 V BluetoothPbapService: state: 12
06-30 13:55:34.978  7185  7256 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-30 13:55:34.978  7185  7185 D LGBluetoothAPIServer: [BTUI] onCreate()
06-30 13:55:34.979  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
06-30 13:55:34.979  7185  7295 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
06-30 13:55:34.980  7185  7375 D BluetoothMapMasInstance: MAS initSocket()
06-30 13:55:34.980  7185  7185 D LGBluetoothAPIServer: [BTUI] onBind()
06-30 13:55:34.981  7185  7375 D BluetoothMapMasInstance:   masId = 00
06-30 13:55:34.981  7185  7375 D BluetoothMapMasInstance:   msgTypes = 0e
06-30 13:55:34.981  7185  7375 D BluetoothMapMasInstance:   masName = SMS/MMS
06-30 13:55:34.981  7185  7375 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
06-30 13:55:34.981  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:34.981  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
06-30 13:55:34.981  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:34.981  1036  1118 D BluetoothManagerService: Message: 30
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistrati,on
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
06-30 13:55:34.981  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
06-30 13:55:34.981  7185  7295 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:34.982  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:34.983  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:34.984  7185  7185 V BluetoothPbapService: Handler(): got msg=1
06-30 13:55:34.985  7185  7185 V BluetoothPbapService: Pbap Service closeService in
06-30 13:55:34.985  7185  7185 V BluetoothPbapService: successfully stopped pbap service
06-30 13:55:34.985  7185  7185 V BluetoothPbapService: Pbap Service closeService out
06-30 13:55:34.986  7185  7185 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:34.986  7185  7185 D BluetoothMapService: STATE_TURNING_OFF
06-30 13:55:34.986  7185  7185 V BluetoothMapService: Handler(): got msg=4
06-30 13:55:34.986  7185  7185 D BluetoothMapService: MAP Service closeService in
06-30 13:55:34.986  7185  7185 D BluetoothMapMasInstance: MAP Service shutdown
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:34.986  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:34.987  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:34.987  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:34.987  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-30 13:55:34.987  1941  2143 D LGBluetoothAPIService: Message: 100
06-30 13:55:34.987  1941  2143 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
06-30 13:55:34.987  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
06-30 13:55:34.988  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:34.990  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:34.991  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
06-30 13:55:34.992  7047  7047 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
06-30 13:55:34.992  7185  7375 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 13:55:34.994  7047  7047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,06-30 13:55:35.007  7346  7346 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
06-30 13:55:35.007  7346  7346 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-30 13:55:35.008  7346  7346 D TelephonyAutoProfiling: [parse] Load xml
06-30 13:55:35.010  7346  7346 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
06-30 13:55:35.010  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
06-30 13:55:35.010  7346  7346 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,06-30 13:55:35.018  7346  7346 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
06-30 13:55:35.032  1036  1777 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7377 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:35.034  7185  7375 E BluetoothServiceJni: Socket listen failed: 2
,06-30 13:55:35.034  7185  7375 E BluetoothAdapterService(746952861): Failed to create socket channel
06-30 13:55:35.035  7185  7375 E BluetoothMapMasInstance: Error create RfcommServerSocket java.io.IOException: Error: -1
06-30 13:55:35.035  7185  7375 W BluetoothMapMasInstance: initServerSocket failed as BT is (being) turned off
06-30 13:55:35.035  7185  7375 E BluetoothMapMasInstance: Error to create listening socket after 10 try
06-30 13:55:35.035  7185  7185 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:55:35.036  7185  7185 V BluetoothMapService: MAP Service closeService out
06-30 13:55:35.036  7185  7185 V BluetoothPbapService: Pbap Service onDestroy
06-30 13:55:35.036  7185  7185 V BluetoothPbapService: Pbap Service closeService in
06-30 13:55:35.036  7185  7185 V BluetoothPbapService: Pbap Service closeService out
06-30 13:55:35.036  7185  7185 D LGBluetoothPbapAdapter: [BTUI] cleanup
06-30 13:55:35.037  7047  7047 D BluetoothA2dp: Proxy object connected
06-30 13:55:35.038  7047  7047 D A2dpProfile: Bluetooth service connected
06-30 13:55:35.039  7185  7185 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:55:35.039  7185  7185 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.039  7047  7047 D BluetoothPbap: Proxy object connected
06-30 13:55:35.039  7185  7185 V BluetoothPbapReceiver: ***********state = 12
06-30 13:55:35.040  7047  7047 D PbapServerProfile: Bluetooth service connected
06-30 13:55:35.040  7047  7047 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
06-30 13:55:35.040  7047  7047 D BluetoothPbap: Proxy object disconnected
06-30 13:55:35.040  7047  7047 D PbapServerProfile: Bluetooth service disconnected
06-30 13:55:35.040  7047  7047 D BluetoothHeadset: Proxy object connected
06-30 13:55:35.041  7047  7047 D HeadsetProfile: Bluetooth service connected
06-30 13:55:35.044  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 13:55:35.044  2181  2181 D c       : Getting all permits...
06-30 13:55:35.044  2181  2181 D a       : Opening database...
06-30 13:55:35.045  7047  7047 D DockEventReceiver: finishStartingService: stopping service
06-30 13:55:35.047  1036  1776 I ActivityManager: Killing 6683:com.google.android.apps.docs/u0a61 (adj 15): empty #17
06-30 13:55:35.048  2181  2181 D a       : Opening database auth.proximity.permit_store...
06-30 13:55:35.048  2181  2181 D a       : Closing database...
,06-30 13:55:35.139  1036  1051 W libprocessgroup: failed to open /acct/uid_10061/pid_6683/cgroup.procs: No such file or directory
06-30 13:55:35.161  7047  7047 D BluetoothPermissionRequest: onReceive
,06-30 13:55:35.163  7047  7047 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-30 13:55:35.165  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-30 13:55:35.172  7185  7185 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
06-30 13:55:35.173  7185  7185 I LGBluetoothOppAdapter: [BTUI] startOppService()
,06-30 13:55:35.182  7185  7185 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
06-30 13:55:35.202  7185  7185 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:55:35.202  7185  7185 V BtOppService: onCreate
,06-30 13:55:35.206  7185  7185 V BluetoothOppNotification: send message
,06-30 13:55:35.213  7185  7185 D BluetoothOppPreference: Dumping Names:  
06-30 13:55:35.213  7185  7185 D BluetoothOppPreference: {}
06-30 13:55:35.213  7185  7185 D BluetoothOppPreference: Dumping Channels:  
06-30 13:55:35.213  7185  7185 D BluetoothOppPreference: {}
06-30 13:55:35.213  7185  7185 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
06-30 13:55:35.213  7185  7185 V BtOppService: onStartCommand
06-30 13:55:35.215  7185  7185 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
06-30 13:55:35.216  7185  7185 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.216  7185  7185 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
06-30 13:55:35.218  7185  7397 V BtOppService: Deleted complete outbound shares, number =  0
,06-30 13:55:35.220  7185  7185 V BluetoothOppNotification: previous thread is not finished yet
06-30 13:55:35.221  7185  7185 V BtOppService: ContentObserver received notification
06-30 13:55:35.221  7185  7185 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
06-30 13:55:35.221  7185  7397 V BtOppService: Deleted complete inbound failed shares, number = 0
06-30 13:55:35.222  7185  7397 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-30 13:55:35.225  7185  7397 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ea0210f on behalf of 
06-30 13:55:35.228  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:35.228  7185  7185 V BluetoothFtpService: Ftp Service onCreate
06-30 13:55:35.228  7185  7185 I BluetoothFtpService: Ftp Service onCreate
06-30 13:55:35.228  7185  7185 V BluetoothFtpService: Ftp Service onStartCommand
06-30 13:55:35.228  7185  7185 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.228  7185  7185 V BluetoothFtpService: Starting Listening on sockets
06-30 13:55:35.229  7185  7185 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:35.229  7185  7185 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 13:55:35.229  7185  7185 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:35.229  7185  7185 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.229  7185  7185 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
06-30 13:55:35.229  7185  7185 V BluetoothSapReceiver: Calling SAP service start service with action = null
06-30 13:55:35.230  7185  7185 V BtOppService: ContentObserver received notification
06-30 13:55:35.230  7185  7185 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
06-30 13:55:35.230  7185  7185 V BluetoothFtpService: Handler(): got msg=1
06-30 13:55:35.232  7185  7185 V BluetoothFtpService: Ftp Service closeService
,06-30 13:55:35.234  7185  7185 V BluetoothFtpService: successfully stopped ftp service
,06-30 13:55:35.236  7047  7047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:55:35.241  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:35.242  7185  7185 V BluetoothSapService: Sap Service onCreate
06-30 13:55:35.242  7047  7047 D DockEventReceiver: finishStartingService: stopping service
06-30 13:55:35.243  7185  7185 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.243  7185  7185 V BluetoothSapService: state: 12
06-30 13:55:35.243  7185  7185 V BluetoothSapService: Starting SAP server process
,06-30 13:55:35.245  7185  7185 V BluetoothFtpService: Ftp Service onDestroy
,06-30 13:55:35.245  7185  7185 V BluetoothFtpService: Ftp Service closeService
06-30 13:55:35.246  7185  7185 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:55:35.246  7185  7185 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.246  7185  7185 V BluetoothPbapReceiver: ***********state = 13
06-30 13:55:35.242  7402  7402 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:35.242  7402  7402 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:35.248  7185  7185 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
06-30 13:55:35.250  7402  7402 V BT_SAP  : Event pipe created
06-30 13:55:35.251  7402  7402 V BT_SAP  : create_server_socket qcom.sap.server
06-30 13:55:35.251  7402  7402 V BT_SAP  : created socket fd 6
06-30 13:55:35.251  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 13:55:35.251  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:35.251  7185  7185 V BluetoothPbapService: Pbap Service onCreate
06-30 13:55:35.251  7185  7185 V BluetoothPbapService: Starting PBAP service
06-30 13:55:35.252  7185  7185 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-30 13:55:35.252  7185  7185 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.252  7185  7185 V BluetoothPbapService: state: 13
06-30 13:55:35.252  7185  7185 V BluetoothPbapService: Pbap Service closeService in
06-30 13:55:35.254  7185  7185 V BluetoothPbapService: successfully stopped pbap service
06-30 13:55:35.254  7185  7185 V BluetoothPbapService: Pbap Service closeService out
06-30 13:55:35.255  7185  7185 V BluetoothPbapService: Pbap Service onDestroy
06-30 13:55:35.255  7185  7185 V BluetoothPbapService: Pbap Service closeService in
06-30 13:55:35.255  7185  7185 V BluetoothPbapService: Pbap Service closeService out
06-30 13:55:35.255  7185  7185 D LGBluetoothPbapAdapter: [BTUI] cleanup
06-30 13:55:35.260  7047  7047 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,06-30 13:55:35.263  7047  7047 D BluetoothPermissionRequest: onReceive
06-30 13:55:35.263  7047  7047 D LGBluetoothAuthorization: [BTUI] cancel All Notification
06-30 13:55:35.266  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-30 13:55:35.268  7185  7185 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
06-30 13:55:35.268  7185  7185 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
06-30 13:55:35.269  7185  7185 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
06-30 13:55:35.271  7185  7185 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:35.271  7185  7185 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
06-30 13:55:35.274  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:35.274  7185  7185 V BluetoothFtpService: Ftp Service onCreate
06-30 13:55:35.274  7185  7185 I BluetoothFtpService: Ftp Service onCreate
06-30 13:55:35.274  7185  7185 V BluetoothFtpService: Ftp Service onStartCommand
06-30 13:55:35.274  7185  7185 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.274  7185  7185 V BluetoothFtpService: Ftp Service closeService
06-30 13:55:35.275  7185  7185 V BluetoothFtpService: successfully stopped ftp service
06-30 13:55:35.275  7185  7185 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:35.275  7185  7185 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 13:55:35.275  7185  7185 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:35.275  7185  7185 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.275  7185  7185 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
06-30 13:55:35.275  7185  7185 V BluetoothSapReceiver: Calling SAP service start service with action = null
06-30 13:55:35.276  7185  7185 V BluetoothFtpService: Ftp Service onDestroy
06-30 13:55:35.276  7185  7185 V BluetoothFtpService: Ftp Service closeService
06-30 13:55:35.278  7185  7185 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:35.278  7185  7185 V BluetoothSapService: state: 13
06-30 13:55:35.278  7185  7185 V BluetoothSapService: Stopping SAP server process
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Sap Service closeSapService in
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Close listen Socket : 
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Close rfcomm Socket : 
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Close sapd  Socket : 
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Sap Service closeSapService out
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Sap Service onDestroy
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Sap Service closeSapService in
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Close listen Socket : 
06-30 13:55:35.279  7185  7185 V BluetoothSapService: Close rfcomm Socket : 
06-30 13:55:35.280  7185  7185 V BluetoothSapService: Close sapd  Socket : 
06-30 13:55:35.282  7185  7185 V BluetoothSapService: Sap Service closeSapService out
06-30 13:55:35.355  1036  1940 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7403 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
06-30 13:55:35.356  1036  1940 I ActivityManager: Killing 6710:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,06-30 13:55:35.425  1036  1667 W libprocessgroup: failed to open /acct/uid_10080/pid_6710/cgroup.procs: No such file or directory
,06-30 13:55:35.551  1036  1939 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7420 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:55:35.552  1036  1939 I ActivityManager: Killing 6756:com.lge.eula/1000 (adj 15): empty #17
,06-30 13:55:35.635  1036  1776 W libprocessgroup: failed to open /acct/uid_1000/pid_6756/cgroup.procs: No such file or directory
,06-30 13:55:35.650  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{13fe2031 type 2 when 300890 com.google.android.gms} when 300890
,06-30 13:55:35.681  7420  7420 I art     : Almond Protected OAT
,06-30 13:55:35.732  7420  7420 D WeatherApplication: removeAccount
06-30 13:55:35.733  7420  7420 D WeatherApplication: Account.length = 0
06-30 13:55:35.734  7420  7420 E WeatherApplication: OPERATOR:OPEN
,06-30 13:55:35.738  7420  7420 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:55:35
06-30 13:55:35.741  7420  7420 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-30 13:55:35.741  7420  7420 D Weather.Utils: 2 : All the weather widget is gone.
06-30 13:55:35.743  7420  7420 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 13:55:35.746  7420  7420 D WeatherAncestor: connectivity changed - connection : true
06-30 13:55:35.747  7420  7420 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,06-30 13:55:35.754  7420  7420 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
06-30 13:55:35.755  7420  7420 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
06-30 13:55:35.755  7420  7420 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
06-30 13:55:35.773  7420  7420 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 13:55:35.773  7420  7420 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:55:35
,06-30 13:55:35.818  1036  1940 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7441 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:35.820  1036  1940 I ActivityManager: Killing 6731:com.google.android.apps.plus/u0a97 (adj 15): empty #17
06-30 13:55:35.906  1036  1776 W libprocessgroup: failed to open /acct/uid_10097/pid_6731/cgroup.procs: No such file or directory
,06-30 13:55:35.921  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:35.921  1036  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:55:35.963  1036  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,06-30 13:55:35.964  1036  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
06-30 13:55:35.975  6956  7019 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:35.975  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,06-30 13:55:35.984  7185  7295 W bt-btif : ag scb idx 1 not allocated
06-30 13:55:35.984  7185  7260 D bt_hci_bdroid: cleanup
06-30 13:55:35.984  7185  7295 E bt-btif : BTA AG is already disabled, ignoring ...
06-30 13:55:35.984  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:35.985  7185  7297 I bt_lpm  : LPM is already off!!!
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
06-30 13:55:35.985  7185  7295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
06-30 13:55:35.985  7185  7295 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:55:35.985  7185  7341 I bt_userial_mct: exiting userial_read_thread
06-30 13:55:35.985  7185  7341 D bt_userial_mct: Leaving userial_evt_read_thread()
06-30 13:55:35.985  7185  7260 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
06-30 13:55:35.985  7185  7297 I bt_vendor: hw_epilog_process
06-30 13:55:35.986  7185  7260 D bt_hci_bdroid: cleanup Finalizing cleanup
06-30 13:55:35.986  7185  7260 D bt_userial_mct: userial_close
06-30 13:55:35.986  7185  7260 E bt_userial_mct: pthread_join() FAILED result:3
06-30 13:55:35.986  7185  7260 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
06-30 13:55:36.023   278   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:55:36.024   278   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 13:55:36.024   278   372 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:55:36.025  7441  7460 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,06-30 13:55:36.030   278   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,06-30 13:55:36.030   278   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 13:55:36.030   278   372 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:55:36.035  7441  7460 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 13:55:36.040   278   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:55:36.040   278   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 13:55:36.040   278   372 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:55:36.041  7441  7464 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,06-30 13:55:36.043   278   372 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:55:36.043   278   372 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 13:55:36.043   278   372 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:55:36.044  7441  7464 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 13:55:36.076  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 13:55:36.076  6956  7023 I jxcore-log: 
,06-30 13:55:36.115  7185  7260 D bt_hci_bdroid: set_power 0
06-30 13:55:36.115  7185  7260 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
06-30 13:55:36.115  7185  7260 I bt_vendor: bluetooth satus is on
06-30 13:55:36.115  7185  7260 I bt_vendor: bt-vendor : resetting BT status
06-30 13:55:36.115  7185  7260 I bt_vendor: Starting hciattach daemon
06-30 13:55:36.115  7185  7260 I bt_vendor: try to set false
,06-30 13:55:36.115  7185  7260 I bt_vendor: Starting hciattach daemon
06-30 13:55:36.115  7185  7260 I bt_vendor: try to set false
06-30 13:55:36.115  7185  7260 I bt_vendor: cleanup
06-30 13:55:36.116  7185  7295 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
06-30 13:55:36.116  7185  7260 I GKI_LINUX: GKI_exit_task 0 done
06-30 13:55:36.116  7185  7260 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
06-30 13:55:36.117  7185  7256 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
06-30 13:55:36.118  7185  7185 D HeadsetService: Received stop request...Stopping profile...
06-30 13:55:36.119  7185  7185 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:55:36.119  7185  7185 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:55:36.119  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:36.119  7185  7263 D HeadsetStateMachine: Exit Disconnected: -1
,06-30 13:55:36.121  7185  7185 D A2dpService: Received stop request...Stopping profile...
06-30 13:55:36.122  7185  7285 D A2dpStateMachine: Exit Disconnected: -1
,06-30 13:55:36.123  1852  1852 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:36.123  1852  1852 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:36.123  1852  1852 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:36.123  1036  1036 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:36.123  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
06-30 13:55:36.124  7185  7256 D BluetoothAdapterState: Stopping profile services that were post enabled
06-30 13:55:36.124  7185  7185 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
06-30 13:55:36.125  7047  7047 D BluetoothHeadset: Proxy object disconnected
06-30 13:55:36.125  7047  7047 D HeadsetProfile: Bluetooth service disconnected
06-30 13:55:36.125  7185  7185 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
06-30 13:55:36.125  7185  7185 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:55:36.126  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
,06-30 13:55:36.126  1036  1036 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:36.126  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
06-30 13:55:36.127  7185  7185 D HidService: Received stop request...Stopping profile...
06-30 13:55:36.127  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:36.128  7185  7185 D HeadsetStateMachine: Unbinding service...
06-30 13:55:36.129  7185  7185 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:55:36.129  7185  7185 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:55:36.129  7185  7185 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:55:36.129  7185  7185 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:55:36.129  7185  7185 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
06-30 13:55:36.129  7185  7185 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:55:36.129  7185  7185 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:55:36.130  7185  7185 D HealthService: Received stop request...Stopping profile...
06-30 13:55:36.130  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:36.131  7185  7185 D PanService: Received stop request...Stopping profile...
06-30 13:55:36.131  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:36.132  7185  7185 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 13:55:36.132  7185  7185 D BtGatt.GattService: Received stop request...Stopping profile...
06-30 13:55:36.132  7185  7185 D BtGatt.GattService: stop()
06-30 13:55:36.132  7185  7185 D BtGatt.AdvertiseManager: advertise clients cleared
06-30 13:55:36.133  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:36.134  7185  7185 D BluetoothMapService: Received stop request...Stopping profile...
06-30 13:55:36.134  7185  7185 D BluetoothMapService: stop()
06-30 13:55:36.145  7185  7185 D BluetoothMapEmailAppObserver: deinitObservers()
06-30 13:55:36.145  7185  7185 D BluetoothMapEmailAppObserver: removeReceiver()
06-30 13:55:36.146  7047  7047 D BluetoothA2dp: Proxy object disconnected
06-30 13:55:36.146  7047  7047 D A2dpProfile: Bluetooth service disconnected
06-30 13:55:36.147  7185  7185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
,06-30 13:55:36.148  7185  7185 I BluetoothA2dpServiceJni: cleanupNative
06-30 13:55:36.149  7185  7287 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
06-30 13:55:36.149  7185  7185 I GKI_LINUX: GKI_exit_task 2 done
06-30 13:55:36.149  7185  7185 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
06-30 13:55:36.149  7185  7185 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
06-30 13:55:36.149  7185  7185 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-30 13:55:36.150  7185  7185 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
06-30 13:55:36.150  7185  7185 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:55:36.150  7185  7185 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:55:36.150  7185  7185 V BluetoothMapService: Handler(): got msg=4
06-30 13:55:36.150  7185  7185 D BluetoothMapService: MAP Service closeService in
06-30 13:55:36.151  7185  7185 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:55:36.151  7185  7185 V BluetoothMapService: MAP Service closeService out
06-30 13:55:36.151  7047  7047 D BluetoothInputDevice: Proxy object disconnected
06-30 13:55:36.151  7047  7047 D HidProfile: Bluetooth service disconnected
06-30 13:55:36.151  7185  7185 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-30 13:55:36.151  7185  7256 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
06-30 13:55:36.151  7185  7185 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
06-30 13:55:36.151  7047  7047 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:55:36.151  7047  7047 D PanProfile: Bluetooth service disconnected
06-30 13:55:36.151  7185  7256 D BluetoothAdapterProperties: Setting state to 10
06-30 13:55:36.151  7185  7256 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
06-30 13:55:36.151  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:36.151  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
06-30 13:55:36.151  7047  7047 D BluetoothMap: Proxy object disconnected
06-30 13:55:36.151  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
06-30 13:55:36.151  7047  7047 D MapProfile: Bluetooth service disconnected
06-30 13:55:36.151  7185  7256 I BluetoothAdapterState: Entering OffState
06-30 13:55:36.152  1852  4478 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:36.152  1852  2401 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:36.152  7185  7185 D BluetoothMapService: cleanup()
06-30 13:55:36.152  7185  7185 D BluetoothMapService: MAP Service closeService in
06-30 13:55:36.152  7185  7185 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:55:36.152  7185  7185 V BluetoothMapService: MAP Service closeService out
06-30 13:55:36.152  7047  7063 D BluetoothInputDevice: onBluetoothStateChange: up=false
06-30 13:55:36.153  1852  4493 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:36.153  7047  7064 D BluetoothA2dp: onBluetoothStateChange: up=false
06-30 13:55:36.153  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
06-30 13:55:36.154  7047  7372 D BluetoothPbap: onBluetoothStateChange: up=false
06-30 13:55:36.154  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:36.154  7047  7063 D BluetoothPan: onBluetoothStateChange on: false
06-30 13:55:36.154  7047  7064 D BluetoothMap: onBluetoothStateChange: up=false
06-30 13:55:36.155  7047  7372 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:55:36.155  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
06-30 13:55:36.155  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
06-30 13:55:36.156  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
06-30 13:55:,36.157  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
06-30 13:55:36.157  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@22c641b6 mBinding = false
06-30 13:55:36.157  1036  1118 D BluetoothManagerService: Sending unbind request.
06-30 13:55:36.158  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
06-30 13:55:36.160  7185  7260 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
06-30 13:55:36.160  7185  7185 I GKI_LINUX: GKI_exit_task 1 done
06-30 13:55:36.160  7185  7185 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
06-30 13:55:36.160  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.160  1941  2143 D LGBluetoothAPIService: Message: 2
06-30 13:55:36.160  1941  2143 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@30979ac4 mBinding = false
06-30 13:55:36.160  1941  2143 D LGBluetoothAPIService: Sending unbind request.
06-30 13:55:36.160  7185  7185 I BluetoothServiceJni: cleanupNative: return from cleanup
06-30 13:55:36.161  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:36.163  7185  7185 I art     : --- WEIRD: removing null entry 249
06-30 13:55:36.163  7185  7185 W art     : JNI WARNING: DeleteGlobalRef(0x2003e6) failed to find entry
06-30 13:55:36.163  7185  7185 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
06-30 13:55:36.166  7185  7185 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,06-30 13:55:36.167  7047  7047 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
06-30 13:55:36.167  7047  7047 D LGBluetoothEventManager: [BTUI] clear device connection state
06-30 13:55:36.172  7047  7047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:55:36.172  7185  7185 I art     : System.exit called, status: 0
06-30 13:55:36.172  7185  7185 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
06-30 13:55:36.181  7047  7047 D DockEventReceiver: finishStartingService: stopping service
06-30 13:55:36.182  1603  1603 D BluetoothAdapter: 808982924: getState() :  mService = null. Returning STATE_OFF
06-30 13:55:36.182  1603  1603 D BluetoothAdapter: 808982924: getState() :  mService = null. Returning STATE_OFF
,06-30 13:55:36.183   322  2154 V AudioFlinger: 7185 died, releasing its sessions
,06-30 13:55:36.183   322  2154 V AudioFlinger:  pid 1852 @ 0
06-30 13:55:36.183   322  2154 V AudioFlinger:  pid 3192 @ 1
06-30 13:55:36.183   322  2154 V AudioFlinger:  pid 3192 @ 2
06-30 13:55:36.184  7047  7047 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
06-30 13:55:36.266  7441  7441 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,06-30 13:55:36.268  1036  1580 I ActivityManager: Process com.android.bluetooth (pid 7185) has died
06-30 13:55:36.268  1036  1580 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.opp.BluetoothOppService in 1000ms
06-30 13:55:36.269  1036  1580 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
06-30 13:55:36.282  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-30 13:55:36.289  7441  7441 I LibraryLoader: Loading: webviewchromium
06-30 13:55:36.292  7441  7441 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1573-1577)
06-30 13:55:36.292  7441  7441 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 13:55:36.298  7441  7441 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a453c10}
06-30 13:55:36.299  7441  7441 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:55:36.299  7441  7441 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:55:36.311  7047  7047 D BluetoothPermissionRequest: onReceive
06-30 13:55:36.312  7441  7441 I BrowserStartupController: Initializing chromium process, renderers=0
,06-30 13:55:36.313  7047  7047 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-30 13:55:36.313  7047  7047 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
06-30 13:55:36.313  7441  7441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:55:36.315  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-30 13:55:36.325  7441  7441 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,06-30 13:55:36.326  7441  7441 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
06-30 13:55:36.327  7441  7441 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
06-30 13:55:36.338   322   322 V AudioPolicyService: registerClient() client 0xb0410340, uid 10093
,06-30 13:55:36.341  7441  7492 W AudioManagerAndroid: Requires BLUETOOTH permission
06-30 13:55:36.348  1036  1958 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7500 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
06-30 13:55:36.350  7441  7441 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:55:36.350  7441  7441 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:55:36.350  7441  7441 I Adreno-EGL: Build Date: 12/12/14 금
06-30 13:55:36.350  7441  7441 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 13:55:36.350  7441  7441 I Adreno-EGL: Remote Branch: 
06-30 13:55:36.350  7441  7441 I Adreno-EGL: Local Patches: 
06-30 13:55:36.350  7441  7441 I Adreno-EGL: Reconstruct Branch: 
,06-30 13:55:36.380  7500  7500 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
06-30 13:55:36.380  7500  7500 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:55:36.380  7500  7500 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
06-30 13:55:36.381  7500  7500 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-30 13:55:36.391  7500  7500 D BluetoothAdapterApp: Loading JNI Library
,06-30 13:55:36.411  7500  7500 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@45e11e5 Instance Count = 1
,06-30 13:55:36.414  7500  7500 D BluetoothAdapterApp: onCreate
06-30 13:55:36.424  7441  7441 I NSApplication: Starting up...
06-30 13:55:36.429  7500  7500 D ProfileConfigQcom: [BTUI] HeadsetService is supported
06-30 13:55:36.429  7500  7500 D ProfileConfigQcom: Adding HeadsetService
06-30 13:55:36.429  7500  7500 D ProfileConfigQcom: [BTUI] A2dpService is supported
06-30 13:55:36.429  7500  7500 D ProfileConfigQcom: Adding A2dpService
06-30 13:55:36.430  7500  7500 D ProfileConfigQcom: [BTUI] HidService is supported
06-30 13:55:36.430  7500  7500 D ProfileConfigQcom: Adding HidService
06-30 13:55:36.430  7500  7500 D ProfileConfigQcom: [BTUI] HealthService is supported
06-30 13:55:36.430  7500  7500 D ProfileConfigQcom: Adding HealthService
06-30 13:55:36.430  7500  7500 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,06-30 13:55:36.430  7500  7500 D ProfileConfigQcom: [BTUI] PanService is supported
06-30 13:55:36.431  7500  7500 D ProfileConfigQcom: Adding PanService
06-30 13:55:36.431  7500  7500 D ProfileConfigQcom: [BTUI] GattService is supported
06-30 13:55:36.431  7500  7500 D ProfileConfigQcom: Adding GattService
06-30 13:55:36.431  7500  7500 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
06-30 13:55:36.431  7500  7500 D ProfileConfigQcom: Adding BluetoothMapService
06-30 13:55:36.431  7500  7500 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
06-30 13:55:36.432  7500  7500 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
06-30 13:55:36.436  7047  7047 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-30 13:55:36.437  7500  7500 V LGMDMManagerInternal: Create singleton instance
06-30 13:55:36.475  1036  1904 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7523 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:55:36.475  1036  1904 I ActivityManager: Killing 6639:com.android.vending/u0a44 (adj 15): empty #17
,06-30 13:55:36.613  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 13:55:36.613  6956  7023 I jxcore-log: 
,06-30 13:55:36.627  1036  1994 W libprocessgroup: failed to open /acct/uid_10044/pid_6639/cgroup.procs: No such file or directory
06-30 13:55:36.627  7500  7500 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:36.642  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 13:55:36.642  6956  7023 I jxcore-log: 
06-30 13:55:36.647  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 13:55:36.647  6956  7023 I jxcore-log: 
06-30 13:55:36.648  7500  7500 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:36.649  7500  7500 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 13:55:36.649  7500  7500 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:36.651  7500  7500 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:36.651  7500  7500 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,06-30 13:55:36.656  7134  7134 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
06-30 13:55:36.659  1036  1903 I ActivityManager: Killing 6778:com.lge.bnr/1000 (adj 15): empty #17
06-30 13:55:36.665  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 13:55:36.665  6956  7023 I jxcore-log: 
06-30 13:55:36.669  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 13:55:36.669  6956  7023 I jxcore-log: 
,06-30 13:55:36.673  7523  7523 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:55:36.776  1036  2050 W libprocessgroup: failed to open /acct/uid_1000/pid_6778/cgroup.procs: No such file or directory
,06-30 13:55:36.948  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,06-30 13:55:36.955  6512  7044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
06-30 13:55:36.966  2181  2181 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:36.977  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-30 13:55:36.977  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:36.977  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-30 13:55:36.977  7268  7268 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
06-30 13:55:36.978  6956  7019 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:36.978  6956  7019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:36.978  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:36.978  6956  7019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:36.978  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fb191ad removed from the list
,06-30 13:55:36.979  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:36.979  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ecce873 added. We now have 2 listener(s)
06-30 13:55:36.979  6956  7019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:55:36.981  7268  7268 I AppUp4:CustModeStarterReceiver: onReceive
06-30 13:55:36.981  6956  7019 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:36.981  6956  7019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:36.981  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:36.981  6956  7019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:36.981  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ecce873 removed from the list
06-30 13:55:36.981  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:36.981  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18043330 added. We now have 2 listener(s)
06-30 13:55:36.982  6956  7019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:55:36.983  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:36.983  1036  1994 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
06-30 13:55:36.984  1036  1118 D BluetoothManagerService: Message: 2
06-30 13:55:36.984  7268  7268 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@197f5747
06-30 13:55:36.984  7268  7268 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 13:55:36.984  7268  7268 D AppUp4:CustFacade: isPhone : true
,06-30 13:55:36.985  7268  7268 D AppUp4:CustModeStarterReceiver: begin check event
06-30 13:55:36.985  7268  7268 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
06-30 13:55:36.985  6956  7019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:36.987  1036  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:36.987  1036  2022 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
06-30 13:55:36.987  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:36.987  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:55:36.989  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:36.991  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,06-30 13:55:36.996  7306  7306 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
06-30 13:55:36.998  1036  1118 D BluetoothManagerService: Message: 1
06-30 13:55:36.998  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-30 13:55:36.999  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:36.999  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:36.999  1036  1036 D Ulp_jni : JNI:system_update. Event-4
06-30 13:55:37.003  4818  7555 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,06-30 13:55:37.014  4818  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:37.014  4818  7559 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:55:37.019  1036  1118 D BluetoothManagerService: Message: 20
06-30 13:55:37.019  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2230bc4e:true
,06-30 13:55:37.020  7500  7500 D BluetoothAdapterState: make
06-30 13:55:37.023  7500  7500 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
06-30 13:55:37.023  7500  7500 I bluedroid-qcom: init
06-30 13:55:37.023  7500  7564 I BluetoothAdapterState: Entering OffState
06-30 13:55:37.023  7500  7500 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
06-30 13:55:37.024  7500  7500 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
06-30 13:55:37.024  7500  7500 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
06-30 13:55:37.024  7500  7500 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
06-30 13:55:37.024  7500  7500 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
06-30 13:55:37.025  7500  7500 I bluedroid-qcom: get_profile_interface socket
06-30 13:55:37.025  7500  7500 I bluedroid-qcom: get_profile_interface map_client
06-30 13:55:37.026  7500  7571 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
06-30 13:55:37.028  7500  7571 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-30 13:55:37.022  7572  7572 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:37.022  7572  7572 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:37.035  7572  7572 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
06-30 13:55:37.035  7572  7572 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
06-30 13:55:37.035  7572  7572 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,06-30 13:55:37.038  7572  7572 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
06-30 13:55:37.039  7306  7561 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:37.040  7500  7571 D BluetoothAdapterProperties: Name is: G3
06-30 13:55:37.040  3192  3192 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
06-30 13:55:37.040  3192  3192 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:37.040  3192  3192 I LgeMiscReceiver: networkInfo.isConnected() = false
06-30 13:55:37.041  7572  7572 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
06-30 13:55:37.041  7572  7572 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
06-30 13:55:37.044  7162  7562 W FormManager: Network not available. Please check & try again.
06-30 13:55:37.047  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
06-30 13:55:37.047  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
06-30 13:55:37.062  7162  7563 V FormManager: Network unavailable.
,06-30 13:55:37.065  7420  7420 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:55:37
06-30 13:55:37.067  7420  7420 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-30 13:55:37.067  7420  7420 D Weather.Utils: 2 : All the weather widget is gone.
06-30 13:55:37.067  7420  7420 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 13:55:37.068  7420  7420 D WeatherAncestor: connectivity changed - connection : true
06-30 13:55:37.068  7420  7420 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c85989d
06-30 13:55:37.068  7162  7563 V FormManager: Network unavailable.
06-30 13:55:37.068  7420  7420 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
06-30 13:55:37.068  7420  7420 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
06-30 13:55:37.068  7420  7420 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
06-30 13:55:37.068  7420  7420 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 13:55:37.069  7420  7420 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:55:37
06-30 13:55:37.088  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:37.088  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:55:37.089  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,06-30 13:55:37.090  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:37.095  7065  7065 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
06-30 13:55:37.096  7065  7065 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:55:37.096  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:37.097  4818  7576 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:55:37.098  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:37.099  4818  7579 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:37.099  4818  7579 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,06-30 13:55:37.108  7162  7578 W FormManager: Network not available. Please check & try again.
06-30 13:55:37.111  7162  7580 V FormManager: Network unavailable.
06-30 13:55:37.113  7162  7580 V FormManager: Network unavailable.
06-30 13:55:37.116  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 13:55:37.134  1036  1036 I art     : Explicit concurrent mark sweep GC freed 35043(1733KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.660ms total 89.993ms
06-30 13:55:37.134  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
06-30 13:55:37.134  1036  1118 D BluetoothManagerService: Message: 40
,06-30 13:55:37.135  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
06-30 13:55:37.135  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-30 13:55:37.136  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
06-30 13:55:37.138  7500  7515 I bluedroid-qcom: config_hci_snoop_log
06-30 13:55:37.138  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-30 13:55:37.138  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
06-30 13:55:37.141   318  7582 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-30 13:55:37.142  7500  7564 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-30 13:55:37.142  7500  7564 D BluetoothAdapterProperties: Setting state to 11
06-30 13:55:37.142  7500  7564 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-30 13:55:37.142  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 13:55:37.142  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:37.142  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-30 13:55:37.142  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
06-30 13:55:37.143  7500  7564 I LGBluetoothServiceJni: classInitNative: succeeds
06-30 13:55:37.145  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:37.145  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:37.146  7047  7047 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
06-30 13:55:37.148  7500  7564 D BluetoothBondStateMachine: make
,06-30 13:55:37.149  7500  7564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.149  7500  7564 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
06-30 13:55:37.149  7500  7564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.149  7500  7500 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:55:37.149  7500  7564 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
06-30 13:55:37.150  7500  7583 I BluetoothBondStateMachine: StableState(): Entering Off State
06-30 13:55:37.150  7500  7564 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
06-30 13:55:37.150  7500  7500 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:37.150  7500  7500 V BluetoothPbapReceiver: ***********state = 11
06-30 13:55:37.152  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 13:55:37.156  7500  7564 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:37.161  7500  7500 D HeadsetService: Received start request. Starting profile...
06-30 13:55:37.161  7500  7564 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:37.162  7500  7500 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 13:55:37.162  7500  7500 D LGBluetoothHfpAdapter: Version 1.6
06-30 13:55:37.162  7047  7047 D BluetoothPermissionRequest: onReceive
06-30 13:55:37.164  7500  7500 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:55:37.164  7500  7564 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:37.164  7500  7500 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,06-30 13:55:37.166  7500  7500 D HeadsetStateMachine: make
06-30 13:55:37.168  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-30 13:55:37.170  7500  7564 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:37.173  7500  7564 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:37.184  7500  7564 E BluetoothAdapterService: File transfer profiles supported!!
,06-30 13:55:37.189  7500  7500 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:37.189  7500  7500 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 13:55:37.189  7500  7564 E BluetoothAdapterService: File transfer profiles supported!!
06-30 13:55:37.192  7500  7500 D HeadsetStateMachine: max_hf_connections = 1
06-30 13:55:37.192  7500  7500 I bluedroid-qcom: get_profile_interface handsfree
06-30 13:55:37.193  7500  7500 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
06-30 13:55:37.193   322  2154 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 1002
06-30 13:55:37.194   322   322 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-30 13:55:37.194   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:55:37.194   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:55:37.194  7500  7500 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-30 13:55:37.194   322  1386 V AudioFlinger: registerClient() client 0xb55815f8, pid 7500
06-30 13:55:37.194   322  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:37.194   322  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:37.194  1603  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:37.194  1603  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:37.194  7500  7500 V ToneGenerator: Create Track: 0xb4928080
06-30 13:55:37.194  1036  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:37.195  7500  7515 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:37.195  1036  1940 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:37.195  7500  7500 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-30 13:55:37.195  7500  7515 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-30 13:55:37.195  7500  7500 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
06-30 13:55:37.195   322  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:37.195   322  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:37.195  1036  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:37.195  1036  1940 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:37.195  1603  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:37.195  1603  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:37.195  3192  3211 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:37.195  7500  7515 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:37.195  3192  3211 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:37.195  7500  7515 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
06-30 13:55:37.195  3192  3211 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:37.195  3192  3211 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:37.195   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 13:55:37.195   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
06-30 13:55:37.195   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:55:37.195   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:55:37.195   322  1386 I AudioFlinger: isAudioPlaybackHookOn() false
06-30 13:55:37.195  1852  2401 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:55:37.195  1852  ,2401 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:55:37.195  1852  2401 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:55:37.196  1852  2401 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:55:37.196   322  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 13:55:37.196   322  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
06-30 13:55:37.196   322  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:55:37.196   322  1387 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:55:37.196  7500  7500 V AudioSystem: getLatency() output 2, latency 50
06-30 13:55:37.196  7500  7500 V AudioSystem: getFrameCount() output 2, frameCount 960
06-30 13:55:37.196  7500  7500 V AudioTrack: createTrack_l() output 2 afLatency 50
,06-30 13:55:37.196   322  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-30 13:55:37.196   322  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-30 13:55:37.196   322  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
06-30 13:55:37.196   322  2154 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
06-30 13:55:37.196   322  2154 V AudioFlinger: createTrack() lSessionId: 23
06-30 13:55:37.196  7500  7500 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-30 13:55:37.197   322   322 V AudioFlinger: acquiring 23 from 7500, for 7500
06-30 13:55:37.197   322   322 V AudioFlinger:  added new entry for 23
06-30 13:55:37.197  7500  7500 V ToneGenerator: ToneGenerator INIT OK, time: 302482
06-30 13:55:37.197  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.197  7500  7584 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-30 13:55:37.198  7500  7584 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:55:37.198  7500  7584 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:55:37.198  7500  7584 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-30 13:55:37.198   322  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7500
06-30 13:55:37.198  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.199  7500  7500 D A2dpService: Received start request. Starting profile...
06-30 13:55:37.200  7500  7500 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 13:55:37.200   322  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-30 13:55:37.200   322  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-30 13:55:37.200   322  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-30 13:55:37.200   322  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 13:55:37.200   322  1387 V voice   : voice_set_parameters: exit with code(0)
06-30 13:55:37.200   322  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-30 13:55:37.200   322  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-30 13:55:37.200   322  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 13:55:37.200   322  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 13:55:37.200   322  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 13:55:37.200   322  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
06-30 13:55:37.200  7500  7584 V ToneGenerator: ToneGenerator destructor
06-30 13:55:37.200  7500  7584 V ToneGenerator: stopTone
06-30 13:55:37.200  7500  7584 V ToneGenerator: Delete Track: 0xb4928080
06-30 13:55:37.200  7500  7500 V Avrcp   : make
06-30 13:55:37.200  7500  7584 V AudioTrack: ~AudioTrack, releasing session id from 7500 on behalf of 7500
06-30 13:55:37.200   322  2154 V AudioFlinger: releasing 23 from 7500 for 7500
06-30 13:55:37.201   322  2154 V AudioFlinger:  decremented refcount to 0
06-30 13:55:37.201   322  2154 V AudioFlinger: purging stale effects
06-30 13:55:37.201   322  2154 V AudioPolicyService: AudioCommandThread() adding release output 2
06-30 13:55:37.201   322  2154 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-30 13:55:37.201   322  1270 V AudioPolicyService: AudioCommandThread() waking up
06-30 13:55:37.201   322  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
06-30 13:55:37.201  7500  7500 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-30 13:55:37.201   322  1270 V AudioPolicyManager: releaseOutput,() 2
06-30 13:55:37.201  7500  7500 I bluedroid-qcom: get_profile_interface avrcp
06-30 13:55:37.201   322  1270 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 13:55:37.201   322  2154 V AudioFlinger: PlaybackThread::Track destructor
06-30 13:55:37.201   322  2154 V AudioFlinger: removeClient_l() pid 7500, calling pid 322
06-30 13:55:37.203  7500  7564 V LGMDMManager: Create singleton instance
06-30 13:55:37.205  1036  2022 W Process : Unable to open /proc/7585/status
06-30 13:55:37.205  7500  7564 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-30 13:55:37.206  7500  7500 V AudioManager: registerRemoteController: size of Media player list: 0
06-30 13:55:37.207  7500  7500 E AudioManager: No RCC entry present to update
06-30 13:55:37.207  7500  7500 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,06-30 13:55:37.209  7500  7500 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
06-30 13:55:37.210  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
06-30 13:55:37.210  7500  7500 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
06-30 13:55:37.212  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
06-30 13:55:37.291  1036  1667 V SIM_STK : Menu title from STK is T-Mobile
06-30 13:55:37.291  1036  1667 V SIM_STK : Menu title from STK is T-Mobile
,06-30 13:55:37.398  1036  1994 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,06-30 13:55:37.409  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
06-30 13:55:37.413  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 13:55:37.414  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
06-30 13:55:37.415  7500  7500 I BluetoothA2dpServiceJni: classInitNative
06-30 13:55:37.415  7500  7500 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-30 13:55:37.415  7500  7500 D A2dpStateMachine: make
06-30 13:55:37.416  7500  7500 I bluedroid-qcom: get_profile_interface a2dp
06-30 13:55:37.417  7500  7589 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 13:55:37.419  7500  7500 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
06-30 13:55:37.419  7500  7500 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-30 13:55:37.420  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.420  7500  7588 D A2dpStateMachine: Enter Disconnected: -2
06-30 13:55:37.421  7500  7500 I BluetoothHidServiceJni: classInitNative: succeeds
06-30 13:55:37.423  7500  7500 D HidService: Received start request. Starting profile...
06-30 13:55:37.423  7500  7500 I bluedroid-qcom: get_profile_interface hidhost
06-30 13:55:37.423  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.424  7500  7500 I BluetoothHealthServiceJni: classInitNative: succeeds
06-30 13:55:37.425  7500  7500 D HealthService: Received start request. Starting profile...
06-30 13:55:37.426  7500  7500 I bluedroid-qcom: get_profile_interface health
06-30 13:55:37.426  7500  7500 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-30 13:55:37.426  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.427  7500  7500 I BluetoothPanServiceJni: classInitNative(L105): succeeds
06-30 13:55:37.429  7500  7500 D PanService: Received start request. Starting profile...
06-30 13:55:37.429  7500  7500 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 13:55:37.429  7500  7500 I bluedroid-qcom: get_profile_interface pan
06-30 13:55:37.432  7500  7500 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
06-30 13:55:37.432  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.433  7500  7500 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,06-30 13:55:37.436  7500  7500 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 13:55:37.437  7500  7500 D BtGatt.GattService: Received start request. Starting profile...
06-30 13:55:37.437  7500  7500 D BtGatt.GattService: start()
06-30 13:55:37.437  7500  7500 I bluedroid-qcom: get_profile_interface gatt
06-30 13:55:37.437  7500  7500 D BtGatt.AdvertiseManager: advertise manager created
06-30 13:55:37.441  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.442  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.442  7500  7500 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-30 13:55:37.443  7500  7500 V BluetoothMapService: BluetoothMapBinder()
06-30 13:55:37.443  7500  7500 D BluetoothMapService: Received start request. Starting profile...
06-30 13:55:37.443  7500  7500 D BluetoothMapService: start()
06-30 13:55:37.446  7500  7500 D BluetoothMapEmailSettingsLoader: Found 0 applications
,06-30 13:55:37.446  7500  7500 D BluetoothMapEmailAppObserver: createReceiver()
06-30 13:55:37.447  7500  7500 D BluetoothMapEmailAppObserver: initObservers()
06-30 13:55:37.447  7500  7500 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
06-30 13:55:37.452  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:37.452  7500  7500 D HeadsetStateMachine: Proxy object connected
06-30 13:55:37.453  7500  7500 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
06-30 13:55:37.453  7500  7500 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
06-30 13:55:37.456  7500  7500 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:37.457  7500  7584 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:55:37.457  7500  7584 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 13:55:37.458  7500  7584 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-30 13:55:37.461  7500  7500 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:37.463  7500  7500 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:37.465  7500  7500 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,06-30 13:55:37.469  7500  7500 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:37.472  7500  7500 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
06-30 13:55:37.472  7500  7500 V PanService: [BTUI] SIM Extra State :ABSENT
06-30 13:55:37.475  7500  7500 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
06-30 13:55:37.475  7500  7500 V BluetoothMapService: Handler(): got msg=1
06-30 13:55:37.476  7500  7564 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-30 13:55:37.476  7500  7564 I bluedroid-qcom: enable
06-30 13:55:37.476  7500  7500 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:37.477  7500  7500 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 13:55:37.477  7500  7500 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:37.477  7500  7564 I bt_hci_bdroid: init
06-30 13:55:37.477  7500  7500 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:37.477  7500  7500 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
06-30 13:55:37.479  7500  7564 I bt_vendor: bt-vendor : init
06-30 13:55:37.479  7500  7596 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
06-30 13:55:37.479  7500  7596 I bt-btu  : btu_task pending for preload complete event
06-30 13:55:37.479  7500  7564 I bt_vendor: bt-vendor : get_bt_soc_type
,06-30 13:55:37.479  7500  7564 E bt_vendor: get_bt_soc_type: Failed to get soc type
06-30 13:55:37.479  7500  7564 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
06-30 13:55:37.480  7500  7564 D bt_userial_mct: userial_init
06-30 13:55:37.480  7500  7564 D bt_hci_bdroid: set_power 1
06-30 13:55:37.480  7500  7564 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
06-30 13:55:37.480  7500  7564 I bt_vendor: Starting hciattach daemon
06-30 13:55:37.480  7500  7564 I bt_vendor: try to set true
06-30 13:55:37.472  7599  7599 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:37.472  7599  7599 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:37.504  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,06-30 13:55:37.598  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,06-30 13:55:37.610  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,06-30 13:55:37.642  7609  7609 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,06-30 13:55:37.654  7610  7610 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,06-30 13:55:37.676  7611  7611 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,06-30 13:55:37.688  7612  7612 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
06-30 13:55:37.702  7617  7617 I libmdmdetect: ESOC framework not supported
06-30 13:55:37.703  7617  7617 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,06-30 13:55:37.718  7617  7617 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
06-30 13:55:37.718  7617  7617 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
06-30 13:55:37.718  7617  7617 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
06-30 13:55:37.718  7617  7617 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
06-30 13:55:37.718  7617  7617 D bthci_qcomm_common: [BTUI]     LE: Class 2
06-30 13:55:37.718  7617  7617 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
06-30 13:55:37.718  7617  7617 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,06-30 13:55:37.765  7617  7618 E QC-QMI  : qmi_client [7617] 15: failed to locate client data
,06-30 13:55:37.766   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
06-30 13:55:37.766   484   484 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
06-30 13:55:37.879  7619  7619 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,06-30 13:55:37.893  7620  7620 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
06-30 13:55:37.937  7500  7564 I bt_vendor: bluetooth satus is on
06-30 13:55:37.937  7500  7564 D bt_hci_bdroid: preload
,06-30 13:55:37.938  7500  7598 D bt_userial_mct: userial_open(port:0)
,06-30 13:55:37.938  7500  7598 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
06-30 13:55:37.942  7500  7598 I bt_vendor: Done intiailizing UART
06-30 13:55:37.945  7500  7598 I bt_vendor: Done intiailizing UART
06-30 13:55:37.945  7500  7598 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
06-30 13:55:37.945  7500  7598 I bt_vendor: Bluetooth Firmware and transport layer are initialized
06-30 13:55:37.945  7500  7596 I bt-btu  : btu_task received preload complete event
06-30 13:55:37.945  7500  7622 D bt_userial_mct: Entering userial_read_thread()
06-30 13:55:37.946  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
06-30 13:55:37.946  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,06-30 13:55:37.948  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_HCI
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_L2CAP
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_RFCOMM
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_AVDT
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_AVRC
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_A2D
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_BNEP
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_BTM
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_HID_HOST
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_GAP
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_PAN
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_SDP
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_GATT
,06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_SMP
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_BTAPP
06-30 13:55:37.952  7500  7596 I         : BTE_InitTraceLevels -- TRC_BTIF
06-30 13:55:38.009  6809  7234 D UEI.SmartControl: Internal timer expired: 2
06-30 13:55:38.009  6809  7234 D UEI.SmartControl: unbind internal service
,06-30 13:55:38.037  7500  7596 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
06-30 13:55:38.037  7500  7596 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0151061 
06-30 13:55:38.037  7500  7596 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0151061 
,06-30 13:55:38.065  6809  7231 D serial_port: close(fd = 24)
,06-30 13:55:38.076  6809  7231 I UEI.SmartControl: Serial port is closed.
06-30 13:55:38.086  7500  7571 E bt-btif : Calling BTA_HhEnable
06-30 13:55:38.086  7500  7571 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
06-30 13:55:38.087  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
06-30 13:55:38.088  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
06-30 13:55:38.088  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,06-30 13:55:38.088  7500  7571 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
06-30 13:55:38.089  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
06-30 13:55:38.089  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
06-30 13:55:38.090  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
06-30 13:55:38.090  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
06-30 13:55:38.091  7500  7571 D BluetoothAdapterProperties: Name is: G3
06-30 13:55:38.093  7500  7571 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:55:38.094  7500  7571 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:38.094  7500  7571 D bt_hci_bdroid: postload
06-30 13:55:38.096  7500  7598 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:38.096  7500  7598 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:38.096  7500  7598 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:38.096  7500  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
06-30 13:55:38.097  7500  7571 D bte_conf: Device ID record 1 : primary
06-30 13:55:38.097  7500  7571 D bte_conf:   vendorId            = 00c4
06-30 13:55:38.097  7500  7571 D bte_conf:   vendorIdSource      = 0001
06-30 13:55:38.097  7500  7571 D bte_conf:   product             = 13a1
06-30 13:55:38.097  7500  7571 D bte_conf:   version             = 1000
06-30 13:55:38.097  7500  7571 D bte_conf:   clientExecutableURL = 
06-30 13:55:38.097  7500  7571 D bte_conf:   serviceDescription  = 
,06-30 13:55:38.097  7500  7571 D bte_conf:   documentationURL    = 
06-30 13:55:38.097  7500  7571 D bte_conf: bte_load_did_conf no section named DID2.
06-30 13:55:38.098  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:38.099  7500  7564 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 13:55:38.099  7500  7564 D BluetoothAdapterProperties: ScanMode =  20
06-30 13:55:38.100  7500  7564 D BluetoothAdapterProperties: State =  11
06-30 13:55:38.100  7500  7564 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-30 13:55:38.092  7625  7625 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:38.092  7625  7625 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:38.106  7500  7598 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:38.107  7500  7564 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
06-30 13:55:38.107  7500  7564 D BluetoothAdapterProperties: Setting state to 12
06-30 13:55:38.107  7500  7564 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-30 13:55:38.108  7500  7571 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-30 13:55:38.108  7500  7571 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,06-30 13:55:38.114  7500  7598 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:38.114  7500  7598 D bt_hci_bdroid: Used up Tx Cmd credits
06-30 13:55:38.114  1036  1118 D BluetoothManagerService: Message: 60
06-30 13:55:38.115  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-30 13:55:38.115  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
06-30 13:55:38.115  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:55:38.115  7500  7564 I BluetoothAdapterState: Entering On State
06-30 13:55:38.122  7500  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 13:55:38.122  7500  7596 W bt-smp  : Plain text(LSB ~ MSB) = e7 52 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:55:38.122  7500  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = ff 54 bd 8f 26 02 65 c9 82 8b 8f a3 d8 8d 03 de 
06-30 13:55:38.122  7500  7596 W bt-btm  : Stopping oneshot timer
,06-30 13:55:38.123  7500  7622 E bt_mct  : hci lib postload completed
06-30 13:55:38.126  7500  7564 D LGBluetoothServiceAdapter: [BTUI] OnState
06-30 13:55:38.126  7500  7564 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
06-30 13:55:38.126  7500  7564 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
06-30 13:55:38.127  7500  7564 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-30 13:55:38.132  7500  7571 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:55:38.132  1852  1852 D BluetoothHeadset: Proxy object connected
06-30 13:55:38.132  7500  7571 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
06-30 13:55:38.132  1852  4486 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:55:38.134  1852  1852 D BluetoothHeadset: Proxy object connected
06-30 13:55:38.137  7047  7372 D BluetoothInputDevice: onBluetoothStateChange: up=true
,06-30 13:55:38.141  7047  7047 D BluetoothInputDevice: Proxy object connected
06-30 13:55:38.141  1852  4478 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:55:38.141  7047  7047 D HidProfile: Bluetooth service connected
06-30 13:55:38.146  1852  1852 D BluetoothHeadset: Proxy object connected
06-30 13:55:38.147  7047  7063 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 13:55:38.151  7500  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 13:55:38.151  7500  7596 W bt-smp  : Plain text(LSB ~ MSB) = a2 e7 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:55:38.151  7500  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 75 9f 4b a9 3e 4f 06 0f 81 2e ef 10 14 ef cf 52 
06-30 13:55:38.151  7500  7596 W bt-btm  : Stopping oneshot timer
,06-30 13:55:38.155  7630  7630 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
06-30 13:55:38.157  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 13:55:38.158  7047  7372 D BluetoothPbap: onBluetoothStateChange: up=true
06-30 13:55:38.158  1036  1036 D BluetoothA2dp: Proxy object connected
06-30 13:55:38.159  7047  7047 D BluetoothA2dp: Proxy object connected
06-30 13:55:38.159  7047  7047 D A2dpProfile: Bluetooth service connected
06-30 13:55:38.162  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
,06-30 13:55:38.163  1036  1036 D BluetoothHeadset: Proxy object connected
06-30 13:55:38.163  7047  7063 D BluetoothPan: onBluetoothStateChange on: true
06-30 13:55:38.163  7047  7063 D BluetoothPan: onBluetoothStateChange call bindService
06-30 13:55:38.165  7047  7064 D BluetoothMap: onBluetoothStateChange: up=true
06-30 13:55:38.165  7500  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 13:55:38.165  7500  7596 W bt-smp  : Plain text(LSB ~ MSB) = f2 c5 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:55:38.165  7500  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 2b b3 61 30 3f 9e ca 39 0e 98 3c 29 90 93 d6 76 
06-30 13:55:38.165  7500  7596 W bt-btm  : Stopping oneshot timer
06-30 13:55:38.165  7500  7564 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
06-30 13:55:38.167  7047  7372 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:55:38.169  7047  7047 D BluetoothHeadset: Proxy object connected
06-30 13:55:38.169  7047  7047 D HeadsetProfile: Bluetooth service connected
06-30 13:55:38.171  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-30 13:55:38.172  7047  7047 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 13:55:38.172  7047  7047 D PanProfile: Bluetooth service connected
06-30 13:55:38.172  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-30 13:55:38.172  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
06-30 13:55:38.173  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.174  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
06-30 13:55:38.174  1941  2143 D LGBluetoothAPIService: Message: 1
06-30 13:55:38.174  1941  2143 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
06-30 13:55:38.175  7500  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 13:55:38.175  7500  7596 W bt-smp  : Plain text(LSB ~ MSB) = c0 42 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:55:38.175  7500  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = f0 80 7b db 42 8e cc 6b ec 81 a4 44 6b 50 2b 60 
06-30 13:55:38.175  7500  7596 W bt-btm  : Stopping oneshot timer
,06-30 13:55:38.182  1036  1118 D BluetoothManagerService: Message: 40
06-30 13:55:38.182  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
06-30 13:55:38.183  7047  7047 D BluetoothMap: Proxy object connected
06-30 13:55:38.183  1941  2143 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
06-30 13:55:38.183  7047  7047 D MapProfile: Bluetooth service connected
06-30 13:55:38.183  7047  7047 D BluetoothMap: getConnectedDevices()
06-30 13:55:38.184  7500  7500 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.184  7500  7500 D BluetoothMapService: STATE_ON
06-30 13:55:38.184  7500  7500 V BluetoothMapService: Handler(): got msg=1
06-30 13:55:38.184  7500  7500 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
06-30 13:55:38.185  7500  7516 V BluetoothMapService: getConnectedDevices()
06-30 13:55:38.186  7500  7500 D LGBluetoothAPIServer: [BTUI] onCreate()
06-30 13:55:38.187  7500  7500 D LGBluetoothAPIServer: [BTUI] onBind()
06-30 13:55:38.188  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-30 13:55:38.188  1941  2143 D LGBluetoothAPIService: Message: 100
06-30 13:55:38.188  1941  2143 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,06-30 13:55:38.189  7500  7632 D BluetoothMapMasInstance: MAS initSocket()
06-30 13:55:38.190  7500  7632 D BluetoothMapMasInstance:   masId = 00
06-30 13:55:38.190  7500  7632 D BluetoothMapMasInstance:   msgTypes = 0e
06-30 13:55:38.190  7500  7632 D BluetoothMapMasInstance:   masName = SMS/MMS
06-30 13:55:38.190  7500  7632 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,06-30 13:55:38.191  7047  7047 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
06-30 13:55:38.191  1036  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:38.192  7500  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 13:55:38.192  7500  7596 W bt-smp  : Plain text(LSB ~ MSB) = b0 7b 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:55:38.192  7500  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 a6 e8 d4 ca 07 e9 e2 32 03 28 8c c9 01 7c ed 
06-30 13:55:38.192  7500  7596 W bt-btm  : Stopping oneshot timer
06-30 13:55:38.196  7500  7632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 13:55:38.197  7047  7047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:55:38.198  7500  7632 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
06-30 13:55:38.198  7500  7632 V BluetoothMapMasInstance: Succeed to create listening socket 
06-30 13:55:38.198  7500  7632 D BluetoothMapMasInstance: Accepting socket connection...
06-30 13:55:38.203  7500  7571 D BluetoothAdapterProperties: Scan Mode:21
06-30 13:55:38.204  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:38.204  7500  7500 V BluetoothPbapService: Pbap Service onCreate
06-30 13:55:38.204  7500  7500 V BluetoothPbapService: Starting PBAP service
06-30 13:55:38.205  7500  7571 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,06-30 13:55:38.208  7500  7500 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-30 13:55:38.208  7500  7500 V BluetoothPbapService: Pbap Service onBind
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:38.209  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:38.209  7500  7500 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.209  7500  7500 V BluetoothPbapService: state: 12
06-30 13:55:38.209  7500  7500 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:55:38.209  7500  7500 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.209  7500  7500 V BluetoothPbapReceiver: ***********state = 12
06-30 13:55:38.211  7500  7500 V BluetoothPbapService: Handler(): got msg=1
06-30 13:55:38.211  7500  7500 V BluetoothPbapService: Pbap Service startRfcommSocketListener
06-30 13:55:38.212  7047  7047 D DockEventReceiver: finishStartingService: stopping service
06-30 13:55:38.213  7047  7047 D BluetoothPbap: Proxy object connected
06-30 13:55:38.213  7047  7047 D PbapServerProfile: Bluetooth service connected
06-30 13:55:38.213  7500  7639 V BluetoothPbapService: Pbap Service initSocket
06-30 13:55:38.214  1036  1580 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:38.214  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:38.215  7500  7639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:38.215  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:38.216  2181  2181 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 13:55:38.217  7500  7639 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
06-30 13:55:38.217  7500  7639 V BluetoothPbapService: Succeed to create listening socket 
06-30 13:55:38.217  7500  7639 V BluetoothPbapService: Accepting socket connection...
06-30 13:55:38.217  2181  2181 D c       : Getting all permits...
06-30 13:55:38.217  2181  2181 D a       : Opening database...
06-30 13:55:38.221  2181  2181 D a       : Opening database auth,.proximity.permit_store...
,06-30 13:55:38.224  2181  2181 D a       : Closing database...
06-30 13:55:38.225  6956  7019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:38.227  6956  7019 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:38.227  6956  7019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:38.227  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:38.227  6956  7019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:38.227  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18043330 removed from the list
06-30 13:55:38.228  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:55:38.228  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8829ba9 added. We now have 2 listener(s)
06-30 13:55:38.228  6956  7019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:55:38.231  1036  1994 D WifiServiceImplEx: setWifiEnabled: false pid=6956, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
06-30 13:55:38.231  1036  1994 D WifiService: setWifiEnabled: false pid=6956, uid=10118
06-30 13:55:38.231  1036  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
06-30 13:55:38.233  7047  7047 D BluetoothPermissionRequest: onReceive
06-30 13:55:38.235  6956  7019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:38.235  7047  7047 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,06-30 13:55:38.237  7047  7047 D LGBluetoothResetSettingReceiver: return without doing reset settings.
06-30 13:55:38.237  1036  1776 D WifiServiceImplEx: setWifiEnabled: true pid=6956, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
06-30 13:55:38.238  1036  1776 D WifiService: setWifiEnabled: true pid=6956, uid=10118
06-30 13:55:38.238  1036  1776 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
06-30 13:55:38.240  7500  7500 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
06-30 13:55:38.241  7500  7500 I LGBluetoothOppAdapter: [BTUI] startOppService()
06-30 13:55:38.246  7500  7500 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,06-30 13:55:38.248  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:38.248  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:55:38.248  1036  1036 D Ulp_jni : JNI:system_update. Event-4
06-30 13:55:38.250  1036  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
06-30 13:55:38.250  1036  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
06-30 13:55:38.250  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
06-30 13:55:38.250  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-30 13:55:38.250  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
06-30 13:55:38.250  1036  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
06-30 13:55:38.250  1036  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
06-30 13:55:38.250  1036  1538 E WifiHW  : unknown target_country: EU , set to default
06-30 13:55:38.250  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
06-30 13:55:38.250  1036  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
06-30 13:55:38.251  1036  1538 I WifiUtil: gEnableBmps=1
06-30 13:55:38.269  7500  7500 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,06-30 13:55:38.269  7500  7500 V BtOppService: onCreate
06-30 13:55:38.273  7500  7500 V BluetoothOppNotification: send message
06-30 13:55:38.277  7500  7500 V BtOppService: Starting RfcommListener
06-30 13:55:38.281  7500  7500 D BluetoothOppPreference: Dumping Names:  
06-30 13:55:38.281  7500  7500 D BluetoothOppPreference: {}
06-30 13:55:38.281  7500  7500 D BluetoothOppPreference: Dumping Channels:  
06-30 13:55:38.281  7500  7500 D BluetoothOppPreference: {}
06-30 13:55:38.282  7500  7500 V BtOppService: onStartCommand
,06-30 13:55:38.283  7500  7649 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
06-30 13:55:38.284  7500  7649 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 13:55:38.286  7500  7500 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.286  7500  7646 V BtOppService: Deleted complete outbound shares, number =  0
06-30 13:55:38.286  7500  7500 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
06-30 13:55:38.289  7500  7646 V BtOppService: Deleted complete inbound failed shares, number = 0
06-30 13:55:38.289  7500  7646 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-30 13:55:38.290  7500  7646 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25d4766e on behalf of 
06-30 13:55:38.291  7500  7649 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ea0210f on behalf of 
06-30 13:55:38.292  7500  7500 V BluetoothOppNotification: new notify threadi!
06-30 13:55:38.293  7500  7500 V BluetoothOppNotification: send delay message
06-30 13:55:38.294  7500  7500 V BtOppService: start RfcommListener
06-30 13:55:38.295  7500  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,06-30 13:55:38.297  7500  7500 V BtOppService: RfcommListener started
06-30 13:55:38.297  7500  7500 V BtOppService: ContentObserver received notification
06-30 13:55:38.298  7500  7651 V BtOppRfcommListener: Starting RFCOMM listener....
06-30 13:55:38.299  1036  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:38.300  7500  7651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 13:55:38.301  7500  7651 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
06-30 13:55:38.302  7500  7651 V BtOppRfcommListener: Started RFCOMM listener....
06-30 13:55:38.302  7500  7651 I BtOppRfcommListener: Accept thread started.
06-30 13:55:38.302  7500  7651 V BtOppRfcommListener: Accepting connection...
06-30 13:55:38.302  7500  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34dad59c on behalf of 
06-30 13:55:38.303  7500  7649 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
06-30 13:55:38.303  7500  7649 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 13:55:38.303  7500  7650 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-30 13:55:38.304  7500  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-30 13:55:38.305  7500  7649 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eaaba5 on behalf of 
06-30 13:55:38.306  7500  7649 V BluetoothOppNotification: update too frequent, put in queue
06-30 13:55:38.307  7500  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ad58b7a on behalf of 
06-30 13:55:38.308  7500  7649 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
06-30 13:55:38.308  7500  7650 V BluetoothOppNotification: outbound: succ-0  fail-0
,06-30 13:55:38.310  7500  7650 V BluetoothOppNotification: outbound notification was removed.
06-30 13:55:38.311  7500  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-30 13:55:38.312  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:38.312  7500  7500 V BluetoothFtpService: Ftp Service onCreate
06-30 13:55:38.312  7500  7500 I BluetoothFtpService: Ftp Service onCreate
06-30 13:55:38.312  7500  7500 V BluetoothFtpService: Ftp Service onStartCommand
06-30 13:55:38.312  7500  7500 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.312  7500  7500 V BluetoothFtpService: Starting Listening on sockets
06-30 13:55:38.312  7500  7500 V BtOppService: ContentObserver received notification
06-30 13:55:38.313  7500  7500 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:55:38.313  7500  7500 V BluetoothSapReceiver: [BTUI] region:EU country:EU
06-30 13:55:38.313  7500  7500 V BluetoothSapReceiver: SapReceiver onReceive 
06-30 13:55:38.313  7500  7500 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.313  7500  7500 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
06-30 13:55:38.313  7500  7652 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
06-30 13:55:38.313  7500  7500 V BluetoothSapReceiver: Calling SAP service start service with action = null
06-30 13:55:38.313  7500  7652 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 13:55:38.315  7500  7500 V BluetoothFtpService: Handler(): got msg=1
06-30 13:55:38.316  7500  7500 V BluetoothFtpService: Ftp Service startRfcommSocketListener
06-30 13:55:38.316  7500  7500 V BluetoothFtpService: Ftp Service initSocket
06-30 13:55:38.318  7500  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@328daf88 on behalf of 
06-30 13:55:38.319  7500  7652 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cff5d21 on behalf of 
06-30 13:55:38.319  7500  7650 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 13:55:38.320  7500  7652 V BluetoothOppNotification: update too frequent, put in queue
06-30 13:55:38.320  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:38.321  7500  7500 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 13:55:38.322  7500  7500 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=79
06-30 13:55:38.322  7500  7500 V BluetoothFtpService: Succeed to create listening socket on channel 20
06-30 13:55:38.324  7500  7652 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
06-30 13:55:38.325  7500  7653 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
06-30 13:55:38.326  7500  7650 V BluetoothOppNotification: inbound notification was removed.
06-30 13:55:38.326  7500  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-30 13:55:38.329  7500  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fa0e546 on behalf of 
06-30 13:55:38.337  7500  7500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c85989d
06-30 13:55:38.337  7500  7500 V BluetoothSapService: Sap Service onCreate
,06-30 13:55:38.339  7500  7500 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:55:38.339  7500  7500 V BluetoothSapService: state: 12
06-30 13:55:38.339  7500  7500 V BluetoothSapService: Starting SAP server process
06-30 13:55:38.332  7654  7654 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:38.332  7654  7654 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file,
06-30 13:55:38.345  7500  7500 V BluetoothSapService: SAP Service startRfcommListenerThread
06-30 13:55:38.346  7500  7655 V BluetoothSapService: Sap Service initRfcommSocket
06-30 13:55:38.346  1036  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:55:38.347  7500  7655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 13:55:38.348  7500  7655 V BluetoothSapService: Succeed to create listening socket 
06-30 13:55:38.348  7500  7655 V BluetoothSapService: Accepting socket connection...
,06-30 13:55:38.351  7654  7654 V BT_SAP  : Event pipe created
06-30 13:55:38.351  7654  7654 V BT_SAP  : create_server_socket qcom.sap.server
06-30 13:55:38.351  7654  7654 V BT_SAP  : created socket fd 6
06-30 13:55:38.830  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:38.830  1036  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:55:39.152   318   894 D SoftapController: Softap fwReload - Ok
06-30 13:55:39.153  1036  1538 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (901ms)
06-30 13:55:39.155   318   894 D CommandListener: Setting iface cfg
06-30 13:55:39.155   318   894 D CommandListener: Trying to bring down wlan0
06-30 13:55:39.155   318   894 D CommandListener: Clearing all IP addresses on wlan0
,06-30 13:55:39.158  1036  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
06-30 13:55:39.159  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
06-30 13:55:39.159  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:39.159  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 13:55:39.164  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-30 13:55:39.164  1036  1118 D Tethering: InitialState.processMessage what=4
06-30 13:55:39.172  1036  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
06-30 13:55:39.172  1036  1538 D WifiMonitor: connecting to supplicant
06-30 13:55:39.176  7669  7669 I wpa_supplicant: Successfully initialized wpa_supplicant
06-30 13:55:39.189  7669  7669 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 13:55:39.189  7669  7669 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
06-30 13:55:39.162  7669  7669 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:39.162  7669  7669 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,06-30 13:55:39.196  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
06-30 13:55:39.197  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:39.197  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:55:39.211  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 13:55:39.213  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
06-30 13:55:39.215  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:39.215  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:39.215  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:39.215  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:39.217  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,06-30 13:55:39.217  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:39.217  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-30 13:55:39.217  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:39.217  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:39.217  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,06-30 13:55:39.217  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-30 13:55:39.218  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 13:55:39.222  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:39.222  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:39.223  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:39.223  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:39.223  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 13:55:39.224  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:39.224  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-30 13:55:39.224  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:39.224  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:39.224  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 13:55:39.224  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 13:55:39.231  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:39.233  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:55:39.239  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:39.253  7162  7683 V FormManager: Network unavailable.
,06-30 13:55:39.254  7162  7682 W FormManager: Network not available. Please check & try again.
06-30 13:55:39.254  7162  7683 V FormManager: Network unavailable.
06-30 13:55:39.294  7500  7500 V BluetoothOppNotification: new notify threadi!
,06-30 13:55:39.294  7500  7500 V BluetoothOppNotification: send delay message
06-30 13:55:39.295  7500  7684 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
06-30 13:55:39.296  7500  7684 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5760fd2 on behalf of 
,06-30 13:55:39.297  7500  7684 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-30 13:55:39.298  7500  7684 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-30 13:55:39.298  7669  7669 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 13:55:39.300  7500  7684 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a82e8a3 on behalf of 
06-30 13:55:39.301  7500  7684 V BluetoothOppNotification: outbound: succ-0  fail-0
06-30 13:55:39.303  7500  7684 V BluetoothOppNotification: outbound notification was removed.
06-30 13:55:39.304  7500  7684 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-30 13:55:39.306  7500  7684 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3db0e7a0 on behalf of 
06-30 13:55:39.307  7500  7684 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 13:55:39.310  7500  7684 V BluetoothOppNotification: inbound notification was removed.
06-30 13:55:39.310  7500  7684 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-30 13:55:39.311  7500  7684 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30a58f59 on behalf of 
,06-30 13:55:39.374  7669  7669 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,06-30 13:55:39.389  7669  7669 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
06-30 13:55:39.389  7669  7669 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
06-30 13:55:39.393  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,06-30 13:55:39.394  1036  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
06-30 13:55:39.394  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,06-30 13:55:39.395  1036  7685 D WifiMonitor: Dropping event because (p2p0) is stopped
06-30 13:55:39.395  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
06-30 13:55:39.395  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
06-30 13:55:39.396  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
06-30 13:55:39.396  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
06-30 13:55:39.396  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
06-30 13:55:39.398  1036  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
06-30 13:55:39.400  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 2 0
06-30 13:55:39.401  1036  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
06-30 13:55:39.403  1036  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:39.404  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:39.405  1036  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
06-30 13:55:39.405  1036  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
06-30 13:55:39.406  1036  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
06-30 13:55:39.407  1036  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
06-30 13:55:39.407  1036  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,06-30 13:55:39.407  1036  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : ,
06-30 13:55:39.407  1036  1538 E WifiStateMachine: useWiFiOffloading() : false
06-30 13:55:39.407  1036  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
06-30 13:55:39.408  1036  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
06-30 13:55:39.408  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:39.408  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:39.408  1036  1538 D WifiNative-wlan0: SET update_config 1: returned true
06-30 13:55:39.408  1036  1538 D WifiConfigStore: Loading config and enabling all networks 
06-30 13:55:39.408  1036  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
06-30 13:55:39.409  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:39.409  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:39.409  1036  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
06-30 13:55:39.409  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:55:39.411  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:39.412  1941  1941 D WfdService: Waiting for WifiP2p enabling
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:39.421  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:39.423  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:55:39.427  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-30 13:55:39.427  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-30 13:55:39.431  1036  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-30 13:55:39.433  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:39.436  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:55:39.440  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:39.440  1036  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,06-30 13:55:39.443  1036  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-30 13:55:39.449  1036  1538 D WifiStateMachine: enableVerboseLogging : level 2
06-30 13:55:39.449  1036  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
06-30 13:55:39.449  1036  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
06-30 13:55:39.449  1036  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
06-30 13:55:39.449  1036  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
06-30 13:55:39.449  1036  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
06-30 13:55:39.450  1036  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
06-30 13:55:39.450  1036  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
06-30 13:55:39.450  1036  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
06-30 13:55:39.450  1036  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
06-30 13:55:39.450  7162  7688 W FormManager: Network not available. Please check & try again.
06-30 13:55:39.451  1036  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
06-30 13:55:39.451  1036  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
06-30 13:55:39.451  1036  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,06-30 13:55:39.451  1036  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
06-30 13:55:39.451  1036  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
06-30 13:55:39.452  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:55:39.452  1036  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
06-30 13:55:39.452  1941  1941 D WfdsService: Supplicant Connection state is changed : true
06-30 13:55:39.452  1941  2340 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-30 13:55:39.452  1941  2340 D WfdsService: Set the WFDS Monitor: true
06-30 13:55:39.452  1941  2340 D WfdsMonitor: WfdsMonitorThread create
06-30 13:55:39.453  1036  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
06-30 13:55:39.453  1036  1538 D WifiNative-HAL: Setting external_sim to 1
06-30 13:55:39.453  1036  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
06-30 13:55:39.453  1941  2340 D WfdsMonitor: WFDS Monitor is created and started
06-30 13:55:39.453  1941  2340 D WfdsService: WiFi: Supplicant connection re-established
06-30 13:55:39.453  1036  1538 D WifiNative-wlan0: SET external_sim 1: returned true
06-30 13:55:39.453  1036  1538 I WifiNative-HAL: startHal
06-30 13:55:39.453  1036  1538 D wifi    : setting scan oui 0xaf650160
06-30 13:55:39.453  1941  7690 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-30 13:55:39.454  1036  1538 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:55:39.454  1941  7690 E CtrlSupplicant: Succeed to open control connection
06-30 13:55:39.454  1036  1538 I WifiNative-HAL: startHal
06-30 13:55:39.454  1036  1538 D wifi    : setting scan oui 0xaf650160
06-30 13:55:39.454  1941  7690 E CtrlSupplicant: Succeed to open monitor connection
06-30 13:55:39.454  1036  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
06-30 13:55:39.454  1036  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
06-30 13:55:39.454  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
06-30 13:55:39.454  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
06-30 13:55:39.454  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
06-30 13:55:39.455  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-30 13:55:39.455  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
06-30 13:55:39.456  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-30 13:55:39.456  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
06-30 13:55:39.456  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
06-30 13:55:39.456  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
06-30 13:55:39.456  7669  7669 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
06-30 13:55:39.457  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
06-30 13:55:39.457  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
06-30 13:55:39.457  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
06-30 13:55:39.457  7162  7689 V FormManager: Network unavailable.
06-30 13:55:39.457  1036  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
06-30 13:55:39.457  1036  1538 E WifiNative: : [304,728,474 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
06-30 13:55:39,.457  1036  1538 D WifiNative-wlan0: doBoolean: RECONNECT
06-30 13:55:39.457  1941  7690 D WfdsMonitor: Supplicant connection established
06-30 13:55:39.458  1941  2340 D WfdsService: Connected to the supplicant for wfds
06-30 13:55:39.458  1036  1538 D WifiNative-wlan0: RECONNECT: returned true
06-30 13:55:39.458  1036  1538 D WifiNative-wlan0: doString: [STATUS]
06-30 13:55:39.458  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
06-30 13:55:39.458  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-30 13:55:39.458  7162  7689 V FormManager: Network unavailable.
06-30 13:55:39.458  1036  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
06-30 13:55:39.458  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
06-30 13:55:39.459  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
06-30 13:55:39.459  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.459  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
06-30 13:55:39.460  1036  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
06-30 13:55:39.460  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 13:55:39.460  1036  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
06-30 13:55:39.460  1036  1036 D RttService: SCAN_AVAILABLE : 3
06-30 13:55:39.460  1036  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.460  1036  1556 I WifiNative-HAL: startHal
06-30 13:55:39.460  1036  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf650160
06-30 13:55:39.460  1036  1556 D wifi    : failed to get capabilities : -3
06-30 13:55:39.460  1036  1556 E WifiScanningService: could not get scan capabilities
06-30 13:55:39.460  1036  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
06-30 13:55:39.460  1036  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
06-30 13:55:39.461  1036  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
06-30 13:55:39.461  1036  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
06-30 13:55:39.461  1036  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
06-30 13:55:39.461  7669  7669 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,06-30 13:55:39.461  1036  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:55:39.461   318   894 D CommandListener: Setting iface cfg
06-30 13:55:39.461   318   894 D CommandListener: Trying to bring up p2p0
06-30 13:55:39.462  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 13:55:39.462  1036  1537 D LGWifiP2pService: P2pEnablingState
06-30 13:55:39.462  1036  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
06-30 13:55:39.462  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.462  1036  1537 D LGWifiP2pService: P2p socket connection successful
06-30 13:55:39.462  1036  1537 D LGWifiP2pService: P2pEnabledState
06-30 13:55:39.462  1036  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
06-30 13:55:39.462  1036  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
06-30 13:55:39.462  1036  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
06-30 13:55:39.462  7669  7669 E wpa_supplicant: disconnect_rssi_lvl: -100
06-30 13:55:39.463  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:55:39.463  6956  7019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:55:39.463  1036  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
06-30 13:55:39.464  1036  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
06-30 13:55:39.464  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
06-30 13:55:39.464  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
06-30 13:55:39.464  6956  7019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:55:39.465  6956  7019 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:55:39.465  6956  7019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:55:39.465  6956  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:55:39.465  6956  7019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:55:39.465  7669  7669 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.465  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,06-30 13:55:39.465  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.465  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.465  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.465  6956  7019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8829ba9 removed from the list
06-30 13:55:39.466  7669  7669 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
06-30 13:55:39.466  7669  7669 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.466  7669  7669 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.467  1941  7690 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.467  1941  7690 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.468  1036  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
06-30 13:55:39.468  1036  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
06-30 13:55:39.469  1036  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.469  1036  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.469  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.469  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.469  1036  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.469  1036  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.469  1036  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
06-30 13:55:39.469  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.469  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.469  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
06-30 13:55:39.469  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
06-30 13:55:39.470  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
06-30 13:55:39.470  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
06-30 13:55:39.470  1036  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
06-30 13:55:39.470  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
06-30 13:55:39.470  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
06-30 13:55:39.471  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-30 13:55:39.471  1036  1537 D LGWifiP2pService: before postfix = G3
06-30 13:55:39.471  1036  1537 D WifiServerServiceExt: postfix byte check : 2
06-30 13:55:39.471  1036  1537 D LGWifiP2pService: after postfix = G3
06-30 13:55:39.471  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
06-30 13:55:39.471  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
06-30 13:55:39.471  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
06-30 13:55:39.471  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
06-30 13:55:39.471  1941  1941 D WfdsService: WifiP2pState is changed : true
06-30 13:55:39.471  1941  2340 D WfdsService: Receive the WFDS_ENABLE Method
06-30 13:55:39.471  1941  2340 D WfdsService: Set the WFDS Monitor: true
06-30 13:55:39.471  1941  2340 D WfdsService: Connected to the supplicant for wfds
06-30 13:55:39.471  1941  2340 D WfdsJNI : doCommand: WFDS_SET TRUE
06-30 13:55:39.471  7669  7669 I wpa_supplicant: WFDS:, wfds_supplicant_wfds_cmd: cmd = SET TRUE
06-30 13:55:39.472  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
06-30 13:55:39.472  1941  2340 D WfdsService: selectPreferredScanChannel [36]
06-30 13:55:39.472  1941  2340 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
06-30 13:55:39.472  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-30 13:55:39.472  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
06-30 13:55:39.472  7669  7669 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 13:55:39.472  1941  1941 D WfdsService: isConnected: false
06-30 13:55:39.473  1036  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
06-30 13:55:39.473  1036  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
06-30 13:55:39.473  1036  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
06-30 13:55:39.473  1036  1538 D WifiNative-wlan0: doBoolean: SCAN
06-30 13:55:39.473  1036  1538 D WifiNative-wlan0: SCAN: returned false
06-30 13:55:39.474  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=304745  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-30 13:55:39.474  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
06-30 13:55:39.474  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 13:55:39.474  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 13:55:39.474  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 13:55:39.474  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
06-30 13:55:39.475  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
06-30 13:55:39.475  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
06-30 13:55:39.475  6956  7019 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
06-30 13:55:39.475  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=304746  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-30 13:55:39.475  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
06-30 13:55:39.475  1036  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:39.476  6956  7019 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
06-30 13:55:39.476  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
06-30 13:55:39.476  6956  7019 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
06-30 13:55:39.476  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
06-30 13:55:39.476  1036  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:39.476  1036  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:39.476  1036  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:39.476  1036  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-30 13:55:39.477  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
06-30 13:55:39.477  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
06-30 13:55:39.478  1603  1603 I StatusBar.NetworkController: net,workInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:39.478  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:39.479  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:39.479  6956  7019 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
06-30 13:55:39.479  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-30 13:55:39.480  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
06-30 13:55:39.480  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
06-30 13:55:39.480  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
06-30 13:55:39.481  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
06-30 13:55:39.481  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
06-30 13:55:39.481  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
06-30 13:55:39.482  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
06-30 13:55:39.482  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
06-30 13:55:39.482  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
06-30 13:55:39.484  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:39.484  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:39.484  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-30 13:55:39.484  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 13:55:39.484  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
06-30 13:55:39.485  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
06-30 13:55:39.485  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
06-30 13:55:39.485  1941  1941 D WfdsService: Update P2p Interface State: 3
06-30 13:55:39.485  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
06-30 13:55:39.485  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
06-30 13:55:39.489  6956  7019 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
06-30 13:55:39.489  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:39.489  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
06-30 13:55:39.489  6956  7019 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
06-30 13:55:39.489  6956  7019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
06-30 13:55:39.490  6956  7019 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
06-30 13:55:39.490  6956  7019 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
06-30 13:55:39.491  6956  7019 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
06-30 13:55:39.491  6956  7019 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
06-30 13:55:39.491  6956  7019 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
06-30 13:55:39.491  6956  7019 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
06-30 13:55:39.492  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
06-30 13:55:39.492  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
06-30 13:55:39.492  1036  1537 D LGWifiP2pService: InactiveState
06-30 13:55:39.492  1036  1537 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.492  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.492  1036  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
06-30 13:55:39.493  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
06-30 13:55:39.493  7669  7669 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.493  1036  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
06-30 13:55:39.493  1036  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.493  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.493  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
06-30 13:55:39.493  1941  7690 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
06-30 13:55:39.493  7669  7669 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
06-30 13:55:39.493  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:55:39.493  7669  7669 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.493  6956  7019 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
06-30 13:55:39.493  1941  7690 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.493  1036  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.494  1036  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.494  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.494  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.494  7669  7669 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.494  6956  7019 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
06-30 13:55:39.494  1941  7690 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.494  1036  7685 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
06-30 13:55:39.494  1036  7685 E WifiMonitor: WifiMonitor:p2p0 cnt=33 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.494  1036  7685 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.494  1036  7685 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
06-30 13:55:39.495  1036  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.495  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:39.495  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.496  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.496  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.496  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.496  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.496  1036  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:39.496  1036  1036 E WifiServerServiceExt: No p2p device connected
06-30 13:55:39.497  1941  2340 W WfdsService: DefaultState - msg [9441285] is not handled
06-30 13:55:39.497  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:39.499  6956  7019 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b236ad1 Bundle[{}]
06-30 13:55:39.500  6956  7019 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:55:39.500  6956  7019 I io.jxcore.node.LifeCycleMonitor: stop: OK
06-30 13:55:39.500  6956  7019 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
06-30 13:55:39.501  6956  7019 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 13:55:39.501  4818  7691 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:55:39.502  6956  7019 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 13:55:39.502  6956  7019 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 13:55:39.506  4818  7692 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:55:39.506  4818  7692 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:55:39.507  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 13:55:39.507  6956  7023 I jxcore-log: 
,06-30 13:55:39.511  6956  7693 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 835, name: My test thread name)
06-30 13:55:39.512  6956  7693 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 835, thread name: My test thread name)
06-30 13:55:39.512  6956  7693 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 835, name: My test thread name)
06-30 13:55:39.514  6956  7694 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 837, name: My test thread name)
06-30 13:55:39.514  6956  7694 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 837, thread name: My test thread name)
06-30 13:55:39.514  6956  7694 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 837, name: My test thread name)
06-30 13:55:39.515  6956  7019 E THALI UNIT TEST: Total number of executed tests: 36
06-30 13:55:39.515  6956  7019 E THALI UNIT TEST: Number of passed tests: 36
06-30 13:55:39.515  6956  7019 E THALI UNIT TEST: Number of failed tests:  0
06-30 13:55:39.515  6956  7019 E THALI UNIT TEST: Number of ignored tests: 0
06-30 13:55:39.515  6956  7019 E THALI UNIT TEST: Total duration: 8779 ms
06-30 13:55:39.515  6956  7019 I System.out: Tests succeded_00
06-30 13:55:39.516  6956  7019 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 8856ms. Plugin should use CordovaInterface.getThreadPool().
06-30 13:55:39.528  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 13:55:39.528  6956  7023 I jxcore-log: 
06-30 13:55:39.529  1036  1051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7695 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
06-30 13:55:39.538  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 13:55:39.538  6956  7023 I jxcore-log: 
,06-30 13:55:39.594  7695  7695 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 13:55:39.594  7695  7695 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
06-30 13:55:39.605  7695  7695 V [BNRBootReceiver]: Boot Receiver Return
06-30 13:55:39.605  7695  7695 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 13:55:39.608  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,06-30 13:55:39.619  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:55:39.632  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:39.642  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-30 13:55:39.642  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:39.645  7111  7111 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-30 13:55:39.706  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 13:55:39.706  6956  7023 I jxcore-log: 
,06-30 13:55:39.790  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 13:55:39.790  6956  7023 I jxcore-log: 
,06-30 13:55:39.851  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 13:55:39.851  6956  7023 I jxcore-log: 
,06-30 13:55:39.858  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 13:55:39.858  6956  7023 I jxcore-log: 
06-30 13:55:40.031  7669  7669 E wpa_supplicant: USIM:  scard_init function
06-30 13:55:40.032  7669  7669 I wpa_supplicant: Trying to associate with SSID 'NG700'
,06-30 13:55:40.035  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,06-30 13:55:40.035  1036  7685 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
06-30 13:55:40.035  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
06-30 13:55:40.035  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
06-30 13:55:40.035  1036  7685 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
06-30 13:55:40.036  1036  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
06-30 13:55:40.037  1036  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
06-30 13:55:40.038  1036  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
06-30 13:55:40.039  1036  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
06-30 13:55:40.039  1036  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
06-30 13:55:40.046  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
06-30 13:55:40.046  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
06-30 13:55:40.054  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
06-30 13:55:40.059  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=305330  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,06-30 13:55:40.063  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.063  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:40.064  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.064  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.064  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.064  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-30 13:55:40.068  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 13:55:40.068  6956  7023 I jxcore-log: 
06-30 13:55:40.072  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.072  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.072  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-30 13:55:40.073  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=305344  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
06-30 13:55:40.074  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 13:55:40.074  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,06-30 13:55:40.082  7047  7047 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
06-30 13:55:40.084  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.084  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:40.085  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.086  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.093  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 13:55:40.093  6956  7023 I jxcore-log: 
06-30 13:55:40.093  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:55:40.098  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 13:55:40.098  6956  7023 I jxcore-log: 
06-30 13:55:40.103  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 13:55:40.103  6956  7023 I jxcore-log: 
06-30 13:55:40.105  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 13:55:40.116  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.116  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:40.117  7111  7111 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
06-30 13:55:40.120  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 13:55:40.120  6956  7023 I jxcore-log: 
06-30 13:55:40.121  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.134  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:55:40.144  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 13:55:40.144  6956  7023 I jxcore-log: 
06-30 13:55:40.146  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 13:55:40.155  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.155  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:40.156  7111  7111 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 13:55:40.156  7669  7669 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
06-30 13:55:40.157  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
06-30 13:55:40.157  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
06-30 13:55:40.157  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
06-30 13:55:40.157  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with f4:f2:6d:22:99:3e
06-30 13:55:40.157  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 13:55:40.157  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 13:55:40.157  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=305428  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
06-30 13:55:40.157  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=305429  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
06-30 13:55:40.158  1036  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=305429
06-30 13:55:40.158  1036  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=305429
06-30 13:55:40.158  1036  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=305429
06-30 13:55:40.158  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=305429
,06-30 13:55:40.160  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-30 13:55:40.161  1036  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=305432
06-30 13:55:40.161  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=305432  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
06-30 13:55:40.163  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:55:40.163  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:55:40.164  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=305435  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
06-30 13:55:40.164  7047  7047 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:55:40.164  7047  7047 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:55:40.164  1036  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:40.164  1036  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:40.164  1036  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:40.165  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:40.165  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 13:55:40.165  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,06-30 13:55:40.165  1036  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-30 13:55:40.165  7669  7669 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 13:55:40.165  7669  7669 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-30 13:55:40.166  1036  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=305436  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
06-30 13:55:40.166  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
06-30 13:55:40.166  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 13:55:40.166  1036  7685 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 13:55:40.166  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
06-30 13:55:40.166  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-30 13:55:40.166  1036  7685 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-30 13:55:40.167  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=305438  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
06-30 13:55:40.167  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 13:55:40.167  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 13:55:40.169  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.169  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:40.173  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.174  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.174  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.174  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-30 13:55:40.174  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.174  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.174  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
06-30 13:55:40.174  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 13:55:40.174  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
06-30 13:55:40.175  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.175  1036  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=305446
06-30 13:55:40.175  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-30 13:55:40.175  1036  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=305447
06-30 13:55:40.176  1036  1538 D WifiNative-wlan0: doString: [STATUS]
06-30 13:55:40.176  1036  7685 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-30 13:55:40.176  1036  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
06-30 13:55:40.176  1036  7685 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-30 13:55:40.177  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.178  1036  1538 I WifiServiceExtension: setVHTCapabilityType  : false
06-30 13:55:40.178  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 13:55:40.179  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
06-30 13:55:40.181  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 13:55:40.184  1036  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
06-30 13:55:40.184  1036  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
06-30 13:55:40.190  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.190  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.190  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,06-30 13:55:40.191  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.191  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.191  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-30 13:55:40.195  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.195  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:40.195  1036  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
06-30 13:55:40.196  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 13:55:40.196  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-30 13:55:40.196  1036  1545 D ConnectivityService: Got NetworkAgent Messenger
06-30 13:55:40.196  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
06-30 13:55:40.196  1036  1545 D ConnectivityService: NetworkAgent connected
06-30 13:55:40.196  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-30 13:55:40.196  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-30 13:55:40.198  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.199  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.199  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:40.201  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 13:55:40.202  7047  7047 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 13:55:40.203  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-30 13:55:40.203  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:55:40.203  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:55:40.203  7047  7047 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 13:55:40.203  7047  7047 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-30 13:55:40.203  7047  7047 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 13:55:40.203  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-30 13:55:40.203  1036  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 13:55:40.203  1036  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
06-30 13:55:40.203  1036  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
06-30 13:55:40.203  1036  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
06-30 13:55:40.206  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.207  1036  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
06-30 13:55:40.208   318   894 D CommandListener: Setting iface cfg
06-30 13:55:40.211  1036  1538 E WifiStateMachine: Start Dhcp Watchdog 2
06-30 13:55:40.211  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:40.211  1036  7731 D DhcpStateMachine: StoppedState
06-30 13:55:40.211  1036  7731 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.211  1036  7731 D DhcpStateMachine: WaitBeforeStartState
06-30 13:55:40.212  1036  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=305483  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:40.212  1036  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=305483  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:40.212  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=305483  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:40.213  1036  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=305484  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:40.213  1036  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=305484  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
06-30 13:55:40.214  1036  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=305485  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,06-30 13:55:40.215  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:259332] from screen [on:0 period:-1591075017] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 13:55:40.215  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1591075017] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 13:55:40.215  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:55:40.218  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:40.220  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.221  1036  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
06-30 13:55:40.221  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.222  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.223  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.223  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.224  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:40.224  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.224  7111  7111 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-30 13:55:40.224  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.226  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.227  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.228  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
06-30 13:55:40.228  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=189,0,0
06-30 13:55:40.228  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=189,0,0
06-30 13:55:40.228  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
06-30 13:55:40.229  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
06-30 13:55:40.229  1036  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
06-30 13:55:40.229  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 0
06-30 13:55:40.229  1036  1538 D WifiNative-wlan0: SET ps 0: returned true
06-30 13:55:40.229  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
06-30 13:55:40.230  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
06-30 13:55:40.230  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
06-30 13:55:40.230  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c4c86c9 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.230  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c4c86c9 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.230  1036  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
06-30 13:55:40.230  1036  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-30 13:55:40.230  1036  7731 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.230  1036  7731 D DhcpStateMachine: DHCP Start wake lock is acquired.
06-30 13:55:40.230  1036  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-30 13:55:40.233   318   894 D CommandListener: Setting iface cfg
06-30 13:55:40.233   318   894 D CommandListener: Trying to bring up wlan0
06-30 13:55:40.234  1036  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
06-30 13:55:40.236  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 13:55:40.236  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
06-30 13:55:40.236  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.237  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.237  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.237  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.238  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
06-30 13:55:40.238  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,06-30 13:55:40.239  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
06-30 13:55:40.239  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
06-30 13:55:40.240  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
06-30 13:55:40.240  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.240  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.240  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:40.240  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
06-30 13:55:40.241  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
06-30 13:55:40.241  1036  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
06-30 13:55:40.241  1036  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
06-30 13:55:40.241  7669  7669 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
06-30 13:55:40.242  1036  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
06-30 13:55:40.242  1036  1538 D WifiNative-wlan0: doBoolean: SET ps 1
06-30 13:55:40.242  1036  1538 D WifiNative-wlan0: SET ps 1: returned true
06-30 13:55:40.243  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
06-30 13:55:40.243  1036  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
06-30 13:55:40.243  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
06-30 13:55:40.243  1036  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
06-30 13:55:40.244  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
06-30 13:55:40.244  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:40.248  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.248  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:40.248  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.248  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.248  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-30 13:55:40.249  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
06-30 13:55:40.249  1036  1545 D ConnectivityService: Adding iface wlan0 to network 101
06-30 13:55:40.253  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 13:55:40.256  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.256  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:55:40.258  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.258  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.258  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-30 13:55:40.258  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.261  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-30 13:55:40.261  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 13:55:40.261  6956  7023 I jxcore-log: 
06-30 13:55:40.263  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
06-30 13:55:40.263  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.263  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.263  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-30 13:55:40.265  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-30 13:55:40.266  1036  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
06-30 13:55:40.267  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 13:55:40.267  6956  7023 I jxcore-log: 
,06-30 13:55:40.269  1036  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-30 13:55:40.269  1036  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
06-30 13:55:40.271  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.271  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:40.271  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-30 13:55:40.273  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.273  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-30 13:55:40.273  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.275  1036  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
06-30 13:55:40.276   318   894 E Netd    : netlink response contains error (File exists)
06-30 13:55:40.276  1036  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
06-30 13:55:40.276  1036  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
06-30 13:55:40.276  1036  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
06-30 13:55:40.276  1036  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
06-30 13:55:40.277  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-30 13:55:40.277  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
06-30 13:55:40.277  1036  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
06-30 13:55:40.277  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
06-30 13:55:40.277  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.277  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:40.277  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
06-30 13:55:40.277  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:40.277  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:40.277  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 13:55:40.277  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.277  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 13:55:40.277  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
06-30 13:55:40.277  1036  1545 D ConnectivityService: currentScore = 0, newScore = 20
06-30 13:55:40.278  1036  1545 D ConnectivityService:    accepting network in place of null
06-30 13:55:40.278  1036  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.278  1036  1,538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.278  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:40.280  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.280  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,06-30 13:55:40.280  1036  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
06-30 13:55:40.280  1036  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
06-30 13:55:40.280  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 13:55:40.282  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:40.282  1036  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
06-30 13:55:40.282  1036  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
06-30 13:55:40.284  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
06-30 13:55:40.284  1036  1545 D ConnectivityService: validation of new default Network = false
06-30 13:55:40.284  1036  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
06-30 13:55:40.284  1036  1545 D DSQN    : enableDataServiceNotify 
06-30 13:55:40.284  1036  1545 D DSQN    : start dsqn bin
06-30 13:55:40.284  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:55:40.284  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-30 13:55:40.284  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.284  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.284  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:40.285  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-30 13:55:40.285  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-30 13:55:40.285  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-30 13:55:40.286   318  7736 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 13:55:40.286   318  7736 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
06-30 13:55:40.289  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
06-30 13:55:40.289  1036  1545 D ConnectivityService:  sending notification for NetworkRequest, [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.289  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:40.289  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:40.282  7737  7737 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:40.282  7737  7737 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:40.290  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 13:55:40.292  7111  7111 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-30 13:55:40.300  7737  7737 E DSQN    : DSQN ssw
06-30 13:55:40.302  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.303  6956  7023 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 13:55:40.303  6956  7023 I jxcore-log: 
,06-30 13:55:40.313  1036  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
06-30 13:55:40.314  6956  7023 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
06-30 13:55:40.315  6956  7023 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 13:55:40.315  6956  7023 I jxcore-log: 
06-30 13:55:40.316  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:40.322  1817  7741 I CheckinService: active receiver: enabled
,06-30 13:55:40.323  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 13:55:40.324  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.325  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.326  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:40.329  1817  7741 I CheckinService: Preparing to send checkin request
06-30 13:55:40.329  1817  7741 I EventLogService: Accumulating logs since 1467287477304
06-30 13:55:40.331   318  7736 D libc-netbsd: res_queryN name = clients3.google.com succeed
06-30 13:55:40.333  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.333  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:40.333  7111  7111 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-30 13:55:40.336  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.341  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:40.344  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 13:55:40.349  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.349  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:40.350  7111  7111 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,06-30 13:55:40.358  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.365   318   893 D LGDataListener: argv[0]=dsqncommand
06-30 13:55:40.365   318   893 D LGDataListener: argv[1]=wlan0
,06-30 13:55:40.365   318   893 D LGDataListener: argv[2]=1
06-30 13:55:40.365   318   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
06-30 13:55:40.365  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
06-30 13:55:40.366  1036  1116 D DSQN    : start to monitor internet connection
06-30 13:55:40.366  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:40.369  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.369  6956  7023 I jxcore-log: 
06-30 13:55:40.370  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.370  6956  7023 I jxcore-log: 
06-30 13:55:40.371  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.371  6956  7023 I jxcore-log: 
06-30 13:55:40.373  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.373  6956  7023 I jxcore-log: 
06-30 13:55:40.374  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.374  6956  7023 I jxcore-log: 
06-30 13:55:40.374  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:40.375  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.375  6956  7023 I jxcore-log: 
06-30 13:55:40.375  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.375  6956  7023 I jxcore-log: 
06-30 13:55:40.376  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.376  6956  7023 I jxcore-log: 
06-30 13:55:40.376  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.376  6956  7023 I jxcore-log: 
06-30 13:55:40.377  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.377  6956  7023 I jxcore-log: 
06-30 13:55:40.378  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.378  6956  7023 I jxcore-log: 
06-30 13:55:40.378  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.378  6956  7023 I jxcore-log: 
06-30 13:55:40.378  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.378  6956  7023 I jxcore-log: 
06-30 13:55:40.379  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:55:40.379  6956  7023 I jxcore-log: 
,06-30 13:55:40.379  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.379  6956  7023 I jxcore-log: 
06-30 13:55:40.380  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 13:55:40.380  6956  7023 I jxcore-log: 
06-30 13:55:40.381  1817  7741 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-30 13:55:40.383  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.383  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:40.385  7111  7111 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 13:55:40.389  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.393  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:40.398  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 13:55:40.401  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 11:55:40 GMT], X-Android-Received-Millis=[1467287740401], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467287740365]}
,06-30 13:55:40.401  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 13:55:40.401  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-30 13:55:40.402  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
06-30 13:55:40.402  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
06-30 13:55:40.402  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.402  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:40.402  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:40.402  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 13:55:40.402  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
06-30 13:55:40.402  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
06-30 13:55:40.402  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
06-30 13:55:40.402  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.402  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:40.402  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:40.402  7111  7111 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
06-30 13:55:40.403  1036  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.403  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-30 13:55:40.403  1036  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.403  1036  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:40.403  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 13:55:40.405  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:40.405  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
06-30 13:55:40.405  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.409  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,06-30 13:55:40.412  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:40.414  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:55:40.418  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:40.422  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,06-30 13:55:40.422  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:40.423  7111  7111 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
06-30 13:55:40.423  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 13:55:40.423  7111  7111 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
06-30 13:55:40.423  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.424  7111  7111 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
06-30 13:55:40.424  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
06-30 13:55:40.427  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
06-30 13:55:40.430  7065  7065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
06-30 13:55:40.430  7065  7065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:55:40.432  1036  7731 D DhcpStateMachine: DHCPV4 request on wlan0
06-30 13:55:40.432  1036  7731 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
06-30 13:55:40.433  1036  7731 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
06-30 13:55:40.433  7047  7047 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:55:40.422  7745  7745 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,06-30 13:55:40.422  7745  7745 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
06-30 13:55:40.440  7745  7745 I dhcpcd  : version 5.5.6 starting
06-30 13:55:40.441  7745  7745 E dhcpcd  : get_duid: m
06-30 13:55:40.441  7745  7745 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
06-30 13:55:40.441  7745  7745 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
06-30 13:55:40.441  7047  7047 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:55:40.446  7111  7111 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
06-30 13:55:40.446  7111  7111 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,06-30 13:55:40.447  7111  7111 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
06-30 13:55:40.447  7111  7111 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
06-30 13:55:40.448  7111  7111 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
06-30 13:55:40.478  7745  7745 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
06-30 13:55:40.478  7745  7745 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
06-30 13:55:40.478  7745  7745 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
06-30 13:55:40.478  7745  7745 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
06-30 13:55:40.479  7745  7745 D dhcpcd  : wlan0: sending REQUEST (xid 0xf2063548), next in 3.54 seconds
,06-30 13:55:40.481  1036  1904 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7752 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,06-30 13:55:40.491   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 236us total 10.563ms
,06-30 13:55:40.495  7745  7745 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
06-30 13:55:40.502   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 227us total 10.485ms
06-30 13:55:40.512  7752  7752 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 13:55:40.512  7752  7752 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 13:55:40.513   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.977ms
,06-30 13:55:40.515  7745  7745 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
06-30 13:55:40.515  7745  7745 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
06-30 13:55:40.515  7745  7745 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
06-30 13:55:40.515  7745  7745 D dhcpcd  : wlan0: adding default route via 192.168.1.1
06-30 13:55:40.515  7745  7745 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
06-30 13:55:40.515  7745  7745 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
06-30 13:55:40.515  7745  7745 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
06-30 13:55:40.515  7745  7745 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
06-30 13:55:40.530  7752  7752 I MultiDex: VM with version 2.1.0 has multidex support
06-30 13:55:40.530  7752  7752 I MultiDex: install
,06-30 13:55:40.530  7752  7752 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 13:55:40.542  7752  7752 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,06-30 13:55:40.545  2181  2181 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 13:55:40.553  2181  2181 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 13:55:40.553  2181  2181 D c       : Getting all permits...
,06-30 13:55:40.553  2181  2181 D a       : Opening database...
06-30 13:55:40.557  2181  2181 D a       : Opening database auth.proximity.permit_store...
,06-30 13:55:40.557  2181  2181 D a       : Closing database...
06-30 13:55:40.834  1036  7731 D DhcpStateMachine: DHCPV4 succeeded on wlan0
06-30 13:55:40.836  1036  7731 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,06-30 13:55:40.837  1036  7731 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-30 13:55:40.837  1036  7731 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
06-30 13:55:40.837  1036  7731 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
06-30 13:55:40.837  1036  7731 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-30 13:55:40.837  1036  7731 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
06-30 13:55:40.837  1036  7731 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
06-30 13:55:40.837  1036  7731 D DhcpStateMachine: RunningState
,06-30 13:55:40.970  1036  1545 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,06-30 13:55:41.043  7441  7462 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,06-30 13:55:41.077  7796  7796 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-30 13:55:41.150  7796  7796 I dex2oat : dex2oat took 72.685ms (threads: 4)
,06-30 13:55:41.169  7752  7768 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:55:41.169  7752  7768 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:55:41.169  7752  7768 I Adreno-EGL: Build Date: 12/12/14 금
06-30 13:55:41.169  7752  7768 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 13:55:41.169  7752  7768 I Adreno-EGL: Remote Branch: 
06-30 13:55:41.169  7752  7768 I Adreno-EGL: Local Patches: 
06-30 13:55:41.169  7752  7768 I Adreno-EGL: Reconstruct Branch: 
,06-30 13:55:41.335  7752  7768 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:55:41.335  7752  7768 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:55:41.335  7752  7768 I Adreno-EGL: Build Date: 12/12/14 금
06-30 13:55:41.335  7752  7768 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 13:55:41.335  7752  7768 I Adreno-EGL: Remote Branch: 
06-30 13:55:41.335  7752  7768 I Adreno-EGL: Local Patches: 
06-30 13:55:41.335  7752  7768 I Adreno-EGL: Reconstruct Branch: 
,06-30 13:55:41.483  7752  7768 D LgDataFeature: LgDataFeature() Constructor: none
,06-30 13:55:41.484  7752  7768 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 13:55:41.615  7752  7768 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:55:41.615  7752  7768 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:55:41.615  7752  7768 I Adreno-EGL: Build Date: 12/12/14 금
06-30 13:55:41.615  7752  7768 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 13:55:41.615  7752  7768 I Adreno-EGL: Remote Branch: 
06-30 13:55:41.615  7752  7768 I Adreno-EGL: Local Patches: 
06-30 13:55:41.615  7752  7768 I Adreno-EGL: Reconstruct Branch: 
,06-30 13:55:41.785   318  7815 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 13:55:41.785   318  7815 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-30 13:55:41.823   318  7815 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 13:55:41.948  1036  1776 I ActivityManager: Killing 7268:com.lge.appbox.client/u0a11 (adj 15): empty #17
,06-30 13:55:41.979  1036  1777 W libprocessgroup: failed to open /acct/uid_10011/pid_7268/cgroup.procs: No such file or directory
,06-30 13:55:42.092  1036  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,06-30 13:55:42.094  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,06-30 13:55:42.106  1036  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 13:55:42.106  1036  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 13:55:42.107  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 13:55:42.107  1036  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-30 13:55:42.108  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
06-30 13:55:42.108  1036  1545 D ConnectivityService: identical MTU - not setting
06-30 13:55:42.109  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-30 13:55:42.109  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
06-30 13:55:42.109  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:42.109  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:42.109  1036  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:42.111  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:55:42.130  1817  7741 I CheckinTask: Sending checkin request (7628 bytes)
,06-30 13:55:42.396  1817  7741 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-30 13:55:42.415  1817  7741 I CheckinService: active receiver: disabled
,06-30 13:55:42.438  2181  2181 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-30 13:55:42.458  2181  2181 I GCM     : GCM config loaded
,06-30 13:55:42.473   318  7823 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 13:55:42.476   318  7823 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,06-30 13:55:42.484  7346  7346 V SetupWizard: Connected to Gservices successfully
06-30 13:55:43.223  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=94.5, 0.0, 0.0  rx=100.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1591072009] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:43.237  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=94.5, 0.0, 0.0  rx=100.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1591071995] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:43.238  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:55:43.256  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,06-30 13:55:43.265  1036  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,06-30 13:55:43.283  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:43.301  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:55:43.326  6956  6956 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 13:55:43.331  6956  6956 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-30 13:55:43.333  6956  7023 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:55:43.333  6956  7023 I jxcore-log: 
06-30 13:55:43.339  1036  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:43.344  6512  6512 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
06-30 13:55:43.346  6512  7044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
06-30 13:55:43.358  5963  5963 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 13:55:43.381  2181  2181 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:43.405   318  7823 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,06-30 13:55:43.426  1036  1940 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,06-30 13:55:43.428  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:43.428  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:55:43.428  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 13:55:43.428  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:55:43.428  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 13:55:43.446  1036  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:55:43.467  1036  1667 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7839 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-30 13:55:43.470  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 11:55:43 GMT], X-Android-Received-Millis=[1467287743470], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467287743437]}
06-30 13:55:43.470  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 13:55:43.470  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-30 13:55:43.471  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
06-30 13:55:43.471  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
06-30 13:55:43.471  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:55:43.471  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:43.471  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 13:55:43.471  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
06-30 13:55:43.471  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
06-30 13:55:43.471  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:55:43.471  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:43.471  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:55:43.472  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 13:55:43.526  7839  7839 I AppUp4:AppBoxCP: onCreate
,06-30 13:55:43.526  7839  7839 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-30 13:55:43.534  7839  7839 I AppUp4:DB:  setFingerPrint start
06-30 13:55:43.534  7839  7839 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
06-30 13:55:43.540  7839  7839 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
06-30 13:55:43.540  7839  7839 I AppUp4:DB:  SDK version = 21
06-30 13:55:43.540  7839  7839 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 13:55:43.541  7839  7839 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,06-30 13:55:43.542  7839  7839 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-30 13:55:43.542  7839  7839 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:43.544  7839  7839 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-30 13:55:43.544  7839  7839 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
06-30 13:55:43.549  7839  7839 I AppUp4:CustModeStarterReceiver: onReceive
06-30 13:55:43.578  7839  7839 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:43.578  7839  7839 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 13:55:43.583  7839  7839 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@197f5747
,06-30 13:55:43.583  7839  7839 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 13:55:43.583  7839  7839 D AppUp4:CustFacade: isPhone : true
06-30 13:55:43.583  7839  7839 D AppUp4:CustModeStarterReceiver: begin check event
06-30 13:55:43.584  7839  7839 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-30 13:55:43.584  7839  7839 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
06-30 13:55:43.585  7839  7862 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-30 13:55:43.585  7839  7862 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-30 13:55:43.585  7839  7862 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
06-30 13:55:43.587  1036  1580 I ActivityManager: Killing 7306:com.lge.email/u0a23 (adj 15): empty #17
06-30 13:55:43.681  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:43.682  1036  1776 W libprocessgroup: failed to open /acct/uid_10023/pid_7306/cgroup.procs: No such file or directory
06-30 13:55:43.683  4818  4818 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-30 13:55:43.691  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
06-30 13:55:43.703  4818  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,06-30 13:55:43.711  3359  3359 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:43.715  3359  3359 V DownloadManager: DownloadService onCreate
06-30 13:55:43.717  4818  7865 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:55:43.718  3359  7866 I DownloadManager: in removeSpuriousFiles
,06-30 13:55:43.721  4818  7867 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:55:43.721  4818  7867 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:55:43.720  3359  7866 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
06-30 13:55:43.725  4818  7865 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
06-30 13:55:43.729  3359  7866 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f0d8058 on behalf of 3359
06-30 13:55:43.732  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
06-30 13:55:43.733  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
06-30 13:55:43.733  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
06-30 13:55:43.733  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
06-30 13:55:43.733  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
06-30 13:55:43.733  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
06-30 13:55:43.733  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
06-30 13:55:43.734  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
06-30 13:55:43.734  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
06-30 13:55:43.734  3359  7866 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
,06-30 13:55:43.738  3359  7866 I DownloadManager: in trimDatabase
06-30 13:55:43.738  3359  7866 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
06-30 13:55:43.739  3359  7866 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@174aaa96 on behalf of 3359
06-30 13:55:43.776  1036  1903 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7871 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-30 13:55:43.778  3359  3359 V DownloadManager: DownloadService onStartCommand
,06-30 13:55:43.781  3359  7868 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
06-30 13:55:43.783  3359  7868 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b064a04 on behalf of 3359
06-30 13:55:43.784  4818  7865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
06-30 13:55:43.787  4818  4818 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
06-30 13:55:43.788  4818  4818 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
06-30 13:55:43.788  4818  4818 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
06-30 13:55:43.789  3359  7868 V DownloadManager: processing inserted download 1
06-30 13:55:43.790  3359  7868 V DownloadManager: processing inserted download 4
06-30 13:55:43.791  3359  7868 V DownloadManager: processing inserted download 7
06-30 13:55:43.792  4818  4818 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
06-30 13:55:43.793  3359  7868 V DownloadManager: processing inserted download 8
06-30 13:55:43.794  3359  7868 V DownloadManager: processing inserted download 9
,06-30 13:55:43.795  3359  7868 V DownloadManager: processing inserted download 10
06-30 13:55:43.797  3359  7868 V DownloadManager: processing inserted download 11
06-30 13:55:43.801  4818  4818 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
06-30 13:55:43.805  3359  7868 V DownloadManager: processing inserted download 12
06-30 13:55:43.806  3359  7868 V DownloadManager: processing inserted download 13
06-30 13:55:43.808  3359  7868 V DownloadManager: processing inserted download 14
06-30 13:55:43.810  3359  3359 V DownloadManager: DownloadService onDestroy
,06-30 13:55:43.859  7871  7871 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:55:43.860  7871  7871 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 13:55:43.862  7871  7871 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 13:55:43.862  7871  7871 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 13:55:43.964  7871  7871 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,06-30 13:55:43.994  7871  7871 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,06-30 13:55:44.046  7871  7871 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-30 13:55:44.082  7871  7871 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:44.082  7871  7871 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 13:55:44.234  7871  7871 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,06-30 13:55:44.293  7871  7871 I HubEmail: JNI_OnLoad()
06-30 13:55:44.293  7871  7871 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:55:44.293  7871  7871 I HubEmail: registerNatives()
06-30 13:55:44.293  7871  7871 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:55:44.293  7871  7871 I HubEmail: registerNativeMethods()
06-30 13:55:44.293  7871  7871 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:55:44.293  7871  7871 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,06-30 13:55:44.296  3192  3192 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
06-30 13:55:44.297  3192  3192 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
06-30 13:55:44.298  3192  3192 I LgeMiscReceiver: networkInfo.isConnected() = true
06-30 13:55:44.298  3192  3192 D PhoneState: setPdpRejectCasuse : false
06-30 13:55:44.305  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
06-30 13:55:44.305  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
06-30 13:55:44.324  7420  7420 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:55:44
,06-30 13:55:44.324  7871  7902 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:44.328  7420  7420 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
06-30 13:55:44.328  7420  7420 D Weather.Utils: 2 : All the weather widget is gone.
06-30 13:55:44.328  7420  7420 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 13:55:44.328  7420  7420 D WeatherAncestor: connectivity changed - connection : true
06-30 13:55:44.328  7420  7420 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c85989d
06-30 13:55:44.330  7420  7420 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
06-30 13:55:44.330  7420  7420 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
06-30 13:55:44.330  7420  7420 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
06-30 13:55:44.330  7420  7420 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 13:55:44.330  7420  7420 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:55:44
06-30 13:55:44.368   318  7913 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 13:55:44.369   318  7913 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,06-30 13:55:44.477   318  7915 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 13:55:44.478   318  7915 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,06-30 13:55:44.518   318  7915 D libc-netbsd: res_queryN name = www.google.com succeed
,06-30 13:55:44.532   318  7917 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 13:55:44.533   318  7917 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
06-30 13:55:44.534   318  7917 D libc-netbsd: res_queryN name = clients3.google.com succeed
,06-30 13:55:44.607  1036  1541 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,06-30 13:55:44.696   318  7913 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,06-30 13:55:44.763  7162  7900 V FormManager: There are no updated forms. The schedule will be deleted.
,06-30 13:55:44.772  7162  7900 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
06-30 13:55:44.801  1036  1994 I ActivityManager: Killing 7087:com.lge.lifetracker/u0a37 (adj 15): empty #17
,06-30 13:55:44.837  1036  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_7087/cgroup.procs: No such file or directory
,06-30 13:55:46.273  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=62.2, 0.0, 0.0  rx=60.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1591068959] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:46.284  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=62.2, 0.0, 0.0  rx=60.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1591068948] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:46.286  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:55:46.627  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f3364c7 type 2 when 311883 com.google.android.gms} when 311883
,06-30 13:55:46.644  7111  7111 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
06-30 13:55:46.644  7111  7111 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:434
06-30 13:55:46.646   318  7928 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 13:55:46.648   318  7928 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
06-30 13:55:46.648   318  7928 D libc-netbsd: res_queryN name = mtalk.google.com succeed
06-30 13:55:46.755  1036  1958 I ActivityManager: Killing 7134:com.lge.settings.easy/1000 (adj 15): empty #17
,06-30 13:55:46.790  1036  1976 W libprocessgroup: failed to open /acct/uid_1000/pid_7134/cgroup.procs: No such file or directory
,06-30 13:55:46.984  2181  7929 D GCM     : Connected
,06-30 13:55:47.030  2181  7929 D GCM     : Message class com.google.e.a.a.q
,06-30 13:55:49.299  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591065933] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:49.310  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=40.6, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1591065922] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 13:55:49.310  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:55:50.361  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,06-30 13:55:50.406  1036  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 13:55:50.481  1036  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7930 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 13:55:50.495  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,06-30 13:55:50.503  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
06-30 13:55:50.512  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,06-30 13:55:50.520  1036  1036 D administrator: Handling package changes for user 0
,06-30 13:55:50.557  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,06-30 13:55:50.614  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
06-30 13:55:50.614  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-30 13:55:50.646  1036  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 13:55:50.650  1036  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
06-30 13:55:50.661  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,06-30 13:55:50.663  2477  2477 V GmsNetworkLocationProvi: DISABLE
06-30 13:55:50.676  1036  1903 I art     : Explicit concurrent mark sweep GC freed 90160(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.287ms total 119.716ms
,06-30 13:55:50.703  7930  7930 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 13:55:50.705  2477  2477 E GCoreFlp: Bound FusedProviderService with LocationManager
06-30 13:55:50.757  7930  7930 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:50.758  7930  7930 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 13:55:50.821  1036  1091 D LocationProviderProxy: applying state to connected service
,06-30 13:55:50.887  7930  7976 I Babel   : MmsConfig: mnc/mcc: 0/0
06-30 13:55:50.887  7930  7976 I Babel   : MmsConfig.loadMmsSettings
06-30 13:55:50.897  7930  7976 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
06-30 13:55:50.897  7930  7976 I Babel   : MmsConfig.loadFromDatabase
,06-30 13:55:50.919  7930  7976 E Babel   : canonicalizeMccMnc: invalid mccmnc 
06-30 13:55:50.919  7930  7976 I Babel   : MmsConfig.loadFromResources
06-30 13:55:50.921  7930  7976 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
06-30 13:55:50.922  7930  7976 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
06-30 13:55:50.926  7930  7930 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:50.934  7930  7974 W AudioCapabilities: Unsupported mime audio/evrc
,06-30 13:55:50.936  7930  7974 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 13:55:50.938  7930  7974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:55:50.948  7930  7974 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,06-30 13:55:50.949  7930  7974 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 13:55:50.952  7930  7974 W AudioCapabilities: Unsupported mime audio/evrc
06-30 13:55:50.964  1817  7978 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
06-30 13:55:50.964  1817  7978 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
06-30 13:55:50.965  7930  7974 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-30 13:55:50.967  7930  7974 W VideoCapabilities: Unsupported mime video/divx
06-30 13:55:50.971  7930  7974 W VideoCapabilities: Unsupported mime video/divx311
06-30 13:55:50.972  7839  7839 I AppUp4:CustModeStarterReceiver: onReceive
06-30 13:55:50.973  7930  7974 W VideoCapabilities: Unsupported mime video/divx4
06-30 13:55:50.975  1817  5244 I Icing   : updateResources: need to parse e{com.google.android.gms}
,06-30 13:55:50.978  7839  7839 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@197f5747
06-30 13:55:50.978  7839  7839 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 13:55:50.978  7839  7839 D AppUp4:CustFacade: isPhone : true
06-30 13:55:50.978  7839  7839 D AppUp4:CustModeStarterReceiver: begin check event
06-30 13:55:50.978  7839  7839 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
06-30 13:55:50.980  7930  7974 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-30 13:55:51.003  7930  7974 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
06-30 13:55:51.007  7930  7974 W AudioCapabilities: Unsupported mime audio/eac3
,06-30 13:55:51.008  7930  7974 W AudioCapabilities: Unsupported mime audio/ac3
06-30 13:55:51.009  7930  7974 W AudioCapabilities: Unsupported mime audio/g726
06-30 13:55:51.010  7930  7974 W AudioCapabilities: Unsupported mime audio/wma-voice
06-30 13:55:51.011  7930  7974 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-30 13:55:51.015  7930  7974 W AudioCapabilities: Unsupported mime audio/adpcm
06-30 13:55:51.015  1036  1976 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7981 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
06-30 13:55:51.019  1036  1903 I ActivityManager: Killing 7695:com.lge.bnr/1000 (adj 15): empty #17
06-30 13:55:51.021  7930  7974 W VideoCapabilities: Unsupported mime video/theora
,06-30 13:55:51.023  7930  7974 W VideoCapabilities: Unsupported mime video/mjpg
06-30 13:55:51.107  1036  2022 W libprocessgroup: failed to open /acct/uid_1000/pid_7695/cgroup.procs: No such file or directory
,06-30 13:55:51.145  7981  7981 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:55:51.145  7981  7981 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:55:51.146  7981  7981 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,06-30 13:55:51.147  7981  7981 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
06-30 13:55:51.148  7981  7981 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 13:55:51.224  7981  7981 I SystemConfig: BUILD Country: EU
06-30 13:55:51.224  7981  7981 I SystemConfig: BUILD Operator: OPEN
,06-30 13:55:51.273  1036  1777 I ActivityManager: Killing 7065:com.lge.sync/1000 (adj 15): empty #17
,06-30 13:55:51.420  1036  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_7065/cgroup.procs: No such file or directory
,06-30 13:55:51.509  1036  1777 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8001 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,06-30 13:55:51.515  7981  7999 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
06-30 13:55:51.516  7981  7999 I SystemConfig: existFile = false
06-30 13:55:51.516  7981  7999 I SystemConfig: canReadFile = false
06-30 13:55:51.516  7981  7999 I SystemConfig: systemFeature RCS result false
06-30 13:55:51.516  7981  7999 D SystemConfig: refreshRcsSupport() :false
,06-30 13:55:51.593  8001  8001 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:55:51.594  8001  8001 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 13:55:51.594  8001  8001 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
06-30 13:55:51.594  8001  8001 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,06-30 13:55:51.718  8001  8001 I AppConfig: Total System Memory = 2995761152
,06-30 13:55:51.736  8001  8001 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,06-30 13:55:51.827  1036  1904 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8026 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:55:51.828  1036  1904 I ActivityManager: Killing 7047:com.android.settings/1000 (adj 15): empty #17
,06-30 13:55:51.917  1036  1776 W libprocessgroup: failed to open /acct/uid_1000/pid_7047/cgroup.procs: No such file or directory
,06-30 13:55:52.167  8026  8026 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,06-30 13:55:52.266  8026  8026 D LgDataFeature: LgDataFeature() Constructor: none
06-30 13:55:52.267  8026  8026 D LgDataFeature: LgDataFeature() Constructor Done, null
,06-30 13:55:52.328  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=24.3, 0.0, 0.0  rx=22.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591062905] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:52.330  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=24.3, 0.0, 0.0  rx=22.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591062902] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 13:55:52.331  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:55:52.338  8026  8026 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,06-30 13:55:52.358  8026  8026 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-30 13:55:52.359  8026  8026 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-30 13:55:52.379  8026  8026 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 13:55:52.379  8026  8026 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
06-30 13:55:52.402  1036  1776 I ActivityManager: Killing 7871:com.lge.email/u0a23 (adj 15): empty #17
,06-30 13:55:52.435  1036  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_7871/cgroup.procs: No such file or directory
,06-30 13:55:52.441  3359  7128 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
06-30 13:55:52.443  3359  7128 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@207eda22 on behalf of 8026
06-30 13:55:52.444  5071  8080 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
06-30 13:55:52.487  1036  2032 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8081 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,06-30 13:55:52.566  8026  8026 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,06-30 13:55:52.603  8026  8026 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,06-30 13:55:52.614  8081  8081 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
06-30 13:55:52.635  8081  8081 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
06-30 13:55:52.635  8081  8081 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
06-30 13:55:52.635  8081  8081 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,06-30 13:55:52.635  8081  8081 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
06-30 13:55:52.635  8081  8081 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
06-30 13:55:52.636  8081  8081 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
06-30 13:55:52.658  1036  1052 I ActivityManager: Killing 7162:com.lge.formmanager/u0a26 (adj 15): empty #17
,06-30 13:55:52.689  1036  1940 W libprocessgroup: failed to open /acct/uid_10026/pid_7162/cgroup.procs: No such file or directory
,06-30 13:55:52.733  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-30 13:55:52.733  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:55:52.742  1036  1544 D WifiController: battery changed pluggedType: 2
06-30 13:55:52.745  1941  2120 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:55:52.745  1941  2120 D LEDHandler: Battery Level Remaining: 100%
06-30 13:55:52.745  1941  2120 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
,06-30 13:55:52.747  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
06-30 13:55:52.747  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:55:52.749  7500  7584 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:55:52.749  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:55:52.749  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:55:52.750  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:55:52.867  1036  1976 V SIM_STK : Menu title from STK is T-Mobile
,06-30 13:55:52.891  5071  8080 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 447 ms] updated apps [took 447 ms] 
,06-30 13:55:55.348  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=12.7, 0.0, 0.0  rx=11.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591059884] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:55.351  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=12.7, 0.0, 0.0  rx=11.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591059881] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:55.351  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:55:58.373  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1591056859] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:58.384  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1591056849] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:55:58.384  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:00.045  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:56:00.046  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:56:00.046  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:56:00.046  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:56:00.062  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 13:56:00.062  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,06-30 13:56:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,06-30 13:56:00.077  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:56:01.405  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1591053828] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:01.408  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1591053824] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:01.409  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:03.566  1036  1580 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,06-30 13:56:03.569  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:56:03.569  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:56:03.570  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 13:56:03.570  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:56:03.570  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 13:56:03.607  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 11:56:03 GMT], X-Android-Received-Millis=[1467287763606], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467287763574]}
06-30 13:56:03.607  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 13:56:03.607  1036  7730 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,06-30 13:56:03.611  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
,06-30 13:56:03.611  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,06-30 13:56:03.612  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-30 13:56:03.612  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:56:03.612  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 13:56:03.612  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
06-30 13:56:03.612  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
06-30 13:56:03.612  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:56:03.612  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 13:56:03.613  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:56:03.614  1603  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 13:56:04.438  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1591050795] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:04.441  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591050792] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:04.441  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:07.464  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591047769] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:07.477  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1591047755] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:07.477  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:08.382  1036  3432 I LocationManagerService: remove 1887ce86
,06-30 13:56:08.392  1036  3432 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,06-30 13:56:08.393  1036  3432 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:56:08.394  1036  3432 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 13:56:08.396  1036  3432 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-30 13:56:08.401  1036  3432 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-30 13:56:10.497  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1591044735] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:10.509  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1591044723] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:10.509  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:12.188  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 13:56:12.205  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{336124ae type 2 when 337456 com.google.android.gms} when 337456
,06-30 13:56:12.229   318  8124 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 13:56:12.232   318  8124 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
06-30 13:56:12.233   318  8124 D libc-netbsd: res_queryN name = mtalk.google.com succeed
06-30 13:56:12.248  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 13:56:12.279  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 13:56:12.580  2181  8125 D GCM     : Connected
,06-30 13:56:12.610  2181  8125 D GCM     : Message class com.google.e.a.a.q
,06-30 13:56:13.528  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591041704] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:13.531  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591041701] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:13.531  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:16.558  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1591038674] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:16.561  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591038671] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:16.561  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:19.584  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591035648] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:19.597  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1591035637] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:19.597  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:20.213  1036  1538 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
06-30 13:56:20.214  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,06-30 13:56:20.223  1036  1538 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,06-30 13:56:20.225  1036  1538 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
06-30 13:56:20.227  1036  1538 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
06-30 13:56:20.229  1036  1538 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
06-30 13:56:22.619  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1591032613] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:22.622  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591032610] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:22.622  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:25.647  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591029585] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:25.650  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591029582] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:25.650  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:28.678  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1591026554] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:28.681  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591026551] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:28.681  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:31.704  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591023528] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:31.716  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1591023518] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:31.717  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:34.738  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591020494] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:34.741  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591020491] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:34.742  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:37.762  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591017470] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:37.772  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1591017460] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:37.772  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:40.789  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1591014444] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:40.792  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591014441] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:40.792  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:43.816  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591011416] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:43.819  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591011413] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:43.819  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:46.842  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-36 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591008390] gl rssi=-36 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:46.852  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-36 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1591008380] gl rssi=-36 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:46.852  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:49.873  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-36 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1591005359] gl rssi=-36 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:49.888  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-36 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1591005346] gl rssi=-36 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:49.888  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:56:52.907  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1591002325] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:52.910  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1591002322] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:56:52.910  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:55.936  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590999297] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:55.939  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590999294] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:55.939  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:56:58.963  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590996269] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:58.974  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590996258] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:56:58.974  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:00.004  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 13:57:00.059  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 13:57:00.076  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:57:00.076  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:57:00.076  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:57:00.076  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:57:00.082  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:57:00.082  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:57:00.082  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:57:00.085  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:57:00.131  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 13:57:01.996  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590993236] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:01.999  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590993233] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:01.999  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:05.029  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590990204] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:05.032  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590990201] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:05.032  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:08.053  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590987179] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:08.064  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590987168] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:08.067  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:11.087  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590984146] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:11.090  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590984143] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:11.090  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:14.118  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1590981114] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:14.121  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590981111] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:14.121  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:17.144  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590978089] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:17.156  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590978076] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:17.156  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:20.177  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590975055] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:20.180  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590975052] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:20.180  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:23.208  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590972024] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:23.211  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590972021] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:23.211  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:26.232  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590969001] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:26.242  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590968998] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:26.242  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:29.264  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590965968] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:29.276  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590965956] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:29.279  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:32.298  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590962935] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:32.301  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590962932] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:32.301  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:35.323  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590959909] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:35.335  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590959898] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:35.337  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:38.354  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1590956878] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:38.359  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1590956873] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:38.359  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:41.376  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590953856] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:41.379  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590953853] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:41.380  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:44.407  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590950826] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:44.410  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590950822] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:44.410  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:47.433  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590947800] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:47.442  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590947790] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:47.442  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:50.463  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590944769] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:50.476  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590944756] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:50.478  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:57:53.498  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-36 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590941734] gl rssi=-36 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:53.501  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-36 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590941731] gl rssi=-36 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:53.501  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:56.528  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590938704] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:56.531  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590938701] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:57:56.531  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:57:59.561  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590935671] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:59.564  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590935668] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:57:59.573  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:00.042  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:58:00.042  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:58:00.042  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:58:00.043  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:58:00.057  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 13:58:00.058  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:58:00.060  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:58:00.062  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:58:02.597  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590932636] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:02.610  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590932622] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:02.610  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:05.630  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590929602] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:05.633  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590929599] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:05.633  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:08.653  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590926579] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:08.664  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590926569] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:08.664  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:11.684  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590923548] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:11.696  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590923536] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:11.697  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:14.718  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590920514] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:14.721  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590920511] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:14.721  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:17.746  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590917488] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:17.749  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590917484] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:17.749  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:20.775  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590914458] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:20.778  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590914454] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:20.779  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:23.808  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590911425] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:23.811  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590911422] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:23.811  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:26.832  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590908400] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:26.843  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590908390] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:26.843  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:29.865  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590905367] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:29.868  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590905364] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:29.868  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:32.892  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1590902340] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:32.902  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590902330] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:32.902  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:35.924  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590899308] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:35.939  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590899294] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:35.939  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:38.958  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590896274] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:38.961  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590896271] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:38.961  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:41.984  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590893248] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:41.995  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590893238] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:41.995  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:43.878  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:58:43.878  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:58:43.897  1036  1544 D WifiController: battery changed pluggedType: 2
,06-30 13:58:43.901  1941  2120 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:58:43.901  1941  2120 D LEDHandler: Battery Level Remaining: 100%
06-30 13:58:43.901  1941  2120 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
06-30 13:58:43.904  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
06-30 13:58:43.904  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:58:43.907  7500  7584 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:58:43.908  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:58:43.910  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:58:43.910  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:58:45.012  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590890220] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:45.023  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590890210] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:45.023  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:48.043  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590887189] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:48.055  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590887177] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:48.055  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:58:51.077  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590884155] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:51.080  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590884152] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:51.080  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:54.109  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590881123] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:54.112  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590881120] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:58:54.112  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:58:57.133  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590878099] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:57.145  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590878089] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:58:57.145  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:59:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 13:59:00.063  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-30 13:59:00.064  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:59:00.071  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:59:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:59:00.073  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:59:00.079  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:59:00.167  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590875065] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:00.170  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590875062] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:00.170  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:03.197  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590872036] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:03.200  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590872032] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:03.200  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:03.362  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 13:59:03.377  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{61dd24f type 2 when 508631 com.google.android.gms} when 508631
06-30 13:59:03.419  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 13:59:03.446  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 13:59:03.474  1817  1817 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 13:59:03.479  2181  2181 I ConfigService: onCreate
06-30 13:59:03.480  2181  2181 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 13:59:03.482  1817  8149 I ConfigFetchService: running network task: configservice_periodic
06-30 13:59:03.485  1817  8149 I ConfigFetchService: launchTask
06-30 13:59:03.492  2181  2181 I ConfigService: onBind returning update interface
,06-30 13:59:03.497  1817  1817 I ConfigFetchService: service connected
06-30 13:59:03.497  2181  2181 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 13:59:03.497  2181  2181 I ConfigService: onBind returning config service
06-30 13:59:03.498  1817  1817 I ConfigClient: service connected
06-30 13:59:03.564  1036  1940 V SIM_STK : Menu title from STK is T-Mobile
,06-30 13:59:03.577  1817  4559 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
06-30 13:59:03.580   318  8169 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
06-30 13:59:03.580   318  8169 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,06-30 13:59:03.616   318  8169 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 13:59:03.878  1817  4559 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-30 13:59:03.887  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
06-30 13:59:03.889  1817  1817 I ConfigFetchService: stopping self
06-30 13:59:03.927  2181  2181 I ConfigService: onDestroy
,06-30 13:59:06.228  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590869005] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:06.231  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590869002] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:06.231  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:09.256  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=8.0, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590865976] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 13:59:09.259  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=8.0, 0.0, 0.0  rx=7.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590865973] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 13:59:09.259  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:12.287  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590862946] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:12.290  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590862943] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:12.290  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:15.313  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590859920] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:15.323  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590859909] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:15.323  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:18.344  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590856888] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:18.355  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590856877] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:18.355  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:21.376  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590853857] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:21.379  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590853854] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:21.379  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:24.408  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590850824] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:24.411  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590850821] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:24.411  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:27.433  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590847800] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:27.443  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590847789] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:27.444  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:30.464  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590844768] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:30.479  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590844754] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:30.479  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:33.501  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590841731] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:33.504  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590841728] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:33.504  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:36.532  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590838700] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:36.547  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590838686] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:36.548  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:39.567  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590835665] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:39.570  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590835662] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:39.570  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:42.592  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590832640] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:42.602  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590832630] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:42.602  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:45.617  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590829615] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:45.620  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590829612] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:45.620  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:48.644  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590826588] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:48.655  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590826578] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:48.655  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:51.677  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590823555] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:51.680  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590823552] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 13:59:51.680  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 13:59:54.703  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590820529] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:54.714  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590820519] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:54.714  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 13:59:57.734  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590817499] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 13:59:57.745  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590817487] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 13:59:57.746  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:00:00.115  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:00:00.115  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:00:00.115  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:00:00.116  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:00:00.131  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:00:00.131  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:00:00.133  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:00:00.138  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:00:00.765  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590814467] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:00.769  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590814464] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:00.769  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:01.223  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 14:00:01.300  1036  1092 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8180 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-30 14:00:01.338  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 14:00:01.470  8180  8180 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-30 14:00:01.476  8180  8180 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@f7bfac8
06-30 14:00:01.477  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
06-30 14:00:01.478  1036  1903 I ActivityManager: Killing 6512:com.wsandroid.suite.lge/1000 (adj 15): empty #17
06-30 14:00:01.529  1036  2022 W libprocessgroup: failed to open /acct/uid_1000/pid_6512/cgroup.procs: No such file or directory
,06-30 14:00:03.792  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590811440] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:03.803  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590811429] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:03.803  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:00:06.825  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590808407] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:06.828  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590808404] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:06.829  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:09.856  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590805376] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:09.859  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590805373] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:09.859  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:12.886  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590802346] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:12.889  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590802343] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:12.889  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:15.917  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590799315] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:15.920  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590799312] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:15.920  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:18.946  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590796286] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:18.949  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590796283] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:18.949  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:21.971  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590793261] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:21.974  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590793258] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:21.974  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:25.002  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590790230] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:25.013  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590790219] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:25.013  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:00:28.031  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590787201] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:28.034  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590787198] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:28.034  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:31.064  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590784169] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:31.076  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590784156] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:31.076  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:00:34.095  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590781137] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:34.098  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590781134] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:34.099  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:37.126  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590778106] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:37.130  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590778103] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:37.130  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:40.156  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590775076] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:40.159  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590775073] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:40.159  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:43.181  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590772051] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:43.184  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590772048] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:43.184  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:46.211  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590769021] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:46.214  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590769018] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:46.214  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:49.241  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590765991] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:49.244  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590765988] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:49.244  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:52.271  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590762961] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:52.274  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590762958] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:52.283  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:00:55.304  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590759928] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:55.316  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590759916] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:00:55.317  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:00:58.337  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590756896] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:58.340  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590756893] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:00:58.340  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:00.115  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 14:01:00.115  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:01:00.115  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:01:00.116  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:01:00.130  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:01:00.130  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:01:00.132  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:01:00.136  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:01:01.367  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590753865] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:01.370  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590753862] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:01.370  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:04.398  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590750835] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:04.401  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590750832] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:04.401  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:07.422  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590747810] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:07.433  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590747800] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:07.433  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:01:10.454  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590744778] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:10.468  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590744764] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:10.468  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:13.487  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590741748] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:13.507  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:22] from screen [on:0 period:-1590741726] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:13.507  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:01:16.527  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590738705] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:16.530  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590738702] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:16.530  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:19.552  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590735680] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:19.562  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590735670] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:19.562  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:01:22.583  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590732650] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:22.596  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590732637] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:22.598  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:01:25.619  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590729613] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:25.622  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590729610] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:25.623  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:26.194  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 14:01:26.245  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 14:01:26.275  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 14:01:28.641  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590726591] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:28.644  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590726588] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:28.644  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:31.670  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590723562] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:31.673  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590723559] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:31.673  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:34.696  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590720536] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:34.699  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590720533] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:34.699  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:37.721  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590717512] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:37.724  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590717508] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:37.724  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:40.746  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590714486] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:40.749  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590714483] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:40.750  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:43.773  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590711459] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:43.783  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590711449] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:43.783  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:01:46.803  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590708429] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:46.816  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590708417] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:46.816  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:01:49.838  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590705394] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:49.840  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1590705392] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:49.841  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:52.865  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590702367] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:52.868  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590702364] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:52.869  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:55.895  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590699337] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:55.898  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590699334] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:55.899  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:01:58.927  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590696306] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:01:58.929  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590696303] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:01:58.930  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 14:02:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:02:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:02:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:02:00.067  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:02:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:02:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:02:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:02:01.957  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590693276] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:01.960  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590693273] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:01.960  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:04.989  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590690248] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:05.007  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:23] from screen [on:0 period:-1590690225] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:05.007  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:08.028  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590687204] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:08.031  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590687201] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:08.032  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:11.059  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590684173] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:11.062  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590684170] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:11.062  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:14.083  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590681149] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:14.094  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590681138] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:14.094  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:02:17.116  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590678117] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:17.119  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590678114] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:17.119  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:20.143  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590675090] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:20.154  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590675079] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:20.154  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:02:23.176  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590672057] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:23.179  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590672054] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:23.179  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:26.205  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590669028] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:26.208  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590669024] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:26.209  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:29.235  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590665997] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:29.239  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590665994] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:29.239  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:32.264  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590662968] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:32.275  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590662957] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:32.275  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:02:35.298  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590659935] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:35.301  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590659931] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:35.301  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:38.322  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590656910] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:38.332  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590656900] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:38.332  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:02:41.352  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590653880] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:41.364  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590653868] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:41.365  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:02:44.387  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590650845] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:44.390  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590650842] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:44.390  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:47.416  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590647816] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:47.419  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590647813] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:47.420  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:50.445  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590644787] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:50.449  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590644784] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:50.449  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:53.471  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590641761] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:53.480  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590641758] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:53.480  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:02:56.499  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590638733] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:56.503  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590638730] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:02:56.503  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:02:59.524  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590635708] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:59.535  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590635698] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:02:59.535  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:03:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:03:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:03:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:03:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:03:00.121  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:03:00.121  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:03:00.124  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:03:00.129  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:03:02.556  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590632677] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:02.568  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590632664] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:02.568  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:03:05.589  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590629643] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:05.592  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590629640] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:05.592  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:08.616  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590626617] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:08.619  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590626614] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:08.619  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:11.644  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590623588] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:11.655  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590623578] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:11.657  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:03:14.679  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590620554] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:14.682  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590620551] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:14.682  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:17.701  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590617531] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:17.704  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590617528] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:17.704  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:20.736  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590614496] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:20.739  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590614493] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:20.739  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:23.762  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590611470] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:23.772  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590611460] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:23.772  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:03:26.794  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590608438] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:26.806  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590608426] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:26.809  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:03:29.828  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590605405] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:29.830  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590605402] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:29.831  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:32.857  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590602375] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:32.860  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590602372] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:32.860  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:35.884  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590599349] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:35.895  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590599338] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:35.895  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:03:38.918  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590596314] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:38.921  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590596311] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:38.922  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:41.948  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590593285] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:41.951  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590593281] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:41.951  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:44.975  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590590257] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:44.979  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590590254] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:44.979  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:48.002  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590587230] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:48.013  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590587219] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:48.014  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:03:51.038  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590584194] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:51.041  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590584191] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:51.041  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:54.065  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590581167] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:54.068  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590581164] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:03:54.068  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:03:57.094  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590578138] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:57.104  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590578128] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:03:57.106  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:04:00.116  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:04:00.116  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:04:00.116  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:04:00.117  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:04:00.130  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1590575102] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:00.133  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590575099] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:00.134  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:00.140  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:04:00.140  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:04:00.141  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:04:00.141  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:04:03.153  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590572080] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:03.166  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590572067] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:03.166  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:04:06.188  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590569044] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:06.191  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590569041] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:06.191  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:09.214  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590566018] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:09.218  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590566014] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:09.219  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:12.246  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590562988] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:12.249  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590562984] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:12.249  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:15.276  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590559956] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:15.279  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590559953] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:15.280  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:18.307  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590556925] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:18.310  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590556922] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:18.310  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:21.338  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590553894] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:21.341  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590553891] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:21.341  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:24.362  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590550870] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:24.372  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590550860] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:24.373  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:04:27.393  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590547839] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:27.406  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590547826] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:27.406  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:04:30.427  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590544806] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:30.430  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590544802] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:30.430  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:33.457  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590541775] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:33.460  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590541772] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:33.460  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:36.487  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590538745] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:36.490  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590538742] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:36.491  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:39.517  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590535716] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:39.520  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590535713] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:39.520  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:42.546  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590532686] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:42.549  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590532683] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:42.549  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:45.577  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590529655] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:45.580  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590529652] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:45.580  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:48.608  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590526624] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:48.611  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590526621] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:48.611  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:51.633  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590523599] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:51.645  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590523588] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:51.645  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:04:54.666  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590520566] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:54.669  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590520563] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:54.669  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:04:57.695  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590517538] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:04:57.699  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1590517533] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:04:57.699  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:00.115  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 14:05:00.116  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:05:00.116  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:05:00.116  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:05:00.134  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:05:00.134  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:05:00.137  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:05:00.138  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:05:00.728  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590514504] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:00.731  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590514501] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:00.731  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:03.753  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590511479] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:03.765  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590511468] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:03.767  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:05:06.789  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590508444] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:06.792  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590508441] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:06.792  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:09.819  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590505414] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:09.822  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590505411] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:09.822  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:12.844  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590502388] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:12.848  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590502384] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:12.848  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:15.872  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590499360] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:15.882  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590499350] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:15.882  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:05:18.903  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590496330] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:18.916  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590496316] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:18.917  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:05:21.937  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590493295] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:21.940  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590493292] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:21.940  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:24.965  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590490268] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:24.969  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590490264] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:24.969  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:28.001  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590487232] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:28.004  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590487229] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:28.004  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:31.029  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1590484203] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:31.032  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590484200] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:31.032  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:34.051  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590481181] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:34.054  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590481178] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:34.054  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:37.079  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1590478153] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:37.080  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1590478152] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:37.081  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:40.101  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590475132] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:40.104  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590475128] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:40.104  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:41.068  1036  1976 I ActivityManager: Killing 7346:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,06-30 14:05:41.116  1036  1994 W libprocessgroup: failed to open /acct/uid_10046/pid_7346/cgroup.procs: No such file or directory
,06-30 14:05:43.129  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590472104] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:43.132  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590472100] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:43.132  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:46.153  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1590469079] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:46.154  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1590469078] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:46.154  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:49.174  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590466059] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:49.184  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590466048] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:49.185  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:05:52.206  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590463026] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:52.209  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590463023] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:52.209  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:05:55.234  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590459999] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:55.243  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590459989] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:05:55.244  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:05:58.267  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590456966] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:58.270  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590456963] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:05:58.270  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:00.115  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 14:06:00.116  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:06:00.116  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:06:00.116  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:06:00.129  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:06:00.130  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:06:00.132  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:06:00.134  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:06:01.299  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590453933] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:01.302  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590453930] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:01.302  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:04.322  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590450910] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:04.333  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590450899] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:04.333  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:07.356  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590447876] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:07.359  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590447873] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:07.359  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:10.383  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590444850] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:10.393  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590444839] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:10.394  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:13.413  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590441819] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:13.426  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590441807] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:13.426  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:16.448  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590438785] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:16.451  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590438782] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:16.451  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:19.474  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590435759] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:19.485  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590435747] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:19.485  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:22.505  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590432728] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:22.509  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590432724] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:22.509  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:25.533  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590429699] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:25.544  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590429689] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:25.544  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:28.567  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590426666] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:28.570  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590426662] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:28.570  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:31.598  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590423634] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:31.600  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1590423632] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:31.601  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:34.625  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590420608] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:34.628  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590420604] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:34.628  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:37.654  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590417579] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:37.665  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590417568] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:37.665  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:40.686  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590414547] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:40.689  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590414544] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:40.689  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:43.712  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590411521] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:43.722  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590411511] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:43.723  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:46.742  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590408490] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:46.754  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590408478] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:46.755  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:49.777  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590405456] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:49.788  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590405444] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:49.788  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:06:52.807  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590402425] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:52.810  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590402422] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:52.811  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:55.838  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590399394] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:55.841  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590399391] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:06:55.842  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:06:58.867  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590396366] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:58.870  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590396363] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:06:58.870  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,06-30 14:07:00.105  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:07:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:07:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:07:00.119  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:07:00.120  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:07:00.122  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:07:00.124  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:07:01.897  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590393335] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:01.900  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590393332] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:01.900  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:03.903  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 14:07:03.919  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3636155e type 2 when 989172 com.google.android.gms} when 989172
,06-30 14:07:03.971  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 14:07:03.999  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 14:07:04.027  1817  1817 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 14:07:04.032  2181  2181 I ConfigService: onCreate
06-30 14:07:04.033  2181  2181 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 14:07:04.042  2181  2181 I ConfigService: onBind returning update interface
,06-30 14:07:04.046  1817  1817 I ConfigFetchService: service connected
06-30 14:07:04.046  2181  2181 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
06-30 14:07:04.046  2181  2181 I ConfigService: onBind returning config service
06-30 14:07:04.047  1817  1817 I ConfigClient: service connected
06-30 14:07:04.049  1817  8223 I ConfigFetchService: running network task: configservice_periodic
06-30 14:07:04.051  1817  8223 I ConfigFetchService: launchTask
06-30 14:07:04.118  1036  1667 V SIM_STK : Menu title from STK is T-Mobile
,06-30 14:07:04.132  1817  6362 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,06-30 14:07:04.138   318  8240 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,06-30 14:07:04.139   318  8240 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
06-30 14:07:04.181   318  8240 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,06-30 14:07:04.395  1817  6362 W ConfigFetchTask: bad response from server: 401 Unauthorized
,06-30 14:07:04.397  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
,06-30 14:07:04.402  1817  1817 I ConfigFetchService: stopping self
06-30 14:07:04.467  2181  2181 I ConfigService: onDestroy
,06-30 14:07:04.928  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1590390304] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:04.931  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590390301] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:04.931  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:07.957  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590387275] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,06-30 14:07:07.960  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590387272] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
06-30 14:07:07.960  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:10.988  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590384245] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:10.991  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590384242] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:10.991  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:14.013  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590381220] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:14.023  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590381209] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:14.024  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:07:17.045  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590378187] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:17.049  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590378184] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:17.049  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:20.072  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590375160] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:20.083  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590375150] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:20.083  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:07:23.104  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590372128] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:23.117  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590372115] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:23.118  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:07:26.138  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590369095] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:26.141  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590369091] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:26.141  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:29.167  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590366065] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:29.170  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590366062] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:29.170  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:32.198  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590363034] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:32.201  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1590363032] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:32.201  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:35.223  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590360010] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:35.233  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590359999] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:35.233  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:07:38.254  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590356979] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:38.267  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590356965] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:38.267  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:07:41.288  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590353944] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:41.291  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590353941] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:41.291  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:44.317  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590350915] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:44.320  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590350912] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:44.320  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:47.343  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590347889] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:47.354  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590347878] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:47.354  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:07:50.376  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590344856] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:50.379  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590344853] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:50.379  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:53.404  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590341828] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:53.408  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590341824] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:53.408  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:07:56.432  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590338800] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:56.443  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590338789] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:56.443  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:07:59.463  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590335769] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:07:59.475  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590335758] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:07:59.475  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:08:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:08:00.105  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:08:00.105  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:08:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:08:00.118  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:08:00.119  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:08:00.121  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:08:00.123  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:08:02.496  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590332736] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:02.499  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590332733] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:02.499  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:05.526  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590329707] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:05.529  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590329703] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:05.529  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:08.556  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590326676] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:08.559  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590326673] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:08.559  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:11.586  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590323646] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:11.597  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590323635] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:11.598  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:08:14.618  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590320614] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:14.621  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590320611] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:14.622  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:17.648  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590317584] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:17.651  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590317581] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:17.651  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:20.670  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590314562] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:20.673  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590314559] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:20.673  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:23.701  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590311532] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:23.704  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590311528] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:23.704  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:26.725  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590308507] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:26.728  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590308504] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:26.729  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:29.756  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590305477] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:29.759  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590305473] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:29.759  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL],
,06-30 14:08:32.784  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590302448] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:32.795  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590302437] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:32.795  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:08:35.819  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590299413] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:35.822  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590299410] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:35.822  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:38.849  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590296383] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:38.852  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590296380] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:38.852  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:41.871  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590293361] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:41.874  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590293358] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:41.881  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:08:44.901  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590290331] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:44.904  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1590290329] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:44.904  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:47.931  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590287302] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:47.934  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590287299] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:47.934  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:08:50.962  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590284270] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:50.972  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590284260] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:50.972  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:08:53.994  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590281238] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:54.007  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590281225] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:08:54.007  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:08:57.029  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590278203] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:57.032  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590278200] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:08:57.032  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:00.061  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590275171] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:00.064  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590275168] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:00.064  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:09:00.105  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:09:00.105  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:09:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:09:00.114  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:09:00.114  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,06-30 14:09:00.118  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:09:00.123  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:09:03.090  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590272143] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:03.093  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590272139] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:03.093  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:06.118  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590269114] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:06.121  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590269111] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:06.121  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:09.146  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590266086] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:09.150  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590266083] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:09.150  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:12.172  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590263060] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:12.182  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590263050] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:12.182  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:09:15.202  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590260030] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:15.214  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590260019] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 14:09:15.214  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:09:18.233  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590257000] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:18.245  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590256987] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:18.245  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:09:21.266  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590253967] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:21.269  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590253963] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:21.269  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:24.297  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590250936] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:24.300  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590250932] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:24.300  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:27.328  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590247904] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:27.331  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590247901] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:27.331  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:30.351  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590244881] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:30.354  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590244878] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:30.354  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:33.383  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590241850] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:33.393  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590241839] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:33.394  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:09:36.416  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590238817] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:36.419  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590238813] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:36.419  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:39.447  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590235785] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:39.450  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590235782] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:39.450  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:42.478  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590232754] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:42.481  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590232751] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:42.481  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:45.507  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1590229725] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:45.510  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590229722] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:45.510  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:48.533  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1590226699] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:48.543  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590226689] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:48.544  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:09:51.566  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590223666] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:51.570  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590223663] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:51.570  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:54.595  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590220638] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:54.598  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590220634] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:54.598  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:09:57.624  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590217608] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:09:57.635  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590217597] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:09:57.635  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:10:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:10:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:10:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:10:00.120  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:10:00.120  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:10:00.122  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:10:00.125  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:10:00.658  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590214574] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:00.661  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590214571] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:00.661  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:03.683  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590211550] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:03.697  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1590211535] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:03.697  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:06.717  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590208515] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:06.720  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590208512] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:06.720  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:09.748  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590205484] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:09.751  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590205481] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:09.752  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:12.779  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590202454] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:12.782  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590202451] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:12.782  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:15.804  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590199429] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:15.814  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590199419] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:15.814  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:18.836  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590196397] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:18.839  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590196393] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:18.839  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:21.863  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590193369] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:21.873  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590193359] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 14:10:21.873  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:24.894  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590190338] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:24.907  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590190326] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:24.907  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:27.928  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590187304] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:27.931  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590187301] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:27.931  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:30.960  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590184273] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:30.963  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590184269] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:30.963  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:33.989  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590181244] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:33.992  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590181241] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:33.992  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:37.015  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590178217] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:37.018  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590178214] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:37.018  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:37.966  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 14:10:37.982  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c222009 type 2 when 1203227 com.android.bluetooth} when 1203227
,06-30 14:10:37.989  7500  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 14:10:37.989  7500  7596 W bt-smp  : Plain text(LSB ~ MSB) = d0 ff 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 14:10:37.990  7500  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 51 26 6c 27 4b a8 c3 57 e0 c5 a9 b0 6b 50 2b 02 
06-30 14:10:37.990  7500  7596 W bt-btm  : Stopping oneshot timer
06-30 14:10:38.016  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 14:10:38.043  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 14:10:40.043  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590175189] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:40.053  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590175179] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:40.054  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:43.072  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590172160] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:43.079  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-1590172153] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:43.079  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:46.095  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590169138] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:46.099  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1590169133] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:46.099  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:49.126  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590166106] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:49.129  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590166103] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:49.129  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:52.154  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590163078] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:52.165  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590163067] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:52.165  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:10:54.627  1036  1091 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:10:55.186  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590160046] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:55.189  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590160043] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:55.189  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:10:58.217  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590157015] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:10:58.220  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590157012] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:10:58.220  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:11:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:11:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:11:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:11:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:11:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:11:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:11:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:11:01.240  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590153992] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:01.243  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1590153990] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:01.243  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:04.269  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590150963] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:04.272  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590150960] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:04.272  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:07.296  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590147937] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:07.299  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590147933] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:07.299  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:10.327  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590144905] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:10.330  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590144902] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:10.330  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:13.357  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590141875] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:13.361  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590141871] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:13.361  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:16.383  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590138849] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:16.393  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590138839] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:16.394  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:11:19.414  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590135818] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:19.427  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1590135805] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:19.427  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:11:22.448  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590132784] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:22.451  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590132781] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:22.451  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:25.478  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590129754] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:25.481  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590129751] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:25.481  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:28.503  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590126729] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:28.514  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590126718] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:28.514  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:11:28.722  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 14:11:28.737  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3040920e type 2 when 1237891 com.google.android.gms} when 1237891
,06-30 14:11:28.777  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 14:11:28.809  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 14:11:28.843  2181  8125 D GCM     : Message class com.google.e.a.a.h
,06-30 14:11:31.536  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590123696] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:31.539  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590123693] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:31.539  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:34.564  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590120668] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:34.574  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590120658] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:34.575  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:11:37.596  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590117636] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:37.599  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590117633] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:37.600  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:40.627  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590114605] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:40.630  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590114602] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:40.631  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:43.659  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590111573] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:43.662  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590111570] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:43.662  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:46.681  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590108551] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:46.684  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590108548] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:46.684  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:11:49.712  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590105520] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:49.723  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1590105510] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:49.723  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:11:52.743  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590102490] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:52.753  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590102479] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:52.754  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:11:55.773  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590099459] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:55.785  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590099448] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:11:55.785  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:11:58.806  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590096426] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:58.810  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590096423] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:11:58.810  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:12:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:12:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:12:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:12:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:12:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:12:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:12:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:12:01.838  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590093394] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:01.841  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590093391] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:01.841  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:04.868  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590090365] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:04.871  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590090362] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:04.871  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:07.897  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590087335] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:07.900  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590087332] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:07.900  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:10.927  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590084305] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:10.930  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590084302] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:10.930  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:13.954  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590081279] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:13.965  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1590081268] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:13.965  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:12:16.987  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590078245] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:16.990  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590078242] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:16.990  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:20.017  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590075215] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:20.020  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590075212] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:20.020  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:23.046  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590072187] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:23.049  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590072183] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:23.049  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:26.076  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590069156] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:26.080  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590069153] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:26.080  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:29.103  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590066129] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:29.122  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:19] from screen [on:0 period:-1590066110] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:29.122  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:32.145  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590063087] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:32.148  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590063084] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:32.148  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:35.176  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590060056] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:35.179  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590060053] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:35.180  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:38.207  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590057026] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:38.210  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590057023] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:38.210  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:41.237  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590053996] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:41.240  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590053993] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:41.240  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:44.268  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590050964] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:44.271  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590050961] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:44.271  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:47.295  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590047937] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:47.299  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590047934] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:47.299  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:50.326  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590044907] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:50.329  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590044904] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:50.329  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:53.356  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590041877] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:53.359  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590041873] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:53.359  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:12:56.384  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590038848] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:56.396  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590038836] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:12:56.396  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:12:59.419  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590035814] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:59.422  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590035811] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:12:59.422  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:13:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:13:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:13:00.107  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:13:00.120  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:13:00.120  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:13:00.122  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:13:00.124  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:13:02.443  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590032789] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:02.456  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1590032777] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:02.456  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:05.479  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590029753] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:05.482  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590029750] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:05.483  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:08.504  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590026728] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:08.518  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1590026714] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:08.518  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:11.541  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1590023692] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:11.544  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590023688] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:11.544  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:14.569  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590020663] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:14.572  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590020660] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:14.572  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:17.594  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590017638] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:17.603  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1590017629] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:17.603  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:20.624  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590014608] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:20.628  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590014604] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:20.628  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:23.651  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1590011581] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:23.654  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1590011579] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:23.654  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:26.679  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590008553] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:26.682  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590008550] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:26.682  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:29.708  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1590005524] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:29.712  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1590005521] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:29.712  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:32.736  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1590002498] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:32.739  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1590002494] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:32.739  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:35.767  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589999466] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:35.770  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589999462] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:35.770  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:38.794  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589996439] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:38.804  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589996428] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:38.805  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:41.826  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589993406] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:41.829  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589993403] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:41.829  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:44.852  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589990380] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:44.863  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1589990370] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:44.863  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:47.884  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589987348] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:47.894  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1589987338] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:47.895  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:50.916  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589984316] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 14:13:50.919  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589984313] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:50.919  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:13:53.944  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589981288] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:13:53.955  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589981277] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:53.955  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:13:56.976  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589978257] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:56.979  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589978253] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:13:56.979  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:00.006  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589975227] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:00.009  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589975223] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:00.009  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:00.106  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:14:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:14:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:14:00.107  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:14:00.119  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:14:00.119  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:14:00.121  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:14:00.123  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:14:03.034  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589972199] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:03.046  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1589972187] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:03.046  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:14:06.069  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589969164] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:06.072  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589969161] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:06.072  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:09.097  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589966135] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:09.100  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589966132] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:09.100  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:12.124  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589963108] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:12.133  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1589963099] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:12.133  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:14:15.153  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1589960080] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:15.164  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589960069] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:15.164  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:14:18.185  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589957047] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:18.188  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589957044] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:18.188  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:21.215  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589954018] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:21.219  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589954014] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:21.219  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:24.244  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589950989] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:24.255  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1589950977] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:24.255  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:14:27.278  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589947954] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:27.281  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589947951] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:27.281  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:30.303  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589944929] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:30.314  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589944918] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:30.314  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:14:33.337  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589941895] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:33.340  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589941892] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:33.340  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:36.367  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589938865] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:36.370  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589938862] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:36.370  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:39.398  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589935834] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:39.401  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589935831] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:39.402  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:42.424  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589932809] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:42.434  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1589932799] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:42.434  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:14:45.457  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589929776] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:45.460  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589929773] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:45.460  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:48.486  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589926746] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:48.490  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589926743] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:48.490  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:51.515  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589923717] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:51.519  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589923714] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:51.519  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:54.547  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589920686] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:14:54.549  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589920683] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:54.550  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:14:57.576  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589917656] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:57.579  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589917653] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:14:57.579  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:15:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:15:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:15:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:15:00.119  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:15:00.120  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:15:00.122  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:15:00.124  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:15:00.607  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589914625] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:00.610  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589914622] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:00.610  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:01.476  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=968747044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,06-30 14:15:01.500  8180  8180 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-30 14:15:01.505  8180  8180 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@f7bfac8
06-30 14:15:01.530  2631  2631 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 14:15:01.557  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=968747044 [*alarm*], flags=0x0
,06-30 14:15:03.638  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589911594] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:03.641  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589911591] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:03.641  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:06.665  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589908567] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:06.669  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589908564] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:06.669  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:09.692  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589905540] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:09.703  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589905529] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:09.704  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:15:12.724  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589902508] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:12.735  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589902497] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:12.736  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:15:15.757  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589899475] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:15.760  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589899472] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:15.760  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:18.786  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589896446] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:18.789  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589896443] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:18.789  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:21.816  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589893416] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:21.819  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589893413] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:21.819  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:24.845  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589890387] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:24.849  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589890384] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:24.849  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:27.876  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589887356] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:27.879  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589887353] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:27.879  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:30.906  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589884326] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:30.909  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589884323] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:30.909  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:33.934  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1589881298] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:33.938  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589881294] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:33.939  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:36.966  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589878268] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:36.969  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589878264] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:36.969  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:39.996  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589875236] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:39.999  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589875233] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:39.999  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:43.022  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589872210] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:43.032  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1589872200] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
06-30 14:15:43.032  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:15:46.052  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589869180] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:46.065  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1589869167] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:46.066  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:15:49.087  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589866146] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:49.090  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589866143] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:49.090  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:52.118  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1589863114] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:52.121  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589863111] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:52.121  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:15:55.143  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589860090] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:55.153  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589860079] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:55.154  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:15:58.174  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589857059] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:15:58.184  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589857048] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:15:58.185  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:16:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:16:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:16:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:16:00.120  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:16:00.120  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:16:00.123  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:16:00.125  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:16:01.206  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589854026] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:01.209  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589854023] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:01.209  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:04.237  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589850996] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:04.240  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589850992] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:04.240  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:07.268  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589847964] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:07.271  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589847961] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:07.271  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:10.290  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589844942] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:10.293  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589844939] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:10.293  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:13.314  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589841919] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:13.324  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589841908] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:13.325  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:16.344  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589838888] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:16.356  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1589838876] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:16.356  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:19.382  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589835850] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:19.393  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589835839] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:19.393  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:22.413  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1589832820] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:22.424  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1589832808] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:22.424  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:25.446  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589829786] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:25.449  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589829783] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:25.449  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:28.472  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589826760] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:28.482  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1589826750] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:28.482  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:31.505  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589823728] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:31.516  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1589823716] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:31.516  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:34.538  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589820694] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:34.541  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589820691] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:34.541  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:37.564  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589817668] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:37.575  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589817657] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:37.575  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:16:40.596  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589814636] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:40.600  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589814633] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:40.600  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:43.626  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589811606] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:43.629  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589811603] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:43.629  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:46.655  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589808577] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:46.658  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589808574] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:46.658  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:49.681  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589805551] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:49.684  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589805548] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:49.691  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:52.710  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1589802522] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:52.713  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589802519] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:52.713  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:55.738  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589799495] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:55.741  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589799492] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:55.741  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:16:58.763  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589796469] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:16:58.774  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589796458] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:16:58.774  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:17:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:17:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:17:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:17:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:17:00.120  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:17:00.120  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:17:00.122  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:17:00.124  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 14:17:01.796  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589793437] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:01.799  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589793434] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:01.799  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:04.827  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589790406] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:04.830  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589790403] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:04.830  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:07.851  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589787381] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:07.862  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589787370] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:07.862  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:17:10.881  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589784351] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:10.884  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589784348] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:10.884  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:13.911  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589781321] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:13.914  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589781318] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:13.914  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:16.942  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1589778291] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:16.952  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1589778281] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:16.952  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:17:19.971  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589775261] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:19.972  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1589775260] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:19.972  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:22.991  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589772242] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:22.994  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589772238] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:22.994  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:26.020  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589769213] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:26.023  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589769209] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:26.023  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:29.046  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1589766186] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:29.049  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589766183] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:29.049  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:32.076  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589763156] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:32.079  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589763153] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:32.080  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:35.101  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589760131] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:35.111  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589760128] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:35.111  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:17:38.130  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589757103] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:38.133  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589757099] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:38.133  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:41.160  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589754072] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:41.163  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589754069] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:41.164  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:44.188  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589751044] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:44.191  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589751041] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:44.191  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:47.218  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589748014] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:47.222  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589748011] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:47.222  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:50.244  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589744988] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:50.255  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589744977] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:50.256  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:17:53.278  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589741954] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:53.281  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589741951] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:53.281  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:56.307  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589738926] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:56.310  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589738922] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:56.310  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:17:59.338  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589735894] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:17:59.341  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589735891] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:17:59.341  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:00.105  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:18:00.106  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:18:00.106  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 14:18:00.106  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:18:00.119  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 14:18:00.119  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:18:00.121  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:18:00.123  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:18:02.367  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589732865] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:02.371  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589732862] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:02.371  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:05.400  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589729833] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:05.403  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589729829] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:05.403  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:08.426  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589726806] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:08.429  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589726803] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:08.429  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:11.454  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589723778] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:11.465  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589723767] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:11.465  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:14.487  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589720745] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:14.490  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589720742] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:14.490  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:17.518  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589717714] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:17.521  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589717711] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:17.521  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:20.540  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589714692] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:20.552  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589714681] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:20.552  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:23.570  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1589711662] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:23.573  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-37 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589711659] gl rssi=-37 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:23.573  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:26.601  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589708632] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:26.604  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1589708628] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:26.604  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:29.628  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589705604] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:29.631  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589705601] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:29.631  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:32.654  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589702578] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:32.666  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589702567] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:32.666  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:35.686  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589699546] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:35.689  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589699543] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:35.689  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:38.712  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589696520] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:38.722  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1589696510] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:38.723  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:41.744  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589693488] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:41.755  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589693477] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:41.755  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:44.779  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589690454] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-30 14:18:44.796  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:18] from screen [on:0 period:-1589690436] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:44.796  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,06-30 14:18:47.814  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1589687419] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,TIME-OUT KILL (timeout was 1400000ms),06-30 14:18:47.825  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1589687408] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:47.825  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:50.849  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1589684383] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:50.852  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1589684380] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:50.852  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:52.920  8269  8269 D AndroidRuntime: 
06-30 14:18:52.920  8269  8269 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 14:18:52.926  8269  8269 D AndroidRuntime: CheckJNI is OFF
06-30 14:18:53.053  8269  8269 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 14:18:53.064  1036  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
06-30 14:18:53.065  1036  1092 I ActivityManager: Killing 6956:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
06-30 14:18:53.101  1036  1940 I WindowState: WIN DEATH: Window{11e1c87b u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 14:18:53.104  1036  1544 D WifiService: Client connection lost with reason: 4
06-30 14:18:53.108  1036  1940 D InputDispatcher: Window went away: Window{11e1c87b u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 14:18:53.173  1036  1092 I ActivityManager:   Force finishing activity ActivityRecord{3529b3e4 u0 com.test.thalitest/.MainActivity t12}
06-30 14:18:53.200   345   363 E GBMv2   : DFP En is all cleared set to be enabled
06-30 14:18:53.201  1036  2022 W ActivityManager: Spurious death for ProcessRecord{3cd2a42f 6956:com.test.thalitest/u0a118}, curProc for 6956: null
06-30 14:18:53.202  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
06-30 14:18:53.205  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{3529b3e4 u0 com.test.thalitest/.MainActivity t12 f}
06-30 14:18:53.206  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{3529b3e4 u0 com.test.thalitest/.MainActivity t12 f}
06-30 14:18:53.230  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
06-30 14:18:53.232  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
06-30 14:18:53.235  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
06-30 14:18:53.235  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{29908473 co.....Launcher}, taskId=11, activityType=1, bIsSplit=false
06-30 14:18:53.235  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
06-30 14:18:53.236  2033  2124 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
06-30 14:18:53.237  1941  2566 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
06-30 14:18:53.238  1941  2566 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ed59f30 co.....Launcher}, taskId=11, activityType=1, bIsSplit=false
06-30 14:18:53.243  1905  1905 D ActionManagerService: notifyUserLog: 1000003
06-30 14:18:53.243  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
06-30 14:18:53.246  3802  4971 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
06-30 14:18:53.246  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
06-30 14:18:53.250  1036  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 14:18:53.263  7500  7500 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
06-30 14:18:53.263  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
06-30 14:18:53.265  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
06-30 14:18:53.265  3802  3802 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
06-30 14:18:53.283  1036  1958 V SIM_STK : Menu title from STK is T-Mobile
06-30 14:18:53.300  5071  5071 I art     : Explicit concurrent mark sweep GC freed 8140(469KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 439us total 78.495ms
06-30 14:18:53.316  2477  2610 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 14:18:53.327  4977  4977 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 14:18:53.327  4977  4977 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-30 14:18:53.327  4977  4977 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
06-30 14:18:53.327  4977  4977 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
06-30 14:18:53.327  4977  4977 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 14:18:53.327  4977  4977 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 14:18:53.327  4977  4977 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 14:18:53.327  4977  4977 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 14:18:53.328  4977  4977 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:18:53.328  4977  4977 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 14:18:53.328  4977  4977 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 14:18:53.328  4977  4977 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 14:18:53.337  1036  1092 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
06-30 14:18:53.339  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
06-30 14:18:53.350  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
06-30 14:18:53.354  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
06-30 14:18:53.355  1603  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 14:18:53.355  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.356  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
06-30 14:18:53.358  1905  1905 D ActionManagerService: notifyUserLog: 1000004
06-30 14:18:53.358  3802  4971 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
06-30 14:18:53.358  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
06-30 14:18:53.361  3802  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
06-30 14:18:53.390  1603  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 14:18:53.390  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.396  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
06-30 14:18:53.396  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , expire_time: 0
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , display: false
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , animation: false }
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , expire_time: 0
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , display: false
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , animation: false }
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1467198142274
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , create_time: 1467198143124
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , expire_time: 0
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1467198142274&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , display: false
06-30 14:18:53.396  2033  2033 I GBoardWebViewUtils: , animation: false }
06-30 14:18:53.408  1036  1903 V SIM_STK : Menu title from STK is T-Mobile
06-30 14:18:53.408  1036  1903 V SIM_STK : Menu title from STK is T-Mobile
06-30 14:18:53.409  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
06-30 14:18:53.410  1603  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 14:18:53.410  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
06-30 14:18:53.411  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 14:18:53.411  2033  8317 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
06-30 14:18:53.413  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:18:53.413  1603  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 14:18:53.426  1603  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 14:18:53.426  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.431  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
06-30 14:18:53.431  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 14:18:53.435  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:18:53.435  1603  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 14:18:53.437  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
06-30 14:18:53.437  1869  1869 D SplitUIManager: split_name #11 / not available #0
06-30 14:18:53.438  1869  1869 D SplitUIService: removed split : 
06-30 14:18:53.448  1036  1036 I art     : Explicit concurrent mark sweep GC freed 382432(18MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 44MB/66MB, paused 1.617ms total 217.765ms
06-30 14:18:53.450  1036  1124 I art     : WaitForGcToComplete blocked for 99.097ms for cause Explicit
06-30 14:18:53.450  1603  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 14:18:53.450  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.458  1603  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 14:18:53.458  1603  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 14:18:53.458  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
06-30 14:18:53.458  1603  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
06-30 14:18:53.469  1036  1903 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
06-30 14:18:53.469  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:18:53.469  1603  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
06-30 14:18:53.471  7500  7500 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
06-30 14:18:53.482  1869  1869 D SplitUIManager: split_name #11 / not available #0
06-30 14:18:53.482  1869  1869 I SplitUIService: split app #11
06-30 14:18:53.485  1603  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 14:18:53.485  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.498  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 14:18:53.500  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
06-30 14:18:53.517  1036  1036 D administrator: Handling package changes for user 0
06-30 14:18:53.548  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
06-30 14:18:53.637  1036  1124 I art     : Explicit concurrent mark sweep GC freed 19084(1077KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.611ms total 170.924ms
06-30 14:18:53.638  1036  2022 I art     : WaitForGcToComplete blocked for 217.268ms for cause Explicit
06-30 14:18:53.722  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
06-30 14:18:53.722  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 14:18:53.722  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 14:18:53.724  1036  1576 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
06-30 14:18:53.749  8269  8269 D AndroidRuntime: Shutting down VM
06-30 14:18:53.761  1036  2022 I art     : Explicit concurrent mark sweep GC freed 4718(267KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.540ms total 122.013ms
06-30 14:18:53.762  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
06-30 14:18:53.764  1603  1603 D KeyguardModel: handleShortcutListChanged...
06-30 14:18:53.764  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
06-30 14:18:53.765  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.767  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
06-30 14:18:53.768  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
06-30 14:18:53.769  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
06-30 14:18:53.769  1603  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 14:18:53.769  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.770  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
06-30 14:18:53.771  1603  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 14:18:53.771  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.772  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:18:53.773  1603  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 14:18:53.774  1603  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 14:18:53.774  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.775  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:18:53.775  1603  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 14:18:53.778  1603  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 14:18:53.778  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.779  1603  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:18:53.779  1603  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 14:18:53.780  1603  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 14:18:53.780  1603  1654 D KeyguardModel: createShortcutInfo...
06-30 14:18:53.787  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
06-30 14:18:53.787  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.795  2033  2305 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
06-30 14:18:53.795  2033  2305 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
06-30 14:18:53.798  1603  1603 D KeyguardModel: handleShortcutListChanged...
06-30 14:18:53.799  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
06-30 14:18:53.803  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
06-30 14:18:53.803  8299  8299 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 14:18:53.803  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
06-30 14:18:53.803  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.812  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
06-30 14:18:53.813  2631  2631 D [Concierge]Service: onStartCommand(). Type : 8
06-30 14:18:53.813  2631  2631 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
06-30 14:18:53.814  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e614b2e u0 com.lge.launcher2/.Launcher t11} time:1699099
06-30 14:18:53.814  2631  2631 D [Concierge]Service: Update widget ID : 11
06-30 14:18:53.815  2033  2033 D [Concierge]WidgetView: change position of spinner
06-30 14:18:53.816  2631  2631 D [Concierge]Service: onStartCommand(). Type : 0
06-30 14:18:53.816  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1467289133816
06-30 14:18:53.831  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1051979706
06-30 14:18:53.831  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
06-30 14:18:53.832  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
06-30 14:18:53.832  8299  8299 D PluginManager: init()
06-30 14:18:53.834  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@b78cdeb
06-30 14:18:53.834  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
06-30 14:18:53.836  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
06-30 14:18:53.836  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.841  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
06-30 14:18:53.841  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
06-30 14:18:53.841  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
06-30 14:18:53.841  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1467287463027, New one : 1467289133816
06-30 14:18:53.842  2033  2033 D [Concierge]WidgetView: Unregister all receivers
06-30 14:18:53.842  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
06-30 14:18:53.842  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.844  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
06-30 14:18:53.845  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
06-30 14:18:53.846  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
06-30 14:18:53.847  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
06-30 14:18:53.848  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
06-30 14:18:53.853  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.853  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.874  1036  1538 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1589681358] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:53.875  1036  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1589681357] gl rssi=-38 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-30 14:18:53.875  1036  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
06-30 14:18:53.885  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
06-30 14:18:53.894  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
06-30 14:18:53.894  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
06-30 14:18:53.895  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
06-30 14:18:53.901  1036  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 14:18:53.907  1036  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
06-30 14:18:53.913  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
06-30 14:18:53.918  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38d2dbf7 time:1699203
06-30 14:18:54.037  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8327 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-30 14:18:54.061  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
06-30 14:18:54.099  1036  1667 I ActivityManager: Killing 7377:com.android.chrome/u0a57 (adj 15): empty #17
06-30 14:18:54.102  2033  2919 I GBoardtInterface: onReloaded()
06-30 14:18:54.103  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
06-30 14:18:54.123  8299  8299 W ExternalStrings: load override strings
06-30 14:18:54.123  8299  8299 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
06-30 14:18:54.123  8299  8299 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
06-30 14:18:54.124  8299  8299 D StatusProvider: onCreate

```
