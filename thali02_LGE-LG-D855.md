#### Test 7975101567d962b_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 12:20:00.094  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-12 12:20:00.104  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:20:00.104  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:20:00.106  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:20:00.108  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 12:20:01.957  6717  6717 D AndroidRuntime: 
08-12 12:20:01.957  6717  6717 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 12:20:01.963  6717  6717 D AndroidRuntime: CheckJNI is OFF
08-12 12:20:02.087  6717  6717 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 12:20:02.092  1035  1696 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 12:20:02.103  1939  1955 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 12:20:02.106  1035  1696 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 12:20:02.107  1035  1696 D ActivityManager: setTaskToReturnTo : TaskRecord{154bd7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 12:20:02.108  1035  1696 D ActivityManager: setTaskToReturnTo : TaskRecord{154bd7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 12:20:02.108  1035  1696 D WindowStateEx: AppWindowTokenEx init.. 
08-12 12:20:02.109   349   401 E GBMv2   : DFP En is all cleared set to be enabled
08-12 12:20:02.141  1035  1696 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6736 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 12:20:02.143  6717  6717 D AndroidRuntime: Shutting down VM
08-12 12:20:02.199  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 12:20:02.199  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{e44e4ef co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 12:20:02.202  1939  2944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 12:20:02.202  1939  2944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{10f07bfc co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 12:20:02.269  6736  6736 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 12:20:02.370  6736  6736 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 12:20:02.380  6736  6736 I LibraryLoader: Loading: webviewchromium
08-12 12:20:02.383  6736  6736 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 4839-4844)
,08-12 12:20:02.384  6736  6736 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 12:20:02.400  6736  6736 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3fc24375}
08-12 12:20:02.402  6736  6736 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 12:20:02.402  6736  6736 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 12:20:02.412  6736  6736 I BrowserStartupController: Initializing chromium process, renderers=0
08-12 12:20:02.413  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 12:20:02.422  6736  6736 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 12:20:02.423  6736  6736 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 12:20:02.423  6736  6736 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 12:20:02.424   325  2189 V AudioPolicyService: registerClient() client 0xb558a8e0, uid 10118
08-12 12:20:02.434  6736  6736 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 12:20:02.434  6736  6736 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 12:20:02.434  6736  6736 I Adreno-EGL: Build Date: 12/12/14 금
08-12 12:20:02.434  6736  6736 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 12:20:02.434  6736  6736 I Adreno-EGL: Remote Branch: 
08-12 12:20:02.434  6736  6736 I Adreno-EGL: Local Patches: 
08-12 12:20:02.434  6736  6736 I Adreno-EGL: Reconstruct Branch: 
,08-12 12:20:02.460  1035  1100 D BluetoothManagerService: Message: 20
08-12 12:20:02.460  1035  1100 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@355ff1a9:true
,08-12 12:20:02.520  6736  6767 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 12:20:02.524  6736  6736 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 12:20:02.539  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 12:20:02.543  6736  6736 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 12:20:02.546  6736  6736 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 12:20:02.549  6736  6736 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 12:20:02.549  6736  6736 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 12:20:02.563  6736  6736 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 12:20:02.570  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 12:20:02.570  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 12:20:02.598  6736  6779 D OpenGLRenderer: Render dirty regions requested: true
08-12 12:20:02.598  6736  6779 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 12:20:02.605  6736  6779 D OpenGLRenderer: Enabling debug mode 0
,08-12 12:20:02.618  6736  6736 D Atlas   : Validating map...
,08-12 12:20:02.623  1035  1936 D SplitWindow: check instance of lgWin Window{3f6a92db u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 12:20:02.642  6736  6777 D LgDataFeature: LgDataFeature() Constructor: none
08-12 12:20:02.642  6736  6777 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 12:20:02.747  1035  1101 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +549ms (total +637ms)
08-12 12:20:02.748  1035  1101 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{576fcc4 u0 com.test.thalitest/.MainActivity t6} time:305208
,08-12 12:20:02.753  6736  6736 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2184c4c8 time:305214
08-12 12:20:02.856  6736  6736 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 12:20:02.872  6736  6736 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 12:20:02.872  6736  6736 I chromium: 
,08-12 12:20:02.907  6736  6777 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 12:20:02.907  6736  6777 I chromium: 
,08-12 12:20:02.982  6736  6790 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-12 12:20:02.990  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 12:20:02.990  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 12:20:02.990  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 12:20:02.990  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 12:20:02.990  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 12:20:02.990  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cd3ef0c added. We now have 1 listener(s)
08-12 12:20:02.993  1035  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 12:20:02.995  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 12:20:02.996  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-12 12:20:02.997  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 12:20:02.997  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 12:20:03.001  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3544fb5b added. We now have 1 listener(s)
08-12 12:20:03.002  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 12:20:03.005  1035  1542 D WifiService: New client listening to asynchronous messages
08-12 12:20:03.008  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 12:20:03.008  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 12:20:03.009  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 12:20:03.009  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 12:20:03.009  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 12:20:03.012  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 12:20:03.012  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 12:20:03.013  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 12:20:03.020  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 12:20:03.020  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 12:20:03.020  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 12:20:03.020  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 12:20:03.023  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 12:20:03.025  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 12:20:03.026  6736  6790 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 12:20:03.050  6736  6736 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 12:20:03.421   349   403 E GBMv2   : DFP En is all cleared set to be enabled
08-12 12:20:03.422   349   403 E GBMv2   : Set value is all cleared set the max
08-12 12:20:03.422   349   403 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 12:20:03.867  6736  6793 W jxcore-log: Initializing JXcore engine
08-12 12:20:03.867  6736  6793 W jxcore-log: JXcore engine is ready
,08-12 12:20:03.898  6793  6793 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9447]" dev="sockfs" ino=9447 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 12:20:03.898  6793  6793 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 12:20:03.898  6793  6793 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9602]" dev="sockfs" ino=9602 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 12:20:03.898  6793  6793 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-12 12:20:03.898  6793  6793 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31560]" dev="sockfs" ino=31560 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 12:20:03.918  6736  6793 W jxcore-log: Starting JXcore engine
08-12 12:20:03.996  6736  6793 W jxcore-log: Platform android
08-12 12:20:03.996  6736  6793 W jxcore-log: 
08-12 12:20:03.997  6736  6793 W jxcore-log: Process ARCH arm
08-12 12:20:03.997  6736  6793 W jxcore-log: 
,08-12 12:20:04.202  6736  6793 I jxcore-log: JXcore Cordova bridge is ready!
08-12 12:20:04.202  6736  6793 I jxcore-log: 
08-12 12:20:04.203  6736  6793 W jxcore-log: JXcore engine is started
,08-12 12:20:04.218  6736  6790 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 12:20:04.222  6736  6736 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 12:20:19.839  6736  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 12:20:19.839  6736  6793 I jxcore-log: 
,08-12 12:20:19.842  6736  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 12:20:19.842  6736  6793 I jxcore-log: 
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 12:20:19.846  6736  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 12:20:19.849  6736  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 12:20:19.852  6736  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 12:20:19.852  6736  6793 I jxcore-log: 
08-12 12:20:19.853  6736  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 12:20:19.853  6736  6793 I jxcore-log: 
,08-12 12:20:20.188  6736  6793 I jxcore-log: Unit Test app is loaded
08-12 12:20:20.188  6736  6793 I jxcore-log: 
,08-12 12:20:20.196  6736  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 12:20:20.196  6736  6793 I jxcore-log: 
08-12 12:20:20.200  6736  6793 I jxcore-log: My device name is: LGE-LG-D855
08-12 12:20:20.200  6736  6793 I jxcore-log: 
08-12 12:20:20.202  6736  6793 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 12:20:20.202  6736  6793 I jxcore-log: 
,08-12 12:20:20.210  6736  6736 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 12:20:22.538  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 12:20:22.538  6736  6793 I jxcore-log: 
,08-12 12:20:23.167  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 12:20:23.167  6736  6793 I jxcore-log: 
,08-12 12:20:23.193  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 12:20:23.193  6736  6793 I jxcore-log: 
,08-12 12:20:24.515  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 12:20:24.515  6736  6793 I jxcore-log: 
,08-12 12:20:24.743  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 12:20:24.743  6736  6793 I jxcore-log: 
,08-12 12:20:24.750  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 12:20:24.750  6736  6793 I jxcore-log: 
,08-12 12:20:24.755  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 12:20:24.755  6736  6793 I jxcore-log: 
,08-12 12:20:24.771  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 12:20:24.771  6736  6793 I jxcore-log: 
,08-12 12:20:24.777  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 12:20:24.777  6736  6793 I jxcore-log: 
,08-12 12:20:25.436  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 12:20:25.436  6736  6793 I jxcore-log: 
,08-12 12:20:25.450  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 12:20:25.450  6736  6793 I jxcore-log: 
,08-12 12:20:25.460  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 12:20:25.460  6736  6793 I jxcore-log: 
,08-12 12:20:25.468  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 12:20:25.468  6736  6793 I jxcore-log: 
,08-12 12:20:25.515  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 12:20:25.515  6736  6793 I jxcore-log: 
,08-12 12:20:25.569  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 12:20:25.569  6736  6793 I jxcore-log: 
,08-12 12:20:25.577  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 12:20:25.577  6736  6793 I jxcore-log: 
,08-12 12:20:25.739  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 12:20:25.739  6736  6793 I jxcore-log: 
,08-12 12:20:25.767  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 12:20:25.767  6736  6793 I jxcore-log: 
,08-12 12:20:25.772  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 12:20:25.772  6736  6793 I jxcore-log: 
,08-12 12:20:25.777  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 12:20:25.777  6736  6793 I jxcore-log: 
08-12 12:20:25.794  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 12:20:25.794  6736  6793 I jxcore-log: 
,08-12 12:20:25.876  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 12:20:25.876  6736  6793 I jxcore-log: 
,08-12 12:20:25.889  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 12:20:25.889  6736  6793 I jxcore-log: 
,08-12 12:20:25.917  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 12:20:25.917  6736  6793 I jxcore-log: 
,08-12 12:20:25.930  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 12:20:25.930  6736  6793 I jxcore-log: 
,08-12 12:20:25.948  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 12:20:25.948  6736  6793 I jxcore-log: 
,08-12 12:20:25.982  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 12:20:25.982  6736  6793 I jxcore-log: 
,08-12 12:20:25.988  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 12:20:25.988  6736  6793 I jxcore-log: 
,08-12 12:20:26.190  6736  6793 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 12:20:26.190  6736  6793 I jxcore-log: 
,08-12 12:20:26.199  6736  6793 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-12 12:20:26.200  6736  6793 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 12:20:26.200  6736  6793 I jxcore-log: 
08-12 12:20:33.357  1035  3579 I LocationManagerService: remove 4e12561
,08-12 12:20:33.365  1035  3579 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 12:20:33.365  1035  3579 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 12:20:33.367  1035  3579 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 12:20:33.369  1035  3579 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 12:20:33.371  1035  3579 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 12:20:44.587  1035  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=956731006, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-12 12:20:44.641  2613  2613 D [Concierge]Service: onStartCommand(). Type : 9
,08-12 12:20:44.674  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=956731006 [*alarm*], flags=0x0
,08-12 12:20:45.053  1035  2031 I art     : Explicit concurrent mark sweep GC freed 29475(1432KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.485ms total 79.207ms
,08-12 12:21:00.060  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:21:00.060  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:21:00.061  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:21:00.061  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:21:00.073  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:21:00.073  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:21:00.076  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:21:00.077  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:22:00.071  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:22:00.071  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:22:00.072  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:22:00.072  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:22:00.085  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:22:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:22:00.087  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:22:00.090  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 12:23:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:23:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:23:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:23:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:23:00.082  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:23:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:23:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:23:00.086  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:24:00.071  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:24:00.071  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:24:00.072  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:24:00.072  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:24:00.084  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:24:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:24:00.087  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:24:00.089  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:25:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:25:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:25:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:25:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:25:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:25:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:25:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:25:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:25:07.022  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 12:25:07.023  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-12 12:25:07.038  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 12:25:07.038  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-12 12:25:07.041  1035  1542 D WifiController: battery changed pluggedType: 2
08-12 12:25:07.043  1939  2075 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 12:25:07.043  1939  2075 D LEDHandler: Battery Level Remaining: 100%
08-12 12:25:07.043  1939  2075 D LEDHandler: Battery Temp: 278, mChargingStatus=5, mChargingStop=false
08-12 12:25:07.044  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
08-12 12:25:07.044  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 12:25:07.046  3915  4049 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 12:25:07.047  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 12:25:07.054  6608  6608 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-12 12:26:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:26:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:26:00.071  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:26:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:26:00.082  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:26:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:26:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:26:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:26:57.701  1035  1957 I ActivityManager: Killing 5941:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-12 12:26:57.734  1035  1972 W libprocessgroup: failed to open /acct/uid_10014/pid_5941/cgroup.procs: No such file or directory
,08-12 12:27:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:27:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:27:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:27:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:27:00.082  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:27:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:27:00.084  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:27:00.086  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:28:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:28:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:28:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:28:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:28:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:28:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:28:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:28:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:29:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:29:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:29:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:29:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:29:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:29:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:29:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:29:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:30:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:30:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:30:00.071  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:30:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:30:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:30:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:30:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:30:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:30:01.605  1035  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=956731006, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-12 12:30:01.673  1035  1093 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6822 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-12 12:30:01.706  2613  2613 D [Concierge]Service: onStartCommand(). Type : 9
,08-12 12:30:01.843  6822  6822 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-12 12:30:01.848  6822  6822 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2cf560fe
08-12 12:30:01.849  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=956731006 [*alarm*], flags=0x0
08-12 12:30:01.850  1035  1956 I ActivityManager: Killing 2178:com.lge.music/u0a34 (adj 15): empty #17
08-12 12:30:01.877   325  2191 V AudioFlinger: 2178 died, releasing its sessions
08-12 12:30:01.877   325  2191 V AudioFlinger:  pid 1852 @ 0
,08-12 12:30:01.877   325  2191 V AudioFlinger:  pid 3483 @ 1
08-12 12:30:01.877   325  2191 V AudioFlinger:  pid 3483 @ 2
08-12 12:30:01.963  1035  1972 W libprocessgroup: failed to open /acct/uid_10034/pid_2178/cgroup.procs: No such file or directory
,08-12 12:30:41.193  1035  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{37c37889 type 2 when 943622 com.android.bluetooth} when 943622
,08-12 12:30:41.201  3915  4125 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-12 12:30:41.201  3915  4125 W bt-smp  : Plain text(LSB ~ MSB) = 4e 62 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-12 12:30:41.201  3915  4125 W bt-smp  : Encrypted text(LSB ~ MSB) = 8a 0a d7 70 c2 96 95 26 e9 5e 11 ce 2b 63 46 bb 
08-12 12:30:41.201  3915  4125 W bt-btm  : Stopping oneshot timer
08-12 12:31:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:31:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:31:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:31:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:31:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:31:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:31:00.086  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:31:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:31:31.041  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 12:31:31.042  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-12 12:31:31.055  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 12:31:31.055  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-12 12:31:31.057  1035  1542 D WifiController: battery changed pluggedType: 2
08-12 12:31:31.061  1939  2075 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 12:31:31.061  1939  2075 D LEDHandler: Battery Level Remaining: 100%
08-12 12:31:31.061  1939  2075 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
08-12 12:31:31.062  3915  4049 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 12:31:31.062  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
08-12 12:31:31.063  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 12:31:31.064  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 12:31:31.069  6608  6608 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-12 12:31:41.341  1035  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=956731006, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-12 12:31:41.353  1035  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{fea408e type 2 when 980109 com.google.android.gms} when 980109
,08-12 12:31:41.394  2613  2613 D [Concierge]Service: onStartCommand(). Type : 9
,08-12 12:31:41.416  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=956731006 [*alarm*], flags=0x0
,08-12 12:31:41.443  2122  6265 D GCM     : Message class com.google.e.a.a.h
,08-12 12:32:00.060  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:32:00.061  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:32:00.061  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:32:00.061  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:32:00.066  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:32:00.066  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:32:00.067  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:32:00.068  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:33:00.074  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:33:00.074  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:33:00.074  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:33:00.075  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:33:00.088  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:33:00.088  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:33:00.092  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-12 12:33:00.098  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:34:00.071  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:34:00.071  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:34:00.071  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:34:00.072  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:34:00.084  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:34:00.084  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:34:00.086  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:34:00.088  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:35:00.071  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:35:00.071  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:35:00.071  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:35:00.072  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:35:00.084  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:35:00.084  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:35:00.087  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:35:00.089  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:35:17.615  1035  1092 I UsageStatsService: User[0] Flushing usage stats to disk
,08-12 12:36:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:36:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:36:00.071  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:36:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:36:00.082  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:36:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:36:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:36:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:37:00.095  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:37:00.096  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:37:00.096  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:37:00.096  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:37:00.108  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:37:00.109  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:37:00.113  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-12 12:37:00.121  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:38:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:38:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:38:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:38:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:38:00.082  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:38:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:38:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:38:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:39:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:39:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:39:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:39:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:39:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:39:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:39:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:39:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:40:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:40:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:40:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:40:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:40:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:40:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:40:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:40:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:41:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:41:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:41:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:41:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:41:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:41:00.083  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:41:00.085  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:41:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:42:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:42:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:42:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:42:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 12:42:00.083  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 12:42:00.084  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:42:00.086  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 12:42:00.088  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 12:43:00.070  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 12:43:00.070  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 12:43:00.070  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 12:43:00.071  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
