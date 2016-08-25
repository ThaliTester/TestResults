#### Test 79763830bc83054_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 10:48:00.113  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-25 10:48:00.113  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-25 10:48:00.114  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-25 10:48:00.114  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-25 10:48:00.128  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 10:48:00.128  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-25 10:48:00.129  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-25 10:48:00.130  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-25 10:48:00.436  6763  6763 D AndroidRuntime: 
08-25 10:48:00.436  6763  6763 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 10:48:00.441  6763  6763 D AndroidRuntime: CheckJNI is OFF
08-25 10:48:00.644  6763  6763 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 10:48:00.655  1031  1811 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 10:48:00.671  1943  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 10:48:00.677  1031  1811 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 10:48:00.679  1031  1811 D ActivityManager: setTaskToReturnTo : TaskRecord{3bf32da0 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 10:48:00.679  1031  1811 D ActivityManager: setTaskToReturnTo : TaskRecord{3bf32da0 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 10:48:00.681  1031  1811 D WindowStateEx: AppWindowTokenEx init.. 
08-25 10:48:00.682   328   356 E GBMv2   : DFP En is all cleared set to be enabled
08-25 10:48:00.711  1031  1811 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6778 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 10:48:00.714  6763  6763 D AndroidRuntime: Shutting down VM
08-25 10:48:00.771  1943  3987 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 10:48:00.771  1943  3987 D SplitWindowPolicy: topRunningActivity=ActivityInfo{24d11fbe co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 10:48:00.772  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 10:48:00.772  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2faa981f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 10:48:00.842  6778  6778 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-25 10:48:00.929  6778  6778 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-25 10:48:00.938  6778  6778 I LibraryLoader: Loading: webviewchromium
08-25 10:48:00.941  6778  6778 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5820-5824)
08-25 10:48:00.941  6778  6778 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 10:48:00.957  6778  6778 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f5b721c}
,08-25 10:48:00.958  6778  6778 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 10:48:00.958  6778  6778 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 10:48:00.968  6778  6778 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 10:48:00.969  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 10:48:00.984  6778  6778 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 10:48:00.985  6778  6778 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-25 10:48:00.985  6778  6778 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-25 10:48:00.990   308  1384 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-25 10:48:00.995  1031  1095 D BluetoothManagerService: Message: 20
08-25 10:48:00.995  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba7dd2a:true
08-25 10:48:01.003  6778  6778 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:01.003  6778  6778 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:01.003  6778  6778 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:01.003  6778  6778 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:01.003  6778  6778 I Adreno-EGL: Remote Branch: 
08-25 10:48:01.003  6778  6778 I Adreno-EGL: Local Patches: 
08-25 10:48:01.003  6778  6778 I Adreno-EGL: Reconstruct Branch: 
,08-25 10:48:01.078  6778  6824 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 10:48:01.084  6778  6778 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 10:48:01.114  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 10:48:01.120  6778  6778 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 10:48:01.123  6778  6778 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-25 10:48:01.127  6778  6778 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 10:48:01.127  6778  6778 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-25 10:48:01.141  6778  6778 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 10:48:01.153  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 10:48:01.153  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 10:48:01.207  6778  6842 D OpenGLRenderer: Render dirty regions requested: true
08-25 10:48:01.207  6778  6842 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 10:48:01.215  6778  6842 D OpenGLRenderer: Enabling debug mode 0
08-25 10:48:01.223  6778  6778 D Atlas   : Validating map...
,08-25 10:48:01.228  1031  1940 D SplitWindow: check instance of lgWin Window{37dcca94 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 10:48:01.263  6778  6840 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:01.263  6778  6840 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:01.360  1031  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +590ms (total +677ms)
08-25 10:48:01.361  1031  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8315d59 u0 com.test.thalitest/.MainActivity t6} time:196244
08-25 10:48:01.363  6778  6778 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@326e0f9b time:196246
,08-25 10:48:01.475  6778  6778 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 10:48:01.475  6778  6778 I chromium: 
,08-25 10:48:01.528  6778  6778 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 10:48:01.703  6778  6853 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-25 10:48:01.724  6778  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 10:48:01.724  6778  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 10:48:01.724  6778  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 10:48:01.724  6778  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 10:48:01.724  6778  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 10:48:01.724  6778  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@278bd16f added. We now have 1 listener(s)
08-25 10:48:01.730  1031  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:01.733  6778  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-25 10:48:01.735  6778  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
08-25 10:48:01.737  6778  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:01.737  6778  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 10:48:01.746  6778  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddfbf5a added. We now have 1 listener(s)
08-25 10:48:01.747  6778  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:01.751  1031  1544 D WifiService: New client listening to asynchronous messages
,08-25 10:48:01.757  6778  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:48:01.757  6778  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 10:48:01.758  6778  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 10:48:01.758  6778  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 10:48:01.758  6778  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 10:48:01.762  6778  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:48:01.764  1031  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:01.766  6778  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 10:48:01.775  6778  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:01.776  6778  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:01.776  6778  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 10:48:01.776  6778  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:01.779  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:01.781  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:01.782  6778  6853 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 10:48:01.823  6778  6840 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 10:48:01.823  6778  6840 I chromium: 
,08-25 10:48:01.837   328   358 E GBMv2   : DFP En is all cleared set to be enabled
08-25 10:48:01.837   328   358 E GBMv2   : Set value is all cleared set the max
08-25 10:48:01.837   328   358 I GBMv2   : DFP Enabled. Ignore VFP set
,08-25 10:48:01.888  6778  6778 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 10:48:02.991  6778  6856 W jxcore-log: Initializing JXcore engine
08-25 10:48:02.991  6778  6856 W jxcore-log: JXcore engine is ready
,08-25 10:48:03.080  6856  6856 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9676]" dev="sockfs" ino=9676 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-25 10:48:03.080  6856  6856 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-25 10:48:03.080  6856  6856 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8828]" dev="sockfs" ino=8828 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 10:48:03.080  6856  6856 W Thread-782: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 10:48:03.080  6856  6856 W Thread-782: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29665]" dev="sockfs" ino=29665 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket,
08-25 10:48:03.124  6778  6856 W jxcore-log: Starting JXcore engine
,08-25 10:48:03.285  6778  6856 W jxcore-log: Platform android
08-25 10:48:03.285  6778  6856 W jxcore-log: 
08-25 10:48:03.285  6778  6856 W jxcore-log: Process ARCH arm
08-25 10:48:03.285  6778  6856 W jxcore-log: 
,08-25 10:48:03.528  6778  6856 I jxcore-log: JXcore Cordova bridge is ready!
08-25 10:48:03.528  6778  6856 I jxcore-log: 
,08-25 10:48:03.529  6778  6856 W jxcore-log: JXcore engine is started
,08-25 10:48:03.540  6778  6853 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 10:48:03.543  6778  6778 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 10:48:13.126  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 10:48:13.126  6778  6856 I jxcore-log: 
,08-25 10:48:13.129  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 10:48:13.129  6778  6856 I jxcore-log: 
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:13.134  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.136  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.138  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 10:48:13.138  6778  6856 I jxcore-log: 
08-25 10:48:13.140  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 10:48:13.140  6778  6856 I jxcore-log: 
,08-25 10:48:13.647  6778  6856 D executeNativeTests: Running unit tests
,08-25 10:48:13.727  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:13.727  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f added. We now have 2 listener(s)
08-25 10:48:13.728  1031  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 10:48:13.729  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 10:48:13.729  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:13.729  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:13.729  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:13.729  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c added. We now have 2 listener(s)
08-25 10:48:13.730  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:13.730  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:48:13.732  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:13.734  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.734  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.735  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:13.737  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.738  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.740  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 10:48:13.740  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 10:48:13.740  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 10:48:13.741  6778  6856 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
08-25 10:48:13.742  6778  6856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 10:48:13.743  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-25 10:48:13.743  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-25 10:48:13.743  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 10:48:13.743  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-25 10:48:13.744  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:48:13.744  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:48:13.745  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.745  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 10:48:13.745  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:48:13.745  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 10:48:13.745  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f removed from the list
,08-25 10:48:13.745  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:48:13.745  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c removed from the list
08-25 10:48:13.745  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.745  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.746  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.746  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.748  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.748  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 10:48:13.748  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.748  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.750  6778  6856 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 10:48:13.751  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.751  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.751  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:48:13.751  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.751  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.751  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.751  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.751  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.751  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.751  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.751  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.751  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.751  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.751  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.752  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.752  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.752  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.752  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 10:48:13.757  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 10:48:13.758  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 10:48:13.759  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-25 10:48:13.759  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.759  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.759  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.759  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.760  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:48:13.760  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.760  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.760  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.760  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.760  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.760  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.760  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.760  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:48:13.760  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.760  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.760  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.760  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.760  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.761  6778  6856 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 10:48:13.762  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:13.764  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.765  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.765  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:48:13.766  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:48:13.767  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 10:48:13.768  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:13.768  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:48:13.768  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:48:13.768  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.768  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:48:13.774  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-25 10:48:13.775  1031  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:13.779  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 10:48:13.783  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:48:13.784  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 10:48:13.785  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 10:48:13.786  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:13.787  6778  6856 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 10:48:13.787  6778  6856 I io.jxcore.node.ConnectionHelper: start: OK
08-25 10:48:13.790  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.790  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.790  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.790  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.790  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.790  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:13.790  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.790  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.790  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.790  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.790  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.791  6778  6856 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 10:48:13.792  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:13.794  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.795  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:48:13.795  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:13.796  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.796  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:13.796  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:48:13.796  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:48:13.796  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.796  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:48:13.798  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.800  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:48:13.800  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:13.801  6778  6856 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 10:48:13.801  6778  6856 I io.jxcore.node.ConnectionHelper: start: OK
08-25 10:48:13.802  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.802  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.802  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.802  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.802  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.802  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:13.802  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.802  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.803  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.803  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.803  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.803  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.803  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.804  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.804  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.805  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.805  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.805  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.805  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.806  6778  6856 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 10:48:13.808  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:13.809  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.811  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.811  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:13.812  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.813  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.813  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:13.813  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:48:13.813  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:48:13.813  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.813  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:48:13.816  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:48:13.816  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:13.817  6778  6856 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 10:48:13.818  6778  6856 I io.jxcore.node.ConnectionHelper: start: OK
08-25 10:48:13.818  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.818  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.818  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.818  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.818  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.818  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.818  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.818  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.818  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:13.818  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.818  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.819  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.819  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.819  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.819  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.819  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.820  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.820  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.820  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.820  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.820  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.820  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.820  6778  6856 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 10:48:13.821  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.821  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.821  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.821  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.821  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.821  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.821  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.821  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.821  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.821  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.821  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.821  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.821  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.821  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.822  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.822  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.822  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.822  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.822  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.822  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.823  6778  6856 D io.jxcore.node.Connec,tionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 10:48:13.823  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.823  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.823  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.823  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.823  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.823  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.824  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.824  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.824  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.824  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.824  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.824  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.824  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.824  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.824  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.824  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.825  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.825  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.825  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.825  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.825  6778  6856 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 10:48:13.825  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.825  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.825  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.826  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.826  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.826  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.826  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.826  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.826  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.826  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.826  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.826  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.826  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.826  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.827  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.827  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.827  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.827  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.827  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.827  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.828  6778  6856 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 10:48:13.828  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.828  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.828  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.828  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.828  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.828  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.828  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.828  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.828  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.828  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.828  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.828  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.828  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.828  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.830  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.830  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.831  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.831  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.831  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.831  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.831  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 10:48:13.832  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 10:48:13.832  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 10:48:13.832  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:48:13.832  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 10:48:13.832  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 10:48:13.832  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.833  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.833  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.833  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.833  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.833  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.833  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.833  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.833  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.833  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.833  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.833  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.833  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.833  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.834  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.834  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.834  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.834  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.834  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.834  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.835  6778  6856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:48:13.835  6778  6856 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 10:48:13.835  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 10:48:13.838  6778  6856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:48:13.839  6778  6856 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 10:48:13.839  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 10:48:13.840  6778  6856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 10:48:13.840  6778  6856 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:48:13.840  6778  6856 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 10:48:13.840  6778  6856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:48:13.840  6778  6856 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:48:13.840  6778  6856 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 10:48:13.840  6778  6856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:48:13.840  6778  6856 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:48:13.840  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 10:48:13.843  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 10:48:13.844  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 10:48:13.844  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 10:48:13.844  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 10:48:13.845  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 10:48:13.845  6778  6856 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 10:48:13.845  6778  6856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:48:13.845  6778  6856 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 10:48:13.845  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.845  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.845  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.845  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.845  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.845  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.846  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 10:48:13.846  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.846  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.846  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.846  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.846  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.846  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.847  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.847  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.847  6778  6862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 846)
08-25 10:48:13.848  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.848  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.848  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.848  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.848  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.848  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.849  6778  6856 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 10:48:13.849  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.849  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.849  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.849  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.849  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.849  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.849  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.849  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.849  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.849  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.849  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.849  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.849  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.849  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.850  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.850  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.850  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.850  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.850  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.850  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.851  6778  6856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 10:48:13.852  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.852  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.852  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.852  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.852  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.852  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.852  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.852  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.852  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.852  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.852  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.852  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.852  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.852  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.853  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.853  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.853  6778  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 846
08-25 10:48:13.853  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.853  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.854  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.854  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.855  6778  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 846)
08-25 10:48:13.855  6778  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 846)
08-25 10:48:13.857  6778  6856 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 10:48:13.857  6778  6856 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 10:48:13.857  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:48:13.859  6778  6856 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 10:48:13.859  6778  6856 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 10:48:13.859  6778  6856 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 10:48:13.860  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:48:13.860  6778  6856 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 10:48:13.860  6778  6856 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 10:48:13.860  6778  6856 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 10:48:13.860  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:48:13.860  6778  6856 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 10:48:13.860  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.860  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.860  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.860  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.860  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.860  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.860  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.860  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.861  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.861  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.861  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.861  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.861  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.861  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.861  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.861  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.862  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.862  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.862  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.862  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.862  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.862  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.862  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.862  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.862  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.862  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.862  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.862  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.862  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.863  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.863  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.863  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.863  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.863  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.863  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.863  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.863  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.863  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.863  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.863  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.863  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.863  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.863  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.863  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.863  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.863  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.863  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.863  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.863  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.864  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.864  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.864  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.864  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.864  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.864  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
,08-25 10:48:13.868  6778  6856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 10:48:13.868  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:13.869  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 10:48:13.870  6778  6856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 10:48:13.871  6778  6856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 10:48:13.871  6778  6778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 10:48:13.871  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 10:48:13.871  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:48:13.872  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.872  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 10:48:13.872  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 10:48:13.872  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 10:48:13.872  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.873  6778  6856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 10:48:13.873  6778  6778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 10:48:13.873  1031  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:13.873  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.873  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.873  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:48:13.873  6778  6856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:48:13.874  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:48:13.874  6778  6864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:13.874  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:48:13.877  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:13.877  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:13.877  6778  6856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:48:13.877  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.877  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.877  3891  3907 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-25 10:48:13.877  6778  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 10:48:13.878  6778  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 10:48:13.878  6778  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 10:48:13.879  6778  6856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:48:13.879  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:48:13.880  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:48:13.880  6778  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 10:48:13.880  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:48:13.880  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.880  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.880  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.880  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.880  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.880  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.880  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.880  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.880  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.880  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.880  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.880  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.880  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.880  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.880  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.881  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.881  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.881  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.881  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.882  6778  6856 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 10:48:13.882  6778  6856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 10:48:13.882  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 10:48:13.882  6778  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:48:13.882  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.883  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.883  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.883  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.883  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.883  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.883  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.883  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.883  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.883  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.883  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.883  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.883  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.883  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.884  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.884  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.884  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.884  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.885  1031  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:13.885  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:13.886  1031  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:13.886  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.886  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.886  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.886  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.886  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.886  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.886  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.886  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.886  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.886  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.886  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.886  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.886  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.886  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.887  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.887  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.887  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.887  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.888  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:13.888  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:13.888  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:13.888  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:13.888  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.888  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.888  6778  6856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3728ee7f not in the list
08-25 10:48:13.888  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.888  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.888  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:13.888  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.888  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.888  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:13.888  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:13.888  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:13.888  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:13.888  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:13.889  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a526e4c not in the list
08-25 10:48:13.889  6778  6856 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 10:48:13.889  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:48:13.890  6778  6856 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 10:48:13.890  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:48:13.890  6778  6856 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 10:48:13.890  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:48:13.892  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 10:48:13.892  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 10:48:13.892  6778  6856 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 10:48:13.892  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 10:48:13.892  6778  6856 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 10:48:13.892  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 10:48:13.892  6778  6856 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 10:48:13.893  6778  6856 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 10:48:13.893  6778  6856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 10:48:13.893  6778  6856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 10:48:13.893  6778  6856 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 10:48:13.893  6778  6856 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 10:48:13.894  6778  6856 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 10:48:13.894  6778  6856 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 10:48:13.894  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:13.894  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1438bb4d added. We now have 2 listener(s)
08-25 10:48:13.894  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:13.897  6778  6856 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 10:48:13.898  1031  2034 D WifiServiceImplEx: setWifiEnabled: true pid=6778, uid=10118, package= com.test.thalitest, App Lable : Thal,iTest
08-25 10:48:13.899  1031  2034 D WifiService: setWifiEnabled: true pid=6778, uid=10118
08-25 10:48:13.899  1031  2034 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 10:48:13.900  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:13.900  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc76602 added. We now have 3 listener(s)
08-25 10:48:13.900  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:13.905  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:13.905  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20873b13 added. We now have 4 listener(s)
08-25 10:48:13.905  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:13.907  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:13.907  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11462150 added. We now have 5 listener(s)
08-25 10:48:13.907  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:13.909  1031  2034 D WifiServiceImplEx: setWifiEnabled: false pid=6778, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 10:48:13.909  1031  2034 D WifiService: setWifiEnabled: false pid=6778, uid=10118
08-25 10:48:13.909  1031  2034 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:48:13.920  1031  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:13.920  1031  2012 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3b8c6cc7 mBinding = false
08-25 10:48:13.920  1031  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:13.920  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:13.921  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:13.921  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-25 10:48:13.921  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:13.921  1031  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-25 10:48:13.921  1031  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:13.922  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:13.922  1031  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 10:48:13.922  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:48:13.922  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 10:48:13.923  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 10:48:13.923  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 10:48:13.927  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 10:48:13.928  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 10:48:13.928  2713  2713 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 10:48:13.928  1031  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.928  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.928  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 10:48:13.928  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:13.928  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-25 10:48:13.928   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:48:13.929  1031  1095 D BluetoothManagerService: Message: 2
08-25 10:48:13.929  1031  2859 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.930  1031  1095 D BluetoothManagerService: Sending off request.
08-25 10:48:13.932  3891  3908 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 10:48:13.933  3891  3971 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 10:48:13.934  3891  3971 D BluetoothAdapterProperties: Setting state to 13
08-25 10:48:13.934  3891  3971 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 10:48:13.934  3891  3971 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 10:48:13.934  3891  3971 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 10:48:13.935  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:13.935  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:13.935  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-25 10:48:13.938  3891  3979 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:48:13.938  3891  3971 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 10:48:13.939  3891  4178 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThr,ead.run(BluetoothMapMasInstance.java:133)
08-25 10:48:13.941  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:13.941  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 10:48:13.941  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 10:48:13.941  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:48:13.958  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:13.958  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.959  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.959  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.959  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:13.961  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.962  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.963  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:13.963  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.964  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.964  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:13.965  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:13.966  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 10:48:13.966  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-25 10:48:13.980  1031  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6869 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-25 10:48:13.982  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:13.982  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:13.982  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:13.982  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:13.983  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:13.983  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:13.983  1031  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 10:48:13.983  1031  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.983  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.984  1031  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d45941a
08-25 10:48:13.984  1031  1537 D LGWifiP2pService: P2pDisablingState
08-25 10:48:13.984  1031  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.984  1031  1537 D LGWifiP2pService: p2p socket connection lost
08-25 10:48:13.984  1031  1537 D LGWifiP2pService: P2pDisabledState
08-25 10:48:13.985  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-25 10:48:13.986  1031  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.986  1031  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:13.986  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 10:48:13.986  2713  2713 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 10:48:13.986  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 10:48:13.986  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:13.988  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:13.989  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 10:48:13.990  3891  3891 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:13.991  3891  3891 D BluetoothMapService: STATE_TURNING_OFF
08-25 10:48:13.991  3891  3891 V BtOppService: Receiver DISABLED_ACTION 
08-25 10:48:13.991  3891  3891 V BluetoothMapService: Handler(): got msg=4
08-25 10:48:13.991  3891  3891 D BluetoothMapService: MAP Service closeService in
08-25 10:48:13.991  3891  3891 D BluetoothMapMasInstance: MAP Service shutdown
08-25 10:48:13.991  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 10:48:13.991  3891  3891 V BluetoothMapService: MAP Service closeService out
08-25 10:48:13.991  3891  3891 I BtOppRfcommListener: stopping Accept Thread
08-25 10:48:13.991  3891  3891 V BtOppRfcommListener: close mBtServerSocket
08-25 10:48:13.992  3891  3891 V BtOppRfcommListener: waiting for thread to terminate
08-25 10:48:13.992  3891  4224 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:13.992  3891  4224 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 10:48:13.992  3891  3891 V BtOppRfcommListener: done waiting for thread to terminate
08-25 10:48:13.994  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:13.994  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.994  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.994  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:13.995  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported,: true
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:13.995  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:13.995  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:13.995  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:48:14.001  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-25 10:48:14.018  6778  6862 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-25 10:48:14.018  6778  6862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 846)
,08-25 10:48:14.035  1031  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6885 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 10:48:14.037   333   333 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.333ms
,08-25 10:48:14.045  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-25 10:48:14.046  3891  3891 V BtOppService: onDestroy
08-25 10:48:14.048   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.989ms total 10.547ms
08-25 10:48:14.051   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:48:14.056  1031  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 10:48:14.057  1031  1545 D DSQN    : disableDataServiceNotify
08-25 10:48:14.057  1031  1545 D DSQN    : stop dsqn bin
08-25 10:48:14.058   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 9.333ms
,08-25 10:48:14.061  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.061  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.061  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:14.062  1031  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 10:48:14.062  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-25 10:48:14.062  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:14.062  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:14.062  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.062  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.062  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:14.062  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 10:48:14.062  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-25 10:48:14.062  1031  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:14.062  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 10:48:14.062  1031  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 10:48:14.063  1031  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:14.063  1031  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:14.063  1031  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:14.063  1031  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:14.063  1031  2858 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 10:48:14.064  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 10:48:14.064  3891  3891 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 10:48:14.064  1031  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 10:48:14.065  1031  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 10:48:14.065  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 10:48:14.065  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNEC,TIVITY_CHANGE
08-25 10:48:14.065  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 10:48:14.065  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:14.065  1031  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:14.066  1031  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:14.066  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 10:48:14.066  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 10:48:14.066  1943  1943 D WfdsService: WifiP2pState is changed : false
08-25 10:48:14.066  1031  1539 D WifiNative-p2p0: TERMINATE: returned true
08-25 10:48:14.066  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:14.066  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:14.066  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 10:48:14.067  1031  1545 D NetworkManagementService: Removing idletimer
08-25 10:48:14.067  1031  1539 E WifiStateMachine:  SupplicantStoppingState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:14.067  1031  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.067  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:14.067  1031  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:14.067  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:14.068  1943  2307 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 10:48:14.068  1943  2307 D WfdsService: Set the WFDS Monitor: false
08-25 10:48:14.069  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:14.069  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 10:48:14.070  1943  2307 D WfdsMonitor: WFDS Monitor is stopped
08-25 10:48:14.070  1943  2307 D WfdsService: STATE : WfdsDisabledState - enter
08-25 10:48:14.070  1943  2762 D CtrlSupplicant: Received on exit socket, terminate
08-25 10:48:14.070  1943  2762 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 10:48:14.070  1031  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 10:48:14.070  1031  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 10:48:14.070  1943  2762 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 10:48:14.070  1943  2762 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 10:48:14.070  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-25 10:48:14.071  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.071  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.071  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:14.071  1031  1031 D LocSvc_java: Sending msg: 4 arg1:,0 arg2:1
08-25 10:48:14.071  1943  2312 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-25 10:48:14.073  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 10:48:14.073  1943  2307 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 10:48:14.082  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:14.082  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:14.083  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:14.083  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:14.084  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 10:48:14.084  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:14.086  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:14.086  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:14.086  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.086  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:14.086  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:14.098  6885  6885 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:14.098  6885  6885 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 10:48:14.098  6885  6885 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 10:48:14.099  6885  6885 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 10:48:14.100  6885  6885 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 10:48:14.101  6885  6885 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 10:48:14.103  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:14.103  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 10:48:14.107  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.108  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 10:48:14.108  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:14.109  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 10:48:14.121  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 10:48:14.122  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.122  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.124  1031  1922 I art     : Explicit concurrent mark sweep GC freed 41416(1951KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.333ms total 187.051ms
08-25 10:48:14.125  1031  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 10:48:14.126  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 10:48:14.126  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 10:48:14.126  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:14.126  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 10:48:14.126  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 10:48:14.126  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-25 10:48:14.126  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 10:48:14.126  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 10:48:14.126  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 10:48:14.126  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 10:48:14.127  3891  4180 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:14.127  3891  3971 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 10:48:14.127  3891  4226 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:14.127  3891  4228 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:14.127  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 10:48:14.128  3891  4084 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 10:48:14.129  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 10:48:14.129  3891  4084 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-25 10:48:14.138  1031  2859 D DhcpStateMachine: StoppedState
08-25 10:48:14.138  1031  2859 D DhcpStateMachine: StoppedState{ when=-136ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:14.145  1031  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 10:48:14.146  1031  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-25 10:48:14.164  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 10:48:14.165  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.165  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.165  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.169  6869  6869 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 10:48:14.169  6869  6869 W LG Account v2.2: No ProfileInfo entries
08-25 10:48:14.169  6869  6869 I LG Account v2.2: isEnabled: false
08-25 10:48:14.169  6869  6869 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 10:48:14.169  6869  6869 I Feature : [Lifetracker]Country: EU
08-25 10:48:14.169  6869  6869 I Feature : [Lifetracker]Operator: OPEN
08-25 10:48:14.169  6869  6869 I Feature : [Lifetracker]Ranking support: false
08-25 10:48:14.170  6869  6869 I Feature : [Lifetracker]Comfort support: false
08-25 10:48:14.170  6869  6869 I Feature : [Lifetracker]Accessory: true
08-25 10:48:14.170  6869  6869 I Feature : [Lifetracker]Health device: true
08-25 10:48:14.170  6869  6869 I Feature : [Lifetracker]Extra Pedometer: false
08-25 10:48:14.170  6869  6869 I Feature : [Lifetracker]Blood glucose device: false
08-25 10:48:14.170  6869  6869 I Feature : [Lifetracker]Device Number: 3
08-25 10:48:14.178  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 10:48:14.188  2713  2713 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 10:48:14.188  2713  2713 I wpa_supplicant: monitor socket send errors count : 1
08-25 10:48:14.188  2713  2713 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-25 10:48:14.189  1031  2757 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-25 10:48:14.189  1031  2757 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 10:48:14.207  1031  1046 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6914 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 10:48:14.207  1031  1046 I ActivityManager: Killing 6285:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-25 10:48:14.214  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 10:48:14.226  2713  2713 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 10:48:14.226  1031  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 10:48:14.226  1031  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 10:48:14.226  1031  2757 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 10:48:14.226  2713  2713 W wpa_supplicant: USIM:  scard_deinit function
08-25 10:48:14.227  1031  2757 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 10:48:14.227  1031  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:14.227  1031  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:14.228  1031  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209098
08-25 10:48:14.228  1031  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209098
08-25 10:48:14.229  1031  1095 D Tethering: InitialState.processMessage what=4
08-25 10:48:14.229  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=209099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 10:48:14.230  1031  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=209100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 10:48:14.247  2713  2713 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 10:48:14.247  1031  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 10:48:14.247  1031  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 10:48:14.247  1031  2757 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 10:48:14.248  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-25 10:48:14.249  1031  1811 W libprocessgroup: failed to open /acct/uid_10014/pid_6285/cgroup.procs: No such file or directory
08-25 10:48:14.255  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 10:48:14.255  1031  1095 D BluetoothManagerService: Message: 20
08-25 10:48:14.255  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26b08b19:true
08-25 10:48:14.257  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 10:48:14.257  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:14.257  3891  3891 V BluetoothPbapReceiver: ***********state = 13
08-25 10:48:14.258  3891  3891 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 10:48:14.259  3891  3891 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:14.259  3891  3891 V BluetoothPbapService: state: 13
08-25 10:48:14.259  3891  3891 V BluetoothPbapService: Pbap Service closeService in
08-25 10:48:14.261  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:48:14.264  3891  3891 V BluetoothPbapService: successfully stopped pbap service
08-25 10:48:14.264  3891  3891 V BluetoothPbapService: Pbap Service closeService out
08-25 10:48:14.264  3891  3891 V BluetoothPbapService: Pbap Service onDestroy
08-25 10:48:14.264  3891  3891 V BluetoothPbapService: Pbap Service closeService in
08-25 10:48:14.264  3891  3891 V BluetoothPbapService: Pbap Service closeService out
08-25 10:48:14.264  3891  3891 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 10:48:14.269  1031  1095 D BluetoothManagerService: Message: 30
08-25 10:48:14.274  1031  1095 D BluetoothManagerService: Message: 30
,08-25 10:48:14.277  6885  6885 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 10:48:14.278  6885  6885 D BluetoothMap: Create BluetoothMap proxy object
08-25 10:48:14.279  1031  1095 D BluetoothManagerService: Message: 30
08-25 10:48:14.282  1031  1095 D BluetoothManagerService: Message: 30
08-25 10:48:14.284  6885  6885 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 10:48:14.285  6885  6885 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-25 10:48:14.298  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 10:48:14.298  6885  6885 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 10:48:14.301  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 10:48:14.304  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 10:48:14.305  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:14.306  1031  1940 I ActivityManager: Killing 6386:com.android.defcontainer/u0a4 (adj 15): empty #17
08-25 10:48:14.339  1031  1941 W libprocessgroup: failed to open /acct/uid_10004/pid_6386/cgroup.procs: No such file or directory
,08-25 10:48:14.339  6885  6885 D DockEventReceiver: finishStartingService: stopping service
08-25 10:48:14.349  1031  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 10:48:14.349  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:14.349  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:14.349  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 10:48:14.351  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:14.352  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-25 10:48:14.352  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 10:48:14.352  1943  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 10:48:14.352  1943  2307 D WfdsService: Set the WFDS Monitor: false
08-25 10:48:14.352  1943  2307 D WfdsMonitor: WFDS Monitor is stopped
08-25 10:48:14.354  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 10:48:14.354  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:14.354  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 10:48:14.354  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 10:48:14.357  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:14.357  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:14.360  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:14.360  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:14.362  6885  6885 D BluetoothInputDevice: Proxy object connected
08-25 10:48:14.362  6885  6885 D HidProfile: Bluetooth service connected
,08-25 10:48:14.364  6885  6885 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:48:14.365  6885  6885 D PanProfile: Bluetooth service connected
,08-25 10:48:14.366  6885  6885 D BluetoothMap: Proxy object connected
08-25 10:48:14.366  6885  6885 D MapProfile: Bluetooth service connected
08-25 10:48:14.367  6885  6885 D BluetoothMap: getConnectedDevices()
08-25 10:48:14.367  6885  6885 D BluetoothMap: Bluetooth is Not enabled
08-25 10:48:14.367  6885  6885 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 10:48:14.377  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:14.381  6778  6778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 10:48:14.431  6885  6885 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:14.431  6885  6885 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:14.441  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:14.443  6885  6885 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 10:48:14.449  6885  6885 D BluetoothPermissionRequest: onReceive
08-25 10:48:14.453  6885  6885 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 10:48:14.469  1031  1940 I ActivityManager: Killing 6545:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-25 10:48:14.477  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 10:48:14.509  3891  3891 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 10:48:14.510  1031  1904 W libprocessgroup: failed to open /acct/uid_10008/pid_6545/cgroup.procs: No such file or directory
,08-25 10:48:14.510  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 10:48:14.511  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 10:48:14.520  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:14.520  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 10:48:14.553  1031  1539 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:14.554  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-25 10:48:14.604  1031  1643 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6943 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 10:48:14.609  3891  3891 V BluetoothFtpService: Ftp Service onStartCommand
08-25 10:48:14.609  3891  3891 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:14.610  3891  3891 V BluetoothFtpService: Ftp Service closeService
08-25 10:48:14.610  3891  3891 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 10:48:14.611  3891  3891 V BluetoothFtpService: successfully stopped ftp service
08-25 10:48:14.612  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:14.612  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:14.612  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:14.612  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:14.613  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 10:48:14.613  3891  3891 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-25 10:48:14.614  3891  3891 V BluetoothFtpService: Ftp Service onDestroy
08-25 10:48:14.614  3891  3891 V BluetoothFtpService: Ftp Service closeService
08-25 10:48:14.615  3891  3891 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:14.615  3891  3891 V BluetoothSapService: state: 13
08-25 10:48:14.615  3891  3891 V BluetoothSapService: Stopping SAP server process
08-25 10:48:14.616  3891  3891 V BluetoothSapService: Sap Service closeSapService in
08-25 10:48:14.616  3891  3891 V BluetoothSapService: Close listen Socket : 
08-25 10:48:14.616  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
08-25 10:48:14.616  3891  3891 V BluetoothSapService: Close sapd  Socket : 
08-25 10:48:14.679  1031  1590 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6960 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 10:48:14.680  3891  3891 V BluetoothSapService: Sap Service closeSapService out
08-25 10:48:14.680  3891  3891 V BluetoothSapService: Sap Service onDestroy
08-25 10:48:14.680  3891  3891 V BluetoothSapService: Sap Service closeSapService in
08-25 10:48:14.680  3891  3891 V BluetoothSapService: Close listen Socket : 
08-25 10:48:14.680  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
08-25 10:48:14.680  3891  3891 V BluetoothSapService: Close sapd  Socket : 
,08-25 10:48:14.690  3891  3891 V BluetoothSapService: Sap Service closeSapService out
08-25 10:48:14.715  6943  6943 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 10:48:14.743  6943  6943 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 10:48:14.754  6960  6960 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 10:48:14.770  1031  1941 I ActivityManager: Killing 6042:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 10:48:14.791  6943  6943 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-25 10:48:14.792  6943  6943 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 10:48:14.792  6943  6943 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 10:48:14.792  6943  6943 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 10:48:14.793  6943  6943 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 10:48:14.795  6943  6943 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 10:48:14.801  6943  6943 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 10:48:14.820  1031  1590 W libprocessgroup: failed to open /acct/uid_10011/pid_6042/cgroup.procs: No such file or directory
,08-25 10:48:14.828  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 10:48:14.833  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:14.866  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 10:48:14.873  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:14.873  6943  6943 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 10:48:14.883  6943  6943 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-25 10:48:14.887  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 10:48:14.887  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 10:48:14.887  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:14.896  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:14.903  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:14.911  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 10:48:14.914  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:14.918  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:14.923  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 10:48:14.928  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 10:48:14.928  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 10:48:14.928  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:14.934  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:14.940  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:14.948  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:14.948  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:14.950  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 10:48:15.011  1031  1922 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6983 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 10:48:15.116  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:15.119  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:48:15.133  3891  3979 D bt_hci_bdroid: cleanup
08-25 10:48:15.134  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:15.136  3891  4163 I bt_userial_mct: exiting userial_read_thread
08-25 10:48:15.136  3891  4163 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 10:48:15.137  3891  4084 W bt-btif : ag scb idx 1 not allocated
08-25 10:48:15.137  3891  4086 I bt_lpm  : LPM is already off!!!
08-25 10:48:15.137  3891  4084 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 10:48:15.137  3891  3979 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:15.137  3891  4086 I bt_vendor: hw_epilog_process
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:48:15.137  3891  3979 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 10:48:15.137  3891  3979 D bt_userial_mct: userial_close
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:15.137  3891  3979 E bt_userial_mct: pthread_join() FAILED result:3
08-25 10:48:15.137  3891  3979 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:15.137  3891  4084 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:15.138  3891  4084 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:15.138  3891  4084 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:15.138  3891  4084 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 10:48:15.152  6983  7002 W FormManager: Network not available. Please check & try again.
,08-25 10:48:15.166  6983  7004 V FormManager: Network unavailable.
,08-25 10:48:15.173  6983  7004 V FormManager: Network unavailable.
08-25 10:48:15.174  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 10:48:15.174  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 10:48:15.174  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 10:48:15.175  6885  6885 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 10:48:15.175  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 10:48:15.185  6885  6885 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 10:48:15.185  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 10:48:15.185  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 10:48:15.185  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-25 10:48:15.185  6885  6885 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 10:48:15.186  6885  6885 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 10:48:15.192  1031  1942 I ActivityManager: Killing 6066:com.android.contacts/u0a19 (adj 15): empty #17
08-25 10:48:15.206  3891  3979 D bt_hci_bdroid: set_power 0
08-25 10:48:15.206  3891  3979 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 10:48:15.207  3891  3979 I bt_vendor: bluetooth satus is on
08-25 10:48:15.207  3891  3979 I bt_vendor: bt-vendor : resetting BT status
08-25 10:48:15.207  3891  3979 I bt_vendor: Starting hciattach daemon
08-25 10:48:15.207  3891  3979 I bt_vendor: try to set false
,08-25 10:48:15.208  3891  3979 I bt_vendor: Starting hciattach daemon
08-25 10:48:15.208  3891  3979 I bt_vendor: try to set false
08-25 10:48:15.208  3891  3979 I bt_vendor: cleanup
08-25 10:48:15.209  3891  4084 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 10:48:15.209  3891  3979 I GKI_LINUX: GKI_exit_task 0 done
08-25 10:48:15.209  3891  3979 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 10:48:15.210  3891  3971 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 10:48:15.222  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 10:48:15.222  1031  1590 W libprocessgroup: failed to open /acct/uid_10019/pid_6066/cgroup.procs: No such file or directory
08-25 10:48:15.222  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:15.224  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 10:48:15.227  3891  3891 D HeadsetService: Received stop request...Stopping profile...
08-25 10:48:15.232  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:15.233  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 10:48:15.233  3891  3891 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 10:48:15.234  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@245c4e25
08-25 10:48:15.234  3891  4010 D HeadsetStateMachine: Exit Disconnected: -1
08-25 10:48:15.235  1853  1853 D BluetoothHeadset: Proxy object disconnected
,08-25 10:48:15.236  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-25 10:48:15.236  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 10:48:15.236  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 10:48:15.236  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 10:48:15.240  3891  3891 D A2dpService: Received stop request...Stopping profile...
,08-25 10:48:15.241  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 10:48:15.241  3891  4044 D A2dpStateMachine: Exit Disconnected: -1
08-25 10:48:15.249  3891  3891 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 10:48:15.249  3891  3891 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 10:48:15.249  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@245c4e25
08-25 10:48:15.250  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-25 10:48:15.250  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-25 10:48:15.251  3891  3971 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-25 10:48:15.252  3891  3891 D HidService: Received stop request...Stopping profile...
08-25 10:48:15.252  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@245c4e25
08-25 10:48:15.252  4354  7011 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 10:48:15.253  3891  3891 D HeadsetStateMachine: Unbinding service...
08-25 10:48:15.254  6885  6885 D BluetoothInputDevice: Proxy object disconnected
08-25 10:48:15.254  6885  6885 D HidProfile: Bluetooth service disconnected
08-25 10:48:15.254  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 10:48:15.254  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 10:48:15.254  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 10:48:15.254  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 10:48:15.254  4354  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 10:48:15.254  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 10:48:15.254  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 10:48:15.254  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 10:48:15.254  4354  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 10:48:15.255  3891  3891 D HealthService: Received stop request...Stopping profile...
08-25 10:48:15.255  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@245c4e25
08-25 10:48:15.258  3891  3891 D PanService: Received stop request...Stopping profile...
08-25 10:48:15.259  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@245c4e25
08-25 10:48:15.260  6885  6885 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 10:48:15.260  6885  6885 D PanProfile: Bluetooth service disconnected
08-25 10:48:15.260  3891  3891 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 10:48:15.261  3891  3891 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 10:48:15.261  3891  3891 D BtGatt.GattService: stop()
08-25 10:48:15.261  3891  3891 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 10:48:15.262  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@245c4e25
08-25 10:48:15.262  6914  6914 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 10:48:15.262  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 10:48:15.262  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:15.266  3891  3891 I BluetoothA2dpServiceJni: cleanupNative
08-25 10:48:15.267  3891  4045 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 10:48:15.267  3891  3891 I GKI_LINUX: GKI_exit_task 2 done
08-25 10:48:15.267  3891  3891 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 10:48:15.268  3891  3891 D BluetoothMapService: Received stop request...Stopping profile...
08-25 10:48:15.268  3891  3891 D BluetoothMapService: stop()
08-25 10:48:15.270  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 10:48:15.271  3891  3891 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 10:48:15.271  3891  3891 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 10:48:15.272  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@245c4e25
08-25 10:48:15.274  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 10:48:15.274  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 10:48:15.274  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 10:48:15.274  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 10:48:15.274  3891  3891 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 10:48:15.275  6983  7015 W FormManager: Network not available. Please check & try again.
,08-25 10:48:15.275  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 10:48:15.275  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 10:48:15.277  3891  3891 V BluetoothMapService: Handler(): got msg=4
08-25 10:48:15.277  3891  3891 D BluetoothMapService: MAP Service closeService in
08-25 10:48:15.277  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 10:48:15.277  3891  3891 V BluetoothMapService: MAP Service closeService out
08-25 10:48:15.278  3891  3891 D BluetoothMapService: cleanup()
08-25 10:48:15.278  3891  3891 D BluetoothMapService: MAP Service closeService in
08-25 10:48:15.278  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 10:48:15.278  3891  3891 V BluetoothMapService: MAP Service closeService out
08-25 10:48:15.278  3891  3971 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 10:48:15.278  3891  3971 D BluetoothAdapterProperties: Setting state to 10
08-25 10:48:15.278  3891  3971 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 10:48:15.278  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:15.278  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 10:48:15.278  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 10:48:15.279  3891  3971 I BluetoothAdapterState: Entering OffState
08-25 10:48:15.279  1853  4008 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:15.280  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:15.280  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:15.281  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:15.281  6885  6901 D BluetoothMap: onBluetoothStateChange: up=false
08-25 10:48:15.286  6885  6909 D BluetoothPan: onBluetoothStateChange on: false
,08-25 10:48:15.287  1853  4008 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:15.288  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 10:48:15.288  6885  6901 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 10:48:15.290  6983  7016 V FormManager: Network unavailable.
,08-25 10:48:15.290  6885  7017 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 10:48:15.292  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 10:48:15.292  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 10:48:15.294  6983  7016 V FormManager: Network unavailable.
08-25 10:48:15.294  1031  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 10:48:15.295  1031  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 10:48:15.295  1031  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3b8c6cc7 mBinding = false
08-25 10:48:15.295  1031  1095 D BluetoothManagerService: Sending unbind request.
08-25 10:48:15.296  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 10:48:15.303  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:15.303  1943  2127 D LGBluetoothAPIService: Message: 2
08-25 10:48:15.304  1943  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@cf6676c mBinding = false
08-25 10:48:15.304  1943  2127 D LGBluetoothAPIService: Sending unbind request.
,08-25 10:48:15.307  6943  6943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 10:48:15.308  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 10:48:15.309  3891  3979 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 10:48:15.310  6885  6885 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 10:48:15.310  6885  6885 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 10:48:15.310  6885  6885 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 10:48:15.311  3891  3891 I GKI_LINUX: GKI_exit_task 1 done
08-25 10:48:15.311  3891  3891 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 10:48:15.311  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:15.312  3891  3891 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 10:48:15.312  3891  3891 I art     : --- WEIRD: removing null entry 246
08-25 10:48:15.312  3891  3891 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 10:48:15.312  3891  3891 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 10:48:15.313  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:15.313  3891  3891 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 10:48:15.315  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 10:48:15.315  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 10:48:15.315  6943  6943 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 10:48:15.316  3891  3891 I art     : System.exit called, status: 0
08-25 10:48:15.316  3891  3891 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 10:48:15.316  1603  1603 D BluetoothAdapter: 809846621: getState() :  mService = null. Returning STATE_OFF
08-25 10:48:15.316  1603  1603 D BluetoothAdapter: 809846621: getState() :  mService = null. Returning STATE_OFF
,08-25 10:48:15.327  6885  6885 D DockEventReceiver: finishStartingService: stopping service
08-25 10:48:15.337   308   308 V AudioFlinger: 3891 died, releasing its sessions
08-25 10:48:15.337   308   308 V AudioFlinger:  pid 1853 @ 0
,08-25 10:48:15.337   308   308 V AudioFlinger:  pid 3453 @ 1
08-25 10:48:15.337   308   308 V AudioFlinger:  pid 3453 @ 2
08-25 10:48:15.338  6885  6885 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-25 10:48:15.364  6943  6943 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:15.364  6943  6943 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:15.372  6943  6943 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 10:48:15.374  6943  6943 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 10:48:15.374  6943  6943 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 10:48:15.374  6943  6943 V SoundPool: doLoad: loading sample sampleID=1
08-25 10:48:15.375  6943  6943 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 10:48:15.378  6943  7023 V SoundPool: Start decode
08-25 10:48:15.379  6943  7023 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 10:48:15.380   308  1749 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 10:48:15.380   308  1749 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 10:48:15.380   308  1749 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 10:48:15.380   308  1749 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,08-25 10:48:15.380   308  1749 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 10:48:15.380   308  1749 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 10:48:15.380   308  1749 V MediaPlayerService: player type = 3
08-25 10:48:15.380   308  1749 V AwesomePlayer: AwesomePlayer create()
08-25 10:48:15.382   308  1749 V AwesomePlayer: reset_l() 
08-25 10:48:15.382   308  1749 V AwesomePlayer: cancelPlayerEvents
08-25 10:48:15.382   308  1749 V AwesomePlayer: setAudioSink() 
08-25 10:48:15.382   308  1749 V AwesomePlayer: reset_l() 
08-25 10:48:15.382   308  1749 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-25 10:48:15.382   308  1749 V AudioCache: ignored
08-25 10:48:15.382   308  1749 V AwesomePlayer: cancelPlayerEvents
08-25 10:48:15.383   308  1749 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 10:48:15.383   308  1749 V AwesomePlayer: setDataSource_l dataSource
08-25 10:48:15.383   308  1749 V LGParserOSAL: SniffLGParser start
08-25 10:48:15.383   308  1749 V LGParserOSAL: MainType:5, SubType=0
08-25 10:48:15.383   308  1749 V LGParserOSAL: #### check Mime : application/ogg
08-25 10:48:15.383   308  1749 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 10:48:15.383   308  1749 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 10:48:15.396  1031  1643 I ActivityManager: Process com.android.bluetooth (pid 3891) has died
08-25 10:48:15.397  1031  1643 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-25 10:48:15.407  6698  6698 D UEI.SmartControl: QS Service created
08-25 10:48:15.407  6943  6943 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 10:48:15.409  6943  6943 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-25 10:48:15.409  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-25 10:48:15.410  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:48:15.423  6943  6943 V LGMDMManager: Create singleton instance
,08-25 10:48:15.431  6885  6885 D BluetoothPermissionRequest: onReceive
08-25 10:48:15.434  6885  6885 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 10:48:15.434  6885  6885 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 10:48:15.437  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 10:48:15.440  6698  6698 I UEI.SmartControl: Service initServices...
08-25 10:48:15.440  6698  6698 D UEI.SmartControl: QS start get config
08-25 10:48:15.457   308  1749 V LGParserOSAL: supported mime: application/ogg
08-25 10:48:15.457   308  1749 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 10:48:15.458   308  1749 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 10:48:15.458   308  1749 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 10:48:15.458   308  1749 V AwesomePlayer: AudioTrack Setting
08-25 10:48:15.458   308  1749 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 10:48:15.458   308  1749 V AwesomePlayer: setAudioSource() 
08-25 10:48:15.458   308  1749 V MediaPlayerService: prepare
08-25 10:48:15.458   308  1749 V AwesomePlayer: prepareAsync_l() 
08-25 10:48:15.458   308  1749 V MediaPlayerService: wait for prepare
08-25 10:48:15.458   308  7024 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 10:48:15.458   308  7024 V AwesomePlayer: initAudioDecoder() 
08-25 10:48:15.458   308  7024 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 10:48:15.458   308  7024 V AudioSystem: isOffloadSupported()
08-25 10:48:15.458   308  7024 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 10:48:15.458   308  7024 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 10:48:15.458   308  7024 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 10:48:15.458   308  7024 V AwesomePlayer: getUseOffload() = 0 
08-25 10:48:15.458   308  7024 V OMXCodec: OMXCodec::Create
08-25 10:48:15.458   308  7024 V OMXCodec: findMatchingCodecs()
08-25 10:48:15.458   308  7024 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 10:48:15.459   308  7024 V OMXCodec: matchingCodecs.size()=1
08-25 10:48:15.459   308  7024 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-25 10:48:15.462   308  7024 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 10:48:15.462   308  7024 V LGCodecAdapter: LG Codec Adapter start
08-25 10:48:15.463   308  7024 V OMXCodec: OMXCodec Createtor
08-25 10:48:15.463   308  7024 V OMXCodec: setComponentRole
08-25 10:48:15.463   308  7024 V OMXCodec: configureCodec protected=0
08-25 10:48:15.463   308  7024 V LGCodecAdapter: called getLGCodecSpecificData
08-25 10:48:15.463   308  7024 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 10:48:15.463   308  7024 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 10:48:15.463   308  7024 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 10:48:15.463   308  7024 V LGCodecOSAL: Not support LGCodec
08-25 10:48:15.463   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 10:48:15.463   308  7024 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 10:48:15.463   308  7024 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 10:48:15.463   308  7024 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 10:48:15.463   308  7024 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 10:48:15.463   308  7024 V AudioSystem: isOffloadSupported()
08-25 10:48:15.463   308  7024 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 10:48:15.463   308  7024 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 10:48:15.463   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 10:48:15.463   308  7024 V OMXCodec: init()
08-25 10:48:15.463   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 10:48:15.463   308  7024 V OMXCodec: allocateBuffers
08-25 10:48:15.463   308  7024 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 10:48:15.463   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-25 10:48:15.464   308  7024 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,08-25 10:48:15.464   308  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ca060 on output port,
08-25 10:48:15.464   308  7024 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 10:48:15.465   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 10:48:15.465   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,08-25 10:48:15.465   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 10:48:15.465   308  7024 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 10:48:15.466   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 10:48:15.466   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 10:48:15.466   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,08-25 10:48:15.467   308  7024 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 10:48:15.467   308  7024 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 10:48:15.467   308  7024 V AudioCache: notify(0xb5474a80, 5, 0, 0)
08-25 10:48:15.467   308  7024 V AudioCache: ignored
08-25 10:48:15.467   308  7024 V AudioCache: notify(0xb5474a80, 1, 0, 0)
08-25 10:48:15.467   308  7024 V AudioCache: prepared
,08-25 10:48:15.467   308  1749 V AudioCache: wait - success
08-25 10:48:15.467   308  1749 V MediaPlayerService: start
08-25 10:48:15.467   308  1749 V AwesomePlayer: play_l() 
08-25 10:48:15.467   308  1749 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 10:48:15.467   308  1749 V AwesomePlayer: createAudioPlayer_l
,08-25 10:48:15.467   308  1749 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 10:48:15.467   308  1749 V AwesomePlayer: startAudioPlayer_l() 
08-25 10:48:15.467   308  1749 D AudioPlayer: start of Playback, useOffload 0
08-25 10:48:15.467   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 10:48:15.467   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-25 10:48:15.471   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044843616
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 10:48:15.472   308  7026 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
,08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ca330 on output port
08-25 10:48:15.472   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 10:48:15.473   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 10:48:15.473   308  1749 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 10:48:15.473   308  1749 V AudioCache: notify(0xb5474a80, 6, 0, 0)
08-25 10:48:15.473   308  1749 V AudioCache: ignored
08-25 10:48:15.474   308  1749 V MediaPlayerService: wait for playback complete
08-25 10:48:15.474   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.474   308  7027 V AudioCache: memcpy(0xaf006000, 0xb57c4000, 4096)
08-25 10:48:15.481   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.481   308  7027 V AudioCache: memcpy(0xaf007000, 0xb57c4000, 4096)
08-25 10:48:15.482   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.482   308  7027 V AudioCache: memcpy(0xaf008000, 0xb57c4000, 4096)
08-25 10:48:15.483   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.483   308  7027 V AudioCache: memcpy(0xaf009000, 0xb57c4000, 4096)
08-25 10:48:15.487   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.487   308  7027 V AudioCache: memcpy(0xaf00a000, 0xb57c4000, 4096)
,08-25 10:48:15.487   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.487   308  7027 V AudioCache: memcpy(0xaf00b000, 0xb57c4000, 4096)
08-25 10:48:15.487   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.487   308  7027 V AudioCache: memcpy(0xaf00c000, 0xb57c4000, 4096)
08-25 10:48:15.487   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.487   308  7027 V AudioCache: memcpy(0xaf00d000, 0xb57c4000, 4096)
08-25 10:48:15.488   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.488   308  7027 V AudioCache: memcpy(0xaf00e000, 0xb57c4000, 4096)
08-25 10:48:15.489   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.489  1031  1904 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7028 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 10:48:15.491   308  7027 V AudioCache: memcpy(0xaf00f000, 0xb57c4000, 4096)
08-25 10:48:15.491   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.492   308  7027 V AudioCache: memcpy(0xaf010000, 0xb57c4000, 4096)
08-25 10:48:15.492   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.492   308  7027 V AudioCache: memcpy(0xaf011000, 0xb57c4000, 4096)
08-25 10:48:15.492   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.492   308  7027 V AudioCache: memcpy(0xaf012000, 0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: memcpy(0xaf013000, 0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: memcpy(0xaf014000, 0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: memcpy(0xaf015000, 0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.493   308  7027 V AudioCache: memcpy(0xaf016000, 0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: memcpy(0xaf017000, 0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: memcpy(0xaf018000, 0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: memcpy(0xaf019000, 0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.495   308  7027 V AudioCache: memcpy(0xaf01a000, 0xb57c4000, 4096)
08-25 10:48:15.496   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.496   308  7027 V AudioCache: memcpy(0xaf01b000, 0xb57c4000, 4096)
08-25 10:48:15.497   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.497   308  7027 V AudioCache: memcpy(0xaf01c000, 0xb57c4000, 4096)
08-25 10:48:15.497   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.497   308  7027 V AudioCache: memcpy(0xaf01d000, 0xb57c4000, 4096)
08-25 10:48:15.498   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.498   308  7027 V AudioCache: memcpy(0xaf01e000, 0xb57c4000, 4096)
,08-25 10:48:15.499   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.499   308  7027 V AudioCache: memcpy(0xaf01f000, 0xb57c4000, 4096)
08-25 10:48:15.499   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.499   308  7027 V AudioCache: memcpy(0xaf020000, 0xb57c4000, 4096)
08-25 10:48:15.500   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.500   308  7027 V AudioCache: memcpy(0xaf021000, 0xb57c4000, 4096)
08-25 10:48:15.501   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.501   308  7027 V AudioCache: memcpy(0xaf022000, 0xb57c4000, 4096)
08-25 10:48:15.502   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.502   308  7027 V AudioCache: memcpy(0xaf023000, 0xb57c4000, 4096)
08-25 10:48:15.503   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.503   308  7027 V AudioCache: memcpy(0xaf024000, 0xb57c4000, 4096)
08-25 10:48:15.504   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.504   308  7027 V AudioCache: memcpy(0xaf025000, 0xb57c4000, 4096)
08-25 10:48:15.504   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.504   308  7027 V AudioCache: memcpy(0xaf026000, 0xb57c4000, 4096)
08-25 10:48:15.505   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.505   308  7027 V AudioCache: memcpy(0xaf027000, 0xb57c4000, 4096)
08-25 10:48:15.506   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.506   308  7027 V AudioCache: memcpy(0xaf028000, 0xb57c4000, 4096)
08-25 10:48:15.506   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.507   308  7027 V AudioCache: memcpy(0xaf029000, 0xb57c4000, 4096)
08-25 10:48:15.507   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.507   308  7027 V AudioCache: memcpy(0xaf02a000, 0xb57c4000, 4096)
08-25 10:48:15.508   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.508   308  7027 V AudioCache: memcpy(0xaf02b000, 0xb57c4000, 4096)
08-25 10:48:15.509   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.509   308  7027 V AudioCache: memcpy(0xaf02c000, 0xb57c4000, 4096)
08-25 10:48:15.509   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.509   308  7027 V AudioCache: memcpy(0xaf02d000, 0xb57c4000, 4096)
08-25 10:48:15.510   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.510   308  7027 V AudioCache: memcpy(0xaf02e000, 0xb57c4000, 4096)
,08-25 10:48:15.511   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.511   308  7027 V AudioCache: memcpy(0xaf02f000, 0xb57c4000, 4096)
08-25 10:48:15.511   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.511   308  7027 V AudioCache: memcpy(0xaf030000, 0xb57c4000, 4096)
08-25 10:48:15.512   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.512   308  7027 V AudioCache: memcpy(0xaf031000, 0xb57c4000, 4096)
08-25 10:48:15.514   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.514   308  7027 V AudioCache: memcpy(0xaf032000, 0xb57c4000, 4096)
08-25 10:48:15.515   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.515   308  7027 V AudioCache: memcpy(0xaf033000, 0xb57c4000, 4096)
08-25 10:48:15.516   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.516   308  7027 V AudioCache: memcpy(0xaf034000, 0xb57c4000, 4096)
08-25 10:48:15.517   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.517   308  7027 V AudioCache: memcpy(0xaf035000, 0xb57c4000, 4096)
08-25 10:48:15.517   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.517   308  7027 V AudioCache: memcpy(0xaf036000, 0xb57c4000, 4096)
08-25 10:48:15.518   308  7027 V AudioCache: write(0xb57c4000, 4096)
08-25 10:48:15.518   308  7027 V AudioCache: memcpy(0xaf037000, 0xb57c4000, 4096)
08-25 10:48:15.518   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 10:48:15.518   308  7027 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 10:48:15.518   308  7027 V AwesomePlayer: postAudioEOS() 
08-25 10:48:15.518   308  7027 V AudioCache: write(0xb57c4000, 280)
08-25 10:48:15.518   308  7027 V AudioCache: memcpy(0xaf038000, 0xb57c4000, 280)
08-25 10:48:15.522   308  7024 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 10:48:15.523   308  7024 V AwesomePlayer: onStreamDone
,08-25 10:48:15.523   308  7024 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 10:48:15.523   308  7024 V AudioCache: notify(0xb5474a80, 2, 0, 0)
08-25 10:48:15.523   308  7024 V AudioCache: playback complete
08-25 10:48:15.523   308  7024 V AwesomePlayer: pause_l() 
08-25 10:48:15.523   308  7024 V AudioCache: notify(0xb5474a80, 7, 0, 0)
08-25 10:48:15.523   308  7024 V AudioCache: ignored
08-25 10:48:15.523   308  7024 V AwesomePlayer: cancelPlayerEvents
08-25 10:48:15.523   308  1749 V AudioCache: wait - success
08-25 10:48:15.523   308  1749 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 10:48:15.523   308  7024 D AudioPlayer: Pause Playback at 1068125
08-25 10:48:15.523   308  1749 V AwesomePlayer: reset_l() 
08-25 10:48:15.523   308  1749 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-25 10:48:15.523   308  1749 V AudioCache: ignored
08-25 10:48:15.523   308  1749 V AwesomePlayer: cancelPlayerEvents
08-25 10:48:15.523   308  1749 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 10:48:15.523   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 10:48:15.523   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 10:48:15.523   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 10:48:15.523   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-25 10:48:15.523   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ca330 on port 1
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 10:48:15.524   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 10:48:15.524   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 10:48:15.524   308  7026 V OMXCodec: [OMX.google.vorbis.decoder] se,tState mState=6 , newState=1
08-25 10:48:15.524   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 10:48:15.524   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 10:48:15.524   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 10:48:15.525   308  1749 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 10:48:15.525   308  1749 D AudioPlayer: AudioPlayer releasing audio source
08-25 10:48:15.525   308  1749 D AudioPlayer: AudioPlayer done releasing audio source
08-25 10:48:15.526   308  1749 V AwesomePlayer: reset_l() 
08-25 10:48:15.526   308  1749 V AwesomePlayer: cancelPlayerEvents
08-25 10:48:15.526   308  1749 V AwesomePlayer: ~AwesomePlayer call
08-25 10:48:15.527   308  1749 V AwesomePlayer: reset_l() 
08-25 10:48:15.527   308  1749 V AwesomePlayer: cancelPlayerEvents
08-25 10:48:15.528  6943  7023 V SoundPool: close(31)
08-25 10:48:15.528  6943  7023 V SoundPool: pointer = 0x9fe6d000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 10:48:15.529  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 10:48:15.530  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 10:48:15.531  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3506
08-25 10:48:15.543  7028  7028 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 10:48:15.544  7028  7028 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 10:48:15.544  7028  7028 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 10:48:15.545  7028  7028 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 10:48:15.570  7028  7028 D BluetoothAdapterApp: Loading JNI Library
,08-25 10:48:15.603  7028  7028 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@20e07aa2 Instance Count = 1
,08-25 10:48:15.609  7028  7028 D BluetoothAdapterApp: onCreate
,08-25 10:48:15.632  7028  7028 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 10:48:15.632  7028  7028 D ProfileConfigQcom: Adding HeadsetService
08-25 10:48:15.632  7028  7028 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 10:48:15.632  7028  7028 D ProfileConfigQcom: Adding A2dpService
,08-25 10:48:15.632  7028  7028 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 10:48:15.633  7028  7028 D ProfileConfigQcom: Adding HidService
08-25 10:48:15.633  7028  7028 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 10:48:15.633  7028  7028 D ProfileConfigQcom: Adding HealthService
,08-25 10:48:15.633  7028  7028 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 10:48:15.634  7028  7028 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 10:48:15.635  7028  7028 D ProfileConfigQcom: Adding PanService
,08-25 10:48:15.635  7028  7028 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 10:48:15.635  7028  7028 D ProfileConfigQcom: Adding GattService
08-25 10:48:15.635  7028  7028 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-25 10:48:15.635  7028  7028 D ProfileConfigQcom: Adding BluetoothMapService
08-25 10:48:15.636  7028  7028 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 10:48:15.637  7028  7028 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter],
,08-25 10:48:15.646  6885  6885 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 10:48:15.649  7028  7028 V LGMDMManagerInternal: Create singleton instance
,08-25 10:48:15.730  7028  7028 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:48:15.734  6698  6698 I UEI.SmartControl: Supports setup maps: true
08-25 10:48:15.736  7028  7028 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:15.736  7028  7028 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:15.737  6698  6698 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 10:48:15.737  6698  6698 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 10:48:15.737  6698  6698 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 10:48:15.737  6698  6698 I UEI.SmartControl: ### init IR Blaster...
08-25 10:48:15.737  7028  7028 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:15.740  7028  7028 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:15.740  7028  7028 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 10:48:15.743  6698  6698 D serial_port: Configuring serial port
08-25 10:48:15.743  6698  6698 E UEI.SmartControl: UEIBLaster setting for 616
08-25 10:48:15.743  6698  6698 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 10:48:15.743  6698  6698 I UEI.SmartControl: configuring settings for MAXQ616
08-25 10:48:15.744  6698  6698 I UEI.SmartControl: Get version...
08-25 10:48:15.759  6960  6960 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-25 10:48:15.761  6698  7046 D UEI.SmartControl: serial port data available: 21
08-25 10:48:15.792  6698  6698 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 10:48:15.792  6698  6698 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-25 10:48:15.792  6698  6698 I UEI.SmartControl: QS saving settings...
08-25 10:48:15.794  6698  6698 D UEI.SmartControl: IR Blaster version: 25672567
08-25 10:48:15.811  6698  7046 D UEI.SmartControl: serial port data available: 4
,08-25 10:48:15.842  6698  7053 I UEI.SmartControl: Device manager: loading config....
08-25 10:48:15.843  6698  7053 D UEI.SmartControl: ----------- loading internal config...
,08-25 10:48:15.846  6698  6698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 10:48:15.853  6698  6698 E UEI.SmartControl: Services init done
08-25 10:48:15.853  6698  6698 D UEI.SmartControl: QS Service init finished
08-25 10:48:15.855  6698  6698 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 10:48:15.856  6698  6698 D UEI.SmartControl: QS Service version code: 201091
,08-25 10:48:15.860  6698  6698 D UEI.SmartControl: Service requested: Control
08-25 10:48:15.865  6698  6698 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 10:48:15.865  6698  7053 E UEI.SmartControl: Loading SETTINGS...
08-25 10:48:15.869  6698  6698 D UEI.SmartControl: Internal service binding...
08-25 10:48:15.869  6943  6943 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-25 10:48:15.873  6698  6714 I UEI.SmartControl: ------ IControl API: 11
08-25 10:48:15.874  6698  6714 D UEI.SmartControl: File observer start...
08-25 10:48:15.875  6698  6714 E UEI.SmartControl: IR Port is disabled: false
08-25 10:48:15.875  6698  6714 D UEI.SmartControl: Starting file observer...
08-25 10:48:15.878  6698  6714 I UEI.SmartControl: Registering callback...
08-25 10:48:15.879  6698  6713 I UEI.SmartControl: ------ IControl API: 19
08-25 10:48:15.879  6698  6713 I UEI.SmartControl: Registering Services Ready callback...
08-25 10:48:15.882  6698  7053 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 10:48:15.902  6698  7052 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 10:48:15.902  6943  6959 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 10:48:15.903  6943  7021 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 10:48:15.903  6943  7021 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-25 10:48:15.904  6943  6943 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 10:48:15.904  6943  6943 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 10:48:15.904  6698  6714 I UEI.SmartControl: ------ IControl API: 8
08-25 10:48:15.905  6698  7052 D UEI.SmartControl: -----service ready thread exits
08-25 10:48:15.908  6943  6943 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 10:48:15.909  6943  6943 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 10:48:15.909  6943  6943 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 10:48:15.910  6943  6943 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 10:48:15.911  6943  6943 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 10:48:15.912  6943  6943 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 10:48:15.914  6943  6943 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 10:48:15.918  6943  6943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-25 10:48:15.919  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 10:48:15.921  6943  6943 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 10:48:15.921  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-25 10:48:15.923  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 10:48:15.925  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 10:48:15.927  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 10:48:15.929  6943  6943 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472114895928]
08-25 10:48:15.934  6943  6943 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-25 10:48:15.938  1031  1047 I ActivityManager: Killing 6090:com.android.gallery3d/u0a27 (adj 15): empty #17
08-25 10:48:15.969  6943  7058 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 10:48:16.006  1031  1047 I ActivityManager: Killing 6590:com.lge.email/u0a23 (adj 15): empty #18
,08-25 10:48:16.038  1031  1643 W libprocessgroup: failed to open /acct/uid_10027/pid_6090/cgroup.procs: No such file or directory
,08-25 10:48:16.042  1031  2033 W libprocessgroup: failed to open /acct/uid_10023/pid_6590/cgroup.procs: No such file or directory
,08-25 10:48:16.050  6943  6943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-25 10:48:16.051  6943  6943 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-25 10:48:16.052  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 10:48:16.052  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 10:48:16.053  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 10:48:16.053  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 10:48:16.054  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-25 10:48:16.069  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-25 10:48:16.971  1031  1922 D WifiServiceImplEx: setWifiEnabled: true pid=6778, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 10:48:16.972  1031  1922 D WifiService: setWifiEnabled: true pid=6778, uid=10118
08-25 10:48:16.972  1031  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:48:16.999  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:16.999  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:16.999  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-25 10:48:17.001  1031  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 10:48:17.001  1031  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 10:48:17.003  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 10:48:17.003  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 10:48:17.004  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 10:48:17.004  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-25 10:48:17.004  1031  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 10:48:17.004  1031  1539 E WifiHW  : unknown target_country: EU , set to default
08-25 10:48:17.004  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 10:48:17.004  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 10:48:17.004  1031  1539 I WifiUtil: gEnableBmps=1
08-25 10:48:17.067  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:17.081  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-25 10:48:17.087  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:48:17.095  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:17.098  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:17.100  1031  1095 D Tethering: MasterInitialState.processMessage what=3
,08-25 10:48:17.111  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:17.112  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:48:17.114  1031  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:17.116  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 10:48:17.124  6496  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 10:48:17.137  5797  5797 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 10:48:17.145  5797  5797 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 10:48:17.171  2191  2191 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:17.198  1031  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:17.249  1031  1940 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7093 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 10:48:17.253  1031  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:17.253  1031  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 10:48:17.334  7093  7093 I AppUp4:AppBoxCP: onCreate
,08-25 10:48:17.335  7093  7093 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-25 10:48:17.347  7093  7093 I AppUp4:DB:  setFingerPrint start
,08-25 10:48:17.347  7093  7093 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-25 10:48:17.357  7093  7093 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-25 10:48:17.357  7093  7093 I AppUp4:DB:  SDK version = 21
08-25 10:48:17.358  7093  7093 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-25 10:48:17.359  7093  7093 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 10:48:17.361  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 10:48:17.361  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:17.363  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 10:48:17.364  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 10:48:17.372  7093  7093 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 10:48:17.414  7093  7093 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:17.414  7093  7093 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:17.423  7093  7093 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f5b721c
08-25 10:48:17.423  7093  7093 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 10:48:17.423  7093  7093 D AppUp4:CustFacade: isPhone : true
08-25 10:48:17.423  7093  7093 D AppUp4:CustModeStarterReceiver: begin check event
08-25 10:48:17.424  7093  7093 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 10:48:17.424  7093  7093 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 10:48:17.425  7093  7112 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 10:48:17.425  7093  7112 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 10:48:17.426  7093  7112 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 10:48:17.428  1031  2033 I ActivityManager: Killing 6177:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-25 10:48:17.459  1031  1922 W libprocessgroup: failed to open /acct/uid_10080/pid_6177/cgroup.procs: No such file or directory
,08-25 10:48:17.460  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:17.461  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:17.468  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:17.476  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 10:48:17.488  4354  7118 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 10:48:17.497  4354  7119 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:17.498  4354  7119 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 10:48:17.554  1031  1995 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7125 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 10:48:17.651  7125  7125 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:17.652  7125  7125 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 10:48:17.654  7125  7125 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 10:48:17.655  7125  7125 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 10:48:17.725  1031  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 10:48:17.725  1031  1095 D Tethering: InitialState.processMessage what=4
,08-25 10:48:17.728  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 10:48:17.739   304   894 D SoftapController: Softap fwReload - Ok
,08-25 10:48:17.740  1031  1539 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (731ms)
08-25 10:48:17.743   304   894 D CommandListener: Setting iface cfg
08-25 10:48:17.743   304   894 D CommandListener: Trying to bring down wlan0
08-25 10:48:17.744   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:48:17.746  1031  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 10:48:17.747  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:17.747  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:17.747  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 10:48:17.751  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-25 10:48:17.740  7144  7144 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 10:48:17.740  7144  7144 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:17.757  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 10:48:17.758  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:17.766  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:17.767  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:17.768  1031  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 10:48:17.768  1031  1539 D WifiMonitor: connecting to supplicant
,08-25 10:48:17.788  7144  7144 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 10:48:17.791  7125  7125 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 10:48:17.808  7125  7125 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 10:48:17.822  7144  7144 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 10:48:17.822  7144  7144 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-25 10:48:17.847  7125  7125 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 10:48:17.889  7125  7125 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 10:48:17.890  7125  7125 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 10:48:17.920  7144  7144 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 10:48:17.975  7144  7144 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 10:48:17.995  7144  7144 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 10:48:17.995  7144  7144 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-25 10:48:17.997  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 10:48:17.997  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 10:48:17.998  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 10:48:17.998  1031  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 10:48:17.999  1031  7155 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 10:48:17.999  1031  7155 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 10:48:17.999  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:17.999  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 10:48:17.999  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 10:48:17.999  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:17.999  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 10:48:18.000  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 10:48:18.000  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.000  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.001  1031  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 10:48:18.001  1031  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 10:48:18.002  1031  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-25 10:48:18.003  1031  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 10:48:18.003  1031  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 10:48:18.005  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:18.005  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:18.005  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 10:48:18.005  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.005  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.005  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.005  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.005  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:18.009  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.011  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-25 10:48:18.007  1031  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 10:48:18.013  1031  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-25 10:48:18.013  1031  1539 D WifiConfigStore: Loading config and enabling all networks 
08-25 10:48:18.013  1031  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 10:48:18.013  1031  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-25 10:48:18.015  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 10:48:18.016  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 10:48:18.017  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:18.017  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:18.017  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:18.017  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:18.018  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:18.018  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:18.018  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:18.018  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:18.022  1031  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 10:48:18.032  1031  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-25 10:48:18.033  1031  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 10:48:18.034  1031  1539 D WifiStateMachine: enableVerboseLogging : level 2
,08-25 10:48:18.034  1031  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 10:48:18.034  1031  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 10:48:18.034  1031  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 10:48:18.035  1031  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 10:48:18.035  1031  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 10:48:18.035  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 10:48:18.035  1031  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 10:48:18.035  1031  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 10:48:18.036  1031  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 10:48:18.036  1031  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 10:48:18.037  1031  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 10:48:18.037  1031  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 10:48:18.037  1031  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 10:48:18.037  1031  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 10:48:18.037  1031  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 10:48:18.038  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 10:48:18.038  1031  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 10:48:18.039  1031  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 10:48:18.039  1031  1539 D WifiNative-HAL: Setting external_sim to 1
08-25 10:48:18.039  1031  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 10:48:18.039  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-25 10:48:18.039  1943  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 10:48:18.039  1943  2307 D WfdsService: Set the WFDS Monitor: true
08-25 10:48:18.039  1943  2307 D WfdsMonitor: WfdsMonitorThread create
08-25 10:48:18.039  1943  2307 D WfdsMonitor: WFDS Monitor is created and started
08-25 10:48:18.039  1943  2307 D WfdsService: WiFi: Supplicant connection re-established
08-25 10:48:18.039  1031  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 10:48:18.040  1031  1539 I WifiNative-HAL: startHal
08-25 10:48:18.040  1031  1539 D wifi    : setting scan oui 0xaf6d1040
08-25 10:48:18.040  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 10:48:18.040  1031  1539 I WifiNative-HAL: startHal
08-25 10:48:18.040  1031  1539 D wifi    : setting scan oui 0xaf6d1040
08-25 10:48:18.040  1943  7156 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 10:48:18.040  1031  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 10:48:18.041  1943  7156 E CtrlSupplicant: Succeed to open control connection
08-25 10:48:18.041  1943  7156 E CtrlSupplicant: Succeed to open monitor connection
08-25 10:48:18.041  1943  7156 D WfdsMonitor: Supplicant connection established
08-25 10:48:18.041  1943  2307 D WfdsService: Connected to the supplicant for wfds
08-25 10:48:18.042  1031  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 10:48:18.042  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 10:48:18.042  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 10:48:18.042  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 10:48:18.043  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 10:48:18.043  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 10:48:18.043  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 10:48:18.043  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 10:48:18.043  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd, RXFILTER-REMOVE 3
08-25 10:48:18.043  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 10:48:18.044  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 10:48:18.044  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 10:48:18.044  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 10:48:18.044  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 10:48:18.044  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 10:48:18.044  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 10:48:18.044  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 10:48:18.044  7144  7144 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 10:48:18.045  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 10:48:18.045  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 10:48:18.045  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 10:48:18.045  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 10:48:18.047  1031  1539 E WifiNative: : [212,916,065 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 10:48:18.047  1031  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 10:48:18.047  1031  1539 D WifiNative-wlan0: RECONNECT: returned true
08-25 10:48:18.047  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-25 10:48:18.048  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 10:48:18.048  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 10:48:18.048  1031  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 10:48:18.048  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:18.049  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-25 10:48:18.049  1031  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.051  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 10:48:18.051  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-25 10:48:18.051  1031  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.051  1031  1556 I WifiNative-HAL: startHal
08-25 10:48:18.051   304   894 D CommandListener: Setting iface cfg
08-25 10:48:18.051  1031  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6d1040
08-25 10:48:18.051  1031  1556 D wifi    : failed to get capabilities : -3
08-25 10:48:18.051   304   894 D CommandListener: Trying to bring up p2p0
08-25 10:48:18.051  1031  1556 E WifiScanningService: could not get scan capabilities
08-25 10:48:18.051  1031  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 10:48:18.051  1031  1537 D LGWifiP2pService: P2pEnablingState
08-25 10:48:18.051  1031  1557 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.051  1031  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.051  1031  1537 D LGWifiP2pService: P2p socket connection successful
08-25 10:48:18.051  1031  1537 D LGWifiP2pService: P2pEnabledState
08-25 10:48:18.052  1031  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 10:48:18.052  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 10:48:18.053  1943  1943 D WfdsService: WifiP2pState is changed : true
08-25 10:48:18.053  1943  2307 D WfdsService: Receive the WFDS_ENABLE Method
08-25 10:48:18.053  1943  2307 D WfdsService: Set the WFDS Monitor: true
08-25 10:48:18.053  1943  2307 D WfdsService: Connected to the supplicant for wfds
08-25 10:48:18.053  1943  2307 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 10:48:18.053  1031  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 10:48:18.053  7144  7144 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 10:48:18.053  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 10:48:18.054  1943  2307 D WfdsService: selectPreferredScanChannel [36]
08-25 10:48:18.054  1943  2307 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 10:48:18.054  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 10:48:18.054  1031  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 10:48:18.055  1943  1943 D WfdsService: isConnected: false
08-25 10:48:18.055  1031  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 10:48:18.055  1031  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 10:48:18.056  1031  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 10:48:18.056  1031  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 10:48:18.056  1031  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 10:48:18.056  1031  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 10:48:18.057  1031  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-25 10:48:18.057  1031  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 10:48:18.057  1031  1537 D LGWifiP2pService: before postfix = G3
08-25 10:48:18.057  1031  1537 D WifiServerServiceExt: postfix byte check : 2
08-25 10:48:18.057  1031  1537 D LGWifiP2pService: after postfix = G3
08-25 10:48:18.057  1031  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 10:48:18.057  1031  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 10:48:18.057  1031  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 10:48:18.057  7144  7144 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 10:48:18.057  1031  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 10:48:18.058  1031  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 10:48:18.058  1031  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 10:48:18.058  1031  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 10:48:18.058  1031  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 10:48:18.058  1031  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 10:48:18.058  1031  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 10:48:18.058  1031  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 10:48:18.058  7144  7144 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 10:48:18.059  1031  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 10:48:18.059  1031  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 10:48:18.059  1031  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 10:48:18.059  1031  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-25 10:48:18.060  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 10:48:18.060  1031  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 10:48:18.063  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 10:48:18.063  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 10:48:18.063  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 10:48:18.063  1031  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 10:48:18.064  1031  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 10:48:18.065  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 10:48:18.065  7144  7144 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.066  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 10:48:18.066  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.066  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.066  7144  7144 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 10:48:18.066  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.066  7144  7144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.066  1943  7156 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.067  1031  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 10:48:18.067  1031  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 10:48:18.067  1031  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 10:48:18.067  7144  7144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.067  1943  7156 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.067  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 10:48:18.067  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 10:48:18.067  1943  1943 D WfdsService: Update P2p Interface State: 3
08-25 10:48:18.067  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 10:48:18.068  1031  7155 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.068  1031  7155 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.068  1031  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 10:48:18.068  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.068  1031  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 10:48:18.068  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.068  1031  7155 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.068  1031  7155 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.068  1031  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 10:48:18.068  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.068  1031  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 10:48:18.068  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.071  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 10:48:18.071  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:18.071  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 10:48:18.071  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 10:48:18.071  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 10:48:18.072  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-25 10:48:18.078  1031  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 10:48:18.078  1031  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 10:48:18.078  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 10:48:18.078  7144  7144 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:18.079  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 10:48:18.079  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:18.079  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:18.079  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:18.079  1031  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 10:48:18.079  1031  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 10:48:18.079  1031  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 10:48:18.079  1031  1539 D WifiNative-wlan0: doBoolean: SCAN
08-25 10:48:18.080  1031  1539 D WifiNative-wlan0: SCAN: returned false
08-25 10:48:18.080  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=212950  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 10:48:18.081  7125  7125 I HubEmail: JNI_OnLoad()
08-25 10:48:18.081  7125  7125 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 10:48:18.081  7125  7125 I HubEmail: registerNatives()
08-25 10:48:18.081  7125  7125 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 10:48:18.081  7125  7125 I HubEmail: registerNativeMethods()
08-25 10:48:18.081  7125  7125 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 10:48:18.081  7125  7125 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-25 10:48:18.119  1031  2012 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7162 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-25 10:48:18.123  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=212993  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 10:48:18.124  1031  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:18.125  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:18.125  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:18.125  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.125  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.125  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 10:48:18.125  1031  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:18.126  1031  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:18.127  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.127  1031  1537 D LGWifiP2pService: InactiveState
08-25 10:48:18.127  1031  1537 D LGWifiP2pService: InactiveState{ when=-61ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandl,er }
08-25 10:48:18.128  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-61ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.128  1031  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-25 10:48:18.128  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 10:48:18.129  7144  7144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.129  7144  7144 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 10:48:18.129  7144  7144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.130  7144  7144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.131  1943  7156 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 10:48:18.131  1943  7156 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.131  1943  7156 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.131  1031  7155 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 10:48:18.131  1031  7155 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.131  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.131  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:18.131  1031  7155 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.132  1031  7155 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.132  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.132  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.132  1031  7155 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:18.132  1031  7155 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.132  1031  7155 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.132  1031  7155 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:18.132  1031  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 10:48:18.132  1031  1537 D LGWifiP2pService: InactiveState{ when=-65ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.132  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-65ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.132  1031  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.132  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.132  1031  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:,48:18.133  1031  1537 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.133  1031  1537 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.134  1031  1031 E WifiServerServiceExt: No p2p device connected
08-25 10:48:18.134  1943  2307 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 10:48:18.134  1031  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:18.135  6983  7160 V FormManager: Network unavailable.
08-25 10:48:18.135  1031  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:18.136  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:18.136  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 10:48:18.140  7125  7161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:48:18.146  6983  7160 V FormManager: Network unavailable.
08-25 10:48:18.150  6983  7159 W FormManager: Network not available. Please check & try again.
08-25 10:48:18.156  1031  1643 I ActivityManager: Killing 6624:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-25 10:48:18.260  1031  1942 W libprocessgroup: failed to open /acct/uid_10061/pid_6624/cgroup.procs: No such file or directory
08-25 10:48:18.367  7162  7162 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:18.368  7162  7162 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 10:48:18.371  7162  7162 D PhoneMonitor: Register our PhoneStateListener
,08-25 10:48:18.393  7162  7162 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 10:48:18.401  7162  7162 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 10:48:18.436  7162  7162 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 10:48:18.438  7162  7162 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 10:48:18.439  7162  7162 D TelephonyAutoProfiling: [parse] Load xml
,08-25 10:48:18.446  7162  7162 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 10:48:18.446  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 10:48:18.446  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 10:48:18.446  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 10:48:18.446  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 10:48:18.447  7162  7162 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 10:48:18.447  7162  7162 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-25 10:48:18.456  7162  7162 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-25 10:48:18.475  1031  1995 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7184 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:48:18.476  1031  1995 I ActivityManager: Killing 6207:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 10:48:18.518  1031  1977 W libprocessgroup: failed to open /acct/uid_10097/pid_6207/cgroup.procs: No such file or directory
,08-25 10:48:18.590  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 10:48:18.590  1031  7155 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 10:48:18.590  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 10:48:18.590  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-25 10:48:18.590  1031  7155 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 10:48:18.591  7144  7144 E wpa_supplicant: USIM:  scard_init function
08-25 10:48:18.592  7144  7144 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 10:48:18.592  1031  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 10:48:18.592  1031  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 10:48:18.593  1031  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 10:48:18.593  1031  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-25 10:48:18.593  1031  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 10:48:18.594  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 10:48:18.594  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-25 10:48:18.609  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=213479  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 10:48:18.612  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.613  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.613  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 10:48:18.614  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:18.614  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:18.616  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 10:48:18.621  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=213490  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 10:48:18.622  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.622  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.622  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 10:48:18.624  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:18.624  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 10:48:18.636  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:18.636  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 10:48:18.639  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.713  7144  7144 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 10:48:18.717  1031  1590 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7202 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-25 10:48:18.718  1031  1590 I ActivityManager: Killing 6660:com.lge.eula/1000 (adj 15): empty #17
08-25 10:48:18.719  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 10:48:18.719  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 10:48:18.719  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 10:48:18.720  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 10:48:18.720  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:18.720  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:18.727  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=213597  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 10:48:18.728  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=213598  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 10:48:18.729  1031  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213599
08-25 10:48:18.729  1031  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213599
,08-25 10:48:18.730  1031  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213600
08-25 10:48:18.730  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213600
08-25 10:48:18.731  1031  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213601
08-25 10:48:18.731  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=213601  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 10:48:18.741  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:18.741  7144  7144 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:48:18.741  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:18.741  7144  7144 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-25 10:48:18.741  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 10:48:18.741  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:48:18.742  1031  7155 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:48:18.742  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-25 10:48:18.742  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 10:48:18.742  1031  7155 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 10:48:18.742  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:18.743  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:18.788  1031  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 10:48:18.788  1031  2033 W libprocessgroup: failed to open /acct/uid_1000/pid_6660/cgroup.procs: No such file or directory
,08-25 10:48:18.794  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=213664  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 10:48:18.798  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.798  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.798  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 10:48:18.799  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.799  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.799  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 10:48:18.799  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=213669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 10:48:18.800  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=213670  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 10:48:18.800  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:18.800  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 10:48:18.801  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:18.801  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 10:48:18.802  1031  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213672
08-25 10:48:18.802  1031  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213672
08-25 10:48:18.802  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-25 10:48:18.803  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:18.804  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:18.804  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.804  1031  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 10:48:18.806  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:18.806  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:18.807  1031  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 10:48:18.808  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.817  1031  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 10:48:18.817  1031  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 10:48:18.824  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.824  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.824  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 10:48:18.824  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:18.824  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:18.825  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.829  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.829  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:18.829  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-25 10:48:18.834  1031  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 10:48:18.835  1031  1545 D ConnectivityService: Got NetworkAgent Messenger
08-25 10:48:18.835  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:48:18.835  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 10:48:18.835  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 10:48:18.835  1031  1545 D ConnectivityService: NetworkAgent connected
08-25 10:48:18.835  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 10:48:18.835  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 10:48:18.842  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 10:48:18.843  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:48:18.843  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 10:48:18.843  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 10:48:18.843  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 10:48:18.848  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:18.848  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:18.850  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.850  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 10:48:18.851   304   894 D CommandListener: Setting iface cfg
08-25 10:48:18.855  1031  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-25 10:48:18.855  1031  7220 D DhcpStateMachine: StoppedState
08-25 10:48:18.855  1031  7220 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.855  1031  7220 D DhcpStateMachine: WaitBeforeStartState
,08-25 10:48:18.855  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=213725  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:18.856  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=213726  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:18.857  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=213727  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:18.858  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:18.858  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.858  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 10:48:18.858  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.858  1031  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.859  1031  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.859  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.860  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:18.907  1031  1590 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7221 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:48:18.909  1031  1590 I ActivityManager: Killing 6677:com.lge.bnr/1000 (adj 15): empty #17
,08-25 10:48:18.932   333   333 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 492us total 20.236ms
,08-25 10:48:18.953   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 19.823ms
,08-25 10:48:18.973   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.914ms
,08-25 10:48:18.977  1031  2052 W libprocessgroup: failed to open /acct/uid_1000/pid_6677/cgroup.procs: No such file or directory
,08-25 10:48:18.978  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=213848  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:18.978  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=213848  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:18.979  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=213849  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:18.980  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:168015] from screen [on:0 period:-1058883548] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 10:48:18.981  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058883547] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 10:48:18.981  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 10:48:18.984  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:18.984  1031  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.984  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 10:48:18.984  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.985  1031  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:18.988  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:18.989  1031  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 10:48:18.990  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:18.990  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:18.991  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:18.992  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 10:48:18.992  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:18.993  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:18.993  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 10:48:18.994  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=168,0,0
08-25 10:48:18.994  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=168,0,0
08-25 10:48:18.994  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 10:48:18.995  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 10:48:18.995  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 10:48:18.995  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 10:48:18.996  1031  1539 D WifiNative-wlan0: SET ps 0: returned true
08-25 10:48:18.996  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 10:48:18.996  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 10:48:18.997  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 10:48:18.997  1031  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 10:48:18.997  1031  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3beef8d6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.997  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3beef8d6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:18.997  1031  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 10:48:18.998  1031  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-25 10:48:19.000  1031  7220 D DhcpStateMachine: WaitBeforeStartState{ when=-2ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:19.000  1031  7220 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 10:48:19.000   304   894 D CommandListener: Setting iface cfg
08-25 10:48:19.001   304   894 D CommandListener: Trying to bring up wlan0
08-25 10:48:19.002  1031  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 10:48:19.003  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:19.003  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 10:48:19.005  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:19.005  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 10:48:19.006  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-25 10:48:19.007  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-25 10:48:19.007  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 10:48:19.007  1031  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:19.007  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:19.007  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 10:48:19.008  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 10:48:19.008  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 10:48:19.008  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 10:48:19.008  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 10:48:19.008  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:19.019  7221  7221 I art     : Almond Protected OAT
,08-25 10:48:19.024  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-25 10:48:19.025  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 10:48:19.025  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:19.026  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:19.027  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:19.027  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:19.028  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:19.028  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:19.029  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 10:48:19.030  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 10:48:19.030  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 10:48:19.030  1031  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 10:48:19.031  1031  1545 D ConnectivityService: ignoring duplicate network state non-change
08-25 10:48:19.034  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:19.034  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 10:48:19.037  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:19.037  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.038  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.038  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 10:48:19.041  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 10:48:19.042  1031  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-25 10:48:19.045  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.045  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.046  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 10:48:19.049  1031  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 10:48:19.063  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 10:48:19.063  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 10:48:19.063  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.063  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.063  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 10:48:19.063  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 10:48:19.069  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.069  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:19.069  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 10:48:19.070  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:19.071  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:19.071  1031  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 10:48:19.071  1031  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 10:48:19.072  1031  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 10:48:19.072  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 10:48:19.072  1031  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 10:48:19.073  1031  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 10:48:19.073   304   894 E Netd    : netlink response contains error (File exists)
08-25 10:48:19.073  1031  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 10:48:19.074  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:19.074  1031  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 10:48:19.074  1031  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,08-25 10:48:19.074  1031  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 10:48:19.073  1031  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 10:48:19.075  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 10:48:19.075  1031  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 10:48:19.075  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 10:48:19.075  1031  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 10:48:19.075  1031  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 10:48:19.076  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 10:48:19.076  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 10:48:19.076  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:19.076  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 10:48:19.076  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:19.076  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 10:48:19.076  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:19.076  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.076  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 10:48:19.076  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 10:48:19.076  1031  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-25 10:48:19.076  1031  1545 D ConnectivityService:    accepting network in place of null
08-25 10:48:19.076  1031  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.081  1031  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.082  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.082   304  7241 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 10:48:19.083  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 10:48:19.081  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:19.083  1031  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 10:48:19.083  1031  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 10:48:19.083  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 10:48:19.087  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:19.087  1031  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 10:48:19.087  1031  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisi,oningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 10:48:19.089  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 10:48:19.089  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 10:48:19.089  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 10:48:19.089  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 10:48:19.091  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 10:48:19.097  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 10:48:19.097  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:19.108  1031  1545 D ConnectivityService: validation of new default Network = false
08-25 10:48:19.108  1031  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 10:48:19.108  1031  1545 D DSQN    : enableDataServiceNotify 
08-25 10:48:19.108  1031  1545 D DSQN    : start dsqn bin
08-25 10:48:19.109  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:19.109  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 10:48:19.109  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 10:48:19.119  1031  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 10:48:19.120  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 10:48:19.120  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.120  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:19.121  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:19.122  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 10:48:19.110  7248  7248 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:19.110  7248  7248 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:19.139  7221  7221 D WeatherApplication: removeAccount
,08-25 10:48:19.140  7221  7221 D WeatherApplication: Account.length = 0
,08-25 10:48:19.141  7221  7221 E WeatherApplication: OPERATOR:OPEN
08-25 10:48:19.141   304  7241 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 10:48:19.143  7248  7248 E DSQN    : DSQN ssw
08-25 10:48:19.153  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:19
08-25 10:48:19.154  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 10:48:19.155  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:19.156  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 10:48:19.157  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 10:48:19.157  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-25 10:48:19.159  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 10:48:19.161  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-25 10:48:19.161  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-25 10:48:19.172  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 10:48:19.172  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 10:48:19.172  7221  7221 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-25 10:48:19.173   304  7241 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 10:48:19.190  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 10:48:19.190  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:19
08-25 10:48:19.201   304   893 D LGDataListener: argv[0]=dsqncommand
08-25 10:48:19.201   304   893 D LGDataListener: argv[1]=wlan0
08-25 10:48:19.201   304   893 D LGDataListener: argv[2]=1
08-25 10:48:19.201   304   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 10:48:19.201  1031  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 10:48:19.201  1031  1093 D DSQN    : start to monitor internet connection
,08-25 10:48:19.203  1031  7220 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 10:48:19.204  1031  7220 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-25 10:48:19.204  1031  7220 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 10:48:19.190  7256  7256 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:19.190  7256  7256 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:19.211  7256  7256 I dhcpcd  : version 5.5.6 starting
08-25 10:48:19.212  7256  7256 E dhcpcd  : get_duid: m
08-25 10:48:19.212  7256  7256 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 10:48:19.212  7256  7256 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-25 10:48:19.229  1031  2012 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7259 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 10:48:19.230  1031  2012 I ActivityManager: Killing 2130:com.lge.music/u0a34 (adj 15): empty #17
,08-25 10:48:19.232  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 08:48:19 GMT], X-Android-Received-Millis=[1472114899232], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472114899200]}
,08-25 10:48:19.232  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 10:48:19.233  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 10:48:19.234  1031  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 10:48:19.234  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 10:48:19.234  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:19.234  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:19.234  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 10:48:19.234  1031  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 10:48:19.234  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 10:48:19.234  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.234  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:19.236  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:19.236  1031  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.236  1031  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.236  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:19.236  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 10:48:19.237  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 10:48:19.238  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:19.238  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 10:48:19.248   308  1384 V AudioFlinger: 2130 died, releasing its sessions
08-25 10:48:19.248   308  1384 V AudioFlinger:  pid 1853 @ 0
08-25 10:48:19.248   308  1384 V AudioFlinger:  pid 3453 @ 1
08-25 10:48:19.249   308  1384 V AudioFlinger:  pid 3453 @ 2
,08-25 10:48:19.266  7256  7256 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 10:48:19.266  7256  7256 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 10:48:19.266  7256  7256 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 10:48:19.266  7256  7256 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 10:48:19.266  7256  7256 D dhcpcd  : wlan0: sending REQUEST (xid 0x9afa7280), next in 3.52 seconds
,08-25 10:48:19.287  7256  7256 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 10:48:19.288  1031  1940 W libprocessgroup: failed to open /acct/uid_10034/pid_2130/cgroup.procs: No such file or directory
08-25 10:48:19.288  1817  7253 I CheckinService: active receiver: enabled
,08-25 10:48:19.296  7256  7256 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 10:48:19.296  7256  7256 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 10:48:19.297  7256  7256 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 10:48:19.297  7256  7256 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 10:48:19.297  7256  7256 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 10:48:19.301  7256  7256 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 10:48:19.301  7256  7256 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 10:48:19.301  7256  7256 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-25 10:48:19.310  1817  7253 I CheckinService: Preparing to send checkin request
08-25 10:48:19.310  1817  7253 I EventLogService: Accumulating logs since 1472114743482
,08-25 10:48:19.328  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 10:48:19.328  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:19.329  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:19.351  1817  7253 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-25 10:48:19.400   279   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 10:48:19.400   279   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 10:48:19.401   279   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 10:48:19.401  7259  7293 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-25 10:48:19.405   279   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 10:48:19.405   279   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 10:48:19.405   279   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 10:48:19.405  7259  7293 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 10:48:19.413   279   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 10:48:19.413   279   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 10:48:19.413   279   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 10:48:19.414  7259  7298 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-25 10:48:19.416   279   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 10:48:19.416   279   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 10:48:19.416   279   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 10:48:19.416  7259  7298 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 10:48:19.444  1031  1590 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7304 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 10:48:19.495  7304  7304 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 10:48:19.495  7304  7304 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 10:48:19.520  7304  7304 I MultiDex: VM with version 2.1.0 has multidex support
,08-25 10:48:19.520  7304  7304 I MultiDex: install
08-25 10:48:19.521  7304  7304 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-25 10:48:19.529  7304  7304 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-25 10:48:19.607  1031  7220 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 10:48:19.609  1031  7220 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 10:48:19.610  1031  7220 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 10:48:19.610  7259  7259 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-25 10:48:19.610  1031  7220 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 10:48:19.610  1031  7220 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 10:48:19.610  1031  7220 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 10:48:19.611  1031  7220 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 10:48:19.611  1031  7220 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 10:48:19.611  1031  7220 D DhcpStateMachine: RunningState
08-25 10:48:19.617  7259  7259 I LibraryLoader: Loading: webviewchromium
08-25 10:48:19.619  7259  7259 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4500-4503)
08-25 10:48:19.619  7259  7259 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 10:48:19.627  7259  7259 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1140a77}
08-25 10:48:19.628  7259  7259 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 10:48:19.628  7259  7259 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 10:48:19.636  7259  7259 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 10:48:19.637  7259  7259 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 10:48:19.653   308   308 V AudioPolicyService: registerClient() client 0xb57f9420, uid 10093
,08-25 10:48:19.655  7259  7345 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 10:48:19.663  7259  7259 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 10:48:19.665  7259  7259 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 10:48:19.666  7259  7259 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 10:48:19.682  7259  7259 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:19.682  7259  7259 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:19.682  7259  7259 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:19.682  7259  7259 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:19.682  7259  7259 I Adreno-EGL: Remote Branch: 
08-25 10:48:19.682  7259  7259 I Adreno-EGL: Local Patches: 
08-25 10:48:19.682  7259  7259 I Adreno-EGL: Reconstruct Branch: 
,08-25 10:48:19.758  7259  7259 I NSApplication: Starting up...
,08-25 10:48:19.812  1031  2012 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7358 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 10:48:19.814  1031  1643 I ActivityManager: Killing 6130:com.android.vending/u0a44 (adj 15): empty #17
08-25 10:48:19.955  1031  1904 W libprocessgroup: failed to open /acct/uid_10044/pid_6130/cgroup.procs: No such file or directory
,08-25 10:48:19.988  7358  7358 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 10:48:20.003  1031  1942 D WifiServiceImplEx: setWifiEnabled: false pid=6778, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 10:48:20.003  1031  1942 D WifiService: setWifiEnabled: false pid=6778, uid=10118
08-25 10:48:20.003  1031  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:48:20.004  7304  7324 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:20.004  7304  7324 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 10:48:20.013  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:20.014  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:20.014  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-25 10:48:20.014  1031  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:20.015  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:20.017  1031  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-25 10:48:20.018  1031  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:20.020  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 10:48:20.020  1031  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 10:48:20.020  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:48:20.020  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 10:48:20.021  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 10:48:20.021  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 10:48:20.032  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 10:48:20.032  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 10:48:20.032  1031  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.033  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:20.033  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 10:48:20.034  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 10:48:20.034  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:20.036  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-25 10:48:20.036  1031  7220 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.037   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:48:20.062  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:20.063  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 10:48:20.063  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:20.063  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:20.063  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:20.063  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:20.064  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 10:48:20.064  1031  1545 D ConnectivityService: ignoring duplicate network state non-change
08-25 10:48:20.064  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-25 10:48:20.064  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-25 10:48:20.065  1031  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.065  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.065  1031  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d45941a
08-25 10:48:20.066  1031  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 10:48:20.067  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:20.067  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:20.067  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.067  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 10:48:20.070  1031  1537 D LGWifiP2pService: P2pDisablingState
08-25 10:48:20.070  1031  1537 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.070  1031  1537 D LGWifiP2pService: p2p socket connection lost
08-25 10:48:20.070  1031  1537 D LGWifiP2pService: P2pDisabledState
08-25 10:48:20.070  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:20.070  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:20.070  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:20.070  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-25 10:48:20.070  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:20.070  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:20.070  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:20.070  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 10:48:20.070  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-25 10:48:20.071  1031  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.071  1031  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.072  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 10:48:20.072  1943  1943 D WfdsService: WifiP2pState is changed : false
08-25 10:48:20.073  1031  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 10:48:20.,073  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 10:48:20.073  1031  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.073  1031  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.073  7144  7144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 10:48:20.074  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 10:48:20.074  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:20.074  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-25 10:48:20.076  1943  2307 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 10:48:20.076  1943  2307 D WfdsService: Set the WFDS Monitor: false
,08-25 10:48:20.085  7376  7376 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 10:48:20.088  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:20.088  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:20.088  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.089  1943  2307 D WfdsMonitor: WFDS Monitor is stopped
08-25 10:48:20.089  1943  2307 D WfdsService: STATE : WfdsDisabledState - enter
08-25 10:48:20.089  1943  7156 D CtrlSupplicant: Received on exit socket, terminate
08-25 10:48:20.089  1943  7156 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 10:48:20.089  1943  7156 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 10:48:20.089  1943  7156 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 10:48:20.089  1943  2312 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 10:48:20.090  1943  2307 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 10:48:20.108   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:48:20.108  1031  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 10:48:20.108  1031  1545 D DSQN    : disableDataServiceNotify
08-25 10:48:20.108  1031  1545 D DSQN    : stop dsqn bin
,08-25 10:48:20.119  1031  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 10:48:20.119  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:20.119  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:20.119  1031  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:20.119  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 10:48:20.120  1031  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 10:48:20.120  1031  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 10:48:20.120  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-25 10:48:20.121  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 10:48:20.122  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.122  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.122  1031  7219 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 10:48:20.137  7376  7376 I dex2oat : dex2oat took 52.192ms (threads: 4)
,08-25 10:48:20.147  7304  7324 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:20.147  7304  7324 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:20.147  7304  7324 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:20.147  7304  7324 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:20.147  7304  7324 I Adreno-EGL: Remote Branch: 
08-25 10:48:20.147  7304  7324 I Adreno-EGL: Local Patches: 
08-25 10:48:20.147  7304  7324 I Adreno-EGL: Reconstruct Branch: 
,08-25 10:48:20.227  7304  7324 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:20.227  7304  7324 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:20.227  7304  7324 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:20.227  7304  7324 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:20.227  7304  7324 I Adreno-EGL: Remote Branch: 
08-25 10:48:20.227  7304  7324 I Adreno-EGL: Local Patches: 
08-25 10:48:20.227  7304  7324 I Adreno-EGL: Reconstruct Branch: 
,08-25 10:48:20.242  1031  7220 D DhcpStateMachine: StoppedState
08-25 10:48:20.243  1031  7220 D DhcpStateMachine: StoppedState{ when=-168ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:20.288  1031  2012 I art     : Explicit concurrent mark sweep GC freed 104730(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.862ms total 178.063ms
,08-25 10:48:20.290  1031  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 10:48:20.291  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:20.291  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 10:48:20.291  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-25 10:48:20.292  1031  1539 D WifiNative-p2p0: TERMINATE: returned true
08-25 10:48:20.292  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:20.292  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:20.292  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 10:48:20.294  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 10:48:20.294  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:20.295  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.296  1031  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 10:48:20.296  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:20.296  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:20.297  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:20.297  1031  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:20.297  1031  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:20.297  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:20.297  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 10:48:20.297  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 10:48:20.297  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 10:48:20.297  1031  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 10:48:20.297  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 10:48:20.298  1031  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 10:48:20.298  1031  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 10:48:20.299  1031  1545 D NetworkManagementService: Removing idletimer
08-25 10:48:20.299  1031  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:20.299  1031  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-25 10:48:20.300  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 10:48:20.300  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 10:48:20.304  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:20.304  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:20.304  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:20.304  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:20.304  1031  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:20.304  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:20.304  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:20.305  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:20.305  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:20.305  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:20.306  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 10:48:20.306  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 10:48:20.306  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 10:48:20.306  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 10:48:20.308  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:20.308  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 10:48:20.309  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:20.309  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 10:48:20.324  7304  7324 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:20.324  7304  7324 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:20.324  7304  7324 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:20.324  7304  7324 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:20.324  7304  7324 I Adreno-EGL: Remote Branch: 
08-25 10:48:20.324  7304  7324 I Adreno-EGL: Local Patches: 
08-25 10:48:20.324  7304  7324 I Adreno-EGL: Reconstruct Branch: 
08-25 10:48:20.333  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-25 10:48:20.334  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.335  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.346  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 10:48:20.347  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.348  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.348  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.374   304  7392 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 10:48:20.374  1031  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 10:48:20.374  1817  7253 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-25 10:48:20.378  7144  7144 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 10:48:20.378  7144  7144 I wpa_supplicant: monitor socket send errors count : 1
08-25 10:48:20.378  7144  7144 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-25 10:48:20.378  1031  7155 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 10:48:20.379  1031  7155 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 10:48:20.383  1817  7253 I CheckinService: active receiver: disabled
,08-25 10:48:20.413  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 10:48:20.416  7144  7144 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 10:48:20.416  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 10:48:20.416  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 10:48:20.416  1031  7155 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 10:48:20.416  1031  7155 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 10:48:20.417  1031  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215287
08-25 10:48:20.417  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:20.417  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:20.417  7144  7144 W wpa_supplicant: USIM:  scard_deinit function
08-25 10:48:20.418  1031  1095 D Tethering: InitialState.processMessage what=4
08-25 10:48:20.418  1031  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215288
08-25 10:48:20.420  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=215290  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 10:48:20.421  1031  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=215291  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 10:48:20.415  6496  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 10:48:20.425  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 10:48:20.429  1031  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:20.429  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:20.442  2191  2191 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:20.449  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 10:48:20.449  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:20.449  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 10:48:20.449  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 10:48:20.451  7093  7093 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 10:48:20.454  7093  7093 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f5b721c
08-25 10:48:20.454  7093  7093 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 10:48:20.454  7093  7093 D AppUp4:CustFacade: isPhone : true
08-25 10:48:20.455  7093  7093 D AppUp4:CustModeStarterReceiver: begin check event
08-25 10:48:20.455  7093  7093 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 10:48:20.458  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:20.458  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:20.459  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:20.460  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:20.464  4354  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 10:48:20.467  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 10:48:20.468  4354  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:20.468  4354  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 10:48:20.479  7125  7403 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:48:20.493  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 10:48:20.493  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:20.493  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-25 10:48:20.496  6983  7405 W FormManager: Network not available. Please check & try again.
,08-25 10:48:20.496  7162  7162 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 10:48:20.497  7162  7162 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 10:48:20.498  7144  7144 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 10:48:20.500  1031  7155 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 10:48:20.500  1031  7155 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 10:48:20.500  1031  7155 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 10:48:20.500  1031  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-25 10:48:20.506  6983  7406 V FormManager: Network unavailable.
,08-25 10:48:20.508  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:20
08-25 10:48:20.510  6983  7406 V FormManager: Network unavailable.
08-25 10:48:20.514  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 10:48:20.514  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-25 10:48:20.514  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 10:48:20.514  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-25 10:48:20.514  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30babbfa
08-25 10:48:20.515  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 10:48:20.515  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 10:48:20.515  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 10:48:20.515  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 10:48:20.516  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:20
08-25 10:48:20.532  1031  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=397101537, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,08-25 10:48:20.551  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 10:48:20.551  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-25 10:48:20.551  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-25 10:48:20.551  6885  6885 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 10:48:20.552  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 10:48:20.553  6885  6885 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 10:48:20.553  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 10:48:20.553  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 10:48:20.553  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 10:48:20.553  6885  6885 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 10:48:20.553  6885  6885 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 10:48:20.566  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:20.574  2575  2575 D [Concierge]Service: onStartCommand(). Type : 9
08-25 10:48:20.578  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 10:48:20.582  6983  7409 W FormManager: Network not available. Please check & try again.
,08-25 10:48:20.586  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:20.594  6983  7410 V FormManager: Network unavailable.
08-25 10:48:20.602  6983  7410 V FormManager: Network unavailable.
,08-25 10:48:20.605  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-25 10:48:20.605  1943  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 10:48:20.605  1943  2307 D WfdsService: Set the WFDS Monitor: false
08-25 10:48:20.606  1943  2307 D WfdsMonitor: WFDS Monitor is stopped
08-25 10:48:20.606  1031  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 10:48:20.606  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:20.606  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:20.606  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 10:48:20.608  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 10:48:20.609  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:20.617  2501  2501 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:48:20.620  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 10:48:20.620  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 10:48:20.620  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 10:48:20.625  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:20.626  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:20.630  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:20.633  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 10:48:20.637  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:20.644  6983  7412 W FormManager: Network not available. Please check & try again.
,08-25 10:48:20.647  6983  7413 V FormManager: Network unavailable.
08-25 10:48:20.652  6983  7413 V FormManager: Network unavailable.
08-25 10:48:20.654  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 10:48:20.654  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:20.656  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 10:48:20.659  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 10:48:20.665  4354  7414 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 10:48:20.671  4354  7415 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 10:48:20.672  4354  7415 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 10:48:20.720  1031  1940 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7416 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 10:48:20.835  7416  7416 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 10:48:20.836  7416  7416 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 10:48:20.843  6698  7054 D UEI.SmartControl: Internal timer expired: 2
08-25 10:48:20.843  6698  7054 D UEI.SmartControl: unbind internal service
08-25 10:48:20.844  7416  7416 V [BNRBootReceiver]: Boot Receiver Return
08-25 10:48:20.847  7416  7416 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 10:48:20.849  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:20.859  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:20.868  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:20.890  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:20.891  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:20.895  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:20.903  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 10:48:20.911  6885  6885 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 10:48:20.921  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 10:48:20.927  6698  7048 D serial_port: close(fd = 24)
08-25 10:48:20.934  6698  7048 I UEI.SmartControl: Serial port is closed.
08-25 10:48:20.941  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:20.955  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:20.964  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:20.965  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:20.968  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:20.976  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:20.992  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.004  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.034  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.035  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:21.036  6943  6943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:21.043  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.055  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.068  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:21.080  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.081  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:21.082  6943  6943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:21.090  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.105  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.119  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:21.137  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.138  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:21.140  6943  6943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:21.149  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.162  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.174  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.184  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.185  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:21.186  6943  6943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:21.195  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.211  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.225  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.237  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 10:48:21.238  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:21.239  6943  6943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:21.254  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 10:48:21.275  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.286  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.298  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.299  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:21.302  6943  6943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:21.308  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.319  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.327  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.341  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.342  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:21.343  6943  6943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:21.348  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.353  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 10:48:21.367  1031  1544 D WifiService: New client listening to asynchronous messages
,08-25 10:48:21.368  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:21.373  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.384  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.396  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 10:48:21.397  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:21.399  6943  6943 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 10:48:21.402  6943  6943 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 10:48:21.403  6943  6943 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 10:48:21.412  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 10:48:21.424  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 10:48:21.427  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:21.432  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.443  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:21.459  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.460  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:21.462  6943  6943 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 10:48:21.464  6943  6943 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 10:48:21.465  6943  6943 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 10:48:21.473  1031  1977 I ActivityManager: Killing 6869:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-25 10:48:21.534  1031  1941 W libprocessgroup: failed to open /acct/uid_10037/pid_6869/cgroup.procs: No such file or directory
,08-25 10:48:21.540  2191  2191 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 10:48:21.560  2191  2191 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-25 10:48:21.561  2191  2191 D c       : Getting all permits...
08-25 10:48:21.561  2191  2191 D a       : Opening database...
08-25 10:48:21.566  2191  2191 D a       : Opening database auth.proximity.permit_store...
08-25 10:48:21.568  2191  2191 D a       : Closing database...
08-25 10:48:21.587  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 10:48:21.596  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 10:48:21.596  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 10:48:21.596  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:21.606  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.621  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:21.638  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.639  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:21.643  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:21.654  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.666  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 10:48:21.666  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-25 10:48:21.666  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:21.673  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:21.680  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:21.692  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.692  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:21.697  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:21.704  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:21.714  6914  6914 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 10:48:21.714  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 10:48:21.714  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:21.722  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:21.730  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:21.739  6943  6943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:21.739  6943  6943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 10:48:21.742  6943  6943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:21.753  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:21.762  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:48:21.769  6983  7441 W FormManager: Network not available. Please check & try again.
08-25 10:48:21.770  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.783  6983  7442 V FormManager: Network unavailable.
,08-25 10:48:21.789  6983  7442 V FormManager: Network unavailable.
08-25 10:48:21.799  2191  2191 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-25 10:48:21.824  6943  6943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-25 10:48:21.825  6943  6943 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3506
08-25 10:48:21.828  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=397101537 [*alarm*], flags=0x0
08-25 10:48:21.832  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 10:48:21.832  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:21.834  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:21.837  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 10:48:21.844  4354  7443 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 10:48:21.850  6914  6914 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 10:48:21.850  6914  6914 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 10:48:21.850  6914  6914 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:21.851  4354  7444 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 10:48:21.851  4354  7444 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 10:48:21.863  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:48:21.870  6983  7446 W FormManager: Network not available. Please check & try again.
08-25 10:48:21.874  6983  7447 V FormManager: Network unavailable.
08-25 10:48:21.875  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:21.883  6983  7447 V FormManager: Network unavailable.
,08-25 10:48:21.992  1031  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058880536] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 10:48:21.994  1031  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058880535] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 10:48:22.094  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:22.101  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-25 10:48:22.105  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:22.108  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:22.110  1031  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:22.113  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 10:48:22.115  6496  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 10:48:22.117  5797  5797 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 10:48:22.130  1031  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 10:48:22.139  2191  2191 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:22.147  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 10:48:22.147  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:22.147  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 10:48:22.147  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 10:48:22.149  7093  7093 I AppUp4:CustModeStarterReceiver: onReceive
08-25 10:48:22.153  7093  7093 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f5b721c
08-25 10:48:22.153  7093  7093 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 10:48:22.153  7093  7093 D AppUp4:CustFacade: isPhone : true
08-25 10:48:22.154  7093  7093 D AppUp4:CustModeStarterReceiver: begin check event
08-25 10:48:22.154  7093  7093 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 10:48:22.158  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:22.159  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 10:48:22.160  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:22.163  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:22.167  4354  7459 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 10:48:22.170  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 10:48:22.177  4354  7460 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:22.177  4354  7460 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 10:48:22.202  6983  7463 W FormManager: Network not available. Please check & try again.
08-25 10:48:22.202  7125  7461 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:48:22.208  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 10:48:22.208  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:22.209  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 10:48:22.209  3453  3453 D PhoneState: setPdpRejectCasuse : false
08-25 10:48:22.219  7162  7162 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 10:48:22.219  7162  7162 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 10:48:22.229  6983  7464 V FormManager: Network unavailable.
08-25 10:48:22.237  6983  7464 V FormManager: Network unavailable.
,08-25 10:48:22.247  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:22
08-25 10:48:22.250  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 10:48:22.250  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-25 10:48:22.254  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 10:48:22.255  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-25 10:48:22.255  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30babbfa
08-25 10:48:22.257  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 10:48:22.257  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 10:48:22.257  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 10:48:22.257  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-25 10:48:22.257  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:22
08-25 10:48:23.015  1031  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 10:48:23.022  1031  1904 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 10:48:23.043  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:23.044  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:23.044  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-25 10:48:23.044  1031  1095 D BluetoothManagerService: Message: 1
08-25 10:48:23.044  1031  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 10:48:23.070  1031  1095 D BluetoothManagerService: Message: 20
08-25 10:48:23.070  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@141db317:true
,08-25 10:48:23.074  7028  7028 D BluetoothAdapterState: make
08-25 10:48:23.078  7028  7028 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 10:48:23.079  7028  7028 I bluedroid-qcom: init
08-25 10:48:23.080  7028  7486 I BluetoothAdapterState: Entering OffState
08-25 10:48:23.080  7028  7028 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 10:48:23.081  7028  7028 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 10:48:23.081  7028  7028 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 10:48:23.081  7028  7028 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 10:48:23.081  7028  7028 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 10:48:23.083  7028  7028 I bluedroid-qcom: get_profile_interface socket
08-25 10:48:23.083  7028  7028 I bluedroid-qcom: get_profile_interface map_client
,08-25 10:48:23.087  7028  7490 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 10:48:23.080  7489  7489 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:23.092  7028  7490 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 10:48:23.080  7489  7489 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:23.103  7489  7489 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 10:48:23.103  7489  7489 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 10:48:23.103  7489  7489 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-25 10:48:23.108  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 10:48:23.108  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 10:48:23.108  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 10:48:23.108  1031  1095 D BluetoothManagerService: Message: 40
08-25 10:48:23.109  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 10:48:23.109  7028  7044 I bluedroid-qcom: config_hci_snoop_log
08-25 10:48:23.111  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 10:48:23.111  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 10:48:23.112  7489  7489 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 10:48:23.119  7028  7486 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-25 10:48:23.123  7489  7489 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 10:48:23.123  7489  7489 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 10:48:23.124  7028  7490 D BluetoothAdapterProperties: Name is: G3
08-25 10:48:23.125  7028  7486 D BluetoothAdapterProperties: Setting state to 11
08-25 10:48:23.125  7028  7486 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 10:48:23.126  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:23.126  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 10:48:23.126  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 10:48:23.127  7028  7486 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 10:48:23.134  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:48:23.137  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 10:48:23.140  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:23.141  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:23.144  6885  6885 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 10:48:23.151  7028  7028 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 10:48:23.152  7028  7028 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:23.153  7028  7028 V BluetoothPbapReceiver: ***********state = 11
,08-25 10:48:23.164  7028  7486 D BluetoothBondStateMachine: make
,08-25 10:48:23.173  7028  7486 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
,08-25 10:48:23.173  7028  7486 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 10:48:23.173  7028  7486 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
,08-25 10:48:23.174  7028  7486 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 10:48:23.175  7028  7486 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-25 10:48:23.184  7028  7492 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 10:48:23.186  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:48:23.191  7028  7486 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:23.251  1031  1940 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7509 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 10:48:23.265  7028  7028 D HeadsetService: Received start request. Starting profile...
08-25 10:48:23.267  7028  7028 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 10:48:23.267  7028  7028 D LGBluetoothHfpAdapter: Version 1.6
,08-25 10:48:23.270  7028  7486 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:23.271  7028  7028 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 10:48:23.272  7028  7028 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 10:48:23.273  7028  7028 D HeadsetStateMachine: make
08-25 10:48:23.277  7028  7486 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 10:48:23.284  7028  7486 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:23.291  7028  7486 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:23.292  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:23.297  1031  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.297  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-25 10:48:23.299  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.302  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:23.306  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 10:48:23.307  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:48:23.307  1031  1095 D Tethering: MasterInitialState.processMessage what=3
08-25 10:48:23.311  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:23.314  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:23.316  7028  7028 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:23.317  7028  7028 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 10:48:23.318  7028  7486 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 10:48:23.322  1031  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.322  1031  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:23.322  1031  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:23.323  7028  7028 D HeadsetStateMachine: max_hf_connections = 1
08-25 10:48:23.323  7028  7028 I bluedroid-qcom: get_profile_interface handsfree
08-25 10:48:23.325  5797  5797 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 10:48:23.326  7028  7028 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 10:48:23.326   308  1384 V AudioPolicyService: registerClient() client 0xb57f87e0, uid 1002
08-25 10:48:23.327   308   308 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 10:48:23.327   308   308 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 10:48:23.327   308   308 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 10:48:23.327  7028  7486 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:23.327  7028  7028 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 10:48:23.328   308  1749 V AudioFlinger: registerClient() client 0xb55815f8, pid 7028
08-25 10:48:23.328   308  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:23.328   308  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:23.328  7028  7028 V ToneGenerator: Create Track: 0xb4928080
08-25 10:48:23.328  7028  7028 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 10:48:23.328  7028  7028 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 10:48:23.329  1031  1811 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:23.329  1031  1811 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:23.329  7028  7043 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:23.329  7028  7043 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 10:48:23.329   308  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:23.329   308  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:23.329  1031  1942 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:23.329  1031  1942 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:23.329   308  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 10:48:23.329   308  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 10:48:23.329  1853  4009 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:23.329   308  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 10:48:23.329  1853  4009 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:23.329   308  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 10:48:23.329  1853  4009 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:23.329  1853  4009 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:23.329  7028  7028 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 10:48:23.329  3453  3472 V AudioSystem: ioConfigChanged() event 0, ioHandle 4,
08-25 10:48:23.329  3453  3472 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:23.329  3453  3472 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:23.329  3453  3472 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:23.329  7028  7043 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:23.329  7028  7043 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 10:48:23.330   308  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 10:48:23.330   308  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 10:48:23.330   308  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 10:48:23.330  1603  3105 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:23.330   308  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 10:48:23.330  1603  3105 V AudioSystem: ioConfigChanged() opening already existing output! 4,
,08-25 10:48:23.330   308  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 10:48:23.330  1603  3105 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:23.330  7028  7028 V AudioSystem: getLatency() output 2, latency 50
08-25 10:48:23.330  1603  3105 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:23.330  7028  7028 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 10:48:23.330  7028  7028 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 10:48:23.331   308  1749 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 10:48:23.331   308  1749 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 10:48:23.331   308  1749 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 10:48:23.331   308  1749 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 10:48:23.331   308  1749 V AudioFlinger: createTrack() lSessionId: 22
08-25 10:48:23.332  6496  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 10:48:23.333  7028  7028 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 10:48:23.333   308   308 V AudioFlinger: acquiring 22 from 7028, for 7028
08-25 10:48:23.333   308   308 V AudioFlinger:  added new entry for 22
08-25 10:48:23.333  7028  7028 V ToneGenerator: ToneGenerator INIT OK, time: 218217
08-25 10:48:23.333  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.334  7028  7525 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 10:48:23.334  7028  7525 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 10:48:23.334  7028  7525 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 10:48:23.335  7028  7525 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 10:48:23.335   308  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7028
08-25 10:48:23.335   308  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 10:48:23.335   308  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 10:48:23.335   308  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 10:48:23.336   308  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 10:48:23.336   308  1384 V voice   : voice_set_parameters: exit with code(0)
08-25 10:48:23.336   308  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 10:48:23.336   308  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 10:48:23.336   308  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 10:48:23.336   308  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 10:48:23.336   308  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 10:48:23.336   308  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 10:48:23.336  7028  7525 V ToneGenerator: ToneGenerator destructor
08-25 10:48:23.336  7028  7525 V ToneGenerator: stopTone
08-25 10:48:23.336  7028  7525 V ToneGenerator: Delete Track: 0xb4928080
08-25 10:48:23.336  7028  7525 V AudioTrack: ~AudioTrack, releasing session id from 7028 on behalf of 7028
08-25 10:48:23.336   308  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 10:48:23.336   308  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 10:48:23.336   308   308 V AudioFlinger: releasing 22 from 7028 for 7028
,08-25 10:48:23.336   308   308 V AudioFlinger:  decremented refcount to 0
08-25 10:48:23.336   308   308 V AudioFlinger: purging stale effects
08-25 10:48:23.336   308  1104 V AudioPolicyService: AudioCommandThread() waking up
08-25 10:48:23.336   308  1104 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 10:48:23.336   308  1104 V AudioPolicyManager: releaseOutput() 2
08-25 10:48:23.337   308  1104 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 10:48:23.337   308  1383 V AudioFlinger: PlaybackThread::Track destructor
08-25 10:48:23.337   308  1383 V AudioFlinger: removeClient_l() pid 7028, calling pid 308
08-25 10:48:23.339  5797  5797 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 10:48:23.343  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.344  1031  2012 W Process : Unable to open /proc/7529/status
08-25 10:48:23.346  7028  7486 V LGMDMManager: Create singleton instance
,08-25 10:48:23.347  7028  7028 D A2dpService: Received start request. Starting profile...
08-25 10:48:23.348  7028  7028 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 10:48:23.349  7028  7028 V Avrcp   : make
08-25 10:48:23.350  7028  7028 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 10:48:23.350  7028  7028 I bluedroid-qcom: get_profile_interface avrcp
08-25 10:48:23.352  7028  7486 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 10:48:23.360  7028  7028 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 10:48:23.362  7028  7028 E AudioManager: No RCC entry present to update
,08-25 10:48:23.362  7028  7028 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 10:48:23.365  7028  7028 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 10:48:23.365  2191  2191 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.366  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 10:48:23.366  7028  7028 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 10:48:23.374  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 10:48:23.374  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.374  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 10:48:23.375  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 10:48:23.375  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 10:48:23.376  7093  7093 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 10:48:23.397  7093  7093 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f5b721c
08-25 10:48:23.397  7093  7093 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 10:48:23.397  7093  7093 D AppUp4:CustFacade: isPhone : true
08-25 10:48:23.413  7093  7093 D AppUp4:CustModeStarterReceiver: begin check event
,08-25 10:48:23.413  7093  7093 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 10:48:23.416  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.416  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:23.417  7509  7509 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 10:48:23.418  7509  7509 W LG Account v2.2: No ProfileInfo entries
08-25 10:48:23.418  7509  7509 I LG Account v2.2: isEnabled: false
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]Country: EU
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]Operator: OPEN
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]Ranking support: false
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]Comfort support: false
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]Accessory: true
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]Health device: true
08-25 10:48:23.418  7509  7509 I Feature : [Lifetracker]Extra Pedometer: false
08-25 10:48:23.419  7509  7509 I Feature : [Lifetracker]Blood glucose device: false
08-25 10:48:23.419  7509  7509 I Feature : [Lifetracker]Device Number: 3
08-25 10:48:23.420  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:23.431  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 10:48:23.435  6885  6885 D BluetoothPermissionRequest: onReceive
08-25 10:48:23.439  4354  7534 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 10:48:23.440  4354  7535 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.440  4354  7535 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 10:48:23.447  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 10:48:23.449  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 10:48:23.471  1031  1047 V SIM_STK : Menu title from STK is T-Mobile
,08-25 10:48:23.471  1031  1047 V SIM_STK : Menu title from STK is T-Mobile
08-25 10:48:23.473  6983  7538 W FormManager: Network not available. Please check & try again.
08-25 10:48:23.478  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 10:48:23.478  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.479  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 10:48:23.481  7125  7536 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:23.485  7162  7162 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 10:48:23.486  7162  7162 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 10:48:23.495  6983  7539 V FormManager: Network unavailable.
,08-25 10:48:23.498  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:23
,08-25 10:48:23.500  6983  7539 V FormManager: Network unavailable.
08-25 10:48:23.501  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 10:48:23.501  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
08-25 10:48:23.501  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 10:48:23.501  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-25 10:48:23.501  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30babbfa
08-25 10:48:23.502  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 10:48:23.502  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 10:48:23.502  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 10:48:23.502  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 10:48:23.502  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:23
08-25 10:48:23.528  6496  6496 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 10:48:23.533  6496  6913 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 10:48:23.549  2191  2191 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:48:23.557  1031  2012 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 10:48:23.560  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 10:48:23.560  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.560  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 10:48:23.560  7093  7093 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 10:48:23.562  7093  7093 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 10:48:23.565  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 10:48:23.568  7093  7093 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f5b721c
08-25 10:48:23.568  7093  7093 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 10:48:23.568  7093  7093 D AppUp4:CustFacade: isPhone : true
08-25 10:48:23.568  7093  7093 D AppUp4:CustModeStarterReceiver: begin check event
08-25 10:48:23.568  7093  7093 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 10:48:23.569  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 10:48:23.569  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 10:48:23.570  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 10:48:23.570  7028  7028 I BluetoothA2dpServiceJni: classInitNative
08-25 10:48:23.570  7028  7028 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 10:48:23.570  7028  7028 D A2dpStateMachine: make
08-25 10:48:23.572  7028  7028 I bluedroid-qcom: get_profile_interface a2dp
08-25 10:48:23.572  7028  7542 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 10:48:23.573  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.573  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:23.574  7028  7028 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 10:48:23.574  7028  7028 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-25 10:48:23.575  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
,08-25 10:48:23.575  7028  7541 D A2dpStateMachine: Enter Disconnected: -2
08-25 10:48:23.575  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:23.575  7028  7028 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 10:48:23.577  7028  7028 D HidService: Received start request. Starting profile...
08-25 10:48:23.577  7028  7028 I bluedroid-qcom: get_profile_interface hidhost
08-25 10:48:23.577  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.578  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:23.578  7028  7028 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 10:48:23.579  7028  7028 D HealthService: Received start request. Starting profile...
08-25 10:48:23.581  7028  7028 I bluedroid-qcom: get_profile_interface health
08-25 10:48:23.581  7028  7028 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 10:48:23.581  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.581  7028  7028 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 10:48:23.583  7028  7028 D PanService: Received start request. Starting profile...
08-25 10:48:23.583  7028  7028 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 10:48:23.583  7028  7028 I bluedroid-qcom: get_profile_interface pan
08-25 10:48:23.584  7125  7125 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 10:48:23.586  4354  7546 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 10:48:23.588  7028  7028 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 10:48:23.588  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.588  7028  7028 D HeadsetStateMachine: Proxy object connected
08-25 10:48:23.589  7028  7028 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 10:48:23.589  7028  7028 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-25 10:48:23.591  4354  7548 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.591  4354  7548 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 10:48:23.593  7028  7028 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 10:48:23.598  7028  7028 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 10:48:23.598  7028  7028 D BtGatt.GattService: Received start request. Starting profile...
08-25 10:48:23.598  7028  7028 D BtGatt.GattService: start()
08-25 10:48:23.598  7028  7028 I bluedroid-qcom: get_profile_interface gatt
08-25 10:48:23.599  7028  7028 D BtGatt.AdvertiseManager: advertise manager created
08-25 10:48:23.607  7125  7549 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:48:23.607  6983  7551 W FormManager: Network not available. Please check & try again.
08-25 10:48:23.608  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.610  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.610  7028  7028 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 10:48:23.611  7028  7028 V BluetoothMapService: BluetoothMapBinder()
08-25 10:48:23.611  7028  7028 D BluetoothMapService: Received start request. Starting profile...
08-25 10:48:23.612  7028  7028 D BluetoothMapService: start()
08-25 10:48:23.615  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 10:48:23.615  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:23.615  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 10:48:23.616  6983  7553 V FormManager: Network unavailable.
08-25 10:48:23.616  7028  7028 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 10:48:23.617  7028  7028 D BluetoothMapEmailAppObserver: createReceiver()
08-25 10:48:23.618  7162  7162 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 10:48:23.619  7162  7162 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 10:48:23.619  7028  7028 D BluetoothMapEmailAppObserver: initObservers()
08-25 10:48:23.619  7028  7028 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 10:48:23.622  6983  7553 V FormManager: Network unavailable.
08-25 10:48:23.627  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:23
08-25 10:48:23.628  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:23.629  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 10:48:23.629  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 10:48:23.631  7028  7028 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:23.631  7028  7525 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 10:48:23.632  7028  7525 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 10:48:23.632  7028  7525 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 10:48:23.633  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 10:48:23.633  7221  7221 D WeatherAncestor: connectivity changed - connection : true
08-25 10:48:23.633  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30babbfa
08-25 10:48:23.634  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 10:48:23.634  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 10:48:23.634  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 10:48:23.634  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 10:48:23.634  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:48:23
08-25 10:48:23.636  7028  7028 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:23.639  7028  7028 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:23.642  7028  7028 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:23.642  7028  7028 V PanService: [BTUI] SIM Extra State :ABSENT
,08-25 10:48:23.645  7028  7028 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:23.648  7028  7028 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 10:48:23.649  7028  7028 V BluetoothMapService: Handler(): got msg=1
08-25 10:48:23.649  7028  7486 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 10:48:23.649  7028  7486 I bluedroid-qcom: enable
08-25 10:48:23.650  7028  7486 I bt_hci_bdroid: init
08-25 10:48:23.651  7028  7028 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:23.651  7028  7486 I bt_vendor: bt-vendor : init
08-25 10:48:23.651  7028  7486 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 10:48:23.651  7028  7486 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 10:48:23.651  7028  7486 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 10:48:23.651  7028  7486 D bt_userial_mct: userial_init
08-25 10:48:23.652  7028  7556 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 10:48:23.652  7028  7486 D bt_hci_bdroid: set_power 1
08-25 10:48:23.652  7028  7486 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 10:48:23.652  7028  7486 I bt_vendor: Starting hciattach daemon
08-25 10:48:23.652  7028  7486 I bt_vendor: try to set true
08-25 10:48:23.653  7028  7028 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:23.640  7559  7559 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:23.640  7559  7559 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:23.653  7028  7028 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:23.653  7028  7028 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:23.653  7028  7028 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:23.653  7028  7028 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 10:48:23.652  7028  7556 I bt-btu  : btu_task pending for preload complete event
,08-25 10:48:23.673  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 10:48:23.772  7566  7566 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 10:48:23.787  7567  7567 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 10:48:23.831  7569  7569 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 10:48:23.847  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 10:48:23.861  7571  7571 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 10:48:23.879  7572  7572 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 10:48:23.903  7574  7574 I libmdmdetect: ESOC framework not supported
,08-25 10:48:23.906  7574  7574 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 10:48:23.918  7574  7574 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 10:48:23.918  7574  7574 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 10:48:23.918  7574  7574 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 10:48:23.918  7574  7574 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 10:48:23.918  7574  7574 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-25 10:48:23.918  7574  7574 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 10:48:23.918  7574  7574 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 10:48:23.968  7574  7575 E QC-QMI  : qmi_client [7574] 14: failed to locate client data
,08-25 10:48:23.969   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 10:48:23.969   444   444 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-25 10:48:24.003  7582  7582 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 10:48:24.023  7583  7583 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 10:48:24.058  7028  7486 I bt_vendor: bluetooth satus is on
08-25 10:48:24.058  7028  7486 D bt_hci_bdroid: preload
08-25 10:48:24.058  7028  7558 D bt_userial_mct: userial_open(port:0)
08-25 10:48:24.058  7028  7558 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 10:48:24.062  7028  7558 I bt_vendor: Done intiailizing UART
,08-25 10:48:24.066  7028  7558 I bt_vendor: Done intiailizing UART
,08-25 10:48:24.066  7028  7558 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 10:48:24.067  7028  7558 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 10:48:24.067  7028  7585 D bt_userial_mct: Entering userial_read_thread()
08-25 10:48:24.067  7028  7556 I bt-btu  : btu_task received preload complete event
08-25 10:48:24.067  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 10:48:24.067  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 10:48:24.072  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 10:48:24.079  7028  7556 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 10:48:24.079  7028  7556 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 10:48:24.079  7028  7556 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 10:48:24.079  7028  7556 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 10:48:24.080  7028  7556 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 10:48:24.146  7028  7556 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 10:48:24.146  7028  7556 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0179061 
08-25 10:48:24.146  7028  7556 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0179061 
,08-25 10:48:24.196  7028  7490 E bt-btif : Calling BTA_HhEnable
,08-25 10:48:24.197  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 10:48:24.197  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 10:48:24.197  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 10:48:24.198  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 10:48:24.198  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 10:48:24.199  7028  7490 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 10:48:24.200  7028  7490 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 10:48:24.202  7028  7490 D BluetoothAdapterProperties: Name is: G3
08-25 10:48:24.204  7028  7490 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:48:24.204  7028  7490 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 10:48:24.205  7028  7490 D bt_hci_bdroid: postload
08-25 10:48:24.207  7028  7558 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:24.208  7028  7556 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 10:48:24.209  7028  7490 D bte_conf: Device ID record 1 : primary
08-25 10:48:24.209  7028  7490 D bte_conf:   vendorId            = 00c4
08-25 10:48:24.209  7028  7490 D bte_conf:   vendorIdSource      = 0001
08-25 10:48:24.209  7028  7490 D bte_conf:   product             = 13a1
08-25 10:48:24.209  7028  7490 D bte_conf:   version             = 1000
08-25 10:48:24.209  7028  7490 D bte_conf:   clientExecutableURL = 
08-25 10:48:24.209  7028  7490 D bte_conf:   serviceDescription  = 
08-25 10:48:24.209  7028  7490 D bte_conf:   documentationURL    = 
08-25 10:48:24.209  7028  7490 D bte_conf: bte_load_did_conf no section named DID2.
08-25 10:48:24.211  7028  7558 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:24.213  7028  7558 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:24.213  7028  7558 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:24.214  7028  7486 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 10:48:24.214  7028  7486 D BluetoothAdapterProperties: ScanMode =  20
08-25 10:48:24.214  7028  7486 D BluetoothAdapterProperties: State =  11
08-25 10:48:24.215  7028  7486 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 10:48:24.215  7028  7486 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 10:48:24.215  7028  7486 D BluetoothAdapterProperties: Setting state to 12
08-25 10:48:24.215  7028  7486 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 10:48:24.200  7587  7587 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:24.200  7587  7587 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:24.217  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:24.217  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 10:48:24.217  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 10:48:24.218  7028  7486 I BluetoothAdapterState: Entering On State
08-25 10:48:24.222  7028  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:24.222  7028  7556 W bt-smp  : Plain text(LSB ~ MSB) = dc df 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:24.222  7028  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = 5a b1 5e 28 49 99 0b fd d7 da e2 83 53 96 24 8c 
08-25 10:48:24.222  7028  7556 W bt-btm  : Stopping oneshot timer
08-25 10:48:24.222  7028  7558 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:24.223  7028  7585 E bt_mct  : hci lib postload completed
08-25 10:48:24.224  7028  7486 D LGBluetoothServiceAd,apter: [BTUI] OnState
08-25 10:48:24.224  7028  7486 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 10:48:24.224  7028  7486 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 10:48:24.225  7028  7486 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-25 10:48:24.226  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:24.233  7028  7490 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 10:48:24.234  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 10:48:24.234  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:24.236  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 10:48:24.236  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:24.237  7028  7490 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 10:48:24.238  1031  1031 D BluetoothHeadset: Proxy object connected
08-25 10:48:24.240  6885  7017 D BluetoothMap: onBluetoothStateChange: up=true
08-25 10:48:24.243  7028  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:24.243  7028  7556 W bt-smp  : Plain text(LSB ~ MSB) = f3 aa 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:24.243  7028  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = 36 21 49 33 99 67 8b 51 fb 35 47 0c d2 f0 81 90 
08-25 10:48:24.243  7028  7556 W bt-btm  : Stopping oneshot timer
,08-25 10:48:24.249  6885  7017 D BluetoothPan: onBluetoothStateChange on: true
08-25 10:48:24.250  6885  7017 D BluetoothPan: onBluetoothStateChange call bindService
08-25 10:48:24.253  7028  7490 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 10:48:24.253  7028  7490 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 10:48:24.256  1853  4008 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:24.257  7028  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-25 10:48:24.257  7028  7556 W bt-smp  : Plain text(LSB ~ MSB) = 7d b9 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:24.257  7028  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 8a eb cc 29 91 c1 e9 74 c9 55 b9 a2 ea 5e 95 
08-25 10:48:24.257  7028  7556 W bt-btm  : Stopping oneshot timer
08-25 10:48:24.260  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 10:48:24.261  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 10:48:24.263  6885  6901 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 10:48:24.264  1031  1031 D BluetoothA2dp: Proxy object connected
,08-25 10:48:24.267  7028  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:24.267  7028  7556 W bt-smp  : Plain text(LSB ~ MSB) = e1 cc 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:24.267  7028  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = 5f 48 62 c3 36 2c e0 a4 3b 10 cb 3f 9e ac 8b e7 
08-25 10:48:24.267  7028  7556 W bt-btm  : Stopping oneshot timer
08-25 10:48:24.268  7028  7486 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 10:48:24.272  6885  7017 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 10:48:24.277  6885  6885 D BluetoothMap: Proxy object connected
08-25 10:48:24.277  6885  6885 D MapProfile: Bluetooth service connected
08-25 10:48:24.277  6885  6885 D BluetoothMap: getConnectedDevices()
,08-25 10:48:24.280  7028  7556 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:24.280  7028  7556 W bt-smp  : Plain text(LSB ~ MSB) = 80 6c 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:24.280  7028  7556 W bt-smp  : Encrypted text(LSB ~ MSB) = b7 45 d0 b7 64 88 32 93 04 db 2a d7 16 a1 69 d9 
08-25 10:48:24.280  7028  7556 W bt-btm  : Stopping oneshot timer
08-25 10:48:24.282  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 10:48:24.282  1031  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 10:48:24.283  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 10:48:24.283  1031  1095 D BluetoothManagerService: Message: 40
08-25 10:48:24.283  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 10:48:24.284  7028  7491 V BluetoothMapService: getConnectedDevices()
08-25 10:48:24.286  6885  6885 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:48:24.286  6885  6885 D PanProfile: Bluetooth service connected
08-25 10:48:24.288  6885  6885 D BluetoothInputDevice: Proxy object connected
08-25 10:48:24.288  6885  6885 D HidProfile: Bluetooth service connected
,08-25 10:48:24.299  7594  7594 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 10:48:24.318  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 10:48:24.318  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-25 10:48:24.327  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:24.327  1943  2127 D LGBluetoothAPIService: Message: 1
08-25 10:48:24.328  1943  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 10:48:24.330  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:24.334  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:24.338  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:24.341  7028  7028 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:24.341  7028  7028 D BluetoothMapService: STATE_ON
08-25 10:48:24.341  6885  6885 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 10:48:24.344  1031  1095 D BluetoothManagerService: Message: 30
08-25 10:48:24.344  1943  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:24.345  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:24.347  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:24.350  6778  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 10:48:24.353  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:24.354  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:24.354  6885  6885 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 10:48:24.358  1031  1095 D BluetoothManagerService: Message: 30
08-25 10:48:24.359  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:24.359  7028  7028 V BluetoothPbapService: Pbap Service onCreate
08-25 10:48:24.359  7028  7028 V BluetoothPbapService: Starting PBAP service
08-25 10:48:24.361  7028  7028 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 10:48:24.361  7028  7028 V BluetoothPbapService: Pbap Service onBind
08-25 10:48:24.362  7028  7028 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:24.362  7028  7028 V BluetoothPbapService: state: 12
08-25 10:48:24.362  7028  7028 V BluetoothMapService: Handler(): got msg=1
08-25 10:48:24.363  7028  7028 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 10:48:24.364  7028  7606 D BluetoothMapMasInstance: MAS initSocket()
08-25 10:48:24.364  6885  6885 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 10:48:24.365  7028  7606 D BluetoothMapMasInstance:   masId = 00
08-25 10:48:24.365  7028  7606 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 10:48:24.365  7028  7606 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 10:48:24.365  7028  7606 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 10:48:24.365  7028  7028 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 10:48:24.365  7028  7028 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 10:48:24.366  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:24.366  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 10:48:24.366  1943  2127 D LGBluetoothAPIService: Message: 100
08-25 10:48:24.366  1943  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 10:48:24.367  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 10:48:24.368  7028  7606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:24.368  7028  7028 V BluetoothPbapService: Handler(): got msg=1
,08-25 10:48:24.371  7028  7606 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 10:48:24.372  7028  7606 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 10:48:24.372  7028  7606 D BluetoothMapMasInstance: Accepting socket connection...
08-25 10:48:24.372  7028  7028 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 10:48:24.372  7028  7490 D BluetoothAdapterProperties: Scan Mode:21
08-25 10:48:24.372  6885  6885 D BluetoothA2dp: Proxy object connected
08-25 10:48:24.373  7028  7028 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 10:48:24.373  7028  7028 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:24.373  7028  7490 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 10:48:24.373  7028  7028 V BluetoothPbapReceiver: ***********state = 12
08-25 10:48:24.373  6885  6885 D A2dpProfile: Bluetooth service connected
08-25 10:48:24.373  7028  7607 V BluetoothPbapService: Pbap Service initSocket
08-25 10:48:24.374  1031  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:24.375  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:24.376  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:24.378  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:48:24.378  7028  7607 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:24.379  2191  2191 D c       : Getting all permits...
08-25 10:48:24.379  2191  2191 D a       : Opening database...
08-25 10:48:24.379  6885  6885 D BluetoothHeadset: Proxy object connected
,08-25 10:48:24.380  6885  6885 D HeadsetProfile: Bluetooth service connected
,08-25 10:48:24.382  7028  7607 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 10:48:24.382  7028  7607 V BluetoothPbapService: Succeed to create listening socket 
08-25 10:48:24.382  7028  7607 V BluetoothPbapService: Accepting socket connection...
08-25 10:48:24.383  6885  6885 D BluetoothPbap: Proxy object connected
08-25 10:48:24.384  6885  6885 D PbapServerProfile: Bluetooth service connected
08-25 10:48:24.385  2191  2191 D a       : Opening database auth.proximity.permit_store...
08-25 10:48:24.386  2191  2191 D a       : Closing database...
08-25 10:48:24.390  6885  6885 D DockEventReceiver: finishStartingService: stopping service
08-25 10:48:24.396  6885  6885 D BluetoothPermissionRequest: onReceive
,08-25 10:48:24.398  6885  6885 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 10:48:24.400  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 10:48:24.403  7028  7028 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 10:48:24.404  7028  7028 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 10:48:24.411  7028  7028 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 10:48:24.421  7259  7299 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-25 10:48:24.430  7028  7028 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 10:48:24.430  7028  7028 V BtOppService: onCreate
,08-25 10:48:24.433  7028  7028 V BluetoothOppNotification: send message
08-25 10:48:24.436  7028  7028 V BtOppService: Starting RfcommListener
08-25 10:48:24.441  7028  7028 D BluetoothOppPreference: Dumping Names:  
08-25 10:48:24.441  7028  7028 D BluetoothOppPreference: {}
08-25 10:48:24.441  7028  7028 D BluetoothOppPreference: Dumping Channels:  
08-25 10:48:24.441  7028  7028 D BluetoothOppPreference: {}
08-25 10:48:24.442  7028  7028 V BtOppService: onStartCommand
08-25 10:48:24.446  7028  7028 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:48:24.446  7028  7028 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 10:48:24.446  7028  7616 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 10:48:24.449  7028  7028 V BluetoothOppNotification: new notify threadi!
08-25 10:48:24.451  7028  7028 V BluetoothOppNotification: send delay message
08-25 10:48:24.455  7028  7028 V BtOppService: start RfcommListener
08-25 10:48:24.455  7028  7613 V BtOppService: Deleted complete outbound shares, number =  0
08-25 10:48:24.456  7028  7616 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 10:48:24.457  7028  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 10:48:24.458  7028  7028 V BtOppService: RfcommListener started
08-25 10:48:24.459  7028  7613 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-25 10:48:24.459  7028  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e781057 on behalf of 
08-25 10:48:24.460  7028  7613 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 10:48:24.460  7028  7617 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 10:48:24.461  7028  7616 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2863a744 on behalf of 
08-25 10:48:24.462  7028  7613 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31fd202d on behalf of 
08-25 10:48:24.464  7028  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 10:48:24.464  7028  7618 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 10:48:24.464  1031  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:24.465  7028  7618 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:48:24.466  7028  7618 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-25 10:48:24.466  7028  7618 V BtOppRfcommListener: Started RFCOMM listener....
08-25 10:48:24.466  7028  7618 I BtOppRfcommListener: Accept thread started.
08-25 10:48:24.466  7028  7618 V BtOppRfcommListener: Accepting connection...
08-25 10:48:24.467  7028  7616 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 10:48:24.468  7028  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38629962 on behalf of 
08-25 10:48:24.469  7028  7617 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 10:48:24.470  7028  7617 V BluetoothOppNotification: outbound notification was removed.
08-25 10:48:24.470  7028  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 10:48:24.472  7028  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10835af3 on behalf of 
08-25 10:48:24.473  7028  7617 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 10:48:24.474  7028  7617 V BluetoothOppNotification: inbound notification was removed.
08-25 10:48:24.474  7028  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 10:48:24.476  7028  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1895f3b0 on behalf of 
08-25 10:48:24.477  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:24.477  7028  7028 V BluetoothFtpService: Ftp Service onCreate
08-25 10:48:24.477  7028  7028 I BluetoothFtpService: Ftp Service onCreate
08-25 10:48:24.478  7028  7028 V BluetoothFtpService: Ftp Service onStartCommand
08-25 10:48:24.478  7028  7028 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:24.478  7028  7028 V BluetoothFtpService: Starting Listening on sockets
08-25 10:48:24.479  7028  7028 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:24.479  7028  7028 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:24.479  7028  7028 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:24.479  7028  7028 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:24.479  7028  7028 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 10:48:24.479  7028  7028 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 10:48:24.481  7028  7028 V BtOppService: ContentObserver received notification
08-25 10:48:24.481  7028  7028 V BtOppService: ContentObserver received notification
08-25 10:48:24.481  7028  7028 V BluetoothFtpService: Handler(): got msg=1
08-25 10:48:24.482  7028  7028 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 10:48:24.483  7028  7028 V BluetoothFtpService: Ftp Service initSocket
08-25 10:48:24.487  7028  7619 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 10:48:24.488  7028  7619 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 10:48:24.488  1031  1643 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:24.490  7028  7028 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:48:24.491  7028  7619 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3354e9ae on behalf of 
08-25 10:48:24.491  7028  7028 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-25 10:48:24.491  7028  7028 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 10:48:24.494  7028  7620 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 10:48:24.495  7028  7619 V BluetoothOppNotification: update too frequent, put in queue
08-25 10:48:24.496  7028  7619 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 10:48:24.511  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:24.512  7028  7028 V BluetoothSapService: Sap Service onCreate
,08-25 10:48:24.514  7028  7028 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:24.514  7028  7028 V BluetoothSapService: state: 12
08-25 10:48:24.514  7028  7028 V BluetoothSapService: Starting SAP server process
08-25 10:48:24.516  7028  7028 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 10:48:24.517  7028  7622 V BluetoothSapService: Sap Service initRfcommSocket
08-25 10:48:24.510  7621  7621 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:24.518  1031  1811 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:24.510  7621  7621 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:24.518  7028  7622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:24.519  7028  7622 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-25 10:48:24.519  7028  7622 V BluetoothSapService: Succeed to create listening socket 
08-25 10:48:24.519  7028  7622 V BluetoothSapService: Accepting socket connection...
08-25 10:48:24.541  7621  7621 V BT_SAP  : Event pipe created
08-25 10:48:24.541  7621  7621 V BT_SAP  : create_server_socket qcom.sap.server
08-25 10:48:24.541  7621  7621 V BT_SAP  : created socket fd 6
,08-25 10:48:25.074  1031  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:25.075  1031  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:25.297  1031  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 10:48:25.298  1031  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 10:48:25.384  1031  1590 I ActivityManager: Killing 7416:com.lge.bnr/1000 (adj 15): empty #17
,08-25 10:48:25.421  1031  1941 W libprocessgroup: failed to open /acct/uid_1000/pid_7416/cgroup.procs: No such file or directory
,08-25 10:48:25.432  1031  1047 I ActivityManager: Killing 6698:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-25 10:48:25.450  6943  6943 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-25 10:48:25.450  6943  6943 W System.err: android.os.DeadObjectException
08-25 10:48:25.450  6943  6943 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 10:48:25.450  6943  6943 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 10:48:25.451  6943  6943 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 10:48:25.451  6943  6943 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 10:48:25.451  6943  6943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 10:48:25.451  6943  6943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 10:48:25.451  6943  6943 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 10:48:25.451  6943  6943 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 10:48:25.451  6943  6943 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 10:48:25.451  6943  6943 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 10:48:25.451  6943  6943 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:48:25.451  6943  6943 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:48:25.451  6943  6943 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 10:48:25.451  6943  6943 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 10:48:25.451  6943  6943 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 10:48:25.451  6943  6943 W System.err: android.os.DeadObjectException
08-25 10:48:25.452  6943  6943 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 10:48:25.452  6943  6943 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 10:48:25.452  6943  6943 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 10:48:25.452  6943  6943 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 10:48:25.452  6943  6943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 10:48:25.452  6943  6943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 10:48:25.452  6943  6943 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 10:48:25.452  6943  6943 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 10:48:25.452  6943  6943 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 10:48:25.452  6943  6943 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 10:48:25.452  6943  6943 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:48:25.452  6943  6943 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:48:25.452  6943  6943 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 10:48:25.452  6943  6943 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 10:48:25.452  6943  6943 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 10:48:25.453  6943  6943 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-25 10:48:25.461  7028  7028 V BluetoothOppNotification: new notify threadi!
08-25 10:48:25.461  7028  7028 V BluetoothOppNotification: send delay message
08-25 10:48:25.463  7028  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 10:48:25.464  7028  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d09f2ba on behalf of 
08-25 10:48:25.465  7028  7632 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 10:48:25.466  7028  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 10:48:25.468  7028  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b0d356b on behalf of 
08-25 10:48:25.469  7028  7632 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-25 10:48:25.473  7028  7632 V BluetoothOppNotification: outbound notification was removed.
08-25 10:48:25.473  7028  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 10:48:25.474  7028  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6a888c8 on behalf of 
08-25 10:48:25.475  7028  7632 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 10:48:25.477  7028  7632 V BluetoothOppNotification: inbound notification was removed.
08-25 10:48:25.477  7028  7632 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 10:48:25.478  7028  7632 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21f5d61 on behalf of 
08-25 10:48:25.488  1031  2052 W libprocessgroup: failed to open /acct/uid_1000/pid_6698/cgroup.procs: No such file or directory
08-25 10:48:25.488  1031  2052 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-25 10:48:25.497  6943  6943 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 10:48:25.497  6943  6943 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 10:48:25.559  1031  1940 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7633 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 10:48:25.610  6943  6943 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 10:48:25.651  7633  7633 D UEI.SmartControl: Quickset Services start...
08-25 10:48:25.654  7633  7633 I UEI.SmartControl: Manufacture = LGE
08-25 10:48:25.654  7633  7633 D UEI.SmartControl: Id = LGNevo
08-25 10:48:25.655  7633  7633 D UEI.SmartControl: File observer start...
,08-25 10:48:25.657  7633  7633 E UEI.SmartControl: IR Port is disabled: false
08-25 10:48:25.658  7633  7633 D UEI.SmartControl: Starting file observer...
08-25 10:48:25.658  7633  7633 D UEI.SmartControl: Extracting JNI libs...
08-25 10:48:25.658  7633  7633 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-25 10:48:25.765  7633  7633 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-25 10:48:25.766  7633  7633 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 10:48:25.766  7633  7633 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-25 10:48:25.805  7633  7633 I UEI.SmartControl: --- Selecting new region: 6
,08-25 10:48:25.808  7633  7633 I UEI.SmartControl: Model = LG-D855
,08-25 10:48:25.810  7633  7633 D UEI.SmartControl: QS Service created
08-25 10:48:25.839  7633  7633 I UEI.SmartControl: Service initServices...
,08-25 10:48:25.845  7633  7633 D UEI.SmartControl: QS start get config
,08-25 10:48:25.934  7633  7633 D UEI.SmartControl: Loading JNI Libs...
,08-25 10:48:26.060  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:26.060  1031  1046 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37d34f8e mBinding = false
,08-25 10:48:26.089  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:26.090  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:26.090  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-25 10:48:26.090  1031  1095 D BluetoothManagerService: Message: 2
08-25 10:48:26.091  1031  1095 D BluetoothManagerService: Sending off request.
08-25 10:48:26.092  7028  7044 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 10:48:26.092  7028  7486 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 10:48:26.092  7028  7486 D BluetoothAdapterProperties: Setting state to 13
08-25 10:48:26.092  7028  7486 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 10:48:26.093  7028  7486 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 10:48:26.093  7028  7486 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 10:48:26.094  7028  7490 D BluetoothAdapterProperties: Scan Mode:20
,08-25 10:48:26.094  7028  7486 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 10:48:26.096  7028  7486 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 10:48:26.098  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 10:48:26.098  7028  7556 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 10:48:26.099  7028  7607 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:26.100  7028  7618 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:26.100  7028  7620 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 10:48:26.101  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 10:48:26.101  7028  7556 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 10:48:26.102  7028  7606 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 10:48:26.107  7028  7622 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 10:48:26.110  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:26.110  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:26.111  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:26.111  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 10:48:26.112  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 10:48:26.112  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:26.112  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:26.114  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:26.115  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:26.115  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:48:26.115  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:26.116  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.117  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 10:48:26.119  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:26.121  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:48:26.122  7028  7028 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.122  7028  7028 D BluetoothMapService: STATE_TURNING_OFF
08-25 10:48:26.122  7028  7028 V BluetoothMapService: Handler(): got msg=4
08-25 10:48:26.123  7028  7028 D BluetoothMapService: MAP Service closeService in
08-25 10:48:26.123  7028  7028 D BluetoothMapMasInstance: MAP Service shutdown
08-25 10:48:26.123  7028  7028 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 10:48:26.123  7028  7028 V BluetoothMapService: MAP Service closeService out
08-25 10:48:26.124  7028  7028 V BtOppService: Receiver DISABLED_ACTION 
08-25 10:48:26.124  7028  7028 I BtOppRfcommListener: stopping Accept Thread
08-25 10:48:26.124  7028  7028 V BtOppRfcommListener: close mBtServerSocket
08-25 10:48:26.125  7028  7618 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 10:48:26.126  7028  7028 V BtOppRfcommListener: waiting for thread to terminate
08-25 10:48:26.126  7028  7028 V BtOppRfcommListener: done waiting for thread to terminate
08-25 10:48:26.129  6885  6885 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-25 10:48:26.131  7028  7028 V BtOppService: onDestroy
08-25 10:48:26.133  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 10:48:26.137  7028  7028 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 10:48:26.143  7028  7028 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 10:48:26.143  7028  7028 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.143  7028  7028 V BluetoothPbapReceiver: ***********state = 13
08-25 10:48:26.144  7028  7028 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 10:48:26.145  6885  6885 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:48:26.147  7028  7028 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.147  7028  7028 V BluetoothPbapService: state: 13
08-25 10:48:26.147  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:48:26.148  7028  7028 V BluetoothPbapService: Pbap Service closeService in
08-25 10:48:26.149  6885  6885 D BluetoothPbap: Proxy object disconnected
,08-25 10:48:26.149  6885  6885 D PbapServerProfile: Bluetooth service disconnected
08-25 10:48:26.150  7028  7028 V BluetoothPbapService: successfully stopped pbap service
08-25 10:48:26.150  7028  7028 V BluetoothPbapService: Pbap Service closeService out
08-25 10:48:26.150  7028  7028 V BluetoothPbapService: Pbap Service onDestroy
08-25 10:48:26.150  7028  7028 V BluetoothPbapService: Pbap Service closeService in
08-25 10:48:26.150  7028  7028 V BluetoothPbapService: Pbap Service closeService out
08-25 10:48:26.150  7028  7028 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 10:48:26.161  6885  6885 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 10:48:26.165  6885  6885 D BluetoothPermissionRequest: onReceive
08-25 10:48:26.165  6885  6885 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 10:48:26.170  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 10:48:26.173  7028  7028 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 10:48:26.173  7028  7028 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 10:48:26.174  7028  7028 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 10:48:26.177  7028  7028 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.177  7028  7028 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-25 10:48:26.178  7028  7028 V BluetoothFtpService: Ftp Service onStartCommand
08-25 10:48:26.178  7028  7028 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.178  7028  7028 V BluetoothFtpService: Ftp Service closeService
08-25 10:48:26.178  7028  7028 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 10:48:26.180  7028  7028 V BluetoothFtpService: successfully stopped ftp service
08-25 10:48:26.180  7028  7028 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:26.180  7028  7028 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:26.181  7028  7028 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:26.181  7028  7028 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.181  7028  7028 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 10:48:26.181  7028  7028 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 10:48:26.182  7028  7028 V BluetoothFtpService: Ftp Service onDestroy
08-25 10:48:26.182  7028  7028 V BluetoothFtpService: Ftp Service closeService
08-25 10:48:26.190  7028  7028 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:26.190  7028  7028 V BluetoothSapService: state: 13
08-25 10:48:26.190  7028  7028 V BluetoothSapService: Stopping SAP server process
,08-25 10:48:26.192  7028  7028 V BluetoothSapService: Sap Service closeSapService in
08-25 10:48:26.192  7028  7028 V BluetoothSapService: Close listen Socket : 
08-25 10:48:26.192  7028  7028 V BluetoothSapService: Close rfcomm Socket : 
08-25 10:48:26.192  7028  7028 V BluetoothSapService: Close sapd  Socket : 
08-25 10:48:26.195  7028  7028 V BluetoothSapService: Sap Service closeSapService out
08-25 10:48:26.195  7028  7028 V BluetoothSapService: Sap Service onDestroy
08-25 10:48:26.195  7028  7028 V BluetoothSapService: Sap Service closeSapService in
08-25 10:48:26.195  7028  7028 V BluetoothSapService: Close listen Socket : 
08-25 10:48:26.195  7028  7028 V BluetoothSapService: Close rfcomm Socket : 
08-25 10:48:26.196  7028  7028 V BluetoothSapService: Close sapd  Socket : 
08-25 10:48:26.197  7028  7028 V BluetoothSapService: Sap Service closeSapService out
08-25 10:48:26.414  7633  7633 I UEI.SmartControl: Supports setup maps: true
,08-25 10:48:26.421  7633  7633 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 10:48:26.421  7633  7633 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 10:48:26.422  7633  7633 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 10:48:26.422  7633  7633 I UEI.SmartControl: ### init IR Blaster...
08-25 10:48:26.430  7633  7633 D serial_port: Configuring serial port
,08-25 10:48:26.441  7633  7633 E UEI.SmartControl: UEIBLaster setting for 616
08-25 10:48:26.441  7633  7633 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 10:48:26.442  7633  7633 I UEI.SmartControl: configuring settings for MAXQ616
08-25 10:48:26.443  7633  7633 I UEI.SmartControl: Get version...
,08-25 10:48:26.459  7633  7678 D UEI.SmartControl: serial port data available: 21
,08-25 10:48:26.488  7633  7633 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 10:48:26.488  7633  7633 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 10:48:26.489  7633  7633 I UEI.SmartControl: QS saving settings...
08-25 10:48:26.492  7633  7633 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 10:48:26.512  7633  7678 D UEI.SmartControl: serial port data available: 4
,08-25 10:48:26.550  7633  7685 I UEI.SmartControl: Device manager: loading config....
08-25 10:48:26.552  7633  7685 D UEI.SmartControl: ----------- loading internal config...
,08-25 10:48:26.564  7633  7633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 10:48:26.568  7633  7633 E UEI.SmartControl: Services init done
08-25 10:48:26.572  7633  7633 D UEI.SmartControl: QS Service init finished
,08-25 10:48:26.575  7633  7633 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 10:48:26.575  7633  7633 D UEI.SmartControl: QS Service version code: 201091
08-25 10:48:26.577  7633  7633 D UEI.SmartControl: Service requested: Control
08-25 10:48:26.580  7633  7685 E UEI.SmartControl: Loading SETTINGS...
08-25 10:48:26.583  7633  7633 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 10:48:26.585  6943  6943 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 10:48:26.587  7633  7649 I UEI.SmartControl: ------ IControl API: 11
,08-25 10:48:26.589  7633  7649 I UEI.SmartControl: Registering callback...
08-25 10:48:26.590  7633  7648 I UEI.SmartControl: ------ IControl API: 19
08-25 10:48:26.591  7633  7648 I UEI.SmartControl: Registering Services Ready callback...
08-25 10:48:26.591  1031  1995 I ActivityManager: Killing 6943:com.lge.qremote/u0a112 (adj 15): empty #17
08-25 10:48:26.599  7633  7685 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 10:48:26.627  1031  1904 W libprocessgroup: failed to open /acct/uid_10112/pid_6943/cgroup.procs: No such file or directory
,08-25 10:48:26.627  7633  7633 D UEI.SmartControl: Internal service binding...
,08-25 10:48:26.631  7633  7684 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-25 10:48:26.631  7633  7684 D UEI.SmartControl: -----service ready thread exits
08-25 10:48:27.090  7028  7490 D bt_hci_bdroid: cleanup
,08-25 10:48:27.099  7028  7558 I bt_lpm  : LPM is already off!!!
,08-25 10:48:27.099  7028  7585 I bt_userial_mct: exiting userial_read_thread
08-25 10:48:27.099  7028  7585 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 10:48:27.100  7028  7556 W bt-btif : ag scb idx 1 not allocated
,08-25 10:48:27.100  7028  7556 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 10:48:27.100  7028  7556 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:48:27.100  7028  7556 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 10:48:27.101  7028  7490 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 10:48:27.101  7028  7558 I bt_vendor: hw_epilog_process
08-25 10:48:27.102  7028  7490 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 10:48:27.102  7028  7490 D bt_userial_mct: userial_close
08-25 10:48:27.102  7028  7490 E bt_userial_mct: pthread_join() FAILED result:3
08-25 10:48:27.102  7028  7490 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 10:48:27.107  7028  7490 D bt_hci_bdroid: set_power 0
08-25 10:48:27.107  7028  7490 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 10:48:27.107  7028  7490 I bt_vendor: bluetooth satus is on
08-25 10:48:27.107  7028  7490 I bt_vendor: bt-vendor : resetting BT status
08-25 10:48:27.107  7028  7490 I bt_vendor: Starting hciattach daemon
08-25 10:48:27.107  7028  7490 I bt_vendor: try to set false
,08-25 10:48:27.111  7028  7490 I bt_vendor: Starting hciattach daemon
,08-25 10:48:27.111  7028  7490 I bt_vendor: try to set false
,08-25 10:48:27.117  7028  7490 I bt_vendor: cleanup
08-25 10:48:27.118  7028  7556 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 10:48:27.118  7028  7490 I GKI_LINUX: GKI_exit_task 0 done
08-25 10:48:27.118  7028  7490 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 10:48:27.120  7028  7486 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 10:48:27.128  7028  7028 D HeadsetService: Received stop request...Stopping profile...
,08-25 10:48:27.131  7028  7028 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 10:48:27.132  7028  7028 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 10:48:27.132  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:27.132  7028  7525 D HeadsetStateMachine: Exit Disconnected: -1
08-25 10:48:27.134  7028  7486 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 10:48:27.137  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 10:48:27.137  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 10:48:27.137  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-25 10:48:27.138  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-25 10:48:27.138  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 10:48:27.138  7028  7028 D A2dpService: Received stop request...Stopping profile...
08-25 10:48:27.139  7028  7541 D A2dpStateMachine: Exit Disconnected: -1
,08-25 10:48:27.144  7028  7028 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 10:48:27.145  7028  7028 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 10:48:27.146  7028  7028 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 10:48:27.146  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:27.149  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-25 10:48:27.149  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 10:48:27.149  7028  7028 D HidService: Received stop request...Stopping profile...
08-25 10:48:27.149  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:27.151  7028  7028 D HealthService: Received stop request...Stopping profile...
08-25 10:48:27.152  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
,08-25 10:48:27.157  7028  7028 D PanService: Received stop request...Stopping profile...
08-25 10:48:27.157  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:27.159  7028  7028 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 10:48:27.160  7028  7028 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 10:48:27.160  7028  7028 D BtGatt.GattService: stop()
08-25 10:48:27.160  7028  7028 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 10:48:27.161  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:27.162  7028  7028 D BluetoothMapService: Received stop request...Stopping profile...
08-25 10:48:27.162  7028  7028 D BluetoothMapService: stop()
08-25 10:48:27.163  7028  7028 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 10:48:27.163  7028  7028 D BluetoothMapEmailAppObserver: removeReceiver()
,08-25 10:48:27.165  7028  7028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30babbfa
08-25 10:48:27.167  7028  7028 D HeadsetStateMachine: Unbinding service...
08-25 10:48:27.168  7028  7028 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 10:48:27.168  7028  7028 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 10:48:27.168  7028  7028 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 10:48:27.168  7028  7028 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 10:48:27.169  7028  7028 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 10:48:27.169  7028  7028 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 10:48:27.169  7028  7028 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 10:48:27.169  7028  7028 I BluetoothA2dpServiceJni: cleanupNative
08-25 10:48:27.170  7028  7542 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 10:48:27.171  7028  7028 I GKI_LINUX: GKI_exit_task 2 done
08-25 10:48:27.171  7028  7028 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 10:48:27.171  7028  7028 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 10:48:27.171  7028  7028 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 10:48:27.171  7028  7028 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 10:48:27.172  7028  7028 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 10:48:27.172  7028  7028 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 10:48:27.172  7028  7028 V BluetoothMapService: Handler(): got msg=4
08-25 10:48:27.172  7028  7028 D BluetoothMapService: MAP Service closeService in
08-25 10:48:27.172  7028  7028 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 10:48:27.172  7028  7028 V BluetoothMapService: MAP Service closeService out
08-25 10:48:27.173  7028  7486 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 10:48:27.173  7028  7486 D BluetoothAdapterProperties: Setting state to 10
08-25 10:48:27.173  7028  7486 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 10:48:27.173  7028  7028 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 10:48:27.173  7028  7028 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 10:48:27.175  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:27.175  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 10:48:27.175  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-25 10:48:27.179  1853  4008 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:27.180  7028  7486 I BluetoothAdapterState: Entering OffState
08-25 10:48:27.181  1853  2454 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:27.182  7028  7028 D BluetoothMapService: cleanup()
08-25 10:48:27.182  7028  7028 D BluetoothMapService: MAP Service closeService in
08-25 10:48:27.182  7028  7028 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 10:48:27.182  7028  7028 V BluetoothMapService: MAP Service closeService out
08-25 10:48:27.184  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:27.184  6885  7017 D BluetoothMap: onBluetoothStateChange: up=false
08-25 10:48:27.185  6885  7017 D BluetoothPan: onBluetoothStateChange on: false
08-25 10:48:27.185  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:27.186  6885  7017 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 10:48:27.189  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 10:48:27.191  6885  7017 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 10:48:27.192  6885  7017 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 10:48:27.193  6885  7017 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 10:48:27.194  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 10:48:27.194  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 10:48:27.197  1031  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 10:48:27.197  1031  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 10:48:27.197  1031  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@37d34f8e mBinding = false
08-25 10:48:27.197  1031  1095 D BluetoothManagerService: Sending unbind request.
08-25 10:48:27.202  7028  7490 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 10:48:27.204  7028  7028 I GKI_LINUX: GKI_exit_task 1 done
08-25 10:48:27.204  7028  7028 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 10:48:27.206  7028  7028 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 10:48:27.206  7028  7028 I art     : --- WEIRD: removing null entry 248
08-25 10:48:27.206  7028  7028 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 10:48:27.206  7028  7028 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 10:48:27.207  7028  7028 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 10:48:27.208  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 10:48:27.210  7028  7028 I art     : System.exit called, status: 0
08-25 10:48:27.210  7028  7028 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 10:48:27.230   308   308 V AudioFlinger: 7028 died, releasing its sessions
08-25 10:48:27.230   308   308 V AudioFlinger:  pid 1853 @ 0
08-25 10:48:27.230   308   308 V AudioFlinger:  pid 3453 @ 1
08-25 10:48:27.230   308   308 V AudioFlinger:  pid 3453 @ 2
,08-25 10:48:27.234  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 10:48:27.234  1943  2127 D LGBluetoothAPIService: Message: 101
08-25 10:48:27.234  1943  2127 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-25 10:48:27.234  1943  2127 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 10:48:27.235  1943  2127 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-25 10:48:27.236  6885  6885 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 10:48:27.277  1031  2012 I ActivityManager: Process com.android.bluetooth (pid 7028) has died
08-25 10:48:27.277  1031  2012 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-25 10:48:27.277  1031  2012 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-25 10:48:27.284  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 10:48:27.290  1603  1603 D BluetoothAdapter: 809846621: getState() :  mService = null. Returning STATE_OFF
08-25 10:48:27.290  1603  1603 D BluetoothAdapter: 809846621: getState() :  mService = null. Returning STATE_OFF
08-25 10:48:27.291  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:48:27.291  1943  2127 D LGBluetoothAPIService: Message: 2
08-25 10:48:27.291  1943  2127 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-25 10:48:27.294  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:27.295  6885  6885 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 10:48:27.295  6885  6885 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 10:48:27.295  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:27.298  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 10:48:27.451  1031  1590 I art     : Explicit concurrent mark sweep GC freed 89376(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.095ms total 150.406ms
,08-25 10:48:27.523  1031  2034 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7716 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 10:48:27.527  6885  6885 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:48:27.596  7716  7716 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 10:48:27.596  7716  7716 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 10:48:27.597  7716  7716 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 10:48:27.598  7716  7716 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 10:48:27.619  7716  7716 D BluetoothAdapterApp: Loading JNI Library
,08-25 10:48:27.656  7716  7716 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@20e07aa2 Instance Count = 1
,08-25 10:48:27.663  7716  7716 D BluetoothAdapterApp: onCreate
08-25 10:48:27.692  7716  7716 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-25 10:48:27.693  7716  7716 D ProfileConfigQcom: Adding HeadsetService
08-25 10:48:27.693  7716  7716 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 10:48:27.694  7716  7716 D ProfileConfigQcom: Adding A2dpService
08-25 10:48:27.694  7716  7716 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 10:48:27.698  7716  7716 D ProfileConfigQcom: Adding HidService
08-25 10:48:27.699  7716  7716 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 10:48:27.699  7716  7716 D ProfileConfigQcom: Adding HealthService
08-25 10:48:27.700  7716  7716 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 10:48:27.702  7716  7716 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 10:48:27.702  7716  7716 D ProfileConfigQcom: Adding PanService
08-25 10:48:27.703  7716  7716 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 10:48:27.703  7716  7716 D ProfileConfigQcom: Adding GattService
08-25 10:48:27.704  7716  7716 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 10:48:27.704  7716  7716 D ProfileConfigQcom: Adding BluetoothMapService
08-25 10:48:27.705  7716  7716 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-25 10:48:27.707  7716  7716 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 10:48:27.711  7716  7716 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:27.711  7716  7716 V BluetoothPbapReceiver: ***********state = 10
08-25 10:48:27.716  7716  7716 V LGMDMManagerInternal: Create singleton instance
08-25 10:48:27.814  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 10:48:27.826  6885  6885 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 10:48:27.829  7716  7716 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 10:48:27.830  7716  7716 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 10:48:27.832  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 10:48:27.832  1943  2127 D LGBluetoothAPIService: Message: 100
08-25 10:48:27.832  1943  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-25 10:48:27.835  6885  6885 D BluetoothPermissionRequest: onReceive
08-25 10:48:27.839  6885  6885 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 10:48:27.840  6885  6885 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 10:48:27.842  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 10:48:27.849  7716  7716 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-25 10:48:27.855  7716  7716 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:27.859  7716  7716 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:27.859  7716  7716 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:27.859  7716  7716 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:27.861  7716  7716 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:27.861  7716  7716 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-25 10:48:27.866  6960  6960 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 10:48:28.663  1031  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{6b8bfa8 type 2 when 223518 com.google.android.gms} when 223518
,08-25 10:48:28.673   304  7743 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 10:48:28.679  1031  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-25 10:48:29.091  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 10:48:29.091  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:48:29.365  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-25 10:48:29.417  1031  1453 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 10:48:29.466  1031  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7744 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 10:48:29.482  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 10:48:29.483  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-25 10:48:29.504  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 10:48:29.523  1031  1031 D administrator: Handling package changes for user 0
,08-25 10:48:29.541  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 10:48:29.570  7744  7744 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 10:48:29.628  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 10:48:29.628  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 10:48:29.669  7744  7744 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 10:48:29.669  7744  7744 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 10:48:29.686  1031  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:29.692  1031  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-25 10:48:29.699  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 10:48:29.702  2501  2501 V GmsNetworkLocationProvi: DISABLE
08-25 10:48:29.726  1031  1090 D LocationProviderProxy: applying state to connected service
08-25 10:48:29.727  2501  2501 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-25 10:48:29.851  7744  7792 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-25 10:48:29.851  7744  7792 I Babel   : MmsConfig.loadMmsSettings
08-25 10:48:29.855  7744  7792 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-25 10:48:29.855  7744  7792 I Babel   : MmsConfig.loadFromDatabase
,08-25 10:48:29.881  7744  7792 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-25 10:48:29.881  7744  7792 I Babel   : MmsConfig.loadFromResources
08-25 10:48:29.889  7744  7792 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 10:48:29.890  7744  7792 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-25 10:48:29.910  7744  7744 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:29.917  7744  7787 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 10:48:29.920  7744  7787 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 10:48:29.924  7744  7787 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:48:29.948  7744  7787 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-25 10:48:29.950  7744  7787 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 10:48:29.951  7744  7787 W AudioCapabilities: Unsupported mime audio/evrc
08-25 10:48:29.964  1817  7798 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-25 10:48:29.964  1817  7798 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-25 10:48:29.968  7744  7787 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-25 10:48:29.973  7093  7093 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 10:48:29.978  7093  7093 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f5b721c
08-25 10:48:29.978  7093  7093 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 10:48:29.978  7093  7093 D AppUp4:CustFacade: isPhone : true
08-25 10:48:29.979  7744  7787 W VideoCapabilities: Unsupported mime video/divx
08-25 10:48:29.980  7093  7093 D AppUp4:CustModeStarterReceiver: begin check event
08-25 10:48:29.980  7093  7093 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-25 10:48:29.985  1817  4835 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-25 10:48:29.991  7744  7787 W VideoCapabilities: Unsupported mime video/divx311
,08-25 10:48:30.000  7744  7787 W VideoCapabilities: Unsupported mime video/divx4
08-25 10:48:30.008  7744  7787 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 10:48:30.023  1031  2033 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7802 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-25 10:48:30.029  1031  1046 I ActivityManager: Killing 6914:com.lge.sync/1000 (adj 15): empty #17
08-25 10:48:30.043  1031  1544 D WifiService: Client connection lost with reason: 4
,08-25 10:48:30.053  7744  7787 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-25 10:48:30.058  7744  7787 W AudioCapabilities: Unsupported mime audio/eac3
08-25 10:48:30.059  7744  7787 W AudioCapabilities: Unsupported mime audio/ac3
,08-25 10:48:30.060  7744  7787 W AudioCapabilities: Unsupported mime audio/g726
08-25 10:48:30.061  7744  7787 W AudioCapabilities: Unsupported mime audio/wma-voice
08-25 10:48:30.062  7744  7787 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 10:48:30.064  7744  7787 W AudioCapabilities: Unsupported mime audio/adpcm
08-25 10:48:30.066  7744  7787 W VideoCapabilities: Unsupported mime video/theora
08-25 10:48:30.069  7744  7787 W VideoCapabilities: Unsupported mime video/mjpg
,08-25 10:48:30.107  1031  1977 W libprocessgroup: failed to open /acct/uid_1000/pid_6914/cgroup.procs: No such file or directory
,08-25 10:48:30.120  1031  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{398058dc type 2 when 224953 android} when 224953
08-25 10:48:30.144  7802  7802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:30.144  7802  7802 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 10:48:30.144  7802  7802 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 10:48:30.145  7802  7802 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 10:48:30.145  7802  7802 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-25 10:48:30.199  7802  7802 I SystemConfig: BUILD Country: EU
,08-25 10:48:30.199  7802  7802 I SystemConfig: BUILD Operator: OPEN
,08-25 10:48:30.235  1031  1590 I ActivityManager: Killing 7125:com.lge.email/u0a23 (adj 15): empty #17
,08-25 10:48:30.347  1031  1811 W libprocessgroup: failed to open /acct/uid_10023/pid_7125/cgroup.procs: No such file or directory
,08-25 10:48:30.358  7802  7822 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 10:48:30.358  7802  7822 I SystemConfig: existFile = false
08-25 10:48:30.358  7802  7822 I SystemConfig: canReadFile = false
08-25 10:48:30.358  7802  7822 I SystemConfig: systemFeature RCS result false
08-25 10:48:30.358  7802  7822 D SystemConfig: refreshRcsSupport() :false
08-25 10:48:30.421  1031  1590 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7827 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-25 10:48:30.472  7827  7827 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:30.473  7827  7827 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 10:48:30.473  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 10:48:30.473  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 10:48:30.558  7827  7827 I AppConfig: Total System Memory = 2995761152
,08-25 10:48:30.570  7827  7827 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-25 10:48:30.672  1031  1046 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7847 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 10:48:30.673  1031  1046 I ActivityManager: Killing 6983:com.lge.formmanager/u0a26 (adj 15): empty #17
08-25 10:48:30.694   333   333 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 24.832ms
,08-25 10:48:30.716   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.633ms
,08-25 10:48:30.738   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 20.934ms
,08-25 10:48:30.758  1031  1995 W libprocessgroup: failed to open /acct/uid_10026/pid_6983/cgroup.procs: No such file or directory
,08-25 10:48:30.990  7847  7847 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 10:48:31.097  7847  7847 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:31.097  7847  7847 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:31.163  7847  7847 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 10:48:31.188  7847  7847 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 10:48:31.189  7847  7847 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-25 10:48:31.206  7847  7847 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-25 10:48:31.206  7847  7847 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-25 10:48:31.225  1031  1941 I ActivityManager: Killing 6496:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-25 10:48:31.270  1031  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_6496/cgroup.procs: No such file or directory
,08-25 10:48:31.290  4648  7887 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-25 10:48:31.296  3521  4540 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-25 10:48:31.299  3521  4540 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29b2ea80 on behalf of 7847
08-25 10:48:31.341  1031  1047 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7888 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 10:48:31.397  7847  7847 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-25 10:48:31.440  7847  7847 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-25 10:48:31.455  7888  7888 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 10:48:31.483  7888  7888 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-25 10:48:31.483  7888  7888 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 10:48:31.483  7888  7888 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-25 10:48:31.483  7888  7888 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 10:48:31.483  7888  7888 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-25 10:48:31.483  7888  7888 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-25 10:48:31.508  1031  1940 I ActivityManager: Killing 7162:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-25 10:48:31.547  1031  1047 W libprocessgroup: failed to open /acct/uid_10046/pid_7162/cgroup.procs: No such file or directory
,08-25 10:48:31.560  7633  7686 D UEI.SmartControl: Internal timer expired: 1
08-25 10:48:31.560  7633  7686 D UEI.SmartControl: unbind internal service
,08-25 10:48:31.564  7633  7633 D UEI.SmartControl: Service.onUnbind: IControl
08-25 10:48:31.565  7633  7633 D UEI.SmartControl: Service.onDestroy
,08-25 10:48:31.565  7633  7633 D UEI.SmartControl: Lock is in USE false
08-25 10:48:31.565  7633  7633 D UEI.SmartControl: unbind internal service
08-25 10:48:31.566  7633  7633 D serial_port: close(fd = 25)
08-25 10:48:31.569  7633  7633 I UEI.SmartControl: Serial port is closed.
08-25 10:48:31.569  7633  7633 I UEI.SmartControl: Serial port is closed.
08-25 10:48:31.570  7633  7633 D UEI.SmartControl: Blaster closed
08-25 10:48:31.570  7633  7633 D UEI.SmartControl: Shut down QS...
08-25 10:48:31.570  7633  7633 D UEI.SmartControl: Stopping QS lib
08-25 10:48:31.571  7633  7633 D UEI.SmartControl: QS lib stop result = true
08-25 10:48:31.571  7633  7633 D UEI.SmartControl: Stopped QS lib
08-25 10:48:31.571  7633  7633 D UEI.SmartControl: Stopped file observer...
08-25 10:48:31.571  7633  7633 D UEI.SmartControl: QS shutdown complete
08-25 10:48:31.710  1031  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-25 10:48:31.738  4648  7887 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 448 ms] updated apps [took 448 ms] 
,08-25 10:48:31.789  1031  1386 V AlarmManager: RTC_WAKEUP set : Alarm{1780df09 type 0 when 1472114910375 com.google.android.gms} when 1472114910375
,08-25 10:48:31.819  1817  7924 I CheckinService: active receiver: enabled
,08-25 10:48:31.856  2191  2191 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-25 10:48:31.908  1031  1942 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7928 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-25 10:48:32.026  7928  7928 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:32.027  7928  7928 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:32.030  7928  7928 D PhoneMonitor: Register our PhoneStateListener
08-25 10:48:32.055  1031  1995 I ActivityManager: Killing 7184:com.android.chrome/u0a57 (adj 15): empty #17
,08-25 10:48:32.084  7928  7928 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 10:48:32.085  7928  7928 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 10:48:32.086  7928  7928 D TelephonyAutoProfiling: [parse] Load xml
08-25 10:48:32.089  7928  7928 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 10:48:32.089  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 10:48:32.090  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 10:48:32.090  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 10:48:32.090  7928  7928 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 10:48:32.090  7928  7928 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-25 10:48:32.097  7928  7928 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-25 10:48:32.103  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:32.103  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e49e04e added. We now have 6 listener(s)
08-25 10:48:32.103  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:48:32.107  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:32.107  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2220756f added. We now have 7 listener(s)
08-25 10:48:32.107  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:32.108  1031  1046 W libprocessgroup: failed to open /acct/uid_10057/pid_7184/cgroup.procs: No such file or directory
08-25 10:48:32.109  6778  6856 I System.out: IsBluetoothEnabled
08-25 10:48:32.112  1031  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:32.113  1031  1940 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 10:48:32.113  1031  1095 D BluetoothManagerService: Message: 2
08-25 10:48:32.116  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:48:32.117  1031  1811 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:32.117  1031  1811 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-25 10:48:32.127  1031  1095 D BluetoothManagerService: Message: 1
08-25 10:48:32.127  1031  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 10:48:32.128  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:32.128  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:32.129  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-25 10:48:32.147  1031  1095 D BluetoothManagerService: Message: 20
,08-25 10:48:32.147  1031  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f4257d:true
,08-25 10:48:32.148  7716  7716 D BluetoothAdapterState: make
08-25 10:48:32.153  7716  7716 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 10:48:32.154  7716  7716 I bluedroid-qcom: init
08-25 10:48:32.154  7716  7950 I BluetoothAdapterState: Entering OffState
08-25 10:48:32.155  7716  7716 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 10:48:32.155  7716  7716 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 10:48:32.155  7716  7716 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 10:48:32.155  7716  7716 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
08-25 10:48:32.155  7716  7716 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-25 10:48:32.156  7716  7716 I bluedroid-qcom: get_profile_interface socket,
,08-25 10:48:32.156  7716  7716 I bluedroid-qcom: get_profile_interface map_client
,08-25 10:48:32.150  7954  7954 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 10:48:32.150  7954  7954 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 10:48:32.165  7954  7954 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,08-25 10:48:32.165  7954  7954 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 10:48:32.165  7954  7954 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 10:48:32.167  7716  7953 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 10:48:32.169  7954  7954 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 10:48:32.173  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-25 10:48:32.173  1031  1095 D BluetoothManagerService: Message: 40
08-25 10:48:32.173  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 10:48:32.174  7954  7954 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 10:48:32.174  7954  7954 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 10:48:32.177  7716  7733 I bluedroid-qcom: config_hci_snoop_log,
,08-25 10:48:32.178  1031  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 10:48:32.178  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 10:48:32.182  7716  7953 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 10:48:32.183  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 10:48:32.183  7716  7953 D BluetoothAdapterProperties: Name is: G3
08-25 10:48:32.183  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 10:48:32.186  7716  7950 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 10:48:32.186  7716  7950 D BluetoothAdapterProperties: Setting state to 11
08-25 10:48:32.186  7716  7950 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 10:48:32.187  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:32.187  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 10:48:32.187  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 10:48:32.188  7716  7950 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 10:48:32.189  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 10:48:32.190  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:32.193  6885  6885 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 10:48:32.198  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:32.199  7716  7716 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 10:48:32.199  7716  7716 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:32.199  7716  7716 V BluetoothPbapReceiver: ***********state = 11
08-25 10:48:32.201  7716  7950 D BluetoothBondStateMachine: make
,08-25 10:48:32.204  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:48:32.207  7716  7955 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 10:48:32.207  7716  7950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.207  7716  7950 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 10:48:32.208  7716  7950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.208  7716  7950 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 10:48:32.208  7716  7950 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 10:48:32.216  7716  7950 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 10:48:32.225  7716  7950 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:32.226  7716  7716 D HeadsetService: Received start request. Starting profile...
08-25 10:48:32.226  7716  7716 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 10:48:32.227  7716  7716 D LGBluetoothHfpAdapter: Version 1.6
08-25 10:48:32.230  7716  7716 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 10:48:32.230  6885  6885 D BluetoothPermissionRequest: onReceive
08-25 10:48:32.231  7716  7716 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 10:48:32.232  7716  7716 D HeadsetStateMachine: make
,08-25 10:48:32.244  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 10:48:32.260  7716  7950 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:32.272  7716  7950 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:32.274  7716  7716 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:32.274  7716  7716 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:32.279  7716  7716 D HeadsetStateMachine: max_hf_connections = 1
08-25 10:48:32.279  7716  7716 I bluedroid-qcom: get_profile_interface handsfree
08-25 10:48:32.279  7716  7950 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:32.282  7716  7716 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 10:48:32.283   308  1384 V AudioPolicyService: registerClient() client 0xb558a260, uid 1002
08-25 10:48:32.284   308  1749 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 10:48:32.284   308  1749 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 10:48:32.284   308  1749 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 10:48:32.284  7716  7716 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 10:48:32.285   308  1383 V AudioFlinger: registerClient() client 0xb14330a0, pid 7716
08-25 10:48:32.285   308  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:32.285   308  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:32.285  1603  3105 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:32.285  1603  3105 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:32.285  1853  4018 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:32.285  1853  4018 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:32.286   308  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:32.286   308  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:32.286  1031  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:32.286  1031  2033 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:32.286  1031  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:32.286  1031  2033 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:32.286  1853  4008 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:32.286  3453  3473 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:32.286  1853  4008 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:32.286  3453  3473 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 10:48:32.286  3453  3473 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:32.286  3453  3473 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:32.286  7716  7732 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 10:48:32.286  1603  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:32.286  1603  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 10:48:32.287  7716  7732 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 10:48:32.287  7716  7732 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 10:48:32.287  7716  7732 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 10:48:32.287  7716  7716 V ToneGenerator: Create Track: 0xb4928080
08-25 10:48:32.287  7716  7716 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 10:48:32.287  7716  7716 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 10:48:32.287   308  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 10:48:32.287   308  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 10:48:32.287   308  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 10:48:32.287   308  1384 V AudioPolicyManagerEx: getOutput() returns ,output 2
08-25 10:48:32.288   308  1749 I AudioFlinger: isAudioPlaybackHookOn() false
,08-25 10:48:32.292   308  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 10:48:32.292   308  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 10:48:32.292   308  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 10:48:32.292   308  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 10:48:32.292  7716  7716 V AudioSystem: getLatency() output 2, latency 50
08-25 10:48:32.292  7716  7716 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 10:48:32.292  7716  7716 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 10:48:32.293   308   308 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 10:48:32.293   308   308 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 10:48:32.293   308   308 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 10:48:32.293   308   308 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 10:48:32.293   308   308 V AudioFlinger: createTrack() lSessionId: 23
08-25 10:48:32.294  7716  7950 E BluetoothAdapterService: File transfer profiles supported!!
08-25 10:48:32.294  7716  7716 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 10:48:32.295   308  1384 V AudioFlinger: acquiring 23 from 7716, for 7716
08-25 10:48:32.295   308  1384 V AudioFlinger:  added new entry for 23
08-25 10:48:32.295  7716  7716 V ToneGenerator: ToneGenerator INIT OK, time: 227178
08-25 10:48:32.295  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.296  7716  7956 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 10:48:32.296  7716  7956 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 10:48:32.296  7716  7956 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 10:48:32.296  7716  7956 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 10:48:32.296   308  1749 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7716
08-25 10:48:32.297   308  1749 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 10:48:32.297   308  1749 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 10:48:32.297   308  1749 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 10:48:32.297   308  1749 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 10:48:32.297   308  1749 V voice   : voice_set_parameters: exit with code(0)
08-25 10:48:32.297   308  1749 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 10:48:32.297   308  1749 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 10:48:32.297   308  1749 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 10:48:32.297   308  1749 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 10:48:32.297   308  1749 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 10:48:32.297   308  1749 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 10:48:32.297  7716  7956 V ToneGenerator: ToneGenerator destructor
08-25 10:48:32.297  7716  7956 V ToneGenerator: stopTone
08-25 10:48:32.297  7716  7956 V ToneGenerator: Delete Track: 0xb4928080
08-25 10:48:32.298  7716  7956 V AudioTrack: ~AudioTrack, releasing session id from 7716 on behalf of 7716
08-25 10:48:32.298   308  1384 V AudioFlinger: releasing 23 from 7716 for 7716
08-25 10:48:32.298   308  1384 V AudioFlinger:  decremented refcount to 0
08-25 10:48:32.298   308  1384 V AudioFlinger: purging stale effects
08-25 10:48:32.298   308  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 10:48:32.298   308  1384 ,V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 10:48:32.298   308  1384 V AudioFlinger: PlaybackThread::Track destructor
08-25 10:48:32.299   308  1104 V AudioPolicyService: AudioCommandThread() waking up
08-25 10:48:32.299   308  1384 V AudioFlinger: removeClient_l() pid 7716, calling pid 308
08-25 10:48:32.299   308  1104 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 10:48:32.299   308  1104 V AudioPolicyManager: releaseOutput() 2
08-25 10:48:32.299   308  1104 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 10:48:32.301  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.301  7716  7950 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 10:48:32.303  7716  7716 D A2dpService: Received start request. Starting profile...
08-25 10:48:32.304  7716  7716 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 10:48:32.305  7716  7716 V Avrcp   : make
08-25 10:48:32.305  7716  7716 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 10:48:32.305  7716  7716 I bluedroid-qcom: get_profile_interface avrcp
08-25 10:48:32.316  7716  7716 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 10:48:32.318  7716  7716 E AudioManager: No RCC entry present to update
08-25 10:48:32.318  7716  7716 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 10:48:32.319  7716  7950 V LGMDMManager: Create singleton instance
08-25 10:48:32.322  7716  7716 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 10:48:32.323  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 10:48:32.323  7716  7716 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 10:48:32.324  7716  7950 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 10:48:32.327  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 10:48:32.437  1031  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-25 10:48:32.437  1031  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-25 10:48:32.572  1031  2034 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 10:48:32.586  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-25 10:48:32.593  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 10:48:32.594  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 10:48:32.594  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 10:48:32.594  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-25 10:48:32.594  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 10:48:32.594  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 10:48:32.594  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 10:48:32.595  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 10:48:32.595  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 10:48:32.595  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 10:48:32.596  7716  7716 I BluetoothA2dpServiceJni: classInitNative
08-25 10:48:32.596  7716  7716 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 10:48:32.596  7716  7716 D A2dpStateMachine: make
08-25 10:48:32.601  7716  7716 I bluedroid-qcom: get_profile_interface a2dp
08-25 10:48:32.601  7716  7976 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 10:48:32.604  7716  7716 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 10:48:32.604  7716  7716 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 10:48:32.606  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.607  7716  7716 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 10:48:32.610  7716  7716 D HidService: Received start request. Starting profile...
08-25 10:48:32.610  7716  7975 D A2dpStateMachine: Enter Disconnected: -2
08-25 10:48:32.610  7716  7716 I bluedroid-qcom: get_profile_interface hidhost
08-25 10:48:32.610  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.611  7716  7716 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 10:48:32.613  7716  7716 D HealthService: Received start request. Starting profile...
,08-25 10:48:32.617  7716  7716 I bluedroid-qcom: get_profile_interface health
08-25 10:48:32.618  7716  7716 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 10:48:32.618  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.619  7716  7716 D HeadsetStateMachine: Proxy object connected
08-25 10:48:32.621  7716  7716 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 10:48:32.621  7716  7716 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 10:48:32.625  7716  7716 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 10:48:32.629  7716  7716 D PanService: Received start request. Starting profile...
08-25 10:48:32.629  7716  7716 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 10:48:32.629  7716  7716 I bluedroid-qcom: get_profile_interface pan
08-25 10:48:32.641  7716  7716 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-25 10:48:32.641  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.643  7716  7716 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 10:48:32.649  7716  7716 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 10:48:32.650  7716  7716 D BtGatt.GattService: Received start request. Starting profile...
08-25 10:48:32.650  7716  7716 D BtGatt.GattService: start()
08-25 10:48:32.650  7716  7716 I bluedroid-qcom: get_profile_interface gatt
08-25 10:48:32.650  7716  7716 D BtGatt.AdvertiseManager: advertise manager created
08-25 10:48:32.657  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
,08-25 10:48:32.662  7716  7716 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:32.663  7716  7956 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 10:48:32.664  7716  7956 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 10:48:32.664  7716  7956 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 10:48:32.666  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.666  7716  7716 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 10:48:32.667  7716  7716 V BluetoothMapService: BluetoothMapBinder()
08-25 10:48:32.668  7716  7716 D BluetoothMapService: Received start request. Starting profile...
08-25 10:48:32.668  7716  7716 D BluetoothMapService: start()
08-25 10:48:32.672  7716  7716 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 10:48:32.672  7716  7716 D BluetoothMapEmailAppObserver: createReceiver()
,08-25 10:48:32.673  7716  7716 D BluetoothMapEmailAppObserver: initObservers()
08-25 10:48:32.674  7716  7716 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 10:48:32.684  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:32.688  7716  7716 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 10:48:32.690  7716  7716 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:32.696  7716  7716 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:32.700  7716  7716 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 10:48:32.700  7716  7716 V PanService: [BTUI] SIM Extra State :ABSENT
,08-25 10:48:32.704  7716  7716 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 10:48:32.708  7716  7716 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 10:48:32.708  7716  7716 V BluetoothMapService: Handler(): got msg=1
,08-25 10:48:32.709  7716  7950 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 10:48:32.710  7716  7950 I bluedroid-qcom: enable
08-25 10:48:32.710  7716  7716 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:32.710  7716  7716 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:32.710  7716  7716 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:32.711  7716  7716 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:32.711  7716  7716 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 10:48:32.711  7716  7983 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-25 10:48:32.712  7716  7983 I bt-btu  : btu_task pending for preload complete event
08-25 10:48:32.712  7716  7950 I bt_hci_bdroid: init
08-25 10:48:32.717  7716  7950 I bt_vendor: bt-vendor : init
08-25 10:48:32.717  7716  7950 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 10:48:32.717  7716  7950 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 10:48:32.717  7716  7950 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 10:48:32.717  7716  7950 D bt_userial_mct: userial_init
,08-25 10:48:32.720  7716  7950 D bt_hci_bdroid: set_power 1
08-25 10:48:32.720  7716  7950 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 10:48:32.720  7716  7950 I bt_vendor: Starting hciattach daemon
08-25 10:48:32.720  7716  7950 I bt_vendor: try to set true
08-25 10:48:32.710  7986  7986 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:32.710  7986  7986 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 10:48:32.750  7987  7987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 10:48:32.873  7993  7993 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 10:48:32.890  7994  7994 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 10:48:32.932  7996  7996 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 10:48:32.950  7997  7997 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 10:48:32.964  7998  7998 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 10:48:32.977  7999  7999 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-25 10:48:33.013  8001  8001 I libmdmdetect: ESOC framework not supported
,08-25 10:48:33.013  8001  8001 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 10:48:33.026  8001  8001 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-25 10:48:33.026  8001  8001 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 10:48:33.026  8001  8001 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 10:48:33.026  8001  8001 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 10:48:33.026  8001  8001 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 10:48:33.027  8001  8001 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 10:48:33.027  8001  8001 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 10:48:33.085  8001  8005 E QC-QMI  : qmi_client [8001] 15: failed to locate client data
,08-25 10:48:33.098   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 10:48:33.098   444   444 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-25 10:48:33.123  8009  8009 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 10:48:33.140  8010  8010 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 10:48:33.158  7716  7950 I bt_vendor: bluetooth satus is on
08-25 10:48:33.158  7716  7950 D bt_hci_bdroid: preload
,08-25 10:48:33.161  7716  7985 D bt_userial_mct: userial_open(port:0)
08-25 10:48:33.161  7716  7985 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 10:48:33.165  7716  7985 I bt_vendor: Done intiailizing UART
08-25 10:48:33.167  7716  7985 I bt_vendor: Done intiailizing UART
08-25 10:48:33.167  7716  7985 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 10:48:33.167  7716  7985 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 10:48:33.167  7716  7983 I bt-btu  : btu_task received preload complete event
08-25 10:48:33.168  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 10:48:33.168  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 10:48:33.170  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 10:48:33.175  7716  8012 D bt_userial_mct: Entering userial_read_thread()
,08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 10:48:33.177  7716  7983 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 10:48:33.245  7716  7983 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 10:48:33.246  7716  7983 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0179061 
08-25 10:48:33.246  7716  7983 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0179061 
,08-25 10:48:33.302  7716  7953 E bt-btif : Calling BTA_HhEnable
,08-25 10:48:33.302  7716  7953 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-25 10:48:33.303  7716  7953 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 10:48:33.315  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 10:48:33.316  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 10:48:33.320  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 10:48:33.320  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-25 10:48:33.320  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 10:48:33.320  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 10:48:33.320  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 10:48:33.328  7716  7953 D BluetoothAdapterProperties: Name is: G3
08-25 10:48:33.337  7716  7953 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:48:33.337  7716  7953 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 10:48:33.337  7716  7953 D bt_hci_bdroid: postload
,08-25 10:48:33.340  7716  7985 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:33.341  7716  7983 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 10:48:33.341  7716  7953 D bte_conf: Device ID record 1 : primary
08-25 10:48:33.341  7716  7953 D bte_conf:   vendorId            = 00c4
08-25 10:48:33.341  7716  7953 D bte_conf:   vendorIdSource      = 0001
08-25 10:48:33.341  7716  7953 D bte_conf:   product             = 13a1
08-25 10:48:33.341  7716  7953 D bte_conf:   version             = 1000
08-25 10:48:33.341  7716  7953 D bte_conf:   clientExecutableURL = 
08-25 10:48:33.341  7716  7953 D bte_conf:   serviceDescription  = 
08-25 10:48:33.341  7716  7953 D bte_conf:   documentationURL    = 
08-25 10:48:33.341  7716  7953 D bte_conf: bte_load_did_conf no section named DID2.
08-25 10:48:33.342  7716  7985 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:33.345  7716  7950 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 10:48:33.345  7716  7950 D BluetoothAdapterProperties: ScanMode =  20
08-25 10:48:33.345  7716  7950 D BluetoothAdapterProperties: State =  11
08-25 10:48:33.346  7716  7950 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 10:48:33.346  7716  7950 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 10:48:33.346  7716  7950 D BluetoothAdapterProperties: Setting state to 12
08-25 10:48:33.346  7716  7950 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 10:48:33.347  7716  7953 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 10:48:33.347  7716  7953 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 10:48:33.340  8014  8014 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 10:48:33.340  8014  8014 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:33.361  1031  1095 D BluetoothManagerService: Message: 60
08-25 10:48:33.361  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 10:48:33.361  1031  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 10:48:33.361  7716  7985 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:33.375  7716  7983 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:33.375  7716  7983 W bt-smp  : Plain text(LSB ~ MSB) = 70 61 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:33.375  7716  7983 W bt-smp  : Encrypted text(LSB ~ MSB) = 06 9f 73 2f 28 be 95 6e 68 c6 bd 27 6c aa 5b 30 
,08-25 10:48:33.378  7716  7985 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 10:48:33.378  7716  7983 W bt-btm  : Stopping oneshot timer
08-25 10:48:33.379  7716  8012 E bt_mct  : hci lib postload completed
08-25 10:48:33.379  7716  7950 I BluetoothAdapterState: Entering On State
08-25 10:48:33.380  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:33.388  7716  7953 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 10:48:33.395  7716  7953 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 10:48:33.405  7716  7983 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:33.405  7716  7983 W bt-smp  : Plain text(LSB ~ MSB) = 0e 83 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:33.406  7716  7983 W bt-smp  : Encrypted text(LSB ~ MSB) = 33 dc d8 55 a6 01 ec e0 b0 10 8b d1 f8 fb 0f ee 
,08-25 10:48:33.408  7716  7983 W bt-btm  : Stopping oneshot timer
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:33.413  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:33.418  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:48:33.430  7716  7983 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:33.430  7716  7983 W bt-smp  : Plain text(LSB ~ MSB) = 4e 26 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:33.430  7716  7983 W bt-smp  : Encrypted text(LSB ~ MSB) = 51 56 a9 60 9f f3 52 94 ba e7 ce 7f b1 10 f5 a3 
08-25 10:48:33.435  7716  7983 W bt-btm  : Stopping oneshot timer
,08-25 10:48:33.442  7716  7950 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 10:48:33.442  7716  7950 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 10:48:33.442  7716  7950 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 10:48:33.444  7716  7950 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 10:48:33.444  7716  7950 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 10:48:33.452  1853  1853 D BluetoothHeadset: Proxy object connected
,08-25 10:48:33.457  7716  7983 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:33.458  7716  7983 W bt-smp  : Plain text(LSB ~ MSB) = 1b 05 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:33.458  7716  7983 W bt-smp  : Encrypted text(LSB ~ MSB) = ce c6 60 61 70 35 b5 30 0e 68 c3 25 29 c7 21 cd 
08-25 10:48:33.459  7716  7983 W bt-btm  : Stopping oneshot timer
08-25 10:48:33.465  1853  4009 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:33.469  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 10:48:33.469  1031  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:33.471  1031  1031 D BluetoothHeadset: Proxy object connected
08-25 10:48:33.473  6885  6909 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 10:48:33.478  6885  6909 D BluetoothPan: onBluetoothStateChange on: true
08-25 10:48:33.479  6885  6909 D BluetoothPan: onBluetoothStateChange call bindService
08-25 10:48:33.481  1853  4008 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:33.482  6885  6885 D BluetoothMap: Proxy object connected
08-25 10:48:33.482  6885  6885 D MapProfile: Bluetooth service connected
08-25 10:48:33.482  6885  6885 D BluetoothMap: getConnectedDevices()
08-25 10:48:33.484  1853  1853 D BluetoothHeadset: Proxy object connected
08-25 10:48:33.484  6885  6909 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 10:48:33.486  1031  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 10:48:33.487  7716  7733 V BluetoothMapService: getConnectedDevices()
08-25 10:48:33.493  1031  1031 D BluetoothA2dp: Proxy object connected
,08-25 10:48:33.495  6885  6909 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 10:48:33.496  8032  8032 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 10:48:33.497  6885  6885 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:48:33.497  6885  6885 D PanProfile: Bluetooth service connected
08-25 10:48:33.498  6885  6901 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 10:48:33.499  6885  6885 D BluetoothA2dp: Proxy object connected
08-25 10:48:33.499  6885  6885 D A2dpProfile: Bluetooth service connected
08-25 10:48:33.500  7716  7983 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 10:48:33.500  7716  7983 W bt-smp  : Plain text(LSB ~ MSB) = c2 bd 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 10:48:33.500  7716  7983 W bt-smp  : Encrypted text(LSB ~ MSB) = ff 40 16 91 8e c7 cd 4b e0 3c 33 d0 1f 84 d4 e8 
08-25 10:48:33.500  7716  7983 W bt-btm  : Stopping oneshot timer
,08-25 10:48:33.501  6885  6909 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 10:48:33.502  6885  6885 D BluetoothHeadset: Proxy object connected
08-25 10:48:33.502  6885  6885 D HeadsetProfile: Bluetooth service connected
08-25 10:48:33.504  1031  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 10:48:33.504  1031  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 10:48:33.505  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 10:48:33.505  6885  6885 D BluetoothInputDevice: Proxy object connected
08-25 10:48:33.505  6885  6885 D HidProfile: Bluetooth service connected
,08-25 10:48:33.508  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:33.509  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 10:48:33.509  1943  2127 D LGBluetoothAPIService: Message: 1
08-25 10:48:33.509  1943  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 10:48:33.509  1943  2127 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-25 10:48:33.509  1943  2127 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 10:48:33.513  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:33.514  1031  1095 D BluetoothManagerService: Message: 40
08-25 10:48:33.514  1031  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 10:48:33.515  7716  7716 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:33.515  7716  7716 D BluetoothMapService: STATE_ON
08-25 10:48:33.515  7716  7716 V BluetoothMapService: Handler(): got msg=1
08-25 10:48:33.516  7716  7716 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 10:48:33.519  7716  8035 D BluetoothMapMasInstance: MAS initSocket()
08-25 10:48:33.519  7716  8035 D BluetoothMapMasInstance:   masId = 00
08-25 10:48:33.519  7716  8035 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 10:48:33.519  7716  8035 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 10:48:33.519  7716  8035 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 10:48:33.519  6885  6885 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-25 10:48:33.523  1031  1590 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:33.523  6885  6885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 10:48:33.526  7716  8035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:33.528  7716  8035 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 10:48:33.528  7716  8035 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 10:48:33.528  7716  8035 D BluetoothMapMasInstance: Accepting socket connection...
08-25 10:48:33.529  7716  7953 D BluetoothAdapterProperties: Scan Mode:21
08-25 10:48:33.529  7716  7953 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 10:48:33.531  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:33.533  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
,08-25 10:48:33.533  7716  7716 V BluetoothPbapService: Pbap Service onCreate
08-25 10:48:33.533  7716  7716 V BluetoothPbapService: Starting PBAP service
08-25 10:48:33.534  7716  7716 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 10:48:33.534  7716  7716 V BluetoothPbapService: Pbap Service onBind
08-25 10:48:33.536  7716  7716 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:33.536  7716  7716 V BluetoothPbapService: state: 12
08-25 10:48:33.536  7716  7716 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 10:48:33.536  6885  6885 D DockEventReceiver: finishStartingService: stopping service
08-25 10:48:33.536  7716  7716 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:33.536  7716  7716 V BluetoothPbapReceiver: ***********state = 12
08-25 10:48:33.538  6885  6885 D BluetoothPbap: Proxy object connected
08-25 10:48:33.538  6885  6885 D PbapServerProfile: Bluetooth service connected
08-25 10:48:33.538  7716  7716 V BluetoothPbapService: Handler(): got msg=1
08-25 10:48:33.538  7716  7716 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 10:48:33.539  7716  8039 V BluetoothPbapService: Pbap Service initSocket
08-25 10:48:33.540  1031  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:33.541  7716  8039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:33.542  2191  2191 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 10:48:33.542  2191  2191 D c       : Getting all permits...
08-25 10:48:33.542  2191  2191 D a       : Opening database...
08-25 10:48:33.542  7716  8039 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 10:48:33.543  7716  8039 V BluetoothPbapService: Succeed to create listening socket 
08-25 10:48:33.543  7716  8039 V BluetoothPbapService: Accepting socket connection...
08-25 10:48:33.546  2191  2191 D a       : Opening database auth.proximity.permit_store...
08-25 10:48:33.546  2191  2191 D a       : Closing database...
,08-25 10:48:33.554  6885  6885 D BluetoothPermissionRequest: onReceive
08-25 10:48:33.555  6885  6885 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 10:48:33.556  6885  6885 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 10:48:33.559  7716  7716 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-25 10:48:33.561  7716  7716 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 10:48:33.566  7716  7716 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 10:48:33.586  7716  7716 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 10:48:33.586  7716  7716 V BtOppService: onCreate
08-25 10:48:33.591  7716  7716 V BluetoothOppNotification: send message
08-25 10:48:33.600  7716  8044 V BtOppService: Deleted complete outbound shares, number =  0
,08-25 10:48:33.602  7716  8044 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 10:48:33.602  7716  8044 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-25 10:48:33.747  1031  1940 I art     : Explicit concurrent mark sweep GC freed 26112(1305KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 4.644ms total 154.800ms
08-25 10:48:33.748  7716  8044 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9b4f5d6 on behalf of 
,08-25 10:48:33.751  7716  7716 V BtOppService: Starting RfcommListener
,08-25 10:48:33.758  7716  7716 D BluetoothOppPreference: Dumping Names:  
08-25 10:48:33.758  7716  7716 D BluetoothOppPreference: {}
08-25 10:48:33.759  7716  7716 D BluetoothOppPreference: Dumping Channels:  
08-25 10:48:33.759  7716  7716 D BluetoothOppPreference: {}
08-25 10:48:33.760  7716  7716 V BtOppService: onStartCommand
,08-25 10:48:33.764  7716  8047 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 10:48:33.764  7716  8047 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 10:48:33.766  7716  8047 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2863a744 on behalf of 
08-25 10:48:33.767  7716  8047 V BluetoothOppNotification: update too frequent, put in queue
08-25 10:48:33.767  7716  7716 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:33.767  7716  7716 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 10:48:33.768  7716  8047 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 10:48:33.768  7716  8047 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 10:48:33.770  7716  8047 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31fd202d on behalf of 
08-25 10:48:33.770  7716  7716 V BluetoothOppNotification: new notify threadi!
08-25 10:48:33.771  7716  7716 V BluetoothOppNotification: send delay message
08-25 10:48:33.771  7716  8047 V BluetoothOppNotification: update too frequent, put in queue
08-25 10:48:33.771  7716  7716 V BtOppService: ContentObserver received notification
08-25 10:48:33.772  7716  7716 V BtOppService: ContentObserver received notification
08-25 10:48:33.772  7716  8047 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 10:48:33.772  7716  8047 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 10:48:33.773  7716  7716 V BtOppService: start RfcommListener
08-25 10:48:33.777  7716  8047 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38629962 on behalf of 
08-25 10:48:33.778  7716  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 10:48:33.781  7716  8047 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 10:48:33.781  7716  7716 V BtOppService: RfcommListener started
08-25 10:48:33.781  7716  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10835af3 on behalf of 
,08-25 10:48:33.783  7716  8049 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 10:48:33.783  1031  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:33.785  7716  8049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:33.786  7716  8049 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-25 10:48:33.787  7716  8049 V BtOppRfcommListener: Started RFCOMM listener....
08-25 10:48:33.787  7716  8049 I BtOppRfcommListener: Accept thread started.
08-25 10:48:33.787  7716  8049 V BtOppRfcommListener: Accepting connection...
08-25 10:48:33.787  7716  8048 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 10:48:33.788  7716  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 10:48:33.790  7716  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1895f3b0 on behalf of 
08-25 10:48:33.790  7716  8048 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 10:48:33.791  7716  8048 V BluetoothOppNotification: outbound notification was removed.
08-25 10:48:33.792  7716  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 10:48:33.793  7716  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12389229 on behalf of 
08-25 10:48:33.793  7716  8048 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 10:48:33.796  7716  8048 V BluetoothOppNotification: inbound notification was removed.
08-25 10:48:33.796  7716  8048 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 10:48:33.797  7716  8048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3354e9ae on behalf of 
08-25 10:48:33.797  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:33.798  7716  7716 V BluetoothFtpService: Ftp Service onCreate
08-25 10:48:33.798  7716  7716 I BluetoothFtpService: Ftp Service onCreate
08-25 10:48:33.798  7716  7716 V BluetoothFtpService: Ftp Service onStartCommand
08-25 10:48:33.798  7716  7716 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:48:33.798  7716  7716 V BluetoothFtpService: Starting Listening on sockets
08-25 10:48:33.798  7716  7716 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 10:48:33.799  7716  7716 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 10:48:33.799  7716  7716 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 10:48:33.799  7716  7716 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:33.799  7716  7716 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 10:48:33.799  7716  7716 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 10:48:33.801  7716  7716 V BluetoothFtpService: Handler(): got msg=1
08-25 10:48:33.801  7716  7716 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 10:48:33.801  7716  7716 V BluetoothFtpService: Ftp Service initSocket
08-25 10:48:33.808  1031  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:33.809  7716  7716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:48:33.811  7716  7716 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-25 10:48:33.812  7716  7716 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 10:48:33.813  7716  8050 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 10:48:33.827  7716  7716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22465ab
08-25 10:48:33.827  7716  7716 V BluetoothSapService: Sap Service onCreate
,08-25 10:48:33.829  7716  7716 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:48:33.829  7716  7716 V BluetoothSapService: state: 12
08-25 10:48:33.829  7716  7716 V BluetoothSapService: Starting SAP server process
08-25 10:48:33.832  7716  7716 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 10:48:33.820  8051  8051 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 10:48:33.820  8051  8051 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:33.834  7716  8052 V BluetoothSapService: Sap Service initRfcommSocket
08-25 10:48:33.834  1031  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:33.835  7716  8052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:48:33.836  7716  8052 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 10:48:33.836  7716  8052 V BluetoothSapService: Succeed to create listening socket 
08-25 10:48:33.836  7716  8052 V BluetoothSapService: Accepting socket connection...
08-25 10:48:33.843  8051  8051 V BT_SAP  : Event pipe created
,08-25 10:48:33.844  8051  8051 V BT_SAP  : create_server_socket qcom.sap.server
08-25 10:48:33.844  8051  8051 V BT_SAP  : created socket fd 6
,08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:34.174  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:48:34.198  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:34.200  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:34.200  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e74027c added. We now have 8 listener(s)
08-25 10:48:34.200  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:34.202  1031  2052 D WifiServiceImplEx: setWifiEnabled: false pid=6778, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 10:48:34.203  1031  2052 D WifiService: setWifiEnabled: false pid=6778, uid=10118
08-25 10:48:34.203  1031  2052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:48:34.210  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:34.211  1031  1995 D WifiServiceImplEx: setWifiEnabled: true pid=6778, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 10:48:34.212  1031  1995 D WifiService: setWifiEnabled: true pid=6778, uid=10118
08-25 10:48:34.212  1031  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 10:48:34.226  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 10:48:34.226  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 10:48:34.226  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-25 10:48:34.228  1031  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 10:48:34.228  1031  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 10:48:34.230  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 10:48:34.230  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 10:48:34.230  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 10:48:34.230  1031  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 10:48:34.231  1031  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 10:48:34.231  1031  1539 E WifiHW  : unknown target_country: EU , set to default
08-25 10:48:34.231  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 10:48:34.231  1031  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 10:48:34.231  1031  1539 I WifiUtil: gEnableBmps=1
08-25 10:48:34.780   304   894 D SoftapController: Softap fwReload - Ok
,08-25 10:48:34.810  7716  7716 V BluetoothOppNotification: new notify threadi!
08-25 10:48:34.811  7716  7716 V BluetoothOppNotification: send delay message
,08-25 10:48:34.814  1031  1539 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (579ms)
08-25 10:48:34.816  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 10:48:34.818  1031  1095 D Tethering: InitialState.processMessage what=4
08-25 10:48:34.820   304   894 D CommandListener: Setting iface cfg
08-25 10:48:34.820   304   894 D CommandListener: Trying to bring down wlan0
08-25 10:48:34.821   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:48:34.824  1031  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 10:48:34.828  1031  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 10:48:34.820  8084  8084 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:34.820  8084  8084 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:34.857  8084  8084 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 10:48:34.858  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 10:48:34.859  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 10:48:34.859  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 10:48:34.859  6885  6885 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 10:48:34.859  7716  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 10:48:34.861  7716  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b0d356b on behalf of 
08-25 10:48:34.861  7716  8080 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 10:48:34.863  7716  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-25 10:48:34.863  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 10:48:34.866  7716  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6a888c8 on behalf of 
08-25 10:48:34.867  6885  6885 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 10:48:34.868  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 10:48:34.868  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 10:48:34.868  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 10:48:34.868  6885  6885 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 10:48:34.868  6885  6885 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 10:48:34.873  7716  8080 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 10:48:34.873  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 10:48:34.873  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 10:48:34.873  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 10:48:34.873  6885  6885 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 10:48:34.874  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 10:48:34.875  6885  6885 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 10:48:34.875  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 10:48:34.875  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 10:48:34.875  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 10:48:34.875  6885  6885 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-25 10:48:34.875  6885  6885 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 10:48:34.881  7716  8080 V BluetoothOppNotification: outbound notification was removed.
08-25 10:48:34.881  7716  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 10:48:34.882  7716  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21f5d61 on behalf of 
08-25 10:48:34.883  7716  8080 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 10:48:34.884  7716  8080 V BluetoothOppNotification: inbound notification was removed.
08-25 10:48:34.884  7716  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 10:48:34.885  7716  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fd48086 on behalf of 
08-25 10:48:34.890  8084  8084 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 10:48:34.891  8084  8084 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 10:48:34.929  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:34.929  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:34.929  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 10:48:34.930  1031  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 10:48:34.931  1031  1539 D WifiMonitor: connecting to supplicant
,08-25 10:48:34.938  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:34.940  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:34.941  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 10:48:34.953  8084  8084 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 10:48:34.998  1031  1091 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8092 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 10:48:35.000  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 10:48:35.009  8084  8084 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-25 10:48:35.013  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-25 10:48:35.015  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 10:48:35.016  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 10:48:35.016  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 10:48:35.016  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 10:48:35.016  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 10:48:35.016  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 10:48:35.017  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 10:48:35.018  1031  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 10:48:35.019  1031  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.020  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.021  1031  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 10:48:35.021  1031  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 10:48:35.021  1031  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 10:48:35.022  1031  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 10:48:35.022  1031  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 10:48:35.023  1031  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 10:48:35.023  1031  1539 E WifiStateMachine: useWiFiOffloading() : false
08-25 10:48:35.023  1031  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 10:48:35.023  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.023  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.024  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.024  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.024  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 10:48:35.024  1031  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 10:48:35.025  1031  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-25 10:48:35.026  1031  1539 D WifiConfigStore: Loading config and enabling all networks 
08-25 10:48:35.026  1031  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 10:48:35.026  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.026  1031  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 10:48:35.026  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 10:48:35.026  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-25 10:48:35.026  1031  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:35.030  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:48:35.031  1031  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 10:48:35.032  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:35.040  1031  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-25 10:48:35.040  1031  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 10:48:35.041  1031  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-25 10:48:35.041  1031  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 10:48:35.042  1031  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 10:48:35.042  1031  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 10:48:35.042  1031  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 10:48:35.042  1031  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 10:48:35.042  1031  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 10:48:35.042  1031  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 10:48:35.043  1031  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 10:48:35.043  1031  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 10:48:35.043  1031  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 10:48:35.043  1031  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 10:48:35.043  1031  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 10:48:35.043  1031  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 10:48:35.044  1031  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 10:48:35.044  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 10:48:35.044  1031  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 10:48:35.044  1031  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 10:48:35.044  1031  1539 D WifiNative-HAL: Setting external_sim to 1
08-25 10:48:35.044  1031  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 10:48:35.045  1031  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 10:48:35.045  1031  1539 I WifiNative-HAL: startHal
08-25 10:48:35.045  1031  1539 D wifi    : setting scan oui 0xaf6d1040
08-25 10:48:35.045  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-25 10:48:35.045  1031  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 10:48:35.045  1031  1539 I WifiNative-HAL: startHal
08-25 10:48:35.045  1031  1539 D wifi    : setting scan oui 0xaf6d1040
08-25 10:48:35.045  1031  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 10:48:35.046  7744  7744 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.046  1031  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 10:48:35.046  1943  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 10:48:35.046  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 10:48:35.046  1943  2307 D WfdsService: Set the WFDS Monitor: true
08-25 10:48:35.046  1943  2307 D WfdsMonitor: WfdsMonitorThread create
08-25 10:48:35.047  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 10:48:35.047  1943  2307 D WfdsMonitor: WFDS Monitor is created and started
08-25 10:48:35.047  1943  2307 D WfdsService: WiFi: Supplicant connection re-established
08-25 10:48:35.047  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 10:48:35.047  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 10:48:35.047  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 10:48:35.047  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 10:48:35.047  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 10:48:35.047  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 10:48:35.048  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMO,VE 3: returned true
08-25 10:48:35.048  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 10:48:35.048  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 10:48:35.048  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 10:48:35.048  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 10:48:35.048  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 10:48:35.048  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 10:48:35.048  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 10:48:35.048  8084  8084 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 10:48:35.049  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 10:48:35.049  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 10:48:35.049  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 10:48:35.049  1031  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 10:48:35.050  1031  1539 E WifiNative: : [229,919,824 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 10:48:35.050  1031  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 10:48:35.050  1031  1539 D WifiNative-wlan0: RECONNECT: returned true
08-25 10:48:35.050  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-25 10:48:35.050  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 10:48:35.050  1031  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 10:48:35.050  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 10:48:35.050  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:35.051  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
08-25 10:48:35.051  1031  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.051  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 10:48:35.052  1031  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 10:48:35.052  1943  8110 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 10:48:35.052  1031  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 10:48:35.052  1031  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 10:48:35.052  1943  8110 E CtrlSupplicant: Succeed to open control connection
08-25 10:48:35.052  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 10:48:35.052  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-25 10:48:35.052  1031  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.052  1031  1556 I WifiNative-HAL: startHal
08-25 10:48:35.052  1031  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6d1040
08-25 10:48:35.052  1031  1556 D wifi    : failed to get capabilities : -3
08-25 10:48:35.052  1031  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 10:48:35.052  1031  1556 E WifiScanningService: could not get scan capabilities
08-25 10:48:35.052  1031  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.052  1031  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 10:48:35.053  1943  8110 E CtrlSupplicant: Succeed to open monitor connection
08-25 10:48:35.053  1943  8110 D WfdsMonitor: Supplicant connection established
,08-25 10:48:35.053  1943  2307 D WfdsService: Connected to the supplicant for wfds
08-25 10:48:35.053  1031  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 10:48:35.053  1031  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 10:48:35.053   304   894 D CommandListener: Setting iface cfg
08-25 10:48:35.053  8084  8084 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 10:48:35.053   304   894 D CommandListener: Trying to bring up p2p0
08-25 10:48:35.054  1031  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 10:48:35.054  1031  1537 D LGWifiP2pService: P2pEnablingState
,08-25 10:48:35.054  1031  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.054  1031  1537 D LGWifiP2pService: P2p socket connection successful
08-25 10:48:35.054  1031  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 10:48:35.054  1031  1537 D LGWifiP2pService: P2pEnabledState
08-25 10:48:35.054  1031  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 10:48:35.055  1031  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,08-25 10:48:35.055  1031  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 10:48:35.055  8084  8084 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 10:48:35.055  1031  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 10:48:35.055  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 10:48:35.056  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 10:48:35.056  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 10:48:35.056  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-25 10:48:35.057  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 10:48:35.057  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:35.058  8084  8084 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 10:48:35.058  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.058  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.059  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 10:48:35.059  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:35.059  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:35.060  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:35.060  1031  8108 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:35.060  1031  8108 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.060  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.060  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.060  1031  8108 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:35.060  1031  8108 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.060  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.060  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.061  1031  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 10:48:35.061  1031  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 10:48:35.062  1031  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 10:48:35.062  1031  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 10:48:35.062  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 10:48:35.062  1031  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-25 10:48:35.062  1031  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 10:48:35.062  1031  1537 D LGWifiP2pService: before postfix = G3
08-25 10:48:35.062  1943  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:35.062  1943  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:35.062  1943  1943 D WfdsService: WifiP2pState is changed : true
08-25 10:48:35.062  1031  1537 D WifiServerServiceExt: postfix byte check : 2
08-25 10:48:35.062  1031  1537 D LGWifiP2pService: after postfix = G3
08-25 10:48:35.062  1031  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 10:48:35.062  1943  2307 D WfdsService: Receive the WFDS_ENABLE Method
08-25 10:48:35.062  1943  2307 D WfdsService: Set the WFDS Monitor: true
08-25 10:48:35.062  1031  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 10:48:35.062  1943  2307 D WfdsService: Connected to the supplicant for wfds
08-25 10:48:35.062  1031  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 10:48:35.063  1031  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 10:48:35.063  1031  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 10:48:35.063  1943  2307 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 10:48:35.063  8084  8084 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 10:48:35.063  1943  2307 D WfdsService: selectPreferredScanChannel [36],
08-25 10:48:35.063  1943  2307 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 10:48:35.063  1031  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 10:48:35.063  1031  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 10:48:35.063  1031  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 10:48:35.063  1031  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 10:48:35.063  1031  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-25 10:48:35.064  1031  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 10:48:35.064  1031  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 10:48:35.064  1031  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 10:48:35.064  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 10:48:35.064  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 10:48:35.064  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:35.065  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 10:48:35.065  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:35.065  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:35.065  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 10:48:35.065  1031  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 10:48:35.065  1031  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 10:48:35.066  1031  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 10:48:35.066  1031  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 10:48:35.067  1031  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 10:48:35.067  1031  1539 D WifiNative-wlan0: doBoolean: SCAN
08-25 10:48:35.067  1031  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 10:48:35.067  1031  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 10:48:35.067  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 10:48:35.067  1031  1539 D WifiNative-wlan0: SCAN: returned false
08-25 10:48:35.068  1031  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 10:48:35.068  1031  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 10:48:35.068  1943  1943 D WfdsService: isConnected: false
08-25 10:48:35.068  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 10:48:35.068  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 10:48:35.068  1943  1943 D WfdsService: Update P2p Interface State: 3
08-25 10:48:35.068  1031  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 10:48:35.068  1031  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-25 10:48:35.069  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=229939  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 10:48:35.073  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:35.073  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.074  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.075  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.075  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.075  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 10:48:35.076  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=229946  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 10:48:35.076  1031  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:35.077  1031  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-25 10:48:35.077  1031  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 10:48:35.077  1031  1537 D LGWifiP2pService: InactiveState
08-25 10:48:35.077  1031  1537 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.078  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.078  1031  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 10:48:35.078  1031  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:35.078  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 10:48:35.078  1031  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 10:48:35.078  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 10:48:35.079  1031  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-25 10:48:35.079  8084  8084 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 10:48:35.079  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.079  1031  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-25 10:48:35.079  1031  8108 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 10:48:35.079  1031  8108 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:35.079  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 10:48:35.079  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 10:48:35.079  1031  8108 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:35.079  1031  8108 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 10:48:35.079  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.079  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 10:48:35.080  8084  8084 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.080  1943  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 10:48:35.080  1943  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-25 10:48:35.080  1943  8110 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:35.080  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-25 10:48:35.080  1031  8108 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 10:48:35.080  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 10:48:35.080  1031  8108 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 10:48:35.080  1031  8108 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.080  1031  8108 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 10:48:35.081  1031  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-25 10:48:35.081  1031  1537 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler },
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:35.081  1031  1537 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:35.081  1031  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:35.081  1031  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.081  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:48:35.081  1031  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.082  1031  1031 E WifiServerServiceExt: No p2p device connected
,08-25 10:48:35.082  1943  2307 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 10:48:35.149  1031  1942 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8115 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 10:48:35.159  8092  8113 W FormManager: Network not available. Please check & try again.
08-25 10:48:35.173  8092  8114 V FormManager: Network unavailable.
,08-25 10:48:35.177  8092  8114 V FormManager: Network unavailable.
,08-25 10:48:35.195  1031  1942 I ActivityManager: Killing 7202:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 10:48:35.224  8115  8115 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:48:35.244  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:48:35.247  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:48:35.250  1031  2034 W libprocessgroup: failed to open /acct/uid_10062/pid_7202/cgroup.procs: No such file or directory
08-25 10:48:35.252  1031  2034 I ActivityManager: Killing 7221:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-25 10:48:35.253  6778  6856 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 10:48:35.254  6778  6856 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 10:48:35.256  6778  6856 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3779f9e Bundle[{}]
08-25 10:48:35.257  6778  6856 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 10:48:35.257  6778  6856 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 10:48:35.258  6778  6856 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 10:48:35.260  6778  6856 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 10:48:35.261  6778  6856 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 10:48:35.262  6778  6856 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 10:48:35.270  6778  6856 I System.out: Running OutgoingSocketThread
,08-25 10:48:35.272  6778  8135 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 876)
08-25 10:48:35.273  6778  8135 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41785
08-25 10:48:35.273  6778  8135 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 10:48:35.303  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:48:35.305  1031  2012 W libprocessgroup: failed to open /acct/uid_10085/pid_7221/cgroup.procs: No such file or directory
08-25 10:48:35.311  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:35.343  8115  8115 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 10:48:35.348  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:48:35.363  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:35.375  8092  8137 W FormManager: Network not available. Please check & try again.
,08-25 10:48:35.386  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 10:48:35.386  4354  4354 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 10:48:35.389  8092  8138 V FormManager: Network unavailable.
08-25 10:48:35.390  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 10:48:35.394  8092  8138 V FormManager: Network unavailable.
,08-25 10:48:35.394  4354  4354 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 10:48:35.402  4354  8139 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 10:48:35.407  4354  8140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 10:48:35.407  4354  8140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 10:48:35.455  1031  1811 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 10:48:35.527  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 10:48:35.527  1031  8108 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 10:48:35.528  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 10:48:35.528  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-25 10:48:35.528  8084  8084 E wpa_supplicant: USIM:  scard_init function
08-25 10:48:35.528  1031  8108 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 10:48:35.528  8084  8084 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 10:48:35.528  1031  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 10:48:35.529  1031  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 10:48:35.529  1031  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 10:48:35.530  1031  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 10:48:35.530  1031  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 10:48:35.530  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 10:48:35.530  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-25 10:48:35.535  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=230405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 10:48:35.537  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:35.537  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.538  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.538  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.538  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.538  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 10:48:35.539  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=230410  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 10:48:35.541  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.541  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.541  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 10:48:35.542  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:35.542  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 10:48:35.559  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 10:48:35.559  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.560  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.575  8141  8141 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 10:48:35.575  8141  8141 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 10:48:35.583  8141  8141 V [BNRBootReceiver]: Boot Receiver Return
08-25 10:48:35.585  8141  8141 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 10:48:35.638  8084  8084 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 10:48:35.641  1031  1940 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8160 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 10:48:35.642  1031  1940 I ActivityManager: Killing 7259:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-25 10:48:35.647  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-25 10:48:35.647  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 10:48:35.647  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 10:48:35.647  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 10:48:35.647  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:35.647  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:35.653  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=230523  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 10:48:35.653  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=230523  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 10:48:35.654  1031  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=230524
08-25 10:48:35.655  1031  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=230525
08-25 10:48:35.655  1031  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=230525
08-25 10:48:35.656  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=230526
08-25 10:48:35.656  1031  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=230526
08-25 10:48:35.657  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=230527  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 10:48:35.658  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:35.658  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 10:48:35.658  8084  8084 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:48:35.658  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 10:48:35.658  8084  8084 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 10:48:35.658  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:48:35.658  1031  8108 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:48:35.659  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 10:48:35.659  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 10:48:35.659  1031  8108 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-25 10:48:35.661  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:35.661  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:35.859  1031  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 10:48:35.868  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=230737  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-25 10:48:35.881  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 10:48:35.881  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.885  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.885  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.885  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.885  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 10:48:35.891  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.891  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.891  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 10:48:35.893  1031  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=230762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 10:48:35.894  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=230764  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 10:48:35.894  1031  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=230764
08-25 10:48:35.894  1031  1590 W libprocessgroup: failed to open /acct/uid_10093/pid_7259/cgroup.procs: No such file or directory
08-25 10:48:35.895  1031  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=230765
08-25 10:48:35.895  1031  1539 D WifiNative-wlan0: doString: [STATUS]
08-25 10:48:35.896  1031  8108 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 10:48:35.897  1031  8108 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 10:48:35.897  1031  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-25 10:48:35.899  1031  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 10:48:35.902  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:35.903  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 10:48:35.909  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:35.909  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.909  1031  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 10:48:35.909  1031  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 10:48:35.911  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 10:48:35.914  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.914  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.914  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 10:48:35.918  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:48:35.919  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.919  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 10:48:35.925  1031  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 10:48:35.925  1031  1545 D ConnectivityService: Got NetworkAgent Messenger
08-25 10:48:35.925  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:48:35.925  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-25 10:48:35.925  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 10:48:35.925  1031  1545 D ConnectivityService: NetworkAgent connected
08-25 10:48:35.925  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 10:48:35.926  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 10:48:35.926  8160  8160 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 10:48:35.930  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 10:48:35.930  1031  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:48:35.930  1031  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 10:48:35.930  1031  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 10:48:35.930  1031  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 10:48:35.934  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:35.934  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.935  1031  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 10:48:35.936   304   894 D CommandListener: Setting iface cfg
08-25 10:48:35.936  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.938  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:35.938  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.939  1031  1539 E WifiStateMachine: Start Dhcp Watchdog 3
08-25 10:48:35.939  1031  8178 D DhcpStateMachine: StoppedState
08-25 10:48:35.939  1031  8178 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.939  1031  8178 D DhcpStateMachine: WaitBeforeStartState
,08-25 10:48:35.940  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=230810  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:35.941  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=230811  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:35.941  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=230811  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:35.941  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.942  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.942  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:35.942  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 10:48:35.942  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.943  1031  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.944  1031  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.944  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.945  1031  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 10:48:35.945  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:35.945  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 10:48:35.946  1031  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=230816  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:35.947  1031  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=230816  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:35.947  1031  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=230817  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 10:48:35.948  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13954] from screen [on:0 period:-1058866580] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 10:48:35.949  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058866579] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 10:48:35.949  1031  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 10:48:35.951  8160  8160 D PluginManager: init()
,08-25 10:48:35.954  1031  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-25 10:48:35.955  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.955  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.955  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.956  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.956  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.956  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:35.957  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.957  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 10:48:35.958  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=177,0,0
08-25 10:48:35.958  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=177,0,0
08-25 10:48:35.958  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 10:48:35.958  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 10:48:35.959  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 10:48:35.959  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 10:48:35.959  1031  1539 D WifiNative-wlan0: SET ps 0: returned true
08-25 10:48:35.959  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 10:48:35.959  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 10:48:35.960  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 10:48:35.960  1031  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2da0b19a target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.960  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2da0b19a target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.960  1031  8178 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.960  1031  8178 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 10:48:35.961  1031  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 10:48:35.961  1031  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 10:48:35.961  1031  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 10:48:35.962   304   894 D CommandListener: Setting iface cfg
08-25 10:48:35.962   304   894 D CommandListener: Trying to bring up wlan0
08-25 10:48:35.963  1031  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 10:48:35.964  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:35.964  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-25 10:48:35.965  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 10:48:35.966  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 10:48:35.967  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.967  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.968  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.968  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.968  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.969  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 10:48:35.969  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 10:48:35.970  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 10:48:35.970  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 10:48:35.971  1031  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.971  1031  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:35.971  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 10:48:35.971  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 10:48:35.971  1031  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 10:48:35.971  1031  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 10:48:35.972  8084  8084 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 10:48:35.972  1031  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 10:48:35.972  1031  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 10:48:35.988  1031  1539 D WifiNative-wlan0: SET ps 1: returned true
,08-25 10:48:35.989  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 10:48:35.990  1031  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 10:48:35.990  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 10:48:35.990  1031  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 10:48:35.991  1031  1545 D ConnectivityService: ignoring duplicate network state non-change
08-25 10:48:35.996  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:35.996  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:35.996  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.996  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:35.996  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 10:48:35.997  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:36.002  1031  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 10:48:36.003  1031  1545 D ConnectivityService: Adding iface wlan0 to network 102
08-25 10:48:36.003  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:36.003  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:36.004  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 10:48:36.006  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 10:48:36.010  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 10:48:36.012  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:36.012  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:36.012  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 10:48:36.013  1031  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 10:48:36.018  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 10:48:36.020  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:36.020  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 10:48:36.022  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:36.025  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:36.026  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:48:36.026  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 10:48:36.027  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:36.027  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 10:48:36.027  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 10:48:36.028  1031  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 10:48:36.028  1031  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 10:48:36.029  1031  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 10:48:36.030  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:48:36.030   304   894 E Netd    : netlink response contains error (File exists)
08-25 10:48:36.030  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 10:48:36.030  1031  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 10:48:36.030  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:36.031  1031  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 10:48:36.031  1031  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-25 10:48:36.031  1031  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-25 10:48:36.032  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 10:48:36.032  1031  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 10:48:36.032  1031  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 10:48:36.032  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 10:48:36.032  1031  8177 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:36.032  1031  8177 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 10:48:36.032  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:36.032  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:36.032  1031  8177 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:48:36.032  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 10:48:36.033  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.033  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 10:48:36.033  1031  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-25 10:48:36.033  1031  1545 D ConnectivityService:    accepting network in place of null
08-25 10:48:36.033  1031  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.033  1031  8177 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 10:48:36.033  1031  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.033  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:36.035  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, l,egacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.036   304  8182 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 10:48:36.036  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 10:48:36.037  1031  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 10:48:36.037  1031  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 10:48:36.037  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 10:48:36.038  1031  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 10:48:36.038  1031  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 10:48:36.039  1031  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-25 10:48:36.042  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 10:48:36.042  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 10:48:36.042  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 10:48:36.042  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 10:48:36.050  1031  1545 D ConnectivityService: validation of new default Network = false
08-25 10:48:36.050  1031  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 10:48:36.050  1031  1545 D DSQN    : enableDataServiceNotify 
08-25 10:48:36.050  1031  1545 D DSQN    : start dsqn bin
,08-25 10:48:36.054  1031  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 10:48:36.057  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 10:48:36.057  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.057  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:36.050  8184  8184 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:36.058  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:36.050  8184  8184 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:36.065  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 10:48:36.071  1817  8183 I CheckinService: active receiver: enabled
08-25 10:48:36.072  8184  8184 E DSQN    : DSQN ssw
08-25 10:48:36.076  1817  8183 I CheckinService: Preparing to send checkin request
08-25 10:48:36.076  1817  8183 I EventLogService: Accumulating logs since 1472114899310
,08-25 10:48:36.081  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 10:48:36.082  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:36.083  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:36.108  1817  8183 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-25 10:48:36.162  1031  8178 D DhcpStateMachine: DHCPV4 request on wlan0
,08-25 10:48:36.165  1031  8178 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 10:48:36.165  1031  8178 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 10:48:36.160  8189  8189 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 10:48:36.160  8189  8189 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 10:48:36.179  8189  8189 I dhcpcd  : version 5.5.6 starting
08-25 10:48:36.181  8189  8189 E dhcpcd  : get_duid: m
08-25 10:48:36.181  8189  8189 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 10:48:36.181  8189  8189 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-25 10:48:36.225  8189  8189 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 10:48:36.225  8189  8189 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-25 10:48:36.225  8189  8189 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-25 10:48:36.225  8189  8189 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-25 10:48:36.225  8189  8189 D dhcpcd  : wlan0: sending REQUEST (xid 0x210cf22e), next in 3.48 seconds
08-25 10:48:36.272  6778  6856 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 877)
,08-25 10:48:36.272  6778  6856 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 877)
,08-25 10:48:36.275  6778  6856 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 882)
,08-25 10:48:36.276  6778  6856 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 10:48:36.276  6778  6856 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 883)
08-25 10:48:36.279  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:48:36.280  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80f0705 added. We now have 2 listener(s)
08-25 10:48:36.280  1031  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 10:48:36.282  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.282  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.282  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-25 10:48:36.282  8189  8189 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 10:48:36.282  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:48:36.282  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3567b35a added. We now have 9 listener(s)
,08-25 10:48:36.282  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.282  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:48:36.284  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:36.288  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:36.291  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:48:36.291  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:36.291  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.291  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@103cca68 added. We now have 3 listener(s)
,08-25 10:48:36.291  1031  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.292  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.295  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.297  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.297  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.297  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.297  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.297  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fe0e81 added. We now have 10 listener(s)
,08-25 10:48:36.298  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-25 10:48:36.298  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:36.298  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:48:36.298  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:36.298  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.298  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.299  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:48:36.299  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.299  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80f0705 removed from the list
08-25 10:48:36.299  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:48:36.299  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3567b35a removed from the list
08-25 10:48:36.299  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:36.299  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.300  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 10:48:36.300  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.307  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.307  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.307  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 10:48:36.307  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3567b35a not in the list,
08-25 10:48:36.307  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.307  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.307  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.307  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:48:36.307  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.308  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23fe0e81 removed from the list
08-25 10:48:36.308  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.308  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.308  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:48:36.308  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.308  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@103cca68 removed from the list
08-25 10:48:36.308  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.308  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@345dab26 added. We now have 2 listener(s)
08-25 10:48:36.308  1031  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.310  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 10:48:36.310  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.310  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.310  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.310  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6ba367 added. We now have 9 listener(s)
08-25 10:48:36.310  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:48:36.310  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:48:36.312  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:36.314  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:36.315  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.315  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:36.315  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.315  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87c11bd added. We now have 3 listener(s)
08-25 10:48:36.315  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.315   304  8182 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 10:48:36.316  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.318  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.318  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.318  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.318  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.318  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6953b2 added. We now have 10 listener(s)
08-25 10:48:36.318  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.318  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.318  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:36.318  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:48:36.319  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:48:36.319  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:36.319  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:48:36.321  6778  6856 V org.,thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 10:48:36.321  1031  1590 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.324  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:48:36.324  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:48:36.325  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:48:36.325  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:36.326  6778  6856 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 10:48:36.327  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:36.327  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:36.328  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:36.328  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:36.328  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:36.328  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.328  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.328  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:36.328  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.328  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@345dab26 removed from the list
08-25 10:48:36.328  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.328  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6ba367 removed from the list
08-25 10:48:36.328  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:36.328  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.328  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.328  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.328  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.328  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.329  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.329  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b6ba367 not in the, list
08-25 10:48:36.329  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.329  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.329  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.329  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:36.329  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:36.329  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.329  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.329  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f6953b2 removed from the list
08-25 10:48:36.329  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.329  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.329  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.329  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.330  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87c11bd removed from the list
08-25 10:48:36.330  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.330  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13dd0cb9 added. We now have 2 listener(s)
08-25 10:48:36.330  1031  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.331  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.332  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.332  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.332  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.332  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f14f8fe added. We now have 9 listener(s)
08-25 10:48:36.332  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.332  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:48:36.333  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:36.335  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:36.337  8189  8189 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 10:48:36.337  8189  8189 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 10:48:36.338  8189  8189 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 10:48:36.338  8189  8189 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 10:48:36.338  8189  8189 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 10:48:36.339  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.339  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:36.339  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.339  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfb02ac added. We now have 3 listener(s)
08-25 10:48:36.339  8189  8189 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 10:48:36.339  1031  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.339  8189  8189 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 10:48:36.339  8189  8189 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 10:48:36.340  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.341  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.341  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.341  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.341  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.341  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.341  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb8bb75 added. We now have 10 listener(s)
08-25 10:48:36.341  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.341  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:36.341  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:36.342  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:48:36.342  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:48:36.342  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:36.342  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:48:36.346  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 10:48:36.346  1031  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.349  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:48:36.349  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:48:36.350  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:48:36.350  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:36.351  6778  6856 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 10:48:36.351  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:36.351  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:36.351  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:36.352  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.352  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.352  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:36.352  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.352  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13dd0cb9 removed from the list
08-25 10:48:36.352  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.352  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f14f8fe removed from the list
08-25 10:48:36.352  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:36.352  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.352  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.352  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.353  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.353  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.353  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.353  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f14f8fe not in the list
08-25 10:48:36.353  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.353  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.353   304  8182 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-25 10:48:36.354  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.354  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:36.354  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:36.354  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.354  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.354  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb8bb75 removed from the list
08-25 10:48:36.354  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.354  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.354  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.354  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.354  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfb02ac removed from the list
08-25 10:48:36.355  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.355  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@326b9d98 added. We now have 2 listener(s)
08-25 10:48:36.355  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.356  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.356  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.356  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.357  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.357  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d6699f1 added. We now have 9 listener(s)
08-25 10:48:36.357  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.359  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:48:36.361  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:36.364  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:48:36.367  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.367  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:36.367  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.367  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e3457 added. We now have 3 listener(s)
08-25 10:48:36.368  1031  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.370  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.371  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.373  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.373  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.373  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.373  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.373  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1448fb44 added. We now have 10 listener(s)
08-25 10:48:36.373  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.373  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:36.373  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:48:36.373  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:48:36.373  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:48:36.373  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:48:36.377  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 10:48:36.378  1031  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.382  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:48:36.383  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:48:36.384  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:48:36.385  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:36.386  6778  6856 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 10:48:36.388  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:36.388  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:36.388  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:36.388  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.388  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.388  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:36.388  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.388  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@326b9d98 removed from the list
08-25 10:48:36.388  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.388  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d6699f1 removed from the list
08-25 10:48:36.388  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:36.389  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.392  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.392  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.393  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.393  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.393  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.393  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d6699f1 not in the list
08-25 10:48:36.393  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.393  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.394  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.395  6778  6856 D BluetoothLeScanner: could not find callback wrapper
08-25 10:48:36.395  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:48:36.395  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.395  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.395  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1448fb44 removed from the list
08-25 10:48:36.395  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.395  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.395  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.395  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.395  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80e3457 removed from the list
08-25 10:48:36.396  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.396  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@757bef3 added. We now have 2 listener(s)
08-25 10:48:36.396  1031  1811 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.399  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.399  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.399  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.399  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.399  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f7c87b0 added. We now have 9 listener(s)
08-25 10:48:36.399  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.406  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:48:36.407   304   893 D LGDataListener: argv[0]=dsqncommand
08-25 10:48:36.407   304   893 D LGDataListener: argv[1]=wlan0
08-25 10:48:36.407   304   893 D LGDataListener: argv[2]=1
08-25 10:48:36.407   304   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 10:48:36.408  1031  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 10:48:36.408  1031  1093 D DSQN    : start to monitor internet connection
,08-25 10:48:36.412  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:48:36.415  6778  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:48:36.416  6778  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:48:36.416  6778  6856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:48:36.417  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:48:36.417  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ef9dae added. We now have 3 listener(s)
08-25 10:48:36.417  1031  1590 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 10:48:36.418  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:48:36.419  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:48:36.420  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 10:48:36.420  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:48:36.420  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:48:36.420  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:48:36.420  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ea5574f added. We now have 10 listener(s)
08-25 10:48:36.420  6778  6856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:48:36.420  6778  6856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:48:36.420  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:36.420  6778  6856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:48:36.421  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.421  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.421  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:48:36.421  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.421  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@757bef3 removed from the list
08-25 10:48:36.421  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.421  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f7c87b0 removed from the list
08-25 10:48:36.421  6778  6856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:48:36.421  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.421  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.421  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.422  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.422  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.422  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.422  6778  6856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f7c87b0 not in the list
08-25 10:48:36.422  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.423  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.423  6778  6856 I org.thaliproje,ct.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:48:36.423  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:48:36.423  6778  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:48:36.423  6778  6856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ea5574f removed from the list
08-25 10:48:36.423  6778  6856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:48:36.424  6778  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:48:36.424  6778  6856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:48:36.424  6778  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:48:36.424  6778  6856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ef9dae removed from the list
08-25 10:48:36.424  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 10:48:36.425  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 10:48:36.425  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 10:48:36.425  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:48:36.425  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 10:48:36.425  6778  6856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 10:48:36.435  6778  8212 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 890, name: My test thread name)
08-25 10:48:36.435  6778  8212 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 890, thread name: My test thread name)
08-25 10:48:36.435  6778  8212 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 890, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 10:48:36.444  1031  8177 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 08:48:36 GMT], X-Android-Received-Millis=[1472114916444], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472114916409]}
08-25 10:48:36.444  1031  8177 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 10:48:36.444  1031  8177 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 10:48:36.444  1031  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-25 10:48:36.444  1031  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 10:48:36.445  1031  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:36.445  1031  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:36.445  1031  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 10:48:36.445  1031  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-25 10:48:36.445  1031  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 10:48:36.445  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.445  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:36.445  1031  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:36.445  1031  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.445  1031  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 10:48:36.446  1031  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.446  1031  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:48:36.446  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 10:48:36.447  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:36.447  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 10:48:36.448  6778  8213 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 892, name: My test thread name)
08-25 10:48:36.448  6778  8213 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 892, thread name: My test thread name)
08-25 10:48:36.448  6778  8213 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 892, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 10:48:36.450  6778  6856 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 10:48:36.450  6778  6856 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 10:48:36.450  6778  6856 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 10:48:36.450  6778  6856 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 10:48:36.450  6778  6856 D com.test.thalitest.ThaliTestRunner: Total duration: 22725 ms
08-25 10:48:36.451  6778  6856 I jxcore-log: Total number of executed tests:  80
08-25 10:48:36.451  6778  6856 I jxcore-log: 
08-25 10:48:36.451  6778  6856 I jxcore-log: Number of passed tests:  80
08-25 10:48:36.451  6778  6856 I jxcore-log: 
08-25 10:48:36.451  6778  6856 I jxcore-log: Number of failed tests:  0
08-25 10:48:36.451  6778  6856 I jxcore-log: 
08-25 10:48:36.451  6778  6856 I jxcore-log: Number of ignored tests:  0
08-25 10:48:36.451  6778  6856 I jxcore-log: 
08-25 10:48:36.451  6778  6856 I jxcore-log: Total duration:  22725
08-25 10:48:36.451  6778  6856 I jxcore-log: 
08-25 10:48:36.452  6778  6856 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 10:48:36.452  6778  6856 I jxcore-log: 
08-25 10:48:36.455  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.455  6778  6856 I jxcore-log: 
08-25 10:48:36.457  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.457  6778  6856 I jxcore-log: 
08-25 10:48:36.458  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.458  6778  6856 I jxcore-log: 
08-25 10:48:36.458  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.458  6778  6856 I jxcore-log: 
08-25 10:48:36.459  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.459  6778  6856 I jxcore-log: 
08-25 10:48:36.460  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.460  6778  6856 I jxcore-log: 
08-25 10:48:36.462  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.462  6778  6856 I jxcore-log: 
08-25 10:48:36.463  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:48:36.463  6778  6856 I jxcore-log: 
08-25 10:48:36.464  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:48:36.464  6778  6856 I jxcore-log: 
08-25 10:48:36.464  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 10:48:36.464  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.464  6778  6856 I jxcore-log: 
08-25 10:48:36.464  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:36.465  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth",:"off","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.465  6778  6856 I jxcore-log: 
08-25 10:48:36.465  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 10:48:36.466  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:48:36.466  6778  6856 I jxcore-log: 
08-25 10:48:36.467  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:48:36.467  6778  6856 I jxcore-log: 
08-25 10:48:36.467  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:48:36.467  6778  6856 I jxcore-log: 
08-25 10:48:36.468  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.468  6778  6856 I jxcore-log: 
08-25 10:48:36.468  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.468  6778  6856 I jxcore-log: 
08-25 10:48:36.469  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.469  6778  6856 I jxcore-log: 
08-25 10:48:36.469  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.469  6778  6856 I jxcore-log: 
08-25 10:48:36.470  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.470  6778  6856 I jxcore-log: 
08-25 10:48:36.470  6778  6778 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 10:48:36.470  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.470  6778  6856 I jxcore-log: 
08-25 10:48:36.471  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.471  6778  6856 I jxcore-log: 
08-25 10:48:36.471  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:48:36.471  6778  6856 I jxcore-log: 
08-25 10:48:36.472  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:48:36.472  6778  6856 I jxcore-log: 
08-25 10:48:36.472  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:48:36.472  6778  6856 I jxcore-log: 
08-25 10:48:36.473  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.473  6778  6856 I jxcore-log: 
08-25 10:48:36.473  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.473  6778  6856 I jxcore-log: 
08-25 10:48:36.474  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.474  6778  6856 I jxcore-log: 
08-25 10:48:36.474  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.474  6778  6856 I jxcore-log: 
08-25 10:48:36.474  8160  8160 W ExternalStrings: load override strings
08-25 10:48:36.474  8160  8160 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 10:48:36.474  8160  8160 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 10:48:36.475  6778  6856 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:48:36.475  6778  6856 I jxcore-log: 
08-25 10:48:36.476  8160  8160 D StatusProvider: onCreate
,08-25 10:48:36.508  8160  8160 V Signer  : override build config not found
,08-25 10:48:36.508  8160  8160 D Signer  : value of property debug is false
08-25 10:48:36.530  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 10:48:36.531  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-25 10:48:36.531  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 10:48:36.531  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 10:48:36.531  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 10:48:36.531  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 10:48:36.531  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 10:48:36.531  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 10:48:36.532  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,08-25 10:48:36.532  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 10:48:36.532  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 10:48:36.532  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-25 10:48:36.532  8160  8160 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-25 10:48:36.539  8160  8160 V LGMDMManager: Create singleton instance
08-25 10:48:36.571  1031  8178 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-25 10:48:36.574  1031  8178 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 10:48:36.574  1031  8178 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 10:48:36.574  1031  8178 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 10:48:36.574  1031  8178 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-25 10:48:36.574  1031  8178 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-25 10:48:36.574  1031  8178 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 10:48:36.574  1031  8178 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 10:48:36.574  1031  8178 D DhcpStateMachine: RunningState
08-25 10:48:36.581  8160  8160 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-25 10:48:36.649  7304  7324 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:36.649  7304  7324 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:36.649  7304  7324 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:36.649  7304  7324 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:36.649  7304  7324 I Adreno-EGL: Remote Branch: 
08-25 10:48:36.649  7304  7324 I Adreno-EGL: Local Patches: 
08-25 10:48:36.649  7304  7324 I Adreno-EGL: Reconstruct Branch: 
08-25 10:48:36.667  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 10:48:36.669  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:36.678  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:36.683  8220  8220 D AndroidRuntime: 
08-25 10:48:36.683  8220  8220 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 10:48:36.685  8220  8220 D AndroidRuntime: CheckJNI is OFF
,08-25 10:48:36.691  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:36.710  7304  7324 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:36.710  7304  7324 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:36.710  7304  7324 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:36.710  7304  7324 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:36.710  7304  7324 I Adreno-EGL: Remote Branch: 
08-25 10:48:36.710  7304  7324 I Adreno-EGL: Local Patches: 
08-25 10:48:36.710  7304  7324 I Adreno-EGL: Reconstruct Branch: 
,08-25 10:48:36.736  1031  1811 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8237 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 10:48:36.790  8237  8237 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 10:48:36.791  8220  8220 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-25 10:48:36.808  1031  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 10:48:36.808  1031  1091 I ActivityManager: Killing 6778:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-25 10:48:36.832  8160  8223 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-25 10:48:36.849  1031  1995 I WindowState: WIN DEATH: Window{37dcca94 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 10:48:36.849  1031  1544 D WifiService: Client connection lost with reason: 4
08-25 10:48:36.855  1031  1995 D InputDispatcher: Window went away: Window{37dcca94 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 10:48:36.884  7304  7324 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 10:48:36.884  7304  7324 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 10:48:36.884  7304  7324 I Adreno-EGL: Build Date: 12/12/14 금
08-25 10:48:36.884  7304  7324 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 10:48:36.884  7304  7324 I Adreno-EGL: Remote Branch: 
08-25 10:48:36.884  7304  7324 I Adreno-EGL: Local Patches: 
08-25 10:48:36.884  7304  7324 I Adreno-EGL: Reconstruct Branch: 
,08-25 10:48:37.026  1031  1091 I ActivityManager:   Force finishing activity ActivityRecord{8315d59 u0 com.test.thalitest/.MainActivity t6}
,08-25 10:48:37.077   328   356 E GBMv2   : DFP En is all cleared set to be enabled
,08-25 10:48:37.081  1031  1904 W ActivityManager: Spurious death for ProcessRecord{37b104fa 6778:com.test.thalitest/u0a118}, curProc for 6778: null
08-25 10:48:37.083  8237  8237 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 10:48:37.085  1031  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 10:48:37.088  1031  1105 I ActivityManager:   Force finishing activity ActivityRecord{8315d59 u0 com.test.thalitest/.MainActivity t6 f}
08-25 10:48:37.088  1031  1105 W ActivityManager: Duplicate finish request for ActivityRecord{8315d59 u0 com.test.thalitest/.MainActivity t6 f}
,08-25 10:48:37.106  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 10:48:37.107  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 10:48:37.107  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4ea973b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 10:48:37.108  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-25 10:48:37.109  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-25 10:48:37.112  2035  2129 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-25 10:48:37.113  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 10:48:37.114  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4988e58 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 10:48:37.135  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-25 10:48:37.135  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-25 10:48:37.137  3839  4531 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 10:48:37.147  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-25 10:48:37.152  2501  2681 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 10:48:37.155  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 10:48:37.156  3839  3839 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 10:48:37.160  7716  7716 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 10:48:37.160  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 10:48:37.170  1031  1453 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 10:48:37.187  4648  4648 I art     : Explicit concurrent mark sweep GC freed 8229(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 864us total 88.974ms
08-25 10:48:37.190  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-25 10:48:37.223  4541  4541 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 10:48:37.224  4541  4541 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 10:48:37.224  4541  4541 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,08-25 10:48:37.225  1031  1031 D administrator: Handling package changes for user 0
08-25 10:48:37.228  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 10:48:37.230  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-25 10:48:37.231  4541  4541 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 10:48:37.231  4541  4541 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 10:48:37.231  4541  4541 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 10:48:37.231  4541  4541 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 10:48:37.233  4541  4541 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 10:48:37.233  4541  4541 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:48:37.233  4541  4541 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:48:37.233  4541  4541 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 10:48:37.233  4541  4541 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 10:48:37.240  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-25 10:48:37.244  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-25 10:48:37.245  3839  4531 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 10:48:37.245  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 10:48:37.247  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 10:48:37.247  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.248  3839  3858 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 10:48:37.249  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 10:48:37.249  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.250  8237  8237 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 10:48:37.250  8237  8237 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 10:48:37.251  8237  8237 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 10:48:37.251  8237  8237 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 10:48:37.251  8237  8237 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , display: false
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , animation: false }
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , display: false
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , animation: false }
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , display: false
08-25 10:48:37.251  2035  2035 I GBoardWebViewUtils: , animation: false }
,08-25 10:48:37.253  8237  8237 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 10:48:37.257  2035  8269 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 10:48:37.267  1031  2033 V SIM_STK : Menu title from STK is T-Mobile
08-25 10:48:37.268  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-25 10:48:37.269  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:37.269  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-25 10:48:37.271  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 10:48:37.272  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-25 10:48:37.278  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 10:48:37.278  8237  8237 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 10:48:37.279  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 10:48:37.280  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-25 10:48:37.288  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-25 10:48:37.288  1870  1870 D SplitUIService: removed split : 
08-25 10:48:37.289  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-25 10:48:37.291   304  8275 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 10:48:37.291   304  8275 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-25 10:48:37.291  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 10:48:37.291  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.296  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 10:48:37.297  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 10:48:37.298  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 10:48:37.298  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-25 10:48:37.312  1031  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-25 10:48:37.317  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 10:48:37.317  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.318  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-25 10:48:37.318  1870  1870 I SplitUIService: split app #11
08-25 10:48:37.320  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:37.320  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 10:48:37.320  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 10:48:37.320  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 10:48:37.321  1031  2052 V SIM_STK : Menu title from STK is T-Mobile
08-25 10:48:37.321  1031  2052 V SIM_STK : Menu title from STK is T-Mobile
08-25 10:48:37.325   304  8275 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-25 10:48:37.331  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 10:48:37.331  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-25 10:48:37.334  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 10:48:37.334  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.338  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.348  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-25 10:48:37.348  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 10:48:37.354  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 10:48:37.354  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.355  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 10:48:37.355  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.356  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 10:48:37.356  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 10:48:37.357  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 10:48:37.357  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.358  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 10:48:37.358  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-25 10:48:37.359  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 10:48:37.359  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.360  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 10:48:37.360  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 10:48:37.375  1031  1922 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 10:48:37.375  7716  7716 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 10:48:37.376  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 10:48:37.376  1603  1656 D KeyguardModel: createShortcutInfo...
08-25 10:48:37.382  1031  1941 V SIM_STK : Menu title from STK is T-Mobile
,08-25 10:48:37.393  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.404  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 10:48:37.404  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 10:48:37.405  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 10:48:37.408  1031  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 10:48:37.409  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 10:48:37.411  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-25 10:48:37.411  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 10:48:37.412  8237  8237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:37.413  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 10:48:37.424  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 10:48:37.445  8237  8237 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 10:48:37.450  8237  8237 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-25 10:48:37.463  8160  8223 D LgDataFeature: LgDataFeature() Constructor: none
08-25 10:48:37.463  8160  8223 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 10:48:37.469  6885  6885 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 10:48:37.471  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.471  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 10:48:37.477  1817  8183 I CheckinTask: Sending checkin request (7989 bytes)
08-25 10:48:37.477  1031  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 10:48:37.478  1031  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:37.478  1031  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:37.479  1031  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:37.479  1031  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:37.479  1031  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 10:48:37.479  1031  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-25 10:48:37.479  1031  1545 D ConnectivityService: identical MTU - not setting
08-25 10:48:37.480  1031  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 10:48:37.480  1031  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 10:48:37.480  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:48:37.480  1031  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:37.480  1031  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 10:48:37.481  1603  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 10:48:37.482  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.486  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:37.487  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-25 10:48:37.490  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.492  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 10:48:37.493  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 10:48:37.494  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 10:48:37.495  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-25 10:48:37.497  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.498  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.499  8237  8237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 10:48:37.500  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.500  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 10:48:37.517  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.517  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 10:48:37.517  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.517  1031  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5b21982 u0 com.lge.launcher2/.Launcher t5} time:232400
,08-25 10:48:37.523  2035  2171 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 10:48:37.523  2035  2171 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-25 10:48:37.534  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:37.537  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.538  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.538  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-25 10:48:37.538  8237  8237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 10:48:37.539  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 10:48:37.539  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.542  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 10:48:37.542  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 10:48:37.542  6885  6885 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 10:48:37.542  6885  6885 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 10:48:37.547  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 10:48:37.559  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 10:48:37.559  2575  2575 D [Concierge]Service: onStartCommand(). Type : 8
08-25 10:48:37.560  2575  2575 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-25 10:48:37.561  2575  2575 D [Concierge]Service: Update widget ID : 11
08-25 10:48:37.562  2035  2035 D [Concierge]WidgetView: change position of spinner
08-25 10:48:37.565  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1472114917564
08-25 10:48:37.565  2575  2575 D [Concierge]Service: onStartCommand(). Type : 0
08-25 10:48:37.569  6885  6885 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 10:48:37.569  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 10:48:37.569  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 10:48:37.569  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 10:48:37.569  6885  6885 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 10:48:37.570  6885  6885 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 10:48:37.570  6885  6885 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 10:48:37.577  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.577  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 10:48:37.582  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.583  8160  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-25 10:48:37.586  1031  1105 I art     : Explicit concurrent mark sweep GC freed 83800(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 15.763ms total 474.407ms
08-25 10:48:37.587  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:37.595  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 868655667
08-25 10:48:37.595  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-25 10:48:37.595  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-25 10:48:37.598  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@da9fb04
08-25 10:48:37.598  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-25 10:48:37.600  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 10:48:37.600  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.601  8160  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-25 10:48:37.606  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 10:48:37.607  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
,08-25 10:48:37.607  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 10:48:37.608  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472114711957, New one : 1472114917564
08-25 10:48:37.608  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-25 10:48:37.608  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.608  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-25 10:48:37.608  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.608  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.608  8237  8237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 10:48:37.610  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.611  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 10:48:37.612  8220  8220 D AndroidRuntime: Shutting down VM
08-25 10:48:37.612  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 10:48:37.613  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 10:48:37.614  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-25 10:48:37.615  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 10:48:37.616  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 10:48:37.617  8160  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-25 10:48:37.617  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.618  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.620  8160  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-25 10:48:37.623  8160  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 10:48:37.624  8160  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-25 10:48:37.624  8160  8223 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-25 10:48:37.624  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.627  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:37.630  8160  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-25 10:48:37.631  8160  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-25 10:48:37.648  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 10:48:37.655  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 10:48:37.655  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-25 10:48:37.657  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 10:48:37.664  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.665  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.665  8237  8237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 10:48:37.667  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.667  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 10:48:37.681  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@96c730c time:232564
,08-25 10:48:37.687  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.691  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:37.694  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.694  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.694  8237  8237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 10:48:37.696  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.697  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 10:48:37.701  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.705  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:37.712  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.712  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.713  8237  8237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:37.718  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.718  8160  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 10:48:37.729  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:37.739  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:37.742  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.743  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.746  8237  8237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 10:48:37.750  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 10:48:37.755  1031  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:48:37.760  1031  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-25 10:48:37.765  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-25 10:48:37.767  1817  8183 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-25 10:48:37.770  1817  8183 I CheckinService: active receiver: disabled
,08-25 10:48:37.786  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 10:48:37.790  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:37.794  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.794  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.795  8237  8237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 10:48:37.797  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.799  8115  8115 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 10:48:37.801  8115  8115 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:37.803  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.807  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 10:48:37.812  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.812  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.813  8237  8237 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 10:48:37.813  8237  8237 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 10:48:37.814  8237  8237 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 10:48:37.816  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.820  8115  8115 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 10:48:37.821  8115  8115 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 10:48:37.824  6885  6885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 10:48:37.828  6885  6885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 10:48:37.834  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-25 10:48:37.871  2035  2880 I GBoardtInterface: onReloaded()
,08-25 10:48:37.871  1031  1105 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8289 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 10:48:37.874  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-25 10:48:37.875  3839  3858 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 10:48:37.883  8237  8237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 10:48:37.883  3839  3857 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 10:48:37.883  8237  8237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 10:48:37.884  8237  8237 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 10:48:37.884  8237  8237 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 10:48:37.884  8237  8237 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-25 10:48:37.897  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 10:48:37.899  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-25 10:48:37.899  8160  8160 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-25 10:48:37.901  3839  4531 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 10:48:37.901  3839  4531 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 10:48:37.903  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-25 10:48:37.904  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-25 10:48:37.905  3839  4531 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 10:48:37.905  3839  4531 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 10:48:37.905  3839  4531 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-25 10:48:37.905  3839  4531 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-25 10:48:37.906  3839  3858 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 10:48:37.910  2191  2191 I ConfigService: onCreate
08-25 10:48:37.910  2191  2191 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 10:48:37.912  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-25 10:48:37.915  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,08-25 10:48:37.915  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-25 10:48:37.917  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-25 10:48:37.917  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 10:48:37.920  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-25 10:48:37.920  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 10:48:37.920  2191  2191 I ConfigService: onBind returning update interface
08-25 10:48:37.920  2191  2191 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 10:48:37.920  2191  2191 I ConfigService: onBind returning config service
08-25 10:48:37.932  2191  2191 I ConfigService: onDestroy
,08-25 10:48:37.935  1817  8308 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 10:48:37.967  5964  8315 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-25 10:48:37.970  1817  8316 I PeopleContactsSync: CP2 sync disabled
,08-25 10:48:37.983  1817  4835 I Icing   : doRemovePackageData com.test.thalitest
08-25 10:48:38.001  2191  2218 I art     : Explicit concurrent mark sweep GC freed 8188(472KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 626us total 21.033ms
,08-25 10:48:38.009  1817  8314 W GmsApplication: Using Auth Proxy for data requests.
08-25 10:48:38.013  1817  8314 W GmsApplication: Using Auth Proxy for data requests.
08-25 10:48:38.083  7093  7093 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest

```
